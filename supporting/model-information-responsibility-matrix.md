# Model / Information Responsibility Matrix

## Document purpose and status

**Purpose.** Records which party and task team is intended to produce and
maintain each information container or container class.

This resource answers one question: **who produces and maintains which
information container?**

It complements, and does not duplicate:

| Resource | Answers |
|---|---|
| `information-management-responsibility-matrix.md` | Who performs which information-management **process function** |
| `information-delivery-schedule.md` | What is exchanged, when, why, to whom and in what form |

Referenced by BEP sections 7.2 and 7.12.

| Field | Value |
|---|---|
| Document status | **FOR REVIEW — Training Baseline 0.1 Candidate** |
| Authority | Supporting management resource under the Harrismith BEP framework |
| Approval | **Not approved.** Candidate review does not confer approval |
| Supports | BEP section 7 — Information Production and Sharing |

**Classification of the allocations below.** Every allocation in section 3 is
**PROPOSED GOVERNANCE** for the training delivery model, derived from the
training organisation model recorded as **TA-03**. No allocation constitutes a
real professional appointment, and no organisation or individual is named.

**Population rule.** Allocations are made against the **functional parties and
task teams** defined in BEP Section 4, not against companies or people. Where the
live project structure differs from an allocation here, the observed structure is
recorded as an OBSERVED FACT in `governance-decision-register.md` and is **not
silently corrected** in this matrix. Level of information need is not assumed
from discipline convention.

**Intended governance, not live inventory.** This matrix describes what is
intended to be produced under the training delivery model. It is **not** an
inventory of what currently exists in the CDE. Only Architecture was observed as
a populated direct production stream at the inspected level (OF-002); absence of
observation is not observation of absence.

---

## 1. Matrix scope

**In scope.** Design discipline information containers for the six discipline
domains in BEP 4.4, plus one multidisciplinary coordination information class.

**Out of scope.** Construction and trade-contractor information containers —
see section 5. Level of information need — see section 4. Delivery events,
formats and timing — see the Information Delivery Schedule.

## 2. Parties and task teams

Taken from BEP 4.2 and 4.3. No organisation is appointed; no holder is
established.

| Party | Task team(s) | Discipline code(s) |
|---|---|---|
| Architectural Consultant | Architectural task team | ARC |
| Structural Consultant | Structural task team | STR |
| **MEP Consultant** | Mechanical task team; Electrical task team; Plumbing task team | MEC, ELE, PLM |
| **Fire Consultant** | Fire task team | FIR |

**Two rules carried from BEP 4.3, and easily got wrong:**

- **MEC, ELE and PLM sit within a single MEP Consultant organisation.** They are
  three task teams and three disciplines within **one** party — not three
  companies.
- **FIR is organisationally separate**, carried by the Fire Consultant as a
  distinct party. It is not an MEP sub-team.

**A discipline code is not an organisation.** A discipline code identifies the
information domain of a container and nothing else — not the organisation, task
team, author, platform team or contractual responsibility (BEP 4.4). Six
discipline codes do not imply six organisations.

## 3. Model and container allocation

All rows: **Classification — PROPOSED GOVERNANCE** (per TA-03).
All Lead entries: **Task-Team Lead, holder TBD** (BEP 5.7).
All Contributors: **Authors and Checkers as allocated through BEP Section 5 and
the Information Management Responsibility Matrix.**

### 3.1 Discipline design / coordination containers

| Ref | Information container / class | Originating party | Task team | Discipline | Primary purpose |
|---|---|---|---|---|---|
| **ARC-01** | Architectural design / coordination model | Architectural Consultant | Architectural task team | ARC | Discipline authoring, multidisciplinary coordination, controlled design exchange |
| **STR-01** | Structural design / coordination model | Structural Consultant | Structural task team | STR | Structural authoring, multidisciplinary coordination, controlled exchange |
| **MEC-01** | Mechanical design / coordination model | **MEP Consultant** | Mechanical task team | MEC | Mechanical authoring, multidisciplinary coordination, controlled exchange |
| **ELE-01** | Electrical design / coordination model | **MEP Consultant** | Electrical task team | ELE | Electrical authoring, multidisciplinary coordination, controlled exchange |
| **PLM-01** | Plumbing design / coordination model | **MEP Consultant** | Plumbing task team | PLM | Plumbing authoring, multidisciplinary coordination, controlled exchange |
| **FIR-01** | Fire design / coordination model | **Fire Consultant** | Fire task team | FIR | Fire authoring, multidisciplinary coordination, controlled exchange |

### 3.2 Formats and intended CDE states

| Ref | Authoring / source format | Exchange format | Intended CDE states |
|---|---|---|---|
| ARC-01 | TBD by approved project standard / fit-for-purpose authoring requirement | TBD by purpose and the Information Delivery Schedule | WIP → Shared → Published/Authorised where a defined delivery requires it |
| STR-01 | TBD by approved project standard / fit-for-purpose authoring requirement | TBD by purpose and the Information Delivery Schedule | WIP → Shared → Published/Authorised where a defined delivery requires it |
| MEC-01 | TBD by approved project standard / fit-for-purpose authoring requirement | TBD by purpose and the Information Delivery Schedule | WIP → Shared → Published/Authorised where a defined delivery requires it |
| ELE-01 | TBD by approved project standard / fit-for-purpose authoring requirement | TBD by purpose and the Information Delivery Schedule | WIP → Shared → Published/Authorised where a defined delivery requires it |
| PLM-01 | TBD by approved project standard / fit-for-purpose authoring requirement | TBD by purpose and the Information Delivery Schedule | WIP → Shared → Published/Authorised where a defined delivery requires it |
| FIR-01 | TBD by approved project standard / fit-for-purpose authoring requirement | TBD by purpose and the Information Delivery Schedule | WIP → Shared → Published/Authorised where a defined delivery requires it |

**On formats.** Revit is an **observed** authoring environment on this project
(BEP 2.4). **Observed use does not make RVT mandatory for any task team or any
container.** No format is mandated here. RVT, IFC, PDF and NWC appear in observed
project context; an observed format is evidence of what has been produced, not a
future delivery requirement (BEP 10.8, 11.9). Exchange formats are governed by
purpose, interoperability need and the Information Delivery Schedule.

**On CDE states.** The state sequence above is **intended governance**, not a
claim that any container currently exists in any of these states. Publication
occurs only where a defined delivery requires it and the required authorisation
has occurred — and that authority is unresolved (section 6).

### 3.3 Dependencies and interfaces

| Ref | Dependencies / interfaces |
|---|---|
| ARC-01 | Spatial and interface dependency with STR-01, MEC-01, ELE-01, PLM-01, FIR-01. Coordinate/reference consistency required (BEP 11.5). |
| STR-01 | Interface with ARC-01; service penetration and support interfaces with MEC-01, ELE-01, PLM-01, FIR-01. |
| MEC-01 | Interface with ARC-01, STR-01; services coordination with ELE-01, PLM-01, FIR-01. |
| ELE-01 | Interface with ARC-01, STR-01; services coordination with MEC-01, PLM-01, FIR-01. |
| PLM-01 | Interface with ARC-01, STR-01; services coordination with MEC-01, ELE-01, FIR-01. |
| FIR-01 | Interface with ARC-01, STR-01; services coordination with MEC-01, ELE-01, PLM-01. |

Interfaces are listed to identify where coordination is expected. They do not
allocate technical design responsibility across parties — each originating task
team remains responsible for its own content (BEP 7.2).

### 3.4 Multidisciplinary coordination information

| Field | Value |
|---|---|
| **Ref** | **COORD-01** |
| Information class | Federated coordination set / coordination working set |
| Classification | PROPOSED GOVERNANCE |
| Lead function | **BIM Coordinator** (holder TBD) |
| Contributors | ARC, STR, MEC, ELE, PLM and FIR task teams, as applicable |
| Originating party | Not applicable — see note below |
| Primary purpose | Temporary controlled aggregation for multidisciplinary coordination |
| Source | Controlled **Shared** discipline containers (BEP 6.6, 8.3) |
| Format | TBD by the coordination environment and approved workflow |
| Intended CDE state | Coordination working information — see note |

**COORD-01 is not a jointly-authored design model.** Federation is the temporary,
controlled aggregation of separate discipline information for coordination
purposes. It does **not**:

- merge authorship;
- transfer technical ownership or responsibility from the originating task teams;
- create a new design author;
- turn discipline models into one jointly-owned authoring model.

Each contributed container keeps its originator, its state and its technical
responsibility (BEP 8.5). The BIM Coordinator leads the coordination process and
does **not** own the technical design solution (BEP 5.6, 8.10).

**COORD-01 is not a project deliverable.** It is a coordination construct. It
does not become a deliverable unless and until it is scheduled as one in the
Information Delivery Schedule through an explicit decision.

## 4. Level of information need

**Not defined.** Level of information need has not been established for any
container.

No formal information requirements are available to this implementation (BEP 7.3,
10.2), and level of information need is **not** assumed from discipline
convention or inferred from observed model content. It is recorded as an
information gap and will be developed as PROPOSED GOVERNANCE alongside the
Information Delivery Schedule.

## 5. Construction and trade information — future extension

The training organisation model (BEP 4.1, 4.3) allows for later introduction of:

- Mechanical Trade Contractor task team;
- Electrical Trade Contractor task team;
- Plumbing Trade Contractor task team;
- Fire Trade Contractor task team.

**No trade or contractor information containers are defined.** This is a
**recorded future extension**, not missing data to be invented now. These task
teams exist in the organisation model only *when introduced* into the training
delivery workflow, and their containers will be allocated at that point.

**Trade/construction information is distinct from design consultant
information.** They are produced by different parties, for different purposes, at
different levels of definition, under different responsibilities. Contractor
models are not to be treated as consultant design information (BEP 7.2).

## 6. Unresolved allocations and dependencies

| Matter | Status | Reference |
|---|---|---|
| Task-Team Lead holders, every task team | **TBD** | BEP 5.7 |
| Authoring and exchange formats | **TBD** — no approved project standard exists | BEP 11.9, OF-003 |
| Level of information need | **Not defined** | Section 4 above |
| Publication / exchange authority | **UNRESOLVED — TBD** | BEP 9.7 |
| Recipient acceptance authority | **UNRESOLVED — TBD** | BEP 9.8, 10.11 |
| Naming and container identification | **TBD** — no Naming Standard exists | BEP 11.3, OF-003 |
| Coordinate reference for coordinated model use | **Candidate context only**, requires confirmation | BEP 11.5, OF-003 |
| Design Collaboration team-space mapping | **UD-001 — UNRESOLVED** | BEP 4.5, 4.7 |
| Trade / contractor containers | Future extension, not defined | Section 5 above |

**UD-001 is not resolved by this matrix.** The observed MEP / Structural
team-space mapping discrepancy remains an open question. Nothing in the
allocations above proposes, implies or applies a replacement mapping, and this
matrix does not correct the observed platform configuration.
