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
| **[vector-core](https://github.com/chrono-vector/vector-core)** | Sanitized Public VECTOR v0 **reference** (Apache-2.0). Architecture, schemas, validators, synthetic fixtures. Not operational authorization. Not this repository. |
| **AI_Lab** | Runtime governance research prototype and validation surface (implementation, harnesses, and campaign artifacts) |
| **[vector-signal-chronicle](https://github.com/chrono-vector/vector-signal-chronicle)** | Upstream external symbolic observation repository (Plane 2 chronicle locus) |
| **[cad-vortex](https://github.com/chrono-vector/cad-vortex)** | VECTOR Plane 2 external-observation intake / normalization component (private repository; frozen v1 plus accepted additive v2 claimed lineage plus additive opt-in v3 emitted-path schema, with limitations; not ERA-verified) |
| **[weaver-forge](https://github.com/chrono-vector/weaver-forge)** | Community collaboration repository and receipt layer; host of VECTOR Package Ingress v0 |

**Public vs private/local publication boundary (descriptive only):** [REPOSITORY_ROLE.md](../../REPOSITORY_ROLE.md) — section *Publication and Workspace Boundary*. Private/local workspaces (including AI_Lab, the private **cad-vortex** repository, the local-only **external_research_archive**, and **job-agent**) are not public authority surfaces. **vector-core** is a public sanitized **reference** and is not constitutional L0a, not a runtime, and not a full operational release. **external_research_archive** is a preservation / provenance archive and is **not** a GitHub repository. **cad-vortex** is a distinct GitHub repository (currently private) for structured Plane 2 intake / normalization; it is not the preservation archive, not Chronicle authority, and not a public authority surface. Listing a repository here does not grant it execution authority.

Authoritative plane and boundary definitions: [[VECTOR_CONSTITUTION_MULTI_PLANE_ARCHITECTURE]], [[VECTOR_CONSTITUTION_SUPPLEMENT_001_AUTHORITY_BOUNDARIES]].  
Architecture orientation: [[VECTOR_2_0_BLUEPRINT]].

---

## 2. Repository classification

Repositories are classified by **primary documentation / responsibility class**. Classification is navigational only.

| Classification | Repository | Primary documentation |
|----------------|------------|------------------------|
| **Authority** | vector-runtime-governance-public | Constitution, Supplement, Blueprint, and published architecture notes |
| **Public reference** | vector-core | Sanitized Public VECTOR v0 reference: architecture, schemas, validators, synthetic fixtures |
| **Observation** | vector-signal-chronicle | External symbolic signals, Observer Events, observation discipline |
| **Intake** | cad-vortex | Structured Plane 2 intake, normalization, provenance, and quarantine labeling |
| **Runtime** | AI_Lab | Runtime governance research prototype and related research notes |
| **Validation** | AI_Lab | Stage-scoped validation corpora, campaigns, and evidence artifacts |
| **Community** | weaver-forge | Builder participation, receipts, community evidence layer, and VECTOR Package Ingress v0 |

AI_Lab appears under both **Runtime** and **Validation** because those classes co-locate in that repository; they remain distinct classes (see AI_Lab repository documents). They are not merged by this index.

**Intake** (cad-vortex) is not **Observation** (vector-signal-chronicle). Structured intake / normalization is not Chronicle authority, not Observer Review, and not preservation-archive custody. **external_research_archive** remains a local preservation / provenance archive and is not classified here as a GitHub repository.

---

## 3. Repository responsibility table

Responsibilities below are **pointers** to existing repository roles. They do not redefine plane ownership. For plane and channel boundaries, read the Constitution and Supplement.

| Repository | Primary role | Contains | Does NOT contain |
|------------|--------------|----------|------------------|
| **vector-runtime-governance-public** | Public constitutional publication and orientation documentation | [[VECTOR_CONSTITUTION_MULTI_PLANE_ARCHITECTURE]], [[VECTOR_CONSTITUTION_SUPPLEMENT_001_AUTHORITY_BOUNDARIES]], [[VECTOR_2_0_BLUEPRINT]], published Stage 4 / Constitutional Stage 5-B notes | Runtime implementation; chronicle signal bodies; community receipts; AI_Lab validation campaign authority; Public VECTOR v0 reference tree |
| **vector-core** | Sanitized Public VECTOR v0 reference | Public architecture/nonclaim docs; public-safe schemas/validators; synthetic fixtures; path-independent CAD copy | Operational authorization; Evidence admission; replay authorization; Weaver execution; Stage 6; Chronicle `signals/`; ERA dumps; private operational artifacts |
| **AI_Lab** | Runtime prototype and validation surface | Runtime governance research prototype; Stage 3-5 research and validation notes; validation artifacts and campaigns | Sole L0a constitutional text (read Authority repo); Plane 2 external observation authority (read chronicle repo); community receipt authority |
| **vector-signal-chronicle** | Upstream observation | External signal chronicles; observation guidelines; symbolic-input execution-boundary records; Observer Event / assessment artifacts as maintained there | Runtime governance freeze authority; constitutional plane law; Stage 3 pin / replay freeze authority |
| **cad-vortex** | Plane 2 external-observation intake / normalization | frozen v1 local UTF-8 intake; additive v2 caller-supplied claimed ERA lineage (accepted with limitations at `53fdebb7175fe419969c5cbd5120752f50699a0f`); additive opt-in v3 emitted-path schema present at `8e3c1c950946638ff104a85c7708f919eaeeafc0`; current private-satellite HEAD `ebc442d5695482952373acfeaa76e2d35731f095`; claimed lineage is **not ERA-verified**; observation-candidate output; `BRIDGE_INADMISSIBLE` posture | Chronicle authority; ERA verification authority; automatic Chronicle record write; AI_Lab runtime dependency; Guard / Gate / executor; External Execution Control Bridge; network / live intake; production readiness; execution authority |
| **weaver-forge** | Community collaboration layer | Receipts; participation templates; builder tracks | Constitutional authority; runtime governance authority; chronicle observation authority |

Cross-repo reading posture for external signals: [[STAGE5B_EXTERNAL_SIGNAL_OBSERVER_ARCHITECTURE]] (vocabulary only). Chronicle ownership detail: chronicle repository documents (e.g. [OBSERVER_GUIDELINES.md](https://github.com/chrono-vector/vector-signal-chronicle/blob/main/OBSERVER_GUIDELINES.md)).

### CAD-Vortex (index entry only)

**cad-vortex** ([https://github.com/chrono-vector/cad-vortex](https://github.com/chrono-vector/cad-vortex), currently private) is a VECTOR Plane 2 external-observation intake / normalization component. This index records that role. It introduces **no new authority**. Listing CAD-Vortex here does **not** grant execution authority, Chronicle authority, runtime-governance authority, or production readiness.

**Current implementation status:** private GitHub repository exists. Frozen v1 remains. Additive v2 **caller-supplied claimed ERA lineage** remains accepted with limitations at `53fdebb7175fe419969c5cbd5120752f50699a0f`. Additive opt-in v3 emitted-path schema is present at `8e3c1c950946638ff104a85c7708f919eaeeafc0` and does not silently replace v2. Current private-satellite HEAD: `ebc442d5695482952373acfeaa76e2d35731f095`. Claimed lineage is **not ERA-verified**. No ERA verification authority. No Chronicle authority. No execution authority. Not production. This HEAD refresh is orientation only and introduces **no new authority**.

**Current behavior (orientation, not a specification):** deterministic local UTF-8 text intake; optional caller-supplied claimed ERA lineage on that path; raw SHA-256 presented-byte identity; deterministic observation-candidate ID; provenance capture; structural screening / admissibility labels; observation-candidate output; `BRIDGE_INADMISSIBLE` posture.

**Explicit boundaries (descriptive):** not Chronicle authority; no automatic Chronicle record write; no ERA verification authority; no AI_Lab runtime dependency; no Guard / Gate / executor; no External Execution Control Bridge; no network / live intake; no production readiness; no execution authority.

These surfaces remain distinct:

| Surface | Distinct role |
|---------|----------------|
| **external_research_archive** | Preservation / provenance archive (local-only; not a GitHub repository) |
| **cad-vortex** | Structured Plane 2 intake / normalization |
| **vector-signal-chronicle** | Chronicle / External Observation record and Observer Review |
| **AI_Lab** | Research / verification / validation |
| **vector-runtime-governance-public** | Public governance / authority orientation |
| **vector-core** | Public sanitized VECTOR v0 reference (not operational authorization) |
| **weaver-forge** | Independent / community receipts and collaboration; VECTOR Package Ingress v0 |

**Architecture relationship (documentation intent only — not a live pipeline):**

```text
external / preserved source material
  ->
CAD-Vortex
  structured intake / normalization / provenance / quarantine labeling
  ->
observation candidate
  ->
future / manual separately-authorized Chronicle handoff
  ->
Chronicle / External Observation
  ->
AI_Lab verification / validation
```

CAD-Vortex → Chronicle is **not** an active automatic path. Any later Chronicle handoff remains future or manual and separately authorized.

CAD-Vortex belongs primarily to **Plane 2**.

Existing distinctions remain in force; this index does not amend them:

- Meaning is not evidence.
- Observation is not interpretation.
- Interpretation is not verification.
- Verification is not execution.
- Gate is not execution.

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
| Sanitized Public VECTOR v0 reference | [vector-core](https://github.com/chrono-vector/vector-core) README / architecture / schemas (not operational authorization) |
| External observation | vector-signal-chronicle entry documents |
| Structured Plane 2 intake / observation candidates | cad-vortex repository documents (private); this index for locus only |
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
- Grant CAD-Vortex execution authority, Chronicle authority, or production readiness by listing it
- Grant vector-core operational authorization, Evidence admission, replay authorization, Weaver execution, or Stage 6 by listing it
- Imply automatic CAD-Vortex → Chronicle write, Guard / Gate / executor wiring, or External Execution Control Bridge activation

Read the Constitution for law. Read the Supplement for boundary clarification. Read the Blueprint for architecture orientation. Use this index only to find **which repository** holds **which class** of material.

---

### Maintenance note

This index is maintained as a navigational aid.

Changes to constitutional authority, boundary definitions, or architectural principles must be made in the authoritative source documents rather than in this index.

---

*End of VECTOR ecosystem repository authority index.*
