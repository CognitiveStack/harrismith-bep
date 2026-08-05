# Module 4 — Visual Register

**Status:** Visual-source baseline. **Not governance.** **No rendered assets
exist.**

Controlling document:
[`../../module-04-cde-workflows-and-information-states/visual-demonstration-plan.md`](../../module-04-cde-workflows-and-information-states/visual-demonstration-plan.md).
Its identifiers `W1`–`W14`, fixed forms, geometry, mandatory design
requirements, classifications and risk ratings are **authoritative and are not
renumbered or restated differently here.**

---

## 1. One identifier space, not two

```text
14 visual concepts
=
14 slides
=
14 slide-specific visual-source files
```

| Space | Count | Meaning |
|---|---|---|
| **`W1`–`W14`** | **14 visual concepts** | The controlling specifications in the visual-demonstration plan |
| **Slides 1–14** | **14 slides** | The presentation in [`presentation-outline.md`](../../module-04-cde-workflows-and-information-states/presentation-outline.md) |
| **`M04-S01`–`M04-S14`** | **14 slide-source files** | One per slide, in [`source/`](source/) |

**Module 4 has a strict one-to-one mapping.** **No visual concept serves more
than one slide**, **no slide has two primary visual concepts**, and there is **no
thirteen-versus-fourteen reconciliation to perform.**

**This differs from Module 3**, where `V1` served both Slide 1 and Slide 2 and
thirteen concepts produced fourteen files. **Module 4 does not have that
asymmetry**, and a reader carrying the Module 3 pattern across should not look
for one.

## 2. Summary

| `W` | Slide | Source file | Form | Overclaim risk | Source status | Rendered |
|---|---|---|---|---|---|---|
| **`W1`** | 1 | [`M04-S01`](source/M04-S01-governance-workflow-platform.md) | Three stacked bands | HIGH | **`SOURCE COMPLETE`** | **`NONE`** |
| **`W2`** | 2 | [`M04-S02`](source/M04-S02-five-properties.md) | Five equal cards, one row | MEDIUM-HIGH | **`SOURCE COMPLETE`** | **`NONE`** |
| **`W3`** | 3 | [`M04-S03`](source/M04-S03-four-state-model.md) | Four concept panels, three connectors | HIGHEST IN THE MODULE | **`SOURCE COMPLETE`** | **`NONE`** |
| **`W4`** | 4 | [`M04-S04`](source/M04-S04-wip-task-team-boundary.md) | One responsibility boundary | MEDIUM-HIGH | **`SOURCE COMPLETE`** | **`NONE`** |
| **`W5`** | 5 | [`M04-S05`](source/M04-S05-shared-defined-purpose.md) | One container, purpose call-outs | HIGH | **`SOURCE COMPLETE`** | **`NONE`** |
| **`W6`** | 6 | [`M04-S06`](source/M04-S06-publication-authority-gate.md) | Vertical gate | HIGH in both directions | **`SOURCE COMPLETE`** | **`NONE`** |
| **`W7`** | 7 | [`M04-S07`](source/M04-S07-retention-obligation-versus-method.md) | Two panels | MEDIUM-HIGH | **`SOURCE COMPLETE`** | **`NONE`** |
| **`W8`** | 8 | [`M04-S08`](source/M04-S08-file-movement-versus-transition.md) | Two panels, no connector | HIGH | **`SOURCE COMPLETE`** | **`NONE`** |
| **`W9`** | 9 | [`M04-S09`](source/M04-S09-eight-controlled-steps.md) | Grouped table | HIGHEST, jointly with `W3` | **`SOURCE COMPLETE`** | **`NONE`** |
| **`W10`** | 10 | [`M04-S10`](source/M04-S10-t1-gate-model.md) | One horizontal chain | MEDIUM-HIGH | **`SOURCE COMPLETE`** | **`NONE`** |
| **`W11`** | 11 | [`M04-S11`](source/M04-S11-t4-and-trn-e03.md) | Two panels | HIGH in both directions | **`SOURCE COMPLETE`** | **`NONE`** |
| **`W12`** | 12 | [`M04-S12`](source/M04-S12-property-stack.md) | Two zones — six rows, four empty boxes | HIGH | **`SOURCE COMPLETE`** | **`NONE`** |
| **`W13`** | 13 | [`M04-S13`](source/M04-S13-governance-then-configuration.md) | Chain, refused reverse, two boxes | MEDIUM-HIGH | **`SOURCE COMPLETE`** | **`NONE`** |
| **`W14`** | 14 | [`M04-S14`](source/M04-S14-triviron-questions.md) | Five question groups | HIGH | **`SOURCE COMPLETE`** | **`NONE`** |

**Fourteen concepts, fourteen slides, fourteen source files. All fourteen are
`SOURCE COMPLETE`. All fourteen rendered statuses are `NONE`.**

**Every form in the table above is a native layout specification.** **No visual
in Module 4 is Mermaid** — the reasoning is recorded in the visual-demonstration
plan §2 and its summary, concept by concept.

## 3. Register entries

### `W1` — Governance → workflow → platform

| Field | Value |
|---|---|
| **Visual identifier** | **`W1`** |
| **Title** | Governance → workflow → platform |
| **Slide** | 1 — *A CDE is a governed process, not a folder tree* |
| **Slide-source identifier** | `M04-S01` |
| **Slide-source path** | [`source/M04-S01-governance-workflow-platform.md`](source/M04-S01-governance-workflow-platform.md) |
| **Teaching purpose** | Show **three ordered layers**, governance above configuration, **each carrying its own status**. |
| **Principal source basis** | `S1` §6.1, §6.9, §12.1; `S2` §1, §14, §17; `S3` §2, §3; `S4` §9; **`CGD-C01`, `CGD-C07`** |
| **Classification** | `CONTROLLED` + `INTERP` — the layering is the presenter's framing; every band item is sourced |
| **Governance status** | Band 1 **`CONTROLLED GOVERNANCE`** · Band 2 **`PROPOSED GOVERNANCE`** · Band 3 topology adopted (`S3` §2) |
| **Implementation status** | Band 3 **`IMPLEMENTATION UNVERIFIED`** (`CGD-C07`). Bands 1 and 2 make no implementation claim |
| **Fixed form** | Three stacked bands — **native layout, not Mermaid** |
| **Source status** | **`SOURCE COMPLETE`** |
| **Overclaim risk** | **HIGH** — three tidy bands read as *this is how it runs* |
| **Mandatory warning** | **`PROPOSED GOVERNANCE` on Band 2 does the warning's work.** It is not optional, not abbreviated and not moved to the notes |
| **Blocked, empty or unresolved element** | No blocked route. **The three status labels are the mandatory element** — without them the diagram asserts a verified operating architecture |
| **Prohibited inference** | That the platform **is** the CDE, that configuration defines governance, or that the workflow is verified live |
| **External imagery** | **None required, none used** |
| **Rendered-asset status** | **`NONE`** |
| **Intended native PowerPoint treatment** | Three rectangles, two straight connectors, no SmartArt |

### `W2` — The five-property comparison

| Field | Value |
|---|---|
| **Visual identifier** | **`W2`** |
| **Title** | The five-property comparison |
| **Slide** | 2 — *State, version, revision, status and suitability are different* |
| **Slide-source identifier** | `M04-S02` |
| **Slide-source path** | [`source/M04-S02-five-properties.md`](source/M04-S02-five-properties.md) |
| **Teaching purpose** | Show **five properties answering five different governance questions**, all describing one container **at the same time**. |
| **Principal source basis** | `S1` §6.8, §11.3; `S2` §13; `S12` |
| **Classification** | `CONTROLLED` + `INTERP` — the definitions are controlled; the five questions are the presenter's framing (`M4-S2-07`) |
| **Governance status** | **`CONTROLLED GOVERNANCE`** — all five definitions. **`UNRESOLVED`** — the revision, status and suitability code sets |
| **Implementation status** | **Not applicable.** This visual makes no implementation claim, and must not appear to |
| **Fixed form** | Five equal cards, one row — **native layout, not Mermaid** |
| **Source status** | **`SOURCE COMPLETE`** |
| **Overclaim risk** | **MEDIUM-HIGH** — five cards in a row read as five stages, and a single invented code teaches a standard this project does not have |
| **Mandatory warning** | **The three `established` negatives are the warning.** They stay on the cards and are not collected into a footnote, where they would read as a caveat rather than as the project's position |
| **Blocked, empty or unresolved element** | **YES — the three absent code sets**, named on their own cards |
| **Prohibited inference** | That the five properties are **stages**, that one creates another, or that a code set exists for any of them |
| **External imagery** | **None required, none used** |
| **Rendered-asset status** | **`NONE`** |
| **Intended native PowerPoint treatment** | Five rectangles, nothing between them, no SmartArt |

### `W3` — The four-state model

| Field | Value |
|---|---|
| **Visual identifier** | **`W3`** |
| **Title** | The four-state model |
| **Slide** | 3 — *The Harrismith information-state model* |
| **Slide-source identifier** | `M04-S03` |
| **Slide-source path** | [`source/M04-S03-four-state-model.md`](source/M04-S03-four-state-model.md) |
| **Teaching purpose** | Show **four governed state concepts, four distinct purposes — and one route that cannot presently proceed**. |
| **Principal source basis** | `S1` §6.3, §6.7, §7.5, §9.4; `S2` §1, §3, §13; `S3` §2, §3, §3.1; `S4` §7, §9; **`CGD-C01`, `CGD-C03`, `CGD-C06`** |
| **Classification** | `CONTROLLED` + `SUPPORTING` + `DECISION-RECORD` |
| **Governance status** | **Per panel** — two `CONTROLLED GOVERNANCE`, one **`BLOCKED`**, one **`UNRESOLVED`** |
| **Implementation status** | **Per panel** — two `IMPLEMENTATION UNVERIFIED`, one **Not reached**, one **Not addressed** |
| **Fixed form** | Four concept panels, three connectors — **native layout, not Mermaid** |
| **Source status** | **`SOURCE COMPLETE`** |
| **Overclaim risk** | **HIGHEST IN THE MODULE** — a four-state chain reads as an operating system |
| **Mandatory warning** | **`Conceptual state model — not proof of live platform implementation`** — on the visual, centred beneath the connector labels, at body size. **Not in the footer, not in the notes, not shrunk to a caption** |
| **Blocked, empty or unresolved element** | **YES — three of them.** The `T4` break, the empty publication authority, and an unreachable third connector |
| **Prohibited inference** | That the four states **operate**, that folders and states align one to one, or that Record / Retained is a folder |
| **External imagery** | **None required, none used** |
| **Rendered-asset status** | **`NONE`** |
| **Intended native PowerPoint treatment** | Four rectangles, three connectors of **three different kinds**, four text blocks |

### `W4` — The WIP task-team boundary

| Field | Value |
|---|---|
| **Visual identifier** | **`W4`** |
| **Title** | The WIP task-team boundary |
| **Slide** | 4 — *Work in Progress: authoring inside the task team* |
| **Slide-source identifier** | `M04-S04` |
| **Slide-source path** | [`source/M04-S04-wip-task-team-boundary.md`](source/M04-S04-wip-task-team-boundary.md) |
| **Teaching purpose** | Show WIP as bounded by the task team, and that **visibility is not permission to rely**. |
| **Principal source basis** | `S1` §6.4, §7.5; `S2` §1; `S3` §3.2; `S4` §7 |
| **Classification** | `CONTROLLED` + `DECISION-RECORD` |
| **Governance status** | **`CONTROLLED GOVERNANCE`** |
| **Implementation status** | **`IMPLEMENTATION UNVERIFIED`** — one qualified container observation |
| **Fixed form** | One responsibility boundary — **native layout, not Mermaid** |
| **Source status** | **`SOURCE COMPLETE`** |
| **Overclaim risk** | **MEDIUM-HIGH** — a boundary with a gate on it invites the eye to follow the route out |
| **Mandatory warning** | **`Visibility is not permission. Permission to read is not authorisation to rely.`** — `S1` §7.5, on the slide |
| **Blocked, empty or unresolved element** | **No route out is drawn.** The Task-Team Lead gate is visible on the boundary and **no connector leaves it** |
| **Prohibited inference** | That **visibility permits reliance**, that the boundary is a permission setting, or that WIP progresses automatically |
| **External imagery** | **None required, none used** |
| **Rendered-asset status** | **`NONE`** |
| **Intended native PowerPoint treatment** | One boundary rectangle, one outside marker, no connector leaving it |

### `W5` — Shared — permitted use for a defined purpose

| Field | Value |
|---|---|
| **Visual identifier** | **`W5`** |
| **Title** | Shared — permitted use for a defined purpose |
| **Slide** | 5 — *Shared: controlled use for a defined purpose* |
| **Slide-source identifier** | `M04-S05` |
| **Slide-source path** | [`source/M04-S05-shared-defined-purpose.md`](source/M04-S05-shared-defined-purpose.md) |
| **Teaching purpose** | Show that Shared carries a **stated purpose**, that reliance is bounded by it, and that **responsibility stays with the originator**. |
| **Principal source basis** | `S1` §6.3, §6.5, §6.6, §7.7; `S2` §1, §3; `S3` §3.3; `S4` §7 |
| **Classification** | `CONTROLLED` + `SUPPORTING` + `DECISION-RECORD` |
| **Governance status** | **`CONTROLLED GOVERNANCE`** — `T1`'s authorising function is established |
| **Implementation status** | **`IMPLEMENTATION UNVERIFIED`** — *"only Architecture currently demonstrable as a Shared input"* |
| **Fixed form** | One container, purpose call-outs — **native layout, not Mermaid** |
| **Source status** | **`SOURCE COMPLETE`** |
| **Overclaim risk** | **HIGH** — Shared is the state most often read as *signed off* |
| **Mandatory warning** | **`Shared means authorised for A DEFINED USE. It does not mean approved for EVERY use.`** — on the slide |
| **Blocked, empty or unresolved element** | None on this visual. **`W5` is the module's only visual with no mandatory incomplete element** — its control is the warning and the retained-responsibility line |
| **Prohibited inference** | That Shared means **approved**, that responsibility transferred, or that placement in `02. Shared` evidences checking |
| **External imagery** | **None required, none used** |
| **Rendered-asset status** | **`NONE`** |
| **Intended native PowerPoint treatment** | One rectangle, a persistent originator line, three terminating call-outs |

### `W6` — The publication-authority gate

| Field | Value |
|---|---|
| **Visual identifier** | **`W6`** |
| **Title** | The publication-authority gate |
| **Slide** | 6 — *Published / Authorised: a separate decision and authority* |
| **Slide-source identifier** | `M04-S06` |
| **Slide-source path** | [`source/M04-S06-publication-authority-gate.md`](source/M04-S06-publication-authority-gate.md) |
| **Teaching purpose** | Show publication as a **separate decision by a separate authority** — and that the authority is **required and unassigned**. |
| **Principal source basis** | `S1` §6.7, §9.7; `S2` §1, §3.1, §3.2, §11; `S3` §3.4; `S4` §9; `S6` `D4` |
| **Classification** | `CONTROLLED` + `SUPPORTING` + `DECISION-RECORD` |
| **Governance status** | **`BLOCKED`** — the authority is **`UNRESOLVED`** |
| **Implementation status** | **Not reached** |
| **Fixed form** | Vertical gate — **native layout, not Mermaid** |
| **Source status** | **`SOURCE COMPLETE`** |
| **Overclaim risk** | **HIGH in both directions** — an empty gate invites the audience to fill it; a red gate reads as a defect |
| **Mandatory warning** | **`T4 BLOCKED` · `No available authorising function` · `INFORMATION REMAINS SHARED`** — all three on the slide |
| **Blocked, empty or unresolved element** | **YES — the authority position is drawn empty, and the output is broken** |
| **Prohibited inference** | That **anyone holds** publication authority, that the block is a fault, or that an administrator may substitute |
| **External imagery** | **None required, none used** |
| **Rendered-asset status** | **`NONE`** |
| **Intended native PowerPoint treatment** | One gate rectangle with an **unfilled inner rectangle**, one solid and one broken connector |

### `W7` — Retention obligation versus method

| Field | Value |
|---|---|
| **Visual identifier** | **`W7`** |
| **Title** | Retention obligation versus method |
| **Slide** | 7 — *Record / Retained: preservation without an Archive folder* |
| **Slide-source identifier** | `M04-S07` |
| **Slide-source path** | [`source/M04-S07-retention-obligation-versus-method.md`](source/M04-S07-retention-obligation-versus-method.md) |
| **Teaching purpose** | Show retention as an **established obligation** with an **undecided method**. |
| **Principal source basis** | `S1` §6.3, §7.10, §9.9, §12.10; `S2` §1, §19; **`S3` §3.1, §3.5, `CGD-C06`** |
| **Classification** | `CONTROLLED` + `SUPPORTING` + `DECISION-RECORD` |
| **Governance status** | **`CONTROLLED GOVERNANCE`** — the obligation. **`UNRESOLVED`** — the method |
| **Implementation status** | **Not addressed in any validation record** |
| **Fixed form** | Two panels — **native layout, not Mermaid** |
| **Source status** | **`SOURCE COMPLETE`** |
| **Overclaim risk** | **MEDIUM-HIGH** — the audience expects a folder and will read one in |
| **Mandatory warning** | **`Record / Retained is a state or obligation. It is NOT automatically a folder.`** — on the slide |
| **Blocked, empty or unresolved element** | **YES — the method panel is visibly empty**, with four unfilled fields |
| **Prohibited inference** | That an **`04 Archive` exists or is proposed**, or that a retention period, location or holder has been decided |
| **External imagery** | **None required, none used** |
| **Rendered-asset status** | **`NONE`** |
| **Intended native PowerPoint treatment** | Two identical rectangles, **no icons**, an empty gutter |

### `W8` — File movement versus authorised transition

| Field | Value |
|---|---|
| **Visual identifier** | **`W8`** |
| **Title** | File movement versus authorised transition |
| **Slide** | 8 — *A transition is more than moving a file* |
| **Slide-source identifier** | `M04-S08` |
| **Slide-source path** | [`source/M04-S08-file-movement-versus-transition.md`](source/M04-S08-file-movement-versus-transition.md) |
| **Teaching purpose** | Show the two side by side, and that **one does not produce the other**. |
| **Principal source basis** | **`CGD-C03`**; `S2` §2, §3, §14, §17; `S1` §6.9, §12.1; `S4` §9 |
| **Classification** | `DECISION-RECORD` + `SUPPORTING` + `CONTROLLED` + `INTERP` |
| **Governance status** | **`CONTROLLED GOVERNANCE`** — `CGD-C03` is an active condition |
| **Implementation status** | **Not applicable.** This visual compares two kinds of act; it asserts nothing about the live platform |
| **Fixed form** | Two panels, no connector — **native layout, not Mermaid** |
| **Source status** | **`SOURCE COMPLETE`** |
| **Overclaim risk** | **HIGH** — a two-panel layout invites the eye to pair them, and pairing them asserts that the left produces the right |
| **Mandatory warning** | **`NO CONNECTOR. The left does not produce the right.`** — on the slide, between the panels |
| **Blocked, empty or unresolved element** | **The absent connector is the mandatory element.** Nothing on this visual may join the two panels |
| **Prohibited inference** | That a **technical action produces** a governed transition, or that software capability establishes authority |
| **External imagery** | **None required, none used** |
| **Rendered-asset status** | **`NONE`** |
| **Intended native PowerPoint treatment** | Two identical rectangles, **an empty gutter**, arrows inside the right panel only |

### `W9` — The eight controlled steps, classified

| Field | Value |
|---|---|
| **Visual identifier** | **`W9`** |
| **Title** | The eight controlled steps, classified |
| **Slide** | 9 — *The eight controlled steps, and the two that change state* |
| **Slide-source identifier** | `M04-S09` |
| **Slide-source path** | [`source/M04-S09-eight-controlled-steps.md`](source/M04-S09-eight-controlled-steps.md) |
| **Teaching purpose** | Show all eight steps **grouped by kind** — and that **only `T1` and `T4` change information state**. |
| **Principal source basis** | **`S2` §3.1, §3.2**; `S2` §2, §3; `S1` §9.4, §9.7, §9.8; `S4` §8 |
| **Classification** | `SUPPORTING` throughout, with `CONTROLLED` for `T1`'s authority |
| **Governance status** | **Mixed** — `T1` controlled · `T4` **`BLOCKED`** · `T7` **`UNRESOLVED`** · the rest proposed |
| **Implementation status** | **`IMPLEMENTATION UNVERIFIED`** — *"no complete traceable cycle"* |
| **Fixed form** | Grouped table — **native layout, not Mermaid** |
| **Source status** | **`SOURCE COMPLETE`** |
| **Overclaim risk** | **HIGHEST, jointly with `W3`** — eight identifiers in a row read as an eight-step state machine |
| **Mandatory warning** | **`Only T1 and T4 change information state.`** — as a prominent headline, on the slide |
| **Blocked, empty or unresolved element** | **YES** — `T4` blocked and `T7` unresolved, both in the same table |
| **Prohibited inference** | That the eight steps run **in order**, that all eight are transitions, or that a complete cycle has been demonstrated |
| **External imagery** | **None required, none used** |
| **Rendered-asset status** | **`NONE`** |
| **Intended native PowerPoint treatment** | One **native table**, banding off, no SmartArt conversion |

### `W10` — The `T1` gate model

| Field | Value |
|---|---|
| **Visual identifier** | **`W10`** |
| **Title** | The `T1` gate model |
| **Slide** | 10 — *Gates, authority and evidence* |
| **Slide-source identifier** | `M04-S10` |
| **Slide-source path** | [`source/M04-S10-t1-gate-model.md`](source/M04-S10-t1-gate-model.md) |
| **Teaching purpose** | Unpack **one** controlled transition — trigger, checks, authority, evidence, permitted use. |
| **Principal source basis** | **`S2` §3.1–§3.3, §9**; `S1` §7.7, §9.4, §9.11; `S4` §7, §8 |
| **Classification** | `SUPPORTING` + `CONTROLLED` + `DECISION-RECORD` |
| **Governance status** | **`CONTROLLED GOVERNANCE`** — the only transition with an established authority |
| **Implementation status** | **`IMPLEMENTATION UNVERIFIED`** — no complete cycle demonstrated |
| **Fixed form** | One horizontal chain — **native layout, not Mermaid** |
| **Source status** | **`SOURCE COMPLETE`** |
| **Overclaim risk** | **MEDIUM-HIGH** — a fully populated example reads as a running procedure |
| **Mandatory warning** | **`Governance definition ≠ live implementation evidence`** — on the slide |
| **Blocked, empty or unresolved element** | **The evidence field is the mandatory element.** It is what distinguishes a governed transition from a file move, and it may not be abbreviated away |
| **Prohibited inference** | That `T1` is **running live**, that CDE Administration decides, or that a folder location satisfies the evidence requirement |
| **External imagery** | **None required, none used** |
| **Rendered-asset status** | **`NONE`** |
| **Intended native PowerPoint treatment** | One connector, four equal column text boxes, CDE Administration outside the chain |

### `W11` — `T4` and `TRN-E03`, two blocked objects

| Field | Value |
|---|---|
| **Visual identifier** | **`W11`** |
| **Title** | `T4` and `TRN-E03`, two blocked objects |
| **Slide** | 11 — *Why `Shared → Published` remains blocked* |
| **Slide-source identifier** | `M04-S11` |
| **Slide-source path** | [`source/M04-S11-t4-and-trn-e03.md`](source/M04-S11-t4-and-trn-e03.md) |
| **Teaching purpose** | Show **two separate blocked objects** — a state transition and a delivery event — and that resolving one would not resolve the other. |
| **Principal source basis** | **`S2` §3.1–§3.3, §11, §19**; **`S5` §5, §5.1**; `S1` §9.4, §9.7, §9.8; `S4` §9 |
| **Classification** | `SUPPORTING` + `CONTROLLED` + `DECISION-RECORD` |
| **Governance status** | **`BLOCKED`** — both. Two authorities **`UNRESOLVED`** |
| **Implementation status** | **Not reached.** *"No governed publication / exchange authority evidence was established"* |
| **Fixed form** | Two panels — **native layout, not Mermaid** |
| **Source status** | **`SOURCE COMPLETE`** |
| **Overclaim risk** | **HIGH in both directions** — merged, it hides four dependencies; styled red, it reads as a defect |
| **Mandatory warning** | **`Satisfying T4 alone would not automatically complete delivery.`** — on the slide, beneath both panels |
| **Blocked, empty or unresolved element** | **YES — the visual is two blocks**, plus an empty authority position on Panel 1 |
| **Prohibited inference** | That `T4` and `TRN-E03` are **the same object**, or that resolving `T4` would complete delivery |
| **External imagery** | **None required, none used** |
| **Rendered-asset status** | **`NONE`** |
| **Intended native PowerPoint treatment** | Two identical rectangles, an unfilled inner rectangle, **no connector across the gutter** |

### `W12` — The property stack and the four unestablished standards

| Field | Value |
|---|---|
| **Visual identifier** | **`W12`** |
| **Title** | The property stack and the four unestablished standards |
| **Slide** | 12 — *Naming, revision, suitability and metadata support control* |
| **Slide-source identifier** | `M04-S12` |
| **Slide-source path** | [`source/M04-S12-property-stack.md`](source/M04-S12-property-stack.md) |
| **Teaching purpose** | Show the six properties as **six different control questions**, and that **four of the standards behind them do not exist**. |
| **Principal source basis** | **`S1` §6.8, §11.3, §11.4**; `S2` §13; `S12`; **`CGD-C01`, `CGD-C03`** |
| **Classification** | `CONTROLLED` + `INTERP` |
| **Governance status** | **`CONTROLLED GOVERNANCE`** — what each property must support. **`UNRESOLVED`** — every code set and the schema |
| **Implementation status** | **No standard established.** All four `standards/` directories hold only `.gitkeep` |
| **Fixed form** | Two zones — six rows, four empty boxes — **native layout, not Mermaid** |
| **Source status** | **`SOURCE COMPLETE`** |
| **Overclaim risk** | **HIGH** — a populated property stack teaches four standards that do not exist |
| **Mandatory warning** | **`A code identifies. It does not authorise, and it does not prove the process behind it occurred.`** — on the slide |
| **Blocked, empty or unresolved element** | **YES — four empty boxes, shown and unfilled** |
| **Prohibited inference** | That any **naming, revision, suitability or metadata standard exists**, is in progress, or is due on a date |
| **External imagery** | **None required, none used** |
| **Rendered-asset status** | **`NONE`** |
| **Intended native PowerPoint treatment** | One two-column table, four **unfilled** rectangles, no icons |

### `W13` — Governance, then configuration

| Field | Value |
|---|---|
| **Visual identifier** | **`W13`** |
| **Title** | Governance, then configuration |
| **Slide** | 13 — *Governance first; permissions and configuration follow* |
| **Slide-source identifier** | `M04-S13` |
| **Slide-source path** | [`source/M04-S13-governance-then-configuration.md`](source/M04-S13-governance-then-configuration.md) |
| **Teaching purpose** | Show the **direction of authority** — decision, process, configuration, evidence — and that the reverse does not hold. |
| **Principal source basis** | **`S1` §5.9, §6.9, §12.1, §12.6, §12.8, §12.9**; `S2` §6, §14, §17; **`CGD-C07`, `CGD-C08`** |
| **Classification** | `CONTROLLED` + `SUPPORTING` + `DECISION-RECORD` |
| **Governance status** | **`CONTROLLED GOVERNANCE`** |
| **Implementation status** | **`IMPLEMENTATION UNVERIFIED`** — `S2` §6 records alignment as a four-layer question |
| **Fixed form** | Chain, refused reverse, two boxes — **native layout, not Mermaid** |
| **Source status** | **`SOURCE COMPLETE`** |
| **Overclaim risk** | **MEDIUM-HIGH** — a forward-only chain can be read in either direction, and a permissions image makes configuration the concrete thing |
| **Mandatory warning** | **`A configuration that was never approved is a deviation, however competently it was applied.`** — `S1` §5.9, verbatim, on the slide |
| **Blocked, empty or unresolved element** | **YES — the refused reverse arrow, and `Holder: TBD`** |
| **Prohibited inference** | That **configuration creates authority**, that permissions assign it, or that a platform setting proves implementation |
| **External imagery** | **None required, none used** |
| **Rendered-asset status** | **`NONE`** |
| **Intended native PowerPoint treatment** | Four rectangles, three arrows, one **broken and struck** reverse arrow, two equal boxes |

### `W14` — Triviron CDE-definition questions

| Field | Value |
|---|---|
| **Visual identifier** | **`W14`** |
| **Title** | Triviron CDE-definition questions |
| **Slide** | 14 — *What Triviron must define before configuring its CDE* |
| **Slide-source identifier** | `M04-S14` |
| **Slide-source path** | [`source/M04-S14-triviron-questions.md`](source/M04-S14-triviron-questions.md) |
| **Teaching purpose** | Convert the module into **questions Triviron must answer before configuring anything**. |
| **Principal source basis** | **No Triviron source exists.** The question *structure* draws on `S1` §6.1, §6.3, §9.7, §9.8, §11.3, §11.4, §5.9, §12.6, §12.8; `S2` §2, §3.3, §19; `S4` §7, §11; `S5` §5.1; `CGD-C01`–`CGD-C08` |
| **Classification** | `INTERP` + `SYNTH` |
| **Governance status** | **None asserted for Triviron** — the project has no entry in any register |
| **Implementation status** | **None asserted for Triviron** |
| **Fixed form** | Five question groups — **native layout, not Mermaid** |
| **Source status** | **`SOURCE COMPLETE`** |
| **Overclaim risk** | **HIGH — about Triviron, not about Harrismith** |
| **Mandatory warning** | **`CDE configuration basis — not yet established`** — the end state, in **neutral styling**, with no warning colour, icon, date or owner |
| **Blocked, empty or unresolved element** | **YES — the two authority questions stay unanswered, and the end state stays open** |
| **Prohibited inference** | Any **Triviron fact**, any answer to either authority question, or any platform recommendation |
| **External imagery** | **None required, none used** |
| **Rendered-asset status** | **`NONE`** |
| **Intended native PowerPoint treatment** | Five text blocks, one bordered authority block, no icons, no progress indicator |

---

## 4. What this register does not do

- It creates **no asset**. No rendered image, no vector, no PDF, no PowerPoint.
- It carries **no governance authority**, and it resolves **no unresolved
  matter**.
- It authorises **no live Autodesk observation, read or configuration act.**
  Root [`README.md`](../../../README.md) §2.1 applies unmodified.
- It does **not** supersede the visual-demonstration plan. **Where this register
  and the plan differ, the plan is authoritative.**
