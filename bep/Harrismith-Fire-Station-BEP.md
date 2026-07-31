# Harrismith Fire Station — BIM Execution Plan

> **Status:** Controlled draft.
> **Target baseline:** BEP Training Baseline 0.1 — in development, **not approved**.
> **Issued to CDE:** No.
> **Authority:** None. Training/reference implementation. Non-contractual.
> **Architecture:** Architecture Baseline v1 (frozen at Gate B). Sections are not
> to be renumbered, merged, split or resequenced.
> **Drafted to date:** Sections 1–5. Sections 6–13 remain scaffold.

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
| Status | Draft — Sections 1–5 drafted; Sections 6–13 scaffold |
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
| TA-03 | The delivery organisation and task-team structure defined in Section 4 is a training organisation model. It does not constitute actual appointment of any organisation, company, consultant, contractor or professional role. | Allows organisation, task-team, discipline and information-management responsibility interfaces to be exercised realistically. |

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
and joins them for transcription to the Governance & Decision Register in a
later controlled increment.

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
in this increment. See section 4.7.

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

That matrix is **not populated in this increment.**

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
