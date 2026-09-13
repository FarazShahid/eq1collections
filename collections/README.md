# EQ1 Collections Taxonomy

Canonical collection structure for EQ1.

- Recorded: 2026-09-06 17:18 PKT
- Last updated: 2026-09-13
- Status: Active / evolving
- Seasonal production references are stored separately by season, e.g. `../winter-2026/`.
- Collection folders below are scaffolds, active records, or preserved development branches. Collection-specific source files take precedence over generic hub rules.

```text
Collections
├── District M [Hub]
│   ├── Anime
│   │   ├── Attack on Titan
│   │   ├── Black Clover
│   │   ├── Bleach
│   │   ├── Blue Lock
│   │   ├── Chainsaw Man
│   │   ├── Dan Da Dan
│   │   ├── Death Note
│   │   ├── Demon Slayer
│   │   ├── Dragon Ball
│   │   ├── Hunter x Hunter
│   │   ├── Jujutsu Kaisen
│   │   ├── My Hero Academia
│   │   ├── Naruto
│   │   ├── One Piece
│   │   ├── Solo Leveling
│   │   ├── Spy x Family
│   │   └── Vinland Saga
│   ├── K-pop Music
│   └── Original Series
│       ├── Arcane
│       ├── Avatar The Last Airbender
│       ├── Blood of Zeus
│       ├── Blue Eye Samurai
│       ├── Castlevania
│       ├── Castlevania Nocturne
│       ├── Cyberpunk Edgerunners
│       ├── Devil May Cry
│       ├── Invincible
│       └── The Legend of Korra
├── Men [Hub]
│   └── T-shirts
│       ├── KING ENERGY
│       ├── LANDMARKS
│       ├── POWERLINE
│       └── The Runtime
├── Women [Hub]
│   ├── Women T-shirts / Long T-shirts
│   │   ├── Ravaani 220
│   │   └── The Line
│   ├── Sweatshirts
│   │   ├── Rare Form
│   │   └── Winter Bloom 280 [versioned development record]
│   └── Tracksuits
│       ├── MOVE DIFFERENTLY
│       └── Winter 2026 Development [historical WIP]
└── Galleries
    ├── Collection Banners
    └── K-POP ICONS — GLOBAL SIGNAL
```

## Repository path convention

Display names remain as approved collection names. Repository folders use lowercase kebab-case for stable paths and easier tooling.

Examples:

- `collections/district-m/anime/attack-on-titan/`
- `collections/district-m/original-series/cyberpunk-edgerunners/`
- `collections/men/t-shirts/the-runtime/`
- `collections/women/women-tshirts/ravaani-220/`
- `collections/women/women-tshirts/the-line/`
- `collections/women/sweatshirts/rare-form/`
- `collections/women/sweatshirts/winter-bloom/`
- `collections/women/tracksuits/move-differently/`
- `collections/galleries/collection-banners/`

## Source-history rule

When multiple source files exist for one collection, preserve version history rather than silently merging conflicts. This is especially important for **Winter Bloom 280**, whose supplied V3 and V4 files define different fabrics and product systems.

## Shared collection rules

District M shared rules recovered from project history are maintained at `district-m/README.md`. Collection-specific source files always take precedence over shared rules.

## Seasonal references

Winter 2026 base fabric colors are recorded at `../winter-2026/base-fabric-colors.md`.

## Templates

Two templates now serve different purposes:

- `../templates/eq1-studio-collection-creator-template.v1 (1).md` — **exact recovered Collection Studio generation template**.
- `../templates/collection-record-template.md` — repository-native metadata / provenance record template created during recovery.

The recovered Studio template controls the standard one-or-three image generation structure. The repository-native template is useful for archival metadata and production history; it should not be misrepresented as the original Studio template.

## Recovered historical source archive

Collection-development sources recovered from older EQ1 storage are preserved separately at `../archive/recovered/`. Archived material is evidence and reference and should not silently override later approved collection-specific files.
