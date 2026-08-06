# Module 5 — Visual Source Set

**Status:** **Visual-source baseline complete — fourteen sources, all
`SOURCE COMPLETE`.** **No rendered asset exists.**

**Teaching material. Not governance.** Nothing here decides, approves or
authorises anything.

---

## 1. Contents

```text
teaching/assets/module-05/
├── README.md               this file — the Module 5 asset rules
├── visual-register.md      fourteen concepts, their risks and their statuses
├── slide-visual-map.md     slide → visual → source, at a glance and in detail
├── M05-S01.md              Slide 1  · M5V-01
├── M05-S02.md              Slide 2  · M5V-02
├── M05-S03.md              Slide 3  · M5V-03
├── M05-S04.md              Slide 4  · M5V-04
├── M05-S05.md              Slide 5  · M5V-05
├── M05-S06.md              Slide 6  · M5V-06
├── M05-S07.md              Slide 7  · M5V-07
├── M05-S08.md              Slide 8  · M5V-08
├── M05-S09.md              Slide 9  · M5V-09
├── M05-S10.md              Slide 10 · M5V-10
├── M05-S11.md              Slide 11 · M5V-11
├── M05-S12.md              Slide 12 · M5V-12
├── M05-S13.md              Slide 13 · M5V-13
├── M05-S14.md              Slide 14 · M5V-14
└── rendered/
    └── README.md           why nothing is rendered, and what applies if it ever is
```

**There is no `source/` subdirectory.** The accepted visual plan reserved the
fourteen source files **directly under this directory**, and that accepted path
takes precedence over the Module 4 arrangement. **Filenames are exactly
`M05-S01.md`–`M05-S14.md`, with no descriptive suffix.**

## 2. What a visual-source baseline is

A source file is the **complete construction specification for one slide
visual** — its fixed form, its exact visible wording, its geometry, its connector
semantics, its build sequence, what must be omitted, how it fails, and what it
must never claim.

**It is not a picture, and it is not a deck.** It is the thing a producer builds
*from*, and the thing a later PowerPoint is checked *against*.

## 3. Authority chain

```text
controlled Harrismith source
  ↓
accepted Module 5 teaching content
  ↓
accepted visual-demonstration plan
  ↓
Module 5 slide-source file
  ↓
future presentation assembly package
  ↓
future external PowerPoint
```

**The order runs downward and never upward.** A later PowerPoint or render
**never becomes authoritative**.

| Where they differ | Which wins |
|---|---|
| A source file and the accepted plan | **The plan** |
| The plan and the accepted teaching content | **The teaching content** |
| Any teaching material and a controlled Harrismith source | **The controlled source** |

## 4. Identifier spaces — strictly one-to-one

```text
14 visual concepts
=
14 slides
=
14 source files
```

| Space | Range |
|---|---|
| Visual concept | `M5V-01` – `M5V-14` |
| Slide | 1 – 14 |
| Slide source | `M05-S01` – `M05-S14` |

**Module 5 has no asymmetry.** Unlike Module 3 — where `V1` serves two slides —
every Module 5 concept serves exactly one slide and is implemented by exactly one
source file.

**Identifiers are stable.** No `M5V` or `M05-S` identifier is renamed or
renumbered to suit a later render, tool or deck.

**No controlled identifier is reused.** `P1`–`P4`, `D4`–`D7`, `A2`, `T1`–`T8`,
`X1`–`X5`, `TRN-E01`–`TRN-E03`, `ARC-01`–`FIR-01` and `COORD-01` belong to the
controlled sources and appear in these files **only as quoted content**.

## 5. Reading order

1. [`visual-register.md`](visual-register.md) — what each visual is, and its risk.
2. [`slide-visual-map.md`](slide-visual-map.md) — which source serves which slide.
3. The relevant `M05-S<nn>.md` — how to build it.
4. **The accepted visual plan, whenever any judgement differs** —
   [`../../module-05-responsibility-matrices-and-information-delivery-planning/visual-demonstration-plan.md`](../../module-05-responsibility-matrices-and-information-delivery-planning/visual-demonstration-plan.md).

## 6. Form — native layout only

**Every one of the fourteen visuals is a native-layout specification.**
Rectangles, tables, text boxes, simple call-outs and deliberately controlled
connectors.

| Prohibited | Why |
|---|---|
| **Mermaid — all fourteen** | Auto-layout would imply hierarchy, sequence, equivalence, completion, identity between an event and a transition, an open route through a blocked gate, one merged matrix, one harmonised vocabulary, or a Triviron answer |
| **SmartArt** | Its automatic layouts imply exactly the hierarchy and sequence this module spends fourteen slides denying |
| **Graphviz, PlantUML** | Same objection as Mermaid |
| **External imagery** | Stock photography, platform or ACC screenshots, Autodesk / Revit / company logos, live CDE images, observed folder captures |
| **Live evidence** | No new observation is needed and **none is authorised** |

**Why no screenshot.** A screenshot makes *software implementation* concrete
while this module teaches **governance and proposed planning**. Module 5's
central hazard is the audience concluding that something is operating; an
interface image asserts exactly that, silently, and more persuasively than any
caption could withdraw.

**Module 5 therefore contains no diagram source a renderer could consume**, which
is a design decision and not a gap.

## 7. Module-wide integrity rules — twenty-six STOP conditions

**A producer must stop and refer back to the accepted plan if any visual:**

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

## 8. Geometry and accessibility conventions

| Parameter | Value |
|---|---|
| Reference canvas | **960 × 540 pt**, 16:9 |
| Origin | Top left; `x` increases right, `y` increases down |
| Title zone | `y = 0–72` — **reserved** |
| Side margins | **≥ 48 pt** |
| Minimum visible type | **14 pt** |
| Principal labels | **≥ 18 pt** |
| Text contrast | **≥ 4.5 : 1** |
| Border and connector contrast | **≥ 3 : 1** |

**Status appears on the slide, in words, and never by colour alone.** Connector
meaning is carried by **form and label**, not by colour. Every source carries a
logical reading order and a screen-reader description, and warnings must remain
legible at projection scale.

## 9. Source-file conventions

Every `M05-S<nn>.md` carries:

- an **eighteen-field header** — identifiers, purpose, sources, classification,
  both statuses, fixed form, known limitation, overclaim risk, the blocked or
  deliberately absent element, the mandatory warning, external imagery and
  rendered status;
- **sixteen sections**, in a fixed order — purpose · source and authority ·
  status · fixed layout · exact wording · geometry · connectors · status
  treatment · build sequence · omissions · accessibility · screen-reader
  description · producer-failure test · STOP conditions · native reconstruction ·
  rendered status;
- a **four-row completion table** recording source status, rendered status,
  renderer used and format.

**No section is omitted.** Where something does not apply, the file says so
explicitly — for example *"Not applicable — no connector is permitted."*

## 10. Rendered status

| Field | Value |
|---|---|
| Rendered assets | **NONE** |
| Rendering attempted | **No** |
| Renderer installed | **None** |
| Dependency installed | **None** |
| Network rendering service | **Not used** |

See [`rendered/README.md`](rendered/README.md).

## 11. Safety boundary

The repository safety boundary in root [`README.md`](../../../README.md) §2.1
applies without modification. **Nothing here reads from, writes to or changes
anything in the Autodesk Desktop Connector / ACCDocs tree**, or any Forma, ACC,
Revit or Navisworks configuration.

**No live observation is required, and none is authorised.** A note in a plan
that an observation might be useful is not an authorisation.

**Extracts inherit their source's status.** All three principal Module 5
resources are **approved with conditions and not published**. Nothing derived
from them may imply they are issued, delivered or accepted.

## 12. Next stage

**`T5-G` — the presentation assembly package.** It **does not exist**.

`T5-H` — external PowerPoint production — follows it, **outside this
repository**.

**Timing remains `20.0 minutes allocated — not measured`.** No review or
rehearsal has been performed.
