# GCB Canon Core (SydTek University)

Contract Address (pump.fun):
`E68E27Y72FHTJH1MycB6KjX5PQAyKPYsRGZjMEx9pump`

## Purpose
This repository is the canonical, versioned “core layer” for the Goldstonian Concordance Bible (GCB).
It provides stable artifacts and schemas so AI agents can behave consistently across forks:

- Canon index (machine-readable)
- Doctrine (tiebreak authority)
- Interpretive rules (how agents must reason)
- Glossary (controlled vocabulary)
- Safety guardrails (canonical constraints)
- Schemas for validation and governance change objects
- DOI-ready hooks for Zenodo releases

## Non-Investment Notice
Token references are for documentation, provenance, participation, and open-source contribution workflows only.
Nothing here is financial advice, an offer, a solicitation, or a promise of profit.

## Fork-Safe Provenance Requirements
Forks/derivatives must retain:
- NOTICE
- CITATION.cff
- INSTITUTIONAL_AFFILIATION_STATEMENT.md
- ONCHAIN_METADATA.md
- `canon/CANON_INDEX.json`

## Quick Start (Agents)
1) Load canon index: `canon/CANON_INDEX.json`
2) Load doctrine: `canon/DOCTRINE.md`
3) Apply interpretive rules: `canon/INTERPRETIVE_RULES.md`
4) Lock definitions: `canon/GLOSSARY.md`
5) Enforce constraints: `canon/SAFETY_GUARDRAILS.md`
6) Validate outputs with `schemas/*`

## Versioning
Semantic versioning is defined in `canon/VERSION.md`.

Canonical root for the ecosystem:
- https://github.com/GoldstonianConcordanceBible/gcb-canon-core