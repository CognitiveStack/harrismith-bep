# Harrismith Fire Station — BIM Execution Plan

> **Status:** Controlled draft.
> **Target baseline:** BEP Training Baseline 0.1 — in development, **not approved**.
> **Issued to CDE:** No.
> **Authority:** None. Training/reference implementation. Non-contractual.
> **Architecture:** Architecture Baseline v1 (frozen at Gate B). Sections are not
> to be renumbered, merged, split or resequenced.
> **Drafted to date:** Sections 1–13. All approved sections now contain
> substantive draft content. Structurally complete is **not** approved,
> baselined, issued or validated against the live project.

Statements in this document are individually classified as OBSERVED FACT,
TRAINING ASSUMPTION, PROPOSED GOVERNANCE, APPROVED GOVERNANCE or UNRESOLVED
DECISION. The document deliberately contains several of these at once, so no
single classification applies to it as a whole. See `README.md` section 6.

---

## 1. Document Purpose and Status

### 1.1 Purpose

This BIM Execution Plan (BEP) is being developed to define the BIM and
information-management approach for the Harrismith Fire Station
training/reference implementation.

Once approved as a training baseline, it will govern how project information is
produced, checked, shared, coordinated, reviewed, authorised, delivered and
governed through change. It does not do so at present: its status is controlled
draft and its authority is none (section 1.2).

Its aim is to make multidisciplinary delivery **controlled, traceable and
repeatable**. The intended outcome of the workflow it defines is that each
information container has a known originator, a known state, a known route to
the next state, and a known role accountable for moving it there. Where this
document does not yet define something, that gap is recorded rather than left to
local habit.

### 1.2 Document Status

| Field | Value |
|---|---|
| Document status | Controlled draft |
| Target baseline | BEP Training Baseline 0.1 — in development, **not approved** |
| Authority | None — training/reference implementation, non-contractual |
| Issued to CDE | No |
| Architecture | Architecture Baseline v1 — frozen |
| Type | Training / reference BIM Execution Plan |
| Contractual status | Creates no appointment, duty or liability |

No single statement classification is assigned to this document. It contains
OBSERVED FACT, TRAINING ASSUMPTION, PROPOSED GOVERNANCE and UNRESOLVED DECISION
statements by design, and each is classified where it appears.

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
| Status | Draft — Sections 1–13 drafted; no section approved |
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
appointing-party organisation has been established for this training BEP.

An authoring-model client metadata value was observed. Its provenance, its
authority and its relationship to any actual Appointing Party have **not** been
established. It is therefore not used as authoritative client information
anywhere in this document, and its value is not reproduced here. See section 2.3.

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

Harrismith Fire Station is the single coherent anchor for that multidisciplinary
workflow.

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

| Statement | Classification |
|---|---|
| Governance artefacts and configuration observed during discovery remain incomplete | OBSERVED FACT |
| Governance will be developed progressively through controlled baselining | PROPOSED GOVERNANCE — training strategy |
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
Section 11 defines how project standards are applied; the standards themselves
are held in `standards/` and remain not established.

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
| TA-03 | The delivery organisation and task-team structure defined in Section 4 is a training organisation model. It does not constitute actual appointment of any organisation, company, consultant, contractor or professional role. | Allows organisation, task-team, discipline and information-management responsibility interfaces to be exercised realistically. |

These assumptions are also recorded in the Governance & Decision Register, which
is separately controlled and declares its own status. Recording an assumption
does not make it a project fact.

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

### 4.1 Delivery Organisation

The intended training delivery organisation is:

```
OWNER / APPOINTING PARTY
    |
    +-- Lead Delivery Party
    |
    +-- Consultants
    |    +-- Architectural Consultant
    |    +-- Structural Consultant
    |    +-- MEP Consultant
    |    |    +-- Mechanical task team
    |    |    +-- Electrical task team
    |    |    +-- Plumbing task team
    |    |
    |    +-- Fire Consultant
    |         +-- Fire task team
    |
    +-- Construction
         +-- General Contractor
              +-- Mechanical Trade Contractor
              +-- Electrical Trade Contractor
              +-- Plumbing Trade Contractor
              +-- Fire Trade Contractor, where required
```

**TA-03 — TRAINING ASSUMPTION.** This is a *training organisation model*. It is
adopted so that the BIM management workflow — multiple parties, multiple task
teams, real interfaces between them — can be exercised realistically rather than
simulated with a single undifferentiated team.

It is not an appointment structure. Specifically:

- No organisation has been appointed to any position shown.
- No company names are assigned, and none are to be invented.
- **Appointing Party identity: TBD.**
- **Lead Delivery Party holder: TBD.**

TA-03 is recorded with TA-01 and TA-02 in the assumptions table at section 2.6,
and with them in the Governance & Decision Register.

### 4.2 Project Parties

A *party* is an organisation-level concept. The intended party categories are:

| Party category | Position in the model |
|---|---|
| Owner / Appointing Party | Client side |
| Lead Delivery Party | Delivery coordination |
| Architectural Consultant | Consultant |
| Structural Consultant | Consultant |
| MEP Consultant | Consultant |
| Fire Consultant | Consultant |
| General Contractor | Construction |
| Trade contractors | Construction, as required |

No actual company is assigned to any category.

**Five concepts, deliberately not interchangeable.** Confusing these is the most
common way information-management responsibility becomes untraceable:

| Concept | What it is |
|---|---|
| **Party** | An organisation |
| **Task team** | The group producing a defined package of information |
| **Discipline** | A technical classification of information |
| **Autodesk collaboration team** | A platform construct |
| **IM role** | A governance function |

These may map to one another — often they do — but a mapping is not an identity.
One party may host several task teams; one task team may produce information in
more than one discipline; a platform team may or may not correspond to either.
Each mapping is a decision to be recorded, not an assumption to be inherited.

### 4.3 Task-Team Structure

A task team produces a defined package of information. The intended training
task-team model is:

| Party | Task team(s) |
|---|---|
| Architectural Consultant | Architectural task team |
| Structural Consultant | Structural task team |
| MEP Consultant | Mechanical task team; Electrical task team; Plumbing task team |
| Fire Consultant | Fire task team |
| General Contractor | Contractor management / coordination function |
| Trade contractors | Mechanical, Electrical, Plumbing and Fire trade-contractor task teams, each **when introduced** |

Covered by TA-03. Three points matter and are easily got wrong:

**Task teams are not companies.** Mechanical, Electrical and Plumbing are task
teams and disciplines that may sit within a **single MEP Consultant
organisation**. The intended model does not create six separate consultant
companies from the six discipline codes, and the discipline codes in section 4.4
must not be read that way.

**Fire is separate from MEP.** In the intended training organisation the Fire
Consultant is a distinct party, not an MEP sub-team.

**Trade contractors sit in the construction structure.** They belong to the
General Contractor's delivery structure. They are not to be treated as design
consultants, and their task teams exist only once introduced into the simulated
workflow.

**Task-team structure evolves by stage.** The set of active task teams at design
stage differs from the set at construction stage. Task teams are introduced,
combined or stood down as the project moves; each such change follows section 4.8.

### 4.4 Discipline Structure

| Code | Discipline |
|---|---|
| ARC | Architecture |
| STR | Structural |
| MEC | Mechanical |
| ELE | Electrical |
| PLM | Plumbing |
| FIR | Fire |

A discipline code identifies the **information domain** of a container. That is
all it does.

A discipline code does **not**, by itself, identify:

- the organisation responsible;
- the task team that produced the information;
- the author;
- a Design Collaboration team;
- contractual responsibility.

Detailed naming syntax — field order, separators, permitted values — belongs to
the Naming Standard (`standards/naming/`), not to this section. That standard
does not yet exist; see section 2.5.

### 4.5 Digital Collaboration Team Structure

An Autodesk Design Collaboration team is a **platform construct**. It is not an
organisation, not a discipline, not a task team, and not a professional
appointment. Membership of one confers no authority of any kind.

**AS-FOUND observations from discovery.** The following are OBSERVED FACTS
recording the state found at Gate A. They are recorded, not endorsed.

Observed Design Collaboration teams:

- Architecture
- MEP Consultant
- Structural

Observed team-space bindings:

| Observed Design Collaboration team | Observed bound WIP space |
|---|---|
| Architecture | Architecture WIP space |
| MEP Consultant | Structural-labelled WIP space |
| Structural | MEP-labelled WIP space |

The second and third bindings constitute the previously recorded discrepancy
**UD-001**, which **remains unresolved**. They are recorded exactly as observed.
They are **not** corrected here, and no intended replacement binding is proposed
by this BEP. See section 4.7.

Further observations, at high level:

| Observation | Classification |
|---|---|
| A Contractors WIP area exists in the CDE | OBSERVED FACT |
| No corresponding Contractors Design Collaboration team was established in the discovery evidence | OBSERVED FACT |
| The Design Collaboration Coordination Space was not configured in the observed discovery state | OBSERVED FACT |

These are observations of a point in time. None of them is a permanent
requirement, and none should be read as one. No additional Design Collaboration
team is created by this document, and this document does **not** state that MEC,
ELE, PLM and FIR require separate Design Collaboration teams. Whether platform
teams should map one-to-one to task teams is an open question, not a settled one.

No personal or member information is recorded here.

### 4.6 Information Management Functions

Four information-management functions are introduced at organisation level. They
are defined in Section 5; only their existence and independence are established
here.

| Function | Concern |
|---|---|
| BIM Manager | Governance of the information-management framework |
| BIM Coordinator | Operational multidisciplinary coordination |
| CDE Administration | Implementation of approved governance in the platform |
| Lead Delivery Party | Project-level delivery coordination |

These are **functions, not job titles and not people**. In a project of this
size, one participant may carry more than one of them; in a larger project each
might be carried by a different organisation.

**Combining functions does not merge them.** If one participant is both BIM
Manager and CDE Administrator, the governance decision and its implementation
are still two separate acts, and the participant must know which one they are
performing. See section 5.11.

### 4.7 Current-State vs Intended-State Configuration

Three things are held apart throughout this BEP. Collapsing them is how
undocumented configuration quietly becomes de facto governance:

| Concept | What it is | Status |
|---|---|---|
| **As-found platform configuration** | What the platform was observed doing at Gate A | Evidence |
| **Intended governance** | What this BEP decides should be the case | A controlled decision |
| **Implemented configuration** | What the platform does after an approved decision is applied | The operational result of a decision |

As-found configuration is evidence of current behaviour. It is not a decision,
not a justification, and not a requirement. Intended governance becomes binding
only through approval. Implemented configuration is legitimate only when it
traces back to an approved decision.

**Worked example — UD-001.**

| | |
|---|---|
| Observed | The MEP Consultant and Structural Design Collaboration team-space bindings appear cross-bound (section 4.5) |
| Current status | **UNRESOLVED DECISION** |
| Intended replacement mapping | None approved |
| Resolution | Not attempted in this section |

This is deliberately left open. Section 4 records what was observed and
establishes the distinction; it does not solve UD-001. Resolution follows the
governance process in Section 12 and is recorded in the Governance & Decision
Register.

### 4.8 Organisation and Task-Team Changes

Project parties, task teams and collaboration structures change during a project.
That is normal. What matters is that changes affecting governance are **decided
and recorded**, not absorbed.

Changes that require the controlled change process include:

- a new discipline is introduced;
- a trade contractor is appointed in the simulated workflow;
- a task team is split or combined;
- responsibility is transferred between teams or roles;
- a Design Collaboration team mapping is changed.

**Organisational change must not be made silently in the CDE.** Reconfiguring a
team, space, permission or mapping in the platform does not constitute a
governance decision, and does not make itself legitimate by having been done.
Where configuration and approved governance diverge, the divergence is recorded
as a deviation rather than adopted.

Detailed change governance is defined in Section 12 and recorded in
`supporting/governance-decision-register.md`.

## 5. Information Management Roles and Responsibilities

### 5.1 Responsibility Principles

These principles govern how responsibility is read throughout this BEP:

| Principle | |
|---|---|
| **Creation is not authority to share** | Producing information does not confer authority to share it. |
| **Sharing is not authority to publish** | Authority to share does not confer authority to publish or exchange. |
| **Coordination is not design approval** | Coordinating information is not approving a technical design solution. |
| **Checking is not acceptance** | Checking confirms compliance with a defined checking requirement; it does not accept the information. |
| **Authorisation is purpose-bound** | Information is authorised *for a defined purpose*, never in general. |
| **Acceptance does not transfer responsibility** | A recipient accepting information does not relieve the originator of professional responsibility for it. |
| **Responsibility must be traceable** | For any container it must be answerable who produced it, who checked it, who authorised it and for what purpose. |

**Two kinds of responsibility.** Technical/design responsibility and
information-management responsibility are related but distinct. A task team
remains responsible for its technical solution regardless of who managed,
coordinated, transmitted or accepted the information describing it. No
information-management act transfers design responsibility.

### 5.2 Project Information Management Role Model

```
Owner / Appointing Party
        |
        v
Lead Delivery Party
        |
        +---- BIM Manager
        |
        +---- BIM Coordinator
        |
        +---- Task-Team Leads
                  |
                  +---- Authors
                  +---- Checkers

CDE Administration supports implementation of approved governance.
```

This is a **conceptual functional model**, not an appointment chart and not an
organisation chart. It shows how information-management functions relate to one
another, not who reports to whom contractually.

No names are populated. Role holders are TBD throughout Section 5.

### 5.3 Owner / Appointing Party

At a high level, the Owner / Appointing Party:

- establishes or approves project information needs;
- defines intended information outcomes;
- receives identified exchanges;
- accepts information for identified purposes, where applicable.

**Identity: TBD.** No appointing party has been established (section 2.3).

Nothing in this section implies design liability, contractual duty, or any
obligation beyond what the training information-management workflow requires.

### 5.4 Lead Delivery Party

The Lead Delivery Party coordinates project-level delivery across contributing
task teams. Functions may include:

- consolidating delivery planning;
- coordinating task-team commitments;
- supporting project-level information readiness;
- coordinating delivery interfaces;
- ensuring required project-level IM processes are applied.

**Holder: TBD.**

Two things must not be assumed:

- **Architecture is not automatically the Lead Delivery Party.** That
  Architecture was the only populated production stream observed at discovery
  (section 2.5) is an observation about files, not an appointment.
- **The Lead Delivery Party is not automatically the BIM Manager.** They are
  different functions with different concerns, and may sit in different
  organisations.

### 5.5 BIM Manager

The BIM Manager is the principal **governance** function for this training BEP.
Responsibilities include:

- maintaining the BEP governance framework;
- maintaining the CDE strategy;
- coordinating information standards;
- maintaining the responsibility architecture;
- coordinating delivery-planning governance;
- managing governance decisions and controlled changes;
- supporting onboarding and BIM capability development;
- performing governance assurance;
- checking that approved governance is reflected in platform and process
  configuration.

**Limits of the function.** The BIM Manager is **not** automatically:

- a design approver;
- a discipline technical lead;
- a contractual decision-maker;
- the Appointing Party;
- the Lead Delivery Party.

The BIM Manager governs *how information is managed*. Authority over technical
design, appointment and contract lies elsewhere and is not acquired by holding
this function. Where the BIM Manager identifies a problem outside the function's
authority, the route is to raise and escalate it, not to decide it.

**Holder: TBD.**

### 5.6 BIM Coordinator

The BIM Coordinator is the **operational** multidisciplinary coordination
function. Responsibilities include:

- organising coordination inputs;
- managing federation and coordination review cycles;
- running or coordinating clash and interface review;
- triaging coordination findings;
- coordinating assignment of issues;
- monitoring resolution;
- verifying that coordination findings have been addressed through the
  coordination process;
- escalating unresolved interface problems.

**Limits of the function.** The BIM Coordinator does **not** take ownership of
design solutions. Verifying that a clash has been closed confirms that the
coordination process was followed to its conclusion — it is **not** design
approval and carries no technical endorsement. The originating task team retains
responsibility for its technical solution, before and after coordination.

**BIM Manager and BIM Coordinator are distinct functions.** The BIM Manager
governs the framework; the BIM Coordinator operates coordination within it. They
may be carried by the same participant (section 5.11), which does not merge them.

**Holder: TBD.**

### 5.7 Task-Team Leads

A Task-Team Lead is responsible for their own team's information production and
readiness:

- organising task-team production;
- ensuring required information is produced;
- ensuring required checking occurs;
- resolving task-team quality issues;
- managing interfaces with other task teams;
- authorising information from WIP for controlled sharing, where governance
  assigns that authority;
- ensuring coordination issues assigned to the team are addressed.

**Technical authority sits here, not with the BIM functions.** The Task-Team Lead
holds responsibility for the team's technical content. Neither the BIM Manager
nor the BIM Coordinator acquires that responsibility by governing or
coordinating the information that describes it.

**Holders: TBD** for every task team.

### 5.8 Authors and Checkers

| Function | Responsibilities |
|---|---|
| **Author** | Creates or modifies information; works within the task team's WIP environment; complies with project conventions; responds to assigned comments and issues. |
| **Checker** | Verifies information against the defined checking requirement; records or provides evidence of checking; identifies deficiencies before controlled progression. |

**Authors do not self-promote their own information.** Having authored a
container is not a reason to advance it; progression requires the checking and
authorisation defined by governance, not the author's confidence in their work.

**On combining the two.** In a training project of this size, Author and Checker
may sometimes be performed by the same participant where independence cannot
reasonably be provided. Where that happens:

- the functional distinction remains — self-checking is still a checking act
  with a defined requirement, not an omission of one;
- the combination is recorded, so the limitation is visible in the evidence.

**Independence is never claimed where it does not exist.** A check performed by
the author is recorded as such. Overstating independence is worse than lacking
it, because it removes the reader's ability to judge the information's
reliability.

### 5.9 CDE Administration Function

CDE Administration implements approved governance in the platform.
Responsibilities may include:

- project membership administration;
- folder and space implementation;
- permissions;
- Design Collaboration team-space configuration;
- coordination-space configuration;
- platform workflow configuration;
- implementation of approved structural and configuration changes;
- checking platform configuration after an approved change.

**Critical principle: CDE Administration implements governance; it does not
create it.** Changing the software does not make a decision. A configuration that
was never approved is a deviation, however competently it was applied.

**Platform permission is not BEP authority.** Holding administrative rights over
a folder, space or team confers the technical ability to change it and nothing
more. It does not confer authority to decide who is responsible for what, to
reassign responsibility, or to alter the organisational structure in section 4.
Those are governance decisions, taken through Section 12.

**Holder: TBD.**

### 5.10 Responsibility Transitions

An information container moves through this lifecycle:

```
Author
  → Check
  → Task-Team Lead authorises sharing
  → Shared information
  → coordination / review
  → resolution where required
  → delivery review
  → authorised publication / exchange
  → recipient acceptance
```

**Each arrow is a separate decision performed by a defined function.** The point
of the sequence is that no single act carries information from authoring to
exchange. Checking does not authorise sharing; sharing does not authorise
publication; acceptance does not reach back and validate what preceded it.

**Separate decisions do not require separate people.** In a small project several
of these may be performed by the same participant. The requirement is that each
decision is *made*, is made against its own criteria, and is traceable — not that
each has a different name attached to it.

Detailed process, states and platform mechanics belong to Sections 6–10 and the
supporting resources. This section defines only who decides what, and in what
order.

### 5.11 Role Combination and Delegation

This is a small training implementation, so functions may be combined. For
example, one participant may act as:

- BIM Manager and CDE Administrator;
- BIM Coordinator and another project role;
- Author and Checker, where independence cannot reasonably be provided.

**Combining roles does not combine the functions.** The responsibilities remain
distinct in meaning. A participant performing two functions must know **which
function they are performing at each decision point** — approving a governance
change as BIM Manager is a different act from applying it as CDE Administrator,
even when performed by one person within a minute of each other.

**Delegation must be explicit.** Delegated authority is stated, scoped and
recorded. In particular:

- **Platform access is not delegation.** Being able to perform an action in the
  software does not mean authority to decide it was delegated.
- Delegation covers a defined scope and does not silently expand.

**Independence limitations must be visible.** Where combining functions reduces
independence, that limitation is recorded rather than obscured, so that anyone
relying on the information can weigh it.

### 5.12 Responsibility Matrix Reference

Detailed allocation of responsibility is recorded in
`supporting/information-management-responsibility-matrix.md`.

That matrix is separately controlled and declares its own status, version and
authority. Reference from this BEP does not constitute approval of it (section
13.6).

**Division of labour between the two documents.** Section 5 defines what each
function *means*. The matrix records *how those functions are allocated* to roles
and process steps. Meaning is defined once, here; allocation is recorded once,
there.

**Approved responsibility grammar.** The matrix will use these terms and no
others:

| Term | Meaning |
|---|---|
| **Perform** | Carries out the activity |
| **Check** | Verifies against a defined requirement |
| **Authorise** | Permits progression, for a defined purpose |
| **Coordinate** | Organises across parties or task teams |
| **Accept** | Receives for an identified purpose |
| **Consult** | Is asked before the act |
| **Inform** | Is told after the act |

**RACI is not adopted.** This grammar is used instead, because it distinguishes
checking from authorising and coordinating from performing — distinctions that
RACI collapses and that this BEP depends on. RACI is not to be introduced unless
explicitly approved later.

## 6. Common Data Environment Strategy

### 6.1 CDE Purpose and Principles

The Common Data Environment is an **information-management process supported by
technology**. It is not a folder tree. A folder structure is one way of
implementing part of the process; it is not the process, and reorganising
folders does not change how information is governed.

Principles:

| Principle | |
|---|---|
| **State is identifiable** | Every information container has a knowable state. |
| **Progression is controlled** | Movement between states happens by decision, not by drift. |
| **Movement has an owner** | Responsibility for each transition is explicit. |
| **Presence is not trust** | Information is not reliable merely because it exists in the platform. |
| **Four distinct properties** | State, version, suitability and authority are separate things (section 6.8). |
| **Originators retain responsibility** | Moving information through the CDE does not transfer responsibility for it. |
| **Sharing is purposeful** | Shared information is made available for a stated purpose. |
| **Publication is purposeful** | Published information is authorised for a defined purpose. |

### 6.2 CDE Technology Environment

Current training technology mapping, at high level:

| Capability | Role in the process |
|---|---|
| Autodesk Forma / Data Management | Cloud document and CDE foundation |
| Design Collaboration | Controlled design-team collaboration and exchange, where configured |
| Model Coordination | Multidisciplinary aggregation, coordination review and clash/interface workflow, where used |
| Issues | Governed project issue and action records, where applicable |
| Reviews | Controlled review workflow, where applicable |
| Transmittals | Formal transmission record, where applicable |
| Desktop Connector | Local filesystem access method to cloud-managed information |

**Two limits.** No claim is made that any of these is fully configured, adopted
or operationally mature — see section 2.4. And **no capability creates governance
by existing**. Design Collaboration, Model Coordination, Reviews, Transmittals
and Issues implement an agreed process; they do not constitute one. A share
performed in the platform is governed because the process says so, not because
the software permitted it.

### 6.3 Information States

Four controlled state concepts:

| State | Meaning |
|---|---|
| **WIP** | Information under originator / task-team control. Not authorised for general project reliance. |
| **Shared** | Information made available beyond the originating task team for an identified purpose, after required checking and authorisation. |
| **Published / Authorised** | Information authorised for a defined delivery or use purpose. |
| **Record / retained** | Historical evidence retained for traceability, according to the project's retention approach. |

**States are not folders.** The live CDE does not need a folder literally named
after every conceptual state, and the presence or absence of such a folder proves
nothing about how information is governed. In particular, **no "04 Archive"
project root requirement is confirmed**, and none is created here. The project's
retention approach is not yet defined.

**Published does not mean final.** Published information is authorised for a
defined purpose at a point in time. It can be superseded, revised, or found
unsuitable for a purpose it was never authorised for. See sections 6.7 and 6.8.

### 6.4 Team Spaces and WIP

WIP belongs under the control of the originating task team, as defined in
Sections 4 and 5. The originating task team is responsible for:

- authoring;
- internal checking;
- readiness assessment;
- authorisation for progression, where governance assigns that authority.

Design Collaboration team spaces may support this workflow where configured.

**A team space is a platform construct.** It is not an organisation, not a
discipline, not a contractual appointment. Membership confers no authority
(sections 4.5, 5.9).

**No automatic mirroring.** The six discipline codes are **not** mirrored
automatically into six platform teams. Whether platform teams should map
one-to-one to task teams remains an open question (section 4.5).

The observed team-space bindings recorded in section 4.5 remain as observed.
**UD-001 is not resolved here.**

### 6.5 Controlled Sharing and Consumption

**Share and consume are different acts performed by different parties.**

| Act | Who | What happens |
|---|---|---|
| **Share** | Originating task team | Makes information available through a controlled exchange |
| **Consume** | Receiving task team | Deliberately adopts shared information into its working context |

Two consequences follow, and both matter:

- **Availability is not consumption.** Information being visible, accessible or
  present in a shared location does not mean any team has adopted it. Nobody
  consumes information by accident.
- **Consumption does not transfer technical ownership.** A receiving team that
  consumes a model does not acquire responsibility for its content. The
  originator remains responsible for what it produced.

Lifecycle:

```
WIP
  → check
  → authorise share
  → Shared
  → receiver reviews
  → consume where appropriate
  → use for stated purpose
```

Where Design Collaboration is configured, its package / share / consume workflow
may support this process. **It is not claimed to be required for every container
or every exchange** — see section 7.8.

### 6.6 Coordination Information

**Coordination inputs come from appropriate Shared information, not from
uncontrolled WIP.** Coordinating against another team's working state produces
findings against information nobody authorised, and wastes the effort of both
teams when it moves.

Coordination information may include:

- discipline models;
- agreed reference models;
- coordination exports;
- clash and interface findings;
- issue records;
- coordination decisions.

**Federation does not merge authorship or responsibility.** Aggregating models
into a federated view creates a coordination artefact, not a jointly-authored
model. Each contributed container keeps its originator, its state and its
technical responsibility.

Detailed coordination process is defined in Section 8.

### 6.7 Published / Authorised Information

Published / authorised information has passed the required preparation, review
and authorisation for an identified purpose.

Purposes may include — **as examples only, not as current project milestones**:

- formal design issue;
- coordination-approved exchange;
- tender / pricing information;
- construction information;
- record / handover information.

None of these is a committed milestone of this project. Actual purposes become
project requirements only when approved in the Information Delivery Schedule,
subject to that resource's own approval status. Entries existing in that
schedule are not thereby approved project requirements.

**Published does not mean:**

| Not | Because |
|---|---|
| Perfect | Authorisation confirms fitness for a stated purpose, not absence of error |
| Forever final | Published information can be superseded or revised |
| Universally suitable | Suitability is bounded by the purpose it was authorised for |
| Accepted by everyone | Acceptance is a separate act by an identified recipient |

**Authorisation is purpose-specific.** Information authorised for one purpose is
not thereby authorised for another.

### 6.8 Versions, Revisions, Status and Suitability

Five terms, routinely conflated, deliberately kept apart:

| Term | Meaning |
|---|---|
| **Version** | A platform or file history instance |
| **Revision** | A controlled issue identifier, where project convention requires one |
| **State** | WIP / Shared / Published / Record |
| **Status** | A workflow or decision condition |
| **Suitability** | What the information may be used for |

**A new platform version creates none of the others.** Saving a new version does
not by itself create a new revision, change the information state, constitute
approval, or make the information suitable for a new purpose. Each of those is a
separate act with its own decision and its own responsible role.

Detailed naming and revision conventions belong to Section 11 and the project
standards.

### 6.9 Access and CDE Administration

CDE Administration implements approved governance (section 5.9). Membership,
permissions, folder access, team-space access and platform roles **support** the
process; they do not create professional or governance authority.

**Platform permission is not:**

- authority to share;
- authority to publish;
- authority to accept.

Access is configured to support approved responsibility — the responsibility
comes first, and the permission follows it. Where access and approved
responsibility diverge, the divergence is a deviation to be recorded, not a
redefinition of who is responsible.

No user names are specified in this document.

### 6.10 Local Authoring and Desktop Connector

Desktop Connector is an **access mechanism** to cloud-managed information.

It is **not**:

- a separate CDE;
- an independent source of truth;
- the BEP authoring repository;
- a substitute for governed cloud state.

Local authoring tools may work with files through approved methods, but **project
state is governed by the CDE process**, not by what exists on a local filesystem.
A file being present locally says nothing about its state, suitability or
authorisation.

**Repository and publication boundary.** The BEP authoring source and the issued
project artefact are separate things, connected only by a deliberate human act:

```
Git repository  (authoritative BEP authoring source)
  → review
  → approved baseline
  → controlled manual publication
  → project-facing issued baseline in Forma
```

The `harrismith-bep` repository is not configured inside, linked to, or
live-synchronised with the Desktop Connector CDE location. **No symlink,
junction, bind-mount or live-sync publication model is approved for this
workflow.** Publication is manual and human-performed. No machine-specific
Desktop Connector paths are recorded in this document.

### 6.11 As-Found vs Intended Configuration

The Section 4.7 distinction applies to the CDE:

| Concept | Status |
|---|---|
| **As-found** | Evidence of current behaviour |
| **Intended governance** | A controlled decision |
| **Implemented configuration** | The result of an authorised change |

High-level as-found observations:

| Observation | Classification |
|---|---|
| The current CDE root contains Common Files, WIP, Shared and Published areas | OBSERVED FACT |
| Observed Design Collaboration configuration comprises the teams recorded in section 4.5 | OBSERVED FACT |
| Some governance and standards areas were observed empty at discovery | OBSERVED FACT |
| The MEP / Structural team-space binding discrepancy remains open | **UD-001 — UNRESOLVED** |

**Current structure is not automatically the approved future state.** That an
area exists, is named a certain way, or is used in a certain way is evidence of
present practice — not an approved requirement, and not a decision.

No correction to UD-001 is proposed here. Detailed CDE inventory is deliberately
not reproduced.

### 6.12 CDE Workflow & State Strategy Reference

Detailed CDE workflow is recorded in `supporting/cde-workflow-state-strategy.md`.

That resource is separately controlled and declares its own status, version and
authority. Reference from this BEP does not constitute approval of it (section
13.6).

Section 6 defines the **governing principles**. The supporting strategy will
contain the detail:

- state definitions;
- transition rules;
- platform mapping;
- team-space mapping;
- share / consume process;
- access implementation rules;
- exception handling.

That detail is not duplicated here. Principles are stated once, in this section;
implementation is recorded once, there.

## 7. Information Production and Sharing

### 7.1 Information Production Principles

Information moves through this lifecycle:

```
requirement
  → author
  → WIP
  → check
  → Task-Team Lead authorises progression
  → controlled share / exchange
  → Shared
  → receiving team reviews
  → consume where appropriate
  → use for stated purpose
```

**Every transition has a purpose and a responsible role.** Production begins from
a requirement, not from availability of time or tools; and each step answers a
different question — is it made, is it correct, may it progress, has it been
adopted, what may it be used for.

**Separate decisions do not require separate people.** In a project of this size
several steps may be performed by the same participant. What is required is that
each decision is made against its own criteria and is traceable (section 5.11).

### 7.2 Information Ownership and Origination

Origination follows this chain:

```
party → task team → discipline → information container
```

**Originator responsibility remains with the producing task team**, through
sharing, consumption, coordination and publication. No downstream act relieves it.

**Design consultant information and trade/construction information are
distinct.** They are produced by different parties, for different purposes, at
different levels of definition, under different responsibilities. Contractor
models are **not** to be treated as consultant design information, and the
distinction is not erased by both being present in the same CDE.

**Authorship is not inferred from folder location.** Where a container sits tells
you where it sits. The originator is recorded, not deduced.

Detailed allocation of production responsibility belongs to the Model /
Information Responsibility Matrix.

### 7.3 Production Requirements

Information production is driven by **defined requirements**, not by assumption
about what might be wanted. A requirement may specify:

- the container required;
- the originator;
- the intended recipient;
- the purpose;
- the required format;
- the milestone or exchange it serves;
- the checking requirement;
- the authorisation requirement;
- dependencies on other information.

Detailed control will come from the **Model / Information Responsibility
Matrix** (who produces what) and the **Information Delivery Schedule** (what is
exchanged, when and why). Each is separately controlled and declares its own
status (section 13.6).

**No formal information requirements are available to this implementation.** No
formal Employer's / Exchange Information Requirements, Asset Information
Requirements, or equivalent project information requirements have been
established or made available to this training implementation (sections 2.3,
2.6). None are invented by this BEP.

This records what is available here. It is not a claim that no such requirements
exist elsewhere. Should formal requirements later be produced or made available,
they take precedence over anything developed in their absence (section 1.5).

Until formal requirements are approved, production requirements developed for
this implementation remain **PROPOSED GOVERNANCE or TRAINING ASSUMPTION**, and
are labelled as such rather than presented as client requirements.

### 7.4 Authoring Environment

Authoring tools are selected as **fit for purpose for the information being
produced**.

Revit is an observed authoring environment on this project (section 2.4). That
observation does **not** make Revit mandatory for every discipline, every
container or every deliverable. Other appropriate tools and formats may be used
where the approved workflow permits.

Two consequences:

- **Software choice does not define governance.** The tool that produced a
  container does not determine its state, suitability or authorisation.
- **Authoring environment is not CDE state.** Work existing in an authoring tool
  — saved, synchronised, or otherwise — is not thereby WIP, Shared or Published.
  State is a property of the governed information container, not of the software.

### 7.5 Task-Team WIP

WIP is the task team's **working state**. It includes:

- drafting and modelling;
- internal iterations;
- local coordination within the team;
- correction;
- checking preparation.

WIP may contain many versions. **WIP versions are not project exchanges.** A new
version in WIP is a working step, not a share, not an issue, and not an event
that other teams are expected to act on.

**Other parties do not rely on WIP** unless an explicitly governed exception
exists (section 7.11).

**Visibility is not permission.** Being able to see or open another team's WIP —
through folder access, a platform permission, or any other means — does not
constitute authority to use it. Permission to read is not authorisation to rely.

### 7.6 Task-Team Checking

Before controlled progression, the originating task team performs checks
appropriate to the information. Three broad categories:

| Category | Concern | Examples |
|---|---|---|
| **Technical / content** | Is the content right? | Appropriate discipline review |
| **Information quality** | Is the container right? | Identity, naming, metadata, completeness, format |
| **Interface / readiness** | Is it usable by others? | Coordinates, references, known interfaces, unresolved items identified |

**This BEP does not define discipline technical QA criteria.** What constitutes
an adequate structural or MEP technical review is a matter for the discipline and
its own professional standards, not for an information-management document.

Detailed checklists may later sit in the Working Process or the project
standards.

### 7.7 Readiness to Share

Before sharing, the originating task team confirms, as applicable:

- required information is present;
- task-team checking is complete;
- container identity is clear;
- coordinates and reference context are appropriate;
- known interfaces and issues are identified;
- the purpose of sharing is known;
- the receiving audience is understood;
- required authorisation has occurred.

**No numeric quality thresholds are set.** This BEP does not define a percentage,
score or count that constitutes readiness; readiness is a judgement made against
the purpose of the share, by the role authorised to make it.

Detailed readiness checklists belong in the supporting working resources.

### 7.8 Controlled Sharing

Information moves from WIP to Shared **only through the approved progression
route**.

Where Design Collaboration is configured, its controlled package / share workflow
is the **preferred project-facing mechanism for design-team exchange where
appropriate**.

**It is not the mechanism for every case.** Design Collaboration is not
necessarily appropriate for every file, every discipline, every deliverable or
every project stage. The route must fit the information type and the approved
workflow, and choosing a route is a governance decision rather than a default.

A share event should be traceable to:

| Attribute |
|---|
| Originator |
| Information / container |
| Purpose |
| Version / revision, as applicable |
| Authorisation |
| Date / event |

This BEP does not create actual exchange identifiers.

### 7.9 Receiving and Consuming Shared Information

Receiving teams distinguish **information is available** from **information has
been reviewed and adopted**. These are different states of the receiver's
knowledge, and only the second justifies relying on it.

Receiver actions may include:

- review;
- accept for a stated working purpose;
- consume / reference;
- reject or request clarification;
- raise a coordination issue.

**Consumption does not transfer originator technical responsibility** (section
6.5). The originator remains responsible for the content it produced.

**The receiving team remains responsible for how it uses the information within
its own work** — for whether the information was appropriate to the use, whether
it was current, and whether the use was within the stated purpose. Both
responsibilities exist at once; neither cancels the other.

### 7.10 Rework and Resharing

When shared information requires change, the originator corrects or revises it
**in its own WIP environment**:

```
WIP correction
  → check
  → authorise
  → reshare
```

**The shared instance is not edited as an uncontrolled workaround.** Modifying
information in place, outside the origination and checking route, breaks the link
between what was authorised and what recipients hold.

**Previous exchanges remain traceable.** Superseded information is marked as
superseded, not deleted. The record of what was shared, when and for what purpose
is part of the project's traceability, and remains needed after the information
itself has been replaced.

### 7.11 Production Exceptions and Deviations

Exceptions happen. They must be **explicit**. Examples:

- an urgent temporary exchange outside the normal route;
- an unavailable platform service;
- an incompatible file format;
- a temporary team configuration issue;
- missing required information.

**An exception does not quietly become the new normal process.** A route used
once under recorded justification carries no precedent; repetition without
decision is how undocumented practice replaces governance.

Each exception records:

| Field |
|---|
| Reason |
| Affected information |
| Temporary route used |
| Responsible role |
| Risk / impact |
| Required follow-up |

**Unrecorded workarounds are not acceptable.** Email attachments, local drives,
messaging apps and personal storage are not controlled exchange routes. Where
circumstances force such a route, it is an exception to be recorded as above —
not an informal alternative to the CDE.

Detailed governance of exceptions and deviations belongs to Section 12 and
`supporting/governance-decision-register.md`.

### 7.12 Supporting Resource References

| Resource | Answers |
|---|---|
| `supporting/model-information-responsibility-matrix.md` | Who produces what |
| `supporting/information-delivery-schedule.md` | What is exchanged, when, why, to whom and in what form |
| `supporting/cde-workflow-state-strategy.md` | How information moves between controlled states |

**Each of these is separately controlled** and declares its own status, version
and authority. Reference from this BEP does not constitute approval of any of
them (section 13.6).

Section 7 defines the principles of production and sharing. The resources above
record the specific allocations, schedules and transition rules. Detail is not
duplicated between them.

## 8. Model and Information Coordination

### 8.1 Coordination Purpose and Principles

Coordination is the controlled multidisciplinary process used to **identify,
communicate, resolve and verify information-interface problems**.

Its purpose is not to generate clash counts. A clash count measures how much
software found; it says nothing about whether anything was understood, decided
or fixed.

| Principle | |
|---|---|
| **Controlled inputs** | Coordination uses controlled information inputs, not working state. |
| **Responsibility stays put** | Originating task teams retain technical responsibility throughout. |
| **Findings require triage** | Detection output is not conclusion. |
| **Not every clash is an issue** | Formal issues are created deliberately, not automatically. |
| **Issues are assigned and traceable** | A formal issue has an owner and a history. |
| **Verification ≠ approval** | Verifying resolution is not technical or design approval. |
| **Completion is by disposition** | Completion rests on required checks and dispositions, not on an absolute zero-clash state. |

### 8.2 Coordination Scope and Participants

Intended design coordination scope may include the discipline domains:

| ARC | STR | MEC | ELE | PLM | FIR |
|---|---|---|---|---|---|

These are **discipline domains**, not necessarily six companies and not
necessarily six platform teams (sections 4.3, 4.4, 4.5).

Construction and trade coordination may be introduced later, when the relevant
task teams enter the training delivery workflow (section 4.3).

Participants may include:

- BIM Coordinator;
- Task-Team Leads;
- relevant Authors and Checkers;
- BIM Manager, for governance and escalation where required;
- the Lead Delivery Party function, where project-level coordination requires it.

No actual people are appointed. **Not every participant is responsible for every
finding** — participation is scoped to the interfaces a team actually holds.

### 8.3 Coordination Inputs and Readiness

Coordination inputs normally come from **controlled Shared information** that has
passed the readiness process in Sections 6 and 7. Uncontrolled WIP is not the
normal project coordination input (section 6.6).

Before coordination, confirm as appropriate:

- identity of the input;
- originator / task team;
- intended coordination purpose;
- current version or revision, where applicable;
- coordinate and reference context;
- completeness and readiness;
- known exclusions or limitations;
- known unresolved interfaces.

**Coordination readiness is not design completeness.** Information can be ready
to coordinate while remaining incomplete, unapproved and subject to change. The
two questions are separate.

### 8.4 Coordination Environments and Tools

| Environment | Role |
|---|---|
| Autodesk Model Coordination | Intended project-facing cloud environment for multidisciplinary aggregation, review and clash/interface coordination, where configured and appropriate |
| Navisworks | Specialist desktop coordination and analysis environment, where detailed desktop federation or review is useful |
| Forma Issues / project issue workflow | Governed project record for coordination issues and actions, where used |

Four constraints:

- **Tools do not define responsibility.** Responsibility comes from Sections 4
  and 5.
- **A software clash result is not automatically a managed issue.** It becomes
  one by triage and decision (section 8.7).
- **Use of Navisworks does not create a second governance system.** Desktop
  analysis feeds the agreed workflow; it does not run in parallel to it.
- **Issue status remains traceable through the agreed workflow**, wherever the
  analysis was performed.

**As-found qualification.** During discovery the project contained a Navisworks
coordination area with limited observed content, and no Design Collaboration
Coordination Space was observed as configured (section 4.5). These are OBSERVED
FACTS about the state at discovery. No maturity is claimed, and **no platform
change is proposed here**.

### 8.5 Model Federation

Federation is the **temporary, controlled aggregation** of separate discipline or
task-team information for coordination purposes.

Federation does **not**:

- merge authorship;
- transfer technical ownership;
- create a new design author;
- turn discipline models into one jointly-owned authoring model.

Originators remain responsible for their own information. The federation is a
lens for multidisciplinary understanding and review — it is not a deliverable
that anyone authored, and nobody becomes responsible for another team's content
by appearing alongside it.

### 8.6 Clash Detection and Coordination Review

Clash detection is **one coordination technique**, not the whole of coordination.

Purpose-based checks may include:

- hard clashes;
- clearance and interface conflicts;
- spatial access conflicts;
- discipline interface conflicts;
- model alignment and reference problems.

**Blind all-versus-all clash testing is not required.** Testing everything
against everything produces volume, not insight, and buries the findings that
matter.

Detailed clash and interface combinations, tolerances and exclusions belong in
the Coordination & Review Strategy.

**A clash result is triaged before any formal issue is created.**

### 8.7 Coordination Issues

| Term | Meaning |
|---|---|
| **Clash / finding** | A detection or observation requiring triage |
| **Issue** | A governed record created because an actionable coordination matter requires assignment, tracking, decision or verification |

**Not every clash becomes an Issue.** Many findings are tolerable, duplicated,
out of scope, already known, or artefacts of the test setup. Creating an issue is
a decision.

An Issue should normally carry enough information to identify:

- what the problem is;
- the affected information or interface;
- the responsible task team or role;
- the required action or outcome;
- status;
- relevant evidence and context.

This BEP does not define project issue numbering or status codes. Detailed
taxonomy belongs in the Coordination & Review Strategy.

### 8.8 Coordination Cycle

```
controlled Shared information
  → input / readiness check
  → federation
  → coordination checks
  → triage findings
  → create / assign Issues where required
  → originating task team resolves in WIP
  → task-team check
  → controlled reshare
  → recoordinate
  → verify resolution
  → close / disposition
  → retain evidence
```

**The originating task team makes the technical change.** Resolution happens in
that team's own WIP environment, through its own checking route.

**The BIM Coordinator manages the process, not the solution.** Identifying a
conflict does not make the coordinator the author of its remedy, and does not
transfer the design decision to them.

### 8.9 Meetings, Decisions and Communication

Coordination meetings support decisions. **A meeting is not the authoritative
information model**, and a discussion is not a record.

Meetings may be used to:

- review unresolved interfaces;
- confirm ownership;
- agree next actions;
- escalate blockers;
- record decisions affecting multiple teams.

**Decisions of consequence are captured in the appropriate controlled record.**
Reliance on undocumented verbal decisions is not acceptable — a decision nobody
can produce afterwards did not happen, whatever was said in the room.

Meeting frequency is not prescribed by this BEP, and no separate
meeting-governance system is created.

### 8.10 Issue Resolution and Verification

The assigned or originating task team resolves the technical issue through its
own controlled WIP process:

```
resolve in WIP
  → check
  → share revised information
  → recoordinate
  → verify
```

The BIM Coordinator may verify that the coordination problem is no longer present
or has been dispositioned appropriately.

**That verification is not:**

- discipline design approval;
- professional certification;
- acceptance of technical responsibility.

Technical and design responsibility remains with the originating task team,
before and after verification.

### 8.11 Coordination Completion and Acceptance

**Completion is not "zero clashes."** A zero-clash report can be produced by
testing nothing, excluding everything, or resolving symptoms rather than
interfaces.

Completion of a defined coordination cycle means, as applicable:

- required coordination checks were performed;
- significant findings were triaged;
- required Issues were assigned;
- required resolutions or dispositions were recorded;
- verification was completed where required;
- known unresolved matters were explicitly carried forward or escalated.

**Completion is purpose-specific.** A completed coordination cycle does not mean
the project design is complete, approved or accepted.

### 8.12 Exceptions and Escalation

Escalate where coordination cannot be resolved through the normal task-team
cycle. Examples:

- an unresolved multidisciplinary interface;
- conflicting design decisions;
- a missing input preventing coordination;
- a repeatedly unresolved issue;
- a coordinate or reference problem affecting multiple teams;
- a platform or configuration problem affecting the coordination process.

An escalation should identify:

| Field |
|---|
| The issue |
| Affected teams |
| Decision required |
| Impact |
| Required decision owner / function |

**Escalation authorities are not invented.** Where the role that should decide
remains TBD (Sections 5.3, 5.4, 9.7), the escalation records that the decision
owner is unresolved rather than naming one. Detailed exception governance belongs
to Section 12.

### 8.13 Coordination & Review Strategy Reference

Detailed coordination arrangements are recorded in
`supporting/coordination-review-strategy.md`.

That resource is separately controlled and declares its own status, version and
authority. Reference from this BEP does not constitute approval of it (section
13.6).

Section 8 establishes the governing principles. The supporting strategy will hold
the detail:

- coordination scope;
- participant mapping;
- input register and readiness;
- federation arrangements;
- clash / interface matrix;
- tolerances and exclusions;
- issue taxonomy and statuses;
- assignment workflow;
- coordination cycle;
- meetings;
- verification;
- escalation;
- outputs and evidence.

## 9. Review, Approval and Authorisation

### 9.1 Purpose and Principles

Section 9 is the **decision-control layer between production and use**. It
governs the decisions that let information move, and the decisions that let
information be relied on.

| Principle | |
|---|---|
| **Check ≠ approval** | Checking verifies against a requirement; it approves nothing. |
| **Coordination ≠ technical approval** | A coordination disposition is not a design decision. |
| **Authorisation is purpose-specific** | Information is authorised *for* something, never in general. |
| **Publication ≠ acceptance** | Issuing information does not mean anyone accepted it. |
| **Acceptance ≠ transfer** | Acceptance does not move professional responsibility off the originator. |
| **Decisions are traceable** | Who decided what, when and for what purpose is recoverable. |
| **Authority comes from governance** | Not from platform access, permission or configuration. |

The term "approve" is used only where a defined approval decision is intended.
More specific terms — check, review, authorise, coordinate, accept and reject —
are used where they describe the actual decision more accurately. "Approval" is
not used as a catch-all for different decision functions. See section 9.2.

### 9.2 Review and Decision Terminology

| Term | Meaning |
|---|---|
| **Check** | Verification against a defined requirement before progression |
| **Review** | Consideration of information for a stated purpose |
| **Authorise** | Permit information to progress, share, publish or exchange for a defined purpose |
| **Accept** | Recipient acknowledges information as suitable or received for the stated purpose, subject to the project arrangement |
| **Reject** | Information is not accepted for the stated progression or use, and action is required |
| **Coordinate** | The multidisciplinary interface process — not design approval |

**These terms are not collapsed into "approval."** Each names a different
decision, made by a different function, against different criteria. Where a
statement in this project means one of these, it uses that word.

### 9.3 Task-Team Check

Task-team checking occurs before information progresses from WIP. The task team
verifies the required:

- technical and content quality;
- information quality;
- readiness and interface conditions.

Checking confirms **readiness for the next controlled decision**.

**Checking does not automatically authorise sharing.** A checked container is a
container that is ready to be considered for progression — the progression itself
is a separate decision (section 9.4).

### 9.4 Authorisation to Share

The Task-Team Lead — or another role explicitly allocated that function by
approved governance — authorises information to progress from WIP to Shared.

Authorisation to share means the information is considered **suitable for the
stated sharing purpose**.

It does **not** mean the information is:

- suitable for construction;
- formally published;
- accepted by recipients;
- technically approved for every downstream purpose.

**Authorisation to share is not authorisation to publish or exchange.** Those are
separate decisions with wider consequences, governed by section 9.7.

### 9.5 Multidisciplinary Coordination Review

Coordination review evaluates shared multidisciplinary information for the
defined coordination purpose.

The BIM Coordinator manages the coordination process. Task-Team Leads retain
responsibility for the technical content of their information and for its
technical resolution.

**A coordination-cycle disposition does not constitute discipline design
approval.** That a clash was closed, waived or carried forward says how the
coordination process treated it — not that any discipline approved the design
condition behind it.

### 9.6 Delivery Review

Delivery review occurs **before an information exchange is authorised**. It may
consider:

- completeness of the required exchange;
- correct containers;
- required formats;
- required checks complete;
- coordination status appropriate to the delivery purpose;
- metadata and identification;
- known exclusions or limitations;
- intended recipient and purpose.

**Delivery review is broader than clash review.** Coordination asks whether the
information works with other information. Delivery review asks whether the right
information, in the right form, is being sent to the right recipient for a
purpose it can serve.

Detailed delivery checklists are not created here; they belong in supporting
resources.

### 9.7 Authorisation to Publish / Exchange

Only information authorised for the identified purpose enters the
Published/Authorised state or a formal exchange.

**The role holding publication and exchange authority is UNRESOLVED.** It depends
on the approved delivery arrangement, which does not yet exist (sections 2.3,
2.6). It is **not** automatically held by:

- the BIM Manager;
- the BIM Coordinator;
- the CDE Administrator;
- the Architect.

Until the delivery arrangement is approved, this authority remains **TBD**, and
this document says so rather than defaulting it to whichever role is nearest.

**Platform write permission is not publication authority** (sections 5.9, 6.9).
Being able to place a file in a published location is a software capability, not
a decision anyone made.

### 9.8 Recipient Acceptance

Receiving and accepting information is a **separate function occurring after
delivery**. Acceptance is:

- for a defined purpose;
- based on the applicable requirement;
- traceable where required.

Acceptance does **not**:

- transfer technical responsibility from the originator;
- make the information suitable for unrelated purposes;
- automatically approve the design.

**No Appointing Party acceptance workflow is defined.** No appointing party has
been established (sections 2.3, 5.3), and no acceptance authority is invented
here. Where acceptance is exercised in the training workflow, it is exercised in
a simulated capacity under TA-02.

### 9.9 Rejection, Rework and Resubmission

Where information is rejected or found unsuitable:

```
rejection / return
  → reason recorded
  → originating task team reworks in WIP
  → check
  → reauthorise
  → reshare / republish / resubmit
  → rereview as required
```

**Prior versions and exchanges are preserved for traceability.** History is not
overwritten to remove failed submissions. What was submitted, why it was
rejected, and what changed are part of the project record — and are usually the
most instructive part of it.

### 9.10 Progressive BEP Agreement and Sign-Off

The same governance model applies to this BEP itself:

```
working draft
  → controlled review
  → decisions resolved
  → baseline candidate
  → authorised training baseline
  → controlled publication
```

Progressive baselines — 0.1, 0.2, … 1.0 — are used **as a governance concept
only**.

**Baseline 0.1 is not approved.** This document remains a controlled draft
(section 1.2). No baseline has been authorised, and no real contractual
signatory is assigned; the authorising role remains TBD (section 1.6).

Later baselines supersede earlier ones. Historical traceability is retained
through version control (section 9.11).

### 9.11 Evidence and Traceability

Evidence may include, as appropriate:

- version history;
- checking records;
- review records;
- coordination issue history;
- decision records;
- meeting decisions;
- publication records;
- transmission records;
- acceptance and rejection records;
- Git history, for BEP authoring.

**Not every platform feature is required for every evidence type.** The evidence
must be sufficient and traceable; it need not be produced by any particular
software function.

**Git history proves authorship, not issue.** It records what changed in the
authoring source and when. It does **not** by itself demonstrate that anything
was issued to the CDE, published, delivered or accepted on the project (sections
1.2, 6.10).

### 9.12 Delegation, Independence and Role Combination

The Section 5.11 principles apply to every decision in this section. Functions
may be combined in this small training implementation, but:

- delegation must be explicit;
- role combination does not collapse the meanings of the decisions;
- independence limitations remain visible;
- platform permission does not constitute delegation;
- a participant must know which function they are exercising at each decision.

**Independent checking is not claimed where it did not occur.** Where one
participant performed both the authoring and the checking, the record says so.
An overstated independence claim is more damaging than an acknowledged
limitation, because it removes the reader's ability to weigh the evidence.

### 9.13 Supporting Resource References

| Resource | Relevance to Section 9 |
|---|---|
| `supporting/information-management-responsibility-matrix.md` | Which role performs, checks, authorises, accepts |
| `supporting/information-delivery-schedule.md` | Which exchanges require which decisions |
| `supporting/coordination-review-strategy.md` | Coordination review and verification detail |
| `supporting/governance-decision-register.md` | Decisions taken, and authorities still unresolved |

**No new Review Matrix is created.** Section 9 defines the decision terminology
and principles; detailed allocation and evidence belong in the existing supporting
resources above. Each is separately controlled and declares its own status;
reference from this BEP does not constitute approval of it (section 13.6).

## 10. Information Delivery and Exchange

### 10.1 Delivery Principles

An information delivery is tied to:

| A need | A recipient | A purpose |
|---|---|---|
| **Timing / event** | **Required content** | **Format** |
| **Readiness** | **Authorisation** | |

**Presence in Published does not establish a delivery.** Information sitting in a
published location has not been delivered to anyone; delivery is an act with a
recipient and a purpose, not a location.

Delivery remains traceable — what was sent, by whom, to whom, when and why
(section 10.10).

### 10.2 Information Requirements

Delivery responds to defined information requirements.

**Where formal client or project information requirements have not been
established or made available to this training implementation, they are not
invented** (section 7.3). Training requirements may be developed for the
exercise, and are explicitly classified as PROPOSED GOVERNANCE or TRAINING
ASSUMPTION.

This records what is available to this implementation. It is **not** a claim that
no such requirements exist elsewhere. The section 1.5 precedence hierarchy
remains applicable: if real requirements later become available, they take
precedence over anything developed in their absence.

### 10.3 Delivery Events and Milestones

A delivery event is a defined point at which identified information is exchanged
for an identified purpose.

Possible training examples — **examples only**:

- design coordination exchange;
- design review;
- tender / pricing information;
- construction information;
- record / handover information.

**These do not become project milestones by appearing in this BEP.** No
contractual dates exist (section 2.3), and none are invented. Actual approved
events belong in the Information Delivery Schedule, subject to that resource's
own approval status.

### 10.4 Deliverables and Information Containers

**A delivery is not synonymous with a file.** One exchange may carry several
information containers, for example:

- models;
- drawings;
- schedules;
- reports;
- specifications;
- supporting records.

Each container retains identifiable **origin, purpose and responsibility**
(section 7.2), regardless of what it was bundled with.

This BEP does not define the project's final deliverable list.

### 10.5 Task-Team Delivery Planning

Each task team should understand:

- what it must produce;
- for which event;
- for whom;
- the purpose;
- the format;
- the required checks;
- the required authorisation;
- its dependencies.

Task-team commitments feed the project-level delivery plan (section 10.6).
Detailed entries belong in the Information Delivery Schedule.

### 10.6 Project-Level Delivery Planning

The **Lead Delivery Party** function coordinates the overall delivery plan across
task teams. The **BIM Manager** supports the information-management governance of
that plan.

**These are two functions and are not automatically held by the same
participant** (sections 4.6, 5.4, 5.11).

Project-level planning reconciles:

- task-team commitments;
- dependencies;
- exchange events;
- coordination needs;
- recipient requirements;
- delivery readiness.

**Lead Delivery Party holder: TBD.**

### 10.7 Exchange Purpose and Suitability

Every formal exchange has a known purpose. Examples — **not currently approved
project uses**:

- coordination;
- review;
- pricing;
- construction;
- record / reference.

**Suitability is purpose-specific** (section 6.8):

- information suitable for coordination may not be suitable for construction;
- information suitable for review may not be accepted as record information.

Suitability for one purpose is never evidence of suitability for another.

### 10.8 Formats and Deliverable Composition

Formats are selected according to:

- purpose;
- recipient;
- interoperability need;
- authoring requirement;
- record requirement;
- project standard.

**No universal format is imposed on every task team.**

Observed and current contexts may include formats such as RVT, IFC, PDF or NWC.
Their **actual required use must be defined by the approved delivery plan** — an
observed historical file format is evidence of what has been produced, not a
mandatory future requirement (section 4.7).

### 10.9 Delivery Preparation and Authorisation

Before formal exchange, verify as applicable:

- correct containers included;
- correct versions and revisions;
- checks complete;
- coordination status appropriate;
- identifiers and metadata;
- formats;
- known limitations;
- intended purpose and recipient;
- required publication or exchange authorisation (section 9.7).

The detailed checklist belongs in the supporting resources.

### 10.10 Controlled Issue and Transmission

Formal exchange uses a controlled route appropriate to the purpose.

A transmission record can evidence:

| What was sent | When | By whom / which role | To whom | For what purpose |
|---|---|---|---|---|

Two distinctions:

- **A transmission record is not the information.** It is evidence that an
  exchange occurred, not a container of what was exchanged.
- **A transmittal is not technical approval.** Sending information formally says
  nothing about whether its content was approved by anyone.

**Transmittals are not required for every internal share.** The workflow is
matched to the delivery type — formal external issue and routine internal
sharing are different acts with different evidence needs.

### 10.11 Receipt and Acceptance

Four distinct states and events, routinely conflated:

| Term | Meaning |
|---|---|
| **Published** | Authorised for a defined purpose and placed in the authorised state |
| **Delivered** | Sent to an identified recipient for an identified purpose |
| **Received** | Arrived with, and was registered by, the recipient |
| **Accepted** | Acknowledged by the recipient as suitable for the stated purpose |

- **Delivery does not prove acceptance.**
- **Receipt does not prove suitability.**
- **Acceptance applies to the identified purpose and requirement**, and to
  nothing beyond it.

**No acceptance authorities are invented.** Where the accepting role remains
unresolved (sections 5.3, 9.7, 9.8), it remains **TBD**.

### 10.12 Failed, Superseded and Revised Deliveries

Where a delivery fails review or acceptance, or requires revision:

- the reason is recorded;
- the originator or task team reworks through controlled WIP;
- revised information is checked;
- it is reauthorised;
- it is reissued;
- the previous delivery remains traceable.

**Superseded deliveries do not silently disappear.** They are marked superseded,
not removed (sections 7.10, 9.9).

**Not every new platform version is a revised delivery.** A version is a file
history instance; a revised delivery is an authorised exchange event. The first
does not create the second (section 6.8).

### 10.13 Information Delivery Schedule Reference

Detailed delivery planning is recorded in
`supporting/information-delivery-schedule.md`.

That resource is separately controlled and declares its own status, version and
authority. Reference from this BEP does not constitute approval of it (section
13.6). This BEP does not create schedule rows.

The schedule will include fields equivalent to:

| Field | Field |
|---|---|
| Delivery ID | Purpose |
| Exchange / milestone | Format |
| Information container | State / suitability |
| Party | Checking requirement |
| Task team | Authorisation requirement |
| Discipline | Acceptance criteria |
| Lead | Status |
| Recipient | Dependencies |

## 11. Standards and Project Conventions

### 11.1 Standards Principles

This BEP governs **how project standards are applied**. It does not reproduce
the standards themselves.

| Principle | |
|---|---|
| **Detail lives in the standard** | Detailed conventions belong in controlled project standards, not in this document. |
| **Define once** | A convention is defined in one place, not duplicated across documents that then drift apart. |
| **Deviations are deliberate** | Project-specific departures are decided and traceable, never incidental. |
| **Defaults are not standards** | Software defaults do not become project standards by being present. |
| **Standards mature progressively** | A standard may develop through controlled governance rather than arriving complete. |
| **Two kinds of standard** | Technical standards and information-management governance remain distinct. |

### 11.2 Standards Hierarchy and Applicability

Consistent with section 1.5:

```
applicable law / regulation
  → contractual / project requirements, where established
  → adopted external standards
  → approved BEP
  → approved project standards
  → operational / software configuration
```

**No external standards list is established for this project.** None is invented
here.

**ISO 19650.** Its principles inform the information-management approach of this
training implementation — the state model, the originator/recipient distinction
and the emphasis on purposeful exchange all derive from that thinking. This is a
statement about influence. **No formal compliance with ISO 19650 is claimed**,
and none has been established or assessed.

**SANS and other national standards.** No SANS standard is claimed to apply to
this project. Applicability has not been established, and asserting it would be
inventing a requirement.

Where the applicability of an external requirement is unknown, it remains an
**information gap** (section 2.6), not an assumed obligation.

### 11.3 Information Naming and Identification

Controlled naming and container identification will be defined in the project
**Naming Standard** (`standards/naming/`), which does not yet exist.

Principles that will inform it:

- information containers require unambiguous identity;
- naming should carry origin, discipline or task-team context, information type
  and other required metadata where approved;
- naming must be consistent enough to support retrieval and traceability;
- **platform folder placement alone is not identification** — a container must
  remain identifiable when moved, copied or exchanged.

**No final naming syntax is created here.** No field order, separator set or
permitted-value list is defined, and **no ISO 19650 filename pattern is imposed**.
Adopting a syntax is a governance decision to be taken when the Naming Standard
is developed.

### 11.4 Classification and Metadata

Classification and metadata should support:

- identity;
- filtering and search;
- responsibility;
- state and status;
- delivery purpose;
- interoperability where required.

**No classification system is adopted.** Uniclass, OmniClass, MasterFormat and
any other system remain **unadopted** unless approved through governance at a
later point. None is in use by default.

**Software-native metadata is not the project standard.** Parameters and
properties native to an authoring tool may carry project metadata, but the
project's metadata requirements are defined by governance, not inherited from
whatever fields a tool happens to provide.

### 11.5 Spatial Reference and Coordinates

**Candidate context — not approved governance.** Existing training and project
context refers to **Hartebeesthoek94 / Lo29** for the Harrismith location.

| | |
|---|---|
| Classification | Candidate / existing working context |
| Status | Requires controlled confirmation |
| Approved as project coordinate standard | **No** |

This is recorded so the context is not lost. It is **not** APPROVED GOVERNANCE,
and it must be confirmed through the governance process before becoming the
project coordinate standard. No detailed control-point coordinates are
reproduced in this document.

The controlled **Coordinates Standard** (`standards/coordinates/`) will define,
as applicable:

- coordinate reference system;
- project and site datum;
- shared-coordinate method;
- survey and control information;
- model positioning;
- true north and project north conventions;
- validation and checking method.

**Coordinate consistency is required before coordinated model use** — federation
across inconsistently positioned models produces findings that describe the
setup rather than the design (section 8.3). The method for achieving and
verifying that consistency belongs in the Coordinates Standard.

### 11.6 Model Authoring Conventions

Detailed model-authoring rules belong in discipline and project standards and in
approved templates, not in this BEP.

Subjects that may be governed there include:

- units;
- levels and grids;
- model segmentation;
- worksets and worksharing, where appropriate;
- model origin and reference rules;
- view and model organisation;
- object, family and content conventions;
- discipline-specific model structure.

**No detailed Revit standards are created here.** Revit remains an observed
authoring environment (section 2.4) and is **not mandatory for every container**
(section 7.4).

### 11.7 Drawing, Sheet and Documentation Standards

Controlled documentation standards may cover:

- sheet identification;
- drawing naming;
- titleblock use;
- revision presentation;
- issue information;
- graphical conventions.

Detailed rules belong in the controlled project standards and resources
(`standards/titleblocks/`). **This BEP defines no titleblock name and no
drawing-number syntax.**

### 11.8 Templates and Approved Project Resources

**As-found observation.** The Common Files areas for Templates and related
project resources were **observed empty during discovery** (section 2.5).

Consequently, **no approved project template set currently exists**, and nothing
in this document should be read as implying otherwise.

**A resource becomes project-approved only through the governance process.**
Software defaults, office templates and local resources are **not** project
resources by virtue of being available, familiar, or already in use. Approval is
an act, not an accumulation of habit.

Resources that may later be approved include:

- authoring templates;
- titleblocks;
- shared parameter resources;
- content libraries;
- checking resources.

None is populated here.

### 11.9 File Formats and Interoperability

Formats are selected according to:

- exchange purpose;
- recipient;
- interoperability requirement;
- authoring requirement;
- record requirement;
- the delivery plan.

Observed project contexts may include **RVT, IFC, PDF and NWC**. These are
**not universally mandatory**.

**Observed files are not future requirements.** That a format exists in the
project today is evidence of what has been produced; it is not evidence of what
must be delivered. Required formats are defined by the Information Delivery
Schedule and the relevant project standards (sections 10.8, 4.7).

### 11.10 Quality and Compliance Requirements

Information quality includes:

- compliance with approved project conventions;
- completeness for the intended purpose;
- correct identity and metadata;
- coordinate and reference consistency, where applicable;
- required checking;
- visibility of known limitations.

**Technical and regulatory design compliance is not an information-management
function.** It remains the responsibility of the appropriate technical or
task-team function (sections 5.7, 8.1).

**Automation assists; it does not replace review.** Software checking, rule
validation and automated reporting may support compliance work. They do not
substitute for professional or technical review where such review is required.
**No automated SANS compliance, regulatory approval or certification is claimed
or implied.**

### 11.11 Standards Exceptions and Changes

A departure from an approved project standard must be **explicit**. Record, as
appropriate:

| Field |
|---|
| Standard or convention affected |
| Reason |
| Affected information |
| Impact |
| Temporary or permanent nature |
| Decision required |
| Implementation and verification |

**Local software habit does not override a project standard.** A convention that
is inconvenient remains in force until it is changed through governance; working
around it silently is a deviation, and an unrecorded deviation is a defect in the
record rather than a change to the standard.

Detailed change governance is defined in Section 12.

### 11.12 Referenced Project Standards

Intended controlled standards areas:

| Area | Intended scope |
|---|---|
| `standards/naming/` | Container identification and naming syntax (section 11.3) |
| `standards/coordinates/` | Coordinate reference, datum, positioning and validation (section 11.5) |
| `standards/titleblocks/` | Titleblocks, sheet identification and documentation presentation (section 11.7) |
| `standards/templates/` | Authoring templates and approved project resources (sections 11.6, 11.8) |

**These directories do not contain approved standards.** They are control
locations for later governed standards work. The existence of a directory
establishes nothing about the existence, status or approval of a standard within
it.

## 12. Governance, Change and Exceptions

### 12.1 Governance Principles

```
observe / identify
  → classify
  → assess
  → decide
  → authorise
  → implement
  → verify
  → close / baseline
```

| Principle | |
|---|---|
| **Evidence ≠ decision** | Observing something is not deciding about it. |
| **Proposed ≠ approved** | Proposed governance carries no authority. |
| **Decision precedes configuration** | Platform change follows a governance decision, not the reverse. |
| **Changes are traceable** | What changed, why, who decided and when remain recoverable. |
| **Exceptions expire** | A temporary exception does not silently become a permanent rule. |
| **History stays visible** | Superseded decisions are retained, not erased. |

### 12.2 Governance Decision Types

The five classification terms used throughout this BEP:

| Term | Meaning |
|---|---|
| **OBSERVED FACT** | Evidence from the project or environment |
| **TRAINING ASSUMPTION** | A deliberate construct adopted for the training workflow |
| **PROPOSED GOVERNANCE** | A rule or change under consideration, not yet approved |
| **APPROVED GOVERNANCE** | A governing decision taken through the approved decision route |
| **UNRESOLVED DECISION** | A matter requiring a future decision |

Four further classes used by the governance register:

| Term | Meaning |
|---|---|
| **DEVIATION** | A deliberate, authorised departure from approved governance |
| **NON-CONFORMANCE** | An unintended failure to comply with approved governance |
| **APPROVED CHANGE** | An authorised alteration to the governed system |
| **SUPERSEDED DECISION** | An earlier decision replaced by a later approved decision, with history retained |

**Non-conformance requires something to conform to.** An as-found discrepancy is
not a non-conformance where no approved intended governance yet exists. Labelling
current observations as non-conformances against governance that has never been
approved would manufacture a compliance failure out of an open question. See
section 12.6.

### 12.3 Observed State vs Intended State

| State | Is |
|---|---|
| **As-found / observed** | Evidence of current reality |
| **Intended governance** | The approved target state |
| **Implemented state** | The operational state after an approved change |

Three consequences, each of which is routinely assumed away:

- **Observed state does not prove correctness.** Current practice is evidence of
  practice, not of rightness.
- **Intended state does not prove implementation.** An approved decision is not a
  configured system.
- **Implementation does not prove success.** A change applied is not a change
  verified (section 12.9).

### 12.4 Training Assumptions

Three training assumptions are in force: **TA-01** (simulated post-appointment
context), **TA-02** (simulated role participation) and **TA-03** (training
delivery organisation model). They are recorded in full in section 2.6 and are
not reproduced here.

Assumptions:

- must be explicit;
- exist so the workflow can be exercised realistically;
- are **not project facts**;
- are revisited when evidence becomes available;
- may be superseded or withdrawn through governance.

An assumption is promoted to OBSERVED FACT only by verification, and the
promotion is recorded (section 2.6).

### 12.5 Proposed Changes

A proposed change may originate from:

- discovery;
- participant contribution;
- coordination;
- a platform limitation;
- standards development;
- a delivery requirement;
- a lesson learned.

**A proposal is not authority to implement.** It must be assessed and decided
through the governance process. The Working Process (`working/`) is where
proposals and contributions live before a decision; governance lives in this BEP
and the register (section 1.4).

### 12.6 Deviations and Non-Conformance

| | |
|---|---|
| **DEVIATION** | A knowingly permitted departure from approved governance |
| **NON-CONFORMANCE** | An unintended departure from, or failure against, approved governance |

The difference is intent and authorisation, not severity.

**UD-001 is not a non-conformance.** Its current status is:

| | |
|---|---|
| Observation | An MEP / Structural Design Collaboration team-space discrepancy was observed (section 4.5) |
| Classification | **OBSERVED discrepancy + UNRESOLVED DECISION** |
| Why not a non-conformance | No intended mapping has been approved, so there is nothing for the configuration to fail against |

If an intended mapping is later approved and the live configuration still does
not match it, **that condition may then become a non-conformance**. Until then it
is an open question, and calling it a failure would assert governance that does
not exist.

### 12.7 Change Assessment and Approval

Changes are assessed according to impact. Three conceptual levels, with no formal
numeric categories:

| Level | Scope |
|---|---|
| **Minor operational change** | Implementation detail within already-approved governance |
| **Governance change** | Alters a process, responsibility, state transition, standard or platform mapping |
| **Major delivery / governance change** | Materially affects delivery obligations, the organisational model, information requirements or an approved baseline |

**The required authority corresponds to the nature of the decision.** A change
that alters responsibility cannot be decided by whoever happens to hold platform
access (sections 5.9, 6.9).

**No named approvers are invented.** Where the authority for a class of decision
remains TBD — including publication and exchange authority (section 9.7) and
acceptance authority (sections 9.8, 10.11) — that is recorded as unresolved
rather than assigned by convenience. The term "approve" is used only where a
defined approval decision exists (section 9.1).

### 12.8 Implementation of Approved Changes

Once a change is approved:

- identify affected documents, processes and platform elements;
- update the controlled documentation;
- implement the operational or platform change;
- communicate affected responsibilities;
- retain evidence of implementation.

**Document, process and platform configuration must remain aligned.** A change
applied to one and not the others produces a governance system that describes
something the project is not doing — the most common way controlled documentation
becomes ignored.

**This BEP does not itself authorise any live platform change.** Platform change
follows an approved governance decision (section 12.1).

### 12.9 Verification After Change

**A change is not complete because a document was edited or a setting was
clicked.** Verify that:

- the intended change was implemented;
- the affected workflow behaves as intended;
- responsibilities remain clear;
- no unintended consequence was introduced;
- supporting records are updated.

**The verifying role varies by change type.** No single universal verifier is
defined, and defining one would either overload a role or make verification
nominal.

### 12.10 Superseded Decisions and Historical Traceability

**History is not deleted because governance changed.** A superseded decision
retains:

| Field |
|---|
| Original decision |
| Status |
| Replacement decision |
| Effective point |
| Reason and context, where appropriate |

**Two complementary histories, not interchangeable:**

- **Git** provides technical change history for repository content — what text
  changed, when, and in which commit.
- **The Governance & Decision Register** provides decision history — what was
  decided, by whom, on what basis, and what it replaced.

Neither substitutes for the other. A commit shows that wording changed; it does
not show that a decision was taken (section 9.11).

### 12.11 BEP Revision and Progressive Baselining

```
controlled draft
  → baseline candidate
  → approved training baseline
  → later revision
  → superseded baseline retained
```

Baselines may run 0.1, 0.2 … 1.0. **No semantic-versioning rules beyond this are
implied or approved.**

**BEP Training Baseline 0.1 is not approved.** This document's current status is
declared in section 1.2; see also section 9.10.

**Changes affecting approved governance may require a new baseline rather than
silent amendment.** Once a baseline is approved, editing it in place would
destroy the distinction between what was agreed and what is currently proposed.

### 12.12 Escalation and Unresolved Decisions

An unresolved decision remains **visible**. Record, as appropriate:

| Field |
|---|
| The decision or question |
| Reason it is unresolved |
| Affected area |
| Impact and risk |
| Responsible decision function or owner, **where established** |
| Review trigger or required next step |

**No owner is invented where none is established.** "Decision owner: not
established" is a valid and useful entry; a plausible name in that field is not.

Escalation is used when the normal governance route cannot resolve a matter
(section 8.12).

**UD-001 remains the current worked example, and remains unresolved.** It is not
resolved in this section, and no intended replacement mapping is proposed.

### 12.13 Governance & Decision Register Reference

`supporting/governance-decision-register.md` is the **single consolidated
authoritative record** for governance matters. It is separately controlled and
declares its own status, version and authority. Reference from this BEP does not
constitute approval of it (section 13.6).

It will record:

- observed facts requiring governance attention;
- training assumptions;
- proposals;
- decisions;
- unresolved decisions;
- deviations;
- non-conformances;
- approved changes;
- superseded decisions;
- implementation and verification status.

**One register only.** Competing governance registers are not created — a
decision recorded in two places is a decision that will eventually exist in two
different versions.

## 13. Controlled References

### 13.1 Purpose

Section 13 identifies the controlled resources this BEP relies upon.

**The BEP references controlled detail rather than duplicating it.** Duplication
creates divergence, and divergence in governance documentation is worse than
absence, because both copies appear authoritative.

**Reference does not imply approval.** Listing a resource here records that the
BEP depends on it. The resource's own status determines whether it may be relied
upon (section 13.6).

### 13.2 Supporting Management Resources

| Resource | Purpose |
|---|---|
| `supporting/information-management-responsibility-matrix.md` | Allocation of information-management functions to roles and process steps |
| `supporting/model-information-responsibility-matrix.md` | Which task team authors and maintains each model and information container |
| `supporting/information-delivery-schedule.md` | What is delivered, by whom, to whom, in what form and when |
| `supporting/cde-workflow-state-strategy.md` | Container states, transitions and the controls on each |
| `supporting/coordination-review-strategy.md` | Coordination cycles, clash and interface management, review and verification |
| `supporting/governance-decision-register.md` | Decisions, assumptions, deviations and unresolved matters |

**Each resource is separately controlled.** Each declares its own status, version
and authority within the resource itself, using the vocabulary in section 13.6.
Listing a resource here records that this BEP depends on it; it does not
constitute approval of that resource or of its content.

### 13.3 Referenced Project Standards

| Standard area | Location | Status |
|---|---|---|
| Naming | `standards/naming/` | Not established |
| Coordinates | `standards/coordinates/` | Not established |
| Titleblocks | `standards/titleblocks/` | Not established |
| Templates / authoring resources | `standards/templates/` | Not established |

**A directory is not a standard.** These areas are not approved merely because
the repository contains them. Each standard's status is controlled individually
(section 13.6), and no standards content is invented (section 11).

### 13.4 External Standards and Requirements

**No external standard is listed as applicable to this project**, because
applicability has not been established for any.

**ISO 19650** principles inform the information-management framework of this
training implementation. This is a statement of influence on the approach taken.
**No formal project compliance, assessment or certification is claimed.** No
copyrighted standards content is reproduced in this repository.

**No SANS applicability is asserted.**

Where the applicability of an external requirement is unresolved, it is recorded
as an information gap (section 2.6) rather than assumed in either direction.

### 13.5 Source-of-Truth and Publication Rules

The **Git repository is the authoritative authoring source** for this BEP and its
controlled source documents.

**A Git draft is not the issued project BEP.**

```
approved source / baseline
  → generated / project-facing artefact
  → controlled manual publication
  → Forma / Data Management CDE
```

The approved project-facing artefact in the CDE is the **issued baseline for that
issued version**.

**Divergence is expected and legitimate.** Git may hold a newer controlled draft
while the CDE still holds the last issued baseline. That is correct behaviour
provided the status of each is clear — it is the reason status is stated in
section 1.2 and carried on every controlled reference.

Three standing constraints (section 6.10):

- the repository is not placed inside the Desktop Connector location;
- **no symlink, junction, bind-mount or live-sync publication model is approved
  for this workflow**;
- **manual controlled publication is the approved initial publication model.**

**No publication automation is approved or implemented.**

### 13.6 Reference Status and Version Control

Status concepts for controlled references:

| Status | Meaning |
|---|---|
| **Working Draft** | Under development; not for reliance |
| **For Review** | Issued for controlled review |
| **Approved Training Baseline** | Approved through the governance route |
| **Superseded** | Replaced by a later approved version, retained for traceability |
| **Withdrawn** | No longer to be relied upon |

**Status is declared by the resource, not inferred from this BEP.** Each
controlled reference states its own status using the vocabulary above, and a
reader determines reliability from that declaration rather than from the fact
that this BEP refers to it. Nothing is approved by virtue of being referenced.

This BEP's own status is declared in section 1.2. No project standard is
established (section 11.12).

A controlled reference should expose enough status and version information for a
reader to determine **whether it may be relied upon**. A later version supersedes
an earlier issued version only through the controlled governance route.

**Git commit history is technical source history.** It does not by itself
establish approval, CDE issue, delivery or recipient acceptance — see section
9.11.
