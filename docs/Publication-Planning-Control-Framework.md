# Publication Planning — Control Framework

| Field | Value |
|---|---|
| Document status | **Controlled Planning Framework** |
| Authority | **None** — control framework only |
| Approval | **Not approved** |
| Phase | Phase 8 — Publication Planning |
| Increment | 8A — Publication Planning Control Framework |
| Date | 2026-08-01 |
| Baseline context | Training Baseline 0.1 — **APPROVED WITH CONDITIONS** (**AD-001**, 2026-08-01) |

> **PUBLICATION REMAINS NOT AUTHORISED — PUBLICATION HOLD ACTIVE.**

**This framework carries no governance authority.** It defines *what Publication
Planning must decide and what evidence those decisions will require*. It decides
none of them, proposes no publication arrangement, and binds nothing.

---

## 1. Purpose and boundary

### 1.1 Purpose

This artefact establishes the **Publication Planning control framework** for
Phase 8. Its purpose is to make the shape of the work visible before any of it
is done, so that:

- the matters left undefined by **GCR-005** are addressed deliberately rather
  than absorbed by assumption;
- each future decision is taken by an identified function, on identified
  evidence, and recorded as a distinct governance output;
- the separate events between planning and acceptance are not collapsed into a
  single act of uploading a file.

### 1.2 What this artefact does not do

This artefact does **not**:

- approve a publication arrangement;
- authorise a publication event;
- execute an upload, publication, issue or distribution;
- nominate a publication location, folder, owner, format or metadata schema;
- write an operational upload procedure;
- establish delivery, receipt or acceptance;
- assign project publication / exchange authority;
- assign recipient acceptance authority;
- close **GCR-005**;
- close **GCR-006**;
- resolve, reinterpret or suppress **UD-001**;
- establish any project standard;
- alter **GD-001** or **AD-001**, or any part of their recorded outcome;
- create a tag, release or publication package.

### 1.3 Classification

This framework is **not APPROVED GOVERNANCE** and **not PROPOSED GOVERNANCE**.
It proposes no rule for the project to follow. It is a planning control
structure: an agenda of decisions, their evidence requirements, and their
boundaries.

**If any part of this framework is later to become governing, that requires a
separate, explicit decision** taken by an identified function through the
approved decision route. Reference to this document by a later artefact does not
approve it (README §7).

### 1.4 Relationship to the approved baseline

The approved baseline already contains the controlled workflow model — the
**T1–T8 transition control table** in
`supporting/cde-workflow-state-strategy.md` §3, and the blocked TRN-E03 route in
§11 of the same document.

**This framework does not amend, replace or reinterpret that model.** Where it
subdivides an existing transition, it does so **for planning purposes only**.
Any actual change to the approved T-model requires change control, not
incremental editing (BEP 12.11; README §7).

---

## 2. Separate governance events

Publication is not one action. The following are **separate events**, each with
its own trigger, its own deciding or performing function, its own evidence, and
its own record.

**No event implies the next.** Reaching one is not authority to reach the one
after it.

### 2.1 The event sequence

| Ref | Event | Nature | Existing model reference |
|---|---|---|---|
| **PE-1** | **Planning** a publication arrangement | Preparatory work — produces options and evidence, decides nothing | — (this framework) |
| **PE-2** | **Approving** the publication arrangement | A decision that a described arrangement is the governed arrangement | — |
| **PE-3** | **Authorising** a particular publication event | A decision that a specific identified content set may be published, at a specific time, for a stated purpose | Decision element of **T4** |
| **PE-4** | **Executing** the publication | A performed act — the upload / transition itself | Execution element of **T4** |
| **PE-5** | **Verifying** the published result | A check that what was executed is what was authorised | Evidence requirement of **T4** |
| **PE-6** | **Delivering** the information | An exchange **event** | **T5** |
| **PE-7** | **Receiving** the information | A recipient **event** | **T6** |
| **PE-8** | **Accepting** the information | A recipient **decision and status** against a stated purpose | **T7** |
| **PE-S** | **Superseding or withdrawing** previously published information | A later, separate controlled act against information already published | **T8** |

### 2.2 Why the separation is load-bearing

| Distinction | What collapsing it would falsely imply |
|---|---|
| **PE-1 is not PE-2** | That describing an arrangement makes it the governed arrangement |
| **PE-2 is not PE-3** | That an approved arrangement authorises every publication under it, without a specific decision |
| **PE-3 is not PE-4** | That authorising publication is the same as having published |
| **PE-4 is not PE-5** | That executing an upload proves the correct content arrived intact and identified |
| **PE-5 is not PE-6** | That verified published information has been delivered to anyone |
| **PE-6 is not PE-7** | That sending is receiving. **Non-receipt is not deemed receipt** |
| **PE-7 is not PE-8** | That receipt is acceptance. **Silence is not acceptance** |
| **PE-S is not PE-3/PE-4** | That withdrawal or supersession is a side effect of a new publication, rather than a controlled act with its own authority and record |

Three further constraints carried from the approved baseline:

- **PE-6, PE-7 and PE-8 create no information state.** Delivery and receipt are
  events; acceptance is a status against a stated purpose. Information that has
  been delivered, received and accepted remains **Published / Authorised**
  (CDE Workflow & State Strategy §3.1, notes to T5–T7).
- **PE-8 is not technical approval and transfers no technical responsibility**
  from the originating task team (BEP 9.8).
- **PE-S retains history.** Superseded exchanges are marked superseded, **not
  deleted** (BEP 7.10, 9.9, 12.10).

### 2.3 Current position in the sequence

| Ref | Current status |
|---|---|
| PE-1 | **Beginning** — this framework opens it; no arrangement planned yet |
| PE-2 to PE-8, PE-S | **Not reached. Not authorised. Not evidenced.** |

**Nothing in this repository has been published, issued, delivered, received or
accepted.**

---

## 3. GCR-005 decision map

**GCR-005 is an open pre-publication condition** (GD-001 §6; AD-001 §6,
Condition 2). It requires the controlled determination of seven matters, none of
which is defined.

> **This section does not answer any of them.** It records, at framework level,
> what each matter must eventually decide, what evidence that decision will
> require, what governance output it is likely to produce, and whether
> repository evidence alone is expected to be sufficient.

**Wording note.** GD-001 §6 and AD-001 §6 state the same seven matters in
slightly different words — *"approved publication location / training
publication owner / output format / version and status metadata / controlled
upload procedure"* against *"publication location / publication owner /
publication format / required metadata / upload procedure"*. The two are read as
the same seven matters. The AD-001 phrasing is used below as the more recent
statement. **No matter is added, removed or reinterpreted by this reading.**

### 3.1 What must eventually be decided, and on what evidence

| Ref | GCR-005 matter | What must eventually be decided | Evidence required |
|---|---|---|---|
| **PM-1** | **Publication location** | Which governed destination holds published information, and on what basis it is *the* governed destination rather than merely an available one | Governance statement of intended destination; live read-only observation of what candidate destinations exist and how they behave |
| **PM-2** | **Publication owner** | Which **function** owns the publication act, and under what authority that function exists | An authority decision. **Not** an access list, a permissions report or a membership list |
| **PM-3** | **Publication format** | What artefact form is published from the authoring source, and how it is generated from it | Repository capability evidence; format constraints observable in the destination; the BEP §13.5 generated-artefact route |
| **PM-4** | **Publication metadata** | What identity, version and status metadata a published artefact must carry, and how each field is populated and checked | Governance requirement for identity and status; live read-only observation of which fields are technically available and enforceable |
| **PM-5** | **Upload procedure** | The controlled sequence of steps by which an authorised publication is executed, including its pre-conditions and its stop conditions | Procedure drafted against confirmed platform behaviour; **manual controlled publication only** (BEP §13.5) |
| **PM-6** | **Post-upload verification** | How it is confirmed that the published result is the authorised content, correctly identified — and what happens when it is not | Verification method; live read-only observation of what version and integrity information is actually observable after upload |
| **PM-7** | **Supersession / withdrawal route** | How previously published information is superseded or withdrawn, by whom, with what record, and with what retention of history | Governance rule; live read-only observation of what the platform supports and what it prevents |

### 3.2 Likely governance output and evidence sufficiency

| Ref | Likely governance record or decision output | Repository evidence sufficient? |
|---|---|---|
| **PM-1** | An arrangement decision identifying the governed location and its basis | **No** — repository evidence cannot establish what exists in the live CDE. Read-only live observation expected to be required |
| **PM-2** | An **authority decision** establishing a publication / exchange function, analogous in form to AG-001 but **not derived from it** | **Yes** — authority is established by decision, not by observation. Live observation is **irrelevant** to this matter and must not be used as a substitute |
| **PM-3** | An arrangement decision recording the published format and its generation route | **Partly** — repository side is sufficient; destination-side constraints may require observation |
| **PM-4** | A metadata requirement recorded as part of the arrangement decision | **No** — which fields are technically available is a live-system fact |
| **PM-5** | A controlled procedure, approved separately from the arrangement | **No** — a procedure written without confirmed platform behaviour would be speculation presented as method |
| **PM-6** | A verification method and its acceptance / failure criteria | **No** — what is observable after upload is a live-system fact |
| **PM-7** | A supersession / withdrawal rule, and its authority | **No** — platform capability and limitation must be confirmed |

**Two standing cautions on this map:**

- **PM-2 is not resolved by any amount of observation.** Every other matter has
  a live-system component; this one does not. Observing who *can* publish
  establishes only permission (§4).
- **Sequence matters.** PM-5 and PM-6 depend on PM-1 to PM-4. Drafting a
  procedure before the location, owner, format and metadata are decided would
  fix those matters by implication rather than by decision.

---

## 4. Authority boundaries

The following are recorded as **unchanged and unresolved** by this framework.

| Authority | Status |
|---|---|
| Project publication / exchange authority | **UNRESOLVED** (BEP 9.7; AD-001 §6, Condition 5) |
| Recipient acceptance authority | **UNRESOLVED** (BEP 9.8, 10.11; AD-001 §6, Condition 5) |

**No person and no functional holder is nominated for either authority by this
framework.** Neither may be assigned as a side effect of Publication Planning.

### 4.1 What does not create authority

None of the following establishes publication authority or acceptance
authority, individually or in combination:

| Not authority | Why |
|---|---|
| **Technical permission** | Being able to perform an action in the software says nothing about who was authorised to decide it |
| **Administrative access** | Platform administration is a system capability, not a governance appointment |
| **Project membership** | Membership records participation in a system, not authority over an exchange |
| **A platform team** | A team is not an organisation, task team, discipline or appointment |
| **A training role** | Training functions operate under **TA-02** — simulated role participation — and are not real project appointments |
| **Ownership of this reference implementation** | Owning the training implementation is not project publication authority |
| **Holding the Training Baseline Approver function** | **AG-001 §9** — holding the approval function confers none of the other authorities |
| **Existing observed publication activity** | Information already present in a Published area evidences platform activity, not governed authority (Increment 7C §6A, §9) |

### 4.2 Acceptance cannot be inferred

**Recipient acceptance may not be inferred from** access, availability,
transmission, receipt, viewing, download, silence, elapsed time, or any system
status.

Acceptance is a **recipient decision against a stated purpose**, and it exists
only where that decision is recorded (CDE Workflow & State Strategy §3.1, T7;
BEP 9.8). Increment 7C observed a Transmittal with **0 of 1 recipients viewed**
and **no completed acceptance evidenced**; that remains the position.

### 4.3 Effect on T4

Transition **T4** currently has **no available authorising function**, and
information remains **Shared** (CDE Workflow & State Strategy §3.3, §11).

**This framework does not unblock T4.** It records what would have to be decided
before T4 could ever have an authorising function — which is not the same thing
as providing one.

---

## 5. Evidence classes

Publication Planning will accumulate evidence of different kinds. They are not
interchangeable, and each answers a different question.

| Ref | Evidence class | What it can establish | What it cannot establish |
|---|---|---|---|
| **EC-1** | **Repository governance evidence** — controlled documents, registers, this framework | What the governance system states and intends | That anything was decided by an authorised function, or that any of it was implemented |
| **EC-2** | **Approval / decision evidence** — a recorded decision by an identified function under a stated authority | That a decision was taken, by whom, on what basis, and with what conditions | That the decision was implemented, or that implementation was correct |
| **EC-3** | **Live-system observational evidence** — read-only observation of Forma / ACC | What is **visibly present or absent** in the live environment at the time of observation | What is intended, governed, authorised, or true beyond what was observed |
| **EC-4** | **Implementation evidence** — records of a performed act | That an act was performed | That it was authorised, or that its result is correct |
| **EC-5** | **Post-publication verification evidence** — checks against the authorised content | That the published result matches what was authorised, as far as the check reaches | That the information was delivered, received or accepted |
| **EC-6** | **Delivery evidence** — a transmission record | That an exchange was executed — what, when, by which function, to whom, for what purpose | That it arrived, or that anyone acted on it |
| **EC-7** | **Receipt evidence** — a registered receipt | That an exchange arrived | Acceptance. **Non-receipt is not deemed acceptance** |
| **EC-8** | **Acceptance evidence** — a recorded recipient decision against a stated purpose | That the recipient accepted or rejected for that purpose | Technical approval, or transfer of technical responsibility from the originator |

### 5.1 The standing evidence rule

> **Evidence is not decision, implementation or verification.**

Evidence of any class becomes governance only where the **governed event** and
the **authority under which it occurred** are separately recorded. A document,
a screenshot, a log entry or an observed system state is an input to a decision
— never the decision itself, and never proof that a decision was taken
(BEP 9.11, 12.3, 12.9, 12.10).

**This applies in both directions.** Absence of evidence in any class is not
evidence that the underlying thing does not exist.

### 5.2 EC-9 — Authority or appointment evidence

> **Controlled extension — added 2026-08-01 by Increment 8B-A.** **EC-9 was not
> part of the original Increment 8A text.** The class table in §5 above recorded
> **EC-1 to EC-8** and is retained unchanged: no class is rewritten, renumbered
> or withdrawn. EC-9 is **added to** that set, having been introduced by the
> Increment 8B register and aligned back into this framework here.

**Why it was separated.** §5 folded authority into **EC-2**. **PM-2 —
publication owner — turns entirely on authority**, and §4.1 lists eight
observable things that are **not** authority. Tracking authority evidence as its
own class keeps that distinction visible rather than implicit.

| Ref | Evidence class | What it can establish | What it cannot establish |
|---|---|---|---|
| **EC-9** | **Authority or appointment evidence** — see definition below | **That a function exists, what its limits are, and who may exercise it** | That the holder exercised it correctly; that any **other** authority follows from it |

**Definition.** EC-9 is evidence contained in, or supported by, a **separately
controlled** record of one of the following kinds:

- an appointment record;
- an authority decision;
- a delegation;
- an approved governance instrument;
- or an equivalent formal record establishing a **functional authority and its
  limits**.

#### 5.2.1 What EC-9 is not

**EC-9 is not live-system observational evidence.** It is not **EC-3**, and
**EC-3 can never be reclassified as EC-9**.

**EC-9 cannot be inferred from** any of the following, individually or in
combination:

| Not EC-9 | |
|---|---|
| Technical permissions | Administrative access |
| Project membership | Team membership |
| Folder ownership | Upload activity |
| Previous publication activity | Previous Transmittal activity |

**Permission is not authority.** Being able to perform an action in the software
says nothing about who was authorised to decide it (§4.1).

#### 5.2.2 Defining a class assigns nothing

> **EC-9 cannot itself assign authority merely by being defined as an evidence
> class.**

**Evidence of authority is not the creation or approval of authority.** A class
that can hold such evidence is not a source of it, and naming the class creates
no record to put in it.

Accordingly, and unchanged by this extension:

| Matter | Status |
|---|---|
| Project publication / exchange authority | **UNRESOLVED** |
| Recipient acceptance authority | **UNRESOLVED** |
| Functional holder appointed by this increment | **None** |
| EC-9 evidence currently recorded | **None** |

**No functional holder is appointed, nominated or identified by Increment 8B-A.**

#### 5.2.3 Where EC-9 evidence is recorded

EC-9 evidence entries are recorded in the controlled register established by
Increment 8B —
[`docs/Publication-Planning-Evidence-and-Observation-Control-Register.md`](Publication-Planning-Evidence-and-Observation-Control-Register.md)
§8 and §9 — under the `PPER-` schema, and nowhere else.

**A decision establishing an authority is recorded in
`supporting/governance-decision-register.md`** through the approved decision
route. The register then holds a reference to it, never a copy (Increment 8B
§2.2).

---

## 6. Future Claude Desktop observation boundary

Several matters in §3 cannot be closed from repository evidence alone. A future
increment **may** define limited read-only live observation to inform them.

> **No observation is requested, defined or authorised by this framework.** No
> Autodesk system was accessed in producing it.

### 6.1 Status of this section

This section defines **categories only**. It is **not** a question set and
**not** a Claude Desktop prompt.

The repository has **no established question register**. Until an increment
establishes one, or another controlled location for provisional questions, no
specific live questions are written here. **Every category below is provisional
and may be narrowed, expanded or discarded** when the questions are actually
drafted.

### 6.2 Candidate categories of read-only observation

| Ref | Category | Relates to |
|---|---|---|
| **OC-A** | What candidate destination structures are **visibly present** in the live environment | PM-1 |
| **OC-B** | What identity, version and status **metadata fields are technically visible** and populatable | PM-4 |
| **OC-C** | What **version, integrity and upload-verification information** the available read-only tools can observe after an upload performed by others | PM-6 |
| **OC-D** | What **technical capabilities and limitations** the platform and connector expose — including what they prevent | PM-3, PM-5, PM-7 |

**PM-2 is deliberately absent from this list.** Publication authority is
established by decision, and no observation can supply it (§4).

### 6.3 Standing limits on any future observation

| Limit | Statement |
|---|---|
| **Read-only** | No creation, modification, deletion, upload, move, rename, issue, review, transmittal or configuration change |
| **Observed state is not intended governance** | What the live project does is evidence, not a rule |
| **A visible folder is not the governed publication location** | A folder named after a state is evidence of naming, not of governance (Increment 7C §4) |
| **Permissions do not establish authority** | See §4.1 |
| **Absence of observation is not observation of absence** | Not seeing something is not evidence that it does not exist |
| **Observation is not a decision** | Observation produces **EC-3** evidence and nothing more |
| **The 7C session is an archive** | The completed Increment 7C session is preserved as an evidence archive; no approval or publication work continues in it |

---

## 7. Open matters and non-closure

Completion of Increment 8A changes the status of nothing below.

| Matter | Status before 8A | Status after 8A |
|---|---|---|
| Publication | **NOT AUTHORISED** | **NOT AUTHORISED — unchanged** |
| Publication hold | Active | **Active — unchanged** |
| **GCR-005** | Open | **Open — unchanged** |
| **GCR-006** | Open | **Open — unchanged** |
| **UD-001** | OBSERVED discrepancy + UNRESOLVED DECISION | **Unresolved — unchanged** |
| Publication / exchange authority | Unresolved | **Unresolved — unchanged** |
| Recipient acceptance authority | Unresolved | **Unresolved — unchanged** |
| Naming standard | Not established | **Not established — unchanged** |
| Coordinates standard | Not established | **Not established — unchanged** |
| Titleblocks standard | Not established | **Not established — unchanged** |
| Templates / Authoring Resources | Not established | **Not established — unchanged** |
| Training Baseline 0.1 | **APPROVED WITH CONDITIONS** (AD-001) | **APPROVED WITH CONDITIONS — unchanged** |
| Tags / releases | None | **None — unchanged** |

Stated expressly, completion of Increment 8A does **not**:

- close **GCR-005**, or define any of its seven matters;
- close **GCR-006** — no governed coordination cycle has been exercised or
  evidenced, and this framework exercises none;
- resolve **UD-001**;
- establish any project standard;
- authorise publication;
- authorise any external information exchange;
- create a release or a published repository version;
- reopen, replace or vary **GD-001** or **AD-001**.

### 7.1 GCR-006 remains distinct

**GCR-005 and GCR-006 are separate conditions.** Progress on Publication
Planning is not progress on the governed coordination cycle, and neither
condition may be closed on the strength of work done against the other.

---

## 8. Framework statement

> **This artefact establishes the Publication Planning control framework and
> nothing else.**
>
> It selects no publication arrangement, assigns no authority, authorises no
> event, and closes no condition.
>
> ## **PUBLICATION REMAINS NOT AUTHORISED — PUBLICATION HOLD ACTIVE.**
