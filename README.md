# VECTOR Project

## Overview

This repository is the **public ecosystem entry point** for the VECTOR portfolio. It documents architecture, governance orientation, and authority navigation for a **research** program in AI systems safety control—not a finished product, production deployment, or operational authorization.

The goal is NOT to improve general performance, but to:

* Prevent critical failures under degraded conditions
* Maintain correct behavior when observations are unreliable

## VECTOR Ecosystem

VECTOR is a **multi-repository** AI systems research and engineering portfolio. Work is distributed so publication, verification, observation, and private research stay separable. The portfolio focuses on:

* **Governance** — how claims, gates, and reading posture stay bounded
* **Verification** — how outcomes can be checked against declared rules
* **Provenance** — where records and evidence come from
* **Reproducibility** — fixture-scoped and receipt-oriented checks
* **Evidence-governed execution** — action only under declared evidence and gates (not default public behavior)
* **Observation and documentation** — curated records and architectural orientation

**Public visibility does not change document authority.** Publication does not authorize implementation, execution, deployment, or bridge activation. Linked public repositories are research and documentation surfaces—not claims of complete production systems.

### Public repository map

| Repository | Role |
| --- | --- |
| **vector-runtime-governance-public** (this repo) | Ecosystem entry point; architecture and governance orientation; document authority navigation |
| **[weaver-forge](https://github.com/chrono-vector/weaver-forge)** | Independent verification, reproducibility, receipt and evidence validation |
| **[vector-signal-chronicle](https://github.com/chrono-vector/vector-signal-chronicle)** | Curated observation, signal review, chronological public record |

### Internal research and preservation

These are **not** public portfolio repositories. No private URLs or local paths are published here.

| Workspace | Role |
| --- | --- |
| **AI_Lab** | Private research, implementation, and validation workspace |
| **external_research_archive** | Local preservation-only archive; **not** a GitHub repository |
| **job-agent** | Private active-development application |

Publication and workspace boundaries (descriptive): [`REPOSITORY_ROLE.md`](REPOSITORY_ROLE.md).

### Start here (document navigation)

| Document | Why |
| --- | --- |
| [`REPOSITORY_ROLE.md`](REPOSITORY_ROLE.md) | This repository’s public role; publication vs private/local workspace boundary |
| [`notes/04 VECTOR/VECTOR_ECOSYSTEM_REPOSITORY_AUTHORITY_INDEX.md`](notes/04%20VECTOR/VECTOR_ECOSYSTEM_REPOSITORY_AUTHORITY_INDEX.md) | Cross-repo responsibility map (navigation only; no new authority) |
| [`notes/04 VECTOR/VECTOR_2_0_BLUEPRINT.md`](notes/04%20VECTOR/VECTOR_2_0_BLUEPRINT.md) | Architecture orientation guide |
| [`notes/04 VECTOR/VECTOR_CONSTITUTION_MULTI_PLANE_ARCHITECTURE.md`](notes/04%20VECTOR/VECTOR_CONSTITUTION_MULTI_PLANE_ARCHITECTURE.md) | Sole L0a constitutional frame (plane law) |
| [`notes/04 VECTOR/VECTOR_CONSTITUTION_SUPPLEMENT_001_AUTHORITY_BOUNDARIES.md`](notes/04%20VECTOR/VECTOR_CONSTITUTION_SUPPLEMENT_001_AUTHORITY_BOUNDARIES.md) | Sole L0a boundary clarification under the Constitution |

**Authority order (unchanged):** Constitution → Supplement → Blueprint take precedence over repository role and indexes. This README is an entry point only.

## VECTOR progression

VECTOR work is organized in staged layers. Each stage addresses a different question; later stages do not replace earlier freeze authority.

| Stage | Focus |
| --- | --- |
| **Stage 1** | Baseline and failure surface — where the system fails under stress |
| **Stage 2** | Delay-robust observer and temporal coherence — observation lag and estimation behavior |
| **Stage 3** | Deterministic replay freeze — fixture-scoped offline validation and pinned evidence |
| **Stage 4** | Runtime governance exploratory layer — specification, mechanical validation, and reading posture on branch `stage4-runtime-governance` |

**Authority separation:** Stage 3 remains the frozen deterministic replay reference. Stage 4 does not supersede Stage 3, and Stage 4 does not inherit Stage 3 freeze status by default.

## Current Governance Architecture (Freeze Phase)

Freeze-phase navigation only: structure and document entry points, bounded to the current freeze candidate.

### 1. Runtime Governance

- Guard
- RiskModel
- Gate
- Replay / Predict boundaries
- Adaptive Decay research stages

Reference: [[VECTOR_RUNTIME_GOVERNANCE_EVOLUTION_INDEX]]

### 2. Deterministic Replay Governance (Stage 3)

- manifest validation
- replay taxonomy
- bundle verification
- stable replay reporting
- minimal executable reference verifier

Reference: [[STAGE3_DOCUMENT_INDEX]]

### 3. Current Freeze Position

- current verifier is digest-only
- promotion is not approved
- Stage 3 v2 is freeze candidate state
- deterministic replay stability is prioritized before widening verification scope

## Stage 3 Freeze Surface

Stage 3 is a **frozen implementation-validation surface**: scope is bounded to deterministic replay, pinned fixtures, and recorded validation evidence—not open-ended product iteration on this track.

**What this freeze is not:** production readiness, a safety proof, or a generalization proof across unseen workloads.

**Suggested reading order (first-time repository readers)**

1. [`STAGE3_FREEZE_SUMMARY.md`](notes/04%20VECTOR/STAGE3_FREEZE_SUMMARY.md) — freeze scope, non-claims, and current position
2. [`STAGE3_ARCHITECTURE_NAVIGATION.md`](notes/04%20VECTOR/STAGE3_ARCHITECTURE_NAVIGATION.md) — layer map and document entry points
3. [`STAGE3_COMPLETION_CANDIDATE_CRITERIA.md`](notes/04%20VECTOR/STAGE3_COMPLETION_CANDIDATE_CRITERIA.md) — completion-candidate gates and explicit boundaries
4. [`STAGE3_FREEZE_COMPLETION_NOTE.md`](notes/04%20VECTOR/STAGE3_FREEZE_COMPLETION_NOTE.md) — handoff posture and freeze completion record

**Evidence themes on this surface**

- **Replay reproducibility** — fixture-scoped outcomes repeatable under declared binding and comparison rules
- **Adversarial reruns** — negative fixtures and regression matrix rows exercised on reruns, not one-off passes
- **Parity validation** — alignment intent documented and bounded; execution scope stated per linked parity notes
- **Governance replay stability** — manifests, bundles, and stable replay narration held consistent across reruns
- **Evaluator boundary stability** — validator contracts, taxonomy, and regression summaries pinned before scope widening

**Track separation:** future **runtime governance** work and **unseen generalization** studies should proceed on separate branches or documentation tracks so they do not silently widen the frozen Stage 3 validation surface.

## Stage 4 — Runtime governance (exploratory)

Stage 4 is the **runtime governance exploratory layer**: candidate review, mechanical validation on `notes/04 VECTOR/`, and archived evidence under `validation_artifacts/stage4/`. It is **not** shipped enforcement, **not** production readiness, and **not** deployment approval. **Stage 3 remains the frozen validation reference** for deterministic replay, pinned fixtures, and regression evidence; Stage 4 must not be read as widening that surface.

### Current milestone (validation chain + reading freeze)

On branch `stage4-runtime-governance`, the **current exploratory validation series** is complete and the **architectural reading posture is frozen**—a documentation and evidence snapshot, not a production system or operational authorization.

| Milestone item | Record |
| --- | --- |
| Validation artifact chain (P1 → P2 → campaign → P3 → P4) | [`STAGE4_VALIDATION_SERIES_COMPLETION_NOTE.md`](notes/04%20VECTOR/STAGE4_VALIDATION_SERIES_COMPLETION_NOTE.md) (`33d63c1`) |
| P4 replay authority non-collapse artifact | `validation_artifacts/stage4/validation_reports/replay_authority_non_collapse_20260525T122754Z.json` (`5c26ea5`) |
| Validation artifact tracking (tracked vs local subset) | [`STAGE4_VALIDATION_ARTIFACT_TRACKING_NOTE_2026-05-25.md`](notes/04%20VECTOR/STAGE4_VALIDATION_ARTIFACT_TRACKING_NOTE_2026-05-25.md) (`baa52b4`) |
| Runtime governance reading freeze | [`STAGE4_RUNTIME_GOVERNANCE_FREEZE.md`](notes/04%20VECTOR/STAGE4_RUNTIME_GOVERNANCE_FREEZE.md) (`e0ea7d0`) |

**What this milestone is:** citable mechanical checks and pinned JSON on the exploratory branch, plus a stable **canonical reading posture** for Stage 4 runtime governance semantics (observer-aware layer, gate contracts, non-collapse boundaries).

**What it is not:** governance closure, merge or release authorization, Stage 3 replay proof on pins, or a claim that Stage 4 supersedes Stage 3.

### Runtime replay validation MVP (supplement)

Exploratory **runtime ↔ replay supplement** on the Stage 4 branch—not Stage 3 replay authority, not shipped enforcement.

| Item | Record |
| --- | --- |
| Runtime ↔ Replay Bridge MVP | [`governance/runtime_replay_bridge/`](governance/runtime_replay_bridge/) |
| ConsistencyReport JSON export | [`tools/stage4_validation/write_runtime_replay_report.py`](tools/stage4_validation/write_runtime_replay_report.py) |
| Batch runtime replay validation | [`tools/stage4_validation/write_runtime_replay_report_batch.py`](tools/stage4_validation/write_runtime_replay_report_batch.py) |
| Batch summary artifact | [`validation_artifacts/stage4/runtime_replay_reports/runtime_replay_summary_20260526.json`](validation_artifacts/stage4/runtime_replay_reports/runtime_replay_summary_20260526.json) |

First batch snapshot (2026-05-26): `total_reports=1`, `reconciled=1`, `divergent=0`, `bridge_ineligible=0`.

**Architecture entry points**

1. [`STAGE4_ARCHITECTURE_SUMMARY.md`](notes/04%20VECTOR/STAGE4_ARCHITECTURE_SUMMARY.md) — architecture summary and layer boundaries
2. [`STAGE4_FREEZE_CANDIDATE_NOTE.md`](notes/04%20VECTOR/STAGE4_FREEZE_CANDIDATE_NOTE.md) — freeze-candidate scope and non-claims
3. [`STAGE4_SEMANTIC_INVARIANTS.md`](notes/04%20VECTOR/STAGE4_SEMANTIC_INVARIANTS.md) — semantic invariants for runtime governance review
4. [`STAGE4_DOCUMENT_INDEX.md`](notes/04%20VECTOR/STAGE4_DOCUMENT_INDEX.md) — document rollup and cross-links

## Stage 3 — Replay-Visible Governance Architecture

Stage 3 specifies a **replay-visible governance architecture**: governance-relevant claims are reasoned against **deterministic replay** outcomes, structured validator semantics, and explicit boundaries between offline verification, parity intent, authenticity, and live runtime. The design treats **deterministic replay** as the **central invariant**—under declared fixtures, binding, schema versions, and comparison rules, outcomes must be reproducible within the stated offline replay model. **Replay-visible semantics** make governance arguments **traceable to replay-visible records** (manifests, bundles, stable replay logs, structured validator results); conclusions that cannot be so tied do not pass the **evidence gate** in the governed **conformance workflow**. **Temporal consistency** is maintained by versioning and explicit reinterpretation rules so that widening verification or coupling does not silently change prior pass/fail meaning.

**Controlled integration** widens scope only through documented gates: parity alignment, authenticity, and runtime coupling are separated so that digest-level checks, cross-stack parity intent, and live inference are not conflated. **Disagreement classification** assigns structured categories to divergent outcomes or interpretations; the **evidence gate** admits only claims supported by replay-linked artifacts and stated comparison rules. A **runtime observability boundary** separates fixture-scoped deterministic replay from live governance inference; on the **Stage 3 freeze surface**, a **full runtime bridge** is **planned but not implemented**—no shipped path asserts continuous runtime-to-replay enforcement from this baseline (see [Runtime replay validation MVP (supplement)](#runtime-replay-validation-mvp-supplement) for the Stage 4 exploratory bridge MVP, which does not supersede Stage 3).

**Architecture outline**

| Layer | Role |
| --- | --- |
| **Replay Foundation** | Fixtures, manifests, bundle layout, stable replay narration, and serialization-sensitive evaluation that ground offline, fixture-scoped replay. |
| **Boundary Architecture** | Separation of digest integrity, parity intent, authenticity, and runtime interpretation. |
| **Governance Architecture** | Validator contracts, taxonomies, structured outcomes, escalation policy, evidence gate, and conformance-oriented reporting in replay-visible terms. |
| **Controlled Integration** | Explicit process for widening verification, parity lifecycle alignment, and runtime coupling without implicit scope merge. |

**Current non-claims (explicit)**  
This README does not assert production deployment, operational enforcement, cryptographic trust roots, full cross-environment parity execution, or completeness of any subsystem beyond what linked notes state under their own scope.

Full layer map and document entry points: [`notes/04 VECTOR/STAGE3_ARCHITECTURE_INDEX.md`](notes/04%20VECTOR/STAGE3_ARCHITECTURE_INDEX.md).

### Current Status

- Parity harness: **not implemented** (alignment is documented; execution is not asserted).
- Runtime bridge (Stage 3 freeze surface): **not implemented** (planning boundary only; Stage 4 supplement MVP is separate—see above).
- Cryptographic authenticity: **not implemented** (digest-level integrity is distinguished from signature-based authenticity in the corpus).
- Production equivalence: **not claimed**.
- Deployment approval: **not claimed**.

## Stage 3 Operational Hardening

Stage 3 regression summaries (`stage3_regression_summary.json`) are checked by a bounded **contract validator** ([`scripts/validate_stage3_summary_contract.py`](scripts/validate_stage3_summary_contract.py)) after the regression matrix emits rollup output. The gate verifies declared structure and rollup consistency within scope; it does **not** assert production deployment, cryptographic trust, or completeness beyond the pinned contract.

- **`schema_version`** and **`contract_version`** are pinned (`1.0.0` and `stage3-v1`) in the summary artifact and enforced by the validator; mismatches fail before rollup semantics are evaluated.
- A **JSON Schema** at [`schemas/stage3_summary.schema.json`](schemas/stage3_summary.schema.json) (draft-07) documents required fields, types, `additionalProperties: false`, and const bindings for the version fields.
- When the optional **`jsonschema`** package is installed, the validator validates the summary instance against that schema; when it is absent, structural and semantic checks still run and schema validation is reported as skipped—not as a contract failure.
- **Required companion artifacts** (`stage3_regression_output.txt`, `schemas/stage3_summary.schema.json` relative to the summary path) must be present **before** field-level and semantic validation; missing files yield `MISSING_COMPANION_ARTIFACT`.
- **SHA-256 artifact metadata:** On validation, the contract gate emits lowercase hex SHA-256 digests over raw file bytes for the bounded regression surface: `summary_sha256`, `output_sha256`, `schema_sha256`, and `validator_sha256` (summary JSON, companion output trace, pinned JSON Schema, and the validator script at validation time).
- **`hash_metadata_status`** is `complete` when all four digests are present, or `partial` when one or more targets were missing or unreadable; partial metadata does not replace existing companion failure codes.
- Digests are **reproducibility evidence only**—they help reviewers and automation compare a run’s artifacts to a prior recorded baseline. They are **not** signing, **not** remote attestation, and **not** a tamper-proof guarantee; hash emission does not establish trust or provenance beyond byte identity of the pinned targets.

## Stage 4 — Governance Candidate Review Architecture

Stage 4 extends the corpus as a **governance candidate review architecture** (統治候補のレビュー・アーキテクチャ): it organizes how candidate governance claims are prepared, cross-referenced, and reviewed against **replay-visible evidence** (replay可視の証拠) and stated comparison rules. The Stage 4 document set refines entry points, glossaries, and cross-links so arguments remain auditable without widening implicit verification scope. **Stage 4 is specification and review structure for candidates—not a claim of implementation completion** (実装完了を主張しない); it does not assert production rollout, deployment approval, or finished subsystems beyond what each linked note states under its own scope. For the completed validation chain, P4 artifact, tracking snapshot, and reading freeze, see [Stage 4 — Runtime governance (exploratory)](#stage-4--runtime-governance-exploratory) above.

**Deterministic replay** (決定論的リプレイ) remains the **central invariant**: under declared fixtures, binding, schema versions, and comparison rules, outcomes in the offline replay model must be reproducible as stated. **Replay-visible evidence** carries **evidence authority** (証拠の権威): governance conclusions are grounded in artifacts and narration that replay can surface; claims that cannot meet the **evidence gate** (証拠ゲート) do not advance in the **conformance workflow** (適合性ワークフロー). **Disagreement classification** (差異分類) assigns structured categories when outcomes or interpretations diverge. **Controlled integration** (制御された統合) widens coupling only through explicit gates so digest checks, parity intent, authenticity, and live interpretation are not conflated. A **runtime bridge** (ランタイム・ブリッジ) remains a bounded planning construct—separating fixture-scoped replay from live governance inference—without asserting continuous runtime-to-replay enforcement from this baseline.

**References**

- Stage 4 index: [`notes/04 VECTOR/STAGE4_DOCUMENT_INDEX.md`](notes/04%20VECTOR/STAGE4_DOCUMENT_INDEX.md)
- Replay-visible glossary: [`notes/04 VECTOR/REPLAY_VISIBLE_GLOSSARY.md`](notes/04%20VECTOR/REPLAY_VISIBLE_GLOSSARY.md)
- Cross-reference map: [`notes/04 VECTOR/STAGE4_CROSS_REFERENCE_MAP.md`](notes/04%20VECTOR/STAGE4_CROSS_REFERENCE_MAP.md)

## Documentation Navigation

Concise map of the current VECTOR governance and Stage 3 verification corpus under `notes/04 VECTOR/`. Promotion and production readiness are **not** claimed unless a linked note states otherwise.

### Governance Concepts

- [`GOVERNANCE_CORPUS_COMPLETION_NOTE.md`](notes/04%20VECTOR/GOVERNANCE_CORPUS_COMPLETION_NOTE.md) — how concept notes fit together; replay-centered posture and non-collapse rules.
- [`GOVERNANCE_SCOPE_CONCEPT.md`](notes/04%20VECTOR/GOVERNANCE_SCOPE_CONCEPT.md), [`GOVERNANCE_SEMANTIC_LAYERING_CONCEPT.md`](notes/04%20VECTOR/GOVERNANCE_SEMANTIC_LAYERING_CONCEPT.md), [`GOVERNANCE_CONSTRAINT_FLOW_CONCEPT.md`](notes/04%20VECTOR/GOVERNANCE_CONSTRAINT_FLOW_CONCEPT.md) — scope planes, layering, and constraint direction between layers.
- [`GOVERNANCE_BRIDGE_ADMISSION_CONCEPT.md`](notes/04%20VECTOR/GOVERNANCE_BRIDGE_ADMISSION_CONCEPT.md), [`GOVERNANCE_EVIDENCE_GATE_CONCEPT.md`](notes/04%20VECTOR/GOVERNANCE_EVIDENCE_GATE_CONCEPT.md) — runtime-to-governance admission vs evidence eligibility.
- [`GOVERNANCE_REPLAY_VISIBILITY_CONCEPT.md`](notes/04%20VECTOR/GOVERNANCE_REPLAY_VISIBILITY_CONCEPT.md), [`GOVERNANCE_DETERMINISTIC_REPLAY_INVARIANT_CONCEPT.md`](notes/04%20VECTOR/GOVERNANCE_DETERMINISTIC_REPLAY_INVARIANT_CONCEPT.md) — replay-visible semantics and the replay-grounding floor.
- [`GOVERNANCE_AUTHORITY_CONCEPT.md`](notes/04%20VECTOR/GOVERNANCE_AUTHORITY_CONCEPT.md), [`GOVERNANCE_AUTHORITY_COORDINATION_CONCEPT.md`](notes/04%20VECTOR/GOVERNANCE_AUTHORITY_COORDINATION_CONCEPT.md) — authority boundaries and coordination without truth substitution.
- [`GOVERNANCE_REVISION_CONCEPT.md`](notes/04%20VECTOR/GOVERNANCE_REVISION_CONCEPT.md), [`GOVERNANCE_TRANSITION_CONCEPT.md`](notes/04%20VECTOR/GOVERNANCE_TRANSITION_CONCEPT.md), [`GOVERNANCE_TYPE_PROMOTION_CONCEPT.md`](notes/04%20VECTOR/GOVERNANCE_TYPE_PROMOTION_CONCEPT.md) — revision, transitions, and governed semantic strengthening.
- [`REPLAY_GOVERNANCE_OVERVIEW.md`](notes/04%20VECTOR/REPLAY_GOVERNANCE_OVERVIEW.md) — research overview tying replay, evidence, and temporal consistency.
- [`CURRENT_STATE.md`](notes/04%20VECTOR/CURRENT_STATE.md) — live project phase, completed work, and next tasks.

### Replay / Deterministic Verification

- [`STAGE3_ARCHITECTURE_INDEX.md`](notes/04%20VECTOR/STAGE3_ARCHITECTURE_INDEX.md) — layer-organized Stage 3 map (replay foundation → boundaries → governance → controlled integration).
- [`STAGE3_DOCUMENT_INDEX.md`](notes/04%20VECTOR/STAGE3_DOCUMENT_INDEX.md) — freeze-phase document rollup and validator/replay spec entry points.
- [`REPLAY_VISIBLE_GLOSSARY.md`](notes/04%20VECTOR/REPLAY_VISIBLE_GLOSSARY.md) — shared Stage 3 / Stage 4 terminology.
- [`STAGE3_STABLE_REPLAY_LOG_SCHEMA.md`](notes/04%20VECTOR/STAGE3_STABLE_REPLAY_LOG_SCHEMA.md), [`STAGE3_GOVERNANCE_BUNDLE_SPEC.md`](notes/04%20VECTOR/STAGE3_GOVERNANCE_BUNDLE_SPEC.md), [`STAGE3_VECTOR_BUNDLE_DIRECTORY_SCHEMA.md`](notes/04%20VECTOR/STAGE3_VECTOR_BUNDLE_DIRECTORY_SCHEMA.md) — replay log, bundle shape, and directory layout.
- [`STAGE3_CONFORMANCE_WORKFLOW.md`](notes/04%20VECTOR/STAGE3_CONFORMANCE_WORKFLOW.md), [`STAGE3_DISAGREEMENT_ESCALATION_POLICY.md`](notes/04%20VECTOR/STAGE3_DISAGREEMENT_ESCALATION_POLICY.md) — conformance gates and disagreement handling in replay-visible terms.
- [`REPLAY_BUNDLE_SCHEMA_CONCEPT.md`](notes/04%20VECTOR/REPLAY_BUNDLE_SCHEMA_CONCEPT.md), [`EVIDENCE_MANIFEST_CONCEPT.md`](notes/04%20VECTOR/EVIDENCE_MANIFEST_CONCEPT.md) — bundle and manifest semantics upstream of Stage 3 specs.
- [`STAGE_D_REPLAY_CONTRACT_PRECHECK.md`](notes/04%20VECTOR/STAGE_D_REPLAY_CONTRACT_PRECHECK.md) — runtime replay-contract primitives (`snapshot`, `reset`, logging) feeding offline verification.
- [`STAGE3_FREEZE_NAVIGATION_INDEX.md`](notes/04%20VECTOR/STAGE3_FREEZE_NAVIGATION_INDEX.md), [`STAGE3_VALIDATOR_REGRESSION_SNAPSHOT_2026-05-13.md`](notes/04%20VECTOR/STAGE3_VALIDATOR_REGRESSION_SNAPSHOT_2026-05-13.md) — freeze checkpoints and pinned PASS/FAIL evidence tables.

### Stage 3 Regression Infrastructure

- [`STAGE3_REGRESSION_MATRIX_PLAN.md`](notes/04%20VECTOR/STAGE3_REGRESSION_MATRIX_PLAN.md) — matrix purpose, Surface A/B row categories, and comparison rules.
- [`stage3_regression_matrix_v1.json`](notes/04%20VECTOR/stage3_regression_matrix_v1.json) — machine-readable expected outcomes catalog for local and CI runners.
- [`scripts/run_stage3_regression_matrix.py`](scripts/run_stage3_regression_matrix.py) — unified matrix runner (manifest + digest bundle surfaces).
- [`scripts/validate_stage3_manifest.py`](scripts/validate_stage3_manifest.py) — Surface A manifest structural validation.
- [`scripts/stage3_v2_reference_verify.py`](scripts/stage3_v2_reference_verify.py) — Surface B digest-only reference verifier (bounded scope per freeze candidate note).
- [`STAGE3_FIXTURE_INVENTORY_MAP.md`](notes/04%20VECTOR/STAGE3_FIXTURE_INVENTORY_MAP.md), [`STAGE3_FIXTURE_MANIFEST_SPEC.md`](notes/04%20VECTOR/STAGE3_FIXTURE_MANIFEST_SPEC.md) — fixture inventory and manifest rules; companion `STAGE3_FIXTURE_MANIFEST_*.json` under `notes/04 VECTOR/`.
- [`stage3_validator_v2_bundle/`](notes/04%20VECTOR/stage3_validator_v2_bundle/) — golden digest bundle; [`stage3_surface_b_negative_bundles/`](notes/04%20VECTOR/stage3_surface_b_negative_bundles/) — negative Surface B fixtures.
- [`STAGE3_SURFACE_B_NEGATIVE_FIXTURE_PLAN.md`](notes/04%20VECTOR/STAGE3_SURFACE_B_NEGATIVE_FIXTURE_PLAN.md), [`STAGE3_V2_MINIMAL_VERIFIER_FREEZE_CANDIDATE.md`](notes/04%20VECTOR/STAGE3_V2_MINIMAL_VERIFIER_FREEZE_CANDIDATE.md) — negative-case plan and minimal verifier freeze scope.

### CI / Artifact Infrastructure

- [`.github/workflows/stage3-regression.yml`](.github/workflows/stage3-regression.yml) — GitHub Actions workflow running the Stage 3 regression matrix on push/PR.
- [`stage3_regression_summary.json`](stage3_regression_summary.json) — local/CI matrix summary output (row counts and pass/fail rollup).
- [`STAGE3_CI_REGRESSION_BASELINE_PASS_NOTE.md`](notes/04%20VECTOR/STAGE3_CI_REGRESSION_BASELINE_PASS_NOTE.md) — first successful CI baseline and Surface A/B row coverage.
- [`STAGE3_VALIDATOR_RESULT_SCHEMA.md`](notes/04%20VECTOR/STAGE3_VALIDATOR_RESULT_SCHEMA.md), [`STAGE3_MACHINE_READABLE_REPORT_SCHEMA.md`](notes/04%20VECTOR/STAGE3_MACHINE_READABLE_REPORT_SCHEMA.md) — structured validator output and audit-oriented report shapes.
- [`STAGE3_MANIFEST_VALIDATOR_SPEC.md`](notes/04%20VECTOR/STAGE3_MANIFEST_VALIDATOR_SPEC.md), [`STAGE3_VALIDATOR_TAXONOMY_SUMMARY.md`](notes/04%20VECTOR/STAGE3_VALIDATOR_TAXONOMY_SUMMARY.md) — normative validation rules and failure taxonomy for tooling alignment.
- CI workflow uploads `stage3-regression-output` artifacts (`stage3_regression_output.txt`, `stage3_regression_summary.json`) for hosted run inspection.

## Runtime Governance Prototype

Research-oriented middleware that ties governance decisions to observer signals. The design targets **bounded state**, **deterministic scripted inputs**, and **replayable CSV-backed evaluation** rather than open-ended autonomy.

**Core runtime concepts**

- `observer_gap` — mismatch between trusted and observed state used as a risk input
- `observer_distrust` — accumulated skepticism toward the observer under sustained divergence
- `p_fail` — scalar failure probability from the risk model
- `escalation` — tightening of gate posture (e.g. ALLOW → THROTTLE → BLOCK) as risk rises
- `recovery` — decay of distrust / risk after clean observations

**Observed behaviors** (evaluation harness; scenario-bounded)

- Hostile distrust accumulation under adversarial gap sequences
- False escalation resistance under moderate, non-hostile oscillation
- Recovery convergence after hostile bursts
- Replayable evaluation evidence via scripted trajectories and emitted reports

**Representative metrics** (current harness; scenario-specific, not a universal guarantee)

| Metric | Value |
| --- | --- |
| hostile distrust growth | 0.4 |
| false_escalation_rate | 0.0 |
| recovered_to_zero | True |
| recovery_steps_to_zero | 5 |

**Architecture separation**

- **Guard** — orchestration, state accumulation, and escalation policy wiring
- **RiskModel** — `p_fail` computation only

**Current philosophy**

Small, stable, measurable, bounded, replayable.

## What the research prototype exercises

Under scripted evaluation harnesses, the AI_Lab runtime governance **research prototype** has been exercised for:

- observer-aware runtime evaluation
- spoofed observation detection
- delayed observation escalation
- repeated adversarial behavior tracking
- adaptive trust-aware governance
- ALLOW -> THROTTLE -> BLOCK escalation

The project combines:

- payload-aware governance
- state-aware governance
- observer-aware governance
- adaptive runtime governance

Key behaviors include:

- confidence collapse detection
- runtime distrust accumulation
- adaptive risk escalation
- recovery-aware risk reduction

This project is not focused on improving raw model intelligence.

Instead, it focuses on:
safe runtime behavior,
explainable execution control,
and reproducible governance evaluation under declared scenarios.

These behaviors are **scenario-bounded research evidence**, not production readiness, deployment approval, or guarantees across unseen workloads.

## Runtime Flow

Input Request
  ↓
Request Adapter
  ↓
Observer State
(observer_gap / estimation_gap)
  ↓
Risk Model
(base risk + observer penalty)
  ↓
Constraint Engine
  ↓
Gate
(ALLOW / THROTTLE / BLOCK)
  ↓
Chronicle Logs
  ↓
Evaluation Pipeline
  ↓
Visualization

The runtime governance layer evaluates:
- payload conditions
- observer divergence
- delayed observations
- trust degradation
- adaptive escalation behavior

Observer divergence is now treated as actionable runtime risk.

## Verification (pytest; harness-scoped)

Observed under current unit tests (not a production sign-off or deployment approval):
- observer_gap increases runtime risk (p_fail) in pinned scenarios
- escalation ordering is monotonic in pinned scenarios
- observer-aware governance behavior is reproducibly testable via pytest

Pytest coverage:
- tests/test_observer_risk.py
- tests/test_observer_escalation.py
- tests/test_guard_runtime_replay_validation.py

Current harness snapshot:
2 passed (re-run locally to confirm)

Meaning:
Selected guard/risk behaviors are **reproducibly checkable in pytest** under the pinned test scenarios—not evidence of full runtime governance implementation, Stage 3 replay proof, or operational authorization.

---

## Observer Distrust Evaluation

The runtime governance layer now tracks observer distrust over repeated observer divergence.

Observed behavior:
- repeated observer divergence increases observer_distrust
- increasing observer_distrust raises p_fail
- safe behavior reduces observer_distrust
- recovery reduces p_fail
- post-recovery divergence remains throttled but with reduced risk

Evaluation artifact:
- `evaluate_observer_distrust.py`
- `plot_observer_distrust.py`
- `reports/observer_distrust_visualization.png`

Harness-scoped observation (not a general guarantee):
Repeated divergence increased observer_distrust from 0.2 to 0.6 in the recorded evaluation run.
Safe recovery reduced observer_distrust from 0.6 to 0.3 in that run.
Post-recovery divergence remained controlled under the scripted trajectory.

---

## Chaos Runtime Test

The project includes a hostile-condition runtime evaluation phase.

This phase **exercises** runtime governance behavior under scripted hostile scenarios (not deployment validation):

* spoofed observations
* delayed spoof escalation
* malformed requests
* contradictory payloads
* fake authorization attempts
* repeated adversarial behavior
* trust degradation
* recovery cycles

### Chaos Batch Evaluation

Run:

python chaos_runtime_test.py

Outputs:

reports/chaos_runtime_test.csv

### Chaos Visualization

Run:

python plot_chaos_runtime_test.py

Outputs:

reports/chaos_runtime_visualization.png

### Key Metrics

The runtime evaluation tracks:

* false_allow_rate
* adjusted_p_fail
* confidence
* trust_score
* recovery_count
* escalation behavior

### Current harness snapshot (chaos batch scenarios)

The recorded hostile runtime evaluation run reported:

false_allow_rate = 0.0

under the mixed adversarial scenarios in that batch—not a universal guarantee.

This phase provides **exploratory chaos-harness evidence** toward trust-aware governance under those scripted conditions—not production robustness certification or deployment approval.

---

## Phase progression (research evaluation milestones)

The phases below are **research and evaluation milestones** on scripted trajectories. They do not imply production maturity, operational rollout, or supersession of Stage 3 as the deterministic replay reference.

This project evolved through the following runtime governance evaluation phases:

### Phase 1 — Basic Runtime Governance

Initial middleware-based runtime control with ALLOW / THROTTLE / BLOCK decisions.

### Phase 2 — Multi-State Runtime Governance

Support for multiple runtime scenarios including clean, spoofed, delayed, and critical observations.

### Phase 3 — Trust and Recovery Governance

Introduction of trust degradation, recovery accumulation, and adaptive risk adjustment.

### Phase 4 — Hostile Runtime Robustness

Chaos batch testing under mixed adversarial conditions.

Harness snapshot (chaos batch scenarios):

false_allow_rate = 0.0 in the recorded run—not a universal guarantee.

### Phase 5 — Observer-Gap-Aware Governance

Runtime risk incorporates observer_gap as a penalty signal.

### Phase 6 — Observer-State-Aware Governance

Observer state is represented through:

* x_obs
* x_hat
* estimation_error

This connects runtime governance to state-estimation-aware behavior.

### Phase 7 — Observer Drift-Aware Governance

Time-evolving observer drift is introduced into runtime risk evaluation.

### Phase 8 — Adaptive Drift Recovery

Recovery behavior reduces effective drift through:

* drift_recovery_factor
* effective_drift_state

### Phase 9 — Feedback-Aware Runtime Governance

Runtime decisions influence future runtime stability.

This creates a closed-loop governance pattern:

runtime state
→ decision
→ stability feedback
→ future runtime risk

Under Phase 9 evaluation scenarios, the harness exhibits closed-loop, observer-state-aware governance dynamics—still a **research prototype**, not shipped enforcement or production readiness.

---

## Project Documents

- [Demo Flow](DEMO_FLOW.md)
- [Runtime Governance Architecture](RUNTIME_GOVERNANCE_ARCHITECTURE.md)
- [Runtime Governance Summary](AI_LAB_RUNTIME_GOVERNANCE_SUMMARY.md)

These documents describe how to run, understand, and interpret the runtime governance **research prototype** (harness-scoped; not production documentation).

---

## Key Concept

This system is:

**Not a performance optimizer**

It is a:

**Robustness layer**

Behavior:

* Normal conditions → No intervention
* Noise → No unnecessary intervention
* Boundary conditions → No false triggering
* Degraded observations (delay) → Strong correction

---

## Scenario-bounded result (sensor delay experiment)

### Sensor delay (recorded experiment)

Under delayed observation:

Baseline:

* Up to **143 false negatives**

With control:

* Reduced to **~0–2% (e.g. 4 / 200)**

Conclusion:

This system does NOT guarantee safety deterministically.
However, it **reduces failure probability dramatically**.

---

## Behavior Summary

| Condition | Behavior           |
| --------- | ------------------ |
| Normal    | No change          |
| Noise     | No change          |
| Boundary  | No false trigger   |
| Delay     | Strong improvement |
| Policy    | No interference    |

---

## System Structure

vector_test → Experiment generation
AI_Lab → Analysis and comparison
Obsidian → Research notes and experiment logs (not deployment validation)

---

## Workflow

1. Run experiments

python run_break_it_new.py

2. Analyze

python scripts/compare_by_variant.py

3. Review results

reports/comparison_by_variant.csv

---

## Key Insight

This system is:

**Selective robustness control**

It does NOT try to improve everything.
It acts ONLY when the system is at risk.

---

## Status (research prototype; not production)

* Scenario-bounded evaluation and fixture-scoped replay evidence recorded—not “functional validation complete” in a product or deployment sense
* Reproducibility confirmed for declared probabilistic experiments under pinned scripts
* Not production readiness; not deployment approval; Stage 4 remains an exploratory runtime governance documentation / validation milestone
* Further work: large-scale Monte Carlo validation and runtime implementation beyond harness-scoped evidence

---

## Concept Shift

Deterministic control
→ Probabilistic robustness

---

Failure occurs when estimation error exceeds a safety margin.

## Visualization

### Failure vs Estimation Error
![Failure vs Error](experiments/vector_delay_robust_control/break_it_results/failure_vs_error.png)

### Lead Time Distribution
![Lead Time](experiments/vector_delay_robust_control/break_it_results/lead_time_distribution.png)

### Integration (prototype code path)
The lag-robustness experiment informed a **prototype** code path—not a production rollout claim:
- `AI_Lab/core/risk_model.py`
- latency-based safety margin added to `p_fail` in the research prototype

## 📊 Evidence

![Failure vs Error](break_it_results/failure_vs_error.png)

→ Failure is not caused by large error magnitude,  
but by delayed observation leading to estimation drift.

---

## AI_Lab / ZTEL Runtime Governance

AI_Lab extends the VECTOR idea into a **runtime governance research prototype** with a gate evaluation path.

Under the current prototype, evaluation is not only payload-aware; it also incorporates:

**payload-aware + state-aware + observer-aware** signals in harness scenarios

The gate path evaluates the request and, in scripted runs, whether the current state can be trusted for gating decisions—not continuous production enforcement.

---

## Observer-Aware Signals

The runtime gate uses:

- `state_hat`
- `estimation_gap`
- `prediction_risk`
- `confidence`
- `p_fail`

These signals allow the system to react before visible failure occurs.

---

## Runtime governance validation (scripted scenarios)

Scenario table values are **harness-scoped** observations from `evaluate_runtime_governance.py`, not universal guarantees or deployment approval.

### Evaluation Script

```bash
python evaluate_runtime_governance.py
```

### Runtime Results

| Scenario | Decision | p_fail | Confidence |
|---|---:|---:|---:|
| observer_clean | allow | 0.38 | 1.0 |
| observer_divergence | throttle | 0.56 | 0.1 |
| observer_spoof | throttle | 0.4225 | 0.0 |
| observer_delayed_spoof | throttle | 0.73 | 0.0 |

---

## Key finding (scripted evaluation scenarios)

Under the evaluation script’s fixed scenarios, the harness distinguishes:

- normal observed state
- observer divergence
- spoofed observation
- delayed spoofed observation

This is **research prototype evidence** for observer-aware gating in those scenarios—not a claim of full runtime governance implementation or production rollout.

The fix was not a better controller.

It was restoring the present.

---

## Runtime Governance Visualization

### Generate Visualization

```bash
python plot_runtime_governance.py
```

### Output

```text
reports/runtime_governance_comparison.png
```

### Visualization Focus

The graph visualizes:

- p_fail escalation
- confidence collapse
- observer spoofing
- delayed observation amplification

The Phase D evaluation also includes adaptive repeated-spoof handling, where repeated adversarial observations increase adjusted risk over time.

---

## Runtime governance evaluations (harness-scoped CSV replay)

CSV evaluations under `scripts/evaluate_*.py` drive fixed `observer_gap` trajectories through `Guard.evaluate` (governance path only; no action execution), emitting a **replayable CSV evaluation suite** under `reports/*.csv`. Runs exhibit **bounded distrust dynamics** (`observer_distrust`), **adaptive runtime escalation** in decisions / `p_fail`, and **recovery-aware throttle behavior** after hostile phases where applicable in the scripted trajectories. **Visualization support**: `scripts/plot_observer_runtime.py`, `plot_hostile_sequences.py`, `plot_recovery_latency.py`, and `plot_throttle_recovery.py` consume the CSVs and write figures under `reports/`.

Consolidated evaluation outputs are available in `reports/governance_evaluation_summary.csv` and `reports/governance_evaluation_summary_visualization.png`.

### Observed under current harness scenarios

- hostile accumulation observed in hostile-sequence scenarios
- throttle escalation observed in escalation scenarios
- throttle recovery observed in recovery scenarios
- false escalation suppression observed in false-escalation scenarios
- bounded recovery dynamics observed in recovery-latency scenarios

### Runtime governance metrics (evaluation harness)

The following values are **baseline evaluation-harness confirmations** under the current scripted scenarios; they are **not universal guarantees** across unseen workloads.

- hostile distrust growth: 0.4
- false_escalation_rate: 0.0
- recovered_to_zero: True
- recovery_steps_to_zero: 5

Fuller summary: [`notes/04 VECTOR/RUNTIME_GOVERNANCE_RESULTS.md`](notes/04%20VECTOR/RUNTIME_GOVERNANCE_RESULTS.md).

### Observer-Aware Runtime Governance

`scripts/evaluate_observer_runtime.py` → `reports/observer_runtime_evaluation.csv`; optional figure via `scripts/plot_observer_runtime.py` → `reports/observer_runtime_visualization.png`. Exercises observer-gap-conditioned risk and escalation along a mixed clean / stressed / recovery trajectory (harness-scoped).

### Hostile Sequence Evaluation

`scripts/evaluate_hostile_sequences.py` → `reports/hostile_sequence_evaluation.csv`; `scripts/plot_hostile_sequences.py` → `reports/hostile_sequence_visualization.png`. Contrasts scripted normal vs hostile `observer_gap` sequences; hostile legs show elevated distrust and risk relative to the normal control.

### Recovery-Aware Governance

`scripts/evaluate_recovery_latency.py` → `reports/recovery_latency_evaluation.csv`; `scripts/plot_recovery_latency.py` → `reports/recovery_latency_visualization.png`. Measures post-burst decay in `observer_distrust` and `p_fail` under sustained clean gaps (**recovery-aware throttle behavior**).

### False Escalation Suppression

`scripts/evaluate_false_escalation.py` → `reports/false_escalation_evaluation.csv`. Moderate, cyclic non-hostile `observer_gap`; checks absence of inappropriate throttle/block escalation versus hostile-tier sequences in that harness.

### Runtime Trust Boundary

`scripts/evaluate_threshold_boundary.py` → `reports/threshold_boundary_evaluation.csv`. Steps `observer_gap` across the hostile threshold band (~1.0); records escalation sensitivity and ordering at the trust / intervention boundary under that script.

### Throttle Recovery

`scripts/evaluate_throttle_recovery.py` → `reports/throttle_recovery_evaluation.csv`; `scripts/plot_throttle_recovery.py` → `reports/throttle_recovery_visualization.png`. Hostile-phase hold followed by extended recovery gaps; records throttle relaxation aligned with distrust and `p_fail` decay in that scenario.

Prolonged hostile stress traces (accumulation without recovery) are additionally captured by `scripts/evaluate_long_hostile_stability.py` → `reports/long_hostile_stability.csv`.