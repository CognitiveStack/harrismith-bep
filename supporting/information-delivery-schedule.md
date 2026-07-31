# Information Delivery Schedule

## Document purpose and status

**Purpose.** Records what information is exchanged, at what event, to whom, why,
in what form, and under what checking, authorisation and acceptance conditions.

This is a **controlled training delivery-planning instrument**. It is **not a
contractual programme**.

Referenced by BEP sections 10.13 and 7.12.

| Field | Value |
|---|---|
| Document status | **Controlled Draft** |
| Authority | Supporting management resource to the Harrismith BEP controlled draft |
| Approval | **Not approved** as part of BEP Training Baseline 0.1 |
| Supports | BEP section 10 — Information Delivery and Exchange |

**Classification.** All entries below are **PROPOSED GOVERNANCE / training
delivery planning**. They are **not** contractual milestones and **not** client
information requirements.

## What these entries are not

These schedule entries exist to exercise the Harrismith BIM-management workflow.
They are **not evidence** of:

- real client information requirements;
- contractual delivery milestones;
- actual consultant appointments;
- construction programme dates.

**No real delivery dates or client milestones have been established.** No formal
Employer's / Exchange Information Requirements, Asset Information Requirements or
equivalent have been established or made available to this implementation (BEP
7.3, 10.2). None are invented here.

**Precedence.** Should real project information requirements later become
available, they take precedence over anything developed in their absence, in
accordance with BEP section 1.5.

**Population rule.** Dates, stages, milestones and deliverables are not invented,
estimated, or inferred from a typical programme. Where timing is not established,
entries are **event-triggered or TBD**. Where an authority is unresolved, the
entry records it as unresolved rather than assigning it.

**Container discipline.** Every scheduled discipline container references an
existing container ref from `model-information-responsibility-matrix.md`. No
container is scheduled that does not exist in that matrix.

---

## 1. Schedule fields

The fields approved in BEP 10.13. Wide tables are split by field group for
readability; no field is removed.

| Field | Meaning |
|---|---|
| Delivery ID | Identifier for a scheduled container row |
| Exchange / Milestone | The event the row belongs to |
| Information Container | Container ref from the Model / Information Responsibility Matrix |
| Originating Party | Party producing the container |
| Task Team | Task team producing the container |
| Discipline | Information domain |
| Lead | Role leading the exchange for that container |
| Recipient | Who receives it |
| Purpose | Why it is exchanged |
| Format | Delivery format |
| State / Suitability | CDE state and what the information may be used for |
| Checking Requirement | Checks required before progression |
| Authorisation Requirement | The authorisation permitting progression |
| Acceptance Criteria | Process-level criteria for receipt |
| Status | Status of the schedule entry itself |
| Dependencies | What the row depends on |

**Identifiers are training schedule identifiers.** `TRN-E01-ARC` and similar are
internal references for this exercise. They are **not** contractual document
numbers and carry no project numbering convention — no Naming Standard exists
(BEP 11.3).

## 2. Delivery event concepts

Three restrained training event concepts. This is **not** a full project delivery
schedule.

| Event | Concept | Timing | Status |
|---|---|---|---|
| **TRN-E01** | Design coordination share | Event-triggered / TBD | PROPOSED |
| **TRN-E02** | Coordination reshare / resolution update | After required resolution; event-triggered / TBD. Repeatable | PROPOSED — **conditional**, activated per affected container only |
| **TRN-E03** | Controlled design review / project-facing exchange | TBD | **PROPOSED — BLOCKED pending governance decisions** |

**No calendar dates, frequencies or contractual milestones exist for any event.**
TRN-E02 is repeatable and conditional, and is deliberately given **no calendar
frequency**. Its rows activate only for containers actually requiring reshare —
see section 4.2.

---

## 3. TRN-E01 — Design coordination share

| Field | Value |
|---|---|
| Purpose | Controlled multidisciplinary coordination |
| Recipient | BIM Coordinator; participating coordination task teams as appropriate |
| State | **Shared** |
| Suitability | **Coordination use only** |
| Timing | Event-triggered / TBD |
| Status | **PROPOSED** — not scheduled as a contractual milestone |

Each discipline container is shared **from its own originating task team**. The
six rows below are six separate exchanges, not one jointly-owned model.

### 3.1 Scheduled rows

| Delivery ID | Container | Originating party | Task team | Discipline | Lead |
|---|---|---|---|---|---|
| TRN-E01-ARC | ARC-01 | Architectural Consultant | Architectural task team | ARC | Task-Team Lead (TBD) |
| TRN-E01-STR | STR-01 | Structural Consultant | Structural task team | STR | Task-Team Lead (TBD) |
| TRN-E01-MEC | MEC-01 | MEP Consultant | Mechanical task team | MEC | Task-Team Lead (TBD) |
| TRN-E01-ELE | ELE-01 | MEP Consultant | Electrical task team | ELE | Task-Team Lead (TBD) |
| TRN-E01-PLM | PLM-01 | MEP Consultant | Plumbing task team | PLM | Task-Team Lead (TBD) |
| TRN-E01-FIR | FIR-01 | Fire Consultant | Fire task team | FIR | Task-Team Lead (TBD) |

MEC, ELE and PLM originate from a **single MEP Consultant** party. FIR originates
from the **separate Fire Consultant** (BEP 4.3).

### 3.2 Conditions — all TRN-E01 rows

| Field | Value |
|---|---|
| Format | **TBD by approved format requirement.** No format is mandated. |
| State / Suitability | **Shared — coordination use only** |
| Checking Requirement | Task-team technical / content check **and** information-quality / readiness check (BEP 7.6, 9.3) |
| Authorisation Requirement | **Task-Team Lead authorisation to share** (BEP 5.7, 7.8, 9.4; IM matrix P4) |
| Acceptance Criteria | The receiver can identify the container, its purpose, its originator and its applicable limitations, and can decide whether to consume or reference it for coordination |
| Dependencies | Readiness confirmed (BEP 7.7); coordinate / reference consistency (BEP 8.3, 11.5 — coordinate reference remains candidate context) |

**Suitability is coordination only.** Information shared under TRN-E01 is **not**
construction-ready, **not** formally accepted design, and **not** record
information (BEP 6.7, 10.7).

**The receiver's decision is not design approval.** A decision to consume or
reference shared information for coordination is a consumption decision. It does
not approve the design, and it does not transfer technical responsibility from
the originating task team (BEP 6.5, 7.9, 9.5).

---

## 4. TRN-E02 — Coordination reshare / resolution update

| Field | Value |
|---|---|
| Purpose | Provide revised discipline information following coordination findings or issues, for re-coordination |
| Originator | The affected discipline / task team |
| Recipient | BIM Coordinator; participating coordination task teams as appropriate |
| State | **Shared** |
| Suitability | **Coordination use only** |
| Timing | After required resolution; event-triggered / TBD |
| Status | **PROPOSED**. **Repeatable and conditional** — **no calendar frequency** |

**TRN-E02 is a repeatable conditional event.** A discipline participates **only
when its own information requires revision and controlled reshare** as a
consequence of a coordination finding or issue, or an equivalent governed need.

**The existence of this event does not mean all six disciplines reshare during
every coordination cycle.** A cycle may activate one container, several, or none.

### 4.1 Lifecycle

```
WIP correction
  → check
  → authorise share
  → Shared
  → re-coordinate
  → verify
```

The **originating task team** performs the correction in its own WIP environment
and its own checking route. The shared instance is not edited in place as an
uncontrolled workaround (BEP 7.10, 8.10).

### 4.2 Conditional template rows

The rows below are **template rows, not active deliveries**. Each is activated
only when its own container requires controlled rework and reshare. An
unactivated row is not a pending exchange and carries no expectation that the
task team will produce anything.

| Delivery ID | Container | Originating party | Task team | Discipline | Activation |
|---|---|---|---|---|---|
| TRN-E02-ARC | ARC-01 | Architectural Consultant | Architectural task team | ARC | **Conditional** — activated only when ARC-01 requires controlled rework and reshare |
| TRN-E02-STR | STR-01 | Structural Consultant | Structural task team | STR | **Conditional** — activated only when STR-01 requires controlled rework and reshare |
| TRN-E02-MEC | MEC-01 | MEP Consultant | Mechanical task team | MEC | **Conditional** — activated only when MEC-01 requires controlled rework and reshare |
| TRN-E02-ELE | ELE-01 | MEP Consultant | Electrical task team | ELE | **Conditional** — activated only when ELE-01 requires controlled rework and reshare |
| TRN-E02-PLM | PLM-01 | MEP Consultant | Plumbing task team | PLM | **Conditional** — activated only when PLM-01 requires controlled rework and reshare |
| TRN-E02-FIR | FIR-01 | Fire Consultant | Fire task team | FIR | **Conditional** — activated only when FIR-01 requires controlled rework and reshare |

**Only affected containers become active exchanges.** A row becomes an active
TRN-E02 exchange when, and only when, its trigger occurs — a coordination
finding or issue assigned to that task team, or an equivalent governed need. The
six rows are the full set of containers that *could* be reshared; they are not a
set that *will* be reshared.

### 4.3 Conditions — applying to any activated TRN-E02 row

| Field | Value |
|---|---|
| Lead | Task-Team Lead (TBD) |
| Format | **TBD by approved format requirement** |
| Checking Requirement | Task-team check of the revised information before reshare (BEP 7.10) |
| Authorisation Requirement | **Task-Team Lead authorisation to share** |
| Acceptance Criteria | Revised information has completed the controlled rework / reshare cycle and is available for re-coordination |
| Dependencies | Coordination finding or issue raised and assigned (BEP 8.7); TRN-E01 row for the same container |

**Verification is not design approval.** BIM Coordinator verification confirms
that the coordination process reached a disposition. It is not discipline design
approval, professional certification, or acceptance of technical responsibility
(BEP 8.10, 9.5).

**Superseded exchanges remain traceable.** Previous exchanges are marked
superseded, not deleted (BEP 7.10, 9.9).

---

## 5. TRN-E03 — Controlled design review / project-facing exchange

| Field | Value |
|---|---|
| Purpose | Exercise the transition from coordinated information toward an authorised project-facing review exchange |
| Classification | **TRAINING delivery event proposal** |
| Timing | **TBD** |
| Format | **TBD** by purpose, recipient and approved standards |
| Status | **PROPOSED — BLOCKED PENDING GOVERNANCE DECISIONS** |

**This is not evidence of a real project milestone.**

### 5.1 Why this event is blocked

| Blocking matter | Status | Reference |
|---|---|---|
| Publication / exchange authorisation authority | **UNRESOLVED — TBD** | BEP 9.7; IM matrix D4 |
| Recipient acceptance authority | **UNRESOLVED — TBD / recipient-dependent** | BEP 9.8, 10.11; IM matrix D7 |
| Recipient identity | Not established | BEP 2.3, 5.3 |
| Required formats | Not established — no approved standard | BEP 11.9, OF-003 |
| Deliverable set | Not defined | BEP 10.4 |

**These are not resolved to complete the schedule.** An entry that cannot proceed
is recorded as blocked. Assigning a plausible authority to make the row look
finished would manufacture governance that does not exist.

### 5.2 Scheduled content

| Field | Value |
|---|---|
| Information Container | **TBD.** May draw on ARC-01, STR-01, MEC-01, ELE-01, PLM-01, FIR-01 and later-defined document containers. The deliverable set is **not defined** |
| Originating Party / Task Team / Discipline | Per the containers ultimately included |
| Lead | TBD |
| Recipient | **TBD — not established** |
| Format | **TBD** |
| State / Suitability | **Published / Authorised only if** the required delivery review has occurred **and** publication authorisation has been given. Neither condition can currently be met |
| Checking Requirement | Task-team checks complete; delivery readiness review performed (BEP 9.6, 10.9) |
| Authorisation Requirement | **TBD — publication / exchange authority unresolved** |
| Acceptance Criteria | **TBD** pending defined recipient, requirement, and publication / acceptance authority |
| Dependencies | Resolution of BEP 9.7 and 9.8 authorities; defined recipient and requirement; approved formats |

**No final deliverable set is invented.** Models, drawings, documents and
supporting information may form part of this exchange **only when later defined**
through an explicit decision.

**RVT, IFC, PDF and NWC are not mandated.** They appear in observed project
context. An observed format is not an approved delivery requirement (BEP 10.8,
11.9).

### 5.3 Four distinct states

TRN-E03 exercises transitions that are routinely conflated. They remain distinct
(BEP 10.11):

| Published | Delivered | Received | Accepted |
|---|---|---|---|
| Authorised for a defined purpose | Sent to an identified recipient | Arrived and registered | Acknowledged as suitable for the stated purpose |

Delivery does not prove acceptance. Receipt does not prove suitability.
Acceptance applies only to the identified purpose, and does not transfer
technical responsibility from the originator.

---

## 6. Role consistency

Consistent with `information-management-responsibility-matrix.md`; not duplicated
here.

| Function | Allocation |
|---|---|
| Authorise controlled sharing (TRN-E01, TRN-E02) | **Task-Team Lead** — established by BEP 9.4 |
| Coordinate TRN-E01 / TRN-E02 | **BIM Coordinator** — coordinates the process; does **not** technically approve discipline information |
| Authorise publication / exchange (TRN-E03) | **UNRESOLVED — TBD** |
| Accept exchange | **UNRESOLVED — TBD / recipient-function dependent** |
| Execute approved platform configuration and transmission functions | **CDE Administration** — does **not** become publication authority by performing them (BEP 5.9, 6.9) |

## 7. Unresolved delivery requirements

| Matter | Status |
|---|---|
| Real delivery milestones and dates | **None established.** All timing event-triggered or TBD |
| Client / project information requirements | **None available to this implementation** |
| Publication / exchange authority | **UNRESOLVED — TBD** |
| Recipient acceptance authority | **UNRESOLVED — TBD** |
| Recipient identity | Not established |
| Required formats | **TBD** — no approved project standard |
| Final deliverable set | Not defined |
| Level of information need | Not defined |
| Naming and container identification | **TBD** — no Naming Standard exists |

None of these is resolved by this schedule. Each is recorded so the gap remains
visible rather than filled with a plausible value.
