# Module 3 — Visual Demonstration Plan

**Status:** The controlling visual plan for Module 3. **Visual source now exists
(T3-F); no rendered image asset exists.** This plan remains **authoritative** —
the source set implements it rather than superseding it.

**All thirteen visual concepts are now specified in full**, and the **visual
source set exists** — see [`../assets/module-03/`](../assets/module-03/) (T3-F).

**Two identifier spaces, and they are not the same size:**

| Space | Count | Meaning |
|---|---|---|
| **`V1`–`V13`** | **13 visual concepts** | This plan's entries — the controlling specifications |
| **`M03-S01`–`M03-S14`** | **14 slide-source files** | One per slide, in [`../assets/module-03/source/`](../assets/module-03/source/) |

**The counts differ because `V1` serves two slides.** It is one concept in two
states — the framework panel on Slide 1, completed with the platform panel on
Slide 2 — and each state has **its own source file**. Every other concept maps to
exactly one slide. **`M03-S01`–`M03-S14` is fourteen files, not thirteen.**

Source identifiers `X1`–`X6`, `H1`–`H3` are defined in
[`external-source-register.md`](external-source-register.md). Classification
follows [`source-map.md`](source-map.md) §1.

---

## 1. The rule that governs every entry

**No ISO diagram, table or figure is reproduced, redrawn, adapted or
reconstructed. Not one.**

Two independent reasons, and either alone is sufficient:

| Reason | |
|---|---|
| **Copyright** | ISO standards are copyrighted. Redrawing a figure produces a derivative work, and calling it "our version" changes nothing |
| **We have not seen them** | The standards have not been read for this programme. A "reconstruction" of a figure nobody has looked at is an invention wearing a citation |

**Every visual in this module is an original teaching diagram** built from public
scope, official guidance or Harrismith evidence — and each is labelled with which.

**A second standing rule, carried from Modules 1 and 2:** a dense screenshot of a
controlled document is not a visual. Extracts are cropped to the rows that carry
the message.

**A third rule, specific to this module:** where a visual shows both ISO-associated
and Harrismith vocabulary, the two appear in **visibly separate columns or
panels**, never in one merged list. See [`source-map.md`](source-map.md) §6.

## 2. How to read this plan

| Field | Meaning |
|---|---|
| **Slide** | Where it is used |
| **Teaching purpose** | The one thing the audience should take from it |
| **Source basis** | The register entries behind it |
| **Classification** | `PUBLIC-SOURCE` · `GUIDANCE` · `HARRISMITH` · `INTERP` · `SYNTH` |
| **Jurisdiction** | International · United Kingdom · This project · — |
| **Simplify** | What must be compressed |
| **Omit** | What must not reach the slide |
| **Overclaim risk** | The risk of asserting more than the sources support |
| **Copyright risk** | The risk of reproducing protected content |
| **External imagery** | Whether an external image would add value |

**On external imagery.** The answer is **no** for every visual in this module, and
the reason is uniform: the only relevant external imagery is ISO's own, which is
protected and unseen. It is recorded per-entry anyway, because a later increment
should have to re-decide it deliberately rather than inherit a blanket.

---

## 3. Candidate visuals

### V1 — Framework versus software platform · **specified (T3-F)**

| Field | Value |
|---|---|
| **Slide** | **1 and 2** — one visual concept in **two states**, and **two separate source files** |
| **Teaching purpose** | Show that the framework governs **information and decisions**, while the platform holds **files and permissions** — and that one does not become the other |
| **Source basis** | `X1` (scope: specifying, exchanging, recording, organising); `H1` §6.1, §6.8, §6.9, §12.1 |
| **Classification** | **`PUBLIC-SOURCE`** for the framework panel's scope wording; **`HARRISMITH`** for every platform-panel statement; **`INTERP`** for the panel framing |
| **Jurisdiction** | International (framework panel) · This project (platform panel) |
| **Source files** | [`../assets/module-03/source/M03-S01-information-management-framework.md`](../assets/module-03/source/M03-S01-information-management-framework.md) · [`../assets/module-03/source/M03-S02-framework-versus-platform.md`](../assets/module-03/source/M03-S02-framework-versus-platform.md) |
| **Simplify** | **Four items per panel.** Framework: specify · produce · exchange · record. Platform: folders · permissions · versions · storage |
| **Omit** | Any vendor logo or product name; any platform screenshot; any equals sign; any bridge, merge or transformation arrow; any tick, score or maturity indicator |
| **Overclaim risk** | **HIGH.** A two-panel diagram under an ISO-titled slide reads as *the ISO model versus reality*. **Both panels are source-labelled on the slide itself** |
| **Copyright risk** | **LOW** — original construction, no ISO figure involved |
| **External imagery** | **No.** A platform screenshot would make the right panel look authoritative and the left panel theoretical — the exact inversion the slide exists to prevent |

**Two states, two source files — and neither depends on an unstated build step.**

| State | Slide | Source file | Contains |
|---|---|---|---|
| **State 1** | 1 | `M03-S01` | **The framework panel alone.** No platform panel exists yet |
| **State 2** | 2 | `M03-S02` | **Both panels**, separated, plus the one permitted connector |

**`M03-S01` is complete in itself.** If Slide 2 is never shown, Slide 1's visual
still stands — it is not half a diagram. `M03-S02` re-states the framework panel
in full rather than referring back to it.

**Six mandatory design requirements.**

1. **The panels never touch.** A visible gutter separates them, and no shape
   spans it.
2. **No equals sign, no bridge, no merge, no transformation arrow.** Nothing may
   suggest the platform *delivers* the framework.
3. **One connector is permitted, and only one**: a single dashed arrow from an
   **authorised decision** node toward the platform panel, labelled
   **`implements`** — per `H1` §12.1, *decision precedes configuration*. It never
   points the other way, and it originates from the decision, **not from the
   framework panel itself**.
4. **Both panels carry a visible source label** — framework: *"published scope
   (`X1`) — paraphrase"*; platform: *"this project's BEP (`H1`) — not ISO
   wording"*.
5. **No product name, logo or interface appears anywhere**, in either state.
6. **No maturity score, tick or completeness indicator.**

**Design note.** Draw the framework panel first and larger in State 1, then keep
it **the same size** in State 2. Shrinking it when the platform panel arrives
teaches that the platform is the substantial thing.

### V3 — Part 1 versus Part 2 · **specified (T3-F)**

| Field | Value |
|---|---|
| **Slide** | 3 |
| **Teaching purpose** | Show two published parts answering **two different questions**, with revision status visible but subordinate |
| **Source basis** | `X1`, `X2` — published scope and edition currency; `X3`, `X4` — draft status only |
| **Classification** | **`PUBLIC-SOURCE`** for both columns and both statuses; **`INTERP`** for the one-line summary beneath |
| **Jurisdiction** | International |
| **Source file** | [`../assets/module-03/source/M03-S03-part-1-versus-part-2.md`](../assets/module-03/source/M03-S03-part-1-versus-part-2.md) |
| **Simplify** | **Two equal columns. One question per part. Three or four public-scope points each. One subordinate footer** |
| **Omit** | **Clause numbers. ISO headings beyond the registered titles. Any Part 2 process-activity list. A third column for drafts. Any other part of the `ISO 19650` series. Any diagram resembling a protected ISO structure** |
| **Overclaim risk** | **HIGH.** A tidy two-column table looks like a summary of the standards' **contents**. It is a summary of their **published scope** |
| **Copyright risk** | **MEDIUM-HIGH — the module's highest**, and treated accordingly. It is the visual closest to reproducing document structure |
| **External imagery** | **No.** An ISO catalogue-page screenshot would imply the presenter is reproducing official content |

**Format decision: a table and a layout specification. Not Mermaid.** A diagram
between the two parts would assert a relationship — sequence, derivation or
hierarchy — that no registered source establishes. **They are two documents with
different scopes, not two stages of anything.**

**Seven mandatory design requirements — copyright controls first.**

1. **The visible label `Published scope — not a summary of requirements`
   appears on the slide.** Not in the notes.
2. **No clause number of any kind.** None has been read.
3. **No ISO heading, section name or structural term is copied** beyond the
   registered document titles and the part numbers themselves.
4. **No Part 2 process-activity list.** Inventing a numbered process is the worst
   available failure — specific, plausible, memorable and wrong.
5. **No third column for the drafts.** Revision status is a **single subordinate
   footer line**; a third column gives drafts equal visual weight, which is the
   status error the slide exists to prevent.
6. **No other part of the `ISO 19650` series is named.** Other parts exist and
   **are not registered** — name only what
   [`external-source-register.md`](external-source-register.md) holds.
7. **No structural diagram.** No nested boxes, no parent-child arrangement, no
   part-of-a-whole graphic. Two columns, side by side, equal weight.

**Design note — why this entry is the most constrained in the plan.** Everything
`V3` shows is metadata about two documents, and metadata about a document is one
short step from the document's own structure. The safeguard is that **only the
registered titles, the edition years and the public scope summaries may appear**.
If a line on this visual cannot be traced to `X1`, `X2`, `X3` or `X4`'s
*information available* field, it does not go on the slide.

### V2 — Asset-life-cycle ribbon · **specified (T3-B)**

| Field | Value |
|---|---|
| **Slide** | 4 |
| **Teaching purpose** | Show that information management does not stop at handover — Part 1's stated reach is the whole asset life cycle — **and that what continues is managed information, not one unchanged model** |
| **Source basis** | `X1` — life-cycle reach (`M3-S4-01`); `H1` §3.3 for the Harrismith scope marker |
| **Classification** | **`PUBLIC-SOURCE`** for the reach only; **`INTERP`** for every phase label; **`SYNTH`** for the continuity annotation |
| **Jurisdiction** | International (the reach) · This project (the scope marker) |
| **Simplify** | A plain horizontal ribbon, **six unnumbered phases**, each carrying one short decision question rather than a description |
| **Omit** | **Any RIBA, ISO, PAS or national stage numbering.** Any named work-stage system. Any single object drawn travelling the ribbon. Any date, duration or scale |
| **Overclaim risk** | **HIGH.** A ribbon with numbered stages reads as *the ISO stages*. **No stage vocabulary is available to this programme**, and inventing a numbered set is fabrication |
| **Copyright risk** | **MEDIUM** — stage-model diagrams are frequently protected by their publishers, and the widely circulated versions are mostly derivatives. **No ISO life-cycle diagram is reproduced, redrawn or adapted** |
| **External imagery** | **No** |

**Phase labels — neutral teaching labels, fixed here so they are not
re-invented per slide:**

| # | Label | Decision question carried |
|---|---|---|
| 1 | Strategic need or initiation | *Is this asset needed, and at what scale?* |
| 2 | Design and delivery | *Does this work, and do the disciplines agree?* |
| 3 | Construction or production | *Can this be built as described?* |
| 4 | Commissioning and handover | *Does what was built match what was intended?* |
| 5 | Operation and maintenance | *What is this, where is it, how is it serviced?* |
| 6 | Alteration, renewal or end of life | *What may change, and what must be preserved?* |

**Five mandatory design requirements.**

1. **The ribbon carries an on-slide label** — *"generic asset life cycle;
   illustrative teaching labels, not a standard stage model"*. **On the slide, not
   in the notes.**
2. **No numbering of any kind.** Not 1–6, not letters, not Roman numerals. A
   numbered band is read as a cited stage system.
3. **Information continuity is drawn as a repeating band beneath the ribbon —
   never as one object moving along it.** Multiple containers appearing,
   superseding and retiring; what persists is the **band**, not any element in it.
4. **An explicit struck-through annotation against the single-eternal-model
   reading.** The misconception is common enough to be worth naming on the visual
   rather than only in speech — `M3-S4-10`, prohibition 19.
5. **Harrismith's scope boundary is marked, not hidden.** A bracket over phases
   1–3 labelled *"Harrismith's current scope — asset management and handover are
   expressly outside it (BEP §3.3)"*. **Not shaded red, not marked incomplete.**
   It is a **deliberately drawn boundary**, and the visual must read that way.

**Design note.** The operational band should be visibly the longest. Audiences
discount it precisely because every diagram they have seen draws it the same
width as design.

### V3 — Part 1 versus Part 2

| Field | Value |
|---|---|
| **Slide** | 3 |
| **Teaching purpose** | Show two published parts answering two different questions, with the revision status visible but subordinate |
| **Source basis** | `X1`, `X2`; status from `X3`, `X4` |
| **Classification** | **`PUBLIC-SOURCE`** for both columns and both statuses; **`INTERP`** for the one-line summary beneath |
| **Jurisdiction** | International |
| **Simplify** | **Two columns, one question each, three or four scope points each.** A single footer line carrying the revision status |
| **Omit** | Clause numbers; section structures; any list of Part 2 process activities; **any other part of the series** — none is registered |
| **Overclaim risk** | **HIGH.** A tidy two-column table looks like a summary of the standards' contents. It is a summary of their **published scope**, and the slide must say so — a visible footnote reading *"published scope; not a summary of requirements"* |
| **Copyright risk** | **MEDIUM-HIGH** — the nearest thing to reproducing structure. Keep to scope in the presenter's paraphrase; **no headings lifted from either document** |
| **External imagery** | **No.** An ISO catalogue-page screenshot would imply the presenter is reproducing official content |

**Requirement.** The revision status appears as a **footer note, not a third
column.** A third column gives the drafts equal visual weight, which is exactly
the status error the slide exists to prevent.

### V4 — Information requirements flowing into production · **specified (T3-B)**

| Field | Value |
|---|---|
| **Slide** | 5 |
| **Teaching purpose** | Show that stating what is needed **precedes** producing it — and that reversing the order is what produces information nobody can rely on |
| **Source basis** | `X1` (scope: exchanging, recording, versioning and organising information); **`X5`/`X6`** (requirements established appointment by appointment); `H1` §7.1, §7.3, §10.1 |
| **Classification** | **`PUBLIC-SOURCE`** for the framing; **`GUIDANCE` — UK** for the appointment-by-appointment annotation; **`HARRISMITH`** for the requirement fields; **`INTERP`** for the six-step sequence itself (`M3-S5-08`) |
| **Jurisdiction** | International · **United Kingdom** · This project — **all three visibly distinguished** |
| **Simplify** | One left-to-right flow, **six nodes, no branches, no loops** |
| **Omit** | **Any named requirements document or acronym** — no client-, exchange-, asset- or project-level requirement abbreviation appears. **Any production node placed before the need or requirement node.** Any platform screenshot. Any named software |
| **Overclaim risk** | **HIGH.** A named-document flow chart is read as the standard's information-requirements structure. **The nodes are generic by requirement**, and the sequence is labelled teaching structure |
| **Copyright risk** | **MEDIUM** — the requirements hierarchy is among the most reproduced ISO figures in circulation. **Do not reconstruct it, and do not reuse a third party's version** — a derivative of protected content does not become safe by carrying someone else's name |
| **External imagery** | **No** |

**The sequence — fixed, and drawn in this order:**

```text
Decision or purpose
  → information need
  → defined requirement
  → planned production
  → checked delivery
  → use
```

**Five mandatory design requirements.**

1. **Production never appears before need or requirement.** Not spatially, not in
   build order, not by emphasis. If the eye reaches *planned production* first,
   the visual teaches the opposite of the slide.
2. **The sequence is labelled *teaching structure*** on the slide — it is built
   from BEP §7.1 and §10.1, and **is not Part 2's process**, which has not been
   read (`M3-S5-14`).
3. **The UK-guidance annotation is visually distinct and labelled
   `OFFICIAL IMPLEMENTATION GUIDANCE — UK CONTEXT`.** This is the module's first
   `GUIDANCE` visual and it sets the convention: a different weight or tint, a
   jurisdiction label, and no merging into the sourced nodes.
4. **The requirement node may carry the seven questions in short form** — what
   decision, who, what, when, how reliable, how checked, what form. **Attributed
   to the BEP, not to the standard**, and **not** presented as a template
   (`M3-S5-06`).
5. **The Harrismith gap is shown on the requirement node**, not omitted: a note
   reading *"on this project: no formal requirements available — not invented
   (BEP §7.3, §10.2)"*. **A flow drawn as fully populated implies requirements
   this project does not have.**

**Design note.** Resist an upstream requirements hierarchy above the flow. It is
the shape everyone expects, it is the protected figure, and **the definitions
needed to label it honestly are not available to this programme.**

### V5 — The right information, not more information · **specified (T3-B)**

| Field | Value |
|---|---|
| **Slide** | 6 |
| **Teaching purpose** | Show that quantity is not quality, that the useful amount is **purpose-dependent**, and that **too little fails as surely as too much** |
| **Source basis** | `X1` (scope); **`X5`** (improving specification, production, review and transfer); `H1` §6.1 (*sharing is purposeful*, *publication is purposeful*), §1.1, §7.3; **`H2` matrix §4** (level of information need — not defined) |
| **Classification** | **`PUBLIC-SOURCE`** framing; **`GUIDANCE` — UK** if `X5` is used; **`HARRISMITH` — `GAP OR UNVERIFIED`** for the level-of-information-need marker; **`INTERP`** for the proportionality factors; **`SYNTH`** for the comparison itself (`M3-S6-04`) |
| **Jurisdiction** | International · **United Kingdom** (optional) · This project — each labelled where used |
| **Simplify** | **Choose one form, not both.** Either the two-column comparison **or** the continuum. The continuum is preferred — see below |
| **Omit** | **Any compliance tick, green, red, score, percentage or progress indicator.** Any file-count or storage-volume figure. Any level, grade, scale or numbered tier. **Any model-detail example for the fire station** |
| **Overclaim risk** | **MEDIUM-HIGH.** Two failure directions: read as *less is better*, or read as a conformity checklist. The point is **fitness for a stated purpose** |
| **Copyright risk** | **LOW** — original construction, provided no level-of-information-need breakdown is drawn |
| **External imagery** | **No** |

**Preferred form: the continuum.**

```text
too little  ————————[ proportionate ]————————  too much
 decision risk        purpose-dependent         cost, ambiguity,
                                                unmaintainable detail
```

**Why the continuum over the two-column comparison.** Two columns make the
right-hand one correct and the left-hand one wrong, which teaches minimalism. The
continuum has **two failure ends**, which is the actual argument (`M3-S6-08`).
The two-column comparison may still be used as a **supporting build** on the
proportionate zone — but not as the primary form.

**Five mandatory design requirements.**

1. **The proportionate zone is drawn as a movable band, not a fixed point**, and
   labelled **purpose-dependent**. A fixed midpoint asserts a universal quantity,
   and no such quantity exists.
2. **Both ends are failures, and drawn with equal weight.** *Too little →
   decision risk* is the half an over-corrected audience forgets.
3. **No tick, no green, no traffic light, no score.** A compliance grammar here
   turns a proportionality argument into a conformity claim — prohibition 18.
4. **No level-of-information-need breakdown of any kind.** No geometric /
   alphanumeric / documentation split, no tiers, no grades. **No definition-level
   source is registered** (prohibition 17). The plain concept may be *stated*; it
   may not be *structured*.
5. **The Harrismith marker appears as a labelled gap on the proportionate zone** —
   *"level of information need: not defined on this project; not inferred from
   observed model content (matrix §4)"*. **No fire-station detail requirement is
   drawn, implied or exemplified** (prohibition and `M3-S6-15`).

**Design note.** If the two-column build is used, keep the columns the same
height. A fat *more* column beside a lean *right* column is a picture of
minimalism, whatever the words say.

### V13 — Function-to-assignment chain · **specified (T3-C)**

| Field | Value |
|---|---|
| **Slide** | 7 |
| **Teaching purpose** | Show that an information-management need becomes a **defined function**, which is **assigned to a party**, which a **participant performs** — and that a job title sits outside that chain |
| **Source basis** | **`X6`** (functions rather than new job titles; appointing party and lead appointed party must each ensure the relevant function is fulfilled); `H1` §4.6, §5.11 |
| **Classification** | **`GUIDANCE` — UK** for the functions framing and both ensure-fulfilment statements; **`HARRISMITH`** for the combination and delegation points; **`INTERP`** for the chain itself |
| **Jurisdiction** | **UNITED KINGDOM** (the guidance basis) · This project (the illustration) — both labelled |
| **Simplify** | **Four nodes in one line, and one detached label.** Nothing else |
| **Omit** | **Any organisational hierarchy, reporting line or org-chart shape.** Any person's name, any organisation, any appointment. Any assertion that a particular title is required — **or that none is** |
| **Overclaim risk** | **HIGH.** The chain will be read as the standard's assignment process. It is **UK guidance plus presenter structure**, and the standard has not been read |
| **Copyright risk** | **LOW** — original construction |
| **External imagery** | **No** |

**The chain — fixed:**

```text
Information-management need
  → defined function
  → assigned party
  → participant performs it
```

**Five mandatory design requirements.**

1. **`job title` appears as a detached, optional label**, offset from the chain
   and connected by a dashed line at most — never as a step in it. A title is an
   organisational label, not a link in the assignment.
2. **No hierarchy of any kind.** No boxes stacked vertically, no reporting lines,
   no seniority ordering. The BEP's role model is *"not an appointment chart and
   not an organisation chart"*, and the visual must not become one.
3. **No name, organisation or appointment appears** — every Harrismith holder is
   **TBD**, and a placeholder reads as a name.
4. **The guidance node is jurisdiction-labelled.** *"UK implementation guidance:
   the relevant party must **ensure the function is fulfilled**"* — with
   `OFFICIAL IMPLEMENTATION GUIDANCE — UK CONTEXT` visible.
5. **Function combination is shown without merging.** If the visual illustrates
   one participant carrying two functions, the two function badges stay **visibly
   separate** on the one participant — never fused into a single combined label.
   Prohibition 23.

**Design note.** Resist adding an arrow back from *participant* to *job title*.
It invites the inference that performing a function confers, or requires, a
title — which is the slide's whole target.

### V6 — The vocabulary gap · **specified (T3-C)**

**Scope refined in T3-C.** In T3-A this entry covered Slides 7 and 8 together.
Slide 7's chain is now `V13`; **`V6` is Slide 8 only.** Its T3-A mandatory
requirements were always a description of the vocabulary gap, and they are
retained below unchanged, with three added.

| Field | Value |
|---|---|
| **Slide** | 8 |
| **Teaching purpose** | Show two vocabularies side by side **without asserting any mapping between them** |
| **Source basis** | **`X6`** (*appointing party*, *lead appointed party* — the only two registered); `H1` §4.2, §4.3, §4.6; verified occurrence counts |
| **Classification** | **`GUIDANCE` — UK** for the two registered terms; **`UNRESOLVED`** for *appointed party*, *delivery team* and *task team* as ISO-associated terms — **named, not defined**; **`HARRISMITH`** for every right-hand term |
| **Jurisdiction** | **UNITED KINGDOM** (left) · **This project** (right) — the distinction is the visual's subject |
| **Simplify** | **Two columns, never merged**, separated by a **visible labelled gutter** |
| **Omit** | **Every connecting line, arrow or equals sign between the columns.** Any colour-coded pairing. Any tick, green, or equivalence symbol. Any person, organisation or job title |
| **Overclaim risk** | **THE HIGHEST IN THE MODULE.** A two-column layout invites the eye to pair rows — and pairing `Lead Delivery Party` with *lead appointed party* is exactly the substitution prohibition 24 refuses. **The layout can commit the error with no word spoken** |
| **Copyright risk** | **LOW** for the layout; **MEDIUM** for the terms — use them as terminology, **never with definitions attached** |
| **External imagery** | **No** |

**Mandatory design requirements — six, and none is optional.**

1. **Rows do not align across the gutter.** Deliberately offset them. Aligned rows
   read as a mapping table, and no mapping decision has been taken. **In
   particular, `lead appointed party` is never drawn directly opposite
   `Lead Delivery Party`.**
2. **The gutter is labelled** — *"Mapping not established"*.
3. **The absence is shown.** `appointed party` appears in the left column with
   **nothing** opposite it. Harrismith has no such term, and **the empty space is
   the teaching**.
4. **No arrows between unverified terms.** None. An arrow is an assertion.
5. **Neutral spacing, not colour-coded matching.** No colour pairs terms; no
   green, no ticks, no equivalence symbols; nothing that reads as a compliance
   visual.
6. **A visible terminology warning on the slide** — `Terminology mapping not
   established`. Not in the notes. On the slide.

**Two further requirements from the T3-C findings.**

7. **The left column distinguishes *registered* from *named*.** `appointing
   party` and `lead appointed party` carry the UK-guidance label; *appointed
   party*, *delivery team* and *task team* carry **named, not defined** — because
   no registered source defines them.
8. **Occurrence counts may appear; they are the evidence.** `0` against
   *lead appointed party* and *appointed party* does more work than any
   annotation, and the **`1`** against *delivery team* is worth showing precisely
   because it is not zero — one incidental prose use is not adoption of a term.

**Design note.** Any conceptual similarity belongs in the speaker notes, **not in
the visual**. The presenter may say *"these may well be related"*; the slide may
not draw it.

### V7 — Separately owned information containers · **specified (T3-C)**

| Field | Value |
|---|---|
| **Slide** | 9 |
| **Teaching purpose** | Show **several separate containers**, each visibly owned, sitting within one information-management frame — and show that gathering them together does not merge ownership |
| **Source basis** | `H1` §7.2 (origination chain; originator responsibility; authorship not inferred from folder), §6.6 and §8.5 (federation), §7.9 (consumption), §10.4 (a delivery is not a file); `H2` matrix §3.1 (container classes) |
| **Classification** | **`HARRISMITH` — analogue** for every sourced statement; **`INTERP`** for the working description and the examples; **`PUBLIC-SOURCE`** only for the *organising information* framing (`X1`) |
| **Jurisdiction** | This project (the illustration) · International (the framing only) |
| **Simplify** | **Six containers maximum**, arranged inside one plain frame. Each carries **four short labels**: originator · responsibility · revision · permitted use |
| **Omit** | **Any federated-model image that visually merges ownership.** Any platform screenshot, folder tree or product name. Any file extension. **Any state-transition arrow.** The full five-property list — Module 4 |
| **Overclaim risk** | **MEDIUM-HIGH.** *Information container* appears in **both** vocabularies, so a clean diagram reads as ISO's definition. **It is a working description drawn from our BEP**, and the slide must say so |
| **Copyright risk** | **LOW** — original, Harrismith-sourced |
| **External imagery** | **No** |

**Suggested container set — deliberately mixed, so *container* does not read as
*model*:**

```text
ARC container    STR container    MEP containers (MEC · ELE · PLM)
Schedule         Report           Specification
```

**Six mandatory design requirements.**

1. **Every container carries a visible originator.** A container without an owner
   label is the picture the slide exists to refute.
2. **Containers stay visually separate.** They sit **within** a shared frame; they
   do not overlap, nest, fuse or share a boundary. **The frame is a lens, not a
   container** — `H1` §8.5.
3. **No federated-model image.** No merged 3D view, no single composite object.
   If federation is shown at all, it is a **translucent outline over separate,
   still-labelled containers**, annotated *"coordination artefact — authorship and
   responsibility unchanged"*.
4. **No state-transition arrows.** Plain association lines only. A brief note that
   controlled states **exist** is permitted; **how a container moves is Module
   4**, and an arrow starts teaching it.
5. **Non-model containers are present and equally weighted.** At least three of
   the six are not models. A grid of six model boxes teaches *container = model*,
   which is prohibition 27.
6. **Examples are labelled illustrative** on the slide, and the description is
   labelled as a working description — **not a definition**. Prohibition 27 and
   `M3-S9-16`.

**Two required annotations.**

- **On the frame:** *"a folder location does not establish authorship or status —
  the originator is recorded, not deduced (BEP §7.2)"*.
- **On the set:** *"allocations are PROPOSED GOVERNANCE; intended governance, not
  live inventory"* — otherwise six neat owned containers read as a running
  system.

**Design note.** The `MEC`/`ELE`/`PLM` grouping is worth drawing accurately:
**three task teams inside one MEP Consultant party**. It is a real feature of this
project, it takes one bracket, and it quietly makes the party / task-team
distinction that Slide 8 argued.

### V8 — CDE state and purpose, with the block visible · **specified (T3-D)**

| Field | Value |
|---|---|
| **Slide** | 10 |
| **Teaching purpose** | Show that a CDE controls **what information may be used for**, that progression happens **by decision**, and that **one route on this project cannot proceed at all** |
| **Source basis** | `H1` §6.1, §6.3, §6.9, §7.2, §7.5, §12.1; **`H2` CDE strategy §1 and §11**; `H2` delivery schedule §5 |
| **Classification** | **`HARRISMITH` — analogue** for the states and principles; **`HARRISMITH` — `GAP OR UNVERIFIED`** for the block and for Record / Retained; **`INTERP`** for the capability list |
| **Jurisdiction** | This project |
| **Simplify** | **Four states, named exactly as Harrismith names them.** Two routes shown — one working, one blocked. Nothing else |
| **Omit** | The full transition set `T1`–`T8`; transition evidence requirements and conditions; **any folder representation**; any naming, suitability or metadata coding; any platform screenshot or product name; **any suggestion that this is the ISO state model** |
| **Overclaim risk** | **HIGH, on two fronts.** It will be read as the ISO state model — **it is not, and no ISO state model has been seen**. And a complete-looking diagram implies a working system that does not exist |
| **Copyright risk** | **MEDIUM** — state-model diagrams are among the most reproduced. **Original construction from Harrismith terms only**, no ISO figure involved |
| **External imagery** | **No** |

**The diagram — fixed:**

```text
WIP
  →  Shared                    solid — Task-Team Lead authorises (BEP §9.4)
  ⇢  Published / Authorised    DASHED / HALTED — publication authority UNRESOLVED
  →  Record / Retained         a conceptual state and a retention requirement
```

**Seven mandatory design requirements.**

1. **`WIP → Shared` is solid**, and only because the authorising function is
   **established** — the Task-Team Lead. If every route is drawn as broken, the
   model reads as non-functional rather than deliberately halted.
2. **`Shared → Published` is dashed or visibly halted.** Never solid, never
   dotted-but-continuous, never a faded arrow that reads as *in progress*.
3. **`Published / Authorised` carries the label `Publication authority
   unresolved`.** On the diagram, not in a footnote.
4. **`TRN-E03` is marked blocked** wherever the delivery event appears.
   **`T4` is never drawn as an operating transition.**
5. **`Record / Retained` is not drawn as a folder, and never as `04 Archive`.**
   **No such root is required or approved**, and the retention approach is
   **TBD** — drawing one invents a requirement (prohibition 21 case,
   `M3-S10-15`).
6. **No automatic-transition implication.** No gears, pipelines, conveyor
   metaphors or system arrows suggesting the platform moves information by
   itself. Progression is **by decision**.
7. **The diagram is labelled a Harrismith project analogue**, not an ISO
   diagram — on the slide.

**The required annotation.** Against the block, in the project's own words:

> *"Governance can intentionally stop a workflow. A route that cannot legitimately
> proceed should visibly halt, rather than complete itself by borrowing an
> authority nobody granted."* — `H2` §11

**Design note — the single most important instruction in this plan.** Every
instinct in visual design will push toward completing that arrow: a broken chain
looks like an unfinished drawing. **It is not unfinished. It is accurate.** A
solid route through Published claims a workflow this project cannot operate, and
it is the most misleading thing this module could put on a screen. If a producer
"fixes" it, the fix must be reverted.

**Boundary.** Two routes, not eight transitions. **If the visual begins showing
how a transition is executed — evidence, conditions, sign-off — it is Module 4's
and must be removed.**

### V9 — Planned information delivery · **specified (T3-D)**

| Field | Value |
|---|---|
| **Slide** | 11 |
| **Teaching purpose** | Show that exchanges are **planned events with stated purposes and recipients** — and that a plan is **not evidence that anything was delivered** |
| **Source basis** | `X2` (delivery-phase exchanges, scope level); `H1` §10.1, §10.11; **`H2` delivery schedule §5, §5.1, §5.3, §7** |
| **Classification** | **`PUBLIC-SOURCE`** for the framing only; **`HARRISMITH` — analogue** for the delivery concepts; **`HARRISMITH` — `GAP OR UNVERIFIED`** for the missing dates, the blocked event and the unestablished recipient; **`INTERP`** for the chain |
| **Jurisdiction** | International (framing) · This project (content) |
| **Simplify** | **Two or three planned events**, each carrying: purpose · planned information · responsible function · planned event · recipient or intended use · **evidence status** |
| **Omit** | **Every tick, completed marker and progress bar.** Any actual date. The schedule's field structure, row construction and condition lists. Any populated recipient or acceptance authority. Any suitability or purpose coding |
| **Overclaim risk** | **HIGH.** A timeline reads as *this happened*. **Nothing has been delivered on this project**, no real dates exist, and one event is blocked |
| **Copyright risk** | **LOW** — original construction |
| **External imagery** | **No** |

**Six mandatory design requirements.**

1. **The visual carries the label `Planned — not evidence of delivery`.** On the
   slide, prominently, not as a footnote.
2. **No checkmarks, no completed states, no progress bar, no percentage.** A
   progress grammar asserts executed delivery — prohibition 36.
3. **No actual dates.** Timing is shown as **event-triggered** or **TBD**,
   because *"real delivery milestones and dates — **none established**"*.
   Inventing one creates a project commitment from a teaching slide.
4. **The `evidence status` column exists and is empty** for every event. Its
   emptiness is the slide's argument; a visual without it is a plan pretending to
   be a record.
5. **The blocked dependency is shown honestly.** `TRN-E03` appears **blocked**,
   with the publication dependency visible — consistent with `V8`. **A timeline
   drawn as operable would contradict Slide 10.**
6. **Recipient and acceptance authority are shown unpopulated** — *not
   established*, *UNRESOLVED — TBD*. **No plausible recipient is invented**;
   *"assigning a plausible authority to make the row look finished would
   manufacture governance that does not exist."*

**Design note.** Resist a left-to-right time axis with even spacing — it implies a
programme. A dependency chain, or events pinned to conditions rather than to
dates, carries the same teaching without asserting a schedule that does not
exist.

**Boundary.** Purpose and suitability mechanics, field structures and row
construction are **Module 5**. This visual shows **that** exchanges are planned
and **that** one is blocked — never **how** a row is populated.

### V10 — The translation chain · **specified (T3-D)**

| Field | Value |
|---|---|
| **Slide** | 12 |
| **Teaching purpose** | Show **the path from principle to evidence** — and show that Harrismith's own path runs out before the end |
| **Source basis** | `H1` §1.1, §2.4, §4.7, §12.1, §12.9, §11.2, §13.4; **`H2` IM matrix §3.7 (`A1`–`A5`)** |
| **Classification** | **`SYNTH`** for the chain itself; **`HARRISMITH` — analogue** for each step's supporting statement; **`HARRISMITH` — `GAP OR UNVERIFIED`** for the unresolved authorities and the missing evidence; **`INTERP`** for the six separated concepts |
| **Jurisdiction** | This project. **No guidance source is used** |
| **Simplify** | **One horizontal chain, seven steps**, with four visually distinguished bands: **principle · project decision · technical implementation · evidence** |
| **Omit** | **Any green compliance tick. Any ISO certification badge. Any Autodesk or vendor logo. Any completed maturity ladder. Any platform screenshot.** Any score, percentage, level or traffic light. Any repetition of Slide 2's argument beyond one callback |
| **Overclaim risk** | **HIGH.** Seven steps in a row with a project's position marked against each is **one design decision away from a scorecard** — and a scorecard is a conformity claim whatever the caption says |
| **Copyright risk** | **LOW** — original construction, provided no certification mark appears |
| **External imagery** | **No.** A vendor logo at the configuration step would read as evidence, which is precisely the inversion the slide refutes |

**The chain — fixed:**

```text
Principle → requirement → governance → assigned authority
          → process → configuration → evidence
```

**Six mandatory design requirements.**

1. **The visible warning `Translation model — not a conformity assessment`
   appears on the slide.** Not in the notes.
2. **The four bands are visually distinct** — principle, project decision,
   technical implementation, evidence — so the audience can see *where a step
   lives*, not merely its order.
3. **The evidence stage is drawn open or incomplete for Harrismith.** Not
   crossed out, not red, not marked failed — **open**. Implementation evidence is
   incomplete or absent, and **no conformity assessment has been performed**.
4. **No scoring grammar of any kind.** No tick, no percentage, no level, no
   traffic light, no filled-progress styling. Prohibition 40.
5. **The chain runs one way, and the reverse is refused.** If a return arrow
   appears at all it is **struck through** — `H1` §12.1: **decision precedes
   configuration**, never the reverse.
6. **Conformity assessment is shown outside the chain**, as a separate act by a
   separate party — not as an eighth step. Making it the terminus implies the
   chain leads there, which is prohibition 38 in diagram form.

**The required annotation.** Against the evidence band, in the project's own
words:

> *"A change is not complete because a document was edited or a setting was
> clicked."* — BEP §12.9

**Design note.** The temptation is to mark Harrismith's position against all seven
steps, which produces a maturity ladder by accident. If positions are shown at
all, show **only the last two** — evidence and assessment — because those are the
two that matter and the two that are empty. Marking the first five invites the
eye to read completion.

**Boundary.** Assurance procedure — how verification is performed, by whom,
against what — is **Module 6**. This visual shows **that** evidence is required
and **that** it is missing here. Never how to produce it.

### V11 — Harrismith mapping, four equal bands · **specified (T3-E)**

| Field | Value |
|---|---|
| **Slide** | 13 — **the module's most important visual** |
| **Teaching purpose** | Show, honestly and in one view, what Harrismith **directly evidences**, what it **illustrates**, what is **unverified**, and what is **excluded** — and that the first band is almost empty |
| **Source basis** | `H1` §11.2, §13.4; `H2`; `H3`; [`source-map.md`](source-map.md) §5 and §9 |
| **Classification** | **`HARRISMITH` — `DIRECTLY EVIDENCED`** for band 1; **analogue** for band 2; **`GAP OR UNVERIFIED`** for band 3; **`EXCLUDED`** for band 4; **`INTERP`** for the categorisation itself |
| **Jurisdiction** | This project. **Band 3 includes the South African framework gap** |
| **Simplify** | **Four bands.** Band 1: one item. Band 2: up to six. Band 3: up to nine, or a representative five with a count. Band 4: the seven excluded conclusions, condensed |
| **Omit** | **Ticks. Crosses. Green. Amber. Red. Percentages. Scores. Maturity levels. Progress bars. Progression arrows. Any ordering from bad to good. Any dominant alignment band. Any visual completion** |
| **Overclaim risk** | **HIGHEST IN THE MODULE, jointly with `V6`.** Any grammar borrowed from a compliance dashboard converts the slide into the claim it exists to refute |
| **Copyright risk** | **LOW** — original construction |
| **External imagery** | **No** |

**The four bands — fixed labels, in this vocabulary:**

```text
DIRECTLY EVIDENCED ALIGNMENT
LOCAL ANALOGUE OR INTERPRETATION
GAP OR UNVERIFIED
EXCLUDED — CONFORMITY CLAIM NOT SUPPORTED
```

**Eight mandatory design requirements.**

1. **All four bands are the same size**, including band 4. A smaller exclusion
   band reads as a footnote; a larger band 2 reads as a result.
2. **Band 1 holds exactly one item** — that ISO 19650 principles **inform** the
   approach, per the BEP's own statement. **It is the only directly evidenced
   item there is, and its near-emptiness is the finding.** The empty space in
   band 1 is deliberate and is not to be filled, padded or balanced.
3. **No band is coloured green, amber or red.** Neutral throughout. Colour turns
   bands 1 and 4 into pass and fail.
4. **No ticks, no crosses, no score, no percentage, no maturity level.**
   Prohibitions 40–45.
5. **The bands are not ordered as a journey.** No left-to-right progression, no
   arrow, no numbering that implies a path. **This is a classification, not a
   maturity ladder** — and vertical stacking must not read as a ranking either.
6. **The licensed-copy requirement is visible on the slide**: *"clause-level
   verification would require a licensed copy — necessary, and not sufficient"*.
7. **The slide is labelled `Mapping — not assessment`.** Prohibition 47.
8. **The conclusion appears verbatim and alone**:
   **`No conformity conclusion supported`**. No qualifier, no adverb, no
   percentage, and none of the six forbidden formulations.

**Design note — the hardest instruction in this plan.** A near-empty band 1 beside
a full band 3 looks unbalanced, and every design instinct will try to correct it —
by promoting analogues upward, by shrinking band 3, or by adding a reassuring
summary line. **The imbalance is the content.** If band 1 ever holds more than one
item, someone has made a claim the evidence does not support.

**Boundary.** The slide maps; it does not assess. **No conformity-assessment
procedure is defined, implied or sketched** — see `M3-S13-22`.

### V12 — Triviron verification questions · **specified (T3-E)**

| Field | Value |
|---|---|
| **Slide** | 14 |
| **Teaching purpose** | Convert the module into **questions a future project must answer** — not conclusions it may inherit |
| **Source basis** | **None.** No Triviron project information exists in this repository. The questions derive from Module 3's principles and Harrismith's recorded gaps |
| **Classification** | **`SYNTH`** — questions only. **The only visual in the module with no evidence basis of any kind** |
| **Jurisdiction** | **None asserted.** Group 1 *asks* which national adoption or local guidance applies; it does not answer |
| **Simplify** | **Five labelled groups.** Two or three questions shown per group — the slide need not carry all thirty |
| **Omit** | **Every Triviron fact** — no jurisdiction, project type, asset type, client, procurement route, contract form, information requirement, appointment, software, delivery stage, date, intended certification or existing alignment. **No populated answer. No tick. No status colour. No organisation name. No software name. No certification badge. No completed final state** |
| **Overclaim risk** | **HIGH — and about Triviron, not about ISO.** The failure mode is inventing a project. A single plausible detail here becomes a project assumption downstream |
| **Copyright risk** | **LOW** |
| **External imagery** | **No** |

**The five groups — fixed:**

```text
1  Applicability and source basis
2  Information requirements and purposes
3  Appointments, functions and terminology
4  CDE and delivery arrangements
5  Implementation evidence and assessment
```

**Seven mandatory design requirements.**

1. **Every item ends in a question mark.** If a line can be read as an answer, it
   is rewritten or removed.
2. **The licensed-copy question appears visibly, verbatim**: *"Does a licensed
   copy of the applicable standard need to be obtained, and by whom?"* — and is
   **not answered**.
3. **No answer column, no response field, no example answer**, not even a greyed
   placeholder. A placeholder reads as a default.
4. **No dates, no organisations, no software, no certification marks.**
5. **The end state is shown and is open**:
   **`Evidence-based conclusion — not yet available`**. **Not a failure state** —
   it is the correct position for a project that has not started, and it must not
   be styled as a warning.
6. **Future-facing styling.** The visual reads as a path ahead, not as a status
   report. No progress indicator, no completion marker, no stage highlighting.
7. **The three closing takeaways are visually last**, after the questions. They
   are the module's final words and nothing follows them.

**Design note.** Thirty questions will not fit and should not be attempted. Show
the five group headings and two or three questions each — **including the
licensed-copy question, which is compulsory** — and let the notes carry the rest.
A wall of thirty questions in sixty seconds reads as a disclaimer rather than a
framework.

**Boundary.** Groups 4 and 5 stay conceptual: **Modules 4 and 5 develop the
detailed controls, and assurance procedure is Module 6.** The questions ask *who
decides* and *what evidence*, never *how to do it*.

---

## 4. Summary

| ID | Slide | Classification | Overclaim risk | Copyright risk |
|---|---|---|---|---|
| `V1` | 1, 2 | `PUBLIC-SOURCE` + `HARRISMITH` | **HIGH** | LOW |
| `V2` | 4 | `PUBLIC-SOURCE` + `INTERP` + `SYNTH` | **HIGH** | MEDIUM |
| `V3` | 3 | `PUBLIC-SOURCE` | **HIGH** | **MEDIUM-HIGH** |
| `V4` | 5 | `PUBLIC-SOURCE` + **`GUIDANCE` — UK** + `HARRISMITH` | **HIGH** | MEDIUM |
| `V5` | 6 | `PUBLIC-SOURCE` + **`GUIDANCE` — UK** + `HARRISMITH` | MEDIUM-HIGH | LOW |
| `V13` | 7 | **`GUIDANCE` — UK** + `HARRISMITH` + `INTERP` | **HIGH** | LOW |
| `V6` | 8 | **`GUIDANCE` — UK** + `UNRESOLVED` + `HARRISMITH` | **HIGHEST** | MEDIUM |
| `V7` | 9 | `HARRISMITH` + `INTERP` | MEDIUM-HIGH | LOW |
| `V8` | 10 | `HARRISMITH` + `INTERP` | **HIGH** | MEDIUM |
| `V9` | 11 | `PUBLIC-SOURCE` + `HARRISMITH` + `INTERP` | **HIGH** | LOW |
| `V10` | 12 | `SYNTH` + `HARRISMITH` + `INTERP` | **HIGH** | LOW |
| `V11` | 13 | `HARRISMITH` (all four sub-categories) + `INTERP` | **HIGHEST** | LOW |
| `V12` | 14 | `SYNTH` — **no evidence basis of any kind** | **HIGH (Triviron)** | LOW |

**All thirteen specified in full**, covering every slide. Each carries fixed
labels, a fixed form and five to eight mandatory design requirements, so the
constraints survive into asset production rather than being re-decided by whoever
draws them.

**The visual source set implements this plan and does not supersede it.** Where a
source file and this plan differ, **the plan is authoritative** and the source
file is the thing to correct.

**Two of them can overclaim without a word being spoken.** `V8` drawn with a
complete route through Published, or `V9` drawn as progress, each assert a
working system this project does not have. Their design requirements are
**content, not styling** — and a producer who "fixes" the broken arrow in `V8`
has introduced the module's most misleading claim.

**Scope refinement recorded in T3-C.** `V6` covered Slides 7 and 8 in T3-A. Slide
7 now has its own entry, **`V13`**, and `V6` is Slide 8 only. The two slides need
different shapes — a chain and a deliberately unmapped pair of columns — and
bundling them risked the chain acquiring the columns' pairing problem. **Existing
identifiers are unchanged**; `V13` is added rather than renumbering.

**Thirteen candidate visuals. Twelve carry HIGH or HIGHEST overclaim risk.**

That ratio is the module, not a defect in the plan. Module 3's subject is a
document the programme does not hold, and **a diagram is the fastest way to
appear to hold it**. Every entry above is therefore constrained by what it must
*omit* at least as much as by what it shows.

**Five carry MEDIUM or higher copyright risk** — `V2`, `V3`, `V4`, `V6` and `V8`.
`V2`, `V3` and `V4` sit near the most reproduced ISO figures in circulation;
`V6` and `V8` carry the risk through **terminology and state labels** rather than
through form. **None is reconstructed**, and third-party versions are not reused
either: a derivative of protected content does not become safe by having someone
else's name on it. On `V6` specifically, the terms appear **as terminology, never
with definitions attached**.

## 5. What this plan does not do

- It creates **no asset**. No source file, no rendered image.
- It authorises **no live Autodesk observation**. The safety boundary in root
  [`README.md`](../../README.md) §2.1 applies unmodified.
- It authorises **no external image acquisition**.
- It carries **no governance authority**.
