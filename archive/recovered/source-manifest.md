# EQ1 Recovered Source Manifest

- **Initial migration pass:** 2026-09-10
- **Last updated:** 2026-09-13
- **Repository:** `FarazShahid/eq1collections`
- **Purpose:** Inventory original, extracted, reconstructed, and versioned EQ1 collection-development sources.

## Provenance Classes

- **Exact readable source in repo** — original readable source committed unchanged and verifiable by blob hash.
- **Original source supplied / structured record recovered** — original project file was supplied and its identity/checksum plus substantive specification were recovered into the repository; full source file may still need byte-for-byte mirroring.
- **Exact structured source** — structured data copied from an original source file.
- **Readable extraction** — readable text recovered from a binary source, not byte-identical.
- **Exact project-chat fragment** — exact visible portion of a historical prompt.
- **Recovered project-development notes** — explicit decisions preserved from project conversation history.
- **Reconstructed record** — rebuilt only from explicit historical decisions and labeled accordingly.
- **Source-evidence record** — proves historical work existed but is not a full collection specification.

## Exact Recovered Template

The historical Collection Studio template that was previously missing is now committed unchanged:

- `templates/eq1-studio-collection-creator-template.v1 (1).md`
- bytes: **10,517**
- SHA-256: `a7b8a9e212fdc415ad454176701a4854f552637d00bf7387addd2823ceea24ff`
- Git blob SHA-1: `1452d41ea5d677273ceacd10a8132229cc888523`

The repository-native `templates/collection-record-template.md` remains a separate metadata/provenance template rather than a replacement for the Studio design-bible template.

## Active / Recovered Collection Records

| Collection / system | Repository path | Provenance / status |
|---|---|---|
| District M shared rules | `collections/district-m/README.md` | Reconstructed record |
| Collection Banners | `collections/galleries/collection-banners/README.md` | Reconstructed from project direction |
| Chainsaw Man | `collections/district-m/anime/chainsaw-man/` | Reconstructed + source evidence + project notes |
| Death Note | `collections/district-m/anime/death-note/collection-record.md` | Source-evidence record |
| Demon Slayer | `collections/district-m/anime/demon-slayer/collection-record.md` | Source-evidence record |
| Jujutsu Kaisen | `collections/district-m/anime/jujutsu-kaisen/` | Reconstructed + source evidence + project notes |
| One Piece | `collections/district-m/anime/one-piece/` | Reconstructed + exact prompt fragment |
| Arcane | `collections/district-m/original-series/arcane/collection-record.md` | Source-evidence record |
| KING ENERGY | `collections/men/t-shirts/king-energy/README.md` | Reconstructed partial identity |
| LANDMARKS | `collections/men/t-shirts/landmarks/` | Reconstructed + exact brief fragment |
| The Runtime | `collections/men/t-shirts/the-runtime/` | Reconstructed + exact prompt fragment |
| Ravaani 220 | `collections/women/women-tshirts/ravaani-220/` | Canonical working record; original source supplied 2026-09-13 |
| The Line | `collections/women/women-tshirts/the-line/README.md` | Original source supplied; 20-design structured record recovered |
| Rare Form | `collections/women/sweatshirts/rare-form/README.md` | Original V4 + V5 sources supplied; working record upgraded |
| Winter Bloom 280 | `collections/women/sweatshirts/winter-bloom/README.md` | Two conflicting versioned development branches preserved |
| MOVE DIFFERENTLY | `collections/women/tracksuits/move-differently/README.md` | Original 20-design source supplied; structured record recovered |
| Winter 2026 women's tracksuit WIP | `collections/women/tracksuits/winter-2026-development.md` | Historical WIP linked to MOVE DIFFERENTLY |
| Winter 2026 fabric colors | `winter-2026/base-fabric-colors.md` | Canonical physical-swatch reference record |

## 2026-09-13 Supplied Women Collection Sources

These original Markdown files were supplied directly in the EQ1 project on 2026-09-13. The exact filenames, sizes, and checksums are preserved here so any later byte-for-byte repository copy can be verified.

| Source file | Bytes | SHA-256 | Git blob SHA-1 | Repository interpretation |
|---|---:|---|---|---|
| `EQ1_Womens_Tracksuit_Move_Differently_20_Designs.md` | 95,829 | `7c65c99f8908417b380625fa8d942169751dc58880913463a5007d63578259b4` | `3e0c3274cc7831edb9b213c5e260fb622b2967eb` | MOVE DIFFERENTLY — 20-design women’s tracksuit source |
| `EQ1_Women_Rare_Form_Collection_Studio_V5.md` | 27,430 | `4fcfcc2486dcf3c30e390d8d9fa0384706b4301d088afff9177b1a7f43892666` | `b902b10430171b5e389e97e57bd5294c49729f00` | Latest supplied Rare Form Collection Studio bible |
| `EQ1_Women_Rare_Form_280_Cotton_Jersey_6_Designs_V4.md` | 22,945 | `faa9bc3e5a0e9bb9ee68a7afb4e5c5a06c981cdaea8103e4bd5d7451c8627532` | `aae021e4405bc1f745339a2a436fb365640645ea` | Rare Form production-oriented V4 source |
| `EQ1_Women_Winter_Bloom_280_Cotton_Jersey_6_Designs_V3.md` | 22,323 | `06740ddf6b875ca31a1653a1cd54658317f392f37774e7c9aa265359b9718a62` | `4ddd131fa2bd1a6ddd7b0e4d1650d3f8a5154b73` | Winter Bloom predecessor branch; 280 GSM cotton jersey contrast/tonal system |
| `EQ1_Women_Winter_Bloom_280_6_Designs_V4.md` | 63,083 | `166114114ec059d4d80e635b7f5c65b898bd78ab928ec0ed9e21b7257896a296` | `668e9d8fdf8157642a67a8b543d5bd9b68323593` | Separate working/proposed Winter Bloom branch; 280 GSM Cotton Fleece construction-led system |
| `eq1-studio-collection-creator-template.v1 (1).md` | 10,517 | `a7b8a9e212fdc415ad454176701a4854f552637d00bf7387addd2823ceea24ff` | `1452d41ea5d677273ceacd10a8132229cc888523` | **Exact source committed unchanged** in `templates/` |
| `EQ1_Women_Ravaani_220_12_Designs.md` | 76,390 | `dc681a4c06abb7d39a0f1eecc810aaae59ac933df4274b4b71230b0de7a1acaf` | `1100b8149f6e9a054b7b9505090d27ce320717a7` | Original Ravaani 220 12-design bible; validates canonical working record |
| `EQ1_Women_The_Line_20_Designs_Regenerated.md` | 129,793 | `1ed31b5d94890a18c25241d07be14b7b7df84b1de1cb7e133ede5efe32e75a9f` | `e69a1c4178223cc64f94133d640e744e596b7faf` | The Line — 20-design women’s long-T-shirt source |

## Version / Conflict Notes

### Rare Form vs Winter Bloom V3

Winter Bloom V3 contains essentially the predecessor naming for the six-design Butterfly/Swan/Archangel/Hummingbird/Crane/Moon-Moth system. The later Rare Form sources explicitly lock **RARE FORM** as the collection name and the 280 GSM cotton-jersey contrast/tonal product system. Preserve Winter Bloom V3 as development provenance; use Rare Form for the locked named collection.

### Winter Bloom V4

Winter Bloom V4 is not simply the next canonical version of Rare Form. It explicitly uses **280 GSM Cotton Fleece**, four monochrome swatch colors, six different construction-led products, and calls Winter Bloom 280 a working/proposed name. It must remain a separate development branch unless explicitly approved later.

### The Line vs Ravaani 220

Both are women’s knee-length long-T-shirt systems but are separate collections. The Line contains 20 designs, five main garment colors, broader soft-form experimentation, and a locked curvy mid-size model baseline. Ravaani 220 later resolves into a 12-design four-primary-color system with three variants per color and a broader young-audience body direction.

## Historical Exact / Extracted Sources

### Tracksuits — June 2026

- `archive/recovered/2026-06/tracksuits/EQ1_tracksuit_master_specification.txt` — exact readable source
- `archive/recovered/2026-06/tracksuits/README.txt` — exact readable source

### Men's T-shirts T01–T10

- `archive/recovered/2026-06/mens-tshirts/EQ1_First_10_TShirt_Master_Production_Packet.recovered.txt` — readable extraction
- `archive/recovered/2026-06/mens-tshirts/EQ1_First_10_Style_Metadata.json` — exact structured source
- `archive/recovered/2026-06/mens-tshirts/README.txt` — exact readable source
- `archive/recovered/2026-06/mens-tshirts/styles/` — individual readable packet extractions

### Men's T-shirts T15–T20

Exact companion README/index and `T15_Info.txt` through `T20_Info.txt` text is preserved under `archive/recovered/2026-06/mens-tshirts/additional-styles/`. No accessible T11–T14 source was found in the migration pass, so those styles are not inferred.

## Historical District M Asset Evidence

`archive/recovered/2026-07-08/district-m-source-asset-index.md` records retained generated-asset evidence for Chainsaw Man, Death Note, Demon Slayer, Jujutsu Kaisen, and Arcane without exposing private storage identifiers.

## Known Original Project Attachments Still Not Fully Recovered

The following historical filenames remain known but their original complete attachment text/bytes have not yet been supplied in this project context:

- `EQ1_KING_ENERGY_THE_RUNTIME_V4_Concise_3_Output_Full_20_Designs.md`
- `EQ1_Mens_Landmarks_V4_Concise_3_Output.md`

Ravaani 220 and the Collection Studio template are no longer on this missing-source list because their originals were supplied on 2026-09-13.

## Recovery Rule

Never label a reconstructed summary as a byte-identical original. When a full source file is mirrored into the repository, verify it against the recorded Git blob SHA-1 / SHA-256 above and then promote its status to **Exact readable source in repo**.