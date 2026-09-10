# EQ1 Collection Chat Document Recovery Index

- Recorded: 2026-09-10
- Last updated: 2026-09-10
- Purpose: Track collection documents recovered from EQ1 project history, identify source evidence, and show which original source files still need exact recovery.
- Rule: Do not invent missing collection specifications. Reconstructed records must clearly state that they are reconstructed; original project files replace them as canonical source when recovered.

## Recovery Status Legend

- **Canonical in repo** — active structured collection record / prompt is already present.
- **Reconstructed from project chat** — useful specification rebuilt from explicit project decisions; exact original attachment bytes unavailable.
- **Partial + source evidence** — project/asset evidence confirms development, but the full collection specification is not yet recovered.
- **Scaffold only** — taxonomy folder exists but no reliable detailed source has been recovered yet.

## Recovered / Recorded Collections

| Collection | Repository record | Recovery status | Known source / evidence |
|---|---|---|---|
| Chainsaw Man | `district-m/anime/chainsaw-man/collection-record.md` | Reconstructed + source assets corroborated | 2026-07-14 design conversation + retained generated artwork set |
| Death Note | `district-m/anime/death-note/collection-record.md` | Partial + source evidence | Historical `03 - Death note` generated-artwork folder, 2026-07-13 |
| Demon Slayer | `district-m/anime/demon-slayer/collection-record.md` | Partial + source evidence | Historical `D5 Design 3: Demon Slayer 'ONI' + the collection`, 2026-07-02 |
| Jujutsu Kaisen | `district-m/anime/jujutsu-kaisen/collection-record.md` | Reconstructed + source assets corroborated | Design conversation + retained Sukuna design evidence |
| One Piece | `district-m/anime/one-piece/collection-record.md` | Reconstructed from project chat | `EQ1 MASTER PROMPT — ONE PIECE COLLECTION` content partially visible in project history |
| Arcane | `district-m/original-series/arcane/collection-record.md` | Partial + source evidence | Retained Arcane ComfyUI generated-asset set, 2026-08-20 |
| LANDMARKS | `men/t-shirts/landmarks/collection-record.md` | Reconstructed from project chat | Known original artifact `EQ1_Mens_Landmarks_V4_Concise_3_Output.md` |
| The Runtime | `men/t-shirts/the-runtime/collection-record.md` | Reconstructed from project chat | Known original artifact `EQ1_KING_ENERGY_THE_RUNTIME_V4_Concise_3_Output_Full_20_Designs.md` |
| Ravaani 220 | `women/women-tshirts/ravaani-220/` | Canonical in repo | Source record `EQ1_Women_Ravaani_220_12_Designs.md`; README + canonical generation prompt present |
| Rare Form | `women/sweatshirts/rare-form/README.md` | Reconstructed from project chat | 2026-09-06 women's sweatshirt development session |
| Winter 2026 Women's Tracksuits | `women/tracksuits/winter-2026-development.md` | Active WIP | Current swatch + style-reference development session; collection name/spec not yet locked |

## Recovered Historical / Production Sources

Historical collection-development sources that are useful to preserve but do not map cleanly to a single current named collection are stored under `../archive/recovered/`.

### Historical EQ1 Tracksuits — June 2026

Recovered exact readable specification:

- `../archive/recovered/2026-06/tracksuits/EQ1_tracksuit_master_specification.txt`
- `../archive/recovered/2026-06/tracksuits/README.txt`

The specification covers:

- Formal Tracksuits `FTS01–FTS06`
- Casual Tracksuits `CTS01–CTS06`
- Interlock 240–280 GSM
- SHY fabric
- Scuba
- Cotton-poly light fleece
- Woven fabrics
- color, top, bottom, branding, and construction direction per style

These are preserved as historical source evidence and should not automatically be treated as the current Women's Winter 2026 tracksuit collection.

### Historical EQ1 Men's T-shirts — First 10 Styles

Recovered:

- `../archive/recovered/2026-06/mens-tshirts/EQ1_First_10_TShirt_Master_Production_Packet.recovered.txt`
- `../archive/recovered/2026-06/mens-tshirts/EQ1_First_10_Style_Metadata.json`
- `../archive/recovered/2026-06/mens-tshirts/README.txt`

The source covers `T01–T10`, fabric families, GSM, fits, colors, construction, and centered lowercase `equilibrium` branding. The `.recovered.txt` file is readable text extracted from the historical DOCX, not a byte-identical binary copy.

## Standard / Template Artifacts

Historical attachment referenced in later project sessions:

`eq1-studio-collection-creator-template.v1 (1).md`

Its original attachment bytes are not exposed in the current runtime, so it has not been falsely recreated as an original. A new repository-native canonical template now exists at:

- `../templates/collection-record-template.md`

## Collection Folders Still Awaiting Detailed Source Recovery

### District M — Anime

- Attack on Titan
- Black Clover
- Bleach
- Blue Lock
- Dan Da Dan
- Dragon Ball
- Hunter x Hunter
- My Hero Academia
- Naruto
- Solo Leveling
- Spy x Family
- Vinland Saga

### District M — K-pop Music

- K-pop Music hub exists; detailed collection source document not recovered yet.

### District M — Original Series

- Avatar The Last Airbender
- Blood of Zeus
- Blue Eye Samurai
- Castlevania
- Castlevania Nocturne
- Cyberpunk Edgerunners
- Devil May Cry
- Invincible
- The Legend of Korra

### Men — T-shirts

- KING ENERGY — standalone source beyond its relationship to The Runtime not yet recovered.
- POWERLINE — detailed source document not yet recovered.

### Galleries

- Collection Banners
- K-POP ICONS — GLOBAL SIGNAL

## Global Design Rules Recovered From Project History

Shared District M rules now live in `district-m/README.md`. Important recovered rules include:

- `EQ1` is written in capitals where that brand treatment is specified.
- Anime and Original Series collections are unisex.
- Female-oriented series may use women in model-based collection imagery.
- Series-banner imagery for Anime / Original Animated Series should not include a human model or T-shirt when the image is functioning as the series banner.
- Men's collection imagery should not use the District M framing/design treatment.
- For DTF artwork, maintain safe margins and avoid fragile thin corners and thin typography.

## Recovery Workflow

When another original project attachment, Drive source, or historical MD file is surfaced:

1. Store the original readable file unchanged wherever possible.
2. Preserve the original filename where practical.
3. If the original is binary and is not being committed, archive an explicitly labeled readable extraction plus provenance rather than pretending it is the binary original.
4. Add date/time, source date, fabric, garment type, colors, prompt/version notes, and production constraints to the matching collection record.
5. Update this index to `Original recovered`, `Canonical in repo`, or the most accurate recovery state.
6. Retain reconstructed records as provenance unless they are exact duplicates and their history is already preserved in Git.
7. Never expose private connector IDs, private storage URLs, credentials, or confidential supplier information in this public repository.
