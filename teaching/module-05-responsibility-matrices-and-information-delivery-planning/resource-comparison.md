# Module 5 — The Three Principal Resources, Compared

**Status:** Analysis record for teaching material. **Not governance.**

The Information Management Responsibility Matrix, the Model / Information
Responsibility Matrix and the Information Delivery Schedule are **three
separately controlled resources answering three different questions**. This file
records each one **on its own terms** before any comparison is drawn.

Source identifiers `S1`–`S15` are defined in
[`source-inventory.md`](source-inventory.md).

> **They do not form one RACI matrix.** `S2` §1 records the refusal explicitly:
> *"**RACI is not adopted.** This grammar is used instead, because it
> distinguishes checking from authorising and coordinating from performing —
> distinctions this BEP depends on and RACI collapses."* `S1` §5.12 states the
> same. **The refusal is controlled governance, not a stylistic preference.**

---

## 1. The three questions

| Resource | The single question it answers — **in its own words** |
|---|---|
| **`S2`** Information Management Responsibility Matrix | *"**who performs which information-management function?**"* |
| **`S3`** Model / Information Responsibility Matrix | *"**who produces and maintains which information container?**"* |
| **`S4`** Information Delivery Schedule | *"what information is exchanged, at what event, to whom, why, in what form, and under what checking, authorisation and acceptance conditions"* |

**Each resource states what it does *not* answer.** The disclaimers are mutual
and explicit — no teaching interpretation is required to keep them apart:

- `S2` does not answer *"which organisation authors each specific model or
  information container"*, *"what is delivered at each milestone"*, or *"which
  individual person currently holds each role"*.
- `S3` *"complements, and does not duplicate"* the other two.
- `S4` schedules **only** containers that already exist in `S3`.

---

## 2. `S2` — Information Management Responsibility Matrix

| Field | Recorded value |
|---|---|
| **Exact path** | [`supporting/information-management-responsibility-matrix.md`](../../supporting/information-management-responsibility-matrix.md) |
| **Exact title** | *Information Management Responsibility Matrix* |
| **Document status** | **APPROVED WITH CONDITIONS — Training Baseline 0.1** |
| **Version / revision** | **No version or revision field is declared.** The baseline identity *Training Baseline 0.1* is the only version marker present |
| **Date** | **No document date is declared.** The only date present is the approval date, **2026-08-01** (`AD-001`) |
| **Stated purpose** | *"Allocates information-management **functions** to **roles** across the process steps defined by the BEP"* |
| **Stated scope** | Information-management process functions in seven groups: governance, CDE, information production, sharing and consumption, coordination, delivery and exchange, change and assurance |
| **Stated exclusions** | Container authorship; milestone deliverables; individual role holders; **duplication of BEP Section 5 definitions** — *"Meaning is defined once… allocation is recorded once"* |
| **Approval / authority** | Supporting management resource under the Harrismith BEP framework. Approved with conditions through **`AD-001`**; conditions active; **publication NOT AUTHORISED** |
| **What a row represents** | **One information-management function** — an activity the process requires. **33 rows** across seven groups (`G1`–`G5`, `C1`–`C4`, `P1`–`P4`, `S1`–`S3`, `X1`–`X5`, `D1`–`D7`, `A1`–`A5`) |
| **What a column represents** | **One functional role** — **9 columns**: `AP`, `LDP`, `BM`, `BC`, `TTL`, `Aut`, `Chk`, `CDE`, `Rcp` |
| **What a populated cell means** | **The function this role holds in this activity** — and nothing more. It does **not** mean the activity happened, that a person exists to do it, or that the role is appointed |
| **Cell vocabulary** | **Seven function codes** — `P` Perform · `Ck` Check · `Au` Authorise · `Co` Coordinate · `Ac` Accept · `Cs` Consult · `In` Inform. **Plus two non-function values** — `TBD` *"Allocation unresolved. The BEP records this authority as not established"* and `—` *"The role holds no function in this activity."* **Codes combine** — `P Co`, `P Ck`, `P Cs`, `TBD Ac` all occur |
| **Identifier system** | Function refs by group letter and number; role codes as column headings. **No project numbering convention** — none exists |
| **Role versus person** | **Roles only.** §2: *"Functional roles only. No holder is established for any of them."* §Population rule: allocations are made *"to **functional roles**, not to companies or people. No organisation is appointed and no individual is named"* |
| **Producer / originator** | `P1` *Author information in WIP* — `Aut` **P**, `TTL` `Co`. §4: the Author *"Produces and modifies information"* and does **not** hold *"Self-authorisation of own work"* |
| **Checker** | `P2` task-team technical / content check and `P3` information-quality / readiness check — `Chk` **Ck**. §4: the Checker holds *"the defined check"*, not *"Authorisation — checking is not authorising"* |
| **Authoriser** | `P4` *Authorise WIP information for controlled sharing* — `TTL` **Au**. `D4` *Authorise publication / exchange* — **`TBD` in every column**. `A2` *Authorise governance change* — **`TBD`**, and *"**No single universal approver exists**"* |
| **Coordinator** | `Co` appears across 20 rows; `X1`–`X5` allocate the coordination process to `BC` as **`P Co`**. §4: the BIM Coordinator does **not** hold *"Ownership of the technical design solution; design-approval authority"* |
| **Recipient / accepting party** | `Rcp` is *"a generic function, not an organisation… whoever receives a given exchange under the approved delivery arrangement, **which does not yet exist**"*. `D6` receive — `Rcp` **P**. `D7` accept — **`TBD Ac`** |
| **Event / milestone** | **Not addressed.** `S2` allocates functions to activities, not to events. Events belong to `S4` |
| **Purpose** | Present in function wording — *"Authorise… for controlled sharing"*, *"Consume / reference Shared information **for a stated purpose**"*, *"Accept exchange **for a stated purpose**"* |
| **Suitability / permitted use** | **Not a field.** Suitability is `S1` §6.8 and `S4`'s *State / Suitability* field |
| **Evidence fields** | `A5` *Retain decision and change evidence* — `BM` **P**. No per-cell evidence field exists |
| **Blank-field treatment** | **There are no blank cells.** Every cell in all seven tables carries a code, `TBD`, or `—` |
| **Conditional-field treatment** | Expressed in prose, not a code — `P4`'s *"or another role expressly allocated it by approved governance"*; `A2`'s *"authority depends on the class of change"* |
| **Unresolved-field treatment** | **`TBD`**, defined once and used consistently. §6 lists all seven unresolved allocations with their BEP reference |
| **Blocked-field treatment** | **`S2` has no blocked class.** `D4` is recorded as **unresolved**, not blocked. The *blocked* classification belongs to `S4` `TRN-E03` and `S5` `T4` |
| **Not-applicable treatment** | **`—`**, expressly defined as *"The role holds no function in this activity"* |
| **Governance / planning / evidence** | **Mixed, and split within the document.** §Population rule: allocations are *"functional governance proposals **unless the BEP already expressly establishes the allocation**"*. `P4` is established by `S1` §9.4; `D4`'s unresolved status is established by `S1` §9.7. **The rest are proposals.** Contains **no implementation evidence** |
| **Dependencies** | `S1` §5 for every definition; `S1` §9 for authorisation and acceptance; `S1` §12.7 for change authority. §6 records that unresolved matters *"are recorded in the Governance & Decision Register and are resolved only by explicit recorded decision"* |
| **Shared identifiers** | `S4` §3.2, §4.3 and §6 cite `S2` rows **`P4`**, **`D4`** and **`D7`** by ref. `S3` §3 cites *"Authors and Checkers as allocated through BEP Section 5 and the Information Management Responsibility Matrix"* |
| **Incomplete / unresolved** | §6 — seven entries: `D4`, `D7`, `A2`, Appointing Party identity, Lead Delivery Party holder, BM/BC/CDE holders, Task-Team Lead holders |
| **Authority to populate or change** | Governance change under `S1` §12.7 — **`A2` authority is itself `TBD`, by change class.** Unresolved allocations are *"resolved only by explicit recorded decision"* |
| **Prohibited interpretations — stated in the source** | RACI substitution; Author self-authorisation (`P1`/`P4` note); *"Check is not Authorise"* (`P2`/`P3` note); permission as authority (`C2`/`C3` note); coordinator as design approver (`X3`/`X4` note); transmittal as approval (`D5`/`D6` note); **reading the matrix as evidence of independence** (§5) |

### 2.1 The independence rule — `S2` §5

`S2` §5 is the clearest statement in the whole source set that **allocation is
not performance**:

> *"This matrix allocates **functions to roles**. It does **not** demonstrate
> that separate people perform them, and it must not be read as evidence of
> independence."*

`S1` §5.11 and §9.12 permit one participant to hold more than one role. Where
Author and Checker combine, `S2` requires that the combination is **recorded**,
that the functional distinction survives, and that *"independence is **never**
claimed where it does not exist. Fictional independence is worse than an
acknowledged limitation, because it removes the reader's ability to weigh the
information."*

---

## 3. `S3` — Model / Information Responsibility Matrix

| Field | Recorded value |
|---|---|
| **Exact path** | [`supporting/model-information-responsibility-matrix.md`](../../supporting/model-information-responsibility-matrix.md) |
| **Exact title** | *Model / Information Responsibility Matrix* |
| **Document status** | **APPROVED WITH CONDITIONS — Training Baseline 0.1** |
| **Version / revision** | **No version or revision field is declared** |
| **Date** | **No document date.** Approval date **2026-08-01** (`AD-001`) |
| **Stated purpose** | *"Records which party and task team is intended to produce and maintain each information container or container class"* |
| **Stated scope** | *"Design discipline information containers for the six discipline domains in BEP 4.4, plus one multidisciplinary coordination information class"* |
| **Stated exclusions** | Construction and trade-contractor containers (§5); level of information need (§4); **delivery events, formats and timing — expressly assigned to `S4`** |
| **Approval / authority** | Supporting management resource. Approved with conditions through **`AD-001`**; **publication NOT AUTHORISED**. **Every §3 allocation is additionally classified `PROPOSED GOVERNANCE`**, derived from **`TA-03`** |
| **What a row represents** | **One information container or container class** — **6 discipline containers** (`ARC-01`, `STR-01`, `MEC-01`, `ELE-01`, `PLM-01`, `FIR-01`) plus **`COORD-01`**, which is recorded as a **field block, not a table row** |
| **What a column represents** | **§3.1** Ref · Container / class · Originating party · Task team · Discipline · Primary purpose. **§3.2** Ref · Authoring format · Exchange format · Intended CDE states. **§3.3** Ref · Dependencies / interfaces |
| **What a populated cell means** | **What is *intended* to be produced, by which party and task team.** §Intended governance: *"It is **not** an inventory of what currently exists in the CDE"* |
| **Cell vocabulary** | **No code set.** Cells carry named parties, task teams, discipline codes and prose. Absence is written as **`TBD`**, **`Not defined`**, or **`Not applicable`** |
| **Identifier system** | Container refs `<DISCIPLINE>-01`; discipline codes `ARC`, `STR`, `MEC`, `ELE`, `PLM`, `FIR`. **`A discipline code is not an organisation`** — §2, from `S1` §4.4 |
| **Role versus person** | Allocations are *"against the **functional parties and task teams** defined in BEP Section 4, not against companies or people"*. All Lead entries: **Task-Team Lead, holder `TBD`** |
| **Producer / originator** | **This is the resource's entire subject.** Origination follows `S1` §7.2: `party → task team → discipline → information container`, and *"**Originator responsibility remains with the producing task team**, through sharing, consumption, coordination and publication. No downstream act relieves it"* |
| **Checker** | **Not allocated here.** §3: *"Authors and Checkers as allocated through BEP Section 5 and the Information Management Responsibility Matrix"* |
| **Authoriser** | **Not allocated here.** §6 records publication / exchange authority as **`UNRESOLVED — TBD`** |
| **Coordinator** | `COORD-01` Lead function — **BIM Coordinator, holder `TBD`**. §3.4: the Coordinator *"leads the coordination process and does **not** own the technical design solution"* |
| **Recipient / accepting party** | **Not addressed** — expressly `S4`'s scope. §6 records recipient acceptance authority as **`UNRESOLVED — TBD`** |
| **Event / milestone** | **Out of scope**, stated in §1 |
| **Purpose** | *Primary purpose* column — authoring, multidisciplinary coordination, controlled design exchange |
| **Suitability / permitted use** | **Not a field.** *Intended CDE states* is the nearest, and is qualified: *"Publication occurs only where a defined delivery requires it **and** the required authorisation has occurred — and that authority is unresolved"* |
| **Evidence fields** | **None.** The document is explicit that it is not evidence: only Architecture was observed as a populated direct production stream (**`OF-002`**), and *"absence of observation is not observation of absence"* |
| **Blank-field treatment** | **There are no blank cells.** Absence is always typed |
| **Conditional-field treatment** | *"WIP → Shared → Published/Authorised **where a defined delivery requires it**"*; trade containers as a *"recorded future extension"* |
| **Unresolved-field treatment** | §6 — a nine-row register carrying `TBD`, `Not defined`, `UNRESOLVED — TBD`, `Candidate context only` and `UD-001 — UNRESOLVED` |
| **Blocked-field treatment** | **No blocked class.** Publication authority is *unresolved*, not blocked |
| **Not-applicable treatment** | **Expressly used once** — `COORD-01` *Originating party*: **`Not applicable — see note below`**, because federation *"does **not** merge authorship"*. §4 uses a different absence: level of information need is **`Not defined`**, an information gap. **These two are not the same absence** |
| **Governance / planning / evidence** | **Intended governance / `PROPOSED GOVERNANCE`.** *"This matrix describes what is intended to be produced under the training delivery model."* **Contains no implementation evidence** |
| **Dependencies** | `S1` §4 (organisation), §7.2 (origination). Formats and exchange states depend on `S4`. `S7` for `OF-002`, `OF-003`, `UD-001`, `TA-03` |
| **Shared identifiers** | **`S4` schedules only containers that exist here** — `S4` §Container discipline: *"Every scheduled discipline container references an existing container ref from `model-information-responsibility-matrix.md`. **No container is scheduled that does not exist in that matrix**"*. Discipline codes are shared with `S4` |
| **Incomplete / unresolved** | §6 — nine entries, including formats, level of information need, naming, publication authority, acceptance authority and **`UD-001`** |
| **Authority to populate or change** | Governance change under `S1` §12; **`UD-001`'s decision owner is `Not established`**. *"Platform change follows a governance decision, not the reverse"* (`S7`, `S1` §12.1) |
| **Prohibited interpretations — stated in the source** | Six discipline codes implying six organisations; MEC/ELE/PLM as three companies; FIR as an MEP sub-team; RVT/IFC/PDF/NWC as mandated; `COORD-01` as a jointly-authored model, a new author, or a deliverable; trade containers as missing data; **silently correcting `UD-001`** |

### 3.1 Two organisational traps the source flags itself

| Trap | `S3` §2, from `S1` §4.3 |
|---|---|
| **MEC, ELE, PLM** | *"three task teams and three disciplines within **one** party — not three companies"* |
| **FIR** | *"organisationally separate", carried by the Fire Consultant. **"It is not an MEP sub-team"*** |

---

## 4. `S4` — Information Delivery Schedule

| Field | Recorded value |
|---|---|
| **Exact path** | [`supporting/information-delivery-schedule.md`](../../supporting/information-delivery-schedule.md) |
| **Exact title** | *Information Delivery Schedule* |
| **Document status** | **APPROVED WITH CONDITIONS — Training Baseline 0.1** |
| **Version / revision** | **No version or revision field is declared** |
| **Date** | **No document date.** Approval date **2026-08-01** (`AD-001`) |
| **Stated purpose** | *"Records what information is exchanged, at what event, to whom, why, in what form, and under what checking, authorisation and acceptance conditions"* |
| **Stated scope** | *"a **controlled training delivery-planning instrument**"* — three restrained event concepts. *"This is **not** a full project delivery schedule"* |
| **Stated exclusions** | *"**not a contractual programme**"*; not real client requirements, contractual milestones, consultant appointments or construction programme dates |
| **Approval / authority** | Supporting management resource. Approved with conditions through **`AD-001`**; **publication NOT AUTHORISED**. **All entries additionally classified `PROPOSED GOVERNANCE` / training delivery planning** |
| **What a row represents** | **One scheduled container within one delivery event** — *"Delivery ID: Identifier for a scheduled container row"*. `TRN-E01` has **6 rows**; `TRN-E02` has **6 conditional template rows**; **`TRN-E03` has none** |
| **What a column represents** | **One of the 16 fields approved in `S1` §10.13** — Delivery ID · Exchange/Milestone · Information Container · Originating Party · Task Team · Discipline · Lead · Recipient · Purpose · Format · State/Suitability · Checking Requirement · Authorisation Requirement · Acceptance Criteria · Status · Dependencies |
| **What a populated cell means** | **A planning intention for that field.** *"These schedule entries exist to exercise the Harrismith BIM-management workflow. They are **not evidence** of"* real requirements, milestones, appointments or dates |
| **Cell vocabulary** | **No code set.** Prose plus recurring absence markers: **`TBD`**, **`Not established`**, **`Not defined`**, **`PROPOSED`**, **`BLOCKED`**, **`Conditional`**, **`Event-triggered / TBD`** |
| **Identifier system** | Event IDs `TRN-E01`–`TRN-E03`; row IDs `TRN-E01-ARC` and similar. **Expressly training-internal** — *"They are **not** contractual document numbers and carry no project numbering convention — no Naming Standard exists"* |
| **Role versus person** | Roles only. Every `Lead` is **Task-Team Lead (`TBD`)**. §6 records role consistency with `S2` and does not duplicate it |
| **Producer / originator** | *Originating Party* and *Task Team* fields, taken from `S3`. §3: *"Each discipline container is shared **from its own originating task team**. The six rows below are **six separate exchanges, not one jointly-owned model**"* |
| **Checker** | *Checking Requirement* field. `TRN-E01`: task-team technical/content check **and** information-quality/readiness check (`S1` §7.6, §9.3) |
| **Authoriser** | *Authorisation Requirement* field. `TRN-E01`/`TRN-E02`: **Task-Team Lead authorisation to share**. **`TRN-E03`: `TBD — publication / exchange authority unresolved`** |
| **Coordinator** | §6: BIM Coordinator *"coordinates the process; does **not** technically approve discipline information"* |
| **Recipient / accepting party** | *Recipient* and *Acceptance Criteria* fields. `TRN-E01`/`TRN-E02`: BIM Coordinator and participating coordination task teams. **`TRN-E03` Recipient: `TBD — not established`** |
| **Event / milestone** | **This is the resource's entire subject** — but *"No calendar dates, frequencies or contractual milestones exist for any event"* |
| **Purpose** | A named field on every event. `TRN-E01` coordination; `TRN-E02` re-coordination after findings; `TRN-E03` *"toward an authorised project-facing review exchange"* |
| **Suitability / permitted use** | *State / Suitability* field. `TRN-E01`/`TRN-E02`: **Shared — coordination use only**, and expressly *"**not** construction-ready, **not** formally accepted design, and **not** record information"* |
| **Evidence fields** | **None.** *Status* records the state of **the schedule entry**, not of any delivery |
| **Blank-field treatment** | **There are no blank cells.** Every unknown is named |
| **Conditional-field treatment** | **A first-class concept.** `TRN-E02` is *"repeatable and conditional"* with **no calendar frequency**; its six rows are *"**template rows, not active deliveries**"*, and *"An unactivated row is **not a pending exchange** and carries no expectation that the task team will produce anything"* |
| **Unresolved-field treatment** | **`TBD`** / **`Not established`** / **`Not defined`**, collected in §7 |
| **Blocked-field treatment** | **`BLOCKED` is defined and used.** `TRN-E03` is **`PROPOSED — BLOCKED PENDING GOVERNANCE DECISIONS`**, with §5.1 naming **five** blocking matters. *"An entry that cannot proceed is recorded as blocked. **Assigning a plausible authority to make the row look finished would manufacture governance that does not exist**"* |
| **Not-applicable treatment** | **Not used.** `S4` has no not-applicable class — every absence is unresolved, undefined, conditional or blocked |
| **Governance / planning / evidence** | **Planning — `PROPOSED GOVERNANCE` / training delivery planning.** **Contains no implementation evidence** |
| **Dependencies** | Container refs from `S3`; authorisation allocations from `S2`; states and transitions from `S5`; `S1` §10.13 for the field list; **`S1` §1.5 for precedence if real requirements later appear** |
| **Shared identifiers** | Container refs and discipline codes from `S3`; `S2` rows `P4`, `D4`, `D7` cited by ref in §3.2, §4.3 and §6 |
| **Incomplete / unresolved** | §7 — nine entries; §5.1 — five `TRN-E03` blocking matters |
| **Authority to populate or change** | Governance change under `S1` §12; **`TRN-E03` cannot be completed at all** until `S1` §9.7 and §9.8 authorities are resolved and a recipient, requirement and formats exist |
| **Prohibited interpretations — stated in the source** | Entries as real requirements, milestones, appointments or programme dates; `TRN-E02` as a per-cycle six-discipline reshare; an unactivated row as a pending exchange; observed formats as delivery requirements; **Published = Delivered = Received = Accepted**; receiver consumption as design approval; coordinator verification as design approval; **completing `TRN-E03` to tidy the row** |

### 4.1 `TRN-E03` — the five blocking matters, recorded exactly

| Blocking matter | Status | Reference |
|---|---|---|
| Publication / exchange authorisation authority | **UNRESOLVED — TBD** | `S1` §9.7; `S2` `D4` |
| Recipient acceptance authority | **UNRESOLVED — TBD / recipient-dependent** | `S1` §9.8, §10.11; `S2` `D7` |
| Recipient identity | **Not established** | `S1` §2.3, §5.3 |
| Required formats | **Not established — no approved standard** | `S1` §11.9; `OF-003` |
| Deliverable set | **Not defined** | `S1` §10.4 |

**None of these five may be populated by Module 5.** Resolving one would not
release the others: `S4` §5.2 records that the container set, lead, recipient,
format, authorisation and acceptance criteria are each independently `TBD`.

---

## 5. Overlaps — where two resources touch the same object

| Object | `S2` | `S3` | `S4` | How the overlap is governed |
|---|---|---|---|---|
| **Information container** | Not named | **Defines** `ARC-01`–`FIR-01`, `COORD-01` | **Consumes** the refs | `S4`'s container-discipline rule: no container is scheduled that `S3` does not define |
| **Authorisation to share** | **`P4`** — `TTL` `Au` | Not allocated | **Cited** as the `TRN-E01`/`TRN-E02` authorisation requirement | Single origin: `S1` §9.4 → `S2` `P4` → `S4` |
| **Publication authority** | **`D4` — `TBD`** | §6 — `UNRESOLVED — TBD` | §5.1 — first blocking matter | **Three records, one unresolved matter.** All trace to `S1` §9.7 |
| **Acceptance authority** | **`D7` — `TBD Ac`** | §6 — `UNRESOLVED — TBD` | §5.1 — second blocking matter | All trace to `S1` §9.8, §10.11 |
| **Task-Team Lead holder** | §2, §6 — `TBD` for every task team | §3 — all Lead entries `TBD` | Every `Lead` field — `TBD` | Consistent across all three |
| **Format** | Not a field | §3.2 — `TBD`, no format mandated | *Format* field — `TBD by approved format requirement` | Both defer to an approved standard that **does not exist** (`OF-003`, `S12`) |
| **Coordination** | `X1`–`X5`, `BC` `P Co` | `COORD-01` lead function | `TRN-E01`/`TRN-E02` recipient and purpose | **The mechanics belong to `S6` and Module 6** |
| **Purpose** | Embedded in function wording | *Primary purpose* column | *Purpose* field per event | Three different granularities of the same idea |

**Overlap is by reference, not by duplication.** Each resource states that it
does not duplicate the others, and in every case above the detail lives in
exactly one place.

---

## 6. Differences — where the three resources genuinely diverge

| # | Difference | Recorded, not harmonised |
|---|---|---|
| **1** | **Only `S2` has a code vocabulary.** `S3` and `S4` use prose | Module 5 must not teach `P`/`Ck`/`Au` as though they applied to schedule or container rows |
| **2** | **Only `S4` uses `BLOCKED`.** `S2` and `S3` record the same authority gaps as **unresolved** | The same underlying matter carries **two different classifications in three documents**. Neither is wrong: `S2`/`S3` classify the *allocation*; `S4` classifies the *entry that cannot proceed* |
| **3** | **Only `S3` uses `Not applicable`**, and exactly once (`COORD-01` originating party) | `S4` has no not-applicable class at all |
| **4** | **Only `S3` and `S4` classify their content below their approval status** as `PROPOSED GOVERNANCE`. `S2` instead applies a **split rule** — proposal unless the BEP expressly establishes it | The three resources are **not at one status level**, and `S2` is not at one status level internally |
| **5** | **Row meaning differs completely** — `S2` row = a *function*; `S3` row = a *container*; `S4` row = a *container within an event* | The same word *row* means three different things |
| **6** | **`S2` allocates to nine role columns; `S3` allocates to parties and task teams; `S4` names a single `Lead` per row** | Three different granularities of "who" |
| **7** | **`S2` has no event dimension; `S3` expressly excludes events; `S4` is organised entirely by event** | Only `S4` answers *when* — and answers it *"event-triggered / TBD"* |
| **8** | **`S3` records an observed condition (`OF-002`, `UD-001`) it refuses to correct; `S2` and `S4` record none** | `S3` is the only principal resource that carries an as-found platform observation |

---

## 7. Terminology variance — recorded, not reconciled

| # | Term | `S2` | `S3` | `S4` | Position |
|---|---|---|---|---|---|
| **1** | The unresolved marker | **`TBD`** — defined in the legend | `TBD`, `Not defined`, `UNRESOLVED — TBD` | `TBD`, `Not established`, `Not defined` | **Only `S2` defines its marker.** `S3` and `S4` use several without a legend. **Not harmonised** |
| **2** | *Lead* | Not a term — `TTL` is a role column | *Lead function* (`COORD-01`), *Lead entries* (§3) | *Lead* — an approved field (`S1` §10.13) | Three usages of one word. `S4`'s is the defined field |
| **3** | *Purpose* | Inside function wording | *Primary purpose* — of the container | *Purpose* — of the exchange | **A container's purpose and an exchange's purpose are different objects** |
| **4** | *Accept* | **`Ac`** — a grammar code, *"Receives for an identified purpose"* | Absent | *Acceptance Criteria* — a field | The code and the field are related but not identical: `S2` allocates *who*, `S4` records *against what* |
| **5** | *Publication* | `D4` — project information | §6 — project information | §5.1 — project information | **Distinct from the training-baseline publication arrangement.** See [`source-inventory.md`](source-inventory.md) §5 |
| **6** | *Status* | Not a field | Not a field | *Status* — **of the schedule entry**, not of a delivery | Easily misread as delivery status |
| **7** | *State* | Absent | *Intended CDE states* | *State / Suitability* | `S1` §6.8 governs the definition; `S5` governs transitions |

**Identifier collision — recorded.** `S2`'s sharing-and-consumption rows are
numbered **`S1`, `S2`, `S3`**, which collide with the source identifiers `S1`,
`S2`, `S3` used throughout this module. **Module 5 always writes these as "the
IM matrix sharing rows"** and never as bare `S1`–`S3`.

---

## 8. Relationships — how the three connect

```
S1 (BEP)  defines every function, term and field
   |
   |-- §5.12 --> S2  allocates FUNCTIONS to ROLES
   |                    |
   |                    |  P4, D4, D7 cited by ref
   |                    v
   |-- §7.2  --> S3  allocates CONTAINERS to PARTIES / TASK TEAMS
   |                    |
   |                    |  container refs consumed
   |                    v
   |-- §10.13 -> S4  schedules CONTAINERS into EVENTS
                        |
                        |  states and transitions
                        v
                     S5  T1 ... T8   (Module 4)
```

**The chain is directional and each link is stated in the sources.** `S4`
depends on `S3` for containers and on `S2` for authorisation allocations. `S3`
depends on `S2` for Author and Checker allocation. **`S2` depends on neither**,
and no resource depends on `S4`.

**Unresolved relationship — recorded.** No source states what happens to a `S4`
row if a `S3` container allocation later changes. `S4` requires every scheduled
container to exist in `S3`, but **no source defines the reverse dependency, the
change-propagation route between them, or which resource is updated first.**
`S1` §12.7's change authority (`A2`) is itself `TBD`. **Recorded as unresolved;
not answered here.**

---

## 9. What this comparison does not do

- It does **not** merge the three resources or propose a combined table.
- It does **not** resolve `D4`, `D7`, `A2`, `UD-001`, the `TRN-E03` recipient,
  the required formats or the deliverable set.
- It does **not** reclassify `BLOCKED` as unresolved, or the reverse.
- It does **not** harmonise the terminology variances in §7.
- It does **not** claim any allocation or schedule row has been performed —
  see [`source-map.md`](source-map.md) §8 for the implementation position.
