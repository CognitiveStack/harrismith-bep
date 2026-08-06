# Module 5 — Production Checklist

**Status:** Build-time checklist for the future PowerPoint producer. **Teaching
material. Not governance.**

**The PowerPoint is produced externally and is not committed to this
repository.**

---

## 1. Before building

- [ ] **Source hierarchy understood.** Controlled Harrismith sources → teaching
      content → visual plan → slide sources → this package → PowerPoint. **The
      order runs downward and never upward**
- [ ] **Package reading order completed** — [`deck-specification.md`](deck-specification.md)
      → [`slide-copy.md`](slide-copy.md) → [`asset-manifest.md`](asset-manifest.md)
      → [`presenter-cues.md`](presenter-cues.md) → this file →
      [`review-checklist.md`](review-checklist.md)
- [ ] **Fourteen-source mapping verified** — Slide *n* ↔ `M5V-nn` ↔ `M05-Snn`,
      one-to-one
- [ ] **Theme audited.** The chosen theme **adds no icons, no SmartArt and no
      default semantic colours** (no automatic red = bad, green = good)
- [ ] **16:9 canvas set**, 960 × 540 pt reference
- [ ] **14 pt minimum** enforced; principal labels ≥ 18 pt
- [ ] **No renderer or import workflow is configured.** None is required
- [ ] **No external imagery is sourced.** `NONE REQUIRED` ×14
- [ ] **No live evidence is gathered.** `NONE REQUIRED` ×14 — **and none is
      authorised**
- [ ] **No Triviron answer is prepared**, in any form

## 2. Global build checks

- [ ] **Title consistency.** Every slide title matches
      [`../presentation-outline.md`](../presentation-outline.md) **exactly** —
      no paraphrase, no shortening
- [ ] **Slide count = 14**
- [ ] **Exact timing.** 1.0 · 1.5 · 1.5 · 1.5 · 1.5 · 1.5 · 1.5 · 1.0 · 1.5 ·
      1.5 · 1.5 · 1.5 · 1.0 · 2.0 — **total 20.0**
- [ ] **Native construction only.** Shapes, text boxes, tables, borders, lines,
      connectors. **No SmartArt, no Mermaid, no imported image**
- [ ] **Status visibility.** Every required status label is **on the slide**
- [ ] **Status/implementation separation.** Governance status and implementation
      status are **never merged into one label**
- [ ] **Source labels present** where the slide source requires them
- [ ] **Colour-independent meaning.** Remove all colour and re-read the deck —
      **every status still readable in words**
- [ ] **Connector semantics correct.** Each form means what §3.4 of the deck
      specification says it means. **A missing connector is intentional**
- [ ] **No hidden speaker-note substitutions.** **No load-bearing status has been
      moved into the notes**
- [ ] **No invented examples** — no sample row, value, date, format or name
- [ ] **No completed gaps.** Nothing unresolved has been filled in to look
      finished

## 3. Slide-specific build checks

---

### Slide 1 — Module 5 — from who holds a role to what must be produced · 1.0 min

- [ ] **Fixed form** — three panels of **equal width and height**, `y = 96–400`,
      gaps ≈ 24 pt, **never touching**; shared footer `y = 424–492`
- [ ] **Exact labels** — the three questions; `APPROVED WITH CONDITIONS —
      Training Baseline 0.1`; `AD-001`
- [ ] **Mandatory warning** — **`PUBLICATION NOT AUTHORISED`** in the footer
- [ ] **Connector rule** — **none.** No arrows or lines between panels
- [ ] **Deliberate separation** — three **separately stated** content statuses;
      `S2` shown as **split**, not proposed
- [ ] **Accessibility** — reading order left → right then footer; status ≥ 18 pt
- [ ] **Producer-failure test** — **cover the footer. Can a reader still tell
      that `S3` and `S4` are `PROPOSED GOVERNANCE` and `S2` is split?** If not,
      the status bands have failed
- [ ] **STOP** — module-wide **1, 5, 6, 8, 25**; package-level **P13**

---

### Slide 2 — Knowing the role and the transition is not yet a plan · 1.5 min

- [ ] **Fixed form** — upper band `y = 96–188`, eight cells; lower band
      `y = 212–470`, two equal columns, gap ≈ 32 pt
- [ ] **Exact labels** — all eight §10.5 fields; *by when* **struck through**,
      *for which event* adjacent; `OBSERVED — QUALIFIED`; `NOT DEMONSTRATED`
- [ ] **Mandatory warning** — **`Absence of observation is not observation of
      absence`**, occupying the bottom ≈ 56 pt of the observed column, **inside
      its border**
- [ ] **Connector rule** — **none between the columns**
- [ ] **Deliberate separation** — allocated and observed stay apart; **the five
      unobserved containers look identical to the observed one apart from their
      status word**
- [ ] **Accessibility** — **strike-through accompanied by the replacement text**,
      never the line alone
- [ ] **Producer-failure test** — **show the lower band alone to someone who has
      not heard the talk. If they conclude five disciplines are behind, the
      visual has failed**
- [ ] **STOP** — module-wide **9, 11, 22, 25**; package-level **P13**

---

### Slide 3 — Three resources, three questions — and why they are not one RACI · 1.5 min

- [ ] **Fixed form** — panels `y = 96–260` in equal thirds; refusal block
      `y = 284–372`, width ≈ 600 pt; chain `y = 396–460`
- [ ] **Exact labels** — three questions **verbatim**; **`RACI is not adopted`**
      with **`BEP §5.12`** and the recorded reason
- [ ] **Mandatory warning** — **the BEP reference beside the refusal**
- [ ] **Connector rule** — **two arrows, both pointing left**, labelled *depends
      on*. **No arrow returns. No arrow between the three panels**
- [ ] **Deliberate separation** — the three panels **never merge**; no hierarchy
      among them
- [ ] **Accessibility** — **arrow direction stated in the alt text**
- [ ] **Producer-failure test** — **can a reader point at which resource depends
      on which, and state that nothing depends on the schedule?** If the arrows
      are ambiguous, redraw
- [ ] **STOP** — module-wide **1, 2, 4**

---

### Slide 4 — Who performs which function — the IM Responsibility Matrix · 1.5 min

- [ ] **Fixed form** — grid `x = 48–640`, `y = 120–470`; **seven equal row
      bands, nine equal columns**; call-outs `x = 664–912`
- [ ] **Exact labels** — `33 information-management functions` · `7 subject
      groups` · `9 functional roles` · `Functional roles only — no holder is
      established`
- [ ] **Mandatory warning** — **both call-outs, together**:
      **`ESTABLISHED — BEP §9.4`** and
      **`UNRESOLVED — BEP §9.7 · TBD ×5 · — ×4 · no allocation made`**
- [ ] **Connector rule** — **leader lines only.** No arrows between grid and
      call-outs
- [ ] **Deliberate gap** — **the grid is unpopulated**, with a caption stating it
      is unpopulated **for teaching** — the source has **297 populated cells**
- [ ] **Accessibility** — grid emptiness stated **in words**; **the `TBD` / `—`
      split read as two separate counts**, never as one
- [ ] **Producer-failure test** — **does any cell contain a character?** If yes,
      the visual has pre-empted Slides 6 and 7. **Do both call-outs appear?** If
      only one, the split rule is broken. **Does the unresolved call-out say
      `TBD` in every column?** If yes, **STOP** — four of those nine cells are `—`
- [ ] **STOP** — module-wide **3, 5, 6, 8, 9, 26**; package-level **P1, P2**

---

### Slide 5 — Who produces which container — the Model / Information Responsibility Matrix · 1.5 min

- [ ] **Fixed form** — chain `y = 96–160`; containers `y = 190–360`; **MEP
      enclosure with ≥ 12 pt internal padding**; **FIR ≥ 40 pt clear of that
      enclosure**; `COORD-01` `y = 396–460`, **horizontally offset**
- [ ] **Exact labels** — `party → task team → discipline → container`; the four
      party names; `A discipline code identifies the information domain — that is
      all it does`; `Originator responsibility remains with the producing task
      team`
- [ ] **Mandatory warning** — `PROPOSED GOVERNANCE` and **`Intended governance —
      not an inventory of what exists in the CDE`**
- [ ] **Connector rule** — chain arrows mean **"resolves to"**; the `COORD-01`
      line means **"aggregates from"** and is **dashed**. **No line implies
      ownership**
- [ ] **Deliberate separation** — **the MEP enclosure is drawn first**, not added
      afterwards; **Fire visibly outside it**
- [ ] **Accessibility** — **the enclosure described in words**
- [ ] **Producer-failure test** — **ask a reader to count the organisations. If
      the answer is six, the enclosure has failed.** **Ask whether `COORD-01` is
      a seventh discipline container. If yes, the offset and line weight have
      failed**
- [ ] **STOP** — module-wide **3, 7, 9, 22**

---

### Slide 6 — The seven-term grammar — and the two values that carry the gaps · 1.5 min

- [ ] **Fixed form** — Panel A `x = 48–560`, seven rows; **gutter `x = 560–600`**;
      Panel B `x = 600–912`, two rows; scope line `y = 276–308`; refusal
      `y = 424–492`
- [ ] **Exact labels** — all seven terms with §5.12 definitions **verbatim**;
      *"The matrix will use these terms and no others"*; `TBD` and `—`
      definitions verbatim; **`Not function codes`**
- [ ] **Mandatory warning** — **`This grammar belongs to the IM Responsibility
      Matrix only`**
- [ ] **Connector rule** — **none. No line joins panel A to panel B**
- [ ] **Deliberate separation** — **the ≥ 40 pt gutter is load-bearing**
- [ ] **Accessibility** — **the gutter described in words**
- [ ] **Producer-failure test** — **ask a reader how many function codes there
      are. If the answer is nine, the separation has failed.** **Ask which
      resources use this grammar. If the answer is more than one, the scope line
      has failed**
- [ ] **STOP** — module-wide **2, 3, 4, 18**; package-level **P3**

---

### Slide 7 — Reading a cell: what a populated cell does and does not prove · 1.5 min

- [ ] **Fixed form** — intersection `x = 48–300`; `P1`–`P4` bars `x = 324–616`
      with **≥ 16 pt vertical gaps so they never abut**; `D4` block
      `x = 640–912`, **visually isolated**, **each of the nine cells ≥ 28 pt
      wide**; census strip `y = 430–470`
- [ ] **Exact labels** — `row × column = cell`; `which function this role holds
      in this activity`; `P4 — Au — ESTABLISHED, BEP §9.4`; `Combined values
      record no order`; the census
- [ ] **Mandatory warning** — **`UNRESOLVED`** and **`NO ALLOCATION MADE`** on
      `D4`, plus the line stating a cell records no name, appointment, occurrence
      or independence
- [ ] **Connector rule** — **leader lines only.** **No arrow between `P1`, `P2`,
      `P3` and `P4`**
- [ ] **Deliberate gap** — **`D4` shown exactly as recorded: `TBD` against AP,
      LDP, BM, BC, TTL; `—` against Aut, Chk, CDE, Rcp. Never completed**
- [ ] **Accessibility** — **each `D4` cell read with its role name**, so the
      five/four split survives audio
- [ ] **Producer-failure test** — **is there an arrow anywhere between `P1` and
      `P4`?** If yes, remove it. **Does the `D4` row show exactly nine cells —
      five `TBD` and four `—`?** If any cell is missing, blank, or carries a
      different value, **STOP**. **Ask a reader who holds publication authority.
      If the answer names any of the five `TBD` roles, `NO ALLOCATION MADE` has
      failed**
- [ ] **STOP** — module-wide **9, 10, 16, 26**; package-level **P4, P5**

---

### Slide 8 — One person, two roles — allocation is not independence · 1.0 min

- [ ] **Fixed form** — role boxes `x = 160–460` and `x = 500–800`, `y = 140–300`;
      **boundary line at `x = 480`, full height, drawn on top**; participant
      outline `x = 130–830`, `y = 120–320`, **no fill**
- [ ] **Exact labels** — `Author` · `Checker` · `One participant may hold more
      than one role` · `A self-check is still a checking act against a defined
      requirement` · `TA-02 — no professional authority, appointment, duty or
      liability`
- [ ] **Mandatory warning** — **`INDEPENDENCE — NOT ESTABLISHED`** **and**
      `Not a defect · not a non-conformance`
- [ ] **Connector rule** — **none.** The overlap is **spatial**, not a connector
- [ ] **Deliberate overlap** — **the boundary remains visible through the
      participant outline**
- [ ] **Accessibility** — **overlap described in words**
- [ ] **Producer-failure test** — **is the boundary still visible where the
      participant outline crosses it?** If not, redraw. **Does anything on the
      slide look like a warning symbol?** If yes, remove it
- [ ] **STOP** — module-wide **8, 10**; package-level **P6**

---

### Slide 9 — The Information Delivery Schedule — sixteen fields · 1.5 min

- [ ] **Fixed form** — six group blocks in two rows of three, `y = 96–340`,
      ≥ 16 pt gaps; caption `y = 348–372`; caution panel `y = 388–470`
- [ ] **Exact labels** — **all sixteen controlled field names verbatim**;
      `Not a contractual programme`; `No delivery dates or client milestones
      established`
- [ ] **Mandatory warning** — **`Teaching grouping — the schedule lists sixteen
      fields flat`**, `PROPOSED GOVERNANCE`, **and `A row is a plan, not a
      record`**
- [ ] **Connector rule** — **none.** Fields grouped **by containment**
- [ ] **Deliberate absence** — **no sample values of any kind**
- [ ] **Accessibility** — **caution markers have text equivalents**, not
      shape-only meaning
- [ ] **Producer-failure test** — **count the field names. Is the answer exactly
      sixteen, each appearing once, spelled as in the source?** If not, **STOP**.
      **Is the grouping caption visible at projection scale?** If not, enlarge it
- [ ] **STOP** — module-wide **11, 22, 25**; package-level **P7**

---

### Slide 10 — Three delivery events — proposed, conditional, blocked · 1.5 min

- [ ] **Fixed form** — three cards, equal width ≈ 272 pt, `y = 110–420`, gaps
      ≈ 24 pt, **never touching**; **status band = top 48 pt of each card**;
      caution strip `y = 440–480`
- [ ] **Exact labels** — `TRN-E01 — PROPOSED`; `TRN-E02 — PROPOSED ·
      CONDITIONAL`; **`TRN-E03 — PROPOSED — BLOCKED PENDING GOVERNANCE
      DECISIONS`**; `Event-triggered / TBD`; `activated per affected container
      only`; `An unactivated row is not a pending exchange`
- [ ] **Mandatory warning** — **`Blocked is not overdue, rejected or
      unfinished`**
- [ ] **Connector rule** — **NONE PERMITTED.** No arrow between the cards, in any
      direction
- [ ] **Deliberate separation** — three **identical-size** cards; **no ordinal
      numbering**
- [ ] **Accessibility** — **status carried by the words in each band**, never by
      band colour
- [ ] **Producer-failure test** — **is there any arrow, chevron or numeral
      suggesting order?** If yes, remove it. **Does `TRN-E03` look late rather
      than blocked?** If yes, the wording has failed
- [ ] **STOP** — module-wide **11, 22**; package-level **P8**

---

### Slide 11 — A delivery event is not an information-state transition · 1.5 min

- [ ] **Fixed form** — event track `y = 110–190`; step track `y = 300–380`;
      connectors in the band `y = 190–300`; four-object strip `x = 724–912`.
      **The tracks never merge and never share a box**
- [ ] **Exact labels** — `An event uses a transition — it is not that
      transition`; `Only T1 and T4 change the information state`; **the kind of
      each of the eight steps, in words**; the four §10.11 definitions
- [ ] **Mandatory warning** — **`T4 — BLOCKED · no available authorising
      function`**, **`Information remains Shared`**, **`Delivered, Received and
      Accepted are not information states`**
- [ ] **Connector rule** — vertical connectors **labelled `uses`**, meaning
      *uses / depends upon*, **never identity**. **No equals sign, no
      double-headed arrow, no shared node**
- [ ] **Deliberate block** — **the `TRN-E03` connector is drawn with a visible
      break and labelled `BLOCKED`.** **No route continues past `T4`**
- [ ] **Accessibility** — **connector labels read aloud; the break described as
      *blocked***, never left to visual inference
- [ ] **Producer-failure test** — **does any connector look like an equals sign
      or a merge?** If yes, redraw. **Is there a box labelled Delivered, Received
      or Accepted in the state track?** If yes, **STOP**
- [ ] **STOP** — module-wide **12, 13, 14, 15**

---

### Slide 12 — Why `TRN-E03` is blocked — five matters, not one · 1.5 min

- [ ] **Fixed form** — five gates across `x = 48–780`, equal width ≈ 134 pt,
      `y = 130–330`, gaps ≈ 12 pt; **status text in the lower third of each
      gate**; variance note `x = 800–912`, **visibly smaller**; consequence line
      `y = 356–396`; boundary footer `y = 420–480`
- [ ] **Exact labels** — the five matters with **`UNRESOLVED — TBD` ×2,
      `Not established` ×2, `Not defined` ×1**; `Resolving one releases none of
      the others`
- [ ] **Mandatory warning** — **`T4 BLOCKED — INFORMATION REMAINS SHARED`**, and
      **each gate's own typed status**
- [ ] **Connector rule** — **none between the gates**
- [ ] **Deliberate block** — **all five gates closed. None opening, none opened,
      none blank. No sixth primary gate**
- [ ] **Accessibility** — **closed state described in words**, never by icon
      alone
- [ ] **Producer-failure test** — **is any gate empty, or does any carry a symbol
      instead of its status words?** If yes, **STOP**. **Does the variance note
      look like a sixth gate?** If yes, reduce and reposition it
- [ ] **Variance preserved** — `S4` counts **five**, `S5` counts **six**.
      **Recorded, not harmonised**
- [ ] **STOP** — module-wide **14, 15, 16, 17, 21, 22**; package-level **P9, P10**

---

### Slide 13 — Nothing is blank — how Harrismith names an absence · 1.0 min

- [ ] **Fixed form** — panel `x = 48–912`, `y = 110–430`, seven equal rows, four
      columns ≈ `160 / 240 / 200 / 264` pt; **visible rule between the `TBD` and
      `—` rows**; label strip `y = 440–476`
- [ ] **Exact labels** — all seven markers; **outcome words `UNRESOLVED` ×3,
      `RESOLVED — no function`, `RESOLVED — does not apply`,
      `TRIGGER-DEPENDENT`, `CANNOT PROCEED`**; `Only the IM Responsibility Matrix
      publishes a legend`; `Nothing is blank`
- [ ] **Mandatory warning** — **`Teaching grouping — not a controlled code set`**
- [ ] **Connector rule** — **none.** A table, not a diagram
- [ ] **Deliberate separation** — **`TBD` and `—` adjacent but ruled apart**
- [ ] **Accessibility** — **outcome read aloud with every marker**
- [ ] **Producer-failure test** — **ask a reader what `—` means. If the answer
      contains "unknown", "not yet" or "blank", the outcome column has failed.**
      **Ask whether this is a project code set. If yes, the label strip has
      failed**
- [ ] **STOP** — module-wide **17, 18, 19, 20, 21**; package-level **P11**

---

### Slide 14 — What Triviron must decide before drawing a matrix · 2.0 min

- [ ] **Fixed form** — five blocks across `x = 48–700`, `y = 96–430`; **answer
      area = lower 40 pt of each block, bordered, containing only the status
      text**; Harrismith panel `x = 724–912`, **visually subordinate**; closing
      strip `y = 450–496`
- [ ] **Exact labels** — the five group names; **at least three questions per
      group**; the three-row Harrismith status contrast; `Example of method — not
      a recommendation`
- [ ] **Mandatory warning** — **`NOT YET ESTABLISHED` in all five answer areas**,
      and **`Triviron responsibility and delivery basis — not yet established`**
- [ ] **Connector rule** — **none. No arrow from a Harrismith example to a
      Triviron question**
- [ ] **Deliberate gap** — **every answer area permanently empty apart from its
      status text**
- [ ] **Accessibility** — **the subordination of the Harrismith panel stated in
      words**, since styling alone does not survive audio
- [ ] **Producer-failure test** — **cover the closing strip. Can a reader extract
      a single Triviron answer from anything on the slide?** If yes, **STOP**.
      **Does the Harrismith panel state one status for all three resources?** If
      yes, the split-status requirement has failed
- [ ] **STOP** — module-wide **5, 6, 22, 24, 25**; package-level **P12**

---

## 4. Module-wide STOP register

**All twenty-six accepted module-wide STOP conditions.** Carried without change
of meaning from [`../visual-demonstration-plan.md`](../visual-demonstration-plan.md)
§3. **A producer must stop and refer back** if any visual:

| # | Condition |
|---|---|
| 1 | Merges the three resources |
| 2 | Presents RACI as the grammar, or maps any code to R/A/C/I |
| 3 | Applies the IM grammar to the container matrix or the schedule |
| 4 | Implies both matrices share one coded vocabulary |
| 5 | Flattens every IM allocation to **proposed** |
| 6 | Flattens every IM allocation to **established** |
| 7 | Converts a discipline into an organisation |
| 8 | Converts a role into a person |
| 9 | Converts an allocation into evidence of performance |
| 10 | Claims independence |
| 11 | Treats a schedule row as a live exchange |
| 12 | Identifies an event with a transition |
| 13 | Creates a Delivered, Received or Accepted **state** |
| 14 | Opens `T4` |
| 15 | Progresses information beyond **Shared** |
| 16 | Resolves any `TRN-E03` blocker |
| 17 | Shows a blocker as blank |
| 18 | Calls `—` unresolved or blank |
| 19 | Calls `Not applicable` unresolved |
| 20 | Presents all seven Slide 13 markers as "not yet" |
| 21 | Harmonises the five-versus-six blocker variance |
| 22 | Introduces a date, frequency, format or final deliverable |
| 23 | Imports a screenshot or external image |
| 24 | Invents a Triviron fact or answer |
| 25 | Suggests the content baseline is already a produced presentation |
| 26 | States that `D4` is `TBD` in every column, omits its four `—` cells, or presents its five `TBD` cells as an allocation, a shortlist or a set of candidate authorities |

## 5. Package-level additions

**These are not part of the accepted twenty-six.** They were identified while
compressing the accepted sources into a build handoff, and are recorded
separately. **They do not alter the upstream visual plan.**

| # | Slide | Package-level condition |
|---|---|---|
| **P1** | 4 | Populating the teaching skeleton — any character in any cell |
| **P2** | 4 | Dropping either call-out |
| **P3** | 6 | Closing the gutter, or joining the two panels with a connector |
| **P4** | 7 | Drawing any arrow between `P1` and `P4` |
| **P5** | 7 | Abbreviating, eliding or ellipsis-ing any of `D4`'s nine cells |
| **P6** | 8 | Hiding the Author/Checker boundary where the participant outline crosses it |
| **P7** | 9 | Renaming, merging, abbreviating or omitting any of the sixteen field names |
| **P8** | 10 | Any connector, chevron or ordinal numeral between the three event cards |
| **P9** | 12 | Adding a sixth primary gate, or letting the variance note read as one |
| **P10** | 12 | Leaving any gate blank, or replacing its typed status with a symbol |
| **P11** | 13 | Dropping the outcome column, or merging it into the question column |
| **P12** | 14 | Filling any answer area — including with a Harrismith example |
| **P13** | all | Moving a load-bearing status label into the presenter notes |
| **P14** | all | Claiming measured timing |

## 6. Post-build checks

- [ ] **Fourteen slides**, no more and no fewer
- [ ] **20.0-minute allocation** recorded, and **described as an allocation**
- [ ] **All section totals** — A 2.5 · B 4.5 · C 4.0 · D 6.0 · E 3.0 = **20.0**
- [ ] **Every slide title** matches the outline exactly
- [ ] **Every visual ID** present — `M5V-01`–`M5V-14`
- [ ] **Every source ID** present — `M05-S01`–`M05-S14`
- [ ] **Every required warning** present and legible at projection scale
- [ ] **Every deliberate block** intact — Slide 11's broken connector, Slide 12's
      five closed gates
- [ ] **Every deliberately absent connector** still absent — Slides 1, 2, 6, 8,
      9, 10, 12, 13, 14
- [ ] **No imported image**, anywhere
- [ ] **No false information state** — no Delivered, Received or Accepted state
- [ ] **No Triviron answer**, anywhere
- [ ] **No measured-time claim**
- [ ] **No unsupported implementation claim**

## 7. Accessibility checks

- [ ] **Reading order** set explicitly on every slide, matching the order in
      [`asset-manifest.md`](asset-manifest.md)
- [ ] **Screen-reader description transferred** to alt text or to the notes, as
      appropriate to the object — **but no load-bearing status moved out of the
      slide** to achieve it
- [ ] **Contrast** — text ≥ 4.5 : 1; borders and connectors ≥ 3 : 1
- [ ] **Text size** — nothing below 14 pt; principal labels ≥ 18 pt
- [ ] **Colour-independent meaning** — remove all colour and re-read
- [ ] **Line-style meaning also stated in words** — the Slide 5 dashed
      aggregation line and the Slide 11 broken connector **must both be described
      in text**
- [ ] **All nine `D4` cells readable**, each with its role name
- [ ] **All sixteen schedule fields readable**, each named once
- [ ] **Five blockers readable and distinct**, each with its typed status
- [ ] **Every empty answer area described in text** as `NOT YET ESTABLISHED`
- [ ] **The Slide 6 gutter, the Slide 5 enclosure and the Slide 8 overlap each
      described in words**

## 8. Status

| Field | Value |
|---|---|
| Checklist covers | **Fourteen slides** |
| Module-wide STOP conditions | **26** |
| Package-level additions | **14**, separately identified |
| Rendered assets | **None required, none authorised** |
| PowerPoint | **Produced externally; not committed here** |
| Timing | **`20.0 minutes allocated — not measured`** |
| Publication automation | **`PAUSED`** |
