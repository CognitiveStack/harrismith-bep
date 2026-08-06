# Module 6 — Source Map, Registers and Prohibited Claims

**Status:** Traceability record for teaching material. **Not governance.**

**Statement-level classification for Slides 1–12** — Slides 1–3 developed in
**T6-A**, Slides 4–8 in **T6-B**, Slides 9–12 in **T6-C** — plus the
classification scheme,
source-authority register, terminology-variance register, hypothesis register,
unresolved-matter register, prohibited-claims register, implementation-evidence
register and boundary-deferral register.

**Slides 13–14 are architecture only.** No statement is classified for them, and
none may be presented as developed.

Source identifiers `S1`–`S14` are defined in
[`source-inventory.md`](source-inventory.md). Resource analysis is in
[`resource-comparison.md`](resource-comparison.md).

---

## 1. Classification scheme

| Class | Meaning |
|---|---|
| **`CONTROLLED`** | Quoted or directly paraphrased from **approved Harrismith governance** — `S1` |
| **`SUPPORTING`** | From an **approved supporting resource** — `S2`–`S6` |
| **`DECISION-RECORD`** | From a **controlled decision, approval, observation or validation record** — `S7`, `S8`, `S9` |
| **`MODULE-2-5`** | Carried forward from **completed teaching interpretation** — `S10`, `S11`, `S12`. The original controlled source is retained alongside |
| **`TEACHING-PLAN`** | From the programme roadmap — `S13` |
| **`INTERP`** | **Assembled from cited sources.** No single source states it in these words, and the sources it rests on are named |
| **`SYNTH`** | **Teaching synthesis with no source citation.** A statement carrying a source reference is never `SYNTH` |
| **`EXCLUDED`** | Named on the slide as something Module 6 **does not** teach or claim |

**The class turns on whether a source is cited, not on whether the wording is
original.** This is the scheme reconciled in Module 5 (`S11`), carried forward
unchanged.

## 2. Source-authority register

| Subject | Governing source | Corroborating | Note |
|---|---|---|---|
| Coordination principles and process | **`S1` §8** | `S2` §1 | `S1` §8.13 defers detail to `S2` |
| Decision terminology | **`S1` §9.2** | `S2` throughout | **Six terms. Not collapsed into "approval"** |
| Coordination detail — checks, triage, taxonomy, statuses | **`S2`** | `S1` §8.6, §8.7 | `S1` expressly declines to define these |
| Which function performs each act | **`S3` §3.5, §3.7** | `S1` §9.13; `S2` §3 | Both expressly defer here |
| Information states and transitions | **`S6`** | `S1` §6, §7 | **Module 4 owns the teaching** (`S10`) |
| Containers and `COORD-01` | **`S4`** | `S2` §4, §8 | **Module 5 owns the teaching** (`S11`) |
| Delivery events | **`S5`** | `S2` §17 | **Module 5 owns the teaching** (`S11`) |
| Publication / exchange authority | **`S1` §9.7** | `S8` §9 | **UNRESOLVED** |
| Recipient acceptance authority | **`S1` §9.8** | `S8` §9 | **No workflow defined** |
| What has been demonstrated | **`S7`, `S8`** | — | `S8` declares **`Authority: None`** |
| Complete governed coordination cycle | **`S7` `GCR-006`** | `S8` §8 | **OPEN — not demonstrated** |
| Coordination visual specification and assets | — | — | **Not created. T6-D and later** |

## 3. Statement classification — Slides 1–12

**Identifier form: `M6-S<slide>-<n>`.** Every statement carries its source
basis, class, governance status and — where applicable — implementation status.

**No preferred statement count was targeted.**

### 3.1 Slide 1 — `M6-S1-01` to `M6-S1-14`

| ID | Statement | Source | Class | Governance | Implementation |
|---|---|---|---|---|---|
| `M6-S1-01` | Module 5 established who is responsible for producing which information | `S11`; `S3`; `S4`; `S5` | `MODULE-2-5` | — | — |
| `M6-S1-02` | **Allocation is not performance** — a matrix records responsibility, never occurrence | `S3` §5; `S11` | `SUPPORTING` | `PROPOSED GOVERNANCE` | `IMPLEMENTATION UNVERIFIED` |
| `M6-S1-03` | Coordination is *"the controlled multidisciplinary process used to identify, communicate, resolve and verify information-interface problems"* | **`S1` §8.1** | **`CONTROLLED`** | `CONTROLLED GOVERNANCE` | — |
| `M6-S1-04` | *"Its purpose is not to generate clash counts"* | **`S1` §8.1** | **`CONTROLLED`** | `CONTROLLED GOVERNANCE` | — |
| `M6-S1-05` | *"A clash count measures how much software found; it says nothing about whether anything was understood, decided or fixed"* | **`S1` §8.1** | **`CONTROLLED`** | `CONTROLLED GOVERNANCE` | — |
| `M6-S1-06` | `S1` §9 is *"the decision-control layer between production and use"* | **`S1` §9.1** | **`CONTROLLED`** | `CONTROLLED GOVERNANCE` | — |
| `M6-S1-07` | Module 6's question concerns the route from a coordination finding to a verified disposition, and which acts stay distinct | `S1` §8, §9.2; `S2` §12–§21; `S13` | **`INTERP`** | — | — |
| `M6-S1-08` | Module 6's evidence boundary: the module teaches governance and records what has been demonstrated separately | `S1` §1.5; `S2` §Classification; `S7`; `S8` | **`INTERP`** | — | — |
| `M6-S1-09` | The four principal resources are approved **with conditions** under `AD-001`, 2026-08-01; **publication NOT AUTHORISED** | `S9`; `S1`, `S2`, `S3` status blocks | `DECISION-RECORD` | `CONTROLLED GOVERNANCE` (approval) | — |
| `M6-S1-10` | `S2`'s coordination arrangements are **`PROPOSED GOVERNANCE`** unless explicitly classified otherwise | `S2` §Classification | `SUPPORTING` | **`PROPOSED GOVERNANCE`** | — |
| `M6-S1-11` | *"This strategy does not describe the live platform"* | **`S2` §Purpose** | `SUPPORTING` | — | **`NOT DEMONSTRATED`** |
| `M6-S1-12` | **`GCR-006` — one complete governed coordination cycle to be exercised and evidenced — remains OPEN** | **`S7` `GCR-006`; `S9`** | `DECISION-RECORD` | — | **`NOT DEMONSTRATED`** |
| `M6-S1-13` | *"Authority comes from governance"* — not from platform access, permission or configuration | **`S1` §9.1** | **`CONTROLLED`** | `CONTROLLED GOVERNANCE` | — |
| `M6-S1-14` | Module 6 does not resolve any open authority, and teaches no Module 4, 5, 7 or 8 content | `S13`; `S1` §9.7, §9.8 | **`EXCLUDED`** | — | — |

**Slide 1 profile.** 5 `CONTROLLED` · 3 `SUPPORTING` · 2 `DECISION-RECORD` ·
1 `MODULE-2-5` · 2 `INTERP` · 1 `EXCLUDED`. **Total 14.** *(`M6-S1-01` is
counted once, as `MODULE-2-5`. Corrected in T6-B by recalculation from the
rows — T6-A recorded 6 `CONTROLLED`.)*

### 3.2 Slide 2 — `M6-S2-01` to `M6-S2-18`

| ID | Statement | Source | Class | Governance | Implementation |
|---|---|---|---|---|---|
| `M6-S2-01` | **Check** — *"Verification against a defined requirement before progression"* | **`S1` §9.2** | **`CONTROLLED`** | `CONTROLLED GOVERNANCE` | — |
| `M6-S2-02` | **Review** — *"Consideration of information for a stated purpose"* | **`S1` §9.2** | **`CONTROLLED`** | `CONTROLLED GOVERNANCE` | — |
| `M6-S2-03` | **Authorise** — *"Permit information to progress, share, publish or exchange for a defined purpose"* | **`S1` §9.2** | **`CONTROLLED`** | `CONTROLLED GOVERNANCE` | — |
| `M6-S2-04` | **Accept** — *"Recipient acknowledges information as suitable or received for the stated purpose, subject to the project arrangement"* | **`S1` §9.2** | **`CONTROLLED`** | `CONTROLLED GOVERNANCE` | — |
| `M6-S2-05` | **Reject** — *"Information is not accepted for the stated progression or use, and action is required"* | **`S1` §9.2** | **`CONTROLLED`** | `CONTROLLED GOVERNANCE` | — |
| `M6-S2-06` | **Coordinate** — *"The multidisciplinary interface process — not design approval"* | **`S1` §9.2** | **`CONTROLLED`** | `CONTROLLED GOVERNANCE` | — |
| `M6-S2-07` | *"These terms are not collapsed into 'approval.' Each names a different decision, made by a different function, against different criteria"* | **`S1` §9.2** | **`CONTROLLED`** | `CONTROLLED GOVERNANCE` | — |
| `M6-S2-08` | *"'Approval' is not used as a catch-all for different decision functions"* | **`S1` §9.1** | **`CONTROLLED`** | `CONTROLLED GOVERNANCE` | — |
| `M6-S2-09` | **Finding** — *"An observed coordination matter requiring triage"* | **`S2` §12** | `SUPPORTING` | **`PROPOSED GOVERNANCE`** | — |
| `M6-S2-10` | **Clash** — *"A geometric or spatial coordination finding generated or identified through review"* | **`S2` §12** | `SUPPORTING` | **`PROPOSED GOVERNANCE`** | — |
| `M6-S2-11` | **Issue** — a governed action record created when a matter requires ownership, action, decision, tracking, verification or escalation, or otherwise needs a controlled project record | **`S2` §12** | `SUPPORTING` | **`PROPOSED GOVERNANCE`** | — |
| `M6-S2-12` | **`Clash / finding ≠ Issue`** | **`S2` §12; `S1` §8.7** | `SUPPORTING` | **`PROPOSED GOVERNANCE`** + `CONTROLLED GOVERNANCE` | — |
| `M6-S2-13` | *"Not every clash becomes an Issue."* Many findings are tolerable, duplicated, out of scope, already known, or artefacts of the test setup | **`S1` §8.7; `S2` §12** | **`CONTROLLED`** | `CONTROLLED GOVERNANCE` | — |
| `M6-S2-14` | *"Creating an issue is a decision"* — taken at triage, not an automatic consequence of detection | **`S1` §8.7; `S2` §12** | **`CONTROLLED`** | `CONTROLLED GOVERNANCE` | — |
| `M6-S2-15` | **`S1` defines Issue more narrowly than `S2`** — variance 3, recorded and not rewritten | `S1` §8.7; `S2` §12 | **`INTERP`** | — | — |
| `M6-S2-16` | *"'Accepted condition' does not mean recipient acceptance or design approval"* — it is a coordination disposition and nothing more | **`S2` §13** | `SUPPORTING` | **`PROPOSED GOVERNANCE`** | — |
| `M6-S2-17` | **Nine objects and acts must stay distinct**; collapsing any two destroys a governed distinction | `S1` §9.1, §9.2; `S2` §12, §13 | **`INTERP`** | — | — |
| `M6-S2-18` | Slide 2 does not teach the triage dispositions, the Issue taxonomy or the status model — **Slides 7, 8 and 10 own them** | `S13` | **`EXCLUDED`** | — | — |

**Slide 2 profile.** 10 `CONTROLLED` · 5 `SUPPORTING` · 2 `INTERP` ·
1 `EXCLUDED`. **The module's most heavily controlled slide** — the decision
vocabulary is BEP §9.2 verbatim.

### 3.3 Slide 3 — `M6-S3-01` to `M6-S3-17`

| ID | Statement | Source | Class | Governance | Implementation |
|---|---|---|---|---|---|
| `M6-S3-01` | The governed cycle runs: controlled Shared inputs → readiness check → federation → coordination checks → findings → triage → create/assign Issues where required → originating task-team WIP correction → task-team check → authorise controlled reshare → Shared → re-coordinate → verify → close/disposition → retain evidence | **`S2` §17** | `SUPPORTING` | **`PROPOSED GOVERNANCE`** | **`NOT DEMONSTRATED`** |
| `M6-S3-02` | `S1` §8.8 states the same governed route, wording *"triage findings"* as one step | **`S1` §8.8** | **`CONTROLLED`** | `CONTROLLED GOVERNANCE` | — |
| `M6-S3-03` | **Variance 1** — `S2` separates *findings* from *triage* and adds a head and tail step. **Both recorded; neither rewritten** | `S1` §8.8; `S2` §17 | **`INTERP`** | — | — |
| `M6-S3-04` | *"The originating task team makes the technical change"*, in its own WIP, through its own checking route | **`S1` §8.8; `S2` §18** | **`CONTROLLED`** | `CONTROLLED GOVERNANCE` | — |
| `M6-S3-05` | *"The BIM Coordinator manages the process, not the solution"* | **`S1` §8.8; `S2` §1** | **`CONTROLLED`** | `CONTROLLED GOVERNANCE` | — |
| `M6-S3-06` | The cycle maps onto the delivery events — `TRN-E01` establishes the input set; `TRN-E02` activates **only for affected containers**; `TRN-E03` is **separate and currently blocked** | **`S2` §17** | `SUPPORTING` | **`PROPOSED GOVERNANCE`** · **`BLOCKED`** (`TRN-E03`) | **`NOT DEMONSTRATED`** |
| `M6-S3-07` | *"Rework returns affected information to the originating task team's WIP. Controlled reshare returns revised information to Shared. Those are the only state transitions in the coordination cycle"* | **`S2` §24; `S6`** | `SUPPORTING` | **`PROPOSED GOVERNANCE`** | — |
| `M6-S3-08` | *"Coordination does not create a new CDE information state"* | **`S2` §24** | `SUPPORTING` | **`PROPOSED GOVERNANCE`** | — |
| `M6-S3-09` | All four principal resources are **`APPROVED WITH CONDITIONS — Training Baseline 0.1`**; `S2`'s content is **`PROPOSED GOVERNANCE`** | `S9`; `S2` §Classification | `DECISION-RECORD` | `CONTROLLED GOVERNANCE` (approval) | — |
| `M6-S3-10` | **One Model Coordination model set exists, with seven included folders and zero coordinated versions** | **`S7` `OF-008`; `S8` §6C** | `DECISION-RECORD` | — | **`OBSERVED — QUALIFIED`** |
| `M6-S3-11` | *"Environment configured ≠ coordination process executed"* | **`S7` `OF-008`** | `DECISION-RECORD` | — | **`NOT DEMONSTRATED`** |
| `M6-S3-12` | **No Design Collaboration Coordination Space was observed configured**; the two Autodesk services are not collapsed | **`S7` `OF-005`, `OF-008`; `S8` §4** | `DECISION-RECORD` | — | **`OBSERVED — QUALIFIED`** |
| `M6-S3-13` | **Two open Client Reviews and one open Coordination-type Issue were observed. "No completed review, authorisation, verification or closure was established"** | **`S7` `OF-007`; `S8` §6B** | `DECISION-RECORD` | — | **`OBSERVED — QUALIFIED`** |
| `M6-S3-14` | Three cycle fragments were observed, and the recorded result is **`PARTIALLY TRACEABLE / NOT YET DEMONSTRATED AS A COMPLETE CYCLE`** | **`S8` §8** | `DECISION-RECORD` | — | **`NOT DEMONSTRATED`** |
| `M6-S3-15` | **`GCR-006` remains OPEN** as a carried IMPLEMENTATION condition of `AD-001` | **`S7`; `S9`** | `DECISION-RECORD` | — | **`NOT DEMONSTRATED`** |
| `M6-S3-16` | **Absence of observation is not observation of absence** — nothing states that other disciplines are absent from the project | **`S8` §7; `S2` §4; `S7` `OF-002`** | `DECISION-RECORD` | — | — |
| `M6-S3-17` | Slide 3 does not teach federation detail, readiness, the interface matrix or triage — **Slides 4–8 own them** | `S13` | **`EXCLUDED`** | — | — |

**Slide 3 profile.** 3 `CONTROLLED` · 4 `SUPPORTING` · 8 `DECISION-RECORD` ·
1 `INTERP` · 1 `EXCLUDED`. **The module's most evidence-heavy slide** — and the
evidence is largely a record of what was not demonstrated.

### 3.4 Slide 4 — `M6-S4-01` to `M6-S4-14`

| ID | Statement | Source | Class | Governance | Implementation |
|---|---|---|---|---|---|
| `M6-S4-01` | Federation is *"the temporary, controlled aggregation of separate discipline or task-team information for coordination purposes"* | **`S1` §8.5** | **`CONTROLLED`** | `CONTROLLED GOVERNANCE` | — |
| `M6-S4-02` | Federation does **not** merge authorship | **`S1` §8.5; `S2` §8** | **`CONTROLLED`** | `CONTROLLED GOVERNANCE` | — |
| `M6-S4-03` | Federation does **not** transfer technical ownership | **`S1` §8.5; `S2` §8** | **`CONTROLLED`** | `CONTROLLED GOVERNANCE` | — |
| `M6-S4-04` | Federation does **not** create a new design author | **`S1` §8.5** | **`CONTROLLED`** | `CONTROLLED GOVERNANCE` | — |
| `M6-S4-05` | Federation does **not** turn discipline models into one jointly-owned authoring model | **`S1` §8.5** | **`CONTROLLED`** | `CONTROLLED GOVERNANCE` | — |
| `M6-S4-06` | *"Originators remain responsible for their own information"* — the federation *"is not a deliverable that anyone authored"* | **`S1` §8.5** | **`CONTROLLED`** | `CONTROLLED GOVERNANCE` | — |
| `M6-S4-07` | *"Nobody becomes responsible for another team's content by appearing alongside it"* | **`S1` §8.5** | **`CONTROLLED`** | `CONTROLLED GOVERNANCE` | — |
| `M6-S4-08` | `COORD-01` is a temporary controlled multidisciplinary coordination aggregation, with the six containers as potential inputs | **`S2` §8; `S4` §3.4** | `SUPPORTING` | **`PROPOSED GOVERNANCE`** | — |
| `M6-S4-09` | `COORD-01` does not merge authorship, transfer technical responsibility, become a jointly-authored design model, replace the discipline containers, or **automatically become a formal deliverable** | **`S2` §8** | `SUPPORTING` | **`PROPOSED GOVERNANCE`** | — |
| `M6-S4-10` | *"The BIM Coordinator leads the federation **process**."* Originating task teams remain responsible for their source information, **before and after federation** | **`S2` §8; `S1` §8.5, §8.8** | `SUPPORTING` | **`PROPOSED GOVERNANCE`** + `CONTROLLED GOVERNANCE` | — |
| `M6-S4-11` | *"Tools do not define responsibility."* Responsibility comes from BEP §4 and §5 | **`S1` §8.4** | **`CONTROLLED`** | `CONTROLLED GOVERNANCE` | — |
| `M6-S4-12` | **Source container, federated view, originator, technical ownership, coordination-process responsibility and deliverable status are six separate things** | `S1` §8.5; `S2` §8; `S4` §3.4 | **`INTERP`** | — | — |
| `M6-S4-13` | **Folder location, platform environment and federation membership do not determine authorship** | `S1` §7.2, §8.4; `S2` §8 | **`INTERP`** | — | — |
| `M6-S4-14` | One Model Coordination model set exists with **zero coordinated versions**; **no completed federation or coordination run has been demonstrated** | **`S7` `OF-008`; `S8` §6C** | `DECISION-RECORD` | — | **`OBSERVED — QUALIFIED`** / **`NOT DEMONSTRATED`** |

**Slide 4 profile.** 8 `CONTROLLED` · 3 `SUPPORTING` · 1 `DECISION-RECORD` ·
2 `INTERP` — **`M6-S4-10` counted once, as `SUPPORTING`**. **Total 14.**

### 3.5 Slide 5 — `M6-S5-01` to `M6-S5-16`

| ID | Statement | Source | Class | Governance | Implementation |
|---|---|---|---|---|---|
| `M6-S5-01` | The coordination input register records **twelve fields**: `Coordination Cycle / Event`, `Container Ref`, `Discipline`, `Originating Party`, `Task Team`, `Information State`, `Version / Revision reference`, `Coordination Purpose`, `Readiness Status`, `Known Limitations / Exclusions`, `Included / Excluded`, `Notes` | **`S2` §4** | `SUPPORTING` | **`PROPOSED GOVERNANCE`** | — |
| `M6-S5-02` | `Information State` **must be `Shared`** for normal coordination | **`S2` §4** | `SUPPORTING` | **`PROPOSED GOVERNANCE`** | — |
| `M6-S5-03` | *"Coordination inputs normally come from controlled Shared information."* **"Uncontrolled WIP is not the normal project coordination input"** | **`S1` §8.3, §6.6** | **`CONTROLLED`** | `CONTROLLED GOVERNANCE` | — |
| `M6-S5-04` | **Ten readiness conditions** are confirmed before inclusion, as applicable — container identity · originator and task team · `Shared` state · coordination purpose · required task-team checks completed · **share authorised** · coordinate and reference context · known omissions and limitations visible · dependencies identified · version or revision identifiable | **`S2` §5** | `SUPPORTING` | **`PROPOSED GOVERNANCE`** | — |
| `M6-S5-05` | *"Coordination readiness is **not** design completeness. Information can be ready to coordinate while remaining incomplete, unapproved and subject to change"* | **`S1` §8.3** | **`CONTROLLED`** | `CONTROLLED GOVERNANCE` | — |
| `M6-S5-06` | Readiness is the **entry condition** to a coordination cycle | `S1` §8.3; `S2` §5 | **`INTERP`** | — | — |
| `M6-S5-07` | *"If an input is not ready, exclude or defer it and record the reason"* | **`S2` §5** | `SUPPORTING` | **`PROPOSED GOVERNANCE`** | — |
| `M6-S5-08` | *"An exclusion with a recorded reason is a governed outcome; coordinating an unready input quietly is not"* | **`S2` §5** | `SUPPORTING` | **`PROPOSED GOVERNANCE`** | — |
| `M6-S5-09` | A coordination cycle is **purpose- and scope-specific**; readiness is assessed against the defined coordination purpose | `S1` §8.3; `S2` §4, §5, §21 | **`INTERP`** | — | — |
| `M6-S5-10` | **Exclusion from one cycle establishes nothing about the project** | `S2` §4, §7; `S8` §7 | **`INTERP`** | — | — |
| `M6-S5-11` | **Being visible or uploaded, being selected as an input, being suitable for the purpose, and being ready are four different conditions** | `S2` §4, §5 | **`INTERP`** | — | — |
| `M6-S5-12` | **Permission to read is a platform capability; authorisation to rely is a governance decision** | **`S1` §9.1, §9.7; `S2` §3** | **`CONTROLLED`** | `CONTROLLED GOVERNANCE` | — |
| `M6-S5-13` | **Observed content and a governed input set are not the same** | `S2` §4, §7; `S7` `OF-002` | **`INTERP`** | — | **`OBSERVED — QUALIFIED`** |
| `M6-S5-14` | *"No live version or revision values are recorded. None were observed or validated, and none is invented"* | **`S2` §4** | `SUPPORTING` | — | **`NOT DEMONSTRATED`** |
| `M6-S5-15` | Only Architecture was observed as a populated direct production stream at the inspected level; **absence of observation is not observation of absence** | **`S7` `OF-002`; `S8` §7; `S2` §4, §7** | `DECISION-RECORD` | — | **`OBSERVED — QUALIFIED`** |
| `M6-S5-16` | The intended coordination environment **remains unresolved** — no Design Collaboration Coordination Space was observed configured, and no configuration is approved | **`S7` `OF-005`; `S2` §6, §26** | `DECISION-RECORD` | **`UNRESOLVED`** | **`OBSERVED — QUALIFIED`** |

**Slide 5 profile.** 3 `CONTROLLED` · 6 `SUPPORTING` · 2 `DECISION-RECORD` ·
5 `INTERP`. **Total 16.**

### 3.6 Slide 6 — `M6-S6-01` to `M6-S6-15`

| ID | Statement | Source | Class | Governance | Implementation |
|---|---|---|---|---|---|
| `M6-S6-01` | *"A check exists because a meaningful interface exists"* | **`S2` §9** | `SUPPORTING` | **`PROPOSED GOVERNANCE`** | — |
| `M6-S6-02` | *"Blind all-versus-all clash testing is not required."* *"Testing everything against everything produces volume, not insight, and buries the findings that matter"* | **`S1` §8.6; `S2` §9** | **`CONTROLLED`** | `CONTROLLED GOVERNANCE` | — |
| `M6-S6-03` | *"Clash detection is **one coordination technique**, not the whole of coordination"* | **`S1` §8.6; `S2` §1** | **`CONTROLLED`** | `CONTROLLED GOVERNANCE` | — |
| `M6-S6-04` | **Six check types** — Hard Clash · Clearance / Access · Alignment / Reference · Spatial Interface · Information / Readiness · Design / Interface Question | **`S2` §10** | `SUPPORTING` | **`PROPOSED GOVERNANCE`** | — |
| `M6-S6-05` | *"Not every category depends on automated clash detection."* Alignment, readiness, spatial-interface and design-question matters are frequently identified **by review**, and are *"no less governed for that"* | **`S2` §10** | `SUPPORTING` | **`PROPOSED GOVERNANCE`** | — |
| `M6-S6-06` | **Twelve proposed training interface checks, `CI-01`–`CI-12`**, across the pairs ARC↔STR, STR↔MEC, STR↔ELE, STR↔PLM, STR↔FIR, ARC↔MEC, ARC↔ELE, ARC↔PLM, ARC↔FIR, MEC↔ELE, MEC↔PLM, MEC↔FIR | **`S2` §9** | `SUPPORTING` | **`PROPOSED`** — all twelve | — |
| `M6-S6-07` | *"These are **PROPOSED TRAINING COORDINATION CHECKS**. They are not evidence of real client requirements, and they do not become project requirements by appearing here"* | **`S2` §9** | `SUPPORTING` | **`PROPOSED GOVERNANCE`** | — |
| `M6-S6-08` | *"Not all possible pairs are built."* The matrix stops at meaningful interfaces rather than completing the combinatorial set | **`S2` §9** | `SUPPORTING` | **`PROPOSED GOVERNANCE`** | — |
| `M6-S6-09` | **Every one of the twelve tolerances or rules remains `TBD`**, by approved coordination requirement, technical standard, system requirement or documented coordination decision | **`S2` §9, §11** | `SUPPORTING` | **`TBD`** | — |
| `M6-S6-10` | *"**A software default tolerance is not a project requirement.** A value shipped with a tool has no governance authority, and adopting it silently would convert a vendor default into a project rule"* | **`S2` §11** | `SUPPORTING` | **`PROPOSED GOVERNANCE`** | — |
| `M6-S6-11` | *"Different interfaces may require different rules."* A single project-wide threshold is not assumed | **`S2` §11** | `SUPPORTING` | **`PROPOSED GOVERNANCE`** | — |
| `M6-S6-12` | *"Where no tolerance is approved, a check must not present a numeric threshold as though it carried governance authority"* | **`S2` §11** | `SUPPORTING` | **`PROPOSED GOVERNANCE`** | — |
| `M6-S6-13` | *"The check may still run; its output is **a finding for triage, not a compliance judgement**"* | **`S2` §11** | `SUPPORTING` | **`PROPOSED GOVERNANCE`** | — |
| `M6-S6-14` | *"A clash count measures how much software found; it says nothing about whether anything was understood, decided or fixed"* | **`S1` §8.1** | **`CONTROLLED`** | `CONTROLLED GOVERNANCE` | — |
| `M6-S6-15` | **No check is recorded as executed**, and no completed coordination run has been demonstrated | **`S7` `OF-008`; `S8` §8** | `DECISION-RECORD` | — | **`NOT DEMONSTRATED`** |

**Slide 6 profile.** 3 `CONTROLLED` · 11 `SUPPORTING` · 1 `DECISION-RECORD`.
**Total 15.**

### 3.7 Slide 7 — `M6-S7-01` to `M6-S7-16`

| ID | Statement | Source | Class | Governance | Implementation |
|---|---|---|---|---|---|
| `M6-S7-01` | **Finding** — *"An observed coordination matter requiring triage"* | **`S2` §12** | `SUPPORTING` | **`PROPOSED GOVERNANCE`** | — |
| `M6-S7-02` | **Clash** — *"A geometric or spatial coordination finding generated or identified through review"* | **`S2` §12** | `SUPPORTING` | **`PROPOSED GOVERNANCE`** | — |
| `M6-S7-03` | **Issue** — a governed action record | **`S2` §12; `S1` §8.7** | `SUPPORTING` | **`PROPOSED GOVERNANCE`** + `CONTROLLED GOVERNANCE` | — |
| `M6-S7-04` | **`Clash / finding ≠ Issue`** | **`S2` §12; `S1` §8.7** | **`CONTROLLED`** | `CONTROLLED GOVERNANCE` | — |
| `M6-S7-05` | *"**Creating an issue is a decision**"* — *"taken at triage, not an automatic consequence of detection"* | **`S1` §8.7; `S2` §12** | **`CONTROLLED`** | `CONTROLLED GOVERNANCE` | — |
| `M6-S7-06` | An Issue is created when a matter requires **ownership, action, decision, tracking, verification or escalation**, *"or otherwise needs a controlled project record"* | **`S2` §12** | `SUPPORTING` | **`PROPOSED GOVERNANCE`** | — |
| `M6-S7-07` | *"Not every clash becomes an Issue. Many findings are **tolerable, duplicated, out of scope, already known, or artefacts of the test setup**"* | **`S1` §8.7; `S2` §12** | **`CONTROLLED`** | `CONTROLLED GOVERNANCE` | — |
| `M6-S7-08` | An Issue should normally carry **what the problem is, the affected information or interface, the responsible task team or role, the required action or outcome, status, and relevant evidence and context** | **`S1` §8.7** | **`CONTROLLED`** | `CONTROLLED GOVERNANCE` | — |
| `M6-S7-09` | A **non-geometric** matter may require a governed record — `Information / Readiness` and `Design / Interface Question` are check types, and neither is a clash | `S2` §10, §12 | **`INTERP`** | — | — |
| `M6-S7-10` | **`S1` §8.7 lists assignment, tracking, decision and verification; `S2` §12 adds ownership, escalation and a residual limb.** The strategy is broader | `S1` §8.7; `S2` §12 | **`INTERP`** | — | — |
| `M6-S7-11` | **Neither Issue definition is rewritten to match the other** — variance 3 | `S1` §8.7; `S2` §12 | **`INTERP`** | — | — |
| `M6-S7-12` | **Creating an Issue does not establish that it was correctly classified, correctly assigned, resolved or verified** | `S1` §8.7; `S2` §12, §19; `S7` `OF-007` | **`INTERP`** | — | **`NOT DEMONSTRATED`** |
| `M6-S7-13` | **Seven `PROPOSED` Issue types** — Clash / Physical Conflict · Clearance / Access · Spatial Interface · Alignment / Reference · Missing / Incomplete Information · Multidisciplinary Design Decision · Coordination Configuration / Process | **`S2` §14** | `SUPPORTING` | **`PROPOSED GOVERNANCE`** | — |
| `M6-S7-14` | *"These are **not Autodesk system-native labels**, and no claim is made that the platform provides them."* Any later mapping *"is an implementation decision, not yet made"* | **`S2` §14** | `SUPPORTING` | **`PROPOSED GOVERNANCE`** | **`NOT DEMONSTRATED`** |
| `M6-S7-15` | *"This BEP does not define project issue numbering or status codes."* Detailed taxonomy belongs in the Coordination & Review Strategy | **`S1` §8.7** | **`CONTROLLED`** | `CONTROLLED GOVERNANCE` | — |
| `M6-S7-16` | **One open Coordination-type Issue was observed**; *"No completed review, authorisation, verification or closure was established"* | **`S7` `OF-007`; `S8` §6B** | `DECISION-RECORD` | — | **`OBSERVED — QUALIFIED`** / **`NOT DEMONSTRATED`** |

**Slide 7 profile.** 5 `CONTROLLED` · 6 `SUPPORTING` · 1 `DECISION-RECORD` ·
4 `INTERP` — **`M6-S7-03` counted once, as `SUPPORTING`**. **Total 16** *(one
`INTERP` row, `M6-S7-12`, also carries an implementation status)*.

### 3.8 Slide 8 — `M6-S8-01` to `M6-S8-15`

| ID | Statement | Source | Class | Governance | Implementation |
|---|---|---|---|---|---|
| `M6-S8-01` | **No action / false positive** — *"Not a real coordination matter for the defined check"* | **`S2` §13** | `SUPPORTING` | **`PROPOSED GOVERNANCE`** | — |
| `M6-S8-02` | **Accepted condition** — *"Requires no further action for the defined check and coordination purpose"* | **`S2` §13** | `SUPPORTING` | **`PROPOSED GOVERNANCE`** | — |
| `M6-S8-03` | **Action required — one task team** — *"A single team must respond"* | **`S2` §13** | `SUPPORTING` | **`PROPOSED GOVERNANCE`** | — |
| `M6-S8-04` | **Action required — multiple task teams** — *"More than one team must respond"* | **`S2` §13** | `SUPPORTING` | **`PROPOSED GOVERNANCE`** | — |
| `M6-S8-05` | **Decision required** — *"A technical or governance decision is needed before action"* | **`S2` §13** | `SUPPORTING` | **`PROPOSED GOVERNANCE`** | — |
| `M6-S8-06` | **Deferred** — *"Carried forward, with a recorded reason"* | **`S2` §13** | `SUPPORTING` | **`PROPOSED GOVERNANCE`** | — |
| `M6-S8-07` | **Escalated** — *"Raised beyond the normal cycle"* | **`S2` §13, §23** | `SUPPORTING` | **`PROPOSED GOVERNANCE`** | — |
| `M6-S8-08` | **The register records exactly seven dispositions.** No eighth exists | **`S2` §13** | `SUPPORTING` | **`PROPOSED GOVERNANCE`** | — |
| `M6-S8-09` | *"**Material dispositions remain traceable.** A finding closed without record is a finding that will be rediscovered"* | **`S2` §13** | `SUPPORTING` | **`PROPOSED GOVERNANCE`** | — |
| `M6-S8-10` | *"**'Accepted condition' does not mean recipient acceptance or design approval.** It means only that the coordination finding requires no further action for the defined check and coordination purpose. It is a coordination disposition and nothing more"* | **`S2` §13** | `SUPPORTING` | **`PROPOSED GOVERNANCE`** | — |
| `M6-S8-11` | **Accept** is a **recipient** function occurring **after delivery**, and its authority is **UNRESOLVED** — no Appointing Party acceptance workflow is defined | **`S1` §9.2, §9.8** | **`CONTROLLED`** | **`UNRESOLVED`** | **`NOT DEMONSTRATED`** |
| `M6-S8-12` | A triage disposition is **not an Issue status** — the status model is a separate construct | `S2` §13, §15 | **`INTERP`** | — | — |
| `M6-S8-13` | A triage disposition is **not an information state** — *"Coordination does not create a new CDE information state"* | **`S2` §24; `S6`** | `SUPPORTING` | **`PROPOSED GOVERNANCE`** | — |
| `M6-S8-14` | A triage disposition is **not a suitability code** — **no suitability code set exists on this project** | `S1` §11; `S11` — teaching carry-forward | **`MODULE-2-5`** | **`NOT ESTABLISHED`** | — |
| `M6-S8-15` | **`Accepted condition` does not release `T4`, resolve recipient acceptance authority, or unblock `TRN-E03`** | `S1` §9.7, §9.8; `S5` §5.1; `S6`; `S10`, `S11` | **`INTERP`** | **`BLOCKED`** / **`UNRESOLVED`** | **`NOT DEMONSTRATED`** |

**Slide 8 profile.** 1 `CONTROLLED` · 11 `SUPPORTING` · 1 `MODULE-2-5` ·
2 `INTERP`. **Total 15.**

### 3.9 Slide 9 — `M6-S9-01` to `M6-S9-15`

| ID | Statement | Source | Class | Governance | Implementation |
|---|---|---|---|---|---|
| `M6-S9-01` | An assignment identifies **the affected interface** | **`S2` §16** | `SUPPORTING` | **`PROPOSED GOVERNANCE`** | — |
| `M6-S9-02` | An assignment identifies **the responsible task team or function** | **`S2` §16** | `SUPPORTING` | **`PROPOSED GOVERNANCE`** | — |
| `M6-S9-03` | An assignment identifies **the required action or outcome** | **`S2` §16** | `SUPPORTING` | **`PROPOSED GOVERNANCE`** | — |
| `M6-S9-04` | An assignment identifies **context and evidence** | **`S2` §16** | `SUPPORTING` | **`PROPOSED GOVERNANCE`** | — |
| `M6-S9-05` | An assignment identifies **priority or impact — *where established*** | **`S2` §16** | `SUPPORTING` | **`PROPOSED GOVERNANCE`** | — |
| `M6-S9-06` | An assignment identifies **status** | **`S2` §16** | `SUPPORTING` | **`PROPOSED GOVERNANCE`** | — |
| `M6-S9-07` | An assignment identifies **a target trigger — *only where genuinely established*** | **`S2` §16** | `SUPPORTING` | **`PROPOSED GOVERNANCE`** | — |
| `M6-S9-08` | *"**No dates are invented.** Where no target is established, the field records that rather than a plausible value"* | **`S2` §16** | `SUPPORTING` | **`PROPOSED GOVERNANCE`** | — |
| `M6-S9-09` | *"The **BIM Coordinator coordinates assignment.** The originating or affected **Task-Team Lead owns the technical response** of its team"* | **`S2` §16** | `SUPPORTING` | **`PROPOSED GOVERNANCE`** | — |
| `M6-S9-10` | *"An Issue assigned to a task team **does not make the BIM Coordinator responsible for designing the fix**. Coordinating an assignment and owning a solution are different things"* | **`S2` §16** | `SUPPORTING` | **`PROPOSED GOVERNANCE`** | — |
| `M6-S9-11` | **Technical resolution occurs in the originating task team's WIP** — the team evaluates and modifies its own container if required | **`S2` §18; `S1` §8.8, §8.10** | **`CONTROLLED`** | `CONTROLLED GOVERNANCE` | — |
| `M6-S9-12` | *"The BIM Coordinator may **facilitate agreement** between teams but **does not author a discipline solution** merely because they chair coordination"* | **`S2` §18; `S1` §8.8** | `SUPPORTING` | **`PROPOSED GOVERNANCE`** + `CONTROLLED GOVERNANCE` | — |
| `M6-S9-13` | *"Where multiple task teams must change, **each remains responsible for its own information**. A jointly-agreed resolution is still **a set of separate changes under separate responsibility**"* | **`S2` §18** | `SUPPORTING` | **`PROPOSED GOVERNANCE`** | — |
| `M6-S9-14` | **`X3` — resolve technical coordination issue — allocates `P` to Author and Task-Team Lead, `Ck` to Checker, `Co` to BIM Coordinator.** The coordinator coordinates; the team resolves | **`S3` §3.5** | `SUPPORTING` | **`PROPOSED GOVERNANCE`** | **`IMPLEMENTATION UNVERIFIED`** |
| `M6-S9-15` | **Issue assignment, process coordination, technical authorship, technical response, WIP correction, task-team check and controlled reshare are seven separate things**, and **no assignment, response or correction has been demonstrated** — *"No actual Issue identifiers are created here"* | `S2` §16, §17, §18; `S7` `OF-007`; `S8` §8 | **`INTERP`** | — | **`NOT DEMONSTRATED`** |

**Slide 9 profile.** 1 `CONTROLLED` · 13 `SUPPORTING` · 1 `INTERP` —
**`M6-S9-12` counted once, as `SUPPORTING`**. **Total 15.**

### 3.10 Slide 10 — `M6-S10-01` to `M6-S10-16`

| ID | Statement | Source | Class | Governance | Implementation |
|---|---|---|---|---|---|
| `M6-S10-01` | The governed status model runs **`New` → `Triaged` → `Assigned` → `In Progress` → `Ready for Verification` → `Closed`** | **`S2` §15** | `SUPPORTING` | **`PROPOSED GOVERNANCE`** | — |
| `M6-S10-02` | **`Deferred` and `Escalated` are *controlled alternate dispositions*** — **not a seventh and eighth step** in the main sequence | **`S2` §15** | `SUPPORTING` | **`PROPOSED GOVERNANCE`** | — |
| `M6-S10-03` | *"Platform implementation may use different native labels. **The governed meaning is what matters; a native label is a rendering of it, not a replacement for it**"* | **`S2` §15** | `SUPPORTING` | **`PROPOSED GOVERNANCE`** | — |
| `M6-S10-04` | *"**This status model is not claimed to be configured in Forma.** Configuring it would follow a governance decision, which has not been taken"* | **`S2` §15; `S1` §12.1** | `SUPPORTING` | **`PROPOSED GOVERNANCE`** | **`NOT DEMONSTRATED`** |
| `M6-S10-05` | An Issue status is **not an information state** — *"Coordination does not create a new CDE information state"* | **`S2` §24; `S6`** | `SUPPORTING` | **`PROPOSED GOVERNANCE`** | — |
| `M6-S10-06` | An Issue status is **not a suitability code** — **no suitability code set exists on this project** | `S1` §11; `S11` — teaching carry-forward | **`MODULE-2-5`** | **`NOT ESTABLISHED`** | — |
| `M6-S10-07` | An Issue status is **not recipient acceptance** — a separate function occurring after delivery, whose authority is **UNRESOLVED** | **`S1` §9.2, §9.8** | **`CONTROLLED`** | **`UNRESOLVED`** | — |
| `M6-S10-08` | An Issue status is **not publication authorisation** — a separate decision, and **UNRESOLVED** | **`S1` §9.7** | **`CONTROLLED`** | **`UNRESOLVED`** | — |
| `M6-S10-09` | An Issue status is **not technical evidence** | `S2` §15, §19; `S7` `OF-007` | **`INTERP`** | — | — |
| `M6-S10-10` | **`Ready for Verification` means verification remains to be performed** — the status records a queue position, not an outcome | `S2` §15, §19 | **`INTERP`** | — | — |
| `M6-S10-11` | **`Closed` as a label does not, by itself, prove the closure conditions were met** — closure follows re-coordination against reshared, controlled information | **`S2` §19** | `SUPPORTING` | **`PROPOSED GOVERNANCE`** | — |
| `M6-S10-12` | **A status change does not demonstrate that the technical condition changed** | **`S2` §19; `S7` `OF-007`** | `SUPPORTING` | **`PROPOSED GOVERNANCE`** | **`NOT DEMONSTRATED`** |
| `M6-S10-13` | **Two Client Reviews and one Coordination-type Issue were observed open** | **`S7` `OF-007`; `S8` §6B** | `DECISION-RECORD` | — | **`OBSERVED — QUALIFIED`** |
| `M6-S10-14` | *"Review and issue **activity** exists in the platform. This is **not** evidence that a governed review, authorisation or verification decision has been taken. **An open item is an open item**"* | **`S7` `OF-007`** | `DECISION-RECORD` | — | **`NOT DEMONSTRATED`** |
| `M6-S10-15` | **`Deferred` and `Escalated` appear in two related but distinct structures** — triage dispositions (`S2` §13) and controlled alternate status dispositions (`S2` §15). **Neither structure is merged into the other** | `S2` §13, §15 | **`INTERP`** | — | — |
| `M6-S10-16` | No new terminology variance arises — **variance 2 already records that `S1` defines no status codes and defers the model to `S2`** | `S1` §8.7; `S2` §15 | **`INTERP`** | — | — |

**Slide 10 profile.** 2 `CONTROLLED` · 7 `SUPPORTING` · 2 `DECISION-RECORD` ·
1 `MODULE-2-5` · 4 `INTERP`. **Total 16.**

### 3.11 Slide 11 — `M6-S11-01` to `M6-S11-16`

| ID | Statement | Source | Class | Governance | Implementation |
|---|---|---|---|---|---|
| `M6-S11-01` | Verification occurs **after** the corrected information has been **checked** | **`S2` §19** | `SUPPORTING` | **`PROPOSED GOVERNANCE`** | — |
| `M6-S11-02` | Verification occurs after the information has been **authorised for reshare** | **`S2` §19** | `SUPPORTING` | **`PROPOSED GOVERNANCE`** | — |
| `M6-S11-03` | Verification occurs after the information has been **returned to `Shared`** | **`S2` §19; `S6`** | `SUPPORTING` | **`PROPOSED GOVERNANCE`** | — |
| `M6-S11-04` | Verification occurs after the information has been **included in re-coordination** | **`S2` §19** | `SUPPORTING` | **`PROPOSED GOVERNANCE`** | — |
| `M6-S11-05` | Verify that the defined coordination matter **no longer exists** | **`S2` §19** | `SUPPORTING` | **`PROPOSED GOVERNANCE`** | — |
| `M6-S11-06` | **or** that it **meets the agreed coordination rule** | **`S2` §19** | `SUPPORTING` | **`PROPOSED GOVERNANCE`** | — |
| `M6-S11-07` | **or** that it **has an explicitly approved and recorded disposition** | **`S2` §19** | `SUPPORTING` | **`PROPOSED GOVERNANCE`** | — |
| `M6-S11-08` | *"**A material Issue is not closed solely because someone says it was fixed in WIP.** Closure follows re-coordination against reshared, controlled information — **a change nobody can see in Shared information has not been demonstrated**"* | **`S2` §19** | `SUPPORTING` | **`PROPOSED GOVERNANCE`** | — |
| `M6-S11-09` | *"**Verification does not equal** design approval, professional certification, publication authority, or recipient acceptance"* | **`S2` §19; `S1` §8.10, §9.5** | **`CONTROLLED`** | `CONTROLLED GOVERNANCE` | — |
| `M6-S11-10` | **Checking is not verification** — *"Checking confirms readiness for the next controlled decision"* | **`S1` §9.3** | **`CONTROLLED`** | `CONTROLLED GOVERNANCE` | — |
| `M6-S11-11` | **A technical response is not verification** — it is the change, not the check on it | `S2` §18, §19 | **`INTERP`** | — | — |
| `M6-S11-12` | **`Ready for Verification` is not verification**, and **Issue status alone is not verification evidence** | `S2` §15, §19 | **`INTERP`** | — | — |
| `M6-S11-13` | *"Technical and design responsibility remains with the originating task team, **before and after verification**"* | **`S1` §8.10** | **`CONTROLLED`** | `CONTROLLED GOVERNANCE` | — |
| `M6-S11-14` | **`X4` — verify coordination resolution / process disposition — allocates `Ck` to the BIM Coordinator.** *"Coordinator verification confirms the coordination process reached a disposition — it is not discipline design approval, professional certification, or acceptance of technical responsibility"* | **`S3` §3.5** | `SUPPORTING` | **`PROPOSED GOVERNANCE`** | **`IMPLEMENTATION UNVERIFIED`** |
| `M6-S11-15` | **Whether verification is mandatory in every cycle is `NOT ESTABLISHED`** — `S1` §8.10 says the BIM Coordinator *"may verify"*; `S2` §19 and `S3` `X4` treat it as a defined act; `S2` §21 conditions it on *"required verification"*. **Variance 4 and `H18`. Module 6 does not decide it** | `S1` §8.10; `S2` §19, §21; `S3` `X4` | **`INTERP`** | **`NOT ESTABLISHED`** | — |
| `M6-S11-16` | **No completed verification has been established** — *"No completed review, authorisation, verification or closure was established"* | **`S7` `OF-007`; `S8` §8** | `DECISION-RECORD` | — | **`NOT DEMONSTRATED`** |

**Slide 11 profile.** 3 `CONTROLLED` · 9 `SUPPORTING` · 1 `DECISION-RECORD` ·
3 `INTERP`. **Total 16.**

### 3.12 Slide 12 — `M6-S12-01` to `M6-S12-16`

| ID | Statement | Source | Class | Governance | Implementation |
|---|---|---|---|---|---|
| `M6-S12-01` | *"**Completion is not 'zero clashes.'** A zero-clash report can be produced by **testing nothing**, **excluding everything**, or **resolving symptoms rather than interfaces**"* | **`S1` §8.11; `S2` §21** | **`CONTROLLED`** | `CONTROLLED GOVERNANCE` | — |
| `M6-S12-02` | Completion condition 1 — **required inputs were identified** | **`S2` §21** | `SUPPORTING` | **`PROPOSED GOVERNANCE`** | **`NOT DEMONSTRATED`** |
| `M6-S12-03` | Condition 2 — **required readiness checks were performed** | **`S2` §21** | `SUPPORTING` | **`PROPOSED GOVERNANCE`** | **`NOT DEMONSTRATED`** |
| `M6-S12-04` | Condition 3 — **required coordination checks were performed** | **`S2` §21; `S1` §8.11** | `SUPPORTING` | **`PROPOSED GOVERNANCE`** | **`NOT DEMONSTRATED`** |
| `M6-S12-05` | Condition 4 — **material findings were triaged** | **`S2` §21; `S1` §8.11** | `SUPPORTING` | **`PROPOSED GOVERNANCE`** | **`NOT DEMONSTRATED`** |
| `M6-S12-06` | Condition 5 — **required Issues were created and assigned** | **`S2` §21; `S1` §8.11** | `SUPPORTING` | **`PROPOSED GOVERNANCE`** | **`NOT DEMONSTRATED`** |
| `M6-S12-07` | Condition 6 — **required resolutions or dispositions were recorded** | **`S2` §21; `S1` §8.11** | `SUPPORTING` | **`PROPOSED GOVERNANCE`** | **`NOT DEMONSTRATED`** |
| `M6-S12-08` | Condition 7 — **required verification was completed** | **`S2` §21; `S1` §8.11** | `SUPPORTING` | **`PROPOSED GOVERNANCE`** | **`NOT DEMONSTRATED`** |
| `M6-S12-09` | Condition 8 — **unresolved matters were explicitly carried forward or escalated** | **`S2` §21; `S1` §8.11** | `SUPPORTING` | **`PROPOSED GOVERNANCE`** | **`NOT DEMONSTRATED`** |
| `M6-S12-10` | Condition 9 — **coordination evidence was retained** | **`S2` §21** | `SUPPORTING` | **`PROPOSED GOVERNANCE`** | **`NOT DEMONSTRATED`** |
| `M6-S12-11` | The conditions apply **"for a defined coordination cycle"** and **"as applicable"**, and seven are qualified by **"required"** or **"material"**. **They are not an unconditional universal checklist** | **`S2` §21** | `SUPPORTING` | **`PROPOSED GOVERNANCE`** | — |
| `M6-S12-12` | *"**Completion is cycle-specific and purpose-specific.**"* Completion of one cycle establishes nothing about every other coordination need | **`S2` §21; `S1` §8.11** | **`CONTROLLED`** | `CONTROLLED GOVERNANCE` | — |
| `M6-S12-13` | **A cycle may complete with an unresolved matter explicitly carried forward or escalated** — condition 8. **Carrying a matter forward is a governed outcome, not concealment** | `S2` §21; `S1` §8.11, §8.12 | **`INTERP`** | — | — |
| `M6-S12-14` | *"It does **not** mean the entire design is complete, technically approved, construction-ready, or accepted by the project"* | **`S2` §21; `S1` §8.11** | **`CONTROLLED`** | `CONTROLLED GOVERNANCE` | — |
| `M6-S12-15` | **Completion does not publish information, resolve recipient acceptance authority, release `T4` or unblock `TRN-E03`** | `S1` §9.7, §9.8; `S5` §5.1; `S6`; `S10`, `S11` | **`INTERP`** | **`UNRESOLVED`** / **`BLOCKED`** | **`NOT DEMONSTRATED`** |
| `M6-S12-16` | **No coordination cycle has been completed**, and **`GCR-006` remains OPEN**. **Module 6 teaching cannot close it** — only evidence of a complete governed cycle could | **`S7` `GCR-006`; `S8` §8; `S9`** | `DECISION-RECORD` | — | **`NOT DEMONSTRATED`** |

**Slide 12 profile.** 3 `CONTROLLED` · 10 `SUPPORTING` · 1 `DECISION-RECORD` ·
2 `INTERP` — **`M6-S12-01`, `M6-S12-12` and `M6-S12-14` counted once each, as
`CONTROLLED`**. **Total 16.**

### 3.13 Totals for the developed slides

**Recalculated from the completed rows.**

| Class | Slides 1–3 | Slides 4–8 | Slides 9–12 | Total |
|---|---:|---:|---:|---:|
| `CONTROLLED` | 18 | 20 | 9 | **47** |
| `SUPPORTING` | 12 | 37 | 39 | **88** |
| `DECISION-RECORD` | 10 | 5 | 4 | **19** |
| `MODULE-2-5` | 1 | 1 | 1 | **3** |
| `TEACHING-PLAN` | 0 | 0 | 0 | **0** |
| `INTERP` | 5 | 13 | 10 | **28** |
| `SYNTH` | 0 | 0 | 0 | **0** |
| `EXCLUDED` | 3 | 0 | 0 | **3** |
| **Total** | **49** | **76** | **63** | **188** |

**Per-slide totals.** S1 14 · S2 18 · S3 17 · S4 14 · S5 16 · S6 15 · S7 16 ·
S8 15 · S9 15 · S10 16 · S11 16 · S12 16 = **188**.

**No count and no class distribution was targeted.** **One aggregate was
corrected by recalculation in T6-C** — the Slide 12 profile, drafted as
4 `CONTROLLED`, which the rows give as **3**. **No individual classification was
altered.** **Slides 13–14 contribute nothing — they are architecture only.**

## 4. Terminology-variance register

**Six variances, all recorded, none harmonised.** Full detail in
[`source-inventory.md`](source-inventory.md) §5.

| # | Variance | Module 6 position |
|---|---|---|
| **1** | Cycle-step wording — `S1` §8.8 versus `S2` §17 | Teach `S2`'s sequence; record `S1`'s one-step wording |
| **2** | Issue status vocabulary — `S1` §8.7 defines none; `S2` §15 proposes six plus two | **No conflict.** `S1` expressly defers |
| **3** | Scope of "Issue" — `S2` §12 broader than `S1` §8.7 | Teach `S2`'s; record `S1`'s as narrower |
| **4** | Verification — `S1` §8.10 *"may verify"*; `S2` §19 and `S3` `X4` definite | **Record both. Do not resolve whether verification is mandatory in every cycle** |
| **5** | "Accepted condition" (triage) versus "Accept" (recipient) | **Keep apart.** `S2` §13 states the distinction expressly |
| **6** | "Review" as a governed decision term versus an observed platform artefact | Governed term is `S1` §9.2; `OF-007` instances evidence **activity** |

## 5. Hypothesis register

**Fifteen provisional hypotheses tested against the sources.** Classification is
from evidence. **No preferred number of confirmations or rejections was
targeted.**

| # | Hypothesis | Result | Basis |
|---|---|---|---|
| **H1** | A coordination finding, a clash and an Issue are not automatically the same object | **`CONFIRMED`** | **`S2` §12** defines all three separately and states **`Clash / finding ≠ Issue`**; **`S1` §8.7** distinguishes *"Clash / finding"* from *"Issue"* |
| **H2** | A finding does not become an Issue merely because it is visible or detected | **`CONFIRMED`** | **`S1` §8.7** — *"Creating an issue is a decision."* **`S2` §12** — *"a decision taken at triage, not an automatic consequence of detection"*. **`S1` §8.6** — *"A clash result is triaged before any formal issue is created"* |
| **H3** | Federation assembles information for coordination but does not merge authorship, technical ownership or originator responsibility | **`CONFIRMED`** | **`S1` §8.5** — federation does not *"merge authorship"*, *"transfer technical ownership"*, *"create a new design author"*. **`S2` §8** repeats it for `COORD-01`. **`S1` §8.5** — *"nobody becomes responsible for another team's content by appearing alongside it"* |
| **H4** | Check, Review, Coordinate, Authorise, Accept and Reject are distinct acts unless a controlled source expressly combines them | **`CONFIRMED`** | **`S1` §9.2** defines all six and states *"These terms are not collapsed into 'approval.'"* **§9.1** — *"'Approval' is not used as a catch-all"*. **§9.12** — role combination *"does not collapse the meanings of the decisions"* |
| **H5** | A technical response is not the same as verification | **`CONFIRMED`** | **`S2` §19** — verification occurs **after** the corrected information has been checked, authorised, returned to Shared and re-coordinated. *"A material Issue is not closed solely because someone says it was fixed in WIP"* |
| **H6** | Resolution, verification and closure are separate conditions | **`CONFIRMED`** | **`S1` §8.10** and **`S2` §17–§19** sequence them as distinct steps. **`S2` §19** — closure follows re-coordination against reshared controlled information; *"a change nobody can see in Shared information has not been demonstrated"* |
| **H7** | Changing an Issue status is not evidence that the underlying technical condition was corrected | **`CONFIRMED`** | **`S2` §19** — as H5. **`S7` `OF-007`** — *"Review and issue activity exists in the platform. This is not evidence that a governed review, authorisation or verification decision has been taken"* |
| **H8** | An Issue status is not an information state, suitability code or approval decision | **`CONFIRMED`** | **`S2` §24** — *"Coordination does not create a new CDE information state"*; coordination input is *"a use and context, not a state"*. **`S6`** — only `T1` and `T4` change the state. **`S1` §9.5** — a coordination disposition is not design approval |
| **H9** | A closed Issue does not, by itself, prove that every affected information container was updated, checked and shared correctly | **`CONFIRMED WITH QUALIFICATION`** | **`S2` §19** requires closure to follow re-coordination against reshared controlled information — so a *correctly operated* closure implies more than status alone. **But `S2` §21** makes completion **cycle- and purpose-specific**, and **`S2` §17** notes a cycle may activate one `TRN-E02` row, several **or none**. **The qualification: closure evidences the defined coordination matter, not the whole container set** |
| **H10** | Assurance sampling is not certification, a guarantee of the entire model, or proof of regulatory compliance | **`CONFIRMED WITH QUALIFICATION`** | **`S1` §8.10** — verification is not *"professional certification"*. **`S2` §21** — completion *"does not mean the entire design is complete, technically approved, construction-ready, or accepted"*. **Qualification: no source uses the phrase "assurance sampling."** `S3` §3.7 allocates `A1`–`A5` for **change** assurance, and `S2` §3 records the BIM Manager *"supports assurance"* without defining a sampling method. **A sampling regime is `NOT ESTABLISHED`** |
| **H11** | A platform capability does not create a governance requirement, role, authority or acceptance rule | **`CONFIRMED`** | **`S1` §9.1** — *"Authority comes from governance. Not from platform access, permission or configuration."* **§9.7** — *"Platform write permission is not publication authority."* **§8.4** — *"Tools do not define responsibility."* **`S7` `OF-005`** — *"Presence of a capability is not maturity"*. **`S8` §11** — *"platform role ≠ professional appointment ≠ governance authority"* |
| **H12** | A complete coordination cycle has not been demonstrated while `GCR-006` remains open | **`CONFIRMED`** | **`S7`** — `GCR-006` **IMPLEMENTATION — open**, carried by `AD-001`. **`S8` §8** — *"No complete traceable cycle was observed"*; result **`PARTIALLY TRACEABLE / NOT YET DEMONSTRATED AS A COMPLETE CYCLE`** |
| **H13** | Absence of observed Issues, findings or clashes is not evidence that none exist | **`CONFIRMED`** | **`S8` §7** — *"Absence of observation is not observation of absence. Nothing here states that other disciplines are absent from the project."* **`S2` §4** and **§7** repeat it. **`S2` §7** — *"Limited observed content does not mean coordination is absent"* |
| **H14** | No named holder or organisation may be inferred for a checking, reviewing, authorising or accepting function | **`CONFIRMED`** | **`S2` §3** — *"All holders remain TBD."* **`S1` §8.2** — *"No actual people are appointed."* **`S1` §9.7** — publication authority **UNRESOLVED**, not automatically the BIM Manager, BIM Coordinator, CDE Administrator or Architect. **`S1` §9.8** — no acceptance workflow defined |
| **H15** | A coordination model or federated view does not automatically become a contractual deliverable | **`CONFIRMED`** | **`S2` §8** — `COORD-01` does not *"automatically become a formal deliverable"*. **`S1` §8.5** — federation *"is not a deliverable that anyone authored"*. **`S4` §3.4** (via `S11`) — not a deliverable unless explicitly scheduled as one |

### 5.1 Hypotheses arising from source comparison

**Three further hypotheses arose during comparison and are recorded here.**

| # | Hypothesis | Result | Basis |
|---|---|---|---|
| **H16** | The twelve interface checks are proposed training checks, not project requirements | **`CONFIRMED`** | **`S2` §9** — *"These are PROPOSED TRAINING COORDINATION CHECKS. They are not evidence of real client requirements, and they do not become project requirements by appearing here"* |
| **H17** | No numeric coordination tolerance exists, and a software default does not supply one | **`CONFIRMED`** | **`S2` §11** — every check's tolerance is **`TBD`**. *"A software default tolerance is not a project requirement."* *"Where no tolerance is approved, a check must not present a numeric threshold as though it carried governance authority"* |
| **H18** | Verification is mandatory in every coordination cycle | **`NOT ESTABLISHED`** | **Variance 4.** `S1` §8.10 — the BIM Coordinator **"may verify"**. `S2` §19 and `S3` `X4` treat it as a defined step. `S2` §21 requires *"required verification was completed"* — **conditioned on "required"**. **The sources do not settle whether every cycle requires it, and Module 6 does not decide** |

**18 hypotheses — 15 `CONFIRMED` · 2 `CONFIRMED WITH QUALIFICATION` · 1 `NOT
ESTABLISHED` · 0 `CONTRADICTED`.** `15 + 2 + 1 + 0 = 18`.

| Result | Hypotheses | Count |
|---|---|---:|
| **`CONFIRMED`** | `H1`–`H8`, `H11`–`H17` | **15** |
| **`CONFIRMED WITH QUALIFICATION`** | `H9`, `H10` | **2** |
| **`NOT ESTABLISHED`** | `H18` | **1** |
| **`CONTRADICTED`** | — | **0** |
| **Total** | `H1`–`H18` | **18** |

**`H10`'s assurance-sampling finding is a qualification within `H10`, not a
separate result.** `H10` confirms that assurance sampling is not certification, a
guarantee or proof of compliance; **the qualification is that no source defines
an assurance-sampling method at all**, recorded as `U14`. **It is one
hypothesis with one result, and it is not counted twice.**

**Fifteen hypotheses came from the increment brief (`H1`–`H15`); three arose
from source comparison (`H16`–`H18`).** No hypothesis was manufactured to
balance the register, and **no result was adjusted to reach a preferred total**.

## 6. Unresolved-matter register

| # | Matter | Status | Source |
|---|---|---|---|
| **U1** | **Numeric clash and clearance tolerances** — all twelve checks | **`TBD`** | `S2` §11, §26 |
| **U2** | **Intended coordination environment and its configuration** | **Not decided or approved** | `S2` §26; `S7` `OF-005` |
| **U3** | **Issue taxonomy and status platform mapping** | **Not yet implemented** | `S2` §14, §15, §26 |
| **U4** | **Coordination-cycle frequency** | **Not established** | `S2` §20, §26 |
| **U5** | **Coordination completion evidence format** | **`PROPOSED` — to be validated** | `S2` §26 |
| **U6** | **Coordinate reference basis for coordinated model use** | **Candidate context only, not approved** | `S2` §26; `S1` §11.5 |
| **U7** | **`UD-001` — MEP / Structural team-space mapping** | **UNRESOLVED** — not corrected, not a non-conformance | `S2` §7, §26; `S7` |
| **U8** | **Governance-change authority (`A2`)** | **`TBD` across four roles.** *"No single universal approver exists"* | `S3` §3.7; `S1` §12.7 |
| **U9** | **Implementation verifier (`A4`)** | *"No single universal verifier is defined"* | `S3` §3.7; `S1` §12.9 |
| **U10** | **Publication / exchange authority** | **UNRESOLVED — `TBD`** | `S1` §9.7 |
| **U11** | **Recipient acceptance authority** | **No workflow defined; none invented** | `S1` §9.8 |
| **U12** | **A complete governed coordination cycle** | **`GCR-006` OPEN — not demonstrated** | `S7`; `S8` §8 |
| **U13** | **Whether verification is required in every cycle** | **`NOT ESTABLISHED`** — see H18 | Variance 4 |
| **U14** | **Assurance sampling method** | **`NOT ESTABLISHED`** — no source defines one | H10 |

**Fourteen unresolved matters. Module 6 resolves none of them.**

## 7. Implementation-evidence register

Full table in [`source-inventory.md`](source-inventory.md) §4. **The position in
summary:**

| Question | Answer | Source |
|---|---|---|
| Is a coordination environment provisioned? | **Partly.** One Model Coordination model set, seven folders, **zero coordinated versions** | `S7` `OF-008`; `S8` §6C |
| Is the Coordination Space configured? | **No** | `S7` `OF-005`; `S8` §4 |
| Does review and Issue activity exist? | **Yes — activity.** Two open Reviews, one open Coordination-type Issue | `S7` `OF-007` |
| Has any review, authorisation, verification or closure completed? | **No.** *"No completed review, authorisation, verification or closure was established"* | `S7` `OF-007` |
| Has a federation or coordination run been demonstrated? | **No.** *"No completed federation or coordination run demonstrated"* | `S7` `OF-008` |
| Has a complete cycle been demonstrated? | **No.** **`PARTIALLY TRACEABLE / NOT YET DEMONSTRATED AS A COMPLETE CYCLE`** | `S8` §8 |
| Is any authority evidenced? | **No** publication/exchange authority; **no** recipient acceptance authority | `S8` §9 |
| What does `S8` itself claim? | **`Authority: None` — observation and comparison record only** | `S8` |

## 8. Prohibited-claims register

**Seventy-three prohibited claims, plus four standing prohibitions** — **34
recorded in T6-A (§8.1–§8.5), 16 added in T6-B (§8.6) and 23 added in T6-C
(§8.7)**. Expanded from the sources. **A statement on any Module 6 slide that
makes one of these claims is wrong, whatever else is correct on the slide.**

### 8.1 Findings, clashes and Issues

| # | Prohibited claim |
|---|---|
| 1 | That **every clash is an Issue** |
| 2 | That **every finding is a clash** |
| 3 | That a **visible clash proves a design error** |
| 4 | That **no detected clash means the models are coordinated** |
| 5 | That **creating an Issue proves it was validly classified** |
| 6 | That **detection alone creates a governed record** |
| 7 | That the **seven Issue types are Autodesk system-native labels**, or that the platform provides them |
| 8 | That the **twelve interface checks are project requirements**, or evidence of real client requirements |
| 9 | That any **numeric tolerance exists**, or that a **software default carries governance authority** |

### 8.2 Federation and ownership

| # | Prohibited claim |
|---|---|
| 10 | That **federation transfers authorship, technical ownership or originator responsibility** |
| 11 | That a **coordination model or federated view is automatically a deliverable** |
| 12 | That `COORD-01` is **jointly authored**, or replaces the discipline containers |
| 13 | That appearing alongside another team's content **creates responsibility for it** |
| 14 | That **six discipline domains are six organisations, six Autodesk teams or six appointments** |

### 8.3 The decision acts

| # | Prohibited claim |
|---|---|
| 15 | That **Check, Review, Authorise, Accept and Reject are interchangeable**, or collapsible into "approval" |
| 16 | That **checking automatically authorises sharing** |
| 17 | That **authorisation to share is authorisation to publish or exchange** |
| 18 | That a **coordination disposition is discipline design approval** |
| 19 | That **"Accepted condition" at triage is recipient acceptance** |
| 20 | That the **BIM Manager automatically authorises or accepts** — or the BIM Coordinator, CDE Administrator or Architect |
| 21 | That the **BIM Coordinator owns the technical solution** or holds design-approval authority |
| 22 | That **acceptance transfers technical responsibility from the originator** |

### 8.4 Response, verification and closure

| # | Prohibited claim |
|---|---|
| 23 | That **assigning an Issue proves work began** |
| 24 | That **responding to an Issue proves technical resolution** |
| 25 | That **marking an Issue resolved proves verification** |
| 26 | That **marking an Issue closed proves the information containers were corrected, checked and reshared** |
| 27 | That **changing a status is evidence of a technical change** |
| 28 | That **completion means zero clashes**, or that a completed cycle means the design is complete, approved, construction-ready or accepted |
| 29 | That **verification is design approval, professional certification, publication authority or recipient acceptance** |

### 8.5 Platform, evidence and status

| # | Prohibited claim |
|---|---|
| 30 | That **ACC or Autodesk terminology overrides the BEP** |
| 31 | That a **platform status is an information state**, or that coordination creates a new state |
| 32 | That a **platform capability creates a governance requirement, role, authority or acceptance rule** |
| 33 | That **a provisioned environment evidences an executed process** |
| 34 | That **a missing observation proves missing work** |

### 8.6 Added in T6-B — Slides 4–8

**Sixteen further prohibited claims**, expanded from the sources while
developing Slides 4–8. **Numbering continues; no earlier claim was renumbered.**

| # | Prohibited claim | Slide |
|---|---|---|
| 35 | That **federation transfers authorship** | 4 |
| 36 | That the **BIM Coordinator owns the federated model's technical content** | 4 |
| 37 | That **`COORD-01` is automatically a deliverable** | 4 |
| 38 | That the federation is a **"single source of truth"** — **no controlled source authorises the expression** | 4 |
| 39 | That **folder location, platform environment or federation membership determines authorship** | 4 |
| 40 | That **upload or visibility proves readiness**, or makes a file a controlled coordination input | 5 |
| 41 | That **exclusion from a cycle proves absence from the project** | 5 |
| 42 | That an **observed platform configuration is the approved coordination environment** — that matter is **unresolved** | 5 |
| 43 | That **every proposed check must be run**, in every cycle | 6 |
| 44 | That the **twelve checks are exhaustive**, or cover every technical, regulatory or constructability concern | 6 |
| 45 | That a **software default tolerance is approved governance**, or a legitimate starting point | 6 |
| 46 | That **zero clashes means coordinated**, or that a clash count evidences quality | 6 |
| 47 | That **every clash is an error**, or that **every finding is a clash** | 6, 7 |
| 48 | That **every clash or finding must become an Issue** | 7 |
| 49 | That **creating an Issue proves valid triage**, classification, assignment, resolution or verification | 7 |
| 50 | That a **triage disposition is an Issue status**, an information state, a suitability code or recipient acceptance | 8 |

**`Accepted condition` is separately and expressly prohibited from being
presented as recipient acceptance, approval or authorisation — claim 19 —
and T6-B adds that it does not release `T4`, resolve acceptance authority or
unblock `TRN-E03`.**

**Fifty prohibited claims, plus four standing prohibitions — the running total
after T6-B.** **No count was targeted.**

### 8.7 Added in T6-C — Slides 9–12

**Twenty-two further prohibited claims**, expanded from the sources while
developing Slides 9–12. **Numbering continues; no earlier claim was renumbered.**

| # | Prohibited claim | Slide |
|---|---|---|
| 51 | That **assignment transfers authorship** | 9 |
| 52 | That the **BIM Coordinator owns or designs the fix** | 9 |
| 53 | That **assignment proves work started** | 9 |
| 54 | That **a response proves resolution** | 9 |
| 55 | That **a WIP correction proves controlled reshare** | 9 |
| 56 | That a **due date, priority, owner or Issue identifier** exists where none is established | 9 |
| 57 | That a **verbal agreement modifies controlled information** | 9 |
| 58 | That the **federated coordination view is edited** to implement a fix | 9 |
| 59 | That the **Issue status model is a CDE information-state model** | 10 |
| 60 | That the **status model is configured** in Forma, ACC or any platform | 10 |
| 61 | That **platform-native labels override the governed meaning** | 10 |
| 62 | That **`Deferred` and `Escalated` are mandatory sequential stages** in the main status sequence | 10 |
| 63 | That **`Ready for Verification` means verified** | 10 |
| 64 | That **`Closed` means technically fixed** | 10 |
| 65 | That **`Closed` proves verification** | 10, 11 |
| 66 | That **a status change proves the underlying condition changed** | 10 |
| 67 | That **verification is checking** | 11 |
| 68 | That **verification is design approval, professional certification, publication authority or recipient acceptance** | 11 |
| 69 | That **verification is mandatory in every cycle** — **`H18` is `NOT ESTABLISHED`** | 11 |
| 70 | That **zero clashes means coordination complete** | 12 |
| 71 | That **all nine completion conditions were performed**, or that they are an unconditional universal checklist | 12 |
| 72 | That **cycle completion means the entire design is complete, construction-ready, technically approved or accepted by the project** | 12 |

**And one that belongs to the module rather than a slide:**

| # | Prohibited claim |
|---|---|
| 73 | That **Module 6 teaching closes `GCR-006`** — only evidence of a complete governed cycle could |

**Seventy-three prohibited claims, plus four standing prohibitions — the current
total.** **No count was targeted.**

### 8.8 Standing programme-status prohibitions

**Four standing prohibitions apply to every Module 6 slide and every Module 6
increment.**

| # | Prohibited claim |
|---|---|
| **A** | That a **complete governed coordination cycle has been demonstrated** — `GCR-006` is **OPEN** |
| **B** | That **a Triviron coordination workflow has been decided** — no Triviron information exists |
| **C** | That **Module 6 teaching changes Harrismith governance** — it explains; it governs nothing |
| **D** | That **Slides 13–14 are developed** — they are **architecture only** after T6-C |

## 9. Boundary-deferral register

| Boundary | Owned by | Module 6 position |
|---|---|---|
| CDE information states; the eight controlled steps; `T1`/`T4`; the blocked `Shared → Published` route; suitability and metadata standards | **Module 4** (`S10`; `S6`) | **Module 6 must not redefine or complete any of them.** It may state that coordination uses `T3` and `T8` and creates no new state |
| Responsibility-matrix structure; the seven-term function grammar; container allocation; delivery-event planning | **Module 5** (`S11`; `S3`, `S4`, `S5`) | **Module 6 must not rewrite them.** It may cite `X1`–`X5`, `A1`–`A5` and the `TRN-E` events as allocated |
| Triviron decisions, role holders, responsibility allocations, workflow configuration | **Module 7** | **Slide 14 poses questions and answers none** |
| Workshop facilitation, meeting scripts, agreement-capture technique | **Module 8** | **Module 6 may say a coordination meeting exists and what it is not** — `S1` §8.9, `S2` §20 — **and stop** |
| Publication arrangement, `PAD-001`, `PM-1`–`PM-7` | **Excluded — `E1`** | **Module 6 does not address the `T4` block or publication authority beyond recording that they remain unresolved** |

## 10. Status

| Field | Value |
|---|---|
| Increment | **T6-C** — Slides 9–12 classified. T6-A classified Slides 1–3; T6-B classified Slides 4–8 |
| Slides classified | **1–12.** Slides 13–14 **architecture only** |
| Classified statements | **188** — 49 (T6-A) + 76 (T6-B) + 63 (T6-C) |
| Registers | **Nine** — classification scheme, source authority, terminology variance, hypothesis, unresolved matter, implementation evidence, prohibited claims, boundary deferral, statement classification |
| Sources consulted / excluded | **14** (`S1`–`S14`) / **9 groups** (`E1`–`E9`) — **unchanged in T6-B and T6-C** |
| Hypotheses tested | **18** — `H1`–`H18`. **15 `CONFIRMED` · 2 `CONFIRMED WITH QUALIFICATION` · 1 `NOT ESTABLISHED` · 0 `CONTRADICTED`. Unchanged in T6-B and T6-C** |
| Terminology variances | **6**, none harmonised. **No seventh arose in T6-B or T6-C** |
| Unresolved matters | **14**, none resolved. **None populated in T6-B or T6-C** |
| Prohibited claims | **73** — 34 (T6-A) + 16 (T6-B) + 23 (T6-C) — plus **4 standing programme-status prohibitions** |
| Timing | **`20.0 minutes allocated — not measured`** |
| Complete governed coordination cycle | **NOT DEMONSTRATED.** `GCR-006` **OPEN** |
| Exercises, visual plan, visual sources, assets, package, PowerPoint | **None exist** |
