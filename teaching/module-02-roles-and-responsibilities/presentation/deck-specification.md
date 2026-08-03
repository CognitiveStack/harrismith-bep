# Module 2 — Deck Specification

**Status:** Production specification. **Not governance.** Not a built deck.

---

## 1. Global details

| Field | Value |
|---|---|
| **Title** | BIM Management Roles and Responsibilities |
| **Subtitle** | Who decides what, and on whose authority |
| **Module** | Module 2 — BIM Management Roles and Responsibilities |
| **Audience** | Mixed multidisciplinary project audience — discipline leads, project managers, at least one CDE administrator, and at least one person whose interest is commercial |
| **Planned duration** | **20 minutes**, plus questions |
| **Slides** | **14** |
| **Objective** | Enable the audience to understand who does what on a project's information — and, more importantly, **who is permitted to decide what** |
| **Central teaching message** | *BIM Management separates production, checking, coordination, authorisation, delivery and acceptance so that each project function has clear authority and accountability.* **Teaching wording** |
| **Opening proposition** | Interface decisions get made either way — deliberately, or by assumption, access or habit |
| **Closing proposition** | Harrismith gives a functional model; Triviron must assign organisations, people and authority to it before relying on it in delivery |

## 2. Narrative arc

Eight sections. The audience should feel the hinge between each.

| # | Section | Slides | Time | The move it makes |
|---|---|---|---:|---|
| 1 | **Why role clarity matters** | 1 | 2.0 | From "another governance topic" to "a situation you recognise" |
| 2 | **Function, title, organisation and person** | 2, 3 | 2.0 | From roles-as-labels to roles-as-decisions |
| 3 | **The distributed governance model** | 4 | 2.0 | From "who is in charge" to "which function decides what" |
| 4 | **BIM Manager and BIM Coordinator boundaries** | 5, 6, 7, 8 | 5.0 | From title-implied authority to defined authority |
| 5 | **Task-team separation of duties** | 9 | 3.0 | From abstraction to the concrete case |
| 6 | **CDE Administration and permission** | 10 | 2.0 | From capability to authority |
| 7 | **The authority chain and unresolved authorities** | 11, 12, 13 | 3.0 | From "approved" to *what was decided, by whom, for what purpose* |
| 8 | **Assigning the model to Triviron** | 14 | 1.0 | From worked example to the audience's own decisions |

**Section 4 is the longest and carries the module's principal boundaries.** Each
of its two pairs is *positive account, then boundary* — and in both, the second
slide carries the teaching.

**Section 5 is the single most valuable three minutes.** It is where the
separation becomes concrete and the audience says "oh — *that's* what you mean".

**Sections 7 and 8 total four minutes and are the easiest to lose.** They carry
the consolidation, the honest position and the transfer. If time is short,
recover from Slide 4 or Slide 10 — never from these.

## 3. Design approach

**16:9. Restrained professional BIM-management style. No final Triviron brand
identity** — that is a later decision, deliberately not taken here.

### 3.1 Format and hierarchy

| Element | Specification |
|---|---|
| **Aspect ratio** | **16:9** |
| **Title** | One line, sentence case, consistent position across all fourteen slides. Never wraps to three lines |
| **Main statement** | One line, subordinate to the title, dominant over supporting items |
| **Supporting items** | Short labels or single-line bullets. **Maximum five per slide** |
| **Body text** | Roughly **45 visible words per slide**, excluding diagram labels. Slides 6, 12 and 14 are the deliberate exceptions |
| **Fonts** | Any clean sans-serif already available. **No specific font is specified** — do not introduce one requiring installation |
| **Type sizes** | Nothing below roughly 18 pt equivalent at 16:9 |

### 3.2 Line and shape semantics — **carries meaning in this module**

| Treatment | Meaning | Where |
|---|---|---|
| **Solid** | Supported allocation, or governed progression | Slide 9's Author → Checker → Task-Team Lead → Shared |
| **Thick / emphasised** | Direction of derivation | Slide 10's responsibility → decision → permission |
| **Plain line, no arrowhead** | Non-hierarchical functional relationship | Slide 4's functions around the process; Slide 5's G1 strip |
| **Dashed** | **Unresolved, blocked, future or unimplemented** | Slides 9, 11, 13, 14 |

**This is not styling.** A render or rebuild that solidifies a dashed element
asserts an authority the sources decline to assign.

### 3.3 Prohibited visual devices

- **No decorative hierarchy**, no pyramid, no tier, no reporting line.
- **No stock organisational chart.**
- **No visual "top role"** — no source establishes one.
- **No platform screenshot** of any kind.
- **No fabricated project imagery.**
- No gradients, shadows, icon sets or product chrome.

### 3.4 Tables

Tables appear where a diagram would imply a hierarchy, sequence or authority the
sources do not establish — Slides 6, 12 and part of 13.

| Rule | |
|---|---|
| Maximum on a main slide | **Six rows, three columns** |
| Never on a main slide | A raw responsibility matrix; the full sixteen-authority register; a source-map extract |
| Extracts | Cropped to the rows that carry the message, captioned as extracts |

### 3.5 Whitespace and consistency

Generous margins. One principal message per slide — if it needs an "and", split
it. The same shape and weight means the same thing on every slide.

### 3.6 Footers and evidence labels

Small, low-contrast, bottom of slide. Short attribution where a claim is quoted
or extracted — `BEP §5.5`, `IM matrix G1`. **Never a full file path.** Not every
slide needs one.

## 4. Visible warnings versus producer-only warnings

**Every slide has a mandatory build requirement.** Fourteen large warning labels
on the visible deck would make all of them invisible.

Four distinct channels:

| Channel | Purpose | Where it lives |
|---|---|---|
| **Visible on-slide warning** | Where an audience misreading is likely | The slide face — 7 slides |
| **Producer-only build warning** | A construction rule the audience never sees | This spec and `production-checklist.md` — all 14 slides |
| **Speaker-note caution** | A delivery risk | `presenter-cues.md` — all 14 slides |
| **Footer evidence label** | Classification or attribution | The slide footer — where a claim is quoted or is synthesis |

**Visible warnings used in this deck** — seven slides carry one:

| Slide | Visible label |
|---|---|
| 3 | `No named holder` |
| 7 | `Not verified as live implementation` |
| 8 | `Illustrative workflow` |
| 11 | `Authority unresolved` · `Blocked` · `Recipient-dependent` |
| 12 | `Outside IM authority` (on the design-approval row) |
| 13 | `No named holder` |
| 14 | `Future assignment questions` · `Teaching synthesis` |

The other seven slides carry their requirement as a **producer-only** rule.

---

## 5. Slide specifications

Copy: [`slide-copy.md`](slide-copy.md). Cues:
[`presenter-cues.md`](presenter-cues.md). Assets:
[`asset-manifest.md`](asset-manifest.md).

### Slide 1

| Field | Value |
|---|---|
| **Title** | BIM roles exist to make decisions explicit |
| **Purpose** | Establish why role clarity matters before naming a role; show that unassigned authority produces an accidental decision, not no decision |
| **Time** | 2.0 min |
| **Narrative role** | §1 — why role clarity matters |
| **Layout** | Diagram-dominant |
| **Primary visual** | `M02-S01` |
| **Optional support** | — |
| **Copy source** | `slide-copy.md` §1 |
| **Cue source** | `presenter-cues.md` §1 |
| **Evidence** | DIRECT (three closures, traceability) · **SYNTHESIS** (central framing) |
| **Mandatory build warning** | **Producer-only.** Never caption any route as a recorded Harrismith failure. No org-chart shape |
| **Transition** | "So — roles. And straight away there's a confusion worth clearing." |

### Slide 2

| Field | Value |
|---|---|
| **Title** | A role is not the same as a job title |
| **Purpose** | Separate project function from job title from person; show that combining functions does not merge them |
| **Time** | 1.0 min |
| **Narrative role** | §2 |
| **Layout** | Diagram + three-concept table |
| **Primary visual** | `M02-S02` |
| **Optional support** | Delegation note |
| **Copy source** | `slide-copy.md` §2 |
| **Cue source** | `presenter-cues.md` §2 |
| **Evidence** | **DIRECT** |
| **Mandatory build warning** | **Producer-only.** No name, avatar, silhouette or photograph. The participant container is neutral |
| **Transition** | "A function isn't a title. It's also not an organisation, and it's not a person." |

### Slide 3

| Field | Value |
|---|---|
| **Title** | Function, organisation and named person |
| **Purpose** | Three layers, with Harrismith's third deliberately empty — and why that is a planning state |
| **Time** | 1.0 min |
| **Narrative role** | §2 |
| **Layout** | Three-band diagram |
| **Primary visual** | `M02-S03` |
| **Optional support** | Five-concepts panel |
| **Copy source** | `slide-copy.md` §3 |
| **Cue source** | `presenter-cues.md` §3 |
| **Evidence** | DIRECT · INTERPRETATION (the stack) · SYNTHESIS (planning value) |
| **Mandatory build warning** | **Visible: `No named holder`.** No name-shaped placeholder in layer 3. Caption *defined, not yet operating* |
| **Transition** | "So those are the layers. Let's populate the middle one." |

### Slide 4

| Field | Value |
|---|---|
| **Title** | Who governs the project information process? |
| **Purpose** | Show governance distributed by function, each with a boundary — not a hierarchy |
| **Time** | 2.0 min |
| **Narrative role** | §3 — the distributed governance model |
| **Layout** | Ring or horizontal functional band |
| **Primary visual** | `M02-S04` |
| **Optional support** | Nine-role strip |
| **Copy source** | `slide-copy.md` §4 |
| **Cue source** | `presenter-cues.md` §4 |
| **Evidence** | DIRECT (functions, roles, holder status) · INTERPRETATION (arrangement, seven concerns) |
| **Mandatory build warning** | **Producer-only, and absolute. If the diagram has a visual top role, it is wrong.** TBD status must be visible on the slide |
| **Transition** | "Let me start with the one everybody's heard of." |

### Slide 5

| Field | Value |
|---|---|
| **Title** | What does the BIM Manager actually do? |
| **Purpose** | A positive functional account, anchored on matrix row G1 |
| **Time** | 1.5 min |
| **Narrative role** | §4 |
| **Layout** | G1 strip + responsibility list |
| **Primary visual** | `M02-S05` |
| **Optional support** | Matrix rows panel |
| **Copy source** | `slide-copy.md` §5 |
| **Cue source** | `presenter-cues.md` §5 |
| **Evidence** | **DIRECT** |
| **Mandatory build warning** | **Producer-only. No exclusions on this slide** — Slide 6 owns them. **Preserve the G4 distinction** |
| **Transition** | "So that's what it does. Now the more useful half." |

### Slide 6

| Field | Value |
|---|---|
| **Title** | What the BIM Manager does not automatically do |
| **Purpose** | Correct the assumption of general project authority, without making the function look marginal |
| **Time** | 1.5 min |
| **Narrative role** | §4 |
| **Layout** | Balanced two-column comparison |
| **Primary visual** | `M02-S06` |
| **Optional support** | Classification markers |
| **Copy source** | `slide-copy.md` §6 |
| **Cue source** | `presenter-cues.md` §6 |
| **Evidence** | DIRECT ×9 · INTERPRETATION ×1 · **SYNTHESIS** (message) |
| **Mandatory build warning** | **Producer-only. Equal column width and weight.** Publication and acceptance marked unresolved **for everyone**, not merely not-the-BIM-Manager's |
| **Transition** | "Same treatment for the other function people assume they understand." |

### Slide 7

| Field | Value |
|---|---|
| **Title** | What does the BIM Coordinator do? |
| **Purpose** | Coordinator at the process centre; task teams retain information ownership and technical responsibility |
| **Time** | 1.0 min |
| **Narrative role** | §4 |
| **Layout** | Central-process diagram |
| **Primary visual** | `M02-S07` |
| **Optional support** | Activity panel |
| **Copy source** | `slide-copy.md` §7 |
| **Cue source** | `presenter-cues.md` §7 |
| **Evidence** | **DIRECT** |
| **Mandatory build warning** | **Visible: `Not verified as live implementation`.** Each container keeps its originating task-team label. No product name or screenshot |
| **Transition** | "Which is worth pinning down properly." |

### Slide 8

| Field | Value |
|---|---|
| **Title** | Coordination responsibility is not design responsibility |
| **Purpose** | Walk one matter end to end; responsibility crosses to the task team and returns |
| **Time** | 1.0 min |
| **Narrative role** | §4 |
| **Layout** | Four-lane swimlane |
| **Primary visual** | `M02-S08` |
| **Optional support** | One boundary call-out |
| **Copy source** | `slide-copy.md` §8 |
| **Cue source** | `presenter-cues.md` §8 |
| **Evidence** | DIRECT (steps, boundaries) · INTERPRETATION (eight-step compression, message) |
| **Mandatory build warning** | **Visible: `Illustrative workflow`.** Step 4 stays in the task-team lane. Responsibility visibly returns at step 7 |
| **Transition** | "Notice how much of that happened inside one task team." |

### Slide 9

| Field | Value |
|---|---|
| **Title** | Task-Team Leads, Authors and Checkers |
| **Purpose** | The clearest separation of duties in the framework — three functions, one container, three acts |
| **Time** | 3.0 min |
| **Narrative role** | §5 — task-team separation of duties |
| **Layout** | Linear flow + P1–P4 extract |
| **Primary visual** | `M02-S09` |
| **Optional support** | Delivery-schedule panel; Author/Checker combination panel |
| **Copy source** | `slide-copy.md` §9 |
| **Cue source** | `presenter-cues.md` §9 |
| **Evidence** | **DIRECT** |
| **Mandatory build warning** | **Producer-only, and absolute. The flow stops at `Shared`. No solid Shared → Published arrow. No RACI letters** anywhere |
| **Transition** | "Everything so far has been about people deciding things. There's one function left that decides nothing." |

### Slide 10

| Field | Value |
|---|---|
| **Title** | CDE Administration implements governance |
| **Purpose** | Separate platform capability from project authority; establish the direction of travel |
| **Time** | 2.0 min |
| **Narrative role** | §6 — CDE Administration and permission |
| **Layout** | Directional chain + `≠` panel |
| **Primary visual** | `M02-S10` |
| **Optional support** | §5.11 two-function example |
| **Copy source** | `slide-copy.md` §10 |
| **Cue source** | `presenter-cues.md` §10 |
| **Evidence** | **DIRECT** |
| **Mandatory build warning** | **Producer-only. No ACC permissions screenshot.** One direction, no return path. Distinguish `CDE Administration` from `CDE Administrator` |
| **Transition** | "Let me put the whole chain together." |

### Slide 11

| Field | Value |
|---|---|
| **Title** | Check, authorise, publish, receive and accept |
| **Purpose** | Show the decision chain with two links visibly unheld; distinguish acts, state transitions, events and statuses |
| **Time** | 1.0 min |
| **Narrative role** | §7 |
| **Layout** | Annotated decision chain |
| **Primary visual** | `M02-S11` |
| **Optional support** | Authority-status strip |
| **Copy source** | `slide-copy.md` §11 |
| **Cue source** | `presenter-cues.md` §11 |
| **Evidence** | DIRECT · INTERPRETATION (message) |
| **Mandatory build warning** | **Visible: `Authority unresolved` · `Blocked` · `Recipient-dependent`.** No complete solid route from Author to Accepted. Unresolved steps shown, never omitted |
| **Transition** | "Which is a lot of separate authorities." |

### Slide 12

| Field | Value |
|---|---|
| **Title** | One process, several distinct authorities |
| **Purpose** | Answer "who may decide each kind of information action?" — including where the answer is nobody |
| **Time** | 1.0 min |
| **Narrative role** | §7 |
| **Layout** | Simplified authority register |
| **Primary visual** | `M02-S12` (simplified slide layout) |
| **Optional support** | Full sixteen-row appendix — **presenter reference only** |
| **Copy source** | `slide-copy.md` §12 |
| **Cue source** | `presenter-cues.md` §12 |
| **Evidence** | DIRECT (allocations) · INTERPRETATION (status vocabulary) · **SYNTHESIS** (message) |
| **Mandatory build warning** | **Visible: `Outside IM authority`.** No hierarchy · BIM Manager not distinguished · **unresolved rows never cut for space** |
| **Transition** | "You'll have noticed something running through all of that." |

### Slide 13

| Field | Value |
|---|---|
| **Title** | Harrismith names functions but not role holders |
| **Purpose** | Separate a governance framework from an implemented appointment structure — both halves |
| **Time** | 1.0 min |
| **Narrative role** | §7 |
| **Layout** | Balanced comparison + three-layer strip |
| **Primary visual** | `M02-S13` |
| **Optional support** | Balance panel |
| **Copy source** | `slide-copy.md` §13 |
| **Cue source** | `presenter-cues.md` §13 |
| **Evidence** | DIRECT (both lists) · INTERPRETATION · **SYNTHESIS** (message, balance) |
| **Mandatory build warning** | **Visible: `No named holder`.** Neither "broken" nor "running". Layers 2 and 3 remain incomplete |
| **Transition** | "Which brings me to what any of this means for us." |

### Slide 14

| Field | Value |
|---|---|
| **Title** | What must Triviron assign before delivery begins? |
| **Purpose** | Convert the model into a project-startup checklist — as questions |
| **Time** | 1.0 min |
| **Narrative role** | §8 — assigning the model to Triviron |
| **Layout** | Seven-stage sequence + question panel + three takeaways |
| **Primary visual** | `M02-S14` |
| **Optional support** | Full question set — handout only |
| **Copy source** | `slide-copy.md` §14 |
| **Cue source** | `presenter-cues.md` §14 |
| **Evidence** | **SYNTHESIS** (sequence, close, takeaways) · DIRECT (each derivation) |
| **Mandatory build warning** | **Visible: `Future assignment questions` · `Teaching synthesis`.** **No Triviron fact.** Permissions fifth. Stage 7 outline-only |
| **Transition** | None — final slide. Move to takeaways, then questions |

---

## 6. The four deliberately incomplete visuals

**These are mandatory requirements. Completing any of them visually is a content
failure, not a style improvement.**

| Slide | What stays incomplete | Why |
|---|---|---|
| **9** | **`Published` remains unreached** — dashed, faint, labelled *authority unresolved*; or omitted entirely | Publication authority is UNRESOLVED and the transition is BLOCKED. A solid arrow would invent it |
| **11** | **Publication and acceptance authority remain visibly unheld** — dashed borders, explicit status labels, dashed links | Neither authority is held by anyone. An omitted step reads as one that does not exist; a solid one reads as one somebody holds |
| **13** | **Organisation and named-holder layers remain incomplete** — layer 2 dashed outline with categories only, layer 3 faint and empty | No organisation is appointed; every holder is TBD |
| **14** | **Verified Triviron implementation remains future-facing** — stage 7 outline-only, dashed link, no tick, no percentage, no date | No Triviron implementation exists or is scheduled |

**A producer's instinct is to finish a diagram.** Here, finishing is the error.

---

## 7. Timing

| # | Section | Slides | Time |
|---|---|---|---:|
| 1 | Why role clarity matters | 1 | 2.0 |
| 2 | Function, title, organisation and person | 2, 3 | 2.0 |
| 3 | The distributed governance model | 4 | 2.0 |
| 4 | BIM Manager and BIM Coordinator boundaries | 5, 6, 7, 8 | 5.0 |
| 5 | Task-team separation of duties | 9 | 3.0 |
| 6 | CDE Administration and permission | 10 | 2.0 |
| 7 | The authority chain and unresolved authorities | 11, 12, 13 | 3.0 |
| 8 | Assigning the model to Triviron | 14 | 1.0 |
| **Total** | | **14** | **20.0** |

Per slide: 2.0 · 1.0 · 1.0 · 2.0 · 1.5 · 1.5 · 1.0 · 1.0 · 3.0 · 2.0 · 1.0 ·
1.0 · 1.0 · 1.0 = **20.0 minutes**.

**This is an allocation, not a measurement.** No rehearsal has occurred and no
timing has been observed.
