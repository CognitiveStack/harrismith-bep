# Teaching Assets

**Status:** Visual **source** is committed for Module 1. **No rendered image
asset exists anywhere in this directory.**

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
└── module-02/     visual source set for Module 2 (14 slide visuals)
```

| Module | Visual source | Rendered assets | External evidence needed |
|---|---|---|---|
| [`module-01/`](module-01/) | **Complete — Slides 1–14** | **None** | 3 optional — `V1`, `V9`, `V10` |
| [`module-02/`](module-02/) | **Complete — Slides 1–14** | **None** | **None** |

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

## 6. Rendering

**No rendering has been performed in this repository.** No Mermaid CLI,
Graphviz, PlantUML or SVG converter is available in the working environment, and
none is installed to obtain one.

Mermaid diagram source is held in fenced ```mermaid blocks inside the source
files, which **render natively on GitHub** — so the diagrams are viewable
without local tooling.

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
