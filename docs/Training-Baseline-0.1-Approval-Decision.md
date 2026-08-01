# Training Baseline 0.1 — Approval Decision

| Field | Value |
|---|---|
| Document status | **Controlled Approval Decision** |
| Decision ID | **AD-001** |
| Decision status | **APPROVED WITH CONDITIONS** |
| Authority | **Training Baseline Approver**, exercised by the Training Implementation Owner under **AG-001** |

> **This decision approves the Training Baseline 0.1 governance baseline, with
> conditions, for its stated training and reference-implementation purpose.**

> **PUBLICATION REMAINS NOT AUTHORISED — PUBLICATION HOLD ACTIVE.**

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
| Decision ID | **AD-001** |
| Decision title | **Training Baseline 0.1 Approval Decision** |
| Project / reference implementation | Harrismith Fire Station — BIM management training / reference implementation |
| Decision subject | **Harrismith Fire Station — Training Baseline 0.1** — the governed management-document system listed in section 4 |
| Decision date | **2026-08-01** |
| Decision function | **Training Baseline Approver** |
| Functional holder | **Training Implementation Owner** |
| Authority basis | **AG-001** — Training Baseline Approval Function (**APPROVED GOVERNANCE**) |
| Gate decision relied upon | **GD-001** — **GATE C — PASS**, 2026-08-01 |
| Gate-assessed candidate snapshot | `cc146a5f84b1ce20d2dfc73d878a77c58959c559` |
| Pre-decision repository state | `707b966f5eb0d0e3975a80e9a939d381bc6f3297` |
| Decision outcome | **APPROVE WITH CONDITIONS** |

No personal holder is recorded. The function operates under **TA-02** —
simulated role participation — and is **not** a real project appointment.

### 1.1 Snapshot identity

The approval must not be read as approving a different body of content from the
one Gate C assessed.

| Snapshot | Role |
|---|---|
| `cc146a5f84b1ce20d2dfc73d878a77c58959c559` | **The governance basis assessed at Gate C** under GD-001 |
| `86241b07d30bf536207c9ac6e584a49f3cb6db68` | Increment 7I-A — companion-document factual status correction |
| `707b966f5eb0d0e3975a80e9a939d381bc6f3297` | Increment 7I-B — companion-document factual status correction; the pre-decision repository state |

**Increments 7I-A and 7I-B were narrowly scoped status corrections** to the
non-authoritative BIM Delivery Guide. They corrected two statements that had
become factually stale — that Gate C had not passed, and that live-project
validation had not been performed. **They changed no governance content and no
part of the substantive governance basis assessed by Gate C.**

The approved baseline is therefore the governance basis assessed at
`cc146a5f…`, carried forward unchanged through `86241b0…` and `707b966…`, and
materialised in the repository by the Increment 7J commit titled *"docs:
approve Training Baseline 0.1 with conditions"*, which records this decision.

**Approval attaches to that governance content — not to the act of committing
it.** A commit shows that wording changed; it does not show that a decision was
taken (BEP 9.11, 12.10).

## 2. Decision outcome

> ## **TRAINING BASELINE 0.1 — APPROVED WITH CONDITIONS**

Training Baseline 0.1 is approved as the **governed training and
reference-implementation baseline** for the Harrismith Fire Station
implementation, **subject to** the conditions in section 6 and the unresolved
matters in section 8, all of which **remain active**.

**This baseline is not unconditionally approved.** The status is
**APPROVED WITH CONDITIONS**, and it must be stated that way wherever the
current baseline status is recorded. Recording it as merely *APPROVED* would
obscure the conditions and misrepresent this decision.

## 3. Meaning of APPROVED WITH CONDITIONS

**APPROVED WITH CONDITIONS** means the Training Baseline 0.1 governance
baseline is approved for its stated training and reference-implementation
purpose, while the recorded conditions and unresolved matters remain active.

It does **not** mean any of the following:

- approved for CDE publication;
- approved for external information exchange;
- accepted by a recipient;
- delivered to an appointing party;
- implemented as a complete live workflow;
- verified through a complete governed coordination cycle;
- approved as final project delivery information.

**`Published`, `Delivered`, `Received` and `Accepted` are not synonyms for
approved**, and none of them is conferred here. Those terms retain the meanings
given in the BEP and the CDE Workflow & State Strategy.

## 4. What is approved

The governance baseline comprises the core governance documents frozen as the
Training Baseline 0.1 Candidate and assessed at Gate C:

| # | Document |
|---|---|
| 1 | `bep/Harrismith-Fire-Station-BEP.md` |
| 2 | `supporting/information-management-responsibility-matrix.md` |
| 3 | `supporting/model-information-responsibility-matrix.md` |
| 4 | `supporting/information-delivery-schedule.md` |
| 5 | `supporting/cde-workflow-state-strategy.md` |
| 6 | `supporting/coordination-review-strategy.md` |
| 7 | `supporting/governance-decision-register.md` |

### 4.1 What is not approved by being adjacent to it

| Item | Effect of AD-001 |
|---|---|
| `working/README.md` — Working Process | **Companion. Authority: None.** Not approved as governance by AD-001 |
| `guidance/BIM-Delivery-Guide.md` — BIM Delivery Guide | **Companion. Authority: None.** Not approved as governance by AD-001 |
| `standards/naming/` | **Not established** |
| `standards/coordinates/` | **Not established** |
| `standards/titleblocks/` | **Not established** |
| `standards/templates/` | **Not established** |
| `working/bep-working-register.md` | Operational working record — outside the baseline |
| `working/workshops/workshop-template.md` | Operational template — outside the baseline |

**The companion documents do not become governing by being approved-adjacent.**
They retain the authority they already had, which is none. AD-001 does not
convert guidance into governance.

**The project standards are absent because they do not exist**, not because they
were overlooked, and AD-001 does not establish them.

## 5. Decision reasoning

| Basis | Record |
|---|---|
| Cross-document validation, audit and pre-candidate correction | Increments 6A, 6B, 6C |
| Candidate prepared and reviewed | Increments 7A, 7B |
| Live-project validation — read-only connector and manual UI evidence | Increment 7C — `docs/Increment-7C-Live-Validation-Record.md` |
| Observed facts incorporated | Increment 7D |
| Post-update candidate review — **PASS** | Increment 7E |
| Gate C readiness assessment | Increment 7F |
| Approval function established — **AG-001** | Increment 7G |
| Approval function verified — **READY FOR GATE C DECISION** | Increment 7H |
| **Gate C — PASS**, **GD-001** | Increment 7I |
| Companion status corrections | Increments 7I-A, 7I-B |

**Gate C passage enabled this approval decision but did not itself approve the
baseline.** GD-001 authorised progression to a separate approval decision and
nothing more. That separate decision is AD-001, and it is recorded here.

**The gate criteria are not re-opened by this decision.** GC-01 to GC-12 were
assessed under GD-001. AD-001 relies on that assessment; it does not repeat,
revise or reconsider it.

Approval is given **with conditions** because the matters in sections 6 and 8
remain open. They were visible, correctly classified and carried forward at Gate
C. **Approving the baseline does not close them**, and this decision approves a
governance baseline that openly records what it has not resolved.

## 6. Conditions carried by AD-001

All six conditions are **active** on and after this decision.

### Condition 1 — Publication hold

> **PUBLICATION REMAINS NOT AUTHORISED. THE PUBLICATION HOLD REMAINS ACTIVE.**

Approval of Training Baseline 0.1 is **not** approval to publish, exchange,
issue, deliver or distribute information through the CDE or any external system.
**AD-001 does not lift the publication hold** and does not authorise upload to
Autodesk Forma or ACC.

### Condition 2 — GCR-005 — pre-publication

**GCR-005 remains open as a pre-publication condition.** The following remain
**undefined** and must be resolved before publication can be authorised:

- publication location;
- publication owner;
- publication format;
- required metadata;
- upload procedure;
- post-upload verification;
- supersession or withdrawal route.

**AD-001 defines none of them.**

### Condition 3 — GCR-006 — post-approval implementation

**GCR-006 remains open as a post-approval implementation condition.** One
complete governed coordination cycle **must still be exercised and evidenced**.

**Approval of the baseline is not evidence that this cycle has been completed.**
Increment 7C recorded the observed coordination activity as *PARTIALLY
TRACEABLE / NOT YET DEMONSTRATED AS A COMPLETE CYCLE*, and that remains the
position.

### Condition 4 — UD-001

**UD-001 remains an OBSERVED discrepancy and an UNRESOLVED DECISION** —
Design Collaboration MEP / Structural team-space mapping.

**AD-001 does not resolve, close, reinterpret or suppress UD-001.** The observed
condition remains recorded as observed, and the intended state remains
undecided.

### Condition 5 — Authority gaps

The following remain **unresolved**, and **AD-001 assigns neither**:

- project publication / exchange authority;
- recipient acceptance authority.

### Condition 6 — Project standards

| Standard | Status |
|---|---|
| Naming | **Not established** |
| Coordinates | **Not established** |
| Titleblocks | **Not established** |
| Templates / Authoring Resources | **Not established** |

**Approval of Training Baseline 0.1 must not be represented as establishing any
project standard.**

## 7. Explicit non-effects

AD-001 does **not**:

- authorise CDE publication, information exchange, issue, delivery or external
  distribution;
- lift or vary the publication hold;
- resolve **GCR-005** or define any publication parameter;
- complete, simulate or evidence **GCR-006**;
- resolve **UD-001**;
- establish project publication / exchange authority;
- establish recipient acceptance authority;
- establish any project standard;
- prove the complete governed coordination workflow;
- create contractual authority or obligation;
- create a professional appointment;
- approve design information;
- authorise Autodesk configuration changes;
- confer governing status on the companion documents;
- create a tag, release or publication package;
- resolve any other recorded authority or standards gap.

## 8. Unresolved matters carried past approval

Carried forward **without resolution**, as recorded at Gate C:

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

**None of these is resolved by AD-001.** An approved baseline that records what
it has not resolved is more honest than one that quietly fills the gaps.

## 9. Mandatory distinctions preserved

This decision changes none of the distinctions the governance system depends on:

| Distinction | Meaning |
|---|---|
| **Observed state is not intended governance** | What the live project does is evidence, not a rule |
| **Permission is not authority** | Being able to perform an action in the software says nothing about who was authorised to decide it |
| **Team is not organisation, task team, discipline or appointment** | A platform team is a platform construct |
| **Published is not Delivered, Received or Accepted** | Each is a separate state with a separate decision behind it |
| **Evidence is not decision, implementation or verification** | Four separate things, never collapsed |
| **Candidate approval is not CDE publication** | Approving the baseline authorises no upload, issue or exchange |
| **Absence of observation is not observation of absence** | Not seeing something is not evidence that it does not exist |

And specifically:

- **Gate C passage enabled the approval decision but did not itself approve the
  baseline;**
- **AD-001 approves the Training Baseline 0.1 governance baseline with
  conditions;**
- **AD-001 does not authorise publication;**
- **AD-001 does not prove the complete governed coordination workflow;**
- **AD-001 does not resolve any recorded authority or standards gap.**

## 10. Approval effect

On this decision:

| | Before AD-001 | After AD-001 |
|---|---|---|
| Training Baseline 0.1 | **FOR REVIEW — NOT APPROVED** | **APPROVED WITH CONDITIONS** |
| Core governance documents | Candidate for review | Approved baseline content, conditions active |
| Publication | **Not authorised** | **Not authorised — unchanged** |
| Publication hold | Active | **Active — unchanged** |
| GCR-005 | Open | **Open — unchanged** |
| GCR-006 | Open | **Open — unchanged** |
| UD-001 | Unresolved | **Unresolved — unchanged** |
| Publication / exchange authority | Unresolved | **Unresolved — unchanged** |
| Recipient acceptance authority | Unresolved | **Unresolved — unchanged** |
| Project standards | Not established | **Not established — unchanged** |
| Companion documents | Authority: None | **Authority: None — unchanged** |

**Only the baseline status changes.** Everything else that was open remains
open, in the same classification it already carried.

### 10.1 Effect on non-conformance

Approved governance now exists as a baseline. A **NON-CONFORMANCE** — an
unintended failure to comply with approved governance — therefore becomes
possible in principle where the approved baseline applies.

**No non-conformance is recorded by this decision**, and none is asserted. The
point is only that the classification is no longer structurally impossible.

## 11. Implementation and verification requirements

**Approval is not implementation, and implementation is not verification**
(BEP 12.3, 12.9).

| Requirement | Status |
|---|---|
| Record AD-001 in the Governance & Decision Register | Required by this decision |
| Update the baseline status wherever a current status is stated | Required by this decision |
| Preserve historical records describing the earlier candidate state | Required by this decision |
| **GCR-006** — exercise and evidence one complete governed coordination cycle | **Outstanding** |
| **GCR-005** — define publication parameters before any publication decision | **Outstanding** |
| Verification of the approved baseline in use | **Not performed** |

**No implementation assignment is created by this decision.** No TA-04 or
equivalent is established, and no Phase 8 implementation content is authorised
by AD-001.

## 12. Publication boundary

> **PUBLICATION REMAINS NOT AUTHORISED — PUBLICATION HOLD ACTIVE.**

Git remains the controlled authoring and history source. Publication to the CDE
remains a **separate, later, explicit decision**, dependent on the GCR-005
parameters (BEP §13.5; AG-001 §8; GD-001 §7).

AD-001 does **not** begin Publication Planning. It defines no publication
location, nominates no publication owner, selects no format or metadata, defines
no upload procedure, performs no post-upload verification, and defines no
supersession or withdrawal route.

**No external system was accessed in taking this decision.** No Autodesk item
was created or modified, no file was uploaded, and no tag or release was
created.

## 13. Change and supersession

- **This approval is tied to the governance basis assessed at
  `cc146a5f84b1ce20d2dfc73d878a77c58959c559`**, carried forward unchanged
  through `86241b0…` and `707b966…`.
- Substantive changes to the approved baseline require **change control**, not
  silent amendment (BEP 12.11).
- A materially changed baseline may require a **new baseline** — 0.2, 0.3 … 1.0
  — rather than in-place editing of an approved one.
- Superseded decisions are retained, not deleted (BEP 12.10).
- **No tag or release exists.** Snapshot identity is held in Git history alone.

## 14. Final decision statement

> ## **TRAINING BASELINE 0.1 — APPROVED WITH CONDITIONS**
>
> Approved by the **Training Baseline Approver**, exercised by the **Training
> Implementation Owner** under **AG-001**, on **2026-08-01**, as **AD-001**,
> following **GD-001 — GATE C PASS**.
>
> Conditions 1 to 6 of section 6 **remain active**.
>
> ## **PUBLICATION REMAINS NOT AUTHORISED — PUBLICATION HOLD ACTIVE.**
