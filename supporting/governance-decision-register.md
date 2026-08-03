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
| CGD-001 | **APPROVED GOVERNANCE** | CDE Structure Governance Decision — intended root topology | **APPROVE WITH CONDITIONS** — 2026-08-01; **OF-001 RESOLVED; VERIFICATION PENDING** | Training CDE Governance Approver |
| AG-003 | **APPROVED GOVERNANCE** | Training Publication Arrangement Approver Function | **FUNCTION ESTABLISHED — PAC-001 APPROVAL DECISION NOT YET TAKEN** — 2026-08-01 | Training Publication Arrangement Approver |
| PAD-001 | **APPROVED GOVERNANCE** | Publication Arrangement Approval Decision — PAC-001 | **APPROVE WITH CONDITIONS** — 2026-08-01; **PE-2 REACHED; PE-3 NOT AUTHORISED** | Training Publication Arrangement Approver |
| AG-004 | **APPROVED GOVERNANCE** | Training Baseline Publication Owner Function | **FUNCTION ESTABLISHED — NO PUBLICATION EVENT AUTHORISED** — 2026-08-02 | Training Baseline Publication Owner |
| AG-005 | **APPROVED GOVERNANCE** | Training Publication Naming and Presentation Approver Function | **FUNCTION ESTABLISHED — C5 CONTROL DECISION NOT YET TAKEN** — 2026-08-02 | Training Publication Naming and Presentation Approver |
| GD-001 | **CONTROLLED GATE DECISION** | Training Baseline 0.1 — Gate C Decision | **PASS** — 2026-08-01 | Training Baseline Approver |
| AD-001 | **APPROVED GOVERNANCE** | Training Baseline 0.1 — Approval Decision | **APPROVED WITH CONDITIONS** — 2026-08-01 | Training Baseline Approver |
| ROA-001 | **CONTROLLED READ-ONLY OBSERVATION AUTHORISATION** | Publication Planning read-only observation | **AUTHORISE WITH CONSTRAINTS** — 2026-08-01; **EXERCISED ONCE — EXPIRED** | Training Implementation Owner |
| PAC-001 | **PROPOSED GOVERNANCE** — historical proposal record | Publication Arrangement Candidate 0.1 — PM-1 to PM-7 | **APPROVED WITH CONDITIONS BY PAD-001** — 2026-08-01 | Training Publication Arrangement Approver under AG-003 |
| NPC-001 | **PROPOSED GOVERNANCE — NOT APPROVED** | Training Baseline Naming and Presentation Control Candidate — PAD-001 condition C5 | **CANDIDATE PREPARED — ASSESSED BY NPRA-001 — NOT APPROVED** — 2026-08-02 | Coordinated under AG-004; decision belongs to Training Publication Naming and Presentation Approver under AG-005 |
| NPRA-001 | **ASSESSMENT RECORD — NOT A GOVERNANCE DECISION** | Training Baseline Naming and Presentation Control Readiness Assessment — subject NPC-001 | **READY FOR AG-005 DECISION WITH CONDITIONS** — 2026-08-02; **Authority: None; AG-005 NOT EXERCISED** | Non-decisional assessment; no decision owner |
| TA-01 | TRAINING ASSUMPTION | Post-appointment context | Adopted | Not established — TBD |
| TA-02 | TRAINING ASSUMPTION | Simulated role participation | Adopted | Not established — TBD |
| TA-03 | TRAINING ASSUMPTION | Training delivery organisation | Adopted | Not established — TBD |
| OF-001 | OBSERVED FACT | CDE root areas at discovery | **RESOLVED BY CGD-001 — ROOT TOPOLOGY ADOPTED WITH CONDITIONS; VERIFICATION PENDING** | Training CDE Governance Approver under AG-002 |
| OF-002 | OBSERVED FACT | Populated production streams observed | Recorded | Not established — TBD |
| OF-003 | OBSERVED FACT | Common Files standards areas observed empty | Recorded — action required | Not established — TBD |
| OF-004 | OBSERVED FACT | Design Collaboration teams observed | Recorded | Not established — TBD |
| OF-005 | OBSERVED FACT | Coordination Space not observed configured | Recorded — action required | Not established — TBD |
| OF-006 | OBSERVED FACT | Published architectural drawing information and Transmittal | Recorded | Not established — TBD |
| OF-007 | OBSERVED FACT | Review and Issue activity | Recorded | Not established — TBD |
| OF-008 | OBSERVED FACT | Model Coordination provisioning | Recorded | Not established — TBD |
| UD-001 | OBSERVED FACT + UNRESOLVED DECISION | Design Collaboration MEP / Structural team-space mapping | **Unresolved** | Not established — TBD |

Ten governance entries exist beyond observations and assumptions:

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
- **CGD-001** — APPROVED GOVERNANCE, recording the **CDE Structure Governance
  Decision**: the as-found four-area root topology is **adopted with conditions**
  as the intended training CDE governance. **It resolves OF-001 at the governance
  level; it implements nothing and approves no child structure** (section 6).
- **AG-003** — APPROVED GOVERNANCE, establishing the **Training Publication
  Arrangement Approver** function. **It establishes who may later decide PAC-001
  at PE-2; it approves nothing** (section 6).
- **PAD-001** — APPROVED GOVERNANCE, recording the **Publication Arrangement
  Approval Decision**: PAC-001 is **approved with conditions** at **PE-2**.
  **It closes GCR-005 at the governance-definition level; it authorises no
  publication and does not reach PE-3** (section 6).
- **AG-004** — APPROVED GOVERNANCE, establishing the **Training Baseline
  Publication Owner** function required by **PM-2**. **It owns package identity,
  preparation governance and readiness coordination; it authorises no
  publication event, pins no commit and confers no publication / exchange,
  execution, CDE implementation or acceptance authority** (section 6).
- **AG-005** — APPROVED GOVERNANCE, establishing the **Training Publication
  Naming and Presentation Approver** function. **It establishes who may later
  decide the PAD-001 condition C5 package-specific naming and presentation
  controls; it decides none of them.** **C5 remains CARRIED FORWARD, P6 step 3
  remains pending, and no project-wide standard, implementation or publication
  authority is conferred** (section 6).

**AG-001 establishes who may decide. GD-001 authorised progression to an
approval decision and approved no baseline. AD-001 is that approval decision.**

**Training Baseline 0.1 is APPROVED WITH CONDITIONS, not unconditionally
approved.** The AD-001 conditions remain active, and **publication remains NOT
AUTHORISED with the publication hold in force**.

Two **PROPOSED GOVERNANCE** entries exist, and **neither counts toward the
approved-governance total above**:

- **PAC-001** — **retained as a historical proposal record**, classified
  **PROPOSED GOVERNANCE — NOT APPROVED when prepared**; its **substantive
  publication arrangement was subsequently APPROVED WITH CONDITIONS BY
  PAD-001**. **PAC-001 itself assigned no authority and did not authorise
  publication**, and **PAD-001's approval reached PE-2 only — it authorised
  neither PE-3 nor publication** (section 5);
- **NPC-001** — the **Training Baseline Naming and Presentation Control
  Candidate** for **PAD-001 condition C5**, **prepared, not assessed and not
  approved**, carrying **Authority: None**. **It proposes package-specific
  filenames, a child-container name and presentation markings; it establishes
  none of them, establishes no project-wide standard and authorises no
  publication** (section 5).

One **non-decisional assessment record** exists and **does not count toward the
approved-governance total above** — **NPRA-001**, the readiness assessment of
NPC-001, carrying **Authority: None**. **It approves nothing, decides nothing,
satisfies no condition or prerequisite and reaches no PE event**; its outcome is
**READY FOR AG-005 DECISION WITH CONDITIONS** (section 6D).

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

**Subsequent governance status — 2026-08-01, Increment 8G-B.** The statements
above record the position **before** the decision, and the *"Intended state. Not
defined"* text is retained as the **historical record of the state at that
time**. The intended state was **subsequently defined** by **CGD-001**.

| Field | Subsequent position |
|---|---|
| Decision | **CGD-001** — `docs/CDE-Structure-Governance-Decision.md` |
| Outcome | **APPROVE WITH CONDITIONS** |
| Structural determination | **As-found four-area root topology adopted as intended governance** — `0. Common Files`, `01. WIP (Work in Progress)`, `02. Shared`, `03. Published` |
| Intended state | **Now defined by CGD-001** |
| Decision owner | **Training CDE Governance Approver under AG-002** |
| Governance matter | **Resolved** |
| Implementation | **Not required at root level** — the observed topology corresponds to the approved one — **but not authorised** (CGD-C07) |
| Verification | **Pending** |
| Child structures | **Not approved** (CGD-C04). **UD-001 remains unresolved** |
| Retrospective effect | **None** (CGD-C02) |
| Authority assigned | **None** — no publication, exchange, acceptance, CDE administration or implementation authority (CGD-C08) |

**States are not folders.** Adoption of the four-area topology does **not**
establish that the state model is implemented — the note above continues to
apply (BEP 6.3; CGD-C01).

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
| Decision owner | **Training Publication Arrangement Approver under AG-003** |

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

**Readiness reassessment — 2026-08-01, Increment 8G-D.** **PRA-002** reassessed
this candidate at repository state `532c4ec74f2013461f7fef637c0e6734a11b2dfb`,
with outcome **READY FOR APPROVAL WITH CONDITIONS** — six later conditions and
eight implementation prerequisites carried forward, and **no current BLOCKER**.
**PAC-001 remains NOT APPROVED**: readiness is eligibility to be decided, not a
decision. **PE-2 remains not reached**, and **AG-003 has not yet been
exercised**. **PRA-002 is a readiness reassessment, not a decision**, and carries
**Authority: None**; no governance-decision identifier is allocated for it.
PRA-001 remains historically valid but is no longer the current basis.
Reassessment record — `docs/Publication-Arrangement-Readiness-Reassessment.md`.

**Decision owner established — 2026-08-01, Increment 8G-C.** **AG-003**
established the **Training Publication Arrangement Approver**, the function that
may later take the **PE-2** arrangement-approval decision. **PAC-001 was not
approved.** **Readiness must first be reassessed** — AG-003 §4 requires a fresh
controlled assessment concluding READY FOR APPROVAL or READY FOR APPROVAL WITH
CONDITIONS, and PRA-001 cannot serve as the current basis. **No PM position
changed**, and **no publication or implementation authority was assigned**.
Function decision — `docs/Training-Publication-Arrangement-Approver-Function-Decision.md`.

**Approved — 2026-08-01, Increment 8H.** **PAD-001 approved this arrangement
with conditions**, subject substantive body hash
**`4d67dcfcc7556665b3f93f2363b3dfd4`**. **All PM-1 to PM-7 positions are
APPROVED WITH CONDITIONS**; **the seven UTF-8 Markdown source companions are
included** as subordinate files; **GCR-005 is closed at the
governance-definition level**; **PE-2 is reached and PE-3 is not**; and **no
publication is authorised**. **PAC-001 is retained as the historical proposal
record** — its classification and substantive content are unchanged. Decision —
`docs/Publication-Arrangement-Approval-Decision.md`.

**Candidate record.** `docs/Publication-Arrangement-Candidate-0.1.md`.
**This entry is a reference, not a duplicate** — the candidate is not restated
here (BEP 12.13, 13.1).

### NPC-001 — Training Baseline Naming and Presentation Control Candidate

| Field | Value |
|---|---|
| Identifier | **NPC-001** |
| Classification | **PROPOSED GOVERNANCE — NOT APPROVED** |
| Status | **CANDIDATE PREPARED — NOT ASSESSED — NOT APPROVED** |
| **Authority** | **None** |
| Candidate date | **2026-08-02** |
| Source | Orchestrator-directed proposal coordinated under AG-004, Increment 8H-C |
| Scope | **Training Baseline 0.1 package-specific naming and presentation controls only** |
| Candidate-coordination function | **Training Baseline Publication Owner under AG-004** |
| Future decision function | **Training Publication Naming and Presentation Approver under AG-005** |
| Source repository state reviewed | `09c04ff9d84e79d95317206b393e217e3fb209a5` |
| Training basis | **TA-02** — simulated role participation |
| Candidate document | `docs/Training-Baseline-Naming-and-Presentation-Control-Candidate.md` |

**What it is.** A controlled proposal of the minimum package-specific naming and
presentation controls required by **PAD-001 condition C5**. **It is not a
decision, not an assessment and not an approval**, and **it carries no
authority**.

**Filename grammar proposed.** Authoritative rendition
`HFS-TB0P1-<DOCUMENT>-AWC.pdf`; authoritative manifest
`HFS-TB0P1-MANIFEST-AWC.json`; subordinate source companion
`HFS-TB0P1-<DOCUMENT>-AWC-SOURCE.md`. Token dictionary: `HFS` Harrismith Fire
Station; `TB0P1` Training Baseline 0.1, with `P` representing the decimal point;
`AWC` **Approved With Conditions**; `SOURCE` subordinate Markdown companion;
`MANIFEST` authoritative package manifest. Fourteen character and format rules
are proposed — uppercase ASCII, digits and hyphen only; hyphen as sole
separator; no spaces, underscores, leading, trailing or consecutive hyphens; a
single period before a lowercase class-fixed extension; fixed token order;
case-insensitive uniqueness; a 120-character limit; `SOURCE` as the only
relationship token; and application to this package only.

**Controlled document-token map.** Seven source documents map to seven tokens —
`BEP`; `IM-RESP-MATRIX`; `MODEL-INFO-RESP-MATRIX`; `INFO-DELIVERY-SCHEDULE`;
`CDE-WORKFLOW-STATE-STRATEGY`; `COORDINATION-REVIEW-STRATEGY`;
`GOVERNANCE-DECISION-REGISTER`. **The map is exhaustive for this package and
creates no reusable project document codes.**

**Package file-count summary.** **Fifteen proposed filenames** — **seven**
authoritative `PDF/A-2b` renditions, **one** authoritative `UTF-8 JSON`
manifest, **seven** subordinate `UTF-8 Markdown` source companions. **This
matches PAD-001's approved boundary exactly**; **no file class is added, removed
or merged**, and **no companion becomes authoritative**. Each rendition has
exactly one companion sharing its complete stem plus `-SOURCE`; **the manifest
has no companion**.

**Proposed child-container name.** `Training Baseline 0.1` — exact title case,
single spaces, no leading or trailing space, numeric form `0.1`, a direct child
of `03. Published`, with **no additional child or subfolder authorised**. **The
container does not exist because NPC-001 names it**; **CDE administration or
implementation authority remains required (P7)** and **CGD-001 live
correspondence remains unverified (C6)**.

**Presentation-marking summary.** A package-specific first-page control block
(project, baseline, document title, `APPROVED WITH CONDITIONS`, `AD-001`,
`PAD-001`, `HFS-TB0P1`, the later-pinned source commit, the later generation
date) and an every-page footer `HFS-TB0P1 | <DOCUMENT> | AWC | Page <x> of <y>`.
**This is not a project titleblock or sheet standard**; **no source document is
modified**; **the marking is applied only during later authorised generation**;
and **the commit and date fields are deliberately unpopulatable today**. The
seven packaged Markdown companions remain **byte-faithful** — no inserted
heading, front matter, footer or content mutation.

**Manifest identity rule.** Filename exactly `HFS-TB0P1-MANIFEST-AWC.json`;
authoritative for package identity and integrity; records the exact fifteen-file
inventory, each file's authoritative or subordinate role and each
companion-to-rendition relationship; carries `HFS-TB0P1`, the full status
`APPROVED WITH CONDITIONS` and the later pinned source commit; **uses PAD-001's
approved PM-4 metadata set without change or enlargement**. **No manifest is
generated.**

**Scope boundary.** NPC-001 applies **only** to the fifteen-file Training
Baseline 0.1 package and its proposed PM-1 child container. **It is not the
Harrismith project naming standard, a general CDE naming standard, a titleblock
standard, a template standard, a coordinate standard or a reusable naming
convention for other packages.** **The project-wide naming, coordinate,
titleblock and template standards remain NOT ESTABLISHED.**

**Collision and ambiguity position.** The candidate records thirteen factual
confirmations — fifteen unique names, unique case-insensitively; one companion
per rendition; no companion for the manifest; `IM-RESP-MATRIX` distinct from
`MODEL-INFO-RESP-MATRIX`; `TB0P1` not confusable with an extension; `SOURCE`
only on companions; one controlled meaning for `AWC`; one period per filename;
class-identifying extensions; container name distinct from the four CDE root
areas; boundary unchanged; no project-wide standard. Longest proposed filename
**52 characters**. **Platform compatibility has not been tested and no such
claim is made.**

**Readiness-assessment requirement.** **A separate controlled `Authority: None`
readiness assessment is required before AG-005 may be exercised against
NPC-001.** It is the orchestrator-directed workflow: it **adds no authority to
NPC-001, does not alter AG-005, does not imply the candidate is ready, and
prevents the candidate-preparation record from becoming its own approval
justification**. **It has not been performed.** Eighteen readiness questions are
recorded in the candidate and **all remain unanswered**.

**C5 status.** **`C5 — CANDIDATE PREPARED; NOT ASSESSED; NOT APPROVED`**, with
C5's overall status **`CARRIED FORWARD`**. The decision route exists under
AG-005; **AG-005 has not been exercised**; **package assembly remains blocked**.

**P6 status.** Step 1 **satisfied**; step 2 **satisfied by AG-004**; step 3
**CANDIDATE PREPARED — NOT ASSESSED — NOT SATISFIED**; step 4 **not performed**;
step 5 **sequence unchanged**. **P6 remains ACTIVE — PUBLICATION-PACKAGE COMMIT
NOT PINNED**, and **no repository commit is the publication-package commit**.

**Publication status.** **NOT AUTHORISED**; publication hold **ACTIVE**;
publication / exchange authority **UNRESOLVED**; technical executor
**unassigned**; CDE implementation authority **not established**; recipient
acceptance authority **UNRESOLVED**; **PE-2 reached, PE-3 through PE-S not
reached**; **no package artefact exists**.

**Identifier-family note.** **NPC-001 opens the `NPC-` family** — *Naming and
Presentation Control Candidate*. **`NPC-001` was unused before this record**,
and the prefix collides with none of the established families (`AD-`, `AG-`,
`CGD-`, `EC-`, `GCR-`, `GD-`, `OC-`, `OF-`, `PAC-`, `PAD-`, `PE-`, `PM-`,
`PPER-`, `PPQ-`, `PRA-`, `ROA-`, `TA-`, `UD-`). **The family is expressly
limited to package-specific naming and presentation control candidates and is a
candidate family, not a decision or authority family** — **no `NPC-` record
carries authority, approves anything or reaches any PE event**. **Later use
still requires a controlled scope and collision review.**

**Candidate record.** `docs/Training-Baseline-Naming-and-Presentation-Control-Candidate.md`.
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

### CGD-001 — CDE Structure Governance Decision

| Field | Value |
|---|---|
| Classification | **APPROVED GOVERNANCE** |
| Topic | Intended CDE root topology and information-state mapping |
| Decision outcome | **APPROVE WITH CONDITIONS** |
| Structural determination | **As-found four-area root topology adopted as intended training CDE governance** |
| Deciding function | **Training CDE Governance Approver under AG-002** |
| Functional holder | **Training Implementation Owner** |
| Training basis | **TA-02** — simulated role participation |
| Scope | **Harrismith BIM-management training / reference implementation only** |
| Source | Orchestrator decision, Increment 8G-B |
| Status | **OF-001 RESOLVED — IMPLEMENTATION AND VERIFICATION NOT YET PERFORMED** |

**Approved topology.** `0. Common Files`; `01. WIP (Work in Progress)`;
`02. Shared`; `03. Published`. Intended mapping: **Common Files** is a
controlled reference / governance-support area and **is not an information
state**; **WIP**, **Shared** and **Published / Authorised** correspond to those
information states; **Record / Retained** remains a **conceptual requirement**
and **no mandatory `04 Archive` root is approved or required**.

**Conditions — all active.** **CGD-C01** states are not folders; **CGD-C02** no
retrospective effect; **CGD-C03** controlled transitions; **CGD-C04** child
structures excluded and **UD-001 remains unresolved**; **CGD-C05** naming
remains provisional; **CGD-C06** retention without a mandatory Archive root;
**CGD-C07** decision is not implementation, no root-level change directed,
**verification pending**; **CGD-C08** authority separation.

**Explicit non-effects.** CGD-001 does **not** authorise publication or lift the
hold; approve **PAC-001** or its PM-1 position; reach **PE-2**; establish
publication / exchange or recipient acceptance authority; confer CDE
administration or implementation authority; authorise any Autodesk
configuration change; approve any child folder, discipline structure or
team-space mapping; resolve **UD-001**; close **GCR-005** or **GCR-006**;
establish any project standard; or retrospectively authorise, approve or
classify existing information.

**Relationship to OF-001.** **Resolves OF-001 at the governance level.** The
intended state is now defined. OF-001's historical record that the intended
state was previously **"Not defined"** is **preserved, not rewritten**.

**Relationship to PAC-001 and PRA-B01.** **PRA-B01's blocking dependency is
resolved**; PRA-001's original outcome remains **historically valid** and its
BLOCKER finding is not rewritten. The adopted topology **supports retaining**
PAC-001's PM-1 candidate position, but **does not approve it**. **PAC-001
remains prepared and not approved**, **no substantive revision is required
solely because of CGD-001**, and **a fresh readiness reassessment is required**.

**Implementation.** **None. Not authorised.** No root-level change is directed,
the observed topology already corresponding to the approved one (CGD-C07).

**Verification.** **Pending.** A later controlled verification must confirm the
live topology before the mapping is relied on operationally.

**Identifier-family note.** **CGD-001 establishes the `CGD-` family for
controlled CDE-governance decisions in this training implementation.** **Later
use of the family still requires a controlled scope and collision review** — no
future CDE decision belongs to it automatically.

**Decision record.** `docs/CDE-Structure-Governance-Decision.md`. **This entry
is a reference, not a duplicate** — the full decision is not restated here
(BEP 12.13, 13.1).

### AG-003 — Training Publication Arrangement Approver Function

| Field | Value |
|---|---|
| Classification | **APPROVED GOVERNANCE** |
| Topic | Training Publication Arrangement Approver Function |
| Source | Orchestrator decision, Increment 8G-C |
| Training basis | **TA-02** — simulated role participation |
| Scope | **Training Baseline 0.1 publication-arrangement governance only** |
| Status | **FUNCTION ESTABLISHED — PAC-001 APPROVAL DECISION NOT YET TAKEN** |
| Decision owner | Training Publication Arrangement Approver |

**Decision.** Establish the **Training Publication Arrangement Approver**
function, exercised by the **Training Implementation Owner**, for the limited
publication-arrangement governance scope. No personal holder is recorded.

**Arising from.** **PAC-001**, whose register entry recorded *"Decision owner:
Not established — TBD"*; **PRA-001**; **CGD-001**, which removed PRA-B01's
stated basis; and the **Increment 8G-B-R exact review** — 32 checks PASS, zero
failures. **No existing function covered PE-2**: AG-001 is limited to Training
Baseline candidate approval, AG-002 to CDE-structure governance, CGD-001 confers
no arrangement-approval authority, publication / exchange authority remains
unresolved and concerns PE-3, and PAC-001 and PRA-001 carry Authority: None.

**Authority source.** **The authority arises from AG-003 itself.** No
independent authority of the Training Implementation Owner is assumed.

**Authority conferred.** Receive a defined publication-arrangement candidate for
Training Baseline 0.1; receive and review its controlled readiness assessment;
confirm the exact candidate version or repository snapshot; **approve, reject,
defer or approve with explicitly recorded conditions**; record which PM-1 to
PM-7 positions are approved; record every condition to be satisfied before later
PE events; and **authorise the PE-2 governance-status transition** from candidate
arrangement to approved publication arrangement — **only through a later
controlled approval-decision record**.

**Readiness precondition.** **PAC-001 may not be approved unless a fresh
controlled readiness assessment concludes `READY FOR APPROVAL` or `READY FOR
APPROVAL WITH CONDITIONS`.** A historical assessment whose blocker has since
changed is **not sufficient by itself**; **PRA-001 remains historically valid but
cannot be the current approval basis**, and **Increment 8G-D must occur first**.

**Authority NOT conferred.** Project publication / exchange authority;
publication-event authorisation; recipient acceptance authority; upload or
execution authority; CDE administration or implementation authority;
CDE-structure governance under AG-002; Training Baseline approval under AG-001;
professional or design approval; acceptance of project deliverables; folder
creation, renaming, moving or deletion; membership or permission change;
generation or assembly of the publication package; establishment of the naming,
coordinate, titleblock or template standards; resolution of technical
implementation prerequisites by assertion; closure of GCR-005 merely by
establishing the function; approval of PAC-001 before the fresh readiness
assessment; or reaching PE-3 or any later PE event. **Holding this function
confers none of the other authorities.**

**Relationship to PAC-001.** Establishes its **decision owner**. **PAC-001 is
not approved**, remains **PROPOSED GOVERNANCE — NOT APPROVED** with **Authority:
None**, and **no PM position changed**.

**Relationship to PM-2.** **AG-003 establishes the arrangement approver, not the
publication owner proposed by PM-2.** They are different functions: the approver
decides the arrangement at PE-2; the proposed Candidate Publication Owner would
own package identity and readiness. **PM-2 remains `GOVERNANCE DECISION
REQUIRED`**, no holder is appointed, and AG-003 does not pre-empt whether the
proposed owner function should exist.

**Relationship to PE-2 and PE-3.** AG-003 establishes **who may take PE-2**;
**PE-2 is not reached**. **PE-3 requires publication / exchange authority, which
remains UNRESOLVED and is not established here.** **Approving an arrangement
never authorises a publication event.**

**Implementation.** Function documented in
`docs/Training-Publication-Arrangement-Approver-Function-Decision.md`. **No
technical act is authorised or performed.**

**Verification.** **Not yet performed.** The function is established and not yet
exercised.

**Identifier-family note.** **AG-003 extends the `AG-` family as this training
implementation's authority-establishment precedent**, following AG-001 and
AG-002. **Use of the AG family for any later authority decision still requires a
controlled scope and collision review** — no future decision belongs to it
automatically.

**Note.** This entry approves a *governance function*, not an arrangement. **No
arrangement is approved**, **PE-2 is not reached**, **PAC-001 remains not
approved and unamended**, and **the publication hold remains in force**. **This
entry is a reference, not a duplicate** — the full decision is not restated here
(BEP 12.13, 13.1).

### PAD-001 — Publication Arrangement Approval Decision

| Field | Value |
|---|---|
| Classification | **APPROVED GOVERNANCE** |
| Decision outcome | **APPROVE WITH CONDITIONS** |
| Subject | **PAC-001 — Publication Arrangement Candidate 0.1** |
| Assessed candidate snapshot | `532c4ec74f2013461f7fef637c0e6734a11b2dfb` |
| Decision-input repository state | `48a50d31ebe6f4533499074c111b9a000c11208b` |
| **PAC-001 substantive-body hash** | **`4d67dcfcc7556665b3f93f2363b3dfd4`** — byte-identical at both commits |
| Deciding function | **Training Publication Arrangement Approver under AG-003** |
| Functional holder | **Training Implementation Owner** |
| Training basis | **TA-02** — simulated role participation |
| Readiness basis | **PRA-002 — READY FOR APPROVAL WITH CONDITIONS** |
| Scope | **Training Baseline 0.1 publication arrangement only** |
| Source | Orchestrator decision, Increment 8H |
| Status | **PE-2 REACHED — PUBLICATION ARRANGEMENT APPROVED WITH CONDITIONS; PE-3 NOT AUTHORISED** |

**PM dispositions.** **PM-1** location — approved with conditions; container
**not created**, name undecided. **PM-2** owner — approved with conditions;
**function required but NOT established, no holder appointed**; residual status
**OWNER FUNCTION ESTABLISHMENT PENDING**. **PM-3** format and package boundary —
approved with conditions. **PM-4** metadata — approved with conditions.
**PM-5** upload procedure — approved with conditions; **no mechanism selected**.
**PM-6** verification — approved with conditions; **none performed**. **PM-7**
supersession — approved with conditions; **no technical route, no PE-S
authority**.

**Source-companion choice.** **All seven UTF-8 Markdown authoring sources are
expressly INCLUDED as subordinate source companions.** Approved package
boundary: **8 authoritative files** (7 × PDF/A-2b + 1 × UTF-8 JSON manifest) plus
**7 subordinate companions** — **15 package files in total**.

**Condition dispositions.** **C1 SATISFIED AT PE-2 AS TO THE ARRANGEMENT
POSITION; RESIDUAL CONDITION OPEN**; **C2 CARRIED FORWARD**; **C3 SATISFIED AT
PE-2**; **C4 CARRIED FORWARD — ENDURING**; **C5 CARRIED FORWARD**; **C6 CARRIED
FORWARD**.

**Implementation prerequisites.** **P1 to P8 are preserved in full, unweakened
and unreclassified.** **PAD-001 approves governance only and does not satisfy a
prerequisite merely by naming it.**

**GCR-005.** **CLOSED BY PAD-001 — SEVEN PUBLICATION-ARRANGEMENT PARAMETERS
DEFINED; IMPLEMENTATION CONDITIONS AND PREREQUISITES REMAIN.** The seven matters
map one-to-one to PM-1 … PM-7. **The GD-001 / AD-001 historical wording variance
is preserved and not rewritten.** **Defining the parameters does not authorise
publication.**

**Event status.** **PE-1 reached previously; PE-2 REACHED by PAD-001; PE-3 to
PE-S not reached.** **ARRANGEMENT APPROVAL IS NOT PUBLICATION AUTHORISATION.**

**Authority exclusions.** PAD-001 confers **no** publication / exchange
authority, PE-3 authority, upload or execution authority, CDE administration or
implementation authority, recipient acceptance authority, PE-S authority, or
design or professional approval authority. **The function was exercised only
within AG-003's PE-2 scope**, and **holding several training functions does not
merge them**.

**Implementation and verification.** **None. Not authorised.** No container
created, no package generated, no digest calculated, **no publication-package
commit pinned**, and **CGD-001 live verification remains pending**.

**Identifier-family note.** **PAD-001 establishes the `PAD-` family for
controlled publication-arrangement decisions in this training implementation.**
**Later use of the family still requires a controlled scope and collision
review** — no future decision belongs to it automatically.

**Decision record.** `docs/Publication-Arrangement-Approval-Decision.md`.
**This entry is a reference, not a duplicate** — the full decision is not
restated here (BEP 12.13, 13.1).

**Subsequent status — 2026-08-02, Increment 8H-A.** **AG-004 established the
`Training Baseline Publication Owner`** function required by PM-2. **PM-2's
owner-function establishment residual is satisfied**, and its status becomes
**APPROVED WITH CONDITIONS BY PAD-001 — OWNER FUNCTION ESTABLISHED UNDER
AG-004**. **Condition C1 is SATISFIED BY AG-004**; **P6 step 2 is satisfied**
while **P6 overall remains ACTIVE and the publication-package commit remains
NOT PINNED**. **PE-3 remains not reached, publication remains NOT AUTHORISED
and the publication hold remains ACTIVE.** **No PAD-001 decision section is
altered.**

### AG-004 — Training Baseline Publication Owner Function

| Field | Value |
|---|---|
| Classification | **APPROVED GOVERNANCE** |
| Topic | Training Baseline Publication Owner Function |
| Source | Orchestrator decision, Increment 8H-A |
| Decision date | **2026-08-02** |
| Training basis | **TA-02** — simulated role participation |
| Scope | **Training Baseline 0.1 publication-package identity, preparation governance and readiness coordination only** |
| Status | **FUNCTION ESTABLISHED — NO PUBLICATION EVENT AUTHORISED** |
| Decision owner | Training Baseline Publication Owner |

**Decision.** Establish the **Training Baseline Publication Owner** function.
**Functional holder — Training Implementation Owner**, under **TA-02**.
**Personal holder — not recorded**; no personal name appears in this repository.

**Arising from.** **PAD-001 PM-2**, whose approved position is that a distinct
Training Baseline Publication Owner function **is required** and which expressly
**did not establish it or appoint a holder**; **PAD-001 condition C1**, disposed
of as *SATISFIED AT PE-2 AS TO THE ARRANGEMENT POSITION; RESIDUAL CONDITION
OPEN*; **PRA-002 condition C1**, which required separate establishment or
refusal through an authorised decision; **PAD-001 prerequisite P6 step 2**; and
**GCR-005's approved publication-owner parameter**. **No existing function
sufficed**: AG-001 is limited to Training Baseline candidate approval, AG-002 to
CDE-structure governance, AG-003 to PE-2 arrangement approval, CGD-001 confers
no publication-owner authority, and publication / exchange authority remains
unresolved and concerns PE-3.

**Authority source.** **The authority arises from AG-004 itself.** **No
pre-existing independent authority of the Training Implementation Owner is
assumed**, and none is inferred from the Training Implementation Owner label,
repository ownership, project membership, system access, administrative
permissions, AG-001, AG-002, AG-003 or PAD-001.

**Function established.** **Training Baseline Publication Owner** — owner of the
controlled **identity, preparation governance and readiness coordination** of a
future Training Baseline 0.1 publication package. **A simulated training
function**; **no real project appointment, professional authority, contractual
duty or liability is created**.

**Authority conferred.** Maintain the authoritative interpretation of PAD-001's
approved package boundary; identify the exact controlled source content;
maintain the package file inventory — **seven authoritative PDF/A-2b renditions,
one authoritative UTF-8 JSON manifest and seven subordinate UTF-8 Markdown
source companions**; maintain each companion-to-rendition relationship;
coordinate satisfaction of PAD-001 conditions and prerequisites relevant to
package preparation; receive and review evidence that required controls are
satisfied; coordinate minimum naming and presentation controls established
through a separately authorised decision; coordinate selection and testing of
generation and validation routes established through separately authorised
technical controls; identify when the repository state is eligible for later
commit pinning; **propose** the exact publication-package commit for a later
controlled pinning action; maintain package identity and version record after a
commit is later pinned; coordinate manifest data preparation using PAD-001's
approved metadata requirements; prepare or coordinate a package-readiness record
for the future publication / exchange authoriser; identify unresolved
conditions, prerequisites or stop conditions; **stop** package preparation where
approved controls are not satisfied; and **request** a later PE-3 decision from
the appropriately established publication / exchange authority.

**Authority NOT conferred.** Project publication / exchange authority; PE-3
authority; authority to authorise a publication event; PE-4 exercise; technical
upload or execution authority; CDE administration or implementation authority;
folder or container creation, renaming, moving or deletion; permission or
membership change; appointment of the technical executor; acceptance of
deliverables; recipient acceptance authority; PE-S authority; professional or
design approval; change to PAD-001; alteration of the approved package boundary;
conversion of Markdown companions into authoritative documents; establishment of
project-wide naming, coordinate, titleblock or template standards; declaring a
technical prerequisite satisfied without evidence; treating repository access or
CDE permissions as publication authority; pinning the publication-package commit
during Increment 8H-A; or generating, assembling, uploading or publishing a
package during Increment 8H-A. **Holding this function confers none of the other
authorities.**

**Relationship to PAD-001.** **PAD-001 is unchanged in substance** — a dated
subsequent-status note only. PAD-001 approved that the function should exist;
**AG-004 establishes it**. **Arrangement approval, package ownership, event
authorisation, execution and acceptance remain five separate things.**

**Relationship to PM-2.** **PM-2's owner-function establishment residual is
satisfied.** New status: **APPROVED WITH CONDITIONS BY PAD-001 — OWNER FUNCTION
ESTABLISHED UNDER AG-004**. Function established; functional holder assigned
under TA-02; **personal holder not recorded**; **publication / exchange
authority remains unresolved**; **technical execution authority remains
unassigned**; **recipient acceptance authority remains unresolved**. **PM-2
remains an approved-with-conditions arrangement position**, and AG-004 removes
no unrelated PAD-001 condition or prerequisite. **No observation established the
function**, and none could.

**Relationship to C1.** **C1 — SATISFIED BY AG-004.** The arrangement position
was approved by PAD-001; AG-004 now establishes the required function and
records a functional holder. **No publication / exchange authority and no PE-3
authority follows.** **The historical PRA-002 and PAD-001 condition wording is
not rewritten.**

**Relationship to P6.** **Step 2 — *the Training Baseline Publication Owner
function has been separately established* — is SATISFIED by AG-004.** **P6
overall remains ACTIVE — PUBLICATION-PACKAGE COMMIT NOT PINNED.** Step 1
(PAD-001 and its register entry) was already satisfied; **step 3, the required
naming and presentation controls, remains pending (C5)**; **pinning is not
performed**, and **pinning still precedes generation and PE-3**.

**PE-event boundaries.** **PE-1 reached previously; PE-2 reached by PAD-001;
PE-3 through PE-S not reached.** **PE-3 requires publication / exchange
authority, which remains UNRESOLVED and is not established here.** **Owning the
package is not authorising its publication.**

**Implementation.** Function documented in
`docs/Training-Baseline-Publication-Owner-Function-Decision.md`. **No technical
act is authorised or performed** — no container, no permission change, no
toolchain or route selected or tested, no naming or presentation control
established, no CGD-001 verification, no rendition, manifest or digest, no
package, **no pinned commit**.

**Verification.** **Not yet performed.** The function is established and not yet
exercised.

**Current status.** **FUNCTION ESTABLISHED — NO PUBLICATION EVENT AUTHORISED.**
**GCR-005 remains closed at the governance-definition level; GCR-006 remains
OPEN; UD-001 remains unresolved; CGD-001 verification remains pending;
publication remains NOT AUTHORISED with the hold active.**

**Identifier-family note.** **AG-004 extends the `AG-` family as this training
implementation's authority-establishment decision precedent**, following AG-001,
AG-002 and AG-003. **`AG-004` was unused before this record.** **Later use of
the family still requires a controlled scope and collision review** — no future
authority decision belongs to it automatically.

**Note.** This entry establishes a *governance function*. **No publication event
is authorised**, **no package exists**, **no commit is pinned**, and **the
publication hold remains in force**. **This entry is a reference, not a
duplicate** — the full decision is not restated here (BEP 12.13, 13.1).

**Subsequent status — 2026-08-02, Increment 8H-B.** **AG-005 established the
`Training Publication Naming and Presentation Approver`** — **the function that
may later decide the PAD-001 condition C5 controls**. **AG-004 remains the
coordinating function**: its authority-scope item 7 coordinates controls
established through a separately authorised decision, and **that decision route
now exists**. **AG-004 does not approve the controls.** **C5 remains CARRIED
FORWARD**, **P6 step 3 remains pending**, **no publication-package commit was
proposed or pinned**, **PE-3 remains not reached** and **publication remains NOT
AUTHORISED with the hold active**. **No part of this entry is rewritten.**

### AG-005 — Training Publication Naming and Presentation Approver Function

| Field | Value |
|---|---|
| Classification | **APPROVED GOVERNANCE** |
| Topic | Training Publication Naming and Presentation Approver Function |
| Source | Orchestrator decision, Increment 8H-B |
| Decision date | **2026-08-02** |
| Training basis | **TA-02** — simulated role participation |
| Scope | **Training Baseline 0.1 package-specific naming and presentation control governance only** |
| Status | **FUNCTION ESTABLISHED — C5 CONTROL DECISION NOT YET TAKEN** |
| Decision owner | Training Publication Naming and Presentation Approver |

**Decision.** Establish the **Training Publication Naming and Presentation
Approver** function. **Functional holder — Training Implementation Owner**,
under **TA-02**. **Personal holder — not recorded**; no personal name appears in
this repository.

**Arising from.** **PAD-001 condition C5** (`CARRIED FORWARD` — minimum controls
must be established before package assembly, for the seven renditions, the
manifest, the source companions and the proposed child container); **PAD-001
prerequisite P6 step 3**; **AG-004 authority-scope item 7**, which coordinates
controls *established through a separately authorised decision* that did not
exist; the **approved PAD-001 package boundary** of fifteen files; the
**proposed PM-1 child-container position**, whose final name remains undecided;
and the **absence of established project-wide naming and presentation
standards**, with **CGD-C05** recording CDE naming as provisional.

**Authority source.** **The authority arises from AG-005 itself.** **No
pre-existing independent authority of the Training Implementation Owner is
assumed**, and none is inferred from the Training Implementation Owner label,
repository ownership, project membership, system access, administrative
permissions, AG-001, AG-002, AG-003, AG-004, CGD-001 or PAD-001.

**Function established.** **Training Publication Naming and Presentation
Approver** — the function that **may later decide** the minimum package-specific
naming and presentation controls required by C5. **A simulated training
function**; **no real project appointment, professional authority, contractual
duty or liability is created**.

**Authority conferred — through a later controlled decision only.** Receive a
defined package-specific naming and presentation control candidate; review its
traceability to PAD-001, C5 and the approved package boundary; **approve, reject,
defer or approve with explicitly recorded conditions**; define minimum naming
controls for the seven PDF/A-2b renditions, for the authoritative UTF-8 JSON
manifest and for the seven subordinate UTF-8 Markdown source companions; define
the required companion-to-rendition filename relationship; define the minimum
controlled name or naming rule for the proposed PM-1 child container; define
permitted separators, character rules, case rules, extension treatment and token
ordering; define minimum package-specific identity, version, status and
relationship tokens; define minimum presentation requirements identifying each
rendition and its governance status; confirm the controls are internally
coherent and **do not alter PAD-001's approved package boundary**; **determine
through a later controlled decision whether C5 is satisfied**; determine whether
**P6 step 3** is satisfied as a consequence of the approved controls; and record
any residual condition remaining before package assembly or commit pinning.

**Exercise rule.** **AG-005 may be exercised only through a later controlled
decision record.** **No C5 control decision is taken in Increment 8H-B**, and
**no naming pattern, filename, container name or presentation rule is approved**.
**Every later exercise must identify AG-005 as its authority basis and the exact
control candidate and repository state considered.**

**Candidate precondition.** **A controlled C5 candidate must exist before the
approval authority may be exercised.** It must cover, at minimum: the seven
PDF/A-2b renditions; the authoritative UTF-8 JSON manifest; the seven
subordinate Markdown companions; companion-to-rendition relationships; the PM-1
proposed child container; package identity; baseline / version / status
representation; filename characters, separators, case, extensions and ordering;
minimum presentation markings; collision and ambiguity risks; and the
distinction between package-specific controls and project-wide standards. **No
such candidate is created in Increment 8H-B.**

**Authority NOT conferred.** Publication / exchange authority; PE-3 authority;
publication-event authorisation; upload or execution authority; PE-4 authority;
CDE administration or implementation authority; creation, renaming, moving or
deletion of files, folders or containers; permission or membership change;
establishment of project-wide naming standards; establishment of project-wide
coordinate, titleblock or template standards; change to PAD-001; alteration of
the approved package boundary; removal or addition of package-file classes;
making Markdown companions authoritative; generation or assembly of the package;
pinning the publication-package commit; selection or testing of the PDF/A
generation or validation toolchain; selection or testing of the upload
mechanism; verification of CGD-001 live correspondence; recipient acceptance
authority; PE-S authority; professional or design approval; declaring C5
satisfied without a later controlled decision; or declaring P6 step 3 satisfied
without approved C5 controls. **Holding this function confers none of the other
authorities.**

**Relationship to AG-004.** **AG-004 coordinates the controls and may submit or
coordinate a C5 candidate; AG-005 may later decide them.** **AG-004 does not
approve the controls and AG-005 does not own the package.** **AG-004 is
unchanged in substance** — a dated subsequent-status note only. **Coordination
and approval remain separate acts even where one functional holder performs
both.**

**Relationship to C5.** **C5 — DECISION ROUTE ESTABLISHED UNDER AG-005; CONTROL
DECISION PENDING.** **C5's overall status remains CARRIED FORWARD.** AG-005
establishes who may later decide C5; **it does not establish the controls and
does not satisfy C5**. **A later controlled candidate and decision are
required**, and **package assembly remains blocked by C5**. **The historical
PAD-001 and PRA-002 C5 wording is not rewritten.**

**Relationship to P6.** **Step 1 remains satisfied; step 2 remains satisfied by
AG-004; the authority route for step 3 is now established by AG-005 while step 3
itself remains PENDING.** **P6 remains ACTIVE — PUBLICATION-PACKAGE COMMIT NOT
PINNED.** **No commit is proposed or pinned**, and **pinning remains prohibited
before approved C5 controls exist.**

**PE-event boundaries.** **PE-1 reached previously; PE-2 reached by PAD-001;
PE-3 through PE-S not reached.** **PE-3 requires publication / exchange
authority, which remains UNRESOLVED and is not established here.** **Deciding a
name is not authorising a publication.**

**Implementation and verification.** **None, and none is authorised.** No
control approved, no candidate created, no file, folder or container created or
renamed, no permission change, no toolchain or route selected or tested, no
CGD-001 verification, no rendition, manifest or digest, no package, **no
proposed or pinned commit**. **Verification not yet performed** — the function
is established and not yet exercised.

**Current status.** **FUNCTION ESTABLISHED — C5 CONTROL DECISION NOT YET
TAKEN.** **GCR-005 remains closed at the governance-definition level; GCR-006
remains OPEN; UD-001 remains unresolved; CGD-001 verification remains pending;
project standards remain Not established; publication remains NOT AUTHORISED
with the hold active.**

**Identifier-family note.** **AG-005 extends the `AG-` family as this training
implementation's authority-establishment decision precedent**, following AG-001,
AG-002, AG-003 and AG-004. **`AG-005` was unused before this record**, and its
scope overlaps none of them. **Later use of the family still requires a
controlled scope and collision review** — no future authority decision belongs
to it automatically.

**Note.** This entry establishes a *governance function*. **No naming or
presentation control is approved**, **no C5 candidate exists**, **no package
exists**, **no commit is pinned**, and **the publication hold remains in force**.
**This entry is a reference, not a duplicate** — the full decision is not
restated here (BEP 12.13, 13.1). Decision record:
`docs/Training-Publication-Naming-and-Presentation-Approver-Function-Decision.md`.

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

**GCR-005 subsequent status — 2026-08-01, Increment 8H.** The condition row
above is retained as the **historical record at this decision**. **GCR-005 is
now `CLOSED BY PAD-001 — SEVEN PUBLICATION-ARRANGEMENT PARAMETERS DEFINED;
IMPLEMENTATION CONDITIONS AND PREREQUISITES REMAIN`.** The seven matters map to
the approved positions PM-1 to PM-7. **The historical wording here is not
rewritten**, **GCR-006 remains OPEN**, **UD-001 remains unresolved**, and
**publication remains NOT AUTHORISED with the hold ACTIVE**.

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

**GCR-005 subsequent status — 2026-08-01, Increment 8H.** The condition row
above is retained as the **historical record at this decision**. **GCR-005 is
now `CLOSED BY PAD-001 — SEVEN PUBLICATION-ARRANGEMENT PARAMETERS DEFINED;
IMPLEMENTATION CONDITIONS AND PREREQUISITES REMAIN`.** The seven matters map to
the approved positions PM-1 to PM-7. **The historical wording here is not
rewritten**, **GCR-006 remains OPEN**, **UD-001 remains unresolved**, and
**publication remains NOT AUTHORISED with the hold ACTIVE**.

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

## 6D. Readiness assessments

*Non-decisional records. **None carries authority, approves anything, decides
anything or reaches any PE event.** Each is recorded by reference only.*

### NPRA-001 — Training Baseline Naming and Presentation Control Readiness Assessment

| Field | Value |
|---|---|
| Identifier | **NPRA-001** |
| Document status | **CONTROLLED ASSESSMENT** |
| Classification | **ASSESSMENT RECORD — NOT A GOVERNANCE DECISION** |
| **Authority** | **None** |
| Subject | **NPC-001 — Training Baseline Naming and Presentation Control Candidate** |
| Scope | **Readiness of NPC-001 for consideration by AG-005 only** |
| Assessed repository state | `5075677224587e6291ac880d5af6a464471b48fc` |
| Candidate source state | `09c04ff9d84e79d95317206b393e217e3fb209a5` |
| Candidate preparation commit | `08aa680026aebf9bcd7ab67fdc7a46bee48310a3` |
| Assessment date | **2026-08-02** |
| Source | Orchestrator-directed `Authority: None` assessment, Increment 8H-D |
| Training basis | **TA-02** — simulated role participation |
| **Assessment outcome** | **READY FOR AG-005 DECISION WITH CONDITIONS** |
| Status | **ASSESSMENT COMPLETE — ELIGIBLE FOR A SEPARATE AG-005 DECISION AFTER EXACT REVIEW; AG-005 NOT EXERCISED** |
| Assessment document | `docs/Training-Baseline-Naming-and-Presentation-Control-Readiness-Assessment.md` |

**What it is.** The second record of the orchestrator-directed three-record
workflow — candidate, assessment, decision. **It answers all eighteen NPC-001
readiness questions and determines eligibility for an AG-005 decision. It is not
a decision, and it carries no authority.**

**Outcome and basis.** **READY FOR AG-005 DECISION WITH CONDITIONS.** All eleven
AG-005 §6 candidate-precondition matters are covered with substantive content;
twenty-two independent mechanical verifications of the fifteen proposed filenames
returned the expected result; every proposed matter falls within AG-005's §4
authority; no internal rule conflict was found; and PAD-001's package boundary is
preserved exactly. **No candidate amendment is required and no blocker is
recorded.**

**Assessment conditions — matters the later AG-005 decision must address
expressly.** **`A1`** — whether `TB0P1` discharges **PM-4 fields 2 and 4
together**, the candidate providing no filename token distinct from `TB0P1` for
revision/version. **`A2`** — that the `AWC` filename status token is **additive**
to PM-4 field 5's approved document and manifest carriers, PAC-001 §5.1 not
having marked status as filename-carried. **`A3`** — that the container-label
rules and the package-filename rules are **deliberately distinct and apply to
different object classes**. **`A4`** — that the approved controls are
**package-specific and may not be cited as a project-wide standard**. **`A1` to
`A4` are local assessment labels only; they are not repository-wide governance
identifiers and allocate nothing.**

**Residual prerequisites — outside C5, unchanged by the assessment.** `R1`
platform/toolchain compatibility untested (**P2**, **C2**); `R2` CGD-001 live
correspondence unverified (**C6**); `R3` CDE implementation authority not
established (**P7**); `R4` technical executor unassigned (**P7**); `R5` upload
route unconfirmed (**P1**); `R6` destination verification not performed (**P8**);
`R7` publication-package commit not pinned and package content not frozen
(**P6 step 4**). **Decision conditions and technical residuals are kept
separate.**

**Relationship to NPC-001.** **NPC-001 is unchanged in substance** — a dated
subsequent-status note only. It **remains PROPOSED GOVERNANCE — NOT APPROVED**
with **Authority: None**, and **remains unapproved**. **The assessment requires no
amendment to it.**

**Relationship to AG-004.** **AG-004 is unchanged and was not exercised.** It
coordinated the candidate at Increment 8H-C; **it neither performed nor is bound
by this assessment**.

**Relationship to AG-005.** **AG-005 is unchanged in substance** — a dated
subsequent-status note only — and **remains NOT EXERCISED**. The assessment
records that AG-005's §4 authority reaches every matter NPC-001 proposes,
including filename composition, version and status tokens, container naming,
presentation markings, C5 satisfaction and the P6 step 3 consequence. **An exact
read-only review of NPRA-001 is required before any exercise of AG-005.**

**C5 status.** **CARRIED FORWARD.** The assessment's prospective finding is that
**an AG-005 approval could satisfy C5 provided the decision records `A1`–`A4`**.
**NPRA-001 does not satisfy C5.**

**P6 status.** **Step 3 remains pending**; the assessment's prospective finding
is that **approval could satisfy P6 step 3 subject to the same conditions**.
**P6 overall remains ACTIVE — PUBLICATION-PACKAGE COMMIT NOT PINNED**, step 4
being a separate act.

**Publication status.** **NOT AUTHORISED**; hold **ACTIVE**; publication /
exchange authority **UNRESOLVED**; technical executor **unassigned**; CDE
implementation authority **not established**; recipient acceptance authority
**UNRESOLVED**; **PE-2 reached, PE-3 to PE-S not reached**; **no package artefact
exists** and **no publication-package commit is proposed or pinned**.

**Identifier-family note.** **NPRA-001 opens the `NPRA-` family** — *Naming and
Presentation Readiness Assessment*. **`NPRA-001` was unused before this record**,
and the prefix collides with none of the nineteen established families; it is
**distinct from `PRA-`**, which denotes publication-arrangement readiness
assessments, and from **`NPC-`**, which denotes control candidates. **`NPRA-` is
an assessment family only: it carries no authority, approves nothing, decides
nothing and reaches no PE event.** **Later use still requires a controlled scope
and collision review.**

**Note.** This entry records a *non-decisional assessment*. **It is not counted
among the approved-governance entries**, **no naming or presentation control is
approved**, **no package exists**, **no commit is pinned**, and **the publication
hold remains in force**. **This entry is a reference, not a duplicate** — the full
assessment is not restated here (BEP 12.13, 13.1).

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
| 2026-08-02 | NPRA-001 recorded by reference — Training Baseline Naming and Presentation Control Readiness Assessment of NPC-001, performed as the separate controlled Authority None assessment required before AG-005 may be exercised. ASSESSMENT RECORD — NOT A GOVERNANCE DECISION; Authority None; assessed at repository state 5075677; candidate source state 09c04ff; candidate preparation commit 08aa680; none of the three is the publication-package commit. Opens the NPRA- assessment family, expressly limited to non-decisional readiness assessments of package-specific naming and presentation control candidates, carrying no authority and distinct from PRA- and NPC-. Outcome READY FOR AG-005 DECISION WITH CONDITIONS. All eighteen NPC-001 readiness questions answered; all eleven AG-005 candidate-precondition matters found covered with substantive content; twenty-two independent mechanical verifications of the fifteen proposed filenames returned the expected result; every proposed matter found within AG-005's authority scope; no internal rule conflict; PAD-001's package boundary preserved exactly. No candidate amendment required and no blocker recorded. Four assessment conditions for the later decision: A1 whether TB0P1 discharges PM-4 fields 2 and 4 together; A2 that the AWC filename status token is additive to PM-4 field 5's approved document and manifest carriers; A3 that container-label and package-filename rules are deliberately distinct object classes; A4 that the approved controls are package-specific and may not be cited as a project-wide standard. A1 to A4 are local assessment labels, not governance identifiers. Seven residual prerequisites outside C5 recorded as R1 to R7 under existing conditions C2 and C6 and prerequisites P1, P2, P6, P7 and P8. Prospective findings only: an AG-005 approval could satisfy C5 provided the decision records the listed conditions, and could satisfy P6 step 3 subject to the same conditions. Not a decision; NPC-001 unchanged in substance and remains PROPOSED GOVERNANCE — NOT APPROVED with Authority None; AG-004 and AG-005 unchanged in substance and neither exercised; no naming or presentation control approved; no project-wide standard established; no file, container, rendition, manifest or digest created; no package assembled; no commit proposed or pinned; no platform compatibility tested; no external system accessed. PAD-001, PAC-001, PRA-001, PRA-002, AG-001, AG-002, AG-003, CGD-001, AD-001 and GD-001 unchanged; PM-1 to PM-7, C1, C2, C3, C4 and C6 unchanged; P1 to P8 remain active; C5 remains CARRIED FORWARD; P6 step 3 remains pending and P6 remains ACTIVE; PPER-001 to PPER-009 and the PPQ records unchanged; no observation performed. An exact read-only review of NPRA-001 is the next controlled gate and is required before any AG-005 exercise. GCR-005 remains closed at the governance-definition level; GCR-006 remains open; UD-001 remains unresolved; CGD-001 verification remains pending; PE-2 remains reached and PE-3 to PE-S not reached; publication remains NOT AUTHORISED with the hold active. | 8H-D |
| 2026-08-02 | Documentary corrections arising from the read-only Increment 8H-C-R exact review of NPC-001. NPC-001's Future decision function header field corrected: it had named the function with an interpolated word belonging to AG-003's function name, and now reads AG-005's established function name "Training Publication Naming and Presentation Approver under AG-005", matching AG-005's title and function-name field. Two NPC-001 internal cross-references corrected: the §8.1 manifest sentence had cited a subsection that does not exist and now cites §§7.2–7.3, and the §11.1 PM-4 routing citation had carried an incorrect section number and now reads §15, question 15. PAC-001's current proposed-governance summary bullet now distinguishes its historical document classification from PAD-001's subsequent approval of its substantive arrangement, while preserving that PAC-001 itself assigned no authority and authorised no publication and that PAD-001 reached PE-2 only. The Increment 8H-C change-log statement corrected to record six unchanged approved baseline source documents and the intentional update of source document 7, that no source document was renamed, that the seven controlled paths remained valid, that the document-token map is path-based and unaffected, and that no commit was identified as the publication-package commit. No proposal content or naming control changed; no token, filename, grammar rule, token-map entry, inventory item, companion relationship, container-name proposal, presentation marking, manifest rule, source-companion rule or collision statement altered. No readiness question was answered, all eighteen remain Unanswered, and no assessment occurred. AG-005 was not exercised and no governance approval occurred; no identifier was allocated. NPC-001 remains PROPOSED GOVERNANCE — NOT APPROVED with Authority None and status CANDIDATE PREPARED — NOT ASSESSED — NOT APPROVED. C5 remains CARRIED FORWARD and P6 step 3 remains pending with P6 ACTIVE; no package or commit was created, proposed or pinned; project-wide standards remain Not established; PE-2 remains reached and PE-3 to PE-S not reached; publication remains NOT AUTHORISED with the hold active. | 8H-C-R-A |
| 2026-08-02 | NPC-001 recorded by reference — Training Baseline Naming and Presentation Control Candidate prepared for PAD-001 condition C5 as PROPOSED GOVERNANCE — NOT APPROVED, Authority None, status CANDIDATE PREPARED — NOT ASSESSED — NOT APPROVED, at repository state 09c04ff. Coordinated under AG-004 as a candidate-coordination and submission act only; AG-004 did not approve it. Opens the NPC- candidate family, expressly limited to package-specific naming and presentation control candidates and carrying no authority; no collision with the eighteen established prefixes. Proposes a token dictionary (HFS, TB0P1, AWC, SOURCE, MANIFEST plus seven document tokens), a three-form filename grammar, fourteen character and format rules, an exhaustive seven-document token map, an exact fifteen-file inventory matching PAD-001's approved boundary, a companion-to-rendition stem rule with a seven-row reconciliation, the child-container name Training Baseline 0.1 under 03. Published, package-specific first-page and footer presentation markings, a manifest identity rule using PAD-001's PM-4 metadata set unchanged, a byte-faithful source-companion rule and a thirteen-point collision and ambiguity assessment. Not a decision; no naming rule, filename, container name or presentation rule established; no project-wide naming, coordinate, titleblock or template standard established; no file, folder, container, rendition, manifest or digest created; no package assembled; no commit proposed or pinned; no platform compatibility tested. AG-005 not exercised and no C5 decision taken; a separate controlled Authority None readiness assessment remains required and was not performed; eighteen readiness questions remain unanswered. PAD-001, PAC-001, PRA-001, PRA-002, AG-001, AG-002, AG-003, CGD-001, AD-001 and GD-001 unchanged. Six of the seven approved baseline source documents were unchanged; supporting/governance-decision-register.md, baseline source document 7, was intentionally updated during Increment 8H-C to record NPC-001. No baseline source document was renamed, the seven controlled repository paths remained valid, and the document-token mapping was unaffected because it maps repository paths and not file-content hashes. No repository commit was identified as the publication-package commit; PM-1 to PM-7, C1, C2, C3, C4 and C6 unchanged; P1 to P8 remain active; P6 step 3 CANDIDATE PREPARED — NOT ASSESSED — NOT SATISFIED and P6 remains ACTIVE; PPER-001 to PPER-009 and the PPQ records unchanged; no observation performed; C5 remains CARRIED FORWARD; GCR-005 remains closed at the governance-definition level; GCR-006 remains open; UD-001 remains unresolved; CGD-001 verification remains pending; PE-2 remains reached and PE-3 to PE-S not reached; publication remains NOT AUTHORISED with the hold active. | 8H-C |
| 2026-08-02 | AG-005 recorded — Training Publication Naming and Presentation Approver function established as APPROVED GOVERNANCE, arising from PAD-001 condition C5, PAD-001 prerequisite P6 step 3, AG-004 authority-scope item 7, the approved fifteen-file package boundary, the proposed PM-1 child-container position and the absence of established project-wide naming and presentation standards. Functional holder Training Implementation Owner under TA-02; no personal holder recorded; the authority arises from AG-005 itself and from no label, ownership, membership, access, permission, AG-001, AG-002, AG-003, AG-004, CGD-001 or PAD-001. Scope limited to package-specific naming and presentation control governance; eighteen authority-scope items exercisable only through a later controlled decision, and only against a controlled C5 candidate covering eleven minimum matters. Establishes who may later decide C5; decides nothing. No control candidate created, no naming pattern, filename, container name or presentation rule approved, no project-wide standard established. C5 remains CARRIED FORWARD with its decision route established and its control decision pending; P6 step 1 and step 2 remain satisfied, step 3 remains pending with its authority route now established, P6 remains ACTIVE and no publication-package commit was proposed or pinned. PAD-001 unmodified; AG-004 unchanged in substance and remains the coordinating function; PM-1 to PM-7, C1, C2, C3, C4 and C6 unchanged; P1 to P8 remain active; PPER-001 to PPER-009 and the PPQ records unchanged; no observation performed; no package artefact; no publication/exchange, PE-3, execution, CDE implementation or recipient acceptance authority conferred; GCR-005 remains closed at the governance-definition level; GCR-006 remains open; UD-001 remains unresolved; CGD-001 verification remains pending; PE-2 remains reached and PE-3 to PE-S not reached; publication remains NOT AUTHORISED with the hold active. | 8H-B |
| 2026-08-02 | AG-004 recorded — Training Baseline Publication Owner function established as APPROVED GOVERNANCE, arising from PAD-001 PM-2, PAD-001 condition C1, PRA-002 condition C1, PAD-001 prerequisite P6 step 2 and GCR-005's approved publication-owner parameter. Functional holder Training Implementation Owner under TA-02; no personal holder recorded; the authority arises from AG-004 itself and from no label, ownership, membership, access, permission, AG-001, AG-002, AG-003 or PAD-001. Scope limited to package identity, preparation governance and readiness coordination for the 15-file approved boundary. PM-2's owner-function establishment residual satisfied, status now APPROVED WITH CONDITIONS BY PAD-001 — OWNER FUNCTION ESTABLISHED UNDER AG-004; C1 SATISFIED BY AG-004; P6 step 2 satisfied while P6 overall remains ACTIVE and the publication-package commit remains unpinned. No publication/exchange, PE-3, execution, CDE implementation or recipient acceptance authority conferred; PAD-001 unchanged in substance; PM-1 and PM-3 to PM-7 unchanged; C2, C4, C5 and C6 carried forward; C3 remains satisfied; P1 to P8 otherwise unchanged; PPER-001 to PPER-009 unchanged; no observation performed; no package artefact; GCR-005 remains closed at the governance-definition level; GCR-006 remains open; UD-001 remains unresolved; CGD-001 verification remains pending; PE-2 remains reached and PE-3 to PE-S not reached; publication remains NOT AUTHORISED with the hold active. | 8H-A |
| 2026-07-31 | Register populated as a controlled draft. TA-01, TA-02, TA-03 transcribed from BEP 2.6. OF-001 to OF-005 recorded. UD-001 detail recorded from the observed condition. | 3A |
| 2026-08-01 | Increment 7C validation evidence incorporated. OF-001 to OF-005 reconfirmed; UD-001 evidence updated and left unresolved; OF-006, OF-007 and OF-008 recorded as OBSERVED FACT. | 7D |
| 2026-08-01 | AG-001 recorded — Training Baseline Approval Function established as APPROVED GOVERNANCE. First approved-governance entry. Baseline 0.1 remains unapproved. | 7G |
| 2026-08-01 | GD-001 recorded — Gate C PASS for candidate snapshot cc146a5f. AG-001 verification completed through Increment 7H. Baseline 0.1 remains unapproved; publication hold active. | 7I |
| 2026-08-01 | AD-001 recorded — Training Baseline 0.1 APPROVED WITH CONDITIONS for the governance basis assessed at cc146a5f. Register status advanced to APPROVED WITH CONDITIONS. GCR-005, GCR-006 and UD-001 remain open; publication/exchange and recipient acceptance authority remain unresolved; project standards remain Not established; publication remains NOT AUTHORISED with the hold active. | 7J |
| 2026-08-01 | ROA-001 recorded by reference — one bounded read-only Publication Planning observation AUTHORISED WITH CONSTRAINTS, covering PPQ-001 to PPQ-007 in a single session, expiring on that session's completion report. Not yet exercised. No authority assigned; GCR-005, GCR-006 and UD-001 remain open; publication remains NOT AUTHORISED with the hold active. | 8C-A |
| 2026-08-01 | PAC-001 recorded by reference — Publication Arrangement Candidate 0.1 prepared for PM-1 to PM-7 as PROPOSED GOVERNANCE — NOT APPROVED. Not a decision; no governance-decision identifier allocated; no authority assigned; no publication authorised. PM matters remain unresolved; GCR-005 and GCR-006 remain open; publication remains NOT AUTHORISED with the hold active. | 8F |
| 2026-08-01 | PAD-001 recorded — Publication Arrangement Approval Decision, APPROVE WITH CONDITIONS, taken by the Training Publication Arrangement Approver under AG-003 on the readiness basis PRA-002. Subject PAC-001, substantive body hash 4d67dcfcc7556665b3f93f2363b3dfd4, identical at 532c4ec and 48a50d3. All PM-1 to PM-7 positions approved with conditions; PM-2 residual OWNER FUNCTION ESTABLISHMENT PENDING; seven UTF-8 Markdown source companions expressly included, giving 15 package files. Conditions C1 and C3 satisfied at PE-2, C2, C4, C5 and C6 carried forward; P1 to P8 preserved unweakened. GCR-005 CLOSED at the governance-definition level with the GD-001 and AD-001 historical wording preserved. PE-2 reached; PE-3 to PE-S not reached; no publication, container, package, digest or pinned commit; CGD-001 verification pending; GCR-006 remains open; UD-001 remains unresolved; publication remains NOT AUTHORISED with the hold active. | 8H |
| 2026-08-01 | PRA-002 recorded by reference — fresh Publication Arrangement Readiness Reassessment of PAC-001 at repository state 532c4ec, outcome READY FOR APPROVAL WITH CONDITIONS. PRA-B01's original blocking dependency was resolved by CGD-001 and now assesses as PASS; no current BLOCKER remains. Six later conditions (C1 to C6) and eight implementation prerequisites (P1 to P8) carried forward, including pending CGD-001 live verification, unconfirmed upload and retrieval routes, unproven PDF/A-2b producibility, and absent implementation authority. Not a decision; no governance-decision identifier allocated; PAC-001 remains PROPOSED GOVERNANCE — NOT APPROVED and unamended; AG-003 not exercised; PE-2 not reached; PM-2 remains GOVERNANCE DECISION REQUIRED; GCR-005 and GCR-006 remain open; publication remains NOT AUTHORISED with the hold active. | 8G-D |
| 2026-08-01 | AG-003 recorded — Training Publication Arrangement Approver function established as APPROVED GOVERNANCE, arising from PAC-001, PRA-001, CGD-001, the Increment 8G-B-R exact review and PAC-001's unresolved decision-owner field. Establishes who may later take the PE-2 arrangement-approval decision; approves nothing. PAC-001's decision owner advanced from "Not established — TBD" to Training Publication Arrangement Approver under AG-003, while PAC-001 remains PROPOSED GOVERNANCE — NOT APPROVED and unamended. A fresh readiness assessment concluding READY FOR APPROVAL or READY FOR APPROVAL WITH CONDITIONS is a mandatory precondition; PRA-001 is not the current basis. PM-2 remains GOVERNANCE DECISION REQUIRED; no publication/exchange, acceptance or implementation authority conferred; PE-2 through PE-S not reached; GCR-005 and GCR-006 remain open; publication remains NOT AUTHORISED with the hold active. | 8G-C |
| 2026-08-01 | CGD-001 recorded — CDE Structure Governance Decision, APPROVE WITH CONDITIONS, taken by the Training CDE Governance Approver under AG-002. The as-found four-area root topology (0. Common Files, 01. WIP, 02. Shared, 03. Published) is adopted as the intended training CDE governance, with the intended state mapping and conditions CGD-C01 to CGD-C08. OF-001 resolved at governance level; its historical "intended state not defined" record preserved. No retrospective effect; no child folder, discipline structure or team-space mapping approved; UD-001 remains unresolved; naming remains provisional; no Autodesk configuration change authorised and none directed at root level; verification pending. PAC-001 remains not approved and unamended, PRA-001's original outcome remains historically valid, PE-2 not reached, publication remains NOT AUTHORISED with the hold active. | 8G-B |
| 2026-08-01 | AG-002 recorded — Training CDE Governance Approver function established as APPROVED GOVERNANCE, arising from OF-001, PRA-B01, PRA-001 and the Increment 8G-R authority-boundary review. Establishes who may decide OF-001; decides nothing. OF-001's decision owner advanced from "Not established — TBD" to Training CDE Governance Approver under AG-002, while its intended state remains "Not defined" and the matter remains unresolved. No structural outcome selected; no implementation, publication/exchange, acceptance or CDE administration authority conferred. PRA-B01 remains open, PAC-001 remains not approved and unamended, publication remains NOT AUTHORISED with the hold active. | 8G-A |
| 2026-08-01 | PRA-001 recorded by reference — Publication Arrangement Readiness Assessment of PAC-001, outcome NOT READY FOR APPROVAL. Sole principal blocker PRA-B01: PM-1 depends on OF-001, whose intended CDE structure remains undefined. Five findings are approval conditions and six are implementation prerequisites; none independently prohibits later arrangement approval. Not a decision; no governance-decision identifier allocated; PAC-001 neither approved nor rejected and not amended; no authority assigned; no publication authorised; PE-2 not reached. OF-001, GCR-005 and GCR-006 remain open; publication remains NOT AUTHORISED with the hold active. | 8G |
| 2026-08-01 | PAC-001 refined — PM-3's candidate format position completed (PDF/A-2b renditions, UTF-8 JSON manifest, optional UTF-8 Markdown source companions, SHA-256 digests) following the Increment 8F-R review, which returned 30 checks PASS and 1 FAIL. Classification and status unchanged: PAC-001 remains PROPOSED GOVERNANCE — NOT APPROVED. No authority assigned; no publication authorised; no new identifier allocated. GCR-005 and GCR-006 remain open; publication remains NOT AUTHORISED with the hold active. | 8F-A |
| 2026-08-01 | ROA-001 status advanced to EXERCISED ONCE — EXPIRED. The authorised observation was performed as Increment 8D and recorded as EC-3 evidence (PPER-004 to PPER-009, all assessed and insufficient); no mutation reported. PM-1 to PM-7 remain UNRESOLVED and no candidate arrangement is prepared. No authority assigned; GCR-005, GCR-006 and UD-001 remain open; publication remains NOT AUTHORISED with the hold active. | 8E |

**Note on histories.** This change log records *decision and register* history.
Git commit history records *source* history. They are complementary and not
interchangeable — a commit shows that wording changed; it does not show that a
decision was taken (BEP 9.11, 12.10).
