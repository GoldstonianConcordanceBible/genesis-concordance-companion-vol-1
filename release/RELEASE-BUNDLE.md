# Release Bundle Standard — Genesis (DOI-ready)

## Bundle name
genesis-concordance-companion-vol-1_v0.1.0_release-bundle.zip

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

## Checksums (Mac)
Run these from repo root:
- shasum -a 256 README.md >> release/checksums.txt
Repeat for each file above (or write a small script later).

## GitHub → Zenodo workflow
1) Commit everything.
2) Create a Git tag: v0.1.0
3) Create a GitHub Release for v0.1.0
4) Zenodo (connected to GitHub) will mint:
   - a version DOI (for v0.1.0)
   - a concept DOI (stable across versions)

## Figshare mirror
Upload the same ZIP as an Item in your “Genesis Companion” collection.
Include:
- Title: Genesis — Concordance Companion (Vol. 1) — Release Bundle v0.1.0
- Keywords: use vocab/keywords.yml
- Link back to the Zenodo DOI and GitHub Release page

## Metadata snippet (paste-friendly)
Title: Genesis — Concordance Companion (Vol. 1)
Description: Spine-based companion for Genesis including manuscript, preacher toolkit, controlled vocabulary, and canon crosswalk dataset (50 links). DOI-ready release bundle for reproducible citation and indexing.
Keywords: Genesis; Bible study; covenant; seed promise; Abrahamic covenant; image of God; providence; Joseph; discipleship; biblical theology
Version: 0.1.0
License: CC BY 4.0