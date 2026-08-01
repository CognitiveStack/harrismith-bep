# Governance & Decision Register

## Document purpose and status

**Purpose.** The single consolidated controlled record of governance matters on
the Harrismith Fire Station training implementation: what was observed, what was
assumed, what was proposed, what was decided, what remains open, and what has
been implemented and verified.

Referenced by BEP section 12.13.

| Field | Value |
|---|---|
| Document status | **APPROVED WITH CONDITIONS — Training Baseline 0.1** |
| Authority | Supporting management resource under the Harrismith BEP framework |
| Approval | **Approved with conditions** through **AD-001**, 2026-08-01. Conditions remain active; **publication remains NOT AUTHORISED** |
| Supports | BEP section 12 — Governance, Change and Exceptions |

This is the consolidated governance register. It is approved with conditions as
part of Training Baseline 0.1 for the training and reference-implementation
purpose stated in AD-001; its status is declared in the table above. **Approval
of the baseline confers no project publication, exchange or acceptance
authority.**

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

**No NON-CONFORMANCE entry is recorded.** A non-conformance requires approved
governance to fail against. Training Baseline 0.1 is approved with conditions
through **AD-001**, so the classification is no longer structurally impossible
where the approved baseline applies — but **none is asserted or recorded**
(BEP 12.2, 12.6).

---

## 1. Register summary

| ID | Type | Topic | Status | Decision owner |
|---|---|---|---|---|
| AG-001 | **APPROVED GOVERNANCE** | Training Baseline Approval Function | Approved — implemented and **verified** | Training Baseline Approver |
| AG-002 | **APPROVED GOVERNANCE** | Training CDE Governance Approver Function | **FUNCTION ESTABLISHED — OF-001 DECISION NOT YET TAKEN** — 2026-08-01 | Training CDE Governance Approver |
| GD-001 | **CONTROLLED GATE DECISION** | Training Baseline 0.1 — Gate C Decision | **PASS** — 2026-08-01 | Training Baseline Approver |
| AD-001 | **APPROVED GOVERNANCE** | Training Baseline 0.1 — Approval Decision | **APPROVED WITH CONDITIONS** — 2026-08-01 | Training Baseline Approver |
| ROA-001 | **CONTROLLED READ-ONLY OBSERVATION AUTHORISATION** | Publication Planning read-only observation | **AUTHORISE WITH CONSTRAINTS** — 2026-08-01; **EXERCISED ONCE — EXPIRED** | Training Implementation Owner |
| PAC-001 | **PROPOSED GOVERNANCE — NOT APPROVED** | Publication Arrangement Candidate 0.1 — PM-1 to PM-7 | **CANDIDATE ARRANGEMENT PREPARED — NOT APPROVED** — 2026-08-01 | Not established — TBD |
| TA-01 | TRAINING ASSUMPTION | Post-appointment context | Adopted | Not established — TBD |
| TA-02 | TRAINING ASSUMPTION | Simulated role participation | Adopted | Not established — TBD |
| TA-03 | TRAINING ASSUMPTION | Training delivery organisation | Adopted | Not established — TBD |
| OF-001 | OBSERVED FACT | CDE root areas at discovery | Recorded — **decision owner established (AG-002)**; intended state **not defined** | Training CDE Governance Approver under AG-002 |
| OF-002 | OBSERVED FACT | Populated production streams observed | Recorded | Not established — TBD |
| OF-003 | OBSERVED FACT | Common Files standards areas observed empty | Recorded — action required | Not established — TBD |
| OF-004 | OBSERVED FACT | Design Collaboration teams observed | Recorded | Not established — TBD |
| OF-005 | OBSERVED FACT | Coordination Space not observed configured | Recorded — action required | Not established — TBD |
| OF-006 | OBSERVED FACT | Published architectural drawing information and Transmittal | Recorded | Not established — TBD |
| OF-007 | OBSERVED FACT | Review and Issue activity | Recorded | Not established — TBD |
| OF-008 | OBSERVED FACT | Model Coordination provisioning | Recorded | Not established — TBD |
| UD-001 | OBSERVED FACT + UNRESOLVED DECISION | Design Collaboration MEP / Structural team-space mapping | **Unresolved** | Not established — TBD |

Five governance entries exist beyond observations and assumptions:

- **AG-001** — APPROVED GOVERNANCE, establishing the Training Baseline Approval
  Function;
- **GD-001** — a CONTROLLED GATE DECISION recording **Gate C — PASS**, taken
  using that function;
- **AD-001** — APPROVED GOVERNANCE, recording **Training Baseline 0.1 —
  APPROVED WITH CONDITIONS**, taken using the same function;
- **ROA-001** — a CONTROLLED READ-ONLY OBSERVATION AUTHORISATION permitting one
  bounded, read-only Publication Planning observation. **It authorises an
  evidence-gathering act only, assigns no authority, and is recorded here by
  reference** (section 6C).
- **AG-002** — APPROVED GOVERNANCE, establishing the **Training CDE Governance
  Approver** function. **It establishes who may decide OF-001; it decides
  nothing** (section 6).

**AG-001 establishes who may decide. GD-001 authorised progression to an
approval decision and approved no baseline. AD-001 is that approval decision.**

**Training Baseline 0.1 is APPROVED WITH CONDITIONS, not unconditionally
approved.** The AD-001 conditions remain active, and **publication remains NOT
AUTHORISED with the publication hold in force**.

One **PROPOSED GOVERNANCE** entry exists — **PAC-001**, a candidate publication
arrangement that is **prepared and not approved**, assigns no authority and
authorises no publication (section 5).

No APPROVED CHANGE, DEVIATION, NON-CONFORMANCE or SUPERSEDED DECISION entries
exist.

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

Entries OF-001 to OF-005 describe the state observed at Discovery Gate A and
reconfirmed during Increment 7C. Entries OF-006 to OF-008 record facts first
observed during Increment 7C. All describe the state at the level inspected, at
that time. **Observed state does not prove correctness** (BEP 12.3).

### OF-001 — CDE root areas at discovery

| Field | Value |
|---|---|
| Classification | OBSERVED FACT |
| Status | Recorded |
| Decision owner | **Training CDE Governance Approver under AG-002** |

**Evidence.** The current CDE root was observed to contain Common Files, WIP,
Shared and Published areas (BEP 6.11).

**Governance consequence.** This is the as-found baseline against which an
intended CDE structure will be decided and, after any approved change, verified.

**7C validation (Increment 7C).** Root CDE topology reconfirmed — Common Files,
WIP, Shared and Published. No `04 Archive` root observed. Evidence: `docs/Increment-7C-Live-Validation-Record.md`.

**Intended state.** Not defined. Any intended-state change is to be decided
through the governance route. The CDE Workflow & State Strategy records the
observed context and the governing workflow; it does not itself create that
decision.

**Decision required.** Whether the as-found structure is adopted, amended or
replaced as intended governance.

**Implementation / verification.** None. Not applicable until a decision exists.

**Note.** Presence of an area named after a state does not establish that the
state model is implemented (BEP 6.3).

**Decision owner established — 2026-08-01, Increment 8G-A.** The decision owner
was established by **AG-002**, which created the **Training CDE Governance
Approver** function for that purpose. **No intended CDE structure was selected**
— nothing was adopted, amended or replaced — and **OF-001 remains unresolved as
a governance matter**, with its **intended state still "Not defined"**. The
later decision **must consider the full as-found structure** — Common Files,
WIP, Shared, Published and the conceptual Record / Retained requirement,
together with the relationship between information states and platform
structure. **No implementation authority was assigned**: AG-002 confers no CDE
administration, configuration, folder-creation or permission authority.
Decision record — `docs/Training-CDE-Governance-Approver-Function-Decision.md`.

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

**7C validation (Increment 7C).** Reconfirmed: Architecture remains the only
populated direct production stream **at the inspected level**. The
absence-of-observation rule above applies unchanged to this reconfirmation.
Evidence: `docs/Increment-7C-Live-Validation-Record.md`.

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

**7C validation (Increment 7C).** The six non-BEP Common Files governance and
standards areas were re-observed **empty**. Evidence: `docs/Increment-7C-Live-Validation-Record.md`.

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

**7C validation (Increment 7C).** Three Design Collaboration teams reconfirmed —
Architecture, MEP Consultant and Structural — each with one visible member.
Included folders: All. **No Contractors team visible.** Member identities are
not recorded. Evidence: `docs/Increment-7C-Live-Validation-Record.md`.

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

**7C validation (Increment 7C).** The **Design Collaboration Coordination
Space** was reconfirmed as **not configured**.

Separately, and as a different Autodesk service, a **Model Coordination model
set** was observed to exist with **zero coordinated versions** — see OF-008. The
two services are not collapsed: provisioning one does not configure the other,
and neither demonstrates that a coordination process has been executed.
Evidence: `docs/Increment-7C-Live-Validation-Record.md`.

**Intended state.** Not decided or approved. The intended coordination
configuration is to be determined through the governance route. The Coordination
& Review Strategy records the matter as open; it does not itself authorise a
configuration.

**Decision required.** The intended coordination environment and its
configuration.

**Implementation / verification.** None.

**Note.** Presence of a capability is not maturity, and existing configuration is
not correctness (BEP 2.4).

### OF-006 — Published architectural drawing information and Transmittal

| Field | Value |
|---|---|
| Classification | OBSERVED FACT |
| Status | Recorded |
| Decision owner | Not established — TBD |

**Evidence.** Observed during Increment 7C:

- one architectural A101/A102 drawing-set PDF, version 1, in
  `03. Published / Drawings - PDF`;
- one Transmittal containing that file;
- the Transmittal / item **in review**;
- **no view or download activity** recorded — 0 of 1 recipients viewed, 0 of 1
  downloaded;
- **no receipt or acceptance evidence.**

Participants are recorded functionally: an **internal sender** and an **external
recipient**. No identities are recorded.

**Interpretation.** Platform publication and delivery **activity** was observed.
Governed publication authority and governed acceptance authority **remain
unresolved** (BEP 9.7, 9.8).

**Published ≠ Delivered ≠ Received ≠ Accepted.** A Transmittal evidences that a
delivery event occurred. It does not establish that anyone was authorised to
publish, that the recipient received it in a governed sense, or that it was
accepted. The ability to create a Transmittal is a platform permission, not
authority.

**Intended state.** Not defined. A governed publication and acceptance
arrangement is to be decided through the governance route.

**Decision required.** Publication / exchange authority and recipient acceptance
authority — both already recorded as unresolved.

**Implementation / verification.** None.

**Related.** BEP 6.7, 9.7, 9.8, 10.10, 10.11. Evidence: `docs/Increment-7C-Live-Validation-Record.md`.

### OF-007 — Review and Issue activity

| Field | Value |
|---|---|
| Classification | OBSERVED FACT |
| Status | Recorded |
| Decision owner | Not established — TBD |

**Evidence.** Observed during Increment 7C:

- **two** open Client Review instances;
- **one** open Coordination-type Issue;
- all relating to the architectural drawing context.

**No completed review, authorisation, verification or closure was
established.**

**Interpretation.** Review and issue **activity** exists in the platform. This is
not evidence that a governed review, authorisation or verification decision has
been taken. An open item is an open item.

**Intended state.** Not defined.

**Decision required.** None arising solely from this observation. Review and
authorisation routes remain as proposed in BEP Section 9.

**Implementation / verification.** None.

**Related.** BEP 8.7, 9.2, 9.6. Evidence: `docs/Increment-7C-Live-Validation-Record.md`.

### OF-008 — Model Coordination provisioning

| Field | Value |
|---|---|
| Classification | OBSERVED FACT |
| Status | Recorded |
| Decision owner | Not established — TBD |

**Evidence.** Observed during Increment 7C:

- **one** Model Coordination model set exists;
- **seven** included folders;
- rooted at the Model Coordination folder;
- **zero** coordinated versions;
- **no completed federation or coordination run demonstrated.**

**Interpretation.** **Environment configured ≠ coordination process executed.**
Provisioning a model set demonstrates that a capability is available, not that
coordination has been performed or governed.

**Distinct from OF-005.** The **Model Coordination** service (this entry) and the
**Design Collaboration Coordination Space** (OF-005, still not configured) are
different Autodesk services. They are not collapsed, and provisioning one does
not configure the other.

**Intended state.** Not defined. The intended coordination environment remains
open — see OF-005.

**Decision required.** See OF-005.

**Implementation / verification.** None.

**Related.** BEP 8.4, 8.5; Coordination & Review Strategy sections 6 and 7.
Evidence: `docs/Increment-7C-Live-Validation-Record.md`.

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

**7C validation (Increment 7C).** The cross-binding was **confirmed as current**
through manual UI evidence: the Architecture team maps to Architecture-labelled
WIP / Shared / Consumed paths, the MEP Consultant team to Structural-labelled
paths, and the Structural team to MEP-labelled paths. Classification, decision
status, decision owner, intended state and implementation status are all
**unchanged**. Evidence: `docs/Increment-7C-Live-Validation-Record.md`.

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

The proposed governance framework for this implementation is the BEP itself,
whose status is declared in BEP 1.2. It is not duplicated here. This section
records discrete governance proposals that need their own decision history —
for example a proposed change to an already-approved rule.

### PAC-001 — Publication Arrangement Candidate 0.1

| Field | Value |
|---|---|
| Classification | **PROPOSED GOVERNANCE — NOT APPROVED** |
| Topic | Candidate publication arrangement for Training Baseline 0.1 — PM-1 to PM-7 |
| Status | **CANDIDATE ARRANGEMENT PREPARED — NOT APPROVED** |
| Prepared | **2026-08-01**, Increment 8F |
| Decision owner | Not established — TBD |

**This is not a decision.** No governance-decision identifier is allocated, no
authority is assigned, and **no publication is authorised**. The candidate
proposes a publication-owner **function** without appointing or nominating any
holder; **publication / exchange authority and recipient acceptance authority
remain UNRESOLVED**.

**It resolves no PM matter and closes no condition.** GCR-005 remains **OPEN**,
and the **publication hold remains ACTIVE**.

**Refinement — 2026-08-01, Increment 8F-A.** PM-3's candidate **format** position
was completed, naming PDF/A-2b renditions, a UTF-8 JSON manifest, optional UTF-8
Markdown source companions and SHA-256 digests. **PAC-001 remains NOT APPROVED**,
its classification and status are unchanged, **no authority was assigned** and
**no publication was authorised**. No new candidate or governance-decision
identifier was allocated.

**Readiness assessment — 2026-08-01, Increment 8G.** **PRA-001** assessed this
candidate with outcome **NOT READY FOR APPROVAL**. The blocker is **PRA-B01** —
PM-1's publication-location position depends on **OF-001**, whose intended state
is undefined. **PAC-001 is neither approved nor rejected**, **no candidate
position was amended**, **no authority was assigned**, **no publication was
authorised**, and **PE-2 remains not reached**. PAC-001's classification and
candidate status are **unchanged**. **PRA-001 is a readiness assessment, not a
decision**, and carries **Authority: None**. Assessment record —
`docs/Publication-Arrangement-Readiness-Assessment.md`.

**Candidate record.** `docs/Publication-Arrangement-Candidate-0.1.md`.
**This entry is a reference, not a duplicate** — the candidate is not restated
here (BEP 12.13, 13.1).

## 6. Approved governance and approved changes

*No approved changes recorded.*

### AG-001 — Training Baseline Approval Function

| Field | Value |
|---|---|
| Classification | **APPROVED GOVERNANCE** |
| Topic | Training Baseline Approval Function |
| Source | Orchestrator decision, Increment 7G |
| Training basis | **TA-02** — simulated role participation |
| Status | **Approved governance — implemented and verified** |
| Decision owner | Training Baseline Approver |

**Decision.** Establish the **Training Baseline Approver** function, exercised by
the **Training Implementation Owner**, for the limited training / reference
baseline scope. No personal holder is recorded.

**Arising from.** Increment 7F readiness assessment, pre-approval condition
**GCR-001** — Training Baseline approval authority undefined.

**Authority conferred.** Review a defined candidate snapshot; approve, reject,
defer, or approve with recorded conditions; confirm the approved Git snapshot;
authorise the controlled baseline status transition.

**Authority NOT conferred.** Contractual authority; professional appointment;
design approval; **project publication / exchange authority**; **recipient
acceptance authority**; Autodesk configuration authority; authority to accept
project deliverables. Those remain as recorded elsewhere — publication and
acceptance authority both **unresolved**.

**Affected resources.** BEP document control (§1.6) and progressive baselining
(§9.10); the candidate manifest; the approval-decision process.

**Implementation.** Function documented in `docs/Training-Baseline-Approval-Function-Decision.md` and cross-referenced
from the BEP and the candidate manifest.

**Verification.** Completed through Increment 7H post-decision review:
**GCR-001 SATISFIED**, **GCR-011 READY FOR IMPLEMENTATION**, result
**READY FOR GATE C DECISION**, no authority bleed identified. Verifying the
function does **not** approve the candidate.

**Note.** This entry approves a *governance function*, not a baseline. Gate C
was subsequently passed through **GD-001**, which likewise approves no baseline,
and Training Baseline 0.1 was subsequently approved with conditions through
**AD-001** (BEP 1.2, 9.10, 12.11). **The publication hold remains in force.**

### AG-002 — Training CDE Governance Approver Function

| Field | Value |
|---|---|
| Classification | **APPROVED GOVERNANCE** |
| Topic | Training CDE Governance Approver Function |
| Source | Orchestrator decision, Increment 8G-A |
| Training basis | **TA-02** — simulated role participation |
| Scope | **Harrismith BIM-management training / reference implementation only** |
| Status | **FUNCTION ESTABLISHED — OF-001 DECISION NOT YET TAKEN** |
| Decision owner | Training CDE Governance Approver |

**Decision.** Establish the **Training CDE Governance Approver** function,
exercised by the **Training Implementation Owner**, for the limited training
CDE-structure governance scope. No personal holder is recorded.

**Arising from.** **OF-001** — decision owner "Not established — TBD" and
intended CDE structure undefined; **PRA-B01** — the sole principal blocker
preventing PAC-001 from reaching PE-2; **PRA-001**; and the Increment 8G-R
authority-boundary review, which established that no existing record authorised
any function to decide OF-001.

**Authority source.** **The authority arises from AG-002 itself.** It does
**not** rely on any pre-existing independent authority of the Training
Implementation Owner, which the 8G-R review found to be **not established**.

**Authority conferred.** Receive and review a defined CDE-structure governance
proposal; decide whether the as-found structure recorded by OF-001 is
**adopted, amended or replaced**; approve, reject, defer or approve with
recorded conditions; establish the intended governance position for Common
Files, WIP, Shared, Published / Authorised and the conceptual Record / Retained
requirement; determine the intended relationship between information states and
platform areas; record the scope and basis of the decision; authorise the
controlled governance-status transition from observed as-found structure to
approved intended governance.

**Authority NOT conferred.** Project publication / exchange authority;
publication-event authorisation; recipient acceptance authority; upload or
publication execution; **CDE administration or platform-configuration
execution**; folder creation, renaming, moving or deletion; membership or
permission change; **implementation** of an approved structure; design approval;
acceptance of project deliverables; professional or contractual authority;
naming, coordinate, titleblock or template standards unless separately
authorised; universal governance-change authority outside the CDE-structure
scope; amendment of PAC-001 through the OF-001 decision itself; closure of
GCR-005, GCR-006 or UD-001 except through a separately authorised decision that
expressly does so. **Holding this function confers none of the other
authorities.**

**Relationship to OF-001.** AG-002 establishes OF-001's **decision owner** and
authorises a later decision on it as a **full CDE-structure governance matter**
covering Common Files, WIP, Shared, Published and Record / Retained. **PM-1 is a
consequence of that decision, not a substitute for it**, and a PM-1-only
determination would **not** fully close OF-001. **OF-001 remains unresolved and
its intended state remains "Not defined".** No structural outcome is selected.

**Implementation.** Function documented in
`docs/Training-CDE-Governance-Approver-Function-Decision.md` and cross-referenced
from OF-001. **No technical implementation is authorised or performed** —
deciding is not implementing (BEP 5.9).

**Verification.** **Not yet performed.** The function is established and not yet
exercised.

**Identifier-family note.** **AG-002 extends the `AG-` identifier family as this
training implementation's authority-establishment decision precedent**, AG-001
being the first such decision. **This does not mean every future authority
decision automatically belongs to the AG family** — family membership for any
later decision requires its own controlled determination.

**Note.** This entry approves a *governance function*, not a structure. **No
CDE structure is adopted, amended or replaced**, PRA-B01 remains **open**,
PAC-001 remains **not approved and unamended**, and **the publication hold
remains in force**. **This entry is a reference, not a duplicate** — the full
decision is not restated here (BEP 12.13, 13.1).

## 6A. Gate decisions

### GD-001 — Training Baseline 0.1 — Gate C Decision

| Field | Value |
|---|---|
| Classification | **CONTROLLED GATE DECISION** |
| Topic | Training Baseline 0.1 — Gate C Decision |
| Decision | **PASS** |
| Decision function | **Training Baseline Approver** |
| Functional holder | **Training Implementation Owner** |
| Authority basis | **AG-001** |
| Candidate snapshot | `cc146a5f84b1ce20d2dfc73d878a77c58959c559` |
| Decision date | **2026-08-01** |
| Status | Recorded |

**Decision effect.** The candidate may proceed to a **separate** Training
Baseline approval decision.

**Explicit non-effects.** GD-001 does **not**:

- approve Training Baseline 0.1 — at this decision the candidate remained
  **FOR REVIEW — NOT APPROVED**; approval was taken separately and later,
  through **AD-001**;
- authorise publication — the **publication hold remains active**;
- resolve project publication / exchange authority — **unresolved**;
- resolve recipient acceptance authority — **unresolved**;
- resolve **UD-001** — it remains an OBSERVED discrepancy and UNRESOLVED
  DECISION;
- establish any project standard — Naming, Coordinates, Titleblocks and
  Templates / Authoring Resources all remain **Not established**.

**Conditions carried forward.**

| Condition | Class |
|---|---|
| **GCR-005** — publication parameters undefined | **PRE-PUBLICATION** |
| **GCR-006** — one governed coordination cycle to be exercised after approval | **IMPLEMENTATION** |
| Publication hold | **Remains active** |

**Classification note.** GD-001 is a **gate decision**, not approved governance,
not an approved change, not professional approval, not project publication
approval and not recipient acceptance.

**Relationship.** **AG-001** establishes *who may decide*. **GD-001** is a
decision taken *using* that function. The Training Baseline approval decision
was taken separately, as **AD-001** — see section 6B.

**Decision record.** `docs/Training-Baseline-0.1-Gate-C-Decision.md`.

## 6B. Baseline approval decisions

### AD-001 — Training Baseline 0.1 — Approval Decision

| Field | Value |
|---|---|
| Classification | **APPROVED GOVERNANCE** |
| Topic | Training Baseline 0.1 — Approval Decision |
| Decision | **APPROVED WITH CONDITIONS** |
| Decision function | **Training Baseline Approver** |
| Functional holder | **Training Implementation Owner** |
| Authority basis | **AG-001** |
| Gate decision relied upon | **GD-001** — Gate C PASS |
| Governance basis approved | `cc146a5f84b1ce20d2dfc73d878a77c58959c559` |
| Pre-decision repository state | `707b966f5eb0d0e3975a80e9a939d381bc6f3297` |
| Decision date | **2026-08-01** |
| Status | Recorded |

**Snapshot identity.** The approved governance basis is the snapshot assessed at
Gate C. Increments **7I-A** (`86241b0…`) and **7I-B** (`707b966…`) were narrowly
scoped factual status corrections to the non-authoritative BIM Delivery Guide;
they **changed no governance content** and no part of the basis Gate C assessed.

**Decision effect.** Training Baseline 0.1 is approved as the governed training
and reference-implementation baseline, **with conditions**, for the purpose
stated in AD-001. It is **not unconditionally approved**.

**Conditions carried — all active.**

| Condition | Class |
|---|---|
| Publication hold | **Remains active — publication NOT AUTHORISED** |
| **GCR-005** — publication parameters undefined | **PRE-PUBLICATION — open** |
| **GCR-006** — one complete governed coordination cycle to be exercised and evidenced | **IMPLEMENTATION — open** |
| **UD-001** — MEP / Structural team-space mapping | **OBSERVED discrepancy + UNRESOLVED DECISION** |
| Project publication / exchange authority | **Unresolved** |
| Recipient acceptance authority | **Unresolved** |
| Naming, Coordinates, Titleblocks, Templates / Authoring Resources | **Not established** |

**Explicit non-effects.** AD-001 does **not**:

- authorise publication, exchange, issue, delivery or external distribution —
  the **publication hold remains active**;
- resolve **GCR-005** or define any publication parameter;
- complete, simulate or evidence **GCR-006** — no complete governed coordination
  cycle has been demonstrated;
- resolve **UD-001**;
- establish project publication / exchange authority;
- establish recipient acceptance authority;
- establish any project standard;
- confer governing status on the companion documents, which retain
  **Authority: None**;
- create a contractual authority, professional appointment, tag or release.

**Classification note.** AD-001 is **APPROVED GOVERNANCE** — an approval of the
baseline itself. It is not an APPROVED CHANGE, not professional approval, not
project publication approval and not recipient acceptance. **Approved is not
Published, Delivered, Received or Accepted.**

**Relationship.** Gate C passage **enabled** this decision but did not itself
approve the baseline. **AD-001 is the approval decision**, and it approves the
governance baseline only.

**Implementation and verification.** Approval is not implementation, and
implementation is not verification (BEP 12.3, 12.9). **GCR-005** and
**GCR-006** remain outstanding, and verification of the approved baseline in use
has **not** been performed. No implementation assignment is created.

**Decision record.** `docs/Training-Baseline-0.1-Approval-Decision.md`.

## 6C. Observation authorisations

### ROA-001 — Publication Planning Read-Only Observation Authorisation

| Field | Value |
|---|---|
| Classification | **CONTROLLED READ-ONLY OBSERVATION AUTHORISATION** |
| Topic | Publication Planning — one bounded read-only observation |
| Decision | **AUTHORISE WITH CONSTRAINTS** |
| Authorising function | **Training Implementation Owner** |
| Scope | `PPQ-001` to `PPQ-007`; **one** Claude Desktop session; read-only; Harrismith Fire Station only; session account visibility only |
| Expiry | On that session producing its completion report, or on withdrawal through a later controlled increment |
| Decision date | **2026-08-01** |
| Status | **EXERCISED ONCE — EXPIRED** (2026-08-01). The one authorised observation was performed as Increment 8D; the authorisation expired on its completion report. **Not renewable; no repeat observation authorised.** No mutation reported |

**Explicit non-effects.** ROA-001 does **not** authorise publication, upload,
issue, delivery, receipt, acceptance or any external information exchange; does
**not** lift or vary the publication hold; does **not** establish project
publication / exchange authority or recipient acceptance authority; and does
**not** resolve PM-1 to PM-7, GCR-005, GCR-006 or UD-001.

**Classification note.** ROA-001 authorises an **evidence-gathering act**, not a
governance outcome. **Observation is not a decision**, and any evidence it
produces is observational evidence only (BEP 12.3).

**Decision record.** `docs/Publication-Planning-Read-Only-Observation-Authorisation.md`.
**This entry is a reference, not a duplicate** — the full decision is not
restated here (BEP 12.13, 13.1).

**Observation record.** `docs/Increment-8D-Publication-Planning-Read-Only-Observation-Record.md`
— **EC-3 observational evidence only.** The observation **resolved no PM matter,
assigned no authority and selected no publication arrangement**, and the
non-effects above are unchanged by it.

---

## 7. Deviations

*No deviations recorded.*

A deviation is a knowingly permitted departure from **approved** governance.
Training Baseline 0.1 is approved with conditions through **AD-001**, so the
classification is available in principle — but **none is authorised or
recorded**, and AD-001 authorises no departure from the baseline it approves
(BEP 12.6).

## 8. Non-conformances

*No non-conformances recorded.*

A non-conformance is an unintended failure against **approved** governance.
Training Baseline 0.1 is approved with conditions through **AD-001**, so the
classification is available in principle where the approved baseline applies —
but **nothing is recorded here, and nothing is asserted**. See UD-001 for why
the observed team-space discrepancy is **not** classified as a non-conformance.

## 9. Superseded decisions

*No superseded decisions recorded.*

When a decision is superseded, this section retains the original decision, its
status, the replacement decision, the effective point, and the reason or context
(BEP 12.10). History is not deleted because governance changed.

## 10. Register change log

| Date | Change | Increment |
|---|---|---|
| 2026-07-31 | Register populated as a controlled draft. TA-01, TA-02, TA-03 transcribed from BEP 2.6. OF-001 to OF-005 recorded. UD-001 detail recorded from the observed condition. | 3A |
| 2026-08-01 | Increment 7C validation evidence incorporated. OF-001 to OF-005 reconfirmed; UD-001 evidence updated and left unresolved; OF-006, OF-007 and OF-008 recorded as OBSERVED FACT. | 7D |
| 2026-08-01 | AG-001 recorded — Training Baseline Approval Function established as APPROVED GOVERNANCE. First approved-governance entry. Baseline 0.1 remains unapproved. | 7G |
| 2026-08-01 | GD-001 recorded — Gate C PASS for candidate snapshot cc146a5f. AG-001 verification completed through Increment 7H. Baseline 0.1 remains unapproved; publication hold active. | 7I |
| 2026-08-01 | AD-001 recorded — Training Baseline 0.1 APPROVED WITH CONDITIONS for the governance basis assessed at cc146a5f. Register status advanced to APPROVED WITH CONDITIONS. GCR-005, GCR-006 and UD-001 remain open; publication/exchange and recipient acceptance authority remain unresolved; project standards remain Not established; publication remains NOT AUTHORISED with the hold active. | 7J |
| 2026-08-01 | ROA-001 recorded by reference — one bounded read-only Publication Planning observation AUTHORISED WITH CONSTRAINTS, covering PPQ-001 to PPQ-007 in a single session, expiring on that session's completion report. Not yet exercised. No authority assigned; GCR-005, GCR-006 and UD-001 remain open; publication remains NOT AUTHORISED with the hold active. | 8C-A |
| 2026-08-01 | PAC-001 recorded by reference — Publication Arrangement Candidate 0.1 prepared for PM-1 to PM-7 as PROPOSED GOVERNANCE — NOT APPROVED. Not a decision; no governance-decision identifier allocated; no authority assigned; no publication authorised. PM matters remain unresolved; GCR-005 and GCR-006 remain open; publication remains NOT AUTHORISED with the hold active. | 8F |
| 2026-08-01 | AG-002 recorded — Training CDE Governance Approver function established as APPROVED GOVERNANCE, arising from OF-001, PRA-B01, PRA-001 and the Increment 8G-R authority-boundary review. Establishes who may decide OF-001; decides nothing. OF-001's decision owner advanced from "Not established — TBD" to Training CDE Governance Approver under AG-002, while its intended state remains "Not defined" and the matter remains unresolved. No structural outcome selected; no implementation, publication/exchange, acceptance or CDE administration authority conferred. PRA-B01 remains open, PAC-001 remains not approved and unamended, publication remains NOT AUTHORISED with the hold active. | 8G-A |
| 2026-08-01 | PRA-001 recorded by reference — Publication Arrangement Readiness Assessment of PAC-001, outcome NOT READY FOR APPROVAL. Sole principal blocker PRA-B01: PM-1 depends on OF-001, whose intended CDE structure remains undefined. Five findings are approval conditions and six are implementation prerequisites; none independently prohibits later arrangement approval. Not a decision; no governance-decision identifier allocated; PAC-001 neither approved nor rejected and not amended; no authority assigned; no publication authorised; PE-2 not reached. OF-001, GCR-005 and GCR-006 remain open; publication remains NOT AUTHORISED with the hold active. | 8G |
| 2026-08-01 | PAC-001 refined — PM-3's candidate format position completed (PDF/A-2b renditions, UTF-8 JSON manifest, optional UTF-8 Markdown source companions, SHA-256 digests) following the Increment 8F-R review, which returned 30 checks PASS and 1 FAIL. Classification and status unchanged: PAC-001 remains PROPOSED GOVERNANCE — NOT APPROVED. No authority assigned; no publication authorised; no new identifier allocated. GCR-005 and GCR-006 remain open; publication remains NOT AUTHORISED with the hold active. | 8F-A |
| 2026-08-01 | ROA-001 status advanced to EXERCISED ONCE — EXPIRED. The authorised observation was performed as Increment 8D and recorded as EC-3 evidence (PPER-004 to PPER-009, all assessed and insufficient); no mutation reported. PM-1 to PM-7 remain UNRESOLVED and no candidate arrangement is prepared. No authority assigned; GCR-005, GCR-006 and UD-001 remain open; publication remains NOT AUTHORISED with the hold active. | 8E |

**Note on histories.** This change log records *decision and register* history.
Git commit history records *source* history. They are complementary and not
interchangeable — a commit shows that wording changed; it does not show that a
decision was taken (BEP 9.11, 12.10).
