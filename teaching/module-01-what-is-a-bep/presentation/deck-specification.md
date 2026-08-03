# Module 1 — Deck Specification

**Status:** Production specification. **Not governance.** Not a built deck.

---

## 1. Global details

| Field | Value |
|---|---|
| **Title** | What Is a BIM Execution Plan? |
| **Subtitle** | The Harrismith Fire Station as a worked example |
| **Module** | Module 1 — What is a BIM Execution Plan? |
| **Audience** | Mixed multidisciplinary project audience — some Revit users, some who never open a model, at least one whose interest is commercial |
| **Planned duration** | **20 minutes**, plus questions |
| **Slides** | **14** |
| **Objective** | Enable the audience to understand what a BEP is, why it exists, who acts on it, and what it changes about how a project handles information |
| **Central teaching message** | *A BIM Execution Plan is the project team's agreed method for producing, coordinating, checking, sharing and approving information.* |
| **Opening proposition** | The questions a BEP answers get answered on every project — deliberately, or accidentally |
| **Closing proposition** | Harrismith gives a tested structure and a set of questions, not a completed BEP |

**Fuller working definition**, where the audience needs more precision:

> A BIM Execution Plan defines how the project team will produce, manage,
> exchange, coordinate, review and deliver information to satisfy the project's
> information requirements.

Both definitions are **teaching wording**. Neither replaces the authoritative
BEP's own purpose statement.

## 2. Narrative arc

Six blocks. The audience should be able to feel the hinge between each.

| # | Block | Slides | Time | The move it makes |
|---|---|---|---|---|
| 1 | **The project information problem** | 1–2 | 3 min | From "another governance document" to "a situation you recognise" |
| 2 | **The BEP as the agreed response** | 3 | 1 min | From problem to definition — six actions |
| 3 | **Roles and supporting management instruments** | 4–8 | 9 min | From definition to operating system: who agrees it, what it contains, how responsibility and delivery are recorded |
| 4 | **CDE and coordination controls** | 9–12 | 4 min | From plan to operation: how information moves and how interfaces are managed |
| 5 | **Approval versus implementation** | 13 | 1.5 min | From "we have a BEP" to "are we doing it?" |
| 6 | **Transfer to Triviron** | 14 | 1.5 min | From worked example to the audience's own decisions |

**Block 3 is the load-bearing one.** It is where the audience either understands
that a BEP is an operating agreement or concludes it is paperwork.

**Blocks 5 and 6 are the two that make the talk worth giving.** If the session
runs long, take time from Block 3 or Slide 11 — never from these.

## 3. Design approach

A restrained professional BIM-management style. **No final corporate or Triviron
identity is established here** — that is a later decision, deliberately not taken
in this increment.

### 3.1 Format and hierarchy

| Element | Specification |
|---|---|
| **Aspect ratio** | **16:9** |
| **Title** | One line, sentence case, largest element. Never wraps to three lines |
| **Subtitle / main statement** | One line, clearly subordinate to the title, clearly dominant over supporting items |
| **Supporting items** | Short labels or single-line bullets. **Maximum five per slide** |
| **Body text quantity** | **Roughly 40 words visible per slide, excluding diagram labels.** Slide 1 and Slide 13's quotation are the deliberate exceptions |
| **Fonts** | Any clean sans-serif already available to the producer. **No specific font is specified** — do not introduce one that must be installed |
| **Type sizes** | Nothing below roughly 18 pt equivalent at 16:9. If it needs to be smaller, it does not belong on the slide |

### 3.2 Diagrams

| Rule | |
|---|---|
| Placement | One diagram per slide, given the dominant area — typically right or centre |
| Complexity | Six to eight nodes maximum. Beyond that, split into builds |
| Labels | Node labels short enough to read at projection distance without leaning forward |
| Arrows | **Semantically meaningful.** Solid = progresses to, by decision. Plain line = holds detail for. **Dashed = unreached, unresolved or not-yet-real** |
| Consistency | The same shape and weight means the same thing on every slide |

### 3.3 Tables

Tables appear only where a document's *structure* is the teaching point — Slides
5, 7, 8 and 13.

| Rule | |
|---|---|
| Maximum | **Five rows, three columns** on any slide |
| Never | A raw responsibility matrix, a raw sixteen-field schedule, a raw sixteen-step process, or a source-map extract |
| Extracts | Cropped to the rows that carry the message, and captioned as an extract |

### 3.4 Whitespace and consistency

- Generous margins. A crowded slide is an unread slide.
- One principal message per slide. If it needs an "and", split it.
- Consistent title position and size across all fourteen slides.
- No gradients, shadows, icon sets, stock photography or product chrome.

### 3.5 Footers and source notes

| Rule | |
|---|---|
| Placement | Bottom of slide, small, low-contrast — legible but unobtrusive |
| Content | Short source attribution where a claim is quoted or extracted, e.g. `BEP §13.1` |
| Never | A full file path. `supporting/information-management-responsibility-matrix.md` is unreadable projected — use the document's plain-English name |
| Restraint | **Not every slide needs a source note.** Use them where a claim is quoted, extracted or likely to be challenged |

### 3.6 Unresolved and blocked matters

**These are shown, not smoothed.** Three visuals are deliberately incomplete, and
completing them would misrepresent the source:

| Slide | What stays visibly incomplete |
|---|---|
| 4 | The `controlled publication` step — not reached |
| 8 | TRN-E03 — **BLOCKED** |
| 10 | The T4 transition — **authority unresolved, blocked** |
| 14 | The implemented Triviron BEP — does not exist |

Treatment: dashed outline, or an explicit `Authority unresolved` / `Blocked`
label. **Never** a solid box, a tick, or a completion indicator.

### 3.7 Teaching synthesis

Where the presenter's framing is not the source's, the slide says so —
unobtrusively, in a footer or a small corner label.

Required on **Slides 5 and 14**. Optional but recommended on **Slide 3**.

Do not label every slide; over-labelling makes the labels invisible.

### 3.8 Optional external visuals

`V1`, `V9` and `V10` do not exist in the repository. The deck is built and
delivered **without them**.

- **Never** fabricate, AI-generate or substitute an image presented as project
  evidence.
- If a genuine, verified image is later supplied, it upgrades Slide 1 — it does
  not rescue it.
- See [`asset-manifest.md`](asset-manifest.md) §4.

---

## 4. Slide specification

Copy: [`slide-copy.md`](slide-copy.md). Cues:
[`presenter-cues.md`](presenter-cues.md). Assets:
[`asset-manifest.md`](asset-manifest.md).

### Slide 1

| Field | Value |
|---|---|
| **Title** | What Is a BIM Execution Plan? |
| **Purpose** | Establish the BEP as an operating agreement; introduce Harrismith as the worked example; identify Triviron as the transfer context |
| **Time** | 1.0 min |
| **Narrative role** | Block 1 — opening |
| **Layout** | Title slide; text-and-space |
| **Primary visual** | `M01-S01` (layout spec) |
| **Optional visual** | `V1` — **does not exist** |
| **Copy source** | `slide-copy.md` §1 |
| **Cue source** | `presenter-cues.md` §1 |
| **Evidence** | DIRECT (status wording) · SYNTHESIS (framing line) |
| **Mandatory warning** | No fabricated project image. No named holder. Status note must appear |
| **Transition** | "So why does a project need one written down?" |

### Slide 2

| Field | Value |
|---|---|
| **Title** | Without an agreed execution plan, coordination becomes accidental |
| **Purpose** | Establish the problem before the solution; make the audience recognise it |
| **Time** | 2.0 min |
| **Narrative role** | Block 1 — the problem |
| **Layout** | Diagram-dominant |
| **Primary visual** | `M01-S02` |
| **Optional visual** | — |
| **Copy source** | `slide-copy.md` §2 |
| **Cue source** | `presenter-cues.md` §2 |
| **Evidence** | INTERPRETATION · teaching statement is SYNTHESIS |
| **Mandatory warning** | **Never caption as Harrismith's failure history.** These are generic uncertainties, not recorded events |
| **Transition** | "That's what a BEP is for. Here's what it actually is." |

### Slide 3

| Field | Value |
|---|---|
| **Title** | A BEP is the agreed operating plan for project information |
| **Purpose** | Deliver the definition, and bound it with what a BEP is not |
| **Time** | 1.0 min |
| **Narrative role** | Block 2 — the response |
| **Layout** | Diagram + short list |
| **Primary visual** | `M01-S03` |
| **Optional visual** | "is not" panel (second build) |
| **Copy source** | `slide-copy.md` §3 |
| **Cue source** | `presenter-cues.md` §3 |
| **Evidence** | **SYNTHESIS** — the six-verb framing is a teaching device |
| **Mandatory warning** | Do not attribute "the six verbs" to any Harrismith document. Do not number them as a sequence |
| **Transition** | "Six verbs — and none of them happen by themselves." |

### Slide 4

| Field | Value |
|---|---|
| **Title** | Who prepares, reviews and approves the BEP? |
| **Purpose** | Show five distinct functions; defeat the "one BIM manager owns it" misconception |
| **Time** | 2.0 min |
| **Narrative role** | Block 3 — roles |
| **Layout** | Left-to-right flow diagram |
| **Primary visual** | `M01-S04` |
| **Optional visual** | BEP §9.10 route strip |
| **Copy source** | `slide-copy.md` §4 |
| **Cue source** | `presenter-cues.md` §4 |
| **Evidence** | DIRECT (G1 allocation, BIM Manager limits, §9.10 route) · INTERPRETATION (five-function framing) |
| **Mandatory warning** | **No hierarchy diagram** — BEP §5.2's model is functional, not an appointment chart. **No named holder.** Do not consume Slide 13's argument |
| **Transition** | "They agree it. Agree to what, though?" |

### Slide 5

| Field | Value |
|---|---|
| **Title** | Template versus project-specific BEP |
| **Purpose** | Separate a reusable framework from a completed BEP containing this project's decisions |
| **Time** | 2.0 min |
| **Narrative role** | Block 3 — what a completed BEP contains |
| **Layout** | Two-column comparison + unresolved panel |
| **Primary visual** | `M01-S05` |
| **Optional visual** | — |
| **Copy source** | `slide-copy.md` §5 |
| **Cue source** | `presenter-cues.md` §5 |
| **Evidence** | **TEACHING SYNTHESIS** — no Harrismith source discusses BEP templates |
| **Mandatory warning** | **Visible `Teaching synthesis` label required.** Never attribute the distinction to a Harrismith document |
| **Transition** | "So where do all those answers live?" |

### Slide 6

| Field | Value |
|---|---|
| **Title** | The Harrismith BEP structure |
| **Purpose** | Show one connected management system and why the split makes it maintainable |
| **Time** | 2.0 min |
| **Narrative role** | Block 3 — the document set |
| **Layout** | Relationship diagram |
| **Primary visual** | `M01-S06` |
| **Optional visual** | Worked trace (§9.4 → P4 → TRN-E01) |
| **Copy source** | `slide-copy.md` §6 |
| **Cue source** | `presenter-cues.md` §6 |
| **Evidence** | DIRECT (documents and roles) · INTERPRETATION (arrangement) |
| **Mandatory warning** | **No contractual hierarchy.** Plain lines, not arrowheads. Register alongside, not beneath. No completion indicators |
| **Transition** | "Two of those seven get mixed up constantly." |

### Slide 7

| Field | Value |
|---|---|
| **Title** | Two responsibility matrices, two different questions |
| **Purpose** | Separate process responsibility from model-content responsibility |
| **Time** | 1.5 min |
| **Narrative role** | Block 3 — responsibility |
| **Layout** | Two-column + two small extracts |
| **Primary visual** | `M01-S07` |
| **Optional visual** | — |
| **Copy source** | `slide-copy.md` §7 |
| **Cue source** | `presenter-cues.md` §7 |
| **Evidence** | DIRECT (both purpose statements, both extracts) · INTERPRETATION (verbs vs things) |
| **Mandatory warning** | **No RACI**, in the diagram, a legend or an answer. **No raw matrix.** No named holder |
| **Transition** | "That's still just an allocation of work." |

### Slide 8

| Field | Value |
|---|---|
| **Title** | Information-delivery planning |
| **Purpose** | Show how responsibility becomes a planned delivery — and what a plan looks like with no dates |
| **Time** | 1.5 min |
| **Narrative role** | Block 3 — delivery |
| **Layout** | Field/value extract + three-row event table |
| **Primary visual** | `M01-S08` |
| **Optional visual** | Published / Delivered / Received / Accepted strip |
| **Copy source** | `slide-copy.md` §8 |
| **Cue source** | `presenter-cues.md` §8 |
| **Evidence** | DIRECT (fields, events, blocking matters) · SYNTHESIS (required message) |
| **Mandatory warning** | **No calendar, Gantt, stage or month label.** TRN-E03 shown **BLOCKED**. `Authority unresolved` label required |
| **Transition** | "Every row named a state. So what is a state?" |

### Slide 9

| Field | Value |
|---|---|
| **Title** | Information moves through controlled CDE states |
| **Purpose** | Four states, each defining permitted use rather than location |
| **Time** | 1.0 min |
| **Narrative role** | Block 4 — CDE |
| **Layout** | State-flow diagram |
| **Primary visual** | `M01-S09` |
| **Optional visual** | Five-term table (version/revision/state/status/suitability) |
| **Copy source** | `slide-copy.md` §9 |
| **Cue source** | `presenter-cues.md` §9 |
| **Evidence** | DIRECT (states, definitions) · INTERPRETATION (required message) |
| **Mandatory warning** | **`Archived` must not appear.** Fourth state is **`Record / Retained`**, drawn detached. Caption as the governed model, not current behaviour |
| **Transition** | "There's one place this goes wrong in practice." |

### Slide 10

| Field | Value |
|---|---|
| **Title** | A folder location is not the same as an information status |
| **Purpose** | Separate technical movement from governed transition; permission from authority |
| **Time** | 1.0 min |
| **Narrative role** | Block 4 — CDE correction |
| **Layout** | Transition diagram + permission/authority panel |
| **Primary visual** | `M01-S10` |
| **Optional visual** | "Not a state" panel |
| **Copy source** | `slide-copy.md` §10 |
| **Cue source** | `presenter-cues.md` §10 |
| **Evidence** | DIRECT (transitions, unresolved authorities) · SYNTHESIS (required message) |
| **Mandatory warning** | **T4 must be shown blocked with `Authority unresolved`.** Never a complete chain. Arrow runs authority → permission, never the reverse |
| **Transition** | "The main reason information moves at all is coordination." |

### Slide 11

| Field | Value |
|---|---|
| **Title** | Coordination is a managed review cycle |
| **Purpose** | Show coordination as a repeatable cycle, not a clash test |
| **Time** | 1.0 min |
| **Narrative role** | Block 4 — coordination |
| **Layout** | Circular / staged cycle |
| **Primary visual** | `M01-S11` |
| **Optional visual** | Tool-connection panel — **with warning node** |
| **Copy source** | `slide-copy.md` §11 |
| **Cue source** | `presenter-cues.md` §11 |
| **Evidence** | DIRECT (cycle, four distinctions) · INTERPRETATION (six-stage compression) |
| **Mandatory warning** | **`Not verified as live implementation` label required.** No screenshots, clash counts, tolerances or frequencies |
| **Transition** | "Triage, and what happens after it, is where this works or quietly doesn't." |

### Slide 12

| Field | Value |
|---|---|
| **Title** | From coordination issue to recorded resolution |
| **Purpose** | Show that detecting and recording is not resolving and closing |
| **Time** | 1.0 min |
| **Narrative role** | Block 4 — issue lifecycle |
| **Layout** | Lifecycle diagram with branches |
| **Primary visual** | `M01-S12` |
| **Optional visual** | STR-01 / MEC-01 worked example — **labelled illustrative** |
| **Copy source** | `slide-copy.md` §12 |
| **Cue source** | `presenter-cues.md` §12 |
| **Evidence** | DIRECT (status model, closure rule) · INTERPRETATION (five functions) |
| **Mandatory warning** | **Must not resemble an ACC Issues board.** `Illustrative workflow` label required. **Closure is not design approval** |
| **Transition** | "All of that is what the team agreed to do." |

### Slide 13

| Field | Value |
|---|---|
| **Title** | Approval does not prove implementation |
| **Purpose** | Separate approved, authorised, implemented, evidenced and verified |
| **Time** | 1.5 min |
| **Narrative role** | Block 5 |
| **Layout** | Five-stage strip + two-column contrast |
| **Primary visual** | `M01-S13` |
| **Optional visual** | UD-001 lifecycle strip with **STOPS HERE** |
| **Copy source** | `slide-copy.md` §13 |
| **Cue source** | `presenter-cues.md` §13 |
| **Evidence** | DIRECT (the quotation) · INTERPRETATION (five states) · SYNTHESIS (required message) |
| **Mandatory warning** | **No publication-planning history.** Minimum evidence only. Frame incompleteness as discipline, not failure |
| **Transition** | "So that's Harrismith. What does it mean for us?" |

### Slide 14

| Field | Value |
|---|---|
| **Title** | What must Triviron decide for itself? |
| **Purpose** | Move from worked example to the audience's own project, as questions |
| **Time** | 1.5 min |
| **Narrative role** | Block 6 — close |
| **Layout** | Transfer chain + question list + three takeaways |
| **Primary visual** | `M01-S14` |
| **Optional visual** | Transfers / does-not-transfer table |
| **Copy source** | `slide-copy.md` §14 |
| **Cue source** | `presenter-cues.md` §14 |
| **Evidence** | **SYNTHESIS** (closing message, takeaways) · DIRECT (each question's derivation) |
| **Mandatory warning** | **No Triviron fact.** Final box outline-only. `Teaching synthesis` label required |
| **Transition** | None — final slide. Move to questions |

---

## 5. Timing

| Block | Slides | Time |
|---|---|---:|
| 1 — The project information problem | 1, 2 | 3.0 |
| 2 — The BEP as the agreed response | 3 | 1.0 |
| 3 — Roles and supporting instruments | 4, 5, 6, 7, 8 | 9.0 |
| 4 — CDE and coordination controls | 9, 10, 11, 12 | 4.0 |
| 5 — Approval versus implementation | 13 | 1.5 |
| 6 — Transfer to Triviron | 14 | 1.5 |
| **Total** | **14** | **20.0** |

Per slide: 1.0 · 2.0 · 1.0 · 2.0 · 2.0 · 2.0 · 1.5 · 1.5 · 1.0 · 1.0 · 1.0 ·
1.0 · 1.5 · 1.5 = **20.0 minutes**.

**This is an allocation, not a measurement.** No rehearsal has occurred and no
timing has been observed.
