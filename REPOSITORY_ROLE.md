# Repository Role

## Purpose

vector-runtime-governance-public is the public publication repository for Runtime Governance.

It publishes:

- Constitutional documents
- Runtime governance principles
- Blueprint documents
- Public architectural guidance
- Governance milestones
- Reading posture
- Public specifications

It is not the primary implementation repository.

It is a **CURRENT_PUBLIC_ENTRY** for constitutional / orientation reading. It is **not** the Public VECTOR v0 reference tree (that is `vector-core`), not a runtime, and not a fully automated live pipeline.

---

## Current VECTOR path (orientation only)

VECTOR is a research reference architecture for keeping observation, interpretation, verification, replay, and execution from collapsing into each other, with a public read-only package boundary at Weaver Forge.

The current high-level path is human-gated:

External Sources → ERA → IG-01 → CAD → IG-02 → Human Promotion Gate → Observation Chronicle → IG-03 → Core-01 Decision Process → IG-04 Decision Trace → IG-05-A Structural Verification → Core-02 Verification Result Registry → Core-03 Replay Contract → IG-05-C Replay Eligibility / Gate → optional Owner-authorized Core-05 Replay → Replay Result → Core-04 Weaver Handoff Control → Repository Owner Handoff Authorization → VECTOR Handoff Package v0 → Weaver Forge VECTOR Package Ingress v0 → deterministic Ingress Result → Human / Repository Owner Review → STOP.

This path is **not** one automatic live pipeline. Implementation lives in the private engineering workspace. **CAD-Vortex is a private satellite, not a public clone requirement.** ERA is local preservation only. Weaver Forge hosts VECTOR Package Ingress v0 as a ZIP-only read-only checking boundary; that Ingress is **not** Independent Witness, Evidence admission, Truth verification, Weaver execution, or Stage 6.

IG-07 is readout / explanation only and does not add authority. Source Weaver GPT is not a mandatory pipeline stage.

See the current-path section in [`README.md`](README.md) for the nonclaim block and document-role labels (`CURRENT_PUBLIC_ENTRY` vs `CONSTITUTIONAL_HISTORICAL` vs `HISTORICAL_RESEARCH`).

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

---

## Relationship to AI_Lab

AI_Lab is the engineering workspace.

AI_Lab contains:

- Runtime implementation
- Guard implementation
- Replay implementation
- Validation campaigns
- Stage3
- Stage4
- Stage5
- Future Stage5-C

AI_Lab is where governance concepts are developed and validated before publication.

---

## Relationship to vector-signal-chronicle

vector-signal-chronicle is responsible for:

- External signals as **observation records**
- Observer Reviews
- Confidence / assessment as **interpretation**, not verification
- Chronicle governance

Observation recorded there is **not** Evidence admission, **not** Truth verification, and **not** execution. This repository does not perform observation.

---

## Runtime Governance

This repository defines:

What Runtime Governance means.

It does not execute runtime governance.

Implementation remains in AI_Lab until promoted.

---

## Promotion Boundary

Concepts mature through:

AI_Lab
↓

Validation

↓

Publication

↓

Operational guidance

Publication does not imply implementation.

Implementation does not imply publication.

---

## Stage5-C

Stage5-C belongs to AI_Lab.

This repository may publish constitutional guidance related to Stage5-C after successful validation and promotion.

---

## Repository Summary

AI_Lab

Research
Prototype
Validation
Implementation

↓

vector-runtime-governance-public

Public governance
Architecture
Constitution
Blueprint

↓

vector-signal-chronicle

Observation Governance
Evidence
Assessment
Chronicle

---

## Design Principle

The VECTOR ecosystem intentionally separates:

Research

Publication

Observation

Execution

Each repository has an independent responsibility.

This separation strengthens governance, reproducibility, and auditability.

---

## Publication and Workspace Boundary

Descriptive only. This section does **not** redefine constitutional plane law, document authority order, or implementation authorization. For plane and channel boundaries, read the Constitution and Supplement. For cross-repo navigation, read the ecosystem repository authority index.

### Public repositories

| Repository | Public role (orientation) |
|------------|---------------------------|
| **vector-runtime-governance-public** | Public ecosystem entry point. Architecture, governance, authority navigation, and portfolio orientation. **Publication does not imply runtime authority or implementation authorization.** |
| **vector-core** | Sanitized Public VECTOR v0 **reference** (Apache-2.0). Architecture, schemas, validators, synthetic fixtures, and a path-independent CAD copy. **Not** operational authorization, Evidence admission, replay authorization, Weaver execution, or Stage 6. **Not** a full operational release. |
| **weaver-forge** | Public verification, reproducibility, receipt-validation methods, sanitized evidence, **and** VECTOR Package Ingress v0 (read-only ZIP-only checking boundary). Ingress is **not** Independent Witness, Evidence admission, Weaver execution, or Stage 6. Public Core is Apache-2.0 with documented exclusions. **Must not** expose private evidence stores, Owner package bytes, or unreviewed third-party material. |
| **vector-signal-chronicle** | Public curated observation records and reviewed signal documentation. Framework/reference material is Apache-2.0. `signals/**` remains public but is excluded from Apache-2.0 by default. Raw drafts, private messages, personal data, and unreviewed source material **must remain outside** the public publication layer. |

### Private or local workspaces

| Workspace | Role (orientation) |
|-----------|--------------------|
| **AI_Lab** | Research, engineering, prototype, documentation, and validation workspace. Content is **not** public authority unless explicitly promoted through the defined review path (see [Promotion Boundary](#promotion-boundary)). |
| **cad-vortex** | Private Plane 2 observation-side intake / normalization / provenance / structural screening → observation candidate. **Not a public clone requirement.** Claimed lineage is **not ERA-verified**. Not Chronicle authority. Not ERA verification authority. Not execution authority. No automatic handoff. Not production ready. Listing it here is orientation only and introduces **no new authority**. |
| **external_research_archive** | Local **preservation-only** layer. **Currently not a GitHub repository.** Preserves external material, inventories, hashes, and review records. Remains **BRIDGE_INADMISSIBLE**. Preservation does **not** grant authority, endorsement, redistribution rights, or implementation permission. |
| **job-agent** | Private active-development repository until an explicit publication review is completed. |

Private and local workspaces are not public publication surfaces. They must not be treated as constitutional, runtime, or execution authority solely because material exists there.

### Publication exclusions

Public repositories must not contain:

- Credentials, API keys, tokens, secrets, or environment files
- Personal information or private communications
- Private local filesystem paths where avoidable
- Raw third-party archives without confirmed redistribution rights
- Unreviewed claims presented as verified facts
- Internal evidence corpora or private receipts
- Unfinished reviews, drafts, or speculative conclusions presented as approved
- Material whose copyright, license, consent, or attribution status is unresolved

### Status changes

- Moving a repository or material from private/local to public requires **explicit review**.
- **Public visibility does not change document authority.**
- **Publication does not authorize** implementation, execution, deployment, governance, or bridge activation.
- **Public VECTOR v0 is not yet a full operational release.** The sanitized reference lives in `vector-core`. This repository remains orientation / constitution only.
