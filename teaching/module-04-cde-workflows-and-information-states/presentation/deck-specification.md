# Module 4 — Deck Specification

**Status:** Controlled specification for the fourteen-slide deck. **Not
governance.** **Not the PowerPoint.**

---

## 1. Global details

| Field | Value |
|---|---|
| **Module** | Module 4 — CDE Workflows and Information States |
| **Presentation title** | **What a Common Data Environment actually controls** |
| **Subtitle** | *States, transitions, and why moving a file is not authority to change it* |
| **Audience** | Multidisciplinary project team — architects, engineers, coordinators, managers. **No prior ISO 19650 knowledge assumed** |
| **Slide count** | **14** |
| **Allocated duration** | **20.0 minutes** |
| **Timing status** | **`20.0 minutes allocated — not yet measured`** |
| **Worked example** | Harrismith Fire Station — **approved with conditions, not issued, not running live** |
| **Transfer context** | A future **Triviron** multidisciplinary project |
| **Objective** | The audience understands what a CDE controls, and why **being able to move a file is not the same as being authorised to change its state** |

### Central teaching statement

> **A CDE is a governed process supported by technology. The states define
> permitted use; the transitions require checks, authority and evidence; and the
> platform implements decisions it does not make.**

### Opening proposition — Slide 1

> The CDE is the governed process; the platform and folders are tools used to
> implement it.

### Closing proposition — Slide 14

> Configure the platform only after the states, purposes, authorities, gates and
> evidence requirements have been decided.

### Source hierarchy

```text
Controlled Harrismith sources → Module 4 teaching source
  → visual-demonstration plan → M04-S01–M04-S14 → this specification
    → external PowerPoint (derivative)
```

**Visual-source hierarchy.** [`visual-demonstration-plan.md`](../visual-demonstration-plan.md)
is authoritative for `W1`–`W14`. The fourteen files in
[`../../assets/module-04/source/`](../../assets/module-04/source/) implement it.
**This specification carries them forward and overrides neither.**

## 2. Narrative arc

| Section | Title | Slides | Time |
|---|---|---:|---:|
| **A** | What a CDE controls | 1–2 | **3.0** |
| **B** | The information states | 3–7 | **6.5** |
| **C** | The transition workflow | 8–11 | **6.0** |
| **D** | Properties and evidence | 12 | **1.5** |
| **E** | Applying the model | 13–14 | **3.0** |
| | **Total** | **1–14** | **20.0** |

**`Allocated — not measured`**

### Slide timing

| Slide | Time | | Slide | Time |
|---|---:|---|---|---:|
| 1 | 1.5 | | 8 | 1.5 |
| 2 | 1.5 | | 9 | 1.5 |
| 3 | 1.5 | | 10 | 1.5 |
| 4 | 1.0 | | 11 | 1.5 |
| 5 | 1.5 | | 12 | 1.5 |
| 6 | 1.5 | | 13 | 1.0 |
| 7 | 1.0 | | 14 | 2.0 |
| | | | **Total** | **20.0** |

**`Allocated — not measured.`** No complete delivery has been run. Every figure
here is an allocation until Exercise 64 in [`../exercises.md`](../exercises.md)
has been performed.

## 3. Design approach

### 3.1 Format and construction

| Rule | Value |
|---|---|
| **Aspect** | **16:9** — reference canvas **960 × 540 pt** |
| **Register** | Restrained, professional BIM-management. Not a marketing deck |
| **Construction** | **Native PowerPoint shapes, text boxes, tables, lines, borders and connectors only** |
| **Imported diagram assets** | **None.** No SVG, PNG, JPG, PDF or Mermaid rendering |
| **Origin** | Top left; `x` right, `y` down |
| **Side margins** | **48 pt**, or **40 pt** where a visual carries four panels |
| **Title zone** | `y` 0–72, reserved |

### 3.2 Prohibited throughout the deck

- **No platform screenshot**, and **no Autodesk logo or product name**.
- **No folder or archive icon** where it would assert governance — PowerPoint's
  icon library contains both, and either would supply a location this project
  has not decided.
- **No green approval grammar** — no ticks, no *cleared* colour, no completion
  markers.
- **No red failure grammar for a deliberate block.** `T4` is stopped by
  governance, not broken.
- **No scorecard, maturity model, progress bar or percentage.**
- **No external icon implying approval or software implementation.**

### 3.3 Labels

| Rule | Value |
|---|---|
| **Minimum type** | **14 pt** for status, source and connector labels — no exceptions for space |
| **Text contrast** | **≥ 4.5:1** |
| **Border and connector contrast** | **≥ 3:1** |
| **Colour** | **No meaning may depend on colour.** Every status is a word, spelled out |
| **Status labels** | **On the slide**, never moved to the notes |
| **Source labels** | Retained where the slide source requires them, and they **travel with the status** so neither can be deleted alone |

**If a shape will not hold its content at 14 pt, shorten the content — never the
label.**

### 3.4 Connector semantics — consistent across the deck

| Form | Meaning | Used on |
|---|---|---|
| **Solid, filled arrowhead** | **Supported progression** | 1, 3 (`T1`), 6 (input), 10, 13 (forward chain) |
| **Broken, with a visible break, arrowhead retained** | **Blocked** — the route exists in governance and cannot presently be traversed | 3 (`T4`), 6 (output), 11 |
| **Broken, open stub, no arrowhead at all** | **Unreachable** — it cannot be entered | 3 (retention) |
| **Drawn and struck, with a gap and a cross** | **Refused** — this direction does not hold | 13 (reverse) |
| **No connector at all** | **No relationship** — and the absence is stated in text | 2, 7, 8, 9, 12, 14 |

**These four forms are not interchangeable.** Drawing *blocked* and *unreachable*
identically implies both wait on the same thing.

### 3.5 Geometry and whitespace

- **Equal objects are numerically equal.** Panels, cards and bands specified as
  peers are set by coordinate, not by eye — a producer's instinct is to grow what
  is populated and shrink what is deliberately empty, **which inverts the
  teaching**.
- **Whitespace stays where the source requires it.** Slides 12 and 14 will look
  sparse. That is the deliverable, not a gap to fill.

## 4. Slide specifications

### Section A — What a CDE controls · Slides 1–2 · 3.0 min

#### Slide 1 — A CDE is a governed process, not a folder tree · 1.5 min

| Field | Value |
|---|---|
| **Number** | 1 |
| **Exact title** | A CDE is a governed process, not a folder tree |
| **Allocated time** | **1.5 min** — allocated, not measured |
| **Narrative role** | **Opening proposition.** Separates the governed process from the software that implements part of it |
| **Teaching purpose** | Show **three ordered layers**, governance above configuration, **each carrying its own status**. |
| **Principal message** | The CDE is the governed process; the platform and folders are tools used to implement it. |
| **Layout** | Three stacked bands |
| **Visual identifier** | **`W1`** |
| **Visual-source identifier** | `M04-S01` |
| **Visual-source path** | [`M04-S01-governance-workflow-platform.md`](../../assets/module-04/source/M04-S01-governance-workflow-platform.md) |
| **Governance status** | Band 1 **`CONTROLLED GOVERNANCE`** · Band 2 **`PROPOSED GOVERNANCE`** · Band 3 topology adopted (`S3` §2) |
| **Implementation status** | Band 3 **`IMPLEMENTATION UNVERIFIED`** (`CGD-C07`). Bands 1 and 2 make no implementation claim |
| **Principal source basis** | `S1` §6.1, §6.9, §12.1; `S2` §1, §14, §17; `S3` §2, §3; `S4` §9; **`CGD-C01`, `CGD-C07`** |
| **Classification** | `CONTROLLED` + `INTERP` — the layering is the presenter's framing; every band item is sourced |
| **Visible labels** | `GOVERNANCE AND AUTHORITY` · `CDE WORKFLOW AND INFORMATION STATES` · `PLATFORM, FOLDERS, PERMISSIONS AND METADATA` · `decides and authorises` · `implemented through` |
| **Mandatory warning** | **`PROPOSED GOVERNANCE` on Band 2 does the warning's work.** It is not optional, not abbreviated and not moved to the notes |
| **Fixed geometry or relationship** | Governance decides · the workflow defines · the platform implements — see [`M04-S01-governance-workflow-platform.md`](../../assets/module-04/source/M04-S01-governance-workflow-platform.md) §6 for the fixed geometry |
| **Connector semantics** | See [`M04-S01-governance-workflow-platform.md`](../../assets/module-04/source/M04-S01-governance-workflow-platform.md) §7 — the connector table is fixed |
| **Accessibility requirement** | Statuses are words, not tints; reading order strictly top to bottom |
| **Overclaim risk** | **HIGH** — three tidy bands read as *this is how it runs* |
| **Likely producer failure** | Reading the three bands as organisational ranks, or the bottom band as *the CDE* |
| **Transition to next slide** | "So the CDE governs how information moves. Before we look at the moving, we need the vocabulary — because there are five different properties people use interchangeably." |

**STOP conditions — Slide 1.** Stop and return to
[`M04-S01-governance-workflow-platform.md`](../../assets/module-04/source/M04-S01-governance-workflow-platform.md) §14 if:

- any arrow points upward, or any connector becomes bidirectional;
- any platform logo, screenshot or product name is introduced;
- any band loses its status label, or a status is moved to the notes;
- the workflow band is labelled operational, live, implemented or verified;
- the bands acquire unequal size, numbering, or an org-chart appearance;
- the three bands are rearranged side by side.

#### Slide 2 — State, version, revision, status and suitability are different · 1.5 min

| Field | Value |
|---|---|
| **Number** | 2 |
| **Exact title** | State, version, revision, status and suitability are different |
| **Allocated time** | **1.5 min** — allocated, not measured |
| **Narrative role** | **Vocabulary.** Establishes the five properties that Sections B and C depend on |
| **Teaching purpose** | Show **five properties answering five different governance questions**, all describing one container **at the same time**. |
| **Principal message** | Five properties may describe the same container, but each answers a different governance question. |
| **Layout** | Five equal cards, one row |
| **Visual identifier** | **`W2`** |
| **Visual-source identifier** | `M04-S02` |
| **Visual-source path** | [`M04-S02-five-properties.md`](../../assets/module-04/source/M04-S02-five-properties.md) |
| **Governance status** | **`CONTROLLED GOVERNANCE`** — all five definitions. **`UNRESOLVED`** — the revision, status and suitability code sets |
| **Implementation status** | **Not applicable.** This visual makes no implementation claim, and must not appear to |
| **Principal source basis** | `S1` §6.8, §11.3; `S2` §13; `S12` |
| **Classification** | `CONTROLLED` + `INTERP` — the definitions are controlled; the five questions are the presenter's framing (`M4-S2-07`) |
| **Visible labels** | `State` · `Version` · `Revision` · `Status` · `Suitability`, each with its question · `A new platform version creates none of the others` |
| **Mandatory warning** | **The three `established` negatives are the warning.** They stay on the cards and are not collected into a footnote, where they would read as a caveat rather than as the project's position |
| **Fixed geometry or relationship** | One container. Five properties. Five different questions. — see [`M04-S02-five-properties.md`](../../assets/module-04/source/M04-S02-five-properties.md) §6 for the fixed geometry |
| **Connector semantics** | **Not applicable — no connector, by requirement.** |
| **Accessibility requirement** | Five cards are peers, not a list with a first item; no meaning in fill |
| **Overclaim risk** | **MEDIUM-HIGH** — five cards in a row read as five stages, and a single invented code teaches a standard this project does not have |
| **Likely producer failure** | Reading five cards in a row as five stages, and adding an example code to make them concrete |
| **Transition to next slide** | "So a container carries five properties at once. The first of them — state — is the one this module is really about, so let's look at ours." |

**STOP conditions — Slide 2.** Stop and return to
[`M04-S02-five-properties.md`](../../assets/module-04/source/M04-S02-five-properties.md) §14 if:

- an arrow, rule, bracket or connecting line appears anywhere in the card row;
- a card becomes visually dominant, or the cards become unequal;
- an example code, filename or field name is added to any card;
- a maturity, progress or completion grammar appears;
- **metadata is added as a sixth card**;
- State or Version acquires a *not established* label;
- **the row is rebuilt as a three-plus-two grid** — the single-row form is a recorded decision, not a default.

### Section B — The information states · Slides 3–7 · 6.5 min

#### Slide 3 — The Harrismith information-state model · 1.5 min

| Field | Value |
|---|---|
| **Number** | 3 |
| **Exact title** | The Harrismith information-state model |
| **Allocated time** | **1.5 min** — allocated, not measured |
| **Narrative role** | **The model in one view.** Four states, four purposes — and one route that cannot proceed |
| **Teaching purpose** | Show **four governed state concepts, four distinct purposes — and one route that cannot presently proceed**. |
| **Principal message** | Each state defines a different permitted purpose; movement between them requires more than technical file movement. |
| **Layout** | Four concept panels, three connectors |
| **Visual identifier** | **`W3`** |
| **Visual-source identifier** | `M04-S03` |
| **Visual-source path** | [`M04-S03-four-state-model.md`](../../assets/module-04/source/M04-S03-four-state-model.md) |
| **Governance status** | **Per panel** — two `CONTROLLED GOVERNANCE`, one **`BLOCKED`**, one **`UNRESOLVED`** |
| **Implementation status** | **Per panel** — two `IMPLEMENTATION UNVERIFIED`, one **Not reached**, one **Not addressed** |
| **Principal source basis** | `S1` §6.3, §6.7, §7.5, §9.4; `S2` §1, §3, §13; `S3` §2, §3, §3.1; `S4` §7, §9; **`CGD-C01`, `CGD-C03`, `CGD-C06`** |
| **Classification** | `CONTROLLED` + `SUPPORTING` + `DECISION-RECORD` |
| **Visible labels** | `WIP` · `SHARED` · `PUBLISHED / AUTHORISED` · `RECORD / RETAINED` · `T1` · `T4 BLOCKED` · `Publication-authorising function: TBD` · `Information remains Shared` |
| **Mandatory warning** | **`Conceptual state model — not proof of live platform implementation`** — on the visual, centred beneath the connector labels, at body size. **Not in the footer, not in the notes, not shrunk to a caption** |
| **Fixed geometry or relationship** | Four states · four permitted purposes · one route that cannot proceed — see [`M04-S03-four-state-model.md`](../../assets/module-04/source/M04-S03-four-state-model.md) §6 for the fixed geometry |
| **Connector semantics** | See [`M04-S03-four-state-model.md`](../../assets/module-04/source/M04-S03-four-state-model.md) §7 — the connector table is fixed |
| **Accessibility requirement** | **Connector meaning in text as well as line style**; no red or green; legible in monochrome |
| **Overclaim risk** | **HIGHEST IN THE MODULE** — a four-state chain reads as an operating system |
| **Likely producer failure** | **Completing the blocked route**, or aligning four folders beneath the four states |
| **Transition to next slide** | "So — four states, four different permissions to rely. Let's take them one at a time, starting where everything starts." |

**STOP conditions — Slide 3.** Stop and return to
[`M04-S03-four-state-model.md`](../../assets/module-04/source/M04-S03-four-state-model.md) §14 if:

- `Shared → Published` becomes solid, or its break mark is removed;
- the third connector gains an arrowhead, or is styled as merely delayed;
- the publication-authority field disappears or is filled;
- **`04 Archive` is added anywhere**;
- four folders or four areas are aligned beneath the four states;
- a completion tick, green lifecycle or red failure styling appears;
- the mandatory warning is removed, moved to the footer or reduced to a caption;
- Record / Retained is presented as reached, or drawn as a folder;
- any status label is dropped, reworded or shrunk below 14 pt;
- a fifth panel appears for delivery, receipt or acceptance.

#### Slide 4 — Work in Progress: authoring inside the task team · 1.0 min

| Field | Value |
|---|---|
| **Number** | 4 |
| **Exact title** | Work in Progress: authoring inside the task team |
| **Allocated time** | **1.0 min** — allocated, not measured |
| **Narrative role** | **First state in detail.** The boundary of task-team control, and what visibility does not confer |
| **Teaching purpose** | Show WIP as bounded by the task team, and that **visibility is not permission to rely**. |
| **Principal message** | WIP is where a task team develops its information — not where the wider project is entitled to rely on it. |
| **Layout** | One responsibility boundary |
| **Visual identifier** | **`W4`** |
| **Visual-source identifier** | `M04-S04` |
| **Visual-source path** | [`M04-S04-wip-task-team-boundary.md`](../../assets/module-04/source/M04-S04-wip-task-team-boundary.md) |
| **Governance status** | **`CONTROLLED GOVERNANCE`** |
| **Implementation status** | **`IMPLEMENTATION UNVERIFIED`** — one qualified container observation |
| **Principal source basis** | `S1` §6.4, §7.5; `S2` §1; `S3` §3.2; `S4` §7 |
| **Classification** | `CONTROLLED` + `DECISION-RECORD` |
| **Visible labels** | `TASK-TEAM WIP` · `Author` · `Checker` · `Task-Team Lead gate` · `CAN SEE` · `MAY NOT RELY` · `originating responsibility — retained` |
| **Mandatory warning** | **`Visibility is not permission. Permission to read is not authorisation to rely.`** — `S1` §7.5, on the slide |
| **Fixed geometry or relationship** | Authoring inside the task team — see [`M04-S04-wip-task-team-boundary.md`](../../assets/module-04/source/M04-S04-wip-task-team-boundary.md) §6 for the fixed geometry |
| **Connector semantics** | See [`M04-S04-wip-task-team-boundary.md`](../../assets/module-04/source/M04-S04-wip-task-team-boundary.md) §7 — the connector table is fixed |
| **Accessibility requirement** | `MAY NOT RELY` is words, not a colour; the boundary's meaning is stated inside it |
| **Overclaim risk** | **MEDIUM-HIGH** — a boundary with a gate on it invites the eye to follow the route out |
| **Likely producer failure** | Drawing the route out of WIP, because a gate invites the eye to follow it |
| **Transition to next slide** | "So information sits in WIP until somebody deliberately does something about it. That deliberate act takes it to the next state." |

**STOP conditions — Slide 4.** Stop and return to
[`M04-S04-wip-task-team-boundary.md`](../../assets/module-04/source/M04-S04-wip-task-team-boundary.md) §14 if:

- **any connector leaves the boundary** toward Shared or anywhere else;
- the boundary is drawn as a **padlock, lock icon or permission shield**;
- a named person appears;
- a team-space screenshot is introduced;
- a green approval tick appears anywhere;
- the observer is drawn inside or on the boundary;
- `MAY NOT RELY` is dropped, softened or reduced to a colour;
- the `ARC-01` annotation is generalised beyond one qualified observation.

#### Slide 5 — Shared: controlled use for a defined purpose · 1.5 min

| Field | Value |
|---|---|
| **Number** | 5 |
| **Exact title** | Shared: controlled use for a defined purpose |
| **Allocated time** | **1.5 min** — allocated, not measured |
| **Narrative role** | **Second state.** Bounded permission for a stated purpose — not approval |
| **Teaching purpose** | Show that Shared carries a **stated purpose**, that reliance is bounded by it, and that **responsibility stays with the originator**. |
| **Principal message** | Shared information may be relied upon only for the purpose for which it was shared. |
| **Layout** | One container, purpose call-outs |
| **Visual identifier** | **`W5`** |
| **Visual-source identifier** | `M04-S05` |
| **Visual-source path** | [`M04-S05-shared-defined-purpose.md`](../../assets/module-04/source/M04-S05-shared-defined-purpose.md) |
| **Governance status** | **`CONTROLLED GOVERNANCE`** — `T1`'s authorising function is established |
| **Implementation status** | **`IMPLEMENTATION UNVERIFIED`** — *"only Architecture currently demonstrable as a Shared input"* |
| **Principal source basis** | `S1` §6.3, §6.5, §6.6, §7.7; `S2` §1, §3; `S3` §3.3; `S4` §7 |
| **Classification** | `CONTROLLED` + `SUPPORTING` + `DECISION-RECORD` |
| **Visible labels** | `SHARED CONTAINER` · `stated purpose:` · `RESPONSIBILITY RETAINED` · `coordination` · `controlled review` · `reference by another task team` |
| **Mandatory warning** | **`Shared means authorised for A DEFINED USE. It does not mean approved for EVERY use.`** — on the slide |
| **Fixed geometry or relationship** | Controlled use for a defined purpose — see [`M04-S05-shared-defined-purpose.md`](../../assets/module-04/source/M04-S05-shared-defined-purpose.md) §6 for the fixed geometry |
| **Connector semantics** | See [`M04-S05-shared-defined-purpose.md`](../../assets/module-04/source/M04-S05-shared-defined-purpose.md) §7 — the connector table is fixed |
| **Accessibility requirement** | `RESPONSIBILITY RETAINED` is text, not line weight; **no green anywhere** |
| **Overclaim risk** | **HIGH** — Shared is the state most often read as *signed off* |
| **Likely producer failure** | Adding a tick, a stamp or green to a state that is not an approval |
| **Transition to next slide** | "So Shared gets information usefully into other people's hands, for a stated purpose. Publishing is a different act altogether — and this is where it stops." |

**STOP conditions — Slide 5.** Stop and return to
[`M04-S05-shared-defined-purpose.md`](../../assets/module-04/source/M04-S05-shared-defined-purpose.md) §14 if:

- an approval stamp, publication symbol, acceptance symbol or tick appears;
- **green is used anywhere** on the visual;
- the responsibility line becomes a handover arrow;
- a purpose call-out terminates in open space rather than a label;
- an example purpose is invented and printed on the stated-purpose line;
- the warning is removed or moved to the notes;
- a platform screenshot or folder tree is introduced.

#### Slide 6 — Published / Authorised: a separate decision and authority · 1.5 min

| Field | Value |
|---|---|
| **Number** | 6 |
| **Exact title** | Published / Authorised: a separate decision and authority |
| **Allocated time** | **1.5 min** — allocated, not measured |
| **Narrative role** | **Third state.** The separate decision this project cannot currently make |
| **Teaching purpose** | Show publication as a **separate decision by a separate authority** — and that the authority is **required and unassigned**. |
| **Principal message** | Publication is not the next folder; it is a separate authorised decision that this project cannot currently make. |
| **Layout** | Vertical gate |
| **Visual identifier** | **`W6`** |
| **Visual-source identifier** | `M04-S06` |
| **Visual-source path** | [`M04-S06-publication-authority-gate.md`](../../assets/module-04/source/M04-S06-publication-authority-gate.md) |
| **Governance status** | **`BLOCKED`** — the authority is **`UNRESOLVED`** |
| **Implementation status** | **Not reached** |
| **Principal source basis** | `S1` §6.7, §9.7; `S2` §1, §3.1, §3.2, §11; `S3` §3.4; `S4` §9; `S6` `D4` |
| **Classification** | `CONTROLLED` + `SUPPORTING` + `DECISION-RECORD` |
| **Visible labels** | `PUBLICATION GATE` · `Publication-authorising function:` · `TBD / UNRESOLVED` · `T4 BLOCKED` · `No available authorising function` · `INFORMATION REMAINS SHARED` · `(not reached)` |
| **Mandatory warning** | **`T4 BLOCKED` · `No available authorising function` · `INFORMATION REMAINS SHARED`** — all three on the slide |
| **Fixed geometry or relationship** | A separate decision, by a separate authority — see [`M04-S06-publication-authority-gate.md`](../../assets/module-04/source/M04-S06-publication-authority-gate.md) §6 for the fixed geometry |
| **Connector semantics** | See [`M04-S06-publication-authority-gate.md`](../../assets/module-04/source/M04-S06-publication-authority-gate.md) §7 — the connector table is fixed |
| **Accessibility requirement** | The block is words, not a dashed stroke alone; the empty position is legible as empty |
| **Overclaim risk** | **HIGH in both directions** — an empty gate invites the audience to fill it; a red gate reads as a defect |
| **Likely producer failure** | **Filling, shading or deleting the empty authority position** — all three are wrong |
| **Transition to next slide** | "One state left — and it's the one people expect me to point at a folder for." |

**STOP conditions — Slide 6.** Stop and return to
[`M04-S06-publication-authority-gate.md`](../../assets/module-04/source/M04-S06-publication-authority-gate.md) §14 if:

- **the authority position is filled, shaded, hatched or removed**;
- any name or substitute role appears — including "the BIM Manager, realistically";
- the `Shared → Published` connector becomes solid, or is faded to read as in progress;
- a checkmark appears anywhere;
- **red failure styling is applied** to the gate or the output;
- `Information remains Shared` is dropped;
- a date or owner is attached to the block;
- `TRN-E03` is drawn as the transition rather than named in one annotation.

#### Slide 7 — Record / Retained: preservation without an Archive folder · 1.0 min

| Field | Value |
|---|---|
| **Number** | 7 |
| **Exact title** | Record / Retained: preservation without an Archive folder |
| **Allocated time** | **1.0 min** — allocated, not measured |
| **Narrative role** | **Fourth state.** A governed obligation with an undecided method |
| **Teaching purpose** | Show retention as an **established obligation** with an **undecided method**. |
| **Principal message** | Retention is a governed obligation; the project has not yet decided the folder, system or method by which it will be implemented. |
| **Layout** | Two panels |
| **Visual identifier** | **`W7`** |
| **Visual-source identifier** | `M04-S07` |
| **Visual-source path** | [`M04-S07-retention-obligation-versus-method.md`](../../assets/module-04/source/M04-S07-retention-obligation-versus-method.md) |
| **Governance status** | **`CONTROLLED GOVERNANCE`** — the obligation. **`UNRESOLVED`** — the method |
| **Implementation status** | **Not addressed in any validation record** |
| **Principal source basis** | `S1` §6.3, §7.10, §9.9, §12.10; `S2` §1, §19; **`S3` §3.1, §3.5, `CGD-C06`** |
| **Classification** | `CONTROLLED` + `SUPPORTING` + `DECISION-RECORD` |
| **Visible labels** | `OBLIGATION — ESTABLISHED` · `METHOD — UNRESOLVED` · `location: TBD` · `retention period: TBD` · `responsible holder: TBD` · `superseded ≠ deleted` |
| **Mandatory warning** | **`Record / Retained is a state or obligation. It is NOT automatically a folder.`** — on the slide |
| **Fixed geometry or relationship** | Preservation without an Archive folder — see [`M04-S07-retention-obligation-versus-method.md`](../../assets/module-04/source/M04-S07-retention-obligation-versus-method.md) §6 for the fixed geometry |
| **Connector semantics** | **Not applicable — no connector, by requirement.** |
| **Accessibility requirement** | `TBD` and `unavailable` are text — whitespace alone would be skipped by a screen reader |
| **Overclaim risk** | **MEDIUM-HIGH** — the audience expects a folder and will read one in |
| **Likely producer failure** | Supplying a folder, because the audience expects one and the panel looks unfinished |
| **Transition to next slide** | "So — four states, four different permissions to rely, and two of them we can't currently reach. Which brings us to the interesting question: what actually moves information between them?" |

**STOP conditions — Slide 7.** Stop and return to
[`M04-S07-retention-obligation-versus-method.md`](../../assets/module-04/source/M04-S07-retention-obligation-versus-method.md) §14 if:

- **`04 Archive` appears anywhere**, in any form, including as a greyed suggestion;
- a folder icon, storage icon or archive graphic is introduced;
- the method panel is **filled, shaded, greyed or removed**;
- a retention period, date or named holder is invented;
- a destination arrow is drawn from the obligation panel;
- the panels become unequal in size;
- the mismatch is redrawn as a four-area-to-four-state alignment;
- a green check appears.

### Section C — The transition workflow · Slides 8–11 · 6.0 min

#### Slide 8 — A transition is more than moving a file · 1.5 min

| Field | Value |
|---|---|
| **Number** | 8 |
| **Exact title** | A transition is more than moving a file |
| **Allocated time** | **1.5 min** — allocated, not measured |
| **Narrative role** | **Section C opens.** What a transition actually is, against what a user can technically do |
| **Teaching purpose** | Show the two side by side, and that **one does not produce the other**. |
| **Principal message** | The transition occurs when the project authorises a new permitted use and records the required evidence — not when a file changes location. |
| **Layout** | Two panels, no connector |
| **Visual identifier** | **`W8`** |
| **Visual-source identifier** | `M04-S08` |
| **Visual-source path** | [`M04-S08-file-movement-versus-transition.md`](../../assets/module-04/source/M04-S08-file-movement-versus-transition.md) |
| **Governance status** | **`CONTROLLED GOVERNANCE`** — `CGD-C03` is an active condition |
| **Implementation status** | **Not applicable.** This visual compares two kinds of act; it asserts nothing about the live platform |
| **Principal source basis** | **`CGD-C03`**; `S2` §2, §3, §14, §17; `S1` §6.9, §12.1; `S4` §9 |
| **Classification** | `DECISION-RECORD` + `SUPPORTING` + `CONTROLLED` + `INTERP` |
| **Visible labels** | `TECHNICAL ACTION` · `GOVERNED TRANSITION` · `establishes NONE of:` · `Teaching structure` · `NO CONNECTOR. The left does not produce the right.` |
| **Mandatory warning** | **`NO CONNECTOR. The left does not produce the right.`** — on the slide, between the panels |
| **Fixed geometry or relationship** | Technical action against governed transition — see [`M04-S08-file-movement-versus-transition.md`](../../assets/module-04/source/M04-S08-file-movement-versus-transition.md) §6 for the fixed geometry |
| **Connector semantics** | **Not applicable between the panels — no connector, by requirement.** |
| **Accessibility requirement** | **The absent connector is stated in text**, because an absence cannot be perceived |
| **Overclaim risk** | **HIGH** — a two-panel layout invites the eye to pair them, and pairing them asserts that the left produces the right |
| **Likely producer failure** | Adding a connector between the panels, because two panels invite pairing |
| **Transition to next slide** | "So a transition is a governed act. Which raises an obvious question — how many of them are there? And the answer surprises most people." |

**STOP conditions — Slide 8.** Stop and return to
[`M04-S08-file-movement-versus-transition.md`](../../assets/module-04/source/M04-S08-file-movement-versus-transition.md) §14 if:

- **any connector, arrow, bracket or equals sign appears between the panels** — this is a STOP failure, not a preference;
- an icon or chevron is placed in the gutter;
- the panels become unequal in size;
- the right panel's fields are populated;
- the `Teaching structure` label is dropped;
- a permission screenshot, folder tree or product logo is introduced;
- a green completion treatment appears;
- the slide is animated so that one panel becomes the other.

#### Slide 9 — The eight controlled steps, and the two that change state · 1.5 min

| Field | Value |
|---|---|
| **Number** | 9 |
| **Exact title** | The eight controlled steps, and the two that change state |
| **Allocated time** | **1.5 min** — allocated, not measured |
| **Narrative role** | **The full set, classified.** Eight controlled steps, and the two that change state |
| **Teaching purpose** | Show all eight steps **grouped by kind** — and that **only `T1` and `T4` change information state**. |
| **Principal message** | The identifiers describe different controlled acts. Only two change the information state. |
| **Layout** | Grouped table |
| **Visual identifier** | **`W9`** |
| **Visual-source identifier** | `M04-S09` |
| **Visual-source path** | [`M04-S09-eight-controlled-steps.md`](../../assets/module-04/source/M04-S09-eight-controlled-steps.md) |
| **Governance status** | **Mixed** — `T1` controlled · `T4` **`BLOCKED`** · `T7` **`UNRESOLVED`** · the rest proposed |
| **Implementation status** | **`IMPLEMENTATION UNVERIFIED`** — *"no complete traceable cycle"* |
| **Principal source basis** | **`S2` §3.1, §3.2**; `S2` §2, §3; `S1` §9.4, §9.7, §9.8; `S4` §8 |
| **Classification** | `SUPPORTING` throughout, with `CONTROLLED` for `T1`'s authority |
| **Visible labels** | `T1`–`T8` in five kind groups · `ESTABLISHED` · `BLOCKED` · `Shared → Shared` · `Published → Published` · `Only T1 and T4 change information state` |
| **Mandatory warning** | **`Only T1 and T4 change information state.`** — as a prominent headline, on the slide |
| **Fixed geometry or relationship** | Eight controlled steps, grouped by kind — see [`M04-S09-eight-controlled-steps.md`](../../assets/module-04/source/M04-S09-eight-controlled-steps.md) §6 for the fixed geometry |
| **Connector semantics** | **Not applicable — no connector, and this is absolute.** |
| **Accessibility requirement** | A real table with a header row; `T1`/`T4` distinguished by weight, never colour; no empty cells |
| **Overclaim risk** | **HIGHEST, jointly with `W3`** — eight identifiers in a row read as an eight-step state machine |
| **Likely producer failure** | **Converting the table to a flowchart**, because eight identifiers look like a sequence |
| **Transition to next slide** | "Two of the eight change state. One of those two has an authority we can point at. Let's take it apart." |

**STOP conditions — Slide 9.** Stop and return to
[`M04-S09-eight-controlled-steps.md`](../../assets/module-04/source/M04-S09-eight-controlled-steps.md) §14 if:

- **the table is converted to a flowchart, an arrow chain or a Mermaid diagram** — this is the module's absolute case;
- the groups are numbered, or reordered into a journey;
- the state-effect column is dropped or left blank on any row;
- `T1` is coloured green or `T4` coloured red;
- the headline is removed or reduced to a caption;
- the implementation line is dropped;
- any row is presented as chronologically following another.

#### Slide 10 — Gates, authority and evidence · 1.5 min

| Field | Value |
|---|---|
| **Number** | 10 |
| **Exact title** | Gates, authority and evidence |
| **Allocated time** | **1.5 min** — allocated, not measured |
| **Narrative role** | **One transition unpacked.** The working case — checks, authority, evidence |
| **Teaching purpose** | Unpack **one** controlled transition — trigger, checks, authority, evidence, permitted use. |
| **Principal message** | `T1` works as a governed transition because its purpose, checks, authority and evidence are defined — even though complete live operation is not yet verified. |
| **Layout** | One horizontal chain |
| **Visual identifier** | **`W10`** |
| **Visual-source identifier** | `M04-S10` |
| **Visual-source path** | [`M04-S10-t1-gate-model.md`](../../assets/module-04/source/M04-S10-t1-gate-model.md) |
| **Governance status** | **`CONTROLLED GOVERNANCE`** — the only transition with an established authority |
| **Implementation status** | **`IMPLEMENTATION UNVERIFIED`** — no complete cycle demonstrated |
| **Principal source basis** | **`S2` §3.1–§3.3, §9**; `S1` §7.7, §9.4, §9.11; `S4` §7, §8 |
| **Classification** | `SUPPORTING` + `CONTROLLED` + `DECISION-RECORD` |
| **Visible labels** | `WIP` · `SHARED` · `Author` · `Checker` · `Task-Team Lead` · `receiving user` · `EVIDENCE` · `NO PARTIAL PROGRESSION` |
| **Mandatory warning** | **`Governance definition ≠ live implementation evidence`** — on the slide |
| **Fixed geometry or relationship** | One transition, unpacked — see [`M04-S10-t1-gate-model.md`](../../assets/module-04/source/M04-S10-t1-gate-model.md) §6 for the fixed geometry |
| **Connector semantics** | See [`M04-S10-t1-gate-model.md`](../../assets/module-04/source/M04-S10-t1-gate-model.md) §7 — the connector table is fixed |
| **Accessibility requirement** | The evidence field is named text, never an icon; CDE Administration's position stated in words |
| **Overclaim risk** | **MEDIUM-HIGH** — a fully populated example reads as a running procedure |
| **Likely producer failure** | Compressing the evidence field for space, or replacing it with a folder icon |
| **Transition to next slide** | "That's what a transition looks like when the authority exists. Now the one where it doesn't." |

**STOP conditions — Slide 10.** Stop and return to
[`M04-S10-t1-gate-model.md`](../../assets/module-04/source/M04-S10-t1-gate-model.md) §14 if:

- **the evidence field is compressed, omitted, or converted into a folder-location icon**;
- a green approval tick or completion marker appears at the Shared end;
- a publication path is drawn;
- CDE Administration is placed **inside** the chain, or connected to it;
- all eight readiness conditions are shown as a checklist;
- a numeric quality threshold is introduced;
- the failure route is dropped;
- the governance-versus-implementation line is removed;
- `ARC-01` is described as a complete cycle.

#### Slide 11 — Why `Shared → Published` remains blocked · 1.5 min

| Field | Value |
|---|---|
| **Number** | 11 |
| **Exact title** | Why `Shared → Published` remains blocked |
| **Allocated time** | **1.5 min** — allocated, not measured |
| **Narrative role** | **The blocked case.** Two separate blocked objects, and why resolving one resolves nothing else |
| **Teaching purpose** | Show **two separate blocked objects** — a state transition and a delivery event — and that resolving one would not resolve the other. |
| **Principal message** | `T4` cannot proceed because publication authority is unassigned; `TRN-E03` remains blocked because a delivery event requires several additional decisions. |
| **Layout** | Two panels |
| **Visual identifier** | **`W11`** |
| **Visual-source identifier** | `M04-S11` |
| **Visual-source path** | [`M04-S11-t4-and-trn-e03.md`](../../assets/module-04/source/M04-S11-t4-and-trn-e03.md) |
| **Governance status** | **`BLOCKED`** — both. Two authorities **`UNRESOLVED`** |
| **Implementation status** | **Not reached.** *"No governed publication / exchange authority evidence was established"* |
| **Principal source basis** | **`S2` §3.1–§3.3, §11, §19**; **`S5` §5, §5.1**; `S1` §9.4, §9.7, §9.8; `S4` §9 |
| **Classification** | `SUPPORTING` + `CONTROLLED` + `DECISION-RECORD` |
| **Visible labels** | `PANEL 1 · T4` · `PANEL 2 · TRN-E03` · `exercises T4` · `TBD` · `Status: BLOCKED` · `Status: PROPOSED — BLOCKED` · `Blocked by FIVE matters` · `T4 is blocked by ONE` |
| **Mandatory warning** | **`Satisfying T4 alone would not automatically complete delivery.`** — on the slide, beneath both panels |
| **Fixed geometry or relationship** | Two blocked objects, not one — see [`M04-S11-t4-and-trn-e03.md`](../../assets/module-04/source/M04-S11-t4-and-trn-e03.md) §6 for the fixed geometry |
| **Connector semantics** | See [`M04-S11-t4-and-trn-e03.md`](../../assets/module-04/source/M04-S11-t4-and-trn-e03.md) §7 — the connector table is fixed |
| **Accessibility requirement** | Separateness stated in words; the block is not red; the empty position is not shaded |
| **Overclaim risk** | **HIGH in both directions** — merged, it hides four dependencies; styled red, it reads as a defect |
| **Likely producer failure** | Merging the two panels into one publication-to-acceptance chain |
| **Transition to next slide** | "So the states and the transitions are defined, and two of them are waiting on decisions. What holds all of it together in practice? Properties and metadata." |

**STOP conditions — Slide 11.** Stop and return to
[`M04-S11-t4-and-trn-e03.md`](../../assets/module-04/source/M04-S11-t4-and-trn-e03.md) §14 if:

- **the two panels are merged into one object**;
- **any connector is drawn between the panels**;
- any solid arrow appears;
- the publication-authority position is filled, shaded or removed;
- any of the five matters is filled with an invented value;
- a completion tick appears;
- **red failure styling is applied** to either panel;
- `Information remains Shared` is dropped;
- the one-versus-five contrast is removed;
- the panels become unequal in size.

### Section D — Properties and evidence · Slides 12 · 1.5 min

#### Slide 12 — Naming, revision, suitability and metadata support control · 1.5 min

| Field | Value |
|---|---|
| **Number** | 12 |
| **Exact title** | Naming, revision, suitability and metadata support control |
| **Allocated time** | **1.5 min** — allocated, not measured |
| **Narrative role** | **The supporting properties.** What they control, and the four standards that do not exist |
| **Teaching purpose** | Show the six properties as **six different control questions**, and that **four of the standards behind them do not exist**. |
| **Principal message** | Naming and metadata support control by identifying information and its permitted use — but the code never replaces the governance decision. |
| **Layout** | Two zones — six rows, four empty boxes |
| **Visual identifier** | **`W12`** |
| **Visual-source identifier** | `M04-S12` |
| **Visual-source path** | [`M04-S12-property-stack.md`](../../assets/module-04/source/M04-S12-property-stack.md) |
| **Governance status** | **`CONTROLLED GOVERNANCE`** — what each property must support. **`UNRESOLVED`** — every code set and the schema |
| **Implementation status** | **No standard established.** All four `standards/` directories hold only `.gitkeep` |
| **Principal source basis** | **`S1` §6.8, §11.3, §11.4**; `S2` §13; `S12`; **`CGD-C01`, `CGD-C03`** |
| **Classification** | `CONTROLLED` + `INTERP` |
| **Visible labels** | Six properties with their control questions · `Naming standard` · `Revision convention` · `Suitability code set` · `Metadata schema`, each `not established` |
| **Mandatory warning** | **`A code identifies. It does not authorise, and it does not prove the process behind it occurred.`** — on the slide |
| **Fixed geometry or relationship** | What the properties control — and what has not been decided — see [`M04-S12-property-stack.md`](../../assets/module-04/source/M04-S12-property-stack.md) §6 for the fixed geometry |
| **Connector semantics** | **Not applicable — no connector, by requirement.** |
| **Accessibility requirement** | `not established` is text, not whitespace; empty boxes are not shaded or hatched |
| **Overclaim risk** | **HIGH** — a populated property stack teaches four standards that do not exist |
| **Likely producer failure** | **Filling one of the four empty boxes with an example**, or dating them as in progress |
| **Transition to next slide** | "So properties support control, and the codes behind them are decisions we haven't made. Which raises the obvious question — in what order do these things happen?" |

**STOP conditions — Slide 12.** Stop and return to
[`M04-S12-property-stack.md`](../../assets/module-04/source/M04-S12-property-stack.md) §14 if:

- **any of the four boxes is filled, shaded, greyed or removed**;
- an example code, filename, field name or schema appears — **including as "something like"**;
- a classification system is named;
- a properties-palette screenshot or software field list is introduced;
- `not established` is replaced by *TBD in progress*, *to follow*, or a date;
- a tick, red styling or warning triangle appears on an empty box;
- an arrow or connector is drawn between properties or into a box;
- the empty zone is shrunk below the area of the property list.

### Section E — Applying the model · Slides 13–14 · 3.0 min

#### Slide 13 — Governance first; permissions and configuration follow · 1.0 min

| Field | Value |
|---|---|
| **Number** | 13 |
| **Exact title** | Governance first; permissions and configuration follow |
| **Allocated time** | **1.0 min** — allocated, not measured |
| **Narrative role** | **Synthesis.** The direction of authority, and the direction that is refused |
| **Teaching purpose** | Show the **direction of authority** — decision, process, configuration, evidence — and that the reverse does not hold. |
| **Principal message** | Configuration implements governance. It does not create it. |
| **Layout** | Chain, refused reverse, two boxes |
| **Visual identifier** | **`W13`** |
| **Visual-source identifier** | `M04-S13` |
| **Visual-source path** | [`M04-S13-governance-then-configuration.md`](../../assets/module-04/source/M04-S13-governance-then-configuration.md) |
| **Governance status** | **`CONTROLLED GOVERNANCE`** |
| **Implementation status** | **`IMPLEMENTATION UNVERIFIED`** — `S2` §6 records alignment as a four-layer question |
| **Principal source basis** | **`S1` §5.9, §6.9, §12.1, §12.6, §12.8, §12.9**; `S2` §6, §14, §17; **`CGD-C07`, `CGD-C08`** |
| **Classification** | `CONTROLLED` + `SUPPORTING` + `DECISION-RECORD` |
| **Visible labels** | `Governance decision` → `Process rule` → `Permission / configuration` → `Implementation evidence` · `Platform setting ──✕──▶ governance authority` · `Holder: TBD` |
| **Mandatory warning** | **`A configuration that was never approved is a deviation, however competently it was applied.`** — `S1` §5.9, verbatim, on the slide |
| **Fixed geometry or relationship** | Direction of authority — see [`M04-S13-governance-then-configuration.md`](../../assets/module-04/source/M04-S13-governance-then-configuration.md) §6 for the fixed geometry |
| **Connector semantics** | See [`M04-S13-governance-then-configuration.md`](../../assets/module-04/source/M04-S13-governance-then-configuration.md) §7 — the connector table is fixed |
| **Accessibility requirement** | The refusal is text as well as stroke; not red; legible in monochrome as a break plus a cross |
| **Overclaim risk** | **MEDIUM-HIGH** — a forward-only chain can be read in either direction, and a permissions image makes configuration the concrete thing |
| **Likely producer failure** | Dropping the reverse arrow, leaving a chain that can be read backwards |
| **Transition to next slide** | "So: decide, record, configure, evidence — in that order. Which means for Triviron the useful question isn't *how do we set up the CDE*. It's *what do we have to decide first*." |

**STOP conditions — Slide 13.** Stop and return to
[`M04-S13-governance-then-configuration.md`](../../assets/module-04/source/M04-S13-governance-then-configuration.md) §14 if:

- **the reverse arrow is removed**, or is drawn as a real traversable arrow with a decoration on it;
- the visual is rebuilt in Mermaid or any graph renderer;
- a name appears in place of `Holder: TBD`;
- the *may* and *does not* boxes become unequal;
- the `S1` §5.9 sentence is paraphrased or dropped;
- a permissions screenshot, matrix or platform UI is introduced;
- an org chart or reporting line appears;
- a loop back to the start is added;
- the evidence stage is dropped from the chain;
- a verification method is added — that is Module 6.

#### Slide 14 — What Triviron must define before configuring its CDE · 2.0 min

| Field | Value |
|---|---|
| **Number** | 14 |
| **Exact title** | What Triviron must define before configuring its CDE |
| **Allocated time** | **2.0 min** — allocated, not measured |
| **Narrative role** | **Transfer.** The questions a new project must answer before configuring anything |
| **Teaching purpose** | Convert the module into **questions Triviron must answer before configuring anything**. |
| **Principal message** | Configure the platform only after the states, purposes, authorities, gates and evidence requirements have been decided. |
| **Layout** | Five question groups |
| **Visual identifier** | **`W14`** |
| **Visual-source identifier** | `M04-S14` |
| **Visual-source path** | [`M04-S14-triviron-questions.md`](../../assets/module-04/source/M04-S14-triviron-questions.md) |
| **Governance status** | **None asserted for Triviron** — the project has no entry in any register |
| **Implementation status** | **None asserted for Triviron** |
| **Principal source basis** | **No Triviron source exists.** The question *structure* draws on `S1` §6.1, §6.3, §9.7, §9.8, §11.3, §11.4, §5.9, §12.6, §12.8; `S2` §2, §3.3, §19; `S4` §7, §11; `S5` §5.1; `CGD-C01`–`CGD-C08` |
| **Classification** | `INTERP` + `SYNTH` |
| **Visible labels** | Five group headings · `Who holds publication authority?` · `Who holds acceptance authority?` · `CDE configuration basis — not yet established` |
| **Mandatory warning** | **`CDE configuration basis — not yet established`** — the end state, in **neutral styling**, with no warning colour, icon, date or owner |
| **Fixed geometry or relationship** | Questions only — see [`M04-S14-triviron-questions.md`](../../assets/module-04/source/M04-S14-triviron-questions.md) §6 for the fixed geometry |
| **Connector semantics** | **Not applicable — no connector.** |
| **Accessibility requirement** | Every item reads as a question; the end state is neutral in colour and text |
| **Overclaim risk** | **HIGH — about Triviron, not about Harrismith** |
| **Likely producer failure** | Balancing a sparse slide with an illustrative answer — **which invents the project** |
| **Transition to next slide** | **Closing — then stop.** No Module 5 preview, no programme summary, no reassurance that Harrismith is nearly finished. |

**STOP conditions — Slide 14.** Stop and return to
[`M04-S14-triviron-questions.md`](../../assets/module-04/source/M04-S14-triviron-questions.md) §14 if:

- **any item on the slide is not a question**;
- either compulsory authority question is answered, hinted at, or paired with a candidate role;
- **either compulsory question is removed** from the bordered block;
- an answer column, placeholder answer or worked example is added;
- a platform is named or recommended;
- a Triviron fact of any kind appears, including a placeholder project name or a date;
- the five groups are reordered, or configuration is moved earlier;
- the end state acquires a warning colour, an icon, a date, an owner or a progress bar;
- a sixth group is added to balance the layout.

## 5. The nine deliberately incomplete visuals

**Listed once, so no producer meets one for the first time mid-build.** The
visual plan ranks eight by completion risk; **Slide 8's empty gutter is added
here**, because a gutter is a space a producer fills.

| Slide | Element | Why it stays |
|---|---|---|
| 2 | Three `not established` code-set lines | Filling one invents a standard; marking all five invents an unresolved matter |
| 3 | `T4` break · empty authority · unreachable stub | Completing any one claims a working publication lifecycle |
| 6 | The publication-authority position | Filled invents an authority; removed implies none is needed; shaded reads as failure |
| 7 | The retention-method panel | The obligation is governed; the method is not |
| 8 | The empty gutter | A connector asserts the causation `CGD-C03` refuses |
| 11 | Two blocked panels | Merging them hides four unresolved matters |
| 12 | Four `not established` boxes | The project has explicitly declined to create these standards |
| 13 | The refused reverse arrow, and `Holder: TBD` | A forward-only chain can be read backwards |
| 14 | Two unanswered questions, and the open end state | Answering either is the module's worst failure |

## 6. Status

| Field | Value |
|---|---|
| Specification | **Complete (T4-F)** |
| Slides | **14**, all specified |
| Timing | **`20.0 minutes allocated — not yet measured`** |
| Visual sources | **14**, all `SOURCE COMPLETE` |
| Rendered assets | **None. None required** |
| PowerPoint | **Does not exist** |
| Authority | **None.** This is teaching material |
