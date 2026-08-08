# Module 7 — Production Checklist

**`MODULE 7 PRESENTATION ASSEMBLY PACKAGE — UNDER GOVERNED CORRECTION`** ·
**`T7-L — ACCEPTED after T7-L-R`** · **`T7-L-R2 — ACCEPTED`** ·
**`T7-L-R3 — PENDING CHATGPT GOVERNANCE REVIEW`**

**`TEACHING PRODUCTION HANDOFF — NOT TRIVIRON GOVERNANCE`**

**Teaching material. Not governance. Not the PowerPoint.**

> **This is the build instrument.** Work top to bottom. **A box that cannot be
> ticked honestly is a `STOP AND REFER BACK`, not a box to leave blank.**

> ### `T7-M-R1` IS NOT AUTHORISED
>
> **Do not begin a new PowerPoint build from this checklist yet.** The `T7-M`
> fabrication reached `7.8 pt` minimum type with **146** runs below `14 pt` and
> correctly stopped at QC. **Four slides — 6, 11, 13 and 14 — remain unresolved
> at the accepted type floors** after `T7-L-R2`'s copy reconciliation. See
> [`deck-specification.md`](deck-specification.md) **§11**.
>
> **A producer reaching this checklist before those four slides are resolved by a
> governed geometry increment must STOP.** The correct response to an unresolved
> slide is **refer back**, never smaller type.
>
> **`T7-L-R3` attempted that geometry increment and did not succeed.** Slides 6,
> 11, 13 and 14 remain **`UNRESOLVED`** at deficits of `75`–`230 pt`. **They are
> not buildable at the type floors in any arrangement of the accepted visual
> concepts**, and Slide 13's mandatory `18 pt` text alone exceeds the canvas.
> **No coordinate in §3 has changed.** Build **nothing** on those four slides
> until a governed increment resolves them — see
> [`deck-specification.md`](deck-specification.md) **§12**.

---

## 0. The `STOP AND REFER BACK` rule

**Stop building and refer the matter back to governance — do not proceed, do not
improvise — whenever implementing accepted copy or geometry would require you
to:**

- [ ] shrink any type below the accepted floor (14 pt visible; **18 pt** for any
      status, classification or governance-boundary word);
- [ ] condense a font, reduce character spacing, or reduce line spacing below
      1.0 to force a fit;
- [ ] change the meaning, order or wording of accepted copy;
- [ ] move, shorten, relocate or restyle a governance boundary;
- [ ] add a connector the specification does not list;
- [ ] invent content, a value, a holder, a date or an example;
- [ ] import an external asset of any kind;
- [ ] adjust an accepted coordinate, span, gap or equality.

**A defect found in an accepted upstream layer is reported, never repaired here.**

---

## 1. Before building

- [ ] Read [`README.md`](README.md), then [`deck-specification.md`](deck-specification.md).
- [ ] Confirm the accepted upstream layers are the ones cited: teaching baseline
      `ACCEPTED`, visual specification `ACCEPTED after T7-J-R + T7-J-R2`, visual
      sources `ACCEPTED under T7-K`.
- [ ] Confirm **no rendered asset exists** and none is required.
- [ ] Confirm **no `.pptx` is to be committed to this repository**.
- [ ] Set the presentation to **16:9** at the **`960 × 540 pt`** reference
      geometry.
- [ ] Establish the reserved title zone **`y = 0–72`** and side margins **≥ 48
      pt** (content span exactly **864 pt**).
- [ ] Set the type floor: **14 pt visible, 18 pt for status, classification and
      boundary words**.
- [ ] Read the **declared typographic basis** in
      [`deck-specification.md`](deck-specification.md) **§1.1**: line height
      **`1.2 ×`** point size, character advance **`0.5 ×`** point size, text-box
      padding **`8 pt`** per axis.
- [ ] **Measure your actual font metrics against that basis.** If your line
      height or character advance is **larger** than declared, **STOP AND REFER
      BACK** — you may not compensate by reducing type.
- [ ] Read [`deck-specification.md`](deck-specification.md) **§11** and **§12**
      and confirm which slides are recorded **feasible** and which are recorded
      **unresolved**. **Do not build an unresolved slide.**
- [ ] Confirm the four slides recorded **`UNRESOLVED`** — **6, 11, 13, 14** —
      have been resolved by a governed increment **that changed their geometry or
      their governing controls**. **`T7-L-R3` did not resolve them and changed no
      coordinate**, so if no later increment has, **STOP: the deck cannot be
      built.**
- [ ] Confirm, for every slide you do build, that its region geometry carries
      **both** claims: **coordinate arithmetic verified** *and* **production fit
      verified with positive margin**. **Coordinate arithmetic alone is not
      feasibility** — that misreading is what produced the `7.8 pt` deck. See
      [`deck-specification.md`](deck-specification.md) **§12.7**.
- [ ] Run the **`G9` text-fit self-check** of
      [`../visual-demonstration-plan.md`](../visual-demonstration-plan.md) §2.3
      on every region before drawing it: worst-case string, chars per line, lines
      required, text height, region height, **remaining margin ≥ 8 pt where
      reasonably possible and never negative**.

## 2. Global build checks

- [ ] **Fourteen slides.** No fifteenth. No appendix, agenda, thank-you or
      contact slide.
- [ ] **Titles exact**, in order, matching [`slide-copy.md`](slide-copy.md).
- [ ] **Timing metadata records allocations only** — `20.0 minutes allocated —
      not measured`. Nothing describes the deck as verified, rehearsed, tested or
      final.
- [ ] Per-slide allocations sum to **20.0**: `1.0 + 1.3 + 1.5 + 1.3 + 1.5 + 1.5 +
      1.5 + 1.5 + 1.5 + 1.5 + 1.5 + 1.5 + 1.4 + 1.5`.
- [ ] **Manual advancement only.** No automatic slide-transition timing anywhere
      in the file.
- [ ] **Slide-copy fidelity:** every verbatim string in `slide-copy.md` §4
      appears exactly, unshortened and unsplit.
- [ ] **One-to-one mapping:** every slide carries exactly one visual, matching
      `Slide n → M7V-nn → M07-Snn`.
- [ ] **Native editable objects only** — text boxes, rectangles, shapes, lines,
      connectors, tables, borders, fills.
- [ ] **No import of any kind:** no PNG, JPG, SVG, screenshot, logo, icon,
      rasterised text, SmartArt, Mermaid, auto-layout, network asset, video or
      audio.
- [ ] **Geometry reproduced exactly** from the deck specification; every stated
      span, equality and gap verified by measurement.
- [ ] **Typography:** contrast ≥ 4.5 : 1 text, ≥ 3 : 1 lines, borders and
      connectors.
- [ ] **Accessibility:** logical reading order set per slide; alternative text
      taken from the accepted source screen-reader descriptions, not invented.
- [ ] **No colour-only semantics** anywhere in the deck.
- [ ] **Connector count across the whole deck is exactly 12** — 2 on Slide 1, 6
      on Slide 3, 4 on Slide 14, **zero on the other eleven slides** — and every
      connector's meaning is expressible in one sentence.
- [ ] **Typed absence is neutral everywhere:** no zero, absence or unknown styled
      as failure, deficiency, negative score, rejected state, red alarm, empty
      progress, grey, dashes, strike-through, cross or unticked box.
- [ ] **`TBD` appears against no Triviron matter** anywhere in the deck.
- [ ] **Classification and status are never merged** — no shared axis, strip,
      ramp, legend, colour scale or numbering; each independently labelled
      wherever both appear.
- [ ] **`ESTABLISHED` is never styled as a destination, endpoint, goal or
      terminus** in either vocabulary.
- [ ] **Every STOP boundary and boundary strip is a principal object** at ≥ 18
      pt — never a footnote, footer, caption or small print.
- [ ] **No unsupported Triviron fact** anywhere: no answer, role, holder,
      authority, organisation, platform, container, tolerance, numeric value,
      taxonomy, status model, date, schedule or workshop **may be presented as an
      established, current or known Triviron arrangement**.
- [ ] **Accepted questions, evidence requirements, exclusions, typed absences and
      governance-warning references to those concepts are permitted and must
      remain where specified.** Deleting one because it contains a listed word is
      itself a defect — the test is presentation as fact, not lexical
      appearance.
- [ ] **No hidden or visually weakened warning:** every governance line is
      legible at projection size.
- [ ] No footer branding, page furniture, date stamp or logo.

## 3. Slide-by-slide build checks

### Slide 1 — Where we are: Harrismith → Triviron · 1.0

- [ ] Three segments, **each exactly 276 × 140 pt**, gaps **exactly 18 pt**
      (`3 × 276 + 2 × 18 = 864`); `y = 150–290`.
- [ ] Framing line `y = 310–370`; boundary strip `y = 396–480`, bordered, all
      three entries at ≥ 18 pt.
- [ ] **Exactly 2 connectors**, each labelled `teaching-programme sequence`.
- [ ] **No arrow leaves segment 3.**
- [ ] No date, calendar, timeline, milestone, percentage, tick, person,
      organisation, logo or platform name.

### Slide 2 — Translate the method, not the answers · 1.3

- [ ] Columns **each exactly 416 × 340 pt**, `x = 48–464` and `496–912`,
      `y = 96–436`; channel **exactly 32 pt**.
- [ ] **The channel contains nothing** — no line, rule, divider, shape or text.
- [ ] **`connector count = 0`.** Verify by counting connector objects: the answer
      must be zero.
- [ ] Columns identical in width, height, border, fill and type.
- [ ] Item lists are **not** aligned or padded to pair across the channel.
- [ ] Boundary strip `y = 452–516`, all four entries, `TEACHING SYNTHESIS`
      labelled in words.

### Slide 3 — The translation chain · 1.5

- [ ] Both rows: four boxes **each exactly 201 × 80 pt**, three gaps **exactly 20
      pt** (`4 × 201 + 3 × 20 = 864`); upper `y = 96–176`, lower `y = 306–386`.
- [ ] **STOP band `y = 196–286`, exactly 90 pt, border ≥ 3 pt, largest type on
      the slide.**
- [ ] Vertical check: `80 + 20 + 90 + 20 + 80 = 290 = 386 − 96`.
- [ ] **Exactly 6 connectors**, three within each row.
- [ ] **No connector crosses, enters, leaves or passes behind the STOP band.**
- [ ] **The upper row's last step does not connect to the lower row's first.**
- [ ] **No loop, no closed cycle, no connector touching the panel.**
- [ ] Lower row is **not** greyed, faded or dashed; it carries `not reached`.
- [ ] Panel `y = 406–500` with all seven entries, including
      `NONE IDENTIFIED ≠ NONE EXISTS` **inside the panel frame**.

### Slide 4 — The decision backlog · 1.3

- [ ] Grid `y = 96–376`: label column **exactly 216 pt**, three question columns
      **each exactly 208 pt**, three gaps **exactly 8 pt**
      (`216 + 8 + 208 + 8 + 208 + 8 + 208 = 864`).
- [ ] **Seven rows of exactly 40 pt** (`7 × 40 = 280 = 376 − 96`).
- [ ] All 21 cells populated with identifier + 3–6 word topic. **No blank, merged
      or spanned cell. No answer.**
- [ ] Classification strip `y = 396–444`: **five separate rectangles, not a
      table**, each exactly 168 pt, four gaps exactly 6 pt
      (`5 × 168 + 4 × 6 = 864`).
- [ ] **The three zero cells are identical to the two in-use cells** in size,
      border, fill and type — no grey, dash, opacity, strike-through or cross.
- [ ] Each zero carries `prerequisite evidence not identified`.
- [ ] `enumeration order — not progression` sits **inside the strip frame**.
- [ ] Panel `y = 460–516` with all six entries; **status appears once, on its own
      line, separate from the strip**.
- [ ] **No connector anywhere.**

### Slides 5–11 — domain family, common checks

**Apply all of these to each of the seven slides:**

- [ ] Three cards **each exactly 280 pt wide**, two gaps **exactly 12 pt**
      (`3 × 280 + 2 × 12 = 864`), `x = 48–328`, `340–620`, `632–912`.
- [ ] Standard family (Slides 5, 6, 7, 9, 11): cards `y = 96–392`; zones
      54 / 94 / 54 / 82 with three 4 pt gaps (`= 296`); strips `y = 408–460` and
      `472–516`.
- [ ] Variant family (Slides 8, 10): cards `y = 96–372`; zones
      54 / 84 / 54 / 72 with three 4 pt gaps (`= 276`); block `y = 388–464`;
      strip `y = 476–516`.
- [ ] **Cards identical** in width, height, border, fill and type. **No card
      emphasised or styled as nearer an answer.**
- [ ] Zone 1 carries the `TDR-` identifier and the question **as a question**.
- [ ] Zone 2 carries **evidence kinds only** — no named document, platform or
      organisation; **no structural artefact is drawn**.
- [ ] Zone 3 on every card: `Triviron evidence currently available: NONE
      IDENTIFIED` and `NONE IDENTIFIED ≠ NONE EXISTS`.
- [ ] Zone 4 on every card: **two separately labelled lines** — `classification:`
      and `status: NOT YET ESTABLISHED`.
- [ ] `METHOD` appears **only** on Slide 7 (`TDR-009`), Slide 9 (`TDR-013`) and
      Slide 11 (`TDR-021`), each **with its qualifier**, as a word — never a
      ribbon, star, tick, highlight, rank or score.
- [ ] Exclusion strip heading `Does not transfer as an answer`.
- [ ] Boundary strip verbatim: `These are questions Triviron must answer for
      itself. No answer on this slide is Triviron's, and none is proposed.`
- [ ] **Connector count = 0.** Zero means zero.
- [ ] No card carries a fabricated Triviron answer.

### Slide 5 — Domain 1 · 1.5

- [ ] `TDR-001`–`TDR-003` questions verbatim.
- [ ] **No arrow from card 1 to card 2 to card 3.**
- [ ] **No document hierarchy drawn** from `TDR-002`'s zone 2.
- [ ] Variance line present: `both recorded, neither rewritten`.

### Slide 6 — Domain 2 · 1.5

- [ ] Zone 1 split into **two equal 25 pt lines** with a 4 pt gap
      (`25 + 4 + 25 = 54`): `function:` then `holder:`.
- [ ] `holder: NOT YET ESTABLISHED` on **each** of the three cards.
- [ ] **The holder line is the same weight as the function line** — not smaller,
      fainter or parenthetical.
- [ ] **No organisation chart, hierarchy, reporting line, tree, swimlane, seat,
      silhouette, avatar, RACI or `X`-allocation grid.**
- [ ] **No line joins any two objects.** Count lines: the answer must be zero.
- [ ] `organisation chart` appears **only as words in zone 2**, never drawn.
- [ ] Mandatory holder statement present.

### Slide 7 — Domain 3 · 1.5

- [ ] `METHOD` on `TDR-009` with `reusable structural distinction — not evidence
      of Triviron adoption`.
- [ ] **No container, folder, topology, CDE area, platform name, discipline set,
      federated-model graphic, lens, funnel, stack or assembly arrow.**
- [ ] Mandatory platform statement present.
- [ ] The `METHOD` card is **identical** to its neighbours in size, border and
      fill.

### Slide 8 — Domain 4 · 1.5

- [ ] Variant geometry; **exclusion block `y = 388–464`, 76 pt, bordered, type ≥
      18 pt**.
- [ ] The exclusion block is **a bordered rectangle, not a table**.
- [ ] All four exclusion items present, with the verbatim heading; **the twelve
      checks are one item and are not listed**.
- [ ] **Search the slide for digits.** Only `CI-01`–`CI-12` and `TDR-` numbers
      may appear. **Any other digit is a STOP.**
- [ ] No starter check table, sample row, interface matrix, pass/fail treatment
      or red/green.
- [ ] No chain drawn from interface to check to rule to approval.
- [ ] `holder: NOT YET ESTABLISHED` on `TDR-012`.

### Slide 9 — Domain 5 · 1.5

- [ ] `METHOD` on `TDR-013` with its full qualifier.
- [ ] **No status set, status sequence, chip, badge, dot or traffic light.**
- [ ] **No arrow from finding to Issue**, from detection to creation, or between
      status words.
- [ ] No Issue example, identifier, numbering scheme, `Accepted condition`,
      `Deferred` or `Escalated`.
- [ ] Neither Harrismith Issue definition is quoted.
- [ ] Mandatory taxonomy statement present.

### Slide 10 — Domain 6 · 1.5

- [ ] Variant geometry; **fence `y = 388–464`, border weight visibly different
      from the card borders**.
- [ ] **Fence heading verbatim and inside the fence's own border:**
      `HARRISMITH EVIDENCE ABOUT HARRISMITH — NOT TRIVIRON EVIDENCE`.
- [ ] All four fence content lines present.
- [ ] **No connector enters or leaves the fence. No line joins the fence to a
      card.**
- [ ] `GCR-006` and the partial-trace status appear **nowhere outside the fence**.
- [ ] **No cycle drawn.** No checklist, tick, completion percentage or
      closed-loop graphic.

### Slide 11 — Domain 7 · 1.5

- [ ] `METHOD` on `TDR-021` with `reusability is not adoption`.
- [ ] Four act cells **each exactly 61 pt**, three gaps **exactly 4 pt**, at
      `x = 652–713`, `717–778`, `782–843`, `847–908`; the **8 pt residual
      distributed 4 pt to each inset, never rounded into a cell**.
- [ ] **Zero connectors between the four act cells**, in any direction.
- [ ] `holder: NOT YET ESTABLISHED` on `TDR-020`, with the **programme-bounded
      authority statement adjacent to it**, verbatim.
- [ ] Mandatory two-directional statement present.
- [ ] **No authority holder, named authoriser, job title, approval chain, gate,
      signature or stamp.**

### Slide 12 — What the evidence lets you say · 1.5

- [ ] Upper three cards **each exactly 200 × 112 pt**, gaps **exactly 132 pt**
      (`3 × 200 + 2 × 132 = 864`), `y = 88–200`.
- [ ] Lower two cards **each exactly 200 × 112 pt** at `x = 214–414` and
      `546–746`, `y = 344–456`.
- [ ] **Verify the offset: no lower card shares an `x` range with an upper
      card.**
- [ ] Hub `x = 288–672` (centred on 480), `y = 224–320`; 24 pt clear above and
      below.
- [ ] Vertical check: `112 + 24 + 96 + 24 + 112 = 368 = 456 − 88`.
- [ ] **All five cards pixel-identical but for their text.**
- [ ] Each zero card carries `prerequisite not satisfied — not a stage awaiting
      arrival` **in its own frame**.
- [ ] **No arrow, spoke, ring, numbering, ramp, staircase, timeline, funnel or
      pyramid.**
- [ ] `ESTABLISHED` is **not** in a terminal position.
- [ ] Foot strip `y = 476–520` with all three entries.

### Slide 13 — Unknowns are controlled work · 1.4

- [ ] Quadrants **each exactly 426 × 114 pt**: columns `x = 48–474` and `486–912`
      with a 12 pt gap (`2 × 426 + 12 = 864`); rows `y = 96–210` and `222–336`
      with a 12 pt gap (`2 × 114 + 12 = 240`).
- [ ] **Each quadrant carries both its meaning and its own misuse bar, inside its
      own frame.** No misuse bar has migrated to the strip.
- [ ] Separating rule at `y = 352`, full width, ≥ 2 pt — **drawn as a boundary,
      not a connector**.
- [ ] Evidence-position panel `y = 368–440`, carrying `NONE IDENTIFIED`,
      `NONE IDENTIFIED ≠ NONE EXISTS` and the not-a-status line.
- [ ] Misuse-warning strip `y = 456–516` with all four entries.
- [ ] **No arrow, numbering, ordering marker, ramp, severity scale, timeline or
      staircase.**
- [ ] **No `TBD` and no `NOT ESTABLISHED` applied to any Triviron matter.**
- [ ] **No fifth quadrant. No classification word.**

### Slide 14 — From decision backlog to BEP workshop · 1.5

- [ ] **Header `x = 48–912`, `y = 84–148`, exactly 64 pt**; 12 pt clear from the
      reserved title zone.
- [ ] **Both semantic statements present, verbatim, across the three authorised
      physical lines, breaking only at the semicolon.**
- [ ] Header typography: **≥ 18 pt, single (1.0) line spacing, no paragraph
      spacing, no condensation, no reduced character spacing.** Nominal fit
      `3 × 18 = 54 pt` inside 64 pt. **If it does not fit, STOP.**
- [ ] Register 1 `y = 156–224`: four boxes **each exactly 201 × 68 pt**, three
      gaps **exactly 20 pt**.
- [ ] **Authority gate `y = 232–272`, exactly 40 pt, border ≥ 3 pt.**
- [ ] Register 2 `y = 280–348`: three boxes **each exactly 276 × 68 pt**, two
      gaps **exactly 18 pt**.
- [ ] Method one-liner `y = 356–412`; roadmap close `y = 420–464`; boundary strip
      `y = 472–520`.
- [ ] **All six inter-band gaps exactly 8 pt.**
- [ ] Vertical check: `64 + 8 + 68 + 8 + 40 + 8 + 68 + 8 + 56 + 8 + 44 + 8 + 48 =
      436 = 520 − 84`.
- [ ] **Exactly 4 connectors** — three in register 1, one from stage 5 to 6.
- [ ] **No connector crosses, enters, leaves or passes behind the authority
      gate.**
- [ ] **No connector enters the final box.** Box 7 carries `only when earned`
      inside itself.
- [ ] Method one-liner **complete, all nine objects**, arrows as typographic
      characters in one text run, labelled as an analytical sequence.
- [ ] Register 2 is **not** greyed, blocked or styled as unavailable.
- [ ] **No meeting room, calendar, date, participant, seat, table, agenda,
      scheduled event, clock or duration.**

## 4. Type-floor verification — mandatory, measured

**This section is the instrument that the `T7-M` build lacked. It is not a
judgement; it is a measurement.**

- [ ] **Enumerate every explicit text run in the file** — every text box, table
      cell, shape label and connector label, on all fourteen slides.
- [ ] **Record the explicit point size of each run.** A run with an inherited or
      theme-derived size is resolved to its **effective** size and recorded.
- [ ] **`minimum explicit type >= 14 pt`.** Compute the minimum across the whole
      deck and write it down. **If the figure is below `14 pt`, production review
      fails — there is no discretion.**
- [ ] **`all principal / status / classification / governance-boundary text >= 18
      pt`.** Enumerate those runs specifically — every `classification:` line,
      every `status:` line, every `holder:` line, every `NONE IDENTIFIED`, every
      `NOT YET ESTABLISHED`, every STOP band, gate strip, fence heading, boundary
      strip, exclusion-strip heading and mandatory programme-bounded statement —
      and confirm each is **`≥ 18 pt`**. **Any one below `18 pt` fails production
      review.**
- [ ] **Count the runs below `14 pt`. The required count is `0`.** For reference,
      the `T7-M` fabrication recorded **146** and a minimum of **`7.8 pt`**.
- [ ] Confirm **no run was reduced below either floor to force a fit**, and that
      **no line spacing is below `1.0`**, **no font is condensed** and **no
      character spacing is reduced**.
- [ ] Confirm **no note, comment, property or instruction anywhere in the file**
      says a producer may shrink type if required.
- [ ] **If any box in this section cannot be ticked, the deck is not finished and
      is not to be presented as finished.** Record it as a
      **`STOP AND REFER BACK`** against the specific slide and run.

## 5. Accessibility checks

- [ ] Minimum visible type **14 pt** on every slide — **verified by measurement
      in §4, not by eye**.
- [ ] **Every status, classification and governance-boundary word ≥ 18 pt** —
      **verified by measurement in §4**.
- [ ] Text contrast ≥ 4.5 : 1; line, border and connector contrast ≥ 3 : 1.
- [ ] **No information carried by colour alone** anywhere.
- [ ] Reading order set per slide, matching the accepted source.
- [ ] Alternative text taken from the accepted source screen-reader descriptions.
- [ ] Where a source requires it, the alt text states **co-equality**,
      **separation**, **emptiness**, **offset** or **the absence of connectors**
      in words.
- [ ] Every warning legible at projection size — none in a corner or footer.

## 6. Timing checks

- [ ] Timing recorded as **`20.0 minutes allocated — not measured`**.
- [ ] No slide, note or property claims verified, rehearsed, tested or final
      timing.
- [ ] **No automatic slide-transition timing** set on any slide.
- [ ] Rehearsal state recorded as **`NOT PERFORMED`**.

## 7. Package-to-deck handoff

- [ ] Every slide traced back to its `M07-Snn` source.
- [ ] Every deviation — **there should be none** — recorded and referred back
      before the deck is presented as complete.
- [ ] **No `.pptx` committed to this repository.**
- [ ] Future filename convention, if used:
      `HFS-BIM-Management-Module-07-Harrismith-to-Triviron-BEP-Translation-REV01.pptx`.
- [ ] Publication automation confirmed **`PAUSED`**; no publication action taken.
- [ ] Hand the built deck to [`review-checklist.md`](review-checklist.md) before
      it is called finished.
