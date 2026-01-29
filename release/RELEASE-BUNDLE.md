# Release Bundle Standard (DOI-ready)

## Goal
Every GitHub Release should produce a single ZIP you can upload to Zenodo/Figshare/Dataverse.

## Bundle name
genesis-concordance-companion-vol-1_vX.Y.Z_release-bundle.zip

## Include these files
- README.md
- CHANGELOG.md
- CITATION.cff
- spine/GOLDSTONIAN-SPINE-SPEC.md
- spine/CROSS-LINKING-AND-CITATION.md
- companion/GENESIS-CONCORDANCE-COMPANION.md
- companion/PREACHER-TOOLKIT-GENESIS.md
- vocab/controlled-vocabulary.csv
- vocab/keywords.yml
- data/crosswalks/genesis-crosswalk.csv
- data/evidence/evidence-index.csv
- schemas/crosslink.schema.json
- schemas/evidence-index.schema.json
- release/checksums.txt

## Checksums
Generate SHA256 checksums for all included files and save to `release/checksums.txt`.
(Mac) `shasum -a 256 <file>` or use `openssl dgst -sha256 <file>`.

## DOI workflow
1. Tag release in GitHub (v0.1.0)
2. If Zenodo is connected to the repo, Zenodo mints a DOI
3. Upload the same ZIP to Figshare (optional mirror)