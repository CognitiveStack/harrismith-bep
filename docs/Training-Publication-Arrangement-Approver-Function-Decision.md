# AG-003 — Training Publication Arrangement Approver Function Decision

| Field | Value |
|---|---|
| Document status | **Controlled Governance Decision** |
| Decision classification | **APPROVED GOVERNANCE** |
| Governance reference | **AG-003** |
| Decision status | **FUNCTION ESTABLISHED — PAC-001 APPROVAL DECISION NOT YET TAKEN** |
| Decision date | **2026-08-01** |
| Source | **Orchestrator decision — Increment 8G-C** |
| Decision scope | **Training Baseline 0.1 publication-arrangement governance only** |
| Training basis | **TA-02** — simulated role participation |
| Authority of this record | Records the approved training-governance function |

> **This record does not approve PAC-001.** It establishes *who may make that
> decision*. **No PE-2 arrangement-approval decision is taken here.**

> **PUBLICATION REMAINS NOT AUTHORISED — PUBLICATION HOLD ACTIVE.**

> **Subsequent status — 2026-08-01, Increment 8H.** **This function was
> exercised through PAD-001.** Subject: **PAC-001 — Publication Arrangement
> Candidate 0.1**, substantive body hash
> **`4d67dcfcc7556665b3f93f2363b3dfd4`**. Outcome: **APPROVE WITH CONDITIONS**.
> **The exercise remained within AG-003's scope** — a PE-2 arrangement-approval
> decision and nothing more. **No PE-3 or implementation authority followed**,
> and the §6 limits are unchanged. **AG-003 remains an established function**
> available for any later decision within its scope, subject to its §4 readiness
> precondition. Decision:
> [`docs/Publication-Arrangement-Approval-Decision.md`](Publication-Arrangement-Approval-Decision.md).

---

## 1. Decision identification

### 1.1 Arising from

| Source | Contribution |
|---|---|
| **PAC-001** | The publication-arrangement candidate awaiting a PE-2 decision, whose register entry records **"Decision owner: Not established — TBD"** |
| **PRA-001** | The readiness assessment recording **NOT READY FOR APPROVAL** and the PRA-B01 blocker |
| **CGD-001** | Resolved the OF-001 / PM-1 structural dependency at the governance level, removing PRA-B01's stated basis |
| **Increment 8G-B-R exact review** | **32 consistency checks PASS, zero failures**; CGD-001 accepted without correction and no repository change made |
| **PAC-001's unresolved decision-owner field** | **No existing function is authorised to take the PE-2 decision** |

### 1.2 Why no existing function suffices

| Existing record | Why it does not cover PE-2 |
|---|---|
| **AG-001** | Limited to **Training Baseline candidate approval** |
| **AG-002** | Limited to **CDE-structure governance** |
| **CGD-001** | A structural decision; **confers no arrangement-approval authority** |
| Publication / exchange authority | **UNRESOLVED**, and concerns **PE-3**, not PE-2 |
| **PAC-001**, **PRA-001** | Both carry **Authority: None** |

## 2. Decision

The **Training Publication Arrangement Approver** function is established.

| Field | Value |
|---|---|
| Function name | **Training Publication Arrangement Approver** |
| Functional holder | **Training Implementation Owner** |
| Training basis | **TA-02** — simulated role participation |
| Personal holder | **Not recorded.** No personal name appears in this repository |

### 2.1 Where the authority comes from

> **The authority arises from AG-003 itself.**

**No independent authority of the Training Implementation Owner is assumed.**
The Increment 8G-R review established that the Training Implementation Owner has
**no independently established authority** — it appears in the repository only as
the **functional holder** of functions established by other decisions.

**AG-003 therefore creates the authority it confers**, as AG-002 §2.1 did before
it.

### 2.2 Nature of the function

**This is a simulated training / reference-implementation function under TA-02.
It is not a real project appointment**, and it creates **no professional
authority, contractual duty or liability** for any person exercising it.

## 3. Authority scope

The Training Publication Arrangement Approver **may**:

1. **receive a defined publication-arrangement candidate** for Training
   Baseline 0.1;
2. **receive and review its controlled readiness assessment**;
3. **confirm the exact candidate version or repository snapshot** being
   considered;
4. **approve** the candidate arrangement;
5. **reject** it;
6. **defer** it;
7. **approve it with explicitly recorded conditions**;
8. **record which PM-1 … PM-7 candidate positions are approved**;
9. **record every condition that must be satisfied before later PE events**;
10. **authorise the governance-status transition represented by PE-2** — from
    **candidate arrangement** to **approved publication arrangement**.

### 3.1 How the function is exercised

> **The function may exercise this authority only through a later controlled
> approval-decision record.**

**No PE-2 decision is taken in Increment 8G-C.** The mechanism established here
is available; it has not been used.

## 4. Readiness precondition

> **The Training Publication Arrangement Approver may not approve PAC-001 unless
> a fresh controlled readiness assessment has concluded one of:**
>
> - **`READY FOR APPROVAL`**; or
> - **`READY FOR APPROVAL WITH CONDITIONS`.**

| Rule | |
|---|---|
| **A historical readiness assessment whose blocker has subsequently changed is not sufficient by itself** | The factual basis has moved; the conclusion has not been retaken |
| **PRA-001 remains historically valid** | As the assessment made on its date, against the position then obtaining |
| **PRA-001 cannot be used as the current approval basis** | Its outcome was **NOT READY FOR APPROVAL**, and CGD-001 subsequently changed PRA-B01's factual basis |
| **Increment 8G-D must occur before any AG-003 approval power is exercised** | The precondition is mandatory, not advisory |

**Approving without a current qualifying readiness assessment is outside the
function's scope**, in the same way AG-001 §5 places approval without its
preconditions outside the Training Baseline Approver's scope.

## 5. Distinct functions

Seven functions and authorities, deliberately kept apart.

| Function | Position |
|---|---|
| **Training Publication Arrangement Approver** | **Established by AG-003.** Approves or refuses the governance **arrangement** at **PE-2**. **Publishes nothing** |
| **Candidate Publication Owner** | **Proposed by PAC-001 PM-2.** Would own package identity and readiness **if later established**. **Remains proposed only**; **no holder is appointed by AG-003**; **PM-2 remains unresolved** pending the eventual arrangement decision and any required authority action |
| **Publication / Exchange Authoriser** | Authorises a specific publication event at **PE-3**. **UNRESOLVED.** **Not established by AG-003** |
| **Technical Uploader / Executor** | Performs **PE-4** under separate implementation authority. **Unassigned.** **Not established by AG-003** |
| **Recipient Acceptance Authority** | Performs recipient-side acceptance at **PE-8**. **UNRESOLVED**, and **cannot be established by the publishing side through AG-003** |
| **Training CDE Governance Approver** | Decides CDE-structure governance under **AG-002**. **Separate from AG-003** |
| **Training Baseline Approver** | Approves Training Baseline snapshots under **AG-001**. **Separate from AG-003** |

> **Holding the Training Publication Arrangement Approver function confers none
> of the other authorities.**

**Approving an arrangement is not authorising a publication event, and neither
is executing one.** The same individual may perform more than one training
function; where they do, **every decision must state which function is being
exercised** (BEP 5.11, 9.12; AG-001 §9; AG-002 §5.1).

## 6. Explicit limits

The Training Publication Arrangement Approver does **not** thereby obtain:

- project **publication / exchange authority**;
- **publication-event authorisation** authority;
- **recipient acceptance authority**;
- technical **upload or execution** authority;
- **CDE administration or implementation** authority;
- **CDE-structure governance authority under AG-002**;
- **Training Baseline approval authority under AG-001**;
- **professional or design approval** authority;
- authority to **accept project deliverables**;
- authority to **create, rename, move or delete folders**;
- authority to **change memberships or permissions**;
- authority to **generate or assemble the publication package**;
- authority to establish the missing **naming, coordinate, titleblock or
  template** standards;
- authority to **resolve technical implementation prerequisites by assertion**;
- authority to **close GCR-005 merely by establishing the function**;
- authority to **approve PAC-001 before the fresh readiness assessment**;
- authority to **reach PE-3 or any later PE event**.

## 7. Decision separation

```text
PAC-001
is the proposed arrangement.

Increment 8G-D
will assess current readiness.

A later AG-003 decision
may approve, reject, defer or approve PAC-001 with conditions at PE-2.

A separate publication/exchange authority
would later be required to authorise PE-3.

Separate implementation authority
would later be required for PE-4 and any technical CDE act.
```

> **Only the function-establishment event occurs in Increment 8G-C.**

## 8. Relationship to PAC-001

| Statement | |
|---|---|
| **PAC-001's decision owner** | Advanced from **"Not established — TBD"** to **Training Publication Arrangement Approver under AG-003** |
| **PAC-001 is not approved** | Establishing who may decide is not deciding |
| **PAC-001 remains prepared and NOT APPROVED** | Classification, status and Authority: None all unchanged |
| **No PM position changed** | PM-1 … PM-7 remain **CANDIDATE ARRANGEMENT PREPARED — NOT APPROVED** |
| **Readiness must first be reassessed** | §4 |
| **No publication or implementation authority was assigned** | §6 |

## 9. Relationship to PM-2

**AG-003 establishes the arrangement approver, not the publication owner
proposed by PM-2.** These are different functions doing different things:

| | **AG-003 function** | **PM-2 proposed function** |
|---|---|---|
| Name | Training Publication Arrangement Approver | Candidate Publication Owner |
| Established? | **Yes — by AG-003** | **No — proposed only** |
| Role | Approves or refuses the **arrangement** at PE-2 | Would own **package identity and readiness** |
| Holder | Training Implementation Owner, no personal holder | **None appointed or nominated** |

> **PM-2 remains `GOVERNANCE DECISION REQUIRED`.** AG-003 does not resolve it,
> does not appoint its holder, and does not pre-empt whether the proposed owner
> function should exist at all.

## 10. Relationship to PE-2 and PE-3

| Event | Position |
|---|---|
| **PE-1** — planning the arrangement | Reached — PAC-001 prepared |
| **PE-2** — approving the arrangement | **Not reached.** AG-003 establishes **who may** take it; **the decision has not been taken**, and the §4 readiness precondition must be satisfied first |
| **PE-3** — authorising a publication event | **Not reached.** Requires **publication / exchange authority**, which remains **UNRESOLVED** and is **not established by AG-003** |
| **PE-4 … PE-S** | **Not reached** |

> **PE-2 and PE-3 are separate events with separate authorities.** Approving an
> arrangement never authorises a publication event.

## 11. Effect on current governance matters

| Matter | Effect of AG-003 |
|---|---|
| **PAC-001** | Decision owner established. **Not approved. Unchanged in substance** |
| PM-1 … PM-7 | **Unchanged** — CANDIDATE ARRANGEMENT PREPARED — NOT APPROVED |
| **PM-2** | **GOVERNANCE DECISION REQUIRED — unchanged** |
| **PRA-001** | Historical outcome **unchanged**; **not the current approval basis** (§4) |
| **CGD-001**, **AG-002** | **Scopes unchanged.** AG-003 confers nothing of theirs, and they confer nothing of AG-003's |
| **OF-001** | Resolved at governance level by CGD-001; **verification pending — unchanged** |
| **GCR-005**, **GCR-006** | **OPEN — unchanged** |
| **UD-001** | **Unresolved — unchanged** |
| Publication / exchange authority | **UNRESOLVED — unchanged** |
| Recipient acceptance authority | **UNRESOLVED — unchanged** |
| CDE implementation authority | **Not established — unchanged** |
| Project standards | **Not established — unchanged** |
| **PE-2 … PE-S** | **Not reached — unchanged** |
| **Publication** | **NOT AUTHORISED — unchanged** |
| **Publication hold** | **ACTIVE — unchanged** |

## 12. Next decision

```
authority-establishment decision   ✓ this record (AG-003, 8G-C)
  → fresh readiness reassessment    (Increment 8G-D)
  → possible PE-2 arrangement-approval decision, if readiness permits
  → separate publication/exchange authority for PE-3
  → separate implementation authority for PE-4
```

**PAC-001 is not approved by this record.** The next step is a **fresh
controlled readiness reassessment**, after which an arrangement-approval decision
**may** be recorded by the Training Publication Arrangement Approver.

### 12.1 Arrangement-approval decision record — required content

Defined here so the next increment need not invent authority. A future PE-2
decision record must identify:

| Field |
|---|
| The candidate considered, and its **exact version or repository snapshot** |
| Decision function — **Training Publication Arrangement Approver** |
| Authority basis — **AG-003** |
| **The current readiness assessment relied upon**, and its outcome |
| Decision — approve / reject / defer / approve with conditions |
| **Which PM-1 … PM-7 positions are approved** |
| Conditions to be satisfied before later PE events |
| Date |
| **Explicit statement that PE-3 is not authorised** |
| **Publication hold** |

> **No PE-2 decision is made in this record.**

## 13. Verification

**Not yet performed.** AG-003 is established and **not yet exercised**.

Verification would follow the AG-001 pattern — a later review confirming that
the function was correctly scoped, correctly exercised, and **nowhere presented
as publication, acceptance, implementation, CDE-structure, design or
configuration authority**.

---

## 14. Decision statement

> ## **AG-003 — TRAINING PUBLICATION ARRANGEMENT APPROVER FUNCTION ESTABLISHED**
>
> **FUNCTION ESTABLISHED — PAC-001 APPROVAL DECISION NOT YET TAKEN.**
>
> The function may later approve, reject, defer or conditionally approve a
> publication-arrangement candidate at **PE-2** — **only after a fresh readiness
> assessment concludes READY FOR APPROVAL or READY FOR APPROVAL WITH
> CONDITIONS**.
>
> **PAC-001 is not approved. No publication event is authorised. No other
> authority is conferred.**
>
> ## **PUBLICATION REMAINS NOT AUTHORISED — PUBLICATION HOLD ACTIVE.**

**Related records.** Candidate — [`docs/Publication-Arrangement-Candidate-0.1.md`](Publication-Arrangement-Candidate-0.1.md).
Readiness assessment — [`docs/Publication-Arrangement-Readiness-Assessment.md`](Publication-Arrangement-Readiness-Assessment.md).
AG-001 — [`docs/Training-Baseline-Approval-Function-Decision.md`](Training-Baseline-Approval-Function-Decision.md).
AG-002 — [`docs/Training-CDE-Governance-Approver-Function-Decision.md`](Training-CDE-Governance-Approver-Function-Decision.md).
CGD-001 — [`docs/CDE-Structure-Governance-Decision.md`](CDE-Structure-Governance-Decision.md).
