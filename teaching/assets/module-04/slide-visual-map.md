# Module 4 — Slide-to-Visual Map

**Status:** Visual-source baseline. **Not governance.** **No rendered assets
exist.**

Slides 1–14 of **Module 4 — CDE Workflows and Information States**, each mapped
to its visual concept and its slide-source file.

**One slide, one visual concept, one source file — for all fourteen.**

Controlling documents:
[`visual-demonstration-plan.md`](../../module-04-cde-workflows-and-information-states/visual-demonstration-plan.md)
for the specifications,
[`presentation-outline.md`](../../module-04-cde-workflows-and-information-states/presentation-outline.md)
for slide content and timing, and
[`speaker-notes.md`](../../module-04-cde-workflows-and-information-states/speaker-notes.md)
for what the speaker supplies that the visual cannot.

---

## 1. The map at a glance

| Slide | Title | `W` | Source | Blocked / empty element |
|---|---|---|---|---|
| 1 | A CDE is a governed process, not a folder tree | **`W1`** | [`M04-S01`](source/M04-S01-governance-workflow-platform.md) | No blocked route |
| 2 | State, version, revision, status and suitability are different | **`W2`** | [`M04-S02`](source/M04-S02-five-properties.md) | **YES — the three absent code sets**, named on their own cards |
| 3 | The Harrismith information-state model | **`W3`** | [`M04-S03`](source/M04-S03-four-state-model.md) | **YES — three of them |
| 4 | Work in Progress: authoring inside the task team | **`W4`** | [`M04-S04`](source/M04-S04-wip-task-team-boundary.md) | **No route out is drawn |
| 5 | Shared: controlled use for a defined purpose | **`W5`** | [`M04-S05`](source/M04-S05-shared-defined-purpose.md) | **None — see the source file** |
| 6 | Published / Authorised: a separate decision and authority | **`W6`** | [`M04-S06`](source/M04-S06-publication-authority-gate.md) | **YES — the authority position is drawn empty, and the output is broken** |
| 7 | Record / Retained: preservation without an Archive folder | **`W7`** | [`M04-S07`](source/M04-S07-retention-obligation-versus-method.md) | **YES — the method panel is visibly empty**, with four unfilled fields |
| 8 | A transition is more than moving a file | **`W8`** | [`M04-S08`](source/M04-S08-file-movement-versus-transition.md) | **The absent connector is the mandatory element |
| 9 | The eight controlled steps, and the two that change state | **`W9`** | [`M04-S09`](source/M04-S09-eight-controlled-steps.md) | **YES** — `T4` blocked and `T7` unresolved, both in the same table |
| 10 | Gates, authority and evidence | **`W10`** | [`M04-S10`](source/M04-S10-t1-gate-model.md) | **The evidence field is the mandatory element |
| 11 | Why `Shared → Published` remains blocked | **`W11`** | [`M04-S11`](source/M04-S11-t4-and-trn-e03.md) | **YES — the visual is two blocks**, plus an empty authority position on Panel 1 |
| 12 | Naming, revision, suitability and metadata support control | **`W12`** | [`M04-S12`](source/M04-S12-property-stack.md) | **YES — four empty boxes, shown and unfilled** |
| 13 | Governance first; permissions and configuration follow | **`W13`** | [`M04-S13`](source/M04-S13-governance-then-configuration.md) | **YES — the refused reverse arrow, and `Holder: TBD`** |
| 14 | What Triviron must define before configuring its CDE | **`W14`** | [`M04-S14`](source/M04-S14-triviron-questions.md) | **YES — the two authority questions stay unanswered, and the end state stays open** |

**Every slide is `Deliverable from repository source alone: YES`.** **No external
imagery is required for any slide**, and **no live platform evidence is required
or authorised for any slide.**

**Timing.** The module is **20.0 minutes allocated across fourteen slides**, per
[`presentation-outline.md`](../../module-04-cde-workflows-and-information-states/presentation-outline.md)
§1–§2. **No delivery has been timed.** Every figure is an allocation until
Exercise 64 has been run.

## 2. Slide entries

### Slide 1 — A CDE is a governed process, not a folder tree

| Field | Value |
|---|---|
| **Slide number** | 1 |
| **Slide title** | A CDE is a governed process, not a folder tree |
| **Visual identifier** | **`W1`** — Governance → workflow → platform |
| **Source identifier** | `M04-S01` |
| **Source path** | [`source/M04-S01-governance-workflow-platform.md`](source/M04-S01-governance-workflow-platform.md) |
| **Visual form** | Three stacked bands — **native layout, not Mermaid** |
| **Five-second takeaway** | Governance decides; the platform implements. Never the other way round. |
| **Principal visible labels** | `GOVERNANCE AND AUTHORITY` · `CDE WORKFLOW AND INFORMATION STATES` · `PLATFORM, FOLDERS, PERMISSIONS AND METADATA` · `decides and authorises` · `implemented through` |
| **Required source or status labels** | Band 1 **`CONTROLLED GOVERNANCE`** · Band 2 **`PROPOSED GOVERNANCE`** · Band 3 topology adopted (`S3` §2) · Band 3 **`IMPLEMENTATION UNVERIFIED`** (`CGD-C07`). Bands 1 and 2 make no implementation claim |
| **Governance status** | Band 1 **`CONTROLLED GOVERNANCE`** · Band 2 **`PROPOSED GOVERNANCE`** · Band 3 topology adopted (`S3` §2) |
| **Implementation status** | Band 3 **`IMPLEMENTATION UNVERIFIED`** (`CGD-C07`). Bands 1 and 2 make no implementation claim |
| **Blocked, empty or unresolved element** | No blocked route. **The three status labels are the mandatory element** — without them the diagram asserts a verified operating architecture |
| **Content to omit** | Platform logo, screenshot or product name · any upward arrow · any org-chart shape |
| **Likely producer failure** | Reading the three bands as organisational ranks, or the bottom band as *the CDE* |
| **Accessibility note** | Statuses are words, not tints; reading order strictly top to bottom |
| **Intended native PowerPoint treatment** | Three rectangles, two straight connectors, no SmartArt |
| **Deliverable from repository source alone** | **YES** |

### Slide 2 — State, version, revision, status and suitability are different

| Field | Value |
|---|---|
| **Slide number** | 2 |
| **Slide title** | State, version, revision, status and suitability are different |
| **Visual identifier** | **`W2`** — The five-property comparison |
| **Source identifier** | `M04-S02` |
| **Source path** | [`source/M04-S02-five-properties.md`](source/M04-S02-five-properties.md) |
| **Visual form** | Five equal cards, one row — **native layout, not Mermaid** |
| **Five-second takeaway** | One container has all five at once. They are not stages. |
| **Principal visible labels** | `State` · `Version` · `Revision` · `Status` · `Suitability`, each with its question · `A new platform version creates none of the others` |
| **Required source or status labels** | **`CONTROLLED GOVERNANCE`** — all five definitions. **`UNRESOLVED`** — the revision, status and suitability code sets · **Not applicable.** This visual makes no implementation claim, and must not appear to |
| **Governance status** | **`CONTROLLED GOVERNANCE`** — all five definitions. **`UNRESOLVED`** — the revision, status and suitability code sets |
| **Implementation status** | **Not applicable.** This visual makes no implementation claim, and must not appear to |
| **Blocked, empty or unresolved element** | **YES — the three absent code sets**, named on their own cards |
| **Content to omit** | Any connector · any example code or filename · **metadata as a sixth card** |
| **Likely producer failure** | Reading five cards in a row as five stages, and adding an example code to make them concrete |
| **Accessibility note** | Five cards are peers, not a list with a first item; no meaning in fill |
| **Intended native PowerPoint treatment** | Five rectangles, nothing between them, no SmartArt |
| **Deliverable from repository source alone** | **YES** |

### Slide 3 — The Harrismith information-state model

| Field | Value |
|---|---|
| **Slide number** | 3 |
| **Slide title** | The Harrismith information-state model |
| **Visual identifier** | **`W3`** — The four-state model |
| **Source identifier** | `M04-S03` |
| **Source path** | [`source/M04-S03-four-state-model.md`](source/M04-S03-four-state-model.md) |
| **Visual form** | Four concept panels, three connectors — **native layout, not Mermaid** |
| **Five-second takeaway** | Four states, four purposes — and the route to Published cannot presently be travelled. |
| **Principal visible labels** | `WIP` · `SHARED` · `PUBLISHED / AUTHORISED` · `RECORD / RETAINED` · `T1` · `T4 BLOCKED` · `Publication-authorising function: TBD` · `Information remains Shared` |
| **Required source or status labels** | **Per panel** — two `CONTROLLED GOVERNANCE`, one **`BLOCKED`**, one **`UNRESOLVED`** · **Per panel** — two `IMPLEMENTATION UNVERIFIED`, one **Not reached**, one **Not addressed** |
| **Governance status** | **Per panel** — two `CONTROLLED GOVERNANCE`, one **`BLOCKED`**, one **`UNRESOLVED`** |
| **Implementation status** | **Per panel** — two `IMPLEMENTATION UNVERIFIED`, one **Not reached**, one **Not addressed** |
| **Blocked, empty or unresolved element** | **YES — three of them.** The `T4` break, the empty publication authority, and an unreachable third connector |
| **Content to omit** | **`04 Archive`** · folder icons as states · a four-area row beneath the panels · Delivered, Received or Accepted |
| **Likely producer failure** | **Completing the blocked route**, or aligning four folders beneath the four states |
| **Accessibility note** | **Connector meaning in text as well as line style**; no red or green; legible in monochrome |
| **Intended native PowerPoint treatment** | Four rectangles, three connectors of **three different kinds**, four text blocks |
| **Deliverable from repository source alone** | **YES** |

### Slide 4 — Work in Progress: authoring inside the task team

| Field | Value |
|---|---|
| **Slide number** | 4 |
| **Slide title** | Work in Progress: authoring inside the task team |
| **Visual identifier** | **`W4`** — The WIP task-team boundary |
| **Source identifier** | `M04-S04` |
| **Source path** | [`source/M04-S04-wip-task-team-boundary.md`](source/M04-S04-wip-task-team-boundary.md) |
| **Visual form** | One responsibility boundary — **native layout, not Mermaid** |
| **Five-second takeaway** | You may be able to see it. That is not permission to use it. |
| **Principal visible labels** | `TASK-TEAM WIP` · `Author` · `Checker` · `Task-Team Lead gate` · `CAN SEE` · `MAY NOT RELY` · `originating responsibility — retained` |
| **Required source or status labels** | **`CONTROLLED GOVERNANCE`** · **`IMPLEMENTATION UNVERIFIED`** — one qualified container observation |
| **Governance status** | **`CONTROLLED GOVERNANCE`** |
| **Implementation status** | **`IMPLEMENTATION UNVERIFIED`** — one qualified container observation |
| **Blocked, empty or unresolved element** | **No route out is drawn.** The Task-Team Lead gate is visible on the boundary and **no connector leaves it** |
| **Content to omit** | Any arrow leaving the boundary · a padlock or permission shield · a named person · a green tick |
| **Likely producer failure** | Drawing the route out of WIP, because a gate invites the eye to follow it |
| **Accessibility note** | `MAY NOT RELY` is words, not a colour; the boundary's meaning is stated inside it |
| **Intended native PowerPoint treatment** | One boundary rectangle, one outside marker, no connector leaving it |
| **Deliverable from repository source alone** | **YES** |

### Slide 5 — Shared: controlled use for a defined purpose

| Field | Value |
|---|---|
| **Slide number** | 5 |
| **Slide title** | Shared: controlled use for a defined purpose |
| **Visual identifier** | **`W5`** — Shared — permitted use for a defined purpose |
| **Source identifier** | `M04-S05` |
| **Source path** | [`source/M04-S05-shared-defined-purpose.md`](source/M04-S05-shared-defined-purpose.md) |
| **Visual form** | One container, purpose call-outs — **native layout, not Mermaid** |
| **Five-second takeaway** | Shared means authorised for a defined use — not approved for every use. |
| **Principal visible labels** | `SHARED CONTAINER` · `stated purpose:` · `RESPONSIBILITY RETAINED` · `coordination` · `controlled review` · `reference by another task team` |
| **Required source or status labels** | **`CONTROLLED GOVERNANCE`** — `T1`'s authorising function is established · **`IMPLEMENTATION UNVERIFIED`** — *"only Architecture currently demonstrable as a Shared input"* |
| **Governance status** | **`CONTROLLED GOVERNANCE`** — `T1`'s authorising function is established |
| **Implementation status** | **`IMPLEMENTATION UNVERIFIED`** — *"only Architecture currently demonstrable as a Shared input"* |
| **Blocked, empty or unresolved element** | None on this visual. **`W5` is the module's only visual with no mandatory incomplete element** — its control is the warning and the retained-responsibility line |
| **Content to omit** | Any approval, publication or acceptance symbol · **any green** · a handover arrow · an invented example purpose |
| **Likely producer failure** | Adding a tick, a stamp or green to a state that is not an approval |
| **Accessibility note** | `RESPONSIBILITY RETAINED` is text, not line weight; **no green anywhere** |
| **Intended native PowerPoint treatment** | One rectangle, a persistent originator line, three terminating call-outs |
| **Deliverable from repository source alone** | **YES** |

### Slide 6 — Published / Authorised: a separate decision and authority

| Field | Value |
|---|---|
| **Slide number** | 6 |
| **Slide title** | Published / Authorised: a separate decision and authority |
| **Visual identifier** | **`W6`** — The publication-authority gate |
| **Source identifier** | `M04-S06` |
| **Source path** | [`source/M04-S06-publication-authority-gate.md`](source/M04-S06-publication-authority-gate.md) |
| **Visual form** | Vertical gate — **native layout, not Mermaid** |
| **Five-second takeaway** | Publication needs an authority. Nobody holds it. So the information stays Shared. |
| **Principal visible labels** | `PUBLICATION GATE` · `Publication-authorising function:` · `TBD / UNRESOLVED` · `T4 BLOCKED` · `No available authorising function` · `INFORMATION REMAINS SHARED` · `(not reached)` |
| **Required source or status labels** | **`BLOCKED`** — the authority is **`UNRESOLVED`** · **Not reached** |
| **Governance status** | **`BLOCKED`** — the authority is **`UNRESOLVED`** |
| **Implementation status** | **Not reached** |
| **Blocked, empty or unresolved element** | **YES — the authority position is drawn empty, and the output is broken** |
| **Content to omit** | Any named or implied holder · any solid `Shared → Published` arrow · any checkmark · **any red failure styling** |
| **Likely producer failure** | **Filling, shading or deleting the empty authority position** — all three are wrong |
| **Accessibility note** | The block is words, not a dashed stroke alone; the empty position is legible as empty |
| **Intended native PowerPoint treatment** | One gate rectangle with an **unfilled inner rectangle**, one solid and one broken connector |
| **Deliverable from repository source alone** | **YES** |

### Slide 7 — Record / Retained: preservation without an Archive folder

| Field | Value |
|---|---|
| **Slide number** | 7 |
| **Slide title** | Record / Retained: preservation without an Archive folder |
| **Visual identifier** | **`W7`** — Retention obligation versus method |
| **Source identifier** | `M04-S07` |
| **Source path** | [`source/M04-S07-retention-obligation-versus-method.md`](source/M04-S07-retention-obligation-versus-method.md) |
| **Visual form** | Two panels — **native layout, not Mermaid** |
| **Five-second takeaway** | The obligation to retain is settled. How to do it is not — and it is not a folder. |
| **Principal visible labels** | `OBLIGATION — ESTABLISHED` · `METHOD — UNRESOLVED` · `location: TBD` · `retention period: TBD` · `responsible holder: TBD` · `superseded ≠ deleted` |
| **Required source or status labels** | **`CONTROLLED GOVERNANCE`** — the obligation. **`UNRESOLVED`** — the method · **Not addressed in any validation record** |
| **Governance status** | **`CONTROLLED GOVERNANCE`** — the obligation. **`UNRESOLVED`** — the method |
| **Implementation status** | **Not addressed in any validation record** |
| **Blocked, empty or unresolved element** | **YES — the method panel is visibly empty**, with four unfilled fields |
| **Content to omit** | **`04 Archive` in any form** · folder or storage icons · an invented retention period or holder · a destination arrow |
| **Likely producer failure** | Supplying a folder, because the audience expects one and the panel looks unfinished |
| **Accessibility note** | `TBD` and `unavailable` are text — whitespace alone would be skipped by a screen reader |
| **Intended native PowerPoint treatment** | Two identical rectangles, **no icons**, an empty gutter |
| **Deliverable from repository source alone** | **YES** |

### Slide 8 — A transition is more than moving a file

| Field | Value |
|---|---|
| **Slide number** | 8 |
| **Slide title** | A transition is more than moving a file |
| **Visual identifier** | **`W8`** — File movement versus authorised transition |
| **Source identifier** | `M04-S08` |
| **Source path** | [`source/M04-S08-file-movement-versus-transition.md`](source/M04-S08-file-movement-versus-transition.md) |
| **Visual form** | Two panels, no connector — **native layout, not Mermaid** |
| **Five-second takeaway** | Being able to move the file establishes nothing at all. |
| **Principal visible labels** | `TECHNICAL ACTION` · `GOVERNED TRANSITION` · `establishes NONE of:` · `Teaching structure` · `NO CONNECTOR. The left does not produce the right.` |
| **Required source or status labels** | **`CONTROLLED GOVERNANCE`** — `CGD-C03` is an active condition · **Not applicable.** This visual compares two kinds of act; it asserts nothing about the live platform |
| **Governance status** | **`CONTROLLED GOVERNANCE`** — `CGD-C03` is an active condition |
| **Implementation status** | **Not applicable.** This visual compares two kinds of act; it asserts nothing about the live platform |
| **Blocked, empty or unresolved element** | **The absent connector is the mandatory element.** Nothing on this visual may join the two panels |
| **Content to omit** | **Any connector between the panels** · any equals sign · anything at all in the gutter |
| **Likely producer failure** | Adding a connector between the panels, because two panels invite pairing |
| **Accessibility note** | **The absent connector is stated in text**, because an absence cannot be perceived |
| **Intended native PowerPoint treatment** | Two identical rectangles, **an empty gutter**, arrows inside the right panel only |
| **Deliverable from repository source alone** | **YES** |

### Slide 9 — The eight controlled steps, and the two that change state

| Field | Value |
|---|---|
| **Slide number** | 9 |
| **Slide title** | The eight controlled steps, and the two that change state |
| **Visual identifier** | **`W9`** — The eight controlled steps, classified |
| **Source identifier** | `M04-S09` |
| **Source path** | [`source/M04-S09-eight-controlled-steps.md`](source/M04-S09-eight-controlled-steps.md) |
| **Visual form** | Grouped table — **native layout, not Mermaid** |
| **Five-second takeaway** | Eight controlled steps. Only two of them change the information state. |
| **Principal visible labels** | `T1`–`T8` in five kind groups · `ESTABLISHED` · `BLOCKED` · `Shared → Shared` · `Published → Published` · `Only T1 and T4 change information state` |
| **Required source or status labels** | **Mixed** — `T1` controlled · `T4` **`BLOCKED`** · `T7` **`UNRESOLVED`** · the rest proposed · **`IMPLEMENTATION UNVERIFIED`** — *"no complete traceable cycle"* |
| **Governance status** | **Mixed** — `T1` controlled · `T4` **`BLOCKED`** · `T7` **`UNRESOLVED`** · the rest proposed |
| **Implementation status** | **`IMPLEMENTATION UNVERIFIED`** — *"no complete traceable cycle"* |
| **Blocked, empty or unresolved element** | **YES** — `T4` blocked and `T7` unresolved, both in the same table |
| **Content to omit** | **Any flowchart, arrow chain or Mermaid** · group numbering · green-for-`T1` or red-for-`T4` |
| **Likely producer failure** | **Converting the table to a flowchart**, because eight identifiers look like a sequence |
| **Accessibility note** | A real table with a header row; `T1`/`T4` distinguished by weight, never colour; no empty cells |
| **Intended native PowerPoint treatment** | One **native table**, banding off, no SmartArt conversion |
| **Deliverable from repository source alone** | **YES** |

### Slide 10 — Gates, authority and evidence

| Field | Value |
|---|---|
| **Slide number** | 10 |
| **Slide title** | Gates, authority and evidence |
| **Visual identifier** | **`W10`** — The `T1` gate model |
| **Source identifier** | `M04-S10` |
| **Source path** | [`source/M04-S10-t1-gate-model.md`](source/M04-S10-t1-gate-model.md) |
| **Visual form** | One horizontal chain — **native layout, not Mermaid** |
| **Five-second takeaway** | A transition needs checks, an authority and evidence. Not one of the three is optional. |
| **Principal visible labels** | `WIP` · `SHARED` · `Author` · `Checker` · `Task-Team Lead` · `receiving user` · `EVIDENCE` · `NO PARTIAL PROGRESSION` |
| **Required source or status labels** | **`CONTROLLED GOVERNANCE`** — the only transition with an established authority · **`IMPLEMENTATION UNVERIFIED`** — no complete cycle demonstrated |
| **Governance status** | **`CONTROLLED GOVERNANCE`** — the only transition with an established authority |
| **Implementation status** | **`IMPLEMENTATION UNVERIFIED`** — no complete cycle demonstrated |
| **Blocked, empty or unresolved element** | **The evidence field is the mandatory element.** It is what distinguishes a governed transition from a file move, and it may not be abbreviated away |
| **Content to omit** | Any publication path · any green tick or completion marker · the full eight-item readiness list · a folder icon for evidence |
| **Likely producer failure** | Compressing the evidence field for space, or replacing it with a folder icon |
| **Accessibility note** | The evidence field is named text, never an icon; CDE Administration's position stated in words |
| **Intended native PowerPoint treatment** | One connector, four equal column text boxes, CDE Administration outside the chain |
| **Deliverable from repository source alone** | **YES** |

### Slide 11 — Why `Shared → Published` remains blocked

| Field | Value |
|---|---|
| **Slide number** | 11 |
| **Slide title** | Why `Shared → Published` remains blocked |
| **Visual identifier** | **`W11`** — `T4` and `TRN-E03`, two blocked objects |
| **Source identifier** | `M04-S11` |
| **Source path** | [`source/M04-S11-t4-and-trn-e03.md`](source/M04-S11-t4-and-trn-e03.md) |
| **Visual form** | Two panels — **native layout, not Mermaid** |
| **Five-second takeaway** | Two different blocked things. Fixing the transition would not deliver anything. |
| **Principal visible labels** | `PANEL 1 · T4` · `PANEL 2 · TRN-E03` · `exercises T4` · `TBD` · `Status: BLOCKED` · `Status: PROPOSED — BLOCKED` · `Blocked by FIVE matters` · `T4 is blocked by ONE` |
| **Required source or status labels** | **`BLOCKED`** — both. Two authorities **`UNRESOLVED`** · **Not reached.** *"No governed publication / exchange authority evidence was established"* |
| **Governance status** | **`BLOCKED`** — both. Two authorities **`UNRESOLVED`** |
| **Implementation status** | **Not reached.** *"No governed publication / exchange authority evidence was established"* |
| **Blocked, empty or unresolved element** | **YES — the visual is two blocks**, plus an empty authority position on Panel 1 |
| **Content to omit** | Any merged object · any connector between the panels · any invented recipient, format or deliverable · red styling |
| **Likely producer failure** | Merging the two panels into one publication-to-acceptance chain |
| **Accessibility note** | Separateness stated in words; the block is not red; the empty position is not shaded |
| **Intended native PowerPoint treatment** | Two identical rectangles, an unfilled inner rectangle, **no connector across the gutter** |
| **Deliverable from repository source alone** | **YES** |

### Slide 12 — Naming, revision, suitability and metadata support control

| Field | Value |
|---|---|
| **Slide number** | 12 |
| **Slide title** | Naming, revision, suitability and metadata support control |
| **Visual identifier** | **`W12`** — The property stack and the four unestablished standards |
| **Source identifier** | `M04-S12` |
| **Source path** | [`source/M04-S12-property-stack.md`](source/M04-S12-property-stack.md) |
| **Visual form** | Two zones — six rows, four empty boxes — **native layout, not Mermaid** |
| **Five-second takeaway** | The properties control identification and permitted use. Four of the standards behind them have not been decided. |
| **Principal visible labels** | Six properties with their control questions · `Naming standard` · `Revision convention` · `Suitability code set` · `Metadata schema`, each `not established` |
| **Required source or status labels** | **`CONTROLLED GOVERNANCE`** — what each property must support. **`UNRESOLVED`** — every code set and the schema · **No standard established.** All four `standards/` directories hold only `.gitkeep` |
| **Governance status** | **`CONTROLLED GOVERNANCE`** — what each property must support. **`UNRESOLVED`** — every code set and the schema |
| **Implementation status** | **No standard established.** All four `standards/` directories hold only `.gitkeep` |
| **Blocked, empty or unresolved element** | **YES — four empty boxes, shown and unfilled** |
| **Content to omit** | Any code, filename, field name or schema · any classification system · a properties-palette screenshot · a date |
| **Likely producer failure** | **Filling one of the four empty boxes with an example**, or dating them as in progress |
| **Accessibility note** | `not established` is text, not whitespace; empty boxes are not shaded or hatched |
| **Intended native PowerPoint treatment** | One two-column table, four **unfilled** rectangles, no icons |
| **Deliverable from repository source alone** | **YES** |

### Slide 13 — Governance first; permissions and configuration follow

| Field | Value |
|---|---|
| **Slide number** | 13 |
| **Slide title** | Governance first; permissions and configuration follow |
| **Visual identifier** | **`W13`** — Governance, then configuration |
| **Source identifier** | `M04-S13` |
| **Source path** | [`source/M04-S13-governance-then-configuration.md`](source/M04-S13-governance-then-configuration.md) |
| **Visual form** | Chain, refused reverse, two boxes — **native layout, not Mermaid** |
| **Five-second takeaway** | Configuration implements governance. It does not create it. |
| **Principal visible labels** | `Governance decision` → `Process rule` → `Permission / configuration` → `Implementation evidence` · `Platform setting ──✕──▶ governance authority` · `Holder: TBD` |
| **Required source or status labels** | **`CONTROLLED GOVERNANCE`** · **`IMPLEMENTATION UNVERIFIED`** — `S2` §6 records alignment as a four-layer question |
| **Governance status** | **`CONTROLLED GOVERNANCE`** |
| **Implementation status** | **`IMPLEMENTATION UNVERIFIED`** — `S2` §6 records alignment as a four-layer question |
| **Blocked, empty or unresolved element** | **YES — the refused reverse arrow, and `Holder: TBD`** |
| **Content to omit** | Any permissions screenshot or matrix · a named administrator · an org chart · a loop back to the start |
| **Likely producer failure** | Dropping the reverse arrow, leaving a chain that can be read backwards |
| **Accessibility note** | The refusal is text as well as stroke; not red; legible in monochrome as a break plus a cross |
| **Intended native PowerPoint treatment** | Four rectangles, three arrows, one **broken and struck** reverse arrow, two equal boxes |
| **Deliverable from repository source alone** | **YES** |

### Slide 14 — What Triviron must define before configuring its CDE

| Field | Value |
|---|---|
| **Slide number** | 14 |
| **Slide title** | What Triviron must define before configuring its CDE |
| **Visual identifier** | **`W14`** — Triviron CDE-definition questions |
| **Source identifier** | `M04-S14` |
| **Source path** | [`source/M04-S14-triviron-questions.md`](source/M04-S14-triviron-questions.md) |
| **Visual form** | Five question groups — **native layout, not Mermaid** |
| **Five-second takeaway** | These are the decisions. Make them before you configure anything. |
| **Principal visible labels** | Five group headings · `Who holds publication authority?` · `Who holds acceptance authority?` · `CDE configuration basis — not yet established` |
| **Required source or status labels** | **None asserted for Triviron** — the project has no entry in any register · **None asserted for Triviron** |
| **Governance status** | **None asserted for Triviron** — the project has no entry in any register |
| **Implementation status** | **None asserted for Triviron** |
| **Blocked, empty or unresolved element** | **YES — the two authority questions stay unanswered, and the end state stays open** |
| **Content to omit** | **Every Triviron fact** · every answer, default, placeholder and recommendation · any status colour on the end state |
| **Likely producer failure** | Balancing a sparse slide with an illustrative answer — **which invents the project** |
| **Accessibility note** | Every item reads as a question; the end state is neutral in colour and text |
| **Intended native PowerPoint treatment** | Five text blocks, one bordered authority block, no icons, no progress indicator |
| **Deliverable from repository source alone** | **YES** |

---

## 3. Reading this map with the plan

**This map is navigational.** It carries the slide-to-visual relationship, the
takeaway, the labels a producer must not lose, and the omissions.

**It is not a substitute for the source file or the specification.** Geometry,
exact wording, connector semantics, build constraints and STOP conditions live in
[`source/`](source/) and, above that, in the visual-demonstration plan.

**Where this map and the plan differ, the plan is authoritative.**
