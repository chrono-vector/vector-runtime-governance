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

- External signals
- Observer Reviews
- Evidence
- Confidence
- Assessment
- Chronicle governance

This repository does not perform observation.

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
| **weaver-forge** | Public verification, reproducibility, receipt-validation methods, and sanitized evidence. **Must not** expose private evidence stores or unreviewed third-party material. |
| **vector-signal-chronicle** | Public curated observation records and reviewed signal documentation. Raw signals, drafts, private messages, personal data, and unreviewed source material **must remain outside** the public publication layer. |

### Private or local workspaces

| Workspace | Role (orientation) |
|-----------|--------------------|
| **AI_Lab** | Research, engineering, prototype, documentation, and validation workspace. Content is **not** public authority unless explicitly promoted through the defined review path (see [Promotion Boundary](#promotion-boundary)). |
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
