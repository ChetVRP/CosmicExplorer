# Cosmic Explorer v0.23.0-rc.3 — Galaxy Structure Lab

**Release date:** 11 October 2026  
**Status:** Public release candidate — not v0.23.0 final  
**Author / compiler:** Chetan Ladwa  
**Website:** https://chetvrp.github.io/CosmicExplorer/  
**Published artifact:** `index.html` (standalone HTML)

## What's new

1. **Solar System orbital realism:** NASA/JPL-based elliptic orbits, planetary inclination and orientation, Keplerian phase progression; optional schematic/exaggerated views. Layout distances and visible planetary sizes are still educationally transformed.
2. **Object Atlas pilot:** accessible object search, category and observation reference filters and contextual relationships; pilot dataset is not a complete astronomical catalogue.
3. **Data & Evidence:** three language levels—Explorer, Student, Research—using ChromaRead-informed semantic colour with textual labels, distinguishing verified, previously published educational and unavailable measurements.
4. **Galaxy Structure Lab:** additional 3D structure cues for Local Group, clusters and superclusters; optional illustrative motion tracers, depth teaching controls, guided camera selection and expanded per-object explanations.
5. **Existing simulation preserved:** all original scenes, gravity fabric, physics demonstration, object controls and rendering fallbacks.

## Verification / release gates

- Local development build passed JavaScript syntax and HTML ID uniqueness checks.
- Focused Canvas 2D browser checks passed on desktop and mobile and checked contextual controls.
- New 3D overlay geometry: 9 deterministic tests passed (three scenes × three subjects).
- **Not yet confirmed:** active WebGL2 appearance and performance for the RC3 overlay on physical hardware, full accessibility audit and merged 2MRS scientific dataset.
- Users should choose *Graphics* and run on-device diagnostics where available.

## Scientific interpretation and data provenance

- New luminous structure, traces, flow paths, visual density and depth exaggeration are **clearly illustrative**, and should not be mistaken for galaxy sky measurements, physical velocities or observational X-ray maps.
- Real catalogue coordinates and their distance uncertainties should be kept separate from modelled 3D placement; no extra measurement precision is implied.
- Existing older inspector numbers may be approximate and heterogeneous. Do not use the website as a substitute for an astronomical database or trajectory prediction.
- The entire 2MASS Redshift Survey is **not embedded** in this build; a validated data pipeline and scientific reconciliation remain in progress.
- Reference material: NASA/JPL Solar System Dynamics; NASA/ESA Hubble observations; ESA Euclid; Chandra X-ray Observatory; Cosmicflows-4 literature, linked in the app and development documentation.

## Version control

- **Previous published version:** GitHub branch `archive/v0.21.1` anchored to commit `a35c79d6e64ebfaf06d885f7c609e7dab03dd266`.
- **This version:** `main` commit identified by GitHub commit history and the `release/v0.23.0-rc.3` branch if created after deployment.
- Formal GitHub tags and pre-release entry require separate creation through GitHub Releases when tooling supports them; do not confuse these branch references with tags.
