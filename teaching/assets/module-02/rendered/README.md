# Module 2 — Rendered visuals

## No rendered assets exist.

This directory contains no image files. **Nothing has been rendered**, and
nothing in this repository should be read as implying that rendering occurred.

---

## 1. Why nothing was rendered

Increment T2-D checked for a locally available renderer before committing.

| Tool | Present | Suitable |
|---|---|---|
| `mmdc` (Mermaid CLI) | **No** | — |
| `dot` (Graphviz) | **No** | — |
| `plantuml` | **No** | — |
| `rsvg-convert` | **No** | — |
| `inkscape` | **No** | — |
| `convert` (ImageMagick) | Yes | **No** — a raster/format converter, not a diagram renderer. It cannot interpret Mermaid or DOT source |
| `node` / `npx` | Yes | **No** — invoking `npx` to fetch Mermaid CLI would install packages and require network access |

The increment permitted rendering **only** with a tool already present that
requires no installation and no network access. **No such tool exists in this
environment**, so diagram source was committed without rendered output, and that
result is reported plainly rather than worked around.

## 2. What exists instead

Text-based visual source in [`../source/`](../source/) — fourteen files,
`M02-S01` through `M02-S14`.

Every file is:

- human-readable;
- reviewable in a Git diff;
- traceable to its slide and to the repository evidence behind it;
- explicit about evidence classification, known limitations and the mandatory
  presentation warning;
- suitable for later native reconstruction in a presentation tool.

**Mermaid diagrams are held in fenced ```mermaid blocks, which GitHub displays
natively** — so the diagrams are viewable today without any local tooling.

## 3. Rendered output is derivative, not authoritative

**The committed source is the authority.** A render is a derived artefact.

If a render and its source ever disagree, **the source is correct and the render
is stale**. A render never becomes the reference, is never edited in place, and
never supersedes the file it came from.

## 4. If rendering is undertaken later

| Rule | Reason |
|---|---|
| Render from the committed source, unchanged | The source is the reviewable artefact; a diverging render is an unreviewed change |
| Name the output after its source identifier — `M02-S09.svg` for `M02-S09` | Keeps the pairing obvious in a directory listing |
| Prefer SVG | Scales to projection without resampling, and diffs as text |
| Update the **Rendered** column in [`../visual-register.md`](../visual-register.md) | The register is the single place recording what exists |
| Do not rename or renumber a source file to suit a render | `R1`–`R11` and `M02-S01`–`M02-S14` are stable identifiers |
| **Preserve the semantic line weights** | Solid, dashed and plain lines carry meaning in this module — a render that flattens them changes the governance content |

The last rule matters more here than in Module 1. **Dashed means unresolved,
blocked, future or not-yet-real**, and three slides depend on it: `M02-S09`'s
unreached `Published`, `M02-S11`'s two unheld links, and `M02-S14`'s
future-facing final stage. A render that solidifies any of them would assert an
authority the sources decline to assign.

## 5. What must never appear in this directory

- Any fabricated or AI-generated image presented as project evidence.
- Any screenshot of Autodesk Forma, ACC, Desktop Connector, Revit or Navisworks
  — and for Slides 7 and 10 specifically, such an image would contradict the
  slide's own argument.
- Any captured platform image that has not been reviewed and cropped.
- Any image implying that a proposed workflow is configured, running or
  verified.
- Any named person or organisation.

The safety boundary in root [`README.md`](../../../../README.md) §2.1 applies to
this directory without modification: nothing is read from, written to or copied
out of the Autodesk Desktop Connector / ACCDocs tree.

## 6. Current contents

*(none — this README only)*
