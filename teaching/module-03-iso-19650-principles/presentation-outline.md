# Module 3 — Presentation Outline

**Status:** Working outline. **Full content baseline — Slides 1–14 developed.**
This is **not a final presentation**: no visual source exists, no deck has been
assembled, and the timing below is an allocation that has never been measured.

Every ISO-related statement in this file is bounded by
[`external-source-register.md`](external-source-register.md). Classification is
in [`source-map.md`](source-map.md).

---

## 1. Working timing structure — 20 minutes

| Section | Slides | Time |
|---|---|---:|
| **A — What ISO 19650 is** | 1, 2, 3 | 4.0 min |
| **B — Why information management comes first** | 4, 5, 6 | 4.5 min |
| **C — Who manages information** | 7, 8, 9 | 4.5 min |
| **D — How control and planning work** | 10, 11 | 3.0 min |
| **E — Application, limits and transfer** | 12, 13, 14 | 4.0 min |
| **Total** | **14** | **20.0 min** |

## 2. Slide architecture — fourteen slides

| Slide | Title | Time | Developed |
|---|---|---:|---|
| 1 | ISO 19650 is an information-management framework | 1.5 | ✅ |
| 2 | It governs information, not a software platform | 1.5 | ✅ |
| 3 | Part 1 and Part 2 answer different questions | 1.0 | ✅ |
| 4 | Information management runs across the asset life cycle | 1.5 | ✅ |
| 5 | Information requirements come before information production | 1.5 | ✅ |
| 6 | The right information — not simply more information | 1.5 | ✅ |
| 7 | Information-management functions are not automatically job titles | 1.5 | ✅ |
| 8 | The parties, the teams and the vocabulary gap | 1.5 | ✅ |
| 9 | Information containers make responsibility manageable | 1.5 | ✅ |
| 10 | The CDE controls permitted use and exchange | 1.5 | ✅ |
| 11 | Information delivery must be planned | 1.5 | ✅ |
| 12 | A principle is not a platform configuration | 1.0 | ✅ |
| 13 | **How Harrismith may be mapped — and where the evidence stops** | 2.0 | ✅ |
| 14 | What Triviron must verify before claiming alignment | 1.0 | ✅ |
| | **Total** | **20.0** | **14 of 14** |

### Refinements to the proposed sequence

Four changes were made to the provisional fourteen-slide list. The count, the
progression and the twenty-minute total are unchanged.

| # | Change | Why |
|---|---|---|
| 1 | Slide 3 retitled *Part 1 and Part 2 answer different questions* | The provisional title stated the answer. A question framing survives the fact that neither text has been read — the slide compares **stated scope**, which is all the available evidence supports |
| 2 | Slide 8 retitled *The parties, the teams and the vocabulary gap* | The provisional title listed ISO-associated party terms. Listing them on a Harrismith-worked-example slide is precisely how `Lead Delivery Party` silently becomes `lead appointed party`. The retitled slide makes the **gap** the subject |
| 3 | Slide 12 cut to **1.0 min** | Slide 2 already separates principle from platform. Slide 12 is the reprise applied to *configuration*, and does not need to re-argue the case |
| 4 | Slide 13 raised to **2.0 min** — the longest in the module | It is the module's honesty slide and the only place a conformity misunderstanding can be corrected. It is also the slide most likely to be cut when running late, which is exactly why it is allocated most |

### Three notes on the allocation

- **Slide 13 is the longest and must not be cut.** If time is short, cut from
  Slide 4 or Slide 10 — both have later modules behind them. Nothing else in the
  programme corrects a conformity misunderstanding.
- **Slides 10 and 11 are capped at 1.5 min each on purpose.** They belong in
  detail to Modules 4 and 5. The cap is the module boundary, expressed as time.
- **Section A is front-loaded at 4.0 minutes for three slides.** The audience's
  existing beliefs about "the BIM standard" are corrected here or not at all.

## 3. Module-boundary control

| Slide | Stays at | Hands off to |
|---|---|---|
| 9 | The **concept** of a container as the unit responsibility attaches to | Module 5 — container allocation, row by row |
| 10 | **Why** states and controlled exchange exist | Module 4 — the state set, transitions and their evidence |
| 11 | **Why** delivery is planned rather than assumed | Module 5 — delivery events, purpose and suitability |
| 12 | Configuration follows decision | Module 6 — verification that it did |

**Test to apply when developing Slides 4–14:** if a slide explains *how a
transition is executed, who signs what, or what a matrix cell contains*, it has
left Module 3. Module 3 explains **why the control exists**.

---

## 4. Developed slides — the full content baseline

Speaker notes: [`speaker-notes.md`](speaker-notes.md). Statement classification:
[`source-map.md`](source-map.md) §4. Source identifiers `X1`–`X6`, `H1`, `H2` are
defined in [`external-source-register.md`](external-source-register.md).

### Slide 1 — ISO 19650 is an information-management framework · 1.5 min

**Purpose of the slide**

Introduce ISO 19650 as a structured **information-management framework** — not a
software standard, not a modelling manual, and not a naming convention. Establish
the subject before any audience assumption fills the gap.

**What the standard is stated to concern**

Five points, all within `X1`'s publicly summarised scope:

| # | | |
|---|---|---|
| 1 | **The information needed for decisions** | Information exists to be relied on, not to be produced |
| 2 | **How that information is specified** | What is needed is stated before it is made |
| 3 | **How it is produced and managed** | Production is managed, not incidental |
| 4 | **How it is exchanged and recorded** | Exchange is deliberate; the record survives it |
| 5 | **Its use across built assets and organisations** | The framework is not tied to one asset type or one organisation |

*(Paraphrase of publicly summarised scope — `X1`, with the cross-organisation
reach also supported by `X2`. **No clause is cited, because none has been
read.**)*

**Suggested teaching message**

> ISO 19650 is about managing information so that the right people can rely on
> the right information for the right purpose.

*(**Teaching synthesis.** No source sentence says this. It is not an ISO
quotation and must not be presented as one — `source-map.md` §4, `M3-S1-05`.)*

**The module's central message, introduced here**

> ISO 19650 provides a structured approach for defining, producing, exchanging
> and managing the information needed to support decisions throughout an asset's
> life cycle.

*(**Teaching wording derived from publicly supported scope** — consistent with
`X1` and `X2`, not quoted from either.)*

**Five things this slide must not say**

| Must not say | Why |
|---|---|
| ISO certifies a particular Autodesk workflow | ISO certifies no vendor workflow, and nothing in `X1`–`X6` supports it |
| Using Revit or ACC means a project complies | Software use is not conformity; see Slide 2 |
| Harrismith is ISO-compliant | `H1` §11.2 and §13.4 expressly claim **no** compliance |
| ISO 19650 is merely a naming standard | Naming is one topic among many; `H1` §11.3 records that **no ISO filename pattern is imposed** on this project |
| ISO 19650 is a BIM software manual | The publicly summarised scope is information management, not tools |

**The subtraction that does the teaching.** The fastest route into the subject is
what it is *not*. An audience arriving with "the BIM standard" in mind is holding
a software expectation, and it must be removed before anything else lands.

**Honesty note.** This slide names a standard the presenter has not read. Say so
once, early, plainly — see [`speaker-notes.md`](speaker-notes.md) Slide 1. It
costs ten seconds and buys the audience's trust for the remaining nineteen
minutes.

### Slide 2 — It governs information, not a software platform · 1.5 min

**Purpose of the slide**

Separate **management principles** from **technology implementation** — the
single most common misunderstanding in the room, and the one that makes every
later slide unteachable if it survives.

**Five distinctions**

| # | Distinction | Support |
|---|---|---|
| 1 | A software platform may **support** the process | `H1` §6.1 — the CDE is *"an information-management process supported by technology"* |
| 2 | **A CDE is not defined by purchasing a platform** | `H1` §6.1 — *"It is not a folder tree"* |
| 3 | **Permissions do not create authority** | `H1` §6.9 — permissions and platform roles *"support the process; they do not create professional or governance authority"* |
| 4 | **Folder location does not establish information status** | `H1` §6.8 — state, version, revision, status and suitability are five separate properties; a new platform version *"creates none of the others"* |
| 5 | Technology should **implement** agreed arrangements | `H1` §12.1 — decision precedes configuration |

**All five are Harrismith wording (`H1`), used as a worked analogy.** They are
**not** ISO definitions and are not attributed to `X1` or `X2`. Any of them may
turn out to be phrased differently in the standard; none has been verified
against it.

**The corroborating observation, and its limit**

`docs/Increment-7C-Live-Validation-Record.md` records the point in the sharpest
available form: *"Folder names do not themselves prove ISO 19650 governance."*

That is a Harrismith observation about a Harrismith environment. It is good
evidence that this project holds the position — and **no** evidence about what
the standard requires.

**Connection to the previous modules — brief, then move on**

| Module | Established | One line on this slide |
|---|---|---|
| **1** | The BEP records the agreed method | *"Module 1: the BEP is where the method is written down."* |
| **2** | Functions and authorities must be assigned | *"Module 2: someone has to hold each function."* |
| **3** | ISO 19650 supplies the wider framework | *"Module 3: this is the framework all of that sits inside."* |

**Three lines, roughly fifteen seconds.** Do not re-teach either module. If the
audience did not attend them, the lines still work as orientation.

**The trap to name aloud**

> "We bought the platform, so we have a CDE."

Purchasing is procurement. A CDE is a process. The platform can support the
process, host it, and record it — and can equally host no process at all.

**Suggested teaching message**

> A platform can hold your information. It cannot decide who may rely on it, or
> for what.

*(**Teaching synthesis**, consistent with `H1` §6.1 and §6.9 — `source-map.md`
§4, `M3-S2-08`.)*

### Slide 3 — Part 1 and Part 2 answer different questions · 1.0 min

**Purpose of the slide**

Distinguish the two currently published core parts used in this module, and
record — without teaching — that both are under revision.

**The comparison**

| | **`ISO 19650-1:2018`** | **`ISO 19650-2:2018`** |
|---|---|---|
| **Answers** | *What is this about, and on what principles?* | *How is information managed while an asset is delivered?* |
| **Publicly summarised scope** | Concepts and principles; an information-management framework; exchanging, recording, versioning and organising information | An information-management process for the **delivery phase** of assets, including the information exchanges within it |
| **Reach** | Across the **whole asset life cycle** | Applicable across asset types, organisations and procurement strategies |
| **Register entry** | `X1` — A1, public metadata only | `X2` — A1, public metadata only |

*(Both columns are paraphrases of publicly summarised scope. **No clause,
definition, table or figure from either part is reproduced**, because neither has
been read for this programme.)*

**Required warning — say it, do not imply it**

Both published editions are **under revision** (`X3`, `X4`).

| Rule | |
|---|---|
| **Record** | A revision project exists for each part |
| **Do not teach** | Any draft wording, stage, scope or date — none is established, and none is to be invented |
| **Do not displace** | The 2018 editions remain the current published editions throughout this module |

**Suggested message**

> Part 1 explains the conceptual framework; Part 2 applies an
> information-management process to asset delivery.

*(**Supported interpretation** — follows from the `X1` and `X2` scope summaries;
neither states it in these words — `source-map.md` §4, `M3-S3-07`.)*

**Why this slide is only one minute**

It is a two-column comparison with one warning. It does not need longer, and
Exercise 4 in [`exercises.md`](exercises.md) rehearses it at exactly sixty
seconds. Resist expanding it — the expansion available is clause detail, and
there is none to give.

**What this slide must not become**

| Must not | Because |
|---|---|
| A list of Part 2's process activities | Not available; inventing a numbered process is the worst failure mode in this module |
| A parts-of-the-series overview | Other parts exist and are **not registered** in `external-source-register.md`. Name only what is registered |
| A comparison of 2018 against the drafts | The drafts' content is not established |

### Slide 4 — Information management runs across the asset life cycle · 1.5 min

**Purpose of the slide**

Show that managed information supports decisions across the life of an asset —
not only while a model is being produced. Open Section B by widening the frame
before narrowing it again on Slides 5 and 6.

**The one public-source anchor**

Part 1's application **extends across the asset life cycle** (`X1`). That is the
whole external basis for this slide, and it is a statement of reach, not a list
of phases.

**Decision points across an asset's life — neutral teaching labels**

| | Phase | Example decision the information serves |
|---|---|---|
| 1 | **Strategic need or initiation** | Is this asset needed at all, and at what scale? |
| 2 | **Design and delivery** | Does this solution work, and do the disciplines agree? |
| 3 | **Construction or production** | Can this be built as information describes it? |
| 4 | **Commissioning and handover** | Does what was built match what was intended? |
| 5 | **Operation and maintenance** | What is this, where is it, and how is it serviced? |
| 6 | **Alteration, renewal or end of life** | What may be changed, and what must be preserved? |

***These are neutral teaching labels, not ISO-defined phase names.*** No stage
vocabulary is available to this programme. **Nothing here is numbered**, and the
list must not be presented as *the* life-cycle model — see
[`source-map.md`](source-map.md) §4, `M3-S4-04`.

**Required message**

> The value of information is not confined to producing the model; it lies in
> supporting decisions throughout the life of the asset.

*(**Supported interpretation** — follows from `X1`'s stated life-cycle reach; no
source phrases it this way — `M3-S4-06`.)*

**Four consequences, which are the actual teaching**

| # | | |
|---|---|---|
| 1 | **The asset outlives the team** | A building may stand for decades after the delivery team disbands. Nobody who authored the information will be available to explain it |
| 2 | **Information must survive its authoring context** | It has to remain understandable and usable to people who were never in the room — which is a management property, not a modelling one |
| 3 | **Delivery-phase information feeds later decisions** | What is produced now is what someone operates from later |
| 4 | **Information with no identified future purpose has little lasting value** | Producing it is not free, and keeping it is not free either |

**Consequence 2 is the slide.** If only one thing survives, it is that
information must remain usable after everyone who made it has gone.

**The misconception to kill on this slide**

> "So one model carries on through the whole life of the building."

**No.** Life-cycle continuity is **continuity of managed information**, not the
survival of a single unchanged file. Information is produced, superseded,
replaced, transformed and re-authored; what continues is that it remains
identifiable, understandable and reliable for the decision at hand.

**Harrismith connection — a gap, stated as a gap**

| | |
|---|---|
| What Harrismith does | Concentrates on **delivery governance** — production, coordination, checking, controlled sharing and delivery |
| What it does not do | BEP §3.3 places **asset management, handover and standards verification outside current scope** — *"not current requirements and not part of the current baseline scope"*, noted only as uses that may be considered later, **following an explicit decision to extend scope** |
| Where handover appears | Only as an **example purpose** — *record / handover information* — in BEP §6.7 and §10.3, both of which say *examples only, not current project milestones* |
| Category | **`GAP OR UNVERIFIED`** |

**Say what this gap is and is not.** It is a **deliberately bounded scope**, and
the BEP records the boundary rather than leaving it to be discovered. It is
**not** a failure, **not** evidence of non-conformity, and **not** an invitation
to invent operational requirements for a fire station that has none.

**One precision worth making.** Harrismith's own lifecycle language is about the
**information container** — BEP §2.2 has participants working *"the whole
lifecycle of an information container"*, and BEP §7.1 uses *lifecycle* for the
requirement-to-use chain. **That is a container lifecycle, not an asset life
cycle.** Two different spans sharing one word, and conflating them would put an
asset-life-cycle claim into a document that does not make one.

### Slide 5 — Information requirements come before information production · 1.5 min

**Purpose of the slide**

Show that a team cannot decide what to produce until someone establishes what is
needed, why, and when it will support a decision. This is Section B's hinge.

**The sequence, at principle level**

```text
Decision or purpose
  → information need
  → defined requirement
  → planned production
  → checked delivery
  → use
```

*(**Teaching structure**, consistent with BEP §7.1's production chain and §10.1's
delivery principles. **No source presents these six steps in this form** —
`M3-S5-08`.)*

**The sourced statement that carries the slide**

> Production begins from a requirement, not from availability of time or tools.

*(BEP §7.1 — Harrismith wording, quotable verbatim as **ours**.)*

And its companion, BEP §7.3:

> Information production is driven by **defined requirements**, not by assumption
> about what might be wanted.

**What a useful requirement answers**

| # | Question | In the sources |
|---|---|---|
| 1 | What **decision or use** does this support? | BEP §7.3 — *the purpose*; §10.1 — *a purpose* |
| 2 | **Who** needs it? | BEP §7.3 — *the intended recipient*; §10.1 — *a recipient* |
| 3 | **What** information is needed? | BEP §7.3 — *the container required*; §10.1 — *required content* |
| 4 | **When** is it needed? | BEP §7.3 — *the milestone or exchange it serves*; §10.1 — *timing / event* |
| 5 | What **level of definition or reliability**? | **Not established** — see Slide 6 |
| 6 | How will it be **checked**? | BEP §7.3 — *the checking requirement*, *the authorisation requirement* |
| 7 | What **form or container** is suitable? | BEP §7.3 — *the required format*; §10.1 — *format* |

*(Questions 1–4, 6 and 7 are **Harrismith evidence** — BEP §7.3's nine-item list
and §10.1's delivery grid. Question 5 is **unresolved** on this project and is
Slide 6's subject.)*

**This is a conceptual list, not a template.** Seven questions to think with. **No
information-requirement template is produced here**, and building one is not
Module 3's job.

**Official implementation guidance — UK context**

`X6` supports the point that information-management requirements should be
established **appointment by appointment**, rather than settled once at project
level and assumed to hold everywhere.

> **`OFFICIAL IMPLEMENTATION GUIDANCE — UK CONTEXT` (`X6`).** This is how the
> framework is implemented in the UK. It is **not ISO wording**, not a universal
> national annex, and not automatically applicable in South Africa.

**The first `GUIDANCE` statement in the module**, and the labelling convention is
set here: **said aloud, and marked on the slide.** Do not say *"ISO requires this
appointment workflow"* — no available source supports that.

**Two prohibitions that hold for the rest of the module**

| Prohibited | Why |
|---|---|
| **Any information-requirement acronym** — the client-, exchange-, asset- and project-level requirement abbreviations | **No definition-level source is registered.** Using the abbreviations invites precisely the clause-level questions this module cannot answer |
| Presenting the six-step sequence as the standard's process | It is teaching structure. Part 2's process has not been read |

**One nuance, stated carefully.** BEP §7.3 does record that **no formal
Employer's / Exchange Information Requirements, Asset Information Requirements or
equivalent have been established or made available** to this implementation.
**That is Harrismith recording an absence, not this module defining the terms.**
Use it as evidence of the gap if asked; do not build teaching vocabulary on it,
and do not explain what any of those documents contains.

**Harrismith connection — the gap, and why it is the right response**

| | |
|---|---|
| The evidence | BEP §7.3 and §10.2: *"No formal information requirements are available to this implementation"*, and *"where formal client or project information requirements have not been established or made available… **they are not invented**"* |
| The related gaps | BEP §2.3 — procurement route, contract type, contractual milestones and final delivery programme are all **not established, TBD** |
| What follows | The delivery schedule uses **event-triggered and TBD entries** rather than invented dates, and training-developed requirements are labelled **PROPOSED GOVERNANCE or TRAINING ASSUMPTION** rather than presented as client requirements (BEP §7.3, §10.2) |
| Category | **`GAP OR UNVERIFIED`** |

**The teaching point is the discipline, not the deficiency.** A project that does
not know its requirements and says so has done something harder than a project
that guesses. And BEP §1.5's precedence rule closes it: if real requirements
later arrive, **they take precedence over anything developed in their absence**.

**Do not present this gap as ISO non-conformity.** No conformity assessment
exists in either direction — see [`source-map.md`](source-map.md) §7.

**Required message**

> Information production should be a response to an identified need — not an
> activity that searches for a purpose afterwards.

*(**Teaching synthesis**, consistent with BEP §7.1 and §7.3 — `M3-S5-11`.)*

### Slide 6 — The right information, not simply more information · 1.5 min

**Purpose of the slide**

Correct the belief that better BIM means more information. Close Section B by
turning the requirements-first principle into a judgement about **quantity and
quality**.

**Proportionate to what?**

Information is proportionate — or not — against six things:

| # | Proportionate to | |
|---|---|---|
| 1 | **The decision** | What is actually being decided |
| 2 | **The recipient** | Who has to act on it |
| 3 | **The delivery event** | The exchange it serves |
| 4 | **The asset or element** | A door handle and a structural frame do not warrant the same treatment |
| 5 | **The required reliability** | How much weight the decision puts on it |
| 6 | **The stage or context of use** | What is knowable, and what is needed, at that point |

*(**Supported interpretation**, built from BEP §7.3's requirement fields, §10.1's
delivery grid and §6.1's *sharing is purposeful* / *publication is purposeful*
principles. **No source lists these six** — `M3-S6-03`.)*

**The comparison**

| **More information** | **Right information** |
|---|---|
| Produced because the software can | Supports an **identified decision** |
| Duplicated across containers | Has a **known originator** |
| Delivered without a defined purpose | Has a **defined recipient and purpose** |
| Detail that cannot be checked or maintained | Delivered **at the appropriate time** |
| Unclear recipient or use | Can be **checked, maintained and relied upon** for that use |

***Teaching examples. Not ISO quotations, and not a conformity checklist.*** The
right-hand column is recognisably the shape of BEP §7.3's requirement fields and
§1.1's *known originator, known state, known route, known accountable role* — but
the pairing and the wording are the presenter's — `M3-S6-04`.

**Five things to say about proportion**

| # | | |
|---|---|---|
| 1 | **Completeness is purpose-dependent** | There is no absolute complete. Complete *for what* is the only answerable question |
| 2 | **More detail carries a burden** | Every additional element is coordinated, checked, revised and maintained by someone |
| 3 | **Unnecessary information creates cost and ambiguity** | Two containers describing the same thing differently is worse than one describing it once |
| 4 | **Insufficient information creates decision risk** | The failure runs both ways, and this half is the one an over-correcting audience forgets |
| 5 | **The goal is proportionate, reliable, usable information** | Not minimal. **Proportionate** |

**Point 4 protects the slide from being heard as "do less".** It is not a
minimalism argument. It is a fitness-for-purpose argument, and the middle of the
range moves with the purpose.

**On "level of information need" — what may and may not be said**

The general concept — that how much detail and reliability is needed depends on
the purpose — **may be mentioned**, and this slide is built on it.

| Permitted | Prohibited |
|---|---|
| The **general concept**, in plain words | **Any formal definition presented as ISO's** |
| That it is decided per purpose, per container | Any geometric / alphanumeric / documentation breakdown |
| That Harrismith has **not established it** | Any level, grade, scale or numbered tier |

**No definition-level source is registered for this term.** Anything beyond the
plain-language concept would be invented.

**Harrismith connection — an unresolved position, stated exactly**

The Model / Information Responsibility Matrix §4 is unusually direct:

> **Level of information need — Not defined.** It *"has not been established for
> any container"*, is *"**not** assumed from discipline convention or inferred
> from observed model content"*, and is *"recorded as an information gap"* to be
> developed as PROPOSED GOVERNANCE alongside the Information Delivery Schedule.

| | |
|---|---|
| Category | **`GAP OR UNVERIFIED`** |
| What may be said | It is not established; it is recorded as a gap; it is an **open project decision** |
| What must not be said | Any model-detail requirement for the fire station. **None exists**, and inventing one would create a production requirement out of a teaching slide |

**Note the second half of that source statement**, because it is the sharper
half: level of information need is **not inferred from what happens to be in the
models**. Observed content is not a requirement. That is the same move as *folder
names do not prove governance*, applied to model detail.

**Required message**

> The target is not maximum information. It is sufficient, reliable information
> for the stated purpose.

*(**Teaching synthesis** — `M3-S6-11`.)*

**Transition out of Section B.** Slides 4–6 have established *why* information
management comes first. Section C asks **who** does it.

### Slide 7 — Information-management functions are not automatically job titles · 1.5 min

**Purpose of the slide**

Show that information-management activities must be **fulfilled**, and that
fulfilling them is not the same as creating a job title for each one. Open
Section C by separating five things an audience routinely collapses into one.

**Five things held apart**

| # | Layer | What it is |
|---|---|---|
| 1 | **Required information-management activity** | Something that has to happen for information to be relied on |
| 2 | **Project function** | The defined responsibility for making it happen |
| 3 | **Appointment or contractual responsibility** | Who is engaged, and on what terms |
| 4 | **Organisational job title** | What someone's employer calls them |
| 5 | **Individual participant** | The human performing it on the day |

**Layers 1–3 must be established for a project to work. Layer 4 is optional, and
layer 5 changes.** Most confusion in this area is layer 4 being mistaken for
layer 2.

**Official implementation guidance — UK context**

> **`OFFICIAL IMPLEMENTATION GUIDANCE — UK CONTEXT` (`X6`).** UK implementation
> guidance explains information management in terms of **functions**, rather than
> requiring every function to become a new job title. It records that the
> **appointing party** must ensure the information-management function is
> fulfilled, and that the **lead appointed party** must also ensure the relevant
> information-management function is fulfilled.

**This is the whole external basis for the slide, and it is guidance, not ISO
text.** Say the jurisdiction aloud and show it.

**The sentence that must not be said**

> ~~"ISO 19650 says no BIM Manager is required."~~

That conclusion is **broader than any authorised source here supports**. The
guidance describes functions; it does not tell us what the standard requires
about titles, and the standard has not been read — see
[`source-map.md`](source-map.md) §7.3, prohibition 21.

**What follows — five points**

| # | | |
|---|---|---|
| 1 | **A function describes what must be performed** | Not who performs it, and not what they are called |
| 2 | **The relevant party must ensure the function is fulfilled** | Guidance, UK — the obligation is to *ensure fulfilment*, not to *create a post* |
| 3 | **One person may perform more than one function** | Common on small projects, and unremarkable |
| 4 | **Combining functions does not merge their authorities** | The responsibilities stay distinct in meaning |
| 5 | **A title does not prove the function was assigned** | Nor does having the software licence, the folder access or the loudest opinion |

**Callback to Module 2 — four lines, then move on**

```text
Function
  ≠ job title
  ≠ organisation
  ≠ person
```

**Do not re-teach Module 2.** If the audience did not attend it, the four lines
still work as orientation.

**Harrismith connection — a project analogue**

Harrismith defines functions and **populates no holders at all**:

| Defined function | Named holder |
|---|---|
| BIM Manager · BIM Coordinator · CDE Administration · Lead Delivery Party (BEP §4.6) | **TBD** |
| Task-Team Lead (§5.7) · Author · Checker (§5.8) | **TBD** |

Two sourced statements do the work:

> **"Combining roles does not combine the functions."** A participant performing
> two functions must know **which function they are performing at each decision
> point** — approving a governance change as BIM Manager is a different act from
> applying it as CDE Administrator, *"even when performed by one person within a
> minute of each other."* *(BEP §5.11)*

> Author and Checker may be combined where independence cannot reasonably be
> provided — but *"self-checking is still a checking act with a defined
> requirement, not an omission of one"*, and **"independence is never claimed
> where it does not exist."** *(BEP §5.8)*

And one more, which closes the title question: **"Platform access is not
delegation."** *(BEP §5.11)*

**Category: `LOCAL ANALOGUE OR INTERPRETATION`.** Harrismith organises itself
around functions rather than titles. That **illustrates** the principle; it is
**not** evidence that the Harrismith model is an ISO implementation.

**Required message**

> The important question is not whether a title exists; it is whether the
> information-management function is assigned, understood and performed.

*(**Teaching synthesis** — `M3-S7-12`.)*

**No holder, appointment or organisation is named on this slide.** None exists in
the sources, and inventing one to make an example concrete would create an
appointment out of a teaching aid.

### Slide 8 — The parties, the teams and the vocabulary gap · 1.5 min

**Purpose of the slide**

Introduce ISO-associated party and team vocabulary **while preventing false
one-to-one substitution into Harrismith**. This is the module's highest-risk
slide, and the risk is not what the presenter says — it is what the layout
implies.

**The governing rule, stated on the slide**

```text
Possible conceptual relationship
  ≠ verified terminological identity
```

**The two vocabularies**

| **ISO-associated / UK-guidance vocabulary** | **Harrismith project vocabulary** |
|---|---|
| **appointing party** — `GUIDANCE`, UK (`X6`) | `Owner / Appointing Party`; `Appointing Party` — **19 occurrences** |
| **lead appointed party** — `GUIDANCE`, UK (`X6`) | `Lead Delivery Party` — **20 occurrences** |
| **appointed party** — named term; **no registered source defines it** | **nothing** — **0 occurrences** |
| **delivery team** — named term; **no registered source defines it** | **1 incidental use in prose**; not a defined term |
| **task team** — named term; **no registered source defines it** | `task team` — **164 occurrences**, a defined structure (BEP §4.3) |
| — | `BIM Manager` · `BIM Coordinator` · `Task-Team Lead` · `Author` · `Checker` · `CDE Administration` |

**Three findings, and each matters more than the table.**

**One — only two ISO-associated terms are actually registered.** `appointing
party` and `lead appointed party` come from `X6` as **UK implementation
guidance**. `appointed party`, `delivery team` and `task team` are in general
circulation, but **no registered source defines any of them** for this
programme. They are named, not defined — `M3-S8-03`, `M3-S8-04`.

**Two — `appointed party` has no Harrismith counterpart at all.** Zero
occurrences across `bep/`, `supporting/` and `docs/`, independently verified.
**The absence is shown, not filled.**

**Three — `task team` is the one word that appears in both columns, and even
that is not an established identity.** Shared vocabulary is not equivalence. The
ISO-associated definition has not been read; Harrismith's is defined in BEP §4.3
and carries this project's own structure — including that Mechanical, Electrical
and Plumbing are **three task teams within one MEP Consultant party**, not three
companies.

**Required warning — visible on the slide**

> ### `Terminology mapping not established`

**What must not be asserted**

| Prohibited assertion | Status |
|---|---|
| `Lead Delivery Party` = *lead appointed party* | **Not established** |
| consultant = *appointed party* | **Not established** |
| contractor = *appointed party* | **Not established** |
| `Task-Team Lead` = *lead appointed party* | **Not established** |
| any other one-to-one identity | **Not established** |

**Required message**

> Similar words do not establish equivalent appointments; project terminology
> must be mapped deliberately.

*(**Teaching synthesis** — `M3-S8-12`.)*

**Why the vocabulary gap is a finding rather than an embarrassment.** Harrismith
chose terms that describe its own arrangement and declined to adopt terminology
whose definitions it does not hold. That is the same discipline as declining to
invent information requirements. A project that adopts the vocabulary without the
appointments has changed its words and nothing else.

**Layout is content on this slide.** The mandatory design requirements in
[`visual-demonstration-plan.md`](visual-demonstration-plan.md) `V6` — offset
rows, a labelled gutter, no arrows, no colour matching, `appointed party` facing
empty space — are **not styling preferences**. An aligned two-column table
asserts the mapping the slide exists to refuse.

### Slide 9 — Information containers make responsibility manageable · 1.5 min

**Purpose of the slide**

Introduce the information container as the **unit responsibility attaches to** —
at principle level. Close Section C by showing why managing information in
identifiable pieces is what makes responsibility answerable at all.

**A working description — explicitly not a definition**

> An **information container** is a managed unit of information for which
> responsibility, status, revision and permitted use can be controlled.

*(**Supported interpretation.** **No formal ISO definition is quoted, and none is
available to this programme.** The term appears in both vocabularies; shared
vocabulary is not established equivalence — `M3-S9-02`.)*

**Examples — illustrative, not exhaustive and not normative**

| | | |
|---|---|---|
| a model | a drawing | a schedule |
| a specification | a report | a data file |

***Teaching examples.*** Say the word *illustrative* aloud. A six-item list on a
slide reads as a closed set unless it is labelled otherwise.

**Six distinctions**

| # | | Support |
|---|---|---|
| 1 | **A container is not necessarily a single file** in every implementation | Interpretation — implementations differ, and none has been verified |
| 2 | **A model is one possible container, not the whole information environment** | Interpretation, consistent with BEP §10.4 — *"a delivery is not synonymous with a file"* |
| 3 | **Federation does not erase originating responsibility** | BEP §6.6, §8.5 |
| 4 | **A folder location alone does not prove status** | BEP §7.2, §6.8 |
| 5 | **The originating task team retains responsibility** | BEP §7.2 |
| 6 | **Controlled sharing makes information available for a purpose without transferring authorship or technical ownership** | BEP §7.9, §6.5 |

**The three sourced statements that carry the slide**

> **Origination follows this chain:** `party → task team → discipline →
> information container`. **Originator responsibility remains with the producing
> task team**, through sharing, consumption, coordination and publication. *"No
> downstream act relieves it."* *(BEP §7.2)*

> **"Authorship is not inferred from folder location. Where a container sits
> tells you where it sits. The originator is recorded, not deduced."**
> *(BEP §7.2)*

> **"Federation does not merge authorship or responsibility."** Aggregating
> models into a federated view *"creates a coordination artefact, not a
> jointly-authored model. Each contributed container keeps its originator, its
> state and its technical responsibility."* *(BEP §6.6)* — and §8.5 adds that
> federation is *"a lens for multidisciplinary understanding and review"*, and
> that *"nobody becomes responsible for another team's content by appearing
> alongside it."*

**On consumption**, BEP §7.9: *"Consumption does not transfer originator
technical responsibility."* The receiving team remains responsible for **how it
uses** the information — whether it was appropriate, current and within the
stated purpose. *"Both responsibilities exist at once; neither cancels the
other."*

**Harrismith connection — a project analogue**

The Model / Information Responsibility Matrix allocates container classes to
originating parties and task teams:

| Container class | Originating party | Task team |
|---|---|---|
| `ARC-01` | Architectural Consultant | Architectural |
| `STR-01` | Structural Consultant | Structural |
| `MEC-01` · `ELE-01` · `PLM-01` | **MEP Consultant** — one party, three task teams | Mechanical · Electrical · Plumbing |
| `FIR-01` | Fire Consultant | Fire |

**Category: `LOCAL ANALOGUE OR INTERPRETATION`.** It illustrates containers with
recorded originators. It is **not** a verified ISO information-container system,
and no such verification exists.

**And the honesty marker.** Every allocation is classified **PROPOSED
GOVERNANCE**; no organisation is appointed and no holder is established. The
matrix also records that it is *"intended governance, not live inventory"* — it
describes what is intended to be produced, **not what exists in the CDE**.

**Module-boundary control — read before developing any visual**

| Permitted here | Deferred |
|---|---|
| That controlled states **exist** — one sentence | **Module 4** — the state set, transitions, transition authority, evidence |
| That containers have originators and purposes | **Module 5** — container breakdown, allocation row by row |
| — | **Modules 4–5** — metadata schemas, naming syntax, revision coding, suitability coding |

**A brief callback to the existence of controlled states is permitted. No
transition mechanics.** If a sentence begins to explain *how* a container moves,
it belongs to Module 4.

**Required message**

> By managing information in identifiable containers, the project can assign
> responsibility, control use and retain traceability without treating all
> project information as one undifferentiated model.

*(**Teaching synthesis**, consistent with BEP §7.2, §6.6 and §8.5 —
`M3-S9-14`.)*

**Transition out of Section C.** Slides 7–9 have established **who** manages
information and **what** it attaches to. Section D asks how use and delivery are
controlled.

### Slide 10 — The CDE controls permitted use and exchange · 1.5 min

**Purpose of the slide**

Explain **why** managed information needs an agreed environment in which status,
permitted use and exchange conditions are controlled. Principle level only — the
CDE workflow lesson is Module 4.

**What a CDE supports**

| # | | |
|---|---|---|
| 1 | **Controlled availability** | Who can see what, and from when |
| 2 | **Traceability** | What happened to a container, and who did it |
| 3 | **Version awareness** | Which one you are looking at |
| 4 | **Defined purposes of use** | What it may be relied on *for* |
| 5 | **Managed exchange** | Sending as a deliberate act |
| 6 | **Separation of development from reliance** | Information being worked on is kept apart from information others may depend on |

*(**Supported interpretation**, built from `H1` §6.1's CDE principles. **Not an
ISO definition** — none is available to this programme — `M3-S10-02`.)*

**Six distinctions**

| # | | Support |
|---|---|---|
| 1 | **Platform ≠ CDE governance** | `H1` §6.1 — *"an information-management process supported by technology… it is not a folder tree"* |
| 2 | **Folder location ≠ information status** | `H1` §7.2, §6.8 |
| 3 | **Access permission ≠ authority** | `H1` §6.9 — permissions *"do not create professional or governance authority"* |
| 4 | **Technical movement ≠ authorised state transition** | `H1` §12.1 — decision precedes configuration |
| 5 | **Information can exist in a platform without being authorised for the next purpose** | `H1` §6.1 — *presence is not trust*; §7.5 — visibility of WIP is not permission to rely on it |
| 6 | **Status and permitted use require agreed governance** | `H1` §6.1, §6.8 |

**Callback to Modules 1 and 2 — three lines, then move**

```text
Module 1 — the BEP records the agreed method
Module 2 — assigned functions hold the relevant authority
Module 3 — the CDE implements those arrangements
```

**Harrismith connection — the four states, as a project analogue**

| State | What it is for |
|---|---|
| **WIP** | Authoring, iteration, internal checking. *"WIP versions are not project exchanges"* |
| **Shared** | Available beyond the originating task team, for an identified purpose |
| **Published / Authorised** | Authorised for an identified formal or project-facing purpose |
| **Record / Retained** | A **conceptual state and a retention requirement — not necessarily a folder** |

**Category: `LOCAL ANALOGUE OR INTERPRETATION`.** These resemble ISO-associated
practice. **Conformity has not been demonstrated**, and no ISO state model has
been seen.

**Two Harrismith cautions that must survive onto the slide**

**One — Record / Retained is not a folder.** `H2` is explicit: **no mandatory CDE
root named `04 Archive` is required or approved**, none is created, and the
project's retention approach is **TBD**. Drawing it as a folder invents a
requirement.

**Two — `Shared → Published` does not currently work.** See below.

**The blocked transition — mandatory, and it is governance evidence**

| | |
|---|---|
| `WIP → Shared` (**T1**) | Authorising function **established** — the **Task-Team Lead** (BEP §9.4) |
| `Shared → Published / Authorised` (**T4**) | **BLOCKED.** Publication / exchange authority is **UNRESOLVED — TBD** (BEP §9.7; IM matrix D4) |
| `TRN-E03` | **PROPOSED — BLOCKED PENDING GOVERNANCE DECISIONS** |

`H2` states the consequence directly:

> Transition **T4** therefore has **no available authorising function**, and
> information remains **Shared**.

And says why the block stays visible:

> *"The block is represented deliberately and is a feature of the model, not a gap
> in it: **governance can intentionally stop a workflow**. A route that cannot
> legitimately proceed should visibly halt, rather than complete itself by
> borrowing an authority nobody granted."*

**That quotation is the best thing on this slide.** It converts an apparent
deficiency into the clearest demonstration of the principle the slide is
teaching. **Do not remove the block to make the diagram tidy** — a complete route
through Published would misrepresent the project and teach the opposite lesson.

**Module-boundary control**

| Permitted here | Deferred to **Module 4** |
|---|---|
| That the states exist, and what each is *for* | Transition mechanics — how a move is performed |
| That progression happens by decision | Transition authority, evidence requirements, conditions |
| That one route is blocked, and why | Naming and suitability codes, metadata, folder workflows, the complete state diagram |

**Delivery test: if the slide explains exactly how a state transition is
performed, stop.**

**Required message**

> A CDE does not merely store information; it controls the conditions under which
> information may be used and exchanged.

*(**Teaching synthesis**, consistent with `H1` §6.1 — `M3-S10-17`.)*

### Slide 11 — Information delivery must be planned · 1.5 min

**Purpose of the slide**

Explain that delivery should be planned against a known purpose, recipient and
event — rather than information being produced and sent whenever it happens to be
ready. Conceptual only; the schedule and matrices are Module 5.

**The planned-delivery chain**

```text
Purpose
  → required information
  → responsible originator
  → planned event
  → checked and authorised delivery
  → intended recipient and use
```

*(**Teaching structure**, consistent with `H1` §10.1's delivery grid and §7.3's
requirement fields. **No source presents these six steps in this form** —
`M3-S11-02`.)*

**What planned delivery answers**

What information · why · who originates it · who checks or authorises it · who
receives it · when or at what event · what use it supports · what dependencies or
gates must be satisfied.

*(Drawn from `H1` §10.1 — *"a need · a recipient · a purpose · timing / event ·
required content · format · readiness · authorisation"* — and §7.3. **This is a
set of questions, not a schedule schema.**)*

**The sourced line that carries the slide**

> **Presence in Published does not establish a delivery.** Information sitting in
> a published location has not been delivered to anyone; **delivery is an act with
> a recipient and a purpose, not a location.** *(BEP §10.1)*

**Nine distinctions — the slide's actual content**

| | ≠ | |
|---|---|---|
| Planned delivery | ≠ | completed delivery |
| A schedule entry | ≠ | evidence that the information exists |
| A target date | ≠ | acceptance |
| An event identifier | ≠ | an automated trigger |
| A planned recipient | ≠ | an established acceptance authority |
| Controlled sharing | ≠ | publication |
| Publication | ≠ | delivery |
| Delivery | ≠ | receipt |
| Receipt | ≠ | acceptance |

**The last four are sourced.** `H2` and BEP §10.11 keep **Published, Delivered,
Received and Accepted** as four distinct states:

> *"Delivery does not prove acceptance. Receipt does not prove suitability.
> Acceptance applies only to the identified purpose, and does not transfer
> technical responsibility from the originator."*

**Do not re-run Module 2's authority chain.** Name the four states, show they are
distinct, move on.

**Harrismith connection — a planning instrument, not a delivery record**

| | |
|---|---|
| What it is | A governance **planning** instrument. Its entries express **planned expectations** |
| Timing | *"Real delivery milestones and dates — **None established.** All timing event-triggered or TBD"* |
| `TRN-E03` | **BLOCKED** — publication-dependent delivery cannot proceed while publication authority is unresolved |
| Recipient | **Not established.** Acceptance authority **UNRESOLVED — TBD** |
| Category | **`GAP OR UNVERIFIED`** |

And the discipline behind it, which is the teaching point:

> *"An entry that cannot proceed is recorded as blocked. **Assigning a plausible
> authority to make the row look finished would manufacture governance that does
> not exist.**"*

**No actual delivery may be inferred from the schedule, and no programme date may
be invented.** None exists.

**Module-boundary control**

| Permitted here | Deferred to **Module 5** |
|---|---|
| That delivery is planned against purpose, recipient and event | The schedule's field structure and row construction |
| That planned is not actual | Purpose and suitability mechanics |
| That some entries are blocked or TBD | The responsibility matrices, read row by row |

**Delivery test: if the slide explains how to populate a delivery-schedule row,
stop.**

**Required message**

> Planning defines what should be delivered and why; evidence is still required
> to prove that delivery occurred.

*(**Teaching synthesis**, consistent with `H1` §10.1 and `H2` — `M3-S11-14`.)*

### Slide 12 — A principle is not a platform configuration · 1.0 min

**Purpose of the slide**

Show **the translation path** from principle to evidence. Slide 2 established that
software is not the standard; Slide 12 does not re-argue that — it shows what has
to happen in between.

**The translation chain**

```text
Information-management principle
  → project-specific requirement
  → agreed governance arrangement
  → assigned function and authority
  → process rule
  → platform configuration
  → implementation evidence
```

*(**Teaching synthesis.** **Not an ISO-prescribed sequence** — no source presents
one, and none has been read — `M3-S12-01`.)*

**What each step means**

| Step | | Support |
|---|---|---|
| **Principle** | What effective information management is trying to achieve | `X1` scope |
| **Requirement** | The project states what it needs, and why | Slide 5 |
| **Governance** | The BEP and supporting controls record the agreed method | `H1` §1.1 |
| **Authority** | Functions are assigned and authorities allocated | `H1` §4.6, §5 |
| **Process** | The rule people actually follow | `H1` §7, §10 |
| **Configuration** | Software is set up to implement those decisions | `H1` §12.1 — **decision precedes configuration** |
| **Evidence** | Someone demonstrates that implementation actually occurred | `H1` §12.9 |

**The line that carries the last step**

> **"A change is not complete because a document was edited or a setting was
> clicked."** *(BEP §12.9)*

`H1` §4.7 makes the same separation structurally — three things held apart:
**as-found configuration** (evidence), **intended governance** (a controlled
decision), and **implemented configuration** (the operational result of a
decision) — with the rule that *"implemented configuration is legitimate only when
it traces back to an approved decision."*

**Six things kept separate — the reason this is not a conformity model**

```text
standard or principle
implementation guidance          ← jurisdiction-bound
project governance
platform configuration
evidence of operation
conformity assessment            ← a separate act, by someone else
```

**Completing the chain does not prove conformity.** Conformity assessment is the
sixth item and a different activity. **Nothing in this module assesses anything.**

**Harrismith connection — an incomplete example, and honest about it**

| Step | Harrismith's position |
|---|---|
| Principle | **Stated as informing the approach** — BEP §11.2, §13.4 |
| Requirement | **No formal information requirements available** (Slide 5) |
| Governance | Governance documents and planned controls **exist** |
| Authority | **Several remain unresolved** — publication, acceptance, governance-change approval by class. IM matrix **A2 is TBD across every function** |
| Process | Defined in the BEP and supporting resources |
| Configuration | Observed, not verified — *"presence is not maturity"*, *"configuration is not correctness"* (BEP §2.4) |
| **Evidence** | **Incomplete or absent** |
| **Conformity assessment** | **None performed** |

**This is not a scorecard.** No score, no percentage, no maturity level, no
traffic light. It is a list of where a real project actually stands, and its
value is that the last two rows are empty.

**Visible warning, on the slide**

> ### `Translation model — not a conformity assessment`

**Delivery test: if the slide begins scoring compliance, stop.**

**Required message**

> The standard supplies principles; the project must turn them into authorised
> arrangements, configuration and evidence.

*(**Teaching synthesis** — `M3-S12-15`.)*

**One brief callback to Slide 2, and no more.** *"Slide 2 said the platform isn't
the standard. This is what sits between them."* Then run the chain. The slide has
one minute and the chain is seven steps.

### Slide 13 — How Harrismith may be mapped, and where the evidence stops · 2.0 min

**Purpose of the slide**

Show how a project may be examined against ISO-associated principles **without
turning the exercise into an unsupported conformity assessment**. This is the
module's principal honesty slide and its longest.

**Four categories, equal status**

#### 1 — `DIRECTLY EVIDENCED ALIGNMENT`

**One item. Only one.**

> Harrismith **states that ISO 19650 principles inform its approach** — BEP
> §11.2, §13.4.

That is **declared influence**, evidenced because the project declared it. In the
same breath the BEP adds: *"This is a statement about influence. **No formal
compliance with ISO 19650 is claimed**, and none has been established or
assessed."*

**It demonstrates influence. It does not demonstrate conformity, implementation
or successful operation.**

#### 2 — `LOCAL ANALOGUE OR INTERPRETATION`

Project arrangements that **resemble or illustrate** information-management
concepts:

| | |
|---|---|
| A BEP governance framework | Controlled information states |
| Role and responsibility definitions | Responsibility matrices |
| Planned information delivery | Issue and coordination controls |

**Every item stays labelled an analogue.** Resemblance is not alignment, and
sharing a word with the standard proves nothing about meeting it.

#### 3 — `GAP OR UNVERIFIED`

Nine, each supported by the source map — **no speculative deficiency is added**:

| # | | Where recorded |
|---|---|---|
| 1 | **No licensed clause-level assessment** | §8 item 1 |
| 2 | No complete information-requirement basis | Slide 5 · `M3-S5-09` |
| 3 | No verified terminology mapping | Slide 8 · §8 item 14 |
| 4 | No named holders or complete appointments | Slide 7 · `M3-S7-10` |
| 5 | **Unresolved publication authority** | Slide 10 · `M3-S10-11` |
| 6 | **Unresolved acceptance authority** | Slide 11 · `M3-S11-12` |
| 7 | Incomplete implementation evidence | Slide 12 · `M3-S12-13` |
| 8 | No verified asset-life-cycle information strategy | Slide 4 · `M3-S4-11` |
| 9 | **No confirmed South African implementation framework** | Register §6 |

#### 4 — `EXCLUDED — CONFORMITY CLAIM NOT SUPPORTED`

The available evidence **does not support** any of these:

| Not supported |
|---|
| Harrismith **conforms** to ISO 19650 |
| Harrismith **fails to conform** to ISO 19650 |
| Autodesk software demonstrates conformity |
| The UK BIM Framework is the applicable South African rule |
| Project terminology is equivalent to ISO-associated terminology |
| Documentation alone proves implementation |
| Completing a checklist constitutes assessment |

**Seven distinctions — the slide's actual teaching**

```text
influence          ≠ implementation
analogue           ≠ requirement satisfaction
documented process ≠ operating process
unresolved         ≠ failed
gap                ≠ non-conformity
mapping            ≠ assessment
```

And the seventh, which closes it:

> **Assessment requires an authorised basis, adequate evidence and a competent
> assessor.** Module 3 has none of the three, and **defines no
> conformity-assessment procedure**.

**The licensed-standard question, answered honestly**

| | |
|---|---|
| 1 | **The public material does not contain the complete requirements.** It describes scope |
| 2 | **A licensed copy would be needed** for clause-level verification |
| 3 | **Obtaining a licensed copy does not itself perform the assessment** |
| 4 | The project would still have to establish **applicability, responsibility and assessment method** |

Point 3 is the one that surprises people. Buying the document is the cheapest
part of the exercise.

**Harrismith status — the only permitted conclusion**

> ### `No conformity conclusion supported`

**Forbidden formulations**, each of which smuggles in an assessment nobody
performed:

`partially compliant` · `not compliant yet` · `mostly aligned` · `ISO-ready` ·
`maturity level` · `percentage aligned`

**Required message**

> Harrismith contains useful analogues and declared influence, but the available
> evidence does not support a conformity conclusion in either direction.

*(**Teaching synthesis**, consistent with `H1` §11.2 and §13.4 — `M3-S13-19`.)*

**Why this slide is worth two minutes.** It is the only place in the programme
where a conformity misunderstanding gets corrected, and an audience that has sat
through twelve slides of principles is primed to ask *"so are we compliant?"*.
Answering that well is the module's deliverable.

### Slide 14 — What Triviron must verify before claiming alignment · 1.0 min

**Purpose of the slide**

Convert Module 3's principles and Harrismith's evidence boundaries into a
**verification checklist for a future project**. It remains a **question
framework, not an answer set**.

**The evidence boundary, stated first**

**No Triviron project facts exist in the registered evidence.** Nothing is
asserted about jurisdiction, project type, asset type, client, procurement route,
contract form, information requirements, appointments, software, delivery stage,
dates, intended certification or existing ISO alignment. **The slide contains
questions only.**

**Five question groups**

#### 1 — Applicability and source basis

- Which published edition of ISO 19650 is applicable?
- Which parts are relevant to the project?
- **Does a licensed copy of the applicable standard need to be obtained, and by
  whom?**
- Who will control access to it?
- Is any national adoption, national annex or local implementation guidance
  applicable?
- Who is authorised to determine that applicability?

#### 2 — Information requirements and purposes

- What decisions must project information support?
- What information does the appointing or client function require?
- At which events is it required?
- Which recipients and purposes are defined?
- What level of information need is required, and how will it be agreed?

*(**No formal requirement hierarchy is defined here** — no definition-level source
is registered. Slide 5's prohibition stands.)*

#### 3 — Appointments, functions and terminology

- Which organisations and parties are appointed?
- Which information-management functions must be fulfilled?
- Who performs each function?
- How will project terminology be mapped to the applicable standard and to the
  contracts?
- **Are job titles being confused with project functions?**
- Which decisions require explicit authority?

#### 4 — CDE and delivery arrangements

- What CDE governance model will apply?
- Which information states and purposes are required?
- Who authorises each transition or exchange?
- How will information delivery be planned?
- Which **publication, receipt and acceptance authorities** must be assigned?
- How will platform permissions follow those decisions?

*(Conceptual only. **Modules 4 and 5 develop the detailed controls.**)*

#### 5 — Implementation evidence and assessment

- What evidence will demonstrate that the agreed process **operates**?
- Who will verify implementation?
- What deviations will be recorded?
- Who is **competent and authorised** to assess alignment or conformity?
- What scope, criteria and evidence will the assessment use?
- Who may approve or publish any alignment claim?

**The end state**

> ### `Evidence-based conclusion — not yet available`

**Closing message**

> ISO alignment is not inherited from a template or a software platform; it must
> be established for the specific project through applicable requirements,
> appointments, authorised processes and evidence.

*(**Teaching synthesis** — `M3-S14-08`.)*

**Three closing takeaways — the last thing said**

| # | |
|---|---|
| 1 | **ISO 19650 concerns information management, not software selection.** |
| 2 | **Principles must become project-specific requirements, authority and evidence.** |
| 3 | **Alignment or conformity must never be claimed beyond the available basis.** |

**Note on Group 3, question 5.** *Are job titles being confused with project
functions?* is deliberately phrased as a diagnostic rather than a task. It is the
one question on this slide that a team can answer immediately, and answering it
honestly usually reveals two more.

---

## 5. Module boundary — what Module 3 does not do

**The content baseline is complete at Slides 1–14. Four things it deliberately
does not contain:**

| Not here | Where it belongs |
|---|---|
| CDE state mechanics, transitions, evidence requirements, naming and suitability coding | **Module 4** |
| Responsibility matrices read row by row; delivery-schedule construction; container breakdown | **Module 5** |
| Coordination, review, approval and **assurance procedure** | **Module 6** |
| Any clause-level ISO requirement, definition or figure | **No module** — not available to this programme |

**And two things no module will supply**, because they are decisions rather than
knowledge: a **terminology mapping** between Harrismith and ISO-associated terms,
and a **conformity assessment**. Both require an authorised basis, adequate
evidence and a competent assessor.
