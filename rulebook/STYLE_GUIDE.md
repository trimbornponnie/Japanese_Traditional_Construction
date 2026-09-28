# Style Guide for the Rulebook (for authors/contributors)

All chapters of this rulebook follow the same conventions so the book reads as one reference.

## 1. File & heading conventions
- One chapter per file: `NN-slug.md` (e.g. `07-tsugite-splice-joints.md`).
- First line: `# Chapter NN — English Title (日本語 / rōmaji)`.
- Then a short "Scope" paragraph and a local table of contents.
- `##` for sections, `###` for sub-sections / individual joints or components.

## 2. Terminology
- On first use in a chapter, write every Japanese term as: **English gloss** (日本語, *rōmaji*) — e.g. **lap dovetail on a seat** (腰掛蟻継ぎ, *koshikake-ari-tsugi*).
- Rōmaji uses modified Hepburn with macrons (ō, ū). Afterwards the rōmaji alone may be used.
- Units: give traditional units first, metric in brackets: 4 sun (≈121 mm). 1 shaku = 10 sun = 100 bu = 303.03 mm (kanejaku, since 1891).

## 3. Rules
- The book is a *rule book*. Normative statements are written as numbered rules in bold ID form:
  - `**R07-012** — Koshikake-ari splices are placed within 150 mm (≈5 sun) of a support, never at mid-span.`
- Rule ID = `R` + chapter number + `-` + three-digit serial within the chapter.
- After each rule, give the *reason* ("Why:") when it is not obvious. Rules without reasons are less useful.
- Distinguish strength of rule:
  - **Must** — structural/traditional necessity; violating it leads to failure or is universally considered wrong.
  - **Should** — strong customary practice; exceptions exist.
  - **May / Variant** — regional, school-specific or period-specific practice.
- Where a practice differs by region (Kansai/Kantō), period, or building type (shrine, temple, minka, sukiya), say so.

## 4. Joint / component entry template
For every joint or component use this template (omit fields that genuinely do not apply):

```
### Name — English (日本語, rōmaji)
- **Class:** tsugite (splice) / shiguchi (connection) / hozo / wedge …
- **Typical use:** which members, where in the building
- **Load behaviour:** tension / compression / bending / shear / what it resists and what it does not
- **Proportions:** in terms of member width/depth (e.g. tongue length = 1.0–1.5 × depth) AND typical absolute sizes
- **Orientation rules:** which piece is male (男木 *ogi*) / female (女木 *megi*), which is on top, which faces the support, moto/sue direction
- **Marking (墨付け sumitsuke):** reference lines used
- **Cutting sequence:** numbered steps
- **Assembly:** order, direction of insertion, pins/wedges, kigoroshi
- **Rules:** numbered R-rules
- **Common errors:** what goes wrong
- **Variants:** related forms
- **ASCII sketch:** optional simple diagram in a code block
```

## 5. Accuracy
- Do not invent citations. Only cite works you are confident exist. When uncertain of a detail (page, year, exact ratio), say "c." / "approximately" / "one common reading".
- Proportional figures from historical *kiwari* texts vary between schools and editions; present them as "representative" and note the variation.
- Prefer ranges over false precision.

## 6. Diagrams
- Simple ASCII diagrams in fenced code blocks are welcome where they clarify geometry.
- Tables are encouraged for dimension series, sizes, species properties, etc.

## 7. Cross-references
- Refer to other chapters as `→ Ch. 07 §3` and to rules as `→ R07-012`.
