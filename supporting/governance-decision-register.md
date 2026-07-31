# Governance & Decision Register

## Document purpose and status

**Purpose.** The single consolidated controlled record of governance matters on
the Harrismith Fire Station training implementation: what was observed, what was
assumed, what was proposed, what was decided, what remains open, and what has
been implemented and verified.

Referenced by BEP section 12.13.

| Field | Value |
|---|---|
| Document status | **Controlled Draft** |
| Authority | Supporting management resource to the Harrismith BEP controlled draft |
| Approval | **Not approved** as part of BEP Training Baseline 0.1 |
| Supports | BEP section 12 — Governance, Change and Exceptions |

This is the intended consolidated governance register. Its current content is
part of the controlled draft system and carries no project authority.

**One register only.** Competing governance registers are not created (BEP
12.13).

## How this register is used

**Population rule.** Entries are created only from actual observations, actual
decisions, or explicitly declared assumptions. No entry is created to make the
register look complete. This register is **not** a copy of the BEP — the BEP
holds the proposed governance framework, and the register holds discrete matters
whose status or history needs to be traceable.

**Standing rule.** Known live-project discrepancies are recorded here and are
**not silently corrected** elsewhere in the documentation set. A discrepancy is
resolved only by an explicit, recorded decision.

**Four things kept separate.** Every entry distinguishes them, because
collapsing them is how an observation quietly becomes a requirement, or a
decision quietly becomes a fact:

| | |
|---|---|
| **Evidence** | What was observed, and where it came from |
| **Decision** | What was decided, by whom, and under what authority |
| **Implementation** | What was actually changed, in a document, process or platform |
| **Verification** | What was checked afterwards, and by whom |

An entry may hold evidence and no decision. An entry may hold a decision with no
implementation. Implementation is never assumed from a decision, and success is
never assumed from implementation (BEP 12.3, 12.9).

## Classification vocabulary

| Term | Meaning |
|---|---|
| **OBSERVED FACT** | Evidence from the project or environment |
| **TRAINING ASSUMPTION** | A deliberate construct adopted for the training workflow |
| **PROPOSED GOVERNANCE** | A rule or change under consideration, not yet approved |
| **APPROVED GOVERNANCE** | A governing decision taken through the approved decision route |
| **UNRESOLVED DECISION** | A matter requiring a future decision |
| **DEVIATION** | A deliberate, authorised departure from approved governance |
| **NON-CONFORMANCE** | An unintended failure to comply with approved governance |
| **APPROVED CHANGE** | An authorised alteration to the governed system |
| **SUPERSEDED DECISION** | An earlier decision replaced by a later approved decision, history retained |

**No NON-CONFORMANCE entry can exist yet.** A non-conformance requires approved
governance to fail against. No governance has been approved on this
implementation, so nothing can currently be in breach of it (BEP 12.2, 12.6).

---

## 1. Register summary

| ID | Type | Topic | Status | Decision owner |
|---|---|---|---|---|
| TA-01 | TRAINING ASSUMPTION | Post-appointment context | Adopted | Not established — TBD |
| TA-02 | TRAINING ASSUMPTION | Simulated role participation | Adopted | Not established — TBD |
| TA-03 | TRAINING ASSUMPTION | Training delivery organisation | Adopted | Not established — TBD |
| OF-001 | OBSERVED FACT | CDE root areas at discovery | Recorded | Not established — TBD |
| OF-002 | OBSERVED FACT | Populated production streams observed | Recorded | Not established — TBD |
| OF-003 | OBSERVED FACT | Common Files standards areas observed empty | Recorded — action required | Not established — TBD |
| OF-004 | OBSERVED FACT | Design Collaboration teams observed | Recorded | Not established — TBD |
| OF-005 | OBSERVED FACT | Coordination Space not observed configured | Recorded — action required | Not established — TBD |
| UD-001 | OBSERVED FACT + UNRESOLVED DECISION | Design Collaboration MEP / Structural team-space mapping | **Unresolved** | Not established — TBD |

No PROPOSED GOVERNANCE, APPROVED GOVERNANCE, APPROVED CHANGE, DEVIATION,
NON-CONFORMANCE or SUPERSEDED DECISION entries exist.

---

## 2. Training assumptions

Assumptions are explicit constructs adopted so the workflow can be exercised.
They are **not project facts**. An assumption is promoted to OBSERVED FACT only
by verification, and the promotion is recorded, never silent (BEP 2.6, 12.4).

### TA-01 — Post-appointment context

| Field | Value |
|---|---|
| Classification | TRAINING ASSUMPTION |
| Topic | Post-appointment context |
| Status | Adopted |
| Decision owner | Not established — TBD |

**Statement.** The implementation proceeds *as if* a post-appointment context
exists, so that a post-appointment-style BEP and BIM management workflow can be
exercised. **No real appointment exists and none is created.**

**Purpose.** Allows the BEP structure and the information-management workflow to
be developed and taught realistically.

**Evidence.** None — this is a declared construct, not an observation.

**Implementation / verification.** Not applicable. An assumption is not
implemented; it is applied and later tested against evidence.

**Related.** BEP 2.6, 1.2, 1.5. Withdrawn or superseded only through governance.

### TA-02 — Simulated role participation

| Field | Value |
|---|---|
| Classification | TRAINING ASSUMPTION |
| Topic | Simulated role participation |
| Status | Adopted |
| Decision owner | Not established — TBD |

**Statement.** Participants may exercise defined project and
information-management roles for training purposes. **Doing so creates no real
professional authority, contractual appointment, duty or liability.**

**Purpose.** Allows roles, responsibility and authorisation to be exercised
without implying real authority.

**Evidence.** None — declared construct.

**Related.** BEP 2.6, 1.3, 5.2, 9.8.

### TA-03 — Training delivery organisation

| Field | Value |
|---|---|
| Classification | TRAINING ASSUMPTION |
| Topic | Training delivery organisation |
| Status | Adopted |
| Decision owner | Not established — TBD |

**Statement.** The organisation and task-team structure defined in BEP Section 4
is a **training organisation model** used to exercise realistic multidisciplinary
interfaces. It does **not** constitute actual appointment of any consultant,
contractor, company or professional role holder.

**Purpose.** Allows organisation, task-team, discipline and
information-management responsibility interfaces to be exercised realistically.

**Evidence.** None — declared construct.

**Related.** BEP 2.6, 4.1, 4.2, 4.3.

---

## 3. Observed facts requiring governance attention

Recorded because each materially supports a future decision, implementation or
verification action. Observations that require no governance action are held in
the BEP rather than duplicated here.

All entries below describe the state observed at Discovery Gate A, at the level
inspected, at that time. **Observed state does not prove correctness** (BEP
12.3).

### OF-001 — CDE root areas at discovery

| Field | Value |
|---|---|
| Classification | OBSERVED FACT |
| Status | Recorded |
| Decision owner | Not established — TBD |

**Evidence.** The current CDE root was observed to contain Common Files, WIP,
Shared and Published areas (BEP 6.11).

**Governance consequence.** This is the as-found baseline against which an
intended CDE structure will be decided and, after any approved change, verified.

**Intended state.** Not defined. To be developed in the CDE Workflow & State
Strategy.

**Decision required.** Whether the as-found structure is adopted, amended or
replaced as intended governance.

**Implementation / verification.** None. Not applicable until a decision exists.

**Note.** Presence of an area named after a state does not establish that the
state model is implemented (BEP 6.3).

### OF-002 — Populated production streams observed

| Field | Value |
|---|---|
| Classification | OBSERVED FACT |
| Status | Recorded |
| Decision owner | Not established — TBD |

**Evidence.** Architecture was the only populated direct production stream
observed at the inspected CDE level (BEP 2.5).

**Governance consequence.** Recorded to prevent a specific misreading. **Absence
of observation is not observation of absence.** Other disciplines must **not** be
described as absent from the project, uncommitted or inactive on the basis of
this observation.

**Intended state.** Not applicable — this entry records an observation and a
standing caution, not a target.

**Decision required.** None at present. Re-observation may be appropriate as the
workflow develops.

**Implementation / verification.** None.

### OF-003 — Common Files standards areas observed empty

| Field | Value |
|---|---|
| Classification | OBSERVED FACT |
| Status | Recorded — action required |
| Decision owner | Not established — TBD |

**Evidence.** The Common Files areas for Naming Standards, Coordinates,
Titleblocks, Templates and Reference Information were observed empty during
discovery (BEP 2.5, 11.8).

**Governance consequence.** There is currently no published project naming
standard, coordinate standard, titleblock set or template set to reference. This
constrains BEP Section 11 and blocks parts of the delivery and coordination
workflow that depend on agreed conventions.

**Intended state.** Controlled project standards developed and approved through
governance, held in `standards/`.

**Decision required.** Scope, sequence and approval route for each standard.
Includes confirming whether Hartebeesthoek94 / Lo29 becomes the approved project
coordinate reference — currently **candidate context only** (BEP 11.5).

**Implementation / verification.** None. No standard exists to implement or
verify.

**Note.** Software defaults, office templates and local resources are not
project-approved resources (BEP 11.8).

### OF-004 — Design Collaboration teams observed

| Field | Value |
|---|---|
| Classification | OBSERVED FACT |
| Status | Recorded |
| Decision owner | Not established — TBD |

**Evidence.** The Design Collaboration teams observed at discovery were
Architecture, MEP Consultant and Structural (BEP 4.5).

**Governance consequence.** This is the as-found platform team configuration and
the context for UD-001. It is also the baseline against which any future intended
team mapping would be decided and verified.

**Intended state.** Not defined. See UD-001.

**Decision required.** See UD-001. Whether platform teams should map one-to-one
to task teams is itself an open question (BEP 4.5).

**Implementation / verification.** None.

**Note.** A Design Collaboration team is a platform construct — not an
organisation, discipline, task team or appointment. Membership confers no
authority (BEP 4.5, 6.4). No additional team is created by this record.

### OF-005 — Coordination Space not observed configured

| Field | Value |
|---|---|
| Classification | OBSERVED FACT |
| Status | Recorded — action required |
| Decision owner | Not established — TBD |

**Evidence.** No Design Collaboration Coordination Space was observed as
configured in the discovery state. A Navisworks coordination area was observed
with limited content (BEP 4.5, 8.4).

**Governance consequence.** The coordination environment required by BEP Section
8 is not established. A decision on the intended coordination environment is
needed before the coordination cycle can be operated as governed.

**Intended state.** Not defined. To be developed in the Coordination & Review
Strategy.

**Decision required.** The intended coordination environment and its
configuration.

**Implementation / verification.** None.

**Note.** Presence of a capability is not maturity, and existing configuration is
not correctness (BEP 2.4).

---

## 4. Unresolved decisions

### UD-001 — Design Collaboration MEP / Structural team-space mapping

| Field | Value |
|---|---|
| Classification | **OBSERVED FACT / UNRESOLVED DECISION** |
| Topic | Design Collaboration MEP / Structural team-space mapping |
| Raised | Discovery Gate A |
| Status | **Unresolved — open, carried forward, not corrected** |
| Decision owner | **Not established — TBD** |

**Evidence — observed condition.** The following team-space bindings were
observed:

| Observed Design Collaboration team | Observed bound WIP space |
|---|---|
| Architecture | Architecture WIP space |
| MEP Consultant | Structural-labelled WIP space |
| Structural | MEP-labelled WIP space |

The second and third bindings constitute an observed cross-binding / mapping
discrepancy.

**Current state.** Observed cross-binding. Recorded exactly as found.

**Intended state.** **NOT YET APPROVED.** No intended Design Collaboration
organisational or team-space mapping has been determined or approved, and none is
proposed in this entry.

**Decision required.** Determine and approve the intended Design Collaboration
organisational / team-space mapping **before** any corrective platform change.
Platform change follows a governance decision, not the reverse (BEP 12.1).

**Decision owner.** Not established. Escalation route and deciding function
remain TBD (BEP 8.12, 12.12).

**Status.** Unresolved.

**Implementation status.** None. No platform change has been made, proposed or
authorised.

**Verification status.** Not applicable until a decision and a change exist.

**Why this is not a non-conformance.** A non-conformance is an unintended failure
against **approved** governance. No intended mapping has been approved, so there
is nothing for the current configuration to fail against. Classifying this as a
non-conformance would assert governance that does not exist. If an intended
mapping is later approved and the live configuration still does not match it,
**that condition may then become a non-conformance** (BEP 12.2, 12.6).

**Handling.** This condition is recorded as observed. It is **not** to be
silently corrected in the BEP, in the Model / Information Responsibility Matrix,
in the CDE Workflow & State Strategy, or in any other document in this set.

**Related.** BEP 2.5, 4.5, 4.7, 6.4, 6.11, 12.6, 12.12. OF-004.

---

## 5. Proposed governance

*No discrete proposed-governance entries recorded.*

The proposed governance framework for this implementation is the BEP itself,
which is a controlled draft (BEP 1.2). It is not duplicated here. This section
records discrete governance proposals that need their own decision history —
for example a proposed change to an already-approved rule.

## 6. Approved governance and approved changes

*No approved governance recorded. No approved changes recorded.*

Nothing on this implementation has been approved. BEP Training Baseline 0.1 is
**not approved** (BEP 1.2, 9.10, 12.11).

## 7. Deviations

*No deviations recorded.*

A deviation is a knowingly permitted departure from **approved** governance. None
can exist until governance is approved (BEP 12.6).

## 8. Non-conformances

*No non-conformances recorded, and none can currently exist.*

A non-conformance is an unintended failure against **approved** governance. No
governance has been approved on this implementation. See UD-001 for why the
observed team-space discrepancy is **not** classified as a non-conformance.

## 9. Superseded decisions

*No superseded decisions recorded.*

When a decision is superseded, this section retains the original decision, its
status, the replacement decision, the effective point, and the reason or context
(BEP 12.10). History is not deleted because governance changed.

## 10. Register change log

| Date | Change | Increment |
|---|---|---|
| 2026-07-31 | Register populated as a controlled draft. TA-01, TA-02, TA-03 transcribed from BEP 2.6. OF-001 to OF-005 recorded. UD-001 detail recorded from the observed condition. | 3A |

**Note on histories.** This change log records *decision and register* history.
Git commit history records *source* history. They are complementary and not
interchangeable — a commit shows that wording changed; it does not show that a
decision was taken (BEP 9.11, 12.10).
