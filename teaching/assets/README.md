# Teaching Assets

**Status:** No assets are committed. This directory holds the rules that apply
when the first one is.

---

## 1. Purpose

`teaching/assets/` is the location for presentation assets supporting the
teaching modules — diagrams, cropped extracts, exported images and prepared
slide graphics.

**It is currently empty by design.** Every visual in
[`../module-01-what-is-a-bep/visual-demonstration-plan.md`](../module-01-what-is-a-bep/visual-demonstration-plan.md)
is a candidate, not a prepared asset.

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

6. **Record provenance.** Every asset gets a row in the register below — what it
   is, where it came from, and any constraint on its use.

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
<module>-<ref>-<short-description>.<ext>
```

Examples: `m01-v1-fire-station-view.png`, `m01-v6-cde-states.svg`.

This is a **local teaching convention only**. It establishes nothing, proposes
no project standard, and has no relationship to the package-specific naming
control approved for the publication arrangement.

## 5. Asset register

| Asset | Module / ref | Source | Constraints on use |
|---|---|---|---|
| *(none)* | | | |
