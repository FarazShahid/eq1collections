# EQ1 Recovered Source Archive

This directory preserves recoverable collection-development source material that predates or sits outside the current collection taxonomy.

- **Migration date:** 2026-09-10
- **Purpose:** Preserve source specifications, metadata, production references, and source-asset evidence before they are lost or fragmented across project conversations and storage.
- **Source handling:** Readable text and structured metadata are copied into the repository. Private connector IDs, private storage URLs, credentials, and confidential access metadata are deliberately omitted.
- **Binary handling:** Large image, PDF, and DOCX binaries are not automatically duplicated into this public repository during recovery. Their readable text, exact companion `.txt` / `.json` files, or structured metadata may be preserved here instead.
- **`.recovered.txt` convention:** Indicates readable text extracted from an original non-text source such as DOCX. It is not a byte-identical copy of the source binary.
- **Canonical-vs-archive rule:** A file in `archive/recovered/` is historical evidence. Active collection directories contain the current canonical design specification unless explicitly stated otherwise.

## Recovered groups

### 2026-06 / Tracksuits

Historical EQ1 tracksuit master specification covering six Formal Tracksuits (`FTS01–FTS06`) and six Casual Tracksuits (`CTS01–CTS06`), including fabric, color, garment, branding, and construction direction.

Files:

- `2026-06/tracksuits/EQ1_tracksuit_master_specification.txt`
- `2026-06/tracksuits/README.txt`

### 2026-06 / Men's T-shirts — T01–T10

Historical first-10 men's T-shirt production packet and exact structured style metadata for `T01–T10`, including fabric families, GSM, colors, fit, construction, and branding direction.

Files include:

- master production-packet text extraction
- exact JSON style metadata
- original packet README text
- individual readable production-packet extractions for T01 through T10 under `styles/`

### 2026-06 / Men's T-shirts — Additional T15–T20

Additional historical production-packet material was recovered for:

- T15 Travel Tee
- T16 Air-Flow Panel Tee
- T17 Pique Tee
- T18 Micro Waffle Tee
- T19 Jacquard Texture Tee
- T20 Studio Oversized Tee

Exact companion README, index, and style-information text files are preserved under `2026-06/mens-tshirts/additional-styles/`. The historical tech packs and website/detail images exist as binaries in source storage but are not automatically duplicated into this public text archive.

No accessible `T11–T14` source was found during this migration pass, so those codes are not fabricated or assumed.

### 2026-07–08 / District M source assets

`2026-07-08/district-m-source-asset-index.md` records identifiable retained generated-asset evidence for Chainsaw Man, Death Note, Demon Slayer, Jujutsu Kaisen, and Arcane without exposing private source-storage identifiers.

## Recovery principles

1. Preserve original readable text whenever possible.
2. Do not silently merge historical specifications into a current collection.
3. Mark reconstructed information as reconstructed.
4. Keep physical fabric records separate from generated-image color approximations.
5. When the exact original project attachment becomes available, store it unchanged and retain recovered text as provenance.
6. Do not invent missing sequence numbers, styles, prompts, or collection assignments.
