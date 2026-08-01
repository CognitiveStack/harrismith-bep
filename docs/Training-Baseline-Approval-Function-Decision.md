# Training Baseline Approval Function — Governance Decision

| Field | Value |
|---|---|
| Document status | **Controlled Governance Decision** |
| Decision status | **APPROVED GOVERNANCE** |
| Governance reference | **AG-001** |
| Authority of this record | Records the approved training-governance function |

**This record does not approve Training Baseline 0.1.** It establishes *who may
make that decision*. The candidate remains **FOR REVIEW — NOT APPROVED** and
publication remains on hold. Gate C was subsequently passed through **GD-001**
using this function — see section 11.

---

## 1. Decision identification

| Field | Value |
|---|---|
| Title | **Establishment of the Training Baseline Approval Function** |
| Decision classification | **APPROVED GOVERNANCE** |
| Decision scope | Harrismith BIM-management training / reference implementation |
| Source | Orchestrator decision, Increment 7G |
| Arising from | Increment 7F readiness assessment, condition **GCR-001** |

## 2. Decision

The **Training Baseline Approver** function is established.

| Field | Value |
|---|---|
| Function name | **Training Baseline Approver** |
| Functional holder | **Training Implementation Owner** |
| Training basis | **TA-02** — simulated role participation |
| Personal holder | **Not recorded.** No personal name appears in this repository |

**This is a simulated training / reference-implementation function under TA-02.
It is not a real project appointment**, and it creates no professional authority
or duty for any person exercising it.

## 3. Authority scope

The Training Baseline Approver **may**:

- review a defined Training Baseline candidate snapshot;
- **approve** it as an Approved Training Baseline;
- **reject** it;
- **defer** it;
- **approve it with explicitly recorded conditions**;
- confirm the exact approved Git snapshot;
- authorise the controlled baseline status transition.

## 4. Explicit limits

The Training Baseline Approver does **not** thereby obtain:

- contractual authority;
- professional appointment;
- professional or design approval authority;
- project publication / exchange authority;
- recipient acceptance authority;
- authority to modify Autodesk configuration;
- authority to approve discipline design;
- authority to accept project deliverables.

**The function approves a training document set. It does not approve the
project, the design, or anything issued from them.**

## 5. Decision preconditions

Before a candidate may be approved, the Training Baseline Approver must have:

- a **defined candidate snapshot**, identifiable in Git;
- a **completed Gate C decision**;
- **candidate review evidence**;
- **live-validation evidence**;
- the **known limitations and conditions**;
- confirmation that **no approval blocker remains**.

Approving without these is outside the function's scope.

## 6. Decision outcomes

| Outcome | Meaning |
|---|---|
| **APPROVE** | The candidate becomes an Approved Training Baseline |
| **APPROVE WITH CONDITIONS** | Approved, with conditions recorded and binding |
| **DEFER** | No decision taken; reason recorded |
| **REJECT** | Not approved; reason recorded and returned for correction |

Every outcome must identify:

| Field |
|---|
| Candidate snapshot |
| Decision function |
| Decision date |
| Conditions |
| **Publication instruction or hold** |
| Supersession / change-control instruction |

## 7. Status transition control

**No status transition is performed by this record.**

A future approval decision may transition the candidate from:

> **FOR REVIEW — Training Baseline 0.1 Candidate · Not approved**

to the applicable status from the **existing** BEP §13.6 vocabulary:

| Working Draft | For Review | **Approved Training Baseline** | Superseded | Withdrawn |
|---|---|---|---|---|

**No new or conflicting status vocabulary is created.** The transition is
authorised by the Training Baseline Approver and applied through a controlled
increment.

## 8. Publication hold

> **Training Baseline approval does not automatically authorise publication to
> Forma / ACC.**

**Unless a later decision explicitly authorises publication, the PUBLICATION
HOLD remains in force.**

Approval and publication are separate decisions with separate prerequisites
(BEP §13.5; Increment 7F condition GCR-005). The publication parameters —
location, training publication owner, output format, version and status
metadata, upload procedure, post-upload verification, and supersession or
withdrawal route — are **not defined**, and no publication may occur while they
remain so.

## 9. Relationship to other authorities

Five authorities, deliberately kept separate:

| Authority | Status |
|---|---|
| **Training Baseline Approver** | **Established by this decision (AG-001)** |
| Project publication / exchange authority | **Unresolved** (BEP 9.7) |
| Recipient acceptance authority | **Unresolved** (BEP 9.8, 10.11) |
| Governance-change authority | **Class-dependent; no universal approver** (BEP 12.7) |
| Professional / design authority | Outside this implementation entirely |

**Holding the approval function confers none of the other four.**

The same individual may perform more than one training function in this small
reference implementation. Where they do, **every decision must state which
function is being exercised** (BEP 5.11, 9.12).

## 10. Next decision

```
approval-function decision   ✓ this record (7G)
  → post-decision candidate review
  → Gate C decision
  → possible Training Baseline approval decision
```

**Gate C is not passed by this record.** The next step is a post-decision
candidate review, after which a Gate C decision may be recorded by the Training
Baseline Approver.

## 11. Verification

**Verification completed through Increment 7H post-decision candidate review.**

| Field | Result |
|---|---|
| Review | Increment 7H — post-decision candidate review |
| Result | **READY FOR GATE C DECISION** |
| **GCR-001** | **SATISFIED** |
| **GCR-011** | **READY FOR IMPLEMENTATION** |
| Authority bleed | **None identified** — the function was found nowhere presented as publication, acceptance, design or configuration authority |

The status of this decision in the Governance & Decision Register is
correspondingly **AG-001 — approved governance, implemented and verified**.

**Verifying the function does not approve the candidate.** Training Baseline 0.1
remains **not approved**, and this record's approved-governance status is
unchanged by the verification.

**Gate C decision.** The mechanism defined in section 10 was used to record
**GD-001 — Gate C PASS** (2026-08-01) for candidate snapshot
`cc146a5f84b1ce20d2dfc73d878a77c58959c559`. See
[`docs/Training-Baseline-0.1-Gate-C-Decision.md`](Training-Baseline-0.1-Gate-C-Decision.md).

### Gate C decision record — required content

Defined here so the next increment need not invent authority. The future Gate C
decision record must identify:

| Field |
|---|
| Candidate snapshot |
| Decision function — **Training Baseline Approver** |
| Readiness recommendation — Increment 7F |
| Decision — pass / conditional pass / defer / reject |
| Conditions |
| Date |
| **Publication hold** |
| Next approval step |

**No Gate C decision is made in this record.**
