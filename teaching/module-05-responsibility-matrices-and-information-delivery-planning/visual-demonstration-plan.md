# Module 5 — Visual Demonstration Plan

**Status:** Teaching material. **Not governance.** This plan explains and
specifies; it decides nothing and approves nothing.

**All fourteen visual specifications are complete after T5-F-A, corrected and
accepted in T5-F-A-R, and implemented by fourteen visual-source files in
T5-F-B.**

> **T5-F-A-R correction.** Repository review found that `M5V-04` and `M5V-07`
> repeated an inaccurate description of the controlled `D4` row. **The row holds
> nine populated cells — `TBD` against AP, LDP, BM, BC and TTL, and `—` against
> Aut, Chk, CDE and Rcp** — and *"No allocation is made here."* Both
> specifications now carry the exact distribution, and **STOP condition 26**
> forbids the inaccurate form. `M5V-12`'s takeaway was also corrected: the five
> blockers carry **three** distinct status terms, not five. **No controlled
> source was changed.**

| Field | Value |
|---|---|
| Specifications | **`M5V-01`–`M5V-14` — 14 of 14, `SPECIFICATION COMPLETE` and `ACCEPTED`** |
| Visual-source files | **14 of 14 — all `SOURCE COMPLETE` (T5-F-B)** |
| Asset directory | **Exists** — [`../assets/module-05/`](../assets/module-05/) |
| Visual register | **Complete** — [`../assets/module-05/visual-register.md`](../assets/module-05/visual-register.md) |
| Slide-visual map | **Complete** — [`../assets/module-05/slide-visual-map.md`](../assets/module-05/slide-visual-map.md) |
| Rendered assets | **NONE. No rendering was attempted** |
| Renderer or dependency installed | **None** |
| Presentation assembly package | **COMPLETE (`T5-G`)** — [`presentation/`](presentation/); **seven production-handoff files** |
| PowerPoint | **PRODUCED — `REV01`** (`T5-H`, corrected in `T5-H-R1`); **governance review ACCEPTED**. **Produced outside this repository and not committed here** |
| Timing | **`20.0 minutes allocated — not measured`** |

## Authority chain

```
teaching content
  → visual-demonstration plan        ← this file
  → visual-source files              ← T5-F-B, complete
  → presentation assembly package    ← T5-G, complete
  → external PowerPoint              ← T5-H, complete (REV01, accepted); outside this repository
```

**Precedence, in order:**

- Where the **accepted teaching content** and this plan differ, **the teaching
  content is authoritative** — [`presentation-outline.md`](presentation-outline.md),
  [`speaker-notes.md`](speaker-notes.md), [`source-map.md`](source-map.md).
- Where a **visual-source file** and this plan differ, **this plan is
  authoritative**.
- Where a **PowerPoint** and a visual source differ, **the source is
  authoritative**.

**And above all of them:** where any teaching material conflicts with a
controlled Harrismith source, **the controlled source wins**.

---

## 1. Identifier spaces

**One visual per slide. Strictly one-to-one.**

```text
14 visual concepts  =  14 slides  =  14 visual-source files
```

| Space | Range | State |
|---|---|---|
| **Visual concept** | `M5V-01` – `M5V-14` | **Specified in T5-F-A** |
| **Slide source** | `M05-S01` – `M05-S14` | **Created in T5-F-B — all `SOURCE COMPLETE`** |

**Slide-source path:** `teaching/assets/module-05/M05-S<nn>.md`. **That
directory exists and holds the fourteen sources, the visual register and the
slide-visual map.** **No rendered asset exists.**

**No controlled identifier is reused.** `P1`–`P4`, `D4`–`D7`, `A2`, `T1`–`T8`,
`X1`–`X5`, `TRN-E01`–`TRN-E03`, `ARC-01`–`FIR-01` and `COORD-01` belong to the
controlled sources and appear in specifications **only as quoted content**, never
as visual identifiers.

---

## 2. Module-wide visual rules

### 2.1 Status must be visible

**Every visual that shows governance, an allocation, an event, a transition or
implementation evidence must show the applicable status on the slide.**

**Status may never exist only in the presenter notes**, and **status meaning may
never depend on colour alone** — every status is carried by a **word**.

The status vocabulary available to Module 5 visuals:

| Status | Used where |
|---|---|
| `CONTROLLED GOVERNANCE` | Explicit BEP wording |
| `ESTABLISHED ALLOCATION` | An `S2` allocation the BEP expressly establishes |
| `PROPOSED GOVERNANCE` | `S3` §3, all `S4` entries, most `S2` allocations |
| `UNRESOLVED` | An open matter recorded as open |
| `CONDITIONAL` | Activates only on a stated trigger |
| `BLOCKED` | Cannot proceed while an input or authority is unresolved |
| `IMPLEMENTATION UNVERIFIED` | Not checked against the live environment |
| `OBSERVED — QUALIFIED` | `ARC-01` only, at the inspected level |
| `NOT DEMONSTRATED` | Looked for and not observed — **never a failure claim** |
| `NOT YET ESTABLISHED` | Triviron; every Slide 14 answer area |

**No visual is required to use every status.** Each specification names the ones
it must carry.

### 2.2 Reference canvas

| Parameter | Value |
|---|---|
| Canvas | **960 × 540 pt**, 16:9 |
| Origin | Top left; `x` increases right, `y` increases down |
| Title zone | `y = 0–72` — **reserved**, no content beneath the title baseline |
| Side margins | **≥ 48 pt** |
| Minimum visible type | **14 pt** |
| Principal labels | **≥ 18 pt** |
| Text contrast | **≥ 4.5 : 1** |
| Border and connector contrast | **≥ 3 : 1** |

Geometry varies by slide. **Every specification states enough spatial
relationship to prevent semantic drift** — which elements are equal, which are
separate, which are adjacent, and which must never touch.

### 2.3 External imagery and live evidence

**External imagery: `NONE REQUIRED` — for all fourteen visuals.**

Prohibited throughout: stock photography · platform screenshots · ACC
screenshots · Autodesk, Revit or company logos · live CDE images · observed
folder screenshots.

**Why.** A screenshot makes *software implementation* concrete while this module
teaches **governance and proposed planning**. Module 5's central hazard is the
audience concluding that something is operating. An interface image would assert
exactly that, silently and more persuasively than any caption could withdraw.

**Live evidence: `NONE REQUIRED` — for all fourteen visuals.** No new
observation is needed and **none is authorised**. The only implementation
evidence Module 5 cites is `S9`, which declares **`Authority: None`**, and it is
quoted as text.

### 2.4 Visual form

**Default form: native, PowerPoint-reconstructable layout** — rectangles,
tables, text boxes, simple call-outs and deliberately controlled connectors.

**SmartArt is prohibited.** Its automatic layouts imply hierarchy and sequence
that Module 5 spends fourteen slides denying.

**Mermaid risk test — applied separately to every visual.** A Mermaid form is
**prohibited** wherever automatic layout could imply hierarchy · sequence ·
equivalence · completion · identity between an event and a transition · an open
route through a blocked gate · one merged matrix · one harmonised vocabulary ·
or a Triviron answer.

**Result: native layout for all fourteen.** Every Module 5 visual carries at
least one of those hazards. **No Mermaid form is proposed anywhere in this
module**, and any future proposal requires an explicit written safety
justification.

### 2.5 Accessibility

Every specification carries: logical reading order · a screen-reader description
· status meaning **in words** · **no information by colour alone** · projection
readability at the stated minimums · connector meaning carried by **form and
label**, not by colour · and warnings that remain legible at projection scale.

---

## 3. Module-wide STOP conditions

**A producer must stop and refer back** if any visual:

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

---

## 4. The fourteen specifications

---

### `M5V-01` — Slide 1

| Field | Value |
|---|---|
| **1 · Identifier** | `M5V-01` |
| **2 · Slide** | 1 — *Module 5: from who holds a role to what must be produced* · 1.0 min |
| **3 · Visual title** | Three resources, three questions, three separately stated statuses |
| **4 · Teaching purpose** | Fix the identity and the **status** of all three resources before any content is shown |
| **5 · Five-second takeaway** | *Three separate documents, and they do not share one status.* |
| **6 · Source basis** | `S1` §5.12, §7.12, §10.13, §13.6; `S2`/`S3`/`S4` status blocks; `S8` `AD-001` |
| **7 · Statements** | `M5-S1-01` – `M5-S1-12` |
| **8 · Classification profile** | 3 `CONTROLLED` · 3 `SUPPORTING` · 2 `DECISION-RECORD` · 2 `MODULE-2-4` · 1 `TEACHING-PLAN` · 1 `EXCLUDED` |
| **9 · Governance status** | `CONTROLLED GOVERNANCE` (approval) · `PROPOSED GOVERNANCE` (content of `S3`, `S4`) · split rule (`S2`) |
| **10 · Implementation status** | **None claimed.** No resource shown as operating |
| **11 · Fixed form** | **Three vertical panels of equal width and height**, side by side, each with its own status band beneath it. One shared footer strip carries the approval and publication position |
| **12 · Why this form** | Three equal panels make separateness structural rather than asserted. A shared footer shows what *is* common without merging what is not |
| **13 · Simplification rule** | If space is short, shorten the question text. **Never merge two panels, and never drop a status band** |
| **14 · Mandatory visible wording** | The three questions; `APPROVED WITH CONDITIONS — Training Baseline 0.1`; `AD-001`; `PROPOSED GOVERNANCE` on the `S3` and `S4` panels; **split rule** on the `S2` panel; `PUBLICATION NOT AUTHORISED` |
| **15 · Mandatory status/warning** | `PUBLICATION NOT AUTHORISED` in the shared footer, and **one status band per panel** |
| **16 · Blocked / unresolved / absent** | **No role holder, person or company appears anywhere.** No implementation indicator |
| **17 · Geometry** | Three panels across `x = 48–912`, equal width ≈ 272 pt, gaps ≈ 24 pt, `y = 96–400`. Status band = lower 64 pt of each panel. Footer strip `y = 424–492`, full width. **Panels never touch** |
| **18 · Connector semantics** | **None.** No arrows, no lines between panels — connection would imply relationship this slide does not teach |
| **19 · Build sequence** | Panels together → status bands → footer |
| **20 · Mandatory omissions** | No combined table · no person · no organisation · no implementation tick · no deck-produced claim |
| **21 · Overclaim risk** | **A shared footer reading only "approved" would flatten three statuses into one.** The footer must carry the approval *and* the publication hold; the per-panel bands carry the content classification |
| **22 · Producer-failure test** | Cover the footer. **Can a reader still tell that `S3` and `S4` are `PROPOSED GOVERNANCE` and `S2` is split?** If not, the status bands have failed |
| **23 · STOP conditions** | Module-wide 1, 5, 6, 8, 25 |
| **24 · Accessibility** | Reading order left → right, then footer. Status words never colour-only. All status text ≥ 18 pt |
| **25 · Screen-reader description** | *"Three separate panels. Panel one: Information Management Responsibility Matrix — who performs which information-management function; status, split rule. Panel two: Model / Information Responsibility Matrix — who produces and maintains which information container; status, proposed governance. Panel three: Information Delivery Schedule — what is exchanged, at what event, to whom, why, in what form; status, proposed governance. Footer: all three approved with conditions under AD-001; publication not authorised."* |
| **26 · External imagery** | `NONE REQUIRED` |
| **27 · Live evidence** | `NONE REQUIRED` |
| **28 · Mermaid decision** | **PROHIBITED.** Any graph form would connect the three panels and imply a relationship — STOP condition 1 |
| **29 · Native reconstruction** | Three rectangles + three text boxes + three status rectangles + one footer rectangle. No connectors |
| **30 · Slide source** | `M05-S01` → [`../assets/module-05/M05-S01.md`](../assets/module-05/M05-S01.md) — **CREATED (T5-F-B)** |
| **31 · Status** | `SPECIFICATION COMPLETE` · source `SOURCE COMPLETE` · rendered `NONE` |

---

### `M5V-02` — Slide 2

| Field | Value |
|---|---|
| **1 · Identifier** | `M5V-02` |
| **2 · Slide** | 2 — *Knowing the role and the transition is not yet a plan* · 1.5 min |
| **3 · Visual title** | The delivery-planning gap, and allocation against observation |
| **4 · Teaching purpose** | Establish the central question from BEP §10.5, and separate what is allocated from what has been observed |
| **5 · Five-second takeaway** | *Six allocated. One observed. And that is not an accusation.* |
| **6 · Source basis** | `S1` §10.5, §7.3, §10.2, §1.5; `S4` §Population rule, §2, §7; `S2` §5; `S9` §7; `S7` `OF-002` |
| **7 · Statements** | `M5-S2-01` – `M5-S2-15` |
| **8 · Classification profile** | 3 `CONTROLLED` · 3 `SUPPORTING` · 5 `DECISION-RECORD` · 3 `INTERP` · 1 `EXCLUDED` |
| **9 · Governance status** | `CONTROLLED GOVERNANCE` (§10.5) · `UNRESOLVED` (no requirements, no dates) |
| **10 · Implementation status** | **`OBSERVED — QUALIFIED`** (`ARC-01`) and **`NOT DEMONSTRATED`** (the other five) |
| **11 · Fixed form** | **Upper band:** the eight §10.5 fields in one row, with *by when* **struck through** and *for which event* adjacent. **Lower band:** two columns — `ALLOCATED` and `OBSERVED` — with the absence-of-observation caution **inside the observed column's frame** |
| **12 · Why this form** | The caution must be structurally inseparable from the observation. Placing it in a footnote or a separate box invites the two halves to be read apart |
| **13 · Simplification rule** | The eight fields may compress to single words. **The caution may never be shortened, moved outside the observed frame, or reduced below 14 pt** |
| **14 · Mandatory visible wording** | The eight §10.5 fields; *by when* struck through; **`Absence of observation is not observation of absence`**; `OBSERVED — QUALIFIED`; `NOT DEMONSTRATED` |
| **15 · Mandatory status/warning** | The absence-of-observation sentence, **inside the observed column** |
| **16 · Blocked / unresolved / absent** | **No dates, no calendar, no timeline.** No count of "outstanding" deliveries |
| **17 · Geometry** | Upper band `y = 96–188`, eight cells across `x = 48–912`. Lower band `y = 212–470`, two columns of equal width, gap ≈ 32 pt. **Caution occupies the bottom ≈ 56 pt of the observed column, inside its border** |
| **18 · Connector semantics** | **None between the columns.** An arrow would imply allocation *leads to* observation |
| **19 · Build sequence** | Eight fields → strike-through → allocated column → observed column **with its caution already present** |
| **20 · Mandatory omissions** | No date · no frequency · no red/warning iconography on the five unobserved containers · no "missing" or "overdue" label |
| **21 · Overclaim risk** | **The observed column reads as an indictment of five task teams.** Mitigated only by the embedded caution and by neutral typography — the five unobserved containers must look **identical** to the observed one apart from their status word |
| **22 · Producer-failure test** | Show the lower band alone to someone who has not heard the talk. **If they conclude five disciplines are behind, the visual has failed** |
| **23 · STOP conditions** | Module-wide 9, 11, 22, 25 |
| **24 · Accessibility** | Reading order: fields → allocated → observed → caution. Strike-through must be accompanied by the replacement text, not rely on the line alone |
| **25 · Screen-reader description** | *"Top: the eight things each task team should be able to answer, from BEP section 10.5. The phrase 'by when' is struck through and replaced by 'for which event'. Below, two columns. Allocated: six containers. Observed: ARC-01 only, at the inspected level, status observed-qualified; the other five, not demonstrated. Inside the observed column: absence of observation is not observation of absence."* |
| **26 · External imagery** | `NONE REQUIRED` |
| **27 · Live evidence** | `NONE REQUIRED` — `S9` is quoted as text |
| **28 · Mermaid decision** | **PROHIBITED.** A graph would sequence allocation into observation, implying a pipeline with five failures in it |
| **29 · Native reconstruction** | One 8-cell table + two rectangles + one nested caution rectangle. No connectors |
| **30 · Slide source** | `M05-S02` → [`../assets/module-05/M05-S02.md`](../assets/module-05/M05-S02.md) — **CREATED (T5-F-B)** |
| **31 · Status** | `SPECIFICATION COMPLETE` · source `SOURCE COMPLETE` · rendered `NONE` |

---

### `M5V-03` — Slide 3

| Field | Value |
|---|---|
| **1 · Identifier** | `M5V-03` |
| **2 · Slide** | 3 — *Three resources, three questions — and why they are not one RACI* · 1.5 min |
| **3 · Visual title** | Three questions, one refusal, one directional chain |
| **4 · Teaching purpose** | Give a durable way to tell the three resources apart, and put the RACI refusal on the record |
| **5 · Five-second takeaway** | *Three questions. RACI was refused, and the BEP says why.* |
| **6 · Source basis** | `S1` §5.12, §13.6; `S2` §Purpose, §1, §7; `S3` §Purpose; `S4` §Purpose, §Container discipline |
| **7 · Statements** | `M5-S3-01` – `M5-S3-16` |
| **8 · Classification profile** | 2 `CONTROLLED` · 7 `SUPPORTING` · 4 `INTERP` · 3 `EXCLUDED` |
| **9 · Governance status** | `CONTROLLED GOVERNANCE` (the refusal) · `PROPOSED GOVERNANCE` (the three resources' content) |
| **10 · Implementation status** | **Not applicable to this visual** — no implementation claim is made |
| **11 · Fixed form** | **Three equal panels**, one question each, each carrying its own *does not answer* line. Beneath: the RACI refusal as a **quotation block with its BEP reference**. Beneath that: a **one-way dependency chain**, schedule → container matrix → function matrix |
| **12 · Why this form** | Equal panels prevent hierarchy. A quotation block makes the refusal governance rather than opinion. A one-way chain shows dependency without implying process order |
| **13 · Simplification rule** | The *does not answer* lines may compress to two words each. **The refusal quotation and its reference may not be shortened** |
| **14 · Mandatory visible wording** | The three questions verbatim; **`RACI is not adopted`** with **`BEP §5.12`**; the recorded reason — *collapses checking from authorising, coordinating from performing*; *"No container is scheduled that does not exist in that matrix"* |
| **15 · Mandatory status/warning** | The BEP reference beside the refusal — **without it the refusal reads as preference** |
| **16 · Blocked / unresolved / absent** | **No merged grid. No R/A/C/I letters anywhere on the slide** |
| **17 · Geometry** | Panels `y = 96–260`, equal thirds across `x = 48–912`. Refusal block `y = 284–372`, centred, width ≈ 600 pt. Chain `y = 396–460`, three labelled boxes with **two arrows, both pointing left** |
| **18 · Connector semantics** | **Arrows mean "depends on / consumes from", one direction only.** No arrow returns. No arrow between the three upper panels |
| **19 · Build sequence** | Three panels → refusal block → chain |
| **20 · Mandatory omissions** | No R/A/C/I mapping · no combined table · no ranking or numbering that implies seniority · no bidirectional arrow |
| **21 · Overclaim risk** | **A left-to-right chain reads as a workflow.** Label the arrows *depends on*, and place the chain below the refusal so it reads as reference structure, not sequence |
| **22 · Producer-failure test** | **Can a reader point at which resource depends on which, and state that nothing depends on the schedule?** If the arrows are ambiguous, redraw |
| **23 · STOP conditions** | Module-wide 1, 2, 4 |
| **24 · Accessibility** | Reading order: panels left → right, refusal, chain. Arrow direction stated in the alt text, not inferred from shape |
| **25 · Screen-reader description** | *"Three equal panels, one question each, each stating what it does not answer. Below, a quotation: RACI is not adopted, BEP section 5.12, because it collapses checking from authorising and coordinating from performing. Below that, a one-way chain: the delivery schedule depends on the container matrix, which depends on the function matrix. Nothing depends on the schedule."* |
| **26 · External imagery** | `NONE REQUIRED` |
| **27 · Live evidence** | `NONE REQUIRED` |
| **28 · Mermaid decision** | **PROHIBITED.** Mermaid would auto-layout the chain and could render the three panels as siblings of a parent node — implying a merged structure. STOP conditions 1 and 4 |
| **29 · Native reconstruction** | Three rectangles + one quotation rectangle + three small boxes + two straight arrow connectors with text labels |
| **30 · Slide source** | `M05-S03` → [`../assets/module-05/M05-S03.md`](../assets/module-05/M05-S03.md) — **CREATED (T5-F-B)** |
| **31 · Status** | `SPECIFICATION COMPLETE` · source `SOURCE COMPLETE` · rendered `NONE` |

---

### `M5V-04` — Slide 4

| Field | Value |
|---|---|
| **1 · Identifier** | `M5V-04` |
| **2 · Slide** | 4 — *Who performs which function — the IM Responsibility Matrix* · 1.5 min |
| **3 · Visual title** | Function groups against functional roles — structure, with the split rule |
| **4 · Teaching purpose** | Show what the matrix allocates, and that its allocations do not share one status |
| **5 · Five-second takeaway** | *Functions down, roles across — and two rows with very different authority.* |
| **6 · Source basis** | `S2` §Purpose, §2, §3.1–§3.7, §Population rule; `S1` §4.6, §5.2, §5.12, §9.4, §9.7 |
| **7 · Statements** | `M5-S4-01` – `M5-S4-19` |
| **8 · Classification profile** | 5 `CONTROLLED` · 10 `SUPPORTING` · 2 `INTERP` · 2 `EXCLUDED` |
| **9 · Governance status** | **`ESTABLISHED ALLOCATION`** (`P4`) · **`UNRESOLVED`** (`D4`) · `PROPOSED GOVERNANCE` (the rest) |
| **10 · Implementation status** | **`IMPLEMENTATION UNVERIFIED`** |
| **11 · Fixed form** | **Matrix skeleton** — seven labelled subject-group bands down the left, nine role columns across the top, **cells showing no values**. Two call-outs to the right: one on an **established** row, one on the **unresolved** row |
| **12 · Why this form** | The structural idea is the teaching point. Showing 297 values would invite reading, and the codes are not defined until Slide 6 |
| **13 · Simplification rule** | Group names may abbreviate. **Role column count may never be reduced below nine**, and **no cell may be populated** |
| **14 · Mandatory visible wording** | `33 information-management functions` · `7 subject groups` · `9 functional roles`; `Functional roles only — no holder is established`; call-out 1 **`ESTABLISHED — BEP §9.4`**; call-out 2 **`UNRESOLVED — BEP §9.7 · TBD ×5 · — ×4 · no allocation made`** |
| **15 · Mandatory status/warning** | **Both call-outs, together.** One alone flattens the split rule |
| **16 · Blocked / unresolved / absent** | **The grid is deliberately unpopulated.** The unresolved row's call-out states the **actual source distribution — `TBD` ×5 (AP, LDP, BM, BC, TTL) · `—` ×4 (Aut, Chk, CDE, Rcp) · `NO ALLOCATION MADE`** — **without drawing the values into the grid**. It must distinguish the **five unresolved** cells from the **four resolved no-function** cells |
| **17 · Geometry** | Grid `x = 48–640`, `y = 120–470`. Seven row bands of equal height; nine columns of equal width. Call-outs `x = 664–912`, vertically aligned to their rows, joined by **short leader lines** |
| **18 · Connector semantics** | **Leader lines only** — they point at a row and mean nothing else. No arrows between grid and call-outs |
| **19 · Build sequence** | Grid frame → row bands → column headings → established call-out → unresolved call-out |
| **20 · Mandatory omissions** | **No function code anywhere** · no person · no company · no appointment or organisation chart · no tick, cross or completion mark |
| **21 · Overclaim risk** | **An empty grid reads as an incomplete document.** A caption must state that the grid is unpopulated **for teaching**, not in the source — the source has 297 populated cells, shown on Slide 7 |
| **22 · Producer-failure test** | **Does any cell contain a character?** If yes, the visual has pre-empted Slide 6 and 7. **Do both call-outs appear?** If only one, the split rule is broken. **Does the unresolved call-out say `TBD` in every column?** If yes, STOP — four of those nine cells are `—` |
| **23 · STOP conditions** | Module-wide 3, 5, 6, 8, 9, **26** |
| **24 · Accessibility** | Reading order: title → grid dimensions → group names → role names → call-out 1 → call-out 2. Grid emptiness stated in words in the alt text. **The `TBD` / `—` split in the call-out must be read as two separate counts**, never as one |
| **25 · Screen-reader description** | *"A matrix skeleton: seven subject-group bands down the left, nine functional-role columns across the top, thirty-three function rows in total. The cells are shown empty for teaching; the source matrix is fully populated. Two call-outs: one marking a row the BEP expressly establishes — Task-Team Lead authorises sharing, BEP 9.4; one marking a row the BEP expressly establishes as unresolved — publication authority, BEP 9.7. That row holds nine populated cells: five TBD, against Appointing Party, Lead Delivery Party, BIM Manager, BIM Coordinator and Task-Team Lead; and four dashes, against Author, Checker, CDE Administration and Recipient. No allocation is made."* |
| **26 · External imagery** | `NONE REQUIRED` |
| **27 · Live evidence** | `NONE REQUIRED` |
| **28 · Mermaid decision** | **PROHIBITED.** Mermaid has no matrix primitive; any graph substitute would imply flow between functions. STOP condition 9 |
| **29 · Native reconstruction** | One PowerPoint table (9 columns × 7 band rows) with empty cells + two call-out shapes + two leader lines |
| **30 · Slide source** | `M05-S04` → [`../assets/module-05/M05-S04.md`](../assets/module-05/M05-S04.md) — **CREATED (T5-F-B)** |
| **31 · Status** | `SPECIFICATION COMPLETE` · source `SOURCE COMPLETE` · rendered `NONE` |

---

### `M5V-05` — Slide 5

| Field | Value |
|---|---|
| **1 · Identifier** | `M5V-05` |
| **2 · Slide** | 5 — *Who produces which container — the Model / Information Responsibility Matrix* · 1.5 min |
| **3 · Visual title** | Party → task team → discipline → container, and where `COORD-01` sits |
| **4 · Teaching purpose** | Show the origination chain, and defuse the six-codes-six-organisations misreading |
| **5 · Five-second takeaway** | *Six containers, six codes — four parties.* |
| **6 · Source basis** | `S1` §4.2, §4.3, §4.4, §7.2; `S3` §Purpose, §2, §3.1, §3.4, §Classification |
| **7 · Statements** | `M5-S5-01` – `M5-S5-22` |
| **8 · Classification profile** | 7 `CONTROLLED` · 12 `SUPPORTING` · 1 `DECISION-RECORD` · 2 `EXCLUDED` |
| **9 · Governance status** | **`PROPOSED GOVERNANCE`** — every §3 allocation, from `TA-03` |
| **10 · Implementation status** | **`IMPLEMENTATION UNVERIFIED`**; `OBSERVED — QUALIFIED` / `NOT DEMONSTRATED` if the observed line is carried |
| **11 · Fixed form** | **Four-stage chain across the top** — party → task team → discipline → container. **Beneath:** six container blocks, with MEC, ELE and PLM **enclosed in one visible party boundary** and FIR **outside it, visibly separate**. **`COORD-01` below and outside the six**, joined by a **different line weight** |
| **12 · Why this form** | The party boundary must be a drawn enclosure, not a colour or a caption — enclosure is what makes "one party, three task teams" unarguable |
| **13 · Simplification rule** | Container labels may reduce to their refs. **The MEP enclosure and the `COORD-01` separation may never be dropped** |
| **14 · Mandatory visible wording** | `party → task team → discipline → container`; the four party names; `A discipline code identifies the information domain — that is all it does`; `PROPOSED GOVERNANCE`; `Originator responsibility remains with the producing task team` |
| **15 · Mandatory status/warning** | `PROPOSED GOVERNANCE` on the container block; **`Intended governance — not an inventory of what exists in the CDE`** |
| **16 · Blocked / unresolved / absent** | **No format, no date, no role holder, no level of information need.** Lead entries, if shown, read `TBD` |
| **17 · Geometry** | Chain `y = 96–160`, four boxes across `x = 48–912`, three arrows. Containers `y = 190–360`; MEP enclosure surrounds MEC/ELE/PLM with ≥ 12 pt internal padding; FIR sits with ≥ 40 pt clear separation from that enclosure. `COORD-01` `y = 396–460`, **horizontally offset from the six** |
| **18 · Connector semantics** | Chain arrows mean **"resolves to"**. The `COORD-01` line means **"aggregates from"** and is drawn **dashed** to mark it as temporary and non-authoring. **No line implies ownership** |
| **19 · Build sequence** | Chain → six containers → MEP enclosure → FIR separation emphasis → `COORD-01` |
| **20 · Mandatory omissions** | No format · no date · no person · no level of information need · **no implication that six codes mean six organisations** · no live-inventory tick |
| **21 · Overclaim risk** | **Six evenly spaced container blocks read as six organisations.** The MEP enclosure is the entire mitigation and must be drawn first, not added as an afterthought |
| **22 · Producer-failure test** | Ask a reader to **count the organisations**. **If the answer is six, the enclosure has failed.** Ask whether `COORD-01` is a seventh discipline container. **If yes, the offset and line weight have failed** |
| **23 · STOP conditions** | Module-wide 3, 7, 9, 22 |
| **24 · Accessibility** | Reading order: chain → containers → enclosure → FIR → `COORD-01`. **The enclosure must be described in words**, since a box outline is invisible to a screen reader |
| **25 · Screen-reader description** | *"A four-stage chain: party, task team, discipline, information container. Below, six discipline containers. Three of them — mechanical, electrical and plumbing — are enclosed within a single boundary labelled MEP Consultant. Fire sits outside that boundary as a separate party. Four parties in total. Below and offset, COORD-01, a coordination construct joined by a dashed aggregation line; it is not a seventh discipline container. All allocations are proposed governance, and this is intended governance, not an inventory."* |
| **26 · External imagery** | `NONE REQUIRED` |
| **27 · Live evidence** | `NONE REQUIRED` |
| **28 · Mermaid decision** | **PROHIBITED.** Mermaid subgraphs would render the MEP enclosure, but auto-layout would place `COORD-01` as a peer or a parent of the six — implying it aggregates authorship. STOP condition 9 |
| **29 · Native reconstruction** | Four boxes + three arrows + six rectangles + one enclosing rectangle (no fill, visible border) + one offset rectangle + one dashed connector |
| **30 · Slide source** | `M05-S05` → [`../assets/module-05/M05-S05.md`](../assets/module-05/M05-S05.md) — **CREATED (T5-F-B)** |
| **31 · Status** | `SPECIFICATION COMPLETE` · source `SOURCE COMPLETE` · rendered `NONE` |

---

### `M5V-06` — Slide 6

| Field | Value |
|---|---|
| **1 · Identifier** | `M5V-06` |
| **2 · Slide** | 6 — *The seven-term grammar — and the two values that carry the gaps* · 1.5 min |
| **3 · Visual title** | Seven function terms, two non-function values, one refusal |
| **4 · Teaching purpose** | Teach the controlled vocabulary **and** its scope — it belongs to one matrix |
| **5 · Five-second takeaway** | *Seven codes, two values that are not codes, and RACI refused on the record.* |
| **6 · Source basis** | `S1` §5.12, §4.6, §9.1, §9.2; `S2` §1 |
| **7 · Statements** | `M5-S6-01` – `M5-S6-20` |
| **8 · Classification profile** | 14 `CONTROLLED` · 3 `SUPPORTING` · 2 `INTERP` · 1 `EXCLUDED` — **the module's most controlled visual** |
| **9 · Governance status** | **`CONTROLLED GOVERNANCE`** — the grammar is BEP §5.12 |
| **10 · Implementation status** | **Not applicable** — a vocabulary carries no implementation state |
| **11 · Fixed form** | **Two visibly detached panels.** Panel A: seven terms with their exact definitions. Panel B: `TBD` and `—`, **separated by a clear gutter of ≥ 40 pt**, under a heading that says they are **not function codes**. Below both: the RACI refusal as a quotation with its reference |
| **12 · Why this form** | The gutter is load-bearing. If `TBD` and `—` share a frame with the seven, they read as an eighth and ninth code |
| **13 · Simplification rule** | Definitions may not be paraphrased — they are quoted controlled wording. **If space is short, reduce type size to the 14 pt floor before cutting words** |
| **14 · Mandatory visible wording** | All seven terms with §5.12 definitions verbatim; *"The matrix will use these terms and no others"*; `TBD` and `—` definitions verbatim; **`Not function codes`**; **`RACI is not adopted`** + reason + `BEP §5.12`; **`This grammar belongs to the IM Responsibility Matrix only`** |
| **15 · Mandatory status/warning** | The scope line — **grammar belongs to `S2` alone**. Without it the slide licenses the codes for use on Slides 9–12 |
| **16 · Blocked / unresolved / absent** | **No R/A/C/I letters. No invented code. No suitability, status or naming code** — none exists |
| **17 · Geometry** | Panel A `x = 48–560`, `y = 96–400`, seven rows. **Gutter `x = 560–600`.** Panel B `x = 600–912`, `y = 96–260`, two rows. Scope line `y = 276–308` under panel B. Refusal block `y = 424–492`, full width |
| **18 · Connector semantics** | **None.** No line joins panel A to panel B — a connector would reunite what the gutter separates |
| **19 · Build sequence** | Panel A → gutter → panel B → scope line → refusal |
| **20 · Mandatory omissions** | No RACI mapping · no eighth code · no application to `S3` or `S4` rows · no colour-coded severity ordering of the seven terms |
| **21 · Overclaim risk** | **Nine rows in one visual field read as one nine-value code set.** The gutter, the separate heading and the *not function codes* label are the three mitigations, and **all three are mandatory** |
| **22 · Producer-failure test** | Ask a reader **how many function codes there are.** **If the answer is nine, the separation has failed.** Ask **which resources use this grammar.** **If the answer is more than one, the scope line has failed** |
| **23 · STOP conditions** | Module-wide 2, 3, 4, 18 |
| **24 · Accessibility** | Reading order: panel A rows → panel B rows → scope → refusal. **The gutter must be described in words** — visual separation is invisible to a screen reader |
| **25 · Screen-reader description** | *"Panel one, seven function terms with their BEP 5.12 definitions: Perform, carries out the activity; Check, verifies against a defined requirement; Authorise, permits progression for a defined purpose; Coordinate, organises across parties or task teams; Accept, receives for an identified purpose; Consult, is asked before the act; Inform, is told after the act. Panel two, visually separate, headed 'not function codes': TBD, allocation unresolved; dash, the role holds no function in this activity. This grammar belongs to the Information Management Responsibility Matrix only. Below: RACI is not adopted, BEP 5.12, because it collapses checking from authorising and coordinating from performing."* |
| **26 · External imagery** | `NONE REQUIRED` |
| **27 · Live evidence** | `NONE REQUIRED` |
| **28 · Mermaid decision** | **PROHIBITED.** A graph would connect terms and imply ordering or hierarchy among the seven, which the source does not state. STOP condition 9 |
| **29 · Native reconstruction** | Two tables (7 rows; 2 rows) with a fixed empty column between them, plus one quotation rectangle. No connectors |
| **30 · Slide source** | `M05-S06` → [`../assets/module-05/M05-S06.md`](../assets/module-05/M05-S06.md) — **CREATED (T5-F-B)** |
| **31 · Status** | `SPECIFICATION COMPLETE` · source `SOURCE COMPLETE` · rendered `NONE` |

---

### `M5V-07` — Slide 7

| Field | Value |
|---|---|
| **1 · Identifier** | `M5V-07` |
| **2 · Slide** | 7 — *Reading a cell: what a populated cell does and does not prove* · 1.5 min |
| **3 · Visual title** | One row × one role = one cell — and the production sequence |
| **4 · Teaching purpose** | Teach cell grammar and fix the limit of what any cell asserts |
| **5 · Five-second takeaway** | *A cell says which function a role holds. Nothing more.* |
| **6 · Source basis** | `S2` §1, §3.1–§3.7 (census by inspection), §3.3, §3.6, §5; `S1` §9.1, §9.3, §9.4, §9.7 |
| **7 · Statements** | `M5-S7-01` – `M5-S7-20` |
| **8 · Classification profile** | 2 `CONTROLLED` · 8 `SUPPORTING` · 8 `INTERP` · 2 `EXCLUDED` |
| **9 · Governance status** | `ESTABLISHED ALLOCATION` (`P4`) · `UNRESOLVED` (`D4`, `D7`) · `PROPOSED GOVERNANCE` (the rest) |
| **10 · Implementation status** | **`IMPLEMENTATION UNVERIFIED`** — a cell records no performance |
| **11 · Fixed form** | **Left:** one row and one column highlighted to their intersection, the cell called out. **Centre:** the four `P1`–`P4` rows as **four separate horizontal bars**, each showing only the values that row actually carries. **Right:** the **complete nine-cell `D4` row** under its nine role headings — **`TBD` in AP, LDP, BM, BC, TTL; `—` in Aut, Chk, CDE, Rcp** — carrying an **`UNRESOLVED`** label and **`NO ALLOCATION MADE`**. **Footer:** the census line |
| **12 · Why this form** | Four separate bars prevent the production rows reading as a flowchart. **The `D4` row must be *shown* as the source records it — all nine cells** — because the contrast is not just *unresolved versus established*: four of `D4`'s cells are **resolved**, and abbreviating them away would teach a row that does not exist |
| **13 · Simplification rule** | The census may reduce to `297 cells · none blank · Au ×2 · Ac ×1`. **The `P1`–`P4` bars may not be merged into one arrow**, and **the four `—` cells of `D4` may not be dropped, summarised or replaced by an ellipsis** — the row is shown complete or not at all |
| **14 · Mandatory visible wording** | `row × column = cell`; `which function this role holds in this activity`; `P1 P2 P3 P4` with their values; `P4 — Au — ESTABLISHED, BEP §9.4`; the nine `D4` cells with the nine role headings; **`UNRESOLVED`**; **`NO ALLOCATION MADE`**; `BEP §9.7`; `Combined values record no order`; the census |
| **15 · Mandatory status/warning** | The two status labels on `P4` and `D4`, **and** a line stating a cell does not record a name, an appointment, occurrence or independence |
| **16 · Blocked / unresolved / absent** | **`D4` is shown exactly as recorded — five `TBD`, four `—` — and is never completed.** The four `—` cells are **populated**, not blank: they record that Author, Checker, CDE Administration and Recipient hold **no function** in that activity. **The row is unresolved even though those four applicability decisions are resolved.** `D7`'s `TBD Ac` may appear as a small annotation, also never completed |
| **17 · Geometry** | Intersection diagram `x = 48–300`, `y = 96–300`. `P1`–`P4` bars `x = 324–616`, four rows of equal height, `y = 96–300`, **≥ 16 pt vertical gaps so they never abut**. `D4` block `x = 640–912`, same vertical band, **visually isolated**: nine equal cells in one row beneath nine role headings, each cell ≥ 28 pt wide so `—` remains legible at 14 pt. Status labels sit immediately beneath the row. Census strip `y = 430–470`, full width |
| **18 · Connector semantics** | **Leader lines only**, from row and column into the cell. **No arrow between `P1`, `P2`, `P3` and `P4`** — an arrow would assert sequence the source does not state |
| **19 · Build sequence** | Intersection → cell call-out → four bars → **`D4` role headings → five `TBD` → four `—` → `UNRESOLVED` → `NO ALLOCATION MADE`** → census |
| **20 · Mandatory omissions** | **No arrow between the production rows** · no tick or completion mark · no person · no populated `D4` · no ordering within a combined value |
| **21 · Overclaim risk** | **Three risks.** Four stacked rows imply a workflow; a populated-looking grid implies work done; and **five `TBD` cells side by side read as a shortlist of candidate authorities**. The third is mitigated by `NO ALLOCATION MADE` and by showing the four `—` cells, which make the row a record of the source rather than a set of options |
| **22 · Producer-failure test** | **Is there an arrow anywhere between `P1` and `P4`?** If yes, remove it. **Does the `D4` row show exactly nine cells — five `TBD` and four `—`?** If any cell is missing, blank, or carries a different value, **STOP**. **Ask a reader who holds publication authority. If the answer names any of the five `TBD` roles, `NO ALLOCATION MADE` has failed** |
| **23 · STOP conditions** | Module-wide 9, 10, 16, **26** |
| **24 · Accessibility** | Reading order: intersection → cell meaning → four rows → `D4` role headings → nine cells → status labels → census. Combined values read aloud as *"holds both functions, in no stated order"*. **Each `D4` cell must be read with its role name**, so the five/four split survives audio |
| **25 · Screen-reader description** | *"Left: one activity row and one role column highlighted to their intersection; the cell records which function that role holds in that activity. Centre: four separate rows — P1, author in WIP; P2, task-team check; P3, readiness check; P4, authorise for controlled sharing, held by the Task-Team Lead, established by BEP 9.4. There is no arrow between them. Right, isolated: the D4 row, authorise publication or exchange, showing all nine cells — TBD against Appointing Party, Lead Delivery Party, BIM Manager, BIM Coordinator and Task-Team Lead; dash against Author, Checker, CDE Administration and Recipient. The row is labelled unresolved under BEP 9.7, and no allocation is made. The five TBD cells are not a shortlist. Footer: 297 cells, none blank; Au appears twice; Ac appears once, inside TBD Ac."* |
| **26 · External imagery** | `NONE REQUIRED` |
| **27 · Live evidence** | `NONE REQUIRED` |
| **28 · Mermaid decision** | **PROHIBITED.** Mermaid would sequence `P1`–`P4`. STOP condition 9 |
| **29 · Native reconstruction** | One small table for the intersection + four separate rectangles + **one isolated 9-column table (one heading row, one value row) for `D4`** + two status text boxes + one text strip + leader lines |
| **30 · Slide source** | `M05-S07` → [`../assets/module-05/M05-S07.md`](../assets/module-05/M05-S07.md) — **CREATED (T5-F-B)** |
| **31 · Status** | `SPECIFICATION COMPLETE` · source `SOURCE COMPLETE` · rendered `NONE` |

---

### `M5V-08` — Slide 8

| Field | Value |
|---|---|
| **1 · Identifier** | `M5V-08` |
| **2 · Slide** | 8 — *One person, two roles — allocation is not independence* · 1.0 min |
| **3 · Visual title** | Separate functions, possibly one participant |
| **4 · Teaching purpose** | Show that a functional separation is not a separation of people |
| **5 · Five-second takeaway** | *Two columns. Possibly one person. Independence not established.* |
| **6 · Source basis** | `S1` §5.8, §5.11, §9.12, §4.6; `S2` §5; `S7` `TA-02`, §Classification vocabulary |
| **7 · Statements** | `M5-S8-01` – `M5-S8-17` |
| **8 · Classification profile** | 8 `CONTROLLED` · 5 `SUPPORTING` · 3 `INTERP` · 1 `EXCLUDED` |
| **9 · Governance status** | `CONTROLLED GOVERNANCE` (§5.8, §5.11, §9.12) · `PROPOSED GOVERNANCE` (`S2` §5) |
| **10 · Implementation status** | **`NOT DEMONSTRATED`** — no independence evidence exists |
| **11 · Fixed form** | **Two role boxes**, Author and Checker, with a **solid boundary between them that remains unbroken**. **One unnamed participant outline spanning both**, drawn so the boundary **stays visible through the overlap**. Beneath: **`INDEPENDENCE — NOT ESTABLISHED`** in words |
| **12 · Why this form** | The boundary surviving the overlap *is* the teaching point: functions stay distinct even when the person does not |
| **13 · Simplification rule** | The participant outline may reduce to a simple rounded rectangle. **The boundary may never be hidden, dashed away or drawn behind the outline** |
| **14 · Mandatory visible wording** | `Author` · `Checker` · `One participant may hold more than one role`; `A self-check is still a checking act against a defined requirement`; **`INDEPENDENCE — NOT ESTABLISHED`**; `TA-02 — no professional authority, appointment, duty or liability`; `Not a defect · not a non-conformance` |
| **15 · Mandatory status/warning** | **`INDEPENDENCE — NOT ESTABLISHED`**, and the *not a defect* line — without the second, the slide reads as an accusation |
| **16 · Blocked / unresolved / absent** | **No name, no headcount, no number of people.** The participant outline is unlabelled |
| **17 · Geometry** | Role boxes `x = 160–460` and `x = 500–800`, `y = 140–300`. **Boundary line at `x = 480`, full height of the boxes, drawn on top.** Participant outline `x = 130–830`, `y = 120–320`, **no fill**, so the boundary reads through it. Status line `y = 350–390`, centred |
| **18 · Connector semantics** | **None.** The overlap is spatial, not a connector. No arrow between Author and Checker |
| **19 · Build sequence** | Two role boxes → boundary → participant outline → status line → *not a defect* line |
| **20 · Mandatory omissions** | **No person icon, no silhouette, no headcount, no name** · no warning triangle, cross or defect symbol · no Module 6 assurance step |
| **21 · Overclaim risk** | **A figure spanning two boxes reads as a criticism.** Neutral line weight, no colour signalling, and the explicit *not a defect · not a non-conformance* line are mandatory |
| **22 · Producer-failure test** | **Is the boundary still visible where the participant outline crosses it?** If not, redraw. **Does anything on the slide look like a warning symbol?** If yes, remove it |
| **23 · STOP conditions** | Module-wide 8, 10 |
| **24 · Accessibility** | Reading order: Author → boundary → Checker → participant → status → *not a defect*. **Overlap described in words** |
| **25 · Screen-reader description** | *"Two role boxes, Author and Checker, separated by a solid boundary. A single unnamed participant outline spans both boxes; the boundary remains visible through it. Beneath: independence — not established. One participant may hold more than one role; a self-check is still a checking act against a defined requirement; the combination is recorded. This is not a defect and not a non-conformance. Under TA-02, exercising a role for training creates no professional authority, appointment, duty or liability."* |
| **26 · External imagery** | `NONE REQUIRED` — **and no person imagery of any kind** |
| **27 · Live evidence** | `NONE REQUIRED` |
| **28 · Mermaid decision** | **PROHIBITED.** Mermaid cannot render a boundary-preserving overlap; it would render a merge or a parent node, asserting exactly the collapse this slide denies |
| **29 · Native reconstruction** | Two rectangles + one line on top + one no-fill rounded rectangle + two text boxes |
| **30 · Slide source** | `M05-S08` → [`../assets/module-05/M05-S08.md`](../assets/module-05/M05-S08.md) — **CREATED (T5-F-B)** |
| **31 · Status** | `SPECIFICATION COMPLETE` · source `SOURCE COMPLETE` · rendered `NONE` |

---

### `M5V-09` — Slide 9

| Field | Value |
|---|---|
| **1 · Identifier** | `M5V-09` |
| **2 · Slide** | 9 — *The Information Delivery Schedule — sixteen fields* · 1.5 min |
| **3 · Visual title** | Sixteen approved fields, grouped for teaching |
| **4 · Teaching purpose** | Show the anatomy of the planning instrument, and separate the four misread fields |
| **5 · Five-second takeaway** | *Sixteen fields. A plan, not a record.* |
| **6 · Source basis** | `S1` §10.13, §10.4, §1.5, §7.3, §10.2, §11.3; `S4` §Purpose, §1, §Classification, §What these entries are not, §Container discipline |
| **7 · Statements** | `M5-S9-01` – `M5-S9-22` |
| **8 · Classification profile** | 4 `CONTROLLED` · 15 `SUPPORTING` · 2 `INTERP` · 1 `EXCLUDED` |
| **9 · Governance status** | `CONTROLLED GOVERNANCE` (the field list, §10.13) · **`PROPOSED GOVERNANCE`** (all entries) |
| **10 · Implementation status** | **`NOT DEMONSTRATED`** — no row evidences a transaction |
| **11 · Fixed form** | **Six labelled group blocks**, containing **sixteen individually visible field names**. A caption labels the grouping as **teaching interpretation**. **Four fields carry a small caution marker**; a side panel gives their four corrections |
| **12 · Why this form** | Grouping aids recall; individual visibility protects the controlled names. Both requirements are absolute and neither may be traded off |
| **13 · Simplification rule** | Group headings may shorten. **No field name may be renamed, merged, abbreviated or omitted — all sixteen appear exactly once** |
| **14 · Mandatory visible wording** | All sixteen controlled field names verbatim; **`Teaching grouping — the schedule lists sixteen fields flat`**; the four corrections; `PROPOSED GOVERNANCE`; `Not a contractual programme`; `No delivery dates or client milestones established` |
| **15 · Mandatory status/warning** | `PROPOSED GOVERNANCE` **and** `A row is a plan, not a record` |
| **16 · Blocked / unresolved / absent** | **No sample values.** No example date, format, milestone or deliverable anywhere on the slide |
| **17 · Geometry** | Six group blocks in two rows of three, `x = 48–912`, `y = 96–340`, ≥ 16 pt gaps. Caption `y = 348–372`. Caution panel `y = 388–470`, full width, four rows |
| **18 · Connector semantics** | **None.** Fields are grouped by containment, not connected — a connector would imply processing order |
| **19 · Build sequence** | Six blocks with all sixteen names → grouping caption → four caution markers → caution panel |
| **20 · Mandatory omissions** | **No example value of any kind** · no date · no format · no milestone · no row that looks like a completed transaction |
| **21 · Overclaim risk** | **A tidy six-group layout reads as the schedule's own structure.** The caption is the only mitigation and must sit **adjacent to the blocks**, not in a corner |
| **22 · Producer-failure test** | **Count the field names. Is the answer exactly sixteen, each appearing once, spelled as in the source?** If not, STOP. **Is the grouping caption visible at projection scale?** If not, enlarge it |
| **23 · STOP conditions** | Module-wide 11, 22, 25 |
| **24 · Accessibility** | Reading order: group 1 → 6, then caption, then cautions. The caution markers must have text equivalents, not shape-only meaning |
| **25 · Screen-reader description** | *"Six teaching groups containing sixteen approved schedule fields, each named once: Delivery ID; Exchange slash Milestone; Information Container; Originating Party; Task Team; Discipline; Lead; Recipient; Purpose; Format; State slash Suitability; Checking Requirement; Authorisation Requirement; Acceptance Criteria; Status; Dependencies. Caption: the grouping is a teaching device; the schedule lists sixteen fields flat. Four carry cautions: Status is the status of the schedule entry, not the information state; State slash Suitability is the CDE state and permitted use; Acceptance Criteria does not establish who may accept; Delivery ID is an internal training reference, not a document number. All entries are proposed governance. A row is a plan, not a record."* |
| **26 · External imagery** | `NONE REQUIRED` |
| **27 · Live evidence** | `NONE REQUIRED` |
| **28 · Mermaid decision** | **PROHIBITED.** Any graph form would connect the fields and imply a workflow through them |
| **29 · Native reconstruction** | Six rectangles containing text lists + one caption text box + one 4-row table |
| **30 · Slide source** | `M05-S09` → [`../assets/module-05/M05-S09.md`](../assets/module-05/M05-S09.md) — **CREATED (T5-F-B)** |
| **31 · Status** | `SPECIFICATION COMPLETE` · source `SOURCE COMPLETE` · rendered `NONE` |

---

### `M5V-10` — Slide 10

| Field | Value |
|---|---|
| **1 · Identifier** | `M5V-10` |
| **2 · Slide** | 10 — *Three delivery events — proposed, conditional, blocked* · 1.5 min |
| **3 · Visual title** | Three event cards, three different conditions |
| **4 · Teaching purpose** | Introduce the three events separately, and teach that their statuses mean three different things |
| **5 · Five-second takeaway** | *Three events, and no two are in the same condition.* |
| **6 · Source basis** | `S4` §2, §3, §3.2, §4, §4.2, §5, §5.1; `S1` §9.4 |
| **7 · Statements** | `M5-S10-01` – `M5-S10-20` |
| **8 · Classification profile** | **0 `CONTROLLED`** · 17 `SUPPORTING` · 1 `INTERP` · 2 `EXCLUDED` — the events are `S4`'s own construction |
| **9 · Governance status** | **`PROPOSED GOVERNANCE`** · **`CONDITIONAL`** · **`BLOCKED`** |
| **10 · Implementation status** | **`NOT DEMONSTRATED`** — no event shown as executed |
| **11 · Fixed form** | **Three cards of identical size**, side by side, **each with its exact status label in a band**. `TRN-E02`'s card carries a **per-affected-container** marker; `TRN-E03`'s carries a forward pointer to Slide 12 |
| **12 · Why this form** | Identical size prevents a status reading as importance. Side-by-side placement without connectors prevents them reading as stages |
| **13 · Simplification rule** | Card body text may compress. **The three status labels are quoted controlled wording and may not be shortened or paraphrased** |
| **14 · Mandatory visible wording** | `TRN-E01 — PROPOSED`; `TRN-E02 — PROPOSED · CONDITIONAL`; `TRN-E03 — PROPOSED — BLOCKED PENDING GOVERNANCE DECISIONS`; `Event-triggered / TBD`; `activated per affected container only`; `An unactivated row is not a pending exchange`; `Blocked is not overdue, rejected or unfinished` |
| **15 · Mandatory status/warning** | All three status labels, **and** the *blocked is not overdue* line |
| **16 · Blocked / unresolved / absent** | **`TRN-E03` is visibly blocked and its blockers are not shown here** — Slide 12 owns them |
| **17 · Geometry** | Three cards, equal width ≈ 272 pt, `x = 48–912`, `y = 110–420`, gaps ≈ 24 pt. **Status band = top 48 pt of each card.** Caution strip `y = 440–480`, full width. **Cards never touch** |
| **18 · Connector semantics** | **NONE PERMITTED.** No arrow between the cards, in any direction — STOP condition 12's neighbour: a sequence arrow would assert a mandatory order |
| **19 · Build sequence** | Three cards together → status bands → per-container marker → caution strip |
| **20 · Mandatory omissions** | **No timeline, no calendar, no date, no frequency** · **no arrow between cards** · no numbering that implies order · no tick, cross or overdue marker |
| **21 · Overclaim risk** | **Three left-to-right cards read as three stages.** Equal sizing, absent connectors and the absence of any ordinal numbering are the mitigations |
| **22 · Producer-failure test** | **Is there any arrow, chevron or numeral suggesting order?** If yes, remove it. **Does `TRN-E03` look late rather than blocked?** If yes, the wording has failed |
| **23 · STOP conditions** | Module-wide 11, 22 |
| **24 · Accessibility** | Reading order: card 1 → 2 → 3 → caution. Status carried by the words in each band, never by band colour |
| **25 · Screen-reader description** | *"Three cards of equal size, no arrows between them. Card one: TRN-E01, design coordination share, status proposed, event-triggered or TBD, state Shared, coordination use only, six separate exchanges. Card two: TRN-E02, coordination reshare, status proposed and conditional, repeatable with no calendar frequency, activated per affected container only; an unactivated row is not a pending exchange. Card three: TRN-E03, controlled design review, status proposed — blocked pending governance decisions, timing TBD. Below: blocked is not overdue, rejected or unfinished."* |
| **26 · External imagery** | `NONE REQUIRED` |
| **27 · Live evidence** | `NONE REQUIRED` |
| **28 · Mermaid decision** | **PROHIBITED.** Mermaid renders nodes in sequence by default; three event nodes would acquire an implied order. STOP condition 12 |
| **29 · Native reconstruction** | Three rectangles, each with a header band rectangle, plus one caution text strip. **No connectors** |
| **30 · Slide source** | `M05-S10` → [`../assets/module-05/M05-S10.md`](../assets/module-05/M05-S10.md) — **CREATED (T5-F-B)** |
| **31 · Status** | `SPECIFICATION COMPLETE` · source `SOURCE COMPLETE` · rendered `NONE` |

---

### `M5V-11` — Slide 11

| Field | Value |
|---|---|
| **1 · Identifier** | `M5V-11` |
| **2 · Slide** | 11 — *A delivery event is not an information-state transition* · 1.5 min |
| **3 · Visual title** | Two parallel tracks — events above, controlled steps below |
| **4 · Teaching purpose** | Hold the boundary: an event **uses** a transition without **being** one |
| **5 · Five-second takeaway** | *Only two steps change the state — and one of them is blocked.* |
| **6 · Source basis** | `S5` §3, §3.1, §3.2, §9, §10, §11; `S1` §10.11, §9.7, §7.10; `S4` §4.1 |
| **7 · Statements** | `M5-S11-01` – `M5-S11-22` |
| **8 · Classification profile** | 1 `CONTROLLED` · 14 `SUPPORTING` · 1 `MODULE-2-4` · 4 `INTERP` · 2 `EXCLUDED` |
| **9 · Governance status** | `PROPOSED GOVERNANCE` (`S5`) · **`BLOCKED`** (`T4`) · `UNRESOLVED` (the authorising function) |
| **10 · Implementation status** | **`NOT DEMONSTRATED`** |
| **11 · Fixed form** | **Two horizontal tracks.** Upper: three event concepts. Lower: the eight controlled steps, with **`T1` and `T4` visually marked as state transitions** and the other six marked as **action, use, event, event, decision/status, rework** — **in words**. **Vertical dependency connectors** from each event to the steps it uses. **The `TRN-E03` → `T4` connector is drawn broken.** A right-hand strip shows the four distinct objects |
| **12 · Why this form** | Two tracks make the categories structurally separate. A broken connector shows the block without removing the dependency |
| **13 · Simplification rule** | Step descriptions may reduce to their kind word. **The `T1`/`T4` marking, the broken connector and the four-object strip may not be dropped** |
| **14 · Mandatory visible wording** | `An event uses a transition — it is not that transition`; `Only T1 and T4 change the information state`; the kind of each of the eight steps; `T4 — BLOCKED · no available authorising function`; `Information remains Shared`; the four §10.11 definitions; **`Delivered, Received and Accepted are not information states`** |
| **15 · Mandatory status/warning** | **`T4 — BLOCKED`** and **`Information remains Shared`** |
| **16 · Blocked / unresolved / absent** | **The `T4` connector is broken and no route continues past it.** `T5`, `T6`, `T7` may appear but **must be shown as leaving the state unchanged** |
| **17 · Geometry** | Event track `y = 110–190`, three boxes across `x = 48–700`. Step track `y = 300–380`, eight boxes across `x = 48–700`. Connectors run vertically in the band `y = 190–300`. Four-object strip `x = 724–912`, `y = 110–380`. **The tracks never merge and never share a box** |
| **18 · Connector semantics** | **Vertical connectors mean "uses / depends upon" — never identity.** Each is labelled `uses`. **No equals sign, no double-headed arrow, no shared node.** The `TRN-E03` connector is **drawn with a visible break and labelled `BLOCKED`** |
| **19 · Build sequence** | Step track → `T1`/`T4` marking → event track → `uses` connectors → broken `T4` connector → four-object strip |
| **20 · Mandatory omissions** | **No arrow between the three events** · **no `T1`→`T2`→…→`T8` sequence arrow** · **no Delivered, Received or Accepted state box** · no completed route past `T4` |
| **21 · Overclaim risk** | **Eight steps in a row read as eight sequential transitions.** Mitigated by marking only `T1` and `T4` as state transitions **in words**, and by giving the other six their own kind labels rather than a shared arrow |
| **22 · Producer-failure test** | **Does any connector look like an equals sign or a merge?** If yes, redraw. **Is there a box labelled Delivered, Received or Accepted in the state track?** If yes, STOP |
| **23 · STOP conditions** | Module-wide 12, 13, 14, 15 |
| **24 · Accessibility** | Reading order: events → steps → connectors → four objects. **Connector labels read aloud** — the break must be described as *blocked*, not left to visual inference |
| **25 · Screen-reader description** | *"Two parallel tracks. Upper: three delivery-event concepts. Lower: eight controlled steps, of which only T1 and T4 are marked state transitions; T2 is a receiving-team action, T3 a use or context, T5 and T6 events, T7 a decision or status, T8 rework. Vertical connectors labelled 'uses' join TRN-E01 to T1 and T3; TRN-E02 to T8, T1 and T3; and TRN-E03 to T4. The TRN-E03 connector is drawn broken and labelled blocked: T4 has no available authorising function and information remains Shared. A side strip lists four distinct objects — Published, Delivered, Received, Accepted — and states that Delivered, Received and Accepted are not information states."* |
| **26 · External imagery** | `NONE REQUIRED` |
| **27 · Live evidence** | `NONE REQUIRED` |
| **28 · Mermaid decision** | **PROHIBITED — the strongest case in the module.** Mermaid's auto-layout would sequence the eight steps, would route the blocked edge as a normal edge, and offers no reliable way to render a *broken* connector. STOP conditions 12, 13, 14 |
| **29 · Native reconstruction** | Eleven rectangles + labelled straight connectors + one connector drawn as two segments with a visible gap and a `BLOCKED` label + one side table |
| **30 · Slide source** | `M05-S11` → [`../assets/module-05/M05-S11.md`](../assets/module-05/M05-S11.md) — **CREATED (T5-F-B)** |
| **31 · Status** | `SPECIFICATION COMPLETE` · source `SOURCE COMPLETE` · rendered `NONE` |

---

### `M5V-12` — Slide 12

| Field | Value |
|---|---|
| **1 · Identifier** | `M5V-12` |
| **2 · Slide** | 12 — *Why `TRN-E03` is blocked — five matters, not one* · 1.5 min |
| **3 · Visual title** | Five separately typed blockers, all closed |
| **4 · Teaching purpose** | Show governance working by stopping, and that the block is five independent matters |
| **5 · Five-second takeaway** | *Five independent matters. Every one typed. None blank.* |
| **6 · Source basis** | `S4` §5, §5.1, §5.2; `S1` §9.7, §9.8, §10.4, §10.11, §11.9, §2.3, §5.3; `S5` §11; `S8` `AD-001`; `S9` §7, §9; `S7` `OF-003`, `PAD-001` |
| **7 · Statements** | `M5-S12-01` – `M5-S12-20` |
| **8 · Classification profile** | 1 `CONTROLLED` · 12 `SUPPORTING` · 2 `DECISION-RECORD` · 3 `INTERP` · 2 `EXCLUDED` |
| **9 · Governance status** | **`BLOCKED`** · **`UNRESOLVED`** ×5 |
| **10 · Implementation status** | **`NOT DEMONSTRATED`** |
| **11 · Fixed form** | **Five closed gates in one row**, each carrying **its matter and its actual recorded status text**. Beneath: the consequence line. To one side: a **small variance note**. A separate footer carries the **publication-arrangement boundary** |
| **12 · Why this form** | Five gates make independence structural — five separate closures, not one barrier. The typed status inside each gate is the content, not a label on it |
| **13 · Simplification rule** | Matter names may shorten. **The status text may never be shortened, abbreviated or replaced by a symbol** |
| **14 · Mandatory visible wording** | The five matters with `UNRESOLVED — TBD` ×2, `Not established` ×2, `Not defined` ×1; `Resolving one releases none of the others`; **`T4 BLOCKED — INFORMATION REMAINS SHARED`**; the variance note; the publication-arrangement boundary |
| **15 · Mandatory status/warning** | **`T4 BLOCKED — INFORMATION REMAINS SHARED`**, and each gate's own typed status |
| **16 · Blocked / unresolved / absent** | **All five gates closed. None opening, none opened, none blank.** **No sixth primary gate is drawn** |
| **17 · Geometry** | Five gates across `x = 48–780`, equal width ≈ 134 pt, `y = 130–330`, gaps ≈ 12 pt. **Status text occupies the lower third of each gate.** Variance note `x = 800–912`, `y = 130–330`, visibly smaller. Consequence line `y = 356–396`, full width. Boundary footer `y = 420–480` |
| **18 · Connector semantics** | **None between the gates** — a connector would imply that clearing one leads to the next, which is exactly the misreading this slide exists to prevent |
| **19 · Build sequence** | Five gates → five status texts → consequence line → variance note → boundary footer |
| **20 · Mandatory omissions** | **No blank or empty box** · **no sixth primary gate** · no gate shown opening · no progress bar · no "4 of 5 resolved" device · no Module 6 procedure |
| **21 · Overclaim risk** | **Five gates in a row read as five sequential hurdles.** The absence of connectors and the explicit *resolving one releases none of the others* line are the mitigations |
| **22 · Producer-failure test** | **Is any gate empty, or does any carry a symbol instead of its status words?** If yes, STOP. **Does the variance note look like a sixth gate?** If yes, reduce and reposition it |
| **23 · STOP conditions** | Module-wide 14, 15, 16, 17, 21, 22 |
| **24 · Accessibility** | Reading order: gate 1 → 5, consequence, variance, boundary. **Closed state described in words**, never by icon alone |
| **25 · Screen-reader description** | *"Five closed gates. One: publication or exchange authorisation authority — unresolved, TBD. Two: recipient acceptance authority — unresolved, TBD, recipient-dependent. Three: recipient identity — not established. Four: required formats — not established, no approved standard. Five: deliverable set — not defined. These are independent; resolving one releases none of the others. T4 blocked; information remains Shared. A smaller side note records that the delivery schedule counts five blocking matters and the CDE workflow strategy enumerates six prerequisite lines; neither list has been rewritten. Footer: the approved Training Baseline publication arrangement concerns the documentation set and does not establish project publication authority, unblock T4, or release TRN-E03."* |
| **26 · External imagery** | `NONE REQUIRED` |
| **27 · Live evidence** | `NONE REQUIRED` — `S9` quoted as text |
| **28 · Mermaid decision** | **PROHIBITED.** Mermaid would chain the gates and could render an edge past a closed node, implying a traversable route. STOP conditions 14, 16 |
| **29 · Native reconstruction** | Five rectangles with internal text blocks + one small side text box + two full-width text strips. **No connectors** |
| **30 · Slide source** | `M05-S12` → [`../assets/module-05/M05-S12.md`](../assets/module-05/M05-S12.md) — **CREATED (T5-F-B)** |
| **31 · Status** | `SPECIFICATION COMPLETE` · source `SOURCE COMPLETE` · rendered `NONE` |

---

### `M5V-13` — Slide 13

| Field | Value |
|---|---|
| **1 · Identifier** | `M5V-13` |
| **2 · Slide** | 13 — *Nothing is blank — how Harrismith names an absence* · 1.0 min |
| **3 · Visual title** | Seven typed markers — not one universal code set |
| **4 · Teaching purpose** | Teach the seven markers as **seven different statements**, two of which are resolved |
| **5 · Five-second takeaway** | *Seven typed markers. Not one blank. Not all "not yet".* |
| **6 · Source basis** | `S2` §1, §6; `S3` §3.4, §4, §6; `S4` §2, §4.2, §5.1, §7; `S5` §11; `S1` §2.3, §5.3, §11.9 |
| **7 · Statements** | `M5-S13-01` – `M5-S13-20` |
| **8 · Classification profile** | **0 `CONTROLLED`** · 11 `SUPPORTING` · 8 `INTERP` · 1 `EXCLUDED` — the BEP publishes no absence vocabulary |
| **9 · Governance status** | `UNRESOLVED` ×3 · `PROPOSED GOVERNANCE` ×2 · `CONDITIONAL` · `BLOCKED` |
| **10 · Implementation status** | **Not applicable** — the markers describe records, not implementation |
| **11 · Fixed form** | **A seven-row reference panel with four columns:** marker · the question it answers · **outcome** · one bounded Harrismith example. **`TBD` and `—` are adjacent rows, visibly separated by a rule.** A panel label states the grouping is a teaching interpretation |
| **12 · Why this form** | The **outcome column** is the correction that makes `—` and `Not applicable` visibly resolved. Without it the panel reads as seven flavours of "unknown" |
| **13 · Simplification rule** | Examples may shorten to a single ref. **The outcome column may never be dropped, merged into the question column, or reduced to a symbol** |
| **14 · Mandatory visible wording** | All seven markers; **outcome words: `UNRESOLVED` ×3, `RESOLVED — no function`, `RESOLVED — does not apply`, `TRIGGER-DEPENDENT`, `CANNOT PROCEED`**; **`Teaching grouping — not a controlled code set`**; **`Only the IM Responsibility Matrix publishes a legend`**; `Nothing is blank` |
| **15 · Mandatory status/warning** | The panel label **`Teaching grouping — not a controlled code set`** |
| **16 · Blocked / unresolved / absent** | **No eighth marker. No replacement vocabulary. No claim that the sources agree** |
| **17 · Geometry** | Panel `x = 48–912`, `y = 110–430`, seven rows of equal height, four columns of roughly `160 / 240 / 200 / 264` pt. **A visible rule between the `TBD` and `—` rows.** Label strip `y = 440–476` |
| **18 · Connector semantics** | **None.** A table, not a diagram |
| **19 · Build sequence** | Panel frame → column headings → seven rows → `TBD`/`—` separating rule → label strip |
| **20 · Mandatory omissions** | **No "seven ways to say not yet" heading or equivalent umbrella** · no severity ordering · no colour-graded scale from "known" to "unknown" · no proposed unified vocabulary |
| **21 · Overclaim risk** | **A seven-row table reads as a controlled code set, and a uniform column reads as seven synonyms.** The label strip and the outcome column are the two mitigations, and **both are mandatory** |
| **22 · Producer-failure test** | **Ask a reader what `—` means. If the answer contains "unknown", "not yet" or "blank", the outcome column has failed.** **Ask whether this is a project code set. If yes, the label strip has failed** |
| **23 · STOP conditions** | Module-wide 17, 18, 19, 20, 21 |
| **24 · Accessibility** | Reading order row by row, all four columns. **Outcome read aloud with every marker** — the distinction must survive audio |
| **25 · Screen-reader description** | *"A seven-row panel labelled 'teaching grouping — not a controlled code set'. Row one: TBD, who or what, unresolved, publication authority. Row two, separated by a rule: dash, does this role act here, resolved — no function, one hundred and thirty-one cells of the IM matrix. Row three: not defined, what content is required, unresolved, final deliverable set. Row four: not established, whose identity or authority, unresolved, recipient identity. Row five: not applicable, does this field apply, resolved — does not apply, COORD-01 originating party. Row six: conditional, does this row activate, trigger-dependent, TRN-E02. Row seven: blocked, can this proceed, cannot proceed, TRN-E03 and T4. Only the IM Responsibility Matrix publishes a legend. Nothing is blank."* |
| **26 · External imagery** | `NONE REQUIRED` |
| **27 · Live evidence** | `NONE REQUIRED` |
| **28 · Mermaid decision** | **PROHIBITED.** A graph form would relate the markers to one another and imply a shared scale or hierarchy of certainty. STOP condition 20 |
| **29 · Native reconstruction** | One 7 × 4 PowerPoint table with a heavier rule between rows one and two + one label text box |
| **30 · Slide source** | `M05-S13` → [`../assets/module-05/M05-S13.md`](../assets/module-05/M05-S13.md) — **CREATED (T5-F-B)** |
| **31 · Status** | `SPECIFICATION COMPLETE` · source `SOURCE COMPLETE` · rendered `NONE` |

---

### `M5V-14` — Slide 14

| Field | Value |
|---|---|
| **1 · Identifier** | `M5V-14` |
| **2 · Slide** | 14 — *What Triviron must decide before drawing a matrix* · 2.0 min |
| **3 · Visual title** | Five decision groups — questions only |
| **4 · Teaching purpose** | Transfer the method, and answer nothing on Triviron's behalf |
| **5 · Five-second takeaway** | *Every field says: not yet established.* |
| **6 · Source basis** | `S15` §2; `S1` §1.5, §4.2, §4.3, §4.6, §5.2, §5.11, §5.12, §7.2, §9, §10.5, §10.13, §12.3, §12.7, §12.9, §11.3; `S2` §Population rule; `S3` §Classification; `S4` §2, §Classification; `S7` `TA-02`, `TA-03` |
| **7 · Statements** | `M5-S14-01` – `M5-S14-22` |
| **8 · Classification profile** | 2 `CONTROLLED` · 5 `SUPPORTING` · 3 `TEACHING-PLAN` · 9 `INTERP` · **1 `SYNTH`** · 2 `EXCLUDED` |
| **9 · Governance status** | **`NOT YET ESTABLISHED`** throughout · `PROPOSED GOVERNANCE` / `ESTABLISHED ALLOCATION` only where a **Harrismith** example is labelled as such |
| **10 · Implementation status** | **Not applicable** — nothing exists to implement |
| **11 · Fixed form** | **A five-group question checklist.** Each group is a labelled block containing its questions, and **each block carries one answer area marked `NOT YET ESTABLISHED`**. A separate side panel gives the **Harrismith status contrast**, labelled *example of method, not a recommendation*. **A closing marker strip runs across the foot** |
| **12 · Why this form** | A visible, permanently empty answer area per group is what makes the slide structurally incapable of asserting a Triviron answer |
| **13 · Simplification rule** | Questions may reduce to keywords. **No answer area may be removed, and none may be filled — including with an example** |
| **14 · Mandatory visible wording** | The five group names; at least three questions per group; **`NOT YET ESTABLISHED`** in every answer area; the Harrismith status contrast — **IM matrix `SPLIT`, container matrix `PROPOSED GOVERNANCE`, schedule `PROPOSED GOVERNANCE`**; `Example of method — not a recommendation`; **`Triviron responsibility and delivery basis — not yet established`** |
| **15 · Mandatory status/warning** | `NOT YET ESTABLISHED` ×5, **and** the closing marker |
| **16 · Blocked / unresolved / absent** | **Every answer area is permanently empty apart from its status text.** No Harrismith value appears in any answer area |
| **17 · Geometry** | Five group blocks in a column-pair layout across `x = 48–700`, `y = 96–430`. Answer area = **lower 40 pt of each block, bordered, containing only the status text**. Harrismith contrast panel `x = 724–912`, `y = 96–430`, **visually subordinate** — smaller type, lighter border. Closing strip `y = 450–496`, full width |
| **18 · Connector semantics** | **None.** No arrow from a Harrismith example to a Triviron question — that would be a recommendation drawn as a line |
| **19 · Build sequence** | Five blocks → questions → answer areas with their status → Harrismith contrast panel → closing strip |
| **20 · Mandatory omissions** | **No Triviron party, task team, role holder, container, event, recipient, format, date, deliverable or acceptance criterion** · no Harrismith value as a default · no arrow from example to question · **no collective claim that every Harrismith allocation is proposed** · no Module 7 output · no Module 6 workflow |
| **21 · Overclaim risk** | **A Harrismith panel beside a question list reads as an answer key.** Mitigated by subordinate styling, the *example of method* label, the absence of connectors, and by the split-status row that makes the Harrismith column visibly *not* a single tidy answer |
| **22 · Producer-failure test** | **Cover the closing strip. Can a reader extract a single Triviron answer from anything on the slide?** If yes, STOP. **Does the Harrismith panel state one status for all three resources?** If yes, the split-status requirement has failed |
| **23 · STOP conditions** | Module-wide 5, 6, 22, 24, 25 |
| **24 · Accessibility** | Reading order: group 1 → 5 with each answer area read as `not yet established`, then the Harrismith panel, then the closing marker. **The subordination of the Harrismith panel must be stated in words**, since styling alone does not survive audio |
| **25 · Screen-reader description** | *"Five decision groups, each a block of questions with an answer area marked 'not yet established'. Group one, delivery organisation. Group two, responsibility architecture. Group three, information-container architecture. Group four, delivery planning. Group five, governance and evidence. To the side, a subordinate panel headed 'example of method — not a recommendation', recording that Harrismith's Information Management Responsibility Matrix carries a split status — proposals unless the BEP expressly establishes them — while its container matrix and delivery schedule are proposed governance. None of it transfers automatically. Closing marker: Triviron responsibility and delivery basis — not yet established."* |
| **26 · External imagery** | `NONE REQUIRED` |
| **27 · Live evidence** | `NONE REQUIRED` |
| **28 · Mermaid decision** | **PROHIBITED.** Any graph would connect Harrismith examples to Triviron questions, which is a recommendation regardless of edge label. STOP condition 24 |
| **29 · Native reconstruction** | Five rectangles, each containing a text list and a bordered sub-rectangle + one subordinate side panel + one footer strip. **No connectors** |
| **30 · Slide source** | `M05-S14` → [`../assets/module-05/M05-S14.md`](../assets/module-05/M05-S14.md) — **CREATED (T5-F-B)** |
| **31 · Status** | `SPECIFICATION COMPLETE` · source `SOURCE COMPLETE` · rendered `NONE` |

---

## 5. Specification register

| Visual | Slide | Form | Mermaid | External imagery | Live evidence | Specification | Source |
|---|---:|---|---|---|---|---|---|
| `M5V-01` | 1 | Three panels + footer | **Prohibited** | `NONE REQUIRED` | `NONE REQUIRED` | `SPECIFICATION COMPLETE` | **`SOURCE COMPLETE`** |
| `M5V-02` | 2 | Field band + two columns | **Prohibited** | `NONE REQUIRED` | `NONE REQUIRED` | `SPECIFICATION COMPLETE` | **`SOURCE COMPLETE`** |
| `M5V-03` | 3 | Three panels + quotation + chain | **Prohibited** | `NONE REQUIRED` | `NONE REQUIRED` | `SPECIFICATION COMPLETE` | **`SOURCE COMPLETE`** |
| `M5V-04` | 4 | Unpopulated matrix skeleton + two call-outs | **Prohibited** | `NONE REQUIRED` | `NONE REQUIRED` | `SPECIFICATION COMPLETE` | **`SOURCE COMPLETE`** |
| `M5V-05` | 5 | Chain + enclosed containers + offset construct | **Prohibited** | `NONE REQUIRED` | `NONE REQUIRED` | `SPECIFICATION COMPLETE` | **`SOURCE COMPLETE`** |
| `M5V-06` | 6 | Two gutter-separated panels + quotation | **Prohibited** | `NONE REQUIRED` | `NONE REQUIRED` | `SPECIFICATION COMPLETE` | **`SOURCE COMPLETE`** |
| `M5V-07` | 7 | Intersection + four bars + isolated row | **Prohibited** | `NONE REQUIRED` | `NONE REQUIRED` | `SPECIFICATION COMPLETE` | **`SOURCE COMPLETE`** |
| `M5V-08` | 8 | Two boxes + preserved boundary + overlap | **Prohibited** | `NONE REQUIRED` | `NONE REQUIRED` | `SPECIFICATION COMPLETE` | **`SOURCE COMPLETE`** |
| `M5V-09` | 9 | Six groups, sixteen named fields | **Prohibited** | `NONE REQUIRED` | `NONE REQUIRED` | `SPECIFICATION COMPLETE` | **`SOURCE COMPLETE`** |
| `M5V-10` | 10 | Three status cards, no connectors | **Prohibited** | `NONE REQUIRED` | `NONE REQUIRED` | `SPECIFICATION COMPLETE` | **`SOURCE COMPLETE`** |
| `M5V-11` | 11 | Two tracks + `uses` connectors + broken link | **Prohibited** | `NONE REQUIRED` | `NONE REQUIRED` | `SPECIFICATION COMPLETE` | **`SOURCE COMPLETE`** |
| `M5V-12` | 12 | Five closed typed gates | **Prohibited** | `NONE REQUIRED` | `NONE REQUIRED` | `SPECIFICATION COMPLETE` | **`SOURCE COMPLETE`** |
| `M5V-13` | 13 | Seven-row panel with outcome column | **Prohibited** | `NONE REQUIRED` | `NONE REQUIRED` | `SPECIFICATION COMPLETE` | **`SOURCE COMPLETE`** |
| `M5V-14` | 14 | Five question groups + empty answer areas | **Prohibited** | `NONE REQUIRED` | `NONE REQUIRED` | `SPECIFICATION COMPLETE` | **`SOURCE COMPLETE`** |

**Fourteen specifications. Fourteen slides. Fourteen source files, all
`SOURCE COMPLETE`. Zero Mermaid. Zero external images. Zero live-evidence
requirements. Zero rendered assets.**

---

## 6. Status

| Field | Value |
|---|---|
| Increment | **T5-F-B — COMPLETE.** Visual-source baseline **COMPLETE**. Production status reconciled after **T5-G** in **T5-G-R** |
| Specifications | **`M5V-01`–`M5V-14`, all `SPECIFICATION COMPLETE` and `ACCEPTED`** |
| Visual-source files | **`M05-S01`–`M05-S14`, all `SOURCE COMPLETE`** |
| Asset directory | [`../assets/module-05/`](../assets/module-05/) |
| Visual register / slide-visual map | **Complete** |
| Rendered assets | **NONE.** No rendering attempted; no renderer installed |
| Assembly package | **COMPLETE (`T5-G`)** — [`presentation/`](presentation/), **seven** production-handoff files |
| PowerPoint | **PRODUCED — `REV01`** (`T5-H`, corrected in `T5-H-R1`); **ACCEPTED**. Outside this repository; **not committed here** |
| Teaching-content baseline | **COMPLETE** and unchanged by this increment |
| Timing | **`20.0 minutes allocated — not measured`** |
| Next | **Module 5 rehearsal and measured timing** |
