# Training Baseline 0.1 — Gate C Decision

| Field | Value |
|---|---|
| Document status | **Controlled Gate Decision** |
| Decision status | **GATE C — PASS** |
| Governance reference | **GD-001** |
| Authority | **Training Baseline Approver**, exercised by the Training Implementation Owner under **AG-001** |

> **This decision passes Gate C only. It does not approve Training Baseline
> 0.1.**

The candidate remains **FOR REVIEW — NOT APPROVED**, and the **publication hold
remains active**.

> **Subsequent status — 2026-08-01.** The statement above records the candidate
> status **at the time of GD-001**. Training Baseline 0.1 was **subsequently**
> approved **with conditions** through **AD-001**, dated 2026-08-01, and its
> current status is **APPROVED WITH CONDITIONS**. **Publication remains NOT
> AUTHORISED and the publication hold remains active.** AD-001 did **not** alter
> this Gate C decision, its reasoning, its outcome or the Gate-assessed
> candidate snapshot. See
> [`docs/Training-Baseline-0.1-Approval-Decision.md`](Training-Baseline-0.1-Approval-Decision.md).

> **Subsequent status — 2026-08-01, Increment 8H.** **PAD-001 defined the same
> seven publication-arrangement matters**, and **GCR-005 is now CLOSED at the
> governance-definition level** — `CLOSED BY PAD-001 — SEVEN
> PUBLICATION-ARRANGEMENT PARAMETERS DEFINED; IMPLEMENTATION CONDITIONS AND
> PREREQUISITES REMAIN`. **The historical GCR-005 wording in this record is
> preserved and is not rewritten**, and the wording variance between GD-001 and
> AD-001 is likewise preserved. **Implementation conditions and prerequisites
> remain** — PAD-001 conditions C1 to C6 and prerequisites P1 to P8. **GCR-006
> remains OPEN.** **PUBLICATION REMAINS NOT AUTHORISED and the PUBLICATION HOLD
> REMAINS ACTIVE.** Decision:
> [`docs/Publication-Arrangement-Approval-Decision.md`](Publication-Arrangement-Approval-Decision.md).

---

## 1. Decision identification

| Field | Value |
|---|---|
| Project / reference implementation | Harrismith Fire Station — BIM management training / reference implementation |
| Candidate | **Harrismith Fire Station — Training Baseline 0.1 Candidate** |
| Candidate snapshot | `cc146a5f84b1ce20d2dfc73d878a77c58959c559` |
| Gate | **Gate C** |
| Decision date | **2026-08-01** |
| Decision function | **Training Baseline Approver** |
| Functional holder | **Training Implementation Owner** |
| Authority reference | **AG-001** — Training Baseline Approval Function |
| Decision | **PASS** |

No personal holder is recorded. The function operates under **TA-02** and is not
a real project appointment.

## 2. Gate definition

Gate C is the boundary between:

```
candidate development and validation
        ↓
formal Training Baseline approval consideration
```

**What Gate C means.** The candidate is sufficiently coherent, evidence-based,
bounded, transparent and usable to proceed to a **separate** Training Baseline
0.1 approval decision.

**What Gate C does not mean.** Gate C does **not**:

- approve Training Baseline 0.1;
- create contractual authority;
- create a professional appointment;
- approve design information;
- establish project publication / exchange authority;
- establish recipient acceptance authority;
- establish project standards;
- authorise Autodesk configuration changes;
- publish anything to Forma / ACC.

## 3. Decision basis

Completed sequence:

| Increment | Outcome |
|---|---|
| 6A / 6B / 6C | Cross-document validation, audit corrections, pre-candidate corrections |
| 7A | Candidate prepared — snapshot `98fa190d…` |
| 7B | Candidate review — PASS WITH FINDINGS; ready for live validation |
| 7C | Live-project validation — read-only connector and manual UI evidence |
| 7D | Observed-fact incorporation — snapshot `f5ce0100…` |
| 7E | Post-update candidate review — PASS |
| 7F | Gate C readiness assessment |
| 7G | Approval function established — **AG-001**; snapshot `cc146a5f…` |
| 7H | Post-decision candidate review |

**Increment 7F recommendation:** *RECOMMEND CONDITIONAL GATE C PASS.*

**Condition:** **GCR-001** — Training Baseline approval authority undefined.

**Resolution:** **AG-001** established through Increment 7G.

**Verification — Increment 7H confirmed:**

- **GCR-001 — SATISFIED;**
- **GCR-011 — READY FOR IMPLEMENTATION;**
- **READY FOR GATE C DECISION;**
- no authority bleed identified.

## 4. Gate criteria result

| ID | Criterion | Result |
|---|---|---|
| **GC-01** | Candidate identity controlled | **PASS** |
| **GC-02** | Scope and authority boundary clear | **PASS** |
| **GC-03** | Cross-document coherence passed | **PASS** |
| **GC-04** | Live validation completed | **PASS** |
| **GC-05** | Observed facts incorporated | **PASS** |
| **GC-06** | No unresolved contradiction | **PASS** |
| **GC-07** | Open matters visible and classified | **PASS** |
| **GC-08** | Public repository boundary clean | **PASS** |
| **GC-09** | Approval prerequisites identified | **PASS** — AG-001 established and verified through 7H |
| **GC-10** | Publication prerequisites identified | **PASS WITH PRE-PUBLICATION CONDITION** — GCR-005 |
| **GC-11** | First implementation cycle defined | **PASS WITH IMPLEMENTATION CONDITION** — GCR-006 |
| **GC-12** | Candidate suitable for limited training purpose | **PASS** |

**No criterion FAILS.** GC-10 records that publication prerequisites are
*identified* — **not that publication is ready**.

## 5. Decision

> ## **GATE C — PASS**

**Meaning.** The candidate may proceed to a separate Training Baseline approval
decision.

That approval decision has **not** been made.

## 6. Conditions carried forward

These are **not candidate defects**. They are transparent, correctly classified
matters carried past Gate C.

### Pre-publication condition

**GCR-005 — publication parameters undefined:**

- approved publication location;
- training publication owner;
- output format;
- version / status metadata;
- controlled upload procedure;
- post-upload verification;
- supersession / withdrawal route.

### Implementation condition

**GCR-006** — one governed coordination cycle must be exercised after approval,
as the first implementation workflow.

### Acceptable baseline limitations

Carried forward **without resolution**:

| Matter | Status |
|---|---|
| **UD-001** (GCR-007) | OBSERVED discrepancy + UNRESOLVED DECISION |
| Project publication / exchange authority | Unresolved |
| Recipient acceptance authority | Unresolved |
| Governance-change authority | Class-dependent |
| Individual role holders | TBD |
| Naming standard | Not established |
| Coordinates standard | Not established |
| Titleblocks standard | Not established |
| Templates / Authoring Resources | Not established |
| Retention approach | Unresolved |
| Coordination tolerances | Unresolved |
| Issue platform mapping | Unresolved |
| Detailed delivery formats and milestones | Unresolved |
| External-standards applicability | Unresolved |

**None of these is resolved by Gate C PASS.**

## 7. Publication hold

> **PUBLICATION HOLD REMAINS ACTIVE.**

**Gate C PASS does not lift it.**

Gate C PASS specifically does **not**:

- authorise publication;
- establish a publication owner;
- define the publication location;
- permit upload to Forma / ACC.

Publication remains dependent on the GCR-005 parameters and on a separate
explicit decision (BEP §13.5; AG-001 §8).

## 8. Candidate status

| | |
|---|---|
| Candidate status | **FOR REVIEW — NOT APPROVED** |

**Gate C PASS does not itself change that status.** The candidate becomes an
Approved Training Baseline only through a separate approval decision.

> **Subsequent status — 2026-08-01.** The status recorded above is the status
> **as at GD-001**, and it is retained as the historical record of this gate
> decision. The separate approval decision anticipated here was **subsequently**
> taken as **AD-001**, dated 2026-08-01, which approved Training Baseline 0.1
> **with conditions**. The current status is **APPROVED WITH CONDITIONS**, and
> **publication remains NOT AUTHORISED with the publication hold active**.
>
> AD-001 approved the governance basis assessed here — snapshot
> `cc146a5f84b1ce20d2dfc73d878a77c58959c559`, which AD-001 did **not** change —
> and left GD-001, its criteria and its reasoning untouched. **Gate C did not
> approve the baseline**; it authorised progression to the decision that did.
>
> AD-001 resolved none of the matters carried forward in sections 6 and 7 above:
> **GCR-005** and **GCR-006** remain open, **UD-001** remains unresolved,
> project publication / exchange authority and recipient acceptance authority
> remain unresolved, the four project standards remain **Not established**, and
> **no complete governed coordination cycle has been demonstrated**. See
> [`docs/Training-Baseline-0.1-Approval-Decision.md`](Training-Baseline-0.1-Approval-Decision.md).

## 9. Next decision

**Training Baseline 0.1 approval decision.**

Allowed outcomes under AG-001:

| APPROVE | APPROVE WITH CONDITIONS | DEFER | REJECT |
|---|---|---|---|

That decision must identify the candidate snapshot, decision function, date,
conditions, publication instruction or hold, and supersession / change-control
instruction.

## 10. Change and supersession

- **This Gate decision is tied to candidate snapshot
  `cc146a5f84b1ce20d2dfc73d878a77c58959c559`.**
- Substantive candidate changes after Gate C require **impact review**.
- A **materially changed candidate may require Gate C reconsideration**.
- The later approval decision **must identify the exact approved snapshot**.
- **No tag or release exists.** Snapshot identity is held in Git history alone.
