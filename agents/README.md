# Divine Companion Agents (Standard Pack)

These agents are a reusable system that ships with every Goldstonian book companion repo.
They produce consistent outputs aligned to the Goldstonian Spine:

Purpose Thesis → Narrative Flow → Core Theology → Messiah Thread → Cross-Links → Hard Questions → Preacher’s Toolkit → Walking Rule

## How to use
1) Pick a passage range (or whole-book scope).
2) Run Agent 01 first (Spine Architect) to establish structure and tags.
3) Run Agents 02–07 to fill modules.
4) Run Agent 08 to package a DOI-ready release bundle.
5) Run Agent 09 to verify quality + consistency.

## Output locations
- companion/ (main manuscript sections)
- vocab/ (controlled vocabulary, keywords)
- data/crosswalks/ (cross-links dataset)
- data/evidence/ (evidence index)
- release/ (bundle rules + checksums)

v0.1
# Divine Companion Agents — Genesis Pack (Fully Populated)

This agent pack ships with the Genesis Concordance Companion repo and is reusable across all books.

It outputs:
- companion/GENESIS-CONCORDANCE-COMPANION.md
- companion/PREACHER-TOOLKIT-GENESIS.md
- vocab/controlled-vocabulary.csv (50 terms)
- vocab/keywords.yml
- data/crosswalks/genesis-crosswalk.csv (50 crosslinks)
- data/evidence/evidence-index.csv
- release/RELEASE-BUNDLE.md
- quality/QA-REPORT.md

Run order (if you were generating from scratch):
01 Spine Architect → 07 Messiah Thread → 02 Crosslinks → 03 Vocab → 04 Hard Questions → 05 Preacher → 06 Walking Rule → 08 Release → 09 QA

But for Genesis: everything is already populated.