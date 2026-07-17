# VECTOR Ecosystem - Repository Authority Index

**Audience:** Contributors orienting across VECTOR-related repositories.  
**Document type:** Orientation / index only. Documentation only.

**This document is not:**

- Constitution
- Constitution Supplement
- Blueprint
- Stage document
- Implementation specification

It introduces **no new authority**.

---

## Authority

| Document | Role |
|----------|------|
| [[VECTOR_CONSTITUTION_MULTI_PLANE_ARCHITECTURE]] | **Sole L0a authority** |
| [[VECTOR_CONSTITUTION_SUPPLEMENT_001_AUTHORITY_BOUNDARIES]] | **Sole boundary clarification** under the Constitution |
| [[VECTOR_2_0_BLUEPRINT]] | **Architecture orientation guide** (inherits L0a framing; no authority) |
| **This document** | **Ecosystem repository index only** |

If any conflict exists:

**Constitution -> Supplement -> Blueprint** take precedence.

This index may only point to those documents. It does not amend, widen, or replace them.

---

## Document authority order

Ecosystem documents are read in the following authority order. Lower-numbered entries take precedence over higher-numbered entries.

| Order | Document | Location | Authority class |
|-------|----------|----------|-----------------|
| **1** | Constitution | vector-runtime-governance-public | L0a — sole plane law |
| **2** | Supplement 001 | vector-runtime-governance-public | L0a clarification |
| **3** | Blueprint | vector-runtime-governance-public | Orientation only |
| **4** | Governance Contract | vector-signal-chronicle | Ecosystem principles; subordinate to L0a |
| **5** | Unified VECTOR Architecture | vector-signal-chronicle | Ecosystem map; subordinate to L0a |
| **6** | Repository Role | vector-runtime-governance-public | Repository locus; descriptive |
| **7** | This index | vector-runtime-governance-public | Navigation only |

**On conflict:**

Constitution → Supplement → Blueprint take precedence over all ecosystem documents in any repository.

---

## Purpose

Help contributors understand:

- which repository contains which responsibility
- where each class of documentation belongs
- where authoritative information should be read

This document **never redefines** those responsibilities. Plane law, boundary rules, and architecture orientation live in the documents named above.

---

## 1. Repository overview

| Repository | One-line orientation |
|------------|----------------------|
| **vector-runtime-governance-public** | Public documentation home for constitutional, boundary, and architecture-orientation notes for VECTOR runtime governance |
| **AI_Lab** | Runtime governance research prototype and validation surface (implementation, harnesses, and campaign artifacts) |
| **[vector-signal-chronicle](https://github.com/chrono-vector/vector-signal-chronicle)** | Upstream external symbolic observation repository (Plane 2 chronicle locus) |
| **[weaver-forge](https://github.com/chrono-vector/weaver-forge)** | Community collaboration repository and receipt layer |

**Public vs private/local publication boundary (descriptive only):** [REPOSITORY_ROLE.md](../../REPOSITORY_ROLE.md) — section *Publication and Workspace Boundary*. Private/local workspaces (including AI_Lab, the local-only **external_research_archive**, and **job-agent**) are not public authority surfaces and are not expanded here. **external_research_archive** is not a GitHub repository.

Authoritative plane and boundary definitions: [[VECTOR_CONSTITUTION_MULTI_PLANE_ARCHITECTURE]], [[VECTOR_CONSTITUTION_SUPPLEMENT_001_AUTHORITY_BOUNDARIES]].  
Architecture orientation: [[VECTOR_2_0_BLUEPRINT]].

---

## 2. Repository classification

Repositories are classified by **primary documentation / responsibility class**. Classification is navigational only.

| Classification | Repository | Primary documentation |
|----------------|------------|------------------------|
| **Authority** | vector-runtime-governance-public | Constitution, Supplement, Blueprint, and published architecture notes |
| **Observation** | vector-signal-chronicle | External symbolic signals, Observer Events, observation discipline |
| **Runtime** | AI_Lab | Runtime governance research prototype and related research notes |
| **Validation** | AI_Lab | Stage-scoped validation corpora, campaigns, and evidence artifacts |
| **Community** | weaver-forge | Builder participation, receipts, and community evidence layer |

AI_Lab appears under both **Runtime** and **Validation** because those classes co-locate in that repository; they remain distinct classes (see AI_Lab repository documents). They are not merged by this index.

---

## 3. Repository responsibility table

Responsibilities below are **pointers** to existing repository roles. They do not redefine plane ownership. For plane and channel boundaries, read the Constitution and Supplement.

| Repository | Primary role | Contains | Does NOT contain |
|------------|--------------|----------|------------------|
| **vector-runtime-governance-public** | Public constitutional publication and orientation documentation | [[VECTOR_CONSTITUTION_MULTI_PLANE_ARCHITECTURE]], [[VECTOR_CONSTITUTION_SUPPLEMENT_001_AUTHORITY_BOUNDARIES]], [[VECTOR_2_0_BLUEPRINT]], published Stage 4 / Constitutional Stage 5-B notes | Runtime implementation; chronicle signal bodies; community receipts; AI_Lab validation campaign authority |
| **AI_Lab** | Runtime prototype and validation surface | Runtime governance research prototype; Stage 3-5 research and validation notes; validation artifacts and campaigns | Sole L0a constitutional text (read Authority repo); Plane 2 external observation authority (read chronicle repo); community receipt authority |
| **vector-signal-chronicle** | Upstream observation | External signal chronicles; observation guidelines; symbolic-input execution-boundary records; Observer Event / assessment artifacts as maintained there | Runtime governance freeze authority; constitutional plane law; Stage 3 pin / replay freeze authority |
| **weaver-forge** | Community collaboration layer | Receipts; participation templates; builder tracks | Constitutional authority; runtime governance authority; chronicle observation authority |

Cross-repo reading posture for external signals: [[STAGE5B_EXTERNAL_SIGNAL_OBSERVER_ARCHITECTURE]] (vocabulary only). Chronicle ownership detail: chronicle repository documents (e.g. [OBSERVER_GUIDELINES.md](https://github.com/chrono-vector/vector-signal-chronicle/blob/main/OBSERVER_GUIDELINES.md)).

---

## 4. Stage 5-B disambiguation

The label **Stage 5-B** is used in two **different** repositories for **different** scopes. Same name; not the same document class.

| Label | Repository | What the name refers to | Authoritative note (in that locus) |
|-------|------------|-------------------------|-------------------------------------|
| **Constitutional Stage 5-B** | vector-runtime-governance-public | External signal observer architecture - bridge **vocabulary** between chronicle observation and runtime governance | [[STAGE5B_EXTERNAL_SIGNAL_OBSERVER_ARCHITECTURE]] |
| **AI_Lab Stage 5-B** | AI_Lab | Validation corpus / campaign plane for Stage 5 agent-validation work | `STAGE5_B_SCOPE_NOTE` (and related Stage 5-B validation notes in AI_Lab) |

When the label appears without a qualifier, the intended documentation track may be ambiguous.

To avoid ambiguity, refer to either:

- Constitutional Stage 5-B

or

- AI_Lab Stage 5-B

This section is descriptive only and does not redefine either documentation track.

---

## 5. Recommended reading order

```text
README
  ->
Blueprint
  ->
Constitution
  ->
Supplement
  ->
Repository-specific documents
```

| Order | Document | Why |
|-------|----------|-----|
| **1** | [README.md](../../README.md) | Repository entry point |
| **2** | [[VECTOR_2_0_BLUEPRINT]] | Architecture orientation map |
| **3** | [[VECTOR_CONSTITUTION_MULTI_PLANE_ARCHITECTURE]] | Sole L0a authority |
| **4** | [[VECTOR_CONSTITUTION_SUPPLEMENT_001_AUTHORITY_BOUNDARIES]] | Sole boundary clarification |
| **5** | Repository-specific documents | Milestone notes, chronicle guidelines, AI_Lab validation notes, weaver-forge receipts - as needed for the task |

**By repository after the shared stack:**

| Task locus | Primary documentation |
|------------|------------------------|
| Authority / architecture claims | Documents in this repository under `notes/04 VECTOR/` |
| External observation | vector-signal-chronicle entry documents |
| Runtime prototype or validation campaigns | AI_Lab notes and validation artifacts for the relevant stage |
| Community participation / receipts | weaver-forge README and receipt templates |

For Blueprint-internal reading guidance and document-class map, see [[VECTOR_2_0_BLUEPRINT]] Section 6 and Section 9. This index does not duplicate that map.

---

## Explicit non-claims (this index)

This document **does not**:

- Introduce constitutional, boundary, or stage authority
- Restate Five Planes, non-collapse rules, or boundary rules
- Redefine Stage 5, Chronicle, or any plane
- Introduce Stage 6 or implementation detail
- Add MUST / MUST NOT rules
- Replace or duplicate the Constitution, Supplement, or Blueprint

Read the Constitution for law. Read the Supplement for boundary clarification. Read the Blueprint for architecture orientation. Use this index only to find **which repository** holds **which class** of material.

---

### Maintenance note

This index is maintained as a navigational aid.

Changes to constitutional authority, boundary definitions, or architectural principles must be made in the authoritative source documents rather than in this index.

---

*End of VECTOR ecosystem repository authority index.*
