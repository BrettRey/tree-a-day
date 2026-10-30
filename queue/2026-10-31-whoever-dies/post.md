# Whoever dies with honor dies well
<!-- SUMMARY: Klingon proverb (paq'batlh) in English, fused relative; Brett's find; tree drafted by Claude · status: posted 2026-10-30 · updated: 2026-10-30 -->

**Posted:** 2026-10-30, as a quote-tweet of @likethemagician
**Image:** `tree.png` (re-render with `bin/render queue/2026-10-31-whoever-dies/tree.cgel`)

## Source

𓄣 d🫀ug henning 𒊮 (@likethemagician) on X, as pasted by Brett on 2026-10-30 (date of the post not in the paste):

> {batlh Heghlu'chugh Heghlu'chu'}
> "Whoever dies with honor dies well."
>
> \- the final line of the {paq'batlh}

The tree is of the English.

## Caption (draft)

> "Whoever" does two jobs. It's the subject of "dies with honor", inside the relative clause, and it heads the noun phrase that's the subject of "dies well". Fused relatives are the one place I'd keep the two-function analysis.

The last sentence follows *Fusion of functions revisited* (lingbuzz/010465), abstract: fused relatives "relativize subjects ... There a second function is favoured, though not forced." It also picks up the Halloween poll, where the paper's answer was B.

## Alt text

> Syntax tree in the style of the Cambridge Grammar of the English Language. [Clause [Subj: NP [Head: Nom [Head-Prenucleus: NP Whoever] [Mod: Clause_rel [Head: Clause_rel [Subj: GAP] [Head: VP [Head: V dies] [Mod: PP [Head: P with] [Obj: NP [Head: Nom [Head: N honor]]]]]]]]] [Head: VP [Head: V dies] [Mod: AdvP [Head: Adv well]]]]; "Whoever" is also the prenucleus of the relative clause, linked to the subject gap.

## Analysis notes

- Fused relative as in gold: `Clause_rel` with `Head-Prenucleus: NP` (*what*, `ewt.cgel` line 3895) and a coindexed `Subj: GAP` (*who*, `ewt-test_iaa50.cgel` line 449). The paper's Figure (a) for *whatever he gave me* has the same shape. *Whoever* is N_pro, as gold's *what*. The validator reports no warnings.
- *with honor* and *well* are Mod in their VPs.

## Rulings needed before posting

1. Caption wording, especially the claim in the last sentence.
