# Training Baseline 0.1 Candidate

## 1. Candidate identification

| Field | Value |
|---|---|
| Name | **Harrismith Fire Station — Training Baseline 0.1 Candidate** |
| Status | **FOR REVIEW — NOT APPROVED** |
| Type | Controlled review snapshot of the management-document system |

**Purpose.** To freeze the validated management-document system for candidate
review and subsequent live-project validation, **before** any baseline approval.

**A candidate is not a baseline.** Preparing this candidate approves nothing,
passes no gate, and changes no authority.

## 2. Validated source state

| | |
|---|---|
| Validated pre-candidate source commit | `9265a12d540a269df6e31bfb8ea035a607560622` |
| Candidate snapshot commit | The Git commit created by Increment 7A, which introduces this manifest and the candidate status transitions |

The validated source commit is the state that passed cross-document validation
(Increment 6A), the audit corrective pass (6B) and the pre-candidate corrective
pass (6C), and that passed the read-only freeze pre-flight at the start of this
increment.

The candidate snapshot is the commit that carries this manifest. Its hash is
created by Git and is therefore not recorded in advance here; it is identifiable
as the commit titled *"docs: prepare Training Baseline 0.1 candidate"*.

## 3. Candidate scope

### 3.1 Core governance documents

| # | Document |
|---|---|
| 1 | `bep/Harrismith-Fire-Station-BEP.md` |
| 2 | `supporting/information-management-responsibility-matrix.md` |
| 3 | `supporting/model-information-responsibility-matrix.md` |
| 4 | `supporting/information-delivery-schedule.md` |
| 5 | `supporting/cde-workflow-state-strategy.md` |
| 6 | `supporting/coordination-review-strategy.md` |
| 7 | `supporting/governance-decision-register.md` |

### 3.2 Companion controlled documents

| # | Document | Retains |
|---|---|---|
| 8 | `working/README.md` — Working Process | Participation mechanism. **Not a governance authority** |
| 9 | `guidance/BIM-Delivery-Guide.md` — BIM Delivery Guide | Educational guidance. **Authority: None** |

The companion documents are included so the set can be reviewed as a whole.
**Neither becomes governing by being included in the candidate.**

### 3.3 Outside the candidate baseline scope

| Item | Reason |
|---|---|
| `working/bep-working-register.md` | Operational working record, not a baseline document |
| `working/workshops/workshop-template.md` | Operational template, not a baseline document |
| `standards/naming/` | Project standard **not established** |
| `standards/coordinates/` | Project standard **not established** |
| `standards/titleblocks/` | Project standard **not established** |
| `standards/templates/` | Project standard **not established** |

**These exclusions are deliberate and must remain visible.** The project
standards are absent because they do not exist, not because they were
overlooked.

## 4. Authority boundary

> **FOR REVIEW ≠ APPROVED TRAINING BASELINE.**

Candidate preparation creates no:

- contractual obligation;
- professional appointment;
- publication authority;
- recipient acceptance authority;
- platform-change authority.

Each document in the candidate retains the authority it already had. A
supporting resource does not outrank the BEP by being listed here, and the
companion documents acquire no governing status.

## 5. Validation basis

| Check | Result |
|---|---|
| Cross-document consistency audit (6A) | Completed — PASS WITH FINDINGS |
| Architecture coherence | Confirmed; no BLOCKER |
| Audit corrective pass (6B) | Completed |
| Pre-candidate corrective pass (6C) | Completed |
| Stem-based stale-language sweep | Completed at 6C and re-run at candidate pre-flight; zero stale occurrences |
| Cross-references and identifiers | Validated; all internal paths and BEP section references resolve |
| Public-repository boundary | Checked; no credentials, personal data, private identifiers or machine paths |

Full audit detail is not reproduced here.

## 6. Known unresolved matters

Unresolved governance is recorded in
`supporting/governance-decision-register.md`.

**Nothing becomes resolved by the preparation of this candidate.** Every open
matter remains open through candidate review and must be resolved through the
governance route, not by the act of freezing a review snapshot.

Examples — not a complete list, and not duplicated from the register:

- **UD-001** — MEP / Structural Design Collaboration team-space mapping;
- publication / exchange authority;
- recipient acceptance authority;
- role holders;
- project standards;
- retention approach;
- coordination configuration and tolerances;
- delivery requirements.

## 7. Candidate review objectives

Review should determine whether:

- the candidate documents remain coherent as a set;
- responsibilities are usable and understandable by the people who must perform
  them;
- the delivery and CDE workflows can be demonstrated;
- unresolved matters requiring decision **before** approval are visible and
  correctly classified;
- the live Autodesk configuration aligns with, or differs from, the governed
  proposal;
- corrective action is required before Gate C.

## 8. Next stage

```
Candidate
  → candidate review
  → live-project validation
  → findings / governance decisions
  → corrections if required
  → Gate C assessment
  → possible Training Baseline 0.1 approval
```

Each step is a separate decision. Reaching one does not imply the next.

## 9. Publication boundary

**This candidate is not an issued or approved project BEP.**

No publication to Autodesk Forma or ACC occurs in Increment 7A. No live platform
configuration is changed, and no external system is accessed.

Git remains the controlled authoring and history source. The controlled
publication route is unchanged:

```
approved source / baseline
  → generated / project-facing artefact
  → controlled manual publication
  → Forma / Data Management CDE
```

Publication is manual and human-performed, and follows baseline approval — which
has not occurred.
