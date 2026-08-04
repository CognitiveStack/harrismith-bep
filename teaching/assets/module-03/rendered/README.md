# Module 3 — Rendered visuals

## No rendered assets exist.

This directory contains no image files. **Nothing has been rendered**, and
nothing in this repository should be read as implying that rendering occurred.

---

## 1. Why nothing was rendered

Increment T3-F checked for a locally available renderer before committing.

| Tool | Present | Suitable |
|---|---|---|
| `mmdc` (Mermaid CLI) | **No** | — |
| `dot` (Graphviz) | **No** | — |
| `plantuml` | **No** | — |
| `rsvg-convert` | **No** | — |
| `inkscape` | **No** | — |
| `convert` (ImageMagick) | Yes | **No** — a raster/format converter, not a diagram renderer. It cannot interpret Mermaid source |
| `node` / `npx` | Yes | **No** — invoking `npx` to fetch Mermaid CLI would install packages and require network access |
| `python3` | Yes | **No** — the `graphviz` module is not installed, and installing it is prohibited |

The increment permitted rendering **only** with a tool already present that
requires no installation and no network access. **No such tool exists in this
environment**, so diagram source was committed without rendered output, and that
result is reported plainly rather than worked around.

**This matches the position recorded for Modules 1 and 2.** No renderer has been
available at any point in the programme.

## 2. What exists instead

Text-based visual source in [`../source/`](../source/) — **fourteen files**,
`M03-S01` through `M03-S14`.

Every file is:

- human-readable;
- reviewable in a Git diff;
- traceable to its slide, to its `V1`–`V13` concept, and to the registered
  sources behind it;
- explicit about evidence classification, jurisdiction, known limitations,
  copyright risk, overclaim risk and the mandatory presentation warning;
- suitable for later reconstruction as **native PowerPoint shapes**.

## 3. Rendered output would be derivative, not authoritative

**If rendering is undertaken later, the rendered file is a derivative of the
source — not a replacement for it.**

| Authoritative | Derivative |
|---|---|
| [`../../../module-03-iso-19650-principles/visual-demonstration-plan.md`](../../../module-03-iso-19650-principles/visual-demonstration-plan.md) — `V1`–`V13`, their mandatory design requirements and risk ratings | Any rendered image |
| [`../source/`](../source/) — the slide visual source | Any rendered image |

**Where a rendered image and its source differ, the source is correct and the
image is the thing to re-render.**

## 4. Five renderings that must not be "improved"

**Five visuals in this module are deliberately incomplete, unbalanced or
unconnected.** A renderer, a designer or a slide template may try to tidy them.
**Each fix asserts something the evidence does not support, and each is
reverted.**

| Source | Drawn how | What a "fix" would claim |
|---|---|---|
| `M03-S08` | Rows **offset**; `appointed party` faces empty space | That `Lead Delivery Party` is *lead appointed party* — prohibition 24 |
| `M03-S10` | `Shared ⇢ Published` **broken** | That a workflow operates which **has no authorising function** |
| `M03-S11` | Evidence column **empty** | That something was delivered. **Nothing has been** |
| `M03-S12` | Evidence stage **open**; assessment **outside** the chain | That the chain leads to conformity |
| `M03-S13` | Band 1 holds **one item** beside a nine-item band 3 | That alignment is broader than one declaration of influence |

## 5. If rendering is undertaken later

1. **Check the tool is already installed.** Do not install a renderer, a Node
   package, browser automation, a diagram application, fonts or SVG tools.
2. **Render from the committed source**, not from a re-typed version.
3. **Inspect every output** against its source file's mandatory design
   requirements — particularly the five above.
4. **Preserve line semantics.** Solid means supported progression; dashed means
   blocked, unresolved or future; a plain line means a relationship without
   authority; **no line means no established relationship**.
5. **Record what was rendered, with what tool, and when** — in this file.
6. **Do not delete the source.** The source remains authoritative.

## 6. Status

| Field | Value |
|---|---|
| Rendered assets | **None** |
| Visual source | **Complete — 14 files**, [`../source/`](../source/) |
| Renderer available | **None** |
| External imagery required | **None** |
| Increment | `T3-F` |
