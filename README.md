# EQ1 Collections

This repository is the working source of truth for **EQ1 collection design and development**.

It records collection concepts, physical fabric colors, garment specifications, generation prompts, prompt revisions, production constraints, recovered historical development files, and final approvals as the collections evolve.

## Repository Structure

- `collections/` — active collection taxonomy and collection-specific records
- `winter-2026/` — seasonal physical fabric / color references
- `templates/` — canonical repository templates for new collection records
- `archive/recovered/` — historical source material recovered from earlier EQ1 development work

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

- Women T-shirts
  - Ravaani 220
- Sweatshirts
  - Rare Form
- Tracksuits
  - Winter 2026 development in progress

### Galleries

- Collection Banners
- K-POP ICONS — GLOBAL SIGNAL

For the complete taxonomy see [`collections/README.md`](collections/README.md).

## Recovery / Migration Status

A project-history recovery pass was performed on **2026-09-10**. Every source that was reliably exposed through the active project history or connected historical storage was either:

1. preserved as exact readable text / structured data,
2. stored as a clearly labeled readable extraction,
3. preserved as an exact visible prompt fragment, or
4. reconstructed only from explicit project decisions and labeled as reconstructed.

No missing prompt, collection specification, or binary source is intentionally fabricated.

See:

- [`collections/chat-document-recovery-index.md`](collections/chat-document-recovery-index.md)
- [`archive/recovered/source-manifest.md`](archive/recovered/source-manifest.md)

## Physical Fabric / Color Records

Winter 2026 base fabric colors are recorded at:

- [`winter-2026/base-fabric-colors.md`](winter-2026/base-fabric-colors.md)

Physical swatches are the production reference. Camera-derived HEX values are visual approximations rather than dye specifications.

## Collection Record Standard

Use:

- [`templates/collection-record-template.md`](templates/collection-record-template.md)

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

Historical material under `archive/recovered/` is evidence and reference; it does not silently override current approved collection specifications.

## Public Repository Safety

Do not commit credentials, private connector IDs, private storage URLs, confidential supplier access details, or other secrets. Historical source references should be preserved without exposing private access metadata.
