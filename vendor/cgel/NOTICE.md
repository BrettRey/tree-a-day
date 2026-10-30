# Vendored CGELBank code

`cgel.py`, `tree2tex.py` and `validate_trees.py` are copied from CGELBank,
<https://github.com/nert-nlp/cgel>, commit `d0a2c2d8c522b23d5aa879fc9cb94948f4285b2c`
(2026-01-17), licensed CC BY 4.0 (`LICENSE-CC-BY`). Authors: Brett Reynolds,
Nathan Schneider, Aryaman Arora and contributors.

Local changes, 2026-10-30, all in `cgel.py`:

- `Tree.drawtex`: terminal nodes are set in italics with no fill (upstream: sans serif
  on a yellow fill), and all terminals share the bottom tier (`tier=word`, which
  upstream has commented out).
- `Tree.drawtex_rec`: in fusion, the long branch is vertical. The fused node and each
  intermediate node above it carry `calign with current`, so packing puts the distant
  ancestor directly above the fused node; intermediate nodes are anchored `base west`
  to the right of that branch (upstream: intermediate node shifted right with
  `before drawing tree={x+=...}` after packing, long branch diagonal). Helpers
  `_is_fused`, `_fusion_skipped_levels` and `_fusion_intermediates` factor out logic
  that upstream had inline.
