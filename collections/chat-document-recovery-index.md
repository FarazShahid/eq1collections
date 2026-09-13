# EQ1 Collection Chat Document Recovery Index

- Recorded: 2026-09-10
- Last updated: 2026-09-13
- Purpose: Track collection documents recovered from EQ1 project history and show which original source files remain pending.
- Rule: Do not invent missing collection specifications. Preserve conflicting versions as version history rather than silently reconciling them.

## Recovery Status Legend

- **Exact original in repo** — original readable source committed unchanged and verifiable by blob hash.
- **Original supplied + structured record** — original source was supplied and substantive content/checksum was recovered into a collection record; full source file can later be byte-mirrored and verified.
- **Canonical in repo** — active structured working collection record / prompt is present.
- **Reconstructed from project chat** — useful specification rebuilt from explicit project decisions; exact original attachment unavailable.
- **Partial + source evidence** — historical evidence confirms development, but full specification is not recovered.
- **Scaffold only** — taxonomy folder exists without a reliable detailed source.

## Recovered / Recorded Collections

| Collection | Repository record | Recovery status | Source / evidence |
|---|---|---|---|
| Chainsaw Man | `district-m/anime/chainsaw-man/` | Reconstructed + source assets | 2026-07 design conversation + retained artwork |
| Death Note | `district-m/anime/death-note/collection-record.md` | Partial + source evidence | Historical named design / generated-artwork folders |
| Demon Slayer | `district-m/anime/demon-slayer/collection-record.md` | Partial + source evidence | Historical `ONI` collection/design evidence |
| Jujutsu Kaisen | `district-m/anime/jujutsu-kaisen/` | Reconstructed + source evidence | Design conversation + retained Sukuna evidence |
| One Piece | `district-m/anime/one-piece/` | Reconstructed + exact prompt fragment | `EQ1 MASTER PROMPT — ONE PIECE COLLECTION` fragment |
| Arcane | `district-m/original-series/arcane/collection-record.md` | Partial + source evidence | Retained Arcane generation assets |
| KING ENERGY | `men/t-shirts/king-energy/README.md` | Partial reconstructed identity | Recovered via The Runtime project source |
| LANDMARKS | `men/t-shirts/landmarks/` | Reconstructed + exact brief fragment | Known original file still pending |
| The Runtime | `men/t-shirts/the-runtime/` | Reconstructed + exact prompt fragment | Known original file still pending |
| Ravaani 220 | `women/women-tshirts/ravaani-220/` | Canonical + original supplied | `EQ1_Women_Ravaani_220_12_Designs.md` supplied 2026-09-13 |
| The Line | `women/women-tshirts/the-line/README.md` | Original supplied + structured record | `EQ1_Women_The_Line_20_Designs_Regenerated.md` |
| Rare Form | `women/sweatshirts/rare-form/README.md` | Original V4 + V5 supplied; record upgraded | `EQ1_Women_Rare_Form_280_Cotton_Jersey_6_Designs_V4.md`, `EQ1_Women_Rare_Form_Collection_Studio_V5.md` |
| Winter Bloom 280 | `women/sweatshirts/winter-bloom/README.md` | Versioned development record | V3 Cotton Jersey branch + V4 Cotton Fleece branch both supplied |
| MOVE DIFFERENTLY | `women/tracksuits/move-differently/README.md` | Original supplied + structured record | `EQ1_Womens_Tracksuit_Move_Differently_20_Designs.md` |
| Winter 2026 Women's Tracksuits WIP | `women/tracksuits/winter-2026-development.md` | Historical WIP | Now linked to MOVE DIFFERENTLY source |
| Collection Banners | `galleries/collection-banners/README.md` | Reconstructed from project chat | Series-banner direction |

## Exact Template Recovery

The previously missing Collection Studio source template has now been recovered **exactly**:

- `../templates/eq1-studio-collection-creator-template.v1 (1).md`
- Git blob SHA-1: `1452d41ea5d677273ceacd10a8132229cc888523`
- SHA-256: `a7b8a9e212fdc415ad454176701a4854f552637d00bf7387addd2823ceea24ff`

The repository-native `../templates/collection-record-template.md` remains a separate metadata/provenance template. The recovered Studio template is the canonical source for the EQ1 V4 Design Bible / one-or-three-image generation structure.

## 2026-09-13 Women Source Recovery

Original project files supplied in this pass:

- `EQ1_Womens_Tracksuit_Move_Differently_20_Designs.md`
- `EQ1_Women_Rare_Form_Collection_Studio_V5.md`
- `EQ1_Women_Rare_Form_280_Cotton_Jersey_6_Designs_V4.md`
- `EQ1_Women_Winter_Bloom_280_Cotton_Jersey_6_Designs_V3.md`
- `EQ1_Women_Winter_Bloom_280_6_Designs_V4.md`
- `eq1-studio-collection-creator-template.v1 (1).md`
- `EQ1_Women_Ravaani_220_12_Designs.md`
- `EQ1_Women_The_Line_20_Designs_Regenerated.md`

Checksums and file sizes are preserved in `../archive/recovered/source-manifest.md`.

### What these sources resolve

**Ravaani 220:** validates the existing 12-design collection bible, full three-output system, long-T-shirt identity, colors, belt variants, model direction, and rainy Lahore campaign system.

**The Line:** adds a previously missing 20-design women’s long-T-shirt collection using Pistachio Green, Bubble Pink, Black, Microsoft Blue, and Gray, with monochrome, contrast, slit, shaped, and belted soft-form variants.

**Rare Form:** resolves previously missing production fields: 280 GSM Cotton Jersey, exact six-color sleeve matrix, six hero motifs, cuff-to-elbow embroidery limits, raglan language, Lahore-after-rain campaign, and three-output system.

**Winter Bloom 280:** reveals two conflicting development branches. V3 is the predecessor contrast-sleeve cotton-jersey system later locked as Rare Form; V4 is a separate 280 GSM Cotton Fleece, four-color, construction-led six-design branch with a working/proposed name. Both are preserved without forced reconciliation.

**MOVE DIFFERENTLY:** resolves the women’s tracksuit WIP into a named 20-design collection with four top silhouette families, explicit EQ1 placements, per-design color-blocking/rails, recorded fabric/GSM references where known, and a three-output system.

## Recovered Historical / Production Sources

Historical material that does not map cleanly to one current named collection remains under `../archive/recovered/`.

### Historical EQ1 Tracksuits — June 2026

Exact readable specification exists for Formal Tracksuits `FTS01–FTS06` and Casual Tracksuits `CTS01–CTS06`, covering Interlock 240–280 GSM, SHY fabric, Scuba, cotton-poly light fleece, woven fabrics, and per-style color/construction direction.

### Historical EQ1 Men's T-shirts

- T01–T10: master packet readable extraction + exact style metadata + individual packet extractions.
- T15–T20: exact companion README/index and `T##_Info.txt` text.
- T11–T14: source still not found and intentionally not inferred.

## Collection Folders Still Awaiting Detailed Source Recovery

### District M — Anime

Attack on Titan, Black Clover, Bleach, Blue Lock, Dan Da Dan, Dragon Ball, Hunter x Hunter, My Hero Academia, Naruto, Solo Leveling, Spy x Family, Vinland Saga.

### District M — K-pop Music

Detailed collection source not yet recovered.

### District M — Original Series

Avatar The Last Airbender, Blood of Zeus, Blue Eye Samurai, Castlevania, Castlevania Nocturne, Cyberpunk Edgerunners, Devil May Cry, Invincible, The Legend of Korra.

### Men — T-shirts

- POWERLINE — detailed source still pending.
- KING ENERGY — full standalone source still pending if one exists separately from The Runtime.

### Galleries

- K-POP ICONS — GLOBAL SIGNAL
- original complete Collection Banners file, if one exists beyond recovered direction

## Original Project Attachments Still Missing

The list of known-but-not-fully-recovered original collection attachments is now shorter:

- `EQ1_KING_ENERGY_THE_RUNTIME_V4_Concise_3_Output_Full_20_Designs.md`
- `EQ1_Mens_Landmarks_V4_Concise_3_Output.md`

`EQ1_Women_Ravaani_220_12_Designs.md` and `eq1-studio-collection-creator-template.v1 (1).md` were supplied on 2026-09-13 and are no longer missing.

## Recovery Workflow

1. Preserve original readable files unchanged wherever possible.
2. Preserve original filenames.
3. Record file size plus SHA-256 / Git blob SHA-1 when an original source is supplied.
4. If full source bytes are not yet mirrored, clearly label the repository record as a structured recovery rather than pretending it is byte-identical.
5. Keep conflicting versions as history until an explicit approval resolves them.
6. Update collection metadata, fabric, colors, prompts, production constraints, and source priority from the strongest available collection-specific source.
7. Never expose private connector IDs, credentials, supplier secrets, or private storage URLs in the public repository.
