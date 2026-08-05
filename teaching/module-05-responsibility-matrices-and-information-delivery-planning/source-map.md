# Module 5 — Source Map, Registers and Prohibited Claims

**Status:** Traceability record for teaching material. **Not governance.**

Statement-level classification for **Slides 1–5** — the slides developed in
increments **T5-A** (1–3) and **T5-B** (4–5) — plus the terminology register, the
hypothesis register, the unresolved register, the prohibited claims and the
Module 6 deferrals.

**Slides 6–14 exist as architecture only.** They carry no classified statements
and no developed content. See
[`presentation-outline.md`](presentation-outline.md) §3.

Source identifiers `S1`–`S15` are defined in
[`source-inventory.md`](source-inventory.md). Resource analysis is in
[`resource-comparison.md`](resource-comparison.md).

---

## 1. Classification scheme

| Class | Meaning |
|---|---|
| **`CONTROLLED`** | Controlled Harrismith governance — explicit wording in `S1` |
| **`SUPPORTING`** | Approved supporting resource — `S2`, `S3`, `S4`, `S5`, `S6`, `S7` |
| **`DECISION-RECORD`** | Controlled decision, approval or validation record — `S8`, `S9`, `S10` |
| **`MODULE-2-4`** | Earlier-module teaching interpretation, already established — `S13`, `S14` |
| **`TEACHING-PLAN`** | Programme planning material — `S15`. **Decides nothing** |
| **`INTERP`** | Supported interpretation — **cited sources support the construction**, but no source phrases it this way |
| **`SYNTH`** | Teaching synthesis — **no source states the wording and none is cited in support**. Presenter framing only |
| **`EXCLUDED`** | Considered and deliberately left out |

**`INTERP` and `SYNTH` are separated by whether a source is cited, not by
whether the wording is original.** Both classes describe statements no controlled
document phrases; `INTERP` records the sources the construction rests on, and
`SYNTH` records that there are none. **A statement with a source reference is
never `SYNTH`** — see §5.1.

## 2. Governance and implementation status

**Every allocation and schedule statement carries both. They are not the same.**

| Governance status | Meaning |
|---|---|
| **`CONTROLLED GOVERNANCE`** | Approved and governing — `S1` |
| **`ESTABLISHED ALLOCATION`** | An `S2` allocation the BEP **expressly establishes** |
| **`PROPOSED GOVERNANCE`** | The source's own classification — `S3` §3, all of `S4` |
| **`PLANNED`** | Recorded as intended |
| **`CONDITIONAL`** | Activates only when a stated trigger occurs |
| **`BLOCKED`** | Cannot proceed; a required authority or input is unresolved |
| **`UNRESOLVED`** | Open matter, recorded as open |

| Implementation status | Meaning |
|---|---|
| **`IMPLEMENTATION UNVERIFIED`** | Not checked against intended governance |
| **`OBSERVED — QUALIFIED`** | Observed in `S9`, **at the inspected level only** |
| **`NOT DEMONSTRATED`** | `S9` looked and did not observe it. **Not a failure claim** |

**Absence of verification is never converted into a failure claim.** `S9`:
*"Absence of observation is not observation of absence."*

## 3. Fields recorded for each statement

| Field | |
|---|---|
| **ID** | `M5-S<slide>-<nn>` |
| **Statement** | What is taught |
| **Source path** | The repository file |
| **Section** | The section or record within it |
| **Auth** | Precedence level 1–5, per [`source-inventory.md`](source-inventory.md) §1 |
| **Governance** | From §2 |
| **Implementation** | From §2, or `—` where not applicable |
| **Class** | From §1 |

---

## 4. Source-authority register — which source governs which Module 5 concept

| Concept | **Governs** | Supporting | Note |
|---|---|---|---|
| Responsibility grammar — the seven terms | **`S1` §5.12** | `S2` §1 | `S1` states *"the matrix will use these terms and no others"* |
| Refusal of RACI | **`S1` §5.12** | `S2` §1 | Stated independently in both |
| Function-to-role allocation | **`S2` §3** | `S1` §5 | `S1` defines meaning; `S2` records allocation |
| Origination chain | **`S1` §7.2** | `S3` §2 | `party → task team → discipline → container` |
| Container-to-party allocation | **`S3` §3** | `S1` §4, §7.2 | `S3` is the only source that allocates containers |
| Delivery schedule fields | **`S1` §10.13** | `S4` §1 | Sixteen fields |
| Delivery events | **`S4` §2** | `S5` §9–§11 | `S4` **defines**; `S5` **maps** them to transitions |
| Authorisation to share | **`S1` §9.4** | `S2` `P4`; `S4` §3.2, §4.3 | **Established allocation** — Task-Team Lead |
| Publication / exchange authority | **`S1` §9.7** | `S2` `D4`; `S3` §6; `S4` §5.1 | **UNRESOLVED in all four** |
| Recipient acceptance | **`S1` §9.8, §10.11** | `S2` `D7`; `S3` §6; `S4` §5.1 | **UNRESOLVED in all four** |
| Deliverable vs container | **`S1` §10.4** | `S4` §5.2 | *"A delivery is not synonymous with a file"* |
| Published / Delivered / Received / Accepted | **`S1` §10.11** | `S4` §5.3; `S5` `T5`–`T7` | Four distinct objects |
| State transitions `T1`–`T8` | **`S5` §3** | `S1` §6, §7 | **Module 4 owns this** |
| Precedence between documents | **`S1` §1.5** | `S1` §13.6 | Reference is not approval |
| Change authority | **`S1` §12.7** | `S2` `A2`; `S7` | **`A2` is `TBD` by change class** |
| Classification vocabulary | **`S7`** | — | `OBSERVED FACT` / `TRAINING ASSUMPTION` / `PROPOSED` / `APPROVED` / `UNRESOLVED` |
| Live implementation status | **`S9`** | `S7` `OF-002` | `S9` declares **`Authority: None`** |
| Coordination mechanics | **`S6`** | — | **Module 6 — deferred** |
| Visual specification and assets | — | — | **T5-F — not started** |

---

## 5. Statement classification — Slides 1–5

**84 statements. 20 `CONTROLLED`, 35 `SUPPORTING`, 8 `DECISION-RECORD`,
2 `MODULE-2-4`, 1 `TEACHING-PLAN`, 9 `INTERP`, 0 `SYNTH`, 9 `EXCLUDED`.**

| Slide | Statements | `CTRL` | `SUPP` | `DEC` | `M2-4` | `PLAN` | `INT` | `SYN` | `EXC` |
|---|---:|---:|---:|---:|---:|---:|---:|---:|---:|
| 1 | 12 | 3 | 3 | 2 | 2 | 1 | 0 | 0 | 1 |
| 2 | 15 | 3 | 3 | 5 | 0 | 0 | 3 | 0 | 1 |
| 3 | 16 | 2 | 7 | 0 | 0 | 0 | 4 | 0 | 3 |
| **4** | **19** | **5** | **10** | **0** | **0** | **0** | **2** | **0** | **2** |
| **5** | **22** | **7** | **12** | **1** | **0** | **0** | **0** | **0** | **2** |
| **Total** | **84** | **20** | **35** | **8** | **2** | **1** | **9** | **0** | **9** |

**Slides 6–14 are architecture only** and carry no classified statements.

**Four observations.**

**Slide 3 is the most heavily `SUPPORTING` material in the programme so far.**
Seven of its sixteen statements come from `S2`, `S3` and `S4` directly, because
the three resources **describe themselves and each other explicitly**. Very
little interpretation is needed to keep them apart — the documents do it.

**Slide 5 is the most heavily `CONTROLLED` slide in the module.** Seven of its
twenty-two statements come from `S1` directly — because the organisational traps
it must defuse are **defined in the BEP, not in the matrix**. `S1` §4.2, §4.3 and
§4.4 do the work; `S3` applies it.

**Slide 2 carries five of the module's eight `DECISION-RECORD` statements**,
because the *allocation ≠ performance* distinction rests on `S9` — the only
source in the inventory that looked at the live environment.

**No `SYNTH` statement exists anywhere in the module.** Every statement across
the five developed slides either cites a source or is expressly `EXCLUDED` —
see §5.1.

### 5.1 Classification reconciliation — recorded in T5-B

**A prior inconsistency was found and resolved.**

| | Position before T5-B |
|---|---|
| §1 | `SYNTH` meant *"Teaching synthesis; no source support"* |
| `M5-S2-14` | The learning objective was classified **`SYNTH`**, source **`none`**, authority level 5 |
| [`README.md`](README.md) §1 | Recorded the objective as *"derived from `S1` §10.5 and the three resources' own purpose statements"* |

**The README and the source map contradicted each other.** One recorded cited
sources; the other recorded none.

**Resolution — the evidence was inspected, and it supports the README.** The
learning objective's substance is source-supported on both halves:

| Clause | Support |
|---|---|
| *"say what each governs"* | `S2`, `S3` and `S4` each state their own question and their own exclusions |
| *"identify what remains unresolved without filling it"* | **All three resources carry an express population rule forbidding invention** — `S2` §Population rule, `S3` §Population rule, `S4` §Population rule |
| The eight things a task team must be able to answer | `S1` §10.5 |

**`M5-S2-14` is therefore reclassified `INTERP`**, at authority level 4, with its
supporting sources recorded. It is a supported interpretation, not unsupported
synthesis.

**`SYNTH` was additionally redefined** so the ambiguity cannot recur. The old
wording — *"no source support"* — conflated two different things. The class now
turns on **whether a source is cited**: `INTERP` records the sources a
construction rests on; `SYNTH` records that there are none. **A statement with a
source reference is never `SYNTH`.**

**Effect on totals.** `INTERP` 6 → **9** (one from this reclassification, two
added on Slide 4); `SYNTH` 1 → **0**. **No count was changed to reach a preferred
figure**, and no other statement was reclassified.

**Scope note.** This refinement applies to **Module 5's scheme only**. Modules
1–4 hold their own classification schemes in their own source maps and are
**unchanged**.

### Slide 1 — Module 5: from who holds a role to what must be produced

| ID | Statement | Source path | Section | Auth | Governance | Implementation | Class |
|---|---|---|---|---|---|---|---|
| `M5-S1-01` | The three principal resources are **separately controlled**, each declaring its own status, version and authority | `bep/Harrismith-Fire-Station-BEP.md` | §5.12, §7.12, §10.13 | 1 | **`CONTROLLED GOVERNANCE`** | — | **`CONTROLLED`** |
| `M5-S1-02` | *"Reference from this BEP does not constitute approval of it"* | `bep/…BEP.md` | §13.6, §5.12, §7.12, §10.13 | 1 | **`CONTROLLED GOVERNANCE`** | — | **`CONTROLLED`** |
| `M5-S1-03` | The BEP **defines what a function means**; the supporting resource **records how it is allocated** | `bep/…BEP.md` | §5.12 | 1 | **`CONTROLLED GOVERNANCE`** | — | **`CONTROLLED`** |
| `M5-S1-04` | All three resources are **APPROVED WITH CONDITIONS — Training Baseline 0.1** | `supporting/information-management-responsibility-matrix.md`; `…/model-information-responsibility-matrix.md`; `…/information-delivery-schedule.md` | Status blocks | 2 | **`CONTROLLED GOVERNANCE`** — approval status | — | **`SUPPORTING`** |
| `M5-S1-05` | `S3` §3 allocations and **all** `S4` entries are additionally classified **`PROPOSED GOVERNANCE`** | `supporting/model-information-responsibility-matrix.md`; `supporting/information-delivery-schedule.md` | §Classification | 2 | **`PROPOSED GOVERNANCE`** | — | **`SUPPORTING`** |
| `M5-S1-06` | **`S2` carries a split status** — allocations are proposals *"unless the BEP already expressly establishes the allocation"* | `supporting/information-management-responsibility-matrix.md` | §Population rule | 2 | **`PROPOSED GOVERNANCE`** / **`ESTABLISHED ALLOCATION`** | — | **`SUPPORTING`** |
| `M5-S1-07` | **Publication remains NOT AUTHORISED**; the hold is active | `docs/Training-Baseline-0.1-Approval-Decision.md` | `AD-001` | 3 | **`CONTROLLED GOVERNANCE`** — active condition | — | **`DECISION-RECORD`** |
| `M5-S1-08` | `AD-001` did **not** establish project publication authority, acceptance authority or any project standard | `docs/Training-Baseline-0.1-Approval-Decision.md` | `AD-001` explicit non-effects | 3 | **`UNRESOLVED`** | — | **`DECISION-RECORD`** |
| `M5-S1-09` | **Module 2 callback** — role, function and authority | `../module-02-roles-and-responsibilities/source-map.md` | — | 4 | — | — | **`MODULE-2-4`** |
| `M5-S1-10` | **Module 4 callback** — states, the two transitions, and `T4` blocked | `../module-04-cde-workflows-and-information-states/source-map.md` | §7 | 4 | **`BLOCKED`** carried forward | **`IMPLEMENTATION UNVERIFIED`** | **`MODULE-2-4`** |
| `M5-S1-11` | Module 5's position as module 5 of 8; Module 6 owns coordination and assurance | `../roadmap.md` | §2 | 4 | — | — | **`TEACHING-PLAN`** |
| `M5-S1-12` | Any claim that the matrices or the schedule are implemented, operating or in live use | — | — | — | — | — | **`EXCLUDED`** |

**Teaching warning — `M5-S1-04` / `M5-S1-05` / `M5-S1-06`.** These three must be
delivered together. Presenting only `M5-S1-04` would leave the audience believing
the three resources sit at one status level. **They do not**, and `S2` does not
sit at one status level internally.

### Slide 2 — Knowing the role and the transition is not yet a plan

| ID | Statement | Source path | Section | Auth | Governance | Implementation | Class |
|---|---|---|---|---|---|---|---|
| `M5-S2-01` | Each task team should understand **what it must produce · for which event · for whom · the purpose · the format · the required checks · the required authorisation · its dependencies** | `bep/…BEP.md` | §10.5 | 1 | **`CONTROLLED GOVERNANCE`** | — | **`CONTROLLED`** |
| `M5-S2-02` | Information production is driven by **defined requirements**, *"not by assumption about what might be wanted"* | `bep/…BEP.md` | §7.3 | 1 | **`CONTROLLED GOVERNANCE`** | — | **`CONTROLLED`** |
| `M5-S2-03` | **No formal information requirements are available** to this implementation | `bep/…BEP.md` §7.3, §10.2; `supporting/information-delivery-schedule.md` §What these entries are not | — | 1, 2 | **`UNRESOLVED`** | — | **`CONTROLLED`** |
| `M5-S2-04` | **`by when` is not supported.** *"No real delivery dates or client milestones have been established"*; all timing is **event-triggered or `TBD`** | `supporting/information-delivery-schedule.md` | §Population rule, §2, §7 | 2 | **`PROPOSED GOVERNANCE`** / **`UNRESOLVED`** | — | **`SUPPORTING`** |
| `M5-S2-05` | The revised central question — **which information · by which task team · for which event and recipient · for what purpose · under which checks and authorisation** | `S1` §10.5; `S4` §1 | — | 4 | — | — | **`INTERP`** |
| `M5-S2-06` | Module 2 answered *who holds the role*; Module 4 answered *how information moves*; **neither answers what must be produced** | — | — | 4 | — | — | **`INTERP`** |
| `M5-S2-07` | **Allocation is not performance** — *"It does **not** demonstrate that separate people perform them, and it must not be read as evidence of independence"* | `supporting/information-management-responsibility-matrix.md` | §5 | 2 | **`PROPOSED GOVERNANCE`** | — | **`SUPPORTING`** |
| `M5-S2-08` | **Intended governance, not live inventory** — *"It is **not** an inventory of what currently exists in the CDE"* | `supporting/model-information-responsibility-matrix.md` | §Intended governance | 2 | **`PROPOSED GOVERNANCE`** | **`IMPLEMENTATION UNVERIFIED`** | **`SUPPORTING`** |
| `M5-S2-09` | **`ARC-01`** — live equivalent observed | `docs/Increment-7C-Live-Validation-Record.md` | §7 | 3 | — | **`OBSERVED — QUALIFIED`** | **`DECISION-RECORD`** |
| `M5-S2-10` | **`STR-01`, `MEC-01`, `ELE-01`, `PLM-01`, `FIR-01`** — not observed as live direct coordination inputs **at the inspected level** | `docs/Increment-7C-Live-Validation-Record.md` | §7 | 3 | — | **`NOT DEMONSTRATED`** | **`DECISION-RECORD`** |
| `M5-S2-11` | *"Absence of observation is not observation of absence."* **This is not a claim that any discipline is absent, uncommitted or inactive** | `docs/Increment-7C-Live-Validation-Record.md` §7; `supporting/governance-decision-register.md` `OF-002` | — | 3, 2 | — | — | **`DECISION-RECORD`** |
| `M5-S2-12` | **`GCR-006` remains OPEN** — no complete governed coordination cycle has been exercised or evidenced | `docs/Training-Baseline-0.1-Approval-Decision.md` `AD-001`; `docs/Increment-7C-Live-Validation-Record.md` §8 | — | 3 | **`UNRESOLVED`** | **`NOT DEMONSTRATED`** | **`DECISION-RECORD`** |
| `M5-S2-13` | **No governed publication or acceptance authority evidence was established** | `docs/Increment-7C-Live-Validation-Record.md` | §9 | 3 | **`UNRESOLVED`** | **`NOT DEMONSTRATED`** | **`DECISION-RECORD`** |
| `M5-S2-14` | Learning objective — *read the three resources, say what each governs, and identify what remains unresolved without filling it* | `S1` §10.5; `S2`, `S3`, `S4` purpose statements and **population rules** | — | 4 | — | — | **`INTERP`** |
| `M5-S2-15` | Any date, programme, frequency or milestone for any delivery event | — | — | — | — | — | **`EXCLUDED`** |

**Teaching warning — `M5-S2-09` to `M5-S2-11`.** The three must be delivered as
one unit. `M5-S2-10` **alone** would be heard as *"five disciplines have not
delivered"*, which the source expressly forbids.

**Recorded correction — `M5-S2-04`.** The provisional central question supplied
to this increment ended *"and by when?"*. **The sources do not support it.**
`S1` §10.5 asks *"for which event"*, not *when*; `S4` records that no dates
exist and that all timing is event-triggered or `TBD`. The question is revised
in `M5-S2-05` and the correction is recorded in §7 hypothesis `H-C1`.

### Slide 3 — Three resources, three questions — and why they are not one RACI

| ID | Statement | Source path | Section | Auth | Governance | Implementation | Class |
|---|---|---|---|---|---|---|---|
| `M5-S3-01` | `S2` answers *"**who performs which information-management function?**"* | `supporting/information-management-responsibility-matrix.md` | §Purpose | 2 | **`PROPOSED GOVERNANCE`** | — | **`SUPPORTING`** |
| `M5-S3-02` | `S3` answers *"**who produces and maintains which information container?**"* | `supporting/model-information-responsibility-matrix.md` | §Purpose | 2 | **`PROPOSED GOVERNANCE`** | — | **`SUPPORTING`** |
| `M5-S3-03` | `S4` answers *what is exchanged, at what event, to whom, why, in what form, and under what conditions* | `supporting/information-delivery-schedule.md` | §Purpose | 2 | **`PROPOSED GOVERNANCE`** | — | **`SUPPORTING`** |
| `M5-S3-04` | **Each resource states what it does not answer**, and the disclaimers are mutual | `S2` §Purpose, §7; `S3` §Purpose; `S4` §Container discipline | — | 2 | **`PROPOSED GOVERNANCE`** | — | **`SUPPORTING`** |
| `M5-S3-05` | **"RACI is not adopted"** | `bep/…BEP.md` §5.12; `supporting/information-management-responsibility-matrix.md` §1 | — | 1, 2 | **`CONTROLLED GOVERNANCE`** | — | **`CONTROLLED`** |
| `M5-S3-06` | Because RACI *"collapses"* checking-from-authorising and coordinating-from-performing — *"distinctions this BEP depends on"* | `bep/…BEP.md` | §5.12 | 1 | **`CONTROLLED GOVERNANCE`** | — | **`CONTROLLED`** |
| `M5-S3-07` | **The word *row* means three different things** — a function, a container, a container-within-an-event | `S2` §3; `S3` §3.1; `S4` §1 | — | 4 | — | — | **`INTERP`** |
| `M5-S3-08` | *"**No container is scheduled that does not exist in that matrix**"* — `S4` consumes `S3`'s refs | `supporting/information-delivery-schedule.md` | §Container discipline | 2 | **`PROPOSED GOVERNANCE`** | — | **`SUPPORTING`** |
| `M5-S3-09` | `S3` defers Author and Checker allocation to `S2` | `supporting/model-information-responsibility-matrix.md` | §3 | 2 | **`PROPOSED GOVERNANCE`** | — | **`SUPPORTING`** |
| `M5-S3-10` | `S4` cites `S2` rows `P4`, `D4` and `D7` **by reference**, and does not duplicate them | `supporting/information-delivery-schedule.md` | §3.2, §4.3, §6 | 2 | **`PROPOSED GOVERNANCE`** | — | **`SUPPORTING`** |
| `M5-S3-11` | **The dependency chain is directional** — `S4` → `S3` → `S2`; nothing depends on `S4` | `S2`, `S3`, `S4` cross-references | — | 4 | — | — | **`INTERP`** |
| `M5-S3-12` | **Overlap is by reference, not duplication** — the detail lives in exactly one place | `S1` §5.12, §7.12, §10.13; `S2` §7 | — | 4 | — | — | **`INTERP`** |
| `M5-S3-13` | **Unresolved** — no source defines the change-propagation route between the three resources, or which is updated first | Recorded gap, found by inspection across `S2`, `S3`, `S4`; `S1` §12.7 `A2` is `TBD` | — | 4 | **`UNRESOLVED`** | — | **`INTERP`** |
| `M5-S3-14` | Cell grammar, codes and their limits | — | — | — | — | — | **`EXCLUDED`** — **Slides 6–8 own it** |
| `M5-S3-15` | Delivery-event structure and the `TRN-E03` block | — | — | — | — | — | **`EXCLUDED`** — **Slides 9–12 own it** |
| `M5-S3-16` | Any combined or simplified single-table view of the three resources | — | — | — | — | — | **`EXCLUDED`** |

### Slide 4 — Who performs which function — the IM Responsibility Matrix

| ID | Statement | Source path | Section | Auth | Governance | Implementation | Class |
|---|---|---|---|---|---|---|---|
| `M5-S4-01` | The matrix *"allocates information-management **functions** to **roles** across the process steps defined by the BEP"* | `supporting/information-management-responsibility-matrix.md` | §Purpose | 2 | **`PROPOSED GOVERNANCE`** | — | **`SUPPORTING`** |
| `M5-S4-02` | It answers one question — *"**who performs which information-management function?**"* | `supporting/information-management-responsibility-matrix.md` | §Purpose | 2 | **`PROPOSED GOVERNANCE`** | — | **`SUPPORTING`** |
| `M5-S4-03` | *"Section 5 defines what each function **means**. The matrix records **how those functions are allocated**… Meaning is defined once, here; allocation is recorded once, there"* | `bep/…BEP.md` | §5.12 | 1 | **`CONTROLLED GOVERNANCE`** | — | **`CONTROLLED`** |
| `M5-S4-04` | **Nine functional-role columns** — `AP`, `LDP`, `BM`, `BC`, `TTL`, `Aut`, `Chk`, `CDE`, `Rcp` | `supporting/information-management-responsibility-matrix.md` | §2, §3 | 2 | **`PROPOSED GOVERNANCE`** | — | **`SUPPORTING`** |
| `M5-S4-05` | **33 process-function rows in seven subject groups** — governance · CDE · information production · sharing and consumption · coordination · delivery and exchange · change and assurance | `supporting/information-management-responsibility-matrix.md` | §3.1–§3.7 | 2 | **`PROPOSED GOVERNANCE`** | — | **`SUPPORTING`** |
| `M5-S4-06` | Allocations are made *"to **functional roles**, not to companies or people. **No organisation is appointed and no individual is named**"* | `supporting/information-management-responsibility-matrix.md` | §Population rule | 2 | **`PROPOSED GOVERNANCE`** | — | **`SUPPORTING`** |
| `M5-S4-07` | *"Functional roles only. **No holder is established for any of them.**"* | `supporting/information-management-responsibility-matrix.md` | §2 | 2 | **`UNRESOLVED`** | — | **`SUPPORTING`** |
| `M5-S4-08` | *"These are **functions, not job titles and not people**"* | `bep/…BEP.md` | §4.6 | 1 | **`CONTROLLED GOVERNANCE`** | — | **`CONTROLLED`** |
| `M5-S4-09` | The role model is *"a **conceptual functional model**, not an appointment chart and **not an organisation chart**"* | `bep/…BEP.md` | §5.2 | 1 | **`CONTROLLED GOVERNANCE`** | — | **`CONTROLLED`** |
| `M5-S4-10` | **Three things it expressly does not answer** — which organisation authors a specific container; what is delivered at each milestone; which individual holds each role | `supporting/information-management-responsibility-matrix.md` | §Purpose | 2 | **`PROPOSED GOVERNANCE`** | — | **`SUPPORTING`** |
| `M5-S4-11` | **The split status rule** — allocations are *"functional governance proposals **unless the BEP already expressly establishes the allocation**"* | `supporting/information-management-responsibility-matrix.md` | §Population rule | 2 | **`PROPOSED GOVERNANCE`** | — | **`SUPPORTING`** |
| `M5-S4-12` | **Expressly established** — the Task-Team Lead, *"or another role explicitly allocated that function by approved governance"*, authorises information from WIP to Shared | `bep/…BEP.md` §9.4; `supporting/information-management-responsibility-matrix.md` `P4` | — | 1, 2 | **`ESTABLISHED ALLOCATION`** | **`IMPLEMENTATION UNVERIFIED`** | **`CONTROLLED`** |
| `M5-S4-13` | **Expressly established as unresolved** — *"The role holding publication and exchange authority is **UNRESOLVED**"* | `bep/…BEP.md` §9.7; `supporting/information-management-responsibility-matrix.md` `D4` | — | 1, 2 | **`UNRESOLVED`** | — | **`CONTROLLED`** |
| `M5-S4-14` | *"Where the BEP records an authority as unresolved, this matrix records it as unresolved **rather than filling it with a plausible role**"* | `supporting/information-management-responsibility-matrix.md` | §Population rule, §6 | 2 | **`UNRESOLVED`** | — | **`SUPPORTING`** |
| `M5-S4-15` | **A populated allocation is not evidence of appointment.** No holder is established for any role, and the model is not an appointment chart | `supporting/information-management-responsibility-matrix.md` §2; `bep/…BEP.md` §5.2, §5.3 | — | 4 | **`UNRESOLVED`** | — | **`INTERP`** |
| `M5-S4-16` | **A populated allocation is not evidence that the activity occurred.** The matrix records what a role holds, not what has been done | `supporting/information-management-responsibility-matrix.md` §5; `docs/Increment-7C-Live-Validation-Record.md` §7 | — | 4 | — | **`IMPLEMENTATION UNVERIFIED`** | **`INTERP`** |
| `M5-S4-17` | *"It does **not** demonstrate that separate people perform them, and **it must not be read as evidence of independence**"* | `supporting/information-management-responsibility-matrix.md` §5; `bep/…BEP.md` §5.11 | — | 2, 1 | **`PROPOSED GOVERNANCE`** | — | **`SUPPORTING`** |
| `M5-S4-18` | The seven function codes and their definitions, combined codes, `TBD` versus `—`, worked rows, `P1`–`P4`, and `D4` / `D7` in detail | — | — | — | — | — | **`EXCLUDED`** — **Slides 6–7 own them** |
| `M5-S4-19` | Separation-of-duty mechanics; coordination workflow mechanics | — | — | — | — | — | **`EXCLUDED`** — **Slide 8 and Module 6 own them** |

**Teaching warning — `M5-S4-11` to `M5-S4-14`.** These four are a set. Delivering
`M5-S4-11` without `M5-S4-12` and `M5-S4-13` leaves the split rule abstract; the
audience needs one allocation the BEP **establishes** and one it **establishes as
unresolved** to see that the rule cuts both ways.

**Teaching warning — `M5-S4-18`.** The codes are visible in any reproduction of
the matrix. **Naming that a code set exists is permitted; defining any code is
not.** If the visual shows cell values, it has left Slide 4.

### Slide 5 — Who produces which container — the Model / Information Responsibility Matrix

| ID | Statement | Source path | Section | Auth | Governance | Implementation | Class |
|---|---|---|---|---|---|---|---|
| `M5-S5-01` | The matrix *"records which party and task team is intended to produce and maintain each information container or container class"* | `supporting/model-information-responsibility-matrix.md` | §Purpose | 2 | **`PROPOSED GOVERNANCE`** | — | **`SUPPORTING`** |
| `M5-S5-02` | It answers one question — *"**who produces and maintains which information container?**"* | `supporting/model-information-responsibility-matrix.md` | §Purpose | 2 | **`PROPOSED GOVERNANCE`** | — | **`SUPPORTING`** |
| `M5-S5-03` | **Origination follows one chain** — `party → task team → discipline → information container` | `bep/…BEP.md` | §7.2 | 1 | **`CONTROLLED GOVERNANCE`** | — | **`CONTROLLED`** |
| `M5-S5-04` | *"**Originator responsibility remains with the producing task team**, through sharing, consumption, coordination and publication. **No downstream act relieves it**"* | `bep/…BEP.md` | §7.2 | 1 | **`CONTROLLED GOVERNANCE`** | — | **`CONTROLLED`** |
| `M5-S5-05` | *"**Authorship is not inferred from folder location.** Where a container sits tells you where it sits. The originator is **recorded, not deduced**"* | `bep/…BEP.md` | §7.2 | 1 | **`CONTROLLED GOVERNANCE`** | — | **`CONTROLLED`** |
| `M5-S5-06` | **Six discipline design / coordination containers** — `ARC-01`, `STR-01`, `MEC-01`, `ELE-01`, `PLM-01`, `FIR-01` | `supporting/model-information-responsibility-matrix.md` | §3.1 | 2 | **`PROPOSED GOVERNANCE`** | — | **`SUPPORTING`** |
| `M5-S5-07` | **`COORD-01` is recorded separately** as multidisciplinary coordination information, not as a seventh discipline container | `supporting/model-information-responsibility-matrix.md` | §3.4 | 2 | **`PROPOSED GOVERNANCE`** | — | **`SUPPORTING`** |
| `M5-S5-08` | *"Mechanical, Electrical and Plumbing are task teams and disciplines that may sit within a **single MEP Consultant organisation**"* — three task teams, **one party** | `bep/…BEP.md` §4.3; `supporting/model-information-responsibility-matrix.md` §2 | — | 1, 2 | **`CONTROLLED GOVERNANCE`** | — | **`CONTROLLED`** |
| `M5-S5-09` | *"**Fire is separate from MEP.**… the Fire Consultant is a distinct party, **not an MEP sub-team**"* | `bep/…BEP.md` §4.3; `supporting/model-information-responsibility-matrix.md` §2 | — | 1, 2 | **`CONTROLLED GOVERNANCE`** | — | **`CONTROLLED`** |
| `M5-S5-10` | *"A discipline code identifies the **information domain** of a container. **That is all it does.**"* It does not identify the organisation, the task team, the author, a Design Collaboration team, or contractual responsibility | `bep/…BEP.md` | §4.4 | 1 | **`CONTROLLED GOVERNANCE`** | — | **`CONTROLLED`** |
| `M5-S5-11` | **Five concepts, deliberately not interchangeable** — party · task team · discipline · Autodesk collaboration team · IM role. *"a mapping is **not an identity**"* | `bep/…BEP.md` | §4.2 | 1 | **`CONTROLLED GOVERNANCE`** | — | **`CONTROLLED`** |
| `M5-S5-12` | **Every §3 allocation is classified `PROPOSED GOVERNANCE`**, derived from the training organisation model **`TA-03`** | `supporting/model-information-responsibility-matrix.md` §Classification; `supporting/governance-decision-register.md` `TA-03` | — | 2 | **`PROPOSED GOVERNANCE`** | — | **`SUPPORTING`** |
| `M5-S5-13` | **Intended governance, not live inventory** — *"It is **not** an inventory of what currently exists in the CDE"* | `supporting/model-information-responsibility-matrix.md` | §Intended governance | 2 | **`PROPOSED GOVERNANCE`** | **`IMPLEMENTATION UNVERIFIED`** | **`SUPPORTING`** |
| `M5-S5-14` | `ARC-01` has a live equivalent observed; the other five were **not observed as live direct coordination inputs at the inspected level**. *"Absence of observation is not observation of absence"* | `docs/Increment-7C-Live-Validation-Record.md` §7; `supporting/governance-decision-register.md` `OF-002` | — | 3 | — | **`OBSERVED — QUALIFIED`** / **`NOT DEMONSTRATED`** | **`DECISION-RECORD`** |
| `M5-S5-15` | **No format is mandated.** *"Observed use does not make RVT mandatory for any task team or any container"*; RVT, IFC, PDF and NWC appear in observed context only | `supporting/model-information-responsibility-matrix.md` §3.2; `bep/…BEP.md` §10.8, §11.9 | — | 2, 1 | **`UNRESOLVED`** | — | **`SUPPORTING`** |
| `M5-S5-16` | **Level of information need — `Not defined`** for any container, and *"**not** assumed from discipline convention or inferred from observed model content"* | `supporting/model-information-responsibility-matrix.md` | §4 | 2 | **`UNRESOLVED`** | — | **`SUPPORTING`** |
| `M5-S5-17` | **All Lead entries are Task-Team Lead, holder `TBD`**; contributors are Authors and Checkers **allocated through the IM Responsibility Matrix**, not here | `supporting/model-information-responsibility-matrix.md` | §3 | 2 | **`UNRESOLVED`** | — | **`SUPPORTING`** |
| `M5-S5-18` | **`COORD-01` is a coordination construct** — it does **not** merge authorship, transfer technical ownership, create a new design author, or become a deliverable *"unless and until it is scheduled as one… through an explicit decision"* | `supporting/model-information-responsibility-matrix.md` | §3.4 | 2 | **`PROPOSED GOVERNANCE`** | — | **`SUPPORTING`** |
| `M5-S5-19` | **Three things it expressly does not answer** — information-management process functions; delivery events, formats and timing; level of information need | `supporting/model-information-responsibility-matrix.md` | §Purpose, §1, §3, §4 | 2 | **`PROPOSED GOVERNANCE`** | — | **`SUPPORTING`** |
| `M5-S5-20` | **Trade and contractor containers are a *recorded future extension*, not missing data to be invented now** | `supporting/model-information-responsibility-matrix.md` | §5 | 2 | **`PLANNED`** | — | **`SUPPORTING`** |
| `M5-S5-21` | Federation mechanics and the coordination cycle | — | — | — | — | — | **`EXCLUDED`** — **Module 6 owns them** |
| `M5-S5-22` | Container dependencies and interfaces; exchange scheduling; delivery-event fields; format selection | — | — | — | — | — | **`EXCLUDED`** — **Slides 9–12 and Module 6 own them** |

**Teaching warning — `M5-S5-14`.** As on Slide 2, the observed and unobserved
halves must be delivered together, with the absence-of-observation line attached.
**`ARC-01`'s observation does not prove the matrix as a whole is implemented**,
and the five unobserved containers are not evidence of anything.

**Teaching warning — `M5-S5-08` / `M5-S5-09` / `M5-S5-10`.** These three defuse
the module's most likely organisational misreading. **`S1` §4.4 is the governing
statement**, not `S3` §2 — the matrix applies a rule the BEP sets.

---

## 6. Terminology register — exact controlled wording

**Recorded, not harmonised.** The full variance analysis is in
[`resource-comparison.md`](resource-comparison.md) §7.

| Term | Governing definition | Exact wording |
|---|---|---|
| **Perform** | `S1` §5.12 | *"Carries out the activity"* |
| **Check** | `S1` §5.12 | *"Verifies against a defined requirement"* |
| **Authorise** | `S1` §5.12 | *"Permits progression, for a defined purpose"* |
| **Coordinate** | `S1` §5.12 | *"Organises across parties or task teams"* |
| **Accept** | `S1` §5.12 | *"Receives for an identified purpose"* |
| **Consult** | `S1` §5.12 | *"Is asked before the act"* |
| **Inform** | `S1` §5.12 | *"Is told after the act"* |
| **`TBD`** | `S2` §1 | *"Allocation unresolved. The BEP records this authority as not established."* |
| **`—`** | `S2` §1 | *"The role holds no function in this activity."* |
| **Published** | `S1` §10.11 | *"Authorised for a defined purpose and placed in the authorised state"* |
| **Delivered** | `S1` §10.11 | *"Sent to an identified recipient for an identified purpose"* |
| **Received** | `S1` §10.11 | *"Arrived with, and was registered by, the recipient"* |
| **Accepted** | `S1` §10.11 | *"Acknowledged by the recipient as suitable for the stated purpose"* |
| **Information container** | `S1` §10.4 | *"A delivery is not synonymous with a file"*; one exchange may carry several |
| **Originator responsibility** | `S1` §7.2 | *"remains with the producing task team… **No downstream act relieves it**"* |

### 6.1 Variances carried into every slide

| # | Variance | Position |
|---|---|---|
| **1** | **Unresolved markers differ.** `S2` defines `TBD`; `S3` uses `TBD`, `Not defined`, `UNRESOLVED — TBD`; `S4` uses `TBD`, `Not established`, `Not defined` | **Recorded. Not harmonised.** Only `S2` publishes a legend |
| **2** | **The same authority gap is classified two ways.** `S2`/`S3` say *unresolved*; `S4` says **`BLOCKED`** | Both correct — they classify different objects. **Neither is rewritten** |
| **3** | ***Purpose*** means the container's purpose in `S3` and the exchange's purpose in `S4` | Two objects, one word |
| **4** | ***Status*** in `S4` is the status **of the schedule entry**, not of a delivery | Frequently misread |
| **5** | ***Publication*** means project information publication (`S1` §9.7) **and** the training-baseline publication arrangement (`PAD-001`) | **Two unrelated senses.** See [`source-inventory.md`](source-inventory.md) §5 |
| **6** | ***Lead*** is a role column in `S2`, a lead function in `S3`, and an approved field in `S4` | `S4`'s is the defined field |
| **7** | **Identifier collision** — `S2`'s sharing rows are numbered `S1`, `S2`, `S3` | Module 5 always writes *"the IM matrix sharing rows"* |

---

## 7. Hypothesis register

The roadmap (`S15`) pre-declares Module 5 content, and this increment was
supplied with sixteen proposed distinctions. **Every one is tested here against
the controlled sources.** `S15` decides nothing.

### 7.1 The pre-declared grammar terms

| ID | Hypothesis | Classification | Source basis and reasoning |
|---|---|---|---|
| `H-G1` | **Perform / Check / Authorise / Coordinate / Accept / Consult / Inform** is the Harrismith responsibility grammar | **`CONFIRMED`** | `S1` §5.12 defines all seven and states *"the matrix will use these terms and no others"*. `S2` §1 implements them as `P`, `Ck`, `Au`, `Co`, `Ac`, `Cs`, `In` |
| `H-G2` | The grammar applies across the three resources | **`SOURCE-SPECIFIC` — `REJECTED` for `S3` and `S4`** | The codes exist **only in `S2`**. `S3` uses parties, task teams and prose; `S4` uses sixteen named fields. **Teaching the codes as schedule or container vocabulary would be wrong** |
| `H-G3` | The grammar has seven values | **`CONFIRMED WITH QUALIFICATION`** | **Seven *function* codes plus two non-function values** — `TBD` and `—`. `S15`'s list omits both, and **they are the values that carry the unresolved matters.** Codes also combine (`P Co`, `P Ck`, `TBD Ac`) |
| `H-G4` | **Container allocation** is Module 5 content | **`CONFIRMED`** | `S3` §3.1 allocates `ARC-01`–`FIR-01`; §3.4 records `COORD-01` |
| `H-G5` | **Delivery events** are Module 5 content | **`CONFIRMED`** | `S4` §2 defines `TRN-E01`, `TRN-E02`, `TRN-E03` |
| `H-G6` | **Delivery purpose** is Module 5 content | **`CONFIRMED`** | *Purpose* is an approved field (`S1` §10.13) and is populated for all three events |
| `H-G7` | **Suitability** is Module 5 content | **`CONFIRMED WITH QUALIFICATION`** | *State / Suitability* is an approved field, and `TRN-E01`/`TRN-E02` carry *"Shared — coordination use only"*. **But no suitability code set exists** (`S5` §19, carried from Module 4). The concept is governed; the coding is not |

### 7.2 The sixteen proposed distinctions

| ID | Distinction | Classification | Source basis and reasoning |
|---|---|---|---|
| `H-D1` | Role responsibility **vs** information responsibility | **`CONFIRMED`** | `S2` allocates functions to roles; `S3` allocates containers to parties and task teams. Each expressly disclaims the other |
| `H-D2` | Information-management function **vs** technical authorship | **`CONFIRMED`** | `S2` §Purpose excludes *"which organisation authors each specific model"*; `S1` §7.2 holds authorship |
| `H-D3` | Producing **vs** checking | **`CONFIRMED`** | `S2` `P1` (`Aut` **P**) vs `P2`/`P3` (`Chk` **Ck**); `S2` §4 — the Author does not hold *"self-authorisation of own work"* |
| `H-D4` | Checking **vs** authorising | **`CONFIRMED`** | `S1` §9.3 — *"Checking does not automatically authorise sharing"*; `S2` `P2`/`P3` note — *"**Check is not Authorise**"* |
| `H-D5` | Authorising a transition **vs** accepting delivery | **`CONFIRMED`** | `S1` §9.4/§9.7 vs §9.8; `S2` `D4` vs `D7` — separate rows, both `TBD`. `S5` classifies `T4` as a **state transition** and `T7` as a **decision/status** |
| `H-D6` | Responsibility matrix **vs** delivery schedule | **`CONFIRMED`** | All three resources cross-declare their boundaries |
| `H-D7` | Responsibility allocation **vs** evidence of performance | **`CONFIRMED`** | `S2` §5 — *"must not be read as evidence of independence"*; `S3` — *"not an inventory of what currently exists"*; `S9` §7 |
| `H-D8` | Planned delivery **vs** completed delivery | **`CONFIRMED`** | `S4` §What these entries are not; §4.2 — *"An unactivated row is **not a pending exchange**"* |
| `H-D9` | Deliverable **vs** information container | **`CONFIRMED WITH QUALIFICATION`** | `S1` §10.4 — *"A delivery is not synonymous with a file"*; one exchange may carry several containers. **Qualification:** `S1` §10.4 also records *"This BEP does not define the project's final deliverable list"*, and `S4` §5.2 records the `TRN-E03` deliverable set as **not defined** |
| `H-D10` | Delivery event **vs** information-state transition | **`CONFIRMED`** | `S4`'s `TRN-E01`–`TRN-E03` vs `S5`'s `T1`–`T8`. Carried from Module 4: **`TRN-E03` exercises or depends upon `T4`; it is not `T4`**. `TRN-E01` *requires* `T1` — an event may depend on a transition without being one |
| `H-D11` | Blank field **vs** not applicable | **`CONFIRMED WITH QUALIFICATION` — and the premise is corrected** | The distinction is real: `S2` defines `—` as *"The role holds no function in this activity"*, and `S3` uses `Not applicable` exactly once (`COORD-01` originating party). **But no controlled Harrismith matrix or schedule contains a blank cell.** Every absence is typed. **Module 5 must not present Harrismith as having blanks to interpret** |
| `H-D12` | Unresolved field **vs** missing formatting | **`NOT ESTABLISHED`** | **No source records any field as a formatting artefact or placeholder.** Since nothing is blank (`H-D11`), no Harrismith instance exists. May be named **only** as a general reading hazard, labelled `SYNTH` — never as a Harrismith condition |
| `H-D13` | Assigned role **vs** named person | **`CONFIRMED`** | `S2` §2 — *"Functional roles only. **No holder is established for any of them.**"*; §Population rule — *"not to companies or people"*; `S7` `TA-02` |
| `H-D14` | Governance function **vs** platform permission | **`CONFIRMED`** | `S2` `C2`/`C3` note — *"Platform permission is not authority to share, publish or accept"*; `S1` §1.5, §9.7; `S9` §9, §11 — *"platform role ≠ professional appointment ≠ governance authority"* |
| `H-D15` | Originator responsibility **vs** recipient use | **`CONFIRMED`** | `S1` §7.2 — *"**No downstream act relieves it**"*; `S2` `S3`-row note; `S4` §3.2 — the receiver's decision *"does not approve the design"* |
| `H-D16` | Schedule entry **vs** live transaction | **`CONFIRMED`** | `S4` §Classification and §4.2; `S9` §7 — only `TRN-E01`'s Architecture row is demonstrable |

### 7.3 The central question

| ID | Hypothesis | Classification | Source basis and reasoning |
|---|---|---|---|
| `H-C1` | *"Who is responsible for producing which information, for whom, for what purpose, **and by when**?"* | **`CONFIRMED WITH QUALIFICATION` — revised** | Three clauses hold. **"By when" does not.** `S1` §10.5 asks *"for which **event**"*; `S4` §2 gives every event *"Event-triggered / `TBD`"* and §7 records *"**No real delivery dates or client milestones have been established.**"* Retaining *by when* would imply a programme that does not exist. **Also incomplete:** the provisional wording omits four of `S1` §10.5's eight fields — format, required checks, required authorisation and dependencies |
| `H-C2` | The revised question — *which information must be produced, by which task team, for which event and recipient, for what purpose, and under which checks and authorisation?* | **`INTERP` — adopted** | Derived from `S1` §10.5 and `S4` §1. **Labelled as interpretation; the sources do not phrase it as a single question** |

### 7.4 Roadmap correction required

`S15` line 207 pre-declares Module 5 as *"The
Perform/Check/Authorise/Coordinate/Accept/Consult/Inform grammar; container
allocation; delivery events, purpose and suitability"*.

**Findings:** the grammar is **`CONFIRMED`** (`H-G1`) — but the entry is
**incomplete and, read alone, misleading**, because it omits `TBD` and `—`
(`H-G3`) and does not record that the grammar applies to **`S2` only**
(`H-G2`). The roadmap is corrected accordingly in T5-A.

---

## 8. Module-wide unresolved register

**Nothing in this register is resolved by Module 5.**

### 8.1 Unresolved authorities — 4

| # | Matter | Recorded in | Status |
|---|---|---|---|
| 1 | **Publication / exchange authority** | `S1` §9.7; `S2` `D4`; `S3` §6; `S4` §5.1 | **UNRESOLVED — TBD.** Not held by the BIM Manager, BIM Coordinator, CDE Administrator or Architect |
| 2 | **Recipient acceptance authority** | `S1` §9.8, §10.11; `S2` `D7`; `S3` §6; `S4` §5.1 | **UNRESOLVED — TBD / recipient-dependent** |
| 3 | **Governance change approval authority** | `S1` §12.7; `S2` `A2` | **UNRESOLVED — TBD by change class.** *"No single universal approver exists"* |
| 4 | **`UD-001` decision owner** | `S7` `UD-001` | **Not established** |

### 8.2 Unresolved role holders — 5

| # | Matter | Status |
|---|---|---|
| 1 | Owner / Appointing Party identity | **Not established — TBD** (`S1` §2.3, §5.3) |
| 2 | Lead Delivery Party holder | **TBD** (`S1` §5.4, §10.6) |
| 3 | BIM Manager, BIM Coordinator, CDE Administration holders | **TBD** (`S1` §5.5, §5.6, §5.9) |
| 4 | Task-Team Lead holders — **every** task team | **TBD** (`S1` §5.7) |
| 5 | `Rcp` — recipient function | **Not established**; *"depends on the exchange"* |

### 8.3 Unresolved planning inputs — 6

| # | Matter | Status |
|---|---|---|
| 1 | Client / project information requirements | **None available** (`S1` §7.3, §10.2) |
| 2 | Real delivery milestones and dates | **None established.** All timing event-triggered or `TBD` |
| 3 | Level of information need | **Not defined** for any container (`S3` §4) |
| 4 | Authoring and exchange formats | **TBD** — no approved standard (`S3` §6; `S4` §7; `OF-003`) |
| 5 | Naming and container identification | **TBD** — no Naming Standard exists (`S1` §11.3; `S12`) |
| 6 | Final deliverable set | **Not defined** (`S1` §10.4; `S4` §5.2) |

### 8.4 Blocked — 1

| # | Matter | Status |
|---|---|---|
| 1 | **`TRN-E03`** | **PROPOSED — BLOCKED PENDING GOVERNANCE DECISIONS**, on **five** independent matters. **`T4` remains blocked; information remains Shared** |

### 8.5 Unverified implementation — 4

| # | Matter | Status |
|---|---|---|
| 1 | `STR-01`, `MEC-01`, `ELE-01`, `PLM-01`, `FIR-01` as live coordination inputs | **`NOT DEMONSTRATED`** at the inspected level (`S9` §7) |
| 2 | `COORD-01` | **Partially demonstrable** — environment exists, no federated version (`S9` §7) |
| 3 | `TRN-E02` reshare cycle | **No controlled affected-container reshare cycle demonstrated** (`S9` §7) |
| 4 | **`GCR-006`** — one complete governed coordination cycle | **OPEN.** *"PARTIALLY TRACEABLE / NOT YET DEMONSTRATED AS A COMPLETE CYCLE"* (`S9` §8) |

### 8.6 Unresolved relationships between the resources — 1

| # | Matter | Status |
|---|---|---|
| 1 | Change-propagation route between `S2`, `S3` and `S4` | **No source defines it.** `S4` requires containers to exist in `S3`; **no source defines the reverse dependency or which resource is updated first.** `A2` is `TBD` |

---

## 9. Prohibited claims

**Fifty-nine claims Module 5 may not make.** Grouped by the error each would
commit. Claims 51–59 were added in **T5-B**.

### 9.1 Collapsing the three resources — 6

| # | Prohibited claim |
|---|---|
| 1 | That the three principal resources are, or can be shown as, **one generic RACI matrix** |
| 2 | That RACI is the Harrismith grammar, or that `P`/`Ck`/`Au` map onto R/A/C/I |
| 3 | That `S2`'s codes apply to `S3` container rows or `S4` schedule rows |
| 4 | That the three resources sit at **one status level** |
| 5 | That **every** `S2` allocation is proposed, or that **every** `S2` allocation is established — the split rule is not simplified in either direction |
| 6 | That a single combined table can replace the three resources without loss |

### 9.2 Manufacturing authority — 9

| # | Prohibited claim |
|---|---|
| 7 | That a **role title** automatically creates authority |
| 8 | That a **platform permission** creates governance authority |
| 9 | That **producer equals checker** |
| 10 | That **checker equals authoriser** |
| 11 | That **authoriser equals accepter** |
| 12 | That **publication authority equals acceptance authority** |
| 13 | That an Author may **self-authorise** their own work |
| 14 | That the BIM Manager, BIM Coordinator, CDE Administrator, Architect or Lead Delivery Party holds publication authority |
| 15 | That a **named role is a named person**, or that any role holder is established |

### 9.3 Confusing planning with performance — 8

| # | Prohibited claim |
|---|---|
| 16 | That a **schedule proves delivery occurred** |
| 17 | That a **planned deliverable has been published** |
| 18 | That a **populated cell proves performance** |
| 19 | That a matrix demonstrates **independence** between Author and Checker |
| 20 | That an **unactivated `TRN-E02` row is a pending exchange**, or that a task team owes anything against it |
| 21 | That `TRN-E02` means **all six disciplines reshare** in every coordination cycle |
| 22 | That the **complete workflow is operating live** |
| 23 | That `S9`'s observations prove any discipline is **absent, uncommitted or inactive** |

### 9.4 Collapsing the delivery states — 5

| # | Prohibited claim |
|---|---|
| 24 | That **Published equals Delivered** |
| 25 | That **Delivered equals Received** |
| 26 | That **Received equals Accepted** |
| 27 | That a **delivery event is automatically an information-state transition** |
| 28 | That a transmission record **is** the information, or that a transmittal is technical approval |

### 9.5 Filling gaps — 10

| # | Prohibited claim |
|---|---|
| 29 | That a **blank is automatically an error** |
| 30 | That an **unresolved field is merely missing formatting** |
| 31 | That the Harrismith matrices or schedule **contain blank fields** — they do not |
| 32 | That **`TBD` and `—` mean the same thing** |
| 33 | That **`TRN-E03` is complete**, or that any of its five blocking matters has been resolved |
| 34 | That resolving publication authority **alone** would complete `TRN-E03` |
| 35 | That **`T4` is unblocked** |
| 36 | That information has **moved beyond Shared** |
| 37 | That a **level of information need** is defined for any container |
| 38 | That a naming, identifier or format convention exists |

### 9.6 Misreading the organisation — 6

| # | Prohibited claim |
|---|---|
| 39 | That six discipline codes imply **six organisations** |
| 40 | That MEC, ELE and PLM are **three companies** |
| 41 | That FIR is an **MEP sub-team** |
| 42 | That a responsibility matrix is an **organisational chart** |
| 43 | That the `Rcp` column is an organisation |
| 44 | That **trade or contractor containers are missing data** to be invented now |

### 9.7 Source-specific traps found in T5-A — 6

| # | Prohibited claim |
|---|---|
| 45 | That **`PAD-001`, `PM-1`–`PM-7` or any publication-arrangement approval resolves `D4`, unblocks `T4`, or releases `TRN-E03`.** They concern the **training-baseline publication arrangement only** |
| 46 | That `AD-001` established project publication authority, acceptance authority or any project standard |
| 47 | That **`COORD-01`** is a jointly-authored model, creates a new design author, transfers technical ownership, or is a project deliverable |
| 48 | That **RVT, IFC, PDF or NWC is a mandated format** — observed use is not a delivery requirement |
| 49 | That **`UD-001` has been corrected**, or that any replacement team-space mapping is proposed or implied |
| 50 | That coordinator verification is **design approval**, or that a receiver's consumption decision approves the design |

### 9.8 Additional prohibitions recorded in T5-B — 9

| # | Prohibited claim |
|---|---|
| 51 | That **a function is a person**, or that a functional role is a named holder. *"These are functions, not job titles and not people"* (`S1` §4.6) |
| 52 | That a **populated allocation proves appointment**. No holder is established for any role, and the role model is *"not an appointment chart"* (`S1` §5.2; `S2` §2) |
| 53 | That **all allocations within the IM Responsibility Matrix share one governance status.** The split rule makes each a proposal **unless the BEP expressly establishes it** (`S2` §Population rule) |
| 54 | That the **two matrices are one matrix**, that either is subordinate to the other, or that a combined matrix could serve both. They are complementary **by reference, not duplication** |
| 55 | That a **discipline code identifies** an organisation, a task team, an author, a Design Collaboration team or contractual responsibility. *"That is all it does"* (`S1` §4.4) |
| 56 | That **every planned container exists**, or that the Model / Information Responsibility Matrix is a **live CDE inventory** (`S3` §Intended governance) |
| 57 | That **originator responsibility transfers downstream** — to a checker, coordinator, recipient or accepter. *"No downstream act relieves it"* (`S1` §7.2) |
| 58 | That **authorship can be inferred from folder location** (`S1` §7.2) |
| 59 | That a **mapping between party, task team, discipline, platform team and IM role is an identity**. *"a mapping is not an identity"* (`S1` §4.2) |

### 9.9 Programme-status claims — required in every increment

| # | Prohibited claim |
|---|---|
| A | That a **PowerPoint is tracked in this repository** — none is, in any module |
| B | That **presentation timing has been measured** — it is **`20.0 minutes allocated — not measured`** |
| C | That **Module 6 mechanics have been completed**, or that Module 5 teaches them |
| D | That Slides 4–14 are developed — **they are architecture only** |

---

## 10. Module-boundary deferrals

### 10.1 Deferred to Module 6 — Coordination, review, approval and assurance

Module 5 may **identify that a function is required**. It must not teach the
function's operational workflow.

| Deferred | Where Module 5 stops |
|---|---|
| Coordination-cycle mechanics | Module 5 names `TRN-E01`/`TRN-E02` as **delivery events** and stops |
| Model federation | Module 5 records `COORD-01` as an **allocated coordination class** and stops |
| Clash detection, findings, triage, escalation | Module 5 names `X1`–`X5` as **allocated functions** and stops |
| Issue assignment and closure | Not taught. `S6` owns it |
| Technical review procedures | Module 5 names *Checking Requirement* as a **field** and stops |
| Approval workflow mechanics | Module 5 names *Authorisation Requirement* as a **field** and stops |
| Assurance sampling and coordination evidence | Not taught |
| Complete review and acceptance cycles | Module 5 records `GCR-006` as **open** and stops |

**Test to apply when developing Slides 4–14:** if a slide explains **how a
coordination run is performed, how a finding is triaged, how an Issue is closed,
or how a review is conducted**, it has left Module 5.

### 10.2 Retained by Module 4

State definitions, the eight controlled steps, `T1`/`T4` classification, gate and
evidence concepts, and the five container properties. Module 5 cites them as
**carry-forward**, and does not re-teach them.

### 10.3 Deferred to Module 7

Which Harrismith allocations transfer to Triviron, and which are Harrismith
decisions. Slide 14 poses the questions; it answers none.

### 10.4 Deferred within Module 5

| Deferred to | Content |
|---|---|
| ~~T5-B~~ | ~~Responsibility-matrix purposes and distinctions — Slides 4–5~~ — **COMPLETE** |
| **T5-C** | Matrix-cell grammar and allocation boundaries — Slides 6–8 |
| **T5-D** | Delivery events and schedule construction — Slides 9–12 |
| **T5-E** | Slides 13–14 and the complete content baseline |
| **T5-F** | Visual specifications and visual-source set |
| **T5-G** | Presentation assembly package |
| **T5-H** | External PowerPoint production — **outside this repository** |

---

## 11. Status

| Field | Value |
|---|---|
| Increment | **T5-B** |
| Slides classified | **1–5.** **84 statements** |
| Slides 6–14 | **Architecture only** — no classified statements |
| Registers | **Six** — source authority, terminology, hypothesis, unresolved, prohibited claims, boundary deferrals |
| Hypotheses tested | **25** — `H-G1`–`H-G7`, `H-D1`–`H-D16`, `H-C1`–`H-C2`. **Unchanged in T5-B** |
| Prohibited claims | **59**, plus 4 standing programme-status prohibitions |
| Classification scheme | **Reconciled in T5-B** — `SYNTH` redefined; `M5-S2-14` reclassified `INTERP`. See §5.1 |
| Timing | **`20.0 minutes allocated — not measured`** |
| Outstanding | **T5-C** — Slides 6–8 — and later increments |
