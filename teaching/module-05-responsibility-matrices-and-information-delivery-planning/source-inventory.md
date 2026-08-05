# Module 5 — Source Inventory

**Status:** Discovery record for teaching material. **Not governance.**

Every Harrismith source relevant to responsibility allocation and
information-delivery planning, discovered by inspection and recorded with its
**exact repository path** and **its own declared status**. No path, title or
status is assumed from a filename.

Produced in increment **T5-A**.

---

## 1. Source precedence

Applied throughout Module 5. **A teaching statement never silently overrides a
controlled project source.**

| Level | Source class | Example |
|---|---|---|
| **1** | Approved Harrismith governance | [`bep/Harrismith-Fire-Station-BEP.md`](../../bep/Harrismith-Fire-Station-BEP.md) |
| **2** | Approved supporting matrices, schedules and strategies | [`supporting/information-management-responsibility-matrix.md`](../../supporting/information-management-responsibility-matrix.md) |
| **3** | Controlled decision, approval and validation records | [`docs/Training-Baseline-0.1-Approval-Decision.md`](../../docs/Training-Baseline-0.1-Approval-Decision.md) |
| **4** | Completed teaching interpretation from Modules 1–4 | [`../module-04-cde-workflows-and-information-states/source-map.md`](../module-04-cde-workflows-and-information-states/source-map.md) |
| **5** | Teaching synthesis | Presenter framing, labelled `SYNTH` |

### 1.1 The precedence is established by the sources, not by this module

**`S1` §1.5 sets the tiering itself.** Where documents conflict, the higher tier
prevails: appointment and appointing-party requirements *(not available)* →
legislation and adopted standards → project information requirements *(not
available)* → **approved BEP** → **supporting controlled resources** →
operational procedures and platform configuration.

Two consequences are recorded verbatim rather than paraphrased:

- *"The absence of a higher tier does **not** promote this BEP to the top of the
  hierarchy."* Tiers 1 and 3 are unavailable in this implementation and remain
  recorded as gaps (`S1` §1.5).
- *"Platform configuration is the lowest tier, not evidence of authority…
  **Authority is never inferred upward from platform configuration**"*
  (`S1` §1.5).

**Level 1 above level 2 is therefore a source-established precedence**, not a
teaching convenience. `S1` §5.12, §7.12 and §10.13 each state the same division
of labour: **the BEP defines what a function means; the supporting resource
records how it is allocated or scheduled.** Meaning is defined once; allocation
is recorded once.

### 1.2 Reference is not approval

`S1` §5.12, §7.12 and §10.13 each state that the referenced supporting resource
is **separately controlled**, **declares its own status, version and authority**,
and that *"reference from this BEP does not constitute approval of it"*
(`S1` §13.6). `S2` §7 states the same in the opposite direction.

**Module 5 must not treat citation as endorsement**, in either direction.

### 1.3 Where controlled sources differ

The difference is **recorded** — see [`source-map.md`](source-map.md) §6. If one
source expressly governs, that is stated. Otherwise the matter is marked
**unresolved**. **No difference is harmonised by invention, and no terminology
is tidied for presentation.**

### 1.4 Governance definition and implementation evidence are separate

Every Module 5 statement about a matrix or schedule row carries **two**
statuses — what the governance says, and whether it has been evidenced in use.
`S9` is the only source in this inventory that records live observation, it
declares **`Authority: None`**, and it states that it *"resolves no decision,
assigns no authority, and approves nothing."*

---

## 2. Primary sources — exact paths and declared status

| # | Path | Declared status | Holds for Module 5 |
|---|---|---|---|
| **S1** | [`bep/Harrismith-Fire-Station-BEP.md`](../../bep/Harrismith-Fire-Station-BEP.md) | **APPROVED WITH CONDITIONS — Training Baseline 0.1**; conditions active | **The governing definitions.** §1.5 precedence; §4 organisation; §5 roles and the **approved responsibility grammar** (§5.12); §7 production and origination; §9 check / authorise / accept; §10 delivery, deliverables and the four receipt states; §12 change authority |
| **S2** | [`supporting/information-management-responsibility-matrix.md`](../../supporting/information-management-responsibility-matrix.md) | **APPROVED WITH CONDITIONS — Training Baseline 0.1**; approved through **AD-001**, 2026-08-01; publication **NOT AUTHORISED** | **Who performs which information-management function.** Seven-term grammar, nine role columns, 33 function rows in seven groups, `D4` / `D7` / `A2` unresolved, role-combination rule, unresolved register |
| **S3** | [`supporting/model-information-responsibility-matrix.md`](../../supporting/model-information-responsibility-matrix.md) | **APPROVED WITH CONDITIONS — Training Baseline 0.1**; approved through **AD-001**, 2026-08-01; publication **NOT AUTHORISED**. Allocations **classified `PROPOSED GOVERNANCE`** per **TA-03** | **Who produces and maintains which information container.** `ARC-01`–`FIR-01`, `COORD-01`, formats, intended CDE states, dependencies, level of information need **not defined**, future trade extension |
| **S4** | [`supporting/information-delivery-schedule.md`](../../supporting/information-delivery-schedule.md) | **APPROVED WITH CONDITIONS — Training Baseline 0.1**; approved through **AD-001**, 2026-08-01; publication **NOT AUTHORISED**. All entries **classified `PROPOSED GOVERNANCE` / training delivery planning** | **What is exchanged, at what event, to whom, why, in what form, under what conditions.** Sixteen approved fields, `TRN-E01` / `TRN-E02` / `TRN-E03`, blocking register, four distinct receipt states, unresolved register |
| **S5** | [`supporting/cde-workflow-state-strategy.md`](../../supporting/cde-workflow-state-strategy.md) | **APPROVED WITH CONDITIONS — Training Baseline 0.1**. Classified **`PROPOSED GOVERNANCE`**; *"does not describe the live platform"* | **The transition logic** `T1`–`T8`, carried forward from Module 4. Needed only to hold the **event ≠ transition** boundary |
| **S6** | [`supporting/coordination-review-strategy.md`](../../supporting/coordination-review-strategy.md) | **APPROVED WITH CONDITIONS — Training Baseline 0.1**. Classified **`PROPOSED GOVERNANCE`** | **Module 6 territory.** Consulted **only** to confirm where Module 5 must stop. No coordination, federation, finding, Issue, triage or closure mechanics are taught here |
| **S7** | [`supporting/governance-decision-register.md`](../../supporting/governance-decision-register.md) | **APPROVED WITH CONDITIONS — Training Baseline 0.1** | **Classification vocabulary**; **TA-02** simulated participation; **TA-03** training delivery organisation; **OF-002** populated streams; **OF-003** empty standards areas; **UD-001** unresolved team-space mapping; **AD-001** conditions |
| **S8** | [`docs/Training-Baseline-0.1-Approval-Decision.md`](../../docs/Training-Baseline-0.1-Approval-Decision.md) | **Controlled Approval Decision — AD-001 — APPROVED WITH CONDITIONS** | **What the approval did and did not do.** Establishes the status all three principal resources carry, and records the **explicit non-effects** — no project publication authority, no acceptance authority, no project standard |
| **S9** | [`docs/Increment-7C-Live-Validation-Record.md`](../../docs/Increment-7C-Live-Validation-Record.md) | **Observation and comparison record. Authority: None** — *"resolves no decision, assigns no authority, and approves nothing"* | **The only implementation evidence in this inventory.** §7 per-container and per-event live status; §8 coordination-cycle evidence; §9 **authority evidence — none established** |
| **S10** | [`docs/CDE-Structure-Governance-Decision.md`](../../docs/CDE-Structure-Governance-Decision.md) | **CGD-001 — APPROVE WITH CONDITIONS**; eight active conditions | Boundary source. Confirms **area ≠ state** and **permission ≠ authority**, carried from Module 4. **Contains no responsibility allocation and no delivery planning** |

### 2.1 Non-governing and boundary sources

| # | Path | Relevance |
|---|---|---|
| **S11** | [`guidance/BIM-Delivery-Guide.md`](../../guidance/BIM-Delivery-Guide.md) | **`Authority: None. This Guide governs nothing.`** Status **FOR REVIEW**, **not approved**. Explains; may **never** be cited as the basis of an allocation. Its own rule: *"If this Guide ever disagrees with a controlled governing resource, the controlled resource wins"* |
| **S12** | [`standards/naming/`](../../standards/naming/) · [`standards/coordinates/`](../../standards/coordinates/) · [`standards/templates/`](../../standards/templates/) · [`standards/titleblocks/`](../../standards/titleblocks/) | **All four contain only `.gitkeep`.** **No naming, coordinates, template or titleblock standard exists.** Confirmed by inspection and by `S3` §6, `S4` §7 and **OF-003** |
| **S13** | [`../module-04-cde-workflows-and-information-states/source-map.md`](../module-04-cde-workflows-and-information-states/source-map.md) · [`source-inventory.md`](../module-04-cde-workflows-and-information-states/source-inventory.md) | Module 4 carry-forward: `T1`/`T4` classification, `T4` blocked, `TRN-E03` ≠ `T4`, four distinct receipt states, governance ≠ implementation. **Teaching interpretation — not governance** |
| **S14** | [`../module-02-roles-and-responsibilities/source-map.md`](../module-02-roles-and-responsibilities/source-map.md) | Module 2 carry-forward: role, function and authority. **Teaching interpretation — not governance** |
| **S15** | [`../roadmap.md`](../roadmap.md) | Programme plan. **Explicitly "Not governance. Carries no authority and decides nothing."** Its pre-declared Module 5 content is treated as **hypothesis** — see [`source-map.md`](source-map.md) §7 |

**Finding — `S12`.** All four `standards/` subdirectories were inspected and
contain **only `.gitkeep`**. Module 5 therefore **cannot teach an identifier,
naming or format convention for any matrix or schedule row**, because none
exists. `S4` §1 says so directly: *"Identifiers are training schedule
identifiers… They are **not** contractual document numbers and carry no project
numbering convention — no Naming Standard exists."*

---

## 3. Why each source was consulted, and what Module 5 may take from it

| # | Consulted because | Module 5 **may** use | Module 5 **may not** use it to establish |
|---|---|---|---|
| **S1** | It defines every term the three resources allocate | Definitions of Perform / Check / Authorise / Coordinate / Accept / Consult / Inform; origination chain; the four receipt states; the schedule field list; precedence | Any allocation — `S1` records none. Any deliverable list — §10.4: *"This BEP does not define the project's final deliverable list"* |
| **S2** | It is the first principal resource | Function-to-role allocation; grammar codes; `TBD` and `—` meanings; role-combination rule | Container production; delivery timing; any role **holder** |
| **S3** | It is the second principal resource | Container-to-party/task-team allocation; interfaces; `COORD-01` construct | Process-function allocation; delivery events; any live inventory claim |
| **S4** | It is the third principal resource | Delivery events, fields, conditions, blocking register | Any real milestone, date, format or deliverable set |
| **S5** | To hold the **event ≠ transition** boundary | `T1` and `T4` are the only state transitions; `T4` blocked | Transition mechanics beyond that boundary — Module 4 owns them |
| **S6** | To locate the **Module 6 boundary** | The fact that a coordination, review and verification function is *required* | Any coordination, federation, finding, Issue, triage, verification or closure mechanic |
| **S7** | For classification vocabulary and the unresolved matters | `OBSERVED FACT` / `TRAINING ASSUMPTION` / `PROPOSED GOVERNANCE` / `APPROVED GOVERNANCE` / `UNRESOLVED DECISION`; TA-02; TA-03; OF-002; OF-003; UD-001 | Any resolution of `UD-001`, `D4`, `D7` or `A2` |
| **S8** | Because it is the approval all three resources cite | The status the three resources carry, and the **explicit non-effects** of that approval | Any claim that approval established publication authority, acceptance authority or a project standard |
| **S9** | Because it is the only live evidence | Per-container and per-event observed status; **no authority evidence established** | Any claim that a container, event or cycle is operating. **Absence of observation is not observation of absence** |
| **S10** | To carry forward area ≠ state, permission ≠ authority | Those two boundaries only | Anything about responsibility allocation — it contains none |
| **S11** | To confirm it is **not** usable as authority | Nothing. Pedagogic phrasing only, always labelled | **Any** allocation, status or authority claim |
| **S12** | To establish whether a standard exists | The recorded fact that **none exists** | Any identifier, naming or format convention |
| **S13**, **S14** | Teaching continuity | Module 2 and Module 4 established positions, cited **as teaching interpretation** | Anything cited as though it were controlled Harrismith governance |
| **S15** | Because it pre-declares Module 5 content | The roadmap's list **as a hypothesis set** | Any fact. It decides nothing and governs nothing |

---

## 4. Materially relevant sources considered and excluded

| # | Path or group | Exclusion reason |
|---|---|---|
| **E1** | [`docs/Publication-Arrangement-Candidate-0.1.md`](../../docs/Publication-Arrangement-Candidate-0.1.md) · [`docs/Publication-Arrangement-Approval-Decision.md`](../../docs/Publication-Arrangement-Approval-Decision.md) · [`docs/Publication-Arrangement-Readiness-Assessment.md`](../../docs/Publication-Arrangement-Readiness-Assessment.md) · [`docs/Publication-Arrangement-Readiness-Reassessment.md`](../../docs/Publication-Arrangement-Readiness-Reassessment.md) | **`PAD-001` scope is expressly *"Training Baseline 0.1 publication arrangement only"*** — publishing the training documentation set. It is **not** project information publication under `S1` §9.7. Excluded to prevent the most dangerous available misreading. **See the terminology warning at §5 below** |
| **E2** | [`docs/Training-Publication-Arrangement-Approver-Function-Decision.md`](../../docs/Training-Publication-Arrangement-Approver-Function-Decision.md) · [`docs/Training-Baseline-Publication-Owner-Function-Decision.md`](../../docs/Training-Baseline-Publication-Owner-Function-Decision.md) · [`docs/Training-Publication-Naming-and-Presentation-Approver-Function-Decision.md`](../../docs/Training-Publication-Naming-and-Presentation-Approver-Function-Decision.md) · [`docs/Training-CDE-Governance-Approver-Function-Decision.md`](../../docs/Training-CDE-Governance-Approver-Function-Decision.md) · [`docs/Training-Baseline-Approval-Function-Decision.md`](../../docs/Training-Baseline-Approval-Function-Decision.md) | These establish **training-programme decision functions** (`AG-001`–`AG-005`) governing the Harrismith *documentation*. They allocate no project information-management responsibility and schedule no project information. **A training approver function is not a project role** |
| **E3** | [`docs/Training-Baseline-Naming-and-Presentation-Control-Candidate.md`](../../docs/Training-Baseline-Naming-and-Presentation-Control-Candidate.md) · [`docs/Training-Baseline-Naming-and-Presentation-Control-Readiness-Assessment.md`](../../docs/Training-Baseline-Naming-and-Presentation-Control-Readiness-Assessment.md) | Naming and presentation control **of the training baseline documents**. **Not** the project Naming Standard, which does not exist (`S12`, OF-003). Excluded to keep the two senses of "naming" apart |
| **E4** | [`docs/Publication-Planning-Control-Framework.md`](../../docs/Publication-Planning-Control-Framework.md) · [`docs/Publication-Planning-Evidence-and-Observation-Control-Register.md`](../../docs/Publication-Planning-Evidence-and-Observation-Control-Register.md) · [`docs/Publication-Planning-Read-Only-Observation-Authorisation.md`](../../docs/Publication-Planning-Read-Only-Observation-Authorisation.md) · [`docs/Increment-8D-Publication-Planning-Read-Only-Observation-Record.md`](../../docs/Increment-8D-Publication-Planning-Read-Only-Observation-Record.md) · [`docs/Claude-Desktop-Publication-Planning-Read-Only-Observation-Brief.md`](../../docs/Claude-Desktop-Publication-Planning-Read-Only-Observation-Brief.md) | Publication-planning control and observation authorisation. **Publication automation is `PAUSED`** and **no Autodesk or ACC activity is authorised**. Nothing here allocates responsibility or plans project information delivery |
| **E5** | [`docs/Training-Baseline-0.1-Candidate.md`](../../docs/Training-Baseline-0.1-Candidate.md) · [`docs/Training-Baseline-0.1-Gate-C-Decision.md`](../../docs/Training-Baseline-0.1-Gate-C-Decision.md) | The candidate and the gate decision **preceding** `AD-001`. `S8` is the approval decision and supersedes both as the current status statement. `S7` §6A records that *"Gate C passage enabled this decision but did not itself approve the baseline"* |
| **E6** | [`working/README.md`](../../working/README.md) · [`working/bep-working-register.md`](../../working/bep-working-register.md) · [`working/workshops/workshop-template.md`](../../working/workshops/workshop-template.md) | Working-process material. Relevant to **Module 8**, not to responsibility allocation or delivery planning |
| **E7** | [`../module-01-what-is-a-bep/source-map.md`](../module-01-what-is-a-bep/source-map.md) · [`../module-03-iso-19650-principles/source-map.md`](../module-03-iso-19650-principles/source-map.md) | No Module 5-specific dependency recorded. Continuity runs through `S13` and `S14` |
| **E8** | [`README.md`](../../README.md) · [`output/`](../../output/) | Repository operating instructions and an empty output directory. Neither is a governance or planning source |

---

## 5. Terminology warning carried into every Module 5 slide

**"Publication" carries two unrelated meanings in this repository, and one of
them is resolved while the other is not.**

| Sense | Where | Status |
|---|---|---|
| **Project information publication / exchange** — moving project information into the Published / Authorised state | `S1` §9.7; `S2` `D4`; `S4` §5.1; `S5` `T4` | **UNRESOLVED — TBD.** `T4` **blocked**; information **remains Shared** |
| **Training-baseline publication arrangement** — publishing the Harrismith documentation set | `PAD-001` (`E1`), scope *"Training Baseline 0.1 publication arrangement only"* | Arrangement **approved with conditions**; **`PE-3` NOT AUTHORISED**; publication hold **active** |

**Neither resolves the other.** `S8` states expressly that `AD-001` does **not**
*"establish project publication / exchange authority"* and does **not**
*"establish recipient acceptance authority"*.

**Prohibited:** presenting `PAD-001`, `PM-1`–`PM-7` or any publication-arrangement
approval as evidence that `D4`, `T4` or `TRN-E03` has been resolved.

---

## 6. Status of the three principal resources — recorded individually

**They do not share a single status.** Each declares its own, and two of the
three additionally classify their *content* below their *approval*.

| Resource | Document status | Content classification | Approval | Publication |
|---|---|---|---|---|
| **`S2`** IM Responsibility Matrix | APPROVED WITH CONDITIONS — Training Baseline 0.1 | **Not separately classified.** §Population rule: allocations are *"functional governance proposals unless the BEP already expressly establishes the allocation"* | `AD-001`, 2026-08-01; conditions active | **NOT AUTHORISED** |
| **`S3`** Model / Information Responsibility Matrix | APPROVED WITH CONDITIONS — Training Baseline 0.1 | **Every allocation in §3 is `PROPOSED GOVERNANCE`**, derived from **TA-03** | `AD-001`, 2026-08-01; conditions active | **NOT AUTHORISED** |
| **`S4`** Information Delivery Schedule | APPROVED WITH CONDITIONS — Training Baseline 0.1 | **All entries are `PROPOSED GOVERNANCE` / training delivery planning** | `AD-001`, 2026-08-01; conditions active | **NOT AUTHORISED** |

**`S2` carries a split status that `S3` and `S4` do not.** Its population rule
makes each allocation *proposed* **unless the BEP already expressly establishes
it**. Two allocations are expressly established by `S1` and are therefore
**controlled, not proposed**:

| Allocation | Established by | Status |
|---|---|---|
| **Task-Team Lead authorises WIP → Shared** (`P4`) | `S1` §9.4 — *"The Task-Team Lead — or another role explicitly allocated that function by approved governance — authorises information to progress from WIP to Shared"* | **Established allocation** |
| **Publication / exchange authority** (`D4`) | `S1` §9.7 — *"The role holding publication and exchange authority is UNRESOLVED"* | **Expressly established as unresolved** |

**Every other `S2` allocation is a functional governance proposal.** Module 5
must not present the whole matrix at one status level.

---

## 7. Conditions active against all three resources

From `S8` / `S7` `AD-001`. All were **carried at approval and remain listed**:

| Condition | Class | Bearing on Module 5 |
|---|---|---|
| Publication hold | **Active — publication NOT AUTHORISED** | Nothing in any resource may be described as published |
| **GCR-005** — publication parameters undefined | **PRE-PUBLICATION** — recorded closed at the governance-definition level by `PAD-001`; **implementation conditions and prerequisites remain** | Concerns the **training baseline**, not `D4`. See §5 |
| **GCR-006** — one complete governed coordination cycle to be exercised and evidenced | **IMPLEMENTATION — OPEN** | **No complete cycle has been demonstrated** (`S9` §8). Directly supports *allocation ≠ performance* |
| **UD-001** — MEP / Structural team-space mapping | **OBSERVED discrepancy + UNRESOLVED DECISION** | Recorded, **not corrected**. `S3` §6: *"Nothing in the allocations above proposes, implies or applies a replacement mapping"* |
| Project publication / exchange authority | **Unresolved** | `D4`, `T4`, `TRN-E03` |
| Recipient acceptance authority | **Unresolved** | `D7`, `T7`, `TRN-E03` |
| Naming, Coordinates, Titleblocks, Templates | **Not established** | No identifier or format convention may be taught |

---

## 8. What this inventory does not do

- It does **not** approve, amend, complete or reclassify any controlled source.
- It does **not** resolve `D4`, `D7`, `A2`, `UD-001`, `GCR-006`, the recipient
  identity, the required formats or the deliverable set.
- It does **not** merge the three principal resources, and it does **not**
  harmonise their differing terminology — differences are recorded in
  [`source-map.md`](source-map.md) §6.
- It does **not** convert `S9`'s observations into either a completion claim or
  a failure claim.
- It does **not** treat `S15`'s pre-declared Module 5 content as established.

## 9. Status

| Field | Value |
|---|---|
| Increment | **T5-A** |
| Sources inspected | **15 consulted** (`S1`–`S15`), **8 groups excluded with reason** (`E1`–`E8`) |
| Precedence | Established, and traced to `S1` §1.5 |
| Three principal resources | **Analysed separately** — see [`resource-comparison.md`](resource-comparison.md) |
| Outstanding | T5-B and later increments |
