# Harrismith Fire Station — BIM Management / BIM Execution Plan

Controlled authoring repository for the Harrismith Fire Station BIM Management
and BIM Execution Plan (BEP) training implementation.

**Status:** The management-document system is **FOR REVIEW** as the Training
Baseline 0.1 Candidate. Nothing is approved, baselined or issued. Current
maturity is stated in section 5.

---

## 1. Purpose

This repository is the **authoring source** for the Harrismith Fire Station BIM
Execution Plan and its supporting information-management resources.

It exists to:

- hold the approved document architecture under version control;
- provide a reviewable history of how information-management governance was
  developed;
- separate *drafting and review* from *issue and publication*;
- support a training implementation in which the reasoning behind each
  governance decision is explicit and traceable.

---

## 2. Authoring source vs issued CDE artefacts

This is the single most important distinction in this repository.

| | Authoring source | Issued artefact |
|---|---|---|
| **Location** | this Git repository | Autodesk Common Data Environment |
| **Nature** | drafts, working text, proposals | approved, issued, controlled deliverables |
| **Authority** | none until approved | contractual / project authority |
| **Change control** | Git commits and review | CDE state and revision control |

Content in this repository carries **no project authority** until it has been
reviewed, approved, and published into the CDE through the controlled route
described in section 4.

### 2.1 Prohibition on direct CDE writes

The Autodesk Desktop Connector / ACCDocs tree is **out of bounds** for this
repository and for any tooling operating on it.

There must be **no** symlink, junction, bind mount, automatic synchronisation,
or other filesystem link between this repository and the Autodesk CDE.

Specifically prohibited from this repository:

- reading from, writing to, creating, renaming, moving or deleting anything in
  the Desktop Connector / ACCDocs tree;
- any automated or scripted synchronisation into the CDE;
- any change to Autodesk Forma, ACC, Desktop Connector, Revit, Navisworks or
  other external project systems.

Publication into the CDE is a **manual, controlled, human-performed** act.

---

## 3. Repository architecture

```
harrismith-bep/
├── README.md        repository governance and safety boundary
├── bep/             the main BIM Execution Plan
├── supporting/      the six supporting management resources
├── working/         working process, workshop material, in-progress thinking
├── guidance/        the BIM Delivery Guide
├── standards/       referenced project standards
├── output/          generated / project-facing artefacts (NOT authoring source)
└── docs/            repository-level documentation and process notes
```

### 3.1 Main BIM Execution Plan — `bep/`

Approved section architecture (Architecture Baseline v1):

1. Document Purpose and Status
2. Project Information
3. BIM and Information Management Objectives
4. Project Organisation and Task Teams
5. Information Management Roles and Responsibilities
6. Common Data Environment Strategy
7. Information Production and Sharing
8. Model and Information Coordination
9. Review, Approval and Authorisation
10. Information Delivery and Exchange
11. Standards and Project Conventions
12. Governance, Change and Exceptions
13. Controlled References

### 3.2 Supporting management resources — `supporting/`

1. Information Management Responsibility Matrix
2. Model / Information Responsibility Matrix
3. Information Delivery Schedule
4. CDE Workflow & State Strategy
5. Coordination & Review Strategy
6. Governance & Decision Register

### 3.3 Working, guidance and standards

- `working/` — the Working Process and workshop material. Working thinking,
  not governance.
- `guidance/` — the BIM Delivery Guide: practical, explanatory support for
  delivery teams.
- `standards/` — referenced project standards for Naming, Coordinates,
  Titleblocks, and Templates / authoring conventions.

### 3.4 Output — `output/`

`output/` holds **generated and project-facing artefacts** produced from the
authoring source.

`output/` is **not** the authoring source. It is never edited directly, and
nothing in it is authoritative merely by being present.

---

## 4. Controlled route to the CDE

```
local Git authoring source
    → review
    → approved baseline
    → manual controlled publication to Autodesk Forma / Data Management
```

Each arrow is a deliberate, recorded step. No step is automated in this
repository.

---

## 5. Gate status

| Gate | Status |
|---|---|
| Discovery Gate A | Complete |
| Architecture Gate B | Complete — frozen as **Architecture Baseline v1** |
| Implementation Increment 1 | Complete — repository scaffold |
| Implementation Increment 2A | Complete — BEP sections 1–3 drafted, revised after review |
| Implementation Increment 2B | Complete — BEP sections 4–5 drafted |
| Implementation Increment 2C | Complete — BEP sections 6–7 drafted |
| Implementation Increment 2D | Complete — BEP sections 8–10 drafted |
| Implementation Increment 2E | Complete — BEP sections 11–13 drafted; main BEP draft complete |
| Implementation Increment 3A | Complete — Governance & Decision Register and Information Management Responsibility Matrix populated as controlled drafts |
| Implementation Increment 3B | Complete — Model / Information Responsibility Matrix and Information Delivery Schedule populated as controlled drafts |
| Implementation Increment 3C | Complete — CDE Workflow & State Strategy populated as a controlled draft |
| Implementation Increment 3D | Complete — Coordination & Review Strategy populated as a controlled draft |
| Implementation Increment 4 | Complete — Working Process implemented as a controlled draft |
| Implementation Increment 5 | Complete — BIM Delivery Guide implemented as a Controlled Draft |
| Implementation Increment 6A | Complete — cross-document consistency audit performed; result **PASS WITH FINDINGS** |
| Implementation Increment 6B | Complete — audit corrections applied |
| Implementation Increment 7A (first attempt) | Halted at read-only pre-flight — further stale statements found; no candidate created |
| Implementation Increment 6C | Complete — pre-candidate stale-language corrections applied |
| Implementation Increment 7A (re-attempt) | Complete — **Training Baseline 0.1 Candidate** prepared for review |

All 13 main BEP sections now contain substantive draft content.

This means the main BEP is **structurally complete**. It does not mean the BEP is
approved, baselined, issued to the CDE, validated against the live project, or
ready for contractual use.

All six supporting management resources are substantively populated: the
Governance & Decision Register, the Information Management Responsibility
Matrix, the Model / Information Responsibility Matrix, the Information Delivery
Schedule, the CDE Workflow & State Strategy and the Coordination & Review
Strategy. The **Working Process** and the **BIM Delivery Guide** are implemented
as companion documents. The project standards remain unpopulated.

The **Training Baseline 0.1 Candidate** has been prepared. Its scope, authority
boundary and exclusions are recorded in
[`docs/Training-Baseline-0.1-Candidate.md`](docs/Training-Baseline-0.1-Candidate.md).

The candidate status is **FOR REVIEW**. That is a review designation, not an
approval:

- **the Training Baseline 0.1 Candidate is NOT approved;**
- **candidate review has not yet been carried out;**
- **live-project validation has not been performed;**
- **Gate C has not passed;**
- **nothing has been published as an approved BEP baseline;**
- **the project standards remain Not established and are outside the candidate.**

Architecture Baseline v1 is **frozen**. The document architecture recorded in
section 3 is not to be redesigned during implementation increments. Proposed
changes to the architecture are raised as an UNRESOLVED DECISION in
`supporting/governance-decision-register.md` and resolved through an explicit
gate, not through incremental editing.

---

## 6. Statement classification

All content in this repository classifies its statements using these terms,
consistently and explicitly:

| Term | Meaning |
|---|---|
| **OBSERVED FACT** | Verified from the live project or a controlled source. |
| **TRAINING ASSUMPTION** | Adopted for the training implementation; not verified as project truth. |
| **PROPOSED GOVERNANCE** | Drafted for consideration. Carries no authority. |
| **APPROVED GOVERNANCE** | Reviewed and approved. Carries authority within its scope. |
| **UNRESOLVED DECISION** | Known open question. Explicitly not answered. |

Two standing rules:

- **Assumptions are never silently converted into facts.** A TRAINING
  ASSUMPTION is promoted to OBSERVED FACT only by verification, and the
  promotion is recorded.
- **Known live-project discrepancies are never silently corrected.** Where the
  live project differs from what governance would suggest, the discrepancy is
  recorded as an OBSERVED FACT and carried as an UNRESOLVED DECISION until it
  is deliberately resolved.

---

## 7. Development approach

This repository is developed through **scoped controlled increments**. The method
below is an enduring working rule, not a description of any particular phase.

- **Each increment has an explicitly defined and approved scope.** Work stays
  inside it.
- **Repository state is verified before modification.** Branch, worktree and
  commit are checked at pre-flight, and unexpected state stops the increment.
- **A contradiction causes STOP and REPORT, not silent repair.** Where a document
  appears to conflict with another controlled resource, the conflict is raised
  rather than quietly patched in whichever file is open.
- **Changes are made as atomic commits** and are reviewed before the next
  increment begins.
- **Controlled resources declare their own status, version and authority.**
  Reference from one document does not constitute approval of another.
- **Later phases may revise any resource through governed change**, including
  supersession or withdrawal.
- **Current maturity is stated by section 5 and the gate table above** — not by
  wording embedded in the body of controlled documents.

No increment beyond the one currently approved is to be started without explicit
approval.
