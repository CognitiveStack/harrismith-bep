# BIM Delivery Guide

*Harrismith Fire Station — BIM management training implementation*

| Field | Value |
|---|---|
| Document status | **FOR REVIEW — Companion to Training Baseline 0.1 Candidate** |
| Nature | **Educational / onboarding guidance** |
| Authority | **None.** This Guide governs nothing |
| Approval | **Not approved.** Inclusion in candidate review confers no governing status |

**If this Guide ever disagrees with a controlled governing resource, the
controlled resource wins.** Tell someone — that is a contribution worth making
(section G9).

---

## G1. About This Guide

### Who this is for

- new project participants;
- anyone learning BIM management;
- Authors and Checkers;
- Task-Team Leads;
- people taking part in BIM coordination;
- people using the CDE and Autodesk tools;
- anyone who needs a practical orientation before reading the full BEP.

You should be able to read this Guide **before** the BEP and afterwards
understand the system well enough to ask good questions.

### What this Guide does

- introduces the concepts;
- explains the terminology;
- gives simple worked examples;
- points you to the authoritative resources.

### What this Guide does not do

It does **not**:

- appoint anyone to anything;
- authorise any information;
- replace the BEP;
- replace project standards;
- approve platform configuration;
- create contractual obligations.

**The Guide teaches the controlled system. It does not create it.** Nothing here
introduces a new responsibility, authority, standard, delivery requirement,
platform setting or project fact. If you find something in this Guide that looks
like a rule you cannot find in a controlled document, treat it as an error and
raise it.

### Where each document sits

```
BIM Delivery Guide                        →  learn
Working Process                           →  contribute
BEP / supporting resources / standards    →  govern
Autodesk Forma and related tools          →  operationalise governed workflows
```

Four different jobs. Confusing them is the most common way a well-intentioned
project loses control of its information.

---

## G2. BIM and Information Management in Plain Language

### BIM is not just a 3D model

A model is part of it. But BIM is a **managed way of producing, sharing,
coordinating and using information** about a building — from design through
construction and into use.

The model is one container of information among many: drawings, schedules,
reports, specifications, records.

### Information management is a set of practical questions

| Question | Why it matters |
|---|---|
| Who needs what information? | Producing information nobody needs wastes effort |
| Who creates it? | Someone must be answerable for its content |
| How do we know it has been checked? | Unchecked information looks identical to checked information |
| Who may share it? | Sharing is a decision, not a side effect of saving a file |
| What may others use it for? | Information fit for one purpose may be unfit for another |
| How are changes tracked? | Without history, you cannot tell what changed or why |
| How do we know which information is current and suitable? | This is the question every project eventually fails on |

### Why BIM management exists

**A project can have excellent models and still be badly managed.**

If nobody knows which model is current, who checked it, what it may be used for,
or who is allowed to issue it, then the technical quality of the modelling does
not save the project. Coordination happens against stale information. Decisions
get made on drawings nobody approved. Two teams work from different versions and
neither knows.

BIM management is what stops that. It is not bureaucracy added to the modelling —
it is the part that makes the modelling usable by other people.

**What this means in practice:** most of what you will read in the BEP is about
*decisions* — who decides that information can move, on what basis, and how
anyone can tell afterwards.

---

## G3. Harrismith BIM Delivery System

### The map

```
BIM Delivery Guide      →  learn the system            (this document)
Working Process         →  ask questions, propose      (working/)
BEP                     →  the governing agreement      (bep/)
Supporting Resources    →  detailed management controls (supporting/)
Project Standards       →  detailed conventions         (standards/)
Autodesk CDE and tools  →  operational implementation
Git                     →  controlled authoring and history for BEP source
```

### Three layers

| Layer | What it covers |
|---|---|
| **1. Governance** | The BEP, the six supporting resources and the project standards — what the rules are and who decides them |
| **2. Information production and coordination** | Authoring, checking, sharing, coordinating, delivering — the daily work |
| **3. Participation and learning** | This Guide and the Working Process — how you understand the system and how you improve it |

### Current status — read this before relying on anything

- This is a **training and reference implementation**.
- The BEP and all six supporting resources are **FOR REVIEW** as the Training
  Baseline 0.1 Candidate. Each declares its own status.
- **BEP Training Baseline 0.1 is not approved.**
- **Gate C passed through GD-001 on 2026-08-01.** Training Baseline 0.1 remains
  **FOR REVIEW — NOT APPROVED**: the approval decision has not yet occurred, and
  publication remains on hold.
- **Live-project validation was completed through Increment 7C** — read-only
  connector observation and supplied manual UI evidence — and the validated
  observations were incorporated through Increment 7D and reviewed through
  Increment 7E. **A complete governed coordination cycle has not been
  demonstrated.**

Several important things are **deliberately unresolved** and are recorded as
such, not quietly filled in. You will meet them in this Guide — publication
authority, acceptance authority, the project standards, and an observed
Design Collaboration mapping discrepancy. Their being open is a feature of an
honest system, not an oversight.

---

## G4. Who Does What?

**A role is not a person.** In an implementation this size, one participant may
hold several roles. What matters is that you know **which role you are acting in
at each decision**.

**No holder is established for any role below.** Everything is TBD, and this
Guide does not appoint anyone.

### Owner / Appointing Party

Defines high-level information needs and outcomes, and may receive and accept
defined information where governance establishes that function.

*Identity remains **TBD**.*

### Lead Delivery Party

Coordinates delivery across the task teams — commitments, dependencies,
project-level readiness.

*Holder remains **TBD**.*

### BIM Manager

> *"Does the BIM-management system make sense, and is it still governed?"*

Looks after the BEP, governance, the standards architecture, the CDE strategy,
information-management responsibilities, change, onboarding and assurance.

**Not automatically** the design approver, the clash fixer, or the publication
authority. The BIM Manager governs *how information is managed* — not the
engineering, and not the contract.

### BIM Coordinator

> *"Are the multidisciplinary information interfaces being coordinated?"*

Organises coordination inputs, manages federation, runs the checks, triages
findings, raises and tracks Issues, monitors resolution, verifies dispositions,
escalates blockers.

**Does not own the discipline design solution.** Spotting a conflict does not
make you the person who decides how to fix it.

### Task-Team Lead

> *"Is my team's information ready and appropriately controlled?"*

Oversees the team's production, ensures required checking happens, leads the
team's technical and interface response, and authorises sharing where governance
allocates that function.

### Author

Creates and changes information, working in WIP.

### Checker

Checks against the defined requirement before information progresses.

**Checking is not authorising.** A check says "this meets the requirement"; it
does not say "this may now move".

### CDE Administration

Implements approved platform configuration — membership, permissions, folders,
spaces, team mappings.

**Permission is not authority.** Being able to do something in the software is
not the same as being allowed to decide it.

### Receiving / recipient function

Receives an exchange and decides whether to accept it for the stated purpose.

*Not established.*

---

## G5. How the CDE Works

### The CDE is not "a folder on Autodesk"

It is the **managed process** by which information changes control and use. The
folders implement part of it. Moving a file into a differently-named folder does
not change how it is governed.

### The four controlled information states

| State | In everyday words |
|---|---|
| **WIP** | *"My team is still working on this."* |
| **Shared** | *"My team has checked this and deliberately made it available for an identified project purpose."* |
| **Published / Authorised** | *"This has been authorised for a defined project-facing use or exchange."* |
| **Record / Retained** | *"We keep this as historical evidence, according to the governed retention approach."* |

**These four are the only controlled information states.**

### Things that are *not* states

You will hear these words constantly. None of them is a CDE state:

| Word | What it actually is |
|---|---|
| **Consume** | A receiving-team **action** — adopting information into your own working context |
| **Coordination input** | A **use and context** for Shared information |
| **Deliver** | An **event** |
| **Receive** | An **event** |
| **Accept** | A **decision and status** for a stated purpose |

**Why this matters:** if you deliver a Published model, its state is still
Published. "Delivered" is something that *happened to it*, recorded alongside it.
An event or a decision does not create a new state.

### Five more words that are not interchangeable

| Term | Meaning |
|---|---|
| **Version** | A file-history instance in the platform |
| **Revision** | A controlled issue identifier, where project convention requires one |
| **State** | WIP / Shared / Published / Retained |
| **Status** | A workflow or decision condition |
| **Suitability** | What the information may actually be used for |

**Saving a new version does not create a new revision, change the state, approve
anything, or make the information suitable for a new purpose.** Each of those is
a separate act.

### Desktop Connector

Convenient filesystem access to cloud-managed information. That is all.

It is **not** another CDE, **not** a local source of truth, and **not** the BEP
Git repository. A file sitting on your machine tells you nothing about its state
or whether you may rely on it.

---

## G6. How Information Moves Through the Project

### The normal production flow

```
requirement
  → author
  → WIP
  → check
  → authorise share
  → Shared
  → review / consume / coordinate
```

| Step | In plain language |
|---|---|
| **requirement** | Somebody needs this information for a reason |
| **author** | Someone produces it |
| **WIP** | It lives under the producing team's control while it is worked on |
| **check** | Someone verifies it against a defined requirement |
| **authorise share** | A specific role decides it may become available to others |
| **Shared** | Other teams can now see it and decide whether to use it |
| **review / consume / coordinate** | Others examine it, adopt it, or coordinate against it |

### Formal delivery, where required

```
Shared
  → delivery review
  → authorise publication / exchange
  → Published / Authorised
  → deliver
  → receive
  → accept for stated purpose
```

### Distinctions to hold on to

| | |
|---|---|
| **Check ≠ Authorise** | Checking confirms it meets the requirement. Authorising permits it to move |
| **Share ≠ Consume** | Sharing makes it available. Consuming is the receiver deciding to use it |
| **Published ≠ Delivered ≠ Received ≠ Accepted** | Four separate things. None of them implies the next |

### A worked example — ARC-01

1. The Architectural task team works on **ARC-01** in **WIP**.
2. It is **checked**.
3. The **Task-Team Lead authorises sharing**.
4. ARC-01 becomes **Shared**.
5. Other participants may now review it, or consume it for the stated purpose.

**What changed:** the state, from WIP to Shared, and with it who may rely on the
information.

**What did not change:** the Architectural task team still owns the content and
remains responsible for it. Nothing has been published, delivered, accepted or
approved.

> ARC-01 is a **training construct** from the Model / Information Responsibility
> Matrix. This example illustrates the workflow; it is not a record of something
> that happened on the live project.

---

## G7. Design Collaboration and Model Coordination

These get confused constantly. They do different jobs.

### Data Management / CDE foundation

Where project information is controlled and managed. The base layer.

### Design Collaboration

Helps design teams:

- work in team spaces;
- share controlled packages of information;
- see what other teams have shared;
- consume that information when appropriate.

**Share ≠ consume.** A package being available is not a package in use. Nobody
consumes information by accident — it is a deliberate act by the receiving team,
and it does not transfer ownership of the content.

### Model Coordination

Helps teams:

- aggregate suitable **Shared** model information;
- visually inspect multidisciplinary interfaces;
- detect clashes;
- coordinate problems;
- understand the combined spatial context.

### Navisworks

A specialist desktop coordination and analysis tool that may complement cloud
coordination.

**It is not a second governance system.** A finding from Navisworks enters the
same governed workflow as any other. The tool you found something with does not
determine how it gets managed.

### Issues

Used for actionable matters that need tracking, assignment, resolution and
verification, where governed.

### One distinction worth learning properly

```
Autodesk team  ≠  organisation  ≠  task team  ≠  discipline
```

An Autodesk collaboration team is a **platform construct**. Being a member of one
gives you no authority of any kind.

**A live example of why this matters.** During discovery, the project's Design
Collaboration teams were observed with the **MEP Consultant team bound to a
Structural-labelled WIP space, and the Structural team bound to an MEP-labelled
space**. That is recorded as **UD-001** and **remains unresolved**.

It has **not** been corrected, and no replacement mapping has been proposed —
because deciding the *intended* mapping is a governance decision that nobody has
taken yet. The observed condition is recorded honestly and left open. That is the
correct behaviour, not a backlog item somebody forgot.

---

## G8. Reviews, Issues, Delivery and Approval

### The decision vocabulary

Use the precise word for the decision you actually mean:

| Word | The question it answers |
|---|---|
| **Check** | *"Does this meet the required checks before it moves on?"* |
| **Review** | *"Am I examining this for a stated purpose?"* |
| **Authorise** | *"May this progress to the next controlled use or state?"* |
| **Coordinate** | *"Do the multidisciplinary interfaces work together?"* |
| **Accept** | *"Does the recipient accept this for the stated purpose?"* |
| **Reject** | *"It is not suitable for this progression or use, and action is needed."* |

**The word "approval" is often used loosely.** In this workflow, use the specific
term that describes the actual decision: **check, review, authorise, coordinate,
accept or reject**. "Approval" is not a substitute for any of them.

### Findings, clashes and Issues

| Term | Meaning |
|---|---|
| **Finding** | Something noticed during coordination that needs triage |
| **Clash** | A geometric or spatial coordination finding |
| **Issue** | A managed action record, created when a matter needs ownership, tracking, decision or verification |

**Not every clash becomes an Issue.** Many findings are duplicates, false
positives, out of scope, already known, or artefacts of how the test was set up.
Creating an Issue is a decision someone takes at triage — not an automatic
consequence of a detection run.

### Delivery

- **Published does not automatically mean Delivered.** Authorised information
  sitting in a published location has not been sent to anyone.
- **Delivered does not automatically mean Accepted.** Sending is not agreeing.

### An honest gap

**Publication and exchange authority is currently unresolved** in this training
implementation. So is **recipient acceptance authority**.

Nobody has been given the authority to publish or to accept, because the delivery
arrangement that would establish it does not exist. This Guide does not solve
that, and neither does the BEP — it is recorded as open (BEP 9.7, 9.8).

**What this means in practice:** the project-facing delivery route currently
stops. See Scenario 5.

---

## G9. How to Participate and Propose Changes

You are not a passive user of this system. If something is unclear, wrong,
missing or unworkable, there is a route for saying so.

### The seven contribution types

| Type | Use it when |
|---|---|
| **QUESTION** | You need an explanation, and no rule may need to change |
| **PROPOSAL** | You want to suggest a new or changed process, standard, responsibility or method |
| **PROBLEM** | You have hit a difficulty, failure, inconsistency or blocker |
| **CLARIFICATION** | An existing rule is ambiguous |
| **IMPROVEMENT** | Something works but could be clearer, quicker or more reliable |
| **TRAINING NEED** | Something needs explaining, demonstrating or practising |
| **EXCEPTION REQUEST** | You need a deliberate departure from an approved rule |

### The flow

```
I notice something
  → Working Register
  → triage
  → discussion / evidence
  → decision if required
  → Governance Register where necessary
  → implementation
  → verification
```

### The rule that makes this work

> **You may contribute freely. You may not directly change authoritative
> governance merely because you disagree with it.**

Contributing is open to everyone. Deciding is not. That asymmetry is the whole
point of having a separate participation layer — it lets the intake route stay
easy without letting the rules change by accident.

### Three records, three jobs

| Record | Holds |
|---|---|
| **Working Register** (`working/bep-working-register.md`) | Your incoming contribution |
| **Project Issue** | The operational coordination or model action |
| **Governance & Decision Register** (`supporting/governance-decision-register.md`) | The authoritative governance decision and its history |

**An entry marked APPROVED in the Working Register does not create approved
governance.** It records that this process reached an approved outcome or route.
The governance decision itself lives in the Governance Register.

### A worked example

Suppose you ask: *"What should the intended MEP / Structural Design Collaboration
team-space mapping be?"*

```
QUESTION raised in the Working Register
  → triaged by the BIM Manager function (this is governance, not admin)
  → status: DECISION REQUIRED
  → hands over to the Governance Register → UD-001
```

You raised a real governance question through an easy route, and it reached the
governance system. **You did not acquire the authority to answer it**, and
UD-001 is still unresolved. That is the system working correctly.

---

## G10. Getting Started — Role-Based Quick Guides

*Orientation, not obligations. The controlled documents define what is required.*

### If you are new to the project

1. Read this Guide.
2. Identify your role and task team.
3. Understand where your information belongs.
4. Learn WIP / Shared / Published — see G5.
5. Know where to ask questions — see G9.
6. **Do not assume access means authority.** Being able to open or edit something
   is not permission to rely on it or to move it.

### If you are an Author

**Before working:**

- identify your container and task team;
- work in **WIP**;
- use approved project resources where they exist — note that the project
  standards do not exist yet;
- understand your known dependencies.

**Before sharing:**

- complete the required checks;
- make limitations and exclusions visible;
- **do not self-authorise.** Having authored something is not a reason to
  advance it — unless governance explicitly allocates that function to you.

### If you are a Checker

- know what the check is *for*;
- check technical/content and information readiness as applicable;
- record material findings;
- **checking does not authorise sharing** — that is a separate decision.

### If you are a Task-Team Lead

- know what your team owns;
- ensure production and readiness;
- ensure the required checking actually happens;
- authorise sharing where that function is allocated to you;
- respond to coordination matters affecting your team;
- **ensure corrections go back through WIP** — never edit shared information in
  place.

### If you are the BIM Coordinator

- identify ready **Shared** inputs;
- federate — without taking ownership of anyone's content;
- run **purpose-based** checks, not everything against everything;
- triage findings;
- raise managed Issues where they are needed;
- monitor resolution;
- verify **after** controlled reshare, not on a claim that it was fixed in WIP;
- escalate what the normal cycle cannot resolve.

### If you are the BIM Manager

- maintain governance coherence;
- manage BEP and supporting-resource governance;
- triage Working Process governance matters;
- manage changes through the governance route;
- support onboarding;
- verify that approved governance changes were actually implemented.

### If you are CDE Administration

- implement approved platform configuration;
- maintain permissions and configuration as instructed;
- verify implementation afterwards;
- **do not infer governance from software permissions.** Configuring something
  does not decide it.

---

## G11. Common BIM Scenarios and Examples

> These use the project's **training constructs** — ARC-01, STR-01, MEC-01,
> COORD-01, TRN-E01 to TRN-E03. They illustrate governed logic. They are not
> records of live project activity.

### Scenario 1 — Sharing architectural information

```
ARC-01:  WIP → check → authorise share → Shared
```

**What changed:** the state, and therefore who may rely on it.

**What did not change:** the Architectural task team still owns and is
responsible for the content. Nothing was published, delivered or approved.

### Scenario 2 — A receiver consumes shared information

The Structural task team reviews Shared **ARC-01** and chooses to consume and
reference it.

- **ARC-01 remains Shared.** Consumption is not a state change.
- **Technical ownership remains with the Architectural task team.**
- The Structural team is responsible for *how it used* the information — both
  responsibilities exist at once.

### Scenario 3 — A mechanical / structural coordination finding

```
STR-01 + MEC-01 shared as coordination inputs   (TRN-E01)
  → coordination
  → finding
  → triage
  → Issue, if required
  → technical resolution in the originating team's WIP
  → check
  → conditional reshare of affected containers only   (TRN-E02)
  → re-coordinate
  → verify
```

**TRN-E02 is conditional.** If only MEC-01 changes, only the mechanical reshare
activates — the structural one does not. A coordination cycle may activate one
container, several, or none.

**The BIM Coordinator does not design the fix.** Each affected task team resolves
its own information in its own WIP.

### Scenario 4 — Not every clash becomes an Issue

```
finding → triage → false positive / no action / accepted coordination condition
        → disposition recorded where material
```

**"Accepted condition" means only that this finding needs no further action for
this check and purpose.** It is not recipient acceptance, and it is not design
approval.

### Scenario 5 — Project-facing delivery is blocked

```
TRN-E03:  Shared → delivery review → [ publication authority TBD ] → STOP
```

The information stops at Shared. It cannot become Published, because no role has
been given publication authority.

**This is the system working, not failing.** Good governance deliberately stops a
process when the authority to proceed does not exist. The alternative — letting
whoever is nearest sign it off — is how projects acquire approvals nobody
actually granted.

### Scenario 6 — A participant wants to change the workflow

```
proposal → Working Register → triage → governance decision
         → implementation → verification
```

The participant does **not** edit the BEP directly. The proposal may eventually
cause a BEP change; it is not itself that change.

### Scenario 7 — Software access does not create authority

Someone has write permission to a folder or space. That does **not** mean they
may:

- authorise sharing;
- publish;
- approve a design;
- accept a delivery.

**Permission is technical capability. Authority comes from governance.** They are
granted by different means, for different reasons, and one never implies the
other.

---

## G12. Glossary and Further Learning

### Glossary

| Term | Meaning |
|---|---|
| **BEP** | BIM Execution Plan — the governing agreement on how project information is managed |
| **BIM** | A managed way of producing, sharing, coordinating and using information about a built asset |
| **Information Management** | Governing who produces information, who checks it, who may share it, and what it may be used for |
| **CDE** | Common Data Environment — the managed *process* by which information changes control and use |
| **WIP** | Work in progress. Under the originating team's control; not for general reliance |
| **Shared** | Made available beyond the originating team for an identified purpose, after check and authorisation |
| **Published / Authorised** | Authorised for a defined project-facing delivery or use purpose |
| **Record / Retained** | Retained as historical evidence for traceability |
| **Information Container** | An identifiable set of information — a model, drawing, schedule, report or record |
| **Task Team** | The group producing a defined package of information |
| **Discipline** | A technical classification of information — ARC, STR, MEC, ELE, PLM, FIR |
| **Design Collaboration** | Autodesk capability supporting team spaces and controlled sharing between design teams |
| **Model Coordination** | Autodesk capability supporting aggregation, clash detection and interface coordination |
| **Federation** | Temporary controlled aggregation of separate discipline information for coordination. Does not merge authorship |
| **Clash** | A geometric or spatial coordination finding |
| **Finding** | Something noticed during coordination that requires triage |
| **Issue** | A managed action record, created when a matter needs ownership, tracking, decision or verification |
| **Check** | Verification against a defined requirement before progression |
| **Review** | Consideration of information for a stated purpose |
| **Authorise** | Permit information to progress, for a defined purpose |
| **Accept** | A recipient's decision that information is suitable for the stated purpose |
| **Suitability** | What the information may actually be used for |
| **Version** | A platform or file-history instance |
| **Revision** | A controlled issue identifier, where project convention requires one |
| **Delivery** | Sending identified information to an identified recipient for an identified purpose |
| **Working Process** | The route by which participants contribute questions, proposals and problems |
| **Governance & Decision Register** | The authoritative record of governance decisions, assumptions and unresolved matters |

Definitions here are simplified for learning. **The controlled documents are
authoritative** — this glossary is not a substitute BEP.

### Where to read more

Inside this repository:

| Resource | Path |
|---|---|
| BIM Execution Plan | `bep/Harrismith-Fire-Station-BEP.md` |
| Information Management Responsibility Matrix | `supporting/information-management-responsibility-matrix.md` |
| Model / Information Responsibility Matrix | `supporting/model-information-responsibility-matrix.md` |
| Information Delivery Schedule | `supporting/information-delivery-schedule.md` |
| CDE Workflow & State Strategy | `supporting/cde-workflow-state-strategy.md` |
| Coordination & Review Strategy | `supporting/coordination-review-strategy.md` |
| Governance & Decision Register | `supporting/governance-decision-register.md` |
| Working Process | `working/README.md` |
| Working Register | `working/bep-working-register.md` |
| Project standards | `standards/` — **not yet established** |

Each of those is separately controlled and declares its own status. Being
referenced here does not make any of them approved.

### External standards

**ISO 19650** principles inform the information-management approach used here —
the state model, the separation of originator and recipient, and the emphasis on
purposeful exchange all come from that thinking.

That is a statement about influence, and nothing more. **No compliance,
assessment or certification is claimed.** No standard has been established as
contractually applicable to this project, and no standards text is reproduced in
this repository.

---

## A closing note

Much of this Guide is about things that are *not* the same as each other: check
and authorise, share and consume, published and accepted, permission and
authority.

That is deliberate. Almost every information-management failure on a project is
one of those pairs being quietly treated as one thing. If you finish this Guide
holding those distinctions, you have the important part.

The rest — where the folders are, which button does what — you will pick up as
you go.
