# Module 1 — Rendered visuals

## No rendered assets exist.

This directory is empty of image files. **Nothing has been rendered**, and
nothing in this repository should be read as implying that rendering occurred.

---

## 1. Why nothing was rendered

Increment T1-D checked for a locally available renderer before committing. The
result:

| Tool | Present |
|---|---|
| `mmdc` (Mermaid CLI) | **No** — not on `PATH`, not in any global `node_modules`, not found on the filesystem |
| `dot` (Graphviz) | **No** |
| `plantuml` | **No** |
| `rsvg-convert` | **No** |
| `inkscape` | **No** |
| `node` / `npx` | Present — but invoking `npx` to fetch Mermaid CLI would **install packages and require network access** |

The increment's boundary permitted rendering **only** with a tool already
present that requires no installation and no network access. No such tool
exists in this environment, so **diagram source was committed without rendered
output**, and that result is reported honestly rather than worked around.

## 2. What exists instead

Text-based visual source, in
[`../source/`](../source/) — fourteen files, `M01-S01` through `M01-S14`.

Every file is:

- human-readable;
- reviewable in a Git diff;
- traceable to its slide and to the repository evidence behind it;
- explicit about whether it represents source fact, supported interpretation or
  teaching synthesis.

Mermaid diagrams are held in fenced ```mermaid blocks, which **render natively on
GitHub** — so the diagrams are already viewable without any local tooling.

## 3. If rendering is undertaken later

Rendering is a separate, bounded activity. When it happens:

| Rule | Reason |
|---|---|
| Render from the committed source, unchanged | The source is the reviewable artefact; a diverging render is an unreviewed change |
| Commit the render **beside** its source identifier — `M01-S09.svg` for `M01-S09` | Keeps the pairing obvious in a directory listing |
| Prefer SVG | Scales to projection without resampling, and diffs as text |
| Update the **Rendered** column in [`../visual-register.md`](../visual-register.md) | The register is the single place that records what exists |
| Do not rename or renumber a source file to suit a render | `V1`–`V10` and `M01-S01`–`M01-S14` are stable identifiers |

**A render never becomes the authority.** If a rendered image and its source
disagree, the source is correct and the render is stale.

## 4. What must never appear in this directory

- Any fabricated or AI-generated image presented as a Harrismith project view,
  model view, CDE view or screenshot.
- Any screenshot of Autodesk Forma, ACC, Desktop Connector, Revit or Navisworks
  obtained outside a separately authorised, bounded, read-only observation.
- Any captured platform image that has not been reviewed and cropped — platform
  views carry filenames, user names, activity history and folder contents that
  should not be projected.
- Any image implying that a proposed workflow is a verified live implementation.

The safety boundary in root [`README.md`](../../../../README.md) section 2.1
applies to this directory without modification: nothing is read from, written to
or copied out of the Autodesk Desktop Connector / ACCDocs tree.

## 5. Current contents

*(none — this README only)*
