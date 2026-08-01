# Publication Planning — Evidence and Observation Control Register

| Field | Value |
|---|---|
| Document status | **Controlled Planning and Evidence Register** |
| Authority | **None** — evidence and question control only |
| Approval | **Not approved** |
| Phase | Phase 8 — Publication Planning |
| Increment | 8B — Publication Planning Evidence and Observation Control Register |
| Date | 2026-08-01 |
| Control framework | [`docs/Publication-Planning-Control-Framework.md`](Publication-Planning-Control-Framework.md) (Increment 8A) |
| Baseline context | Training Baseline 0.1 — **APPROVED WITH CONDITIONS** (**AD-001**, 2026-08-01) |

> **PUBLICATION REMAINS NOT AUTHORISED — PUBLICATION HOLD ACTIVE.**

**This register carries no governance authority.** It records what evidence each
Publication Planning matter will require, what evidence already exists, and what
questions might later be asked of the live environment. **It records no
decision**, selects no publication arrangement, and assigns no authority.

---

## 1. Purpose and non-effect

### 1.1 Purpose

This register provides controlled traceability across nine linked things:

1. the seven **GCR-005** publication matters;
2. the evidence each matter requires;
3. repository evidence already available;
4. potential future read-only live-system evidence;
5. governance or authority inputs that **no observation can replace**;
6. exact observation questions, to be developed in a later increment;
7. observations eventually received;
8. assessment of that evidence;
9. later decision outputs, held as **references** to decisions recorded
   elsewhere.

### 1.2 Non-effect

This register does **not**:

- approve a publication arrangement;
- authorise publication, or any observation;
- assign publication / exchange or recipient acceptance authority;
- execute or verify a publication;
- establish delivery, receipt or acceptance;
- select a location, owner, format, metadata set, procedure, verification method
  or supersession route;
- close **GCR-005**;
- close **GCR-006**;
- resolve **UD-001**;
- establish any project standard;
- create, vary or supersede any decision;
- create a tag, release or publication package.

### 1.3 Classification

Consistent with the Increment 8A framework §1.3, this register is **not APPROVED
GOVERNANCE** and **not PROPOSED GOVERNANCE**. It proposes no rule for the
project to follow. It is a **planning and evidence control record**.

It is also **not** a publication decision, a publication-authorisation record,
implementation evidence, post-upload verification evidence, delivery evidence,
receipt evidence or recipient acceptance evidence.

---

## 2. Relationship to existing controlled records

### 2.1 Why this is a separate artefact

**BEP 12.13 requires one governance register only**, on the stated ground that
*"a decision recorded in two places is a decision that will eventually exist in
two different versions."*

**This register does not compete with `supporting/governance-decision-register.md`
and does not duplicate it**, for three reasons:

| # | Reason |
|---|---|
| 1 | **It records no decisions.** It records evidence requirements, evidence and questions. Decisions are outside its scope entirely — see §2.2 |
| 2 | **Its authority differs.** The Governance & Decision Register is **APPROVED WITH CONDITIONS** as document 7 of Training Baseline 0.1 (AD-001 §4). This register carries **no authority** and is not part of any approved baseline |
| 3 | **Its purpose differs.** The Governance & Decision Register holds discrete governance matters whose status and history must be traceable. This register holds Phase 8 planning inputs that are not yet, and may never become, governance matters |

**The approved register was therefore not extended.** Adding Phase 8 planning
material to an approved baseline document would be a change to approved baseline
content requiring change control, not incremental editing (AD-001 §13;
BEP 12.11).

### 2.2 The non-duplication rule

> **No decision is recorded in this register.**

Where Publication Planning eventually produces a decision, that decision is
recorded in **`supporting/governance-decision-register.md`** under its own
identifier, through the approved decision route. This register then holds a
**reference** to it — never a copy of it, and never a restatement of its terms
(BEP 13.1).

**Where this register and any controlled record appear to disagree, the
controlled record governs and the conflict is reported, not silently
reconciled** (README §7).

### 2.3 Relationship to Increment 8A

The Increment 8A framework is the authoritative source for the **PM-1…PM-7**
matter identifiers, the **PE-1…PE-8 / PE-S** event separation, the **EC-1…EC-8**
evidence classes and the **OC-A…OC-D** observation categories.

**This register carries those forward unchanged.** It does not amend, replace or
reinterpret the framework. One additive extension is made — **EC-9** (§8) — which
alters no existing class and is declared as an extension rather than a revision.

---

## 3. Identifier control

### 3.1 Identifiers reused, not redefined

| Family | Meaning | Owner |
|---|---|---|
| **PM-1…PM-7** | The seven GCR-005 publication matters | Increment 8A §3 |
| **OC-A…OC-D** | Candidate read-only observation categories | Increment 8A §6.2 |
| **EC-1…EC-8** | Evidence classes | Increment 8A §5 |
| **PE-1…PE-8, PE-S** | Separate governance events | Increment 8A §2.1 |

### 3.2 Identifiers introduced by this register

| Family | Form | Meaning | Allocation rule |
|---|---|---|---|
| **PPER-nnn** | `PPER-001`, `PPER-002`, … | A Publication Planning **evidence entry** | Allocated when an evidence entry is first recorded. Sequential, never reused, never renumbered |
| **PPQ-nnn** | `PPQ-001`, `PPQ-002`, … | A Publication Planning **observation question** | **Allocated only when a question is first drafted.** No identifier is reserved for an unwritten question |
| **EC-9** | — | Evidence class extension (§8) | Single additive class; no further EC extension is made here |

### 3.3 Collision check

The repository was swept for existing identifier families before these were
chosen. In use: `AD-`, `AG-`, `GD-`, `GC-`, `GCR-`, `TA-`, `OF-`, `UD-`, `CI-`,
`IM-`, `WP-`, `PM-`, `PE-`, `EC-`, `OC-`, `TRN-E`, and the container identifiers
`ARC-`, `STR-`, `MEC-`, `ELE-`, `PLM-`, `FIR-`, `COORD-`.

**`PPER-` and `PPQ-` were unused and do not collide with any of them.**

### 3.4 No decision identifier

**No decision identifier is allocated by this increment.** `PPER-` and `PPQ-`
are evidence and question identifiers only. They confer nothing, decide nothing,
and must never be cited as though they were decisions.

---

## 4. Controlled status vocabularies

Three vocabularies, deliberately kept apart. **A status from one may never be
used in place of a status from another.**

### 4.1 Evidence-requirement status

| Status | Meaning |
|---|---|
| **IDENTIFIED** | The evidence requirement is known and recorded. Nothing has been gathered |
| **NOT YET SOUGHT** | No attempt to obtain it has been made or authorised |
| **AVAILABLE IN REPOSITORY** | Existing controlled repository material is expected to satisfy it |
| **LIVE OBSERVATION MAY BE REQUIRED** | Repository material is not expected to suffice; read-only observation may inform it |
| **GOVERNANCE DECISION REQUIRED** | **No evidence of any class can satisfy it.** It requires a decision |
| **NOT OBSERVABLE** | The available read-only tooling cannot produce it |
| **OBTAINED** | Evidence has been recorded as a `PPER-` entry. **Not yet assessed** |
| **ASSESSED** | Obtained evidence has been evaluated against the matter it was gathered for |
| **INSUFFICIENT** | Assessed and found not to support the matter. The requirement remains open |
| **SUPERSEDED / NO LONGER REQUIRED** | The requirement was replaced or removed. History retained, never deleted |

**OBTAINED does not become ASSESSED by the passage of time.** Assessment is a
performed act, recorded in a later controlled increment.

### 4.2 Observation-question status

| Status | Meaning |
|---|---|
| **NOT DRAFTED** | No question text exists. **The position for every category after Increment 8B** |
| **DRAFT** | Question text exists in the repository and is not yet reviewed |
| **READY FOR GOVERNANCE REVIEW** | Drafted and put forward for review. **Not authorised** |
| **AUTHORISED FOR READ-ONLY OBSERVATION** | A recorded authorisation permits the question to be asked, read-only |
| **ASKED** | Put to a live-observation session under that authorisation |
| **ANSWERED** | A factual answer was returned and recorded as a `PPER-` entry |
| **PARTIALLY ANSWERED** | Some requested fact returned; the remainder did not |
| **NOT OBSERVABLE WITH AVAILABLE TOOLING** | Asked, and the tooling could not produce the fact. **This is not evidence that the fact is untrue or absent** |
| **WITHDRAWN / SUPERSEDED** | No longer to be asked, or replaced by another question. History retained |

**No status beyond NOT DRAFTED is recorded by Increment 8B.**

### 4.3 Decision status

Kept separate from evidence status, because evidence accumulating is not a
decision approaching.

| Status | Meaning |
|---|---|
| **UNRESOLVED** | The matter has no decision and no candidate arrangement |
| **CANDIDATE ARRANGEMENT NOT YET PREPARED** | No arrangement has been described for consideration |
| **CANDIDATE ARRANGEMENT PREPARED — NOT APPROVED** | An arrangement has been described. **It governs nothing** |
| **DECISION NOT YET TAKEN** | Prepared and put forward; no decision record exists |
| **DECISION TAKEN — see decision record** | **Usable only where a separately identified decision record exists** in `supporting/governance-decision-register.md`. Never asserted from this register alone |

### 4.4 The separation rule

> **Evidence status never implies decision status.**

A matter may hold complete, assessed evidence and remain **UNRESOLVED**.
Evidence informs a decision; it does not take one, and it never takes one
implicitly (Increment 8A §5.1; BEP 9.11, 12.3).

---

## 5. GCR-005 matter register

**Authoritative source of the seven matters:** condition **GCR-005**, arising
from the Increment 7F readiness assessment, carried at **GD-001 §6** and
restated at **AD-001 §6, Condition 2**. Matter identifiers **PM-1…PM-7** are
from Increment 8A §3.

> **No matter below is answered here.** Each records what must eventually be
> decided and what evidence that will require.

Presented as four aligned tables keyed by matter reference.

### 5.1 Matter, source and decision status

| Ref | Matter | What must eventually be decided | Decision status |
|---|---|---|---|
| **PM-1** | Publication location | Which governed destination holds published information, and on what basis it is *the* governed destination rather than merely an available one | **UNRESOLVED** — candidate arrangement not yet prepared |
| **PM-2** | Publication owner | Which **function** owns the publication act, and under what authority that function exists | **UNRESOLVED** — candidate arrangement not yet prepared |
| **PM-3** | Publication format | What artefact form is published from the authoring source, and how it is generated from it | **UNRESOLVED** — candidate arrangement not yet prepared |
| **PM-4** | Publication metadata | What identity, version and status metadata a published artefact must carry, and how each field is populated and checked | **UNRESOLVED** — candidate arrangement not yet prepared |
| **PM-5** | Upload procedure | The controlled sequence by which an authorised publication is executed, including its pre-conditions and its stop conditions | **UNRESOLVED** — candidate arrangement not yet prepared |
| **PM-6** | Post-upload verification | How it is confirmed that the published result is the authorised content, correctly identified — and what happens when it is not | **UNRESOLVED** — candidate arrangement not yet prepared |
| **PM-7** | Supersession / withdrawal route | How previously published information is superseded or withdrawn, by whom, with what record, and with what retention of history | **UNRESOLVED** — candidate arrangement not yet prepared |

### 5.2 Evidence required

| Ref | Repository evidence required | Possible live observation category | Can observation **resolve** it? | Can observation **inform** it? |
|---|---|---|---|---|
| **PM-1** | Governance statement of intended destination and its basis | **OC-A** | **No** | Yes — bounded to what is visibly present |
| **PM-2** | An authority decision | **None — excluded (§6)** | **No** | **No** |
| **PM-3** | Generation route from the authoring source (BEP §13.5) | **OC-D** | **No** | Yes — destination-side format constraints only |
| **PM-4** | Governance requirement for identity, version and status | **OC-B** | **No** | Yes — which fields are technically available |
| **PM-5** | Procedure drafted against confirmed platform behaviour; manual controlled publication only (BEP §13.5) | **OC-D** | **No** | Yes — platform behaviour and limits |
| **PM-6** | Verification method with acceptance and failure criteria | **OC-C** | **No** | Yes — what is observable after an upload |
| **PM-7** | Supersession / withdrawal rule and its authority | **OC-D** | **No** | Yes — what the platform supports and prevents |

> **No matter is resolved by observation.** Observation produces **EC-3**
> evidence and nothing more. **Observation informs; decisions resolve.** The
> "resolve" column is `No` for all seven by design, and is not expected to change.

### 5.3 Governance input, dependencies and current evidence status

| Ref | Governance / authority input required | Dependencies | Current evidence-requirement status |
|---|---|---|---|
| **PM-1** | Arrangement decision identifying the governed destination and its basis | — | **IDENTIFIED — NOT YET SOUGHT**; live observation may be required |
| **PM-2** | **An authority decision establishing a publication / exchange function** | — | **GOVERNANCE DECISION REQUIRED** |
| **PM-3** | Arrangement decision recording format and generation route | PM-1 | **IDENTIFIED — NOT YET SOUGHT**; partly available in repository |
| **PM-4** | Metadata requirement, recorded as part of the arrangement decision | PM-1, PM-3 | **IDENTIFIED — NOT YET SOUGHT**; live observation may be required |
| **PM-5** | Approved controlled procedure, separate from the arrangement decision | PM-1, PM-2, PM-3, PM-4 | **IDENTIFIED — NOT YET SOUGHT**; live observation may be required |
| **PM-6** | Verification method and its criteria | PM-1, PM-3, PM-4, PM-5 | **IDENTIFIED — NOT YET SOUGHT**; live observation may be required |
| **PM-7** | Supersession / withdrawal rule, and the authority to exercise it | PM-1, PM-2, PM-4 | **IDENTIFIED — NOT YET SOUGHT**; live observation may be required |

### 5.4 Future decision output, notes and restrictions

| Ref | Future decision output | Notes and restrictions |
|---|---|---|
| **PM-1** | An arrangement decision, recorded in the Governance & Decision Register | **A visible folder is not the governed publication location.** Naming is evidence of naming (Increment 7C §4) |
| **PM-2** | An **authority decision**, analogous in form to AG-001 but **not derived from it**. AG-001 §9 — holding the approval function confers none of the other authorities | **Observationally excluded — see §6.** No holder may be nominated as a side effect of planning |
| **PM-3** | An arrangement decision | Must not fix PM-1 or PM-4 by implication |
| **PM-4** | A metadata requirement | Field availability is a platform fact; **what must be carried is a governance requirement**. The two are not the same |
| **PM-5** | An approved controlled procedure | **Depends on PM-1…PM-4.** A procedure drafted first would fix them by implication rather than by decision. **Manual controlled publication only** — no automation or live-sync model is approved (BEP §13.5, 6.10) |
| **PM-6** | A verification method | Verification is of the **published result against what was authorised** — it establishes nothing about delivery, receipt or acceptance |
| **PM-7** | A supersession / withdrawal rule | **Supersession retains history; it does not delete it** (BEP 7.10, 9.9, 12.10). PE-S is a separate act from the original publication (Increment 8A §2.1) |

---

## 6. PM-2 — observational exclusion

> **PM-2 — publication owner — cannot be resolved by live platform
> observation, and is excluded from every observation category in this
> register.**

### 6.1 What does not establish the governed publication owner

None of the following, individually or in combination:

| Observable thing | Why it is not the answer |
|---|---|
| Folder ownership | A platform attribute of a container |
| Account ownership | A platform account is not a project function |
| Administrative access | A system capability, not a governance appointment |
| Upload permission | **Permission is not authority** — being able to perform an action says nothing about who was authorised to decide it |
| Project membership | Records participation in a system, not authority over an exchange |
| Team membership | **A team is not an organisation, task team, discipline or appointment** |
| Previous publication activity | Evidences platform activity, not governed authority (Increment 7C §6A, §9) |
| Being the sender of a previous Transmittal | Evidences an action performed, not an authority held |

### 6.2 Standing position

PM-2 remains:

- **NOT OBSERVABLE as a governance answer** — no read-only observation can
  supply it;
- **GOVERNANCE DECISION REQUIRED** — dependent on a later authority decision;
- **excluded from OC-A to OC-D**, and from any successor category.

> **No observation session, and no report from one, may be cited as having
> identified the publication owner.** If a future observation returns ownership,
> permission or membership facts, those are **EC-3** platform facts about
> permission, and they are recorded as such — never as authority (§8.2).

### 6.3 Related unresolved authority

**Recipient acceptance authority is likewise unresolved** and likewise cannot be
established by observation (AD-001 §6, Condition 5; Increment 8A §4.2).
Acceptance may not be inferred from access, availability, transmission, receipt,
viewing, download, silence or elapsed time.

**Neither authority is assigned by this register, and no person or functional
holder is nominated for either.**

---

## 7. Observation categories

Carried forward unchanged from Increment 8A §6.2. **These are categories, not
questions.**

### 7.1 Category control table

| Ref | Category | Permitted observational scope | Matters it may inform | What it cannot prove | Likely source / tool boundary | Exact question drafted? |
|---|---|---|---|---|---|---|
| **OC-A** | Candidate destination structures visibly present | Read-only enumeration of what structures exist and how they are labelled | PM-1 | That any structure is the **governed** publication location; that any arrangement is intended | Read-only folder/project listing; limited to what the account can see | **NOT DRAFTED** |
| **OC-B** | Metadata fields technically visible and populatable | Read-only inspection of which identity, version and status fields exist | PM-4 | What metadata **must** be carried; that a visible field is governed or enforced | Read-only item/version property inspection | **NOT DRAFTED** |
| **OC-C** | Version, integrity and upload-verification information observable after an upload performed by others | Read-only inspection of version and related information already present | PM-6 | That any upload was authorised; that a verification process exists or was followed | Read-only version history; **no upload is performed to create the observation** | **NOT DRAFTED** |
| **OC-D** | Technical capabilities and limitations the platform and connector expose, including what they prevent | Read-only determination of supported and prevented operations | PM-3, PM-5, PM-7 | That a supported operation is permitted governance; that a prevented one is governed prohibition | Read-only capability inspection and documented tool behaviour | **NOT DRAFTED** |

**PM-2 appears in no row.** That is deliberate (§6).

### 7.2 Standing limits on any future observation

Carried from Increment 8A §6.3 and binding on every category above:

- **read-only** — no creation, modification, deletion, upload, move, rename,
  issue, review, transmittal or configuration change;
- **observed state is not intended governance**;
- **a visible folder is not the governed publication location**;
- **permissions do not establish authority**;
- **absence of observation is not observation of absence**;
- **observation is not a decision** — it produces EC-3 evidence and nothing more;
- the completed Increment 7C session is preserved as an **evidence archive**; no
  approval or publication work continues in it.

### 7.3 Authorisation position

> **No observation is authorised.** No category above has been put forward for
> authorisation, and no authorisation record exists.

---

## 8. Evidence-source classes

### 8.1 Class table

**EC-1 to EC-8 are carried forward unchanged from Increment 8A §5.** **EC-9 is
an additive extension** made by this register; it alters no existing class.

| Ref | Class | What it can establish | What it cannot establish |
|---|---|---|---|
| **EC-1** | **Controlled repository evidence** — controlled documents and registers | What the governance system states and intends | That anything was decided by an authorised function, or implemented |
| **EC-2** | **Historical decision evidence** — a recorded decision by an identified function under a stated authority | That a decision was taken, by whom, on what basis, with what conditions | That it was implemented, or that implementation was correct |
| **EC-3** | **Live-system observational evidence** — read-only observation | What is **visibly present or absent** at the time of observation | What is intended, governed, authorised, or true beyond what was observed |
| **EC-4** | **Implementation evidence** — records of a performed act | That an act was performed | That it was **authorised**, or that its result is correct |
| **EC-5** | **Post-upload verification evidence** — checks against the authorised content | That the published result matches what was authorised, as far as the check reaches | That the information was delivered, received or accepted |
| **EC-6** | **Delivery evidence** — a transmission record | That an exchange was executed — what, when, by which function, to whom, for what purpose | That it arrived, or that anyone acted on it |
| **EC-7** | **Receipt evidence** — a registered receipt | That an exchange arrived | Acceptance |
| **EC-8** | **Acceptance evidence** — a recorded recipient decision against a stated purpose | That the recipient accepted or rejected for that purpose | Technical approval, or transfer of technical responsibility |
| **EC-9** | **Authority / appointment evidence** — a recorded decision establishing a function and its authority | **That a function exists and who may exercise it** | That the holder used it correctly, or that any other authority follows from it |

**Why EC-9 was added.** Increment 8A §5 folded authority into EC-2. PM-2 turns
entirely on authority, and Increment 8A §4.1 lists eight observable things that
are **not** authority. Tracking authority evidence as its own class keeps that
distinction visible in the register rather than implicit. **This is an extension
of the 8A set, not a revision of it**; reading it back into the framework would
require a later controlled increment.

### 8.2 Non-substitution rules

> **One evidence class may never silently stand in for another.**

| Rule | |
|---|---|
| **EC-3 cannot establish authority** | Observation shows permission and configuration. Authority comes from **EC-9** |
| **EC-4 cannot establish approval** | Implementation evidence shows an act occurred, not that it was authorised. Approval comes from **EC-2** |
| **EC-4 cannot establish verification** | Performing is not checking. Verification comes from **EC-5** |
| **EC-6 cannot establish receipt** | Sending is not arriving. **Non-receipt is not deemed receipt.** Receipt comes from **EC-7** |
| **EC-7 cannot establish acceptance** | Arrival is not agreement. **Silence is not acceptance.** Acceptance comes from **EC-8** |
| **EC-3 cannot establish intended governance** | **Visible system state is not intended governance** |
| **EC-1 cannot establish that a decision was taken** | A document stating a position is not a decision record. That comes from **EC-2** |

**Substitution across these lines is the failure mode this register exists to
prevent.** Where an entry's class is unclear, it is recorded at the **weaker**
class, not the stronger one.

---

## 9. Evidence-entry schema

### 9.1 Required fields

Every `PPER-` entry must carry all of the following. **An entry missing any
field is incomplete and may not be assessed.**

| # | Field | Requirement |
|---|---|---|
| 1 | **Evidence identifier** | `PPER-nnn`, sequential, never reused |
| 2 | **Related identifier** | The `PM-` matter and / or `OC-` category it relates to |
| 3 | **Source** | The controlled record, system area or session it came from |
| 4 | **Source / observation date** | When the evidence was produced or observed |
| 5 | **Collector / recorder function** | The **function**, where applicable. Never a personal identity |
| 6 | **Evidence class** | One of `EC-1` … `EC-9` (§8.1) |
| 7 | **Factual observation** | What was recorded, stated as fact and nothing more |
| 8 | **Limitations** | Scope, timing, tooling and visibility limits on that fact |
| 9 | **What it supports** | Stated narrowly |
| 10 | **What it does not support** | **Mandatory.** An entry without this field invites exactly the substitution §8.2 prohibits |
| 11 | **Repository location / external reference** | Where the underlying material is held |
| 12 | **Assessment status** | From §4.1 — **OBTAINED** on creation |
| 13 | **Supersession relationship** | What it supersedes or is superseded by, where applicable. History retained |

### 9.2 Population rule

Adopted from the Governance & Decision Register: **entries are created only from
actual observations, actual records or explicitly declared assumptions. No entry
is created to make the register look complete.**

**No live evidence entry is fabricated.** No entry below was produced by
observation performed during Increment 8B — **no observation was performed**.

### 9.3 Seeded entries — existing repository evidence only

Three entries are seeded, drawn entirely from **existing controlled repository
records**. They are recorded because the evidence already exists and is relevant;
they are **not** new evidence, and none has been assessed.

#### PPER-001

| Field | Value |
|---|---|
| Related identifier | PM-1 (context only), OC-A |
| Source | `docs/Increment-7C-Live-Validation-Record.md` §6A |
| Source / observation date | Increment 7C, recorded 2026-08-01 |
| Collector / recorder function | Repository developer, read-only validation |
| Evidence class | **EC-3** — live-system observational, recorded historically |
| Factual observation | One architectural A101/A102 drawing-set PDF, version 1, was observed in a `03. Published / Drawings - PDF` area |
| Limitations | Single point in time; one inspected level; read-only; visibility limited to the observing account |
| What it supports | That an area so named existed and contained drawing information at the time of observation |
| **What it does not support** | **That this is, or should be, the governed publication location.** Establishes no governed publication authority, no approved delivery requirement, no recipient acceptance. **Naming is evidence of naming** (7C §4) |
| Repository location | `docs/Increment-7C-Live-Validation-Record.md` §6A |
| Assessment status | **OBTAINED — not assessed** |
| Supersession | None |

#### PPER-002

| Field | Value |
|---|---|
| Related identifier | PM-2 |
| Source | `docs/Increment-7C-Live-Validation-Record.md` §9 |
| Source / observation date | Increment 7C, recorded 2026-08-01 |
| Collector / recorder function | Repository developer, read-only validation |
| Evidence class | **EC-3** — live-system observational, recorded historically |
| Factual observation | No governed publication / exchange authority evidence, and no governed recipient acceptance authority evidence, was established during Increment 7C |
| Limitations | **Absence of observation is not observation of absence.** Records what was not established, not that no such thing exists anywhere |
| What it supports | That the authority gaps recorded at AD-001 §6, Condition 5 were not closed by the 7C observation |
| **What it does not support** | **That any authority exists, or that any does not.** Platform permissions, sender identity, review participation and the ability to create a Transmittal are not governance authority. **PM-2 remains GOVERNANCE DECISION REQUIRED** (§6) |
| Repository location | `docs/Increment-7C-Live-Validation-Record.md` §9 |
| Assessment status | **OBTAINED — not assessed** |
| Supersession | None |

#### PPER-003

| Field | Value |
|---|---|
| Related identifier | PM-1 … PM-7 (all) |
| Source | **GD-001** §6; **AD-001** §6, Condition 2 |
| Source / observation date | 2026-08-01 |
| Collector / recorder function | Training Baseline Approver, under AG-001 |
| Evidence class | **EC-2** — historical decision evidence |
| Factual observation | GCR-005 is carried as an **open pre-publication condition**; its seven matters are recorded as **undefined**, and AD-001 defines none of them |
| Limitations | Records the condition and its status. Defines no matter and prescribes no answer |
| What it supports | That all seven matters are open, and that the publication hold remains active |
| **What it does not support** | **No arrangement, location, owner, format, metadata, procedure, verification method or supersession route.** Confers no authority and lifts no hold |
| Repository location | `docs/Training-Baseline-0.1-Gate-C-Decision.md` §6; `docs/Training-Baseline-0.1-Approval-Decision.md` §6 |
| Assessment status | **OBTAINED — not assessed** |
| Supersession | None |

**No further entry exists.** `PPER-004` onward are unallocated.

---

## 10. Observation-question schema

### 10.1 Required fields

Every `PPQ-` entry must carry all of the following.

| # | Field | Requirement |
|---|---|---|
| 1 | **Question identifier** | `PPQ-nnn`, allocated **only when the question is first drafted** |
| 2 | **Related PM and observation category** | Which matter it informs and under which `OC-` category it falls |
| 3 | **Exact read-only question** | The precise text to be asked. **No instruction to change anything** |
| 4 | **Purpose** | What planning matter it informs, and why repository evidence does not suffice |
| 5 | **Factual output requested** | The specific fact sought — enumerable, inspectable, bounded |
| 6 | **Prohibited inference** | **Mandatory.** What must **not** be concluded from any answer |
| 7 | **Tool / connector boundary** | Which read-only tools may be used, and the explicit no-write boundary |
| 8 | **Expected evidence class** | Normally `EC-3`. **Never `EC-9`** — no question can return authority |
| 9 | **Status** | From §4.2 — **NOT DRAFTED** until text exists |
| 10 | **Authorisation reference** | The record authorising the question to be asked. **Empty until one exists** |
| 11 | **Answer / evidence reference** | The `PPER-` entry holding the answer. Empty until answered |
| 12 | **Limitations** | Known limits on what any answer can establish |

### 10.2 Question placeholders

> **No question text is written by Increment 8B, and no `PPQ-` identifier is
> allocated.**

| Category | Exact question text | Status | Authorisation | Answer |
|---|---|---|---|---|
| **OC-A** | *— not drafted —* | **NOT DRAFTED** | None | None |
| **OC-B** | *— not drafted —* | **NOT DRAFTED** | None | None |
| **OC-C** | *— not drafted —* | **NOT DRAFTED** | None | None |
| **OC-D** | *— not drafted —* | **NOT DRAFTED** | None | None |
| **PM-2** | **Not applicable — observationally excluded (§6)** | **N/A** | **N/A** | **N/A** |

**No Claude Desktop instruction, prompt or session brief is written here.** A
question becoming `DRAFT` does not make it askable; drafting, review,
authorisation and asking are four separate steps (§4.2).

---

## 11. Current register state

As at completion of Increment 8B:

| Statement | Position |
|---|---|
| PM-1 … PM-7 exist as controlled planning matters | **Yes — all seven** |
| A publication arrangement has been selected | **No** |
| PM-2 is excluded from observational resolution | **Yes — §6** |
| Exact live questions drafted | **None — all NOT DRAFTED** |
| Any question authorised | **No** |
| Live observation performed | **None** |
| Publication authority assigned | **No** |
| Recipient acceptance authority assigned | **No** |
| Evidence entries recorded | **Three — PPER-001 … PPER-003, all repository-sourced, all OBTAINED and unassessed** |
| Decisions recorded in this register | **None — and none may be** (§2.2) |
| **GCR-005** | **OPEN — unchanged** |
| **GCR-006** | **OPEN — unchanged** |
| **UD-001** | **OBSERVED discrepancy + UNRESOLVED DECISION — unchanged** |
| Publication | **NOT AUTHORISED — unchanged** |
| Publication hold | **ACTIVE — unchanged** |
| Project standards | **Not established — unchanged** |
| Tags / releases | **None — unchanged** |

**GCR-006 is untouched by this register.** No governed coordination cycle has
been exercised or evidenced, and progress on Publication Planning is not
progress on GCR-006 (Increment 8A §7.1).

---

## 12. Change control

Later changes to any of the following must be made through **later controlled
increments with identifiable repository history** — never by silent edit:

| Change | Requirement |
|---|---|
| Matter status (§5) | A controlled increment recording what changed and on what basis |
| Evidence assessment — `OBTAINED` → `ASSESSED` / `INSUFFICIENT` | A controlled increment. Assessment is a performed act, not a lapse of time |
| Drafting an exact observation question | A controlled increment; allocates the `PPQ-` identifier |
| **Authorising an observation** | A **separate recorded authorisation**. Drafting a question does not authorise asking it |
| Recording an answer | A controlled increment creating the `PPER-` entry |
| **A decision** | Recorded in `supporting/governance-decision-register.md` under its own identifier, through the approved decision route. **Referenced here, never duplicated** (§2.2) |
| Implementation or verification evidence | A controlled increment, after the event it evidences has been separately authorised |

**Entries are never deleted or renumbered.** Superseded material is marked
superseded and retained (BEP 12.10).

---

## 13. Register statement

> **This register controls Publication Planning evidence and observation
> questions, and nothing else.**
>
> It records no decision, selects no publication arrangement, assigns no
> authority, drafts no question, authorises no observation, and closes no
> condition.
>
> ## **PUBLICATION REMAINS NOT AUTHORISED — PUBLICATION HOLD ACTIVE.**
