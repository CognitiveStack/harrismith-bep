# Module 4 — Source Map, Registers and Prohibited Claims

**Status:** Traceability record for teaching material. **Not governance.**

Statement-level classification for the developed slides, the four required
registers, and the list of claims that **may not be made** in this module.

Source identifiers `S1`–`S14` are defined in
[`source-inventory.md`](source-inventory.md).

---

## 1. Classification scheme

| Class | Meaning |
|---|---|
| **`CONTROLLED`** | Controlled Harrismith governance — explicit wording in `S1` |
| **`SUPPORTING`** | Supporting project control — `S2`, `S5`–`S9` |
| **`DECISION-RECORD`** | Controlled validation or decision record — `S3`, `S4` |
| **`MODULE-1-3`** | Earlier-module interpretation, already established |
| **`INTERP`** | Supported interpretation; no source phrases it this way |
| **`SYNTH`** | Teaching synthesis; no source support |
| **`EXCLUDED`** | Considered and deliberately left out |

## 2. Governance and implementation status

**Every workflow statement carries both. They are not the same.**

| Governance status | Meaning |
|---|---|
| **`CONTROLLED GOVERNANCE`** | Approved and governing |
| **`PROPOSED GOVERNANCE`** | Classified as proposed — `S2`'s own classification |
| **`PLANNED`** | Recorded as intended |
| **`CONDITIONALLY AVAILABLE`** | Available where a stated condition is met |
| **`BLOCKED`** | Cannot proceed; a required authority or input is unresolved |
| **`UNRESOLVED`** | Open matter, recorded as open |

| Implementation status | Meaning |
|---|---|
| **`IMPLEMENTATION UNVERIFIED`** | Not checked against intended governance |
| **`LIVE IMPLEMENTATION VERIFIED`** | **Only where `S4` explicitly supports it** |

**Absence of verification is not converted into a failure claim.** `S4` §7:
*"Absence of observation is not observation of absence."*

## 3. Fields recorded for each statement

| Field | |
|---|---|
| **ID** | `M4-S<slide>-<nn>` |
| **Statement** | What is taught |
| **Source path** | The repository file |
| **Section** | The section or record within it |
| **Authority level** | 1–5, per [`source-inventory.md`](source-inventory.md) §1 |
| **Governance status** | From §2 |
| **Implementation status** | From §2, or `—` where not applicable |
| **Class** | From §1 |
| **Teaching use / warning** | Recorded in the per-slide notes |

---

## 4. Source-authority register

**Which source governs which CDE concept.** Reproduced in summary; the full
register is [`source-inventory.md`](source-inventory.md) §3.

| Concept | **Governs** | Supporting |
|---|---|---|
| CDE principles | **`S1` §6.1** | `S2` purpose |
| Information states | **`S1` §6.3** | `S2` §1 |
| States are not folders | **`S1` §6.3** | `S2` §1; **`CGD-C01`** |
| Folder topology and state mapping | **`S3` §2, §3** | `S1` §6.11 |
| State transitions | **`S2` §3** | `S1` §6.5, §7 |
| Transition authority | **`S6`** | `S2` §3.2; `S1` §9.4, §9.7, §9.8 |
| Transition evidence | **`S2` §3.3, §16** | `S1` §9.11 |
| Delivery events | **`S5`** | `S2` §9–§11 |
| The five properties | **`S1` §6.8** | `S2` §13 |
| Access and permissions | **`S1` §6.9** | `S2` §14; **`CGD-C08`** |
| Retention / Record | **`S1` §6.3** | `S2` §1; **`CGD-C06`** |
| Naming | **`S1` §11.3** | `S2` §19; **`CGD-C05`**; `S12` |
| Platform implementation rules | **`S2` §17** | `S1` §12.1, §12.9 |
| Implementation verification | **`S4`** | **`CGD-C07`**; `S2` §6 |

---

## 5. Statement classification — Slides 1–7

**113 statements. 53 `CONTROLLED`, 14 `SUPPORTING`, 21 `DECISION-RECORD`,
1 `MODULE-1-3`, 7 `INTERP`, 7 `SYNTH`, 10 `EXCLUDED`.**

| Slide | Statements | `CTRL` | `SUPP` | `DEC` | `M1-3` | `INT` | `SYN` | `EXC` |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| 1 | 12 | 3 | 2 | 3 | 1 | 1 | 1 | 1 |
| 2 | 14 | 7 | 2 | 1 | 0 | 2 | 1 | 1 |
| 3 | 18 | 9 | 3 | 4 | 0 | 1 | 1 | 0 |
| **4** | **16** | **8** | **0** | **4** | **0** | **1** | **1** | **2** |
| **5** | **18** | **8** | **3** | **3** | **0** | **1** | **1** | **2** |
| **6** | **18** | **9** | **3** | **2** | **0** | **1** | **1** | **2** |
| **7** | **17** | **9** | **1** | **4** | **0** | **0** | **1** | **2** |
| **Total** | **113** | **53** | **14** | **21** | **1** | **7** | **7** | **10** |

**Three observations.**

**Section B is overwhelmingly controlled.** Of the 69 statements on Slides 4–7,
**34 are `CONTROLLED` and 13 are `DECISION-RECORD`** — 68 per cent from level-1
and level-3 sources. **Only two are `SYNTH` per slide at most.** The four states
are among the best-evidenced material in the programme.

**Every Slide 2 property definition is `CONTROLLED`** while **every code set is
`UNRESOLVED`**: the vocabulary is governed, the coding is not.

**The two states the audience most wants are the two least available.** Published
/ Authorised is **`BLOCKED`** and Record / Retained is **`UNRESOLVED`** — and
both carry a mandatory **empty field** rather than an omission.

### Slide 1 — A CDE is a governed process, not a folder tree

| ID | Statement | Source path | Section | Auth | Governance | Implementation | Class |
|---|---|---|---|---|---|---|---|
| `M4-S1-01` | *"an information-management process supported by technology… **It is not a folder tree**"* | `bep/Harrismith-Fire-Station-BEP.md` | §6.1 | 1 | **`CONTROLLED GOVERNANCE`** | — | **`CONTROLLED`** |
| `M4-S1-02` | *"The CDE is a process, not a folder tree… the presence or absence of a folder proves nothing about state"* | `supporting/cde-workflow-state-strategy.md` | Purpose | 2 | `PROPOSED GOVERNANCE` | — | **`SUPPORTING`** |
| `M4-S1-03` | Reorganising folders does not change how information is governed | `bep/Harrismith-Fire-Station-BEP.md` | §6.1 | 1 | **`CONTROLLED GOVERNANCE`** | — | **`CONTROLLED`** |
| `M4-S1-04` | The six things a CDE controls — develop · check · share · authorise · deliver · retain | `S1` §6.1; `S2` §1 | — | 4 | — | — | **`INTERP`** |
| `M4-S1-05` | *"The existence or name of an area does not by itself establish an information state"* | `docs/CDE-Structure-Governance-Decision.md` | **`CGD-C01`** | 3 | **`CONTROLLED GOVERNANCE`** — active condition | — | **`DECISION-RECORD`** |
| `M4-S1-06` | **Permission ≠ authority.** Platform access confers no authority to share, publish, approve or accept | `bep/…BEP.md` §6.9; `supporting/cde-workflow-state-strategy.md` §14 | — | 1, 2 | **`CONTROLLED GOVERNANCE`** | — | **`CONTROLLED`** |
| `M4-S1-07` | *"**Being able to perform an action in the software says nothing about who was authorised to decide it**"* | `docs/Increment-7C-Live-Validation-Record.md` | §9 | 3 | — | Observed | **`DECISION-RECORD`** |
| `M4-S1-08` | The Modules 1 / 2 / 3 / 4 callback | Modules 1–3 | — | 4 | — | — | **`MODULE-1-3`** |
| `M4-S1-09` | *"The CDE is the governed process; the platform and folders are tools used to implement it"* | none | — | 5 | — | — | **`SYNTH`** |
| `M4-S1-10` | **`S2`'s workflow is `PROPOSED GOVERNANCE` and *"does not describe the live platform"*** | `supporting/cde-workflow-state-strategy.md` | Purpose | 2 | **`PROPOSED GOVERNANCE`** | **`IMPLEMENTATION UNVERIFIED`** | **`SUPPORTING`** |
| `M4-S1-11` | The four-area root topology is adopted; **a later controlled verification must confirm the live topology before the mapping is relied on operationally** | `docs/CDE-Structure-Governance-Decision.md` | §2; **`CGD-C07`** | 3 | **`CONTROLLED GOVERNANCE`** | **`IMPLEMENTATION UNVERIFIED`** | **`DECISION-RECORD`** |
| `M4-S1-12` | Any claim that the CDE is the software, or that the folder tree is the CDE | — | — | — | — | — | **`EXCLUDED`** |

### Slide 2 — State, version, revision, status and suitability are different

| ID | Statement | Source path | Section | Auth | Governance | Implementation | Class |
|---|---|---|---|---|---|---|---|
| `M4-S2-01` | **State** — *"WIP / Shared / Published / Record"*, the governed information-use context | `bep/…BEP.md` | §6.8 | 1 | **`CONTROLLED GOVERNANCE`** | — | **`CONTROLLED`** |
| `M4-S2-02` | **Version** — *"A platform or file history instance"* | `bep/…BEP.md` §6.8; `supporting/cde-workflow-state-strategy.md` §13 | — | 1, 2 | **`CONTROLLED GOVERNANCE`** | — | **`CONTROLLED`** |
| `M4-S2-03` | **Revision** — *"A controlled issue identifier, **where project convention requires one**"* | `bep/…BEP.md` | §6.8 | 1 | **`CONTROLLED GOVERNANCE`** | — | **`CONTROLLED`** |
| `M4-S2-04` | **Status** — *"A workflow or decision condition"* | `bep/…BEP.md` | §6.8 | 1 | **`CONTROLLED GOVERNANCE`** | — | **`CONTROLLED`** |
| `M4-S2-05` | **Suitability** — *"What the information may be used for"* | `bep/…BEP.md` | §6.8 | 1 | **`CONTROLLED GOVERNANCE`** | — | **`CONTROLLED`** |
| `M4-S2-06` | **"A new platform version creates none of the others."** Each is a separate act with its own decision and responsible role | `bep/…BEP.md` | §6.8 | 1 | **`CONTROLLED GOVERNANCE`** | — | **`CONTROLLED`** |
| `M4-S2-07` | The five questions — where may it be used · which occurrence · which issue · what condition · for what use | none | — | 4 | — | — | **`INTERP`** |
| `M4-S2-08` | The six relationships — version ≠ revision · revision ≠ transition · status ≠ suitability · suitability ≠ acceptance · folder creates none · several may change together | `S1` §6.8; `S2` §13; `CGD-C01` | — | 4 | — | — | **`INTERP`** |
| `M4-S2-09` | **No revision convention is established** | `bep/…BEP.md` §11.3; `standards/naming/` | — | 1 | **`UNRESOLVED`** | — | **`CONTROLLED`** |
| `M4-S2-10` | **No suitability code set is established** | `supporting/cde-workflow-state-strategy.md` | §19 | 2 | **`UNRESOLVED`** | — | **`SUPPORTING`** |
| `M4-S2-11` | Folder location creates none of the five | `docs/CDE-Structure-Governance-Decision.md` | **`CGD-C01`** | 3 | **`CONTROLLED GOVERNANCE`** | — | **`DECISION-RECORD`** |
| `M4-S2-12` | *"Five properties may describe the same container, but each answers a different governance question"* | none | — | 5 | — | — | **`SYNTH`** |
| `M4-S2-13` | A Published container does **not** automatically mean delivered, received, accepted, or suitable for a different purpose | `supporting/cde-workflow-state-strategy.md` | §13 | 2 | `PROPOSED GOVERNANCE` | — | **`SUPPORTING`** |
| `M4-S2-14` | Any invented revision, status or suitability code | — | — | — | — | — | **`EXCLUDED`** |

### Slide 3 — The Harrismith information-state model

| ID | Statement | Source path | Section | Auth | Governance | Implementation | Class |
|---|---|---|---|---|---|---|---|
| `M4-S3-01` | **WIP** — *"Information under originator / task-team control. Not authorised for general project reliance."* | `bep/…BEP.md` | §6.3 | 1 | **`CONTROLLED GOVERNANCE`** | — | **`CONTROLLED`** |
| `M4-S3-02` | **Shared** — *"made available beyond the originating task team for an identified purpose, after required checking and authorisation"* | `bep/…BEP.md` | §6.3 | 1 | **`CONTROLLED GOVERNANCE`** | — | **`CONTROLLED`** |
| `M4-S3-03` | **Published / Authorised** — *"authorised for a defined delivery or use purpose"* | `bep/…BEP.md` | §6.3 | 1 | **`CONTROLLED GOVERNANCE`** | — | **`CONTROLLED`** |
| `M4-S3-04` | **Record / Retained** — *"Historical evidence retained for traceability, according to the project's retention approach"* | `bep/…BEP.md` | §6.3 | 1 | **`CONTROLLED GOVERNANCE`** | — | **`CONTROLLED`** |
| `M4-S3-05` | *"visibility of WIP is not permission to rely on it"* | `bep/…BEP.md` §7.5; `supporting/cde-workflow-state-strategy.md` §1 | — | 1, 2 | **`CONTROLLED GOVERNANCE`** | — | **`CONTROLLED`** |
| `M4-S3-06` | *"**Shared does not mean** published, accepted, or suitable for every purpose"* | `supporting/cde-workflow-state-strategy.md` | §1 | 2 | `PROPOSED GOVERNANCE` | — | **`SUPPORTING`** |
| `M4-S3-07` | *"**Published does not mean** universally suitable, forever final, or automatically accepted"* | `supporting/cde-workflow-state-strategy.md` §1; `bep/…BEP.md` §6.7 | — | 1, 2 | **`CONTROLLED GOVERNANCE`** | — | **`CONTROLLED`** |
| `M4-S3-08` | Four adopted root areas — **`0. Common Files`**, **`01. WIP (Work in Progress)`**, **`02. Shared`**, **`03. Published`** | `docs/CDE-Structure-Governance-Decision.md` | §2 | 3 | **`CONTROLLED GOVERNANCE`** | **`IMPLEMENTATION UNVERIFIED`** | **`DECISION-RECORD`** |
| `M4-S3-09` | **`0. Common Files` is an area, not a state.** *"Nothing becomes approved, controlled or relied upon by being placed in it"* | `docs/CDE-Structure-Governance-Decision.md` | §3.1 | 3 | **`CONTROLLED GOVERNANCE`** | — | **`DECISION-RECORD`** |
| `M4-S3-10` | *"Placement alone does not evidence that checking or authorisation occurred"*; *"**Putting a file in `03. Published` does not publish it**"* | `docs/CDE-Structure-Governance-Decision.md` | §3.3, §3.4 | 3 | **`CONTROLLED GOVERNANCE`** | — | **`DECISION-RECORD`** |
| `M4-S3-11` | **Record / Retained need not be a root folder; no mandatory `04 Archive` root is approved or required** | `bep/…BEP.md` §6.3; `supporting/…strategy.md` §1; **`CGD-C06`** | — | 1, 2, 3 | **`CONTROLLED GOVERNANCE`** | — | **`CONTROLLED`** |
| `M4-S3-12` | **Four label forms exist for the fourth state**; they differ in casing and abbreviation, not meaning; **no source declares them synonyms** | Verified across `S1`, `S2`, `S3`, `S9` | — | 4 | — | — | **`INTERP`** |
| `M4-S3-13` | The **retention approach is TBD** | `bep/…BEP.md` §6.3; **`CGD-C06`** | — | 1, 3 | **`UNRESOLVED`** | — | **`CONTROLLED`** |
| `M4-S3-14` | *"Each state defines a different permitted purpose; movement between them requires more than technical file movement"* | none | — | 5 | — | — | **`SYNTH`** |
| `M4-S3-15` | **`Shared → Published` (`T4`) has no available authorising function; information remains Shared** | `supporting/cde-workflow-state-strategy.md` | §3.1, §3.2, §3.3 | 2 | **`BLOCKED`** | Not reached | **`SUPPORTING`** |
| `M4-S3-16` | The state model is **conceptual**; the topology and every state's live realisation are **unverified** | `docs/Increment-7C-Live-Validation-Record.md`; **`CGD-C07`** | — | 3 | — | **`IMPLEMENTATION UNVERIFIED`** | **`DECISION-RECORD`** |
| `M4-S3-17` | *Delivered*, *received*, *accepted*, *consumed* and *coordination input* are **not information states** | `supporting/cde-workflow-state-strategy.md` | §3, §13 | 2 | `PROPOSED GOVERNANCE` | — | **`SUPPORTING`** |
| `M4-S3-18` | `T1` — **the authorising function is established**: Task-Team Lead | `supporting/…strategy.md` §3.2; `bep/…BEP.md` §9.4 | — | 1, 2 | **`CONTROLLED GOVERNANCE`** | **`IMPLEMENTATION UNVERIFIED`** | **`CONTROLLED`** |

---

### Slide 4 — Work in Progress: authoring inside the task team

| ID | Statement | Source path | Section | Auth | Governance | Implementation | Class |
|---|---|---|---|---|---|---|---|
| `M4-S4-01` | *"WIP is the task team's **working state**"* — drafting, iterations, local coordination, correction, checking preparation | `bep/…BEP.md` | §7.5 | 1 | **`CONTROLLED GOVERNANCE`** | — | **`CONTROLLED`** |
| `M4-S4-02` | The originating task team is responsible for authoring, internal checking, readiness assessment, and authorisation for progression **where governance assigns it** | `bep/…BEP.md` | §6.4 | 1 | **`CONTROLLED GOVERNANCE`** | — | **`CONTROLLED`** |
| `M4-S4-03` | *"WIP may contain many versions"* — incomplete, provisional or uncoordinated work is expected | `bep/…BEP.md` | §7.5 | 1 | **`CONTROLLED GOVERNANCE`** | — | **`CONTROLLED`** |
| `M4-S4-04` | **Not authorised for general project reliance** | `bep/…BEP.md` §6.3; `supporting/cde-workflow-state-strategy.md` §1 | — | 1, 2 | **`CONTROLLED GOVERNANCE`** | — | **`CONTROLLED`** |
| `M4-S4-05` | *"**WIP versions are not project exchanges.** A new version in WIP is a working step, not a share, not an issue"* | `bep/…BEP.md` | §7.5 | 1 | **`CONTROLLED GOVERNANCE`** | — | **`CONTROLLED`** |
| `M4-S4-06` | *"**Other parties do not rely on WIP** unless an explicitly governed exception exists"* | `bep/…BEP.md` | §7.5, §7.11 | 1 | **`CONTROLLED GOVERNANCE`** | — | **`CONTROLLED`** |
| `M4-S4-07` | **"Visibility is not permission."** *"Being able to see or open another team's WIP… does not constitute authority to use it. **Permission to read is not authorisation to rely.**"* | `bep/…BEP.md` | §7.5 | 1 | **`CONTROLLED GOVERNANCE`** | — | **`CONTROLLED`** |
| `M4-S4-08` | *"**A team space is a platform construct**… **Membership confers no authority**"* | `bep/…BEP.md` | §6.4 | 1 | **`CONTROLLED GOVERNANCE`** | — | **`CONTROLLED`** |
| `M4-S4-09` | **`01. WIP (Work in Progress)`** corresponds to the WIP state; information remains under originator or task-team control | `docs/CDE-Structure-Governance-Decision.md` | §3.2 | 3 | **`CONTROLLED GOVERNANCE`** | **`IMPLEMENTATION UNVERIFIED`** | **`DECISION-RECORD`** |
| `M4-S4-10` | *"Progression from WIP requires the governed transition applicable to the intended next state"* | `docs/CDE-Structure-Governance-Decision.md` | §3.2 | 3 | **`CONTROLLED GOVERNANCE`** | — | **`DECISION-RECORD`** |
| `M4-S4-11` | The responsibility chain — Author authors · Checker checks · Task-Team Lead may authorise progression where governance establishes it | `bep/…BEP.md` §5.7, §5.8, §9.4 | — | 4 | — | — | **`INTERP`** |
| `M4-S4-12` | `ARC-01` — *"Live equivalent observed"*. **A container observation, not a workflow demonstration.** Five other containers *"not observed as a live direct coordination input at the inspected level"* | `docs/Increment-7C-Live-Validation-Record.md` | §7 | 3 | — | **`IMPLEMENTATION UNVERIFIED`** | **`DECISION-RECORD`** |
| `M4-S4-13` | The WIP workflow as a whole is **not demonstrated**; *"absence of observation is not observation of absence"* | `docs/Increment-7C-Live-Validation-Record.md` | §7 | 3 | — | **`IMPLEMENTATION UNVERIFIED`** | **`DECISION-RECORD`** |
| `M4-S4-14` | *"WIP is where a task team develops its information — not where the wider project is entitled to rely on it"* | none | — | 5 | — | — | **`SYNTH`** |
| `M4-S4-15` | Any claim that WIP access constitutes authorisation, or that visibility permits reliance | — | — | — | — | — | **`EXCLUDED`** |
| `M4-S4-16` | The complete `WIP → Shared` workflow — gates, checks and evidence | — | — | — | — | — | **`EXCLUDED` — Slides 8–11** |

### Slide 5 — Shared: controlled use for a defined purpose

| ID | Statement | Source path | Section | Auth | Governance | Implementation | Class |
|---|---|---|---|---|---|---|---|
| `M4-S5-01` | *"Information made available beyond the originating task team **for an identified purpose, after required checking and authorisation**"* | `bep/…BEP.md` | §6.3 | 1 | **`CONTROLLED GOVERNANCE`** | — | **`CONTROLLED`** |
| `M4-S5-02` | Shared carries a **stated purpose**, and readiness is judged against it | `bep/…BEP.md` | §6.3, §7.7 | 1 | **`CONTROLLED GOVERNANCE`** | — | **`CONTROLLED`** |
| `M4-S5-03` | *"**Availability is not consumption.** Information being visible, accessible or present in a shared location does not mean any team has adopted it. **Nobody consumes information by accident.**"* | `bep/…BEP.md` | §6.5 | 1 | **`CONTROLLED GOVERNANCE`** | — | **`CONTROLLED`** |
| `M4-S5-04` | *"**Consumption does not transfer technical ownership.** A receiving team that consumes a model does not acquire responsibility for its content. **The originator remains responsible for what it produced.**"* | `bep/…BEP.md` | §6.5 | 1 | **`CONTROLLED GOVERNANCE`** | — | **`CONTROLLED`** |
| `M4-S5-05` | *"**Coordination inputs come from appropriate Shared information, not from uncontrolled WIP**"* | `bep/…BEP.md` | §6.6 | 1 | **`CONTROLLED GOVERNANCE`** | — | **`CONTROLLED`** |
| `M4-S5-06` | **Shared is not technical design approval** — *"coordination input is not design approval"* | `supporting/…strategy.md` §3; `bep/…BEP.md` §8.1, §9.5 | — | 1, 2 | **`CONTROLLED GOVERNANCE`** | — | **`CONTROLLED`** |
| `M4-S5-07` | **Shared is not delivery, receipt or acceptance** — those are events, an event and a status | `supporting/cde-workflow-state-strategy.md` | §3, §13 | 2 | `PROPOSED GOVERNANCE` | — | **`SUPPORTING`** |
| `M4-S5-08` | *"No numeric quality thresholds are set"* — readiness is a judgement against the purpose, by the role authorised to make it | `bep/…BEP.md` | §7.7 | 1 | **`CONTROLLED GOVERNANCE`** | — | **`CONTROLLED`** |
| `M4-S5-09` | *"**Shared does not mean** published, accepted, or suitable for every purpose"* | `supporting/cde-workflow-state-strategy.md` | §1 | 2 | `PROPOSED GOVERNANCE` | — | **`SUPPORTING`** |
| `M4-S5-10` | `T1` is authorised by the **Task-Team Lead** — **established**. This creates **no** publication authority | `supporting/…strategy.md` §3.2; `bep/…BEP.md` §9.4, §9.7 | — | 1, 2 | **`CONTROLLED GOVERNANCE`** | **`IMPLEMENTATION UNVERIFIED`** | **`SUPPORTING`** |
| `M4-S5-11` | **`02. Shared`** corresponds to the Shared state | `docs/CDE-Structure-Governance-Decision.md` | §3.3 | 3 | **`CONTROLLED GOVERNANCE`** | **`IMPLEMENTATION UNVERIFIED`** | **`DECISION-RECORD`** |
| `M4-S5-12` | *"**Placement alone does not evidence that checking or authorisation occurred**"* | `docs/CDE-Structure-Governance-Decision.md` | §3.3 | 3 | **`CONTROLLED GOVERNANCE`** | — | **`DECISION-RECORD`** |
| `M4-S5-13` | The **BIM Coordinator** may use Shared information for coordination **without becoming the designer or originator**; **CDE Administration** implements permissions but does not authorise the transition | `bep/…BEP.md` §5.6, §6.9, §8.10; `supporting/…strategy.md` §14 | — | 1, 2 | **`CONTROLLED GOVERNANCE`** | — | **`CONTROLLED`** |
| `M4-S5-14` | *"Only Architecture currently demonstrable as a Shared input"* | `docs/Increment-7C-Live-Validation-Record.md` | §7 | 3 | — | **`IMPLEMENTATION UNVERIFIED`** | **`DECISION-RECORD`** |
| `M4-S5-15` | The authority-boundary summary — sharing authority, coordination use and administration kept apart | `S1`, `S2` | — | 4 | — | — | **`INTERP`** |
| `M4-S5-16` | *"Shared information may be relied upon only for the purpose for which it was shared"* | none | — | 5 | — | — | **`SYNTH`** |
| `M4-S5-17` | **Shared = approved** | — | — | — | — | — | **`EXCLUDED`** |
| `M4-S5-18` | `T1`'s gate, checks and evidence in detail | — | — | — | — | — | **`EXCLUDED` — Slide 10** |

### Slide 6 — Published / Authorised: a separate decision and authority

| ID | Statement | Source path | Section | Auth | Governance | Implementation | Class |
|---|---|---|---|---|---|---|---|
| `M4-S6-01` | *"passed the **required preparation, review and authorisation for an identified purpose**"* | `bep/…BEP.md` | §6.7 | 1 | **`CONTROLLED GOVERNANCE`** | — | **`CONTROLLED`** |
| `M4-S6-02` | **Published does not mean perfect** — *"Authorisation confirms fitness for a stated purpose, not absence of error"* | `bep/…BEP.md` | §6.7 | 1 | **`CONTROLLED GOVERNANCE`** | — | **`CONTROLLED`** |
| `M4-S6-03` | **Published does not mean forever final** — it can be superseded or revised | `bep/…BEP.md` | §6.7 | 1 | **`CONTROLLED GOVERNANCE`** | — | **`CONTROLLED`** |
| `M4-S6-04` | **Published does not mean universally suitable** — *"Suitability is bounded by the purpose it was authorised for"* | `bep/…BEP.md` | §6.7 | 1 | **`CONTROLLED GOVERNANCE`** | — | **`CONTROLLED`** |
| `M4-S6-05` | **Published does not mean accepted** — *"Acceptance is a separate act by an identified recipient"* | `bep/…BEP.md` | §6.7 | 1 | **`CONTROLLED GOVERNANCE`** | — | **`CONTROLLED`** |
| `M4-S6-06` | *"**Authorisation is purpose-specific.** Information authorised for one purpose is not thereby authorised for another"* | `bep/…BEP.md` | §6.7 | 1 | **`CONTROLLED GOVERNANCE`** | — | **`CONTROLLED`** |
| `M4-S6-07` | **"The role holding publication and exchange authority is UNRESOLVED."** It depends on the approved delivery arrangement, **which does not yet exist** | `bep/…BEP.md` | §9.7 | 1 | **`UNRESOLVED`** | — | **`CONTROLLED`** |
| `M4-S6-08` | It is **not automatically held by the BIM Manager, the BIM Coordinator, the CDE Administrator or the Architect**; it remains TBD *"rather than defaulting it to whichever role is nearest"* | `bep/…BEP.md` | §9.7 | 1 | **`UNRESOLVED`** | — | **`CONTROLLED`** |
| `M4-S6-09` | *"**Platform write permission is not publication authority.** Being able to place a file in a published location is a software capability, **not a decision anyone made**"* | `bep/…BEP.md` | §9.7 | 1 | **`CONTROLLED GOVERNANCE`** | — | **`CONTROLLED`** |
| `M4-S6-10` | *"`T4` therefore has **no available authorising function**, and information remains **Shared**"* | `supporting/cde-workflow-state-strategy.md` | §3.1, §3.2, §11 | 2 | **`BLOCKED`** | Not reached | **`SUPPORTING`** |
| `M4-S6-11` | **Publication is not delivery, receipt or acceptance** — `T5` and `T6` are events; `T7` is a decision and status | `supporting/cde-workflow-state-strategy.md` | §3 | 2 | `PROPOSED GOVERNANCE` | Not reached | **`SUPPORTING`** |
| `M4-S6-12` | *"**Putting a file in `03. Published` does not publish it.** Publication is a chain of governed events, not a location"* | `docs/CDE-Structure-Governance-Decision.md` | §3.4 | 3 | **`CONTROLLED GOVERNANCE`** | — | **`DECISION-RECORD`** |
| `M4-S6-13` | *"**No governed publication / exchange authority evidence was established**"* | `docs/Increment-7C-Live-Validation-Record.md` | §9 | 3 | — | **`IMPLEMENTATION UNVERIFIED`** | **`DECISION-RECORD`** |
| `M4-S6-14` | The `Shared → Published` route is **blocked**, and the block is **deliberate governance, not a technical fault** | `supporting/cde-workflow-state-strategy.md` | §11, §19 | 2 | **`BLOCKED`** | Not reached | **`SUPPORTING`** |
| `M4-S6-15` | The publication-authorising function field appears **and is empty** — omitting it would imply no authority is required | — | — | 4 | **`UNRESOLVED`** | — | **`INTERP`** |
| `M4-S6-16` | *"Publication is not the next folder; it is a separate authorised decision that this project cannot currently make"* | none | — | 5 | — | — | **`SYNTH`** |
| `M4-S6-17` | `TRN-E03` presented **as the transition itself** | — | — | — | — | — | **`EXCLUDED` — a later delivery event that depends on `T4`; detail is Slides 8–11** |
| `M4-S6-18` | Any named or substituted publication authority | — | — | — | — | — | **`EXCLUDED`** |

### Slide 7 — Record / Retained: preservation without an Archive folder

| ID | Statement | Source path | Section | Auth | Governance | Implementation | Class |
|---|---|---|---|---|---|---|---|
| `M4-S7-01` | *"Historical evidence retained for traceability, **according to the project's retention approach**"* | `bep/…BEP.md` | §6.3 | 1 | **`CONTROLLED GOVERNANCE`** | — | **`CONTROLLED`** |
| `M4-S7-02` | *"**States are not folders**"* | `bep/…BEP.md` | §6.3 | 1 | **`CONTROLLED GOVERNANCE`** | — | **`CONTROLLED`** |
| `M4-S7-03` | *"**No `04 Archive` project root requirement is confirmed**, and none is created here"* | `bep/…BEP.md` | §6.3 | 1 | **`CONTROLLED GOVERNANCE`** | — | **`CONTROLLED`** |
| `M4-S7-04` | *"The project's **retention approach is not yet defined**"* | `bep/…BEP.md` | §6.3 | 1 | **`UNRESOLVED`** | — | **`CONTROLLED`** |
| `M4-S7-05` | *"Superseded information is marked as superseded, **not deleted**"*; *"Previous exchanges remain traceable"* | `bep/…BEP.md` | §7.10 | 1 | **`CONTROLLED GOVERNANCE`** | — | **`CONTROLLED`** |
| `M4-S7-06` | *"**Prior versions and exchanges are preserved for traceability.** History is not overwritten to remove failed submissions"* | `bep/…BEP.md` | §9.9 | 1 | **`CONTROLLED GOVERNANCE`** | — | **`CONTROLLED`** |
| `M4-S7-07` | *"**History is not deleted because governance changed**"* | `bep/…BEP.md` | §12.10 | 1 | **`CONTROLLED GOVERNANCE`** | — | **`CONTROLLED`** |
| `M4-S7-08` | **Two complementary histories** — Git for technical change history, the Governance & Decision Register for decision history; *"neither substitutes for the other"* | `bep/…BEP.md` | §12.10 | 1 | **`CONTROLLED GOVERNANCE`** | — | **`CONTROLLED`** |
| `M4-S7-09` | *"**Record / Retained is a conceptual state and a retention requirement — not necessarily a folder**"*; *"no mandatory CDE root named `04 Archive` is required or approved"* | `supporting/cde-workflow-state-strategy.md` | §1, §19 | 2 | **`CONTROLLED GOVERNANCE`** · retention **TBD** | — | **`SUPPORTING`** |
| `M4-S7-10` | *"Record / Retained is approved as a **conceptual requirement, not as a mandatory `04 Archive` root**"*; *"a later approved retention and technical implementation route is still required"* | `docs/CDE-Structure-Governance-Decision.md` | §3.5; **`CGD-C06`** | 3 | **`CONTROLLED GOVERNANCE`** · method **UNRESOLVED** | — | **`DECISION-RECORD`** |
| `M4-S7-11` | **`0. Common Files` is an area mapped to no state** — *"Nothing becomes approved, controlled or relied upon by being placed in it"* | `docs/CDE-Structure-Governance-Decision.md` | §3.1 | 3 | **`CONTROLLED GOVERNANCE`** | — | **`DECISION-RECORD`** |
| `M4-S7-12` | **Record / Retained is a state mapped to no approved area** — the two mismatches are a controlled finding | `docs/CDE-Structure-Governance-Decision.md` | §3.1, §3.5 | 3 | **`CONTROLLED GOVERNANCE`** | — | **`DECISION-RECORD`** |
| `M4-S7-13` | **Retention method, location, period and holder are all unresolved.** No controlled source assigns a retention function | `bep/…BEP.md` §6.3; `supporting/…strategy.md` §19; **`CGD-C06`** | — | 1, 2, 3 | **`UNRESOLVED`** | — | **`CONTROLLED`** |
| `M4-S7-14` | *"Retention is a governed obligation; the project has not yet decided the folder, system or method by which it will be implemented"* | none | — | 5 | — | — | **`SYNTH`** |
| `M4-S7-15` | **Retention is not addressed in any validation record** — not verified, not observed, not demonstrated | `docs/Increment-7C-Live-Validation-Record.md` | — | 3 | — | **`IMPLEMENTATION UNVERIFIED`** | **`DECISION-RECORD`** |
| `M4-S7-16` | **`04 Archive`** in any form — proposed label, example, placeholder, future suggestion or visual destination | — | — | — | — | — | **`EXCLUDED`** |
| `M4-S7-17` | Any invented retention period, storage method or named holder | — | — | — | — | — | **`EXCLUDED`** |

---

## 5.1 Section B — state register

**Every field populated from controlled sources. This is a state register, not a
transition matrix.**

| Field | **WIP** | **Shared** | **Published / Authorised** | **Record / Retained** |
|---|---|---|---|---|
| **Exact controlled wording** | *"Information under originator / task-team control. Not authorised for general project reliance."* | *"Information made available beyond the originating task team for an identified purpose, after required checking and authorisation."* | *"Information authorised for a defined delivery or use purpose."* | *"Historical evidence retained for traceability, according to the project's retention approach."* |
| **Source** | `S1` §6.3 | `S1` §6.3 | `S1` §6.3 | `S1` §6.3 |
| **Purpose** | Authoring, iteration, internal checking, correction, readiness preparation | Controlled use beyond the originating team, for a stated purpose | Authorised use or delivery for a defined purpose | Preservation and traceability |
| **Reliance boundary** | **None outside the originating task team** | **The stated purpose only** | **The authorised purpose only** | Traceability and later reference |
| **Responsible originator** | Originating task team | **Originating task team — retained** | Originating task team — retained | Not assigned |
| **Checking boundary** | Task-team internal checking | Required checking **before** the share | Required review before authorisation | Not defined |
| **Authorising boundary** | Task-Team Lead may authorise progression where governance assigns it | **Task-Team Lead — established** (`T1`) | **UNRESOLVED — TBD.** Not the BIM Manager, Coordinator, CDE Administrator or Architect | **Not established** |
| **Physical-area relationship** | `01. WIP (Work in Progress)` | `02. Shared` | `03. Published` | **No approved area** |
| **Governance status** | `CONTROLLED GOVERNANCE` | `CONTROLLED GOVERNANCE` | **`BLOCKED`** | **`UNRESOLVED`** |
| **Implementation status** | `IMPLEMENTATION UNVERIFIED` | `IMPLEMENTATION UNVERIFIED` | **Not reached** | **Not addressed** |
| **Prohibited inference** | That visibility permits reliance; that access is authorisation | That Shared means approved; that consumption transfers responsibility | That it is delivered, accepted or technically approved; that an administrator may substitute | **That it is a folder; that `04 Archive` exists or is proposed** |

**`0. Common Files` appears in no column.** It is an **area mapped to no state**
(`S3` §3.1). **Four areas and four states do not align**, and the mismatch is a
controlled finding.

---

## 6. Terminology register

| Term | Exact controlled wording | Source | Status |
|---|---|---|---|
| **CDE** | *"an information-management process supported by technology"*; *"It is not a folder tree"* | `S1` §6.1 | **Defined** |
| **Information container** | Used throughout as the unit responsibility attaches to | `S1` §1.1, §7.2 | **No formal definition clause** |
| **State** | *"WIP / Shared / Published / Record"* | `S1` §6.8 | **Defined.** Short form differs in `S2` §13 |
| **Version** | *"A platform or file history instance"* | `S1` §6.8; `S2` §13 | **Defined — identical in both** |
| **Revision** | *"A controlled issue identifier, where project convention requires one"* | `S1` §6.8; `S2` §13 | **Defined; no convention established** |
| **Status** | *"A workflow or decision condition"* | `S1` §6.8; `S2` §13 | **Defined — identical in both** |
| **Suitability** | `S1`: *"What the information may be used for"*; `S2`: *"The permitted intended use"* | `S1` §6.8; `S2` §13 | **Defined; wording differs; no code set** |
| **Metadata** | Supports identity, filtering and search | `S1` §11.4 | **No schema established** |
| **WIP** | *"Information under originator / task-team control. Not authorised for general project reliance."* | `S1` §6.3; `S2` §1 | **Defined — identical in both** |
| **Shared** | *"…for an identified purpose, after required checking and authorisation"* | `S1` §6.3; `S2` §1 | **Defined; `S2` adds "deliberately"** |
| **Published / Authorised** | *"authorised for a defined delivery or use purpose"* | `S1` §6.3; `S2` §1 | **Defined; `S2` more specific** |
| **Record / Retained** | *"Historical evidence retained for traceability, according to the project's retention approach"* | `S1` §6.3 | **Defined; four label forms; retention TBD** |
| **Delivery** | *"an exchange **event**"* | `S2` §3 | **Not a state** |
| **Receipt** | *"a recipient **event**"* | `S2` §3 | **Not a state** |
| **Acceptance** | *"a recipient **decision and status** for a stated purpose"* | `S2` §3 | **Not a state** |

**Variance recorded, not harmonised — see [`source-inventory.md`](source-inventory.md) §6.**

---

## 7. Transition register

**Eight controlled steps. `S2` §3: *"only `T1` and `T4` are information-state
transitions. `T8` returns information to the originator's WIP for rework."***

| Ref | Kind | From → To | Authorising function | Governance | Implementation |
|---|---|---|---|---|---|
| **`T1`** | **State transition** | WIP → **Shared** | **Task-Team Lead** — established | **`CONTROLLED GOVERNANCE`** | **`IMPLEMENTATION UNVERIFIED`** — only Architecture demonstrable |
| `T2` | Action | Shared → Shared | Receiving task team | `PROPOSED GOVERNANCE` | `IMPLEMENTATION UNVERIFIED` |
| `T3` | Use / context | Shared → Shared | BIM Coordinator | `PROPOSED GOVERNANCE` | `IMPLEMENTATION UNVERIFIED` |
| **`T4`** | **State transition** | Shared → **Published** | **UNRESOLVED — TBD** | **`BLOCKED`** | Not reached |
| `T5` | Event | Published → Published | Originating task team; CDE Administration may execute | `PROPOSED GOVERNANCE` | Downstream of `T4` |
| `T6` | Event | Published → Published | Receiving / recipient function | `PROPOSED GOVERNANCE` | Downstream of `T4` |
| `T7` | Decision / status | Published → Published | **UNRESOLVED — TBD** | **`UNRESOLVED`** | Downstream of `T4` |
| `T8` | Rework | Shared or Published → **WIP** | Originating task team; Task-Team Lead | `PROPOSED GOVERNANCE` | `IMPLEMENTATION UNVERIFIED` |

**Full detail — purpose, gates, inputs and evidence — is in
[`source-inventory.md`](source-inventory.md) §8.**

### 7.1 `T4` and `TRN-E03` are different objects

| | `T4` | `TRN-E03` |
|---|---|---|
| Kind | **State transition** | **Delivery event** |
| Defined in | `S2` §3 | `S5` §5 |
| Relationship | **`TRN-E03` exercises `T4`** (`S2` §11) | |
| Blocking matters | **1** — publication authority | **5** — publication authority · acceptance authority · recipient identity · formats · deliverable set |

**They are not interchangeable, and `TRN-E03` is blocked by more than `T4` is.**

---

## 8. Unresolved-matter register

| # | Matter | Reference | Status |
|---|---|---|---|
| 1 | **Publication / exchange authority** | `S1` §9.7; `S6` `D4` | **UNRESOLVED / TBD** |
| 2 | **Recipient** | `S1` §2.3, §5.3 | **Not established** |
| 3 | **Acceptance authority** | `S1` §9.8, §10.11; `S6` `D7` | **UNRESOLVED / TBD** |
| 4 | **Retention approach** | `S1` §6.3; `CGD-C06` | **TBD** |
| 5 | **`04 Archive` folder** | `S1` §6.3; `S2` §1; `CGD-C06` | **Not approved, not required, not created** |
| 6 | **Platform configuration** | `CGD-C07`; `S2` §6 | **Not verified against intended governance** |
| 7 | **Implementation evidence** | `S4` | **Partial.** No complete cycle demonstrated |
| 8 | **Naming and suitability code completeness** | `S1` §11.3; `S2` §19; `S12` | **Not established — no standard exists** |
| 9 | **Metadata implementation** | `S1` §11.4 | **No schema established** |
| 10 | **Live transition operation** | `S4` §7, §8 | **Not demonstrated as a complete cycle** |
| 11 | MEP / Structural team-space mapping | **UD-001** | **UNRESOLVED** |
| 12 | Governance change approval authority by class | `S1` §12.7; `S6` `A2` | **UNRESOLVED / TBD** |

**`S2` §19's position is adopted:** *"Each is recorded so the gap stays visible
rather than being filled with a plausible value."*

---

## 9. Prohibited claims

**These may not be made in Module 4, in any file, on any slide, or in answer to
any question.**

| # | Prohibited claim | Why |
|---|---|---|
| 1 | **ACC is automatically the CDE** | `S1` §6.1 — a CDE is a process supported by technology |
| 2 | **The folder tree is the CDE** | `S1` §6.1; `S2` purpose |
| 3 | **Folder location proves state** | **`CGD-C01`** |
| 4 | **Upload or movement proves a transition** | **`CGD-C03`** |
| 5 | **Version equals revision** | `S1` §6.8 — *a new version creates none of the others* |
| 6 | **Revision equals state** | `S1` §6.8 |
| 7 | **Status equals suitability** | `S1` §6.8 — different properties, different questions |
| 8 | **Suitability equals approval or acceptance** | `S2` §3 — acceptance is a recipient decision against a purpose |
| 9 | **Shared equals Published** | `S2` §1 — *"Shared does not mean published"* |
| 10 | **Published equals Delivered** | `S2` §13 — delivery is an **event** |
| 11 | **Delivered equals Received** | `S2` §3 — separate events |
| 12 | **Received equals Accepted** | `S2` §3 — acceptance is a decision and status |
| 13 | **CDE Administration creates authority** | `S2` §14 — *"implements governance; it does not define it"* |
| 14 | **Platform permissions create authority** | `S1` §6.9; `S2` §14; **`CGD-C08`** |
| 15 | **All `T1`–`T8` operate** | `S4` — no complete cycle demonstrated |
| 16 | **`TRN-E03` is available** | `S5` §5 — **PROPOSED — BLOCKED** |
| 17 | **`T4` is operational** | `S2` §3 — **no available authorising function** |
| 18 | **Publication authority is established** | `S1` §9.7; `S4` §9 — **no evidence established** |
| 19 | **Acceptance authority is established** | `S1` §9.8; `S4` §9 — **no evidence established** |
| 20 | **`04 Archive` exists or is required** | `S1` §6.3; `S2` §1; **`CGD-C06`** |
| 21 | **Record / Retained is a folder** | `S1` §6.3; **`CGD-C06`** |
| 22 | **Planned governance is live implementation** | `S2` purpose; `S2` §6; **`CGD-C07`** |
| 23 | **The Harrismith state model proves ISO conformity** | Module 3 — no assessment exists in either direction |
| 24 | **A platform screenshot proves implementation** | `S4` §9 |
| 25 | **A missing verification proves failure** | `S4` §7 — *"Absence of observation is not observation of absence"* |

### 9.1 Additional prohibitions recorded in T4-A

| # | Prohibited | Why |
|---|---|---|
| 26 | **Eight state transitions** | **Only `T1` and `T4` are state transitions.** The other six are actions, uses, events, a status and a rework route |
| 27 | **`T4` and `TRN-E03` used interchangeably** | Different kinds of object; `TRN-E03` **exercises** `T4` and is blocked by five matters rather than one |
| 28 | **Any invented revision, status or suitability code** | **No code set exists.** All four `standards/` directories are empty |
| 29 | **Any invented metadata schema** | **None established** (`S1` §11.4) |
| 30 | **Any named CDE administrator or authority holder** | **No holder is established anywhere in the Harrismith set** |
| 31 | **Silent harmonisation of the four `Record / Retained` label forms** | No source declares them synonyms; the variance is **recorded**, not resolved |
| 32 | **Treating `0. Common Files` as an information state** | **`S3` §3.1** — *"an area, not a state"* |
| 33 | **Any live Autodesk observation, read or configuration act** | Root `README.md` §2.1. `S4` is an **existing** record, read as evidence |

**Prohibitions 22 and 25 are a matched pair, and both hold at once.** Module 4
may not present proposed governance as running, **and** may not present the
absence of verification as failure.

### 9.2 Additional prohibitions recorded in T4-B

Twenty more, arising from Slides 4–7. Same weight as §9. **These close the list
at 53.**

| # | Prohibited | Why |
|---|---|---|
| 34 | **WIP being safe for wider reliance because it is visible** | `S1` §7.5 — *"Visibility is not permission"* |
| 35 | **WIP access meaning authorisation** | `S1` §7.5 — *"Permission to read is not authorisation to rely"* |
| 36 | **Shared meaning universally approved** | `S2` §1 — *"Shared does not mean published, accepted, or suitable for every purpose"* |
| 37 | **Shared transferring technical responsibility** | `S1` §6.5 — *"The originator remains responsible for what it produced"* |
| 38 | **Shared creating publication authority** | `S1` §9.7 — the two authorities are distinct |
| 39 | **The BIM Coordinator becoming originator through coordination use** | `S1` §5.6, §8.10 — the Coordinator does not own the technical design solution |
| 40 | **The BIM Manager automatically holding publication authority** | `S1` §9.7 — **named as not automatically holding it** |
| 41 | **The CDE Administrator holding publication authority** | `S1` §9.7 — **named as not automatically holding it**; §6.9 — permission is not authority |
| 42 | **Published meaning delivered** | `S1` §6.7; `S2` §3 — delivery is an **event** |
| 43 | **Published meaning technically approved** | `S1` §6.7 — authorisation confirms fitness for a stated purpose, not technical approval |
| 44 | **Omission of the publication-authority field** | An omitted field implies **no authority is required**. It appears, and it is **empty** |
| 45 | **`T4` being operational** | `S2` §3 — **no available authorising function** |
| 46 | **`TRN-E03` being the same object as `T4`** | `TRN-E03` is a delivery event that **exercises** `T4`; it is blocked by five matters where `T4` is blocked by one |
| 47 | **Record / Retained being a folder** | `S1` §6.3; `S2` §1; **`CGD-C06`** — three independent statements |
| 48 | **`04 Archive` being proposed or assumed** | Not as a label, example, placeholder, future suggestion or visual destination |
| 49 | **Omission of the unresolved retention-method field** | An omitted method panel reads as complete. It appears, and it is **empty** |
| 50 | **A retention period being established** | **None exists in any controlled source** |
| 51 | **A named retention holder existing** | **No records manager or archive administrator exists in the Harrismith set** |
| 52 | **Four states mapping neatly to four root areas** | `0. Common Files` maps to no state; Record / Retained has no approved area. **The mismatch is a controlled finding** |
| 53 | **One qualified live observation proving full CDE implementation** | `ARC-01` is *"Live equivalent observed"* — a **container** observation, not a workflow demonstration |

**Prohibitions 44 and 49 are the same instruction applied twice.** Where an
authority or a method is required but unassigned, **the field appears and stays
empty**. Omission reads as *not needed*; an empty field reads as *needed and not
yet decided*, which is the truth.

## 10. Module-boundary deferrals

| Deferred to | Subject |
|---|---|
| **Module 5** | Responsibility-matrix construction; matrix-cell grammar; information-delivery-schedule construction; appointment-level delivery planning |
| **Module 6** | Coordination cycles; clash triage; issue escalation; technical review; assurance sampling; design approval |
| **No module** | **Any coding standard** — none exists |

**References to those controls may explain a transition gate. Detailed teaching
remains deferred.**

## 11. Status

| Field | Value |
|---|---|
| Statements classified | **Slides 1–7 — 113 statements** |
| `CONTROLLED` | 53 |
| `SUPPORTING` | 14 |
| `DECISION-RECORD` | 21 |
| `MODULE-1-3` | 1 |
| `INTERP` | 7 |
| `SYNTH` | 7 |
| `EXCLUDED` | 10 |
| Registers | **5** — source authority (§4), **state register (§5.1)**, terminology (§6), transition (§7), unresolved (§8) |
| Prohibited claims | **53** (§9, §9.1, §9.2) |
| Slides 8–14 | **Not classified.** Not developed |
| Invented codes, schemas, folders, periods or holders | **Zero** |
| Mandatory empty fields | **2** — publication authority (Slide 6) · retention method (Slide 7) |
| Live observations requested | **Zero** |
