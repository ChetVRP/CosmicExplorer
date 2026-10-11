# Changelog — Cosmic Explorer

All notable changes to the public website are recorded here. The single-file website in `index.html` remains the canonical executable release artifact.

## v0.23.0-rc.3 — 11 October 2026 (public release candidate)

**Base:** Original published v0.21.1 plus integrated local v0.22/v0.23 work.

### Added
- NASA/JPL-element-based inclined elliptical planetary orbit models and optional simplified/teaching view. Orbital speed changes with position; not a full N-body solution.
- Universal astronomical-object registry pilot, global search and wavelength-aware reference filtering.
- Right-hand **Data & Evidence** experience with **Explorer / Student / Research** reading depths and ChromaRead semantic cues.
- **Galaxy Structure Lab** in Local Group, Galaxy Clusters (Virgo, Fornax, Coma) and Superclusters & Flows: optional 3D structure layers, educational depth exaggeration, conceptual luminous tracers and guided exploration.
- Additional educational inspector content explaining selected large-scale structures and their observational limitations.

### Preserved
- All eight cosmic environments (Earth renamed from Earth Magnetic Field while retaining its magnetic field models).
- Existing WebGL2 rendering, Canvas 2D fallback, astronomical time, gravity visual modes, scientific reference links and available local survey import features.

### Known limitations
- The complete 2012+2019 2MRS galaxy-table acquisition/reconciliation is outstanding.
- The new GS animations and overlays are conceptual, not measured 3D galaxy motions, registered X-ray images or reconstructed physical velocities.
- Some astronomical coordinates, morphologies and distances remain approximations/educational models.
- RC3-specific real-hardware WebGL2 and full-device-performance verification are outstanding. Earlier versions were tested on an Android tablet.
- Individual preliminary registry/test fixtures do not constitute the entire astrophysical object catalogue.

### Technical validation performed before publication
- Single-file JavaScript syntax check and unique HTML ID check.
- Targeted scene/inspector browser checks on desktop/mobile in Canvas 2D fallback.
- Nine deterministic 3D geometry testing combinations for the new Galaxy Structure Lab.
- Scientific and technical test limits described in [release notes](./docs/RELEASE_v0.23.0-rc.3.md).

## v0.21.1 — 10 October 2026 (initial GitHub-hosted baseline)

- Initial publicly hosted Cosmic Explorer self-contained website.
- Eight-scale astronomical navigation, conceptual cosmic models, observational-source references, import tools, interactive controls and WebGL2/Canvas 2D fallback.
- Preserved as [archive/v0.21.1](../../tree/archive/v0.21.1).
