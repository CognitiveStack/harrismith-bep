# Module 4 — Source Map, Registers and Prohibited Claims

**Status:** Traceability record for teaching material. **Not governance.**

Statement-level classification for **all fourteen slides**, the **seven
registers**, the **module-wide final reconciliation** (§11), and the list of
claims that **may not be made** in this module.

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

## 5. Statement classification — Slides 1–14

**244 statements. 94 `CONTROLLED`, 52 `SUPPORTING`, 30 `DECISION-RECORD`,
1 `MODULE-1-3`, 34 `INTERP`, 13 `SYNTH`, 20 `EXCLUDED`.**

| Slide | Statements | `CTRL` | `SUPP` | `DEC` | `M1-3` | `INT` | `SYN` | `EXC` |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| 1 | 12 | 3 | 2 | 3 | 1 | 1 | 1 | 1 |
| 2 | 14 | 7 | 2 | 1 | 0 | 2 | 1 | 1 |
| 3 | 18 | 9 | 3 | 4 | 0 | 1 | 1 | 0 |
| 4 | 16 | 8 | 0 | 4 | 0 | 1 | 1 | 2 |
| 5 | 18 | 8 | 3 | 3 | 0 | 1 | 1 | 2 |
| 6 | 18 | 9 | 3 | 2 | 0 | 1 | 1 | 2 |
| 7 | 17 | 9 | 1 | 4 | 0 | 0 | 1 | 2 |
| 8 | 17 | 3 | 3 | 5 | 0 | 3 | 1 | 2 |
| 9 | 19 | 1 | 13 | 1 | 0 | 2 | 0 | 2 |
| 10 | 20 | 7 | 9 | 1 | 0 | 0 | 1 | 2 |
| 11 | 20 | 5 | 10 | 1 | 0 | 2 | 1 | 1 |
| **12** | **20** | **13** | **1** | **0** | **0** | **4** | **1** | **1** |
| **13** | **19** | **11** | **2** | **1** | **0** | **3** | **1** | **1** |
| **14** | **16** | **1** | **0** | **0** | **0** | **13** | **1** | **1** |
| **Total** | **244** | **94** | **52** | **30** | **1** | **34** | **13** | **20** |

**Seven observations.**

**Section C shifts the source balance.** Slides 8–11 draw **35 of their 76
statements from `S2`** — the CDE strategy holds the transition logic, and says so
itself. **Section C is the only part of the module where a level-2 supporting
resource outweighs the BEP**, which is exactly what `S2` §18 records: *"This
strategy holds the transition logic."*

**Section B is overwhelmingly controlled.** Of the 69 statements on Slides 4–7,
**34 are `CONTROLLED` and 13 are `DECISION-RECORD`** — 68 per cent from level-1
and level-3 sources. **Only two are `SYNTH` per slide at most.** The four states
are among the best-evidenced material in the programme.

**Every Slide 2 property definition is `CONTROLLED`** while **every code set is
`UNRESOLVED`**: the vocabulary is governed, the coding is not.

**The two states the audience most wants are the two least available.** Published
/ Authorised is **`BLOCKED`** and Record / Retained is **`UNRESOLVED`** — and
both carry a mandatory **empty field** rather than an omission.

**Slide 12 is the most heavily controlled slide in the module** — **13 of its 20
statements are `CONTROLLED`**, and **six of those record something the project has
declined to establish**. The BEP is unusually explicit about naming and metadata
precisely because it is not creating them: it states the principles, then states
four times over that the standard, the syntax, the classification system and the
schema do not exist.

**Slide 14 inverts the module's source balance entirely.** **13 of its 16
statements are `INTERP`**, and only one is `CONTROLLED` — the two unresolved
authorities. That is the correct profile for a slide whose subject is a project
**no controlled source describes**: the Harrismith material supports the *asking*
of every question and the *answering* of none.

**Across the module, 176 of 244 statements are `CONTROLLED`, `SUPPORTING` or
`DECISION-RECORD`** — 72 per cent traceable to level 1–3 sources. **13 are
`SYNTH`**, and every one of them is a required-message line rather than a factual
claim.

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

### Slide 8 — A transition is more than moving a file

| ID | Statement | Source path | Section | Auth | Governance | Implementation | Class |
|---|---|---|---|---|---|---|---|
| `M4-S8-01` | *"**Movement or placement between platform areas must not be treated as sufficient evidence** of a WIP-to-Shared, Shared-to-Published or other information-state transition"* | `docs/CDE-Structure-Governance-Decision.md` | **`CGD-C03`** | 3 | **`CONTROLLED GOVERNANCE`** — active condition | — | **`DECISION-RECORD`** |
| `M4-S8-02` | The technical actions a user may perform — upload · move · copy · rename · change permissions · create a new platform version | — | — | 4 | — | — | **`INTERP`** |
| `M4-S8-03` | **None of those establishes** the required checks, the required evidence, transition authority, a changed permitted use, a changed suitability, publication, delivery, receipt or acceptance | `CGD-C03`; `S1` §6.8; `S2` §3 | — | 1, 2, 3 | **`CONTROLLED GOVERNANCE`** | — | **`DECISION-RECORD`** |
| `M4-S8-04` | *"Each transition requires the applicable governed **checks, authorisation and evidence**"* | `docs/CDE-Structure-Governance-Decision.md` | **`CGD-C03`** | 3 | **`CONTROLLED GOVERNANCE`** | — | **`DECISION-RECORD`** |
| `M4-S8-05` | *"**Every arrow is a controlled transition.** Each has its own trigger, its own criteria and its own responsible function"* | `supporting/cde-workflow-state-strategy.md` | §2 | 2 | `PROPOSED GOVERNANCE` | — | **`SUPPORTING`** |
| `M4-S8-06` | The six-step transition anatomy — **required input → checks → gate conditions → authorised decision → recorded evidence → changed permitted use** | `S2` §2, §3 | — | 4 | — | — | **`INTERP`** |
| `M4-S8-07` | *"Separate transitions do not require separate people… **the requirement is that each decision is made, against its own criteria, and is traceable**"* | `supporting/cde-workflow-state-strategy.md` | §2 | 2 | `PROPOSED GOVERNANCE` | — | **`SUPPORTING`** |
| `M4-S8-08` | Technical capability may allow an action | `docs/Increment-7C-Live-Validation-Record.md` | §9 | 3 | — | Observed | **`DECISION-RECORD`** |
| `M4-S8-09` | **Platform write access does not create governance authority** | `bep/…BEP.md` | §6.9, §9.7 | 1 | **`CONTROLLED GOVERNANCE`** | — | **`CONTROLLED`** |
| `M4-S8-10` | **CDE Administration configures the agreed arrangement** | `bep/…BEP.md` §5.9; `supporting/…strategy.md` §14 | — | 1, 2 | **`CONTROLLED GOVERNANCE`** | — | **`CONTROLLED`** |
| `M4-S8-11` | *"**CDE Administration implements governance; it does not define it.** Changing the software does not make a decision"* | `supporting/cde-workflow-state-strategy.md` | §14 | 2 | `PROPOSED GOVERNANCE` | — | **`SUPPORTING`** |
| `M4-S8-12` | *"**Governance decision precedes configuration change**"* | `supporting/cde-workflow-state-strategy.md` §17; `bep/…BEP.md` §12.1 | — | 1, 2 | **`CONTROLLED GOVERNANCE`** | — | **`CONTROLLED`** |
| `M4-S8-13` | *"**Being able to perform an action in the software says nothing about who was authorised to decide it**"* | `docs/Increment-7C-Live-Validation-Record.md` | §9 | 3 | — | Observed | **`DECISION-RECORD`** |
| `M4-S8-14` | **Moving the file before the decision is not a substitute for the decision** | `CGD-C03`; `S2` §17 | — | 4 | — | — | **`INTERP`** |
| `M4-S8-15` | *"The transition occurs when the project authorises a new permitted use and records the required evidence — not when a file changes location"* | none | — | 5 | — | — | **`SYNTH`** |
| `M4-S8-16` | Technical file movement constituting an authorised transition | — | — | — | — | — | **`EXCLUDED`** |
| `M4-S8-17` | A platform log proving the governance decision | — | — | — | — | — | **`EXCLUDED`** |

### Slide 9 — The eight controlled steps, and the two that change state

| ID | Statement | Source path | Section | Auth | Governance | Implementation | Class |
|---|---|---|---|---|---|---|---|
| `M4-S9-01` | **"Only `T1` and `T4` are information-state transitions. `T8` returns information to the originator's WIP for rework."** | `supporting/cde-workflow-state-strategy.md` | §3 | 2 | `PROPOSED GOVERNANCE` | — | **`SUPPORTING`** |
| `M4-S9-02` | **`T1`** — state transition, **WIP → Shared**: *"Check, then authorise share, then controlled share"* | `supporting/…strategy.md` | §3.1 | 2 | **`CONTROLLED GOVERNANCE`** | **`IMPLEMENTATION UNVERIFIED`** | **`SUPPORTING`** |
| `M4-S9-03` | **`T2`** — **action**, not a state transition: *"Receiver review; **consume** decision"*. State after: **Shared — unchanged** | `supporting/…strategy.md` | §3.1 | 2 | `PROPOSED GOVERNANCE` | `IMPLEMENTATION UNVERIFIED` | **`SUPPORTING`** |
| `M4-S9-04` | **`T3`** — **use / context**, not a state transition: *"Include in a defined coordination cycle"*. State after: **Shared — unchanged** | `supporting/…strategy.md` | §3.1 | 2 | `PROPOSED GOVERNANCE` | `IMPLEMENTATION UNVERIFIED` | **`SUPPORTING`** |
| `M4-S9-05` | **`T4`** — state transition, **Shared → Published / Authorised**: *"Delivery review, then publication / exchange authorisation"* | `supporting/…strategy.md` | §3.1 | 2 | **`BLOCKED`** | Not reached | **`SUPPORTING`** |
| `M4-S9-06` | **`T5`** — **event**: *"Controlled delivery / exchange executed"*. State after: **Published — unchanged** | `supporting/…strategy.md` | §3.1 | 2 | `PROPOSED GOVERNANCE` | Downstream of `T4` | **`SUPPORTING`** |
| `M4-S9-07` | **`T6`** — **event**: *"Recipient receives the exchange"*. State after: **Published — unchanged** | `supporting/…strategy.md` | §3.1 | 2 | `PROPOSED GOVERNANCE` | Downstream of `T4` | **`SUPPORTING`** |
| `M4-S9-08` | **`T7`** — **decision / status**: *"Recipient **accepts** or rejects for the stated purpose"*. State after: **Published — unchanged** | `supporting/…strategy.md` | §3.1 | 2 | **`UNRESOLVED`** | Downstream of `T4` | **`SUPPORTING`** |
| `M4-S9-09` | **`T8`** — **rework**, returning information to the originator's WIP, then reprogression through `T1` or `T4` | `supporting/…strategy.md` | §3.1 | 2 | `PROPOSED GOVERNANCE` | `IMPLEMENTATION UNVERIFIED` | **`SUPPORTING`** |
| `M4-S9-10` | *"**Consumed**, **coordination input**, **delivered**, **received** and **accepted** are **not** information states"* | `supporting/…strategy.md` | §3, §13 | 2 | `PROPOSED GOVERNANCE` | — | **`SUPPORTING`** |
| `M4-S9-11` | **`T4`'s authorising function is UNRESOLVED — TBD** | `supporting/…strategy.md` §3.2; `bep/…BEP.md` §9.7 | — | 1, 2 | **`BLOCKED`** | Not reached | **`SUPPORTING`** |
| `M4-S9-12` | **`T7`'s authorising function is UNRESOLVED — TBD / recipient-dependent** | `supporting/…strategy.md` §3.2; `bep/…BEP.md` §9.8, §10.11 | — | 1, 2 | **`UNRESOLVED`** | Not reached | **`SUPPORTING`** |
| `M4-S9-13` | **Five acts never collapsed** — check · authorisation · review · coordination · acceptance. *"**Checking does not authorise. Coordination does not approve design. Publication does not constitute acceptance.**"* | `supporting/…strategy.md` | §2 | 2 | `PROPOSED GOVERNANCE` | — | **`SUPPORTING`** |
| `M4-S9-14` | **`T1`'s authorising function is the Task-Team Lead** — established | `bep/…BEP.md` §9.4; `supporting/…strategy.md` §3.2 | — | 1, 2 | **`CONTROLLED GOVERNANCE`** | — | **`CONTROLLED`** |
| `M4-S9-15` | *"**PARTIALLY TRACEABLE / NOT YET DEMONSTRATED AS A COMPLETE CYCLE**"* | `docs/Increment-7C-Live-Validation-Record.md` | §8 | 3 | — | **`IMPLEMENTATION UNVERIFIED`** | **`DECISION-RECORD`** |
| `M4-S9-16` | *"The identifiers describe different controlled acts. Only two change the information state"* | `S2` §3 | — | 4 | — | — | **`INTERP`** |
| `M4-S9-17` | Grouping the eight by kind — state transitions · actions and uses · events · decision or status · rework | `S2` §3.1 | — | 4 | — | — | **`INTERP`** |
| `M4-S9-18` | Any sequential rendering — `T1 → T2 → … → T8`, a flowchart, an arrow chain or a maturity ladder | — | — | — | — | — | **`EXCLUDED`** |
| `M4-S9-19` | **`T8` as a third information-state transition** | — | — | — | — | — | **`EXCLUDED`** |

### Slide 10 — Gates, authority and evidence

| ID | Statement | Source path | Section | Auth | Governance | Implementation | Class |
|---|---|---|---|---|---|---|---|
| `M4-S10-01` | `T1` source state **WIP**, destination state **Shared** | `supporting/…strategy.md` | §3.1 | 2 | **`CONTROLLED GOVERNANCE`** | — | **`SUPPORTING`** |
| `M4-S10-02` | Purpose: *"Information is available beyond the originating task team **for the stated purpose**"* | `supporting/…strategy.md` | §3.1 | 2 | **`CONTROLLED GOVERNANCE`** | — | **`SUPPORTING`** |
| `M4-S10-03` | Trigger: *"Information ready for controlled sharing"* | `supporting/…strategy.md` | §3.2 | 2 | `PROPOSED GOVERNANCE` | — | **`SUPPORTING`** |
| `M4-S10-04` | Required check: *"Task-team technical / content check **and** information-quality / readiness check"* | `supporting/…strategy.md` | §3.2 | 2 | `PROPOSED GOVERNANCE` | — | **`SUPPORTING`** |
| `M4-S10-05` | Initiating function: **authoring team performs** | `supporting/…strategy.md` | §3.2 | 2 | `PROPOSED GOVERNANCE` | — | **`SUPPORTING`** |
| `M4-S10-06` | **Evidence: version history · checking record · share / exchange record as appropriate** | `supporting/…strategy.md` | §3.3 | 2 | `PROPOSED GOVERNANCE` | — | **`SUPPORTING`** |
| `M4-S10-07` | Failure route: *"Information remains in, or returns to, WIP. **No partial progression**"* | `supporting/…strategy.md` | §3.3 | 2 | `PROPOSED GOVERNANCE` | — | **`SUPPORTING`** |
| `M4-S10-08` | The `TRN-E01` worked chain — WIP → check → Task-Team Lead authorises share → Shared → coordination input; suitability *"coordination use only"* | `supporting/…strategy.md` | §9 | 2 | `PROPOSED GOVERNANCE` | `IMPLEMENTATION UNVERIFIED` | **`SUPPORTING`** |
| `M4-S10-09` | *"Entering a coordination cycle **does not promote a container to Published**"* | `supporting/…strategy.md` | §9 | 2 | `PROPOSED GOVERNANCE` | — | **`SUPPORTING`** |
| `M4-S10-10` | The eight readiness confirmations — information present · checking complete · container identity clear · coordinates and reference context appropriate · interfaces and issues identified · **purpose of sharing known** · receiving audience understood · required authorisation occurred | `bep/…BEP.md` | §7.7 | 1 | **`CONTROLLED GOVERNANCE`** | — | **`CONTROLLED`** |
| `M4-S10-11` | *"**No numeric quality thresholds are set**… readiness is a judgement made against the purpose of the share, by the role authorised to make it"* | `bep/…BEP.md` | §7.7 | 1 | **`CONTROLLED GOVERNANCE`** | — | **`CONTROLLED`** |
| `M4-S10-12` | *"The **Task-Team Lead** — or another role explicitly allocated that function by approved governance — authorises information to progress from WIP to Shared"* | `bep/…BEP.md` | §9.4 | 1 | **`CONTROLLED GOVERNANCE`** | — | **`CONTROLLED`** |
| `M4-S10-13` | Authorisation to share means the information is *"suitable for the **stated sharing purpose**"* — **not** suitable for construction, formally published, accepted by recipients, or technically approved for every downstream purpose | `bep/…BEP.md` | §9.4 | 1 | **`CONTROLLED GOVERNANCE`** | — | **`CONTROLLED`** |
| `M4-S10-14` | *"**Authorisation to share is not authorisation to publish or exchange.** Those are separate decisions with wider consequences"* | `bep/…BEP.md` | §9.4, §9.7 | 1 | **`CONTROLLED GOVERNANCE`** | — | **`CONTROLLED`** |
| `M4-S10-15` | *"**Not every platform feature is required for every evidence type.** The evidence must be **sufficient and traceable**"* | `bep/…BEP.md` §9.11; `supporting/…strategy.md` §16 | — | 1, 2 | **`CONTROLLED GOVERNANCE`** | — | **`CONTROLLED`** |
| `M4-S10-16` | *"**Git history proves authorship, not issue**"*; *"Authorship is not inferred from folder location"* | `bep/…BEP.md` §9.11, §7.2; `supporting/…strategy.md` §16 | — | 1, 2 | **`CONTROLLED GOVERNANCE`** | — | **`CONTROLLED`** |
| `M4-S10-17` | **The complete `T1` cycle is not demonstrated.** `ARC-01` is a container observation; *"only Architecture currently demonstrable as a Shared input"*; no complete traceable cycle observed | `docs/Increment-7C-Live-Validation-Record.md` | §7, §8 | 3 | — | **`IMPLEMENTATION UNVERIFIED`** | **`DECISION-RECORD`** |
| `M4-S10-18` | *"`T1` works as a governed transition because its purpose, checks, authority and evidence are defined — even though complete live operation is not yet verified"* | none | — | 5 | — | — | **`SYNTH`** |
| `M4-S10-19` | Omission of the `T1` evidence field | — | — | — | — | — | **`EXCLUDED`** |
| `M4-S10-20` | Folder location accepted as `T1` evidence; `ARC-01` accepted as proof of a full `T1` cycle | — | — | — | — | — | **`EXCLUDED`** |

### Slide 11 — Why `Shared → Published` remains blocked

| ID | Statement | Source path | Section | Auth | Governance | Implementation | Class |
|---|---|---|---|---|---|---|---|
| `M4-S11-01` | `T4` is the **Shared → Published / Authorised** information-state transition | `supporting/…strategy.md` | §3.1 | 2 | **`BLOCKED`** | Not reached | **`SUPPORTING`** |
| `M4-S11-02` | `T4` trigger: *"A defined delivery or exchange requirement"*; required check: **delivery readiness review** | `supporting/…strategy.md` | §3.2 | 2 | **`BLOCKED`** | Not reached | **`SUPPORTING`** |
| `M4-S11-03` | *"`T4` therefore has **no available authorising function**, and information remains **Shared**"* | `supporting/…strategy.md` | §3.1, §11 | 2 | **`BLOCKED`** | Not reached | **`SUPPORTING`** |
| `M4-S11-04` | `T4` evidence: *"Delivery review record; publication authorisation record"* — ***"Currently blocked** — no authorisation can be given while the authority is unresolved"* | `supporting/…strategy.md` | §3.3 | 2 | **`BLOCKED`** | Not reached | **`SUPPORTING`** |
| `M4-S11-05` | *"The block is represented deliberately and is **a feature of the model, not a gap in it**: **governance can intentionally stop a workflow**"* | `supporting/…strategy.md` | §11 | 2 | `PROPOSED GOVERNANCE` | — | **`SUPPORTING`** |
| `M4-S11-06` | **Published · Delivered · Received · Accepted** are four distinct things; **only Published is an information state** | `supporting/…strategy.md` §3, §13; `bep/…BEP.md` §10.11 | — | 1, 2 | **`CONTROLLED GOVERNANCE`** | — | **`SUPPORTING`** |
| `M4-S11-07` | *"**The role holding publication and exchange authority is UNRESOLVED.** It depends on the approved delivery arrangement, **which does not yet exist**"* | `bep/…BEP.md` | §9.7 | 1 | **`UNRESOLVED`** | — | **`CONTROLLED`** |
| `M4-S11-08` | It is **not automatically held by** the BIM Manager, BIM Coordinator, CDE Administrator or Architect; it remains TBD *"rather than defaulting it to whichever role is nearest"* | `bep/…BEP.md` | §9.7 | 1 | **`UNRESOLVED`** | — | **`CONTROLLED`** |
| `M4-S11-09` | *"**Authorisation to share is not authorisation to publish or exchange**"* — publication needs an authority distinct from sharing authority | `bep/…BEP.md` | §9.4 | 1 | **`CONTROLLED GOVERNANCE`** | — | **`CONTROLLED`** |
| `M4-S11-10` | *"**Platform write permission is not publication authority.** Being able to place a file in a published location is a software capability, **not a decision anyone made**"* | `bep/…BEP.md` | §9.7 | 1 | **`CONTROLLED GOVERNANCE`** | — | **`CONTROLLED`** |
| `M4-S11-11` | **Recipient acceptance authority is also UNRESOLVED — TBD** | `bep/…BEP.md` §9.8, §10.11; `S6` `D7` | — | 1, 2 | **`UNRESOLVED`** | — | **`CONTROLLED`** |
| `M4-S11-12` | `TRN-E03` is a **delivery event** — *"controlled design review / project-facing exchange"* — with status **PROPOSED — BLOCKED PENDING GOVERNANCE DECISIONS** | `supporting/information-delivery-schedule.md` | §5 | 2 | **`BLOCKED`** | Not reached | **`SUPPORTING`** |
| `M4-S11-13` | **`TRN-E03` exercises `T4`** — the event maps onto the transition; they are **different controlled objects** | `supporting/…strategy.md` | §11 | 2 | **`BLOCKED`** | — | **`SUPPORTING`** |
| `M4-S11-14` | **The five blocking matters** — publication / exchange authorisation authority · recipient acceptance authority · recipient identity · required formats · deliverable set | `supporting/information-delivery-schedule.md` | §5.1 | 2 | **`BLOCKED`** | Not reached | **`SUPPORTING`** |
| `M4-S11-15` | *"An entry that cannot proceed is recorded as blocked. **Assigning a plausible authority to make the row look finished would manufacture governance that does not exist**"* | `supporting/information-delivery-schedule.md` | §5.1 | 2 | `PROPOSED GOVERNANCE` | — | **`SUPPORTING`** |
| `M4-S11-16` | *"**No governed publication / exchange authority evidence was established**"*; *"**No governed recipient acceptance authority evidence was established**"* | `docs/Increment-7C-Live-Validation-Record.md` | §9 | 3 | — | **`IMPLEMENTATION UNVERIFIED`** | **`DECISION-RECORD`** |
| `M4-S11-17` | The publication-authorising position **appears and is empty** — omitting it would imply no authority is required | — | — | 4 | **`UNRESOLVED`** | — | **`INTERP`** |
| `M4-S11-18` | *"`T4` cannot proceed because publication authority is unassigned; `TRN-E03` remains blocked because a delivery event requires several additional decisions"* | none | — | 5 | — | — | **`SYNTH`** |
| `M4-S11-19` | **Satisfying `T4` alone would not automatically complete delivery** — `T4` is blocked by one matter, `TRN-E03` by five | `S2` §11; `S5` §5.1 | — | 4 | — | — | **`INTERP`** |
| `M4-S11-20` | `T4` and `TRN-E03` used interchangeably; any invented authority, recipient, format or deliverable; the block described as a technical failure | — | — | — | — | — | **`EXCLUDED`** |

### Slide 12 — Naming, revision, suitability and metadata support control

| ID | Statement | Source path | Section | Auth | Governance | Implementation | Class |
|---|---|---|---|---|---|---|---|
| `M4-S12-01` | *"Information containers require **unambiguous identity**"* | `bep/…BEP.md` | §11.3 | 1 | **`CONTROLLED GOVERNANCE`** | — | **`CONTROLLED`** |
| `M4-S12-02` | The six properties presented as **six distinct control questions** | — | — | 4 | — | — | **`INTERP`** |
| `M4-S12-03` | Version — *"a platform or file history instance"* | `bep/…BEP.md` | §6.8 | 1 | **`CONTROLLED GOVERNANCE`** | — | **`CONTROLLED`** |
| `M4-S12-04` | Revision — *"a controlled issue identifier, **where project convention requires one**"* | `bep/…BEP.md` | §6.8 | 1 | **`CONTROLLED GOVERNANCE`** | **No convention established** | **`CONTROLLED`** |
| `M4-S12-05` | Status — *"a workflow or decision condition"*; Suitability — *"what the information may be used for"* | `bep/…BEP.md` | §6.8 | 1 | **`CONTROLLED GOVERNANCE`** | **No code set established** | **`CONTROLLED`** |
| `M4-S12-06` | The five properties named and kept distinct in the CDE strategy | `supporting/…strategy.md` | §13 | 2 | `PROPOSED GOVERNANCE` | — | **`SUPPORTING`** |
| `M4-S12-07` | *"**A new platform version creates none of the others**"* | `bep/…BEP.md` | §6.8 | 1 | **`CONTROLLED GOVERNANCE`** | — | **`CONTROLLED`** |
| `M4-S12-08` | Metadata should support **identity; filtering and search; responsibility; state and status; delivery purpose; interoperability where required** | `bep/…BEP.md` | §11.4 | 1 | **`CONTROLLED GOVERNANCE`** | **No schema established** | **`CONTROLLED`** |
| `M4-S12-09` | *"**Platform folder placement alone is not identification** — a container must remain identifiable when moved, copied or exchanged"* | `bep/…BEP.md` | §11.3 | 1 | **`CONTROLLED GOVERNANCE`** | — | **`CONTROLLED`** |
| `M4-S12-10` | Naming should carry **origin, discipline and task-team context**, information type and required metadata where approved, with consistency for retrieval and traceability | `bep/…BEP.md` | §11.3 | 1 | **`CONTROLLED GOVERNANCE`** | — | **`CONTROLLED`** |
| `M4-S12-11` | The project **Naming Standard** (`standards/naming/`) *"**does not yet exist**"* | `bep/…BEP.md` | §11.3 | 1 | **`UNRESOLVED`** | **Not established** | **`CONTROLLED`** |
| `M4-S12-12` | *"**No final naming syntax is created here.** No field order, separator set or permitted-value list is defined, and **no ISO 19650 filename pattern is imposed**"* | `bep/…BEP.md` | §11.3 | 1 | **`UNRESOLVED`** | **Not established** | **`CONTROLLED`** |
| `M4-S12-13` | *"**No classification system is adopted.** Uniclass, OmniClass, MasterFormat and any other system remain **unadopted**"* | `bep/…BEP.md` | §11.4 | 1 | **`UNRESOLVED`** | **Not adopted** | **`CONTROLLED`** |
| `M4-S12-14` | *"**Software-native metadata is not the project standard**"*; requirements are *"**defined by governance, not inherited** from whatever fields a tool happens to provide"* | `bep/…BEP.md` | §11.4 | 1 | **`CONTROLLED GOVERNANCE`** | — | **`CONTROLLED`** |
| `M4-S12-15` | **A revision does not authorise a transition; status is not suitability; suitability is not acceptance** | `bep/…BEP.md` §6.8; `supporting/…strategy.md` §3 | — | 4 | — | — | **`INTERP`** |
| `M4-S12-16` | **Metadata alone proves no authorisation** — a complete attribute set is consistent with an unauthorised transition | `bep/…BEP.md` §11.4, §6.9 | — | 4 | — | — | **`INTERP`** |
| `M4-S12-17` | The properties **contribute to** transition evidence — identity, originator, version history, checked condition, declared permitted use, transition record, traceability | `bep/…BEP.md` §9.11; `supporting/…strategy.md` §3.3 | — | 4 | — | — | **`INTERP`** |
| `M4-S12-18` | **Naming standard, revision convention, suitability code set and metadata schema are all `not established`** — `standards/naming/`, `standards/coordinates/`, `standards/templates/` and `standards/titleblocks/` each contain only a `.gitkeep` | `standards/` (repository state); `bep/…BEP.md` §11.3, §11.4 | — | 1 | **`UNRESOLVED`** | **Not established** | **`CONTROLLED`** |
| `M4-S12-19` | *"Naming and metadata support control by identifying information and its permitted use — but the code never replaces the governance decision"* | none | — | 5 | — | — | **`SYNTH`** |
| `M4-S12-20` | Any invented filename, revision, suitability, status or metadata value; any adopted classification system; any claim that a correct name proves state, authorisation or process | — | — | — | — | — | **`EXCLUDED`** |

### Slide 13 — Governance first; permissions and configuration follow

| ID | Statement | Source path | Section | Auth | Governance | Implementation | Class |
|---|---|---|---|---|---|---|---|
| `M4-S13-01` | The chain **governance decision → process rule → permission or configuration → implementation evidence** presented as one model | `bep/…BEP.md` §12.1, §12.8; `supporting/…strategy.md` §17 | — | 4 | — | — | **`INTERP`** |
| `M4-S13-02` | **The reverse arrow appears and is visibly refused** — a platform setting creates no governance authority | `bep/…BEP.md` §5.9, §6.9 | — | 4 | — | — | **`INTERP`** |
| `M4-S13-03` | *"**CDE Administration implements governance; it does not create it.** Changing the software does not make a decision"* | `bep/…BEP.md` | §5.9 | 1 | **`CONTROLLED GOVERNANCE`** | — | **`CONTROLLED`** |
| `M4-S13-04` | The **may / does not** boundary presented as a matched pair of equal weight | `bep/…BEP.md` §5.9 | — | 4 | — | — | **`INTERP`** |
| `M4-S13-05` | CDE Administration responsibilities — membership; folder and space implementation; permissions; Design Collaboration team-space configuration; coordination-space configuration; platform workflow configuration; implementation of approved changes; checking configuration after change | `bep/…BEP.md` | §5.9 | 1 | **`CONTROLLED GOVERNANCE`** | **`IMPLEMENTATION UNVERIFIED`** | **`CONTROLLED`** |
| `M4-S13-06` | *"**A configuration that was never approved is a deviation, however competently it was applied**"* | `bep/…BEP.md` | §5.9 | 1 | **`CONTROLLED GOVERNANCE`** | — | **`CONTROLLED`** |
| `M4-S13-07` | *"Holding administrative rights over a folder, space or team confers **the technical ability to change it and nothing more**"* | `bep/…BEP.md` | §5.9 | 1 | **`CONTROLLED GOVERNANCE`** | — | **`CONTROLLED`** |
| `M4-S13-08` | *"**Platform permission is not BEP authority**"*; administrator rights do not substitute for an appointment | `bep/…BEP.md` | §5.9 | 1 | **`CONTROLLED GOVERNANCE`** | — | **`CONTROLLED`** |
| `M4-S13-09` | CDE Administration — **Holder: TBD** | `bep/…BEP.md` | §5.9 | 1 | **`UNRESOLVED`** | — | **`CONTROLLED`** |
| `M4-S13-10` | **Deviation** = knowingly permitted departure; **non-conformance** = unintended departure. *"The difference is **intent and authorisation, not severity**"* | `bep/…BEP.md` | §12.6 | 1 | **`CONTROLLED GOVERNANCE`** | — | **`CONTROLLED`** |
| `M4-S13-11` | *"**Document, process and platform configuration must remain aligned.** A change applied to one and not the others produces a governance system that describes something the project is not doing — **the most common way controlled documentation becomes ignored**"* | `bep/…BEP.md` | §12.8 | 1 | **`CONTROLLED GOVERNANCE`** | **`IMPLEMENTATION UNVERIFIED`** | **`CONTROLLED`** |
| `M4-S13-12` | *"**This BEP does not itself authorise any live platform change**"* | `bep/…BEP.md` | §12.8 | 1 | **`CONTROLLED GOVERNANCE`** | — | **`CONTROLLED`** |
| `M4-S13-13` | A configuration is **not complete because a setting was applied** — the change must be checked after it is made | `bep/…BEP.md` | §12.9, §5.9 | 1 | **`CONTROLLED GOVERNANCE`** | **`IMPLEMENTATION UNVERIFIED`** | **`CONTROLLED`** |
| `M4-S13-14` | Governance change decisions sit with the **responsible governance function**, by change class | `bep/…BEP.md` | §12.1, §12.7 | 1 | **`CONTROLLED GOVERNANCE`** | — | **`CONTROLLED`** |
| `M4-S13-15` | *"Access is configured to follow approved responsibility; responsibility comes first and permission follows it. Where access and approved responsibility diverge, the divergence is recorded as a **deviation**"* | `supporting/…strategy.md` | §14 | 2 | `PROPOSED GOVERNANCE` | **`IMPLEMENTATION UNVERIFIED`** | **`SUPPORTING`** |
| `M4-S13-16` | Intended-versus-implemented is a **four-layer** question, and platform rules are recorded separately from governance rules | `supporting/…strategy.md` | §6, §17 | 2 | `PROPOSED GOVERNANCE` | **`IMPLEMENTATION UNVERIFIED`** | **`SUPPORTING`** |
| `M4-S13-17` | *"Configuration implements governance. It does not create it."* — the controlled sentence condensed for the slide | `bep/…BEP.md` §5.9 | — | 5 | — | — | **`SYNTH`** |
| `M4-S13-18` | **Harrismith's own configuration alignment is not verified** — *"no complete cycle demonstrated"*; demonstrability judged on evidence, not intent | `docs/Increment-7C-Live-Validation-Record.md` | §7, §11 | 3 | — | **`IMPLEMENTATION UNVERIFIED`** | **`DECISION-RECORD`** |
| `M4-S13-19` | Any named CDE Administrator; configuration presented as conferring authority; Harrismith's alignment presented as verified; any authorisation of a live platform change | — | — | — | — | — | **`EXCLUDED`** |

### Slide 14 — What Triviron must define before configuring its CDE

**No controlled source describes Triviron.** Every `INTERP` row below is a
**question structure** derived from a Harrismith control — the control supports
the *asking*, never an answer.

| ID | Statement | Source path | Section | Auth | Governance | Implementation | Class |
|---|---|---|---|---|---|---|---|
| `M4-S14-01` | **No Triviron project fact exists in the controlled evidence** — no jurisdiction, project type, client, asset, procurement route, appointment, platform, structure, state, code, schema or date | — | — | 4 | **None asserted** | **None asserted** | **`INTERP`** |
| `M4-S14-02` | **Group 1 — CDE purpose and scope**: what information, which teams, which uses, which phases, what evidence that the process operates | `bep/…BEP.md` §6.1; `supporting/…strategy.md` §1 | — | 4 | — | — | **`INTERP`** |
| `M4-S14-03` | **Group 2 — states and permitted use**: which states, what each is for, who may rely on each, conceptual or physical, which folder relationship | `bep/…BEP.md` §6.3, §6.4 | — | 4 | — | — | **`INTERP`** |
| `M4-S14-04` | **"How will the project prevent folder location from being mistaken for state?"** | `bep/…BEP.md` §6.1; **`CGD-C01`, `CGD-C03`** | — | 4 | — | — | **`INTERP`** |
| `M4-S14-05` | **Group 3 — transitions, gates and authority**: which actions change state, who initiates, who checks, who authorises | `supporting/…strategy.md` §2, §3.3 | — | 4 | — | — | **`INTERP`** |
| `M4-S14-06` | **"What happens when an authority is unassigned?"** | `supporting/…strategy.md` §11, §19; `S5` §5.1 | — | 4 | — | — | **`INTERP`** |
| `M4-S14-07` | **"Which transitions must remain blocked?"** | `supporting/…strategy.md` §11 | — | 4 | — | — | **`INTERP`** |
| `M4-S14-08` | **Group 4 — naming, revision, suitability and metadata**: which standard, which convention, which codes, what schema, who assigns and checks | `bep/…BEP.md` §11.3, §11.4 | — | 4 | — | — | **`INTERP`** |
| `M4-S14-09` | **"How will codes be distinguished from evidence of the underlying process?"** | `bep/…BEP.md` §9.11; **`CGD-C03`** | — | 4 | — | — | **`INTERP`** |
| `M4-S14-10` | **Group 5 — platform configuration and implementation evidence**: which platform, who may configure, how authorised, how deviations are recorded, how configuration is verified, who declares readiness | `bep/…BEP.md` §5.9, §12.6, §12.8; `S4` §7, §11 | — | 4 | — | — | **`INTERP`** |
| `M4-S14-11` | **The order of the five groups is the argument** — purpose before states, states before transitions, configuration last | — | — | 4 | — | — | **`INTERP`** |
| `M4-S14-12` | **`Who holds publication authority?`** and **`Who holds acceptance authority?`** correspond to two Harrismith authorities recorded as **UNRESOLVED**, and `S1` §9.7 names **four roles that do not hold the first by default** | `bep/…BEP.md` | §9.7, §9.8 | 1 | **`UNRESOLVED`** | — | **`CONTROLLED`** |
| `M4-S14-13` | *"Configure the platform only after the states, purposes, authorities, gates and evidence requirements have been decided"* | none | — | 5 | — | — | **`SYNTH`** |
| `M4-S14-14` | **`CDE configuration basis — not yet established`** as the visible end state — a neutral future position, not a failure warning | — | — | 4 | **`UNRESOLVED`** | — | **`INTERP`** |
| `M4-S14-15` | **Triviron has no entry in any register in this module** — no governance status and no implementation status is asserted for it, because no controlled source describes it | — | — | 4 | **None asserted** | **None asserted** | **`INTERP`** |
| `M4-S14-16` | Any Triviron fact; any answered or hinted-at authority question; any recommended convention, code set, schema, platform or folder structure; any implementation or ISO conformity claim; any Harrismith status transferred onto Triviron | — | — | — | — | — | **`EXCLUDED`** |

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

## 5.2 Property register

**Six properties. Every definition controlled; every code set unestablished.**

| Field | **Name / identifier** | **Version** | **Revision** | **Status** | **Suitability** | **Metadata** |
|---|---|---|---|---|---|---|
| **Control question** | Which container is this? | Which stored platform occurrence? | Which managed issue applies? | What condition is declared? | For what purpose may it be relied upon? | Which structured attributes support control? |
| **Exact controlled wording** | *"Information containers require unambiguous identity"* | *"A platform or file history instance"* | *"A controlled issue identifier, **where project convention requires one**"* | *"A workflow or decision condition"* | `S1`: *"What the information may be used for"*; `S2`: *"The permitted intended use"* | Supports *"identity; filtering and search; responsibility; state and status; delivery purpose; interoperability where required"* |
| **Source** | `S1` §11.3 | `S1` §6.8; `S2` §13 | `S1` §6.8; `S2` §13 | `S1` §6.8; `S2` §13 | `S1` §6.8; `S2` §13 | `S1` §11.4 |
| **Created by** | Governance decision, applied by the originator | **The platform, automatically** | **A person, as part of a managed issue** | A workflow or decision act | An authorising decision | Governance requirement, applied by the originator |
| **What it does control** | Identification and traceability | Which stored occurrence is referenced | Which issue is referenced | The declared condition | **Permitted use** | Filtering, search, responsibility, delivery purpose |
| **What it does not control** | **State, authorisation, permitted use** | **Revision, state, status, suitability** | **State transition or authorisation** | **Suitability** | **Approval or acceptance** | **Authority** |
| **Standard established?** | **NO** — `standards/naming/` empty | Platform-native; no project convention | **NO** — no convention | **NO** — no code set | **NO** — no code set | **NO** — no schema |
| **Governance status** | **`UNRESOLVED`** | `CONTROLLED GOVERNANCE` (definition) | **`UNRESOLVED`** | **`UNRESOLVED`** | **`UNRESOLVED`** | **`UNRESOLVED`** |
| **Implementation status** | **Not established** | Platform behaviour, **unverified against governance** | **Not established** | **Not established** | **Not established** | **Not established** |
| **Prohibited inference** | That a correct name proves state, authorisation or that a process occurred | That a new version is a new revision or issue | That a revision authorises a transition | That status equals suitability | That suitability equals approval or acceptance | That metadata creates authority, or that software fields are the standard |

**Four standards do not exist, and the BEP says so four separate times.** The
**Naming Standard** *"does not yet exist"*; **no final naming syntax is created**
and **no ISO 19650 filename pattern is imposed** (`S1` §11.3); **no
classification system is adopted** (`S1` §11.4); and **software-native metadata is
not the project standard** (`S1` §11.4).

**All four `standards/` directories were inspected and contain only a
`.gitkeep`** — `standards/naming/`, `standards/coordinates/`,
`standards/templates/`, `standards/titleblocks/`. **This is a repository
observation, not an inference.**

**The register's whole point is the row second from the bottom.** Every
definition is governed; **not one code set is established.** A module that taught
the definitions without that row would leave an audience believing a standard
exists somewhere it has not yet looked.

---

## 5.3 Configuration-decision register

**What must be decided, who decides it, and what may only implement it.**

| # | Decision | Decided by | Implemented by | Status | Source |
|---|---|---|---|---|---|
| 1 | **The information-state model** — which states, what each permits | Governance | Not a configuration act at all | **`CONTROLLED GOVERNANCE`** — four states defined | `S1` §6.3; `S2` §1 |
| 2 | **Which actions constitute state transitions** | Governance | — | **`PROPOSED GOVERNANCE`** — only `T1` and `T4` | `S2` §3 |
| 3 | **`T1` sharing authority** | Governance | Platform permission follows | **Established** — Task-Team Lead | `S2` §3.1 |
| 4 | **`T4` publication / exchange authority** | Governance | — | **`UNRESOLVED` — TBD** | `S1` §9.7 |
| 5 | **Recipient acceptance authority** | Governance | — | **`UNRESOLVED` — TBD** | `S1` §9.8 |
| 6 | **Retention approach and method** | Governance | Platform or process, once decided | **`UNRESOLVED` — TBD**; **no `04 Archive` approved** | `S1` §6.3; `CGD-C06` |
| 7 | **CDE structural areas** | Governance | CDE Administration | **Adopted with eight conditions** | `CGD-001` §2; `CGD-C01`–`CGD-C08` |
| 8 | **Folder and space implementation** | — | **CDE Administration, where authorised** | **`IMPLEMENTATION UNVERIFIED`** | `S1` §5.9 |
| 9 | **Permissions and access rights** | Governance assigns responsibility first | **CDE Administration configures to follow it** | **`IMPLEMENTATION UNVERIFIED`**; divergence is a **deviation** | `S1` §6.9; `S2` §14 |
| 10 | **Design Collaboration team-space configuration** | Governance | CDE Administration | **`IMPLEMENTATION UNVERIFIED`**; **UD-001** unresolved | `S1` §5.9, §6.4 |
| 11 | **Platform workflow configuration** | Governance | CDE Administration | **`IMPLEMENTATION UNVERIFIED`** | `S1` §5.9; `S2` §17 |
| 12 | **Naming standard** | Governance | Applied by originators | **`UNRESOLVED`** — does not exist | `S1` §11.3 |
| 13 | **Revision convention** | Governance | Applied by originators | **`UNRESOLVED`** — none | `S1` §6.8 |
| 14 | **Status and suitability code sets** | Governance | Applied at transitions | **`UNRESOLVED`** — none | `S1` §6.8 |
| 15 | **Metadata schema** | Governance | Platform fields may carry it | **`UNRESOLVED`** — none; **software-native metadata is not the standard** | `S1` §11.4 |
| 16 | **Classification system** | Governance | — | **`UNRESOLVED`** — **none adopted** | `S1` §11.4 |
| 17 | **CDE Administration holder** | Appointment | — | **TBD** | `S1` §5.9 |
| 18 | **Verification that configuration matches governance** | Governance sets the requirement | CDE Administration checks after change | **`IMPLEMENTATION UNVERIFIED`** — *"no complete cycle demonstrated"* | `S1` §12.9; `S4` §8, §11 |

**Read the two right-hand columns of the middle rows together.** Rows 8–11 are
**implementation without verification**; rows 12–17 are **decisions not yet made**.
Neither is a software problem, and neither is fixed by configuring something.

**Three sentences govern the whole register.** *"CDE Administration implements
governance; it does not create it"* (`S1` §5.9). *"A configuration that was never
approved is a deviation, however competently it was applied"* (`S1` §5.9).
*"Document, process and platform configuration must remain aligned"* (`S1` §12.8).

**And one boundary applies to every row.** *"This BEP does not itself authorise
any live platform change"* (`S1` §12.8) — **and neither does this teaching
module.**

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

### 7.1 Expanded register — seventeen fields, `T1`–`T8`

**Verified in T4-C. `—` means the source supplies no value; no field is
populated by inference.**

#### `T1` — WIP → Shared · the only transition with an established authority

| Field | Value | Source |
|---|---|---|
| **Identifier** | `T1` | `S2` §3.1 |
| **Exact description** | *"Check, then authorise share, then controlled share"* | `S2` §3.1 |
| **Kind** | **Information-state transition** | `S2` §3 |
| **Source state** | WIP | `S2` §3.1 |
| **Destination** | **Shared** | `S2` §3.1 |
| **Initiating function** | Authoring team performs | `S2` §3.2 |
| **Checking function** | Task team — technical/content **and** information-quality/readiness | `S2` §3.2; `S1` §5.8 |
| **Authorising function** | **Task-Team Lead**, or another role explicitly allocated by approved governance | **`S1` §9.4**; `S2` §3.2 |
| **Required input** | Information ready for controlled sharing | `S2` §3.2 |
| **Gate conditions** | The eight readiness confirmations; **no numeric threshold** | `S1` §7.7 |
| **Evidence required** | Task-team checking complete before authorisation | `S1` §7.7; `S2` §3.2 |
| **Evidence produced** | **Version history · checking record · share / exchange record** | `S2` §3.3 |
| **Permitted use** | *"Suitable for the stated sharing purpose"* — and no further | `S1` §9.4 |
| **Governance status** | **`CONTROLLED GOVERNANCE`** | — |
| **Implementation status** | **`IMPLEMENTATION UNVERIFIED`** — only Architecture demonstrable; no complete cycle | `S4` §7, §8 |
| **Source reference** | `S2` §3.1–§3.3, §9; `S1` §7.7, §9.4 | — |
| **Prohibited inference** | That `T1` authority creates publication authority; that folder location is evidence; that `ARC-01` proves a complete cycle | — |

#### `T4` — Shared → Published / Authorised · blocked

| Field | Value | Source |
|---|---|---|
| **Identifier** | `T4` | `S2` §3.1 |
| **Exact description** | *"Delivery review, then publication / exchange authorisation"* | `S2` §3.1 |
| **Kind** | **Information-state transition** | `S2` §3 |
| **Source state** | Shared | `S2` §3.1 |
| **Destination** | **Published / Authorised** — **not reached** | `S2` §3.1 |
| **Initiating function** | — | — |
| **Checking function** | Delivery readiness review | `S2` §3.2 |
| **Authorising function** | **UNRESOLVED — TBD** | **`S1` §9.7**; `S6` `D4` |
| **Required input** | A defined delivery or exchange requirement | `S2` §3.2 |
| **Gate conditions** | Delivery readiness review | `S2` §3.2 |
| **Evidence required** | — **cannot be produced; the decision cannot be made** | `S2` §3.3 |
| **Evidence produced** | *"Delivery review record; publication authorisation record"* — **currently unobtainable** | `S2` §3.3 |
| **Permitted use** | *"Authorised for the identified purpose"* — **not reached** | `S2` §3.1 |
| **Governance status** | **`BLOCKED`** — *"no available authorising function… information remains Shared"* | `S2` §3.1, §3.3, §11 |
| **Implementation status** | **Not reached.** *"No governed publication / exchange authority evidence was established"* | `S4` §9 |
| **Source reference** | `S2` §3.1–§3.3, §11, §19; `S1` §9.7 | — |
| **Prohibited inference** | That `T4` is available; that an administrator may substitute; that `T4` and `TRN-E03` are the same object | — |

#### `T2`, `T3`, `T5`, `T6`, `T7`, `T8` — not state transitions

| Field | `T2` | `T3` | `T5` | `T6` | `T7` | `T8` |
|---|---|---|---|---|---|---|
| **Kind** | **Action** | **Use / context** | **Event** | **Event** | **Decision / status** | **Rework route** |
| **Exact description** | *"Receiver review; consume decision"* | *"Include in a defined coordination cycle"* | *"Controlled delivery / exchange executed"* | *"Recipient receives the exchange"* | *"Recipient accepts or rejects for the stated purpose"* | *"Correction in the originator's WIP, then check, then reauthorise"* |
| **State before** | Shared | Shared | Published | Published | Published | Shared or Published |
| **State after** | **Shared — unchanged** | **Shared — unchanged** | **Published — unchanged** | **Published — unchanged** | **Published — unchanged** | **WIP**, then reprogression |
| **Initiating function** | Receiving task team | **BIM Coordinator** | Originating task team | Recipient | Recipient | Originating task team |
| **Checking function** | Receiver review of suitability | Input readiness | Transmission prepared | Registration of receipt | Assessment against the requirement | Task-team check of revised information |
| **Authorising function** | Receiving task team | BIM Coordinator | Originating task team; **CDE Administration may execute platform functions** | Receiving / recipient function | **UNRESOLVED — TBD / recipient-dependent** | **Task-Team Lead** |
| **Evidence produced** | Consume state or history; receiver's record | Coordination input record; federation record | Transmission record — what, when, by which role, to whom, for what purpose | Receipt record | Acceptance or rejection record, with the stated purpose | Issue history; revised version history; re-check and re-authorisation records; superseded marking |
| **Governance status** | `PROPOSED` | `PROPOSED` | `PROPOSED` | `PROPOSED` | **`UNRESOLVED`** | `PROPOSED` |
| **Implementation status** | Unverified | Unverified | Downstream of `T4` | Downstream of `T4` | Downstream of `T4` | Unverified |
| **Prohibited inference** | That availability is consumption | That coordination input is design approval | That delivery changes the state | That receipt is acceptance | That acceptance transfers technical responsibility | **That `T8` is a third state transition** |

**Source for the whole table:** `S2` §3.1, §3.2, §3.3. **Full purpose and gate
detail is in [`source-inventory.md`](source-inventory.md) §8.**

**Two fields are deliberately empty.** `T4`'s **initiating function** and its
**evidence required** carry no value, because **the decision cannot be made**.
They are shown, not omitted.

### 7.2 `T4` and `TRN-E03` are different objects

| | `T4` | `TRN-E03` |
|---|---|---|
| Kind | **State transition** | **Delivery event** |
| Defined in | `S2` §3 | `S5` §5 |
| Relationship | **`TRN-E03` exercises `T4`** (`S2` §11) | |
| Blocking matters | **1** — publication authority | **5** — publication authority · acceptance authority · recipient identity · formats · deliverable set |

**They are not interchangeable, and `TRN-E03` is blocked by more than `T4` is.**

---

## 8. Module-wide unresolved register

**Every unresolved matter Module 4 touches, in one place. Eighteen entries, in
five classes.** Nothing here is filled with a plausible value.

### 8.1 Unresolved authorities — 4

| # | Matter | Reference | Status | Slides |
|---|---|---|---|---|
| 1 | **Publication / exchange authority** | `S1` §9.7; `S6` `D4` | **UNRESOLVED / TBD.** *"Not automatically"* the BIM Manager, BIM Coordinator, CDE Administrator or Architect | **6, 11, 14** |
| 2 | **Recipient acceptance authority** | `S1` §9.8, §10.11; `S6` `D7` | **UNRESOLVED / TBD** | **9, 11, 14** |
| 3 | **CDE Administration holder** | `S1` §5.9 | **TBD.** No name exists anywhere in the Harrismith set | **13** |
| 4 | Governance change approval authority by class | `S1` §12.7; `S6` `A2` | **UNRESOLVED / TBD** | 13 |

### 8.2 Unresolved standards — 5

| # | Matter | Reference | Status | Slides |
|---|---|---|---|---|
| 5 | **Naming standard** | `S1` §11.3; `standards/naming/` | **Does not exist.** No syntax, no field order, no separators, no permitted values; **no ISO 19650 pattern imposed** | **12, 14** |
| 6 | **Revision convention** | `S1` §6.8 | **Not established** | **12, 14** |
| 7 | **Status and suitability code sets** | `S1` §6.8; `S2` §19 | **Not established** | **2, 12, 14** |
| 8 | **Metadata schema** | `S1` §11.4 | **Not established.** *"Software-native metadata is not the project standard"* | **12, 14** |
| 9 | **Classification system** | `S1` §11.4 | **None adopted.** Uniclass, OmniClass, MasterFormat all **unadopted** | **12** |

### 8.3 Unresolved process matters — 4

| # | Matter | Reference | Status | Slides |
|---|---|---|---|---|
| 10 | **Retention approach and method** | `S1` §6.3; `CGD-C06` | **TBD** | **7, 14** |
| 11 | **`04 Archive` folder** | `S1` §6.3; `S2` §1; `CGD-C06` | **Not approved, not required, not created — and not to be invented** | **7** |
| 12 | **Recipient identity** | `S1` §2.3, §5.3; `S5` §5.1 | **Not established** | 11 |
| 13 | **Required formats and deliverable set** | `S5` §5.1 | **Not established** | 11 |

### 8.4 Unverified implementation — 4

| # | Matter | Reference | Status | Slides |
|---|---|---|---|---|
| 14 | **Platform configuration versus intended governance** | `CGD-C07`; `S2` §6 | **Not verified** | **13** |
| 15 | **Live transition operation** | `S4` §7, §8 | **Not demonstrated as a complete cycle** | 9, 10 |
| 16 | **Implementation evidence generally** | `S4` | **Partial.** No complete cycle demonstrated | 3–11 |
| 17 | MEP / Structural team-space mapping | **UD-001** | **UNRESOLVED** — recorded, never silently corrected | 3 |

### 8.5 Outside the evidence entirely — 1

| # | Matter | Reference | Status | Slides |
|---|---|---|---|---|
| 18 | **Every Triviron decision** | **No source exists** | **Not unresolved — undescribed.** Triviron has no entry in any register in this module, and no status is asserted for it | **14** |

**Entry 18 is a different kind of entry, and the distinction matters.** Entries
1–17 are matters a controlled document has **recorded as open**. Entry 18 is a
project **no controlled document mentions at all** — so Module 4 asks questions
about it and records nothing.

**`S2` §19's position is adopted throughout:** *"Each is recorded so the gap
stays visible rather than being filled with a plausible value."* **Eighteen gaps,
eighteen visible.**

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

### 9.3 Additional prohibitions recorded in T4-C

Twenty-two more, arising from Slides 8–11. Same weight as §9. **These close the
list at 75.**

| # | Prohibited | Why |
|---|---|---|
| 54 | **Technical file movement constituting an authorised transition** | **`CGD-C03`** — movement *"must not be treated as sufficient evidence"* of a transition |
| 55 | **A platform log proving the governance decision** | `S1` §9.11; `S2` §16 — *"**Git history proves authorship, not issue**"* |
| 56 | **`T1`–`T8` being eight sequential state transitions** | `S2` §3 — **only `T1` and `T4` are information-state transitions** |
| 57 | **`T1`–`T8` being a mandatory chronological workflow** | They are identifiers for different controlled **acts**, not steps in a queue |
| 58 | **Mermaid or arrow chains implying progression through `T1`–`T8`** | A chain asserts one mandatory order, eight transitions, automatic progression and a complete operating route — **four claims the sources deny** |
| 59 | **`T8` being a third information-state transition** | `S2` §3 — it **returns** information to WIP and reuses `T1` or `T4` on reprogression |
| 60 | **All `T1`–`T8` having authorising functions** | `T4` and `T7` are **UNRESOLVED — TBD** |
| 61 | **All `T1`–`T8` being operational** | `S4` §8 — *"PARTIALLY TRACEABLE / NOT YET DEMONSTRATED AS A COMPLETE CYCLE"* |
| 62 | **Omission of the `T1` evidence field** | Evidence is what distinguishes a governed transition from a file move. **If something must be cut, cut a gate condition** |
| 63 | **Folder location accepted as `T1` evidence** | `S1` §7.2 — *"Authorship is not inferred from folder location"* |
| 64 | **`ARC-01` proving a full `T1` cycle** | A **container** observation, not a cycle. `S4` §8 records no complete traceable cycle |
| 65 | **Task-Team Lead publication authority arising from `T1`** | **`S1` §9.4** — *"Authorisation to share is not authorisation to publish or exchange"* |
| 66 | **`T4` being available** | `S2` §3.1 — **no available authorising function** |
| 67 | **`T4` and `TRN-E03` being interchangeable** | Different controlled objects — a state transition and a delivery event. **`TRN-E03` exercises `T4`** |
| 68 | **`TRN-E03` being only a publication transition** | It is a **delivery event** with four dependencies beyond publication authority |
| 69 | **Assigning publication authority automatically completing `TRN-E03`** | Four further matters remain — acceptance authority, recipient identity, formats, deliverable set. **Satisfying `T4` alone would not complete delivery** |
| 70 | **Published meaning Delivered** | `S2` §3 — delivery is an **event**; the state is unchanged |
| 71 | **Delivered meaning Received** | `S2` §3 — two separate events |
| 72 | **Received meaning Accepted** | `S2` §3 — acceptance is a **decision and status**, and its authority is unresolved |
| 73 | **CDE Administration substituting for publication authority** | `S1` §9.7 — named as **not** holding it; *"platform write permission is not publication authority"* |
| 74 | **The block being a software failure** | `S2` §11 — *"a feature of the model, not a gap in it: **governance can intentionally stop a workflow**"* |
| 75 | **Information progressing while authority remains unresolved** | `S2` §3.1 — **information remains Shared**. There is no partial progression |

**Prohibitions 56–59 are one error in four forms**, and **58 is the one a
producer commits silently.** A flowchart of `T1`–`T8` renders eight sequential
transitions no matter what the caption says — which is why `W9` is specified as a
**grouped table, and not Mermaid**.

**Prohibitions 66–69 protect the `T4`/`TRN-E03` distinction**, and 69 is the one
an audience reaches for: resolving the publication authority is necessary for
delivery and **nowhere near sufficient**.

### 9.4 Additional prohibitions recorded in T4-D

Twenty-four more, arising from Slides 12–14. Same weight as §9. **These close
the module-wide list at 99.**

**Codes and standards — 12**

| # | Prohibited | Why |
|---|---|---|
| 76 | **Any invented filename or naming syntax, in any format** | `S1` §11.3 — *"No final naming syntax is created here"*; the Naming Standard **does not yet exist** |
| 77 | **An ISO 19650 filename pattern presented as this project's standard** | `S1` §11.3 — **no ISO 19650 filename pattern is imposed** |
| 78 | **Claiming the project rejects, is exempt from, or has failed ISO 19650 naming** | The BEP is **silent by design**, not opposed. Both directions are conformity claims, and neither is supported |
| 79 | **Any invented revision code or convention** | `S1` §6.8 — a revision applies *"where project convention requires one"*, and **no convention exists** |
| 80 | **Any invented status or suitability code set** | `S1` §6.8; `S2` §19 — **no code set is established** |
| 81 | **Any invented metadata schema or field list** | `S1` §11.4 — **no schema established** |
| 82 | **Any classification system presented as adopted** | `S1` §11.4 — *"No classification system is adopted"*; Uniclass, OmniClass, MasterFormat **unadopted** |
| 83 | **Software-native fields presented as the project metadata standard** | `S1` §11.4 — *"Software-native metadata is not the project standard"* |
| 84 | **An unlabelled conceptual placeholder presented as a real identifier** | A placeholder is permitted **only** if visibly labelled illustrative; unlabelled, it is an invented standard |
| 85 | **Omission of the four `not established` fields** | An omitted field implies **no decision is needed**. All four appear, and all four are **empty** |
| 86 | **Describing the four unestablished standards as *in progress*, or giving them a date** | **No source records work in progress or a date.** An unmade decision is not a work item |
| 87 | **A correct name or folder location presented as proof of state, authorisation or process** | `S1` §11.3 — *"platform folder placement alone is not identification"*; **`CGD-C01`, `CGD-C03`** |

**Governance direction and configuration — 6**

| # | Prohibited | Why |
|---|---|---|
| 88 | **Metadata or a code presented as creating authority** | `S1` §11.4, §6.9 — metadata supports governance; it does not create it |
| 89 | **Configuration presented as creating, confirming or constituting governance** | `S1` §5.9 — *"CDE Administration implements governance; it does not create it"* |
| 90 | **Naming any CDE Administration holder** | `S1` §5.9 — **Holder: TBD**. Extends prohibition 30 to this role specifically |
| 91 | **Presenting *deviation* as the mild category and *non-conformance* as the severe one** | `S1` §12.6 — *"The difference is intent and authorisation, not severity"* |
| 92 | **Claiming Harrismith's configuration has been verified as aligned with its governance** | `S2` §6 — a **four-layer** question; `S4` §8 — *"no complete cycle demonstrated"* |
| 93 | **Presenting this module, or the BEP, as authorising a live platform change** | `S1` §12.8 — *"This BEP does not itself authorise any live platform change"*; root `README.md` §2.1 |

**Triviron — 6**

| # | Prohibited | Why |
|---|---|---|
| 94 | **Stating any Triviron project fact** | **No controlled source describes Triviron** — no jurisdiction, project type, client, asset, procurement route, appointment, named role, platform, folder structure, state, code, schema, date or team |
| 95 | **Answering, or hinting at an answer to, either compulsory authority question** | Both are **UNRESOLVED** on Harrismith (`S1` §9.7, §9.8), and a hint from the front of a room assigns them |
| 96 | **Recommending a naming convention, code set, schema, platform or folder structure for Triviron** | A recommendation is an answer wearing a qualifier, and it invents the project |
| 97 | **Presenting `CDE configuration basis — not yet established` as a failure, or attaching a date or an owner to it** | It is a **neutral future position** — the correct status before the decisions are made |
| 98 | **Transferring a Harrismith status onto Triviron** | Harrismith's blocked `T4` is the **reason a question is asked**, not a prediction about a project nobody has described |
| 99 | **Offering Harrismith's CDE model to another project as a template, a starting point or a thing to copy** | The structure is **`CONDITIONALLY ADOPTED`** on a project with **two unresolved authorities** (`S1` §9.7, §9.8) and **one blocked route** (`S2` §3.1). Copied, it transfers both **without the record that explains them**. **The five question groups are what transfers** — not the answers |

**Prohibitions 85 and 86 extend the empty-field rule to its third and fourth
applications.** After 44 (publication authority) and 49 (retention method), the
same instruction now covers the four unestablished standards: **the field
appears, it is empty, and it is not dated.** Omission reads as *not needed*; a
date reads as *already in hand*. **Neither is true.**

**Prohibitions 94–99 are the module's hardest boundary**, because every one of
them would be broken by trying to be helpful. **95 is the single worst**: it
answers the two questions the module exists to leave open, and it does so in
front of the people most likely to act on it.

## 10. Module-boundary deferrals

| Deferred to | Subject |
|---|---|
| **Module 5** | Responsibility-matrix construction; matrix-cell grammar; information-delivery-schedule construction; appointment-level delivery planning |
| **Module 6** | Coordination cycles; clash triage; issue escalation; technical review; assurance sampling; design approval |
| **No module** | **Any coding standard** — none exists |

**References to those controls may explain a transition gate. Detailed teaching
remains deferred.**

## 11. Module-wide final reconciliation

**Module 4's content baseline is complete. This section checks it against
itself.**

### 11.1 Coverage

| Check | Result |
|---|---|
| Slides developed | **14 of 14** |
| Timing | **20.0 minutes**, verified against both the section table and the slide table in [`presentation-outline.md`](presentation-outline.md) §1–§2 |
| Speaker notes | **14 of 14 slides**, 12–13 elements each, plus a **module closing (30 s), a closing fallback (10 s) and Section D and E recovery sentences** |
| Statements classified | **244**, `M4-S1-01` – `M4-S14-16`, no gaps |
| Visuals specified in full | **11 of 14** — `W4`–`W14`. `W1`–`W3` remain candidates |
| Exercises | **71**, in four sets |
| Registers | **7** |
| Prohibited claims | **99**, contiguous, no duplicates |

### 11.2 The four state-model claims, reconciled across all fourteen slides

| Claim | Where made | Where it must not be contradicted |
|---|---|---|
| **A CDE is a process, not a folder tree** | Slide 1 | Slides 3, 7, 8, 12 — each of which discusses folders. **None asserts a folder is a state** |
| **Only `T1` and `T4` are information-state transitions** | Slide 9 | Slides 8, 10, 11. **`T8` is named as a rework route, never as a third transition** |
| **`T4` and `TRN-E03` are different objects** | Slide 11 | Slides 9, 14. **They appear separately in §7.2, and never in one shape** |
| **The concepts are governed; the codes are not** | Slide 12 | Slides 2, 3, 5, 6. **Slide 2 defines the properties and states no code set; Slide 12 says why** |

### 11.3 The six mandatory empty or refused elements

| Element | Slide | Rule |
|---|---|---|
| **Publication-authorising function** | **6, 11** | Shown, **empty**. Prohibition 44 |
| **Retention method** | **7** | Shown, **empty**. Prohibition 49 |
| **`T4` initiating function and evidence-required** | §7.1 | Shown, **empty**. Prohibition 62 protects the sibling evidence field on `T1` |
| **The four `not established` standards** | **12** | Shown, **empty**, **undated**. Prohibitions 85, 86 |
| **The refused reverse arrow** | **13** | Shown, **refused** — not omitted. `W13` |
| **The two authority questions** | **14** | Asked, **unanswered**. Prohibition 95 |

**Six elements, one rule.** Where something is required but unassigned, blocked
or undecided, **it appears and stays incomplete**. Omission reads as *not
needed*; completion invents a decision. **A producer or presenter who "fixes" any
of the six has changed the claim.**

### 11.4 Status distribution across the module

| Status class | Count | Principal examples |
|---|---:|---|
| **`CONTROLLED GOVERNANCE`** | Most of Sections A, B and D | The four state definitions; the six property definitions; the CDE Administration boundary |
| **`PROPOSED GOVERNANCE`** | Most of Section C | The eight controlled steps; the transition control tables |
| **`CONDITIONALLY AVAILABLE`** | The four adopted CDE areas | `CGD-001` §2, with **eight conditions** |
| **`BLOCKED`** | **2 objects** | `T4`; `TRN-E03` |
| **`UNRESOLVED`** | **17 matters** | §8.1–§8.4 |
| **`IMPLEMENTATION UNVERIFIED`** | **Nearly everything** | `S4` — *"no complete cycle demonstrated"* |
| **`LIVE IMPLEMENTATION VERIFIED`** | **Nothing in this module** | — |
| **Undescribed** | **1** | **Triviron** — §8.5 |

**The bottom two rows are the module's honest summary.** **Not one control in
Module 4 is verified as operating**, and the project the module is preparing for
**is not described by any source at all**.

### 11.5 What is not claimed anywhere in Module 4

- **No ISO 19650 conformity claim**, in either direction — Module 3's boundary
  holds unchanged.
- **No live implementation claim.** `ARC-01` is one qualified **container**
  observation, and it proves no cycle.
- **No invented code, syntax, schema, classification, folder, retention period,
  authority holder or Triviron fact.** **Zero, across all seven files.**
- **No authorisation of any platform act.** Root [`README.md`](../../README.md)
  §2.1 applies unmodified, and `S1` §12.8 says the BEP itself authorises none
  either.
- **No measured timing.** Every figure is an allocation until Exercise 64 has
  been run.

### 11.6 Known residual work

| Item | Status |
|---|---|
| `W1`, `W2`, `W3` | **Candidates only** — specification belongs to the visual source set increment |
| `teaching/assets/module-04/` | **Does not exist.** No visual source file and no rendered asset |
| Module 4 assembly package | **Not started** |
| Timing measurement | **Never performed**, for this or any module |

---

## 12. Status

| Field | Value |
|---|---|
| Statements classified | **Slides 1–14 — 244 statements** |
| `CONTROLLED` | 94 |
| `SUPPORTING` | 52 |
| `DECISION-RECORD` | 30 |
| `MODULE-1-3` | 1 |
| `INTERP` | 34 |
| `SYNTH` | 13 |
| `EXCLUDED` | 20 |
| Registers | **7** — source authority (§4), state (§5.1), **property (§5.2)**, **configuration-decision (§5.3)**, terminology (§6), transition (§7), **module-wide unresolved (§8)** |
| Prohibited claims | **99** (§9, §9.1–§9.4) |
| Content baseline | **Complete.** Slides 1–14 developed |
| Invented codes, schemas, folders, periods, holders or Triviron facts | **Zero** |
| Mandatory empty or refused elements | **6** — §11.3 |
| Transition register | **Expanded (T4-C)** — seventeen fields, `T1`–`T8`, §7.1 |
| Module-wide final reconciliation | **§11 (T4-D)** |
| Live observations requested | **Zero** |
