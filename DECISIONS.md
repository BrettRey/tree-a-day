# Decisions
<!-- SUMMARY: tree-a-day decisions log · status: active · updated: 2026-10-30 -->

2026-10-30 — Revive the tree-a-day account with Claude drafting trees and Brett reviewing each one before he posts it. Reason: model-drafted trees often differ from CGELBank gold, so unreviewed trees would go out with errors under Brett's name. Brett approved the review-gated workflow ("yes, that looks good").

2026-10-30 — Rendering: CGELBank `tree2tex` output as in the demo, but with leaves "in italics and not highlighted" (Brett). Nom layer and bold head edges kept as in the demo he approved.

2026-10-30 — Fusion: "in fusion, I prefer the long branch to be vertical" (Brett). The ancestor (NP for Det-Head) sits directly above the fused node; intermediate Nom nodes are set to the right of that branch. Done at layout time so labels can't collide with neighbours, which a post-layout shift did on gold trees.

2026-10-30 — Selection: trees "should be topical and/or somehow inherently interesting to X readers" (Brett). Sentences are attested and sourced; none are made up.

2026-10-30 — Renderer vendored from nert-nlp/cgel commit d0a2c2d (CC BY 4.0) into `vendor/cgel/`, so the frozen benchmark checkout and its venv stay untouched.

2026-10-30 — Git repository is local only for now. The public-GitHub default is on hold until Brett confirms, since the queue holds unreviewed trees under his name.

2026-10-30 — Leaves: "lett's align the leaves at the bottom" (Brett). All terminals, gaps included, sit on one bottom row (forest `tier=word`, already present but commented out upstream).

2026-10-30 — Pair image for the Halloween post: CGEL fused Det-Head beside the ordinary Head analysis of papers/drafting/fusion-of-functions-revisited, at Brett's request ("under my treatment in the fusion paper. Don't separate Something"). Adjudication with that paper: adopted (Fig. 1c and section 3 give the right-hand tree). The draft caption repeats CGEL p. 423's fusion explanation of the postposed adjective, which that paper's section 3 argues against; flagged in post.md for Brett.

2026-10-30 — Halloween post format: X poll with a tree on each option (Brett: "make the poll version with images on each option"). X added images to poll options in February 2026 (Social Media Today, 3 Feb 2026); X publishes no size spec, so option images are padded to square. The LingBuzz link goes in a reply, timed so it does not steer the vote; X said on 29 July 2026 that links have not been demoted for over a year, so reach is no longer the reason.

2026-10-30 — Make it not so (Stewart tribute): "so" in predicative function is P, an intransitive preposition (Brett chose it over Adj, Adv and "?"). Brett: "pro-form is a semantic category, not a syntactic one", so CGEL p. 1538's "simply as a pro-form" is not a category; Adv is out because "adverbs cannot function as predicatives" (CGEL p. 529). Brett will quote-tweet @JenLRossman's "Make it not so".

2026-10-30 — Cadence: weekly batch. Brett: "OK, do the week" after the first post went up; Claude drafts a week of dated folders in queue/ and Brett reviews and posts. Topical posts (here the Stewart tribute) can go up the same day alongside.

2026-10-30 — Selection: no textbook chestnuts. Brett: "don't do obvious things like the horse raced past the barn fell." Dropped from the week: The horse raced past the barn fell, Colorless green ideas sleep furiously, and the Buffalo sentence; their slots (2, 4 and 6 Nov) get fresh sentences.

2026-10-30 — Repository made public on GitHub as BrettRey/tree-a-day (Brett: "make it public on GitHub"), superseding the local-only entry above. Before the first push, the unpublished CGELBank benchmark figures were generalized out of CLAUDE.md and DECISIONS.md and the single commit amended, so they never enter public history (Brett chose "Generalize, then push"). Unreviewed week drafts in queue/ are not committed.

2026-10-30 — Week rulings (Brett): 31 Oct Folio text of the Macbeth refrain; 1 Nov two coordinated clauses; 2 Nov the NYT "give A.I. access" ambiguity; 4 Nov a live "too early to call" headline, drafted on the day; 5 Nov Halliwell's "I know no reason"; 6 Nov the Schwab "FIND YOUR FILTHY COMFORTABLE" ad. The 19th Amendment (3 Nov) is dropped. Brett: "I'm not American, for one thing, and there's already the results one." One post on the US election is enough.

2026-10-30 — Fire burne (31 Oct): redrawn as vocatives plus imperatives, "probably imperative" with the subjunctive kept as the alternative, following an analysis Brett pasted (nearby "Boyle thou first", "Starres hide your fires" without a comma, bare singular Cauldron); its Folio citations checked in Gutenberg #1129.

2026-10-30 — 31 Oct becomes one four-image post from Macbeth 4.1 (Brett: "a bunch of trees from that bit at once, including the subjunctive"): Boyle thou first, Fire burne, Open Lockes who euer knockes, and Deny me this And an eternall Curse fall on you.

2026-10-30 — Index letters start at x in each tree and go on in order (x, y, z), as in gold; a tree with one link uses x (Brett asked why Boyle had y). Brett approved the four Macbeth trees as drawn ("otherwise good. And the other trees too"), which includes Lockes as vocative and ordinary Head for "this".

2026-10-30 — Captions: not didactic. Brett: "In General, I don't want to be didactic, and mostly I'll favour just \"Syntax tree for x\"". Default caption is "Syntax tree for “…”", with at most a short second line; the week's plain captions are in queue/CAPTIONS.md, and the explanatory drafts in each post.md are now notes for Brett, not post text.
