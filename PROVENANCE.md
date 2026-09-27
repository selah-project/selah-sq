# PROVENANCE — how this rendering came to be

*Albanian (shqip), chair 101. Floor 23,213 verses.*

This is the record of how the text in this repository was produced and what had
to be corrected in it. A machine-assisted rendering has no standing unless you
can see how it was made, so this file says both — **including the faults, and
including the ones found by accusing the machine of things it had got right.**

---

## The approach

Every verse is rendered from the Hebrew of that verse, under a written discipline
— `docs/methodology/translation-discipline/sq.md` in the Selah project, itself
written in Albanian. The rules: the Hebrew token is the unit; the Name stays the
Name; both truths of Deuteronomy 6:4; no foreknowledge, so Genesis 22:1 does not
know Genesis 22:13; numbers and marks stay put; the Tanakh only, with no New
Testament vocabulary reaching back into it.

The source text is the Hebrew consonantal stream with its pointing, token by
token. Each verse produces two surfaces: a **gloss per Hebrew token**, and a
**flow** — the verse as an Albanian sentence. Both are kept, because they can
disagree, and where they disagree something is wrong.

## What this chair inverted

Albanian is the first chair of its kind in this fleet, and it overturned three
rules that the previous chair needed:

- **`ë` and `ç` are letters of the alphabet.** The previous chair (Shona) wrote no
  diacritics at all, and a check there stripped every accented character as stray
  decoration. That check **could not be copied**; it would have convicted correct
  Albanian on every other line. It was deleted rather than adapted.
- **`l` and `ll` are different letters**, and the digraphs `dh gj ll nj rr sh th
  xh zh` are single letters. The previous chair collapsed doubled consonants.
- **Albanian permits final consonants**, so `Elohim` stands where the previous
  chair needed a vowel appended.

## Where the rules had to be written mid-course

Four rules were added to the discipline while the rendering was running, each
because a fault appeared that no existing rule named:

1. **Numeral order.** Hebrew writes the unit before the ten — `חמש וששים`, *five
   and sixty* = 65. Albanian writes the ten before the unit. The machine kept
   Hebrew's order and, because Albanian builds tens by suffixing, produced
   **well-formed Albanian numbers with the wrong value**: 65 → 56, 95 → 59,
   32 → 42, 403 → 433. The gloss row had both words right in every case; only
   the flow recomposed them.
2. **`שה` is the lamb.** It had 29 appearances and 23 different renderings,
   including *one*, *the thousand* and *head* — and the three worst were in
   Exodus 12, where the Passover is instituted. The machine knew the word: at
   Genesis 22:7–8 it wrote `qengji` correctly. **The scatter was the fault, not
   ignorance.**
3. **`שאול` is three different referents** — the king, Simeon's son, and the place
   of the dead. The king was written two ways, `Saul` 255 times and `Shaul` 42,
   in the same two books.
4. **The Name's stem.** `Jehovai` and `për Jehovain` appeared in Exodus 13:14–16.
   Albanian suffixes case onto the root, so forbidding a nominative leaves every
   other form unnamed; the rule had to name the root.

**The first three of those four are not demonstrated to have taken hold.** The
fourth demonstrably did not: `Jehova` forms continued to appear for two hours
after the rule was written. That is recorded rather than smoothed over.

## Faults found and not yet cured

Named here so a reader knows what to expect:

- **Corrupted Hebrew surfaces.** A token's Hebrew is a verbatim copy of the
  source, but some hold Latin letters — a Hebrew letter replaced by its own
  transliteration mid-word (`תעבod` for `תעבד`), or the whole word Latinized
  (`zekhub` for `זהב`, *gold*). This is not confined to this rendering; it occurs
  across the fleet at a similar rate.
- **Malformed marks.** `⟨do të> shfaqet` closes an angle bracket with an ASCII
  `>`; one bracket pair is empty; some brackets swallow the following noun.
- **The mark where the text has none.** `⟨את⟩` appears in some flows where the
  Hebrew verse contains no `את` at all.
- **Invented words.** A handful of words in the text are not Albanian and not
  anything else — including one Spanish word, `ofrece`.
- **Deliberation left in the text.** In a few verses the machine's own working is
  visible: a self-correction written into the verse, or grammatical terminology
  where a rendering should be.

## What was measured wrongly, and corrected

The checks that produced the list above also produced false accusations, and
several were caught only by reading the verses:

- A number probe convicted 433 verses of inventing *one* — `një` is the Albanian
  **indefinite article**, which Hebrew lacks and the flow must supply.
- The same probe convicted `tribut` of containing *three*, and a date formula of
  inventing a numeral, because in Albanian **the ordinal is marked by a preceding
  article, not a suffix** — `muajin e gjashtë` is *the sixth month*.
- A word-list check convicted `the` and `ma`, which are Albanian verb and clitic
  forms, not English and Italian.
- A boundary widened to catch declined forms then convicted `Godit` — the
  Albanian verb *to strike*, at Amos 9:1 and 2 Kings 6:18, where the Hebrew is
  `הך`, *smite*.
- A fixed-term audit flagged `ברית` as untranslated where it is **Baal-Berith**,
  a proper name; `נביא` where the Hebrew is the hiphil of `בוא`, *to bring*; and
  `קרבן` four times where `בקרבנו` is `ב`+`קרב`+`נו`, *in our midst*.

Every one of those is the same law: **a word lawful in the language cannot be
convicted by a pattern that does not know the language.**

## The standing of this text

**Unreviewed by a native speaker.** It is published openly because a hidden text
cannot be corrected. `CONTRIBUTING.md` says what is a deliberate choice, what is
a fault, and what is an open question — in Albanian, for the reader who can
judge it.
