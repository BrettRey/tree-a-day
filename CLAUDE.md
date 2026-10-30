# CLAUDE.md: tree-a-day

Brett's tree-a-day account on X, revived 2026-10-30: one CGEL-style syntax tree per post, of a sentence that's topical or interesting to X readers. Claude drafts; Brett reviews every tree and posts it himself.

## Workflow

1. **Pick a sentence.** It should be topical (news, calendar, what's being argued about this week) or catch an X reader's eye (famous lines, ambiguities found in the wild, usage fights the tree settles). No textbook chestnuts: nothing every linguist has already seen, such as *The horse raced past the barn fell*, *Colorless green ideas sleep furiously* or the Buffalo sentence (Brett, 2026-10-30). Every sentence is attested: quote it from the source, never from memory, and record the source in the post.
2. **Draft the tree** as CGELBank `.cgel` source in `queue/<YYYY-MM-DD>-<slug>/tree.cgel`. Follow CGELBank conventions; check `all.trees` gold (nert-nlp/cgel) for a matching construction before inventing one, and flag anything without a gold precedent.
3. **Render**: `bin/render queue/<post>/tree.cgel` validates, then writes `tree.png`. Aim for 0 validator warnings: `# text =` carries punctuation, `# sent =` doesn't, verbs carry `:xpos`. For a contrast, `bin/pair left.cgel right.cgel <out-stem>` sets two trees side by side with their leaf rows aligned; a constructed member of a pair is labelled as constructed in its `# source`.
4. **Write `post.md`**: source, draft caption, alt text (the bracketed tree), and any rulings Brett needs to make.
5. **Brett reviews.** Nothing is posted until he signs off. Corrections go into the `.cgel` source and get re-rendered; log the error type in `corrections.md` (model errors in CGEL annotation are data for the CGELBank benchmark work).

## Conventions

- Rendering is CGELBank `tree2tex` output with italic, unhighlighted leaves aligned on the bottom row, and vertical long branches in fusion (`vendor/cgel/`, see `NOTICE.md`). Don't change the style without asking.
- Captions aren't didactic. The default is "Syntax tree for “…”", with at most a short second line for context (a source credit, a question for a pair); the explanation belongs in `post.md` for Brett, not in the post (Brett, 2026-10-30). Writing-style rules still apply: no em-dashes.
- One deliberate departure from gold: terminals keep the source's capitalization (*Something*, not gold's lowercased sentence-initial *something*), because the tree is an image of the quoted text.
- Category and function stay distinct (Det is the function, D the category).
- Model-drafted trees often differ from CGELBank gold. Assume the draft has errors.
