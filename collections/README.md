# EQ1 Collections Taxonomy

Canonical collection structure for EQ1.

- Recorded: 2026-09-06 17:18 PKT
- Last updated: 2026-09-10
- Status: Active / evolving
- Seasonal production references are stored separately by season, e.g. `../winter-2026/`.
- Collection folders below are scaffolds or active records. Fabric, garment type, approved colors, prompts, revisions, production constraints, metadata, and final references are added as each collection is recovered or developed.

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
│   ├── Women Tshirts
│   │   └── Ravaani 220
│   ├── Sweatshirts
│   │   └── Rare Form
│   └── Tracksuits
│       └── Winter 2026 Development [WIP]
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
- `collections/women/sweatshirts/rare-form/`
- `collections/women/tracksuits/`
- `collections/galleries/collection-banners/`

## Shared collection rules

District M shared rules recovered from project history are maintained at:

- `district-m/README.md`

Collection-specific source files always take precedence over shared rules.

## Seasonal references

Winter 2026 base fabric colors are recorded at:

- `../winter-2026/base-fabric-colors.md`

## Templates

New and reconstructed collection records should use:

- `../templates/collection-record-template.md`

The repository template is a new canonical structure and is not represented as a byte-identical copy of any unavailable historical attachment.

## Recovered historical source archive

Collection-development sources recovered from older EQ1 storage are preserved separately at:

- `../archive/recovered/`

This archive currently includes historical EQ1 tracksuit specifications and the first-10 men's T-shirt production packet / structured metadata. Archived source material should not silently override current collection specifications.
