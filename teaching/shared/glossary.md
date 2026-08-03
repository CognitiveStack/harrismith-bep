# Teaching Glossary

**Status:** Teaching glossary for the BIM Management programme. **Not
governance, and not a standards reference.**

---

## 1. How to read this glossary

Definitions here are **simplified for spoken teaching**. The controlled
documents are authoritative. Where a teaching definition and a controlled
document differ, the controlled document is correct.

Two columns are given where they differ:

- **Practical teaching wording** — how to say it to a mixed audience.
- **As used in the Harrismith sources** — how the controlled documents actually
  use the term, with the source reference.

Where a term is commonly associated with ISO 19650 but is **not used in the
Harrismith sources**, this is stated explicitly. See section 3.

---

## 2. Terms

### BIM

| | |
|---|---|
| **Practical** | A managed way of producing, sharing, coordinating and using information about a building — not a piece of software |
| **In the sources** | Used throughout as an information-management discipline. The BIM Delivery Guide glossary defines it as "a managed way of producing, sharing, coordinating and using information about a built asset" |

The most useful teaching move is subtraction: BIM is not Revit, and a project can
own a great deal of Revit without doing any of this.

### BIM Management

| | |
|---|---|
| **Practical** | Governing who produces information, who checks it, who may share it, and what it may be used for |
| **In the sources** | The BEP's own objective (§3.1) is a BIM management objective; the BIM Delivery Guide defines information management in these terms |

Distinguished from software operation throughout the programme — see
[`presentation-principles.md`](presentation-principles.md) section 3.

### BIM Execution Plan (BEP)

| | |
|---|---|
| **Practical** | The project team's agreed method for producing, coordinating, checking, sharing and approving information |
| **Fuller teaching definition** | Defines how the project team will produce, manage, exchange, coordinate, review and deliver information to satisfy the project's information requirements |
| **In the sources** | BEP §1.1: developed to define the BIM and information-management approach; once approved, governs how information is produced, checked, shared, coordinated, reviewed, authorised, delivered and governed through change |

**The two teaching definitions above are teaching wording.** They do not replace
or restate the BEP's own purpose statement.

Harrismith's BEP is described in its own §1.2 as a **post-appointment-style BEP
written as a training and reference implementation** — structured as a real
project BEP would be, with no real appointment behind it.

### Information requirement

| | |
|---|---|
| **Practical** | What the project needs the information for, and who needs it |
| **In the sources** | BEP §10.2: delivery responds to defined information requirements. **No formal client or project information requirements have been established** for this implementation, and none are invented; training requirements are explicitly classified as PROPOSED GOVERNANCE or TRAINING ASSUMPTION |

**Teaching caution.** Do not imply Harrismith has established information
requirements. It has recorded their absence — which is itself the lesson.

### Information container

| | |
|---|---|
| **Practical** | An identifiable set of information — a model, drawing, schedule, report or record |
| **In the sources** | Used throughout the BEP and both matrices. BEP §10.4: a delivery is not synonymous with a file — one exchange may carry several containers |

The term earns its place in teaching because "file" is wrong and "model" is too
narrow.

### Appointing party

| | |
|---|---|
| **Practical** | The client — the party that establishes what information the project needs and receives it |
| **In the sources** | Used as **"Owner / Appointing Party"** (BEP §4.1, §4.2, §5.3). **Identity: not established — TBD** (BEP §2.3) |

### Lead appointed party

| | |
|---|---|
| **Practical** | The party that coordinates delivery across the other contributing parties |
| **In the sources** | **This term is not used anywhere in the Harrismith sources.** The sources use **"Lead Delivery Party"** for this position (BEP §4.1, §4.2, §5.4). Holder **not established — TBD** |

**Do not attribute "lead appointed party" to the Harrismith BEP.** If the term
is introduced in teaching as the more widely recognised one, say plainly that
Harrismith uses "Lead Delivery Party".

### Appointed party

| | |
|---|---|
| **Practical** | A party appointed to deliver part of the project's information |
| **In the sources** | **This term is not used anywhere in the Harrismith sources.** The sources use party categories directly — Architectural Consultant, Structural Consultant, MEP Consultant, Fire Consultant, General Contractor, trade contractors (BEP §4.2) — and **no organisation is appointed to any of them** |

### Task team

| | |
|---|---|
| **Practical** | The group producing a defined package of information |
| **In the sources** | BEP §4.3, and throughout both matrices. Explicitly **not** the same as a party, a discipline, an Autodesk collaboration team or an information-management role (BEP §4.2) |

BEP §4.2 lists these five as deliberately not interchangeable. They may map to
one another — often they do — but a mapping is a decision to be recorded, not an
identity to be assumed. Concretely: Mechanical, Electrical and Plumbing are three
task teams inside a **single MEP Consultant** party, and Fire is a **separate**
party.

### CDE — Common Data Environment

| | |
|---|---|
| **Practical** | The managed process by which project information changes state and control — supported by technology |
| **In the sources** | BEP §6.1: an **information-management process supported by technology**. "It is not a folder tree" |

**The single most repeated caution in the sources**: reorganising folders does
not change how information is governed, and no capability creates governance by
existing (BEP §6.2).

### WIP

| | |
|---|---|
| **Practical** | Work in progress — under the originating team's control, not for general reliance |
| **In the sources** | BEP §6.3, CDE Strategy §1: information under originator / task-team control, **not authorised for general project reliance**. May hold many versions; WIP versions are not project exchanges, and visibility of WIP is not permission to rely on it |

### Shared

| | |
|---|---|
| **Practical** | Made available beyond the originating team, for an identified purpose, after checking and authorisation |
| **In the sources** | BEP §6.3, CDE Strategy §1. **Shared does not mean published, accepted, or suitable for every purpose** |

### Published

| | |
|---|---|
| **Practical** | Authorised for a defined delivery or use purpose |
| **In the sources** | Used as **"Published / Authorised"** (BEP §6.3, CDE Strategy §1) — authorised for an identified formal or project-facing delivery or use purpose |

Two cautions, both directly sourced:

- **Published does not mean final.** It is authorised for a defined purpose at a
  point in time, and can be superseded or revised (BEP §6.3).
- **Presence in Published does not establish a delivery.** Delivery is an act
  with a recipient and a purpose, not a location (BEP §10.1).

### Archived

| | |
|---|---|
| **Practical** | Retained as historical evidence for traceability |
| **In the sources** | **"Archived" is not a state in the Harrismith model.** The fourth state is **"Record / Retained"** (BEP §6.3, CDE Strategy §1) |

**Two specific cautions.** The sources state that Record / Retained is a
conceptual state and a retention requirement, **not necessarily a folder**; that
**no mandatory CDE root named `04 Archive` is required or approved**, and none is
created; and that the project's **retention approach is TBD**.

If a four-state model is presented using "Archived" as the fourth label, say that
Harrismith uses "Record / Retained" and why the distinction matters.

### Responsibility matrix

| | |
|---|---|
| **Practical** | The written record of who does what to which information |
| **In the sources** | **Two** distinct matrices answering two distinct questions |

| Matrix | Answers |
|---|---|
| Information Management Responsibility Matrix | Who performs which information-management **function** |
| Model / Information Responsibility Matrix | Who produces and maintains which **information container** |

**The approved grammar is Perform, Check, Authorise, Coordinate, Accept,
Consult, Inform** (BEP §5.12). **RACI is expressly not adopted**, and is not to
be introduced unless explicitly approved later — because it collapses checking
from authorising and coordinating from performing.

**No holder is established** for any role in either matrix.

### Information-delivery schedule

| | |
|---|---|
| **Practical** | The plan of what is delivered, by whom, to whom, when and for what purpose |
| **In the sources** | A **controlled training delivery-planning instrument** — explicitly **not a contractual programme** |

**No calendar dates, frequencies or contractual milestones exist.** Entries are
event-triggered or TBD. The three training events are TRN-E01 (design
coordination share), TRN-E02 (conditional reshare) and TRN-E03 (project-facing
exchange, currently **BLOCKED**).

### Coordination

| | |
|---|---|
| **Practical** | Checking that information from different teams actually fits together, and managing what to do when it does not |
| **In the sources** | BEP §8, Coordination Strategy §1: manages **multidisciplinary interfaces**, not geometry alone. **Clash detection is one technique, not the whole process.** Federation creates a coordination artefact — it **does not merge ownership**. **Coordination is not design approval** |

### Review

| | |
|---|---|
| **Practical** | Considering information for a stated purpose |
| **In the sources** | BEP §9.2, exactly: "Consideration of information for a stated purpose" |

Distinguished from **check** — verification against a defined requirement before
progression.

### Approval

| | |
|---|---|
| **Practical** | A decision that something may proceed |
| **In the sources** | Used **only where a defined approval decision is intended** (BEP §9.1). It is **not** a catch-all: check, review, authorise, coordinate, accept and reject each name a different decision, made by a different function, against different criteria — and are not collapsed into "approval" |

**Teaching caution.** "Approval" is the word audiences reach for automatically.
Introduce **authorise** as the more precise term early, and use the sourced
distinction rather than fighting the audience's vocabulary.

### Authorisation

| | |
|---|---|
| **Practical** | Permission for information to move or be relied on — for a stated purpose |
| **In the sources** | BEP §9.2: permit information to progress, share, publish or exchange **for a defined purpose**. **Authorisation is purpose-bound** — never given in general (BEP §5.1) |

Three sourced separations worth teaching together:

- **creation is not authority to share** — producing information does not confer
  authority to share it;
- **authorisation to share is not authorisation to publish or exchange** — those
  are separate decisions with wider consequences (BEP §9.4);
- **authority comes from governance, not from platform access, permission or
  configuration** (BEP §9.1).

### Implementation

| | |
|---|---|
| **Practical** | Actually doing what was agreed — as opposed to having agreed it |
| **In the sources** | BEP §12.3 distinguishes three states: **as-found / observed** (evidence of current reality), **intended governance** (the approved target state) and **implemented state** (the operational state after an approved change) |

Sourced principles: **evidence is not decision**, **proposed is not approved**,
**decision precedes configuration** — platform change follows a governance
decision, not the reverse (BEP §12.1). And BEP §1.2: **development state is not
issue state** — content existing in Git means it has been drafted, not approved
and not issued.

---

## 3. On ISO terminology

**No ISO 19650 wording is reproduced or verified in this repository.**

The Harrismith sources state only that **ISO 19650 principles inform the
information-management approach** — a statement of influence. **No formal
compliance, assessment or certification is claimed**, no standard has been
established as applicable to the project, and no standards text is reproduced
(BEP §11.2, §13.4).

Three consequences for teaching:

1. **Do not present any definition in this glossary as the ISO definition.**
   These are practical teaching definitions and Harrismith source usage.
2. **Two commonly expected terms are absent from the sources** — *lead appointed
   party* and *appointed party*. Harrismith uses *Lead Delivery Party* and names
   party categories directly. Attributing the absent terms to Harrismith would
   be wrong.
3. **One state label differs** — the sources use *Record / Retained*, not
   *Archived*.

Where the strict standard definition matters to an audience, refer them to the
standard itself. Do not paraphrase it here and do not claim it from memory.

---

## 4. Scope

This glossary covers the terms needed for Module 1 and for the foundation
modules that follow. It will grow as modules are developed. Terms specific to a
single module belong in that module's files, not here.
