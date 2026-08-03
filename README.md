# Harrismith Fire Station — BIM Management / BIM Execution Plan

Controlled authoring repository for the Harrismith Fire Station BIM Management
and BIM Execution Plan (BEP) training implementation.

**Status:** The management-document system is **APPROVED WITH CONDITIONS** as
**Training Baseline 0.1** (AD-001, 2026-08-01). That is a training / reference
baseline approval with active conditions — **nothing is published, issued,
delivered or accepted**, and **publication remains NOT AUTHORISED**. Current
maturity is stated in section 5.

---

## 1. Purpose

This repository is the **authoring source** for the Harrismith Fire Station BIM
Execution Plan and its supporting information-management resources.

It exists to:

- hold the approved document architecture under version control;
- provide a reviewable history of how information-management governance was
  developed;
- separate *drafting and review* from *issue and publication*;
- support a training implementation in which the reasoning behind each
  governance decision is explicit and traceable.

**Teaching material.** The BIM Management teaching and presentation programme
built on this material is in [`teaching/`](teaching/). Like the BIM Delivery
Guide, it **explains only** — it carries no governance authority and is not part
of the controlled document architecture in section 3.

---

## 2. Authoring source vs issued CDE artefacts

This is the single most important distinction in this repository.

| | Authoring source | Issued artefact |
|---|---|---|
| **Location** | this Git repository | Autodesk Common Data Environment |
| **Nature** | drafts, working text, proposals | approved, issued, controlled deliverables |
| **Authority** | none until approved | contractual / project authority |
| **Change control** | Git commits and review | CDE state and revision control |

Content in this repository carries **no project authority** until it has been
reviewed, approved, and published into the CDE through the controlled route
described in section 4.

### 2.1 Prohibition on direct CDE writes

The Autodesk Desktop Connector / ACCDocs tree is **out of bounds** for this
repository and for any tooling operating on it.

There must be **no** symlink, junction, bind mount, automatic synchronisation,
or other filesystem link between this repository and the Autodesk CDE.

Specifically prohibited from this repository:

- reading from, writing to, creating, renaming, moving or deleting anything in
  the Desktop Connector / ACCDocs tree;
- any automated or scripted synchronisation into the CDE;
- any change to Autodesk Forma, ACC, Desktop Connector, Revit, Navisworks or
  other external project systems.

Publication into the CDE is a **manual, controlled, human-performed** act.

---

## 3. Repository architecture

```
harrismith-bep/
├── README.md        repository governance and safety boundary
├── bep/             the main BIM Execution Plan
├── supporting/      the six supporting management resources
├── working/         working process, workshop material, in-progress thinking
├── guidance/        the BIM Delivery Guide
├── standards/       referenced project standards
├── output/          generated / project-facing artefacts (NOT authoring source)
└── docs/            repository-level documentation and process notes
```

### 3.1 Main BIM Execution Plan — `bep/`

Approved section architecture (Architecture Baseline v1):

1. Document Purpose and Status
2. Project Information
3. BIM and Information Management Objectives
4. Project Organisation and Task Teams
5. Information Management Roles and Responsibilities
6. Common Data Environment Strategy
7. Information Production and Sharing
8. Model and Information Coordination
9. Review, Approval and Authorisation
10. Information Delivery and Exchange
11. Standards and Project Conventions
12. Governance, Change and Exceptions
13. Controlled References

### 3.2 Supporting management resources — `supporting/`

1. Information Management Responsibility Matrix
2. Model / Information Responsibility Matrix
3. Information Delivery Schedule
4. CDE Workflow & State Strategy
5. Coordination & Review Strategy
6. Governance & Decision Register

### 3.3 Working, guidance and standards

- `working/` — the Working Process and workshop material. Working thinking,
  not governance.
- `guidance/` — the BIM Delivery Guide: practical, explanatory support for
  delivery teams.
- `standards/` — referenced project standards for Naming, Coordinates,
  Titleblocks, and Templates / authoring conventions.

### 3.4 Output — `output/`

`output/` holds **generated and project-facing artefacts** produced from the
authoring source.

`output/` is **not** the authoring source. It is never edited directly, and
nothing in it is authoritative merely by being present.

---

## 4. Controlled route to the CDE

```
local Git authoring source
    → review
    → approved baseline
    → manual controlled publication to Autodesk Forma / Data Management
```

Each arrow is a deliberate, recorded step. No step is automated in this
repository.

---

## 5. Gate status

| Gate | Status |
|---|---|
| Discovery Gate A | Complete |
| Architecture Gate B | Complete — frozen as **Architecture Baseline v1** |
| Implementation Increment 1 | Complete — repository scaffold |
| Implementation Increment 2A | Complete — BEP sections 1–3 drafted, revised after review |
| Implementation Increment 2B | Complete — BEP sections 4–5 drafted |
| Implementation Increment 2C | Complete — BEP sections 6–7 drafted |
| Implementation Increment 2D | Complete — BEP sections 8–10 drafted |
| Implementation Increment 2E | Complete — BEP sections 11–13 drafted; main BEP draft complete |
| Implementation Increment 3A | Complete — Governance & Decision Register and Information Management Responsibility Matrix populated as controlled drafts |
| Implementation Increment 3B | Complete — Model / Information Responsibility Matrix and Information Delivery Schedule populated as controlled drafts |
| Implementation Increment 3C | Complete — CDE Workflow & State Strategy populated as a controlled draft |
| Implementation Increment 3D | Complete — Coordination & Review Strategy populated as a controlled draft |
| Implementation Increment 4 | Complete — Working Process implemented as a controlled draft |
| Implementation Increment 5 | Complete — BIM Delivery Guide implemented as a Controlled Draft |
| Implementation Increment 6A | Complete — cross-document consistency audit performed; result **PASS WITH FINDINGS** |
| Implementation Increment 6B | Complete — audit corrections applied |
| Implementation Increment 7A (first attempt) | Halted at read-only pre-flight — further stale statements found; no candidate created |
| Implementation Increment 6C | Complete — pre-candidate stale-language corrections applied |
| Implementation Increment 7A (re-attempt) | Complete — **Training Baseline 0.1 Candidate** prepared for review |
| Implementation Increment 7B | Complete — candidate review; result **PASS WITH FINDINGS**; ready for live-project validation |
| Implementation Increment 7C | Complete — live-project validation through read-only connector and manual UI evidence; **no candidate contradiction found**; observed-fact update required |
| Implementation Increment 7D | Complete — validated observed facts incorporated into the candidate record |
| Implementation Increment 7E | Complete — post-update candidate review; result **PASS** |
| Implementation Increment 7F | Complete — Gate C readiness assessment; **conditional Gate C pass recommended**; approval function identified as the pre-approval condition |
| Implementation Increment 7G | Complete — **Training Baseline Approver** function established as approved training governance (**AG-001**) |
| Implementation Increment 7H | Complete — approval function verified; result **READY FOR GATE C DECISION** |
| Implementation Increment 7I | Complete — **Gate C PASSED** for candidate snapshot `cc146a5f…` (**GD-001**) |
| Implementation Increment 7I-A / 7I-B | Complete — companion-document factual status corrections; no governance changed |
| Implementation Increment 7J | Complete — **Training Baseline 0.1 APPROVED WITH CONDITIONS** (**AD-001**) |
| Implementation Increment 7J-A | Complete — dated subsequent-status references added to **GD-001** recording the later **AD-001** approval; historical Gate C record preserved; no governance changed |
| Implementation Increment 8A | Complete — Publication Planning control framework established; **no publication arrangement selected, no authority assigned** |
| Implementation Increment 8A-A | Complete — Increment 7J-A restored to this table; roadmap traceability only, **no historical decision changed, no governance changed, no Publication Planning work performed** |
| Implementation Increment 8B | Complete — Publication Planning evidence and observation control register established; **no evidence assessed, no question drafted, no observation authorised** |
| Implementation Increment 8B-A | Complete — **EC-9** aligned into the Increment 8A framework as a dated additive extension, EC-1 to EC-8 unchanged; Increment 8A-A roadmap traceability restored; **no authority assigned, no question drafted or authorised** |
| Implementation Increment 8C | Complete — seven exact read-only observation questions drafted (`PPQ-001`–`PPQ-007`), all **READY FOR GOVERNANCE REVIEW**; **none authorised, asked or answered; no observation performed; PM-2 excluded** |
| Implementation Increment 8C-A | Complete — PPQ questions refined where necessary and **authorised under ROA-001 for one bounded read-only observation**; observation brief prepared but **not sent**; **no observation performed, no evidence recorded, no authority assigned** |
| Implementation Increment 8D | Complete — the single bounded read-only observation completed under **ROA-001**; **no mutation occurred** and **ROA-001 expired** on its completion report; **no repeat observation authorised** |
| Implementation Increment 8E | Complete — observation recorded and evidence assessed (**PPER-004**–**PPER-009**, EC-3, all insufficient); final PPQ statuses recorded; **all PM matters remain UNRESOLVED, no publication arrangement selected, no authority assigned** |
| Implementation Increment 8F | Complete — **Publication Arrangement Candidate 0.1 (PAC-001)** prepared for PM-1 to PM-7; **PROPOSED GOVERNANCE — NOT APPROVED**; **no arrangement approved, no authority assigned, no publication authorised**. Next stage: **Increment 8G** candidate review |
| Implementation Increment 8F-A | Complete — PAC-001's **PM-3 format position completed**: seven **PDF/A-2b** renditions, one **UTF-8 JSON** manifest and **SHA-256** integrity records proposed; **candidate remains NOT APPROVED, no authority assigned, no publication authorised**. **Increment 8G** remains the next stage |
| Implementation Increment 8G | Complete — **Publication Arrangement Readiness Assessment (PRA-001)**; outcome **NOT READY FOR APPROVAL**, sole blocker **PRA-B01** — PM-1 depends on the unresolved **OF-001** CDE-structure decision. **PAC-001 remains prepared and NOT APPROVED, and is not rejected; no authority assigned, no publication authorised, PE-2 not reached.** Next controlled stage: **resolve the OF-001 dependency** |
| Implementation Increment 8G-A | Complete — **AG-002** established the **Training CDE Governance Approver**, a training-only function under **TA-02** authorised to decide **OF-001** later. **OF-001 was not decided** — its intended state remains undefined; **PAC-001 remains not approved and unamended; PRA-B01 remains open; no publication or implementation authority was conferred.** Next stage: the **full OF-001 CDE-structure decision** |
| Implementation Increment 8G-B | Complete — **CGD-001** approved **with conditions**: the as-found **four-area root topology** (`0. Common Files`, `01. WIP`, `02. Shared`, `03. Published`) adopted as intended training CDE governance. **OF-001 resolved at governance level**; **no retrospective authorisation, no child structures approved, no Autodesk change or implementation authorised, verification pending**. **PAC-001 remains not approved**; PRA-B01's dependency is resolved but **a fresh readiness assessment is required**. Next stage: **Increment 8G-C** |
| Implementation Increment 8G-C | Complete — **AG-003** established the **Training Publication Arrangement Approver**, a simulated function under **TA-02** that **may take a later PE-2 arrangement-approval decision**. **PAC-001 was not approved**; the **fresh readiness reassessment is still required**; **publication/exchange authority remains UNRESOLVED**; **no publication or implementation was authorised**. Next stage: **Increment 8G-D** |
| Implementation Increment 8G-D | Complete — **PRA-002** fresh readiness reassessment; outcome **READY FOR APPROVAL WITH CONDITIONS**. **PRA-B01's dependency resolved by CGD-001** and **no current PE-2 blocker remains**; six conditions and eight implementation prerequisites carried forward. **PAC-001 remains NOT APPROVED, PE-2 not reached, AG-003 not exercised, publication remains NOT AUTHORISED.** Next possible stage: **Increment 8H** |
| Implementation Increment 8H | Complete — **PAD-001** recorded; outcome **APPROVE WITH CONDITIONS**, **AG-003 exercised**. **All PM-1 to PM-7 positions approved with conditions**; the **seven Markdown source companions included as subordinate files** (15 package files); **GCR-005 CLOSED at the governance-definition level**. **PE-2 reached; PE-3 NOT reached; publication remains NOT AUTHORISED and the hold remains ACTIVE**; **P1–P8 and residual conditions remain**. Next controlled stage: **exact PAD-001 review** |
| Implementation Increment 8H-R-A | Complete — corrected stale post-PAD-001 current-state summaries in this README and in §11 of the Publication Planning Evidence and Observation Control Register. **No governance decision amended, no authority exercised, no function established, no PE event reached**; **publication remains NOT AUTHORISED and the publication hold remains ACTIVE**. Next controlled stage: **Increment 8H-A** |
| Implementation Increment 8H-A | Complete — **AG-004** established the **Training Baseline Publication Owner**, functional holder the **Training Implementation Owner** under **TA-02**, no personal holder recorded. **PM-2's owner-function establishment residual is satisfied**; **condition C1 is SATISFIED BY AG-004**; **P6 step 2 is satisfied** while **P6 overall remains ACTIVE and the publication-package commit remains unpinned**. **Publication/exchange authority remains UNRESOLVED; PE-3 remains NOT reached; publication remains NOT AUTHORISED and the publication hold remains ACTIVE.** Next controlled stage: **exact AG-004 review** |
| Implementation Increment 8H-B | Complete — **AG-005** established the **Training Publication Naming and Presentation Approver**, functional holder the **Training Implementation Owner** under **TA-02**, no personal holder recorded. **The C5 decision route is established; the C5 controls are not decided and no control candidate exists.** **C5 remains CARRIED FORWARD**; **P6 step 3 remains pending** and **P6 remains ACTIVE**; **the publication-package commit remains unpinned**. **Publication/exchange authority remains UNRESOLVED; PE-3 remains NOT reached; publication remains NOT AUTHORISED and the publication hold remains ACTIVE.** Next possible stage: **preparation of a controlled C5 candidate** |
| Implementation Increment 8H-C | Complete — **NPC-001** prepared: the **Training Baseline Naming and Presentation Control Candidate** for **PAD-001 condition C5**, **coordinated under AG-004**, classified **PROPOSED GOVERNANCE — NOT APPROVED** with **Authority: None**. Defines an **exact fifteen-file naming candidate** (7 PDF/A-2b + 1 JSON manifest + 7 Markdown source companions), the proposed **PM-1 container name `Training Baseline 0.1`** and **minimum package-specific PDF publication markings**. **No project-wide naming, coordinate, titleblock or template standard is established**; **the candidate is not assessed or approved and AG-005 was not exercised**. **C5 remains CARRIED FORWARD**; **P6 step 3 remains pending**; **the publication-package commit remains unpinned**; **publication remains NOT AUTHORISED and the publication hold remains ACTIVE**. Next controlled stage: **exact candidate review**, after which a **separate readiness assessment** follows |
| Implementation Increment 8H-C-R-A | Complete — corrected the **five documentary defects** found by the exact NPC-001 review: the **AG-005 function name** in NPC-001's header, **two internal cross-references** (`§§7.2–7.3` and `§15, question 15`), the **PAC-001 historical/current-status wording** in the Governance & Decision Register, and the **Increment 8H-C source-document statement** (six unchanged; source document 7 intentionally updated). **No candidate proposal changed, no readiness question was answered, no assessment was performed and AG-005 was not exercised.** **C5 remains CARRIED FORWARD**; **P6 step 3 remains pending**; **the publication-package commit remains unpinned**; **publication remains NOT AUTHORISED and the publication hold remains ACTIVE**. Next controlled stage: **exact corrective review** |
| Implementation Increment 8H-D | Complete — **NPRA-001** performed: the **Training Baseline Naming and Presentation Control Readiness Assessment** of **NPC-001**, classified **ASSESSMENT RECORD — NOT A GOVERNANCE DECISION** with **Authority: None**. Outcome **READY FOR AG-005 DECISION WITH CONDITIONS** — **four assessment conditions `A1`–`A4`** (the `TB0P1` dual PM-4 carrier, the additive `AWC` status carrier, the container/filename form distinction and the project-wide scope bar) and **seven residual prerequisites `R1`–`R7`** outside C5. **All eighteen NPC-001 readiness questions assessed; no blocker; no candidate amendment required.** **AG-005 was not exercised and NPC-001 remains NOT APPROVED.** **C5 remains CARRIED FORWARD**; **P6 step 3 remains pending**; **the publication-package commit remains unpinned**; **publication remains NOT AUTHORISED and the publication hold remains ACTIVE**. Next controlled stage: **exact NPRA-001 review** |
| Implementation Increment 8H-D-R-A | Complete — corrected the **two assessment-status propagation defects** found by the exact NPRA-001 review: a **dated subsequent-status note** was added to the Governance & Decision Register's **NPC-001** entry recording the **NPRA-001** assessment, and the Publication Planning register's **C5 control-candidate row** was corrected to distinguish the **preserved original candidate status** from the **current assessed position**. **NPC-001's original candidate status is preserved as historical provenance**; **no candidate or assessment content changed**, and **NPRA-001's outcome, `A1`–`A4` and `R1`–`R7` are unchanged**. **AG-005 was not exercised and NPC-001 remains NOT APPROVED.** **C5 remains CARRIED FORWARD**; **P6 step 3 remains pending**; **the publication-package commit remains unpinned**; **publication remains NOT AUTHORISED and the publication hold remains ACTIVE**. Next controlled stage: **exact corrective review** |
| Implementation Increment 8H-D-R-A-B | Complete — corrected the **four residual current-state statements** that still described **NPC-001** as unassessed: the Governance & Decision Register's **§1 proposed-governance bullet**, its **§5 readiness-assessment paragraph**, its **§5 C5 status** and its **§5 P6 step 3 status**. Each now records that NPC-001 was **prepared on 2026-08-02 as an `Authority: None` candidate and unassessed at that date**, that **NPRA-001 subsequently assessed it** with outcome **READY FOR AG-005 DECISION WITH CONDITIONS**, and that **NPC-001 remains NOT APPROVED**. **Preparation-state wording is retained only where labelled as historical provenance**; **the eighteen readiness questions are preserved unchanged in NPC-001, with the assessment answers held in NPRA-001**. The Publication Planning register's **§11 preamble was advanced to Increment 8H-D-R-A-B**; **no §11 row changed**. **NPC-001, NPRA-001 and AG-005 were not amended; `A1`–`A4` and `R1`–`R7` are unchanged; AG-005 was not exercised.** **C5 remains CARRIED FORWARD and unsatisfied**; **P6 step 3 remains pending and unsatisfied**; **no naming or presentation control is established**; **the publication-package commit remains unpinned**; **publication remains NOT AUTHORISED and the publication hold remains ACTIVE**. Next controlled stage: **exact corrective review** |
| Implementation Increment 8H-E | Complete — **AG-005 exercised once** and the **PAD-001 condition C5 control decision taken**: **`NPC-001` APPROVED WITH CONDITIONS `A1`–`A4`**, on the readiness basis **NPRA-001**. **The approval is package-specific to the fifteen-file `TB0P1` Training Baseline 0.1 package and its proposed PM-1 child container — no project-wide naming, coordinate, titleblock or template standard is established.** **`A1`–`A4` are mandatory conditions of the approved control and are not yet implemented**; **`R1`–`R7` remain separate technical and implementation prerequisites and none is closed**. **`C5` is SATISFIED BY AG-005** and **`P6` step 3 is SATISFIED BY AG-005**, at the governance-decision level only; **P6 remains ACTIVE and no publication-package commit was proposed or pinned**. **No package was generated and PE-3 was not authorised**; **publication remains NOT AUTHORISED and the publication hold remains ACTIVE**. Next controlled stage: **exact AG-005 decision review** |
| Implementation Increment 8H-E-R-A | Complete — corrected the **NPC-001 approval-status propagation defect** found by the exact AG-005 decision review: the Publication Planning register's **§11 C5 control-candidate row** no longer states that NPC-001 remains unapproved. **The historical candidate classification `PROPOSED GOVERNANCE — NOT APPROVED`, the `Authority: None` position and the candidate-status field are preserved and expressly labelled as the position at preparation**, distinguished from the current status. **AG-005 was not exercised again and its decision is unamended** — **`NPC-001` remains APPROVED WITH CONDITIONS `A1`–`A4`**, package-specific to `TB0P1`. **`A1`–`A4` remain mandatory and not yet implemented**; **`R1`–`R7` remain separate and open**. **`C5` and `P6` step 3 remain SATISFIED BY AG-005**; **P6 remains ACTIVE and no publication-package commit is proposed or pinned**; **publication remains NOT AUTHORISED and the publication hold remains ACTIVE**. Next controlled stage: **exact corrective review** |

All 13 main BEP sections now contain substantive draft content.

This means the main BEP is **structurally complete**. It does not mean the BEP is
approved, baselined, issued to the CDE, validated against the live project, or
ready for contractual use.

All six supporting management resources are substantively populated: the
Governance & Decision Register, the Information Management Responsibility
Matrix, the Model / Information Responsibility Matrix, the Information Delivery
Schedule, the CDE Workflow & State Strategy and the Coordination & Review
Strategy. The **Working Process** and the **BIM Delivery Guide** are implemented
as companion documents. The project standards remain unpopulated.

The **Training Baseline 0.1 Candidate** was prepared and assessed. Its scope,
authority boundary and exclusions are recorded in
[`docs/Training-Baseline-0.1-Candidate.md`](docs/Training-Baseline-0.1-Candidate.md).

The baseline status is **APPROVED WITH CONDITIONS**. That is a training /
reference-implementation approval with active conditions, not an unconditional
approval and not an authorisation to publish:

- **Training Baseline 0.1 is APPROVED WITH CONDITIONS through AD-001
  (2026-08-01) — see
  [`docs/Training-Baseline-0.1-Approval-Decision.md`](docs/Training-Baseline-0.1-Approval-Decision.md);**
- **the AD-001 conditions remain active — the publication hold, GCR-005,
  GCR-006, UD-001, the two unresolved authority gaps and the four Not
  established project standards;**
- **candidate review and live-project validation are complete; live validation
  found no candidate contradiction, and its observed facts are incorporated —
  see [`docs/Increment-7C-Live-Validation-Record.md`](docs/Increment-7C-Live-Validation-Record.md);**
- **the Training Baseline Approver function is established as approved training
  governance (AG-001), implemented and verified;**
- **Gate C is PASSED for the identified candidate snapshot (GD-001,
  2026-08-01) — see
  [`docs/Training-Baseline-0.1-Gate-C-Decision.md`](docs/Training-Baseline-0.1-Gate-C-Decision.md).
  Gate C PASS authorised progression to an approval decision and nothing more;**
- **a complete governed coordination cycle has not been demonstrated — GCR-006
  remains outstanding;**
- **publication remains NOT AUTHORISED and the publication hold remains active —
  nothing has been published, issued, delivered or accepted;**
- **UD-001 remains unresolved;**
- **the project standards remain Not established and are outside the candidate.**

**Phase 8 — Publication Planning is the current phase.** It defines the
governance needed to address GCR-005 and to establish a controlled basis for a
later publication-authorisation decision. The control framework for that work is
[`docs/Publication-Planning-Control-Framework.md`](docs/Publication-Planning-Control-Framework.md),
and its evidence and observation questions are controlled through
[`docs/Publication-Planning-Evidence-and-Observation-Control-Register.md`](docs/Publication-Planning-Evidence-and-Observation-Control-Register.md).
Both carry **no authority**, select no publication arrangement and assign no
authority. One bounded read-only observation was carried out under **ROA-001**
and is recorded in
[`docs/Increment-8D-Publication-Planning-Read-Only-Observation-Record.md`](docs/Increment-8D-Publication-Planning-Read-Only-Observation-Record.md);
**ROA-001 has since expired, no publication arrangement was selected and no
authority was assigned.** A candidate arrangement —
[`docs/Publication-Arrangement-Candidate-0.1.md`](docs/Publication-Arrangement-Candidate-0.1.md)
(**PAC-001**) — was **prepared as a proposed arrangement** and has since been
**approved with conditions**; it is retained as the **historical proposal
record**. It was first assessed at Increment 8G through
[`docs/Publication-Arrangement-Readiness-Assessment.md`](docs/Publication-Arrangement-Readiness-Assessment.md)
(**PRA-001**), outcome **NOT READY FOR APPROVAL**, whose sole blocker
**PRA-B01** was PM-1's dependency on the then unresolved **OF-001**
CDE-structure decision. **PRA-001 remains the historically valid initial
assessment and PRA-B01 remains intact as the blocker identified at that earlier
state**, but neither is the current readiness position: **CGD-001**
subsequently resolved PRA-B01's CDE-structure dependency, and
[`docs/Publication-Arrangement-Readiness-Reassessment.md`](docs/Publication-Arrangement-Readiness-Reassessment.md)
(**PRA-002**) then concluded **READY FOR APPROVAL WITH CONDITIONS**. On that
basis
[`docs/Publication-Arrangement-Approval-Decision.md`](docs/Publication-Arrangement-Approval-Decision.md)
(**PAD-001**) **exercised AG-003** and **reached PE-2**, approving **PM-1 to
PM-7 with conditions**. **GCR-005 is closed only at the governance-definition
level**, and **conditions C1 to C6 and implementation prerequisites P1 to P8
continue according to PAD-001**. The **Training Baseline Publication Owner**
function required by PM-2 has since been established by **AG-004** —
[`docs/Training-Baseline-Publication-Owner-Function-Decision.md`](docs/Training-Baseline-Publication-Owner-Function-Decision.md)
— so **PM-2's owner-function establishment residual and condition C1 are
satisfied** and **P6 step 2 is satisfied**; **AG-004 owns package identity,
preparation governance and readiness coordination only** and **authorises no
publication event**. **P6 otherwise remains ACTIVE, publication/exchange
authority remains UNRESOLVED, PE-3 through PE-S remain not reached, publication
remains NOT AUTHORISED and the publication hold remains ACTIVE; no package
exists and no publication-package commit has been pinned.**

Architecture Baseline v1 is **frozen**. The document architecture recorded in
section 3 is not to be redesigned during implementation increments. Proposed
changes to the architecture are raised as an UNRESOLVED DECISION in
`supporting/governance-decision-register.md` and resolved through an explicit
gate, not through incremental editing.

---

## 6. Statement classification

All content in this repository classifies its statements using these terms,
consistently and explicitly:

| Term | Meaning |
|---|---|
| **OBSERVED FACT** | Verified from the live project or a controlled source. |
| **TRAINING ASSUMPTION** | Adopted for the training implementation; not verified as project truth. |
| **PROPOSED GOVERNANCE** | Drafted for consideration. Carries no authority. |
| **APPROVED GOVERNANCE** | Reviewed and approved. Carries authority within its scope. |
| **UNRESOLVED DECISION** | Known open question. Explicitly not answered. |

Two standing rules:

- **Assumptions are never silently converted into facts.** A TRAINING
  ASSUMPTION is promoted to OBSERVED FACT only by verification, and the
  promotion is recorded.
- **Known live-project discrepancies are never silently corrected.** Where the
  live project differs from what governance would suggest, the discrepancy is
  recorded as an OBSERVED FACT and carried as an UNRESOLVED DECISION until it
  is deliberately resolved.

---

## 7. Development approach

This repository is developed through **scoped controlled increments**. The method
below is an enduring working rule, not a description of any particular phase.

- **Each increment has an explicitly defined and approved scope.** Work stays
  inside it.
- **Repository state is verified before modification.** Branch, worktree and
  commit are checked at pre-flight, and unexpected state stops the increment.
- **A contradiction causes STOP and REPORT, not silent repair.** Where a document
  appears to conflict with another controlled resource, the conflict is raised
  rather than quietly patched in whichever file is open.
- **Changes are made as atomic commits** and are reviewed before the next
  increment begins.
- **Controlled resources declare their own status, version and authority.**
  Reference from one document does not constitute approval of another.
- **Later phases may revise any resource through governed change**, including
  supersession or withdrawal.
- **Current maturity is stated by section 5 and the gate table above** — not by
  wording embedded in the body of controlled documents.

No increment beyond the one currently approved is to be started without explicit
approval.
