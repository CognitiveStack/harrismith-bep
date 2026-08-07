# Teaching Assets

**Status:** Visual **source** is committed for Modules 1, 2, 3, 4, 5 and 6. **No
rendered image asset exists anywhere in this directory.**

**Module 6's visual-source baseline is `SOURCE COMPLETE — ACCEPTED after
T6-F-R`.** Its **presentation assembly package (`T6-G`) is `PENDING CHATGPT
GOVERNANCE REVIEW` and not accepted**.

---

## 1. Purpose

`teaching/assets/` is the location for presentation assets supporting the
teaching modules — diagram source, cropped extracts, exported images and
prepared slide graphics.

### Current contents

```text
teaching/assets/
├── README.md      this file — asset rules for all modules
├── module-01/     visual source set for Module 1 (14 slide visuals)
├── module-02/     visual source set for Module 2 (14 slide visuals)
├── module-03/     visual source set for Module 3 (14 slide visuals, 13 concepts)
├── module-04/     visual source set for Module 4 (14 slide visuals, 14 concepts)
├── module-05/     visual source set for Module 5 (14 slide visuals, 14 concepts)
└── module-06/     visual source set for Module 6 (14 slide visuals, 14 concepts)
```

| Module | Visual source | Rendered assets | External evidence needed |
|---|---|---|---|
| [`module-01/`](module-01/) | **Complete — Slides 1–14** | **None** | 3 optional — `V1`, `V9`, `V10` |
| [`module-02/`](module-02/) | **Complete — Slides 1–14** | **None** | **None** |
| [`module-03/`](module-03/) | **Complete — Slides 1–14** | **None** | **None** |
| [`module-04/`](module-04/) | **Complete — Slides 1–14** | **None** | **None** |
| [`module-05/`](module-05/) | **Complete — Slides 1–14** | **None** | **None** |
| [`module-06/`](module-06/) | **Complete — Slides 1–14; ACCEPTED after `T6-F-R`** | **None** | **None** |

**Module 3 registers two identifier spaces of different sizes** — **13 visual
concepts** (`V1`–`V13`) and **14 slide-source files** (`M03-S01`–`M03-S14`),
because `V1` serves both Slide 1 and Slide 2. See
[`module-03/visual-register.md`](module-03/visual-register.md) §1.

**Modules 4 and 5 do not have that asymmetry.** Module 4 has **fourteen
concepts** (`W1`–`W14`), fourteen slides and fourteen slide-source files
(`M04-S01`–`M04-S14`); **Module 5 has fourteen concepts** (`M5V-01`–`M5V-14`),
fourteen slides and fourteen slide-source files (`M05-S01`–`M05-S14`). **Both are
strict one-to-one mappings.** See
[`module-04/visual-register.md`](module-04/visual-register.md) §1 and
[`module-05/visual-register.md`](module-05/visual-register.md) §1.

**Module 6 has the same strict one-to-one arrangement** — **fourteen concepts**
(`M6V-01`–`M6V-14`), fourteen slides and fourteen slide-source files
(`M06-S01`–`M06-S14`). See
[`module-06/visual-register.md`](module-06/visual-register.md) §1.

**Module 5's and Module 6's source files sit directly under their module
directories, with no `source/` subdirectory.** That is the path their accepted
visual plans reserved, and it takes precedence over the Module 4 arrangement.

**Module 4 differs from the other three in one further respect: it contains no
Mermaid at all.** Every one of its fourteen visuals is a **native-layout
specification** — geometry in points, exact labels, connector semantics, and
elements that are deliberately empty, broken or refused. **There is no diagram
source to render**, and the PowerPoint is reconstructed with native shapes. The
reasoning is recorded concept by concept in
[`../module-04-cde-workflows-and-information-states/visual-demonstration-plan.md`](../module-04-cde-workflows-and-information-states/visual-demonstration-plan.md)
§2, and summarised in [`module-04/README.md`](module-04/README.md) §6.

**Module 5 contains no Mermaid either, for the same reason and by the same
concept-by-concept decision.** All fourteen of its visuals are native-layout
specifications, recorded in
[`../module-05-responsibility-matrices-and-information-delivery-planning/visual-demonstration-plan.md`](../module-05-responsibility-matrices-and-information-delivery-planning/visual-demonstration-plan.md)
§2.4, and summarised in [`module-05/README.md`](module-05/README.md) §6. Its
hazards include a **blocked route that must stay broken**, an **unpopulated
matrix skeleton**, **five closed gates**, and a **question-only transfer slide
whose answer areas must stay empty**.

**Module 6 contains no Mermaid either**, decided visual by visual in
[`../module-06-coordination-review-approval-and-assurance/visual-demonstration-plan.md`](../module-06-coordination-review-approval-and-assurance/visual-demonstration-plan.md)
§2.5 and summarised in [`module-06/README.md`](module-06/README.md) §6. Its
hazards include a **governed route that must never close into a loop**,
**upward-only federation connectors**, a **deliberately incomplete check grid**,
**two detached status dispositions**, **nine permanently unticked completion
boxes**, and **seven Triviron answer areas that must stay empty**.

**Module 4's assembly package and external PowerPoint are already produced** —
the PowerPoint **outside this repository**, and **not committed here**. **Review
and rehearsal remain deferred**, as for Modules 1, 2 and 3.

**Module 5's assembly package is complete (T5-G)**, and its **external PowerPoint
is produced and accepted as `REV01`** (T5-H, corrected in T5-H-R1) — **held
outside this repository and not committed here**. **Rehearsal and measured timing
remain `DEFERRED` by governance decision (T5-I-D).**

**Module 6's visual-source baseline is complete and ACCEPTED after `T6-F-R`.**
**Its presentation assembly package is complete (`T6-G`)** —
[`../module-06-coordination-review-approval-and-assurance/presentation/`](../module-06-coordination-review-approval-and-assurance/presentation/),
**seven production-handoff files** — and is **`ACCEPTED after T6-G-R`**. **Its
external PowerPoint is produced and accepted as `REV01` (`T6-H`, corrected in
`T6-H-R1`) — held outside this repository and not committed here.** **Rehearsal
and measured timing remain `DEFERRED`.**

**One prohibition applies to `module-03/` specifically, and it is absolute.**
**No ISO diagram, table or figure is reproduced, redrawn, adapted or
reconstructed** — including from memory, from search results, from third-party
reproductions, or as a "simplified" derivative with changed styling. Every
Module 3 visual is an original teaching construction.

**Source and rendered output are different things**, and this directory
currently holds only the first. See
[`module-01/rendered/README.md`](module-01/rendered/README.md) for why nothing
was rendered and what happens if rendering is undertaken later.

The candidate visuals in
[`../module-01-what-is-a-bep/visual-demonstration-plan.md`](../module-01-what-is-a-bep/visual-demonstration-plan.md)
remain the controlling plan; `module-01/` implements it.

## 2. What belongs here

| Belongs | Does not belong |
|---|---|
| Redrawn diagrams of sourced processes | Anything from the Desktop Connector / ACCDocs tree |
| Cropped extracts of controlled tables | Uncropped screenshots of full documents |
| Reviewed, cropped platform screenshots | Raw platform captures that have not been reviewed |
| Exported model views prepared for projection | Project deliverables of any kind |
| Slide graphics authored for teaching | Anything that would be an authoring source or an issued artefact |

**This directory is teaching material.** It is not an authoring source, not an
output location, and nothing placed here acquires authority by being here.
`output/` remains the location for generated project-facing artefacts, and this
is not that.

## 3. Rules for adding an asset

1. **Safety boundary first.** Root [`README.md`](../../README.md) section 2.1
   applies without modification. Nothing is read from, written to or copied out
   of the Autodesk Desktop Connector / ACCDocs tree. No asset is produced by
   changing any Autodesk configuration.

2. **Live observation requires separate authorisation.** A note in a visual plan
   that an observation "may be useful" is not an authorisation. Any live
   observation is bounded, read-only and separately authorised.

3. **Review platform captures before committing.** Screenshots of ACC, Forma,
   Revit or Navisworks can carry more than intended — filenames, user names,
   activity history, folder contents, project metadata. Review the whole image,
   crop to the teaching content, and commit only what the slide needs.

4. **Crop extracts to the rows that carry the message.** A full-table screenshot
   is not thorough; it is unreadable at projection size and invites the audience
   to read instead of listen.

5. **Extracts inherit their source's status.** All seven principal sources are
   **approved with conditions and not published**. An asset derived from one
   must not imply it is issued, delivered or accepted.

6. **Record provenance.** Every asset is recorded in its module's visual
   register — what it is, where it came from, and any constraint on its use.
   For Module 1 that is
   [`module-01/visual-register.md`](module-01/visual-register.md).

7. **Prefer redrawing to screenshotting.** Several source sequences are already
   diagram-shaped in text — the CDE transition routes and the coordination cycle
   in particular. A redrawn diagram is clearer, carries no incidental detail, and
   states its own simplification honestly.

8. **Do not commit large binaries casually.** Keep images at the resolution the
   presentation actually needs.

## 4. Naming

Until a project naming standard exists — and **none is established**
(BEP §11.12) — assets use a simple descriptive local convention:

```text
<MODULE>-<REF>-<short-description>.<ext>
```

As implemented for Module 1: `M01-S09-cde-states.md` for visual source, and
`M01-S09.svg` for a render of it, should one ever be produced.

This is a **local teaching convention only**. It establishes nothing, proposes
no project standard, and has no relationship to the package-specific naming
control approved for the publication arrangement.

**Identifiers are stable.** `V1`–`V10` in the Module 1 visual plan and
`M01-S01`–`M01-S14` in the visual source set are not renamed or renumbered to
suit a later render, tool or deck.

## 5. Module registers

Each module holds its own visual register rather than a shared list here.

| Module | Register | Source | Rendered |
|---|---|---|---|
| Module 1 | [`module-01/visual-register.md`](module-01/visual-register.md) | 14 slide visuals, `SOURCE COMPLETE` | **None** |
| Module 2 | [`module-02/visual-register.md`](module-02/visual-register.md) | 14 slide visuals — 13 `SOURCE COMPLETE`, 1 `SOURCE PARTIAL` by design | **None** |
| Module 3 | [`module-03/visual-register.md`](module-03/visual-register.md) | 14 slide visuals, 13 concepts, `SOURCE COMPLETE` | **None** |
| Module 4 | [`module-04/visual-register.md`](module-04/visual-register.md) | 14 slide visuals, 14 concepts, all `SOURCE COMPLETE` | **None** |
| Module 5 | [`module-05/visual-register.md`](module-05/visual-register.md) | 14 slide visuals, 14 concepts, all `SOURCE COMPLETE` | **None** |
| Module 6 | [`module-06/visual-register.md`](module-06/visual-register.md) | 14 slide visuals, 14 concepts, all `SOURCE COMPLETE — ACCEPTED after T6-F-R` | **None** |

## 6. Rendering

**No rendering has been performed in this repository.** No Mermaid CLI,
Graphviz, PlantUML or SVG converter is available in the working environment, and
none is installed to obtain one.

Mermaid diagram source is held in fenced ```mermaid blocks inside the Module 1,
2 and 3 source files, which **render natively on GitHub** — so those diagrams are
viewable without local tooling.

**Modules 4, 5 and 6 hold no Mermaid**, and therefore have nothing a renderer
could consume. That is a design decision, not a gap: a renderer that normalises a
broken line into a solid one would complete a blocked route those modules exist
to show as blocked. See
[`module-04/rendered/README.md`](module-04/rendered/README.md) §2,
[`module-05/rendered/README.md`](module-05/rendered/README.md) §2 and
[`module-06/rendered/README.md`](module-06/rendered/README.md) §2.

**Module 5 adds an explicit completion prohibition.** No empty, blocked, broken
or refused element may be completed by a renderer — the broken `TRN-E03` → `T4`
connector, the unpopulated matrix skeleton, the five closed gates, the nine-cell
`D4` row and the five empty Triviron answer areas all stay exactly as
specified.

**Module 6 carries thirteen equivalent prohibitions**, listed in
[`module-06/rendered/README.md`](module-06/rendered/README.md) §3 — among them:
**do not close the Slide 3 route**, **do not reverse Slide 4 connector
direction**, **do not rank Slide 5 outcomes**, **do not fill Slide 6 empty
cells**, **do not add an eighth Slide 8 row**, **do not add a Slide 9 return
connector**, **do not tick Slide 12 boxes**, **do not populate Slide 14 answer
areas**, and **do not replace status words with colour or icons**.

If rendering is undertaken later, the rules are in each module's `rendered/`
README — [Module 1](module-01/rendered/README.md) §3,
[Module 2](module-02/rendered/README.md) §4. The short version: render from
committed source unchanged, name the output after its source identifier, prefer
SVG, update the register — and remember that **a render never becomes the
authority.**

**Module 2 adds one further rule:** a render must **preserve the semantic line
weights**. Solid, dashed and plain lines carry governance meaning there, and
three slides depend on it — an unreached `Published`, two unheld authority links,
and a future-facing final stage. A render that solidifies any of them would
assert an authority the sources decline to assign.
