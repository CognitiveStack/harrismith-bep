# Harrismith Fire Station — BIM Execution Plan

> **Status:** Controlled draft — not an approved baseline.
> **Working toward:** BEP Training Baseline 0.1.
> **Authority:** None. Training/reference implementation. Non-contractual.
> **Architecture:** Architecture Baseline v1 (frozen at Gate B). Sections are not
> to be renumbered, merged, split or resequenced.
> **Drafted to date:** Sections 1–3. Sections 4–13 remain scaffold.

All statements in this document are classified as OBSERVED FACT, TRAINING
ASSUMPTION, PROPOSED GOVERNANCE, APPROVED GOVERNANCE or UNRESOLVED DECISION.
See `README.md` section 6.

---

## 1. Document Purpose and Status

### 1.1 Purpose

This BIM Execution Plan (BEP) defines the agreed BIM and information-management
approach for the Harrismith Fire Station project.

It governs how project information is produced, checked, shared, coordinated,
reviewed, authorised, delivered and governed through change.

Its purpose is to make multidisciplinary delivery **controlled, traceable and
repeatable**: every information container has a known originator, a known state,
a known route to the next state, and a known person accountable for moving it
there. Where this document does not yet define something, that gap is recorded
rather than left to local habit.

### 1.2 Document Status

| Field | Value |
|---|---|
| Type | Training / reference BIM Execution Plan |
| Contractual status | **Non-contractual.** Creates no appointment, duty or liability. |
| Current state | Controlled draft |
| Target | BEP Training Baseline 0.1 — **not yet approved** |
| Classification | PROPOSED GOVERNANCE |

This is a post-appointment-style BEP written as a training and reference
implementation. It is structured as a real project BEP would be, but no real
appointment exists behind it.

Governance is **progressively baselined**. Sections are drafted in controlled
increments, reviewed, and only then baselined. A later approved training
baseline supersedes an earlier one; superseded baselines remain in the history
rather than being deleted.

**Development state is not issue state.** Content existing in Git means it has
been *drafted*. It does not mean it has been approved, and it does not mean it
has been issued. A baseline becomes an issued artefact only by the controlled
route in `README.md` section 4 — review, approved baseline, then manual
publication to the CDE. The two states are tracked separately and may legitimately
differ: the repository will normally be ahead of what has been issued.

### 1.3 Scope

**This BEP covers:**

- BIM and information management for the project;
- project organisation and the interfaces between task teams;
- CDE governance — structure, states and transitions;
- information production and sharing;
- multidisciplinary coordination;
- review, authorisation and acceptance interfaces;
- information delivery and exchange;
- project BIM standards and conventions;
- governance, change and exceptions.

**This BEP explicitly does not:**

- create any real contractual appointment, obligation or liability;
- reproduce the content of ISO, SANS or other published standards — it
  references them;
- specify discipline technical design (structural sizing, MEP selection,
  architectural specification);
- define construction means, methods, sequencing or temporary works;
- confer real professional authority on any simulated role holder. A person
  exercising a role in this training implementation does so for training
  purposes only.

### 1.4 Relationship to Supporting Resources

This BEP states *what is required*. The supporting resources hold the detail and
are controlled alongside it. Detail is **not** duplicated here.

| Resource | Holds |
|---|---|
| Information Management Responsibility Matrix | Who is responsible for each information-management function |
| Model / Information Responsibility Matrix | Which task team authors and maintains each model and container |
| Information Delivery Schedule | What is delivered, by whom, in what form, when |
| CDE Workflow & State Strategy | Container states, transitions and the controls on each |
| Coordination & Review Strategy | Coordination cycles, clash and interface management, review and approval route |
| Governance & Decision Register | Decisions taken, assumptions adopted, questions left open |

Four document types are kept distinct, because confusing them is how governance
quietly erodes:

| Document | Role | Authority |
|---|---|---|
| **BEP** | The controlled agreement on how information is managed | Governs, once baselined |
| **BIM Delivery Guide** | Education and onboarding — how to actually do it | Explains only |
| **Working Process** | Questions, proposals, feedback and contribution *before* a governance decision | None |
| **Project Standards** | Detailed technical and information conventions | Governs within its subject, subordinate to the BEP |

A proposal in the Working Process is not governance. It becomes governance only
by being decided, recorded in the Governance & Decision Register, and reflected
in this BEP or a project standard.

### 1.5 Authority and Precedence

Where documents conflict, the higher tier prevails:

1. Actual appointment and client/appointing-party requirements — *where available*
2. Applicable legislation, regulations and adopted standards
3. Project information requirements
4. Approved BEP
5. Supporting controlled resources and project standards
6. Operational procedures and platform configuration

**Important qualification.** In this training implementation, tiers 1 and 3 are
**not currently available**. No appointment documents and no formal information
requirements have been established.

The absence of a higher tier does **not** promote this BEP to the top of the
hierarchy. Missing higher-order requirements are recorded as TRAINING ASSUMPTIONS
or information gaps (section 2.6) and remain visible as such. Where a real
appointment or requirement later exists, it takes precedence over this document
without argument.

This training BEP does not override, reinterpret or satisfy any real contract,
regulation or standard.

**Platform configuration is the lowest tier, not evidence of authority.** How a
CDE, folder, permission or workflow is currently configured describes what the
software is doing. It does not establish that a party is appointed, responsible
or authorised. Authority is never inferred upward from platform configuration.

### 1.6 Document Control

| Field | Value |
|---|---|
| Document title | Harrismith Fire Station — BIM Execution Plan |
| Document identifier | TBD — pending the project naming standard |
| Version | Pre-baseline controlled draft |
| Status | Draft — Sections 1–3 drafted; Sections 4–13 scaffold |
| Maintainer role | TBD — to be defined in Section 5 |
| Approval / authorising role | TBD — to be defined in Section 5 |
| Issue date | Not issued |
| Change history | Git commit history of this repository; governance decisions in the Governance & Decision Register |

Change history is held in version control rather than in a revision table inside
this document. The register records *why* a change was made; Git records *what*
changed and when.

---

## 2. Project Information

### 2.1 Project Identification

The following is **OBSERVED PLATFORM METADATA** recorded from the live Harrismith
project environment. It describes how the project is configured in the platform.
It is **not** a statement of contractual project particulars.

| Attribute | Observed value |
|---|---|
| Project name | Harrismith Fire Station |
| Address | Harrismith Street, Harrismith, Free State 9880, South Africa |
| Platform project number | 02 |
| Platform project type | Government Building |
| Platform time zone | Pretoria |

Observed as unavailable or N/A in platform metadata:

| Attribute | Observed state |
|---|---|
| Project start date | Not available |
| Project end date | Not available |
| Project value | Not available |
| Source / template information | Not available |

**Client / appointing party: not established.** No real client or
appointing-party organisation has been established for this training BEP. A
placeholder client string exists in authoring-model metadata; it is a default
value, it is not authoritative, and it is not used as client information
anywhere in this document. See section 2.3.

**Platform identifiers are not project identifiers.** A platform project number
is an environment configuration value. The project's controlled identifier will
be defined by the project naming standard, which does not yet exist. Where
observed identifier values differ between systems, the difference is recorded as
an information gap (section 2.6), not reconciled by assumption.

### 2.2 Project Context

The Harrismith Fire Station is the anchor project for an end-to-end BIM and
information-management training and reference implementation in a South African
context.

The intent is to demonstrate a realistic multidisciplinary BIM workflow on a
single coherent project — from information production through coordination,
review and controlled delivery — rather than through unrelated software
exercises. Participants work the same project through the whole lifecycle of an
information container, so that governance is experienced as an operating system
of work rather than described in the abstract.

The building type is deliberately modest in scale and genuinely
multidisciplinary, which makes the coordination and information-management
problems real without making them unmanageable.

### 2.3 Project Delivery Context

The following have **not** been established as project facts and are **not**
asserted anywhere in this document:

| Item | Status |
|---|---|
| Named Appointing Party | Not established — TBD |
| Named Lead Delivery Party | Not established — TBD |
| Formal appointments | Not established — TBD |
| Procurement route | Not established — TBD |
| Contract type | Not established — TBD |
| Contractual milestones | Not established — TBD |
| Project budget / value | Not established — TBD |
| Final delivery programme | Not established — TBD |

These are information gaps, not omissions to be filled with plausible values.
Where the training workflow later requires one of them in order to exercise a
process, it may be introduced as an **explicit, labelled TRAINING ASSUMPTION**
and recorded in the Governance & Decision Register. It is never introduced
silently and never presented as a project fact.

### 2.4 BIM / Digital Delivery Context

Established observations and context for the digital delivery environment:

- Autodesk Forma / Data Management is in use as the cloud CDE environment.
- Design Collaboration is configured.
- Revit is present as an authoring environment on the project.
- A Navisworks coordination area exists in the CDE.
- Model Coordination capability is available to the training workflow.
- The project is being used to develop a controlled end-to-end BIM workflow.

**Two limits on how these observations may be read.**

*Presence is not maturity.* That a service exists or is available does not mean
it is fully configured, adopted, or operationally mature. No claim of operational
maturity is made for any service listed above.

*Configuration is not correctness.* That Design Collaboration is configured does
not establish that it is configured correctly, or that its configuration reflects
intended project governance. Observed configuration is evidence of what the
platform is currently doing — nothing more. See section 2.5.

### 2.5 Known Project Constraints

| Constraint | Classification |
|---|---|
| BIM governance is immature and is being developed progressively | OBSERVED FACT |
| Architecture was the only populated direct production stream at the inspected CDE level | OBSERVED FACT |
| Design Collaboration contains an MEP / Structural team-space mapping discrepancy | OBSERVED FACT — unresolved |
| Common Files areas for Naming Standards, Coordinates, Titleblocks, Templates and Reference Information were observed empty at discovery | OBSERVED FACT |

**On the single populated production stream.** Only Architecture was observed as
a populated direct production stream at the level inspected. This is a statement
about what was observed, at one level, at one time. Other disciplines must **not**
be described as absent from the project, uncommitted, or inactive merely because
direct production files were not observed at that level. Absence of observation
is not observation of absence.

**On the MEP / Structural mapping discrepancy.** A discrepancy in the MEP /
Structural Design Collaboration team-space mapping was observed during discovery.
It remains **unresolved** and is carried as **UD-001** in the Governance &
Decision Register. It is recorded here as observed and is **not** corrected,
worked around, or quietly normalised in this document or in any supporting
resource. No decision has been taken on whether it is retained, changed or
worked around, or on who owns that decision.

**On empty Common Files areas.** The standards areas were observed empty at
discovery. This constrains the project: there is currently no published naming
standard, coordinate standard, titleblock set or template set to reference.
Section 11 and the `standards/` directory address this in a later increment.

**Current configuration is not intended governance.** Throughout this document,
what the platform currently does and what governance intends are held apart. The
gap between them is the work; collapsing the two would hide it.

### 2.6 Training Assumptions and Information Gaps

**The rule.** A TRAINING ASSUMPTION is a deliberate construct adopted so that
the BIM management workflow can be exercised. It is a scaffold for learning, not
evidence. No training assumption constitutes evidence of an actual appointment,
an actual project fact, or an actual professional authority. An assumption is
promoted to OBSERVED FACT only by verification, and the promotion is recorded —
never silent.

**Training assumptions adopted to date.**

| Ref | Assumption | Purpose |
|---|---|---|
| TA-01 | The implementation proceeds *as if* a post-appointment context exists, so that a post-appointment BEP can be exercised. No appointment exists. | Allows the BEP structure to be developed and taught realistically. |
| TA-02 | Participants exercise defined roles in a simulated capacity. No participant holds real professional authority or duty by virtue of a role in this implementation. | Allows roles, responsibility and authorisation to be exercised without implying real authority. |

These are to be transcribed to the Governance & Decision Register in a later
controlled increment.

**Current information gaps.** These are categories of missing information, not
questions answered here:

- appointing-party identity;
- lead-delivery-party holder;
- discipline and company appointments;
- procurement and contract strategy;
- formal delivery milestones;
- formal information requirements;
- project budget / value;
- final project standards;
- final CDE and team mapping.

Unresolved decisions are referred to the **Governance & Decision Register** and
resolved there by explicit recorded decision. They are not resolved in this
section, and they are not resolved by drafting around them.

---

## 3. BIM and Information Management Objectives

### 3.1 BIM Management Objective

> Establish a controlled, traceable and repeatable information-management
> workflow that enables multidisciplinary project information to be produced,
> checked, shared, coordinated, reviewed and published with clearly defined
> responsibility.

Every objective, role, process and standard in the remainder of this BEP exists
to serve this objective.

### 3.2 Information Management Objectives

| Ref | Objective | Intent |
|---|---|---|
| **IM-01** | Controlled CDE | Establish controlled information states and exchange routes within the CDE. |
| **IM-02** | Clear responsibility | Make originators, task-team responsibility and governance authority clear. |
| **IM-03** | Reliability before exchange | Require appropriate checking and authorisation before information progresses. |
| **IM-04** | Multidisciplinary coordination | Enable coordinated review of information originating from separate disciplines and task teams. |
| **IM-05** | Traceability | Maintain traceability of information state, origin, version/revision, responsibility, review and exchange. |
| **IM-06** | Reliable information delivery | Plan and deliver information appropriate to its intended purpose and recipient. |
| **IM-07** | Auditable and improvable governance | Record decisions, deviations, changes and lessons so the information-management system can improve without losing control. |
| **IM-08** | BIM capability and adoption | Build BIM capability across the delivery team through onboarding, demonstrations, guided exercises, feedback and progressive adoption. |

### 3.3 BIM Uses

The BIM uses within the current scope of this BEP are:

- model and information authoring;
- multidisciplinary model coordination;
- clash and interface review;
- issue management;
- drawing and document production;
- information exchange;
- controlled CDE delivery.

**Outside current scope.** Quantity takeoff, cost estimating, construction
management, asset management, handover and standards verification are **not**
current requirements and are **not** part of the current baseline scope. They
are noted only as uses that may be considered in a later module, following an
explicit decision to extend scope. Nothing in this BEP should be read as
committing to them.

### 3.4 Success Principles

This BEP succeeds when the following are true in practice:

- participants know where trusted information is found, and can say why it is
  trusted;
- responsibilities and state transitions are understandable to the people who
  have to perform them;
- work in progress is not accidentally consumed as though it were authorised
  shared information;
- information is checked before controlled exchange, not after;
- coordination findings are **managed to resolution** — assigned, tracked,
  resolved and verified — rather than merely counted;
- the purpose of a delivery and the authority under which it was made are
  traceable after the fact;
- deviations and changes are visible rather than absorbed;
- participants measurably improve their ability to operate the workflow over
  time.

**Success is not** a clash count of zero, nor all information residing in any
single authoring tool. A zero-clash report says nothing about whether
coordination happened, and tool consolidation is not information management.

### 3.5 Evidence of Achievement

Achievement is demonstrated by evidence produced through the workflow, not by
assertion. The following are the forms of evidence that **will** demonstrate
achievement. **None is claimed as complete at this time.**

| Objective | Evidence that will demonstrate achievement |
|---|---|
| IM-01 | CDE workflow demonstrated end to end in the live training project |
| IM-02 | Responsibility matrices populated and demonstrably used in delivery |
| IM-03 | Controlled sharing and consumption demonstrated, with checking evidenced before exchange |
| IM-04 | A coordination cycle completed using approved inputs |
| IM-05 | Delivery and exchange records traceable to origin, state and responsibility |
| IM-06 | Delivery records showing purpose and recipient, traceable after the fact |
| IM-07 | Governance decisions recorded; observed platform configuration checked against intended governance |
| IM-08 | Participant onboarding and workshops completed; assigned issues resolved and verified by participants |

Evidence is recorded as it is produced. No item above is treated as achieved
until evidence exists to support the claim.

---

## 4. Project Organisation and Task Teams

TBD — To be developed.

## 5. Information Management Roles and Responsibilities

TBD — To be developed.

Supported by `supporting/information-management-responsibility-matrix.md`.

## 6. Common Data Environment Strategy

TBD — To be developed.

Supported by `supporting/cde-workflow-state-strategy.md`.

## 7. Information Production and Sharing

TBD — To be developed.

Supported by `supporting/model-information-responsibility-matrix.md`.

## 8. Model and Information Coordination

TBD — To be developed.

Supported by `supporting/coordination-review-strategy.md`.

## 9. Review, Approval and Authorisation

TBD — To be developed.

Supported by `supporting/coordination-review-strategy.md`.

## 10. Information Delivery and Exchange

TBD — To be developed.

Supported by `supporting/information-delivery-schedule.md`.

## 11. Standards and Project Conventions

TBD — To be developed.

Supported by the project standards in `standards/`.

## 12. Governance, Change and Exceptions

TBD — To be developed.

Supported by `supporting/governance-decision-register.md`.

## 13. Controlled References

TBD — To be developed.
