# Module 1 — Production Checklist

**Status:** To be followed while the PowerPoint is built. **Not governance.**

Work through this as the deck is assembled, not afterwards. Items marked **STOP**
are defects that must be fixed before the deck is shown to anyone.

**This checklist does not cover publication-package generation.** That programme
remains paused and is out of scope.

---

## 1. Structure

- [ ] **Exactly 14 slides**, numbered 1–14 in the specified order
- [ ] **16:9** aspect ratio
- [ ] Slide titles match [`deck-specification.md`](deck-specification.md) §4
      exactly — no paraphrasing
- [ ] Title position, size and case consistent across all fourteen
- [ ] No title wraps to three lines
- [ ] Slide numbering visible and consistent
- [ ] Deck opens on Slide 1 and closes on Slide 14

## 2. Readability

- [ ] Nothing below roughly **18 pt equivalent** at 16:9
- [ ] Every diagram label readable at projection distance
- [ ] **One principal message per slide** — if it needs an "and", it is two slides
- [ ] No more than **five supporting items** on any slide
- [ ] Supporting items generally one line
- [ ] No paragraph-style text blocks
- [ ] Generous margins; no edge-to-edge content

## 3. Visual mapping

- [ ] Every slide carries the primary visual named in
      [`asset-manifest.md`](asset-manifest.md)
- [ ] Diagrams built from the committed source in
      [`../../assets/module-01/source/`](../../assets/module-01/source/), not
      redrawn from memory
- [ ] Arrow semantics preserved: **solid** = progresses to, by decision;
      **plain line** = holds detail for; **dashed** = unreached, unresolved or
      not-yet-real
- [ ] The same shape and weight means the same thing on every slide
- [ ] No gradients, shadows, icon sets, stock photography or product chrome

## 4. Tables and density

- [ ] **No raw responsibility matrix** — Slide 7 shows two rows and four rows
- [ ] **No raw sixteen-field schedule** — Slide 8 shows one row, vertical
- [ ] **No raw sixteen-step coordination process** — Slide 11 shows six stages
- [ ] **No source-map extract** anywhere in the deck
- [ ] No table exceeds five rows or three columns
- [ ] Extracts are captioned as extracts

## 5. Terminology — **STOP items**

- [ ] **STOP** — `Record / Retained` is the fourth CDE state on Slide 9
- [ ] **STOP** — **`Archived` appears nowhere** in the deck
- [ ] **STOP** — **No RACI** in any diagram, legend, label or note
- [ ] *Lead Delivery Party* used; **never** *lead appointed party* or *appointed
      party*
- [ ] The seven-term grammar quoted correctly where shown: Perform · Check ·
      Authorise · Coordinate · Accept · Consult · Inform
- [ ] Container references correct: `ARC-01`, `STR-01`, `MEC-01`, `ELE-01`,
      `PLM-01`, `FIR-01`, `COORD-01`
- [ ] Delivery events correct: `TRN-E01`, `TRN-E02`, `TRN-E03`

## 6. Unresolved matters shown honestly — **STOP items**

- [ ] **STOP** — Slide 8: `TRN-E03` shown **BLOCKED**, with
      `Authority unresolved`
- [ ] **STOP** — Slide 10: `T4` shown **blocked**, `Authority unresolved`;
      **no complete transition chain**
- [ ] Slide 10: `T7` acceptance authority shown unresolved
- [ ] Slide 4: `controlled publication` step drawn as not reached
- [ ] Slide 14: final box outline-only, dashed — no tick, no completion indicator
- [ ] No unresolved matter has been "tidied" into a resolved one

## 7. Evidence and synthesis labels

- [ ] Slide 5 carries a visible `Teaching synthesis` label
- [ ] Slide 11 carries `Not verified as live implementation`
- [ ] Slide 12 carries `Illustrative workflow`
- [ ] Slide 14 carries `Teaching synthesis`
- [ ] Slides 8 and 10 carry `Authority unresolved`
- [ ] Slide 2's teaching statement is footnoted as teaching wording
- [ ] Labels are unobtrusive — **not** a metadata band on every slide

## 8. Prohibited content — **STOP items**

- [ ] **STOP** — **No fabricated, AI-generated or substituted project image**
      presented as Harrismith evidence
- [ ] **STOP** — No diagram styled to resemble an ACC, Forma, Revit or Navisworks
      screenshot
- [ ] **STOP** — **No Triviron project fact** — no requirement, appointment,
      date, programme, team structure, platform choice or scope
- [ ] **STOP** — **No named person, company or signatory.** All role holders are
      TBD
- [ ] **STOP** — **No invented date, milestone, duration, stage or programme.**
      No calendar or Gantt fragment anywhere
- [ ] **No ISO wording presented as an ISO definition.** ISO 19650 principles
      *inform* the approach; no compliance or certification is claimed
- [ ] Slide 12's worked example, if used, carries the source's own limits — no
      geometry, coordinates, Issue identifier, tolerance or named person
- [ ] Slide 13 contains **no publication-planning history** — no conditions,
      prerequisites, hold or naming control

## 9. Agreed process versus observed implementation

- [ ] Slide 9 captioned as the **governed model**, not current platform behaviour
- [ ] Slide 11 states the coordination process is **not evidenced as configured
      or running**
- [ ] Slide 12 states the status model is **not claimed to be configured** in the
      platform
- [ ] Slide 12 makes clear that **issue closure is not design approval**
- [ ] Slide 13 keeps **approved / authorised / implemented / evidenced /
      verified** visibly distinct
- [ ] Slide 10 keeps **permission** and **authority** as separate concepts, with
      the arrow running authority → permission

## 10. Speaker notes and attribution

- [ ] Presenter cues from [`presenter-cues.md`](presenter-cues.md) embedded in
      the notes pane, or supplied alongside
- [ ] Cues remain **fragments**, not prose paragraphs
- [ ] Fallbacks and recovery cues included or supplied
- [ ] Source notes present where a claim is quoted or extracted
- [ ] Source notes legible but unobtrusive — small, low-contrast, bottom of slide
- [ ] **No full file paths** on any slide — use plain-English document names

## 11. Timing

- [ ] Per-slide allocation carried into the notes pane
- [ ] Block totals: Slides 1–2 = 3 min · Slide 3 = 1 · Slides 4–8 = 9 ·
      Slides 9–12 = 4 · Slide 13 = 1.5 · Slide 14 = 1.5
- [ ] **Total = 20.0 minutes**
- [ ] Nothing in the deck describes the timing as measured or rehearsed

## 12. Accessibility and contrast

- [ ] Text-to-background contrast sufficient for a projected room
- [ ] Meaning never carried by colour alone — the solid/dashed distinction must
      survive greyscale
- [ ] Diagram labels are real text, not baked into an image, wherever possible
- [ ] Alt text supplied for any placed image
- [ ] Deck legible if printed in black and white

## 13. Final export review

- [ ] Full pass at presentation scale on the actual display, not a laptop preview
- [ ] Every dashed element still reads as dashed at projection distance
- [ ] No placeholder text, no `TODO`, no lorem ipsum
- [ ] File name and title metadata do not imply an issued or published artefact
- [ ] Deck is understood to be a **teaching artefact with no governance
      authority**
- [ ] **No rehearsal has been performed** — do not record timings as observed

---

## Sign-off

| Check | Status |
|---|---|
| All **STOP** items clear | ☐ |
| Sections 1–13 worked through | ☐ |
| Ready for review against [`review-checklist.md`](review-checklist.md) | ☐ |

**Production complete does not mean rehearsal complete.** Rehearsal follows
review, and neither has occurred.
