# Module 7 — Deck Specification

**`MODULE 7 PRESENTATION ASSEMBLY PACKAGE — UNDER GOVERNED CORRECTION (T7-L-R2)`** ·
**`T7-L — ACCEPTED after T7-L-R`** ·
**`T7-L-R2 — PENDING CHATGPT GOVERNANCE REVIEW`**

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

---

## 1. Global details

| Field | Value |
|---|---|
| Format | **16:9 presentation** |
| Reference geometry | **`960 × 540 pt`** — origin top left; `x` right, `y` down |
| Title zone | **`y = 0–72` reserved.** No content beneath the title baseline |
| Side margins | **≥ 48 pt** — content span exactly **864 pt**, `x = 48–912` |
| Lowest permitted object edge | **`y ≤ 520`** |
| Slides | **Fourteen** |
| Total time | **`20.0 minutes allocated — not measured`** |
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

**Titles are exact. A producer may not shorten, retitle or "improve" one.**

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
| 10 | **Geometry — accepted `T7-J-R2` reconciliation, used exactly** | **Header `x = 48–912`, `y = 84–148` (exactly 64 pt)** · register 1 `y = 156–224`, four boxes **each exactly 201 × 68 pt**, three **20 pt** gaps · **authority gate `y = 232–272` (exactly 40 pt, border ≥ 3 pt)** · register 2 `y = 280–348`, three boxes **each exactly 276 × 68 pt**, two **18 pt** gaps · method one-liner `y = 356–412` · roadmap close `y = 420–464`, three segments **each exactly 276 pt** · boundary strip `y = 472–520`. **All six inter-band gaps exactly 8 pt.** Vertical: `64 + 8 + 68 + 8 + 40 + 8 + 68 + 8 + 56 + 8 + 44 + 8 + 48 = 436 = 520 − 84`. Title zone `y = 0–72` reserved, **12 pt clear interval** to the header |
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
| **P9** | Add no slide, no appendix, no agenda slide, no thank-you slide and no contact slide |
| **P10** | Add no logo, footer branding, page furniture or date stamp |

## 10. Production-state summary

| Field | Value |
|---|---|
| Package | **`UNDER GOVERNED CORRECTION — T7-L-R2 PENDING CHATGPT GOVERNANCE REVIEW`** |
| `T7-L` | **`ACCEPTED after T7-L-R`** |
| `T7-L0` | **`ACCEPTED`** |
| Slides specified | **14 of 14** |
| Slides feasible at the accepted type floors | **10 of 14** — Slides 1, 2, 3, 4, 5, 7, 8, 9, 10, 12 |
| Slides **unresolved** at the accepted type floors | **4 of 14** — Slides **6, 11, 13, 14**. See §11 |
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
