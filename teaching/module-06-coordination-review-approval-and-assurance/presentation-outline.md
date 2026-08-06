# Module 6 — Presentation Outline

**Status:** **Slides 1–3 developed in T6-A; Slides 4–8 developed in T6-B.
Slides 9–14 are architecture only.**

**An architecture is not a developed slide.** Slides 9–14 record a title, a time
and an intended function. **They carry no on-slide copy, no source basis, no
classified statements and no speaker notes**, and must not be presented as
though they did.

**There is no visual specification, no visual source, no asset, no exercise set,
no assembly package and no PowerPoint**, and no review or rehearsal has been
performed.

Source identifiers `S1`–`S14` are defined in
[`source-inventory.md`](source-inventory.md). Statement classification is in
[`source-map.md`](source-map.md) §3. Presenter notes for **Slides 1–8** are in
[`speaker-notes.md`](speaker-notes.md).

**Timing throughout: `20.0 minutes allocated — not measured`.** The per-slide
times are **pacing allocations**. **No automatic slide-transition timing is
created; the presenter advances each slide manually when ready.**

---

## 1. Working timing structure — 20 minutes

| Section | Slides | Time |
|---|---|---:|
| **A — Why allocation did not settle it** | 1, 2 | 2.5 min |
| **B — The governed cycle, and what has been shown** | 3, 4 | 3.0 min |
| **C — From input to Issue** | 5, 6, 7, 8 | 5.5 min |
| **D — Response, verification and closure** | 9, 10, 11, 12 | 6.0 min |
| **E — Evidence, assurance and transfer** | 13, 14 | 3.0 min |
| **Total** | **14** | **20.0 min** |

## 2. Slide architecture — fourteen slides

| Slide | Working title | Time | Developed |
|---|---|---:|---|
| 1 | Module 6 — from who is responsible to what actually happened | 1.0 | ✅ **T6-A** |
| 2 | Nine objects, and the words that collapse them | 1.5 | ✅ **T6-A** |
| 3 | The governed coordination cycle — and the evidence gap | 1.5 | ✅ **T6-A** |
| 4 | Federation — a lens, not an author | 1.5 | ✅ **T6-B** |
| 5 | Inputs and readiness — what may enter a cycle | 1.5 | ✅ **T6-B** |
| 6 | Checks are chosen, not exhaustive | 1.5 | ✅ **T6-B** |
| 7 | Finding, clash, Issue — and the decision between them | 1.5 | ✅ **T6-B** |
| 8 | Triage — seven dispositions, one dangerous word | 1.0 | ✅ **T6-B** |
| 9 | Assignment and technical response — who owns the fix | 1.5 | Architecture only |
| 10 | The Issue status model is not an information state | 1.5 | Architecture only |
| 11 | Verification — after reshare, against controlled information | 1.5 | Architecture only |
| 12 | Completion is not zero clashes | 1.5 | Architecture only |
| 13 | Evidence, escalation, and what a closed Issue does not prove | 1.0 | Architecture only |
| 14 | What Triviron must decide about coordination | 2.0 | Architecture only |
| | **Total** | **20.0** | **8 of 14** |

### 2.1 How the architecture was derived

**The provisional architecture in the increment brief listed thirteen topics.
Five changes were made on source evidence**, and the count and the twenty-minute
total are unchanged.

| # | Change | Why |
|---|---|---|
| 1 | **Assurance does not get its own slide.** It joins evidence and closure at Slide 13 | **No source defines an assurance-sampling method.** `S3` §3.7 allocates `A1`–`A5` for **change** assurance and `S2` §3 records that the BIM Manager *"supports assurance"* — that is all. A dedicated slide would have to invent content (`H10`, `U14`) |
| 2 | **A dedicated slide (4) for federation, immediately after the cycle** | `S1` §8.5 and `S2` §8 are the clearest statements in the source set that **aggregation does not merge ownership**, and the misreading is the module's earliest hazard |
| 3 | **Inputs and readiness get their own slide (5)** | `S2` §4 and §5 carry a twelve-field register and ten readiness conditions, and **`S1` §8.3 makes readiness the entry condition for the whole cycle.** Folding it into federation would lose the exclusion decision |
| 4 | **The evidence gap is taught on Slide 3, with the cycle — not deferred to the end** | **`GCR-006` is open and `S8` §8 records the cycle as not demonstrated.** Teaching the cycle for eleven slides and disclosing the gap at Slide 13 would let the audience carry an implementation belief through most of the module |
| 5 | **"Authorisation, acceptance and rejection" is not a separate slide** | `S1` §9.7 and §9.8 are **unresolved**, and Module 5 already taught the `T4` block. Slide 2 fixes the vocabulary; Slide 11 covers what verification is not. **A slide on unresolved authorities would repeat Module 5 without adding a Module 6 position** |

### 2.2 Three notes on the allocation

- **Section D is the longest at 6.0 minutes.** Response, status, verification
  and completion is where a status change is most easily mistaken for a
  technical fact.
- **Slide 3 must not be cut.** It carries the implementation position for the
  whole module. **If time is short, recover from Slide 8 or Slide 13.**
- **Slide 6 must stay at concept level.** **No numeric tolerance exists**
  (`S2` §11, `H17`); there is no threshold to teach.

## 3. Increment attribution

| Increment | Slides | Subject |
|---|---|---|
| **T6-A** | 1, 2, 3 | Module establishment, the acts that must stay distinct, and the governed cycle with its evidence gap |
| **T6-B** | 4, 5, 6, 7, 8 | Federation, input readiness, check selection, the finding-to-Issue decision, and triage |
| T6-C onward | 9–14 | **Not started** |

**Each developed slide carries:** purpose · exact title · allocated time ·
on-slide copy · source basis · classified-statement range · governance status ·
implementation status · prohibited claims · a **high-level** visual concept · a
transition. **Presenter notes are in [`speaker-notes.md`](speaker-notes.md).**

**The visual concepts are high-level only.** They record what a visual must show
and must not show. **They are not visual specifications**, and **no visual
specification, visual source or asset directory exists.**

---

## 4. Developed slides — 1 to 8

### Slide 1 — Module 6: from who is responsible to what actually happened · 1.0 min

**Purpose of the slide**

Bridge from Module 5; state that allocation does not prove performance; and
establish Module 6's question **and its evidence boundary** before any process
content is shown.

**On-slide copy**

> # Module 6
> ## Coordination, Review, Approval and Assurance
>
> **Module 5** told you *who is responsible for producing which information.*
> **Module 6** asks *what happened to it, who decided, and what was verified.*
>
> ### The gap Module 5 left open
>
> **A matrix records responsibility. It never records occurrence.**
>
> ### What coordination is — BEP §8.1
>
> > *"The controlled multidisciplinary process used to **identify, communicate,
> > resolve and verify** information-interface problems."*
> >
> > *"Its purpose is **not** to generate clash counts. A clash count measures how
> > much software found; it says nothing about whether anything was understood,
> > decided or fixed."*
>
> ### And what §9 adds — BEP §9.1
>
> > *"The **decision-control layer** between production and use."*
>
> **Authority comes from governance** — *"not from platform access, permission
> or configuration."*
>
> ### The question this module answers
>
> **How does Harrismith govern the route from a coordination finding to a
> verified disposition — and which acts must stay distinct?**
>
> ### And the boundary it keeps
>
> | | |
> |---|---|
> | Four principal resources | **APPROVED WITH CONDITIONS — Training Baseline 0.1** · `AD-001` · **publication NOT AUTHORISED** |
> | The Coordination & Review Strategy's arrangements | **`PROPOSED GOVERNANCE`** |
> | *"This strategy does not describe the live platform"* | — |
> | **`GCR-006`** — one complete governed coordination cycle to be exercised and evidenced | **OPEN** |
>
> **This module explains a governed route. It does not claim the route has been
> run.**

**Source basis**

| Claim | Source |
|---|---|
| Coordination definition and the clash-count warning | `S1` §8.1 |
| §9 as the decision-control layer; authority from governance | `S1` §9.1 |
| Allocation is not performance | `S3` §5; `S11` — **teaching carry-forward** |
| Approval status and date | `S1`, `S2`, `S3` status blocks; `S9` `AD-001` |
| `S2` content is `PROPOSED GOVERNANCE`; does not describe the live platform | `S2` §Classification, §Purpose |
| `GCR-006` open | `S7`; `S9` |
| The module's central question | **`INTERP`** — assembled from `S1` §8, §9.2; `S2` §12–§21 |

Classified statements `M6-S1-01` to `M6-S1-14`.

**Teaching synthesis on this slide:** none. **Two statements are `INTERP`** —
the central question and the evidence boundary, both citing their sources.

**The central question was corrected**

The increment proposed: *"How does Harrismith turn coordination findings into
controlled decisions, verified resolution and traceable closure — and which acts
remain distinct?"*

**"Turn … into" and "traceable closure" overstate what the sources support.**
`S8` §8 records the cycle as **`PARTIALLY TRACEABLE / NOT YET DEMONSTRATED AS A
COMPLETE CYCLE`**, and `GCR-006` is open — so Harrismith **governs** the route
rather than being shown to **perform** it. The wording now reads *"how Harrismith
**governs** the route … to a **verified disposition**"*, which matches `S2` §19's
own term. **Classified `INTERP`.** See [`source-map.md`](source-map.md) §3.1
`M6-S1-07`.

**Prohibited on this slide**

- Any claim that a coordination cycle **has been performed** or demonstrated.
- Presenting the four resources at one status level, or as unconditionally
  approved.
- Naming any role holder, organisation or person.
- Claiming Module 6 resolves the publication or acceptance authority.
- Teaching Module 4 states, Module 5 matrices, or any Module 7 or 8 content.
- Describing `GCR-006` as closed, or as a formality.

**Visual concept — high level**

**Two panels, left and right.** Left: what Module 5 established — allocation.
Right: what Module 6 asks — occurrence, decision, verification. **Beneath both,
a single status strip** carrying the conditional approval, `PROPOSED
GOVERNANCE`, and **`GCR-006` OPEN**. **The status strip is not a footnote; it
is the slide's second message.** No person, no platform imagery.

**Transition into Slide 2**

> *"Before any of that route makes sense, we have to stop nine different things
> from turning into one word. The BEP is unusually direct about this."*

---

### Slide 2 — Nine objects, and the words that collapse them · 1.5 min

**Purpose of the slide**

Prevent the early collapse of **finding, clash and Issue** on one side, and
**check, review, coordinate, authorise, accept and reject** on the other. This
is the module's vocabulary slide, and it is almost entirely controlled.

**On-slide copy**

> ## Nine things. Not one word.
>
> ### Six decisions — BEP §9.2
>
> | Term | Meaning |
> |---|---|
> | **Check** | Verification against a defined requirement **before progression** |
> | **Review** | Consideration of information **for a stated purpose** |
> | **Authorise** | Permit information to progress, share, publish or exchange **for a defined purpose** |
> | **Accept** | **Recipient** acknowledges information as suitable or received for the stated purpose |
> | **Reject** | Information is **not accepted** for the stated progression or use, and action is required |
> | **Coordinate** | The multidisciplinary interface process — **not design approval** |
>
> > *"These terms are **not collapsed into 'approval.'** Each names a different
> > decision, made by a different function, against different criteria."*
> >
> > *"'Approval' is **not** used as a catch-all for different decision
> > functions."* — BEP §9.1
>
> ### Three coordination objects — Coordination & Review Strategy §12
>
> | Term | Meaning |
> |---|---|
> | **Finding** | An observed coordination matter **requiring triage** |
> | **Clash** | A geometric or spatial finding, generated or identified through review |
> | **Issue** | A **governed action record**, created when a matter needs ownership, action, decision, tracking, verification or escalation |
>
> ### **`Clash / finding ≠ Issue`**
>
> > *"**Not every clash becomes an Issue.** Many findings are tolerable,
> > duplicated, out of scope, already known, or artefacts of the test setup."*
> >
> > *"**Creating an issue is a decision.**"* — BEP §8.7
>
> ### The word that catches people
>
> **`Accepted condition`** at triage is **not** recipient **`Accept`**.
> *"It means only that the coordination finding requires no further action for
> the defined check and purpose. It is a coordination disposition and nothing
> more."*
>
> **Two controlled sources, two scopes.** The BEP defines *Issue* more narrowly
> than the strategy does. **Both are recorded. Neither is rewritten.**

**Source basis**

| Claim | Source |
|---|---|
| All six decision terms, verbatim | `S1` §9.2 |
| Terms not collapsed; "approval" not a catch-all | `S1` §9.1, §9.2 |
| Finding, Clash, Issue definitions | `S2` §12 |
| `Clash / finding ≠ Issue` | `S2` §12; `S1` §8.7 |
| Not every clash becomes an Issue; creating an issue is a decision | `S1` §8.7; `S2` §12 |
| "Accepted condition" is not recipient acceptance | `S2` §13 |
| The two Issue scopes differ | **`INTERP`** — variance 3 |

Classified statements `M6-S2-01` to `M6-S2-18`. **Ten are `CONTROLLED`** — the
most heavily controlled slide in the module.

**Teaching synthesis on this slide:** none. **Two statements are `INTERP`** —
the recorded scope variance, and the nine-object framing.

**Prohibited on this slide**

- Collapsing any two of the six decision terms, or offering "approval" as a
  synonym.
- Mapping the terms onto R/A/C/I, or onto any platform status set.
- Treating *Accepted condition* as recipient acceptance or design approval.
- Presenting *Finding*, *Clash* and *Issue* as three names for one object.
- **Teaching the triage dispositions, the Issue taxonomy or the status model** —
  Slides 7, 8 and 10 own them.
- Naming who performs any of the six acts — **allocation is Slide 9 and `S3`**.

**Visual concept — high level**

**Two clearly separated registers.** Upper: the six decision terms with their
§9.2 definitions. Lower: the three coordination objects. **A visible rule
between the two registers**, because they come from different sources and govern
different things. **One call-out** on the `Accepted condition` trap. **No arrows
between any two terms** — a connector would imply a sequence the sources do not
state here.

**Transition into Slide 3**

> *"Those are the pieces. Now the route they sit in — and the part most decks
> would leave out, which is how much of it has actually been done."*

---

### Slide 3 — The governed coordination cycle — and the evidence gap · 1.5 min

**Purpose of the slide**

Establish the source-supported cycle, its governance status, and — in the same
breath — **the recorded implementation position**. State clearly that **no
complete cycle has been demonstrated.**

**On-slide copy**

> ## One governed route. Fifteen steps. Not yet demonstrated.
>
> ### The cycle — Coordination & Review Strategy §17
>
> `controlled Shared inputs` → `readiness check` → `federation` →
> `coordination checks` → `findings` → `triage` →
> `create / assign Issues where required` →
> `originating task-team WIP correction` → `task-team check` →
> `authorise controlled reshare` → `Shared` → `re-coordinate` → `verify` →
> `close / disposition` → `retain evidence`
>
> **BEP §8.8 states the same route**, wording *findings* and *triage* as one
> step. **Both are recorded. Neither is rewritten.**
>
> ### Two rules inside the route
>
> > *"The **originating task team** makes the technical change."*
> > *"The BIM Coordinator manages the **process**, not the **solution**."*
> > — BEP §8.8
>
> ### And one boundary
>
> **Coordination does not create a new CDE information state.**
> *"Rework returns affected information to the originating task team's WIP.
> Controlled reshare returns revised information to Shared. **Those are the only
> state transitions in the coordination cycle.**"*
>
> ---
>
> ### What has actually been observed
>
> | Observation | Status |
> |---|---|
> | One Model Coordination model set · seven folders · **zero coordinated versions** | `OBSERVED — QUALIFIED` |
> | **No** Design Collaboration Coordination Space configured | `OBSERVED — QUALIFIED` |
> | Two open Client Reviews · one open Coordination-type Issue | `OBSERVED — QUALIFIED` |
> | **"No completed review, authorisation, verification or closure was established"** | — |
>
> > *"**Environment configured ≠ coordination process executed.**"* — `OF-008`
>
> ### The recorded result
>
> **`PARTIALLY TRACEABLE / NOT YET DEMONSTRATED AS A COMPLETE CYCLE`**
>
> **`GCR-006` — one complete governed coordination cycle to be exercised and
> evidenced — remains OPEN.**
>
> *Absence of observation is not observation of absence.* **Nothing here says
> the other disciplines are absent from the project.**

**Source basis**

| Claim | Source |
|---|---|
| The fifteen-step cycle | `S2` §17 |
| The same route in the BEP; the one-step wording | `S1` §8.8 |
| Originating task team makes the change; coordinator manages the process | `S1` §8.8; `S2` §1, §18 |
| Only two state transitions in the cycle; no new state | `S2` §24; `S6` |
| Model set, seven folders, zero coordinated versions | `S7` `OF-008`; `S8` §6C |
| No Coordination Space configured | `S7` `OF-005`; `S8` §4 |
| Two Reviews, one Issue; nothing completed | `S7` `OF-007`; `S8` §6B |
| Environment configured ≠ process executed | `S7` `OF-008` |
| Partially traceable / not yet demonstrated | `S8` §8 |
| `GCR-006` open | `S7`; `S9` |
| Absence of observation | `S8` §7; `S2` §4, §7 |

Classified statements `M6-S3-01` to `M6-S3-17`. **Eight are
`DECISION-RECORD`** — the module's most evidence-heavy slide.

**Teaching synthesis on this slide:** none. **One statement is `INTERP`** — the
recorded cycle-step variance.

**Prohibited on this slide**

- Presenting the cycle as **operating**, or the fragments as a partial run in
  progress.
- Describing the model set as evidence that coordination occurred.
- Treating an open Review or open Issue as a completed decision.
- Claiming any discipline is absent, inactive or behind.
- Closing, softening or dating `GCR-006`.
- **Teaching federation detail, readiness, the interface matrix or triage** —
  Slides 4–8 own them.
- Introducing any tolerance, frequency or date.

**Visual concept — high level**

**Two horizontal bands.** Upper: the governed cycle as a single labelled route.
Lower: the observed evidence, as **separate unconnected records** — because
fragments are what was observed, and joining them would draw a cycle nobody has
run. **A visible gap between the two bands**, carrying the recorded result and
**`GCR-006` OPEN**. **No arrow crosses from the evidence band into the cycle
band.** No platform screenshot, no Autodesk imagery.

**Transition into Slide 4**

> *"Step three of that route is federation, and it is the step most likely to be
> misunderstood — because assembling the models looks like merging them."*

---

### Slide 4 — Federation: a lens, not an author · 1.5 min

**Purpose of the slide**

Fix the boundary around federation before any finding is discussed. Aggregating
information for coordination looks like merging it, and the misreading transfers
responsibility that no source transfers.

**On-slide copy**

> ## Federation assembles. It does not absorb.
>
> **Federation is a temporary, controlled aggregation** of separate discipline or
> task-team information, **for coordination purposes** — BEP §8.5.
>
> ### What federation does **not** do — BEP §8.5
>
> | It does not | |
> |---|---|
> | **merge authorship** | |
> | **transfer technical ownership** | |
> | **create a new design author** | |
> | **turn discipline models into one jointly-owned authoring model** | |
>
> > *"Originators remain responsible for their own information… it is **not a
> > deliverable that anyone authored**, and **nobody becomes responsible for
> > another team's content by appearing alongside it**."*
>
> ### `COORD-01` — the coordination construct
>
> **A temporary controlled multidisciplinary coordination aggregation.**
> Potential inputs: `ARC-01` `STR-01` `MEC-01` `ELE-01` `PLM-01` `FIR-01`.
>
> It does **not** merge authorship · transfer technical responsibility · become a
> jointly-authored design model · replace the discipline containers ·
> **automatically become a formal deliverable**.
>
> ### Six things that stay separate
>
> | | |
> |---|---|
> | **Source container** | What a task team authored and shared |
> | **Federated coordination view** | A lens assembled from those containers |
> | **Originator** | The task team that produced the container |
> | **Technical ownership** | Stays with the originator, before and after |
> | **Coordination-process responsibility** | The BIM Coordinator leads the federation **process** |
> | **Deliverable status** | Separate, and **not conferred by federation** |
>
> ### And two rules that decide nothing about authorship
>
> > *"**Tools do not define responsibility.**"* — BEP §8.4
>
> **Folder location, platform environment and federation membership do not
> determine authorship.**
>
> **Status:** `PROPOSED GOVERNANCE` · **`IMPLEMENTATION UNVERIFIED`**
> A model set exists with **zero coordinated versions**. **No completed
> federation or coordination run has been demonstrated.**

**Source basis**

| Claim | Source |
|---|---|
| Federation is a temporary controlled aggregation | `S1` §8.5 |
| The four things federation does not do | `S1` §8.5 |
| Originators remain responsible; not a deliverable anyone authored | `S1` §8.5 |
| Nobody becomes responsible by appearing alongside | `S1` §8.5 |
| `COORD-01` and its five exclusions | `S2` §8; `S4` §3.4 |
| The BIM Coordinator leads the federation process | `S2` §8; `S1` §8.8 |
| Tools do not define responsibility | `S1` §8.4 |
| Model set with zero coordinated versions; no run demonstrated | `S7` `OF-008`; `S8` §6C |

Classified statements `M6-S4-01` to `M6-S4-14`.

**Governance status:** `CONTROLLED GOVERNANCE` (`S1` §8.5, §8.4) ·
`PROPOSED GOVERNANCE` (`S2` §8; `S4` §3.4).

**Implementation status:** **`IMPLEMENTATION UNVERIFIED`** ·
**`NOT DEMONSTRATED`** — no completed federation or coordination run.

**Teaching synthesis on this slide:** none. **Two statements are `INTERP`** —
the six-way separation, and the folder-location corollary.

**Prohibited on this slide**

- Showing ownership or authorship **flowing into** the federated model.
- Showing authorship transferring to the BIM Coordinator.
- Calling the federation a **"single source of truth"** — **no controlled source
  authorises that expression**.
- Implying a model set with included folders **demonstrates** a completed
  federation or coordination cycle.
- Converting `COORD-01` into a formally scheduled deliverable.
- Presenting six discipline domains as six organisations or six platform teams.
- Teaching Navisworks or ACC configuration.

**Visual concept — high level**

**Six source containers along the top, a federated view beneath them.** The
connectors run **upward from the view to the containers**, labelled *"assembled
from"* — **never downward**, because a downward arrow reads as ownership
flowing in. **Each source container keeps a visible originator label that the
federated view does not carry.** `COORD-01` sits **beside**, not above, the six.
No platform imagery.

**Transition into Slide 5**

> *"So the federation is a lens. The next question is what is allowed to be in
> it — because 'the file is there' is not the same as 'the information is a
> governed input.'"*

---

### Slide 5 — Inputs and readiness: what may enter a cycle · 1.5 min

**Purpose of the slide**

Establish readiness as the **entry condition** to the cycle, and separate eight
things that a platform view makes look identical.

**On-slide copy**

> ## Visible is not selected. Selected is not ready.
>
> ### The coordination input register — twelve recorded fields
>
> `Coordination Cycle / Event` · `Container Ref` · `Discipline` ·
> `Originating Party` · `Task Team` · `Information State` ·
> `Version / Revision reference` · `Coordination Purpose` · `Readiness Status` ·
> `Known Limitations / Exclusions` · `Included / Excluded` · `Notes`
>
> **`Information State` must be `Shared` for normal coordination.**
> *"Coordinating uncontrolled WIP is not the normal method."*
>
> ### Readiness — confirm before inclusion, as applicable
>
> correct container identity · correct originator and task team · **`Shared`
> state** · intended coordination purpose · required task-team checks completed ·
> **share authorised** · coordinate and reference context known well enough for
> the check · known omissions and limitations visible · dependencies identified ·
> version or revision identifiable where required
>
> ### Eight things that are not the same
>
> | | |
> |---|---|
> | **Visible / uploaded** | A file exists somewhere |
> | **Selected as an input** | Someone decided it belongs in this cycle |
> | **Suitable for the defined purpose** | It can answer the question being asked |
> | **Ready** | The conditions above are confirmed |
> | **Permission to read** | A platform capability |
> | **Authorisation to rely** | A governance decision |
> | **Observed content** | What someone happened to see |
> | **A governed input set** | What the register records |
>
> ### Readiness is not completeness — BEP §8.3
>
> > *"Coordination readiness is **not** design completeness. Information can be
> > ready to coordinate while remaining **incomplete, unapproved and subject to
> > change**. The two questions are separate."*
>
> ### If an input is not ready
>
> **Exclude or defer it, and record the reason.**
> *"An exclusion with a recorded reason is a governed outcome; coordinating an
> unready input quietly is not."*
>
> **A cycle is purpose- and scope-specific. Exclusion from one cycle establishes
> nothing about the project.**
>
> **Status:** `PROPOSED GOVERNANCE` · **`OBSERVED — QUALIFIED`**
> Only Architecture was observed as a populated direct production stream, at the
> inspected level. **Absence of observation is not observation of absence.**

**Source basis**

| Claim | Source |
|---|---|
| The twelve input-register fields | `S2` §4 |
| `Shared` state required for normal coordination | `S2` §4; `S1` §8.3; `S6` |
| Uncontrolled WIP is not the normal method | `S1` §6.6, §8.3; `S2` §5 |
| The ten readiness conditions | `S2` §5 |
| Readiness is not design completeness | `S1` §8.3; `S2` §5 |
| Exclude or defer and record the reason | `S2` §5 |
| Permission is not authority | `S1` §9.1, §9.7; `S2` §3 |
| Architecture only observed; absence of observation | `S7` `OF-002`; `S8` §7; `S2` §4, §7 |
| The eight-way separation | **`INTERP`** — assembled from the above |

Classified statements `M6-S5-01` to `M6-S5-16`.

**Governance status:** `CONTROLLED GOVERNANCE` (`S1` §8.3, §6.6) ·
`PROPOSED GOVERNANCE` (`S2` §4, §5).

**Implementation status:** **`OBSERVED — QUALIFIED`** (`ARC-01` only) ·
**`NOT DEMONSTRATED`** (a governed input set).

**Teaching synthesis on this slide:** none. **One statement is `INTERP`** — the
eight-way separation.

**Prohibited on this slide**

- Treating an uploaded or visible file as a **controlled coordination input**.
- Presenting exclusion from a cycle as **absence from the project**.
- Presenting limited observed content as proof that other containers do not
  exist.
- Presenting any observed platform configuration as **the approved coordination
  environment** — **that matter is unresolved** (`OF-005`, `U2`).
- Shortening the twelve fields or the ten conditions in a way that changes
  meaning.
- **Inventing** a submission deadline · a completeness percentage · a
  model-health score · a required file format · a coordination frequency · a
  named approver · a suitability code · a platform workflow.

**Visual concept — high level**

**A gate, not a pipeline.** Left: the twelve register fields as a plain list.
Centre: the ten readiness conditions. Right: **two exits — *Included* and
*Excluded with a recorded reason*** — drawn at **equal weight**, because an
exclusion is a governed outcome, not a failure. The eight-way separation sits
beneath as a two-column table. **No percentage, no score, no traffic light.**

**Transition into Slide 6**

> *"Once you have a governed input set, you have to decide what to test — and
> Harrismith is explicit that you do not test everything."*

---

### Slide 6 — Checks are chosen, not exhaustive · 1.5 min

**Purpose of the slide**

Teach check selection as a **governed choice**, and fix the two things that
carry no authority: an unapproved threshold, and a clash count.

**On-slide copy**

> ## A check exists because a meaningful interface exists.
>
> ### Blind all-versus-all is not adopted — BEP §8.6
>
> > *"Testing everything against everything produces **volume, not insight**, and
> > **buries the findings that matter**."*
>
> **Clash detection is one coordination technique, not the whole of
> coordination.**
>
> ### Six check types — Coordination & Review Strategy §10
>
> | Type | |
> |---|---|
> | **Hard Clash** | A physical geometric intersection |
> | **Clearance / Access** | Required operating, installation, maintenance or access space |
> | **Alignment / Reference** | Inconsistent alignment, coordinates, levels, reference basis or positioning |
> | **Spatial Interface** | Elements competing for required space **without necessarily intersecting** |
> | **Information / Readiness** | Missing, incomplete, incorrectly identified or unsuitable input |
> | **Design / Interface Question** | A multidisciplinary interface requiring a **technical decision**, not necessarily a geometric clash |
>
> **Not every category depends on automated clash detection.** Alignment,
> readiness, spatial-interface and design-question matters are frequently
> identified **by review**, and are **no less governed for that**.
>
> ### Twelve proposed training interface checks — `CI-01` to `CI-12`
>
> `CI-01` ARC↔STR · `CI-02` STR↔MEC · `CI-03` STR↔ELE · `CI-04` STR↔PLM ·
> `CI-05` STR↔FIR · `CI-06` ARC↔MEC · `CI-07` ARC↔ELE · `CI-08` ARC↔PLM ·
> `CI-09` ARC↔FIR · `CI-10` MEC↔ELE · `CI-11` MEC↔PLM · `CI-12` MEC↔FIR
>
> **All twelve: Status `PROPOSED` · Tolerance / rule `TBD`.**
>
> > *"These are **PROPOSED TRAINING COORDINATION CHECKS**. They are **not**
> > evidence of real client requirements, and they **do not become project
> > requirements by appearing here**."*
>
> **Not all possible pairs are built.** The matrix stops at meaningful
> interfaces rather than completing the combinatorial set.
>
> ### No tolerance is approved — §11
>
> > *"**A software default tolerance is not a project requirement.** A value
> > shipped with a tool has no governance authority, and adopting it silently
> > would convert a vendor default into a project rule."*
>
> **Where no tolerance is approved, a check must not present a numeric threshold
> as though it carried governance authority.** The check may still run; **its
> output is a finding for triage, not a compliance judgement.**
>
> ### And the number nobody should quote
>
> > *"A clash count measures how much software found; it says nothing about
> > whether anything was **understood, decided or fixed**."* — BEP §8.1

**Source basis**

| Claim | Source |
|---|---|
| A check exists because a meaningful interface exists | `S2` §9 |
| Blind all-versus-all not adopted / not required | `S1` §8.6; `S2` §9 |
| Clash detection is one technique | `S1` §8.6; `S2` §1 |
| The six check types | `S2` §10 |
| Not every category depends on automated detection | `S2` §10 |
| The twelve checks, their pairs, `PROPOSED` status, `TBD` tolerances | `S2` §9 |
| Proposed training checks, not client requirements | `S2` §9 |
| Not all possible pairs are built | `S2` §9 |
| A software default is not a project requirement | `S2` §11 |
| No numeric threshold as governance authority; output is a finding | `S2` §11 |
| The clash-count warning | `S1` §8.1 |

Classified statements `M6-S6-01` to `M6-S6-15`.

**Governance status:** `CONTROLLED GOVERNANCE` (`S1` §8.1, §8.6) ·
**`PROPOSED GOVERNANCE`** (all twelve checks) · **`TBD`** (every tolerance).

**Implementation status:** **`NOT DEMONSTRATED`** — **no check is recorded as
executed**, and no coordination run has been demonstrated.

**Teaching synthesis on this slide:** none. **One statement is `INTERP`** — that
a check result requires interpretation before it means anything.

**Prohibited on this slide**

- Attaching **any numeric tolerance** to any check.
- Presenting a software default as approved, or as a starting point.
- Marking any check as **executed, passed or failed**.
- Implying every cycle must run every check.
- Implying the twelve cover every technical, regulatory or constructability
  concern.
- Presenting **"zero clashes"** as success or as coordination.
- Presenting a detected clash as a **design error**.
- Presenting **no detected clash** as proof of coordination.
- Red/green pass-fail treatment without the source-supported status wording.
- Importing software screenshots or platform defaults.
- Teaching Navisworks or ACC configuration.

**Visual concept — high level**

**A selection grid, deliberately incomplete.** The six discipline domains on
both axes, with **only the twelve built pairs marked** — **the unbuilt cells
stay visibly empty**, because the incompleteness is the teaching point. Every
marked cell carries **`PROPOSED`** and **`TBD`** in words. **No numeric value
appears anywhere on the slide.** The six check types sit beside as a plain list.
**No colour-coded pass/fail.**

**Transition into Slide 7**

> *"A check produces output. Output is not yet a finding anybody has accepted,
> and a finding is not yet an Issue. That gap is where the governance lives."*

---

### Slide 7 — Finding, clash, Issue: and the decision between them · 1.5 min

**Purpose of the slide**

Slide 2 named the three objects. **Slide 7 develops the decision between them** —
what an Issue must carry, what creating one does and does not establish, and the
recorded scope variance between the two controlled definitions.

**On-slide copy**

> ## Detection produces output. A decision produces an Issue.
>
> ### The three objects, and the boundary
>
> | **Finding** | An observed coordination matter **requiring triage** |
> |---|---|
> | **Clash** | A **geometric or spatial** finding, generated or identified through review |
> | **Issue** | A **governed action record** |
>
> ### **`Clash / finding ≠ Issue`**
>
> > *"**Creating an issue is a decision.**"* — BEP §8.7
> > *"A decision taken **at triage**, not an automatic consequence of
> > detection."* — Strategy §12
>
> ### An Issue is created when a matter requires — Strategy §12
>
> **ownership** · **action** · **decision** · **tracking** · **verification** ·
> **escalation** — *"or otherwise needs a controlled project record"*
>
> **Not every clash becomes an Issue.** *"Many findings are tolerable,
> duplicated, out of scope, already known, or artefacts of the test setup."*
>
> ### A non-geometric matter can still need an Issue
>
> **`Information / Readiness`** and **`Design / Interface Question`** are check
> types too. **A missing input and an unresolved interface decision are governed
> matters — neither is a clash.**
>
> ### An Issue should normally carry — BEP §8.7
>
> what the problem is · the affected information or interface · the responsible
> task team or role · the required action or outcome · status · relevant evidence
> and context
>
> ### Two controlled scopes. Recorded, not merged.
>
> | Source | Issue is created when a matter requires |
> |---|---|
> | **BEP §8.7** | assignment · tracking · decision · verification |
> | **Strategy §12** | ownership · action · decision · tracking · verification · escalation · **or otherwise needs a controlled project record** |
>
> **The strategy is broader. Neither is rewritten to match the other.**
>
> ### What creating an Issue does **not** establish
>
> **that it was correctly classified · correctly assigned · resolved · verified**
>
> **The seven Issue types are `PROPOSED` governance concepts.**
> *"These are **not Autodesk system-native labels**, and no claim is made that
> the platform provides them."* **A platform object type does not override a
> controlled definition.**

**Source basis**

| Claim | Source |
|---|---|
| Finding, Clash, Issue definitions | `S2` §12 |
| `Clash / finding ≠ Issue` | `S2` §12; `S1` §8.7 |
| Creating an issue is a decision, taken at triage | `S1` §8.7; `S2` §12 |
| The six Issue-creation criteria plus the residual limb | `S2` §12 |
| Not every clash becomes an Issue; the five reasons | `S1` §8.7; `S2` §12 |
| `Information / Readiness` and `Design / Interface Question` check types | `S2` §10 |
| What an Issue should normally carry | `S1` §8.7 |
| The two Issue scopes | `S1` §8.7; `S2` §12 — **variance 3** |
| Issue types are not Autodesk-native labels | `S2` §14 |
| No project issue numbering or status codes defined by the BEP | `S1` §8.7 |

Classified statements `M6-S7-01` to `M6-S7-16`.

**Governance status:** `CONTROLLED GOVERNANCE` (`S1` §8.7) ·
**`PROPOSED GOVERNANCE`** (`S2` §12, §14).

**Implementation status:** **`OBSERVED — QUALIFIED`** — one open
Coordination-type Issue observed; **`NOT DEMONSTRATED`** — no completed
classification, assignment, resolution or verification established.

**Teaching synthesis on this slide:** none. **Two statements are `INTERP`** —
the recorded scope variance, and that a non-geometric matter may require a
governed record.

**Prohibited on this slide**

- Repeating Slide 2's vocabulary walk instead of developing the decision.
- Presenting **every clash** as an Issue, or **every finding** as a clash.
- Implying detection alone creates a governed record.
- Claiming **creating an Issue proves valid triage**, classification,
  assignment, resolution or verification.
- Harmonising the two Issue scopes, or picking one as correct.
- Implying an Autodesk, ACC or Navisworks object type **overrides** the
  controlled definitions.
- Inventing an Issue identifier, numbering scheme or status code.
- **Teaching the triage dispositions** — Slide 8 owns them.
- **Teaching assignment, response or status progression** — Slides 9 and 10.

**Visual concept — high level**

**A decision point, not a conveyor.** Left: findings — a mixed set, **some
geometric, some not**. Centre: a single labelled decision, *"does this require
ownership, action, decision, tracking, verification or escalation?"*. Right:
**two outcomes at equal weight — an Issue, and a disposition without one.**
**The two Issue scopes appear as a two-row comparison, side by side, neither
styled as preferred.** No platform imagery, no invented identifier.

**Transition into Slide 8**

> *"That decision has seven recorded outcomes — and one of them uses a word that
> means something completely different three sections later."*

---

### Slide 8 — Triage: seven dispositions, one dangerous word · 1.0 min

**Purpose of the slide**

Show the seven recorded triage outcomes, and prevent the single most damaging
word-collision in the module.

**The 1.0-minute allocation is tight. The copy is a table and one warning —
deliver it as a list, not as prose.**

**On-slide copy**

> ## Seven outcomes. One of them is a trap.
>
> ### Finding triage — Coordination & Review Strategy §13
>
> | Disposition | What it records |
> |---|---|
> | **No action / false positive** | Not a real coordination matter for the defined check |
> | **Accepted condition** | Requires no further action **for the defined check and coordination purpose** |
> | **Action required — one task team** | A single team must respond |
> | **Action required — multiple task teams** | More than one team must respond |
> | **Decision required** | A technical or governance decision is needed **before** action |
> | **Deferred** | Carried forward, **with a recorded reason** |
> | **Escalated** | Raised beyond the normal cycle |
>
> **Seven. Not six, not eight.**
>
> > *"**Material dispositions remain traceable.** A finding closed without record
> > is a finding that will be rediscovered."*
>
> ### A disposition is not four other things
>
> | A triage disposition is **not** | |
> |---|---|
> | an **Issue status** | that model is Slide 10 |
> | an **information state** | coordination creates none |
> | a **suitability code** | none exists on this project |
> | **recipient acceptance** | a separate function, after delivery |
>
> ---
>
> ### ⚠ `Accepted condition`
>
> > *"**'Accepted condition' does not mean recipient acceptance or design
> > approval.** It means only that the coordination finding requires no further
> > action **for the defined check and coordination purpose**. It is a
> > coordination disposition **and nothing more**."*
>
> **`Accepted condition` is not:**
>
> recipient **`Accept`** · publication authorisation · technical approval of the
> design · regulatory acceptance · acceptance of the container for **every** use
>
> **And it does not:**
>
> release **`T4`** · resolve recipient acceptance authority · unblock
> **`TRN-E03`**
>
> **Status:** `PROPOSED GOVERNANCE` · **`NOT DEMONSTRATED`** — no completed
> triage decision has been established.

**Source basis**

| Claim | Source |
|---|---|
| The seven triage dispositions, verbatim | `S2` §13 |
| Material dispositions remain traceable | `S2` §13 |
| `Accepted condition` is not recipient acceptance or design approval | `S2` §13; `S1` §9.2, §9.8 |
| A disposition is not an Issue status | `S2` §13, §15 |
| Coordination creates no information state | `S2` §24; `S6` |
| No suitability code set exists | `S1` §11; `S11` — teaching carry-forward |
| Recipient acceptance is a separate post-delivery function | `S1` §9.8 |
| `T4` blocked; `TRN-E03` blocked; acceptance authority unresolved | `S1` §9.7, §9.8; `S5`; `S6`; `S10`, `S11` |
| No completed decision established | `S7` `OF-007`; `S8` §8 |

Classified statements `M6-S8-01` to `M6-S8-15`.

**Governance status:** **`PROPOSED GOVERNANCE`** (`S2` §13) ·
`CONTROLLED GOVERNANCE` (`S1` §9.2, §9.8) · **`UNRESOLVED`** (acceptance
authority) · **`BLOCKED`** (`T4`, `TRN-E03`).

**Implementation status:** **`NOT DEMONSTRATED`** — *"No completed review,
authorisation, verification or closure was established."*

**Teaching synthesis on this slide:** none. **One statement is `INTERP`** — the
four-way *"a disposition is not"* separation.

**Prohibited on this slide**

- Showing **fewer or more than seven** dispositions.
- Merging two dispositions for visual simplicity.
- Renaming a disposition, or paraphrasing its recorded wording.
- Presenting a disposition as an **Issue status**, an **information state**, a
  **suitability code** or **recipient acceptance**.
- Presenting **`Accepted condition`** as acceptance, approval, authorisation or
  regulatory clearance.
- Implying `Accepted condition` releases `T4`, resolves acceptance authority or
  unblocks `TRN-E03`.
- Claiming any triage decision **has been taken** on this project.
- **Teaching the Issue status model** — Slide 10 owns it.

**Visual concept — high level**

**A seven-row table, and one call-out that cannot be missed.** The seven
dispositions carry **equal visual weight** — none is styled as the normal or
preferred outcome. **`Accepted condition` is marked with a warning glyph and a
call-out**, placed so it reads as a caution rather than a recommendation. The
*"is not"* comparisons sit as a compact four-row block. **No colour-only
signalling**, and **no eighth row for any reason**.

**Transition into Slide 9**

> *"Four of those seven send work somewhere. Which raises the question Slide 9
> answers: who owns the fix — and what does an assignment actually prove?"*

**Slide 9 is architecture only after T6-B.** If you are presenting before Slide
9 is developed, **stop here and say so.**

---

## 5. Slides 9–14 — architecture only

**No on-slide copy, source basis, classified statements or speaker notes exist
for these slides.** The entries below record intended function only, and **may
be corrected by source analysis in a later increment.**

### Section D — Response, verification and closure · 6.0 min

| Slide | Working title | Time | Intended function |
|---|---|---:|---|
| **9** | Assignment and technical response — who owns the fix | 1.5 | What an assignment identifies; **no dates invented**; resolution in the originating team's WIP; `X1`–`X5` allocation |
| **10** | The Issue status model is not an information state | 1.5 | The proposed status model and alternate dispositions; **not claimed to be configured**; a status is not a state, a suitability code or an approval |
| **11** | Verification — after reshare, against controlled information | 1.5 | The preconditions for verification; the three satisfaction conditions; **verification is not design approval, certification, publication authority or acceptance**; the recorded `may`/`must` variance |
| **12** | Completion is not zero clashes | 1.5 | The completion conditions; **completion is cycle- and purpose-specific**; a zero-clash report proves nothing on its own |

### Section E — Evidence, assurance and transfer · 3.0 min

| Slide | Working title | Time | Intended function |
|---|---|---:|---|
| **13** | Evidence, escalation, and what a closed Issue does not prove | 1.0 | The coordination evidence outputs; escalation without an invented decision owner; **assurance is allocated but no sampling method is established**; what closure does and does not evidence |
| **14** | What Triviron must decide about coordination | 2.0 | **Questions only.** No Triviron answer, no Module 7 translation |

**Section totals: A 2.5 · B 3.0 · C 5.5 · D 6.0 · E 3.0 = 20.0.**

---

## 6. Status

| Field | Value |
|---|---|
| Increment | **T6-B — Slides 4–8 developed.** T6-A established the foundation and Slides 1–3 |
| Slides developed | **1–8** — each with on-slide copy, source basis, classified statements, prohibited claims, a high-level visual concept and a transition |
| Architecture only | **Slides 9–14** |
| Sections | **Five** — A 2.5 · B 3.0 · C 5.5 · D 6.0 · E 3.0 |
| Timing | **`20.0 minutes allocated — not measured`** · total verified at **20.0** |
| Slide progression | **No automatic slide-transition timing.** Presenter advances manually when ready |
| Classified statements | **125** — 49 (Slides 1–3, T6-A) + 76 (Slides 4–8, T6-B) |
| Exercises | **None.** Not created in T6-A or T6-B |
| Visual specifications / sources / assets | **None.** Not created in T6-A or T6-B |
| Assembly package | **None** |
| PowerPoint | **None** |
| Review, rehearsal, measured timing | **None performed** |
| Complete governed coordination cycle | **NOT DEMONSTRATED.** `GCR-006` **OPEN** |
| Outstanding | **T6-C** — develop Slides 9–12. **Not started** |
