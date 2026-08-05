# Module 4 — Rendered visuals

## No rendered assets exist.

This directory contains no image files. **Nothing has been rendered**, and
nothing in this repository should be read as implying that rendering occurred.

---

## 1. The position, stated plainly

| Question | Answer |
|---|---|
| Does any rendered asset exist? | **No.** No SVG, PNG, JPG, PDF or PowerPoint file |
| Was rendering attempted? | **No** |
| Was a renderer installed? | **No** |
| Was a network rendering service used? | **No** |
| What form is the visual source in? | **Markdown native-layout specifications**, in [`../source/`](../source/) |
| Is any of it Mermaid? | **No.** **No visual in Module 4 is Mermaid** |

**Increment T4-E-B produced fourteen slide-source files and no images.** That is
the intended result, not a shortfall — **the specification is the deliverable at
this stage**, and the assembly package is a later increment.

## 2. Why Module 4 has nothing to render

**Modules 1 to 3 hold Mermaid source**, which renders natively on GitHub and
could in principle be converted by a renderer. **Module 4 holds none.**

Every Module 4 visual is a **native-layout specification** — geometry in points,
exact labels, connector semantics, and elements that are deliberately empty,
broken or refused. **There is no diagram-source language to run through a
renderer**, because a renderer is precisely what these visuals were specified to
avoid:

| Risk | Affected visuals |
|---|---|
| Auto-completing a blocked route | `W3`, `W9`, `W11` |
| Drawing a refused edge as a real edge | `W13` |
| Arranging non-sequential items as a sequence | `W2`, `W12` |
| Choosing the layout direction when the order is the content | `W1` |
| Normalising side labels into the chain | `W10` |
| Rendering an outbound edge that must not be drawn | `W4` |

**A renderer that normalises a broken line into a solid one commits the module's
central error.**

## 3. How the PowerPoint will be built

**With native PowerPoint shapes, tables and text boxes.** Not by importing an
image.

Each source file in [`../source/`](../source/) carries a
**Native PowerPoint reconstruction notes** section giving the shape-by-shape
build, the numeric geometry, and the checks to repeat after any theme change.

**The recurring checks are three:**

1. **Arrowheads are explicit.** PowerPoint's default connector has none, and some
   themes apply an arrow style to all connectors. `W3`'s third connector **must
   remain headless**; `W13`'s refused reverse **must keep its break visible**.
2. **Equal things stay numerically equal.** Panels, cards and bands that are
   peers are set by coordinate, not by eye.
3. **Nothing empty is filled.** Theme fills, autofit and "clean up" actions all
   tend to close the gaps this module depends on.

## 4. If rendering is undertaken later

**It has not been authorised, and this file does not authorise it.** If a future
increment does authorise it:

1. **Render from committed source, unchanged.** A render that differs from its
   source is a new claim, not a new format.
2. **Name the output after its source identifier** — `M04-S03.svg` for
   [`../source/M04-S03-four-state-model.md`](../source/M04-S03-four-state-model.md).
   **Identifiers are stable** and are not renumbered to suit a tool.
3. **Prefer SVG.** Raster output loses the line-weight distinctions three visuals
   depend on.
4. **Update [`../visual-register.md`](../visual-register.md)** — the rendered
   status moves from `NONE` only for the visual actually rendered.
5. **A render must not normalise blocked, empty or unequal content.** This is the
   binding rule for Module 4, and it is stricter than the equivalent rule for
   Modules 1 to 3:
   - **solid, broken and open-stub connectors carry different meanings** and must
     survive the render distinguishably;
   - **empty positions stay empty** — not filled, not shaded, not hatched, not
     removed;
   - **panels and cards specified as equal stay equal**;
   - **no element acquires a colour that carries meaning**, and neither red nor
     green is introduced.
6. **A render never becomes the authority.** The Markdown source remains
   authoritative, and the visual-demonstration plan remains authoritative over
   that.

**A rendered file that has been tidied is not a rendering of this source.** It is
a different visual making different claims, and the register should not record it
as the same thing.

## 5. Safety boundary

Root [`README.md`](../../../../README.md) §2.1 applies without modification. **No
rendering activity may read from, write to or change anything in the Autodesk
Desktop Connector / ACCDocs tree**, and **no live Autodesk observation is
authorised** for the purpose of producing or checking an asset.
