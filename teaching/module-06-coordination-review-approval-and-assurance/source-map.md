# Module 6 — Source Map, Registers and Prohibited Claims

**Status:** Traceability record for teaching material. **Not governance.**

**Statement-level classification for Slides 1–3**, developed in **T6-A**, plus
the classification scheme, source-authority register, terminology-variance
register, hypothesis register, unresolved-matter register, prohibited-claims
register, implementation-evidence register and boundary-deferral register.

**Slides 4–14 are architecture only.** No statement is classified for them, and
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
| Coordination visual specification and assets | — | — | **Not created. T6-B and later** |

## 3. Statement classification — Slides 1–3

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

**Slide 1 profile.** 6 `CONTROLLED` · 3 `SUPPORTING` · 2 `DECISION-RECORD` ·
1 `MODULE-2-5` · 2 `INTERP` · 1 `EXCLUDED`. *(`M6-S1-01` is counted once, as
`MODULE-2-5`.)*

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

### 3.4 Totals for the developed slides

| Class | Count |
|---|---|
| `CONTROLLED` | **19** |
| `SUPPORTING` | **12** |
| `DECISION-RECORD` | **10** |
| `MODULE-2-5` | **1** |
| `TEACHING-PLAN` | **0** |
| `INTERP` | **5** |
| `SYNTH` | **0** |
| `EXCLUDED` | **3** |
| **Total** | **49** |

**No count was targeted.** Slides 4–14 contribute nothing — they are
architecture only.

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

**Eighteen hypotheses: fourteen `CONFIRMED`, two `CONFIRMED WITH
QUALIFICATION`, one `NOT ESTABLISHED`, one further `NOT ESTABLISHED` limb inside
H10.** No hypothesis was `CONTRADICTED`, and none was manufactured to balance
the register.

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

**Thirty-four prohibited claims.** Expanded from the sources. **A statement on
any Module 6 slide that makes one of these claims is wrong, whatever else is
correct on the slide.**

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

### 8.6 Standing programme-status prohibitions

**Four standing prohibitions apply to every Module 6 slide and every Module 6
increment.**

| # | Prohibited claim |
|---|---|
| **A** | That a **complete governed coordination cycle has been demonstrated** — `GCR-006` is **OPEN** |
| **B** | That **a Triviron coordination workflow has been decided** — no Triviron information exists |
| **C** | That **Module 6 teaching changes Harrismith governance** — it explains; it governs nothing |
| **D** | That **Slides 4–14 are developed** — they are **architecture only** after T6-A |

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
| Increment | **T6-A** |
| Slides classified | **1–3.** Slides 4–14 **architecture only** |
| Classified statements | **49** |
| Registers | **Nine** — classification scheme, source authority, terminology variance, hypothesis, unresolved matter, implementation evidence, prohibited claims, boundary deferral, statement classification |
| Sources consulted / excluded | **14** (`S1`–`S14`) / **9 groups** (`E1`–`E9`) |
| Hypotheses tested | **18** — `H1`–`H18` |
| Terminology variances | **6**, none harmonised |
| Unresolved matters | **14**, none resolved |
| Prohibited claims | **34**, plus **4 standing programme-status prohibitions** |
| Timing | **`20.0 minutes allocated — not measured`** |
| Complete governed coordination cycle | **NOT DEMONSTRATED.** `GCR-006` **OPEN** |
| Exercises, visual plan, visual sources, assets, package, PowerPoint | **None exist** |
