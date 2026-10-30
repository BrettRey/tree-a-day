# Macbeth 4.1, four trees
<!-- SUMMARY: four-image Halloween post from the cauldron scene (First Folio): imperatives with subject, vocative, exhaustive conditional, and imperative + subjunctive · status: draft, awaiting Brett's review · updated: 2026-10-30 -->

**Slot:** Saturday 31 October (Halloween), one post with four images in scene order
**Images:** `boyle.png`, `tree.png`, `lockes.png`, `deny.png` (re-render each with `bin/render queue/2026-10-31-fire-burn/<name>.cgel`)

## Source

Shakespeare, *Macbeth* 4.1, First Folio text, Project Gutenberg #1129 (Claude checked each line):

1. Line 2102, a witch to the toad: "Boyle thou first i'th' charmed pot"
2. Line 2105, All: "Fire burne, and Cauldron bubble"
3. Line 2150, Second Witch: "Open Lockes, who euer knockes."
4. Lines 2253–2254, Macbeth to the witches: "Deny me this, / And an eternall Curse fall on you: Let me know."

## Caption

> Syntax trees from Macbeth for Hallowe'en

(Brett, 2026-10-30.)

## Alt text, one per image

1. Syntax tree in the style of the Cambridge Grammar of the English Language. [Clause [Prenucleus: V Boyle] [Head: Clause [Subj: NP thou] [Head: VP [Head: VP [Head: GAP] [Mod: AdvP first]] [Mod: PP [Head: P i'] [Obj: NP [Det: DP th'] [Head: Nom [Mod: AdjP charmed] [Head: N pot]]]]]]]; the gap is linked to "Boyle".
2. Syntax tree in the style of the Cambridge Grammar of the English Language. [Coordination [Coordinate: Clause [Vocative: NP Fire] [Head: Clause [Head: VP [Head: V burne]]]] [Coordinate: Clause [Marker: Coordinator and] [Head: Clause [Vocative: NP Cauldron] [Head: Clause [Head: VP [Head: V bubble]]]]]]
3. Syntax tree in the style of the Cambridge Grammar of the English Language. [Clause [Head: VP [Head: VP [Head: V Open] [Vocative: NP Lockes]] [Mod: Clause [Prenucleus: NP who euer] [Head: Clause [Subj: GAP] [Head: VP [Head: V knockes]]]]]]; the gap is linked to "who euer".
4. Syntax tree in the style of the Cambridge Grammar of the English Language. [Coordination [Coordinate: Clause [Head: VP [Head: V Deny] [Obj_ind: NP me] [Obj_dir: NP [Head: Nom [Head: DP this]]]]] [Coordinate: Clause [Marker: Coordinator And] [Head: Clause [Subj: NP [Det: DP an] [Head: Nom [Mod: AdjP eternall] [Head: N Curse]]] [Head: VP [Head: V fall] [Comp: PP [Head: P on] [Obj: NP you]]]]]]

## Analysis notes

1. **Boyle thou first.** The lexical verb comes before its subject, drawn like gold's auxiliary inversion (*NZers: Have you decided*, `ewt-test_pilot5.cgel` line 6) with a gap in the VP. The validator warns twice because present-day English inverts only auxiliaries, which is the point of the tree. *first* as Adv has no gold precedent (gold has only attributive Adj *first*). *charmed* is Adj. *i'th'* is two tokens, *i'* (P) and *th'* (D).
2. **Fire burne.** Vocatives plus imperatives, "probably imperative" with the subjunctive kept as the alternative, following the analysis Brett pasted. Citations checked: "Boyle thou first" (line 2102), "Starres hide your fires" with no comma (line 550), and this scene's own subjunctive (line 2254). The validator's two warnings are false positives: its unary-rule check ignores Vocative dependents.
3. **Open Lockes, who euer knockes.** *Lockes* is a vocative inside the VP, as in gold's *thank you Just Autos for your help* (`ewt.cgel` line 2046). *who euer knockes* is an exhaustive conditional ("no matter who knocks"), not a fused relative. CGEL p. 429: compounds in *-ever* "are found only in fused relatives ([Whoever said that] was wrong) and in the exceptional interrogative construction that functions as exhaustive conditional adjunct (I shan't be attending the meeting, [whoever takes over as chair])". It contrasts with the Klingon *Whoever dies with honor*, which is a fused relative. *who euer* is one N_pro with two orthographic words (the validator notes it).
4. **Deny me this, And an eternall Curse fall on you.** An imperative coordinated with a subjunctive. The reading is roughly "if you deny me this, may an eternal curse fall on you". *this* is drawn as ordinary Head, the same open convention question as *all* in the 2 November draft.

## Rulings needed before posting

1. **Lockes:** vocative, as drawn and as modern editions punctuate it ("Open, locks, / Whoever knocks!"), or the object of *Open*.
2. **"this":** ordinary Head or CGELBank's Det-Head (the same question as for *all* on 2 November).
3. **Caption:** wording, and whether *boss things about* fits #4.
