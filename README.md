# EQ1 Collections

This repository is the working source of truth for **EQ1 collection design and development**.

It records collection concepts, physical fabric colors, garment specifications, generation prompts, prompt revisions, production constraints, recovered historical development files, and final approvals as the collections evolve.

## Repository Structure

- `collections/` — active collection taxonomy and collection-specific records
- `winter-2026/` — seasonal physical fabric / color references
- `templates/` — Collection Studio generation template plus repository metadata template
- `archive/recovered/` — historical source material and recovery provenance

## Current Collection Families

### District M

- Anime
- K-pop Music
- Original Series

### Men

- T-shirts
  - KING ENERGY
  - LANDMARKS
  - POWERLINE
  - The Runtime

### Women

- Long T-shirts / coordinated sets
  - Ravaani 220
  - The Line
- Sweatshirts
  - Rare Form
  - Winter Bloom 280 — versioned development branch
- Tracksuits
  - MOVE DIFFERENTLY
  - Winter 2026 WIP retained as development provenance

### Galleries

- Collection Banners
- K-POP ICONS — GLOBAL SIGNAL

For the complete taxonomy see [`collections/README.md`](collections/README.md).

## Recovery / Migration Status

The initial project-history recovery pass was performed on **2026-09-10** and expanded on **2026-09-13** when additional original women’s collection files were supplied.

The repository now distinguishes among:

1. exact original readable sources,
2. structured records derived from supplied originals with checksums preserved,
3. readable extractions from historical binary files,
4. exact prompt fragments,
5. reconstructed project-history records, and
6. source-evidence-only records.

No missing prompt, collection specification, or binary source is intentionally fabricated.

See:

- [`collections/chat-document-recovery-index.md`](collections/chat-document-recovery-index.md)
- [`archive/recovered/source-manifest.md`](archive/recovered/source-manifest.md)

## Recovered Collection Studio Template

The exact historical Collection Studio generation template is now available at:

- [`templates/eq1-studio-collection-creator-template.v1 (1).md`](templates/eq1-studio-collection-creator-template.v1%20(1).md)

It defines the EQ1 V4 Design Bible structure and the rule that a design contains either **Image 1 only** or the complete **Image 1 / Image 2 / Image 3** sequence — never exactly two outputs.

The separate [`templates/collection-record-template.md`](templates/collection-record-template.md) is a repository-native metadata/provenance template.

## Physical Fabric / Color Records

Winter 2026 base fabric colors are recorded at [`winter-2026/base-fabric-colors.md`](winter-2026/base-fabric-colors.md).

Physical swatches are the production reference. Camera-derived HEX values are visual approximations rather than dye specifications.

## Collection Record Standard

A mature collection record should preserve, at minimum:

- date / time and season
- garment type and audience
- fabric composition, construction, GSM, and finish
- approved physical colors
- garment cut / construction rules
- branding and artwork rules
- collection design matrix
- master generation prompt
- per-design prompts and guardrails
- prompt revision history
- model / presentation direction
- production constraints
- source assets / provenance
- final approved designs and samples

## Source Priority

When records conflict, use this priority:

1. final approved production specification / sample
2. collection-specific canonical master file
3. collection-specific approved prompt / record
4. physical seasonal fabric record
5. recovered original source text
6. reconstructed project-history notes
7. shared / global collection rules

Versioned development sources should be preserved rather than merged when they conflict. **Winter Bloom 280** is the current example: its supplied V3 and V4 files define different fabrics and product systems and therefore remain separate development branches until explicitly approved.

## Public Repository Safety

Do not commit credentials, private connector IDs, private storage URLs, confidential supplier access details, or other secrets. Historical source references should be preserved without exposing private access metadata.
