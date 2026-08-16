# VECTOR Project

## Overview

This repository is the **public constitutional / governance / orientation surface** for the VECTOR research portfolio. It publishes architecture, plane law, authority navigation, and reading posture.

It is **not**:

- the AI_Lab implementation repository
- a runtime repository
- the location of Stage 3–5 implementation code, fixtures, tests, scripts, or validation artifacts
- an operational system, production deployment, or execution surface

This repository **does not execute tools**. Publication does not authorize implementation, execution, deployment, or bridge activation.

The research goal is **not** to improve general model performance. The program studies how to:

- prevent critical failures under degraded conditions
- keep governance claims bounded when observations are unreliable

## What lives here vs elsewhere

| Surface | Role |
| --- | --- |
| **This repository** (`vector-runtime-governance-public`) | Public constitutional documents, governance orientation, and published architectural snapshots |
| **Separate engineering / research workspace** | Implementation, validation campaigns, fixtures, contract tests, analysis scripts, and Stage 3–5 engineering evidence |
| **[vector-signal-chronicle](https://github.com/chrono-vector/vector-signal-chronicle)** | Curated external observation / signal chronicle (observation only) |
| **[weaver-forge](https://github.com/chrono-vector/weaver-forge)** | Independent community receipt / witness surface (not VECTOR runtime authority) |

Implementation and research evidence live in a **separate engineering workspace / repository**. This public repository does **not** contain those files and must not be read as if they were local here.

**Public visibility does not change document authority.** Linked public repositories are research and documentation surfaces — not claims of complete production systems.

Publication and workspace boundaries (descriptive): [`REPOSITORY_ROLE.md`](REPOSITORY_ROLE.md).

### Internal research and preservation (not public code)

These are **not** this repository and are **not** published as local paths here.

| Workspace | Role |
| --- | --- |
| **AI_Lab** | Private research, implementation, and validation workspace |
| **external_research_archive** | Local preservation-only / untrusted archive; **not** a GitHub repository |
| **job-agent** | Private active-development application |

## Start here (documents that exist in this repository)

| Document | Why |
| --- | --- |
| [`REPOSITORY_ROLE.md`](REPOSITORY_ROLE.md) | This repository’s public role; publication vs private/local workspace boundary |
| [`notes/04 VECTOR/VECTOR_ECOSYSTEM_REPOSITORY_AUTHORITY_INDEX.md`](notes/04%20VECTOR/VECTOR_ECOSYSTEM_REPOSITORY_AUTHORITY_INDEX.md) | Cross-repo responsibility map (navigation only; no new authority) |
| [`notes/04 VECTOR/VECTOR_CONSTITUTION_MULTI_PLANE_ARCHITECTURE.md`](notes/04%20VECTOR/VECTOR_CONSTITUTION_MULTI_PLANE_ARCHITECTURE.md) | Sole L0a constitutional frame (plane law) |
| [`notes/04 VECTOR/VECTOR_CONSTITUTION_SUPPLEMENT_001_AUTHORITY_BOUNDARIES.md`](notes/04%20VECTOR/VECTOR_CONSTITUTION_SUPPLEMENT_001_AUTHORITY_BOUNDARIES.md) | Sole L0a boundary clarification under the Constitution |
| [`notes/04 VECTOR/VECTOR_2_0_BLUEPRINT.md`](notes/04%20VECTOR/VECTOR_2_0_BLUEPRINT.md) | Architecture orientation guide |

**Authority order (unchanged):** Constitution → Supplement → Blueprint take precedence over repository role and indexes. This README is an entry point only. It introduces **no new authority**.

## Naming collision — two different “Stage 5-B” labels

These are **different tracks**. Shared numbering is not shared architecture or authority.

| Label | Meaning | Where it lives |
| --- | --- | --- |
| **AI_Lab Stage 5-B** | Validation corpus / validation campaign | Engineering workspace (not this repository) |
| **Constitutional Stage 5-B** | External Signal Observer Architecture — vocabulary and architecture boundary; **no ingestion or execution authority** | This repository: [`STAGE5B_EXTERNAL_SIGNAL_OBSERVER_ARCHITECTURE.md`](notes/04%20VECTOR/STAGE5B_EXTERNAL_SIGNAL_OBSERVER_ARCHITECTURE.md) |

Do not read Constitutional Stage 5-B as campaign closure. Do not read AI_Lab Stage 5-B as this repository’s architecture note.

## Explicit non-claims (read first)

This repository **does not** claim:

- **External observation does not directly authorize execution.**
- **Execution Control Bridge is not activated.**
- **This repository does not execute tools.**
- **Gate ≠ Execution.** A gate decision (ALLOW / THROTTLE / BLOCK) is eligibility posture. It does not itself perform the action.
- **Production readiness is not claimed.**
- **Stage 5 overall is not complete** and is **not claimed complete**.
- Constitutional documentation in this repository is **not** engineering implementation in AI_Lab.
- Stage 4 published notes here are **documentation / reading-posture snapshots**. They are not runtime enforcement and do not supersede Stage 3 freeze authority.

## Conservative stage orientation

This table is **orientation only**. Constitutional documentation and engineering implementation are **separate**. Presence of a published note here does **not** mean the corresponding engineering track is complete, fielded, or located in this repository.

| Stage / track | In this public repository | Engineering implementation (separate workspace) |
| --- | --- | --- |
| **Stage 3** | Cited as L0b freeze / deterministic replay **authority class** in constitutional notes. Implementation, fixtures, matrix runners, and CI workflows are **not** in this repository. | Frozen replay/validation reference lives in the engineering workspace. |
| **Stage 4** | Published freeze, closure, validation-series, extension-map, and PR-preparation **notes** (historical documentation snapshots). | Exploratory runtime governance and `runtime_replay_bridge` MVP live in the engineering workspace. That MVP is **not** the External Execution Control Bridge. |
| **Constitutional Stage 5-B** | External Signal Observer Architecture note exists (vocabulary / plane boundary). | Does **not** ingest signals or authorize execution. |
| **AI_Lab Stage 5-B** | **Not published as implementation here.** | Validation corpus / campaign track in the engineering workspace. |
| **Stage 5 overall** | **Not claimed complete.** | **Not claimed complete.** |

Stage 4 notes in this repository may **cite** engineering paths (scripts, artifacts, branches) that exist only in the separate workspace. Those citations are historical/architectural references. They are **not** local files in this public repository.

## Documents published in this repository

Only the following notes are present under `notes/04 VECTOR/` in this public clone. Links below are local to this repository.

### Constitutional / orientation

- [`VECTOR_CONSTITUTION_MULTI_PLANE_ARCHITECTURE.md`](notes/04%20VECTOR/VECTOR_CONSTITUTION_MULTI_PLANE_ARCHITECTURE.md)
- [`VECTOR_CONSTITUTION_SUPPLEMENT_001_AUTHORITY_BOUNDARIES.md`](notes/04%20VECTOR/VECTOR_CONSTITUTION_SUPPLEMENT_001_AUTHORITY_BOUNDARIES.md)
- [`VECTOR_2_0_BLUEPRINT.md`](notes/04%20VECTOR/VECTOR_2_0_BLUEPRINT.md)
- [`VECTOR_ECOSYSTEM_REPOSITORY_AUTHORITY_INDEX.md`](notes/04%20VECTOR/VECTOR_ECOSYSTEM_REPOSITORY_AUTHORITY_INDEX.md)

### Constitutional Stage 5-B (External Signal Observer Architecture)

- [`STAGE5B_EXTERNAL_SIGNAL_OBSERVER_ARCHITECTURE.md`](notes/04%20VECTOR/STAGE5B_EXTERNAL_SIGNAL_OBSERVER_ARCHITECTURE.md)

This note is a **bridge-layer vocabulary and plane-separation document**. It does **not** authorize implementation, ingestion, bridge activation, or runtime wiring.

### Stage 4 published snapshots (documentation / reading posture)

These are **historical documentation snapshots** published for orientation. They are not runtime code and not a claim that Stage 4 engineering artifacts live here.

- [`STAGE4_RUNTIME_GOVERNANCE_FREEZE.md`](notes/04%20VECTOR/STAGE4_RUNTIME_GOVERNANCE_FREEZE.md)
- [`STAGE4_CLOSURE_NOTE.md`](notes/04%20VECTOR/STAGE4_CLOSURE_NOTE.md)
- [`STAGE4_VALIDATION_SERIES_COMPLETION_NOTE.md`](notes/04%20VECTOR/STAGE4_VALIDATION_SERIES_COMPLETION_NOTE.md)
- [`STAGE4_FUTURE_EXTENSION_MAP.md`](notes/04%20VECTOR/STAGE4_FUTURE_EXTENSION_MAP.md)
- [`STAGE4_PR_PREPARATION_NOTE.md`](notes/04%20VECTOR/STAGE4_PR_PREPARATION_NOTE.md)

Stage 4 closure in those notes is a **documentation / validation milestone** on an exploratory branch. It is **not** operational authorization, merge approval, production readiness, or supersession of Stage 3.

## What this repository does not contain

This public repository does **not** contain:

- Stage 3–5 implementation code (`core/`, `governance/`, `stage5_a/`, `stage5_b/`, and related trees)
- validation artifact trees
- pytest suites
- regression matrix runners or contract-validator scripts
- GitHub Actions workflows
- evaluation harness scripts or `reports/` outputs
- local Windows filesystem paths as documentation links

If a published note mentions such paths, treat them as **references to the separate engineering workspace**, not as files in this clone.

## Design principle

The VECTOR ecosystem intentionally separates:

- Research
- Publication
- Observation
- Execution

This repository is the **publication / constitutional** surface. It does not collapse those boundaries.

---

**Status:** public constitutional / governance orientation only. Not production. Not runtime. Not Stage 5 overall completion. Execution Control Bridge not activated. Gate ≠ Execution.
