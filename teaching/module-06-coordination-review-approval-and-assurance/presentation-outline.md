# Module 6 — Presentation Outline

**Status:** **Slides 1–3 developed in T6-A. Slides 4–14 are architecture only.**

**An architecture is not a developed slide.** Slides 4–14 record a title, a time
and an intended function. **They carry no on-slide copy, no source basis, no
classified statements and no speaker notes**, and must not be presented as
though they did.

**There is no visual specification, no visual source, no asset, no exercise set,
no assembly package and no PowerPoint**, and no review or rehearsal has been
performed.

Source identifiers `S1`–`S14` are defined in
[`source-inventory.md`](source-inventory.md). Statement classification is in
[`source-map.md`](source-map.md) §3. Presenter notes for **Slides 1–3** are in
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
| 4 | Federation — a lens, not an author | 1.5 | Architecture only |
| 5 | Inputs and readiness — what may enter a cycle | 1.5 | Architecture only |
| 6 | Checks are chosen, not exhaustive | 1.5 | Architecture only |
| 7 | Finding, clash, Issue — and the decision between them | 1.5 | Architecture only |
| 8 | Triage — seven dispositions, one dangerous word | 1.0 | Architecture only |
| 9 | Assignment and technical response — who owns the fix | 1.5 | Architecture only |
| 10 | The Issue status model is not an information state | 1.5 | Architecture only |
| 11 | Verification — after reshare, against controlled information | 1.5 | Architecture only |
| 12 | Completion is not zero clashes | 1.5 | Architecture only |
| 13 | Evidence, escalation, and what a closed Issue does not prove | 1.0 | Architecture only |
| 14 | What Triviron must decide about coordination | 2.0 | Architecture only |
| | **Total** | **20.0** | **3 of 14** |

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
| T6-B onward | 4–14 | **Not started** |

**Each developed slide carries:** purpose · exact title · allocated time ·
on-slide copy · source basis · classified-statement range · governance status ·
implementation status · prohibited claims · a **high-level** visual concept · a
transition. **Presenter notes are in [`speaker-notes.md`](speaker-notes.md).**

**The visual concepts are high-level only.** They record what a visual must show
and must not show. **They are not visual specifications**, and **no visual
specification, visual source or asset directory exists.**

---

## 4. Developed slides — 1 to 3

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

## 5. Slides 4–14 — architecture only

**No on-slide copy, source basis, classified statements or speaker notes exist
for these slides.** The entries below record intended function only, and **may
be corrected by source analysis in a later increment.**

### Section B, continued

| Slide | Working title | Time | Intended function |
|---|---|---:|---|
| **4** | Federation — a lens, not an author | 1.5 | `COORD-01` as a temporary controlled aggregation; the four things federation does **not** do; originator responsibility before and after |

### Section C — From input to Issue · 5.5 min

| Slide | Working title | Time | Intended function |
|---|---|---:|---|
| **5** | Inputs and readiness — what may enter a cycle | 1.5 | The coordination input register; readiness conditions; **readiness is not design completeness**; exclusion with a recorded reason as a governed outcome |
| **6** | Checks are chosen, not exhaustive | 1.5 | Why blind all-versus-all is not adopted; the proposed interface checks and check types; **no numeric tolerance exists, and a software default is not a project requirement** |
| **7** | Finding, clash, Issue — and the decision between them | 1.5 | The Issue taxonomy as **proposed governance concepts, not platform-native labels**; what an Issue must carry; why creating one is a decision |
| **8** | Triage — seven dispositions, one dangerous word | 1.0 | The triage outcomes; **"Accepted condition" is not acceptance**; material dispositions remain traceable |

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
| Increment | **T6-A — Module 6 foundation, source architecture and Slides 1–3** |
| Slides developed | **1, 2, 3** — each with on-slide copy, source basis, classified statements, prohibited claims, a high-level visual concept and a transition |
| Architecture only | **Slides 4–14** |
| Sections | **Five** — A 2.5 · B 3.0 · C 5.5 · D 6.0 · E 3.0 |
| Timing | **`20.0 minutes allocated — not measured`** · total verified at **20.0** |
| Slide progression | **No automatic slide-transition timing.** Presenter advances manually when ready |
| Classified statements | **49**, Slides 1–3 only |
| Exercises | **None.** Not created in T6-A |
| Visual specifications / sources / assets | **None.** Not created in T6-A |
| Assembly package | **None** |
| PowerPoint | **None** |
| Review, rehearsal, measured timing | **None performed** |
| Complete governed coordination cycle | **NOT DEMONSTRATED.** `GCR-006` **OPEN** |
| Outstanding | **T6-B** — the next Module 6 increment. **Not started** |
