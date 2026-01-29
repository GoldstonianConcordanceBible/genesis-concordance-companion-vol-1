# Genesis — Concordance Companion (Vol. 1)

This repository is the **companion layer** for *Genesis* using the **Goldstonian Spine** (Purpose Thesis → Narrative Flow → Core Theology → Messiah Thread → Cross-Links → Hard Questions → Preacher’s Toolkit → Walking Rule).

It is designed to be:
- **Preacher-ready**
- **Everyday-reader-ready**
- **Machine-friendly** (schemas + CSV templates + controlled vocabulary)
- **DOI-ready** (release bundle standard for Zenodo/Figshare/Dataverse)

## What’s inside
- `spine/` — the reusable standards (Spine Spec + Cross-linking/Citation rules)
- `companion/` — Genesis companion manuscript + Genesis-specific preacher toolkit
- `vocab/` — controlled vocabulary + keywords used for discovery and indexing
- `data/` — crosswalk CSV + evidence index CSV (starter rows included)
- `schemas/` — JSON schemas so tools/agents can validate your data
- `release/` — release bundle rules + checksums

## Recommended workflow
1. Edit `companion/GENESIS-CONCORDANCE-COMPANION.md`
2. Update/extend `vocab/controlled-vocabulary.csv`
3. Add cross-links in `data/crosswalks/genesis-crosswalk.csv`
4. Add proof artifacts in `data/evidence/evidence-index.csv`
5. Cut a GitHub Release (e.g., `v0.1.0`) and export a “release bundle” ZIP per `release/RELEASE-BUNDLE.md`

## Versioning
See `CHANGELOG.md`. Use semantic versioning:
- `0.x` = drafts evolving
- `1.0.0` = stable public standard + companion release

## License
CC BY 4.0 (see LICENSE).
