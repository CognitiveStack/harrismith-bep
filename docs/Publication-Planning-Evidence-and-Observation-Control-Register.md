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
6. exact observation questions — drafted by Increment 8C, authorised by
   **ROA-001**, and **asked once** in the Increment 8D observation (§10.2);
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
| **PM-1** | Publication location | Which governed destination holds published information, and on what basis it is *the* governed destination rather than merely an available one | **APPROVED WITH CONDITIONS BY PAD-001** (`docs/Publication-Arrangement-Approval-Decision.md`); candidate **PAC-001** |
| **PM-2** | Publication owner | Which **function** owns the publication act, and under what authority that function exists | **APPROVED WITH CONDITIONS BY PAD-001** (`docs/Publication-Arrangement-Approval-Decision.md`); **OWNER FUNCTION ESTABLISHED UNDER AG-004** (`docs/Training-Baseline-Publication-Owner-Function-Decision.md`); candidate **PAC-001** |
| **PM-3** | Publication format | What artefact form is published from the authoring source, and how it is generated from it | **APPROVED WITH CONDITIONS BY PAD-001** (`docs/Publication-Arrangement-Approval-Decision.md`); candidate **PAC-001** |
| **PM-4** | Publication metadata | What identity, version and status metadata a published artefact must carry, and how each field is populated and checked | **APPROVED WITH CONDITIONS BY PAD-001** (`docs/Publication-Arrangement-Approval-Decision.md`); candidate **PAC-001** |
| **PM-5** | Upload procedure | The controlled sequence by which an authorised publication is executed, including its pre-conditions and its stop conditions | **APPROVED WITH CONDITIONS BY PAD-001** (`docs/Publication-Arrangement-Approval-Decision.md`); candidate **PAC-001** |
| **PM-6** | Post-upload verification | How it is confirmed that the published result is the authorised content, correctly identified — and what happens when it is not | **APPROVED WITH CONDITIONS BY PAD-001** (`docs/Publication-Arrangement-Approval-Decision.md`); candidate **PAC-001** |
| **PM-7** | Supersession / withdrawal route | How previously published information is superseded or withdrawn, by whom, with what record, and with what retention of history | **APPROVED WITH CONDITIONS BY PAD-001** (`docs/Publication-Arrangement-Approval-Decision.md`); candidate **PAC-001** |

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
| **PM-1** | Arrangement decision identifying the governed destination and its basis | — | **ASSESSED — INSUFFICIENT** (PPER-004). Observational evidence obtained and assessed; **insufficient to select a location** |
| **PM-2** | **An authority decision establishing a publication / exchange function** | — | **GOVERNANCE DECISION SATISFIED** — **AG-004** established the **Training Baseline Publication Owner**; **publication / exchange, execution and acceptance authorities remain separate and unresolved or unassigned**. **PM-2 has no observational route**: it was excluded from observation, **no observation was made against it**, and **no observation established the function** (§6, §10.3) |
| **PM-3** | Arrangement decision recording format and generation route | PM-1 | **ASSESSED — INSUFFICIENT** (PPER-005). Observational evidence obtained and assessed; **publication format remains undecided** |
| **PM-4** | Metadata requirement, recorded as part of the arrangement decision | PM-1, PM-3 | **ASSESSED — INSUFFICIENT** (PPER-006). Observational evidence obtained and assessed; **required metadata remains undefined** |
| **PM-5** | Approved controlled procedure, separate from the arrangement decision | PM-1, PM-2, PM-3, PM-4 | **ASSESSED — INSUFFICIENT** (PPER-007). Observational evidence obtained and assessed; **upload procedure remains undefined** |
| **PM-6** | Verification method and its criteria | PM-1, PM-3, PM-4, PM-5 | **ASSESSED — INSUFFICIENT** (PPER-008). Observational evidence **partially** obtained and assessed — version identity returned, integrity attributes not; **verification method remains undefined** |
| **PM-7** | Supersession / withdrawal rule, and the authority to exercise it | PM-1, PM-2, PM-4 | **ASSESSED — INSUFFICIENT** (PPER-009). Authorised observation **completed**, but the **central successive-version relationship was not observable**; **supersession or withdrawal route remains undefined** |

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

> **Subsequent status — 2026-08-02, Increment 8H-A.** **The later authority
> decision anticipated by the second bullet above has been taken**: **AG-004**
> established the **Training Baseline Publication Owner**. **The observational
> position is unchanged** — PM-2 remains **NOT OBSERVABLE as a governance
> answer** and remains excluded from **OC-A to OC-D**, and **no observation
> established the function**. **Authority came from a decision, as this section
> requires.** Decision:
> [`docs/Training-Baseline-Publication-Owner-Function-Decision.md`](Training-Baseline-Publication-Owner-Function-Decision.md).

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
| **OC-A** | Candidate destination structures visibly present | Read-only enumeration of what structures exist and how they are labelled | PM-1 | That any structure is the **governed** publication location; that any arrangement is intended | Read-only folder/project listing; limited to what the account can see | **PPQ-001** — asked under ROA-001; **ANSWERED** |
| **OC-B** | Metadata fields technically visible and populatable | Read-only inspection of which identity, version and status fields exist | PM-4 | What metadata **must** be carried; that a visible field is governed or enforced | Read-only item/version property inspection | **PPQ-003** — asked under ROA-001; **ANSWERED** |
| **OC-C** | Version, integrity and upload-verification information observable after an upload performed by others | Read-only inspection of version and related information already present | PM-6 | That any upload was authorised; that a verification process exists or was followed | Read-only version history; **no upload is performed to create the observation** | **PPQ-005** — asked under ROA-001; **PARTIALLY ANSWERED** |
| **OC-D** | Technical capabilities and limitations the platform and connector expose, including what they prevent | Read-only determination of supported and prevented operations | PM-3, PM-5, PM-7 | That a supported operation is permitted governance; that a prevented one is governed prohibition | Read-only capability inspection and documented tool behaviour | **PPQ-002, PPQ-004, PPQ-007** — asked; **ANSWERED**. **PPQ-006** — asked; **NOT OBSERVABLE WITH AVAILABLE TOOLING** |

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

> **ROA-001 was exercised once on 2026-08-01 and has EXPIRED.** The one
> authorised observation is complete; **no further observation is authorised.**
> The original authorisation —
> [`docs/Publication-Planning-Read-Only-Observation-Authorisation.md`](Publication-Planning-Read-Only-Observation-Authorisation.md),
> outcome **AUTHORISE WITH CONSTRAINTS**, dated 2026-08-01.

**`ROA-001` authorises one session only**, covering `PPQ-001` to `PPQ-007`, on
the Harrismith Fire Station project, read-only, within the account visibility
available in that session. It **expires** when that session has produced its
completion report, or on withdrawal through a later controlled increment.

> **No observation has been performed.** Authorisation permits the act; it is
> not the act (§10.4). **ROA-001 assigns no publication or acceptance authority**
> and does not lift the publication hold.

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
of the 8A set, not a revision of it.**

**Framework alignment — completed 2026-08-01 by Increment 8B-A.** EC-9 has been
aligned back into the controlling framework as a clearly dated post-8A
controlled extension —
[`docs/Publication-Planning-Control-Framework.md`](Publication-Planning-Control-Framework.md)
§5.2. **EC-1 to EC-8 were retained unchanged there**, and the framework records
that EC-9 was not part of the original Increment 8A text. **This is no longer
outstanding work.**

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

### 9.4 Observation entries — Increment 8D, under ROA-001

> **Recorded 2026-08-01 by Increment 8E**, from the single observation session
> authorised by **ROA-001**, which **expired** on producing its completion
> report. Source record:
> [`docs/Increment-8D-Publication-Planning-Read-Only-Observation-Record.md`](Increment-8D-Publication-Planning-Read-Only-Observation-Record.md).

**All six are EC-3 observational evidence.** Each has been **assessed**; none is
a decision, and none resolves any PM matter.

#### PPER-004

| Field | Value |
|---|---|
| Related identifier | **PM-1**; **PPQ-001** / OC-A |
| Source | Increment 8D observation record §6.1; `list_top_folders`, `list_folder_contents` ×4 |
| Source / observation date | **2026-08-01** |
| Collector / recorder function | Read-only observing session under ROA-001; recorded by the repository developer |
| Evidence class | **EC-3** |
| Factual observation | One level-1 folder `Project Files`; four level-2 areas — `0. Common Files`, `01. WIP (Work in Progress)`, `02. Shared`, `03. Published`; level-3 contents enumerated for each, including the names **`07.  Reference Infomation`**, **`2. Structural Consultanrt`** and **`3. MEP consultant`** exactly as displayed |
| Limitations | Depth 3 only; bounded by the observing account's visibility; single point in time. **Absence of observation is not observation of absence** |
| What it supports | The **exact visible folder structure and paths to the authorised depth**; that areas named `WIP`, `Shared` and `Published` **exist**; the **visible naming inconsistencies as displayed** |
| **What it does not support** | **Selection of a governed publication location**; that the information-state model is **implemented or approved**; **completeness outside the observed depth and account boundary**; **an approved naming standard** — none exists, so the inconsistencies are recorded, not raised as non-conformance |
| Repository location | Increment 8D observation record §6.1 |
| Assessment status | **ASSESSED** — obtained, evaluated against PM-1, and **INSUFFICIENT** to select a publication location |
| Supersession | None. Complements **PPER-001** without replacing it |

#### PPER-005

| Field | Value |
|---|---|
| Related identifier | **PM-3**; **PPQ-002** / OC-D |
| Source | Increment 8D observation record §6.2; `get_derivative_manifest` ×2 |
| Source / observation date | **2026-08-01** |
| Collector / recorder function | Read-only observing session under ROA-001; recorded by the repository developer |
| Evidence class | **EC-3** |
| Factual observation | Sampled `.pdf` with `outputType: svf`, `status: success`, two 2D viewables; sampled `.rvt` (`RVTVersion: 2027`) with `outputType: svf`, `overrideOutputType: svf2`, `status: success`, two 3D viewables, property database and `Autodesk.AEC.ModelData`. **Both manifests pre-existing; no translation triggered** |
| Limitations | Two sampled items only; **content was never retrieved**, so format is observable **only as declared**, not verified from the file |
| What it supports | That the sampled **PDF and RVT formats are present**; that **existing completed derivative manifests are exposed**; the **exact derivative types reported** |
| **What it does not support** | **Approval of a publication format**; **approval of any derivative as a deliverable**; **suitability, completeness or correctness of file content** |
| Repository location | Increment 8D observation record §6.2 |
| Assessment status | **ASSESSED** — obtained, evaluated against PM-3, and **INSUFFICIENT** to decide a publication format |
| Supersession | None |

#### PPER-006

| Field | Value |
|---|---|
| Related identifier | **PM-4**; **PPQ-003** / OC-B |
| Source | Increment 8D observation record §6.3; `get_item_details` ×2, `list_item_versions` ×2, `get_derivative_manifest` |
| Source / observation date | **2026-08-01** |
| Collector / recorder function | Read-only observing session under ROA-001; recorded by the repository developer |
| Evidence class | **EC-3** |
| Factual observation | Item-version inspection returned only `id`, `tip_version_id` and `versionNumber`. The RVT manifest additionally exposed embedded authoring properties — `Project Name: "Project Name"`, `Project Number: "Project Number"`, `Author: ""`, `Project Address: "Enter address here"`, `Project Issue Date: "Issue Date"`, `Project Status: "Project Status"`, `Client Name: "Owner"`, three empty organisation/building fields, `revitNumberOfSaves: 14` — **several being Revit default or placeholder strings**. The PDF manifest carried no such block |
| Limitations | Two sampled items; custom attribute schemas may not be exposed. **Populatability could not be tested** — that would require a write, which ROA-001 §3 prohibits |
| What it supports | The **exact metadata surface returned by the authorised inspection**; that the **Data Management item surface was minimal**; that the **RVT manifest exposed embedded authoring properties, including default or placeholder values** |
| **What it does not support** | **Required publication metadata**; **metadata correctness**; **metadata governance**; **technical populatability through a read-only route** |
| Repository location | Increment 8D observation record §6.3 |
| Assessment status | **ASSESSED** — obtained, evaluated against PM-4, and **INSUFFICIENT** to define required metadata |
| Supersession | None |

#### PPER-007

| Field | Value |
|---|---|
| Related identifier | **PM-5**; **PPQ-004** / OC-D |
| Source | Increment 8D observation record §6.4, §7 |
| Source / observation date | **2026-08-01** |
| Collector / recorder function | Read-only observing session under ROA-001; recorded by the repository developer |
| Evidence class | **EC-3** |
| Factual observation | **41 operations exposed — 40 non-mutating, 1 state-changing.** The single state-changing operation is `create_forma_proposal`, a guarded write concerning **Forma proposal creation**, requiring `confirm_write: true` and a valid `source_proposal_urn`; **it was not invoked and `confirm_write` was never set**. `prepare_native_floor_stack_preview` is exposed but documented as non-mutating and was not invoked. `list_autodesk_hubs` returned **seven `403 BIM360DM_ERROR` regional warnings** — US, AUS, IND, GBR, CAN, DEU, JPN — each *"You don't have permission to access this API"* |
| Limitations | The **exposed surface may be narrower** than the platform's capability, and narrower than what an account may exercise. Classification is from **exposed definitions, never from trial** |
| What it supports | The **exposed connector operation surface at the observation date**; **classification of those operations as non-mutating or state-changing**; that the **only exposed state-changing operation concerned Forma proposal creation**; the **connector limitations and regional access warnings observed** |
| **What it does not support** | **The complete capability of Autodesk ACC or Forma**; **authority to invoke a write**; **an approved upload procedure**; **a governed prohibition where an operation was not exposed**. The 403 warnings are **platform-access facts and establish nothing about governance authority** |
| Repository location | Increment 8D observation record §6.4, §7 |
| Assessment status | **ASSESSED** — obtained, evaluated against PM-5, and **INSUFFICIENT** to define an upload procedure |
| Supersession | None |

#### PPER-008

| Field | Value |
|---|---|
| Related identifier | **PM-6**; **PPQ-005** / OC-C |
| Source | Increment 8D observation record §6.5; `list_item_versions` ×2, `get_file_version_approval_statuses` ×2 |
| Source / observation date | **2026-08-01** |
| Collector / recorder function | Read-only observing session under ROA-001; recorded by the repository developer |
| Evidence class | **EC-3** |
| Factual observation | Both sampled items returned **exactly one version** (`count: 1`, `has_more: false`). The PDF tip returned **two approval records**, both `review_status: OPEN`, `approval_label: "In review"`, `approval_value: IN_REVIEW`. The RVT tip returned `results: []`, `count: 0`. **Creation timestamp, file size and checksum / hash were not returned** for either item |
| Limitations | Two sampled items; attributes vary by item type and storage route. **No upload was performed to create the observation** |
| What it supports | The **sampled version counts**; the **exact approval-status values returned**; that **timestamp, size and checksum / hash fields were not returned through the inspected routes** |
| **What it does not support** | **That approval occurred** — `IN_REVIEW` is a field value, not an approval event; **that verification occurred**; **information integrity**; **the absence of approval or integrity information elsewhere** — an empty result means none was returned, not that none exists |
| Repository location | Increment 8D observation record §6.5 |
| Assessment status | **ASSESSED** — obtained, evaluated against PM-6, and **INSUFFICIENT** to define a verification method. The requirement is **partially met**: version identity was returned; integrity attributes were not |
| Supersession | None |

#### PPER-009

| Field | Value |
|---|---|
| Related identifier | **PM-7**; **PPQ-006** / OC-D |
| Source | Increment 8D observation record §6.6 |
| Source / observation date | **2026-08-01** |
| Collector / recorder function | Read-only observing session under ROA-001; recorded by the repository developer |
| Evidence class | **EC-3** |
| Factual observation | **No eligible multi-version item was visible** within the bounded sample-establishment paths: both sampled items were single-version, and `03. Published / Models - RVT`, `03. Published / Models - IFC` and `Consumed` each returned `counts: {items:0, folders:0, total:0}`. **No version was created.** Incidentally, none of the 41 exposed operations replaces, supersedes, archives, withdraws or removes a document version or item |
| Limitations | Bounded to the checked paths and to the exposed connector surface. **The version-listing calls succeeded** — this is an absence of eligible subject matter, not a tooling failure |
| What it supports | That **no eligible multi-version item was visible within the bounded sample-establishment paths**; that **successive-version relationships could not be observed under ROA-001**; that the **connector exposed no document supersession, withdrawal, archive or removal operation in the inspected surface** |
| **What it does not support** | **That no multi-version item exists elsewhere**; **that Autodesk lacks versioning or supersession capabilities**; **a governed retention rule**; **an approved supersession or withdrawal route**; **a governed prohibition** |
| Repository location | Increment 8D observation record §6.6 |
| Assessment status | **ASSESSED** — obtained, evaluated against PM-7, and **INSUFFICIENT**. The central successive-version relationship **was not observable**, and PM-7's evidence requirement is **not met** |
| Supersession | None |

**No further entry exists.** `PPER-010` onward are unallocated.

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

### 10.2 Drafted question set

> **Drafted by Increment 8C, refined and authorised by Increment 8C-A, asked
> once in the Increment 8D observation, and recorded by Increment 8E — all
> 2026-08-01.** Seven questions, `PPQ-001` to `PPQ-007`, **all asked under
> `ROA-001`, which has since expired**. Final statuses are recorded per question
> below. **No further observation is authorised.**

**No Claude Desktop instruction, prompt or session brief is written here.** A
question being drafted does not make it askable; drafting, review, authorisation
and asking are four separate steps (§4.2, §10.4).

#### 10.2.1 Index

| PPQ | Related PM | Category | Subject | Status |
|---|---|---|---|---|
| **PPQ-001** | PM-1 | **OC-A** | Visible area and folder structure | **ANSWERED** |
| **PPQ-002** | PM-3 | **OC-D** | File types and derivative output formats of items already present | **ANSWERED** |
| **PPQ-003** | PM-4 | **OC-B** | Metadata field names and current values returned | **ANSWERED** |
| **PPQ-004** | PM-5 | **OC-D** | Connector operation surface and documented constraints | **ANSWERED** |
| **PPQ-005** | PM-6 | **OC-C** | Version and integrity attributes of versions already present | **PARTIALLY ANSWERED** |
| **PPQ-006** | PM-7 | **OC-D** | Inter-version relationships and exposed lifecycle capabilities | **NOT OBSERVABLE WITH AVAILABLE TOOLING** |
| **PPQ-007** | PM-3, PM-5, PM-7 | **OC-D** | Connector limitations encountered | **ANSWERED** |
| **PM-2** | — | **None** | **No question drafted — observationally excluded (§6)** | **N/A** |

**Category boundaries were not widened to fit a question.** OC-D informs PM-3,
PM-5 and PM-7 only (§7.1), so `PPQ-007` is scoped to those matters. A limitation
encountered while answering `PPQ-001`, `PPQ-003` or `PPQ-005` is recorded in
**that question's own answer and status**, not reassigned to OC-D.

#### 10.2.2 PPQ-001

| Field | Value |
|---|---|
| Related PM / category | **PM-1** / **OC-A** |
| **Exact read-only question** | *"Using read-only listing operations only, enumerate the visible top-level areas of the Harrismith Fire Station project and their child folders to a depth of three levels. For each, report the exact visible name as displayed and the exact observed path. Report only what is listed; report nothing about intended use, suitability or governance."* |
| Purpose | Informs **PM-1**. Repository evidence cannot establish what structures exist in the live environment; only observation can enumerate them |
| Factual output requested | Exact visible names; exact observed paths; depth reached at each branch; count of children per level; any area visible but not enumerable |
| **Prohibited inference** | **A visible area or folder is not the governed publication location.** An area named after an information state is evidence of naming only — not that a state model is implemented, governed or approved (Increment 7C §4). **No enumerated structure is selected, preferred or recommended by being listed** |
| Tool / connector boundary | `autodesk-aps-forma` read-only listing (hub, project, top-folder and folder-contents enumeration). **No create, rename, move, delete, upload or permission change.** No Desktop Connector / ACCDocs interaction |
| Expected evidence class | **EC-3** |
| Status | **ANSWERED** |
| Authorisation reference | **ROA-001** — `docs/Publication-Planning-Read-Only-Observation-Authorisation.md` |
| Answer / evidence reference | **PPER-004** — `docs/Increment-8D-Publication-Planning-Read-Only-Observation-Record.md` §6.1 |
| Limitations | Visibility is bounded by what the observing account can see; point-in-time; depth-limited by the question. Increment 7C observed only "at the inspected level", and the same bound applies. **A `NOT OBSERVABLE WITH AVAILABLE TOOLING` result would mean the listing route did not return the structure — not that the structure is absent** |

#### 10.2.3 PPQ-002

| Field | Value |
|---|---|
| Related PM / category | **PM-3** / **OC-D** |
| **Exact read-only question** | *"For each item version in the controlled observation sample defined by ROA-001, report the exact file extension and, where the tooling exposes it, the source file type and any derivative or translated output formats listed for that version. Do not request, trigger or download any translation, export or file content."* |
| Purpose | Informs **PM-3**. The generation route is a repository matter (BEP §13.5), but destination-side format constraints are observable only in the live environment |
| Factual output requested | File extensions; source file types as reported; derivative or translated output formats listed; whether a derivative manifest is exposed; items for which no format information is returned |
| **Prohibited inference** | **An observed file format is not an approved publication format**, and the presence of a derivative output is not evidence that the derivative is an approved deliverable form. **The format in which information currently exists in the live environment does not determine the format in which anything may later be published** |
| Tool / connector boundary | `autodesk-aps-forma` read-only item / version detail and derivative-manifest inspection. **No file download or content retrieval, no translation job creation, no export.** A manifest may be inspected without retrieving what it references |
| Expected evidence class | **EC-3** |
| Status | **ANSWERED** |
| Authorisation reference | **ROA-001** — `docs/Publication-Planning-Read-Only-Observation-Authorisation.md` |
| Answer / evidence reference | **PPER-005** — `docs/Increment-8D-Publication-Planning-Read-Only-Observation-Record.md` §6.2 |
| Limitations | **Bounded to the ROA-001 controlled sample — at most three items — and therefore not exhaustive of the project.** Derivative availability varies per item and per translation state. **Content retrieval is out of scope**, so format is observable only as declared, not as verified from the file. **`NOT OBSERVABLE` would mean the format field or manifest was not returned — not that the item has no format** |

#### 10.2.4 PPQ-003

| Field | Value |
|---|---|
| Related PM / category | **PM-4** / **OC-B** |
| **Exact read-only question** | *"For each item version in the controlled observation sample defined by ROA-001, report the exact name of every metadata field returned by read-only inspection and, for each field, the exact current value as returned or an explicit indication that it is empty. Report field names exactly as returned, without normalising, translating or grouping them."* |
| Purpose | Informs **PM-4**. Which fields are technically available is a live-system fact that repository evidence cannot supply |
| Factual output requested | Exact field names; exact current values, or an explicit empty indication; which of the identity, version and status field categories appear; fields returned but unpopulated |
| **Prohibited inference** | **A metadata field visible in the live environment is not automatically required publication metadata**, and a populated field is not evidence that its value is governed, checked or correct. **What must be carried is a governance requirement; what is available is a platform fact. The two are not the same** (§5.4) |
| Tool / connector boundary | `autodesk-aps-forma` read-only item / version property inspection. **No property creation, edit, schema change or custom-attribute definition.** |
| Expected evidence class | **EC-3** |
| Status | **ANSWERED** |
| Authorisation reference | **ROA-001** — `docs/Publication-Planning-Read-Only-Observation-Authorisation.md` |
| Answer / evidence reference | **PPER-006** — `docs/Increment-8D-Publication-Planning-Read-Only-Observation-Record.md` §6.3 |
| Limitations | **Bounded to the ROA-001 controlled sample — at most three items — and therefore not exhaustive of the project.** Custom attribute schemas may not be exposed. **OC-B's "populatable" aspect is only partially observable**: whether a field *accepts* a value **cannot be tested read-only**, because **no write may be attempted** under ROA-001 §3. **`NOT OBSERVABLE` would mean the property route returned nothing — not that the item carries no metadata** |

#### 10.2.5 PPQ-004

| Field | Value |
|---|---|
| Related PM / category | **PM-5** / **OC-D** |
| **Exact read-only question** | *"Report which operations the available Autodesk connector exposes, classified as read-only or state-changing, listing each by its exposed operation name. Do not invoke any state-changing operation, including for testing. Where the connector or its documentation states a pre-condition, constraint, or operation that is unavailable or prevented, report that statement exactly as given."* |
| Purpose | Informs **PM-5**. A procedure drafted without confirmed platform behaviour would be speculation presented as method (§5.4) |
| Factual output requested | Exposed operation names; read-only versus state-changing classification; documented pre-conditions and constraints; operations documented as unavailable or prevented |
| **Prohibited inference** | **An available upload or version-creation action is not an approved upload procedure.** The existence of a state-changing operation is neither permission to use it nor evidence that its use would be authorised. **A prevented operation is a technical limitation, not a governed prohibition.** Manual controlled publication remains the only model contemplated (BEP §13.5, 6.10), and no observation can alter that |
| Tool / connector boundary | Enumeration of the connector's exposed operation surface and its documented behaviour. **No state-changing operation is invoked under any circumstances**, and classification is taken from the exposed definition, never from trial |
| Expected evidence class | **EC-3** |
| Status | **ANSWERED** |
| Authorisation reference | **ROA-001** — `docs/Publication-Planning-Read-Only-Observation-Authorisation.md` |
| Answer / evidence reference | **PPER-007** — `docs/Increment-8D-Publication-Planning-Read-Only-Observation-Record.md` §6.4 |
| Limitations | The exposed surface may be narrower than the platform's full capability, and narrower still than what a given account may exercise. **`NOT OBSERVABLE` would mean the operation surface could not be enumerated — not that the platform lacks the capability** |

#### 10.2.6 PPQ-005

| Field | Value |
|---|---|
| Related PM / category | **PM-6** / **OC-C** |
| **Exact read-only question** | *"For each item version in the controlled observation sample defined by ROA-001 — none created by this observation — report the version-identifying and integrity-related attributes returned by read-only inspection, including version number, creation timestamp, file size, any checksum or hash field, and any approval-status field. For each, give the exact field name and value, or an explicit indication that the field is not returned."* |
| Purpose | Informs **PM-6**. What is observable about an existing version bounds what any future verification method could check |
| Factual output requested | Version numbers; creation timestamps; file sizes; checksum or hash fields where present; approval-status fields where present; an explicit list of which of these are not returned |
| **Prohibited inference** | **A visible verification-related field is not an approved verification requirement**, and the presence of an approval-status field is not evidence that any approval, authorisation or verification occurred. **No upload is performed to create this observation** (OC-C), and nothing observed evidences that any existing version was authorised — Increment 7C recorded published drawing information without any governed publication authority evidence (PPER-001, PPER-002) |
| Tool / connector boundary | `autodesk-aps-forma` read-only version-history, version-detail and approval-status inspection where exposed. **No upload, no version creation, no status change, no approval action.** |
| Expected evidence class | **EC-3** |
| Status | **PARTIALLY ANSWERED** |
| Authorisation reference | **ROA-001** — `docs/Publication-Planning-Read-Only-Observation-Authorisation.md` |
| Answer / evidence reference | **PPER-008** — `docs/Increment-8D-Publication-Planning-Read-Only-Observation-Record.md` §6.5 |
| Limitations | **Bounded to the ROA-001 controlled sample — at most three items — and therefore not exhaustive of the project.** Attributes vary by item type and storage route. **Absence of a checksum field is not evidence that integrity data does not exist elsewhere.** **`NOT OBSERVABLE` would mean the attribute was not returned by the inspection route used** |

#### 10.2.7 PPQ-006

| Field | Value |
|---|---|
| Related PM / category | **PM-7** / **OC-D** |
| **Exact read-only question** | *"For one item in the controlled observation sample that has at least two visible versions, report the read-only relationships the tooling exposes between its successive versions and any exposed capability for replacing, superseding, archiving, withdrawing or removing a version or item — by exposed operation or field name only, without invoking any of them. Report whether previous versions remain listed and retrievable in version history."* |
| Purpose | Informs **PM-7**. A supersession or withdrawal route cannot be decided without knowing what the platform supports and what it prevents |
| Factual output requested | Version-to-version relationships exposed; names of any replace, supersede, archive, withdraw or delete capability; whether previous versions remain listed; retention behaviour as exposed |
| **Prohibited inference** | **A technical supersession, archive or delete capability is not an approved supersession or withdrawal route**, and its absence is not a governed prohibition on supersession. **That previous versions remain listed is not evidence that a retention rule exists or is governed.** Supersession retains history (BEP 7.10, 9.9, 12.10); the governed route, and the authority to exercise it, remain undecided (§5.4) |
| Tool / connector boundary | `autodesk-aps-forma` read-only version-history and relationship inspection, plus operation-surface enumeration. **No delete, archive, restore, supersede, withdraw or version-removal operation is invoked.** |
| Expected evidence class | **EC-3** |
| Status | **NOT OBSERVABLE WITH AVAILABLE TOOLING** |
| Authorisation reference | **ROA-001** — `docs/Publication-Planning-Read-Only-Observation-Authorisation.md` |
| Answer / evidence reference | **PPER-009** — `docs/Increment-8D-Publication-Planning-Read-Only-Observation-Record.md` §6.6 |
| Limitations | **If no sampled item has at least two visible versions, this question is `NOT OBSERVABLE WITH AVAILABLE TOOLING`. No version may be created to answer it** (ROA-001 §4.1, rule 8). Bounded to the ROA-001 controlled sample. Exposure may be partial, and a capability present in the platform UI may not be exposed to the connector. **`NOT OBSERVABLE` would mean the relationship or capability was not exposed to inspection — not that the platform cannot do it** |

#### 10.2.8 PPQ-007

| Field | Value |
|---|---|
| Related PM / category | **PM-3, PM-5, PM-7** / **OC-D** |
| **Exact read-only question** | *"Where PPQ-002, PPQ-004 or PPQ-006 could not be answered, report for each the exact request attempted, the exact error, empty result or refusal returned, and whether the connector reported the operation as unavailable, unauthorised or unsupported. Report the limitation exactly as encountered, without substituting an explanation for why it occurred."* |
| Purpose | Informs **PM-3, PM-5, PM-7** by bounding what the tooling can establish. Turns a tooling failure into recorded evidence rather than silence |
| Factual output requested | The exact request attempted; the exact error, empty result or refusal text; the connector's own classification of the failure where it gives one |
| **Prohibited inference** | **Inability of the connector to observe a fact is not observation that the fact is absent, unavailable or prohibited.** A refusal or empty result is evidence about the tooling, not about the project. **Absence of observation is not observation of absence.** An "unauthorised" response is a platform-access fact and **establishes nothing about governance authority** (§6) |
| Tool / connector boundary | Recording of results already returned while answering PPQ-002, PPQ-004 and PPQ-006. **No retry with elevated access, no alternative credential, no workaround route.** |
| Expected evidence class | **EC-3** |
| Status | **ANSWERED** |
| Authorisation reference | **ROA-001** — `docs/Publication-Planning-Read-Only-Observation-Authorisation.md` |
| Answer / evidence reference | `docs/Increment-8D-Publication-Planning-Read-Only-Observation-Record.md` §6.7 — **no PPER entry**; no connector error, refusal or unauthorised result arose |
| Limitations | Scoped to OC-D's matters (§7.1). **Limitations encountered on PPQ-001, PPQ-003 or PPQ-005 belong to those questions' own answers and statuses**, and are not reassigned here. **Answer-status rule — a question takes the status matching what was actually returned:** **`ANSWERED`** where **all** requested factual outputs were returned; **`PARTIALLY ANSWERED`** where **some** were returned and some were unavailable; **`NOT OBSERVABLE WITH AVAILABLE TOOLING`** where **none** of the requested factual output could be obtained through the authorised route. **A recorded limitation does not by itself make a question NOT OBSERVABLE.** Absence of observation is not observation of absence, and **no elevated access, alternative credential or workaround route is permitted** to convert one status into another |

### 10.3 PM-2 — no question drafted

> **No question in this set seeks to identify a publication owner, publication
> or exchange authority, recipient acceptance authority, an authorised uploader,
> or an authorised approver.**

Project membership, folder ownership, permissions, administrative access and
previous activity were **not** used as indirect routes to PM-2. Where any such
fact is returned incidentally by `PPQ-001` to `PPQ-007`, it remains **EC-3**
evidence about permission or configuration and **carries the prohibited
inference that it does not establish authority** (§6, §8.2).

**No question may be added later to answer PM-2 by observation.** PM-2 is
**GOVERNANCE DECISION REQUIRED**, and no read-only observation can supply it.

### 10.4 Status progression

Moving a question from **READY FOR GOVERNANCE REVIEW** to **AUTHORISED FOR
READ-ONLY OBSERVATION** requires a **later explicit governance review and an
identifiable authorisation reference** recorded in the question's authorisation
field. It does not occur by default, by elapsed time, or by a question being
well drafted.

| | |
|---|---|
| **Drafting a question is not authorising it** | Increment 8C drafted; **ROA-001**, through Increment 8C-A, authorised |
| **Authorising a question is not asking it** | Authorisation permits the act; it is not the act. The questions were **subsequently asked once**, in Increment 8D |
| **Asking a question is not receiving an answer** | A question may return nothing, or return `NOT OBSERVABLE` |
| **Receiving an answer is not assessing the evidence** | Answers became `PPER-004`…`PPER-009`; assessment was performed separately, by Increment 8E (§9.4) |

---

## 11. Current register state

As at completion of Increment 8H-A:

| Statement | Position |
|---|---|
| PM-1 … PM-7 exist as controlled planning matters | **Yes — all seven** |
| **PM decision statuses** | All seven read **APPROVED WITH CONDITIONS BY PAD-001** (§5.1). **PM-2 additionally records OWNER FUNCTION ESTABLISHED UNDER AG-004.** **PM-2's authority requirement at §5.3 is now GOVERNANCE DECISION SATISFIED** — PAD-001 approved that the owner function should exist; **AG-004 established it** |
| **Publication owner function** | **ESTABLISHED — `Training Baseline Publication Owner`, AG-004, 2026-08-02.** Functional holder **Training Implementation Owner** under **TA-02**; **no personal holder recorded**. **The function owns package identity, preparation governance and readiness coordination only** |
| **PAD-001 condition C1** | **SATISFIED BY AG-004** |
| **PAD-001 prerequisite P6** | **Step 2 satisfied by AG-004**; **P6 overall remains ACTIVE** |
| **Publication-package commit** | **NOT PINNED** |
| PM evidence positions | **PM-1, PM-3 … PM-7 ASSESSED — INSUFFICIENT**; PM-2 now **GOVERNANCE DECISION SATISFIED** through AG-004, **not through observation** (§5.3) |
| A publication arrangement has been **selected or approved** | **Yes — approved with conditions by PAD-001 at PE-2.** **PE-3 is not authorised and publication remains NOT AUTHORISED** |
| A candidate arrangement has been prepared | **Yes — `PAC-001`, Increment 8F**, classified **at preparation** as **PROPOSED GOVERNANCE — NOT APPROVED**. **PAD-001 subsequently approved the PAC-001 substantive arrangement with conditions at PE-2**; PAC-001 is retained as the **historical proposal record**, and its original document classification is **historical provenance, not the current status of the approved arrangement**. **PE-3 remains not authorised and publication remains NOT AUTHORISED** |
| PM-2 is excluded from observational resolution | **Yes — §6, §10.3.** No observation was made against it |
| Exact live questions drafted | **Seven — `PPQ-001` … `PPQ-007`** (§10.2) |
| PPQ identifiers allocated | **`PPQ-001` to `PPQ-007`; `PPQ-008` onward unallocated** |
| Final question statuses | **ANSWERED** ×5 (001–004, 007); **PARTIALLY ANSWERED** (005); **NOT OBSERVABLE WITH AVAILABLE TOOLING** (006) |
| Authorisation reference populated | **Yes — `ROA-001` on all seven** |
| Any question asked | **Yes — all seven, once**, in the Increment 8D observation |
| Answer / evidence references populated | **Yes — all seven**, to the observation record and, for six, a `PPER-` entry |
| Live observation performed | **One — Increment 8D, 2026-08-01, under ROA-001** |
| **ROA-001** | **EXERCISED ONCE — EXPIRED.** Not renewable; **no further observation is authorised** |
| Claude Desktop session executed | **One** — the authorised session; the brief is **not reusable** |
| Controlled observation sample | **Two items** selected under the rule (maximum three) — recorded in the observation record §5 |
| Mutation reported | **None** |
| Publication authority assigned | **No** |
| Recipient acceptance authority assigned | **No** |
| Evidence entries recorded | **Nine** — PPER-001 … PPER-003 repository-sourced (**OBTAINED — not assessed**); PPER-004 … PPER-009 observation-sourced, **EC-3, all ASSESSED and INSUFFICIENT** |
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

> **Subsequent status — 2026-08-02, Increment 8H-R-A.** The **§11 adjacency was
> corrected** so that **PAC-001's historical candidate classification is
> distinguished from PAD-001's subsequent approval**. **No evidence finding was
> corrected, no PPER assessment was changed, no new decision was made, no
> authority was assigned, no observation was performed and no publication was
> authorised.**

> **Subsequent status — 2026-08-02, Increment 8H-A.** **AG-004 established the
> `Training Baseline Publication Owner` function**, satisfying PM-2's
> owner-function establishment residual, **PAD-001 condition C1** and **P6
> step 2**. **§5.1 PM-2, §5.3 PM-2, §6.2 and §11 were updated to record it.**
> **No evidence finding or PPER assessment changed, no observation occurred,
> PAD-001 remained unchanged in substance, and no publication was authorised.**
> **P6 remains ACTIVE, the publication-package commit remains unpinned, PE-3
> remains not reached and publication remains NOT AUTHORISED.**

---

## 13. Register statement

> **This register controls Publication Planning evidence and observation
> questions, and nothing else.**
>
> It records no decision, selects no publication arrangement, assigns no
> authority, authorises no observation, and closes no condition. **Decisions are
> recorded in `supporting/governance-decision-register.md` and referenced here,
> never duplicated** (§2.2).
>
> The questions at §10.2 were asked once under **ROA-001**, which has since
> **expired**. Their answers are recorded as **EC-3 evidence** at §9.4. The
> candidate arrangement — **PAC-001** — was **approved with conditions by
> PAD-001** at **PE-2**; the §5.1 statuses reference that decision. **PAD-001 is
> a governance decision, not observational evidence, and is not recorded as
> evidence here.** **PE-3 is not authorised, no further observation is
> authorised, and publication remains unauthorised.**
>
> ## **PUBLICATION REMAINS NOT AUTHORISED — PUBLICATION HOLD ACTIVE.**
