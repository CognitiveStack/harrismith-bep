# Module 5 — Source Map, Registers and Prohibited Claims

**Status:** Traceability record for teaching material. **Not governance.**

Statement-level classification for **all fourteen slides** — developed across
increments **T5-A** (1–3), **T5-B** (4–5), **T5-C** (6–8), **T5-D** (9–12) and
**T5-E** (13–14) — plus the terminology register, the hypothesis register, the
unresolved register, the prohibited claims, the Module 6 and Module 7 deferrals,
and the **module-wide final reconciliation** (§12).

**The Module 5 teaching-content baseline is complete.** No slide remains
architecture only. **The visual specifications are complete and accepted**
(`M5V-01`–`M5V-14`,
[`visual-demonstration-plan.md`](visual-demonstration-plan.md)) and the **visual
sources are complete** (`M05-S01`–`M05-S14` in
[`../assets/module-05/`](../assets/module-05/), with a visual register and a
slide-visual map). **The presentation assembly package is complete** —
[`presentation/`](presentation/), seven PowerPoint-production handoff files
(T5-G). **The external PowerPoint has been produced and accepted at `REV01`**
(`T5-H`, corrected in `T5-H-R1`); **it is not committed to this repository**.
**No rendered asset exists**, and none is claimed.

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
| Visual specification and sources | — | — | **Teaching-production controls, not governance.** Controlling plan [`visual-demonstration-plan.md`](visual-demonstration-plan.md) (`M5V-01`–`M5V-14`); sources `M05-S01`–`M05-S14`. **Both complete. They add no Harrismith authority** |

---

## 5. Statement classification — all fourteen slides

**267 statements. 52 `CONTROLLED`, 125 `SUPPORTING`, 10 `DECISION-RECORD`,
3 `MODULE-2-4`, 4 `TEACHING-PLAN`, 49 `INTERP`, 1 `SYNTH`, 23 `EXCLUDED`.**

| Slide | Statements | `CTRL` | `SUPP` | `DEC` | `M2-4` | `PLAN` | `INT` | `SYN` | `EXC` |
|---|---:|---:|---:|---:|---:|---:|---:|---:|---:|
| 1 | 12 | 3 | 3 | 2 | 2 | 1 | 0 | 0 | 1 |
| 2 | 15 | 3 | 3 | 5 | 0 | 0 | 3 | 0 | 1 |
| 3 | 16 | 2 | 7 | 0 | 0 | 0 | 4 | 0 | 3 |
| 4 | 19 | 5 | 10 | 0 | 0 | 0 | 2 | 0 | 2 |
| 5 | 22 | 7 | 12 | 1 | 0 | 0 | 0 | 0 | 2 |
| 6 | 20 | 14 | 3 | 0 | 0 | 0 | 2 | 0 | 1 |
| 7 | 20 | 2 | 8 | 0 | 0 | 0 | 8 | 0 | 2 |
| 8 | 17 | 8 | 5 | 0 | 0 | 0 | 3 | 0 | 1 |
| 9 | 22 | 4 | 15 | 0 | 0 | 0 | 2 | 0 | 1 |
| 10 | 20 | 0 | 17 | 0 | 0 | 0 | 1 | 0 | 2 |
| 11 | 22 | 1 | 14 | 0 | 1 | 0 | 4 | 0 | 2 |
| 12 | 20 | 1 | 12 | 2 | 0 | 0 | 3 | 0 | 2 |
| **13** | **20** | **0** | **11** | **0** | **0** | **0** | **8** | **0** | **1** |
| **14** | **22** | **2** | **5** | **0** | **0** | **3** | **9** | **1** | **2** |
| **Total** | **267** | **52** | **125** | **10** | **3** | **4** | **49** | **1** | **23** |

**All fourteen slides are classified.** No slide remains architecture only.

**Eight observations — recalculated from the final table in T5-E.**

**Slide 10 carries the most `SUPPORTING` statements — 17 of 20.** All three
delivery-event concepts are `S4`'s own construction, and the schedule describes
them itself. **Slide 3 is second at 7 of 16**, for the same reason in a different
place: the three resources define themselves *by contrast with each other*, so
very little interpretation is needed to keep them apart.

**Slide 6 carries the most `CONTROLLED` statements — 14 of 20.** Every one of the
seven function terms is defined verbatim in `S1` §5.12, and the refusal of RACI
is stated twice over. **The vocabulary slide needs almost no interpretation,
because the BEP wrote the vocabulary.** **Slide 5 is second at 7 of 22** — the
organisational traps it defuses are defined in `S1` §4.2, §4.3 and §4.4, and the
container matrix applies them.

**Slide 2 carries five of the module's ten `DECISION-RECORD` statements**,
because the *allocation ≠ performance* distinction rests on `S9` — the only
source in the inventory that looked at the live environment. **Slide 12 carries
the other two**, where the `TRN-E03` block rests on `AD-001`'s explicit
non-effects.

**Slide 14 carries the most `INTERP` statements — 9 of 22 — and Slides 7 and 13
follow at 8 each.** All three are slides where the work is reading rather than
quoting: reading a cell, reading an absence, and reading what a project would
have to decide. **Every one of those `INTERP` statements cites the sources its
construction rests on.**

**Two slides carry no `CONTROLLED` statement — 10 and 13.** The BEP creates no
delivery events and publishes no absence vocabulary; both subjects belong
entirely to the supporting resources. That is the correct profile, and it is
recorded rather than disguised.

**The module contains exactly one `SYNTH` statement — `M5-S14-14`.** It is a
closing framing line on the transfer slide, it cites no source, and it is
labelled as presenter framing. **Every other statement across all fourteen
slides either cites a source or is expressly `EXCLUDED`.**

**`SUPPORTING` outweighs `CONTROLLED` roughly two to one — 125 against 52.**
That is the expected shape for a module whose subject is three supporting
resources. **The BEP defines the vocabulary and the principles; the matrices and
the schedule do the allocating and the scheduling**, and Module 5 spends most of
its time in the second layer.

**23 statements are `EXCLUDED`** — material considered and deliberately kept off
the slides, most of it deferred to Slides that own it, to Module 6 or to
Module 7.

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

**Effect on totals at T5-B.** `INTERP` 6 → **9** (one from this reclassification,
two added on Slide 4); `SYNTH` 1 → **0**. **No count was changed to reach a
preferred figure**, and no other statement was reclassified.

**Position at the completed baseline.** The module ran from T5-B to T5-D with
**zero `SYNTH` statements**, because every statement written in those increments
cited a source. **T5-E introduced exactly one** — `M5-S14-14`, the closing
framing line on the transfer slide, which cites nothing and is labelled presenter
framing. **It was not manufactured to populate the class**, and no other
statement was reclassified to accommodate it.

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

### Slide 6 — The seven-term grammar, and the two values that carry the gaps

| ID | Statement | Source path | Section | Auth | Governance | Implementation | Class |
|---|---|---|---|---|---|---|---|
| `M5-S6-01` | **The approved responsibility grammar has seven terms**, defined by the BEP and implemented as codes by the matrix | `bep/…BEP.md` §5.12; `supporting/information-management-responsibility-matrix.md` §1 | — | 1, 2 | **`CONTROLLED GOVERNANCE`** | — | **`CONTROLLED`** |
| `M5-S6-02` | **`P` Perform** — *"Carries out the activity"* | `bep/…BEP.md` | §5.12 | 1 | **`CONTROLLED GOVERNANCE`** | — | **`CONTROLLED`** |
| `M5-S6-03` | **`Ck` Check** — *"Verifies against a defined requirement"* | `bep/…BEP.md` | §5.12 | 1 | **`CONTROLLED GOVERNANCE`** | — | **`CONTROLLED`** |
| `M5-S6-04` | **`Au` Authorise** — *"Permits progression, for a defined purpose"* | `bep/…BEP.md` | §5.12 | 1 | **`CONTROLLED GOVERNANCE`** | — | **`CONTROLLED`** |
| `M5-S6-05` | **`Co` Coordinate** — *"Organises across parties or task teams"* | `bep/…BEP.md` | §5.12 | 1 | **`CONTROLLED GOVERNANCE`** | — | **`CONTROLLED`** |
| `M5-S6-06` | **`Ac` Accept** — *"Receives for an identified purpose"* | `bep/…BEP.md` | §5.12 | 1 | **`CONTROLLED GOVERNANCE`** | — | **`CONTROLLED`** |
| `M5-S6-07` | **`Cs` Consult** — *"Is asked before the act"* | `bep/…BEP.md` | §5.12 | 1 | **`CONTROLLED GOVERNANCE`** | — | **`CONTROLLED`** |
| `M5-S6-08` | **`In` Inform** — *"Is told after the act"* | `bep/…BEP.md` | §5.12 | 1 | **`CONTROLLED GOVERNANCE`** | — | **`CONTROLLED`** |
| `M5-S6-09` | *"The matrix will use these terms **and no others**"* | `bep/…BEP.md` | §5.12 | 1 | **`CONTROLLED GOVERNANCE`** | — | **`CONTROLLED`** |
| `M5-S6-10` | **`TBD`** — *"Allocation unresolved. The BEP records this authority as **not established**."* | `supporting/information-management-responsibility-matrix.md` | §1 | 2 | **`UNRESOLVED`** | — | **`SUPPORTING`** |
| `M5-S6-11` | **`—`** — *"The role holds **no function in this activity**."* | `supporting/information-management-responsibility-matrix.md` | §1 | 2 | **`PROPOSED GOVERNANCE`** | — | **`SUPPORTING`** |
| `M5-S6-12` | **`TBD` and `—` are not function codes, and they are not equivalent.** One records an unresolved allocation; the other records a role with no part in the activity | `supporting/information-management-responsibility-matrix.md` §1 — the two are separately defined | — | 4 | — | — | **`INTERP`** |
| `M5-S6-13` | **"RACI is not adopted."** Stated independently in both sources | `bep/…BEP.md` §5.12; `supporting/information-management-responsibility-matrix.md` §1 | — | 1, 2 | **`CONTROLLED GOVERNANCE`** | — | **`CONTROLLED`** |
| `M5-S6-14` | The recorded reason — RACI *"collapses"* **checking from authorising** and **coordinating from performing**, *"distinctions this BEP depends on"* | `bep/…BEP.md` | §5.12 | 1 | **`CONTROLLED GOVERNANCE`** | — | **`CONTROLLED`** |
| `M5-S6-15` | *"RACI is **not to be introduced unless explicitly approved later**"* | `bep/…BEP.md` | §5.12 | 1 | **`CONTROLLED GOVERNANCE`** | — | **`CONTROLLED`** |
| `M5-S6-16` | **Verification is recorded as `Ck`** — *"since verification is checking against a defined requirement"* | `supporting/information-management-responsibility-matrix.md` | §1 | 2 | **`PROPOSED GOVERNANCE`** | — | **`SUPPORTING`** |
| `M5-S6-17` | **The grammar belongs to the IM Responsibility Matrix alone.** The codes appear in no other resource; the container matrix uses parties and task teams, the schedule uses sixteen named fields | `supporting/information-management-responsibility-matrix.md` §1; `supporting/model-information-responsibility-matrix.md` §3; `supporting/information-delivery-schedule.md` §1 | — | 4 | — | — | **`INTERP`** |
| `M5-S6-18` | **A second, different vocabulary exists and is not the grammar.** `S1` §9.2 defines a **decision terminology** — Check · Review · Authorise · Accept · Reject · Coordinate — which **adds** *Review* and *Reject* and **omits** Perform, Consult and Inform. *"These terms are not collapsed into 'approval'"* | `bep/…BEP.md` | §9.2 | 1 | **`CONTROLLED GOVERNANCE`** | — | **`CONTROLLED`** |
| `M5-S6-19` | The grammar records **functions** — *"not job titles and not people"* — and *"**Authority comes from governance.** Not from platform access, permission or configuration"* | `bep/…BEP.md` | §4.6, §9.1 | 1 | **`CONTROLLED GOVERNANCE`** | — | **`CONTROLLED`** |
| `M5-S6-20` | Any mapping of a code to R, A, C or I; any invented code; any suitability, status or naming code | — | — | — | — | — | **`EXCLUDED`** |

**Teaching warning — `M5-S6-18`.** The two vocabularies are **recorded, not
harmonised**. If the audience hears *Review* or *Reject* and looks for a code,
say plainly that the grammar has no code for either — they belong to `S1` §9.2's
decision terminology, which serves a different purpose.

### Slide 7 — Reading a cell: what a populated cell does and does not prove

| ID | Statement | Source path | Section | Auth | Governance | Implementation | Class |
|---|---|---|---|---|---|---|---|
| `M5-S7-01` | **A cell is the intersection of one information-management activity row and one functional-role column** | `supporting/information-management-responsibility-matrix.md` §3 — structure by inspection | — | 4 | — | — | **`INTERP`** |
| `M5-S7-02` | **A populated cell records which function or functions that role holds in that activity** — and nothing further | `supporting/information-management-responsibility-matrix.md` §1, §3 | — | 4 | **`PROPOSED GOVERNANCE`** | — | **`INTERP`** |
| `M5-S7-03` | **33 rows × 9 columns = 297 cells, and not one is blank.** Every cell carries a code, `TBD`, or `—` | `supporting/information-management-responsibility-matrix.md` §3.1–§3.7 — **census by inspection** | — | 4 | — | — | **`INTERP`** |
| `M5-S7-04` | **The census** — `—` 131 · `Cs` 69 · `In` 34 · `P` 18 · `Co` 13 · `TBD` 10 · `Ck` 10 · `P Co` 5 · `P Ck` 2 · `Au` 2 · `TBD Ac` 1 · `P Cs` 1 · `Co Ck` 1 | `supporting/information-management-responsibility-matrix.md` §3.1–§3.7 — **census by inspection** | — | 4 | — | — | **`INTERP`** |
| `M5-S7-05` | **One cell may record more than one function.** `P Co`, `P Ck`, `P Cs`, `Co Ck` and `TBD Ac` all occur | `supporting/information-management-responsibility-matrix.md` | §3.1–§3.7 | 2 | **`PROPOSED GOVERNANCE`** | — | **`SUPPORTING`** |
| `M5-S7-06` | **A combined value records no sequence, priority, chronology, hierarchy, competence, separate people or successful performance.** No source states an order between codes in a cell | none states an ordering — **recorded absence** | — | 4 | — | — | **`INTERP`** |
| `M5-S7-07` | **`P1` Author information in WIP** — Author **`P`**, Task-Team Lead `Co`; every other role `—` | `supporting/information-management-responsibility-matrix.md` | §3.3 | 2 | **`PROPOSED GOVERNANCE`** | **`IMPLEMENTATION UNVERIFIED`** | **`SUPPORTING`** |
| `M5-S7-08` | **`P2` task-team technical / content check** — Checker **`Ck`**, Task-Team Lead **`Co Ck`**, Author `Cs` | `supporting/information-management-responsibility-matrix.md` | §3.3 | 2 | **`PROPOSED GOVERNANCE`** | **`IMPLEMENTATION UNVERIFIED`** | **`SUPPORTING`** |
| `M5-S7-09` | **`P3` information-quality / readiness check** — Checker **`Ck`**; BIM Manager and BIM Coordinator `Cs` | `supporting/information-management-responsibility-matrix.md` | §3.3 | 2 | **`PROPOSED GOVERNANCE`** | **`IMPLEMENTATION UNVERIFIED`** | **`SUPPORTING`** |
| `M5-S7-10` | **`P4` authorise WIP information for controlled sharing** — Task-Team Lead **`Au`** | `supporting/information-management-responsibility-matrix.md` §3.3; `bep/…BEP.md` §9.4 | — | 2, 1 | **`ESTABLISHED ALLOCATION`** | **`IMPLEMENTATION UNVERIFIED`** | **`SUPPORTING`** |
| `M5-S7-11` | *"An Author does **not** self-authorise merely because they authored the information"* | `supporting/information-management-responsibility-matrix.md` §3.3 `P1`/`P4` note; `bep/…BEP.md` §5.8 | — | 2, 1 | **`CONTROLLED GOVERNANCE`** | — | **`SUPPORTING`** |
| `M5-S7-12` | *"**Check is not Authorise.** Checking confirms readiness for the next controlled decision; **it does not permit progression**"* | `supporting/information-management-responsibility-matrix.md` §3.3 `P2`/`P3` note; `bep/…BEP.md` §9.3 | — | 2, 1 | **`CONTROLLED GOVERNANCE`** | — | **`SUPPORTING`** |
| `M5-S7-13` | **`Au` appears exactly twice in 297 cells** — at `P4`, and at the IM matrix sharing row allocating authorisation to consume or reference Shared information for a stated purpose. **Both are held by the Task-Team Lead** | `supporting/information-management-responsibility-matrix.md` §3.3, §3.4 — **census by inspection** | — | 4 | **`PROPOSED GOVERNANCE`** | — | **`INTERP`** |
| `M5-S7-14` | **`Ac` appears once, and only inside `TBD Ac`.** **No acceptance allocation is resolved anywhere in the matrix** | `supporting/information-management-responsibility-matrix.md` §3.6 `D7` — **census by inspection** | — | 4 | **`UNRESOLVED`** | — | **`INTERP`** |
| `M5-S7-15` | **`TBD Ac` at `D7`** — acceptance is the relevant function at that cell, **the allocation and the authority remain unresolved**, and the value proves **no exchange has been accepted** | `supporting/information-management-responsibility-matrix.md` §3.6 `D7` note; `bep/…BEP.md` §9.8, §10.11 | — | 2, 1 | **`UNRESOLVED`** | **`NOT DEMONSTRATED`** | **`SUPPORTING`** |
| `M5-S7-16` | **`P4` and `D4` carry different authority statuses.** `P4` is expressly established by `S1` §9.4. In `D4`, **AP, LDP, BM, BC and TTL are `TBD`; Aut, Chk, CDE and Rcp are `—`** — five unresolved cells and four resolved no-function cells. **Publication / exchange authority remains unresolved and no allocation is made** | `bep/…BEP.md` §9.4, §9.7; `supporting/information-management-responsibility-matrix.md` §1, §3.3, §3.6 | — | 1, 2 | **`ESTABLISHED ALLOCATION`** / **`UNRESOLVED`** | — | **`CONTROLLED`** |
| `M5-S7-17` | **A populated cell does not record** the holder's name · that anyone was appointed · that the activity occurred · that a check was independent · authority beyond the exact function recorded · competence · contractual authority · platform permission · completion | `supporting/information-management-responsibility-matrix.md` §2, §5; `bep/…BEP.md` §5.2, §9.1 | — | 4 | — | **`IMPLEMENTATION UNVERIFIED`** | **`INTERP`** |
| `M5-S7-18` | *"**Authority comes from governance.** Not from platform access, permission or configuration"* | `bep/…BEP.md` | §9.1 | 1 | **`CONTROLLED GOVERNANCE`** | — | **`CONTROLLED`** |
| `M5-S7-19` | Approval workflow mechanics; CDE transition detail; `TRN-E03`; recipient acceptance mechanics; a full technical-review procedure | — | — | — | — | — | **`EXCLUDED`** — **Module 4, Slides 9–12 and Module 6 own them** |
| `M5-S7-20` | Completing `D4`, `D7` or `A2` | — | — | — | — | — | **`EXCLUDED`** |

**Teaching warning — `M5-S7-03` / `M5-S7-04` / `M5-S7-13` / `M5-S7-14`.** These
four are **counts produced by inspecting the matrix**, not statements any source
makes. They are classified `INTERP` and **must be presented as observations about
the document**, not as governance. Their value is that they are checkable: anyone
can open the matrix and count.

**Teaching warning — `M5-S7-16`.** `D4` is shown **only** to demonstrate the
status boundary. **No `D4` cell may be completed, and no publication or delivery
mechanic may be taught here.**

### Slide 8 — One person, two roles — allocation is not independence

| ID | Statement | Source path | Section | Auth | Governance | Implementation | Class |
|---|---|---|---|---|---|---|---|
| `M5-S8-01` | *"**One participant may hold more than one role** in this training implementation"* | `supporting/information-management-responsibility-matrix.md` §5; `bep/…BEP.md` §5.11, §9.12 | — | 2, 1 | **`PROPOSED GOVERNANCE`** | — | **`SUPPORTING`** |
| `M5-S8-02` | *"**Combining roles does not combine the functions.** The responsibilities remain distinct in meaning"* | `bep/…BEP.md` | §5.11 | 1 | **`CONTROLLED GOVERNANCE`** | — | **`CONTROLLED`** |
| `M5-S8-03` | *"A participant performing two functions must know **which function they are performing at each decision point**"* | `bep/…BEP.md` | §5.11, §9.12 | 1 | **`CONTROLLED GOVERNANCE`** | — | **`CONTROLLED`** |
| `M5-S8-04` | Author and Checker may be performed by the same participant *"**where independence cannot reasonably be provided**"* | `bep/…BEP.md` | §5.8 | 1 | **`CONTROLLED GOVERNANCE`** | — | **`CONTROLLED`** |
| `M5-S8-05` | *"**self-checking is still a checking act with a defined requirement, not an omission of one**"* | `bep/…BEP.md` | §5.8 | 1 | **`CONTROLLED GOVERNANCE`** | — | **`CONTROLLED`** |
| `M5-S8-06` | *"the combination is **recorded**, so the limitation is **visible in the evidence**"* | `bep/…BEP.md` | §5.8 | 1 | **`CONTROLLED GOVERNANCE`** | — | **`CONTROLLED`** |
| `M5-S8-07` | *"**Independence is never claimed where it does not exist**"*; *"**Independent checking is not claimed where it did not occur.** Where one participant performed both the authoring and the checking, the record says so"* | `bep/…BEP.md` | §5.8, §9.12 | 1 | **`CONTROLLED GOVERNANCE`** | — | **`CONTROLLED`** |
| `M5-S8-08` | *"**Fictional independence is worse than an acknowledged limitation**, because it removes the reader's ability to weigh the information"* — **Harrismith supporting-resource wording, not an external standard** | `supporting/information-management-responsibility-matrix.md` | §5 | 2 | **`PROPOSED GOVERNANCE`** | — | **`SUPPORTING`** |
| `M5-S8-09` | The BEP's parallel formulation — *"An overstated independence claim is more damaging than an acknowledged limitation, because it **removes the reader's ability to weigh the evidence**"* | `bep/…BEP.md` | §9.12 | 1 | **`CONTROLLED GOVERNANCE`** | — | **`CONTROLLED`** |
| `M5-S8-10` | The matrix *"does **not** demonstrate that separate people perform them, and **it must not be read as evidence of independence**"* | `supporting/information-management-responsibility-matrix.md` | §5 | 2 | **`PROPOSED GOVERNANCE`** | — | **`SUPPORTING`** |
| `M5-S8-11` | **Separate Author and Checker *columns* do not establish separate *people*.** A column is a functional role; a role is not a headcount | `supporting/information-management-responsibility-matrix.md` §2, §5; `bep/…BEP.md` §4.6 | — | 4 | — | — | **`INTERP`** |
| `M5-S8-12` | **`TA-02`** — participants may exercise defined roles for training purposes; *"**Doing so creates no real professional authority, contractual appointment, duty or liability**"* | `supporting/governance-decision-register.md` | `TA-02` | 2 | **`TRAINING ASSUMPTION`** | — | **`SUPPORTING`** |
| `M5-S8-13` | **Role combination is not automatically a defect**, a non-conformance, evidence of inadequate competence, or evidence that checking did not occur | `bep/…BEP.md` §5.8, §5.11 — the combination is expressly permitted and recorded | — | 4 | — | — | **`INTERP`** |
| `M5-S8-14` | **No `NON-CONFORMANCE` entry is recorded** in the register, and *"**none is asserted or recorded**"* | `supporting/governance-decision-register.md` | §Classification vocabulary | 2 | **`PROPOSED GOVERNANCE`** | — | **`SUPPORTING`** |
| `M5-S8-15` | *"**Delegation must be explicit**"*; *"**Platform permission does not constitute delegation**"* | `bep/…BEP.md` | §5.11, §9.12 | 1 | **`CONTROLLED GOVERNANCE`** | — | **`CONTROLLED`** |
| `M5-S8-16` | **The degree of independence changes how the evidence should be weighed** — which is why the limitation is recorded rather than obscured | `bep/…BEP.md` §5.8, §9.12; `supporting/information-management-responsibility-matrix.md` §5 | — | 4 | — | — | **`INTERP`** |
| `M5-S8-17` | Assurance sampling; independence requirements for a real appointment; professional certification; technical or design approval; competence assessment; a complete review procedure; a remedy for insufficient independence | — | — | — | — | — | **`EXCLUDED`** — **Module 6 and future project-specific governance own them** |

**Teaching warning — `M5-S8-08`.** Deliver this as **Harrismith's own recorded
position**, attributed to the supporting resource. It is not a universal
professional standard and must not be presented as one. `M5-S8-09` is the BEP's
parallel wording and may be used alongside it.

**Teaching warning — `M5-S8-13` / `M5-S8-14`.** Together these stop the slide
tipping into criticism. **The sources permit role combination and record no
non-conformance.** Slide 8 explains a limitation on what the evidence proves — it
does not allege a failing.

### Slide 9 — The Information Delivery Schedule — sixteen fields

| ID | Statement | Source path | Section | Auth | Governance | Implementation | Class |
|---|---|---|---|---|---|---|---|
| `M5-S9-01` | The schedule *"records what information is exchanged, at what event, to whom, why, in what form, and under what checking, authorisation and acceptance conditions"* | `supporting/information-delivery-schedule.md` | §Purpose | 2 | **`PROPOSED GOVERNANCE`** | — | **`SUPPORTING`** |
| `M5-S9-02` | It is *"a **controlled training delivery-planning instrument**. It is **not a contractual programme**"* | `supporting/information-delivery-schedule.md` | §Purpose | 2 | **`PROPOSED GOVERNANCE`** | — | **`SUPPORTING`** |
| `M5-S9-03` | **The sixteen fields are approved by the BEP** — the schedule *"will include fields equivalent to"* the list at `S1` §10.13 | `bep/…BEP.md` | §10.13 | 1 | **`CONTROLLED GOVERNANCE`** | — | **`CONTROLLED`** |
| `M5-S9-04` | **All sixteen field definitions, verbatim** — Delivery ID · Exchange / Milestone · Information Container · Originating Party · Task Team · Discipline · Lead · Recipient · Purpose · Format · State / Suitability · Checking Requirement · Authorisation Requirement · Acceptance Criteria · Status · Dependencies | `supporting/information-delivery-schedule.md` | §1 | 2 | **`PROPOSED GOVERNANCE`** | — | **`SUPPORTING`** |
| `M5-S9-05` | **Teaching grouping** — the sixteen fields grouped by the question each answers: identity and event · origin and responsibility · recipient and purpose · form and permitted use · checks and decisions · status and dependencies | none — **teaching grouping only**; `S4` §1 presents one flat list | — | 4 | — | — | **`INTERP`** |
| `M5-S9-06` | **`Delivery ID`** — *"Identifier for a scheduled container row"*. *"`TRN-E01-ARC` and similar are internal references for this exercise. They are **not** contractual document numbers and carry no project numbering convention — **no Naming Standard exists**"* | `supporting/information-delivery-schedule.md` §1; `bep/…BEP.md` §11.3 | — | 2, 1 | **`UNRESOLVED`** | — | **`SUPPORTING`** |
| `M5-S9-07` | **`Exchange / Milestone`** — *"The event the row belongs to"*. An **event concept**, not necessarily a contractual milestone | `supporting/information-delivery-schedule.md` | §1, §2 | 2 | **`PROPOSED GOVERNANCE`** | — | **`SUPPORTING`** |
| `M5-S9-08` | **`Status`** — *"**Status of the schedule entry itself**"*. **Not the information state, and not proof that a delivery completed** | `supporting/information-delivery-schedule.md` | §1, §What these entries are not | 2 | **`PROPOSED GOVERNANCE`** | — | **`SUPPORTING`** |
| `M5-S9-09` | **`State / Suitability`** — *"CDE state and what the information may be used for"* | `supporting/information-delivery-schedule.md` §1; `bep/…BEP.md` §6.8 | — | 2, 1 | **`CONTROLLED GOVERNANCE`** | — | **`SUPPORTING`** |
| `M5-S9-10` | **`Format`** — *"Delivery format"*. A requirement field whose value **may remain `TBD`**; *"No format is mandated"* | `supporting/information-delivery-schedule.md` | §1, §3.2 | 2 | **`UNRESOLVED`** | — | **`SUPPORTING`** |
| `M5-S9-11` | **`Acceptance Criteria`** — *"Process-level criteria for receipt"*. **It does not establish who holds acceptance authority**, which remains `UNRESOLVED — TBD` | `supporting/information-delivery-schedule.md` | §1, §6, §7 | 2 | **`UNRESOLVED`** | — | **`SUPPORTING`** |
| `M5-S9-12` | **`Lead`** — *"Role leading the exchange for that container"*. Every populated `Lead` reads **Task-Team Lead (`TBD`)** — a role, **not a named person** | `supporting/information-delivery-schedule.md` | §1, §3.1, §4.3 | 2 | **`UNRESOLVED`** | — | **`SUPPORTING`** |
| `M5-S9-13` | **`Recipient`** — *"Who receives it"*. **It does not establish an appointing party**; no appointing party has been established | `supporting/information-delivery-schedule.md` §1; `bep/…BEP.md` §2.3, §5.3 | — | 2, 1 | **`UNRESOLVED`** | — | **`SUPPORTING`** |
| `M5-S9-14` | **All entries are classified `PROPOSED GOVERNANCE` / training delivery planning.** They are *"**not** contractual milestones and **not** client information requirements"* | `supporting/information-delivery-schedule.md` | §Classification | 2 | **`PROPOSED GOVERNANCE`** | — | **`SUPPORTING`** |
| `M5-S9-15` | The entries are *"**not evidence** of"* — real client information requirements · contractual delivery milestones · actual consultant appointments · construction programme dates | `supporting/information-delivery-schedule.md` | §What these entries are not | 2 | **`PROPOSED GOVERNANCE`** | — | **`SUPPORTING`** |
| `M5-S9-16` | *"**No real delivery dates or client milestones have been established.**"* Timing is **event-triggered or `TBD`** | `supporting/information-delivery-schedule.md` | §Population rule, §2, §7 | 2 | **`UNRESOLVED`** | — | **`SUPPORTING`** |
| `M5-S9-17` | **No formal information requirements are available** to this implementation — no EIR, AIR or equivalent. *"**None are invented here.**"* | `bep/…BEP.md` §7.3, §10.2; `supporting/information-delivery-schedule.md` §What these entries are not | — | 1, 2 | **`UNRESOLVED`** | — | **`CONTROLLED`** |
| `M5-S9-18` | **Precedence** — *"Should real project information requirements later become available, **they take precedence** over anything developed in their absence"* | `bep/…BEP.md` §1.5; `supporting/information-delivery-schedule.md` §Precedence | — | 1 | **`CONTROLLED GOVERNANCE`** | — | **`CONTROLLED`** |
| `M5-S9-19` | *"This BEP does **not** define the project's final deliverable list"* | `bep/…BEP.md` | §10.4 | 1 | **`UNRESOLVED`** | — | **`CONTROLLED`** |
| `M5-S9-20` | **Container discipline** — *"Every scheduled discipline container references an existing container ref from `model-information-responsibility-matrix.md`. **No container is scheduled that does not exist in that matrix**"* | `supporting/information-delivery-schedule.md` | §Container discipline | 2 | **`PROPOSED GOVERNANCE`** | — | **`SUPPORTING`** |
| `M5-S9-21` | **A schedule row is a planning entry, not a transaction record.** It does not prove an exchange occurred, that a recipient received anything, or that anything was accepted | `supporting/information-delivery-schedule.md` §Classification, §What these entries are not; `S9` §7 | — | 4 | **`PROPOSED GOVERNANCE`** | **`NOT DEMONSTRATED`** | **`INTERP`** |
| `M5-S9-22` | The three delivery events, their statuses, and the `TRN-E03` block | — | — | — | — | — | **`EXCLUDED`** — **Slides 10–12 own them** |

**Teaching warning — `M5-S9-05`.** The grouping is a **teaching device**, not
schedule structure. `S4` §1 presents one flat list of sixteen. **All sixteen
controlled names must remain visible on the slide**, and none may be merged,
renamed or dropped.

### Slide 10 — Three delivery events — proposed, conditional, blocked

| ID | Statement | Source path | Section | Auth | Governance | Implementation | Class |
|---|---|---|---|---|---|---|---|
| `M5-S10-01` | **Three restrained training event concepts.** *"This is **not** a full project delivery schedule"* | `supporting/information-delivery-schedule.md` | §2 | 2 | **`PROPOSED GOVERNANCE`** | — | **`SUPPORTING`** |
| `M5-S10-02` | **`TRN-E01`** — Design coordination share · Timing **event-triggered / `TBD`** · Status **`PROPOSED`** | `supporting/information-delivery-schedule.md` | §2, §3 | 2 | **`PROPOSED GOVERNANCE`** | — | **`SUPPORTING`** |
| `M5-S10-03` | `TRN-E01` State **Shared**; Suitability **"Coordination use only"** | `supporting/information-delivery-schedule.md` | §3 | 2 | **`PROPOSED GOVERNANCE`** | — | **`SUPPORTING`** |
| `M5-S10-04` | *"Each discipline container is shared **from its own originating task team**. The six rows below are **six separate exchanges, not one jointly-owned model**"* | `supporting/information-delivery-schedule.md` | §3 | 2 | **`PROPOSED GOVERNANCE`** | — | **`SUPPORTING`** |
| `M5-S10-05` | `TRN-E01` Authorisation Requirement — **Task-Team Lead authorisation to share** | `supporting/information-delivery-schedule.md` §3.2; `bep/…BEP.md` §9.4; IM matrix `P4` | — | 2, 1 | **`ESTABLISHED ALLOCATION`** | **`IMPLEMENTATION UNVERIFIED`** | **`SUPPORTING`** |
| `M5-S10-06` | `TRN-E01` Format — *"**TBD by approved format requirement. No format is mandated.**"* | `supporting/information-delivery-schedule.md` | §3.2 | 2 | **`UNRESOLVED`** | — | **`SUPPORTING`** |
| `M5-S10-07` | *"Information shared under `TRN-E01` is **not** construction-ready, **not** formally accepted design, and **not** record information"* | `supporting/information-delivery-schedule.md` | §3.2 | 2 | **`PROPOSED GOVERNANCE`** | — | **`SUPPORTING`** |
| `M5-S10-08` | **`TRN-E02`** — Coordination reshare / resolution update · Timing **after required resolution, event-triggered / `TBD`** · Status **`PROPOSED` — conditional**, activated per affected container only | `supporting/information-delivery-schedule.md` | §2, §4 | 2 | **`CONDITIONAL`** | — | **`SUPPORTING`** |
| `M5-S10-09` | *"**Repeatable and conditional** — **no calendar frequency**"* | `supporting/information-delivery-schedule.md` | §2, §4 | 2 | **`CONDITIONAL`** | — | **`SUPPORTING`** |
| `M5-S10-10` | The six `TRN-E02` rows are *"**template rows, not active deliveries**"*, each activated *"only when its own container requires controlled rework and reshare"* | `supporting/information-delivery-schedule.md` | §4.2 | 2 | **`CONDITIONAL`** | — | **`SUPPORTING`** |
| `M5-S10-11` | *"An unactivated row is **not a pending exchange** and carries **no expectation that the task team will produce anything**"* | `supporting/information-delivery-schedule.md` | §4.2 | 2 | **`CONDITIONAL`** | — | **`SUPPORTING`** |
| `M5-S10-12` | *"A cycle may activate **one container, several, or none**"* | `supporting/information-delivery-schedule.md` | §4 | 2 | **`CONDITIONAL`** | — | **`SUPPORTING`** |
| `M5-S10-13` | *"The existence of this event does **not** mean all six disciplines reshare during every coordination cycle"* | `supporting/information-delivery-schedule.md` | §4 | 2 | **`CONDITIONAL`** | — | **`SUPPORTING`** |
| `M5-S10-14` | **`TRN-E03`** — Controlled design review / project-facing exchange · Timing **`TBD`** · Status **`PROPOSED — BLOCKED PENDING GOVERNANCE DECISIONS`** | `supporting/information-delivery-schedule.md` | §2, §5 | 2 | **`BLOCKED`** | — | **`SUPPORTING`** |
| `M5-S10-15` | *"**This is not evidence of a real project milestone.**"* | `supporting/information-delivery-schedule.md` | §5 | 2 | **`BLOCKED`** | — | **`SUPPORTING`** |
| `M5-S10-16` | **The three statuses mean three different things** — `PROPOSED` is planned governance, not an executed exchange; `CONDITIONAL` activates only on its stated trigger; `BLOCKED` cannot proceed while required governance or inputs remain unresolved | `S4` §2, §4.2, §5.1 — **synthesised across the three event records** | — | 4 | — | — | **`INTERP`** |
| `M5-S10-17` | *"**No calendar dates, frequencies or contractual milestones exist for any event.**"* | `supporting/information-delivery-schedule.md` | §2 | 2 | **`UNRESOLVED`** | — | **`SUPPORTING`** |
| `M5-S10-18` | **Blocked is not rejected, overdue or unfinished** — *"An entry that cannot proceed **is recorded as blocked**"* | `supporting/information-delivery-schedule.md` | §5.1 | 2 | **`BLOCKED`** | — | **`SUPPORTING`** |
| `M5-S10-19` | The five `TRN-E03` blocking matters in detail | — | — | — | — | — | **`EXCLUDED`** — **Slide 12 owns them** |
| `M5-S10-20` | The mapping of each event onto controlled workflow steps | — | — | — | — | — | **`EXCLUDED`** — **Slide 11 owns it** |

**Teaching warning — `M5-S10-10` to `M5-S10-13`.** These four are a set. **A
template row obliges nobody.** Presenting the six `TRN-E02` rows without them
produces the module's most likely delivery misreading — that six reshares are
pending.

### Slide 11 — A delivery event is not an information-state transition

| ID | Statement | Source path | Section | Auth | Governance | Implementation | Class |
|---|---|---|---|---|---|---|---|
| `M5-S11-01` | *"Of the eight steps below, **only `T1` and `T4` are information-state transitions**. `T8` returns information to the originator's WIP for rework"* | `supporting/cde-workflow-state-strategy.md` | §3 | 2 | **`PROPOSED GOVERNANCE`** | — | **`SUPPORTING`** |
| `M5-S11-02` | **The eight steps are four different kinds of object** — state transition · receiving-team action · use / context · event · decision / status · rework | `supporting/cde-workflow-state-strategy.md` | §3.1 | 2 | **`PROPOSED GOVERNANCE`** | — | **`SUPPORTING`** |
| `M5-S11-03` | **`T2`** — receiving-team **action**, *"not a state transition"*; state **Shared — unchanged** | `supporting/cde-workflow-state-strategy.md` | §3.1 | 2 | **`PROPOSED GOVERNANCE`** | — | **`SUPPORTING`** |
| `M5-S11-04` | **`T3`** — **use / context**, *"not a state transition"*; state **Shared — unchanged** | `supporting/cde-workflow-state-strategy.md` | §3.1 | 2 | **`PROPOSED GOVERNANCE`** | — | **`SUPPORTING`** |
| `M5-S11-05` | **`T5`** — **Event**; *"A **Delivered** event is recorded"*; state **Published / Authorised — unchanged** | `supporting/cde-workflow-state-strategy.md` | §3.1 | 2 | **`PROPOSED GOVERNANCE`** | — | **`SUPPORTING`** |
| `M5-S11-06` | **`T6`** — **Event**; *"A **Receipt** event is recorded"*; state **unchanged** | `supporting/cde-workflow-state-strategy.md` | §3.1 | 2 | **`PROPOSED GOVERNANCE`** | — | **`SUPPORTING`** |
| `M5-S11-07` | **`T7`** — **Decision / status**; an acceptance or rejection **status** is recorded against that purpose; state **unchanged**. *"Not technical approval; no transfer of responsibility"* | `supporting/cde-workflow-state-strategy.md` | §3.1 | 2 | **`PROPOSED GOVERNANCE`** | — | **`SUPPORTING`** |
| `M5-S11-08` | **Delivered, Received and Accepted are not information states.** `T5`, `T6` and `T7` each leave the state **unchanged** — they record an event or a status | `supporting/cde-workflow-state-strategy.md` §3.1 — the *"unchanged"* column | — | 4 | **`PROPOSED GOVERNANCE`** | — | **`INTERP`** |
| `M5-S11-09` | **The four distinct objects** — **Published** *"Authorised for a defined purpose and placed in the authorised state"* · **Delivered** *"Sent to an identified recipient for an identified purpose"* · **Received** *"Arrived with, and was registered by, the recipient"* · **Accepted** *"Acknowledged by the recipient as suitable for the stated purpose"* | `bep/…BEP.md` | §10.11 | 1 | **`CONTROLLED GOVERNANCE`** | — | **`CONTROLLED`** |
| `M5-S11-10` | **`TRN-E01` transitions used — `T1` (WIP → Shared), then `T3` (Shared → coordination input).** State reached: **Shared** | `supporting/cde-workflow-state-strategy.md` | §9 | 2 | **`PROPOSED GOVERNANCE`** | — | **`SUPPORTING`** |
| `M5-S11-11` | **`TRN-E01` is not `T1`.** It is a delivery-event concept that **requires** the `T1` route | `S4` §3; `S5` §9 — the event *uses* the transition | — | 4 | **`PROPOSED GOVERNANCE`** | — | **`INTERP`** |
| `M5-S11-12` | The `TRN-E01` route — `WIP → check → Task-Team Lead authorises share → Shared → coordination input` | `supporting/cde-workflow-state-strategy.md` | §9 | 2 | **`PROPOSED GOVERNANCE`** | **`IMPLEMENTATION UNVERIFIED`** | **`SUPPORTING`** |
| `M5-S11-13` | **`TRN-E02` transitions used — `T8` (rework), then `T1` and `T3` again.** Activation *"per affected container only"*; frequency *"None"* | `supporting/cde-workflow-state-strategy.md` | §10 | 2 | **`CONDITIONAL`** | — | **`SUPPORTING`** |
| `M5-S11-14` | The `TRN-E02` lifecycle — `coordination finding → originating task-team WIP → correction → check → authorise share → Shared → re-coordinate → verify` | `supporting/cde-workflow-state-strategy.md` §10; `supporting/information-delivery-schedule.md` §4.1 | — | 2 | **`CONDITIONAL`** | — | **`SUPPORTING`** |
| `M5-S11-15` | **`TRN-E02` is neither `T8` nor `T1`.** It is an event that uses the rework route and then the share route | `S5` §10 — the event *uses* both transitions | — | 4 | **`CONDITIONAL`** | — | **`INTERP`** |
| `M5-S11-16` | *"**The originating task team performs the technical correction**, in its own WIP, through its own checking route. The shared instance is **never edited in place** as an uncontrolled workaround"* | `supporting/cde-workflow-state-strategy.md` §10; `bep/…BEP.md` §7.10 | — | 2, 1 | **`PROPOSED GOVERNANCE`** | — | **`SUPPORTING`** |
| `M5-S11-17` | **`TRN-E03` exercises or depends upon `T4` — it is not `T4`.** Established in Module 4 and carried forward | `../module-04-cde-workflows-and-information-states/source-map.md` §7.2; `S5` §11 | — | 4 | **`BLOCKED`** | — | **`MODULE-2-4`** |
| `M5-S11-18` | **`T4` is the Shared → Published / Authorised state transition**, requiring delivery review then publication / exchange authorisation — performing function **`UNRESOLVED — TBD`** | `supporting/cde-workflow-state-strategy.md` §3.1, §3.2; `bep/…BEP.md` §9.7 | — | 2, 1 | **`UNRESOLVED`** | — | **`SUPPORTING`** |
| `M5-S11-19` | *"Transition **`T4`** therefore has **no available authorising function**, and information remains **Shared**"* | `supporting/cde-workflow-state-strategy.md` | §11, §3.3 | 2 | **`BLOCKED`** | **`NOT DEMONSTRATED`** | **`SUPPORTING`** |
| `M5-S11-20` | **An event may require, depend upon or exercise a transition without being that transition.** Information state, workflow event, recipient action and decision status are **four separate dimensions** | `S5` §3, §3.1, §9–§11 — **synthesised across the mappings** | — | 4 | — | — | **`INTERP`** |
| `M5-S11-21` | Issue-triage, coordination-resolution and verification mechanics | — | — | — | — | — | **`EXCLUDED`** — **Module 6 owns them** |
| `M5-S11-22` | Any mandatory `TRN-E01 → TRN-E02 → TRN-E03` sequence; any depiction of `T1`–`T8` as eight sequential state transitions; any Delivered, Received or Accepted **state** | — | — | — | — | — | **`EXCLUDED`** |

**Teaching warning — `M5-S11-05` to `M5-S11-08`.** `T5`, `T6` and `T7` are the
easiest place in the module to invent a state. **The source's "unchanged" column
is the evidence** — Published / Authorised is the last state reached, and
delivery, receipt and acceptance record events and statuses against it.

### Slide 12 — Why `TRN-E03` is blocked — five matters, not one

| ID | Statement | Source path | Section | Auth | Governance | Implementation | Class |
|---|---|---|---|---|---|---|---|
| `M5-S12-01` | **`TRN-E03` status — `PROPOSED — BLOCKED PENDING GOVERNANCE DECISIONS`** | `supporting/information-delivery-schedule.md` | §2, §5 | 2 | **`BLOCKED`** | — | **`SUPPORTING`** |
| `M5-S12-02` | **Blocker 1 — publication / exchange authorisation authority: `UNRESOLVED — TBD`.** *"The role holding publication and exchange authority is **UNRESOLVED**"* | `bep/…BEP.md` §9.7; `supporting/information-delivery-schedule.md` §5.1; IM matrix `D4` | — | 1, 2 | **`UNRESOLVED`** | — | **`CONTROLLED`** |
| `M5-S12-03` | **Blocker 2 — recipient acceptance authority: `UNRESOLVED — TBD / recipient-dependent`** | `supporting/information-delivery-schedule.md` §5.1; `bep/…BEP.md` §9.8, §10.11; IM matrix `D7` | — | 2, 1 | **`UNRESOLVED`** | — | **`SUPPORTING`** |
| `M5-S12-04` | **Blocker 3 — recipient identity: `Not established`** | `supporting/information-delivery-schedule.md` §5.1, §5.2; `bep/…BEP.md` §2.3, §5.3 | — | 2, 1 | **`UNRESOLVED`** | — | **`SUPPORTING`** |
| `M5-S12-05` | **Blocker 4 — required formats: `Not established — no approved standard`** | `supporting/information-delivery-schedule.md` §5.1; `bep/…BEP.md` §11.9; `supporting/governance-decision-register.md` `OF-003` | — | 2, 1 | **`UNRESOLVED`** | — | **`SUPPORTING`** |
| `M5-S12-06` | **Blocker 5 — deliverable set: `Not defined`** | `supporting/information-delivery-schedule.md` §5.1, §5.2; `bep/…BEP.md` §10.4 | — | 2, 1 | **`UNRESOLVED`** | — | **`SUPPORTING`** |
| `M5-S12-07` | *"These are **not resolved to complete the schedule**. An entry that cannot proceed is recorded as blocked. **Assigning a plausible authority to make the row look finished would manufacture governance that does not exist**"* | `supporting/information-delivery-schedule.md` | §5.1 | 2 | **`BLOCKED`** | — | **`SUPPORTING`** |
| `M5-S12-08` | **The five matters are independent. Resolving one releases none of the others** — assigning publication authority would leave the recipient, formats, deliverable set and acceptance authority exactly as they are | `S4` §5.1, §5.2 — each recorded separately, with its own status and reference | — | 4 | **`BLOCKED`** | — | **`INTERP`** |
| `M5-S12-09` | **`S4` §5.2 records each scheduled field independently `TBD`** — Information Container, Lead, Recipient, Format, Authorisation Requirement and Acceptance Criteria | `supporting/information-delivery-schedule.md` | §5.2 | 2 | **`UNRESOLVED`** | — | **`SUPPORTING`** |
| `M5-S12-10` | State / Suitability — *"**Published / Authorised only if** the required delivery review has occurred **and** publication authorisation has been given. **Neither condition can currently be met**"* | `supporting/information-delivery-schedule.md` | §5.2 | 2 | **`BLOCKED`** | — | **`SUPPORTING`** |
| `M5-S12-11` | **`T4` cannot proceed; information remains Shared** | `supporting/cde-workflow-state-strategy.md` §11; `supporting/information-delivery-schedule.md` §5.2 | — | 2 | **`BLOCKED`** | **`NOT DEMONSTRATED`** | **`SUPPORTING`** |
| `M5-S12-12` | *"**No final deliverable set is invented.** Models, drawings, documents and supporting information may form part of this exchange **only when later defined** through an explicit decision"* | `supporting/information-delivery-schedule.md` | §5.2 | 2 | **`UNRESOLVED`** | — | **`SUPPORTING`** |
| `M5-S12-13` | *"**RVT, IFC, PDF and NWC are not mandated.** They appear in observed project context. **An observed format is not an approved delivery requirement**"* | `supporting/information-delivery-schedule.md` §5.2; `bep/…BEP.md` §10.8, §11.9 | — | 2, 1 | **`UNRESOLVED`** | — | **`SUPPORTING`** |
| `M5-S12-14` | **`TRN-E03` remains `PROPOSED` and `BLOCKED`** in the live validation record; **no delivery, receipt or acceptance event is demonstrated** | `docs/Increment-7C-Live-Validation-Record.md` | §7, §9 | 3 | **`BLOCKED`** | **`NOT DEMONSTRATED`** | **`DECISION-RECORD`** |
| `M5-S12-15` | **Every one of the five is typed, and none is blank** — `UNRESOLVED — TBD` · `Not established` · `Not defined` · `PROPOSED — BLOCKED`. **The schedule records the absence rather than concealing it** | `S4` §5.1, §5.2, §7 — every entry carries an explicit marker | — | 4 | **`BLOCKED`** | — | **`INTERP`** |
| `M5-S12-16` | **The publication-arrangement boundary.** `AD-001` does **not** *"establish project publication / exchange authority"*; `PAD-001`'s scope is *"Training Baseline 0.1 publication arrangement only"* | `docs/Training-Baseline-0.1-Approval-Decision.md` `AD-001`; `supporting/governance-decision-register.md` `PAD-001` | — | 3, 2 | **`UNRESOLVED`** | — | **`DECISION-RECORD`** |
| `M5-S12-17` | **Recorded variance — the two sources enumerate the blockers differently.** `S4` §5.1 records **five**; `S5` §11 records **six**, adding *"Delivery purpose defined — Not defined"* and merging acceptance authority with acceptance criteria. **Both record the event as blocked. Neither list is rewritten** | `supporting/information-delivery-schedule.md` §5.1; `supporting/cde-workflow-state-strategy.md` §11 | — | 2 | **`BLOCKED`** | — | **`SUPPORTING`** |
| `M5-S12-18` | **A delivery review, a publication decision and a recipient acceptance function would each be required.** Module 5 identifies that they are required and stops | `S4` §5.2; `S1` §9.6, §9.7, §9.8 — **requirement identified, mechanics not taught** | — | 4 | **`UNRESOLVED`** | — | **`INTERP`** |
| `M5-S12-19` | Detailed delivery-review, approval, acceptance, assurance, technical-review, issue-closure and coordination-resolution mechanics; professional certification | — | — | — | — | — | **`EXCLUDED`** — **Module 6 owns them** |
| `M5-S12-20` | Populating, resolving or narrowing any of the five blocking matters | — | — | — | — | — | **`EXCLUDED`** |

**Teaching warning — `M5-S12-15`.** The slide must **show the typed markers**.
Five blank boxes would teach the opposite of what the schedule does — the whole
point is that the absence is **recorded**, in writing, with a name.

**Teaching warning — `M5-S12-17`.** If the audience has read the CDE strategy,
they will count six. **Say that both lists exist and that neither is corrected.**
Module 5 teaches the schedule's five because the schedule is the resource that
owns the event.

### Slide 13 — Nothing is blank — how Harrismith names an absence

| ID | Statement | Source path | Section | Auth | Governance | Implementation | Class |
|---|---|---|---|---|---|---|---|
| `M5-S13-01` | **No controlled Harrismith responsibility-matrix or delivery-schedule field is left as an untyped blank.** Every absence carries a written marker | `S2` §3.1–§3.7 (297-cell census); `S3` §3, §4, §6; `S4` §5.1, §7 — **verified by inspection** | — | 4 | — | — | **`INTERP`** |
| `M5-S13-02` | **Only the IM Responsibility Matrix publishes a formal cell-value legend.** `S3` and `S4` use several prose forms without one | `supporting/information-management-responsibility-matrix.md` §1; `supporting/model-information-responsibility-matrix.md`; `supporting/information-delivery-schedule.md` | — | 4 | — | — | **`INTERP`** |
| `M5-S13-03` | **The seven markers are a teaching grouping assembled across four sources — not a controlled code set.** No source publishes them as one vocabulary | `S2` §1; `S3` §3.4, §4; `S4` §2, §5.1; `S5` §11 — **grouping is teaching interpretation** | — | 4 | — | — | **`INTERP`** |
| `M5-S13-04` | **`TBD`** — *"Allocation unresolved. The BEP records this authority as **not established**."* | `supporting/information-management-responsibility-matrix.md` | §1 | 2 | **`UNRESOLVED`** | — | **`SUPPORTING`** |
| `M5-S13-05` | **`TBD` does not mean** a holder exists but is unnamed · the answer is known informally · the matter will necessarily be resolved later · the field may be completed by inference | `S2` §1, §Population rule — *"records it as unresolved **rather than filling it with a plausible role**"* | — | 4 | **`UNRESOLVED`** | — | **`INTERP`** |
| `M5-S13-06` | **`—`** — *"The role holds **no function in this activity**."* **A populated cell recording a resolved answer** | `supporting/information-management-responsibility-matrix.md` | §1 | 2 | **`PROPOSED GOVERNANCE`** | — | **`SUPPORTING`** |
| `M5-S13-07` | **`—` is not blank, not unresolved, and not equivalent to `TBD`**, and it does not mean the role, person, party or discipline is absent from the project | `S2` §1 — the two values are separately defined | — | 4 | **`PROPOSED GOVERNANCE`** | — | **`INTERP`** |
| `M5-S13-08` | **`Not defined`** — the required content, list or purpose has not been defined. Harrismith instances: **final deliverable set** · **level of information need** · **delivery purpose** (`S5` only) | `supporting/information-delivery-schedule.md` §7; `supporting/model-information-responsibility-matrix.md` §4; `supporting/cde-workflow-state-strategy.md` §11 | — | 2 | **`UNRESOLVED`** | — | **`SUPPORTING`** |
| `M5-S13-09` | **`Not established`** — the identity, authority, standard or requirement has not been established. Instances: **recipient identity** · **required formats — no approved standard** · **Appointing Party identity** | `supporting/information-delivery-schedule.md` §5.1, §7; `bep/…BEP.md` §2.3, §5.3, §11.9 | — | 2, 1 | **`UNRESOLVED`** | — | **`SUPPORTING`** |
| `M5-S13-10` | **`Not defined` and `Not established` are used distinctly by the sources** and are not treated as equivalent here | `S3` §4 and `S4` §5.1 use them for different objects — **recorded, not merged** | — | 4 | **`UNRESOLVED`** | — | **`INTERP`** |
| `M5-S13-11` | **`Not applicable`** — the field does not apply to the object. **Bounded Harrismith instance:** `COORD-01` *Originating party* — *"Not applicable — see note below"*, because federation *"does not merge authorship"* | `supporting/model-information-responsibility-matrix.md` | §3.4 | 2 | **`PROPOSED GOVERNANCE`** | — | **`SUPPORTING`** |
| `M5-S13-12` | **`Not applicable` is never used to conceal an unresolved answer.** In the one place it appears, the source explains **why** the field does not apply | `S3` §3.4 — the entry carries a reasoned note | — | 4 | **`PROPOSED GOVERNANCE`** | — | **`INTERP`** |
| `M5-S13-13` | **`Conditional`** — the row or event activates **only when its stated trigger occurs**. Instance: **`TRN-E02`**, *"repeatable and conditional"*, with **no calendar frequency** | `supporting/information-delivery-schedule.md` | §2, §4, §4.2 | 2 | **`CONDITIONAL`** | — | **`SUPPORTING`** |
| `M5-S13-14` | **Conditional is not** delayed · overdue · optional without rules · pending · active. *"An unactivated row is **not a pending exchange**"* | `supporting/information-delivery-schedule.md` | §4.2 | 2 | **`CONDITIONAL`** | — | **`SUPPORTING`** |
| `M5-S13-15` | **`BLOCKED`** — the event or route **cannot proceed** while required governance or inputs remain unresolved. Instances: **`TRN-E03`** and **`T4`**, which *"has no available authorising function"* | `supporting/information-delivery-schedule.md` §2, §5; `supporting/cde-workflow-state-strategy.md` §11 | — | 2 | **`BLOCKED`** | — | **`SUPPORTING`** |
| `M5-S13-16` | **Blocked is not** rejected · failed · overdue · merely unfinished · blank. *"An entry that cannot proceed **is recorded as blocked**"* | `supporting/information-delivery-schedule.md` | §5.1 | 2 | **`BLOCKED`** | — | **`SUPPORTING`** |
| `M5-S13-17` | **The sources do not share one harmonised absence vocabulary**, and the same authority gap is recorded as **unresolved** in `S2` and `S3` but as **blocking an event** in `S4`. **Both are correct — they classify different objects** | §6.1 variances 1 and 2; `S2` §6; `S3` §6; `S4` §5.1 | — | 2 | **`UNRESOLVED`** / **`BLOCKED`** | — | **`SUPPORTING`** |
| `M5-S13-18` | **No universal replacement vocabulary is proposed.** Module 5 records the differences and teaches how to read each source on its own terms | Module method — §1.3 of [`source-inventory.md`](source-inventory.md) | — | 4 | — | — | **`INTERP`** |
| `M5-S13-19` | **`H-D12` remains `NOT ESTABLISHED`** — no source records any field as a formatting artefact or placeholder, so **no Harrismith instance of that reading exists** | §7.2 `H-D12` | — | 4 | **`UNRESOLVED`** | — | **`SUPPORTING`** |
| `M5-S13-20` | Any claim that Harrismith contains an untyped blank; any presentation of the seven markers as a controlled universal code set; any equivalence between `TBD` and `—`, or between `Not defined` and `Not established` | — | — | — | — | — | **`EXCLUDED`** |

**Teaching warning — `M5-S13-03`.** The panel will look like a code table.
**Say once, explicitly, that it is not one.** Only `S2` publishes a legend; the
other six markers were gathered from three further sources by this module.

**Teaching warning — `M5-S13-17`.** This is the slide's honest ending. **Do not
resolve the variance** by proposing a single vocabulary — the point is that two
resources can classify the same gap differently and both be right, because they
are classifying different objects.

### Slide 14 — What Triviron must decide before drawing a matrix

| ID | Statement | Source path | Section | Auth | Governance | Implementation | Class |
|---|---|---|---|---|---|---|---|
| `M5-S14-01` | **No Triviron project information exists in this repository.** Module 7 *"cannot be developed beyond generic transfer principles until Triviron project context is available"* | [`../roadmap.md`](../roadmap.md) | §2 | 4 | — | — | **`TEACHING-PLAN`** |
| `M5-S14-02` | **This slide asks questions and answers none of them.** Every field on it is marked *not yet established* | Module method; `S15` §2 | — | 4 | — | — | **`INTERP`** |
| `M5-S14-03` | **Delivery organisation — seven questions.** What parties exist · what task teams sit within each · which disciplines are information domains rather than organisations · who is formally appointed · which functional roles are required · who holds them · which roles may validly be combined | `bep/…BEP.md` §4.2, §4.3, §4.6, §5.2, §5.11 — **questions derived from the BEP's own distinctions** | — | 4 | — | — | **`INTERP`** |
| `M5-S14-04` | **Harrismith's four-party structure is a training organisation model (`TA-03`)** and *"does **not** constitute actual appointment of any consultant, contractor, company or professional role holder"* | `supporting/governance-decision-register.md` | `TA-03` | 2 | **`TRAINING ASSUMPTION`** | — | **`SUPPORTING`** |
| `M5-S14-05` | **Responsibility architecture — seven questions.** Which functions need allocation · what grammar will be used · adopt Harrismith's, another, or decide later · who performs, checks, authorises, coordinates and accepts · which authorities are project-wide and which purpose-specific · how unresolved allocations will be typed · how independence limitations will be recorded | `bep/…BEP.md` §5.12, §9.1–§9.8, §5.11; `S2` §1, §5, §6 | — | 4 | — | — | **`INTERP`** |
| `M5-S14-06` | **Harrismith's allocations are not recommendations — and they do not share one status.** `S2`'s functional allocations are *"functional governance proposals **unless the BEP already expressly establishes the allocation**"* (`P4` established; `D4` established as unresolved); `S3`'s container allocations are **`PROPOSED GOVERNANCE`**; `S4`'s entries are **`PROPOSED GOVERNANCE`**, each additionally proposed, conditional or blocked | `supporting/information-management-responsibility-matrix.md` §Population rule; `bep/…BEP.md` §9.4, §9.7; `supporting/model-information-responsibility-matrix.md` §Classification; `supporting/information-delivery-schedule.md` §Classification | — | 2, 1 | **`PROPOSED GOVERNANCE`** / **`ESTABLISHED ALLOCATION`** / **`UNRESOLVED`** | — | **`SUPPORTING`** |
| `M5-S14-07` | **Information-container architecture — seven questions.** What containers must exist · who originates and maintains each · how party, task team, discipline and container are recorded · which dependencies and interfaces must be visible · whether a coordination construct is required · whether it is a working set or a deliverable · what level of information need applies | `bep/…BEP.md` §7.2, §7.3; `S3` §1, §3, §3.3, §3.4, §4 | — | 4 | — | — | **`INTERP`** |
| `M5-S14-08` | **Harrismith's container identifiers are `PROPOSED GOVERNANCE` for the training delivery model**, derived from `TA-03`. They are not a naming scheme to copy — **no Naming Standard exists** | `supporting/model-information-responsibility-matrix.md` §Classification, §6; `bep/…BEP.md` §11.3 | — | 2, 1 | **`PROPOSED GOVERNANCE`** | — | **`SUPPORTING`** |
| `M5-S14-09` | **Delivery planning — eleven questions.** What information requirements govern delivery · what events or milestones actually exist · which recipients are identified · the purpose of each exchange · required formats · required checking · who authorises each progression · who may accept for each stated purpose · what acceptance criteria apply · what dependencies and dates are real · what final deliverable set is required | `bep/…BEP.md` §10.5, §10.13; `S4` §1 | — | 4 | — | — | **`INTERP`** |
| `M5-S14-10` | **`TRN-E01`, `TRN-E02` and `TRN-E03` are training event concepts** — *"three restrained training event concepts… **not** a full project delivery schedule"* — and are not Triviron events | `supporting/information-delivery-schedule.md` | §2, §Classification | 2 | **`PROPOSED GOVERNANCE`** | — | **`SUPPORTING`** |
| `M5-S14-11` | **Governance and evidence — seven questions.** Which source governs each decision · who may approve changes · how decisions will be recorded · what counts as implementation evidence · what must be verified after implementation · how proposed governance stays separate from live evidence · how unknowns stay visible instead of being completed by assumption | `bep/…BEP.md` §1.5, §12.3, §12.7, §12.9; `S7` §Classification vocabulary | — | 4 | — | — | **`INTERP`** |
| `M5-S14-12` | **Precedence is decided, not inherited** — *"Where documents conflict, the higher tier prevails"*, and *"**Authority is never inferred upward from platform configuration**"* | `bep/…BEP.md` | §1.5 | 1 | **`CONTROLLED GOVERNANCE`** | — | **`CONTROLLED`** |
| `M5-S14-13` | *"**Intended state does not prove implementation.** An approved decision is not a configured system"*; and *"**A change is not complete because a document was edited or a setting was clicked**"* | `bep/…BEP.md` | §12.3, §12.9 | 1 | **`CONTROLLED GOVERNANCE`** | — | **`CONTROLLED`** |
| `M5-S14-14` | Closing framing — ***define the questions before you fill the cells*** | none — **presenter framing** | — | 5 | — | — | **`SYNTH`** |
| `M5-S14-15` | **Keep the three allocations apart** — function allocation, container allocation and delivery planning are three separate acts requiring three separate resources | Carried from Slides 3–5; `S2`, `S3`, `S4` mutual disclaimers | — | 4 | — | — | **`INTERP`** |
| `M5-S14-16` | **Keep governance definition separate from implementation evidence.** Approval is not implementation, and implementation is not verification | `bep/…BEP.md` §12.3, §12.9; `docs/Training-Baseline-0.1-Approval-Decision.md` `AD-001` | — | 1 | **`CONTROLLED GOVERNANCE`** | **`IMPLEMENTATION UNVERIFIED`** | **`SUPPORTING`** |
| `M5-S14-17` | **Leave unresolved matters visibly typed** — the Slide 13 discipline, carried into whatever Triviron builds | Slide 13; `S2` §1; `S4` §5.1 | — | 4 | — | — | **`INTERP`** |
| `M5-S14-18` | **Harrismith is an example of method, not a Triviron template.** What transfers is the discipline of asking, separating and typing — not the answers | Module method; `TA-02`, `TA-03` | — | 4 | — | — | **`INTERP`** |
| `M5-S14-19` | **`Triviron responsibility and delivery basis — not yet established.`** | [`../roadmap.md`](../roadmap.md) §2 — no Triviron information exists | — | 4 | **`UNRESOLVED`** | — | **`TEACHING-PLAN`** |
| `M5-S14-20` | **Module 7 owns the translation** — deciding which Harrismith positions transfer, establishing Triviron-specific answers, writing the Triviron BEP, and populating project-specific matrices and schedules. **None of that has been performed** | [`../roadmap.md`](../roadmap.md) | §2 | 4 | — | — | **`TEACHING-PLAN`** |
| `M5-S14-21` | Any Triviron role holder, party, task team, discipline structure, container, event, recipient, format, authority, date, deliverable or acceptance criterion | — | — | — | — | — | **`EXCLUDED`** |
| `M5-S14-22` | Any recommendation that Triviron adopt a specific Harrismith allocation, identifier, event, grammar or organisational structure | — | — | — | — | — | **`EXCLUDED`** |

**Teaching warning — the whole slide.** **Every line is a question or a
boundary.** If a sentence on this slide can be read as an answer about Triviron,
it is wrong. The audience will push for answers; the correct response is that
Module 7 owns them and the basis is not yet established.

**Teaching warning — `M5-S14-14`.** This is **the module's only `SYNTH`
statement**. It is a framing line, it cites nothing, and it must not be delivered
as though a source said it.

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
| **9** | **The `TRN-E03` blocking matters are enumerated twice, differently.** `S4` §5.1 records **five**; `S5` §11 records **six** | `S5` adds *"Delivery purpose defined — Not defined"* and merges *acceptance authority* with *acceptance criteria*, which `S4` separates. **Both record the event as `BLOCKED`.** Module 5 teaches `S4`'s five, because `S4` owns the event — and **records that `S5` counts six**. Neither list is rewritten |
| **8** | **Two vocabularies, one project.** `S1` §5.12 defines the **seven-term responsibility grammar**; `S1` §9.2 defines a **six-term decision terminology** — Check · Review · Authorise · Accept · Reject · Coordinate | **Recorded, not merged.** §9.2 **adds** *Review* and *Reject*, which have **no code**, and **omits** Perform, Consult and Inform. Both are controlled; they answer different questions — *who holds which function* against *what kind of decision was made*. **Neither is rewritten to match the other** |

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

**One hundred and three claims Module 5 may not make.** Grouped by the error each
would commit. Claims 51–59 were added in **T5-B**; 60–75 in **T5-C**; 76–89 in
**T5-D**; 90–102 in **T5-E**; 103 in **T5-F-A-R**.

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

### 9.9 Additional prohibitions recorded in T5-C — 16

**Reading the vocabulary**

| # | Prohibited claim |
|---|---|
| 60 | That **`TBD` means a holder exists but has not yet been named.** It records that the allocation or authority is **not established** — and carries no promise that one will be |
| 61 | That **`—` means the role, the person or the party is absent from the project.** It records that the role holds **no function in that activity**, and nothing else |
| 62 | That the grammar records **seniority, contractual authority or platform permission**. *"Authority comes from governance"* (`S1` §9.1) |
| 63 | That *Review* or *Reject* has a grammar code. They belong to `S1` §9.2's **decision terminology**, which is a different vocabulary |

**Reading a cell**

| # | Prohibited claim |
|---|---|
| 64 | That a **combined cell value establishes sequence, priority, chronology or hierarchy.** No source states an order between codes in a cell |
| 65 | That a **combined cell value implies separate people**, competence, or successful performance |
| 66 | That a **populated `Ck` cell proves independent checking** |
| 67 | That **`Au` creates professional or contractual authority** beyond the defined progression it permits, for the defined purpose |
| 68 | That **`Ac` is allocated anywhere in the matrix as a resolved function.** It appears **once**, inside **`TBD Ac`** |
| 69 | That **`TBD Ac` proves an exchange was accepted**, or that it resolves recipient acceptance authority |
| 70 | That **`P4` and `D4` carry the same authority status** |
| 71 | That **coordination (`Co`) equals authorisation**, or that **consultation (`Cs`) equals approval** |
| 72 | That **checking permits progression** — *"it does not permit progression"* (`S2` `P2`/`P3` note; `S1` §9.3) |

**Role combination and independence**

| # | Prohibited claim |
|---|---|
| 73 | That **separate Author and Checker columns prove separate people** |
| 74 | That **role combination is automatically a defect, a non-conformance, evidence of inadequate competence, or evidence that checking did not occur.** The register records **no non-conformance**, and *"none is asserted"* |
| 75 | That **simulated role participation creates real professional authority, contractual appointment, duty or liability** (`TA-02`); or that **independence may be claimed for presentation neatness**; or that **Slide 8 establishes an assurance procedure, an independence requirement, or a remedy** |

### 9.10 Additional prohibitions recorded in T5-D — 14

**Reading the schedule**

| # | Prohibited claim |
|---|---|
| 76 | That the Information Delivery Schedule is a **contractual programme** |
| 77 | That schedule entries are **real client information requirements**, contractual delivery milestones, actual consultant appointments or construction programme dates |
| 78 | That a **`Delivery ID` is a contractual document number**, or that any project numbering convention exists. **No Naming Standard exists** |
| 79 | That a **schedule row proves an exchange occurred, was received, or was accepted** |
| 80 | That **`Status` is the information state.** It is the status **of the schedule entry itself** |
| 81 | That **`State / Suitability` is the row's planning status** |
| 82 | That **`Acceptance Criteria` establishes who holds acceptance authority**; that **`Recipient` establishes an appointing party**; or that **`Lead` names a person** |

**Reading the events**

| # | Prohibited claim |
|---|---|
| 83 | That **`PROPOSED` means authorised for execution** |
| 84 | That **`CONDITIONAL` means delayed**, or that **`BLOCKED` means overdue, rejected, or merely unfinished** |
| 85 | That **`TRN-E01`, `TRN-E02` and `TRN-E03` form a mandatory sequence** |

**Events against transitions**

| # | Prohibited claim |
|---|---|
| 86 | That **`TRN-E01` is `T1`**, that **`TRN-E02` is `T8` or `T1`**, or that **`TRN-E03` is `T4`**. Each **uses** a transition; none **is** one |
| 87 | That **`T1`–`T8` are eight sequential information-state transitions.** Only `T1` and `T4` change state |
| 88 | That **Delivered, Received or Accepted is an information state.** `T5`, `T6` and `T7` leave the state **unchanged** |
| 89 | That any **`TRN-E03` blocking matter is blank, empty, or a formatting artefact.** Each is **typed** — `UNRESOLVED — TBD`, `Not established`, `Not defined`, `PROPOSED — BLOCKED` |

### 9.11 Additional prohibitions recorded in T5-E — 13

**Reading an absence**

| # | Prohibited claim |
|---|---|
| 90 | That an **untyped blank exists** in any controlled Harrismith matrix or schedule field |
| 91 | That the **seven typed markers form one controlled, universal code set.** Only `S2` publishes a legend; the grouping is a teaching interpretation across four sources |
| 92 | That **`Not defined` and `Not established` mean the same thing** |
| 93 | That **`Not applicable` may be used to conceal an unresolved answer** |
| 94 | That **every source uses the same absence terminology.** They do not, and the differences are recorded rather than harmonised |

**Transfer to Triviron**

| # | Prohibited claim |
|---|---|
| 95 | That **Harrismith's role or function allocations are recommendations for Triviron** |
| 96 | That **Harrismith's parties, task teams or discipline structure are Triviron facts.** They are a training organisation model under `TA-03` |
| 97 | That **Harrismith's container identifiers** — `ARC-01`–`FIR-01`, `COORD-01` — **transfer to Triviron** |
| 98 | That **Harrismith's delivery events** — `TRN-E01`–`TRN-E03` — **transfer to Triviron** |
| 99 | That **any Triviron role holder, party, task team, container, event, recipient, format, authority, date, deliverable or acceptance criterion is known.** None is |
| 100 | That **Module 5 has written, or begun, the Triviron BEP**, or that **Module 7's translation has been performed** |

**Completion status**

| # | Prohibited claim |
|---|---|
| 101 | That a **complete teaching-content baseline means the presentation is produced**, reviewed or rehearsed. **No rendered asset exists, and no PowerPoint is committed to this repository** |
| 102 | That **the existence of an exercise set means rehearsal has occurred**, or that any allocated time has been measured |

### 9.12 Additional prohibition recorded in T5-F-A-R — 1

| # | Prohibited claim |
|---|---|
| 103 | That **`D4` contains `TBD` in all nine columns**, or that its **five `TBD` cells constitute a resolved or proposed authority allocation.** The row holds **five `TBD`** (AP, LDP, BM, BC, TTL) and **four `—`** (Aut, Chk, CDE, Rcp); *"No allocation is made here"* |

### 9.13 Programme-status claims — required in every increment

| # | Prohibited claim |
|---|---|
| A | That a **PowerPoint is tracked in this repository** — none is, in any module |
| B | That **presentation timing has been measured** — it is **`20.0 minutes allocated — not measured`** |
| C | That **Module 6 mechanics have been completed**, or that Module 5 teaches them |
| D | That a **complete teaching-content baseline is a produced, reviewed or rehearsed presentation** — see prohibited claims 101 and 102 |

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

**Test applied to every slide, and passed:** if a slide explained **how a
coordination run is performed, how a finding is triaged, how an Issue is closed,
or how a review is conducted**, it would have left Module 5. **No slide does.**

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
| ~~T5-C~~ | ~~Matrix-cell grammar and allocation boundaries — Slides 6–8~~ — **COMPLETE** |
| ~~T5-D~~ | ~~Delivery events and schedule construction — Slides 9–12~~ — **COMPLETE** |
| ~~T5-E~~ | ~~Slides 13–14, the exercise baseline and the complete content baseline~~ — **COMPLETE** |
| ~~T5-F~~ | ~~Visual specifications and visual-source set~~ — **COMPLETE** (T5-F-A, T5-F-A-R, T5-F-A-R2, T5-F-B) |
| ~~T5-G~~ | ~~Presentation assembly package~~ — **COMPLETE** — [`presentation/`](presentation/), seven files |
| ~~T5-H~~ | ~~External PowerPoint production — **outside this repository**~~ — **COMPLETE.** `REV01` produced and **accepted**; corrected in `T5-H-R1`; **not committed here** |

---

## 11. Status

| Field | Value |
|---|---|
| Increment | **T5-F-B — visual-source baseline COMPLETE** |
| Slides classified | **All fourteen. 267 statements** |
| Architecture only | **None.** No slide remains undeveloped |
| Registers | **Six** — source authority, terminology, hypothesis, unresolved, prohibited claims, boundary deferrals |
| Hypotheses tested | **25** — `H-G1`–`H-G7`, `H-D1`–`H-D16`, `H-C1`–`H-C2`. **Unchanged since T5-A** |
| Prohibited claims | **103**, plus 4 standing programme-status prohibitions |
| Classification scheme | **Reconciled in T5-B** — `SYNTH` redefined; `M5-S2-14` reclassified `INTERP`. **Unchanged since**; see §5.1 |
| Terminology variances | **9** — seven from T5-A, one from T5-C (grammar vs decision terminology), one from T5-D (**five vs six `TRN-E03` blocking matters**) |
| Final reconciliation | **COMPLETE** — see §12 |
| Exercise baseline | [`exercises.md`](exercises.md) — **79 exercises**, created in T5-E |
| Timing | **`20.0 minutes allocated — not measured`** |
| Assembly package | **COMPLETE (T5-G)** — [`presentation/`](presentation/), **seven** production-handoff files |
| PowerPoint | **PRODUCED — `REV01`** (`T5-H`, corrected in `T5-H-R1`), outside this repository; **not committed here** |
| Presentation review | **ACCEPTED** at `REV01` |
| Rehearsal, measured timing | **None** |
| Visual specifications | **COMPLETE and ACCEPTED (T5-F-A, corrected in T5-F-A-R)** — [`visual-demonstration-plan.md`](visual-demonstration-plan.md), `M5V-01`–`M5V-14` |
| Visual sources | **COMPLETE (T5-F-B)** — `M05-S01`–`M05-S14` in [`../assets/module-05/`](../assets/module-05/), all `SOURCE COMPLETE`; register and slide-visual map complete; **rendered `NONE`** |
| `D4` reconciliation | **CLOSED (T5-F-A-R2).** All eight Module 5 files agree with the controlled row — **five `TBD`, four `—`, no allocation made** |
| Outstanding | **Module 5 rehearsal and measured timing** |

---

## 12. Module-wide final reconciliation — T5-E

**The Module 5 teaching-content baseline is complete.** This section reconciles
all fourteen developed slides against every control the module established.
**Every superlative and observation in §5 was recalculated from the final tables
in this increment**; none was carried forward because it had been true earlier.

### 12.1 Coverage

| Field | Result |
|---|---|
| Slides developed | **14 of 14.** None architecture only |
| Classified statements | **267** |
| Slides with a statement table | **14** |
| Presenter notes | **All fourteen slides**, plus a normal and an emergency closing |
| Exercises | [`exercises.md`](exercises.md) — **79**, numbered consecutively `E1`–`E79` |
| Timing | **20.0 minutes allocated — not measured** |
| Increments | T5-A · T5-B · T5-C · T5-D · T5-E — **all complete** |

### 12.2 Source hierarchy

The five-level precedence established in T5-A, traced to `S1` §1.5, **was applied
unchanged throughout and was not reopened**. Fifteen sources consulted
(`S1`–`S15`); eight groups excluded with reasons (`E1`–`E8`).

**No level-4 or level-5 material was ever cited as though it governed.** Modules
1–4 appear only as `MODULE-2-4` (3 statements); the roadmap only as
`TEACHING-PLAN` (4 statements).

### 12.3 The three principal resources

**They remain separate on every slide that touches them.**

| Resource | Owns | Never used for |
|---|---|---|
| `S2` IM Responsibility Matrix | Functions to roles; the seven-term grammar; `TBD` and `—` | Container authorship; delivery events |
| `S3` Model / Information Responsibility Matrix | Containers to parties and task teams | Process functions; events, formats, timing |
| `S4` Information Delivery Schedule | Sixteen fields; three events; the `TRN-E03` block | Function allocation; container definition |

**No combined table was produced. No RACI substitution occurred.** The refusal of
RACI is taught as controlled governance (`S1` §5.12), and prohibited claims 1–6
and 86 protect the boundaries.

### 12.4 Classification scheme

| Class | Count | Check |
|---|---:|---|
| `CONTROLLED` | 52 | Explicit `S1` wording |
| `SUPPORTING` | 125 | Approved supporting resource |
| `DECISION-RECORD` | 10 | `S8`, `S9`, `S10` |
| `MODULE-2-4` | 3 | Cited as teaching interpretation only |
| `TEACHING-PLAN` | 4 | `S15`; decides nothing |
| `INTERP` | 49 | **Every one cites the sources its construction rests on** |
| `SYNTH` | 1 | **`M5-S14-14` only** — cites nothing; presenter framing; labelled as such |
| `EXCLUDED` | 23 | **None appears as slide teaching** |
| **Total** | **267** | Sums to the per-slide table in §5 |

**The scheme was revised once, in T5-B, and not since.** The reconciliation is
recorded at §5.1.

### 12.5 Terminology variances — 9, all recorded, none harmonised

| # | Variance | State |
|---|---|---|
| 1 | Unresolved markers differ across `S2`, `S3`, `S4` | Recorded |
| 2 | The same authority gap is *unresolved* in `S2`/`S3` and **`BLOCKED`** in `S4` | Recorded — they classify different objects |
| 3 | *Purpose* means the container's purpose in `S3`, the exchange's in `S4` | Recorded |
| 4 | *Accept* is a code in `S2`, a field in `S4` | Recorded |
| 5 | *Publication* has two unrelated senses | Recorded — see [`source-inventory.md`](source-inventory.md) §5 |
| 6 | *Status* in `S4` is the entry's status | Recorded |
| 7 | *State* appears in `S3` and `S4` with different scope | Recorded |
| 8 | The grammar (`S1` §5.12) and the decision terminology (`S1` §9.2) are two vocabularies | Recorded |
| 9 | `S4` counts **five** `TRN-E03` blocking matters; `S5` counts **six** | **Recorded and unresolved. Neither list rewritten** |

**No conflict *between controlled sources* was found, and none was silently
reconciled.**

**One teaching-to-controlled-source contradiction was found**, during the
**T5-F-A review**. It was corrected across the teaching and specification files
in **T5-F-A-R** and closed in the analysis file in **T5-F-A-R2** — see §12.16 and
§12.16.1. The controlled source was always correct and **was not changed**.

### 12.6 Hypotheses — all 25 accounted for

| Group | Count | Outcome |
|---|---:|---|
| `H-G1`–`H-G7` — the pre-declared grammar | 7 | 4 `CONFIRMED`, 2 `CONFIRMED WITH QUALIFICATION`, 1 `SOURCE-SPECIFIC` / `REJECTED` for `S3` and `S4` |
| `H-D1`–`H-D16` — the proposed distinctions | 16 | 14 `CONFIRMED` (3 with qualification), 1 `NOT ESTABLISHED` (`H-D12`), 1 premise corrected (`H-D11`) |
| `H-C1`–`H-C2` — the central question | 2 | 1 `CONFIRMED WITH QUALIFICATION` and revised; 1 `INTERP` adopted |

**None was reopened after T5-A**, and none was converted into project governance.

### 12.7 Unresolved register — unchanged

All sixteen entries across §8.1–§8.6 remain open. **Nothing was populated,
narrowed or resolved by teaching need.**

| Safeguard | Final state |
|---|---|
| Publication / exchange authority | **UNRESOLVED — TBD** |
| Recipient acceptance authority | **UNRESOLVED — TBD** |
| Governance change approval (`A2`) | **UNRESOLVED — TBD by change class** |
| `TRN-E03` recipient identity | **Not established** |
| `TRN-E03` required formats | **Not established** |
| `TRN-E03` deliverable set | **Not defined** |
| `T4` | **BLOCKED** |
| Information state | **Remains Shared** |
| `UD-001` | **Unresolved, not corrected** |
| `GCR-006` | **OPEN** |
| Level of information need | **Not defined** |
| Naming Standard | **Does not exist** |
| Change-propagation route between the three resources | **Not defined by any source** |

**Published, Delivered, Received and Accepted remain four distinct objects**, and
**no schedule row was treated as a live transaction** anywhere in the module.

### 12.8 Prohibited claims

**103 numbered prohibitions plus 4 standing programme-status prohibitions.**

| Increment | Added | Range |
|---|---:|---|
| T5-A | 50 | 1–50 |
| T5-B | 9 | 51–59 |
| T5-C | 16 | 60–75 |
| T5-D | 14 | 76–89 |
| T5-E | 13 | 90–102 |
| T5-F-A-R | 1 | 103 |

**Highest identifier equals the count: 103.**

### 12.9 Module 6 boundary — not consumed

Coordination-cycle mechanics, model federation, clash detection, finding and
issue triage, escalation, technical review procedures, approval and acceptance
workflow mechanics, assurance sampling, coordination evidence, issue closure,
professional certification and competence assessment **are named as required
where the sources require them, and taught nowhere.**

**Slides 8 and 12 come closest** — each identifies that a function would be
required and stops. Neither describes how it would operate.

### 12.10 Module 7 boundary — not consumed

**No Triviron fact, role holder, party, task team, container, event, recipient,
format, authority, date, deliverable or acceptance criterion appears anywhere in
this module.** Slide 14 asks 39 questions across five decision groups and answers
none of them.

**No Harrismith position is offered as a Triviron recommendation.** The closing
marker is *`Triviron responsibility and delivery basis — not yet established.`*

### 12.11 Governance status versus implementation status

**Both are recorded on every statement where both apply.** The only implementation
evidence in the inventory is `S9`, which declares **`Authority: None`**.

| Implementation status | Used for |
|---|---|
| `IMPLEMENTATION UNVERIFIED` | Intended governance not checked against the live environment |
| `OBSERVED — QUALIFIED` | `ARC-01` only, at the inspected level |
| `NOT DEMONSTRATED` | Five containers, `TRN-E02` reshare, `GCR-006`, authority evidence |

**No absence of observation was converted into a failure claim anywhere.**

### 12.12 Timing

| Section | Slides | Allocated |
|---|---|---:|
| A — Why allocation is a separate problem | 1, 2 | 2.5 |
| B — Three resources, three questions | 3, 4, 5 | 4.5 |
| C — Matrix grammar and its limits | 6, 7, 8 | 4.0 |
| D — Information-delivery planning | 9, 10, 11, 12 | 6.0 |
| E — Naming an absence, and transferring the method | 13, 14 | 3.0 |
| **Total** | **14** | **20.0** |

**`20.0 minutes allocated — not measured.`** No rehearsal has been performed, in
this or any module.

### 12.13 What still does not exist

| Artefact | Current state |
|---|---|
| Visual specifications | **COMPLETE and ACCEPTED** — `M5V-01`–`M5V-14` |
| Visual sources / `assets/module-05/` | **COMPLETE** — `M05-S01`–`M05-S14`, all `SOURCE COMPLETE`, with register and slide-visual map |
| Visual-demonstration plan | **Exists and accepted** — [`visual-demonstration-plan.md`](visual-demonstration-plan.md) |
| Rendered visuals | **None**, in any module |
| Presentation assembly package | **COMPLETE (T5-G)** — [`presentation/`](presentation/), **seven** files |
| PowerPoint **in this repository** | **None**, in this or any module. `REV01` exists **externally only** |
| Rehearsal, measured timing | **None** |

**The external PowerPoint has been produced and accepted at `REV01`, and it is
still not a rehearsed presentation.** **No complete run has been performed and no
timing has been measured**, and prohibited claims 101 and 102 forbid the
confusion.

### 12.14 Residual work

- **T5-F-A** — the pre-visual correction gate and the fourteen visual
  specifications — **COMPLETE**. See
  [`visual-demonstration-plan.md`](visual-demonstration-plan.md).
- **T5-F-A-R** — the `D4` controlled-source correction, the Slide 12 wording
  correction and final specification acceptance — **COMPLETE**. See §12.16.
- **T5-F-A-R2** — closure of the remaining `resource-comparison.md` occurrence —
  **COMPLETE**. See §12.16.1. **No current Module 5 file contradicts the
  controlled `D4` row.**
- **T5-F-B** — the fourteen visual-source files, the visual register and the
  slide-visual map — **COMPLETE**. See
  [`../assets/module-05/`](../assets/module-05/). **Fourteen sources, all
  `SOURCE COMPLETE`; no rendered asset; no renderer installed; no source
  conflict with the accepted plan was found.**
- **T5-G** — the presentation assembly package — **COMPLETE**. See
  [`presentation/`](presentation/). **Seven production-handoff files; no
  PowerPoint, no rendered asset and no binary was created.**
- **T5-H** — external PowerPoint production, **outside this repository** —
  **COMPLETE**. The first build carried **four bounded visual-production
  defects** (Slides 2–5); **`T5-H-R1`** corrected them, changing **only Slides
  2–5** and leaving Slides 1 and 6–14 and all fourteen speaker-note files
  **byte-for-byte unchanged**. **`REV01` was ACCEPTED by governance review.**
  **The `.pptx` is not committed here.**
- **Rehearsal and measured timing** — **outstanding**, as for Modules 1–4.

### 12.15 T5-F-A correction record

**Four wording corrections were applied before any visual was specified.** None
changed a statement classification or a total; `M5-S14-06` was **revised in
place**, retaining its identifier and its `SUPPORTING` class.

| # | Correction | Where |
|---|---|---|
| **1** | **The grammar belongs to one matrix only.** The Slide 5 → 6 transition said both matrices *"are read cell by cell"*. It now states that one matrix uses the controlled cell grammar and **the container matrix uses none**, and that Slide 6 examines the function matrix's vocabulary | [`presentation-outline.md`](presentation-outline.md), [`speaker-notes.md`](speaker-notes.md), [`exercises.md`](exercises.md) `E72` |
| **2** | **Slide 13 is not seven forms of "not yet".** The umbrella heading and the *"not settled"* narration implied all seven markers are unresolved. **`—` and `Not applicable` record resolved answers.** An **outcome column** was added so each marker's outcome is visible, and the recovery line was rewritten | [`presentation-outline.md`](presentation-outline.md), [`speaker-notes.md`](speaker-notes.md) |
| **3** | **The IM split status is preserved on Slide 14.** The slide grouped organisation, containers, events and allocations as one `PROPOSED GOVERNANCE` block. It now carries a three-row status contrast — **IM matrix split**, container matrix and schedule `PROPOSED GOVERNANCE` — and `M5-S14-06` was revised to cite `S2`, `S3` and `S4` | [`presentation-outline.md`](presentation-outline.md), [`speaker-notes.md`](speaker-notes.md), §5 `M5-S14-06`, [`exercises.md`](exercises.md) `E57`, `E69` |
| **4** | **Unsupported generalisations removed.** *"which on most projects at kick-off is nobody"*, *"causes more argument than anything else on the list"* and *"the three that get skipped are always the same"* were replaced with bounded cues drawn from the Module 5 material. One further prevalence remark in the Slide 6 notes — *"where the vocabulary is usually mis-taught"* — was replaced with a reference to prohibited claims 32, 60 and 61 | [`speaker-notes.md`](speaker-notes.md) |

**No new external source was introduced, and `SYNTH` was not increased.** The
module's `SYNTH` count remains **1** — `M5-S14-14`.

### 12.16 Controlled-source correction record — T5-F-A-R

**A teaching statement contradicted the controlled Information Management
Responsibility Matrix. The matrix was correct; the teaching wording was wrong.**

| Field | Value |
|---|---|
| Discovered | **Repository review of the T5-F-A commit**, before source production began |
| Contradicted source | [`supporting/information-management-responsibility-matrix.md`](../../supporting/information-management-responsibility-matrix.md) §1, §2, §3.6 |
| Nature | Teaching and visual-specification wording described the `D4` row as *"`TBD` in every column"* and, later, as *"`TBD` in every one of its five allocated columns"* |
| Controlled position | `D4` holds **nine populated cells** — **`TBD`** against AP, LDP, BM, BC and TTL; **`—`** against Aut, Chk, CDE and Rcp. *"No allocation is made here (BEP 9.7)."* |
| Where it originated | **T5-C**, in `M5-S7-16` and the Slide 7 material; it then propagated into T5-D's roadmap summary and T5-F-A's `M5V-04` and `M5V-07` |
| Corrected in | **T5-F-A-R**, across all eight permitted files |
| Controlled source changed | **NO.** It was read, not edited |

**What was and was not wrong.**

- **The cell census was always correct.** 297 cells · `—` 131 · `TBD` 10 ·
  `Au` 2 · `Ac` 1 inside `TBD Ac`. `D4`'s five `TBD` cells are five of that ten
  (`D7` contributes one, `A2` four). **No count changes.**
- **The status conclusion was always correct.** Publication / exchange authority
  is unresolved, `D4` makes no allocation, and `P4` versus `D4` remains a valid
  status contrast.
- **The distribution was wrong.** Saying every column reads `TBD` erased four
  populated `—` cells; calling five columns *allocated* implied an allocation the
  source expressly refuses.

**Two teaching points recovered by the correction.**

1. **`D4` is not blank and not uniform.** It is a row in which **four
   applicability decisions are resolved** and **five allocations are not** — a
   sharper illustration of Module 5's own typed-absence discipline than the
   inaccurate version was.
2. **Five `TBD` cells are not a shortlist.** `S1` §9.7 states the authority is
   **not** automatically held by the BIM Manager, BIM Coordinator, CDE
   Administrator, Architect or Lead Delivery Party. **Nothing licenses an
   inference that the eventual holder is one of the five.** Prohibited claim
   **103** now forbids it.

**Effect on totals: none.** 267 statements, classification totals and the
79-exercise count are unchanged; `M5-S7-16` was revised **in place**, retaining
its identifier and its `CONTROLLED` class, and its source basis was **extended**
to include `S2` §1 for the `—` definition.

### 12.16.1 Closure of the remaining comparison-file occurrence — T5-F-A-R2

**CLOSED.** The last active contradiction with the controlled `D4` row has been
corrected. **No current Module 5 file contradicts the controlled matrix.**

**How it was discovered.** During T5-F-A-R's validation sweep,
[`resource-comparison.md`](resource-comparison.md) line 61 was found carrying the
same inaccurate wording as the teaching files — its *Authoriser* row read
*"`D4` Authorise publication / exchange — `TBD` in every column"*, contradicting
`S2` §3.6.

**Why T5-F-A-R did not correct it.** That increment's permitted paths expressly
excluded `resource-comparison.md`. **The file was correctly left untouched
rather than modified outside scope**, and the need was recorded here for the
orchestrator to scope.

**How it was closed.** **T5-F-A-R2 expressly authorised the file.** The
*Authoriser* row now reads: `D4` — **`TBD`** against `AP`, `LDP`, `BM`, `BC` and
`TTL`; **`—`** against `Aut`, `Chk`, `CDE` and `Rcp`; **publication / exchange
authority is unresolved and no allocation is made.**

| Field | Value |
|---|---|
| File | [`resource-comparison.md`](resource-comparison.md), *Authoriser* row |
| Controlled source | `supporting/information-management-responsibility-matrix.md` §1, §2, §3.6 and the `D4` note |
| Controlled source changed | **NO.** It was read, not edited |
| Corrected in | **T5-F-A-R2** |
| Status | **CLOSED** |

**Local consistency confirmed.** The surrounding comparison rows were reviewed
and needed no change: *Cell vocabulary* already quotes both `TBD` and `—`
verbatim; *Blank-field treatment* already states *"There are no blank cells"*;
*Unresolved-field treatment* and *Blocked-field treatment* already record `D4` as
**unresolved, not blocked**; and *Governance / planning / evidence* already
attributes `D4`'s unresolved status to `S1` §9.7. **No general rewrite was
performed.**

**Verified clean:** [`source-inventory.md`](source-inventory.md) contains **no**
statement of the `D4` distribution and needed no correction.

**The correction chain is complete before source production.** The contradiction
originated in T5-C, propagated through T5-D and T5-F-A, was corrected across the
eight teaching and specification files in **T5-F-A-R**, and is closed in the
analysis file here in **T5-F-A-R2**. **No statement, classification, prohibited
claim, census figure or total was altered by either correction.**

### 12.16.2 Second correction in the same increment

Slide 12's transition claimed *"five different words for 'we do not know yet'"*. The five blockers carry **three**
distinct status terms — `UNRESOLVED — TBD` twice, `Not established` twice,
`Not defined` once. The wording is now **"Five matters. Every one typed. None
blank."** **The independent-blocker rule and the five-versus-six variance are
unchanged.**
