# To give A.I. access to all of its 51 million citizens
<!-- SUMMARY: NYT ambiguity, indirect object vs to-complement, pair image; trees drafted by Claude · status: draft, awaiting Brett's review · updated: 2026-10-30 -->

**Slot:** Monday 2 November
**Image:** `pair.png` (re-render with `bin/pair queue/2026-11-02-ai-access/reading-a.cgel queue/2026-11-02-ai-access/reading-b.cgel queue/2026-11-02-ai-access/pair`)

## Source

Beth Simone Noveck, "How AI can be good for democracy", *New York Times* opinion, 6 October 2026, as quoted in Mark Liberman, "An ominous syntactic ambiguity", *Language Log*, 7 October 2026, https://languagelog.ldc.upenn.edu/nll/?p=74365 (Claude checked the quotation there; the NYT page was walled):

> In return for providing government funding, South Korea is securing contracts with multiple tech and telecom companies to give A.I. access to all of its 51 million citizens.

The trees are of the infinitival clause only.

## Caption (draft)

> "to give A.I. access to all of its 51 million citizens" (NYT, via Language Log)
>
> Left: A.I. is the indirect object, so the AI gets access to the citizens. Right: "A.I. access" is the object and "to all of its citizens" a complement, so the citizens get the AI.

## Alt text

> Two syntax trees of "to give A.I. access to all of its 51 million citizens". Left: give has an indirect object NP "A.I." and a direct object NP "access to all of its 51 million citizens". Right: give has an object NP "A.I. access", with "A.I." modifying "access", and a complement PP "to all of its 51 million citizens".

## Analysis notes

- Ditransitive labels `Obj_ind` and `Obj_dir` as in gold (*give her a ...*, `ewt.cgel` line 1012). *A.I.* modifying *access* follows gold's *Honda models* (`Mod: Nom`).
- *51 million* is a `Mod: DP` after the determiner *its*, written as a flat D as in gold's *120 million* (`ewt.cgel` line 1093).

## Rulings needed before posting

1. **"all" in *all of its citizens*.** Drawn with your ordinary Head (*Fusion of functions revisited*: the of-phrase is "a complement in the nominal headed by" the determinative), not CGELBank's fused Det-Head. The validator warns once in each tree. Should this be the account's default for determinatives standing alone, outside the polls?
2. **Size.** The image is 3121 × 2615. The two readings differ only at the VP, which reads at phone width, but the NP below is small.
