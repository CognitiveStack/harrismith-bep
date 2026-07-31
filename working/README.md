# Working Process

## Document purpose and status

**Purpose.** Defines how participants contribute questions, problems,
proposals, improvements and lessons into the BIM-management system **without
directly modifying authoritative governance**.

It is the participation and discussion layer between participant learning and
controlled governance.

| Field | Value |
|---|---|
| Document status | **Controlled Draft** |
| Authority | Supports development and operation of the Harrismith BEP training system |
| Approval | **Not approved** as part of BEP Training Baseline 0.1 |
| Supports | BEP section 1.4 |

**This process is not:**

- approved as part of Training Baseline 0.1;
- the authoritative governance decision record — that is
  `supporting/governance-decision-register.md`;
- an alternative BEP;
- an informal mechanism for bypassing approved governance.

## The core model

```
BIM Delivery Guide          → helps a participant understand
Working Process             → allows a participant to contribute and discuss
Governance process          → determines whether governance changes
BEP / supporting resource   → the controlled governing result
   / project standard
```

**A participant may propose a change. A participant does not obtain authority
to change the BEP by making the proposal.**

## Status of material in `working/`

Everything under `working/` is **working thinking**: contributions under
consideration, discussion notes, options, and reasoning in progress.

Working material:

- carries no governance authority of any kind;
- may contain unverified, provisional or later-rejected content;
- is never published to the CDE;
- is not a source of governance. Governance lives in `bep/` and `supporting/`.

---

## WP1 — Purpose and participation

The Working Process provides an accessible route for project participants to:

- ask questions;
- identify problems;
- propose improvements;
- request clarification;
- raise training needs;
- request controlled exceptions;
- contribute lessons learned.

**Everyone participating in the training workflow may contribute.** The route is
deliberately low-friction: a participant who sees a problem should be able to
record it without first knowing who owns it or which document it affects.

**Contribution rights are not governance authority.** Being able to raise
anything is not the same as being able to decide anything. The two are separated
on purpose — an easy intake route only works if it cannot accidentally change the
rules.

No participant names are recorded. Contributions are attributed to **roles and
functions**, all of which remain TBD (BEP 5.3–5.9).

## WP2 — Contribution types

Exactly seven types:

| Type | Meaning |
|---|---|
| **QUESTION** | Request for explanation or guidance, where governance change may not be required |
| **PROPOSAL** | Suggested new or changed process, standard, responsibility, configuration or working method |
| **PROBLEM** | Observed difficulty, failure, inconsistency or blocker |
| **CLARIFICATION** | Request to remove ambiguity in an existing rule, process or resource |
| **IMPROVEMENT** | Suggested refinement making an established process clearer, more efficient or more reliable |
| **TRAINING NEED** | Gap in understanding or capability requiring explanation, demonstration, practice or Guide content |
| **EXCEPTION REQUEST** | Request for a deliberate temporary or permanent departure from approved governance |

**An EXCEPTION REQUEST is not an authorised deviation.** It is a request. It
becomes a deviation only through a governance decision — see *Relationship to
exceptions* below.

## WP3 — Contribution intake

A contribution is recorded in `bep-working-register.md` with:

| Field | Note |
|---|---|
| Working ID | See below |
| Contribution Type | One of the seven in WP2 |
| Topic | Short subject |
| Raised By Role / Function | **Role, not person** |
| Date Raised | Only where actually known. Not invented |
| Description | What was observed or asked |
| Why It Matters | The consequence if unaddressed |
| Affected Process / Document / Platform | Where it lands |
| Suggested Outcome | Optional |
| Initial Status | Normally NEW |
| Related Issue / Decision / Resource | Where already known |

**Working IDs** use a simple pattern — `WP-001`, `WP-002`, and so on.

**A Working ID is a working-process identifier.** It is **not** a Governance
Register decision ID, **not** a Forma Issue ID, and **not** a contractual
document number. A matter may carry all three, and they are not
interchangeable.

## WP4 — Triage and ownership

First routing, by the nature of the matter:

| Matter | Triaged by |
|---|---|
| Governance, BEP, responsibility, standard or CDE-rule | **BIM Manager** function |
| Multidisciplinary coordination process | **BIM Coordinator** function, for operational coordination content |
| Discipline technical or design matter | Relevant **Task-Team Lead** / discipline function |
| Platform configuration | See below |
| Training or understanding | May route toward onboarding, demonstration or BIM Delivery Guide content |

**Platform configuration matters are triaged in two steps.** First determine
whether the matter is *a governance question* or *implementation of
already-approved governance*. Only the second is an administration task.

**CDE Administration does not invent governance because a matter concerns
software configuration.** The subject being technical does not make the decision
technical (BEP 5.9, 6.9).

**No role holder is appointed here.** Triage functions are functions; every
holder remains TBD.

## WP5 — Discussion and workshop

A contribution may require clarification, evidence gathering, focused
discussion, a workshop, technical input, platform investigation, or review of
existing governance.

**Discussion is exploratory. It does not alter approved governance.**

Where a workshop is held, record only what is useful:

- Working ID;
- topic;
- participating functions;
- evidence considered;
- options considered;
- conclusions and proposals;
- decisions required;
- actions;
- links to related controlled records.

A template is available at `workshops/workshop-template.md`.

**A workshop is not a parallel decision authority.** Its output is a proposal
and a record of reasoning. Where the matter has governance significance, the
decision is taken through the governance route and recorded in the Governance &
Decision Register.

## WP6 — Decision path

```
contribution
  → triage
  → discussion / evidence
  → proposal where required
  → decision required?
  → decision
  → approved / rejected / deferred
  → Governance & Decision Register where governance significance requires it
```

Three routes, distinguished:

| Contribution | Route |
|---|---|
| **QUESTION** or **TRAINING NEED** resolved without governance change | May close in the Working Process |
| **PROPOSAL** requiring governance change | **Must** enter the governed decision route |
| **PROBLEM** exposing a non-conformance, deviation or unresolved governance matter | **Must** be classified through the Governance & Decision Register, as applicable |

**A Working Register status of APPROVED does not create APPROVED GOVERNANCE.**
It records that this process reached an approved outcome or route. The
authoritative governance decision belongs in
`supporting/governance-decision-register.md`, and nowhere else.

## WP7 — Implementation path

An approved governance decision may require change to the BEP, a supporting
management resource, a project standard, the BIM Delivery Guide, CDE or platform
configuration, a working procedure, or training material.

```
approved decision
  → identify affected controlled artefacts
  → authorised implementation
  → update
  → communicate
  → verify
  → close / baseline as applicable
```

**An approved proposal in the Working Process does not authorise external
platform change.** Implementation follows the authority defined by the
governance system, and platform change follows an approved governance decision —
not a Working Register entry (BEP 12.1, 12.8).

## WP8 — Verification and closure

A contribution closes only when its required outcome is **complete**.

| Type | Closes when |
|---|---|
| **QUESTION** | Answered, and no further decision or action is required |
| **TRAINING NEED** | The agreed training or onboarding action is complete and, where appropriate, its effectiveness has been checked |
| **Governance change** | Decision → implementation → verification are complete, as applicable |
| **Platform change** | The approved configuration change is implemented **and verified against intended governance** |

**A decision made is not a change completed.** Closing at the decision leaves an
approved rule that nothing implements — the most common way a governance system
becomes a description of work nobody does (BEP 12.9).

## WP9 — Status model

| Status | Meaning |
|---|---|
| **NEW** | Recorded, not yet triaged |
| **UNDER REVIEW** | Being clarified, investigated or discussed |
| **DECISION REQUIRED** | Needs a decision through the governance route |
| **APPROVED** | The Working Process has a recorded approved outcome or route |
| **REJECTED** | Not proceeding; reason recorded |
| **DEFERRED** | Carried forward; reason recorded |
| **IMPLEMENTING** | Approved change being applied |
| **VERIFICATION REQUIRED** | Applied, awaiting verification |
| **CLOSED** | Required outcome complete |

**APPROVED here does not create APPROVED GOVERNANCE.** Where the matter changes
governance, the authoritative decision must be recorded in the Governance &
Decision Register. A matter can be APPROVED in this register and still have no
approved governance behind it until that happens.

**Stages may be skipped where they do not apply.** A question needs no
artificial governance steps:

```
QUESTION:  NEW → UNDER REVIEW → CLOSED
```

## WP10 — Tooling and collaboration channels

Channel principles, not prescribed software:

| Channel | Role |
|---|---|
| **Working Register** | Primary record for contributions entering this process |
| **Workshop / discussion notes** | Supporting evidence where deeper discussion occurs |
| **Forma / project Issues** | Operational project and model actions requiring assignment, tracking, resolution and verification |
| **Governance & Decision Register** | Authoritative decision history for governance-significant matters |
| **Git** | Authoritative source and history for controlled repository content |
| **Email / chat / meeting** | May initiate or discuss a contribution |

Three boundaries:

- **An operational Issue is not a governance decision.**
- **A Git commit is not governance approval.** It records that content changed,
  not that anything was decided (BEP 9.11).
- **Casual communication is not the governance system.** A conversation may start
  a contribution; material decisions and actions must move into the appropriate
  controlled record. A decision nobody can produce afterwards did not happen.

## WP11 — Working records

`bep-working-register.md` is the lightweight incoming Working Register.

It records contributions moving through this process. **It is not the
authoritative governance decision register**, and it is not an Issue database —
operational actions requiring assignment and tracking belong in governed Issues
(WP10).

The register carries no active entries. It holds one clearly labelled
illustrative example, which is not a project record.

## WP12 — Relationship to BEP baselining

```
current baseline / controlled draft
  → participant experience
  → Working Process contribution
  → governance decision
  → controlled change
  → verification
  → next baseline candidate
  → review
  → authorised baseline
  → controlled publication
```

**Participants do not directly mutate the issued BEP.** A Working Process
contribution may eventually cause a BEP change. **It is not itself that change.**

Progressive baselines run 0.1, 0.2 … 1.0 as already defined in BEP 12.11.
**Baseline 0.1 is not approved.**

Publication remains manual and human-performed:

```
local Git authoring source
  → review
  → approved baseline
  → manual controlled publication to Autodesk Forma / Data Management
```

See `README.md` sections 2.1 and 4.

---

## Relationship to the BIM Delivery Guide

| Document | Nature | Records / explains |
|---|---|---|
| **BIM Delivery Guide** | Educational | Why the workflow exists; what the terminology means; what each role generally does; how to get started; practical examples |
| **Working Process** | Participatory | Questions, proposals, problems, improvements, training needs, exception requests |
| **BEP** | Governing | The controlled agreement, once baselined |

**Guide ≠ Working Process ≠ BEP.**

The BIM Delivery Guide is **separately controlled** and declares its own current
status and authority. A TRAINING NEED raised here may inform future Guide
content, but the Working Process **does not govern or approve the Guide**.

## Relationship to Issues and the Governance Register

Three records, three purposes:

| Record | Holds |
|---|---|
| **Working Register** | The incoming participant contribution |
| **Forma / project Issue** | The operational coordination or model action, where governed |
| **Governance & Decision Register** | The governance decision |

One matter may link across all three:

```
Working contribution
  → investigation
  → operational Issue discovered
  → governance decision required
  → Governance Register
  → approved change
  → operational implementation
  → verification
```

**The same function is not duplicated across three records.** Each holds its own
part: the contribution, the operational action, the decision. Recording the same
decision in more than one place produces two versions of it eventually.

## Relationship to exceptions

An **EXCEPTION REQUEST** is an incoming contribution type. It is **not yet a
deviation**.

```
exception request
  → assessment
  → governance decision
```

| Outcome | Classification |
|---|---|
| Deliberately authorised departure from approved governance | **DEVIATION** |
| Unintended failure against approved governance | **NON-CONFORMANCE** |

Both terms carry their BEP Section 12 meanings. Note that **neither can exist
until governance has been approved** — a non-conformance requires something to
conform to (BEP 12.2, 12.6).

## No direct policy editing

**The Working Process is not a collaborative free-edit layer for authoritative
governance.**

Participants may contribute freely. Controlled governance changes require:

```
decision → authorisation → implementation → verification
```

Contributing is open. Deciding is not. That asymmetry is the point of having a
separate participation layer at all.

## Distinctions preserved

| | |
|---|---|
| Evidence | ≠ decision |
| Proposal | ≠ approval |
| Decision | ≠ implementation |
| Implementation | ≠ verification |
| Issue | ≠ governance decision |
| Working Register | ≠ Governance Register |
| Git history | ≠ approval |
