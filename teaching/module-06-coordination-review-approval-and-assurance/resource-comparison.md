# Module 6 — Principal-Resource Comparison

**Status:** Analysis of teaching material. **Not governance.**

**The four principal Module 6 resources are analysed separately before any
teaching implication is drawn.** They are **not** merged into one generic
workflow, and **terminology is not harmonised to simplify teaching**.

Source identifiers are defined in [`source-inventory.md`](source-inventory.md).

---

## 1. Why these four, and why separately

Module 6 spans two BEP sections and two supporting resources that govern
**different objects**:

| Resource | Governed object |
|---|---|
| **`S1` §8** — BEP Model and Information Coordination | **The multidisciplinary interface process** |
| **`S1` §9** — BEP Review, Approval and Authorisation | **The decisions that let information move or be relied on** |
| **`S2`** — Coordination & Review Strategy | **How coordination is performed using controlled Shared information** |
| **`S3`** — IM Responsibility Matrix §3.5, §3.7 | **Which function performs each coordination and assurance act** |

**Collapsing them would destroy the module's central distinction.** §8 governs a
*process*; §9 governs *decisions*; `S2` governs *execution detail*; `S3` governs
*allocation*. A single "coordination workflow" slide would silently merge four
different kinds of statement.

## 2. `S1` §8 — Model and Information Coordination

| Field | Record |
|---|---|
| **Governed object** | The controlled multidisciplinary process used to *"identify, communicate, resolve and verify information-interface problems"* (§8.1) |
| **Initiating condition** | Availability of **controlled Shared information** that has passed the readiness process of §6 and §7. *"Uncontrolled WIP is not the normal project coordination input"* (§8.3) |
| **Actors / functions** | BIM Coordinator; Task-Team Leads; relevant Authors and Checkers; BIM Manager for governance and escalation; Lead Delivery Party where project-level coordination requires it (§8.2). **"No actual people are appointed"** |
| **Inputs** | Controlled Shared information, with identity, originator, purpose, version, coordinate context, completeness, exclusions and known unresolved interfaces confirmed (§8.3) |
| **Activities** | Federation (§8.5); clash detection and purpose-based checks (§8.6); triage (§8.6, §8.7); Issue creation (§8.7); resolution in originating WIP (§8.8, §8.10); recoordination; verification (§8.10); meetings (§8.9); escalation (§8.12) |
| **Decision points** | **Triage** — *"A clash result is triaged before any formal issue is created"* (§8.6). **Issue creation** — *"Creating an issue is a decision"* (§8.7) |
| **Outputs** | Issues with owner and history; dispositions; verification; retained evidence (§8.8, §8.11) |
| **Status vocabulary** | **None defined.** *"This BEP does not define project issue numbering or status codes"* (§8.7) |
| **Evidence required** | Traceable Issue history; recorded decisions of consequence (§8.9). *"A decision nobody can produce afterwards did not happen"* |
| **Authority required** | **None created by §8.** Responsibility comes from §4 and §5 — *"Tools do not define responsibility"* (§8.4) |
| **Closure condition** | Completion **by disposition**, not by clash count: required checks performed; significant findings triaged; required Issues assigned; resolutions or dispositions recorded; verification completed where required; unresolved matters carried forward or escalated (§8.11) |
| **Implementation status** | **`NOT DEMONSTRATED`.** §8.4 records the as-found qualification directly: a Navisworks area with limited content, and **no Design Collaboration Coordination Space observed configured** |
| **Unresolved matters** | Tolerances, exclusions, taxonomy and statuses — **all deferred to `S2`** (§8.6, §8.7, §8.13) |
| **Explicit exclusions** | *"Its purpose is not to generate clash counts"* (§8.1); blind all-versus-all testing **not required** (§8.6); **verification is not design approval, professional certification or acceptance of technical responsibility** (§8.10); **escalation authorities are not invented** (§8.12) |
| **Relationship to the others** | **Defers detail to `S2`** (§8.13), and expressly states that reference *"does not constitute approval of it"*. Hands the decision layer to §9 |

## 3. `S1` §9 — Review, Approval and Authorisation

| Field | Record |
|---|---|
| **Governed object** | *"The decision-control layer between production and use"* — the decisions that let information **move**, and the decisions that let information be **relied on** (§9.1) |
| **Initiating condition** | Information reaching a point where a controlled decision is required — before progression, before exchange, or on receipt |
| **Actors / functions** | Task team (check); Task-Team Lead (authorise share); BIM Coordinator (coordination review); **publication/exchange authority — UNRESOLVED**; **recipient acceptance — no workflow defined** |
| **Inputs** | Checked information; a stated purpose. **Authorisation is always *for* something, never in general** (§9.1) |
| **Activities** | Task-team check (§9.3); authorisation to share (§9.4); coordination review (§9.5); delivery review (§9.6); authorisation to publish/exchange (§9.7); acceptance (§9.8); rejection and rework (§9.9) |
| **Decision points** | **Six named acts (§9.2)** — Check · Review · Authorise · Accept · Reject · Coordinate |
| **Outputs** | A decision, for a defined purpose, traceable to who decided it and when (§9.1, §9.11) |
| **Status vocabulary** | **The six decision terms of §9.2.** *"These terms are not collapsed into 'approval.'"* **"Approval" is not used as a catch-all** (§9.1) |
| **Evidence required** | Version history; checking, review and coordination-Issue records; decision and meeting records; publication, transmission, acceptance and rejection records (§9.11). **"Not every platform feature is required for every evidence type"** |
| **Authority required** | *"Authority comes from governance"* — **not from platform access, permission or configuration** (§9.1). **Platform write permission is not publication authority** (§9.7) |
| **Closure condition** | Not defined as a single condition. Each act closes against **its own** criteria and purpose |
| **Implementation status** | **`NOT DEMONSTRATED`.** `S8` §9 records that **no governed publication/exchange authority and no governed recipient acceptance authority evidence was established** |
| **Unresolved matters** | **Publication / exchange authority — UNRESOLVED, `TBD`** (§9.7); **recipient acceptance — no Appointing Party acceptance workflow defined** (§9.8) |
| **Explicit exclusions** | **Check does not authorise sharing** (§9.3); **authorisation to share is not authorisation to publish** (§9.4); **a coordination disposition is not design approval** (§9.5); **acceptance does not transfer responsibility** (§9.8); **"No new Review Matrix is created"** (§9.13) |
| **Relationship to the others** | Governs the decisions §8's process depends on. **Allocation of who performs them lives in `S3`** — §9.13 defers it there |

## 4. `S2` — Coordination & Review Strategy

| Field | Record |
|---|---|
| **Governed object** | *"How multidisciplinary coordination is performed using controlled Shared information."* **Expands BEP §8** |
| **Initiating condition** | A coordination cycle opening with controlled Shared inputs (§17) |
| **Actors / functions** | **Coordination-specific functions only** (§3) — BIM Coordinator, Task-Team Lead, Author, Checker, BIM Manager, CDE Administration, Lead Delivery Party. **"All holders remain TBD"** |
| **Inputs** | The **coordination input register** — twelve fields (§4); readiness confirmed against **ten conditions** (§5); the six container refs `ARC-01`–`FIR-01` (§4) |
| **Activities** | Readiness (§5); federation of **`COORD-01`** (§8); **twelve proposed interface checks `CI-01`–`CI-12`** across **six check types** (§9, §10); triage (§13); Issue creation (§12); assignment (§16); technical resolution in originating WIP (§18); verification (§19); meetings (§20); escalation (§23) |
| **Decision points** | **Triage** — **seven dispositions** (§13); **Issue creation** — *"a decision taken at triage, not an automatic consequence of detection"* (§12); **inclusion/exclusion of an input** (§5) |
| **Outputs** | **Nine evidence outputs** (§22) — input register · `COORD-01` federation/reference · check execution record · clash/finding record · Issue records and history · meeting decisions and actions · verification record · unresolved/escalated matter list · cycle summary and status |
| **Status vocabulary** | **A six-state Issue status model** — New → Triaged → Assigned → In Progress → Ready for Verification → Closed — plus **two controlled alternate dispositions**, Deferred and Escalated (§15). **Seven Issue types** (§14) |
| **Evidence required** | The nine outputs of §22. *"No duplicate record is required where an existing controlled platform record already provides adequate evidence"* |
| **Authority required** | **None created.** *"Coordination is not technical or design approval. Nothing in this document confers design approval, professional certification, publication authority or recipient acceptance"* |
| **Closure condition** | **Nine completion conditions** (§21), and **completion is cycle-specific and purpose-specific**. *"Completion is not 'zero clashes.'"* Verification precedes closure and follows re-coordination against **reshared, controlled information** (§19) |
| **Implementation status** | **`PROPOSED GOVERNANCE` throughout, except §7.** §7 is explicitly **`OBSERVED FACT`**. The document states: *"This strategy does not describe the live platform"* |
| **Unresolved matters** | **Seven, listed at §26** — `UD-001`; Coordination Space configuration; **numeric tolerances (`TBD`)**; Issue taxonomy and status platform mapping; **cycle frequency — not established**; completion evidence format; coordinate reference basis. *"None of these is resolved by this strategy"* |
| **Explicit exclusions** | **Blind all-versus-all testing not adopted** (§9); **"A software default tolerance is not a project requirement"** (§11); **"Not every clash becomes an Issue"** (§12); **"'Accepted condition' does not mean recipient acceptance or design approval"** (§13); **Issue types "are not Autodesk system-native labels"** (§14); status model **"not claimed to be configured in Forma"** (§15); **"No actual Issue identifiers are created here"** (§16); **"No dates are invented"** (§16); **"Coordination does not create a new CDE information state"** (§24) |
| **Relationship to the others** | Expands `S1` §8; supports §8 and §9; **references `S3`, `S4`, `S5`, `S6` and `S7` without duplicating them** (§25). *"Reference here does not constitute approval of it"* |

## 5. `S3` §3.5 and §3.7 — the allocated functions

| Field | Record |
|---|---|
| **Governed object** | **Which functional role holds which coordination or assurance function** — not who, and not whether it happened |
| **Coordination rows (§3.5)** | **`X1`** organise coordination inputs · **`X2`** perform/manage the multidisciplinary coordination process · **`X3`** resolve technical coordination issue · **`X4`** verify coordination resolution / process disposition · **`X5`** escalate unresolved multidisciplinary interfaces |
| **Assurance rows (§3.7)** | **`A1`** assess governance change · **`A2`** authorise governance change · **`A3`** implement approved change · **`A4`** verify implementation · **`A5`** retain decision and change evidence |
| **Decision points** | **`X4`** carries **`Ck`** to the BIM Coordinator — **verification is a *checking* act, not an authorising one**. **`A2` is `TBD` against four roles** |
| **Status vocabulary** | The seven-term function grammar of `S3` §1, **which belongs to this matrix alone** (Module 5 position, `S11`) |
| **Authority required** | **None conferred.** *"The BIM Coordinator does not own the technical design solution and does not hold design-approval authority"* (`X3`/`X4` note) |
| **Implementation status** | **`IMPLEMENTATION UNVERIFIED`.** *"It does not demonstrate that separate people perform them"* (§5) |
| **Unresolved matters** | **`A2` — `TBD` across Appointing Party, Lead Delivery Party, BIM Manager and Task-Team Lead.** *"No single universal approver exists"*. **`A4` — "No single universal verifier is defined"** |
| **Relationship to the others** | Holds what `S2` §3 expressly declines to duplicate and what `S1` §9.13 expressly defers to it |

## 6. Where the resources agree

| Agreement | `S1` | `S2` | `S3` |
|---|---|---|---|
| **A finding is not an Issue** | §8.7 | §12 | — |
| **Issue creation is a decision** | §8.7 | §12 | — |
| **Federation does not merge authorship or ownership** | §8.5 | §1, §8 | — |
| **Resolution happens in the originating task team's WIP** | §8.8, §8.10 | §18 | `X3` — `P` to Author and Task-Team Lead |
| **The BIM Coordinator manages the process, not the solution** | §8.8 | §1, §18 | `X3`/`X4` note |
| **Verification is not design approval, certification or acceptance** | §8.10, §9.5 | §19 | `X3`/`X4` note |
| **Completion is by disposition, not zero clashes** | §8.11 | §21 | — |
| **Clash detection is one technique, not the whole process** | §8.6 | §1 | — |
| **Escalation records an unresolved decision owner rather than naming one** | §8.12 | §23 | `A2` `TBD` |
| **Authority comes from governance, not platform permission** | §9.1, §9.7 | §3 (CDE Administration) | §1 grammar |

## 7. Where they govern different objects

| Object | Governed by | Not governed by |
|---|---|---|
| **The interface process** | `S1` §8, `S2` | `S1` §9 |
| **The decision terms** | `S1` §9.2 | `S2` — which uses them but does not define them |
| **Which function performs an act** | `S3` §3.5, §3.7 | `S1` §9.13 and `S2` §3 both expressly defer |
| **Information states** | `S6` | `S2` §24 — *"Coordination does not create a new CDE information state"* |
| **Which containers exist** | `S4` | `S2` §4 — it references the refs, it does not allocate them |
| **Which exchanges carry the cycle** | `S5` | `S2` §17 — it maps onto them, it does not define them |
| **What has been demonstrated** | `S7`, `S8` | **All of `S1`–`S6`** — none evidences execution |

## 8. Where similar words mean different things

**Six variances are recorded in [`source-inventory.md`](source-inventory.md) §5.
The two most dangerous for teaching:**

- **"Accepted"** — `S2` §13 *"Accepted condition"* is a **triage disposition**
  for a defined check and purpose. `S1` §9.8 *Accept* is **recipient
  acceptance**, a separate function occurring **after delivery**, whose
  authority is **unresolved**. `S2` states the distinction expressly.
- **"Review"** — `S1` §9.2 *Review* is a **governed decision term**; §9.5 and
  §9.6 name two different reviews. `S7` `OF-007` records observed **"Client
  Review instances"** — a **platform artefact** evidencing activity, not a
  governed decision.

**Two more worth holding:**

- **"Verify"** — `S1` §8.10 says the BIM Coordinator **may** verify; `S2` §19
  and `S3` `X4` treat verification as a **defined step with stated conditions**.
- **"Check"** — `S1` §9.3 task-team check, `S3` `X4` verification `Ck`, and
  `S2` §5 readiness check are **three different checking acts** at three points
  in the cycle.

## 9. Where they overlap

| Overlap | How it is handled |
|---|---|
| **`S1` §8.8 and `S2` §17 both state a coordination cycle** | **Variance 1.** `S2` adds a head and tail step and splits *findings* from *triage*. **Both are recorded; neither is rewritten** |
| **`S1` §8.7 and `S2` §12 both define Issue** | **Variance 3.** `S2` is broader. **Module 6 teaches `S2`'s and records `S1`'s as narrower** |
| **`S1` §9.5 and `S2` §19 both bound verification** | They agree. `S2` adds the three satisfaction conditions and the reshare precondition |
| **`S2` §17 and `S5` both concern `TRN-E01`–`TRN-E03`** | `S5` defines the events; `S2` maps the cycle onto them. **`S2` §17 records `TRN-E03` as *not* part of the normal coordination reshare cycle** |
| **`S2` §24 and `S6` both concern states** | `S6` governs. `S2` defers: *"Rework returns affected information to the originating task team's WIP. Controlled reshare returns revised information to Shared. Those are the only state transitions in the coordination cycle"* |

## 10. Where they depend on one another

```text
S1 §8  ──defers detail to──▶  S2
S1 §9  ──defers allocation to──▶  S3
S2     ──references, does not duplicate──▶  S3, S4, S5, S6, S7
S2 §17 ──consumes the events of──▶  S5
S2 §24 ──accepts the state model of──▶  S6
```

**The dependency runs one way.** `S2` does not amend `S1`; `S3` does not amend
`S9`'s decision terms; and **no supporting resource is approved by being
referenced** (`S1` §13.6).

## 11. What every one of them leaves unresolved

| Unresolved matter | Recorded in |
|---|---|
| **Numeric clash and clearance tolerances** | `S2` §11, §26 — **`TBD` for all twelve checks** |
| **Coordination environment configuration** | `S2` §26; `S7` `OF-005` — **intended configuration not yet approved** |
| **Issue taxonomy and status platform mapping** | `S2` §14, §15, §26 — **not yet implemented** |
| **Coordination-cycle frequency** | `S2` §20, §26 — **not established** |
| **Completion evidence format** | `S2` §26 — **PROPOSED, to be validated** |
| **Coordinate reference basis** | `S2` §26 — **candidate context only, not approved** |
| **`UD-001` MEP / Structural mapping** | `S2` §7, §26; `S7` — **UNRESOLVED, not corrected** |
| **Governance-change authority (`A2`)** | `S3` §3.7 — **`TBD` across four roles** |
| **Publication / exchange authority** | `S1` §9.7 — **UNRESOLVED** |
| **Recipient acceptance authority** | `S1` §9.8 — **no workflow defined** |
| **A complete governed coordination cycle** | `S7` `GCR-006` — **OPEN**; `S8` §8 — **NOT YET DEMONSTRATED AS A COMPLETE CYCLE** |

**Eleven unresolved matters across four approved resources. None is resolved by
Module 6.**

## 12. Teaching implication

**The four resources describe a coherent governed route that has not been shown
to run.** `S1` §8 and §9 define the principles and the decisions; `S2` supplies
a detailed, internally consistent cycle; `S3` allocates the functions — and
`S7` and `S8` record that the environment is partly provisioned, the fragments
exist, and **`GCR-006` remains open**.

**Module 6 teaches the route and the evidence gap together.** Teaching the cycle
without the gap would convert proposed governance into implementation; teaching
the gap without the cycle would suggest nothing has been governed. **Both are
true at once, and the module must hold both.**
