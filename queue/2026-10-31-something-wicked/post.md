# Something wicked this way comes
<!-- SUMMARY: Halloween post as an X poll, CGEL fused head (A) vs ordinary Head (B), trees drafted by Claude · status: posted 2026-10-30 · updated: 2026-10-30 -->

**Posted:** 2026-10-30, a day early, as the poll below (Brett: "posted"). The "this way" analysis went out as drafted; Brett didn't rule on it separately.
**Format:** an X poll with a tree on each option (Brett, 2026-10-30). The single-tree and side-by-side versions are kept below as fallbacks.

## Source

William Shakespeare, *Macbeth*, Act 4, Scene 1, Second Witch:

> By the pricking of my thumbs,
> Something wicked this way comes.

Text checked against Project Gutenberg eBook #1533 (updated 2025-09-19), lines 2609–2610 of the plain-text file.

## Poll (draft)

**Post:**

> "Something wicked this way comes" (Macbeth 4.1)
>
> Is "Something" both the determiner and the head of its noun phrase (A), or just the head (B)?

**Options:**

| Option | Text | Image |
|---|---|---|
| A | A: determiner and head | `option-a.png` (CGEL's fused Det-Head, from `tree.cgel`) |
| B | B: just the head | `option-b.png` (ordinary Head, from `ordinary.cgel`) |
| C | Something else | `option-c.png` (a question mark in the trees' Times, same square) |

**Reply with the link** (posting it after the poll closes keeps the argument from steering the vote):

> I come down on B, though the comparison is close: "Fusion of functions revisited", https://lingbuzz.net/lingbuzz/010465

The B tree follows *Fusion of functions revisited*, Figure 1c and section 3: "the compound's DP heads the nominal and the restrictor follows it in the nominal." The validator flags it once (a DP as plain head of a Nom), because it checks CGEL's grammar.

**Images:** both 1016 × 1016, white-padded to square because X publishes no size or crop spec for option images. The trees differ only in the subject NP. To rebuild after a correction, re-render with `bin/render` and pad again: `sips --padToHeightWidth <h> <h> --padColor FFFFFF option-a.png`, where `<h>` is the taller of the two trees.

**Alt text** (if X offers it on option images):

- A: Syntax tree in the style of the Cambridge Grammar of the English Language, with "Something" in fused determiner-head function. [Clause [Subj: NP [Head: Nom [Det-Head: DP [Head: D Something]] [Mod: AdjP [Head: Adj wicked]]]] [Head: VP [Comp: NP [Det: DP [Head: D this]] [Head: Nom [Head: N way]]] [Head: V comes]]]; the DP also has a line up to the NP.
- B: Syntax tree in the style of the Cambridge Grammar of the English Language, with "Something" as head only. [Clause [Subj: NP [Head: Nom [Head: DP [Head: D Something]] [Mod: AdjP [Head: Adj wicked]]]] [Head: VP [Comp: NP [Det: DP [Head: D this]] [Head: Nom [Head: N way]]] [Head: V comes]]]

**Check in the composer before posting** (none of this is documented, as of 2026-10-30):

- whether the tree labels are legible at option size. If they aren't, the fallback is subject-NP-only trees, or the pair image with the poll in a reply;
- the 25-character limit on option text, which comes from an ads-spec guide, not X's own help pages.

## Fallback: single tree

**Image:** `tree.png` (re-render with `bin/render queue/2026-10-31-something-wicked/tree.cgel`). Alt text as for option A.

> "Something wicked this way comes" (Macbeth 4.1)
>
> Adjectives usually sit between determiner and head: the wicked thing. In "something", determiner and head are one word, so there's nowhere in between for "wicked" to go, and it follows instead.

This caption gives CGEL's explanation: the adjective follows "because determiner and head are fused" (p. 423, as quoted in *Fusion of functions revisited*, section 3). That section argues against it: the restrictor also follows where nothing is fused (*a little something extra*), so "fusion isn't necessary for the position." Rewrite it before using this version.

## Fallback: side by side

**Image:** `pair.png` (re-render with `bin/pair queue/2026-10-31-something-wicked/tree.cgel queue/2026-10-31-something-wicked/ordinary.cgel queue/2026-10-31-something-wicked/pair`), with the poll in a reply.

**Alt text:** Two syntax trees of the same sentence in the style of the Cambridge Grammar of the English Language. Left, with fusion: as option A. Right, with an ordinary head: as option B.

## Rulings needed before posting

1. **"this way".** Drafted as Comp: NP inside the VP, before its head verb, with no gap. Alternatives: Mod rather than Comp; or a preposed element linked to a gap after *comes*. CGELBank's gold trees have no instance of a goal NP before its verb, so this one is unsourced. It's the same in both trees.
2. **Option wording.** "Determiner and head" and "just the head" describe the two analyses without naming CGEL or the paper. Naming them would tell voters which answer is yours.
