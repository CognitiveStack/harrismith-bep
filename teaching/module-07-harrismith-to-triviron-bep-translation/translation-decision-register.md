# Module 7 — Translation Decision Register

**Status:** **`REGISTER BASELINE — ACCEPTED after T7-C-R`**

**`TEACHING / TRANSLATION CONTROL — NOT TRIVIRON GOVERNANCE`**

**The register records what must be established for a future project-specific
Triviron BEP. It does not establish those answers.**

This register implements the accepted schema in
[`translation-decision-register-schema.md`](translation-decision-register-schema.md)
and is bounded by the STOP register in [`README.md`](README.md) §9 and the STOP
rule in [`translation-framework.md`](translation-framework.md) §2.5. It is not
a Triviron BEP, not Triviron governance, and not a proposal register.

**Evidence position (fixed):**
**`NO CONTROLLED TRIVIRON GOVERNANCE FACT IDENTIFIED IN T7-A`.** No controlled
repository source introduced since T7-A establishes otherwise. Field 8 is
therefore **`NONE IDENTIFIED`** in every row. `NONE IDENTIFIED` is not
`NONE EXISTS`.

---

## 1. Register conventions

- **Rows:** exactly **21**, `TDR-001`–`TDR-021` — the seven accepted decision
  domains × their three questions, from the accepted Module 6 → Module 7
  handoff. No other row may be added without an authorised increment.
- **Fields:** all 20 schema fields appear in every row, numbered as in the
  schema.
- **Field 4 status abbreviation:** `AWC-TB0.1` abbreviates the declared status
  **APPROVED WITH CONDITIONS — Training Baseline 0.1** (`AD-001`, 2026-08-01;
  conditions active; publication NOT AUTHORISED). Source classes A–F are those
  of [`source-inventory.md`](source-inventory.md).
- **Field 11 fixed value for this baseline:**
  **`NOT POPULATED — PROPOSAL STAGE NOT AUTHORISED`** — no candidate Triviron
  decision exists, and none may be written until a proposal stage is expressly
  authorised.
- **Field 12 convention:** only the **kind** of authority is identified, where
  it follows from the question; every holder is `NOT YET ESTABLISHED`. No
  Triviron role, holder or function is named or invented.
- **Classification ceiling for this baseline:** only `METHOD` and
  `EVIDENCE REQUIRED` are used. `DECISION REQUIRED`, `PROPOSAL` and
  `ESTABLISHED` are unreachable — the prerequisite Triviron evidence has not
  been identified.
- Secondary teaching references are always marked
  **`TEACHING INTERPRETATION — NOT GOVERNANCE`**. No PowerPoint is a source.

---

## 2. Domain 1 — Coordination governance

### TDR-001 — What is the approved purpose of coordination?

| # | Field | Value |
|---|---|---|
| 1 | Decision ID | `TDR-001` |
| 2 | Decision domain | 1 — Coordination governance |
| 3 | Decision topic | The approved purpose of coordination on the future Triviron project |
| 4 | Harrismith reference pattern | `bep/Harrismith-Fire-Station-BEP.md` §8.1–§8.2 — AWC-TB0.1 — class A; `supporting/coordination-review-strategy.md` §1–§2 — AWC-TB0.1, content largely `PROPOSED GOVERNANCE` — class B |
| 5 | What transfers as method | Coordination purpose must be explicitly governed, stated in a controlled document, and distinguished from software capability |
| 6 | What explicitly does not transfer | Harrismith's stated coordination purpose and principles text; its project context and training framing |
| 7 | Triviron evidence required | Appointment/contract information; client / appointing-party information requirements; project brief; a coordination requirement or governance decision record stating the project's coordination purpose |
| 8 | Triviron evidence currently available | `NONE IDENTIFIED` |
| 9 | Triviron evidence missing | Controlled Triviron coordination-purpose decision or requirement not identified |
| 10 | Current translation classification | `EVIDENCE REQUIRED` |
| 11 | Candidate decision | `NOT POPULATED — PROPOSAL STAGE NOT AUTHORISED` |
| 12 | Decision authority required | Required authority type: project coordination-governance authority — holder `NOT YET ESTABLISHED` |
| 13 | Decision owner | `NOT YET ESTABLISHED` |
| 14 | Candidate BEP destination | Main BEP clause; coordination / review strategy — exact destination `NOT YET ESTABLISHED` |
| 15 | Dependent matrix / schedule / appendix | Coordination / review strategy |
| 16 | Implementation dependency | A controlled Triviron governance decision adopting the purpose, before any coordination arrangement is configured or operated |
| 17 | Open question | What is coordination *for* on this project — and which document controls that statement? |
| 18 | Status | `NOT YET ESTABLISHED` |
| 19 | Source / decision references | Class A/B as field 4; Module 6 Slide 14 group 1 — `TEACHING INTERPRETATION — NOT GOVERNANCE` |
| 20 | Notes / boundary warning | Overclaim risk: reading Harrismith's purpose text as a default answer. STOP `M7-S15`, `M7-S18` |

### TDR-002 — What is the controlling governance document for coordination?

| # | Field | Value |
|---|---|---|
| 1 | Decision ID | `TDR-002` |
| 2 | Decision domain | 1 — Coordination governance |
| 3 | Decision topic | Which controlled document governs Triviron coordination, and how subordinate resources relate to it |
| 4 | Harrismith reference pattern | `bep/Harrismith-Fire-Station-BEP.md` §1.4–§1.5, §8.13, §13.6 — AWC-TB0.1 — class A; `supporting/coordination-review-strategy.md` (its own status declaration and stated subordination to the BEP) — AWC-TB0.1 — class B |
| 5 | What transfers as method | A governing document must be identified; detail may be expressly deferred to a subordinate resource that declares its own status; reference does not constitute approval |
| 6 | What explicitly does not transfer | Harrismith's document set, the BEP/strategy split itself, and any Harrismith document title or architecture |
| 7 | Triviron evidence required | Project delivery strategy; governance decision record establishing the Triviron information-management document architecture and precedence |
| 8 | Triviron evidence currently available | `NONE IDENTIFIED` |
| 9 | Triviron evidence missing | Controlled Triviron document-architecture and precedence decision not identified |
| 10 | Current translation classification | `EVIDENCE REQUIRED` |
| 11 | Candidate decision | `NOT POPULATED — PROPOSAL STAGE NOT AUTHORISED` |
| 12 | Decision authority required | Required authority type: project information-management governance authority — holder `NOT YET ESTABLISHED` |
| 13 | Decision owner | `NOT YET ESTABLISHED` |
| 14 | Candidate BEP destination | Main BEP clause — exact destination `NOT YET ESTABLISHED` |
| 15 | Dependent matrix / schedule / appendix | Coordination / review strategy; decision register |
| 16 | Implementation dependency | A controlled Triviron BEP architecture within which precedence can be declared |
| 17 | Open question | Which Triviron document governs coordination meaning, and what may it defer? |
| 18 | Status | `NOT YET ESTABLISHED` |
| 19 | Source / decision references | Class A/B as field 4; Module 6 source-inventory hierarchy — `TEACHING INTERPRETATION — NOT GOVERNANCE` |
| 20 | Notes / boundary warning | Overclaim risk: implying the Harrismith two-tier BEP/strategy architecture is already Triviron's. STOP `M7-S14`, `M7-S15` |

### TDR-003 — What constitutes and triggers one coordination cycle?

| # | Field | Value |
|---|---|---|
| 1 | Decision ID | `TDR-003` |
| 2 | Decision domain | 1 — Coordination governance |
| 3 | Decision topic | The definition of one Triviron coordination cycle and its trigger (event basis or frequency) |
| 4 | Harrismith reference pattern | `bep/Harrismith-Fire-Station-BEP.md` §8.8 — AWC-TB0.1 — class A; `supporting/coordination-review-strategy.md` §17, §20 — AWC-TB0.1, `PROPOSED GOVERNANCE` — class B; recorded terminology variance 1 (S1 "triage findings" as one step vs S2 findings→triage as two) carried, not reconciled |
| 5 | What transfers as method | A cycle must be defined as a governed sequence with an entry condition and an evidence-retaining tail; its trigger is a governance choice, not a software rhythm; wording variances between sources are recorded, never silently harmonised |
| 6 | What explicitly does not transfer | Harrismith's cycle-step wording (either variant), its meeting arrangements, and any implied frequency |
| 7 | Triviron evidence required | Coordination requirement; project delivery strategy; governance decision record defining the cycle and its trigger |
| 8 | Triviron evidence currently available | `NONE IDENTIFIED` |
| 9 | Triviron evidence missing | Controlled Triviron cycle-definition and trigger decision not identified |
| 10 | Current translation classification | `EVIDENCE REQUIRED` |
| 11 | Candidate decision | `NOT POPULATED — PROPOSAL STAGE NOT AUTHORISED` |
| 12 | Decision authority required | Required authority type: project coordination-governance authority — holder `NOT YET ESTABLISHED` |
| 13 | Decision owner | `NOT YET ESTABLISHED` |
| 14 | Candidate BEP destination | Coordination / review strategy — exact destination `NOT YET ESTABLISHED` |
| 15 | Dependent matrix / schedule / appendix | Information-delivery schedule (event linkage) |
| 16 | Implementation dependency | Agreed input-container set and readiness conditions (TDR-007, TDR-008) before any cycle could run |
| 17 | Open question | What is *one* cycle for Triviron, and what starts it? |
| 18 | Status | `NOT YET ESTABLISHED` |
| 19 | Source / decision references | Class A/B as field 4; Module 6 source-inventory variance register — `TEACHING INTERPRETATION — NOT GOVERNANCE` |
| 20 | Notes / boundary warning | Overclaim risk: presenting the Harrismith sequence as a ready-made Triviron workflow. STOP `M7-S15`, `M7-S13` |

## 3. Domain 2 — Roles and authority

### TDR-004 — Who coordinates?

| # | Field | Value |
|---|---|---|
| 1 | Decision ID | `TDR-004` |
| 2 | Decision domain | 2 — Roles and authority |
| 3 | Decision topic | Which Triviron function coordinates, and who holds it |
| 4 | Harrismith reference pattern | `supporting/information-management-responsibility-matrix.md` §3.5 (`X1` organise inputs · `X2` manage the process) — AWC-TB0.1, split content rule — class B; `bep/Harrismith-Fire-Station-BEP.md` §5.6, §5.11 — AWC-TB0.1 — class A; `supporting/governance-decision-register.md` `TA-02` (all holders simulated/TBD) — class C |
| 5 | What transfers as method | Coordination is allocated to a *function*, separated from any holder; functions must be separated from persons and organisations; an unfilled holder is recorded as a typed absence, not filled by assumption |
| 6 | What explicitly does not transfer | Harrismith's role model, the `X1`–`X5` allocation, the BIM Manager / BIM Coordinator constructs, and every Harrismith holder position (themselves `TBD` under `TA-02`) |
| 7 | Triviron evidence required | Organisation chart; appointment/contract information; responsibility / authority decision allocating the coordination function |
| 8 | Triviron evidence currently available | `NONE IDENTIFIED` |
| 9 | Triviron evidence missing | Controlled Triviron coordination-function allocation not identified |
| 10 | Current translation classification | `EVIDENCE REQUIRED` |
| 11 | Candidate decision | `NOT POPULATED — PROPOSAL STAGE NOT AUTHORISED` |
| 12 | Decision authority required | Required authority type: project role-and-authority allocation authority — holder `NOT YET ESTABLISHED` |
| 13 | Decision owner | `NOT YET ESTABLISHED` |
| 14 | Candidate BEP destination | Main BEP clause; responsibility matrix — exact destination `NOT YET ESTABLISHED` |
| 15 | Dependent matrix / schedule / appendix | Responsibility matrix |
| 16 | Implementation dependency | Controlled authority allocation, before any platform permission is configured to follow it |
| 17 | Open question | Which function coordinates for Triviron — and is it one function or several? |
| 18 | Status | `NOT YET ESTABLISHED` |
| 19 | Source / decision references | Class A/B/C as field 4; Module 2 and Module 6 role teaching — `TEACHING INTERPRETATION — NOT GOVERNANCE` |
| 20 | Notes / boundary warning | Overclaim risk: naming a Triviron BIM Coordinator by habit. STOP `M7-S01`, `M7-S04`, `M7-S16` |

### TDR-005 — Who owns each technical response?

| # | Field | Value |
|---|---|---|
| 1 | Decision ID | `TDR-005` |
| 2 | Decision domain | 2 — Roles and authority |
| 3 | Decision topic | Ownership of technical resolution of coordination matters within Triviron task teams |
| 4 | Harrismith reference pattern | `supporting/information-management-responsibility-matrix.md` §3.5 `X3` (resolve technically) — AWC-TB0.1 — class B; `supporting/coordination-review-strategy.md` §16, §18 (originating task team resolves in its own WIP; coordinator coordinates, does not design) — AWC-TB0.1, `PROPOSED GOVERNANCE` — class B |
| 5 | What transfers as method | Coordination ≠ design: the coordinating function manages the process while the originating team owns the technical response in its own working environment; allocation is not performance |
| 6 | What explicitly does not transfer | Harrismith's task-team structure, discipline codes, party groupings and the `X3` allocation itself |
| 7 | Triviron evidence required | Discipline / task-team structure; responsibility / authority decision allocating technical-response ownership |
| 8 | Triviron evidence currently available | `NONE IDENTIFIED` |
| 9 | Triviron evidence missing | Controlled Triviron task-team structure and technical-response allocation not identified |
| 10 | Current translation classification | `EVIDENCE REQUIRED` |
| 11 | Candidate decision | `NOT POPULATED — PROPOSAL STAGE NOT AUTHORISED` |
| 12 | Decision authority required | Required authority type: project role-and-authority allocation authority — holder `NOT YET ESTABLISHED` |
| 13 | Decision owner | `NOT YET ESTABLISHED` |
| 14 | Candidate BEP destination | Responsibility matrix — exact destination `NOT YET ESTABLISHED` |
| 15 | Dependent matrix / schedule / appendix | Responsibility matrix; coordination / review strategy |
| 16 | Implementation dependency | An established Triviron task-team structure (TDR-005 evidence) and container allocation (TDR-007) |
| 17 | Open question | Which Triviron teams exist, and which owns each kind of technical response? |
| 18 | Status | `NOT YET ESTABLISHED` |
| 19 | Source / decision references | Class B as field 4; Module 6 Slides 9–10 teaching — `TEACHING INTERPRETATION — NOT GOVERNANCE` |
| 20 | Notes / boundary warning | Overclaim risk: transplanting Harrismith's discipline/party structure. STOP `M7-S01`, `M7-S15` |

### TDR-006 — Who verifies, and when is verification required?

| # | Field | Value |
|---|---|---|
| 1 | Decision ID | `TDR-006` |
| 2 | Decision domain | 2 — Roles and authority |
| 3 | Decision topic | The Triviron verification function and whether verification is mandatory in every cycle |
| 4 | Harrismith reference pattern | `bep/Harrismith-Fire-Station-BEP.md` §8.10 (*"may verify"*) — AWC-TB0.1 — class A; `supporting/coordination-review-strategy.md` §19 (defined step) — AWC-TB0.1, `PROPOSED GOVERNANCE` — class B; `supporting/information-management-responsibility-matrix.md` §3.5 `X4`, §3.7 `A4` (*"No single universal verifier is defined"*) — class B. **Recorded variance 4 — permissive vs definite — carried, not reconciled** |
| 5 | What transfers as method | Verification is a distinct act allocated to a function, with prerequisites and evidence; whether it is mandatory in every cycle is itself a governance decision — and an unresolved source variance must be carried visibly, not resolved by convenience |
| 6 | What explicitly does not transfer | Harrismith's `X4`/`A4` allocations, its verification wording in either variant, and the Harrismith position that no universal verifier is defined |
| 7 | Triviron evidence required | Verification requirement; responsibility / authority decision allocating verification and deciding its mandatoriness |
| 8 | Triviron evidence currently available | `NONE IDENTIFIED` |
| 9 | Triviron evidence missing | Controlled Triviron verification allocation and mandatoriness decision not identified |
| 10 | Current translation classification | `EVIDENCE REQUIRED` |
| 11 | Candidate decision | `NOT POPULATED — PROPOSAL STAGE NOT AUTHORISED` |
| 12 | Decision authority required | Required authority type: project role-and-authority allocation authority — holder `NOT YET ESTABLISHED` |
| 13 | Decision owner | `NOT YET ESTABLISHED` |
| 14 | Candidate BEP destination | Main BEP clause; coordination / review strategy — exact destination `NOT YET ESTABLISHED` |
| 15 | Dependent matrix / schedule / appendix | Responsibility matrix |
| 16 | Implementation dependency | Verified evidence requirement (TDR-016, TDR-017) and controlled authority allocation |
| 17 | Open question | Who verifies for Triviron — and must every cycle be verified, or only some? |
| 18 | Status | `NOT YET ESTABLISHED` |
| 19 | Source / decision references | Class A/B as field 4; Module 6 recorded-absence register — `TEACHING INTERPRETATION — NOT GOVERNANCE` |
| 20 | Notes / boundary warning | Overclaim risk: resolving the Harrismith may-verify variance on Triviron's behalf. STOP `M7-S01`, `M7-S13`, `M7-S16` |

## 4. Domain 3 — Inputs and federation

### TDR-007 — Which information containers enter each coordination cycle?

| # | Field | Value |
|---|---|---|
| 1 | Decision ID | `TDR-007` |
| 2 | Decision domain | 3 — Inputs and federation |
| 3 | Decision topic | The controlled set of Triviron information containers admitted to a coordination cycle |
| 4 | Harrismith reference pattern | `supporting/model-information-responsibility-matrix.md` §3.1 (six discipline containers), §3.4 (`COORD-01` as a separately recorded coordination construct) — AWC-TB0.1, allocations `PROPOSED GOVERNANCE` — class B; `supporting/coordination-review-strategy.md` §4 (input register) — class B |
| 5 | What transfers as method | Cycle inputs are a governed, registered set of containers with recorded originators — not whatever is visible in the platform; a coordination construct is recorded separately from deliverable containers |
| 6 | What explicitly does not transfer | Harrismith's container references, the six-discipline set, `COORD-01`, and its party/task-team mapping |
| 7 | Triviron evidence required | Information-container inventory; discipline / task-team structure; coordination requirement identifying admissible inputs |
| 8 | Triviron evidence currently available | `NONE IDENTIFIED` |
| 9 | Triviron evidence missing | Controlled Triviron container inventory and cycle-input decision not identified |
| 10 | Current translation classification | `EVIDENCE REQUIRED` |
| 11 | Candidate decision | `NOT POPULATED — PROPOSAL STAGE NOT AUTHORISED` |
| 12 | Decision authority required | Required authority type: project coordination-governance authority — holder `NOT YET ESTABLISHED` |
| 13 | Decision owner | `NOT YET ESTABLISHED` |
| 14 | Candidate BEP destination | Responsibility matrix; coordination / review strategy — exact destination `NOT YET ESTABLISHED` |
| 15 | Dependent matrix / schedule / appendix | Responsibility matrix; information-delivery schedule |
| 16 | Implementation dependency | Agreed input-container set, itself dependent on an established container inventory |
| 17 | Open question | Which Triviron containers exist, and which are coordination inputs? |
| 18 | Status | `NOT YET ESTABLISHED` |
| 19 | Source / decision references | Class B as field 4; Module 5/6 container teaching — `TEACHING INTERPRETATION — NOT GOVERNANCE` |
| 20 | Notes / boundary warning | Overclaim risk: reusing Harrismith container names or `COORD-01`. STOP `M7-S15`, `M7-S02` |

### TDR-008 — What readiness conditions apply to those inputs?

| # | Field | Value |
|---|---|---|
| 1 | Decision ID | `TDR-008` |
| 2 | Decision domain | 3 — Inputs and federation |
| 3 | Decision topic | The entry conditions an input must satisfy before a Triviron coordination cycle may consume it |
| 4 | Harrismith reference pattern | `supporting/coordination-review-strategy.md` §5 (readiness) — AWC-TB0.1, `PROPOSED GOVERNANCE` — class B; `supporting/cde-workflow-state-strategy.md` `T3` (coordination input is a use and context, not a state) — AWC-TB0.1, `PROPOSED GOVERNANCE` — class B |
| 5 | What transfers as method | Readiness must be defined before federation; visible ≠ selected ≠ suitable ≠ ready; consuming an input for coordination changes no information state |
| 6 | What explicitly does not transfer | Harrismith's readiness conditions themselves and its state-model mapping (`T3`, the eight steps) |
| 7 | Triviron evidence required | Coordination requirement; CDE / platform governance decision defining input readiness and its relationship to information states |
| 8 | Triviron evidence currently available | `NONE IDENTIFIED` |
| 9 | Triviron evidence missing | Controlled Triviron readiness-condition decision not identified |
| 10 | Current translation classification | `EVIDENCE REQUIRED` |
| 11 | Candidate decision | `NOT POPULATED — PROPOSAL STAGE NOT AUTHORISED` |
| 12 | Decision authority required | Required authority type: project coordination-governance authority — holder `NOT YET ESTABLISHED` |
| 13 | Decision owner | `NOT YET ESTABLISHED` |
| 14 | Candidate BEP destination | Coordination / review strategy; CDE strategy — exact destination `NOT YET ESTABLISHED` |
| 15 | Dependent matrix / schedule / appendix | CDE strategy |
| 16 | Implementation dependency | An established Triviron information-state model against which readiness can be expressed |
| 17 | Open question | What makes a Triviron input *ready* — and who says so? |
| 18 | Status | `NOT YET ESTABLISHED` |
| 19 | Source / decision references | Class B as field 4; Module 4/6 state teaching — `TEACHING INTERPRETATION — NOT GOVERNANCE` |
| 20 | Notes / boundary warning | Overclaim risk: importing the Harrismith state model with readiness attached. STOP `M7-S02`, `M7-S15` |

### TDR-009 — How is originator responsibility preserved through federation?

| # | Field | Value |
|---|---|---|
| 1 | Decision ID | `TDR-009` |
| 2 | Decision domain | 3 — Inputs and federation |
| 3 | Decision topic | Preserving authorship, technical ownership and deliverable status when Triviron inputs are federated |
| 4 | Harrismith reference pattern | `supporting/coordination-review-strategy.md` §8 (federation) — AWC-TB0.1, `PROPOSED GOVERNANCE` — class B; `bep/Harrismith-Fire-Station-BEP.md` §8 (federation boundary) — AWC-TB0.1 — class A |
| 5 | What transfers as method | **Federation is a lens: it transfers no authorship, no technical ownership and no deliverable status.** The structural principle is reusable as stated |
| 6 | What explicitly does not transfer | Harrismith's federation arrangement, its federated-model construct and any platform mechanism that implements the boundary |
| 7 | Triviron evidence required | Coordination requirement or governance decision record adopting a federation-responsibility rule for the project |
| 8 | Triviron evidence currently available | `NONE IDENTIFIED` |
| 9 | Triviron evidence missing | Controlled Triviron federation-responsibility adoption not identified |
| 10 | Current translation classification | `METHOD` — the reusable structural distinction is the row's content; no responsible candidate decision can yet be framed |
| 11 | Candidate decision | `NOT POPULATED — PROPOSAL STAGE NOT AUTHORISED` |
| 12 | Decision authority required | Required authority type: project coordination-governance authority — holder `NOT YET ESTABLISHED` |
| 13 | Decision owner | `NOT YET ESTABLISHED` |
| 14 | Candidate BEP destination | Coordination / review strategy — exact destination `NOT YET ESTABLISHED` |
| 15 | Dependent matrix / schedule / appendix | Responsibility matrix |
| 16 | Implementation dependency | Controlled adoption of the rule before any federated environment is operated |
| 17 | Open question | How will Triviron state, and evidence, that federation moved no responsibility? |
| 18 | Status | `NOT YET ESTABLISHED` |
| 19 | Source / decision references | Class A/B as field 4; Module 6 Slide 4 teaching — `TEACHING INTERPRETATION — NOT GOVERNANCE` |
| 20 | Notes / boundary warning | Overclaim risk: treating the principle's reusability as evidence Triviron has adopted it. STOP `M7-S15`, `M7-S18` |

## 5. Domain 4 — Checks and tolerances

### TDR-010 — Which interfaces and check types apply?

| # | Field | Value |
|---|---|---|
| 1 | Decision ID | `TDR-010` |
| 2 | Decision domain | 4 — Checks and tolerances |
| 3 | Decision topic | The interface set and check types applicable to Triviron coordination |
| 4 | Harrismith reference pattern | `supporting/coordination-review-strategy.md` §9 (interface matrix — twelve proposed checks), §10 (six check types) — AWC-TB0.1, `PROPOSED GOVERNANCE` — class B |
| 5 | What transfers as method | Check selection is a governed choice made against the project's own interfaces; an interface matrix is a controlled artefact, not a software output |
| 6 | What explicitly does not transfer | The twelve Harrismith checks, the `CI-01`–`CI-12` identifiers, the six-type classification and the Harrismith interface set |
| 7 | Triviron evidence required | Discipline / task-team structure; agreed check schedule or coordination requirement identifying project interfaces |
| 8 | Triviron evidence currently available | `NONE IDENTIFIED` |
| 9 | Triviron evidence missing | Controlled Triviron interface and check-type decision not identified |
| 10 | Current translation classification | `EVIDENCE REQUIRED` |
| 11 | Candidate decision | `NOT POPULATED — PROPOSAL STAGE NOT AUTHORISED` |
| 12 | Decision authority required | Required authority type: check / tolerance approval authority — holder `NOT YET ESTABLISHED` |
| 13 | Decision owner | `NOT YET ESTABLISHED` |
| 14 | Candidate BEP destination | Coordination / review strategy; controlled appendix — exact destination `NOT YET ESTABLISHED` |
| 15 | Dependent matrix / schedule / appendix | Controlled appendix (check schedule) |
| 16 | Implementation dependency | Established discipline structure (TDR-005) and input-container set (TDR-007) from which interfaces arise |
| 17 | Open question | Which interfaces exist on the Triviron project, and which check types do they need? |
| 18 | Status | `NOT YET ESTABLISHED` |
| 19 | Source / decision references | Class B as field 4; Module 6 Slide 6 teaching — `TEACHING INTERPRETATION — NOT GOVERNANCE` |
| 20 | Notes / boundary warning | Overclaim risk: the twelve checks travelling as a "starter set". STOP `M7-S05`, `M7-S15` |

### TDR-011 — What rule or tolerance applies to each check?

| # | Field | Value |
|---|---|---|
| 1 | Decision ID | `TDR-011` |
| 2 | Decision domain | 4 — Checks and tolerances |
| 3 | Decision topic | The rule or tolerance governing each Triviron check |
| 4 | Harrismith reference pattern | `supporting/coordination-review-strategy.md` §11 — **every Harrismith tolerance is `TBD`** — AWC-TB0.1, `PROPOSED GOVERNANCE` — class B; `standards/` — **Not established** (all four standards empty; `bep/Harrismith-Fire-Station-BEP.md` §11 records them Not established) — class B family |
| 5 | What transfers as method | A software default is not a project tolerance; a tolerance is a governed decision recorded per check; an undecided tolerance is typed `TBD` within an established scope, never left blank |
| 6 | What explicitly does not transfer | Harrismith's `TBD` tolerance entries (even the `TBD` status does not transfer), and the absence of Harrismith standards does not become a Triviron position |
| 7 | Triviron evidence required | Technical tolerance decision; controlled project standard; agreed check schedule carrying per-check rules |
| 8 | Triviron evidence currently available | `NONE IDENTIFIED` |
| 9 | Triviron evidence missing | Controlled Triviron tolerance or rule decision not identified for any check |
| 10 | Current translation classification | `EVIDENCE REQUIRED` |
| 11 | Candidate decision | `NOT POPULATED — PROPOSAL STAGE NOT AUTHORISED` |
| 12 | Decision authority required | Required authority type: check / tolerance approval authority — holder `NOT YET ESTABLISHED` |
| 13 | Decision owner | `NOT YET ESTABLISHED` |
| 14 | Candidate BEP destination | Controlled appendix; coordination / review strategy — exact destination `NOT YET ESTABLISHED` |
| 15 | Dependent matrix / schedule / appendix | Controlled appendix (tolerance schedule); other controlled project schedule |
| 16 | Implementation dependency | Approved check set (TDR-010) and an approved check/tolerance decision before any check is configured |
| 17 | Open question | Which rules and tolerances will Triviron govern — and from which standard basis? |
| 18 | Status | `NOT YET ESTABLISHED` |
| 19 | Source / decision references | Class B as field 4; Module 6 Slide 6 tolerance teaching — `TEACHING INTERPRETATION — NOT GOVERNANCE` |
| 20 | Notes / boundary warning | Overclaim risk: software-default clearances presented as project tolerances. STOP `M7-S06`, `M7-S05` |

### TDR-012 — Who approves those checks, rules and tolerances?

| # | Field | Value |
|---|---|---|
| 1 | Decision ID | `TDR-012` |
| 2 | Decision domain | 4 — Checks and tolerances |
| 3 | Decision topic | The approval authority for the Triviron check set, rules and tolerances |
| 4 | Harrismith reference pattern | `supporting/coordination-review-strategy.md` §11, §26 (approval of tolerances among the recorded open matters) — AWC-TB0.1 — class B; `supporting/information-management-responsibility-matrix.md` §3.7 `A2` (authorise governance change — `TBD` across four roles) — class B |
| 5 | What transfers as method | Checks, rules and tolerances require an identified approval authority; an unallocated approval is recorded as a typed absence, not exercised informally |
| 6 | What explicitly does not transfer | Harrismith's `A2` allocation pattern, its candidate roles, and its open-matter record |
| 7 | Triviron evidence required | Responsibility / authority decision; governance decision record allocating check/tolerance approval |
| 8 | Triviron evidence currently available | `NONE IDENTIFIED` |
| 9 | Triviron evidence missing | Controlled Triviron check/tolerance approval allocation not identified |
| 10 | Current translation classification | `EVIDENCE REQUIRED` |
| 11 | Candidate decision | `NOT POPULATED — PROPOSAL STAGE NOT AUTHORISED` |
| 12 | Decision authority required | Required authority type: check / tolerance approval authority — holder `NOT YET ESTABLISHED` |
| 13 | Decision owner | `NOT YET ESTABLISHED` |
| 14 | Candidate BEP destination | Main BEP clause; responsibility matrix — exact destination `NOT YET ESTABLISHED` |
| 15 | Dependent matrix / schedule / appendix | Responsibility matrix |
| 16 | Implementation dependency | Controlled authority allocation before any check schedule can carry approved status |
| 17 | Open question | Who may approve a Triviron check, rule or tolerance — and who decides that? |
| 18 | Status | `NOT YET ESTABLISHED` |
| 19 | Source / decision references | Class B as field 4; Module 6 governed-choice teaching — `TEACHING INTERPRETATION — NOT GOVERNANCE` |
| 20 | Notes / boundary warning | Overclaim risk: inferring an approver from a job title or tool role. STOP `M7-S16`, `M7-S05`, `M7-S06` |

## 6. Domain 5 — Findings, Issues and statuses

### TDR-013 — What distinguishes a finding, a clash and an Issue?

| # | Field | Value |
|---|---|---|
| 1 | Decision ID | `TDR-013` |
| 2 | Decision domain | 5 — Findings, Issues and statuses |
| 3 | Decision topic | The governed distinction between a finding, a clash and an Issue for Triviron |
| 4 | Harrismith reference pattern | `supporting/coordination-review-strategy.md` §12 — AWC-TB0.1, `PROPOSED GOVERNANCE` — class B; `bep/Harrismith-Fire-Station-BEP.md` §8.7 — AWC-TB0.1 — class A. **Recorded variance 3 — `S2`'s Issue definition is broader than `S1`'s — carried, not reconciled** |
| 5 | What transfers as method | Finding, clash and Issue must be distinguished: a clash is one kind of finding, and an Issue is a governed record — not every finding becomes one; where two controlled definitions differ in breadth, both are recorded |
| 6 | What explicitly does not transfer | Harrismith's definitions in either variant, its Issue construct and its record structure |
| 7 | Triviron evidence required | Issue-management procedure or coordination requirement adopting governed definitions |
| 8 | Triviron evidence currently available | `NONE IDENTIFIED` |
| 9 | Triviron evidence missing | Controlled Triviron finding/clash/Issue definition decision not identified |
| 10 | Current translation classification | `METHOD` — the reusable structural distinction is the row's content; no responsible candidate decision can yet be framed |
| 11 | Candidate decision | `NOT POPULATED — PROPOSAL STAGE NOT AUTHORISED` |
| 12 | Decision authority required | Required authority type: project coordination-governance authority — holder `NOT YET ESTABLISHED` |
| 13 | Decision owner | `NOT YET ESTABLISHED` |
| 14 | Candidate BEP destination | Coordination / review strategy — exact destination `NOT YET ESTABLISHED` |
| 15 | Dependent matrix / schedule / appendix | Decision register (for the adopting decision) |
| 16 | Implementation dependency | Controlled adoption of definitions before any Issue-management procedure is configured |
| 17 | Open question | Where will Triviron draw the finding → Issue line, and in which document? |
| 18 | Status | `NOT YET ESTABLISHED` |
| 19 | Source / decision references | Class A/B as field 4; Module 6 Slide 7 teaching — `TEACHING INTERPRETATION — NOT GOVERNANCE` |
| 20 | Notes / boundary warning | Overclaim risk: importing the Harrismith taxonomy with the distinction. STOP `M7-S07`, `M7-S13` |

### TDR-014 — When must an Issue be created?

| # | Field | Value |
|---|---|---|
| 1 | Decision ID | `TDR-014` |
| 2 | Decision domain | 5 — Findings, Issues and statuses |
| 3 | Decision topic | The governed trigger for creating a Triviron Issue |
| 4 | Harrismith reference pattern | `bep/Harrismith-Fire-Station-BEP.md` §8.7 (an actionable matter requiring assignment, tracking, decision or verification) — AWC-TB0.1 — class A; `supporting/coordination-review-strategy.md` §12–§13 (broader limbs; seven triage dispositions) — AWC-TB0.1, `PROPOSED GOVERNANCE` — class B |
| 5 | What transfers as method | Issue creation is a governed decision with stated limbs, taken at triage — not an automatic consequence of detection; dispositions other than "raise an Issue" must be governed too |
| 6 | What explicitly does not transfer | Harrismith's creation limbs in either variant, its seven triage dispositions and the `Accepted condition` construct |
| 7 | Triviron evidence required | Issue-management procedure; coordination requirement stating creation limbs and triage dispositions |
| 8 | Triviron evidence currently available | `NONE IDENTIFIED` |
| 9 | Triviron evidence missing | Controlled Triviron Issue-creation and triage decision not identified |
| 10 | Current translation classification | `EVIDENCE REQUIRED` |
| 11 | Candidate decision | `NOT POPULATED — PROPOSAL STAGE NOT AUTHORISED` |
| 12 | Decision authority required | Required authority type: project coordination-governance authority — holder `NOT YET ESTABLISHED` |
| 13 | Decision owner | `NOT YET ESTABLISHED` |
| 14 | Candidate BEP destination | Coordination / review strategy — exact destination `NOT YET ESTABLISHED` |
| 15 | Dependent matrix / schedule / appendix | Decision register |
| 16 | Implementation dependency | Approved taxonomy and definitions (TDR-013) before creation rules can bind |
| 17 | Open question | Which matters must become Triviron Issues, and who decides at triage? |
| 18 | Status | `NOT YET ESTABLISHED` |
| 19 | Source / decision references | Class A/B as field 4; Module 6 Slide 8 teaching — `TEACHING INTERPRETATION — NOT GOVERNANCE` |
| 20 | Notes / boundary warning | Overclaim risk: the seven dispositions travelling as defaults. STOP `M7-S07`, `M7-S15` |

### TDR-015 — What status meanings are governed?

| # | Field | Value |
|---|---|---|
| 1 | Decision ID | `TDR-015` |
| 2 | Decision domain | 5 — Findings, Issues and statuses |
| 3 | Decision topic | The governed Triviron Issue-status vocabulary and its meanings |
| 4 | Harrismith reference pattern | `bep/Harrismith-Fire-Station-BEP.md` §8.7 (*"This BEP does not define project issue numbering or status codes"* — express deferral) — AWC-TB0.1 — class A; `supporting/coordination-review-strategy.md` §15 (six-status model with two controlled alternate dispositions, not claimed configured) — AWC-TB0.1, `PROPOSED GOVERNANCE` — class B |
| 5 | What transfers as method | Status meanings are governed, not platform-supplied; a status label is not technical evidence; alternate dispositions are controlled outcomes, not stages; deferral of a vocabulary is itself an explicit governed act |
| 6 | What explicitly does not transfer | The Harrismith six-status model, `Deferred`/`Escalated` handling, and any numbering scheme |
| 7 | Triviron evidence required | Issue-management procedure or governance decision record adopting a status vocabulary and its meanings |
| 8 | Triviron evidence currently available | `NONE IDENTIFIED` |
| 9 | Triviron evidence missing | Controlled Triviron Issue-status vocabulary decision not identified |
| 10 | Current translation classification | `EVIDENCE REQUIRED` |
| 11 | Candidate decision | `NOT POPULATED — PROPOSAL STAGE NOT AUTHORISED` |
| 12 | Decision authority required | Required authority type: project coordination-governance authority — holder `NOT YET ESTABLISHED` |
| 13 | Decision owner | `NOT YET ESTABLISHED` |
| 14 | Candidate BEP destination | Coordination / review strategy — exact destination `NOT YET ESTABLISHED` |
| 15 | Dependent matrix / schedule / appendix | Controlled appendix (status definitions), if adopted |
| 16 | Implementation dependency | Approved taxonomy (TDR-013, TDR-014) before statuses can attach to it; any platform configuration follows the governed meanings, never precedes them |
| 17 | Open question | Which status meanings will Triviron govern, and where are they defined? |
| 18 | Status | `NOT YET ESTABLISHED` |
| 19 | Source / decision references | Class A/B as field 4; Module 6 Slide 10 teaching — `TEACHING INTERPRETATION — NOT GOVERNANCE` |
| 20 | Notes / boundary warning | Overclaim risk: platform status lists read as governed meanings. STOP `M7-S07`, `M7-S03` |

## 7. Domain 6 — Verification, evidence and completion

### TDR-016 — What must occur before verification?

| # | Field | Value |
|---|---|---|
| 1 | Decision ID | `TDR-016` |
| 2 | Decision domain | 6 — Verification, evidence and completion |
| 3 | Decision topic | The prerequisites a Triviron matter must satisfy before verification may occur |
| 4 | Harrismith reference pattern | `supporting/coordination-review-strategy.md` §19 (four prerequisites; `Ready for Verification` is a state of the record, not verification) — AWC-TB0.1, `PROPOSED GOVERNANCE` — class B; `bep/Harrismith-Fire-Station-BEP.md` §8.10 — AWC-TB0.1 — class A |
| 5 | What transfers as method | Verification has governed prerequisites; being ready for verification is not being verified; verification examines evidence, not assertions |
| 6 | What explicitly does not transfer | Harrismith's four prerequisites as content, and its verification-step wording |
| 7 | Triviron evidence required | Verification requirement stating prerequisites; issue-management procedure carrying them |
| 8 | Triviron evidence currently available | `NONE IDENTIFIED` |
| 9 | Triviron evidence missing | Controlled Triviron verification-prerequisite decision not identified |
| 10 | Current translation classification | `EVIDENCE REQUIRED` |
| 11 | Candidate decision | `NOT POPULATED — PROPOSAL STAGE NOT AUTHORISED` |
| 12 | Decision authority required | Required authority type: project verification-governance authority — holder `NOT YET ESTABLISHED` |
| 13 | Decision owner | `NOT YET ESTABLISHED` |
| 14 | Candidate BEP destination | Coordination / review strategy — exact destination `NOT YET ESTABLISHED` |
| 15 | Dependent matrix / schedule / appendix | Responsibility matrix (verification allocation, TDR-006) |
| 16 | Implementation dependency | Verified evidence requirement and verification allocation (TDR-006) |
| 17 | Open question | What must be true of a Triviron matter before anyone may verify it? |
| 18 | Status | `NOT YET ESTABLISHED` |
| 19 | Source / decision references | Class A/B as field 4; Module 6 Slide 11 teaching — `TEACHING INTERPRETATION — NOT GOVERNANCE` |
| 20 | Notes / boundary warning | Overclaim risk: importing the four prerequisites as Triviron's. STOP `M7-S15`, `M7-S18` |

### TDR-017 — What evidence permits closure?

| # | Field | Value |
|---|---|---|
| 1 | Decision ID | `TDR-017` |
| 2 | Decision domain | 6 — Verification, evidence and completion |
| 3 | Decision topic | The evidence on which a Triviron coordination matter may be closed |
| 4 | Harrismith reference pattern | `supporting/coordination-review-strategy.md` §18–§19 (resolution and verification findings), §21 (nine completion conditions with `as applicable` / `required` qualifiers) — AWC-TB0.1, `PROPOSED GOVERNANCE` — class B |
| 5 | What transfers as method | Closure requires evidence of disposition, not absence of complaint; a closed record proves what it evidences and nothing more; completion conditions carry their qualifiers |
| 6 | What explicitly does not transfer | Harrismith's three verification findings, nine completion conditions and closure wording |
| 7 | Triviron evidence required | Verification requirement; issue-management procedure defining closure evidence |
| 8 | Triviron evidence currently available | `NONE IDENTIFIED` |
| 9 | Triviron evidence missing | Controlled Triviron closure-evidence decision not identified |
| 10 | Current translation classification | `EVIDENCE REQUIRED` |
| 11 | Candidate decision | `NOT POPULATED — PROPOSAL STAGE NOT AUTHORISED` |
| 12 | Decision authority required | Required authority type: project verification-governance authority — holder `NOT YET ESTABLISHED` |
| 13 | Decision owner | `NOT YET ESTABLISHED` |
| 14 | Candidate BEP destination | Coordination / review strategy — exact destination `NOT YET ESTABLISHED` |
| 15 | Dependent matrix / schedule / appendix | Decision register (closure decisions), if adopted |
| 16 | Implementation dependency | Verification prerequisites (TDR-016) and an operating record structure to hold the evidence |
| 17 | Open question | What will a closed Triviron matter actually prove? |
| 18 | Status | `NOT YET ESTABLISHED` |
| 19 | Source / decision references | Class B as field 4; Module 6 Slides 11–13 teaching — `TEACHING INTERPRETATION — NOT GOVERNANCE` |
| 20 | Notes / boundary warning | Overclaim risk: closure treated as proof of coordination quality. STOP `M7-S15`, `M7-S12` |

### TDR-018 — What evidence demonstrates one complete governed coordination cycle?

| # | Field | Value |
|---|---|---|
| 1 | Decision ID | `TDR-018` |
| 2 | Decision domain | 6 — Verification, evidence and completion |
| 3 | Decision topic | The evidence set that would demonstrate one complete governed Triviron coordination cycle |
| 4 | Harrismith reference pattern | `supporting/governance-decision-register.md` `GCR-006` (one complete governed cycle to be exercised and evidenced — **OPEN**) — class C; `docs/Increment-7C-Live-Validation-Record.md` §8 (`PARTIALLY TRACEABLE / NOT YET DEMONSTRATED AS A COMPLETE CYCLE`) — Controlled Validation Record, `Authority: None` — class C; `supporting/coordination-review-strategy.md` §21–§22 (completion conditions; nine evidence outputs) — class B |
| 5 | What transfers as method | A complete cycle is a demonstrated, evidenced thing — not an asserted one; completion is not zero clashes; a partial trace is recorded as partial; the demonstration requirement is itself recorded as an open condition until met |
| 6 | What explicitly does not transfer | `GCR-006` itself, Harrismith's evidence-output list, and Harrismith's observed partial trace — Triviron inherits neither the condition nor its status |
| 7 | Triviron evidence required | Verification requirement; coordination requirement defining the cycle-demonstration evidence set; governance decision record adopting it |
| 8 | Triviron evidence currently available | `NONE IDENTIFIED` |
| 9 | Triviron evidence missing | Controlled Triviron cycle-demonstration evidence requirement not identified |
| 10 | Current translation classification | `EVIDENCE REQUIRED` |
| 11 | Candidate decision | `NOT POPULATED — PROPOSAL STAGE NOT AUTHORISED` |
| 12 | Decision authority required | Required authority type: project verification-governance authority — holder `NOT YET ESTABLISHED` |
| 13 | Decision owner | `NOT YET ESTABLISHED` |
| 14 | Candidate BEP destination | Coordination / review strategy; decision register — exact destination `NOT YET ESTABLISHED` |
| 15 | Dependent matrix / schedule / appendix | Decision register |
| 16 | Implementation dependency | A defined cycle (TDR-003), operating inputs (TDR-007, TDR-008) and closure evidence rules (TDR-017) — none established |
| 17 | Open question | What would Triviron accept as proof that one governed cycle ran end to end? |
| 18 | Status | `NOT YET ESTABLISHED` |
| 19 | Source / decision references | Class B/C as field 4; Module 6 implementation-position teaching — `TEACHING INTERPRETATION — NOT GOVERNANCE` |
| 20 | Notes / boundary warning | Overclaim risk: treating capability provisioning as cycle demonstration. STOP `M7-S12`, `M7-S15` |

## 8. Domain 7 — Publication and acceptance boundary

### TDR-019 — How does coordination link to controlled reshare or exchange?

| # | Field | Value |
|---|---|---|
| 1 | Decision ID | `TDR-019` |
| 2 | Decision domain | 7 — Publication and acceptance boundary |
| 3 | Decision topic | The governed link between Triviron coordination outcomes and controlled reshare or exchange events |
| 4 | Harrismith reference pattern | `supporting/cde-workflow-state-strategy.md` `T3` (coordination input is a use, not a state) and `T8` (rework returns to WIP) — AWC-TB0.1, `PROPOSED GOVERNANCE` — class B; `supporting/information-delivery-schedule.md` §2, §4.2 (`TRN-E02` conditional reshare, activated per affected container) — AWC-TB0.1, entries `PROPOSED GOVERNANCE` — class B; `supporting/coordination-review-strategy.md` §17 (cycle-to-event mapping) — class B |
| 5 | What transfers as method | Coordination consumes and reshapes information through governed exchange events; an event uses a state transition but is not one; a reshare is activated per affected container, not by calendar habit |
| 6 | What explicitly does not transfer | Harrismith's `T`-numbered transitions, `TRN-` events, activation conditions and event set |
| 7 | Triviron evidence required | Information exchange requirement; CDE / platform governance decision; coordination requirement mapping cycle outcomes to exchange events |
| 8 | Triviron evidence currently available | `NONE IDENTIFIED` |
| 9 | Triviron evidence missing | Controlled Triviron coordination-to-exchange mapping not identified |
| 10 | Current translation classification | `EVIDENCE REQUIRED` |
| 11 | Candidate decision | `NOT POPULATED — PROPOSAL STAGE NOT AUTHORISED` |
| 12 | Decision authority required | Required authority type: project information-management governance authority — holder `NOT YET ESTABLISHED` |
| 13 | Decision owner | `NOT YET ESTABLISHED` |
| 14 | Candidate BEP destination | CDE strategy; information-delivery schedule — exact destination `NOT YET ESTABLISHED` |
| 15 | Dependent matrix / schedule / appendix | Information-delivery schedule; CDE strategy |
| 16 | Implementation dependency | An established Triviron state model and exchange-event set — neither established |
| 17 | Open question | Through which governed events do Triviron coordination outcomes move — and what activates them? |
| 18 | Status | `NOT YET ESTABLISHED` |
| 19 | Source / decision references | Class B as field 4; Module 4/5/6 event-vs-transition teaching — `TEACHING INTERPRETATION — NOT GOVERNANCE` |
| 20 | Notes / boundary warning | Overclaim risk: `TRN-` events or `T`-transitions reused as Triviron's. STOP `M7-S02`, `M7-S15` |

### TDR-020 — Who may authorise publication or exchange?

| # | Field | Value |
|---|---|---|
| 1 | Decision ID | `TDR-020` |
| 2 | Decision domain | 7 — Publication and acceptance boundary |
| 3 | Decision topic | The Triviron publication / exchange authorisation authority |
| 4 | Harrismith reference pattern | `bep/Harrismith-Fire-Station-BEP.md` §9.7 (publication authority — **unresolved even for Harrismith**) — AWC-TB0.1 — class A; `supporting/information-management-responsibility-matrix.md` `D4` row (five `TBD`, four `—`, no allocation made) — class B; `supporting/information-delivery-schedule.md` §5.1 (`TRN-E03` blocked on five independent typed matters) — class B; `docs/Increment-7C-Live-Validation-Record.md` §9 (*"No governed publication / exchange authority evidence was established"*) — `Authority: None` — class C |
| 5 | What transfers as method | Publication/exchange requires an identified authorising function before the transition is available; an unresolved authority is typed and blocks the route visibly; ability to move a file is not authority to change its state |
| 6 | What explicitly does not transfer | Harrismith's `D4` distribution, its blocked `T4`, `TRN-E03` and its unresolved-status record — Triviron inherits neither the block nor the vacancy |
| 7 | Triviron evidence required | Acceptance / publication authority decision; appointment/contract information establishing who may authorise exchange |
| 8 | Triviron evidence currently available | `NONE IDENTIFIED` |
| 9 | Triviron evidence missing | Controlled Triviron authority allocation for publication/exchange not identified |
| 10 | Current translation classification | `EVIDENCE REQUIRED` |
| 11 | Candidate decision | `NOT POPULATED — PROPOSAL STAGE NOT AUTHORISED` |
| 12 | Decision authority required | Required authority type: publication / exchange authorisation authority (its own allocation is itself the decision) — holder `NOT YET ESTABLISHED` |
| 13 | Decision owner | `NOT YET ESTABLISHED` |
| 14 | Candidate BEP destination | Main BEP clause; responsibility matrix — exact destination `NOT YET ESTABLISHED` |
| 15 | Dependent matrix / schedule / appendix | Responsibility matrix; information-delivery schedule |
| 16 | Implementation dependency | Controlled authority allocation before any publication transition is configured or exercised |
| 17 | Open question | Who may say "publish" on the Triviron project — and who appoints them? |
| 18 | Status | `NOT YET ESTABLISHED` |
| 19 | Source / decision references | Class A/B/C as field 4; Module 5/6 publication teaching — `TEACHING INTERPRETATION — NOT GOVERNANCE` |
| 20 | Notes / boundary warning | Overclaim risk: any implication a publication authority exists on either side. STOP `M7-S09`, `M7-S16` |

### TDR-021 — How are completion, publication and recipient acceptance kept distinct?

| # | Field | Value |
|---|---|---|
| 1 | Decision ID | `TDR-021` |
| 2 | Decision domain | 7 — Publication and acceptance boundary |
| 3 | Decision topic | Keeping coordination completion, publication and recipient acceptance distinct in Triviron governance |
| 4 | Harrismith reference pattern | `bep/Harrismith-Fire-Station-BEP.md` §9.2 (decision vocabulary), §9.8 (*Accept* — recipient acceptance as a separate post-delivery function) — AWC-TB0.1 — class A; `supporting/coordination-review-strategy.md` §13 (*"Accepted condition" does not mean recipient acceptance*) — class B. **Recorded variance 5 — two objects sharing one word — carried, not reconciled**; `supporting/governance-decision-register.md` `PAD-001` context (a publication-*arrangement* approval is not project publication authority) — class C |
| 5 | What transfers as method | Verification, authorisation, publication and recipient acceptance are distinct governance acts; completion is not publication, and neither is acceptance; where one word carries two meanings, both are recorded and kept apart |
| 6 | What explicitly does not transfer | Harrismith's vocabulary text, its `Accepted condition` construct, and the `PAD-001` arrangement record |
| 7 | Triviron evidence required | Governance decision record adopting the act distinctions; information exchange requirement; acceptance / publication authority decision |
| 8 | Triviron evidence currently available | `NONE IDENTIFIED` |
| 9 | Triviron evidence missing | Controlled Triviron adoption of the completion / publication / acceptance distinctions not identified |
| 10 | Current translation classification | `METHOD` — the reusable structural distinction is the row's content; no responsible candidate decision can yet be framed |
| 11 | Candidate decision | `NOT POPULATED — PROPOSAL STAGE NOT AUTHORISED` |
| 12 | Decision authority required | Required authority type: project information-management governance authority — holder `NOT YET ESTABLISHED` |
| 13 | Decision owner | `NOT YET ESTABLISHED` |
| 14 | Candidate BEP destination | Main BEP clause — exact destination `NOT YET ESTABLISHED` |
| 15 | Dependent matrix / schedule / appendix | Information-delivery schedule; responsibility matrix |
| 16 | Implementation dependency | Controlled adoption of the distinctions before any exchange or acceptance workflow is configured |
| 17 | Open question | How will Triviron's documents keep the four acts apart — and evidence each separately? |
| 18 | Status | `NOT YET ESTABLISHED` |
| 19 | Source / decision references | Class A/B/C as field 4; Module 6 Slide 12–13 teaching — `TEACHING INTERPRETATION — NOT GOVERNANCE` |
| 20 | Notes / boundary warning | Overclaim risk: "accepted" read as one thing; completion read as delivery. STOP `M7-S09`, `M7-S13`, `M7-S15` |

---

## 9. Domain summary

| Domain | Rows | Controlled Triviron evidence identified | Highest reachable classification | Candidate decisions | Triviron values established |
|---|---|---|---|---|---|
| 1 — Coordination governance | 3 (`TDR-001`–`TDR-003`) | **0** — `NONE IDENTIFIED` × 3 | `EVIDENCE REQUIRED` | **0** | **0** |
| 2 — Roles and authority | 3 (`TDR-004`–`TDR-006`) | **0** — `NONE IDENTIFIED` × 3 | `EVIDENCE REQUIRED` | **0** | **0** |
| 3 — Inputs and federation | 3 (`TDR-007`–`TDR-009`) | **0** — `NONE IDENTIFIED` × 3 | `EVIDENCE REQUIRED` (`TDR-009` is `METHOD`) | **0** | **0** |
| 4 — Checks and tolerances | 3 (`TDR-010`–`TDR-012`) | **0** — `NONE IDENTIFIED` × 3 | `EVIDENCE REQUIRED` | **0** | **0** |
| 5 — Findings, Issues and statuses | 3 (`TDR-013`–`TDR-015`) | **0** — `NONE IDENTIFIED` × 3 | `EVIDENCE REQUIRED` (`TDR-013` is `METHOD`) | **0** | **0** |
| 6 — Verification, evidence and completion | 3 (`TDR-016`–`TDR-018`) | **0** — `NONE IDENTIFIED` × 3 | `EVIDENCE REQUIRED` | **0** | **0** |
| 7 — Publication and acceptance boundary | 3 (`TDR-019`–`TDR-021`) | **0** — `NONE IDENTIFIED` × 3 | `EVIDENCE REQUIRED` (`TDR-021` is `METHOD`) | **0** | **0** |

**Overall: 21 rows · controlled Triviron evidence identified 0 · candidate
decisions 0 · `PROPOSAL` rows 0 · `ESTABLISHED` Triviron answer rows 0.**

## 10. Register-wide reconciliation

| Check | Result |
|---|---|
| Row count | **21 exactly** |
| IDs | **`TDR-001`–`TDR-021`, sequential, no gaps or duplicates** |
| Domains | **All seven represented, exactly three rows each** |
| Fields | **All 20 schema fields present in every row; no required field blank** |
| Field 8 | **`NONE IDENTIFIED` across all 21 rows; no governed exception identified or reported** |
| Field 11 | **Candidate decisions populated: 0** — all rows `NOT POPULATED — PROPOSAL STAGE NOT AUTHORISED` |
| Field 13 | **Decision owners established: 0** — all `NOT YET ESTABLISHED`; no controlled evidence found |
| Classifications | **18 × `EVIDENCE REQUIRED` · 3 × `METHOD`** (`TDR-009`, `TDR-013`, `TDR-021`) · `DECISION REQUIRED` 0 · **`PROPOSAL` 0 · `ESTABLISHED` 0** |
| Statuses | **`NOT YET ESTABLISHED` × 21.** `NOT ESTABLISHED` used nowhere as a synonym for missing evidence; `TBD` used nowhere as a blank |
| Triviron values established | **0** |
| STOP coverage | **Every row cites at least one `M7-S` condition** |
| Publication automation | **`PAUSED`** |

**The existence of this register does not make the future Triviron BEP
complete or partially complete.** It records what must be established; it
establishes nothing.

