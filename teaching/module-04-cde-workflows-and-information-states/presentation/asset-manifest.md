# Module 4 — Asset Manifest

**Status:** Visual-source manifest for PowerPoint production. **Not governance.**

---

## 1. The position, stated once

| Question | Answer |
|---|---|
| How many visual sources? | **Fourteen** — `M04-S01`–`M04-S14`, one per slide |
| What form are they in? | **Markdown native-layout specifications** |
| Does any rendered SVG, PNG, JPG or PDF exist? | **No** |
| Is any rendering required? | **No** |
| Is any live Autodesk evidence required? | **No**, for any slide |
| Is any external imagery required? | **No**, for any slide |
| How are the diagrams built? | **Rebuilt using native PowerPoint objects** — shapes, text boxes, tables, lines, borders, connectors |
| Would a future rendered asset be authoritative? | **No.** It would be derivative and non-authoritative |
| Does any source use Mermaid? | **No.** No visual in Module 4 is Mermaid |

**No entry in this manifest is an image.** Every one is a specification to be
rebuilt.

## 2. Summary

| Slide | `W` | Source | Native treatment | Import allowed | Screenshot allowed |
|---|---|---|---|---|---|
| 1 | **`W1`** | [`M04-S01`](../../assets/module-04/source/M04-S01-governance-workflow-platform.md) | **Stacked bands** | **No** | **No** |
| 2 | **`W2`** | [`M04-S02`](../../assets/module-04/source/M04-S02-five-properties.md) | **Equal cards** | **No** | **No** |
| 3 | **`W3`** | [`M04-S03`](../../assets/module-04/source/M04-S03-four-state-model.md) | **Concept panels** | **No** | **No** |
| 4 | **`W4`** | [`M04-S04`](../../assets/module-04/source/M04-S04-wip-task-team-boundary.md) | **Responsibility boundary** | **No** | **No** |
| 5 | **`W5`** | [`M04-S05`](../../assets/module-04/source/M04-S05-shared-defined-purpose.md) | **Central container and call-outs** | **No** | **No** |
| 6 | **`W6`** | [`M04-S06`](../../assets/module-04/source/M04-S06-publication-authority-gate.md) | **Blocked gate** | **No** | **No** |
| 7 | **`W7`** | [`M04-S07`](../../assets/module-04/source/M04-S07-retention-obligation-versus-method.md) | **Obligation / method comparison** | **No** | **No** |
| 8 | **`W8`** | [`M04-S08`](../../assets/module-04/source/M04-S08-file-movement-versus-transition.md) | **Two-panel contrast** | **No** | **No** |
| 9 | **`W9`** | [`M04-S09`](../../assets/module-04/source/M04-S09-eight-controlled-steps.md) | **Classified table** | **No** | **No** |
| 10 | **`W10`** | [`M04-S10`](../../assets/module-04/source/M04-S10-t1-gate-model.md) | **Gate-and-evidence model** | **No** | **No** |
| 11 | **`W11`** | [`M04-S11`](../../assets/module-04/source/M04-S11-t4-and-trn-e03.md) | **Paired blocked-object panels** | **No** | **No** |
| 12 | **`W12`** | [`M04-S12`](../../assets/module-04/source/M04-S12-property-stack.md) | **Property stack** | **No** | **No** |
| 13 | **`W13`** | [`M04-S13`](../../assets/module-04/source/M04-S13-governance-then-configuration.md) | **One-way governance chain with refused reverse route** | **No** | **No** |
| 14 | **`W14`** | [`M04-S14`](../../assets/module-04/source/M04-S14-triviron-questions.md) | **Question framework** | **No** | **No** |

## 3. Manifest entries

### Slide 1 — `W1` · Governance → workflow → platform

| Field | Value |
|---|---|
| **Slide** | 1 — *A CDE is a governed process, not a folder tree* |
| **Visual identifier** | **`W1`** |
| **Slide-source identifier** | `M04-S01` |
| **Slide-source path** | [`M04-S01-governance-workflow-platform.md`](../../assets/module-04/source/M04-S01-governance-workflow-platform.md) |
| **Fixed source form** | **Three stacked horizontal bands of equal width and equal height, top to bottom.** Never side by side |
| **Intended native PowerPoint treatment** | **Stacked bands** — three equal rectangles, two straight connectors. Three rectangles, two straight connectors, no SmartArt |
| **Imported rendering allowed** | **No** |
| **External imagery allowed** | **No** |
| **Screenshot allowed** | **No** |
| **Governance status** | Band 1 **`CONTROLLED GOVERNANCE`** · Band 2 **`PROPOSED GOVERNANCE`** · Band 3 topology adopted (`S3` §2) |
| **Implementation status** | Band 3 **`IMPLEMENTATION UNVERIFIED`** (`CGD-C07`). Bands 1 and 2 make no implementation claim |
| **Blocked, empty or unresolved element** | No blocked route. **The three status labels are the mandatory element** — without them the diagram asserts a verified operating architecture |
| **Mandatory visible warning** | **`PROPOSED GOVERNANCE` on Band 2 does the warning's work.** It is not optional, not abbreviated and not moved to the notes |
| **Accessibility requirement** | Statuses are words, not tints; reading order strictly top to bottom |
| **Producer prohibition** | That the platform **is** the CDE, that configuration defines governance, or that the workflow is verified live |
| **Proposed external PowerPoint asset name** | `M04-S01-group` — **a shape-group name inside the deck, not a file.** No asset file is produced |

**Must not appear.** Platform logo, screenshot or product name · any upward arrow · any org-chart shape

---

### Slide 2 — `W2` · The five-property comparison

| Field | Value |
|---|---|
| **Slide** | 2 — *State, version, revision, status and suitability are different* |
| **Visual identifier** | **`W2`** |
| **Slide-source identifier** | `M04-S02` |
| **Slide-source path** | [`M04-S02-five-properties.md`](../../assets/module-04/source/M04-S02-five-properties.md) |
| **Fixed source form** | **Five equal cards in a single row.** Not a grid, not columns, not a stack |
| **Intended native PowerPoint treatment** | **Equal cards** — five rectangles in one row, nothing between them. Five rectangles, nothing between them, no SmartArt |
| **Imported rendering allowed** | **No** |
| **External imagery allowed** | **No** |
| **Screenshot allowed** | **No** |
| **Governance status** | **`CONTROLLED GOVERNANCE`** — all five definitions. **`UNRESOLVED`** — the revision, status and suitability code sets |
| **Implementation status** | **Not applicable.** This visual makes no implementation claim, and must not appear to |
| **Blocked, empty or unresolved element** | **YES — the three absent code sets**, named on their own cards |
| **Mandatory visible warning** | **The three `established` negatives are the warning.** They stay on the cards and are not collected into a footnote, where they would read as a caveat rather than as the project's position |
| **Accessibility requirement** | Five cards are peers, not a list with a first item; no meaning in fill |
| **Producer prohibition** | That the five properties are **stages**, that one creates another, or that a code set exists for any of them |
| **Proposed external PowerPoint asset name** | `M04-S02-group` — **a shape-group name inside the deck, not a file.** No asset file is produced |

**Must not appear.** Any connector · any example code or filename · **metadata as a sixth card**

---

### Slide 3 — `W3` · The four-state model

| Field | Value |
|---|---|
| **Slide** | 3 — *The Harrismith information-state model* |
| **Visual identifier** | **`W3`** |
| **Slide-source identifier** | `M04-S03` |
| **Slide-source path** | [`M04-S03-four-state-model.md`](../../assets/module-04/source/M04-S03-four-state-model.md) |
| **Fixed source form** | **Four concept panels in one horizontal row**, equal size, three connectors in the gutters, labels beneath |
| **Intended native PowerPoint treatment** | **Concept panels** — four rectangles, three connectors of three different kinds. Four rectangles, three connectors of **three different kinds**, four text blocks |
| **Imported rendering allowed** | **No** |
| **External imagery allowed** | **No** |
| **Screenshot allowed** | **No** |
| **Governance status** | **Per panel** — two `CONTROLLED GOVERNANCE`, one **`BLOCKED`**, one **`UNRESOLVED`** |
| **Implementation status** | **Per panel** — two `IMPLEMENTATION UNVERIFIED`, one **Not reached**, one **Not addressed** |
| **Blocked, empty or unresolved element** | **YES — three of them.** The `T4` break, the empty publication authority, and an unreachable third connector |
| **Mandatory visible warning** | **`Conceptual state model — not proof of live platform implementation`** — on the visual, centred beneath the connector labels, at body size. **Not in the footer, not in the notes, not shrunk to a caption** |
| **Accessibility requirement** | **Connector meaning in text as well as line style**; no red or green; legible in monochrome |
| **Producer prohibition** | That the four states **operate**, that folders and states align one to one, or that Record / Retained is a folder |
| **Proposed external PowerPoint asset name** | `M04-S03-group` — **a shape-group name inside the deck, not a file.** No asset file is produced |

**Must not appear.** **`04 Archive`** · folder icons as states · a four-area row beneath the panels · Delivered, Received or Accepted

---

### Slide 4 — `W4` · The WIP task-team boundary

| Field | Value |
|---|---|
| **Slide** | 4 — *Work in Progress: authoring inside the task team* |
| **Visual identifier** | **`W4`** |
| **Slide-source identifier** | `M04-S04` |
| **Slide-source path** | [`M04-S04-wip-task-team-boundary.md`](../../assets/module-04/source/M04-S04-wip-task-team-boundary.md) |
| **Fixed source form** | **One boundary**, three functions inside, several versions inside, one observer outside |
| **Intended native PowerPoint treatment** | **Responsibility boundary** — one enclosing rectangle, one outside marker. One boundary rectangle, one outside marker, no connector leaving it |
| **Imported rendering allowed** | **No** |
| **External imagery allowed** | **No** |
| **Screenshot allowed** | **No** |
| **Governance status** | **`CONTROLLED GOVERNANCE`** |
| **Implementation status** | **`IMPLEMENTATION UNVERIFIED`** — one qualified container observation |
| **Blocked, empty or unresolved element** | **No route out is drawn.** The Task-Team Lead gate is visible on the boundary and **no connector leaves it** |
| **Mandatory visible warning** | **`Visibility is not permission. Permission to read is not authorisation to rely.`** — `S1` §7.5, on the slide |
| **Accessibility requirement** | `MAY NOT RELY` is words, not a colour; the boundary's meaning is stated inside it |
| **Producer prohibition** | That **visibility permits reliance**, that the boundary is a permission setting, or that WIP progresses automatically |
| **Proposed external PowerPoint asset name** | `M04-S04-group` — **a shape-group name inside the deck, not a file.** No asset file is produced |

**Must not appear.** Any arrow leaving the boundary · a padlock or permission shield · a named person · a green tick

---

### Slide 5 — `W5` · Shared — permitted use for a defined purpose

| Field | Value |
|---|---|
| **Slide** | 5 — *Shared: controlled use for a defined purpose* |
| **Visual identifier** | **`W5`** |
| **Slide-source identifier** | `M04-S05` |
| **Slide-source path** | [`M04-S05-shared-defined-purpose.md`](../../assets/module-04/source/M04-S05-shared-defined-purpose.md) |
| **Fixed source form** | **One central container**, two or three purpose call-outs, one retained-responsibility line |
| **Intended native PowerPoint treatment** | **Central container and call-outs** — one rectangle, terminating call-out lines. One rectangle, a persistent originator line, three terminating call-outs |
| **Imported rendering allowed** | **No** |
| **External imagery allowed** | **No** |
| **Screenshot allowed** | **No** |
| **Governance status** | **`CONTROLLED GOVERNANCE`** — `T1`'s authorising function is established |
| **Implementation status** | **`IMPLEMENTATION UNVERIFIED`** — *"only Architecture currently demonstrable as a Shared input"* |
| **Blocked, empty or unresolved element** | None on this visual. **`W5` is the module's only visual with no mandatory incomplete element** — its control is the warning and the retained-responsibility line |
| **Mandatory visible warning** | **`Shared means authorised for A DEFINED USE. It does not mean approved for EVERY use.`** — on the slide |
| **Accessibility requirement** | `RESPONSIBILITY RETAINED` is text, not line weight; **no green anywhere** |
| **Producer prohibition** | That Shared means **approved**, that responsibility transferred, or that placement in `02. Shared` evidences checking |
| **Proposed external PowerPoint asset name** | `M04-S05-group` — **a shape-group name inside the deck, not a file.** No asset file is produced |

**Must not appear.** Any approval, publication or acceptance symbol · **any green** · a handover arrow · an invented example purpose

---

### Slide 6 — `W6` · The publication-authority gate

| Field | Value |
|---|---|
| **Slide** | 6 — *Published / Authorised: a separate decision and authority* |
| **Visual identifier** | **`W6`** |
| **Slide-source identifier** | `M04-S06` |
| **Slide-source path** | [`M04-S06-publication-authority-gate.md`](../../assets/module-04/source/M04-S06-publication-authority-gate.md) |
| **Fixed source form** | **One Shared input, one gate, one empty authority position, one blocked output** |
| **Intended native PowerPoint treatment** | **Blocked gate** — one gate rectangle with an unfilled inner rectangle. One gate rectangle with an **unfilled inner rectangle**, one solid and one broken connector |
| **Imported rendering allowed** | **No** |
| **External imagery allowed** | **No** |
| **Screenshot allowed** | **No** |
| **Governance status** | **`BLOCKED`** — the authority is **`UNRESOLVED`** |
| **Implementation status** | **Not reached** |
| **Blocked, empty or unresolved element** | **YES — the authority position is drawn empty, and the output is broken** |
| **Mandatory visible warning** | **`T4 BLOCKED` · `No available authorising function` · `INFORMATION REMAINS SHARED`** — all three on the slide |
| **Accessibility requirement** | The block is words, not a dashed stroke alone; the empty position is legible as empty |
| **Producer prohibition** | That **anyone holds** publication authority, that the block is a fault, or that an administrator may substitute |
| **Proposed external PowerPoint asset name** | `M04-S06-group` — **a shape-group name inside the deck, not a file.** No asset file is produced |

**Must not appear.** Any named or implied holder · any solid `Shared → Published` arrow · any checkmark · **any red failure styling**

---

### Slide 7 — `W7` · Retention obligation versus method

| Field | Value |
|---|---|
| **Slide** | 7 — *Record / Retained: preservation without an Archive folder* |
| **Visual identifier** | **`W7`** |
| **Slide-source identifier** | `M04-S07` |
| **Slide-source path** | [`M04-S07-retention-obligation-versus-method.md`](../../assets/module-04/source/M04-S07-retention-obligation-versus-method.md) |
| **Fixed source form** | **Two panels, side by side, the same size** — obligation established, method unresolved |
| **Intended native PowerPoint treatment** | **Obligation / method comparison** — two identical rectangles, empty gutter. Two identical rectangles, **no icons**, an empty gutter |
| **Imported rendering allowed** | **No** |
| **External imagery allowed** | **No** |
| **Screenshot allowed** | **No** |
| **Governance status** | **`CONTROLLED GOVERNANCE`** — the obligation. **`UNRESOLVED`** — the method |
| **Implementation status** | **Not addressed in any validation record** |
| **Blocked, empty or unresolved element** | **YES — the method panel is visibly empty**, with four unfilled fields |
| **Mandatory visible warning** | **`Record / Retained is a state or obligation. It is NOT automatically a folder.`** — on the slide |
| **Accessibility requirement** | `TBD` and `unavailable` are text — whitespace alone would be skipped by a screen reader |
| **Producer prohibition** | That an **`04 Archive` exists or is proposed**, or that a retention period, location or holder has been decided |
| **Proposed external PowerPoint asset name** | `M04-S07-group` — **a shape-group name inside the deck, not a file.** No asset file is produced |

**Must not appear.** **`04 Archive` in any form** · folder or storage icons · an invented retention period or holder · a destination arrow

---

### Slide 8 — `W8` · File movement versus authorised transition

| Field | Value |
|---|---|
| **Slide** | 8 — *A transition is more than moving a file* |
| **Visual identifier** | **`W8`** |
| **Slide-source identifier** | `M04-S08` |
| **Slide-source path** | [`M04-S08-file-movement-versus-transition.md`](../../assets/module-04/source/M04-S08-file-movement-versus-transition.md) |
| **Fixed source form** | **Two panels, side by side, the same size, with no connector between them** |
| **Intended native PowerPoint treatment** | **Two-panel contrast** — two identical rectangles, empty gutter, arrows inside the right panel only. Two identical rectangles, **an empty gutter**, arrows inside the right panel only |
| **Imported rendering allowed** | **No** |
| **External imagery allowed** | **No** |
| **Screenshot allowed** | **No** |
| **Governance status** | **`CONTROLLED GOVERNANCE`** — `CGD-C03` is an active condition |
| **Implementation status** | **Not applicable.** This visual compares two kinds of act; it asserts nothing about the live platform |
| **Blocked, empty or unresolved element** | **The absent connector is the mandatory element.** Nothing on this visual may join the two panels |
| **Mandatory visible warning** | **`NO CONNECTOR. The left does not produce the right.`** — on the slide, between the panels |
| **Accessibility requirement** | **The absent connector is stated in text**, because an absence cannot be perceived |
| **Producer prohibition** | That a **technical action produces** a governed transition, or that software capability establishes authority |
| **Proposed external PowerPoint asset name** | `M04-S08-group` — **a shape-group name inside the deck, not a file.** No asset file is produced |

**Must not appear.** **Any connector between the panels** · any equals sign · anything at all in the gutter

---

### Slide 9 — `W9` · The eight controlled steps, classified

| Field | Value |
|---|---|
| **Slide** | 9 — *The eight controlled steps, and the two that change state* |
| **Visual identifier** | **`W9`** |
| **Slide-source identifier** | `M04-S09` |
| **Slide-source path** | [`M04-S09-eight-controlled-steps.md`](../../assets/module-04/source/M04-S09-eight-controlled-steps.md) |
| **Fixed source form** | **A table grouped by kind.** Five groups, eight rows — **never a flowchart, never Mermaid** |
| **Intended native PowerPoint treatment** | **Classified table** — one native table, grouped by kind, banding off. One **native table**, banding off, no SmartArt conversion |
| **Imported rendering allowed** | **No** |
| **External imagery allowed** | **No** |
| **Screenshot allowed** | **No** |
| **Governance status** | **Mixed** — `T1` controlled · `T4` **`BLOCKED`** · `T7` **`UNRESOLVED`** · the rest proposed |
| **Implementation status** | **`IMPLEMENTATION UNVERIFIED`** — *"no complete traceable cycle"* |
| **Blocked, empty or unresolved element** | **YES** — `T4` blocked and `T7` unresolved, both in the same table |
| **Mandatory visible warning** | **`Only T1 and T4 change information state.`** — as a prominent headline, on the slide |
| **Accessibility requirement** | A real table with a header row; `T1`/`T4` distinguished by weight, never colour; no empty cells |
| **Producer prohibition** | That the eight steps run **in order**, that all eight are transitions, or that a complete cycle has been demonstrated |
| **Proposed external PowerPoint asset name** | `M04-S09-group` — **a shape-group name inside the deck, not a file.** No asset file is produced |

**Must not appear.** **Any flowchart, arrow chain or Mermaid** · group numbering · green-for-`T1` or red-for-`T4`

---

### Slide 10 — `W10` · The `T1` gate model

| Field | Value |
|---|---|
| **Slide** | 10 — *Gates, authority and evidence* |
| **Visual identifier** | **`W10`** |
| **Slide-source identifier** | `M04-S10` |
| **Slide-source path** | [`M04-S10-t1-gate-model.md`](../../assets/module-04/source/M04-S10-t1-gate-model.md) |
| **Fixed source form** | **One transition, five stages, four side labels.** Nothing else |
| **Intended native PowerPoint treatment** | **Gate-and-evidence model** — one connector, four equal column text boxes. One connector, four equal column text boxes, CDE Administration outside the chain |
| **Imported rendering allowed** | **No** |
| **External imagery allowed** | **No** |
| **Screenshot allowed** | **No** |
| **Governance status** | **`CONTROLLED GOVERNANCE`** — the only transition with an established authority |
| **Implementation status** | **`IMPLEMENTATION UNVERIFIED`** — no complete cycle demonstrated |
| **Blocked, empty or unresolved element** | **The evidence field is the mandatory element.** It is what distinguishes a governed transition from a file move, and it may not be abbreviated away |
| **Mandatory visible warning** | **`Governance definition ≠ live implementation evidence`** — on the slide |
| **Accessibility requirement** | The evidence field is named text, never an icon; CDE Administration's position stated in words |
| **Producer prohibition** | That `T1` is **running live**, that CDE Administration decides, or that a folder location satisfies the evidence requirement |
| **Proposed external PowerPoint asset name** | `M04-S10-group` — **a shape-group name inside the deck, not a file.** No asset file is produced |

**Must not appear.** Any publication path · any green tick or completion marker · the full eight-item readiness list · a folder icon for evidence

---

### Slide 11 — `W11` · `T4` and `TRN-E03`, two blocked objects

| Field | Value |
|---|---|
| **Slide** | 11 — *Why `Shared → Published` remains blocked* |
| **Visual identifier** | **`W11`** |
| **Slide-source identifier** | `M04-S11` |
| **Slide-source path** | [`M04-S11-t4-and-trn-e03.md`](../../assets/module-04/source/M04-S11-t4-and-trn-e03.md) |
| **Fixed source form** | **Two panels, side by side, equal weight.** `T4` left, `TRN-E03` right |
| **Intended native PowerPoint treatment** | **Paired blocked-object panels** — two identical rectangles, one unfilled inner rectangle. Two identical rectangles, an unfilled inner rectangle, **no connector across the gutter** |
| **Imported rendering allowed** | **No** |
| **External imagery allowed** | **No** |
| **Screenshot allowed** | **No** |
| **Governance status** | **`BLOCKED`** — both. Two authorities **`UNRESOLVED`** |
| **Implementation status** | **Not reached.** *"No governed publication / exchange authority evidence was established"* |
| **Blocked, empty or unresolved element** | **YES — the visual is two blocks**, plus an empty authority position on Panel 1 |
| **Mandatory visible warning** | **`Satisfying T4 alone would not automatically complete delivery.`** — on the slide, beneath both panels |
| **Accessibility requirement** | Separateness stated in words; the block is not red; the empty position is not shaded |
| **Producer prohibition** | That `T4` and `TRN-E03` are **the same object**, or that resolving `T4` would complete delivery |
| **Proposed external PowerPoint asset name** | `M04-S11-group` — **a shape-group name inside the deck, not a file.** No asset file is produced |

**Must not appear.** Any merged object · any connector between the panels · any invented recipient, format or deliverable · red styling

---

### Slide 12 — `W12` · The property stack and the four unestablished standards

| Field | Value |
|---|---|
| **Slide** | 12 — *Naming, revision, suitability and metadata support control* |
| **Visual identifier** | **`W12`** |
| **Slide-source identifier** | `M04-S12` |
| **Slide-source path** | [`M04-S12-property-stack.md`](../../assets/module-04/source/M04-S12-property-stack.md) |
| **Fixed source form** | **Two zones.** Left: six property rows, each with its control question. Right: four boxes, all **empty** |
| **Intended native PowerPoint treatment** | **Property stack** — one two-column table plus four unfilled rectangles. One two-column table, four **unfilled** rectangles, no icons |
| **Imported rendering allowed** | **No** |
| **External imagery allowed** | **No** |
| **Screenshot allowed** | **No** |
| **Governance status** | **`CONTROLLED GOVERNANCE`** — what each property must support. **`UNRESOLVED`** — every code set and the schema |
| **Implementation status** | **No standard established.** All four `standards/` directories hold only `.gitkeep` |
| **Blocked, empty or unresolved element** | **YES — four empty boxes, shown and unfilled** |
| **Mandatory visible warning** | **`A code identifies. It does not authorise, and it does not prove the process behind it occurred.`** — on the slide |
| **Accessibility requirement** | `not established` is text, not whitespace; empty boxes are not shaded or hatched |
| **Producer prohibition** | That any **naming, revision, suitability or metadata standard exists**, is in progress, or is due on a date |
| **Proposed external PowerPoint asset name** | `M04-S12-group` — **a shape-group name inside the deck, not a file.** No asset file is produced |

**Must not appear.** Any code, filename, field name or schema · any classification system · a properties-palette screenshot · a date

---

### Slide 13 — `W13` · Governance, then configuration

| Field | Value |
|---|---|
| **Slide** | 13 — *Governance first; permissions and configuration follow* |
| **Visual identifier** | **`W13`** |
| **Slide-source identifier** | `M04-S13` |
| **Slide-source path** | [`M04-S13-governance-then-configuration.md`](../../assets/module-04/source/M04-S13-governance-then-configuration.md) |
| **Fixed source form** | **One forward chain, one visibly refused reverse arrow, one may/does-not table** |
| **Intended native PowerPoint treatment** | **One-way governance chain with refused reverse route** — four rectangles, three arrows, one struck reverse arrow. Four rectangles, three arrows, one **broken and struck** reverse arrow, two equal boxes |
| **Imported rendering allowed** | **No** |
| **External imagery allowed** | **No** |
| **Screenshot allowed** | **No** |
| **Governance status** | **`CONTROLLED GOVERNANCE`** |
| **Implementation status** | **`IMPLEMENTATION UNVERIFIED`** — `S2` §6 records alignment as a four-layer question |
| **Blocked, empty or unresolved element** | **YES — the refused reverse arrow, and `Holder: TBD`** |
| **Mandatory visible warning** | **`A configuration that was never approved is a deviation, however competently it was applied.`** — `S1` §5.9, verbatim, on the slide |
| **Accessibility requirement** | The refusal is text as well as stroke; not red; legible in monochrome as a break plus a cross |
| **Producer prohibition** | That **configuration creates authority**, that permissions assign it, or that a platform setting proves implementation |
| **Proposed external PowerPoint asset name** | `M04-S13-group` — **a shape-group name inside the deck, not a file.** No asset file is produced |

**Must not appear.** Any permissions screenshot or matrix · a named administrator · an org chart · a loop back to the start

---

### Slide 14 — `W14` · Triviron CDE-definition questions

| Field | Value |
|---|---|
| **Slide** | 14 — *What Triviron must define before configuring its CDE* |
| **Visual identifier** | **`W14`** |
| **Slide-source identifier** | `M04-S14` |
| **Slide-source path** | [`M04-S14-triviron-questions.md`](../../assets/module-04/source/M04-S14-triviron-questions.md) |
| **Fixed source form** | **Five grouped question sets**, then two isolated authority questions, then the end state |
| **Intended native PowerPoint treatment** | **Question framework** — five text blocks, one bordered authority block. Five text blocks, one bordered authority block, no icons, no progress indicator |
| **Imported rendering allowed** | **No** |
| **External imagery allowed** | **No** |
| **Screenshot allowed** | **No** |
| **Governance status** | **None asserted for Triviron** — the project has no entry in any register |
| **Implementation status** | **None asserted for Triviron** |
| **Blocked, empty or unresolved element** | **YES — the two authority questions stay unanswered, and the end state stays open** |
| **Mandatory visible warning** | **`CDE configuration basis — not yet established`** — the end state, in **neutral styling**, with no warning colour, icon, date or owner |
| **Accessibility requirement** | Every item reads as a question; the end state is neutral in colour and text |
| **Producer prohibition** | Any **Triviron fact**, any answer to either authority question, or any platform recommendation |
| **Proposed external PowerPoint asset name** | `M04-S14-group` — **a shape-group name inside the deck, not a file.** No asset file is produced |

**Must not appear.** **Every Triviron fact** · every answer, default, placeholder and recommendation · any status colour on the end state

---

## 4. Naming

**The proposed asset names above are shape-group names inside the PowerPoint, not
filenames.** No image file is produced by this package, so no image filename is
proposed.

**Identifiers are stable.** `W1`–`W14` and `M04-S01`–`M04-S14` are not renamed or
renumbered to suit a deck, a tool or a later render.

**If rendering is ever undertaken** — it has not been authorised — the rules are
in [`../../assets/module-04/rendered/README.md`](../../assets/module-04/rendered/README.md)
§4. The short version: render from committed source unchanged, name the output
after its source identifier, prefer SVG, update the register, and **remember that
a render never becomes the authority.**

## 5. Status

| Field | Value |
|---|---|
| Visual sources | **14**, all `SOURCE COMPLETE` |
| Rendered assets | **`NONE`** — none exists, none required, none attempted |
| Imported assets permitted | **Zero** |
| Live Autodesk evidence required | **None**, for any slide |
| Construction | **Native PowerPoint objects only** |
