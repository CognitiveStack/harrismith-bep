# Module 7 — Deck Specification

**`MODULE 7 PRESENTATION ASSEMBLY PACKAGE — UNDER GOVERNED CORRECTION`** ·
**`T7-L — ACCEPTED after T7-L-R`** ·
**`T7-L-R2 — ACCEPTED`** · **`T7-L-R3 — ACCEPTED`** ·
**`T7-L-R4 — NOT YET ACCEPTED`** ·
**`T7-L-R5 — NOT YET ACCEPTED`** *(one bounded stale Slide 14 current-production
typography instruction remained)* ·
**`T7-L-R6 — PENDING CHATGPT GOVERNANCE REVIEW`** ·
**`P9 — SUPERSEDED FOR MODULE 7`** by the governed 14-logical / 18-physical
pagination rule — see **§13**

**`TEACHING PRODUCTION HANDOFF — NOT TRIVIRON GOVERNANCE`**

**Teaching material. Not governance. Not the PowerPoint.**

> **The questions and distinctions may transfer. Harrismith's populated answers
> do not.** **Visual grammar may transfer. Populated answers do not.**

**This is a compression layer.** It carries what a producer must build. Where it
is silent, the accepted `M07-Snn` source file governs; where they differ, **the
source file wins**.

> **`T7-L-R2` correction.** External fabrication (`T7-M`) produced fourteen
> slides but **stopped at QC**: minimum explicit type `7.8 pt`, with **146** text
> runs below `14 pt`. The producer correctly declined to delete mandatory wording
> or freely change accepted geometry, and invoked **`STOP AND REFER BACK`**.
>
> **The root cause is arithmetic, not taste.** Every accepted zone and band
> height in this deck was computed treating **line height as equal to nominal
> point size**. Real single line spacing is approximately **`1.2 ×`** the point
> size. Every accepted band is therefore understated by about **20 %** before
> padding — see §11 field 11 of Slide 14, whose accepted `3 × 18 pt = 54 pt`
> nominal fit is **wrong**: three `18 pt` lines occupy `64.8 pt`.
>
> **`T7-L-R2` has applied every compression the accepted architecture permits**
> and declared the typographic basis in §1. **Four slides remain unresolved at
> the accepted type floors** — see **§11**. **`T7-M-R1` is not authorised.**
>
> **`T7-L-R3` then attempted to resolve those four by geometry/layout
> reconciliation within the accepted visual concepts. It could not.** All four
> remain **`UNRESOLVED`**, with deficits of `75` to `230 pt` at the best
> arrangement tested — and Slide 13's mandatory `18 pt` text **alone** exceeds the
> canvas in any arrangement. **No coordinate has been changed**, because no
> arrangement of the accepted concepts achieves a pass. **The full arithmetic, the
> levers tested, and the options that would work — each requiring a governance
> decision this increment does not take — are in §12.**

---

## 1. Global details

| Field | Value |
|---|---|
| Format | **16:9 presentation** |
| Reference geometry | **`960 × 540 pt`** — origin top left; `x` right, `y` down |
| Title zone | **`y = 0–72` reserved.** No content beneath the title baseline |
| Side margins | **≥ 48 pt** — content span exactly **864 pt**, `x = 48–912` |
| Lowest permitted object edge | **`y ≤ 520`** |
| **Logical teaching units** | **Fourteen** |
| **Physical PowerPoint slides** | **Eighteen** — governed split pagination, `T7-L-R4`. **Only logical Slides 6, 11, 13 and 14 are paginated, each into exactly two frames.** See **§13** |
| Total time | **`20.0 minutes allocated — not measured`** — unchanged; each A/B pair shares its parent's allocation |
| Advancement | **Manual, presenter-controlled.** **No automatic slide-transition timing** |
| Object policy | **Native editable PowerPoint objects only** |
| External imagery | **NONE** |
| Screenshots | **NONE** |
| Icons | **NONE** |
| SVG / PNG / JPG imports | **NONE** |
| SmartArt | **PROHIBITED** |
| Mermaid | **PROHIBITED** |
| Automatic graph layout | **PROHIBITED** |
| Rendered assets | **`NONE`** — **this specification therefore defines no image-import workflow, and no import path may be invented** |

**Permitted objects:** text boxes · rectangles · native shapes · straight lines ·
connectors · native tables · borders · fills.

### 1.1 Declared typographic basis — `T7-L-R2`

**No feasibility claim in this specification is verifiable without a declared
measurement basis.** The absence of one is what allowed the `T7-M` fabrication to
reach `7.8 pt`. **This basis is now part of the specification.**

| Parameter | Declared value | Consequence |
|---|---|---|
| **Line height** | **`1.2 × nominal point size`** — PowerPoint "single" spacing | `14 pt` → **`16.8 pt`** per line · `18 pt` → **`21.6 pt`** per line |
| **Character advance** | **`0.5 × nominal point size`** — proportional sans, mixed case | `14 pt` → **`7.0 pt`** per character · `18 pt` → **`9.0 pt`** per character |
| **Text-box padding** | **`8 pt` total per axis** — `4 pt` each side | Usable width = object width **− 8 pt**; usable height = object height **− 8 pt** |
| **Line spacing floor** | **`1.0` (single). Never below** | Reduced leading is a **`STOP`**, not a fit strategy |
| **Condensation** | **PROHIBITED** | No font condensation, no reduced character spacing |

**Derived line capacities, at the floors:**

| Object width | Usable | `14 pt` chars/line | `18 pt` chars/line |
|---:|---:|---:|---:|
| **864 pt** full-width strip | 848 | **121** | **94** |
| **426 pt** Slide 13 quadrant | 418 | **59** | **46** |
| **416 pt** Slide 2 column | 408 | **58** | **45** |
| **280 pt** family card | 272 | **38** | **30** |
| **208 pt** Slide 4 grid cell | 200 | **28** | **22** |
| **200 pt** Slide 12 card | 192 | **27** | **21** |
| **168 pt** Slide 4 classification cell | 160 | **22** | **17** |
| **61 pt** Slide 11 act cell | 53 | **7** | **5** |

**This basis is a floor-setting convention, not a measurement.** A producer whose
actual font metrics are **wider or taller** than the declared basis **STOPS and
refers back** — that producer may not compensate by reducing type. A producer
whose metrics are narrower or shorter gains slack and may use it.

**The basis is what makes `≥ 14 pt` and `≥ 18 pt` testable.** Any statement in
this specification that a band "fits" means: **fits at the floors, on this
basis.**

## 2. Narrative arc

| Slides | Section | Carries |
|---|---|---|
| 1–3 | **A — the rule before the content** | Where Module 7 sits; what may and may not transfer; the analytical chain and its STOP |
| 4 | **B — the working record** | The 21-question decision backlog and its classification profile |
| 5–11 | **C — the seven domains** | One shared three-card grammar, instantiated seven times |
| 12–13 | **D — precision about limits** | What the evidence permits; the typed-absence vocabulary |
| 14 | **E — the handoff** | The future teaching workflow and the Module 8 bridge |

## 3. Slide timing table

| Slide | Exact accepted title | Allocation |
|---:|---|---:|
| 1 | Where we are: Harrismith → Triviron | 1.0 |
| 2 | Translate the method, not the answers | 1.3 |
| 3 | The translation chain | 1.5 |
| 4 | The decision backlog: 21 questions, zero Triviron answers | 1.3 |
| 5 | Domain 1: Coordination governance | 1.5 |
| 6 | Domain 2: Roles and authority | 1.5 |
| 7 | Domain 3: Inputs and federation | 1.5 |
| 8 | Domain 4: Checks and tolerances | 1.5 |
| 9 | Domain 5: Findings, Issues and statuses | 1.5 |
| 10 | Domain 6: Verification, evidence and completion | 1.5 |
| 11 | Domain 7: Publication and acceptance boundary | 1.5 |
| 12 | What the evidence lets you say | 1.5 |
| 13 | Unknowns are controlled work | 1.4 |
| 14 | From decision backlog to BEP workshop | 1.5 |
| | **Total** | **20.0 — allocated, not measured** |

**This table is the fourteen LOGICAL teaching units.** For the eighteen physical
slides, their allocations and their logical parents, see **§13.3** and **§13.5**.
**Both tables sum to exactly `20.0`.**

**Titles are exact. A producer may not shorten, retitle or "improve" one** —
including on a continuation frame, where the parent title is reproduced
**verbatim** and the continuation label sits outside the title wording (§13.4).

## 4. Design approach

**Plain, native, typographic.** No decoration competes with a governance
boundary.

| Rule | Requirement |
|---|---|
| **D1** | **Every boundary strip is a principal object** — full width, bordered, never a footnote, footer, caption or small print |
| **D2** | **Co-equal objects are pixel-identical** but for their text — same width, height, border, fill and type |
| **D3** | **Nothing is emphasised to look more advanced, more important or nearer to an answer** |
| **D4** | **No decorative three-dimensional effect, gradient, shadow ramp or software-interface replica** |
| **D5** | **If space is short, the answer is `STOP AND REFER BACK`.** Content compression is **exhausted** — `T7-L-R2` applied it. **Never cut boundary text, and never reduce type** |
| **D6** | **Geometry comes from the accepted source and is never improvised.** A producer who cannot achieve a stated span, equality or gap **STOPS and refers back** |
| **D7** | **Type floors are absolute.** `≥ 14 pt` every visible run; `≥ 18 pt` every principal label, classification, status and governance boundary. **No exception, no "temporary small print", no producer discretion to shrink** |

## 5. Status-label rules

**Two separate vocabularies. Never merged.**

| System | Values | Label on slide |
|---|---|---|
| **Translation classification** | `METHOD` · `EVIDENCE REQUIRED` · `DECISION REQUIRED` · `PROPOSAL` · `ESTABLISHED` | **`classification`** |
| **Status** | `NOT YET ESTABLISHED` · `NOT ESTABLISHED` · `UNRESOLVED` · `TBD` · `PROPOSED — NOT APPROVED` · `ESTABLISHED` | **`status`** |
| **Evidence availability** | `NONE IDENTIFIED` | evidence position — **not a status** |

| Rule | Requirement |
|---|---|
| **S1** | **Never one axis, strip, ramp, legend, colour scale or numbering across the two systems** |
| **S2** | **Wherever both appear, each is independently labelled in words** |
| **S3** | **`ESTABLISHED` is never styled as a destination, endpoint, goal, right-hand terminus or filled state** in either system |
| **S4** | A row that is validly `METHOD` **and** `NOT YET ESTABLISHED` must look consistent — those are two independent facts |
| **S5** | Status meaning is carried by a **word**, never by colour, chip, badge, dot or traffic light |
| **S6** | **`METHOD` appears only on `TDR-009`, `TDR-013` and `TDR-021`**, each with its qualifier — and never as a ribbon, star, tick, highlight, rank or score |
| **S7** | **`TBD` is never applied to a Triviron matter** anywhere in the deck |

**Register counts, quoted and never recalculated:** `METHOD` **3** ·
`EVIDENCE REQUIRED` **18** · `DECISION REQUIRED` **0** · `PROPOSAL` **0** ·
`ESTABLISHED` **0**; `3 + 18 = 21`.

## 6. Connector-semantics register

**Twelve connectors in the entire deck. No others may be added.**

| Slide | Count | Meaning | Absolute prohibition |
|---:|---:|---|---|
| 1 | **2** | `the next module in the teaching programme` | No arrow leaves segment 3 |
| 2 | **0** | — | **Zero between the two principal columns. Zero on the slide** |
| 3 | **6** | `the next step in the analytical sequence` | **None crosses the STOP band**; upper row never joins lower row |
| 4 | **0** | — | No arrow between classification cells |
| 5 | **0** | — | Family rule — **zero means zero** |
| 6 | **0** | — | **A single line joining two objects is an organisation chart** |
| 7 | **0** | — | No assembly, lens or funnel connector |
| 8 | **0** | — | No interface → check → rule → approval chain |
| 9 | **0** | — | **No finding → Issue arrow** |
| 10 | **0** | — | **No connector touches the fence** |
| 11 | **0** | — | **Zero between the four governance acts** |
| 12 | **0** | — | No spoke to the hub; no ring |
| 13 | **0** | — | The separating rule is a boundary, **not** a connector |
| 14 | **4** | `the next stage of the teaching workflow` | **None crosses the authority gate; none enters the final box** |

**Every connector's meaning must be expressible in one sentence in words.**
**Nothing flows along an analytical arrow: no Harrismith value becomes a
Triviron answer by traversing one.**

## 7. Deck-wide accessibility rules

| Rule | Requirement |
|---|---|
| **A1** | **Minimum visible type `14 pt` — absolute.** Any explicit visible text run below `14 pt` is an **automatic production-review failure** |
| **A2** | **Principal labels `≥ 18 pt`; every status, classification and governance-boundary word `≥ 18 pt` — absolute.** Any such run below `18 pt` is an **automatic production-review failure** |
| **A2.1** | **Both floors are tested against the declared typographic basis of §1.1.** A producer may set larger type, **never smaller**. There is no note, allowance or condition anywhere in this package permitting a producer to shrink below either floor |
| **A3** | Text contrast **≥ 4.5 : 1**; line, border and connector contrast **≥ 3 : 1** |
| **A4** | **No colour-only semantics** anywhere |
| **A5** | Logical reading order, defined per slide |
| **A6** | Warnings legible at projection size — never in a corner, a footer or small print |
| **A7** | **Alternative text is taken from the accepted source's screen-reader description**, not invented independently |
| **A8** | Anything a sighted reader takes from separation, enclosure, weight, offset or position is **also said in words** |

## 8. The fourteen slide specifications

Each entry compresses its accepted `M07-Snn` source. **Where this entry is
silent or differs, the source file governs.**

---

### Slide 1

| # | Field | Value |
|---:|---|---|
| 1 | **Number** | 1 |
| 2 | **Exact title** | Where we are: Harrismith → Triviron |
| 3 | **Allocated time** | **1.0 min** — allocated, not measured |
| 4 | **Narrative role** | Section A opener — from worked example to translation method |
| 5 | **Teaching purpose** | Locate Module 7 in the teaching roadmap and establish the transition from reference implementation to translation method |
| 6 | **Five-second takeaway** | *We have moved from a worked example to the questions a future BEP needs.* |
| 7 | **Visual / source** | `M7V-01` → [`M07-S01`](../../assets/module-07/M07-S01.md) |
| 8 | **Visual form** | `NATIVE TYPOGRAPHIC / CONCEPT` — three-segment roadmap band, framing line, full-width boundary strip |
| 9 | **Required visible copy** | See [`slide-copy.md`](slide-copy.md) Slide 1 |
| 10 | **Geometry** | Segments **each exactly 276 × 140 pt**, two gaps of **exactly 18 pt** — `x = 48–324`, `342–618`, `636–912`; `y = 150–290` (`3 × 276 + 2 × 18 = 864`). Framing line `x = 48–912`, `y = 310–370`. Boundary strip `x = 48–912`, `y = 396–480`, one visible border |
| 11 | **Connectors** | **2** — segment 1 → 2 and 2 → 3, each labelled `teaching-programme sequence`. **No arrow leaves segment 3** |
| 12 | **Boundary treatment** | Boundary strip carries **all three entries together**, ≥ 18 pt, principal object |
| 13 | **Source/authority labels** | All sources are teaching plan / architecture — **no controlled Harrismith value is asserted** |
| 14 | **Type controls** | Segment headings ≥ 18 pt; every boundary word ≥ 18 pt |
| 15 | **Mandatory omissions** | No date, year, quarter, calendar, timeline axis, milestone, percentage, progress bar, tick, funnel, person, organisation, logo, platform name, Triviron project reference or workshop imagery |
| 16 | **Principal STOPs** | `M7-S10`, `M7-S11`, `M7-S18` · `M7V-S08`, `M7V-S10`, `M7V-S31` |
| 17 | **Producer failure condition** | A reader answers *a Triviron workshop* or *a Triviron project* to "what happens after Module 7?", or believes anything is scheduled |

---

### Slide 2

| # | Field | Value |
|---:|---|---|
| 1 | **Number** | 2 |
| 2 | **Exact title** | Translate the method, not the answers |
| 3 | **Allocated time** | **1.3 min** — allocated, not measured |
| 4 | **Narrative role** | Section A — the governing boundary, before any domain content |
| 5 | **Teaching purpose** | Establish the governing boundary before any domain content is taught |
| 6 | **Five-second takeaway** | *Two lists. No bridge between them.* |
| 7 | **Visual / source** | `M7V-02` → [`M07-S02`](../../assets/module-07/M07-S02.md) |
| 8 | **Visual form** | Two co-equal columns with a **visible empty channel**, over a full-width boundary strip |
| 9 | **Required visible copy** | See [`slide-copy.md`](slide-copy.md) Slide 2 |
| 10 | **Geometry** | Columns **each exactly 416 × 340 pt** — `x = 48–464` and `496–912`, `y = 96–436`; channel `x = 464–496` **exactly 32 pt, empty** (`2 × 416 + 32 = 864`). Boundary strip `x = 48–912`, `y = 452–516` |
| 11 | **Connectors** | **`connector count = 0`.** Zero between the columns; zero on the slide. **No arrow, bridge, line, bracket, shared border, row alignment implying pairing, or numbering implying correspondence** |
| 12 | **Boundary treatment** | Boundary strip carries **all four entries together**, ≥ 18 pt |
| 13 | **Source/authority labels** | Takeaway line labelled **`TEACHING SYNTHESIS`** in words |
| 14 | **Type controls** | Identical heading weight and body type in both columns; boundary words ≥ 18 pt |
| 15 | **Mandatory omissions** | No arrow, bridge, line in the channel, "vs" symbol, scales, balance imagery, tick, cross, per-item pairing, "recommended" styling, colour ramp, person or organisation |
| 16 | **Principal STOPs** | `M7-S01`, `M7-S02`, `M7-S03`, `M7-S05`, `M7-S06`, `M7-S07`, `M7-S09`, `M7-S15`, `M7-S16` · `M7V-S13`, `M7V-S14`, `M7V-S20` |
| 17 | **Producer failure condition** | A reader calls the right column *the defaults* or *the starting point*, or can point at anything joining the two sides |

---

### Slide 3

| # | Field | Value |
|---:|---|---|
| 1 | **Number** | 3 |
| 2 | **Exact title** | The translation chain |
| 3 | **Allocated time** | **1.5 min** — allocated, not measured |
| 4 | **Narrative role** | Section A close — the analytical sequence and the STOP rule |
| 5 | **Teaching purpose** | Teach the accepted analytical sequence and the STOP rule |
| 6 | **Five-second takeaway** | *The chain stops in the middle, and that is the current state.* |
| 7 | **Visual / source** | `M7V-03` → [`M07-S03`](../../assets/module-07/M07-S03.md) |
| 8 | **Visual form** | Four steps · **full-width STOP band** · four steps · separate current-position panel. **Complexity HIGH** |
| 9 | **Required visible copy** | See [`slide-copy.md`](slide-copy.md) Slide 3 |
| 10 | **Geometry** | Both rows **four boxes each exactly 201 × 80 pt, three gaps of exactly 20 pt** — `x = 48–249`, `269–470`, `490–691`, `711–912` (`4 × 201 + 3 × 20 = 864`); upper `y = 96–176`, lower `y = 306–386`. **STOP band `x = 48–912`, `y = 196–286`, exactly 90 pt, border ≥ 3 pt — the heaviest object on the slide.** Panel `x = 48–912`, `y = 406–500`. Vertical: `80 + 20 + 90 + 20 + 80 = 290 = 386 − 96` |
| 11 | **Connectors** | **6** — three within the upper row, three within the lower row. **No connector crosses, enters, leaves or passes behind the STOP band. The upper row's last step does not connect to the lower row's first. No loop, no closed cycle. No connector touches the panel** |
| 12 | **Boundary treatment** | STOP band's **three lines together**; **`NONE IDENTIFIED ≠ NONE EXISTS` inside the panel's own frame** |
| 13 | **Source/authority labels** | Counts quoted from the accepted register's own reconciliation — **never recalculated** |
| 14 | **Type controls** | STOP band largest type on the slide; every panel status word ≥ 18 pt |
| 15 | **Mandatory omissions** | No connector across the band, loop, closed cycle, percentage, progress bar, gauge, tick, cross, red alarm, barrier or padlock iconography, **greyed lower row**, date, owner, authority holder, platform, or Triviron answer in any box |
| 16 | **Principal STOPs** | `M7-S12`, `M7-S13`, `M7-S15`, `M7-S18` · `M7V-S16`, `M7V-S17`, `M7V-S18`, `M7V-S26` |
| 17 | **Producer failure condition** | A finger tracing steps 1→8 crosses the band without stopping; a reader names content the arrows carry; a reader reads the lower row as a problem |

---

### Slide 4

| # | Field | Value |
|---:|---|---|
| 1 | **Number** | 4 |
| 2 | **Exact title** | The decision backlog: 21 questions, zero Triviron answers |
| 3 | **Allocated time** | **1.3 min** — allocated, not measured |
| 4 | **Narrative role** | Section B — the working record |
| 5 | **Teaching purpose** | Introduce the Translation Decision Register as the working record of Module 7 |
| 6 | **Five-second takeaway** | *Twenty-one questions. No answers, and none claimed.* |
| 7 | **Visual / source** | `M7V-04` → [`M07-S04`](../../assets/module-07/M07-S04.md) |
| 8 | **Visual form** | 7 × 3 backlog grid with a domain label column · five co-equal classification cells · full-width current-state panel |
| 9 | **Required visible copy** | See [`slide-copy.md`](slide-copy.md) Slide 4 |
| 10 | **Geometry** | Grid `y = 96–376`; label column **exactly 216 pt** `x = 48–264`; three question columns **each exactly 208 pt** with three **8 pt** gaps (`216 + 8 + 208 + 8 + 208 + 8 + 208 = 864`); **seven rows of exactly 40 pt** (`7 × 40 = 280`). Strip `y = 396–444`, **five cells each exactly 168 pt, four gaps of exactly 6 pt** (`5 × 168 + 4 × 6 = 864`). Panel `x = 48–912`, `y = 460–516` |
| 11 | **Connectors** | **0.** No arrow between grid and strip, between strip cells, from a grid cell to a classification cell, or into the panel |
| 12 | **Boundary treatment** | `enumeration order — not progression` **inside the strip's own frame**; each zero cell carries `prerequisite evidence not identified`; panel's six entries together |
| 13 | **Source/authority labels** | Every count quoted from register §10 — **no invented, adjusted or supplemented value** |
| 14 | **Type controls** | Cells 40 pt tall carry identifier + short label at ≥ 14 pt; classification, status and boundary words ≥ 18 pt |
| 15 | **Mandatory omissions** | No arrow, numbering of the classification cells, colour ramp, size or weight gradient, progress bar, percentage, tick, cross, per-row status column, candidate decision, authority holder, owner, date, platform, or Triviron answer in any cell |
| 16 | **Principal STOPs** | `M7-S10`, `M7-S12`, `M7-S13`, `M7-S18` · `M7V-S01`, `M7V-S21`, `M7V-S23`, `M7V-S26` |
| 17 | **Producer failure condition** | A reader reads `ESTABLISHED 0` as *the goal* or *the last stage*, or believes the grid is an incomplete form awaiting answers |

---

### Slides 5–11 — the domain family

**Seven slides, one shared grammar.** The family is specified once here and
instantiated seven times. **No domain slide is independently redesigned.**

| Shared control | Requirement |
|---|---|
| **Form** | **Three co-equal cards**, four stacked zones each, over a full-width exclusion strip, over a full-width boundary strip |
| **Zones** | **Z1** `TDR-` identifier + accepted question, verbatim · **Z2** evidence **kinds** only · **Z3** `Triviron evidence currently available: NONE IDENTIFIED` + `NONE IDENTIFIED ≠ NONE EXISTS` · **Z4** two independently labelled lines — `classification:` and `status: NOT YET ESTABLISHED` |
| **Geometry** | Cards **each exactly 280 pt wide, two gaps of exactly 12 pt** — `x = 48–328`, `340–620`, `632–912` (`3 × 280 + 2 × 12 = 864`). Standard family: `y = 96–392` (296 pt), zones 54 / 94 / 54 / 82 with three 4 pt gaps; strips `y = 408–460` and `472–516`. **Slides 8 and 10 use the accepted variant:** `y = 96–372` (276 pt), zones 54 / 84 / 54 / 72, block `y = 388–464`, strip `y = 476–516` |
| **Connectors** | **0 on every slide in the family.** No arrow between cards, between zones, from a card to a strip, or into a card. **Zero means zero** |
| **Co-equality** | Cards identical in width, height, border, fill and type. **No card is emphasised, widened or styled as nearer an answer** |
| **Typed absence** | `NONE IDENTIFIED` and `NOT YET ESTABLISHED` on **every** card, identically, neutrally. **No grey, dashes, opacity, strike-through, cross, unticked box, empty bar, red or amber, "0 of 3" tally, or "awaiting"/"pending" wording** |
| **Method badge** | `METHOD` only on `TDR-009` (Slide 7), `TDR-013` (Slide 9), `TDR-021` (Slide 11), each with its qualifier, as a **word in the classification line** |
| **Boundary strip** | Verbatim: **`These are questions Triviron must answer for itself. No answer on this slide is Triviron's, and none is proposed.`** |
| **Reading order** | Card 1 Z1→Z4, card 2 Z1→Z4, card 3 Z1→Z4, exclusion strip, boundary strip. **Co-equality and the absence of connectors stated in words** |
| **Family failure test** | Cover the boundary strip and ask which card is closest to being answered. **If a reader can pick one, the co-equality rule has failed.** Then ask what the project's answer is — **any answer offered is a STOP** |

---

### Slide 5

| # | Field | Value |
|---:|---|---|
| 1 | **Number** | 5 |
| 2 | **Exact title** | Domain 1: Coordination governance |
| 3 | **Allocated time** | **1.5 min** — allocated, not measured |
| 4 | **Teaching purpose** | Teach the three Domain 1 translation questions — `TDR-001`–`TDR-003` |
| 5 | **Five-second takeaway** | *Coordination has to be governed before any tool matters — and none of it is settled here.* |
| 6 | **Visual / source** | `M7V-05` → [`M07-S05`](../../assets/module-07/M07-S05.md) |
| 7 | **Family** | Standard geometry · `EVIDENCE REQUIRED` × 3 · no `METHOD` badge |
| 8 | **Slide-specific control** | **No arrow from `TDR-001` to `TDR-002` to `TDR-003`**, even though the argument runs in that order — the order is spoken, never drawn |
| 9 | **Mandatory omissions** | Family omissions, plus: no Harrismith purpose text, **no BEP/strategy document split drawn as a Triviron architecture**, no cycle-step diagram, no meeting, no frequency, no calendar |
| 10 | **Principal STOPs** | `M7-S13`, `M7-S14`, `M7-S15`, `M7-S18` · family `M7V-S` set plus `M7V-S05`, `M7V-S29` |
| 11 | **Producer failure condition** | Any document, structure or hierarchy can be named or pointed at in answer to *what document governs Triviron's coordination?* |

---

### Slide 6

| # | Field | Value |
|---:|---|---|
| 1 | **Number** | 6 |
| 2 | **Exact title** | Domain 2: Roles and authority |
| 3 | **Allocated time** | **1.5 min** — allocated, not measured |
| 4 | **Teaching purpose** | Teach the three Domain 2 translation questions — `TDR-004`–`TDR-006` |
| 5 | **Five-second takeaway** | *Three allocation decisions. Not one holder is known, and none may be guessed.* |
| 6 | **Visual / source** | `M7V-06` → [`M07-S06`](../../assets/module-07/M07-S06.md) |
| 7 | **Family** | Standard geometry, **with Z1 split into two equal-weight lines** — `function:` at `y = 96–121` and `holder:` at `y = 125–150`, exactly 25 pt each with a 4 pt gap (`25 + 4 + 25 = 54`) |
| 8 | **Slide-specific control** | **HIGHEST ORG-CHART AND HOLDER RISK. An organisation-chart visual form is prohibited in every variant.** `holder: NOT YET ESTABLISHED` appears on **each** card, never as a slide-level note. **A single line joining two objects is an organisation chart** |
| 9 | **Mandatory omissions** | Family omissions, plus: **no organisation chart, hierarchy, reporting line, tree, swimlane, matrix of people, seat, silhouette, avatar, photograph, job title as a holder, RACI, `X`-allocation grid, or Harrismith role name presented as a Triviron function** |
| 10 | **Principal STOPs** | `M7-S01`, `M7-S04`, `M7-S16`, `M7-S17`, `M7-S18` · family set plus `M7V-S02`, `M7V-S03`, `M7V-S04`, `M7V-S09` |
| 11 | **Producer failure condition** | Any person, organisation, job title or role holder can be named or pointed at; or the slide contains an organisation chart *"of a sort"* |

---

### Slide 7

| # | Field | Value |
|---:|---|---|
| 1 | **Number** | 7 |
| 2 | **Exact title** | Domain 3: Inputs and federation |
| 3 | **Allocated time** | **1.5 min** — allocated, not measured |
| 4 | **Teaching purpose** | Teach the three Domain 3 translation questions — `TDR-007`–`TDR-009` |
| 5 | **Five-second takeaway** | *Federation is a lens. It moves no authorship — and nothing here says what Triviron federates.* |
| 6 | **Visual / source** | `M7V-07` → [`M07-S07`](../../assets/module-07/M07-S07.md) |
| 7 | **Family** | Standard geometry · `EVIDENCE REQUIRED` × 2 · **`METHOD` on `TDR-009`** with its qualifier |
| 8 | **Slide-specific control** | **No container-to-view assembly diagram, no `assembled from` connector, no lens or funnel graphic, no upward or inward arrows.** Module 6's assembly form is **expressly not reused** |
| 9 | **Mandatory omissions** | Family omissions, plus: **no container, container name, folder, topology, CDE area, platform name, discipline set, federated-model graphic, lens, funnel, stack, assembly arrow, or state/transition symbol** |
| 10 | **Principal STOPs** | `M7-S02`, `M7-S03`, `M7-S12`, `M7-S15`, `M7-S18` · family set plus `M7V-S05` |
| 11 | **Producer failure condition** | Any container, discipline, folder or platform can be named or pointed at; or a reader reads the `METHOD` card as answered |

---

### Slide 8

| # | Field | Value |
|---:|---|---|
| 1 | **Number** | 8 |
| 2 | **Exact title** | Domain 4: Checks and tolerances |
| 3 | **Allocated time** | **1.5 min** — allocated, not measured |
| 4 | **Teaching purpose** | Teach the three Domain 4 translation questions — `TDR-010`–`TDR-012` |
| 5 | **Five-second takeaway** | *No check, no rule, no tolerance and no approver is inherited — not even as a starting point.* |
| 6 | **Visual / source** | `M7V-08` → [`M07-S08`](../../assets/module-07/M07-S08.md) |
| 7 | **Family** | **Variant geometry** — cards `y = 96–372`, zones 54 / 84 / 54 / 72; **enlarged bordered exclusion block `y = 388–464`**; boundary strip `y = 476–516`. `TDR-012` carries `holder: NOT YET ESTABLISHED` |
| 8 | **Slide-specific control** | **The exclusion block is the slide's second principal object and is a bordered rectangle — never a table**, because a table reads as a selectable menu. **No numeric Triviron value anywhere. No chain from interface to check to rule to approval** |
| 9 | **Mandatory omissions** | Family omissions, plus: **no numeric value of any kind, clearance, distance, percentage, threshold, score, starter check table, sample check row, interface matrix, check-type list presented as available, `CI-` identifier outside the exclusion block, pass/fail treatment, red/green, or approver** |
| 10 | **Principal STOPs** | `M7-S05`, `M7-S06`, `M7-S13`, `M7-S15`, `M7-S16` · family set plus `M7V-S07` |
| 11 | **Producer failure condition** | Any check, type, identifier or value can be named; **or any digit appears that is not part of `CI-01–CI-12` or a `TDR-` identifier** |

---

### Slide 9

| # | Field | Value |
|---:|---|---|
| 1 | **Number** | 9 |
| 2 | **Exact title** | Domain 5: Findings, Issues and statuses |
| 3 | **Allocated time** | **1.5 min** — allocated, not measured |
| 4 | **Teaching purpose** | Teach the three Domain 5 translation questions — `TDR-013`–`TDR-015` |
| 5 | **Five-second takeaway** | *Detecting something does not decide what it becomes — and no vocabulary here is Triviron's.* |
| 6 | **Visual / source** | `M7V-09` → [`M07-S09`](../../assets/module-07/M07-S09.md) |
| 7 | **Family** | Standard geometry · **`METHOD` on `TDR-013`** with its qualifier · `EVIDENCE REQUIRED` × 2 |
| 8 | **Slide-specific control** | **No arrow from finding to Issue, from detection to creation, from creation to status, or between any two status words.** Neither Harrismith Issue definition is quoted — the variance is referred to, not reproduced |
| 9 | **Mandatory omissions** | Family omissions, plus: **no status model, status sequence, status chip/badge/dot/traffic light, triage disposition list, Issue example, Issue identifier, numbering scheme, `Accepted condition`, `Deferred`, `Escalated`, funnel from findings to Issues, or counts of findings, clashes or Issues** |
| 10 | **Principal STOPs** | `M7-S03`, `M7-S07`, `M7-S13`, `M7-S15`, `M7-S18` · family set plus `M7V-S06`, `M7V-S29` |
| 11 | **Producer failure condition** | Any status Triviron would use can be named; or a reader believes every finding becomes an Issue |

---

### Slide 10

| # | Field | Value |
|---:|---|---|
| 1 | **Number** | 10 |
| 2 | **Exact title** | Domain 6: Verification, evidence and completion |
| 3 | **Allocated time** | **1.5 min** — allocated, not measured |
| 4 | **Teaching purpose** | Teach the three Domain 6 translation questions — `TDR-016`–`TDR-018` |
| 5 | **Five-second takeaway** | *A complete cycle is demonstrated, never asserted — and the only worked evidence here is Harrismith's.* |
| 6 | **Visual / source** | `M7V-10` → [`M07-S10`](../../assets/module-07/M07-S10.md) |
| 7 | **Family** | **Variant geometry** — cards `y = 96–372`, zones 54 / 84 / 54 / 72; **fenced Harrismith evidence note `y = 388–464`**, border weight **visibly different from the card borders**; boundary strip `y = 476–516` |
| 8 | **Slide-specific control** | **The fence heading is verbatim and inside the fence's own border: `HARRISMITH EVIDENCE ABOUT HARRISMITH — NOT TRIVIRON EVIDENCE`. No connector of any kind enters or leaves the fence. `GCR-006` and the partial-trace status appear nowhere outside it. No cycle is drawn** |
| 9 | **Mandatory omissions** | Family omissions, plus: **no verification prerequisite list, completion condition list or evidence-output list as Triviron content; no checklist, tick, completion percentage, closed-loop cycle graphic, zero-clash claim, `GCR-006` outside the fence, or Triviron cycle depicted as having run** |
| 10 | **Principal STOPs** | `M7-S12`, `M7-S13`, `M7-S15`, `M7-S18` · family set plus `M7V-S05` |
| 11 | **Producer failure condition** | Covering the cards, a reader says the note describes *Triviron's* evidence, or is unclear; or any cycle is drawn |

---

### Slide 11

| # | Field | Value |
|---:|---|---|
| 1 | **Number** | 11 |
| 2 | **Exact title** | Domain 7: Publication and acceptance boundary |
| 3 | **Allocated time** | **1.5 min** — allocated, not measured |
| 4 | **Teaching purpose** | Teach the three Domain 7 translation questions — `TDR-019`–`TDR-021` |
| 5 | **Five-second takeaway** | *Ability to move a file is not authority to change its state — and nobody here holds that authority.* |
| 6 | **Visual / source** | `M7V-11` → [`M07-S11`](../../assets/module-07/M07-S11.md) |
| 7 | **Family** | Standard geometry · **`METHOD` on `TDR-021`** · `TDR-020` carries `holder: NOT YET ESTABLISHED`. **Four act cells inside `TDR-021`'s Z2** — `x = 652–713`, `717–778`, `782–843`, `847–908`, **each exactly 61 pt, three gaps of exactly 4 pt**, the 8 pt residual **distributed 4 pt to each inset, never rounded into a cell** |
| 8 | **Slide-specific control** | **Zero connectors between the four governance acts, in any direction.** The programme-bounded authority statement sits **adjacent to `TDR-020`'s holder line**, not in a distant strip. **No holder invented in either direction** — the slide must not read as *Triviron has nobody* |
| 9 | **Mandatory omissions** | Family omissions, plus: **no authority holder in either direction, named authoriser, job title, approval chain, state or transition symbol, `T`-transition, `TRN-` event, CDE area, publication route, arrow between the four acts, gate, signature or stamp** |
| 10 | **Principal STOPs** | `M7-S02`, `M7-S09`, `M7-S13`, `M7-S15`, `M7-S16`, `M7-S18` · family set plus `M7V-S02`, `M7V-S04`, `M7V-S09` |
| 11 | **Producer failure condition** | Any answer is offered to *who may authorise publication for Triviron?*; **or the answer to *does Triviron have a publication authority?* is *no*** — the only correct answer is *this programme has not identified one*; or any arrow joins the four acts |

---

### Slide 12

| # | Field | Value |
|---:|---|---|
| 1 | **Number** | 12 |
| 2 | **Exact title** | What the evidence lets you say |
| 3 | **Allocated time** | **1.5 min** — allocated, not measured |
| 4 | **Narrative role** | Section D — precision about limits |
| 5 | **Teaching purpose** | Teach how to state the current translation position precisely without overstating evidence or governance maturity |
| 6 | **Five-second takeaway** | *Five kinds of statement. Not five rungs.* |
| 7 | **Visual / source** | `M7V-12` → [`M07-S12`](../../assets/module-07/M07-S12.md) |
| 8 | **Visual form** | Five co-equal cards in a **deliberately non-linear offset arrangement** around a central non-sequence hub, over a full-width foot strip. **Complexity HIGH** |
| 9 | **Required visible copy** | See [`slide-copy.md`](slide-copy.md) Slide 12 |
| 10 | **Geometry** | Upper three cards **each exactly 200 × 112 pt**, two gaps of **exactly 132 pt** — `x = 48–248`, `380–580`, `712–912`, `y = 88–200` (`3 × 200 + 2 × 132 = 864`). Lower two cards **each exactly 200 × 112 pt**, **centred in the upper gaps** — `x = 214–414` and `546–746`, `y = 344–456`. Hub `x = 288–672` (centred on 480), `y = 224–320`. Foot strip `x = 48–912`, `y = 476–520`. Vertical: `112 + 24 + 96 + 24 + 112 = 368 = 456 − 88` |
| 11 | **Connectors** | **0.** **No arrow between cards; no spoke from a card to the hub; no ring, orbit, circle or wheel.** A spoke makes the hub a parent; a ring makes a cycle |
| 12 | **Boundary treatment** | Hub's two lines together; each zero card carries `prerequisite not satisfied — not a stage awaiting arrival` **in its own frame**; foot strip's three entries together |
| 13 | **Source/authority labels** | Counts quoted from register §10; the central statement labelled **`TEACHING SYNTHESIS`** |
| 14 | **Type controls** | Every classification word, count, qualifier, hub line and foot-strip word ≥ 18 pt |
| 15 | **Mandatory omissions** | No arrow, spoke, ring, numbering, ordering marker, colour ramp, size ramp, weight ramp, progress bar, staircase, timeline, funnel, pyramid, maturity scale, percentage, tick, left-to-right advancement, **`ESTABLISHED` in a terminal position**, or status value on any card |
| 16 | **Principal STOPs** | `M7-S12`, `M7-S13`, `M7-S15`, `M7-S17`, `M7-S18` · `M7V-S21`, `M7V-S23`, `M7V-S24`, `M7V-S26` |
| 17 | **Producer failure condition** | A reader can put the five categories in order and believes the order means progress; merges the two `ESTABLISHED` meanings; or reads the zeros as a problem |

---

### Slide 13

| # | Field | Value |
|---:|---|---|
| 1 | **Number** | 13 |
| 2 | **Exact title** | Unknowns are controlled work |
| 3 | **Allocated time** | **1.4 min** — allocated, not measured |
| 4 | **Narrative role** | Section D — the typed-absence vocabulary |
| 5 | **Teaching purpose** | Teach the precise typed-absence vocabulary and why disciplined absence is a positive information-management result |
| 6 | **Five-second takeaway** | *Four kinds of unknown. The reason decides which one.* |
| 7 | **Visual / source** | `M7V-13` → [`M07-S13`](../../assets/module-07/M07-S13.md) |
| 8 | **Visual form** | **2 × 2 quadrant block** · full-width separating rule · separate evidence-position panel · full-width misuse-warning strip. **Complexity HIGH** |
| 9 | **Required visible copy** | See [`slide-copy.md`](slide-copy.md) Slide 13 |
| 10 | **Geometry** | Quadrants **each exactly 426 × 114 pt** — columns `x = 48–474` and `486–912` with one **12 pt** gap (`2 × 426 + 12 = 864`); rows `y = 96–210` and `222–336` with one **12 pt** gap (`2 × 114 + 12 = 240`). Separating rule `x = 48–912` at `y = 352`, ≥ 2 pt. Panel `x = 48–912`, `y = 368–440`. Strip `x = 48–912`, `y = 456–516` |
| 11 | **Connectors** | **0.** No arrow between quadrants, across the rule, or into the panel. **The separating rule is a boundary, not a connector** |
| 12 | **Boundary treatment** | **Each quadrant's misuse bar sits inside that quadrant**, never in the strip; the strip's four entries together |
| 13 | **Source/authority labels** | The two Harrismith illustrations are **Harrismith evidence about Harrismith**; the central statement labelled **`TEACHING SYNTHESIS`** |
| 14 | **Type controls** | Every status word, misuse bar, panel line and strip word ≥ 18 pt |
| 15 | **Mandatory omissions** | No arrow, numbering, ordering marker, colour ramp, severity scale, progress indicator, timeline, staircase, funnel, percentage, tick, cross, **`TBD` applied to any Triviron matter**, **`NOT ESTABLISHED` applied to any Triviron matter**, fifth quadrant, or classification word |
| 16 | **Principal STOPs** | `M7-S06`, `M7-S12`, `M7-S13`, `M7-S18` · `M7V-S22`, `M7V-S23`, `M7V-S25`, `M7V-S26` |
| 17 | **Producer failure condition** | A reader can say which status comes first; believes Triviron could be `NOT ESTABLISHED` today; or takes `NONE IDENTIFIED` for a status |

---

### Slide 14

| # | Field | Value |
|---:|---|---|
| 1 | **Number** | 14 |
| 2 | **Exact title** | From decision backlog to BEP workshop |
| 3 | **Allocated time** | **1.5 min** — allocated, not measured |
| 4 | **Narrative role** | Section E — the handoff and the Module 8 bridge |
| 5 | **Teaching purpose** | Close Module 7 by showing what future governed work must accomplish, and bridge to Module 8 |
| 6 | **Five-second takeaway** | *The answers have to be earned, and nothing here says when.* |
| 7 | **Visual / source** | `M7V-14` → [`M07-S14`](../../assets/module-07/M07-S14.md) |
| 8 | **Visual form** | Declared teaching-workflow band · register 1 · **authority gate strip** · register 2 · method one-liner · roadmap close · boundary strip |
| 9 | **Required visible copy** | See [`slide-copy.md`](slide-copy.md) Slide 14 |
| 10 | **Geometry — accepted `T7-J-R2` reconciliation · SUPERSEDED, RETAINED AS HISTORY.** `T7-L-R3` proved this single-frame layout infeasible at the accepted type floors, and its `64 pt` header band is arithmetically wrong for three 18 pt lines (which need `72.8 pt`). **Do not build these coordinates — the current production geometry is the two-frame `T7-L-R5` A/B geometry of §13.9** | **Header `x = 48–912`, `y = 84–148` (exactly 64 pt)** · register 1 `y = 156–224`, four boxes **each exactly 201 × 68 pt**, three **20 pt** gaps · **authority gate `y = 232–272` (exactly 40 pt, border ≥ 3 pt)** · register 2 `y = 280–348`, three boxes **each exactly 276 × 68 pt**, two **18 pt** gaps · method one-liner `y = 356–412` · roadmap close `y = 420–464`, three segments **each exactly 276 pt** · boundary strip `y = 472–520`. **All six inter-band gaps exactly 8 pt.** Vertical: `64 + 8 + 68 + 8 + 40 + 8 + 68 + 8 + 56 + 8 + 44 + 8 + 48 = 436 = 520 − 84`. Title zone `y = 0–72` reserved, **12 pt clear interval** to the header |
| 11 | **Header layout** | **Two semantic statements across three physical text lines**, wording unchanged: line 1 `TEACHING WORKFLOW — NOT A CURRENT TRIVIRON WORKFLOW`; line 2 `no actual Triviron workshop or schedule is established in this programme;`; line 3 `this diagram does not assert or schedule one`. **The semicolon is the only permitted break point.** Single (1.0) line spacing, no paragraph spacing, **no font condensation, no reduced character spacing**. **`T7-L-R2` CORRECTION — the accepted nominal fit `3 × 18 pt = 54 pt` is arithmetically wrong.** It treats line height as equal to point size. On the declared basis of §1.1, three `18 pt` lines occupy **`3 × 21.6 = 64.8 pt`**, plus `8 pt` padding = **`72.8 pt`**, against an accepted band of **`64 pt`** — a **deficit of `8.8 pt` before any other content**. **The header cannot be achieved at `≥ 18 pt` in `y = 84–148`. STOP AND REFER BACK — this is an unresolved item, see §11** |
| 12 | **Connectors** | **4** — three within register 1, one from stage 5 to stage 6. **No connector crosses, enters, leaves or passes behind the authority gate. No connector enters the final box** — it is reached by condition, not by arrow. **No connector touches the one-liner, roadmap close or boundary strip.** The one-liner's arrows are **typographic characters in a single text run**, not drawn connectors |
| 13 | **Boundary treatment** | Header's two statements together; gate strip's two lines together; boundary strip's three entries together |
| 14 | **Source/authority labels** | The roadmap close names a **module, not an event**; the central statement labelled **`TEACHING SYNTHESIS`** |
| 15 | **Type controls** | Every header, gate, one-liner and boundary word ≥ 18 pt |
| 16 | **Mandatory omissions** | **No meeting room, calendar, date, participant, seat, table, workshop photograph, agenda, scheduled event, clock or duration.** Also no connector across the gate, no connector into box 7, no tick, percentage, progress bar, authority holder, owner, organisation, platform, or Triviron BEP clause or section number |
| 17 | **Principal STOPs** | `M7-S10`, `M7-S11`, `M7-S15`, `M7-S17`, `M7-S18` · `M7V-S10`, `M7V-S16`, `M7V-S17`, `M7V-S18`, `M7V-S30`, `M7V-S31` |
| 18 | **Producer failure condition** | Any answer is offered to *when does the workshop happen?* or *who is the appropriate authority?*; or a finger tracing stages 1→7 crosses the gate without stopping or reaches stage 7 along an arrow |

---

## 9. Package-level production additions

**These are production controls. They add nothing to the accepted teaching or
visual STOP registers, which are unchanged.**

| # | The deck must… |
|---:|---|
| **P1** | Use the exact accepted slide titles, in order |
| **P2** | Carry the exact allocated times as **allocations**, never as measured or verified results |
| **P3** | Keep **manual advancement**; create no automatic slide-transition timing |
| **P4** | Build every visual from **native editable objects** and import nothing |
| **P5** | Reproduce accepted geometry exactly, and **STOP and refer back** rather than adjust it |
| **P6** | Keep every boundary strip a **principal object** at ≥ 18 pt |
| **P7** | Keep the deck's total connector count at **twelve**, with the per-slide distribution in §6 |
| **P8** | Take alternative text from the accepted source screen-reader descriptions |
| **P9** | **SUPERSEDED FOR MODULE 7 by `T7-L-R4`.** **Add no physical slide except the four expressly authorised second frames for logical Slides 6, 11, 13 and 14.** Physical count **exactly `18`** — expected, maximum and minimum; logical count **exactly `14`**. Still no appendix, agenda, thank-you, references, contact or bonus slide. See **§13.1** |
| **P10** | Add no logo, footer branding, page furniture or date stamp |

## 10. Production-state summary

| Field | Value |
|---|---|
| Package | **`MODULE 7 PRESENTATION ASSEMBLY PACKAGE — UNDER GOVERNED CORRECTION`** |
| `T7-L` · `T7-L0` | **`ACCEPTED after T7-L-R`** · **`ACCEPTED`** |
| `T7-L-R2` | **`ACCEPTED`** — *copy-density / type-floor reconciliation and feasibility audit* |
| `T7-L-R3` | **`ACCEPTED`** — *proof that the four one-frame layouts are production-infeasible; production-fit status reconciliation* |
| `T7-L-R4` | **`NOT YET ACCEPTED`** — *bounded production-robustness correction required: Slide 14 seam choice and avoidably tight local text-fit margins*. Its architecture (14 logical / 18 physical, four two-frame splits, `P9` supersession, titles, labels, timing, copy, type floors, connector census) is **accepted in principle and not reopened** |
| `T7-L-R5` | **`NOT YET ACCEPTED`** — *one bounded stale Slide 14 current-production typography instruction remained*. Its production architecture — 14 logical / 18 physical, the `workflow | close` seam, `14A = 4` / `14B = 0`, type floors, the AutoFit prohibition, the `G9` robustness framework and the hardened geometry — is **accepted and not reopened** |
| `T7-L-R6` | **`PENDING CHATGPT GOVERNANCE REVIEW`** — **not accepted** |
| `P9` | **`SUPERSEDED FOR MODULE 7`** — 14 logical units / 18 physical slides |
| Logical teaching units | **14** |
| Physical PowerPoint slides | **18** |
| Logical units specified | **14 of 14** |
| Physical frames specified | **18 of 18** — ten single-frame, four A/B pairs. See §13 |
| Physical frames **production-fit VERIFIED on the declared basis** | **17 of 18** — the ten single-frame logical units, plus seven of the eight split frames at `T7-L-R5` (§13.11) |
| Physical frames **`PRODUCTION FIT — BOUNDED / TIGHT`** | **1 — `M07-S11-A`**, min load-bearing region margin `+6.6 pt` against an `8 pt` target and a `+6.7 pt` mathematical maximum. **`BOUNDED / TIGHT — ACCEPTED FOR FABRICATION SUBJECT TO RENDERED-MEASUREMENT GATE`** (ChatGPT, at `T7-L-R6`) — see §13.12 |
| Physical frames unresolved | **`0`** |
| Production-robustness criterion | **`≥ 8 pt` planned slack on every load-bearing region** — §13.13. Achieved on **7 of 8** split frames; **`M07-S11-A` is at its arithmetic ceiling** |
| Slide 14 seam | **`workflow | close`** — `T7-L-R5`, on governance decision. The `T7-L-R4` authority-gate seam is **superseded** |
| Superseded | The four **one-frame** layouts for logical Slides 6, 11, 13 and 14. Their `T7-K` **coordinate arithmetic** stands as history; their **production geometry** is now the A/B geometry of §13.7–§13.9 (§12 records why) |
| Rendered assets | **`NONE`** |
| External imagery | **`NONE`** |
| PowerPoint (`T7-M`) | **`PRODUCED; QC FAILED; NOT ACCEPTED`** — external, not in this repository |
| PowerPoint (`T7-M-R1`) | **`NOT STARTED`** — **not authorised** |
| Deck review | **NOT PERFORMED** on a conforming deck |
| Rehearsal · measured timing | **`NOT PERFORMED`** |
| Timing | **`20.0 minutes allocated — not measured`** |
| Publication automation | **`PAUSED`** |

---

## 11. Type-floor feasibility audit — `T7-L-R2`

**Method.** Every visible run in [`slide-copy.md`](slide-copy.md) was classified
**A / B / C** (§3 there), Class C was removed from visible copy, Class B was
compressed to the limit the accepted architecture permits, and the residue was
measured against the accepted geometry on the **declared typographic basis of
§1.1**.

**Notation.** *need* = lines × line height + `8 pt` padding. *have* = accepted
band or zone height. **Deficits are stated, never absorbed.**

### 11.1 Slides feasible at the floors

| Slide | Binding element | Need | Have | Margin |
|---:|---|---:|---:|---:|
| **1** | boundary strip, 3 runs @ 18 pt, full width | `3 × 21.6 + 8 = 72.8` | `84` | **+11.2** |
| **2** | column content @ 18/14 pt | `21.6 + 3 × 16.8 + 8 = 80.0` | `340` | **+260.0** |
| **3** | STOP band, 3 runs @ 18 pt, full width | `1 + 1 + 2 = 4 lines → 86.4 + 8 = 94.4` | `90` | **−4.4 → resolved by re-allocating the panel's spare `44 pt`** |
| **4** | grid cell, identifier + 3–6 word topic @ 14 pt | `2 × 16.8 + 8 = 41.6` | `40` | **−1.6 → resolved by capping topic labels at 3–4 words** |
| **5** | family card, no mandatory statement | `257.6` | `300` | **+42.4** |
| **7** | family card, `METHOD` qualifier | `236.0` | `252` | **+16.0** |
| **8** | family card, variant | `257.6` | `276` | **+18.4** |
| **9** | family card, `METHOD` qualifier compressed | `236.0` | `252` | **+16.0** |
| **10** | family card, variant, fence reduced to 3 runs | `257.6` | `276` | **+18.4** |
| **12** | card, operative clause only | `43.2 + 3 × 16.8 + 8 = 101.6` | `112` | **+10.4** |

**Slides 3 and 4 carry a bounded residual** that the accepted geometry absorbs
without changing any coordinate: Slide 3's current-position panel has `44 pt` of
spare height above its own need, and Slide 4's topic labels are already specified
as three-to-six words — **capped at three to four by `T7-L-R2`** so a 28-character
cell fits two `14 pt` lines. **Neither is a geometry change.**

### 11.2 Slides unresolved at the floors

**These four slides cannot be built at `≥ 14 pt` / `≥ 18 pt` under the accepted
geometry, after full Class B compression. They are reported, not repaired.**

#### Slide 6 — Zone 1 carries three runs, two of them `18 pt`

```text
function:  <value>            18 pt, 1 line   = 21.6
holder: NOT YET ESTABLISHED   18 pt, 1 line   = 21.6      (status → 18 pt floor)
TDR-nnn — <question>          14 pt, 2 lines  = 33.6
padding                                       =  8.0
                                        need  = 84.8
                              accepted Z1     = 54.0
                                      DEFICIT = 30.8
```

**Card-level:** `84.8 + 24.8 + 72.8 + 72.8 + 12 = 267.2` against `252 pt`
available once the boundary strip is enlarged to carry the mandatory holder
statement. **Card deficit `15.2 pt`.**

**Why it cannot be compressed away.** The question may not be deleted; `holder:
NOT YET ESTABLISHED` is a **status** and is floored at `18 pt`; the holder line
**may not be lighter or smaller than the function line** (a protected control);
and `function ≠ person` is carried **structurally** by the two separate lines, so
merging them destroys the slide's principal teaching point. **No org chart,
hierarchy, RACI or role-holder graphic may be introduced.**

#### Slide 11 — card 2 must carry a 107-character `18 pt` governance statement

```text
TDR-020 — <question>          14 pt, 2 lines  = 33.6
holder: NOT YET ESTABLISHED   18 pt, 1 line   = 21.6
programme-bounded authority   18 pt, 4 lines  = 86.4      (107 ch ÷ 30 ch/line)
Z3 evidence position          18 pt, 3 lines  = 64.8
Z4 classification + status    18 pt, 3 lines  = 64.8
padding, 4 zones                              = 32.0
zone gaps                                     = 12.0
                                        need  = 315.2
                              available       = 252.0
                                      DEFICIT =  63.2
```

**Why it cannot be compressed away.** The statement is **mandatory verbatim** and
must sit **adjacent to `TDR-020`'s holder line**, not in a distant strip. Card 3's
Zone 2 separately carries the **four co-equal act cells**, which at `61 pt` wide
hold only **7 characters per `14 pt` line** — `recipient acceptance` needs three
lines. **The four acts may not be collapsed, and zero connectors may run among
them.**

#### Slide 13 — four quadrants at the `18 pt` floor

```text
quadrant meaning line         18 pt, 2 lines  = 43.2      (46 ch/line at 426 pt)
misuse bar                    18 pt, 2 lines  = 43.2
padding                                       =  8.0
                                        need  = 94.4
                              accepted        = 114.0     → +19.6  OK
NOT YET ESTABLISHED quadrant additionally carries the 21-status note:
                              18 pt, 4 lines  = 86.4
                                        need  = 180.8
                              accepted        = 114.0
                                      DEFICIT =  66.8
```

**Slide 13 was treated as presumptively feasible. The audit does not support
that.** Three of the four quadrants fit; the `NOT YET ESTABLISHED` quadrant does
not, because it alone carries the 21-status note. **No copy correction has been
applied**, because the increment protects this slide's content and the deficit is
a geometry matter. **The four semantic states, the 2 × 2 non-sequential
arrangement, the absence of arrows, the separate evidence-position panel and
`states ≠ stages` are all intact.**

#### Slide 14 — the seven bands exceed the envelope

| Band | Need | Accepted | Deficit |
|---|---:|---:|---:|
| header declaration, 3 lines @ 18 pt | `72.8` | `64` | **8.8** |
| register 1, 2 lines @ 18 pt | `51.2` | `68` | — |
| **authority gate, 2 runs @ 18 pt** | `72.8` | `40` | **32.8** |
| register 2, 3 lines @ 18 pt | `72.8` | `68` | **4.8** |
| method one-liner, 202 ch @ 18 pt | `72.8` | `56` | **16.8** |
| roadmap close, 2 lines @ 14 pt | `41.6` | `44` | — |
| boundary strip, compressed, @ 18 pt | `2 + 2 + 2 = 6 lines → 129.6 + 8 = 137.6` | `48` | **89.6** |
| six inter-band gaps | `48` | `48` | — |
| **total** | **`≈ 570`** | **`436`** | **`≈ 134`** |

**After the Class B compressions recorded in [`slide-copy.md`](slide-copy.md)
Slide 14**, the deficit falls from approximately `163 pt` to approximately
`134 pt`. **It does not reach zero.** The gate strip and the boundary strip are
the binding elements, and **both are Class A governance boundaries at the `18 pt`
floor**.

**Why it cannot be compressed away.** The header declaration is verbatim across
three lines; `AUTHORITY REQUIRED — no automatic progression` and `evidence ≠
authority` are load-bearing; the method one-liner appears **in full, all nine
objects, or not at all**; and the boundary strip's three entries include a
`TEACHING SYNTHESIS` line and the unchanged-backlog statement. **The authority
gate remains between the registers, four connectors remain, none crosses the
gate, and none enters the final box.**

### 11.3 Geometry position — deliberately not changed here

**`T7-L-R2` applies no geometry change.** Every deficit above would require
re-allocating band and zone heights, and §26 of the increment requires any
geometry change to propagate consistently through the visual-demonstration plan,
the affected `M07-Snn` sources, this specification, the asset manifest and both
checklists. **A partial propagation would create the conflicting geometry layers
that rule expressly prohibits.**

**The reconciliation is therefore complete on copy and incomplete on geometry**,
and the geometry work is **referred back** as a distinct governed increment. The
arithmetic above is the input that increment needs:

| Slide | Minimum geometry reconciliation required |
|---:|---|
| **5–11** | Re-allocate the family zones inside the **unchanged** `296 pt` / `276 pt` card envelope — indicative `Z1 60 / Z2 60 / Z3 76 / Z4 88`, sum `284 + 12 = 296` ✓ — and enlarge the boundary strip on Slides 6, 7, 9 and 11 to carry the mandatory statement at `18 pt` |
| **6** | Additional Zone 1 height for the third run, or an authorised relocation of the question within the card |
| **11** | A band for the programme-bounded authority statement that remains **adjacent** to card 2's holder line |
| **13** | Additional height for the `NOT YET ESTABLISHED` quadrant **without** breaking the 2 × 2 co-equality |
| **14** | Re-allocation across the seven bands within `x = 48–912`, `y ≤ 520`, preserving the title zone, the visual ordering, the gate between the registers and the no-crossing connector semantics |

**No coordinate in §8 has been altered.** **No conflicting geometry layer has
been created.**

### 11.4 Audit conclusion

| Question | Answer |
|---|---|
| Does the corrected specification target `≥ 14 pt` for every visible run? | **YES — §7 A1, absolute** |
| Does it target `≥ 18 pt` for every principal / status / classification / boundary run? | **YES — §7 A2, absolute** |
| Does any instruction anywhere permit shrinking below those floors? | **NO — all such latitude removed** |
| Is the visible-copy density materially reduced? | **YES — Slides 2, 4, 5–11, 12, 14** |
| Is every accepted semantic boundary intact? | **YES** |
| Is the package ready for `T7-M-R1`? | **NO. Four slides are unresolved. `T7-M-R1` is `NOT STARTED` and not authorised** |

---

## 12. Geometry-feasibility reconciliation — `T7-L-R3`

**`T7-L-R2 — ACCEPTED`** *(as copy-density / type-floor reconciliation and
feasibility audit; production readiness not established)*.
**`T7-L-R3 — PENDING CHATGPT GOVERNANCE REVIEW`.**

`T7-L-R3` was directed to resolve the four slides §11 recorded unresolved —
**6, 11, 13, 14** — by **geometry/layout reconciliation within the accepted visual
concepts**, at the accepted type floors, with **positive safety margin**.

**Result: none of the four can be resolved that way. All four remain
`UNRESOLVED`.** The reason is not layout skill; it is arithmetic, and it is set
out in full below so the governance decision can be taken on evidence.

### 12.1 Method

Every region of each slide was re-derived from the **`T7-L-R2` accepted visible
copy** on the **declared basis of §1.1** — line height `1.2 ×`, character advance
`0.5 ×`, padding `8 pt` per axis — using the **worst-case string** in each
co-equal object, since co-equal objects must share one height.

**Content budget.** Slides 6, 11 and 13 begin at `y = 96`; §6 of the increment
permits a first content edge at `y ≥ 84`, so all four were given the **maximum
budget `y = 84–520 = 436 pt`**. Slide 14 already begins at `y = 84`.

**No coordinate has been changed.** Changing coordinates that still fail would
create churn across five controlling layers for no feasibility gain, and would
breach the §21 requirement that no layer be left inconsistent with another. §8
therefore still carries the accepted geometry, now correctly labelled as
**coordinate-arithmetic verified, production fit NOT verified** — see §12.7.

### 12.2 Slide 6 — three co-equal Domain 2 cards

**Cards `280 pt` wide → interior `272 pt` → `30 chars/line` at 18 pt, `38` at 14 pt.**

| Zone | Runs, worst case | Lines | Height |
|---|---|---:|---:|
| **Z1** | `function: technical-response ownership` 37 ch @ 18 | 2 | `43.2` |
| | `holder: NOT YET ESTABLISHED` 27 ch @ 18 | 1 | `21.6` |
| | `TDR-006 — Who verifies, and when is verification required?` 58 ch @ 14 | 2 | `33.6` |
| | *+ 2 internal gaps + padding* | | `16.0` |
| | **Z1 need** | | **`114.4`** |
| **Z2** | evidence kinds, 87 ch @ 14 | 3 | `58.4` |
| **Z3** | `Triviron evidence currently available: NONE IDENTIFIED` 54 ch @ 18 | 2 | `43.2` |
| | `NONE IDENTIFIED ≠ NONE EXISTS` 29 ch @ 18 | 1 | `21.6` |
| | **Z3 need** | | **`76.8`** |
| **Z4** | `classification: EVIDENCE REQUIRED` 33 ch @ 18 | 2 | `43.2` |
| | `status: NOT YET ESTABLISHED` 27 ch @ 18 | 1 | `21.6` |
| | **Z4 need** | | **`76.8`** |
| | *3 inter-zone gaps* | | `12.0` |
| | **CARD** | | **`338.4`** |

| Full-width band | Runs | Height |
|---|---|---:|
| Exclusion strip | heading 29 ch @ 18 (1 line) + grouped nouns 75 ch @ 14 (1 line) | `50.4` |
| Boundary strip | family sentence 112 ch @ 18 (2 lines) + mandatory holder statement 147 ch @ 18 (2 lines) | `98.4` |
| *2 band gaps* | | `24.0` |

**Total `511.2 pt` · budget `436 pt` · DEFICIT `75.2 pt`.**

**Every lever was tested and none closes it.** Starting at `y = 84` is already
included. Merging the two full-width bands into one saves `20 pt`. Shortening the
worst function value to `function: technical response` (28 ch, one line) saves
`21.6 pt` — and was **rejected** under §4/§25, since *ownership* is load-bearing
for `TDR-005`. Even taking both, the deficit is `33.6 pt`.

**Why nothing else is available.** `holder: NOT YET ESTABLISHED` is a **status**
and is floored at 18 pt; the production control requires the holder line to be
**the same weight as the function line**, so `function:` is floored at 18 pt too;
`function ≠ person` is carried **structurally** by those two separate lines, so
they may not be merged. Z3's two lines and Z4's two lines are mandatory verbatim
at 18 pt. **Sub-dividing the card into columns makes it worse** — a narrower
column carries fewer characters per line and therefore needs more lines.

### 12.3 Slide 11 — three co-equal Domain 7 cards

| Zone | Runs, worst case | Lines | Height |
|---|---|---:|---:|
| **Z1** | `TDR-021` question 80 ch @ 14 | 3 | `50.4` |
| | `holder: NOT YET ESTABLISHED` @ 18 (card 2) | 1 | `21.6` |
| | **Z1 need** | | **`84.0`** |
| **Z2** | evidence kinds 86 ch @ 14 | 3 | `58.4` |
| | **act cells — `recipient acceptance` 20 ch @ 18 in a `61 pt` cell (`5 chars/line`)** | **4** | **`94.4`** |
| | **Z2 need — the act cells govern** | | **`94.4`** |
| **Z3** | as Slide 6 | 3 | `76.8` |
| **Z4** | `classification: METHOD` @ 18 + four-act qualifier 65 ch @ 14 + `status:` @ 18 | 1+2+1 | `92.8` |
| | *3 inter-zone gaps* | | `12.0` |
| | **CARD** | | **`360.0`** |

| Full-width band | Height |
|---|---:|
| Authority band — `no controlled Triviron publication / exchange authority allocation is currently identified in this programme`, 107 ch @ 18 (2 lines) | `51.2` |
| Exclusion strip | `50.4` |
| Boundary strip — family sentence + two-directional statement, 2 + 2 lines @ 18 | `98.4` |
| *3 band gaps* | `36.0` |

**Total `596.0 pt` · budget `436 pt` · DEFICIT `160.0 pt`.**

**The §12 authorisation to relocate the authority statement was used.** Moving it
out of card 2's narrow column into a dedicated full-width band **saves `43.2 pt`**
— inside the card it needs 4 lines (`94.4 pt`), full width only 2 (`51.2 pt`).
**That saving is real and is already counted above.** It leaves `160 pt` still
missing.

**The four act cells are the second binding element.** At `61 pt` wide a cell
carries **five characters** per 18 pt line, so `recipient acceptance` needs four
lines. Rearranging them vertically inside the card (`106.4 pt`) or as a 2 × 2
block (`98.4 pt`) is **no better than the accepted horizontal row (`94.4 pt`)**.
They may not be collapsed, may not be narrowed further, and **zero connectors may
run among them**.

### 12.4 Slide 13 — four co-equal semantic-state quadrants

**Quadrants `426 pt` wide → interior `418 pt` → `46 chars/line` at 18 pt, `59` at 14 pt.**

| Quadrant | Head @ 18 | Meaning @ 14 | Misuse bar @ 18 | Need |
|---|---:|---:|---:|---:|
| `NOT YET ESTABLISHED` | 1 line | 3 lines | 118 ch → 3 lines | `153.6` |
| `NOT ESTABLISHED` | 1 | 2 | 165 ch → 4 lines | `157.6` |
| `UNRESOLVED` | 1 | 2 | 48 ch → 2 lines | `114.4` |
| `TBD` | 1 | 2 | 158 ch → 4 lines | `157.6` |

**Co-equality forces every quadrant to the worst case: `157.6 pt`.**
Two rows + one `12 pt` gap = **`327.2 pt`**.

| Lower region | Height |
|---|---:|
| `CURRENT REGISTER POSITION` + the 21-status statement, 146 ch @ 18 → 4 lines in a `426 pt` column | `120.0` |
| `EVIDENCE AVAILABILITY` + `NONE IDENTIFIED` + field-8 definition + `NONE IDENTIFIED ≠ NONE EXISTS` + not-a-status line 152 ch @ 18 → 4 lines | `208.8` |
| **side-by-side panel — the taller column governs** | **`208.8`** |
| Misuse-warning strip, four entries @ 18, full width | `106.4` |
| *2 band gaps* | `24.0` |

**Total `666.4 pt` · budget `436 pt` · DEFICIT `230.4 pt`.**

**The authorised relocation was applied and it works as intended.** Moving the
21-row status census out of the `NOT YET ESTABLISHED` quadrant into a separately
labelled `CURRENT REGISTER POSITION` element **removes the co-equality defect** —
that quadrant no longer carries more weight than its three peers, and the four
remain genuinely co-equal. **The relocation is a correct and reusable design
decision; it simply does not create space, because the census still has to appear
somewhere on the slide.**

**Slide 13 also fails a stronger test.** Its mandatory `≥ 18 pt` text, counted as
bare line height with **no** 14 pt copy, **no** padding, **no** inter-run gap,
**no** border and **no** band gap, is **24 lines = `518.4 pt`** against a content
height of `436 pt`. **The governance text alone does not fit the canvas at 18 pt,
in any arrangement whatsoever.** This is a proof of impossibility, not a layout
shortfall.

### 12.5 Slide 14 — declaration · Register 1 · gate · Register 2 · supporting regions

**Horizontal packing was authorised by §18 and was tested.**

| Region | Composition | Height |
|---|---|---:|
| Header declaration | 3 lines @ 18, full width | `72.8` |
| Register 1 | 4 boxes `201 pt` (`21 chars/line`); `appropriate authority engaged` → 2 lines | `51.2` |
| Authority gate | `AUTHORITY REQUIRED — no automatic progression` 1 line + `evidence ≠ authority · …` 2 lines | `76.8` |
| Register 2 | 3 boxes `276 pt` (`29 chars/line`); `BEP / matrix / schedule / appendix populated only when earned` → 3 lines | `72.8` |
| Method chain + roadmap close **side by side** | chain in `640 pt` (2 runs, 4 lines) `98.4`; roadmap in `212 pt` `108.8` | `108.8` |
| Boundary strip | 3 entries @ 18, full width, 2 + 2 + 2 lines | `145.6` |
| *5 band gaps* | | `40.0` |

**Best achievable total `557.6 pt` · budget `436 pt` · DEFICIT `121.6 pt`.**
Horizontal packing of the supporting regions **saved `49.6 pt`** against the
`607.2 pt` all-stacked arrangement. It is a genuine improvement and it is
retained in the recommendation below — but it recovers `50 pt`, not `134 pt`.

**Why horizontal packing cannot close the rest.** For a fixed string, a narrower
column produces **more** lines and therefore **more** height. Full-width
single-column stacking already **minimises** the height of every long region.
Horizontal packing helps only where two **short** regions can share a row, and
Slide 14 has exactly one such pairing. The header, the gate, the nine-object
chain and the boundary strip are all long, and all are already at their
minimum-height full-width form.

**Header note.** The accepted `3 × 18 pt = 54 pt inside 64 pt` claim is
superseded, as §11 already recorded. Three 18 pt lines need `64.8 pt` of line
height plus `8 pt` padding = **`72.8 pt`**, so the header band must be at least
`82 pt` to carry the declaration with the `≥ 8 pt` margin this increment
requires. **The declaration's wording, its three physical lines and the semicolon
break point are unchanged.**

### 12.6 Options that would resolve all four — for governance decision

**Reported, not applied. `T7-L-R3` invents none of these and chooses none.**

| # | Option | Result | Blocked by |
|---:|---|---|---|
| **1** | **Split each overloaded slide into two**, preserving every accepted string and both type floors | **All eight halves PASS with large margin** — see §12.6.1 | **`P9`** — *add no slide* |
| **2** | Set **explanatory** boundary prose (misuse bars, definitions, qualifiers) at 14 pt, keeping status and classification **words**, STOP declarations and verbatim declarations at 18 pt | **Still fails all four**: margins `−65.6`, `−162.4`, `−112.8`, `−59.2` | insufficient anyway |
| **3** | Move further load-bearing content from slides to presenter cues | untested | **§4 · §25** of this increment |
| **4** | Adopt a larger reference canvas than `960 × 540 pt` | untested | **§6** — canvas preserved |
| **5** | Revise the declared basis, if a producer's real font metrics are narrower or shorter | conditional | **§5** — basis is fixed for planning |

**Option 2 is quantified because it is the least invasive, and it is reported
precisely so that it is not mistaken for a solution: it does not work.**

#### 12.6.1 Option 1, quantified

Budget `436 pt` per slide, full `18/14 pt` floors, **every accepted visible string
retained**, nothing moved to notes.

| Half | Carries | Need | Margin |
|---|---|---:|---:|
| **6a** | three co-equal Domain 2 cards | `338.4` | **`+97.6`** |
| **6b** | exclusion strip · boundary strip · mandatory holder statement | `160.8` | **`+275.2`** |
| **11a** | three co-equal Domain 7 cards incl. the four act cells | `372.0` | **`+64.0`** |
| **11b** | authority band · exclusion strip · boundary strip | `224.0` | **`+212.0`** |
| **13a** | four co-equal semantic-state quadrants | `327.2` | **`+108.8`** |
| **13b** | `CURRENT REGISTER POSITION` · `EVIDENCE AVAILABILITY` · misuse-warning strip | `327.2` | **`+108.8`** |
| **14a** | declaration · Register 1 · authority gate · Register 2 | `297.6` | **`+138.4`** |
| **14b** | nine-object method chain · roadmap close · boundary strip | `301.6` | **`+134.4`** |

**Every half passes with well above the `≥ 8 pt` margin this increment requires.**
The split lines fall on the accepted semantic seams — cards from strips, quadrants
from panels, workflow from supporting close — so **no visual concept is replaced
and no teaching meaning is redesigned**. Slide 14's split falls exactly at the
**authority gate**, which is where the slide's own argument already divides.

**This is the only tested arrangement that satisfies all of: required visible
copy · accepted semantic boundaries · connector controls · `≥ 14 pt` every run ·
`≥ 18 pt` every principal, status, classification and boundary run · positive
safety margin.** **It requires a governance decision to relax `P9`, and
`T7-L-R3` does not take that decision.**

### 12.7 `GEOMETRY VERIFIED` — the distinction that was missing

**The accepted sources record `GEOMETRY ARITHMETIC — VERIFIED AGAINST ACCEPTED
SPECIFICATION`. That claim is true and remains true. It was also misread as
production feasibility, and it never meant that.**

| Claim | Meaning | Status on Slides 6, 11, 13, 14 |
|---|---|---|
| **Coordinate arithmetic verified** | Spans, equalities, gaps and disjointness reconcile: `Σ widths + Σ gaps = span`, no overlap, no off-canvas object | **VERIFIED — unchanged by `T7-L-R3`** |
| **Production fit verified** | The required copy **fits the stated regions at the type floors**, on a declared typographic basis, with positive margin | **NOT VERIFIED — `UNRESOLVED`** |

**The plan's self-check rules `G1`–`G8` test only the first.** No rule tested
text fit, which is why fourteen slides could be recorded `GEOMETRY VERIFIED` and
still be unbuildable at 18 pt. **`T7-L-R3` adds `G9` to the visual-demonstration
plan** to close that gap; it is a clarification of the existing self-check, **not
a new automatic-fail condition** — the register stays at **42**.

**From `T7-L-R3` onward, no slide may be described as production-feasible unless
its type-floor arithmetic passes with positive margin.**

### 12.8 `T7-L-R3` result

| Slide | Result | Deficit at best arrangement tested |
|---:|---|---:|
| **6** | **UNRESOLVED** | `75.2 pt` |
| **11** | **UNRESOLVED** | `160.0 pt` |
| **13** | **UNRESOLVED** | `230.4 pt` — and its 18 pt text alone exceeds the canvas |
| **14** | **UNRESOLVED** | `121.6 pt` after authorised horizontal packing |

**Not all four PASS. Production readiness is therefore not recommended, and
`T7-M-R1` remains `NOT STARTED` and `NOT AUTHORISED`.**

**Slides 1, 2, 3, 4, 5, 7, 8, 9, 10 and 12 are untouched** by `T7-L-R3` and keep
their `T7-L-R2` result, *feasible on the declared basis*.

---

## 13. Governed split pagination — `T7-L-R4`

**`T7-L-R3 — ACCEPTED`** *(as proof that the four one-frame layouts are
production-infeasible, and as the production-fit status reconciliation)*.
**`T7-L-R4 — PENDING CHATGPT GOVERNANCE REVIEW`.**

**ChatGPT has expressly authorised a narrow relaxation of `P9`.** Module 7 is now
produced as **fourteen logical teaching units across eighteen physical
PowerPoint slides**. Only logical Slides **6, 11, 13 and 14** are paginated, each
into **exactly two** physical frames.

**This is controlled pagination.** It is **not** new teaching content, not four
new topics, not an appendix, not optional or bonus slides, not an expanded
curriculum, and not a change to the Translation Decision Register.

### 13.1 `P9` — superseded for Module 7

| | |
|---|---|
| **Old `P9`** | *Add no slide, no appendix, no agenda slide, no thank-you slide and no contact slide* — **exactly fourteen physical slides** |
| **New `P9`** | **`P9 — SUPERSEDED FOR MODULE 7` by the governed 14-logical / 18-physical pagination rule.** **Add no physical slide except the four expressly authorised second frames for logical Slides 6, 11, 13 and 14.** Still no appendix, agenda, thank-you, references, contact or bonus slide |
| **Physical slide count** | **expected `18` · maximum `18` · minimum `18`** |
| **Logical unit count** | **expected `14` · maximum `14` · minimum `14`** |

### 13.2 The one-to-one rule, reconciled

**Former rule:** *one logical slide → one visual source → one physical slide.*

**Replaced by:** **one logical teaching unit → one accepted logical visual source
→ one, or (only where governed split pagination is authorised) two, physical
frames.**

**Ten logical units map 1 : 1. Four map 1 : 2. Fourteen logical sources →
eighteen physical frames.** **This deck has eighteen physical slides and
fourteen teaching topics. It does not have eighteen teaching topics.**

### 13.3 Logical-to-physical map

| Logical unit | Exact accepted title | Logical visual | Physical frame | Physical # | Continuation label | Allocation |
|---:|---|---|---|---:|---|---:|
| 1 | Where we are: Harrismith → Triviron | `M7V-01` | `M07-S01` | **1** | — | 1.0 |
| 2 | Translate the method, not the answers | `M7V-02` | `M07-S02` | **2** | — | 1.3 |
| 3 | The translation chain | `M7V-03` | `M07-S03` | **3** | — | 1.5 |
| 4 | The decision backlog: 21 questions, zero Triviron answers | `M7V-04` | `M07-S04` | **4** | — | 1.3 |
| 5 | Domain 1: Coordination governance | `M7V-05` | `M07-S05` | **5** | — | 1.5 |
| **6** | Domain 2: Roles and authority | `M7V-06-A` | **`M07-S06-A`** | **6** | **`PART 1 OF 2`** | **1.0** |
| **6** | Domain 2: Roles and authority | `M7V-06-B` | **`M07-S06-B`** | **7** | **`PART 2 OF 2`** | **0.5** |
| 7 | Domain 3: Inputs and federation | `M7V-07` | `M07-S07` | **8** | — | 1.5 |
| 8 | Domain 4: Checks and tolerances | `M7V-08` | `M07-S08` | **9** | — | 1.5 |
| 9 | Domain 5: Findings, Issues and statuses | `M7V-09` | `M07-S09` | **10** | — | 1.5 |
| 10 | Domain 6: Verification, evidence and completion | `M7V-10` | `M07-S10` | **11** | — | 1.5 |
| **11** | Domain 7: Publication and acceptance boundary | `M7V-11-A` | **`M07-S11-A`** | **12** | **`PART 1 OF 2`** | **1.0** |
| **11** | Domain 7: Publication and acceptance boundary | `M7V-11-B` | **`M07-S11-B`** | **13** | **`PART 2 OF 2`** | **0.5** |
| 12 | What the evidence lets you say | `M7V-12` | `M07-S12` | **14** | — | 1.5 |
| **13** | Unknowns are controlled work | `M7V-13-A` | **`M07-S13-A`** | **15** | **`PART 1 OF 2`** | **0.8** |
| **13** | Unknowns are controlled work | `M7V-13-B` | **`M07-S13-B`** | **16** | **`PART 2 OF 2`** | **0.6** |
| **14** | From decision backlog to BEP workshop | `M7V-14-A` | **`M07-S14-A`** | **17** | **`PART 1 OF 2`** | **1.0** |
| **14** | From decision backlog to BEP workshop | `M7V-14-B` | **`M07-S14-B`** | **18** | **`PART 2 OF 2`** | **0.5** |
| | **Total** | **14 logical** | **18 physical** | **18** | **4 pairs** | **20.0** |

**A producer must always be able to answer both questions:** *which physical
PowerPoint slide is this?* and *which logical Module 7 teaching unit does it
implement?* **Both identifiers appear in every controlling layer.**

### 13.4 Titles and continuation labels

| Rule | Requirement |
|---|---|
| **T1** | **The parent title is reproduced verbatim on both frames of a pair.** It is never rewritten, shortened, suffixed or qualified to create a new claim |
| **T2** | The continuation label is **`PART 1 OF 2`** / **`PART 2 OF 2`**, placed **inside the reserved title zone `y = 0–72`, right-aligned, separate from the title wording**. It consumes **no content height** |
| **T3** | **The label is production navigation, not teaching content.** It carries no semantic, sequential or progression meaning |
| **T4** | **On logical Slide 13 the label means `second physical page` and nothing else** — never *next semantic stage*. The four semantic states are **not divided** between the pages, so no state ordering can arise |
| **T5** | **On logical Slide 14 the label never implies that the page advance carries authority.** Frame B opens with its own boundary reminder — see §13.9 |
| **T6** | The label is **not** a logo, footer, page furniture or date stamp, all of which remain prohibited by `P10` |

### 13.5 Timing reconciliation

**Total remains `20.0 minutes allocated — not measured`. No allocation was
increased because a logical unit uses two frames.**

| Logical unit | Parent allocation | Frame A | Frame B | Pair sum |
|---:|---:|---:|---:|---:|
| **6** | **1.5** | 1.0 | 0.5 | **1.5** ✓ |
| **11** | **1.5** | 1.0 | 0.5 | **1.5** ✓ |
| **13** | **1.4** | 0.8 | 0.6 | **1.4** ✓ |
| **14** | **1.5** | **1.0** | **0.5** | **1.5** ✓ |

**Child allocations are unequal where the semantic split warrants it** — each A
frame carries the substantive cards, quadrants or workflow core, each B frame the
governance bands or supporting close. **Every pair sum equals its parent
exactly.** Deck total:
`1.0 + 1.3 + 1.5 + 1.3 + 1.5 + 1.0 + 0.5 + 1.5 + 1.5 + 1.5 + 1.5 + 1.0 + 0.5 +
1.5 + 0.8 + 0.6 + 1.0 + 0.5 = 20.0` ✓ — **allocated, not measured. No rehearsal
or timing verification is claimed.**

**`T7-L-R5` rebalanced logical Slide 14's children only**, from `0.8 + 0.7` to
**`1.0 + 0.5`**, because the corrected `workflow | close` seam moves Register 2
onto frame A. **The pair sum is unchanged at `1.5` and the deck total is unchanged
at `20.0`.** No other allocation changed.

### 13.6 Repeated boundary text — the governed reason

**Rule `G7` requires that no boundary, status or STOP warning be positioned
outside the visual region it governs.** Splitting a logical slide therefore
**requires** the governing boundary to appear on **both** frames wherever both
frames carry governed content. This is not padding and not duplication for
appearance.

| Frame | Repeated text | Why `G7` requires it |
|---|---|---|
| **6A · 11A** | family boundary strip, verbatim | The frame shows three unanswered Triviron question cards. Without the boundary, the cards would sit outside the region their governing warning occupies |
| **6B · 11B** | family boundary strip, verbatim | The frame shows exclusions and a mandatory programme-bounded statement; the same boundary governs them |
| **13A** | `THESE ARE SEMANTIC STATES, NOT STAGES — no chronological progression exists among them` | This warning governs the four quadrants. It may not sit on the other page |
| **14A · 14B** | **nothing repeated** | **`T7-L-R5`:** the `workflow | close` seam keeps the declaration, both registers and the gate together on frame A, so no reminder is needed on frame B. **The `T7-L-R4` post-authority reminder band is removed** as obsolete production mitigation — see §13.9 |

**Nothing else is repeated.** No large text block is duplicated without the `G7`
reason stated above.

### 13.7 Physical-frame specifications — Slides 6 and 11

**Both remain inside the Slides 5–11 logical domain family.** The family now has a
**single-frame variant** (Slides 5, 7, 8, 9, 10) and a **governed two-frame
pagination variant** (logical 6 and 11). **There are not eight unrelated
layouts**, and no domain slide is independently redesigned.

#### `M07-S06-A` — physical 6

| Field | Value |
|---|---|
| Logical parent | **logical Slide 6 · `M07-S06` · `M7V-06`** |
| Title | **Domain 2: Roles and authority** — verbatim · `PART 1 OF 2` |
| Carries | **Three co-equal Domain 2 cards** — `TDR-004`, `TDR-005`, `TDR-006`; `function:` and `holder: NOT YET ESTABLISHED` on each; evidence kinds; evidence position; `classification:`; `status:` · **family boundary strip, verbatim** |
| Geometry — **hardened by `T7-L-R5`** | Cards `x = 48–328`, `340–620`, `632–912`, `y = 84–452` — **each exactly 280 × 368 pt, two gaps of exactly 12 pt** (`3 × 280 + 2 × 12 = 864`). Boundary strip `x = 48–912`, `y = 460–520` — **60 pt**, one visible border. Lowest edge `520 ≤ 520` ✓ |
| Zones | **`Z1 = 123` · `Z2 = 63` · `Z3 = 85` · `Z4 = 85`**, three gaps of `4 pt` — `123 + 63 + 85 + 85 + 12 = 368` ✓ |
| Region margins | **`Z1` need `114.4` → `+8.6`** · `Z2` need `58.4` → `+4.6` · **`Z3` need `76.8` → `+8.2`** · **`Z4` need `76.8` → `+8.2`** · **boundary strip need `51.2` → `+8.8`**. **Every load-bearing region `≥ 8 pt`.** `Z2` carries evidence kinds, which §13.13 does not classify load-bearing; it takes the residual after the four load-bearing regions are satisfied |
| `Z1` worst case | **Card 2 governs.** `function: technical-response ownership` 38 ch @ 18 pt (2 lines) + `holder: NOT YET ESTABLISHED` @ 18 pt (1 line) + `TDR-005 — Who owns each technical response?` 43 ch @ 14 pt (2 lines) = `98.4` + 2 internal gaps + padding = **`114.4`**. Cards 1 and 3 need `76.0` and `92.8`; **co-equality sets all three to the worst case** |
| Connectors | **`0`** |
| Allocation | **1.0 min** — allocated, not measured |
| Production fit | **`PRODUCTION FIT — VERIFIED ON DECLARED BASIS`** · allocated `368 + 8 + 60 = 436` · budget `436` · **min load-bearing region margin `+8.2 pt`**. **The frame's former `+24.0 pt` of unallocated spare has been moved into the text regions**, which is where robustness lives |

#### `M07-S06-B` — physical 7

| Field | Value |
|---|---|
| Logical parent | **logical Slide 6 · `M07-S06` · `M7V-06`** |
| Title | **Domain 2: Roles and authority** — verbatim · `PART 2 OF 2` |
| Carries | **Exclusion strip** (heading verbatim + grouped nouns) · **mandatory programme-bounded holder statement**, verbatim · **family boundary strip**, verbatim |
| Geometry — **hardened by `T7-L-R5`** | Exclusion strip `x = 48–912`, `y = 84–160` — **76 pt** · holder-statement band `y = 168–244` — **76 pt** · boundary strip `y = 252–328` — **76 pt**. **All bands full width, one visible border, `8 pt` inter-band gaps.** Lowest edge `328 ≤ 520` ✓ |
| Region margins | **exclusion need `50.4` → `+25.6`** · **holder statement need `51.2` → `+24.8`** · **boundary need `51.2` → `+24.8`**. **All load-bearing, all `≥ 8 pt`** |
| Connectors | **`0`** |
| Allocation | **0.5 min** — allocated, not measured |
| Production fit | **`PRODUCTION FIT — VERIFIED ON DECLARED BASIS`** · allocated `76 + 76 + 76 + 16 = 244` · budget `436` · **min load-bearing region margin `+24.8 pt`**, frame reserve `+192.0` |

**The large margin on 6B is deliberate and is not to be filled with prose.**
`P9` forbids adding content; §19 of the increment records that positive margin is
a feature.

#### `M07-S11-A` — physical 12

| Field | Value |
|---|---|
| Logical parent | **logical Slide 11 · `M07-S11` · `M7V-11`** |
| Title | **Domain 7: Publication and acceptance boundary** — verbatim · `PART 1 OF 2` |
| Carries | **Three co-equal Domain 7 cards** — `TDR-019`, `TDR-020` with `holder: NOT YET ESTABLISHED`, `TDR-021` with `classification: METHOD` and its qualifier; evidence kinds; **the four co-equal act cells**; evidence position; `classification:`; `status:` · **family boundary strip, verbatim** |
| Geometry — **hardened by `T7-L-R5`** | Cards `x = 48–328`, `340–620`, `632–912`, `y = 84–454` — **each exactly 280 × 370 pt, two gaps of exactly 12 pt**. Zones **`Z1 = 74` · `Z2 = 101` · `Z3 = 83.5` · `Z4 = 99.5`**, three `4 pt` gaps — `74 + 101 + 83.5 + 99.5 + 12 = 370` ✓. **Act cells inside card 3's `Z2`, unchanged: `x = 652–713`, `717–778`, `782–843`, `847–908`, each exactly 61 pt, three gaps of exactly 4 pt, the 8 pt residual distributed 4 pt to each inset.** Boundary strip `x = 48–912`, `y = 462–520` — **58 pt**. Lowest edge `520 ≤ 520` ✓ |
| Region margins | `Z1` need `67.2` → **`+6.8`** · `Z2` need `94.4` → **`+6.6`** · `Z3` need `76.8` → **`+6.7`** · `Z4` need `92.8` → **`+6.7`** · boundary need `51.2` → **`+6.8`**. **Min `+6.6`. Below the `8 pt` target — this frame is `BOUNDED / TIGHT`**, see §13.12 |
| **`T7-L-R4` arithmetic corrected** | `T7-L-R4` recorded `Z1` need as `84.0` by **blending card 3's longest question with card 2's holder line**. A zone's height is the **worst single card**, not a blend. Per card: card 1 `41.6`, **card 2 `67.2` (governs)**, card 3 `58.4`. **The corrected need is `67.2`, releasing `16.8 pt`** — which is why every region on this frame improved from `+1.2 … +2.0` to `+6.6 … +6.8` |
| Connectors | **`0` — including zero between the four governance acts, in any direction** |
| Allocation | **1.0 min** — allocated, not measured |
| Production fit | **`PRODUCTION FIT — BOUNDED / TIGHT`** · allocated `370 + 8 + 58 = 436` · budget `436` · **min load-bearing region margin `+6.6 pt`**. **Mathematical maximum uniform slack is `+6.7 pt`** — total need `402.4`, budget `436`, spare `33.6` across five load-bearing regions. **`≥ 8 pt` is not achievable on this frame without altering accepted content.** Reported to governance; see §13.12 |

#### `M07-S11-B` — physical 13

| Field | Value |
|---|---|
| Logical parent | **logical Slide 11 · `M07-S11` · `M7V-11`** |
| Title | **Domain 7: Publication and acceptance boundary** — verbatim · `PART 2 OF 2` |
| Carries | **Programme-bounded publication / exchange authority statement**, verbatim, **explicitly labelled `on TDR-020:`** · **exclusion strip** · **mandatory two-directional statement**, verbatim · **family boundary strip**, verbatim |
| Geometry — **hardened by `T7-L-R5`** | Authority band `x = 48–912`, `y = 84–160` — **76 pt**, labelled `on TDR-020:` · exclusion strip `y = 168–244` — **76 pt** · two-directional band `y = 252–328` — **76 pt** · boundary strip `y = 336–412` — **76 pt**. **`8 pt` inter-band gaps.** Lowest edge `412 ≤ 520` ✓ |
| Region margins | **authority need `51.2` → `+24.8`** · **exclusion need `50.4` → `+25.6`** · **two-directional need `51.2` → `+24.8`** · **boundary need `51.2` → `+24.8`**. **All load-bearing, all `≥ 8 pt`** |
| Connectors | **`0`. No leader, arrow or line joins the authority band to anything** |
| Allocation | **0.5 min** — allocated, not measured |
| Production fit | **`PRODUCTION FIT — VERIFIED ON DECLARED BASIS`** · allocated `76 × 4 + 24 = 328` · budget `436` · **min load-bearing region margin `+24.8 pt`**, frame reserve `+108.0` |

**Neither frame may imply a known Triviron authority holder, and neither may
imply that Triviron lacks one.** The authority band carries the label
`on TDR-020:` so its attribution is unmistakable and cannot read as a deck-wide,
card-1 or card-3 statement.

### 13.8 Physical-frame specifications — Slide 13

**The four semantic states are NOT divided between the pages.** All four
quadrants sit on Frame A. **No pagination-induced ordering is therefore
possible**, which is why the §12.6.1 seam was preferred over any arrangement that
splits the states.

#### `M07-S13-A` — physical 15

| Field | Value |
|---|---|
| Logical parent | **logical Slide 13 · `M07-S13` · `M7V-13`** |
| Title | **Unknowns are controlled work** — verbatim · `PART 1 OF 2` |
| Carries | **All four co-equal semantic-state quadrants** — `NOT YET ESTABLISHED`, `NOT ESTABLISHED`, `UNRESOLVED`, `TBD`, each with its meaning and its own misuse bar **inside its own frame** · **`THESE ARE SEMANTIC STATES, NOT STAGES — no chronological progression exists among them`**, verbatim |
| Geometry — **hardened by `T7-L-R5`** | Quadrants `x = 48–474` and `486–912` (**each exactly 426 pt, one 12 pt gap**, `2 × 426 + 12 = 864`); rows `y = 84–270` and `282–468` — **each exactly 186 pt, one 12 pt gap** (`2 × 186 + 12 = 384`). Non-progression band `x = 48–912`, `y = 476–520` — **44 pt**. Lowest edge `520 ≤ 520` ✓ |
| Region margins | **Co-equal quadrant need `157.6`** (worst case: the `NOT ESTABLISHED` and `TBD` misuse bars at four 18 pt lines) **→ `+28.4` each** · **non-progression band need `29.6` → `+14.4`**. **All load-bearing, all `≥ 8 pt`.** **All four quadrants remain pixel-identical** |
| Connectors | **`0`.** No arrow, no numbering, no first/last treatment, no ordering marker |
| Allocation | **0.8 min** — allocated, not measured |
| Production fit | **`PRODUCTION FIT — VERIFIED ON DECLARED BASIS`** · allocated `384 + 8 + 44 = 436` · budget `436` · **min load-bearing region margin `+14.4 pt`** |

#### `M07-S13-B` — physical 16

| Field | Value |
|---|---|
| Logical parent | **logical Slide 13 · `M07-S13` · `M7V-13`** |
| Title | **Unknowns are controlled work** — verbatim · `PART 2 OF 2` |
| Carries | **`CURRENT STATUS POSITION`** band — the 21-row status census · **`EVIDENCE AVAILABILITY`** band — `NONE IDENTIFIED`, its field-8 definition, `NONE IDENTIFIED ≠ NONE EXISTS`, and the not-a-status line · **misuse-warning strip**, all four entries |
| Geometry — **hardened by `T7-L-R5`** | Status band `x = 48–912`, `y = 84–190` — **106 pt**, own border, labelled · evidence band `y = 198–376` — **178 pt**, own border, labelled · misuse strip `y = 384–520` — **136 pt**, own border. **`8 pt` inter-band gaps.** Lowest edge `520 ≤ 520` ✓ |
| Region margins | **`CURRENT STATUS POSITION` need `76.8` → `+29.2`** · **`EVIDENCE AVAILABILITY` need `148.8` → `+29.2`** · **misuse strip need `106.4` → `+29.6`**. **All load-bearing, all `≥ 8 pt`** |
| Connectors | **`0`.** The two bands are **independently labelled and explicitly separated**; nothing joins them, and neither is placed on an axis with the other |
| Allocation | **0.6 min** — allocated, not measured |
| Production fit | **`PRODUCTION FIT — VERIFIED ON DECLARED BASIS`** · allocated `106 + 178 + 136 + 16 = 436` · budget `436` · **min load-bearing region margin `+29.2 pt`** |

**`status ≠ evidence availability` is carried structurally** by two separately
bordered, separately labelled bands — **`CURRENT STATUS POSITION`** and
**`EVIDENCE AVAILABILITY`** — with no shared axis, ramp, legend or numbering.
**`NONE IDENTIFIED` is never a fifth quadrant and never a status.** **No
classification vocabulary appears on either frame of logical Slide 13.**

### 13.9 Physical-frame specifications — Slide 14 · the `workflow | close` seam

> **`T7-L-R5` — SEAM CORRECTED ON GOVERNANCE DECISION.** `T7-L-R4` implemented an
> **authority-gate seam** (frame A ending at the gate, Register 2 opening frame
> B) and reported the §12.6.1 prose/table contradiction that produced it.
> **ChatGPT has decided in favour of the `workflow | close` seam.** The
> authority-gate seam is **superseded**.
>
> **Frame A now carries the entire governed workflow core** —
> `Register 1` → `AUTHORITY REQUIRED — no automatic progression` → `Register 2` —
> so the gate and the conditional post-authority stages **remain visible
> together**. **The page turn therefore cannot be read as progression across
> authority**, because the page turn happens only after the whole workflow core
> has been shown. **Frame B is the supporting close.**
>
> **This arrangement is governance-superior and carries substantially more
> production slack**: every load-bearing region on both frames now exceeds
> `+23 pt`, against the superseded seam's `+0.4 pt` worst band.

#### `M07-S14-A` — physical 17 · the workflow core

| Field | Value |
|---|---|
| Logical parent | **logical Slide 14 · `M07-S14` · `M7V-14`** |
| Title | **From decision backlog to BEP workshop** — verbatim · `PART 1 OF 2` |
| Carries | **Header declaration, both semantic statements, three physical lines, verbatim** · **Register 1** — `decision backlog`, `evidence gathering`, `decision agenda`, `appropriate authority engaged` · **the authority gate**, carrying `AUTHORITY REQUIRED — no automatic progression` and `evidence ≠ authority · no appropriate Triviron authority holder is currently identified or established in this programme` · **Register 2** — `candidate decision, if authorised`, `decision recorded with status`, `BEP / matrix / schedule / appendix populated only when earned` |
| Geometry — **`T7-L-R5`** | Header `x = 48–912`, `y = 84–184` — **exactly 100 pt** · Register 1 `y = 192–268`, four boxes `x = 48–249`, `269–470`, `490–691`, `711–912` — **each exactly 201 × 76 pt, three gaps of exactly 20 pt** (`4 × 201 + 3 × 20 = 864`) · **authority gate `x = 48–912`, `y = 276–376` — exactly 100 pt, border ≥ 3 pt, the heaviest object on the frame** · Register 2 `y = 384–480`, three boxes `x = 48–324`, `342–618`, `636–912` — **each exactly 276 × 96 pt, two gaps of exactly 18 pt** (`3 × 276 + 2 × 18 = 864`). **All three inter-band gaps exactly `8 pt`.** Vertical: `100 + 8 + 76 + 8 + 100 + 8 + 96 = 396`; lowest edge `480 ≤ 520` ✓ |
| Region margins | **header need `72.8` → `+27.2`** · **Register 1 need `51.2` → `+24.8`** · **authority gate need `76.8` → `+23.2`** · **Register 2 need `72.8` → `+23.2`**. **All load-bearing, all `≥ 8 pt`**, frame reserve `+40.0` |
| Connectors | **`4` — all four of logical Slide 14's connectors.** Three within Register 1 (`1 → 2`, `2 → 3`, `3 → 4`) and one within Register 2 (`5 → 6`). **No connector `4 → 5`. No connector crosses, enters, leaves or passes behind the authority gate. No connector `6 → 7`, and none enters the final controlled-destination box** — it is reached by condition, not by arrow |
| Allocation | **1.0 min** — allocated, not measured. **Rebalanced from `0.8` by `T7-L-R5`**, because this frame now carries the whole workflow core |
| Production fit | **`PRODUCTION FIT — VERIFIED ON DECLARED BASIS`** · allocated `396` · budget `436` · **min load-bearing region margin `+23.2 pt`** |

**The header's `82 pt` band from `T7-L-R4` is enlarged to `100 pt`.** The accepted
`3 × 18 pt = 54 pt inside 64 pt` claim remains superseded: three 18 pt lines
occupy `64.8 pt` of line height plus `8 pt` padding = **`72.8 pt`**. **Wording, the
three physical lines and the semicolon break point are unchanged.**

#### `M07-S14-B` — physical 18 · the supporting close

| Field | Value |
|---|---|
| Logical parent | **logical Slide 14 · `M07-S14` · `M7V-14`** |
| Title | **From decision backlog to BEP workshop** — verbatim · `PART 2 OF 2` |
| Carries | **The complete nine-object method chain**, labelled `analytical sequence — nothing flows along these arrows` · **roadmap close** — the accepted Module 8 teaching handoff · **teaching / workshop boundary strip**, all three entries |
| Geometry — **`T7-L-R5`** | Method chain `x = 48–912`, `y = 84–216` — **132 pt** · roadmap close `y = 224–296`, three segments **each exactly 276 pt**, two gaps of exactly 18 pt, **72 pt** tall · boundary strip `x = 48–912`, `y = 304–520` — **216 pt**. **Both inter-band gaps exactly `8 pt`.** Vertical: `132 + 8 + 72 + 8 + 216 = 436`; lowest edge `520 ≤ 520` ✓ |
| Region margins | **method chain need `98.4` → `+33.6`** · **roadmap close need `41.6` → `+30.4`** · **teaching boundary strip need `145.6` → `+70.4`**. **All load-bearing, all `≥ 8 pt`** |
| Connectors | **`0`.** **No drawn connector anywhere on this frame.** The chain's arrows are **typographic characters in a single text run**, not drawn connectors. Nothing joins the chain, the roadmap close or the boundary strip |
| Allocation | **0.5 min** — allocated, not measured. **Rebalanced from `0.7` by `T7-L-R5`.** Pair sum `1.0 + 0.5 = 1.5` = parent ✓ |
| Production fit | **`PRODUCTION FIT — VERIFIED ON DECLARED BASIS`** · allocated `436` · budget `436` · **min load-bearing region margin `+30.4 pt`** |

**Module 8 remains a future *teaching module* — not an event, not a scheduled
workshop.** The roadmap close names a module, never an occurrence.

#### The `A → B` page turn on logical Slide 14

**It means exactly one thing: `workflow core → supporting explanation and
close`.**

**It does not mean** authority progression · approval · acceptance ·
candidate-decision progression · controlled-destination progression.

**Nothing is drawn between the frames** — no arrow, connector, chevron, bracket,
leader or transition line. **The continuation label is production navigation
only.**

#### Obsolete mitigation removed — `T7-L-R5`

**`T7-L-R4` added a `post-authority reminder band` to frame B:**
`TEACHING WORKFLOW — NOT A CURRENT TRIVIRON WORKFLOW · continued only when
authorised`. **Its sole purpose was to mitigate the authority-seam page turn.**

**That seam no longer exists, so the band is removed.** It is recorded as the
**removal of temporary production mitigation, not of teaching content**:

| Check | Result |
|---|---|
| Was it accepted teaching content? | **No.** It was introduced by `T7-L-R4` as seam mitigation and appears in no accepted teaching source |
| Is any accepted statement lost? | **No.** The **full** declaration `TEACHING WORKFLOW — NOT A CURRENT TRIVIRON WORKFLOW` and `no actual Triviron workshop or schedule is established in this programme; this diagram does not assert or schedule one` sits **complete and verbatim on frame A** |
| Is the authority boundary weakened? | **No.** The **entire** authority gate — `AUTHORITY REQUIRED — no automatic progression` and `evidence ≠ authority` — sits on frame A, **between** the two registers it separates |
| Is the workshop/programme boundary intact? | **Yes**, across the logical unit: the declaration on frame A, the teaching/workshop boundary strip on frame B |

**No other text was removed by `T7-L-R5`.**

### 13.10 Connector census under pagination

**The deck-wide drawn connector total remains exactly `12`. Four extra physical
pages add no connector.**

| Physical # | Logical unit | Connectors |
|---:|---:|---:|
| **1** | 1 | **2** |
| **3** | 3 | **6** |
| **17** | 14 A | **4** — three within Register 1, one within Register 2 (`5 → 6`) |
| **18** | 14 B | **0** |
| all other 15 physical slides | 2, 4–13 | **0 each** |
| | **Total** | **`12`** |

**A continuation or page transition is not a connector.** **`A → B` is never
represented by an arrow, line, bracket, chevron, leader or any other mark.**

### 13.11 Eight-frame production-fit summary — hardened by `T7-L-R5`

| Frame | Phys | Text need | Allocated | Budget | Min **load-bearing region** margin | Conn | Status |
|---|---:|---:|---:|---:|---:|---:|---|
| `M07-S06-A` | 6 | `397.6` | `436` | `436` | **`+8.2`** | **0** | **VERIFIED** |
| `M07-S06-B` | 7 | `168.8` | `244` | `436` | **`+24.8`** | **0** | **VERIFIED** |
| `M07-S11-A` | 12 | `402.4` | `436` | `436` | **`+6.6`** | **0** | **BOUNDED / TIGHT** |
| `M07-S11-B` | 13 | `228.0` | `328` | `436` | **`+24.8`** | **0** | **VERIFIED** |
| `M07-S13-A` | 15 | `364.8` | `436` | `436` | **`+14.4`** | **0** | **VERIFIED** |
| `M07-S13-B` | 16 | `348.0` | `436` | `436` | **`+29.2`** | **0** | **VERIFIED** |
| `M07-S14-A` | 17 | `297.6` | `396` | `436` | **`+23.2`** | **4** | **VERIFIED** |
| `M07-S14-B` | 18 | `301.6` | `436` | `436` | **`+30.4`** | **0** | **VERIFIED** |

**Seven of eight frames reach `≥ 8 pt` on every load-bearing region.**
**`M07-S11-A` reaches `+6.6` against a mathematical maximum of `+6.7` and is
recorded `PRODUCTION FIT — BOUNDED / TIGHT`** — see §13.12.

**Before and after `T7-L-R5`, minimum load-bearing region margin:**

| Frame | `T7-L-R4` | `T7-L-R5` | Change |
|---|---:|---:|---|
| `M07-S06-A` | `+2.2` | **`+8.2`** | **+6.0** |
| `M07-S06-B` | `+4.8` | **`+24.8`** | **+20.0** |
| `M07-S11-A` | `+1.2` | **`+6.6`** | **+5.4** |
| `M07-S11-B` | `+4.8` | **`+24.8`** | **+20.0** |
| `M07-S13-A` | `+2.4` | **`+14.4`** | **+12.0** |
| `M07-S13-B` | `+3.2` | **`+29.2`** | **+26.0** |
| `M07-S14-A` | `+7.2` | **`+23.2`** | **+16.0** |
| `M07-S14-B` | `+0.4` | **`+30.4`** | **+30.0** |

**No content was added, removed or shortened to achieve this.** Every gain comes
from **enlarging existing text containers and governed regions** with capacity the
frames already had, plus the corrected `M07-S11-A` `Z1` arithmetic and the
corrected Slide 14 seam.

### 13.12 `M07-S11-A` — the one bounded frame

**`PRODUCTION FIT — BOUNDED / TIGHT`. Min load-bearing region margin `+6.6 pt`
against the `8 pt` target.**

| | |
|---|---|
| **Total need** | `402.4 pt` — `Z1 67.2` + `Z2 94.4` + `Z3 76.8` + `Z4 92.8` + three `4 pt` zone gaps + boundary `51.2` + one `8 pt` band gap |
| **Budget** | `436 pt` (`y = 84–520`) |
| **Spare** | `33.6 pt` across **five** load-bearing regions |
| **Mathematical maximum uniform slack** | **`+6.72 pt`.** `≥ 8 pt` would require `40 pt` of spare — `6.4 pt` more than the canvas provides |
| **Achieved** | **`+6.6 pt` minimum**, within `0.12 pt` of the theoretical optimum |

**Why nothing further is available.** `Z2` is governed by the **four act cells**:
at `61 pt` wide a cell carries **five characters** per 18 pt line, so
`recipient acceptance` needs four lines (`94.4 pt`). Widening the cells to their
maximum `63 pt`, stacking them vertically (`108.8 pt`) and arranging them 2 × 2
(`98.4 pt`) were all tested — **none improves on `94.4 pt`**. `Z4` is governed by
card 3's `classification: METHOD` + qualifier + `status:`, and **co-equality sets
all three cards to that height**. `Z3`'s two mandatory lines and the boundary
strip's verbatim sentence are fixed. **The four acts may not be collapsed, the
cards may not be narrowed, and co-equality may not be broken.**

**What a producer does.** **`STOP AND REFER BACK`** — governed by rule `D6` and
the `STOP AND REFER BACK` rule. **Never shrink type, condense a font, reduce
character spacing, reduce line spacing, narrow a card or break co-equality.**
`+6.6 pt` is roughly a third of one 18 pt line, so a font materially wider or
taller than the §1.1 declared basis will not fit — **and that is a referral, not a
production decision.**

**Governance position — `T7-L-R6`.** ChatGPT has **expressly accepted** this
bounded exception as **`BOUNDED / TIGHT — ACCEPTED FOR FABRICATION SUBJECT TO
RENDERED-MEASUREMENT GATE`**, on the basis that the `6.4 pt` shortfall is
arithmetic, the alternative four-act layouts are worse, accepted content is not to
be shortened, a third physical frame is not justified for the remaining
planning-margin difference, and **rendered measurement is the final production
gate**.

**Acceptance is conditional and is not a pass.** The built frame must still show
**AutoFit off · every visible run `≥ 14 pt` · every principal, status,
classification and governance-boundary run `≥ 18 pt` · no overflow · no clipping ·
no text reduction**. **If actual metrics do not fit — `STOP AND REFER BACK`.**

### 13.13 Production-robustness criterion — `T7-L-R5`

**`T7-L-R4` treated any positive margin as sufficient. That was too fragile**,
because the §1.1 basis is a **planning convention, not measured PowerPoint font
geometry**. A region planned at `+0.4 pt` has no tolerance for a real font that is
one percent wider.

| Rule | Requirement |
|---|---|
| **R1** | **Every load-bearing region carries `≥ 8 pt` planned vertical slack** on the declared basis, wherever the frame's existing unused capacity makes this achievable |
| **R2** | **Spare capacity is used only to enlarge existing text containers and governed regions.** **Never to add content.** A frame may remain visually sparse — **sparse is acceptable** |
| **R3** | **A whole-frame margin never substitutes for a region margin.** Every region is reported individually, so a weak region cannot hide inside a healthy frame |
| **R4** | A frame reads **`PRODUCTION FIT — VERIFIED ON DECLARED BASIS`** only if **every** required run meets its type floor, **every** load-bearing region has positive slack, the robustness audit is recorded, and **no avoidable sub-`8 pt` region remains where unused capacity could have solved it** |
| **R5** | A region below `8 pt` for a **genuine** constraint makes its frame **`PRODUCTION FIT — BOUNDED / TIGHT`**, reported to governance. **It is never silently called fully verified** |
| **R6** | **The declared basis of §1.1 is unchanged and may not be adjusted to improve a calculated margin.** Line height `1.2 ×`, character advance `0.5 ×`, padding `8 pt` per axis, line spacing `≥ 1.0`, no condensation, no reduced character spacing. **The objective is better geometry against the same basis** |

#### What counts as a load-bearing region

Any zone or band carrying: a `TDR-` question · `function:` · `holder:` · an
evidence position · `NONE IDENTIFIED ≠ NONE EXISTS` · a classification · a status
· an exclusion heading · a programme-bounded statement · a boundary strip · a
semantic-state definition · a misuse warning · `CURRENT STATUS POSITION` ·
`EVIDENCE AVAILABILITY` · the Slide 14 declaration · the authority gate · a
Register stage · the method chain · the roadmap close · the teaching-synthesis /
workshop boundary.

**One region in the deck falls outside this list:** `M07-S06-A`'s **`Z2`
evidence-kind** zone, at `+4.6 pt`. It carries evidence **kinds** at 14 pt — not a
question, position, classification, status or boundary — and it takes the residual
after the frame's four load-bearing regions are satisfied at `≥ 8 pt`. **It is
reported here rather than omitted.**

#### Planned margin is not the final check

**`≥ 8 pt` planned slack is a design check on a declared convention. It is not a
measurement.** The final production check is **measurement of the rendered
PowerPoint** — see [`production-checklist.md`](production-checklist.md) §4 and
[`review-checklist.md`](review-checklist.md) §8. **A producer whose real metrics
exceed a governed container STOPS and refers back.**
