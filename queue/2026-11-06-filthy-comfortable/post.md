# Find your filthy comfortable
<!-- SUMMARY: Schwab ad, AdjP heading a noun phrase, CGEL Mod-Head vs ordinary Head pair; trees drafted by Claude · status: draft, awaiting Brett's review · updated: 2026-10-30 -->

**Slot:** Friday 6 November
**Image:** `pair.png` (re-render with `bin/pair queue/2026-11-06-filthy-comfortable/fused.cgel queue/2026-11-06-filthy-comfortable/ordinary.cgel queue/2026-11-06-filthy-comfortable/pair`)

## Source

Charles Schwab display ad, as captured in Mark Liberman, "'Filthy comfortable'", *Language Log*, 9 October 2026, https://languagelog.ldc.upenn.edu/nll/?p=74386. The ad image (https://languagelog.ldc.upenn.edu/myl/SchwabFilthyComfortable.jpg, checked by Claude) reads:

> FIND YOUR
> FILTHY COMFORTABLE

## Caption (draft)

> "FIND YOUR FILTHY COMFORTABLE" (Charles Schwab ad)
>
> An adjective phrase heads the noun phrase, with no noun. CGEL fuses it as modifier and head (left), as in "the rich". I'd draw it as an ordinary head (right).

The last sentence is the position of *Fusion of functions revisited* (lingbuzz/010465), abstract: for the modifier function, "there's none" (no evidence of form). The two trees differ only inside the object NP's nominal.

## Alt text

> Two syntax trees of "FIND YOUR FILTHY COMFORTABLE". In both, "YOUR" is the determiner and the adjective phrase "FILTHY COMFORTABLE", with "FILTHY" modifying "COMFORTABLE", heads the nominal. Left, CGEL's analysis: the adjective phrase is a fused modifier-head. Right: it is an ordinary head.

## Analysis notes

- CGEL side follows gold's *the best* (`ewt-test_iaa50.cgel` line 1250): `Nom [Head: Nom [Mod-Head: AdjP]]`. 0 validator warnings.
- Ordinary-Head side: the validator warns once (AdjP as head of a Nom), because it checks CGEL's grammar.
- *YOUR* is `Det: NP` with N_pro, as gold's *my*.

## Rulings needed before posting

1. **"FILTHY": Adj or Adv.** Drawn as Adj modifying Adj, as gold's *pure white* (`ewt.cgel` line 1273). Language Log quotes the OED treating *filthy* in *filthy rich* as an adverb.
2. **Format.** The pair with the caption above, or a second A/B poll like Halloween's.
