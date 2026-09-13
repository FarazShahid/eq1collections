# EQ1 Women — Winter Bloom 280

## Recovery Record

Two different Winter Bloom source branches were supplied on 2026-09-13. They contain materially different product systems and must be preserved as **versioned development history**, not silently merged.

### Source A — V3 Cotton Jersey Contrast-Sleeve Edition

- **Filename:** `EQ1_Women_Winter_Bloom_280_Cotton_Jersey_6_Designs_V3.md`
- **Size:** 22,323 bytes
- **SHA-256:** `06740ddf6b875ca31a1653a1cd54658317f392f37774e7c9aa265359b9718a62`
- **Git blob SHA-1:** `4ddd131fa2bd1a6ddd7b0e4d1650d3f8a5154b73`
- **Collection label:** Winter Bloom 280 — Cotton Jersey Edition
- **Fabric:** 280 GSM Cotton Jersey
- **Design count:** 6
- **Product system:** color-block / tonal full-sleeve sweatshirts with lower-sleeve embroidery

This branch uses the same six named design concepts later locked under Rare Form:

1. Fuchsia Nightwing
2. Tangerine Swan
3. Olive Seraph
4. Mustard Hummingbird
5. Black Crane Rose
6. Midnight Moth

Locked color logic in V3:

- Pink/Fuchsia → Black sleeves
- Orange → Silver/Light Grey sleeves
- Green/Muted Olive → Silver/Light Grey sleeves
- Yellow/Mustard → Black sleeves
- Black → Black tonal sleeves only
- Blue/Deep Navy → Blue tonal sleeves only

Embroidery is limited strictly to cuff-to-elbow with one hero element appearing once across the garment: Butterfly, Swan, Archangel Wings, Hummingbird, Crane, or Moon Moth. The opposite sleeve carries botanical support.

### Source B — V4 Cotton Fleece Construction-Led Edition

- **Filename:** `EQ1_Women_Winter_Bloom_280_6_Designs_V4.md`
- **Size:** 63,083 bytes
- **SHA-256:** `166114114ec059d4d80e635b7f5c65b898bd78ab928ec0ed9e21b7257896a296`
- **Git blob SHA-1:** `668e9d8fdf8157642a67a8b543d5bd9b68323593`
- **Collection label:** Winter Bloom 280
- **Naming status in source:** explicitly described as a **working / proposed collection name**, not a previously approved collection name
- **Confirmed material in source:** 280 GSM Cotton Fleece
- **Design count:** 6
- **Product system:** monochrome sweatshirt bodies using four physical swatch colors with a distinct construction signature per design

V4 approved fabric colors:

- Fuchsia Pink
- Orange
- Golden Mustard
- Light Heather Grey

All six V4 garments are tonal / monochrome. The source explicitly rejects contrast-color sleeves, panels, rib, and linings for this branch.

### V4 Design Matrix

| # | Product | Fixed color | Signature construction | Proposed SKU root |
|---|---|---|---|---|
| 01 | Marigold — Rib Contour | Golden Mustard | Same-color rib side inserts; softly shaped regular fit | `EQ1-WB280-01-MUS` |
| 02 | Rosebud — Thumbhole | Fuchsia Pink | Long thumbhole cuffs; tonal side-seam topstitch | `EQ1-WB280-02-FUS` |
| 03 | Silver Stem — Arc Raglan | Light Heather Grey | Curved raglan seams with close tonal coverstitch | `EQ1-WB280-03-HGR` |
| 04 | Ember Petal — Tucked Sleeve | Orange | Controlled sleeve volume with two shallow cuff tucks | `EQ1-WB280-04-ORG` |
| 05 | Fuchsia Bloom — Cinch Hem | Fuchsia Pink | Adjustable self-fabric hem casing with two side cord locks | `EQ1-WB280-05-FUS` |
| 06 | Quiet Bloom — Step Hem | Light Heather Grey | Longer back hem, reinforced side vents, twin-needle finish | `EQ1-WB280-06-HGR` |

V4 also contains proposed medium-sample measurements and construction targets, including design-specific body lengths, rib dimensions, motif dimensions, thumb opening placement, tuck lengths, side-vent proportions, and drawcord/cord-lock details. The source explicitly labels these as **sampling proposals**, not a factory-ready graded pattern or confirmed production specification.

## Branding Shared Across the Winter Bloom Sources

- **EQ1** exactly
- wearer’s upper-left chest
- approximately 2.5 inches / 6.35 cm wide
- Rubik 600 / SemiBold uppercase direction
- no additional chest/back branding

V4 proposes matte-charcoal EQ1 embroidery and small connected botanical sleeve motifs. Its Image 3 rule is especially strict: construction only, no embroidery/logo/artwork, no collage.

## Important Version Conflict

V3 and V4 conflict on the core fabric and color-block system:

- **V3:** 280 GSM Cotton Jersey; contrast sleeves on four colors; Black/Blue tonal; hero embroidery system shared with what became Rare Form.
- **V4:** 280 GSM Cotton Fleece; four physical monochrome colors only; six different construction-led products; Winter Bloom name still marked as proposed.

Do not treat V4 as an automatic production replacement for V3 merely because the version number is higher. Preserve both and require explicit product approval before declaring a canonical Winter Bloom production specification.

## Relationship to Rare Form

The V3 Winter Bloom design system is effectively the predecessor to the later **Rare Form** source files. Rare Form explicitly locks the collection name and the 280 GSM cotton-jersey contrast/tonal system. Therefore:

- use **Rare Form** for the locked six-design Butterfly/Swan/Archangel/Hummingbird/Crane/Moon-Moth collection;
- retain Winter Bloom V3 as naming/development provenance;
- retain Winter Bloom V4 as a separate construction-led experimental branch unless it is explicitly revived and approved.

## Output / Model Direction in V4

V4 uses adult Pakistani female models with varied realistic proportions across designs, light-heather-grey styling trousers, white sneakers, and cool post-rain Lahore campaign environments with strong background-only motion blur. Product and construction images use neutral studio treatment.

## Repository Status

This directory is a **version-history / development record**. No single Winter Bloom version is marked production-canonical here without a later explicit approval.