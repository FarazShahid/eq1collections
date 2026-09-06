# EQ1 Collections Taxonomy

Canonical collection structure for EQ1.

- Recorded: 2026-09-06 17:18 PKT
- Status: Active / evolving
- Seasonal production references are stored separately by season, e.g. `../winter-2026/`.
- Collection folders below are scaffolds. Fabric, garment type, approved colors, prompts, revisions, production constraints, metadata, and final references will be added as each collection is developed.

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
│   └── Women Tshirts
│       └── Ravaani 220
└── Galleries
    ├── Collection Banners
    └── K-POP ICONS — GLOBAL SIGNAL
```

## Repository path convention

Display names remain exactly as listed above. Repository folders use lowercase kebab-case for stable paths and easier tooling.

Examples:

- `collections/district-m/anime/attack-on-titan/`
- `collections/district-m/original-series/cyberpunk-edgerunners/`
- `collections/men/t-shirts/the-runtime/`
- `collections/women/women-tshirts/ravaani-220/`
- `collections/galleries/collection-banners/`

## Seasonal references

Winter 2026 base fabric colors are recorded at:

- `winter-2026/base-fabric-colors.md`
