# Cosmic Explorer

**Interactive astronomy laboratory — v0.24 Pass 24.6B (Guided Scene Journeys)**

Authored and compiled by **Chetan Ladwa**.

**Live website:** https://chetvrp.github.io/CosmicExplorer/

**Current release status:** Public development preview of v0.24 Pass 24.6B; not a fully validated stable release. The previous v0.23.0-rc.3 is preserved at `archive/v0.23.0-rc.3-pre-24.6b`. Full 2MRS ingestion, scientific reconciliation, native WebGL2, device and accessibility checks remain open.

## New in v0.24 Pass 24.6B

- Guided discovery tours in the eight astronomical environments: Next, Previous, Play/Pause, route progress and return-to-start.
- Integrated searchable Cosmic Hierarchy and relationship-aware ChromaRead contextual inspector from Pass 24.6.
- Research-only / illustrative objects remain distinguished from true 3D camera destinations. Cross-scale transitions are labelled context changes, not literal measured flights.
- 11 curated tour routes with 85 stop instances, the first integrated implementation of the larger Pass 24.6A proposed 23-preset journey plan.

## Explore

The complete browser app lives in [index.html](./index.html), supports WebGL2 with a Canvas 2D fallback, and can also be saved and opened offline in supported browsers. It retains the eight scenes: Cosmic Web; Superclusters & Flows; Galaxy Clusters; Local Group; Milky Way; Heliosphere; Solar System; Earth.

Features incorporated across the v0.22–v0.23 development programme:

- Interactive astronomy objects, object search, selection, inspector and observational-source links.
- Planetary Keplerian orbit geometry based on JPL planetary elements, with teaching exaggeration distinctly labelled. Planet sizes and spacing in the overview remain compressed/enlarged for readability; these are not JPL Horizons ephemerides.
- Newtonian gravity demonstration and the previously available educational gravitational-fabric views.
- **Galaxy Structure Lab (RC3):** optional structure/depth overlays and conceptual motion tracers for Local Group, galaxy clusters and superclusters; guided camera exploration; richer ChromaRead-inspired explanations at Explorer, Student and Research depths.
- Contextual **Data & Evidence** inspector, distinguishing older educational figures from newly validated measurements or missing catalogue data.
- Offline self-contained HTML, responsive desktop/tablet/mobile design.

## Source integrity and scientific limitations

- The newer overlays are **educational illustrations**, not registered observations or measured galaxy velocity trajectories. The supercluster flow displays are model interpretations, not direct measurements.
- This build does **not** include the complete merged 2MRS observational catalogue. The planned source-data acquisition and reconciliation are pending.
- Some distances and galaxy features are approximate, compiled from heterogeneous sources, or reconstructed schematically; see the in-app inspector for individual reference links.
- Real-device WebGL2 **RC3-specific** verification and further accessibility/performance testing are pending. Earlier versions were verified on an Android tablet using WebGL2.
- No third-party asset redistribution licence is implied by publication of the repository.

## Version history

| Version | Reference | Description |
| --- | --- | --- |
| `v0.21.1` | [archive/v0.21.1](../../tree/archive/v0.21.1) | Original published baseline, preserved before update |
| `v0.23.0-rc.3` | `archive/v0.23.0-rc.3-pre-24.6b` | Previous published RC3 preserved before 24.6B update |
| `v0.24 Pass 24.6B` | `main` | Published development preview: hierarchy, ChromaRead context and guided scene journeys |
| `v0.23.0` | Planned | Final release after outstanding verification and catalogue decisions |

See [CHANGELOG.md](./CHANGELOG.md) and [the RC3 release record](./docs/RELEASE_v0.23.0-rc.3.md).

**Versioning policy:** `vMAJOR.MINOR.PATCH` for stable releases; `-rc.N` for release candidates. Git commits record every repository edit; named version references are maintained separately. GitHub branch `archive/v0.21.1` preserves the old version. A formal GitHub Release/tag for this RC can be added through the GitHub Releases UI.
