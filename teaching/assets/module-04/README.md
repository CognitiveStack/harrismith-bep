# Module 4 — Visual source set

**Status:** Visual-source baseline complete. **No rendered assets exist.**
**Not governance.**

Text-based, reviewable visual source for all fourteen slides of
**Module 4 — CDE Workflows and Information States**.

**Every visual in this set is a native-layout specification.** **No visual in
Module 4 is Mermaid**, and none is a rendered image.

---

## 1. Contents

```text
teaching/assets/module-04/
├── README.md               this file — conventions and integrity rules
├── visual-register.md      14 concepts and 14 slide sources, with status and warnings
├── slide-visual-map.md     Slides 1–14 mapped to their visuals
├── source/                 the slide visual source files (14)
│   ├── M04-S01-governance-workflow-platform.md
│   ├── M04-S02-five-properties.md
│   ├── M04-S03-four-state-model.md
│   ├── M04-S04-wip-task-team-boundary.md
│   ├── M04-S05-shared-defined-purpose.md
│   ├── M04-S06-publication-authority-gate.md
│   ├── M04-S07-retention-obligation-versus-method.md
│   ├── M04-S08-file-movement-versus-transition.md
│   ├── M04-S09-eight-controlled-steps.md
│   ├── M04-S10-t1-gate-model.md
│   ├── M04-S11-t4-and-trn-e03.md
│   ├── M04-S12-property-stack.md
│   ├── M04-S13-governance-then-configuration.md
│   └── M04-S14-triviron-questions.md
└── rendered/
    └── README.md           records that nothing has been rendered
```

| Start here | For |
|---|---|
| [`visual-register.md`](visual-register.md) | What exists, its status, its warnings and what may not be inferred from it |
| [`slide-visual-map.md`](slide-visual-map.md) | Which visual serves which slide, and what must be omitted |
| [`source/`](source/) | The visual source itself — geometry, wording, connectors, STOP conditions |

## 2. Purpose of this baseline

**A visual specification says what a visual must be. A slide source says how to
build it. Neither is a picture.**

This set exists so that a PowerPoint can be reconstructed later **without
reopening the full teaching baseline** — the eighteen-field header and sixteen
sections in each source file carry everything a producer needs, and nothing the
producer is free to reinterpret.

## 3. Four artefacts, and they are not interchangeable

| Artefact | What it is | Where |
|---|---|---|
| **Teaching source** | The controlled Harrismith documents, and the module's classified reading of them | `bep/`, `supporting/`, `docs/` · [`source-map.md`](../../module-04-cde-workflows-and-information-states/source-map.md) |
| **Visual specification** | `W1`–`W14` — the **authoritative** statement of each visual's form, geometry, labels and prohibitions | [`visual-demonstration-plan.md`](../../module-04-cde-workflows-and-information-states/visual-demonstration-plan.md) |
| **Slide source** | `M04-S01`–`M04-S14` — this set. **Implements** the specification for one slide | [`source/`](source/) |
| **Rendered derivative** | An image or a PowerPoint slide built from a slide source | **Does not exist** |

**The order of authority runs downward and never upward.**

**Where a slide source and the visual plan differ, the plan is authoritative and
the slide source is the thing to correct.** **A rendered derivative never becomes
the authority**, however carefully it was produced or however widely it was
circulated.

## 4. One identifier space

```text
14 visual concepts
=
14 slides
=
14 slide-specific visual-source files
```

**Module 4 has a strict one-to-one mapping.** No visual concept serves more than
one slide; no slide has two primary visual concepts.

**This differs from Module 3**, where `V1` served two slides and thirteen
concepts produced fourteen files. **There is no thirteen-versus-fourteen
reconciliation here**, and a reader carrying the Module 3 pattern across should
not look for one.

**Identifiers are stable.** `W1`–`W14` and `M04-S01`–`M04-S14` are not renamed or
renumbered to suit a later render, tool or deck.

## 5. Reading order

1. [`visual-register.md`](visual-register.md) — the fourteen concepts, their
   status and their prohibited inferences.
2. [`slide-visual-map.md`](slide-visual-map.md) — which visual serves which
   slide, and the likely producer failure for each.
3. [`source/`](source/) — the file for the slide being built.
4. [`visual-demonstration-plan.md`](../../module-04-cde-workflows-and-information-states/visual-demonstration-plan.md)
   — **whenever a source file and a producer's judgement disagree.**

## 6. Native layout only — and no Mermaid

**Every Module 4 visual is a Markdown native-layout specification**, and the
PowerPoint is reconstructed with **native shapes, tables and text boxes**.

**No visual in Module 4 is Mermaid.** This is a decision taken concept by concept
and recorded in the plan's §2 and summary. The short form:

| Risk | Why a renderer is prohibited |
|---|---|
| **Auto-completing a blocked route** | `W3`, `W9`, `W11` — a renderer draws a chain, and a chain implies traversal |
| **Drawing a refused edge as a real edge** | `W13` — a strike-through is styling a graph engine may drop |
| **Arranging non-sequential items as a sequence** | `W2`, `W12` — the properties are peers, not stages |
| **Choosing the layout direction** | `W1` — the **vertical order is the content**, and a horizontal rendering states the layers are peers |
| **Normalising side labels into the chain** | `W10` — CDE Administration must sit beside it, not in it |
| **Rendering an outbound edge** | `W4` — the route out of WIP must not be drawn |

**A renderer that normalises a broken line into a solid one commits the module's
central error.**

## 7. Mandatory visual integrity rules

**These apply to every visual in this set, to any render of one, and to any
PowerPoint built from one.**

1. **Governance status and implementation status both remain visible.** They are
   not the same thing, and neither is moved to the speaker notes.
2. **No blocked route is completed.** `Shared → Published` stays broken;
   `Published → Record / Retained` stays unreachable.
3. **No empty authority field is filled** — and none is shaded, greyed or
   removed. Filled invents an authority; removed implies none is needed; shaded
   reads as failure.
4. **No unanswered question is answered**, hinted at, or paired with a candidate.
5. **No unestablished code or schema is populated** — not with an example, not
   with a placeholder, not with "something like".
6. **No area is silently converted into a state.** The existence or name of an
   area establishes no information state.
7. **No state is silently converted into a folder.** Record / Retained is a state
   and an obligation, and **no `04 Archive` root exists, is approved or is
   required.**
8. **No technical action is converted into authority.** Being able to perform an
   action in the software says nothing about who was authorised to decide it.
9. **No proposed governance is described as live.** The CDE workflow is
   `PROPOSED GOVERNANCE` and **does not describe the live platform.**
10. **No platform screenshot is introduced**, and no external imagery of any
    kind.
11. **No final asset overrides the Markdown source.** A render is derivative.
12. **No visual uses Mermaid.**

**A producer who removes, fills, shades or completes any mandatory empty element
has changed the claim** — not the styling.

## 8. Geometry and accessibility conventions

**Reference canvas — fixed for `W1`, `W2` and `W3`, and applied by a producer to
all fourteen:**

| Convention | Value |
|---|---|
| **Reference canvas** | **960 × 540 pt** — 13.333 × 7.5 in, standard 16:9 |
| **Origin** | Top left. `x` increases right, `y` increases down |
| **Side margins** | **48 pt**, or **40 pt** where a visual carries four panels |
| **Title zone** | `y` 0–72, reserved |
| **Minimum type size** | **14 pt.** Status, source and connector labels never go below it |
| **Minimum text contrast** | **4.5:1** |
| **Minimum stroke and border contrast** | **3:1** |

**Three accessibility rules apply to every visual in this set:**

- **A blocked, refused or absent element is carried in text as well as in line
  style.** An absence cannot be perceived by a screen reader, and a dashed stroke
  cannot be relied on at projection scale.
- **No meaning depends on colour**, and **neither red nor green carries meaning
  anywhere in this module.** A block is deliberate governance, not an error; a
  supported route is not an approval.
- **Equal things are drawn equal.** Where two panels or five cards are peers,
  they are set to identical dimensions numerically — because a producer's
  instinct is to grow what is populated and shrink what is deliberately empty,
  **which inverts the teaching.**

## 9. Source-file conventions

**Every file in [`source/`](source/) opens with an eighteen-field header:**

slide-source identifier · slide number · slide title · visual identifier ·
visual title · increment · teaching purpose · principal sources · classification
· governance status · implementation status · fixed visual form · known
limitation · overclaim risk · blocked or unresolved element · mandatory on-slide
warning · external imagery · rendered-asset status.

**Then sixteen sections, in fixed order:**

| # | Section |
|---|---|
| 1 | Purpose and five-second takeaway |
| 2 | Source and authority basis |
| 3 | Governance and implementation status |
| 4 | Fixed layout |
| 5 | Exact visible wording |
| 6 | Geometry or spatial relationships |
| 7 | Connector semantics |
| 8 | Status and warning treatment |
| 9 | Build or reveal sequence |
| 10 | Mandatory omissions |
| 11 | Accessibility and projection requirements |
| 12 | Screen-reader or presenter-notes description |
| 13 | Producer-failure test |
| 14 | STOP conditions |
| 15 | Native PowerPoint reconstruction notes |
| 16 | Rendered-asset status |

**No section is omitted.** Where a field does not apply it says so precisely —
`Not applicable — no connector` — because an omitted section reads as an
oversight and a stated absence reads as a decision.

**`M04-S03` additionally carries its producer-failure test at the top**, before
section 1. It is the module's highest-risk visual, and the test belongs where a
producer will read it first.

## 10. Rendered assets

**None exist.** See [`rendered/README.md`](rendered/README.md).

**No rendering was attempted, no renderer was installed, and no network rendering
service was used.**

## 11. Safety boundary

Root [`README.md`](../../../README.md) §2.1 applies to this directory without
modification.

**Nothing here reads from, writes to or copies out of the Autodesk Desktop
Connector / ACCDocs tree.** **No asset was produced by changing any Autodesk
configuration.** **No live Autodesk observation was performed, and none is
authorised** — `S4` is an **existing controlled record**, read as evidence.

## 12. What happens next

**The assembly package is the next step**, after this baseline is accepted. It is
a separate increment and does not exist.

| Stage | Status |
|---|---|
| Teaching-content baseline, Slides 1–14 | **Complete (T4-D)** |
| Visual specifications `W1`–`W14` | **Complete (T4-E-A)** |
| **Visual-source baseline `M04-S01`–`M04-S14`** | **Complete (T4-E-B)** |
| Presentation assembly package | **Outstanding — next** |
| PowerPoint | **Outstanding** |
| Review and rehearsal | **Outstanding** |
| Measured timing | **Never performed.** 20.0 minutes is an allocation |
