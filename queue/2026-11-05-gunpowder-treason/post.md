# Gunpowder treason
<!-- SUMMARY: Guy Fawkes rhyme, "forgot" as past participle; tree drafted by a subagent · status: draft, awaiting Brett's review · updated: 2026-10-30 -->

**Slot:** Thursday 5 November (Guy Fawkes Night)
**Image:** `tree.png` (re-render with `bin/render queue/2026-11-05-gunpowder-treason/tree.cgel`); validator: 0 warnings

## Source

J. O. Halliwell, *The Nursery Rhymes of England*, 5th edn (London and New York: Frederick Warne, 1886), no. XV, p. 7; Project Gutenberg #32415, lines 415–422 (Claude checked the text):

> Please to remember
> The fifth of November,
>   Gunpowder treason and plot;
> I know no reason
> Why gunpowder treason
>   Should ever be forgot.

The familiar *see* version: Charlotte S. Burne, "Guy Fawkes' Day", *Folk-Lore* 23 (1912), p. 411: "I see no reason why Gunpowder treason / Should ever be forgot." (subagent read the Wikisource transcription, not the scan).

## Caption (draft)

> "I know no reason / Why gunpowder treason / Should ever be forgot." (Halliwell, 1886)
>
> After passive be, forgot is a past participle. CGEL gives forgotten as forget's only past participle (p. 1610). Here forgot rhymes with plot.

CGEL p. 1610: "Forget has the forms forget ∼ forgot ∼ forgotten ... except that the past participle has only the form with ·en" (Claude checked the text).

## Alt text

> Syntax tree in the style of the Cambridge Grammar of the English Language. [Clause [Subj: NP I] [Head: VP [Head: V know] [Obj: NP [Det: DP no] [Head: Nom [Head: N reason] [Mod: Clause_rel [Prenucleus: AdvP Why] [Head: Clause_rel [Subj: NP gunpowder treason] [Head: VP [Head: VP [Head: V_aux Should] [Comp: Clause [Head: VP [Mod: AdvP ever] [Head: VP [Head: V_aux be] [Comp: Clause [Head: VP [Head: V forgot]]]]]]] [Mod: GAP]]]]]]]]; the gap is linked to "Why".

## Rulings

- **Wording** (Brett, 2026-10-30): Halliwell's *know*, as drawn.

Still open:

1. **Gap height for *why*.** High, as Mod of the relative's outermost VP, following `oneoff/bakhmut.cgel` lines 85 and 184. Gold has no *reason why* relative at all.
2. **Where *ever* attaches** (inside *should*'s complement, following `ewt-test_iaa50.cgel` line 1152; gold isn't uniform).
3. **Verse capitals** *Why* and *Should*, kept under the source-capitalization rule.
