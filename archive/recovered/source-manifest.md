# EQ1 Recovered Source Manifest

- **Migration pass:** 2026-09-10
- **Repository:** `FarazShahid/eq1collections`
- **Purpose:** Inventory the material recovered from EQ1 project history and connected historical storage during the repository migration.

## Provenance Classes

- **Exact readable source** — text copied from an original readable source file.
- **Exact structured source** — structured data copied from an original source file.
- **Readable extraction** — text recovered from a binary document; not byte-identical to the original binary.
- **Exact project-chat fragment** — exact portion of a historical prompt visible in project history; source was longer.
- **Reconstructed record** — collection specification rebuilt only from explicit historical decisions and labeled accordingly.
- **Source-evidence record** — proves historical collection work existed but is not a full collection specification.

## Active Collection Records

| Collection / system | Repository path | Provenance |
|---|---|---|
| District M shared rules | `collections/district-m/README.md` | Reconstructed record |
| Chainsaw Man | `collections/district-m/anime/chainsaw-man/collection-record.md` | Reconstructed + source evidence |
| Death Note | `collections/district-m/anime/death-note/collection-record.md` | Source-evidence record |
| Demon Slayer | `collections/district-m/anime/demon-slayer/collection-record.md` | Source-evidence record |
| Jujutsu Kaisen | `collections/district-m/anime/jujutsu-kaisen/collection-record.md` | Reconstructed + source evidence |
| One Piece | `collections/district-m/anime/one-piece/collection-record.md` | Reconstructed record |
| One Piece master prompt fragment | `collections/district-m/anime/one-piece/recovered-master-prompt-fragment.md` | Exact project-chat fragment |
| Arcane | `collections/district-m/original-series/arcane/collection-record.md` | Source-evidence record |
| KING ENERGY | `collections/men/t-shirts/king-energy/README.md` | Reconstructed partial identity |
| LANDMARKS | `collections/men/t-shirts/landmarks/collection-record.md` | Reconstructed record |
| The Runtime | `collections/men/t-shirts/the-runtime/collection-record.md` | Reconstructed record |
| The Runtime master prompt fragment | `collections/men/t-shirts/the-runtime/recovered-master-prompt-fragment.md` | Exact project-chat fragment |
| Ravaani 220 | `collections/women/women-tshirts/ravaani-220/README.md` | Canonical repo record |
| Ravaani 220 generation prompt | `collections/women/women-tshirts/ravaani-220/generation-prompt.md` | Canonical repo prompt |
| Rare Form | `collections/women/sweatshirts/rare-form/README.md` | Reconstructed record |
| Winter 2026 women's tracksuits | `collections/women/tracksuits/winter-2026-development.md` | Active WIP record |
| Winter 2026 fabric colors | `winter-2026/base-fabric-colors.md` | Canonical physical-swatch reference record |

## Historical Exact / Extracted Sources

### Tracksuits

| File | Provenance |
|---|---|
| `archive/recovered/2026-06/tracksuits/EQ1_tracksuit_master_specification.txt` | Exact readable source |
| `archive/recovered/2026-06/tracksuits/README.txt` | Exact readable source |

### Men's T-shirts T01–T10

| File | Provenance |
|---|---|
| `archive/recovered/2026-06/mens-tshirts/EQ1_First_10_TShirt_Master_Production_Packet.recovered.txt` | Readable extraction from historical production packet |
| `archive/recovered/2026-06/mens-tshirts/EQ1_First_10_Style_Metadata.json` | Exact structured source |
| `archive/recovered/2026-06/mens-tshirts/README.txt` | Exact readable source |
| `archive/recovered/2026-06/mens-tshirts/styles/T01_Core_Crew_Production_Packet.recovered.txt` | Readable extraction |
| `archive/recovered/2026-06/mens-tshirts/styles/T02_Relaxed_Core_Crew_Production_Packet.recovered.txt` | Readable extraction |
| `archive/recovered/2026-06/mens-tshirts/styles/T03_Supima_Soft_Crew_Production_Packet.recovered.txt` | Readable extraction |
| `archive/recovered/2026-06/mens-tshirts/styles/T04_Clean_V-Neck_Production_Packet.recovered.txt` | Readable extraction |
| `archive/recovered/2026-06/mens-tshirts/styles/T05_Heavyweight_Box_Crew_Production_Packet.recovered.txt` | Readable extraction |
| `archive/recovered/2026-06/mens-tshirts/styles/T06_Heavy_Straight_Tee_Production_Packet.recovered.txt` | Readable extraction |
| `archive/recovered/2026-06/mens-tshirts/styles/T07_Split_Hem_Tee_Production_Packet.recovered.txt` | Readable extraction |
| `archive/recovered/2026-06/mens-tshirts/styles/T08_Minimal_Mock_Neck_Tee_Production_Packet.recovered.txt` | Readable extraction |
| `archive/recovered/2026-06/mens-tshirts/styles/T09_Equilibrium_Center_Tee_Production_Packet.recovered.txt` | Readable extraction |
| `archive/recovered/2026-06/mens-tshirts/styles/T10_Equilibrium_Washed_Tee_Production_Packet.recovered.txt` | Readable extraction |

### Men's T-shirts T15–T20

The exact companion README, index, and `T##_Info.txt` source text is preserved under:

- `archive/recovered/2026-06/mens-tshirts/additional-styles/T15-T16/`
- `archive/recovered/2026-06/mens-tshirts/additional-styles/T17-T18/`
- `archive/recovered/2026-06/mens-tshirts/additional-styles/T19-T20/`

No accessible T11–T14 source was found in this migration pass; those styles are intentionally not inferred.

## Historical District M Asset Evidence

`archive/recovered/2026-07-08/district-m-source-asset-index.md` records identifiable retained generated assets for:

- Chainsaw Man
- Death Note
- Demon Slayer
- Jujutsu Kaisen
- Arcane

This evidence is deliberately recorded without private source-storage identifiers.

## Known Historical Project Attachments Not Yet Byte-Recovered

These filenames are known from project history but their original attachment bytes are not exposed to the current runtime:

- `EQ1_KING_ENERGY_THE_RUNTIME_V4_Concise_3_Output_Full_20_Designs.md`
- `EQ1_Mens_Landmarks_V4_Concise_3_Output.md`
- `EQ1_Women_Ravaani_220_12_Designs.md`
- `eq1-studio-collection-creator-template.v1 (1).md`

Where exact prompt fragments or reconstructed records are available, they are kept separately and are never mislabeled as the unavailable original file.

## Binary Sources Not Duplicated in This Pass

Historical production PDFs, DOCX files, tech-pack PNGs, website/product images, and generated collection artwork exist in connected source storage. The GitHub write interface used for this migration is text-oriented, so those binaries were not silently replaced by fake files. Readable text and metadata were preserved wherever retrievable.
