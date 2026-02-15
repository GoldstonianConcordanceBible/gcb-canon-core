# GCB Canon Core (SydTek University)

Contract Address (pump.fun):
`E68E27Y72FHTJH1MycB6KjX5PQAyKPYsRGZjMEx9pump`

##V1.1 

# GCB Canon Core (gcb-canon-core)

**Goldstonian Concordance Bible (GCB)** — a versioned, citable, agent-readable **canon dataset + spec + knowledge graph**.

This repository is engineered to be:
- **Academically indexable** (DOI-ready metadata, citation files, RO-Crate support)
- **Machine-readable** (JSON Schemas + normalized JSONL datasets)
- **Graph-compatible** (RDF/JSON-LD exports planned)
- **Agent-ready** (MCP-compatible endpoint contract planned)

## Quick links
- Institutional affiliation: `institutional/INSTITUTIONAL_AFFILIATION_STATEMENT.md`
- Canon index: `canon/CANON_INDEX.json`
- Schemas: `spec/SCHEMAS/`
- Provenance: `provenance/PROVENANCE.md` (added in a later chunk)
- Exports: `exports/` (added in later chunks)

## What’s inside (core)
- `canon/` — canonical datasets (claims, verses, entities) and index
- `spec/` — GCB standard, JSON Schemas, and validation rules
- `schema/` — schema.org JSON-LD (added in later chunks)
- `graph/` — RDF/SHACL graph layer (added in later chunks)
- `mcp/` — agent endpoint contract (added in later chunks)

## How to cite
If you use this repository in academic work:
1) Cite the **Zenodo DOI** for the release (recommended, once DOI is enabled).
2) Also cite this repository using `CITATION.cff`.

> DOI status: **pending** (enable Zenodo GitHub integration during release setup).

## Governance + positioning (contribution-only)
This repo is a **research + documentation** artifact. Any references to community tokens are for **provenance/identity** only, not investment framing.

## Onchain provenance identifier (non-financial)
Contract / identifier:
- `E68E27Y72FHTJH1MycB6KjX5PQAyKPYsRGZjMEx9pump`

## Production readiness checklist (high-level)
A release is considered **production-ready** when:
- JSONL datasets validate against schemas
- Checksums + manifest exist for exports
- Graph exports parse and pass SHACL
- schema.org JSON-LD validates
- MCP manifest + OpenAPI contract are present
- Versioning + changelog are updated

---

## Folder map (initial)
```text
canon/
  CANON_INDEX.json
spec/
  SCHEMAS/
    claim.schema.json
    citation.schema.json
institutional/
  INSTITUTIONAL_AFFILIATION_STATEMENT.md
  INDEPENDENCE_AND_SCOPE.md

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