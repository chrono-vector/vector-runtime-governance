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
| **[weaver-forge](https://github.com/chrono-vector/weaver-forge)** | Independent community receipt / witness surface **and** host of VECTOR Package Ingress v0 (read-only checking boundary; not VECTOR runtime authority, not Independent Witness, not Stage 6) |

Implementation and research evidence live in a **separate engineering workspace / repository**. This public repository does **not** contain those files and must not be read as if they were local here.

**Public visibility does not change document authority.** Linked public repositories are research and documentation surfaces — not claims of complete production systems.

Publication and workspace boundaries (descriptive): [`REPOSITORY_ROLE.md`](REPOSITORY_ROLE.md).

## Current VECTOR orientation (2026-08-20 path)

**VECTOR is a research reference architecture for keeping observation, interpretation, verification, replay, and execution from collapsing into each other, with a public read-only package boundary at Weaver Forge.**

This README is a **CURRENT_PUBLIC_ENTRY** for that orientation. It is **not** Public VECTOR v0, not a production product, and not a fully automated live pipeline. A sanitized public VECTOR operational release does **not** yet exist.

Human gates and cross-repository boundaries remain. Do not read the path below as one automatic system, as an execution engine for third parties, as Truth verification, as Evidence admission, or as Stage 6.

### High-level path (orientation only)

```text
External Sources
→ ERA                          (private preservation; not this repository)
→ IG-01
→ CAD                          (private satellite; not a public clone requirement)
→ IG-02
→ Human Promotion Gate
→ Observation Chronicle
→ IG-03
→ Core-01 Decision Process
→ IG-04 Decision Trace
→ IG-05-A Structural Verification
→ Core-02 Verification Result Registry
→ Core-03 Replay Contract
→ IG-05-C Replay Eligibility / Gate
→ optional Owner-authorized Core-05 Replay
→ Replay Result
→ Core-04 Weaver Handoff Control
→ Repository Owner Handoff Authorization
→ VECTOR Handoff Package v0
→ Weaver Forge VECTOR Package Ingress v0
→ deterministic Ingress Result
→ Human / Repository Owner Review
→ STOP
```

**IG-07** is human explanation / readout only. It does not increase authority.

Distinguish:

- **Callable edges** — structural checks; Weaver Forge ZIP-only Package Ingress v0
- **Human gates** — Chronicle promotion, replay authorization, handoff authorization, Ingress-result review
- **External repository boundaries** — ERA and CAD remain private; this repository publishes constitution / orientation; Chronicle records observation; Weaver Forge hosts the public read-only Ingress boundary

Operational sidecars (Core Pipeline Preflight, Multi-machine Portability, Registry Migration / Versioning, Operational Health, Backup Snapshot) live in the private engineering workspace. They are **not** published here and are **not** a third-party clone requirement.

Public read-only Ingress docs: [`VECTOR Package Ingress v0`](https://github.com/chrono-vector/weaver-forge/blob/main/external_verifications/vector-handoff/README.md) on Weaver Forge.

Source Weaver GPT is **not** a mandatory pipeline stage.

### Public nonclaims

```text
Observation ≠ Interpretation
Interpretation ≠ Verification
Verification ≠ Execution
Schema-valid ≠ True
Replayable ≠ Externally True
REPLAY_ELIGIBLE_BY_CONTRACT ≠ Replay Authorized
Ingress Ready ≠ Evidence Admitted
Ingress Ready ≠ Weaver Execution Authorized
Ingress Ready ≠ Independent Witness PASS
Ingress Ready ≠ Stage 6
External review ≠ constitutional authority
```

VECTOR is **not**:

- a production product
- a fully autonomous governance system
- AI governance as a service
- an execution engine for third parties
- a Truth verification system
- an Evidence admission system
- a Stage 6 system

### Document roles in this repository

| Surface | Public documentation role |
| --- | --- |
| This README / [`REPOSITORY_ROLE.md`](REPOSITORY_ROLE.md) | `CURRENT_PUBLIC_ENTRY` — current orientation, not an operational release |
| Constitution / Supplement / Blueprint | `CONSTITUTIONAL_HISTORICAL` — valuable plane law / orientation; **not** the 2026-08-20 running pipeline and **not** Weaver Ingress |
| Stage 4 notes | `CONSTITUTIONAL_HISTORICAL` — documentation / reading-posture snapshots |
| Constitutional Stage 5-B note | vocabulary / plane-boundary documentation; **not** ingestion or execution authority |
| Weaver Forge Ingress README | `CURRENT_PUBLIC_ENTRY` for the public VECTOR package boundary (hosted there, not here) |
| Chronicle `UNIFIED_VECTOR_ARCHITECTURE.md` | `CONSTITUTIONAL_HISTORICAL` — earlier two-repo map; not current operational architecture |
| Stage 3–5 research notes elsewhere | `HISTORICAL_RESEARCH` / frozen research lineage — not the current operational VECTOR v0 map |

### Internal research and preservation (not public code)

These are **not** this repository and are **not** published as local paths here.

| Workspace | Role |
| --- | --- |
| **AI_Lab** | Private research, implementation, and validation workspace |
| **CAD-Vortex** | Private Plane 2 intake satellite. **Not** a public clone requirement for this documentation repository |
| **external_research_archive** | Local preservation-only / untrusted archive; **not** a GitHub repository |
| **job-agent** | Private active-development application |

## Start here (documents that exist in this repository)

| Document | Why |
| --- | --- |
| [`REPOSITORY_ROLE.md`](REPOSITORY_ROLE.md) | This repository’s public role; publication vs private/local workspace boundary |
| [`notes/04 VECTOR/VECTOR_ECOSYSTEM_REPOSITORY_AUTHORITY_INDEX.md`](notes/04%20VECTOR/VECTOR_ECOSYSTEM_REPOSITORY_AUTHORITY_INDEX.md) | Cross-repo responsibility map (navigation only; no new authority) |
| [`notes/04 VECTOR/VECTOR_CONSTITUTION_MULTI_PLANE_ARCHITECTURE.md`](notes/04%20VECTOR/VECTOR_CONSTITUTION_MULTI_PLANE_ARCHITECTURE.md) | Sole L0a constitutional frame (plane law). `CONSTITUTIONAL_HISTORICAL` relative to the current implemented path; **not** Weaver Ingress |
| [`notes/04 VECTOR/VECTOR_CONSTITUTION_SUPPLEMENT_001_AUTHORITY_BOUNDARIES.md`](notes/04%20VECTOR/VECTOR_CONSTITUTION_SUPPLEMENT_001_AUTHORITY_BOUNDARIES.md) | Sole L0a boundary clarification under the Constitution. `CONSTITUTIONAL_HISTORICAL`; **not** the running pipeline |
| [`notes/04 VECTOR/VECTOR_2_0_BLUEPRINT.md`](notes/04%20VECTOR/VECTOR_2_0_BLUEPRINT.md) | Architecture orientation guide. `CONSTITUTIONAL_HISTORICAL`; **not** the 2026-08-20 implemented Ingress path |

**Authority order (unchanged):** Constitution → Supplement → Blueprint take precedence over repository role and indexes. This README is an entry point only. It introduces **no new authority**. Constitutional documents remain plane law; they are **not** a substitute for the current-path orientation above and are **not** Weaver Ingress.

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
- **Public VECTOR v0 is not a full operational release.**
- **Stage 6 is not entered.**
- See [Public nonclaims](#public-nonclaims) for the Observation ≠ Interpretation ≠ Verification ≠ Execution inequalities.

## Conservative stage orientation

This table is **orientation only**. Constitutional documentation and engineering implementation are **separate**. Presence of a published note here does **not** mean the corresponding engineering track is complete, fielded, or located in this repository.

| Stage / track | In this public repository | Engineering implementation (separate workspace) |
| --- | --- | --- |
| **Stage 3** | Cited as L0b freeze / deterministic replay **authority class** in constitutional notes. Implementation, fixtures, matrix runners, and CI workflows are **not** in this repository. | Frozen replay/validation reference lives in the engineering workspace. |
| **Stage 4** | Published freeze, closure, validation-series, extension-map, and PR-preparation **notes** (historical documentation snapshots). | Exploratory runtime governance and `runtime_replay_bridge` MVP live in the engineering workspace. That MVP is **not** the External Execution Control Bridge. |
| **Constitutional Stage 5-B** | External Signal Observer Architecture note exists (vocabulary / plane boundary). | Does **not** ingest signals or authorize execution. |
| **AI_Lab Stage 5-B** | **Not published as implementation here.** | Validation corpus / campaign track in the engineering workspace. Treat as `HISTORICAL_RESEARCH` relative to the current IG/Core/Ingress path. |
| **IG / Core / Weaver Ingress (2026-08-20)** | Orientation only (this README). Implementation, registries, and Owner packages are **not** in this repository. | Human-gated path in the private engineering workspace, with public ZIP-only Ingress on Weaver Forge. **Not** an automatic live pipeline. **Not** Public VECTOR v0. |
| **Stage 5 overall** | **Not claimed complete.** | **Not claimed complete.** |
| **Stage 6** | **Not entered. Not claimed.** | **Not entered. Not claimed.** |

Stage 4 notes in this repository may **cite** engineering paths (scripts, artifacts, branches) that exist only in the separate workspace. Those citations are historical/architectural references. They are **not** local files in this public repository.

## Documents published in this repository

Only the following notes are present under `notes/04 VECTOR/` in this public clone. Links below are local to this repository.

### Constitutional / orientation (`CONSTITUTIONAL_HISTORICAL`)

These remain constitutional / orientation documents. They are **not** the current implemented IG/Core/Weaver Ingress pipeline and **not** Public VECTOR v0.

- [`VECTOR_CONSTITUTION_MULTI_PLANE_ARCHITECTURE.md`](notes/04%20VECTOR/VECTOR_CONSTITUTION_MULTI_PLANE_ARCHITECTURE.md)
- [`VECTOR_CONSTITUTION_SUPPLEMENT_001_AUTHORITY_BOUNDARIES.md`](notes/04%20VECTOR/VECTOR_CONSTITUTION_SUPPLEMENT_001_AUTHORITY_BOUNDARIES.md)
- [`VECTOR_2_0_BLUEPRINT.md`](notes/04%20VECTOR/VECTOR_2_0_BLUEPRINT.md)
- [`VECTOR_ECOSYSTEM_REPOSITORY_AUTHORITY_INDEX.md`](notes/04%20VECTOR/VECTOR_ECOSYSTEM_REPOSITORY_AUTHORITY_INDEX.md)

### Constitutional Stage 5-B (External Signal Observer Architecture)

- [`STAGE5B_EXTERNAL_SIGNAL_OBSERVER_ARCHITECTURE.md`](notes/04%20VECTOR/STAGE5B_EXTERNAL_SIGNAL_OBSERVER_ARCHITECTURE.md)

This note is a **bridge-layer vocabulary and plane-separation document**. It does **not** authorize implementation, ingestion, bridge activation, or runtime wiring.

### Stage 4 published snapshots (`CONSTITUTIONAL_HISTORICAL`)

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

## License

Owner-authored documents in this repository are licensed under Apache-2.0. See [LICENSE](LICENSE) and [NOTICE](NOTICE).

This is a constitutional / orientation publication surface. The Apache grant does not license private engineering workspaces, CAD, ERA, Chronicle signal bodies, Weaver Forge materials hosted elsewhere, or other repositories. Public visibility is not a license grant. Apache-2.0 on this public surface does not require publishing private operational layers.

---

**Status:** public constitutional / governance orientation only (`CURRENT_PUBLIC_ENTRY` for orientation). Not production. Not runtime. Not Public VECTOR v0. Not Stage 5 overall completion. Not Stage 6. Execution Control Bridge not activated. Gate ≠ Execution. Ingress Ready ≠ Evidence Admitted ≠ Weaver Execution Authorized.
