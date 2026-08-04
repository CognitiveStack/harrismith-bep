# Module 4 — Source Inventory

**Status:** Discovery record for teaching material. **Not governance.**

Every controlled Harrismith source relevant to CDE workflow and information
states, discovered by inspection and recorded with its **exact repository
path**. No path or title is assumed.

---

## 1. Source precedence

Applied throughout Module 4. **A teaching statement never silently overrides a
controlled project source.**

| Level | Source class | Example |
|---|---|---|
| **1** | Approved Harrismith governance documents | [`bep/Harrismith-Fire-Station-BEP.md`](../../bep/Harrismith-Fire-Station-BEP.md) |
| **2** | Approved supporting schedules, matrices and strategies | [`supporting/cde-workflow-state-strategy.md`](../../supporting/cde-workflow-state-strategy.md) |
| **3** | Controlled decision or validation records | [`docs/CDE-Structure-Governance-Decision.md`](../../docs/CDE-Structure-Governance-Decision.md) |
| **4** | Completed teaching-source interpretation from Modules 1–3 | [`../module-03-iso-19650-principles/source-map.md`](../module-03-iso-19650-principles/source-map.md) |
| **5** | Teaching synthesis | Presenter framing, labelled |

**Where controlled documents differ:** the difference is **recorded**; if one
source explicitly governs, that is stated; otherwise the matter is marked
**unresolved**. **No difference is harmonised by invention** — see §6.

## 2. Primary sources — exact paths

| # | Path | Declared status | Holds |
|---|---|---|---|
| **S1** | [`bep/Harrismith-Fire-Station-BEP.md`](../../bep/Harrismith-Fire-Station-BEP.md) | APPROVED WITH CONDITIONS — Training Baseline 0.1 | **Governing CDE principles** — §6 CDE Strategy, §7 Information Production and Sharing, §10 Delivery and Exchange, §11 Standards, §12 Governance and Change |
| **S2** | [`supporting/cde-workflow-state-strategy.md`](../../supporting/cde-workflow-state-strategy.md) | APPROVED WITH CONDITIONS — Training Baseline 0.1. **Classified PROPOSED GOVERNANCE** | **The transition logic.** States, transitions `T1`–`T8`, gates, evidence, access model, exceptions, platform rules, unresolved register |
| **S3** | [`docs/CDE-Structure-Governance-Decision.md`](../../docs/CDE-Structure-Governance-Decision.md) | **CGD-001 — APPROVE WITH CONDITIONS.** Eight active conditions | **The folder decision.** Four adopted root areas, their intended state mapping, and conditions `CGD-C01`–`CGD-C08` |
| **S4** | [`docs/Increment-7C-Live-Validation-Record.md`](../../docs/Increment-7C-Live-Validation-Record.md) | Controlled validation record | **Implementation evidence** — container and workflow demonstrability, coordination-cycle evidence, **authority evidence**, remaining gaps |
| **S5** | [`supporting/information-delivery-schedule.md`](../../supporting/information-delivery-schedule.md) | APPROVED WITH CONDITIONS — Training Baseline 0.1 | **Delivery events** `TRN-E01`, `TRN-E02`, `TRN-E03`; blocking matters; four distinct states |
| **S6** | [`supporting/information-management-responsibility-matrix.md`](../../supporting/information-management-responsibility-matrix.md) | APPROVED WITH CONDITIONS — Training Baseline 0.1 | **Who performs each transition and process function.** `D4`, `D7`, `A2` allocations |
| **S7** | [`supporting/model-information-responsibility-matrix.md`](../../supporting/model-information-responsibility-matrix.md) | APPROVED WITH CONDITIONS — Training Baseline 0.1 | **Which task team originates each container.** Container classes, formats, intended CDE states |
| **S8** | [`supporting/coordination-review-strategy.md`](../../supporting/coordination-review-strategy.md) | APPROVED WITH CONDITIONS — Training Baseline 0.1 | The coordination process **after** Shared information becomes coordination input — **Module 6 territory** |
| **S9** | [`supporting/governance-decision-register.md`](../../supporting/governance-decision-register.md) | APPROVED WITH CONDITIONS — Training Baseline 0.1 | Decisions, deviations and changes affecting the workflow |
| **S10** | [`guidance/BIM-Delivery-Guide.md`](../../guidance/BIM-Delivery-Guide.md) | Explanatory guidance — **no authority** | Explains; governs nothing |

### 2.1 Secondary and boundary sources

| # | Path | Relevance |
|---|---|---|
| **S11** | [`docs/Increment-8D-Publication-Planning-Read-Only-Observation-Record.md`](../../docs/Increment-8D-Publication-Planning-Read-Only-Observation-Record.md) | Observed conditions referenced by `CGD-C02` |
| **S12** | [`standards/naming/`](../../standards/naming/) | **Empty — contains only `.gitkeep`.** **No naming standard exists** |
| **S13** | [`standards/coordinates/`](../../standards/coordinates/) · [`standards/templates/`](../../standards/templates/) · [`standards/titleblocks/`](../../standards/titleblocks/) | **All empty.** No standard established in any |
| **S14** | [`../module-03-iso-19650-principles/source-map.md`](../module-03-iso-19650-principles/source-map.md) §9.9 | Module 3's **recorded deferrals to Module 4** |

**Finding — `S12`/`S13`.** All four `standards/` subdirectories contain **only
`.gitkeep`**. **No naming standard, coordinates standard, template set or
titleblock standard exists.** `S2` §19 confirms: *Naming standard — **Not
established***. **Module 4 must not teach a coding standard, because none
exists.**

## 3. Source-authority register — which source governs which concept

| Concept | Governing source | Supporting | Note |
|---|---|---|---|
| **CDE principles** | **`S1` §6.1** | `S2` purpose statement | *"The CDE is a process, not a folder tree"* appears in both |
| **Information states** | **`S1` §6.3** | `S2` §1 | `S1` is the governing definition; `S2` elaborates. **Wording differs — see §6** |
| **States are not folders** | **`S1` §6.3** | `S2` §1; **`S3` `CGD-C01`** | Three independent statements |
| **Folder topology** | **`S3` §2** | `S1` §6.11 | **`S3` is the only source that adopts a topology** |
| **Folder-to-state mapping** | **`S3` §3** | — | `S3` §3.1–§3.5 |
| **State transitions** | **`S2` §3** | `S1` §6.5, §7 | **`S2` holds the transition logic** — `S2` §18 says so explicitly |
| **Transition authority** | **`S6`** | `S2` §3.2; `S1` §9.4, §9.7, §9.8 | Allocation lives in the IM matrix |
| **Transition evidence** | **`S2` §3.3, §16** | `S1` §9.11 | — |
| **Delivery events** | **`S5`** | `S2` §9–§11 | `S2` **maps** the events; `S5` **defines** them |
| **Version / revision / state / status / suitability** | **`S1` §6.8** | `S2` §13 | **Wording differs — see §6** |
| **Access and permissions** | **`S1` §6.9** | `S2` §14; `S3` `CGD-C08` | *Permission ≠ authority* |
| **Retention / Record** | **`S1` §6.3** | `S2` §1; **`S3` §3.5, `CGD-C06`** | **TBD in all three** |
| **Naming** | **`S1` §11.3** | `S2` §19; `S3` `CGD-C05`; `S12` | **Not established** |
| **Platform implementation rules** | **`S2` §17** | `S1` §12.1, §12.9 | Decision precedes configuration |
| **Implementation verification** | **`S4`** | `S1` §12.9; `S2` §6; `S3` `CGD-C07` | — |
| **Governance change** | **`S1` §12** | `S6` `A1`–`A5`; `S9` | `A2` **TBD** |
| **Coordination process** | **`S8`** | — | **Module 6 — deferred** |
| **Matrix and schedule construction** | `S5`, `S6`, `S7` | — | **Module 5 — deferred** |

## 4. Governance and implementation status of the CDE material

**The single most important finding in this inventory.**

> **`S2` classification:** *"The workflow defined here is **PROPOSED
> GOVERNANCE** for the training implementation."*
>
> *"**This strategy does not describe the live platform.** It defines proposed
> governed CDE behaviour. It is **not** evidence that the current Autodesk
> configuration matches it."*

`S2` §6 gives the four-layer model that Module 4 must preserve:

| Layer | Is |
|---|---|
| **AS-FOUND** | Observed evidence of current behaviour |
| **INTENDED GOVERNANCE** | The approved target configuration |
| **IMPLEMENTED CONFIGURATION** | The platform result after an authorised change |
| **VERIFIED CONFIGURATION** | The implemented state checked against intended governance |

> *"**Observed state does not prove correctness. Intended state does not prove
> implementation. Implementation does not prove success until verified.**"*
> — `S2` §6

**And `CGD-C07`:** *"CGD-001 authorises no folder creation, renaming, movement,
deletion, permission change or other Autodesk configuration act… **A later
controlled verification must confirm the live topology before the mapping is
relied on operationally.**"*

## 5. Terminology register — exact controlled wording

**Verified by inspection. Not standardised.**

| Term | Exact wording found | Source | Note |
|---|---|---|---|
| **CDE** | *"an information-management process supported by technology"*; *"It is not a folder tree"* | `S1` §6.1 | Also `S2` purpose: *"The CDE is a process, not a folder tree"* |
| **Information container** | Used throughout; the unit responsibility attaches to | `S1` §1.1, §7.2 | **No formal definition clause** |
| **WIP** | *"Information under originator / task-team control. Not authorised for general project reliance."* | `S1` §6.3; `S2` §1 | **Identical in both** |
| **Shared** | `S1`: *"made available beyond the originating task team for an identified purpose, after required checking and authorisation"* · `S2`: *"deliberately made available… after required check and authorisation"* | `S1` §6.3; `S2` §1 | **Near-identical; `S2` adds "deliberately"** |
| **Published / Authorised** | `S1`: *"authorised for a defined delivery or use purpose"* · `S2`: *"authorised for an identified formal or project-facing delivery or use purpose"* | `S1` §6.3; `S2` §1 | **`S2` is more specific** |
| **Record / Retained** | See §6 — **four label forms across the sources** | `S1` §6.3; `S2` §1; `S3` §3.5 | **Variance recorded, not harmonised** |
| **Version** | *"A platform or file history instance"* | `S1` §6.8; `S2` §13 | **Identical** |
| **Revision** | *"A controlled issue identifier, where project convention requires one"* | `S1` §6.8; `S2` §13 | **Identical.** Note the conditional — *where convention requires one* |
| **Status** | *"A workflow or decision condition"* | `S1` §6.8; `S2` §13 | **Identical** |
| **Suitability** | `S1`: *"What the information may be used for"* · `S2`: *"The permitted intended use"* | `S1` §6.8; `S2` §13 | **Different wording, same concept** |
| **Metadata** | Discussed at `S1` §11.4 as supporting identity, filtering and search | `S1` §11.4 | **No metadata schema established** |
| **Delivery** | *"an exchange **event**"* | `S2` §3 | **Not an information state** |
| **Receipt** | *"a recipient **event**"* | `S2` §3 | **Not an information state** |
| **Acceptance** | *"a recipient **decision and status** for a stated purpose"* | `S2` §3 | **Not an information state** |
| **Consume** | *"A receiving-team action — adoption into that team's working context"* | `S2` §3 | **Not an information state** |
| **Coordination input** | *"An approved **use and context** of Shared information"* | `S2` §3 | **Not an information state** |

## 6. Terminology variance — recorded, not harmonised

**Four label forms exist for the fourth state across controlled sources.** No
source declares them as formal synonyms.

| Form | Occurrences | Where |
|---|---|---|
| **`Record / Retained`** | **10** | `S2` (3), `S3` (3), `S9` (4) |
| **`Record / retained`** | 1 | **`S1` §6.3 — the governing definition table** |
| **`Published / Record`** | 1 | `S1` §6.8 — the state short-form in the five-property table |
| **`Published / retained`** | 1 | `S2` §13 — the same short-form, differently cased |

**Assessment.**

| Question | Answer |
|---|---|
| Does one source explicitly govern? | **`S1` §6.3 is the governing state definition** — `S1` is the level-1 document and §6.3 is titled *Information States* |
| Are synonyms formally declared? | **No.** No source states that these forms are equivalent |
| Is the variance material? | **No — it is casing and short-form abbreviation**, not a difference of meaning. All four refer to the same conceptual state |
| Resolution | **Record the variance. Teach the majority form `Record / Retained`, and state that the governing definition at `S1` §6.3 uses `Record / retained`.** Do not present either as *the* correct label |

**A second, smaller variance.** The state short-form in the five-property table
differs between the two sources — `S1` §6.8 gives *WIP / Shared / Published /
Record*; `S2` §13 gives *WIP / Shared / Published / retained*. **Same four
states, two abbreviations.** Recorded.

**Neither variance is a defect to raise through the Working Process.** They are
casing and abbreviation differences within a consistent concept, and the
teaching position is to show the full form and note that the sources abbreviate
it differently.

## 7. Folder topology — exact adopted labels

**`S3` §2 adopts four root areas. These are the exact labels**, including
punctuation:

| # | Adopted root area | Intended mapping — `S3` §3 |
|---|---|---|
| 1 | **`0. Common Files`** | **An area, not a state.** *"Nothing becomes approved, controlled or relied upon by being placed in it"* |
| 2 | **`01. WIP (Work in Progress)`** | Corresponds to the **WIP** information state |
| 3 | **`02. Shared`** | Corresponds to the **Shared** information state. *"Placement alone does not evidence that checking or authorisation occurred"* |
| 4 | **`03. Published`** | Corresponds to **Published / Authorised**. *"Putting a file in `03. Published` does not publish it"* |
| — | **Record / Retained** | **No root folder.** *"It need not be represented by a literal root folder"*; *"no mandatory `04 Archive` root is approved or required by CGD-001"* |

**What `S3` does not adopt:** every child folder, every observed discipline
mapping, every existing filename, every spelling or capitalisation, every
existing item or version, every current operational practice.

## 8. Transition register — verified from `S2` §3

**Eight controlled steps. Only two are information-state transitions.**

`S2` §3 states it directly: *"Of the eight steps below, only **T1** and **T4**
are information-state transitions. T8 returns information to the originator's
WIP for rework."*

| Ref | Kind | From → To | Purpose | Authorising function | Gate | Evidence | Status |
|---|---|---|---|---|---|---|---|
| **`T1`** | **State transition** | WIP → **Shared** | Make available beyond the originating task team for a stated purpose | **Task-Team Lead** (or explicitly allocated function) — **established** | Task-team technical/content check **and** information-quality/readiness check | Version history; checking record; share/exchange record | **`CONTROLLED GOVERNANCE`** — authority established (`S1` §9.4) |
| **`T2`** | **Action** — not a state transition | Shared → Shared *(unchanged)* | Receiver adopts or references for a stated working purpose | Receiving task team | Receiver review of suitability for that purpose | Consume state or history; receiver's record | `PROPOSED GOVERNANCE` |
| **`T3`** | **Use / context** — not a state transition | Shared → Shared *(unchanged)* | Include in a defined coordination cycle | **BIM Coordinator** (process function) | Input readiness appropriate to the coordination purpose | Coordination input record; federation record | `PROPOSED GOVERNANCE` |
| **`T4`** | **State transition** | Shared → **Published / Authorised** | Authorise for an identified delivery or use purpose | **UNRESOLVED — TBD** (`S1` §9.7) | Delivery readiness review | Delivery review record; publication authorisation record | **`BLOCKED`** — *"no authorisation can be given while the authority is unresolved. Information remains Shared"* |
| **`T5`** | **Event** | Published → Published *(unchanged)* | Controlled delivery / exchange executed | Originating task team; CDE Administration may execute platform functions | Transmission prepared per the delivery requirement | Transmission record — what, when, by which role, to whom, for what purpose | `PROPOSED GOVERNANCE` — **downstream of `T4`** |
| **`T6`** | **Event** | Published → Published *(unchanged)* | Recipient receives the exchange | Receiving / recipient function | Registration of receipt | Receipt record | `PROPOSED GOVERNANCE` — **downstream of `T4`** |
| **`T7`** | **Decision / status** | Published → Published *(unchanged)* | Recipient accepts or rejects for the stated purpose | **UNRESOLVED — TBD / recipient-function dependent** (`S1` §9.8, §10.11) | Assessment against the applicable requirement | Acceptance or rejection record, with the stated purpose | **`UNRESOLVED`** |
| **`T8`** | **Rework** | Shared or Published → **WIP**, then reprogression | Correction, re-check, reauthorise | **Originating** task team; **Task-Team Lead** authorises | Task-team check of the revised information | Issue history; revised version history; re-check and re-authorisation records; superseded marking | `PROPOSED GOVERNANCE` |

### 8.1 `T4` and `TRN-E03` are not interchangeable

**Verified. They are different kinds of object.**

| | `T4` | `TRN-E03` |
|---|---|---|
| **What it is** | A **state transition** — Shared → Published / Authorised | A **delivery event** — controlled design review / project-facing exchange |
| **Defined in** | **`S2` §3** | **`S5` §5** |
| **Relationship** | `TRN-E03` **exercises** `T4` — `S2` §11 maps the event onto the transition | |
| **Status** | **Blocked** — no available authorising function | **PROPOSED — BLOCKED PENDING GOVERNANCE DECISIONS** |
| **Blocking matters** | Publication / exchange authority **UNRESOLVED** | Publication authority · recipient acceptance authority · recipient identity · required formats · deliverable set — **five, per `S5` §5.1** |

**`TRN-E03` is blocked by more than `T4` is.** Even if publication authority
were resolved, `TRN-E03` would remain blocked on recipient identity, formats and
deliverable set.

### 8.2 Delivery events — `S5`

| Event | Purpose | Status |
|---|---|---|
| **`TRN-E01`** | Design coordination share | Scheduled. **Only Architecture currently demonstrable as a Shared input** (`S4` §7) |
| **`TRN-E02`** | Coordination reshare / resolution update | Conditional template rows. **No controlled reshare cycle demonstrated** (`S4` §7) |
| **`TRN-E03`** | Controlled design review / project-facing exchange | **PROPOSED — BLOCKED** |

## 9. Implementation-status register — from `S4`

**Controlled live-validation evidence. Read-only observation, already
performed and recorded. Module 4 requests none.**

| Matter | Live status | Classification |
|---|---|---|
| Four-area root topology | Observed; corresponds to the approved intended topology | `IMPLEMENTATION UNVERIFIED` — *"a later controlled verification must confirm the live topology"* (`CGD-C07`) |
| `ARC-01` container | **Live equivalent observed** | `LIVE IMPLEMENTATION VERIFIED` *(observation only)* |
| `STR-01`, `MEC-01`, `ELE-01`, `PLM-01`, `FIR-01` | *"Not observed as a live direct coordination input at the inspected level"* | `IMPLEMENTATION UNVERIFIED` |
| `COORD-01` | **Partially demonstrable** — environment exists, no federated or coordinated version | `IMPLEMENTATION UNVERIFIED` |
| `TRN-E01` | Only Architecture demonstrable as a Shared input | `IMPLEMENTATION UNVERIFIED` |
| `TRN-E02` | No controlled reshare cycle demonstrated | `IMPLEMENTATION UNVERIFIED` |
| `TRN-E03` | **Remains PROPOSED and BLOCKED** | **`BLOCKED`** |
| Complete coordination cycle | **PARTIALLY TRACEABLE / NOT YET DEMONSTRATED AS A COMPLETE CYCLE** | `IMPLEMENTATION UNVERIFIED` |
| **Publication / exchange authority** | *"**No governed publication / exchange authority evidence was established**"* | **`UNRESOLVED`** |
| **Recipient acceptance authority** | *"**No governed recipient acceptance authority evidence was established**"* | **`UNRESOLVED`** |

**`S4` §9, quotable and load-bearing:**

> *"Platform permissions, sender identity, review participation and the ability
> to create a Transmittal are **not** governance authority. **Being able to
> perform an action in the software says nothing about who was authorised to
> decide it.**"*

**`S4` §11, on the remaining gap:**

> **platform role ≠ professional appointment ≠ governance authority.**

**And the standing caution, `S4` §7:** *"Absence of observation is not
observation of absence."* **A missing verification is not a failure claim.**

## 10. Unresolved-matter register — from `S2` §19 and `S4`

| # | Matter | Reference | Status |
|---|---|---|---|
| 1 | **Publication / exchange authority** (`TRN-E03`, `T4`) | `S1` §9.7; `S6` `D4` | **UNRESOLVED / TBD** |
| 2 | **Recipient acceptance authority** | `S1` §9.8, §10.11; `S6` `D7` | **UNRESOLVED / TBD** |
| 3 | **Recipient identity** | `S1` §2.3, §5.3 | **Not established** |
| 4 | **Retention / record approach** | `S1` §6.3; `CGD-C06` | **TBD** — no `04 Archive` root requirement approved |
| 5 | **`04 Archive` root** | `S1` §6.3; `S2` §1; `CGD-C06` | **Not approved, not required, not created** |
| 6 | **Naming standard** | `S1` §11.3; `S12` | **Not established** |
| 7 | **Coordinates standard** | `S1` §11.5; OF-003 | **Not approved** |
| 8 | **Metadata implementation** | `S1` §11.4 | **No schema established** |
| 9 | **Suitability code set** | `S1` §6.8 | **No code set established** |
| 10 | **MEP / Structural team-space mapping** | **UD-001** | **UNRESOLVED** — observed discrepancy; intended state not decided |
| 11 | **Design Collaboration Coordination Space** | OF-005 | **Not observed configured** |
| 12 | **Contractors Design Collaboration team** | OF-004; `S1` §4.5 | **Not established in discovery evidence** |
| 13 | **Platform-team to task-team mapping** | `S1` §4.5 | **Open question** |
| 14 | **Governance change approval authority by class** | `S1` §12.7; `S6` `A2` | **UNRESOLVED / TBD** |
| 15 | **Live transition operation** | `S4` | **Not demonstrated as a complete cycle** |

**`S2` §19 closes with the position Module 4 adopts:**

> *"None of these is resolved by this strategy. Each is recorded so the gap
> stays visible rather than being filled with a plausible value."*

## 11. What this inventory does not do

- It does **not** resolve any unresolved matter.
- It does **not** authorise any Autodesk read, write or configuration act. The
  safety boundary in root [`README.md`](../../README.md) §2.1 applies unmodified.
- It does **not** request a live observation. `S4` is an **existing controlled
  record**, read as evidence.
- It does **not** approve, publish or issue any source by referencing it
  (`S1` §13.6).
- It carries **no governance authority.**
