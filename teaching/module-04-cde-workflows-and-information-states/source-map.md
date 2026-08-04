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

## 5. Statement classification — Slides 1–3

**44 statements. 19 `CONTROLLED`, 7 `SUPPORTING`, 8 `DECISION-RECORD`,
1 `MODULE-1-3`, 4 `INTERP`, 3 `SYNTH`, 2 `EXCLUDED`.**

| Slide | Statements | `CTRL` | `SUPP` | `DEC` | `M1-3` | `INT` | `SYN` | `EXC` |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| 1 | 12 | 3 | 2 | 3 | 1 | 1 | 1 | 1 |
| 2 | 14 | 7 | 2 | 1 | 0 | 2 | 1 | 1 |
| 3 | 18 | 9 | 3 | 4 | 0 | 1 | 1 | 0 |
| **Total** | **44** | **19** | **7** | **8** | **1** | **4** | **3** | **2** |

**Two observations.** **Slide 3 is the most source-dense in the increment** —
eighteen statements, sixteen of them from controlled documents. And **every
Slide 2 property definition is `CONTROLLED`** while **every code set is
`UNRESOLVED`**: the vocabulary is governed, the coding is not.

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
| Statements classified | **Slides 1–3 — 44 statements** |
| `CONTROLLED` | 19 |
| `SUPPORTING` | 7 |
| `DECISION-RECORD` | 8 |
| `MODULE-1-3` | 1 |
| `INTERP` | 4 |
| `SYNTH` | 3 |
| `EXCLUDED` | 2 |
| Registers | **4** — source authority (§4), terminology (§6), transition (§7), unresolved (§8) |
| Prohibited claims | **33** (§9, §9.1) |
| Slides 4–14 | **Not classified.** Not developed |
| Invented codes, schemas or holders | **Zero** |
| Live observations requested | **Zero** |
