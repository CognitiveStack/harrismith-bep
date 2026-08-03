# Module 2 — Presentation Assembly Package

**Status:** Production handoff. **Not governance. Not the final presentation.**

---

## 1. What this package is

A concise, traceable specification from which the fourteen-slide Module 2
PowerPoint can be built **without reinterpreting the long-form source**.

Module 2's teaching content and visual source together run to roughly **7,000
lines** across outline, speaker notes, exercises, source map, visual plan,
register, slide map and fourteen visual-source files. That volume is correct for
developing and defending the material. It is the wrong input for a producer
building slides.

This package compresses it to what a producer needs: what goes on each slide,
what the presenter says around it, which visual belongs there, and — for this
module in particular — **what must not be tidied**.

## 2. What this package is not

| It is not | Because |
|---|---|
| A controlled BEP deliverable | It carries **no project governance authority** and decides nothing |
| A replacement for the teaching source | The detailed source remains authoritative; this is a derived view |
| The final PowerPoint | **PowerPoint production follows this increment**, performed by ChatGPT after this package is reviewed and accepted |
| A rehearsal record | **No rehearsal has occurred and no timing has been measured** |
| A publication artefact | Publication automation remains **paused** |

**Where this package and the teaching source differ, the teaching source is
correct** and this package is the thing to fix.

## 3. Relationship to the Module 2 source

```text
Detailed teaching source              →  This package              →  PowerPoint
presentation-outline.md                  deck-specification.md        (not yet built)
speaker-notes.md                         slide-copy.md
visual-demonstration-plan.md             presenter-cues.md
source-map.md                            asset-manifest.md
assets/module-02/source/ (14)            production-checklist.md
assets/module-02/visual-register.md      review-checklist.md
assets/module-02/slide-visual-map.md
```

| Derived from | Into |
|---|---|
| [`../presentation-outline.md`](../presentation-outline.md) | `deck-specification.md`, `slide-copy.md` |
| [`../speaker-notes.md`](../speaker-notes.md) | `presenter-cues.md` |
| [`../source-map.md`](../source-map.md) | Evidence classifications throughout |
| [`../../assets/module-02/`](../../assets/module-02/) | `asset-manifest.md`, all visual references |

Nothing in the teaching or visual source was altered to produce this package.

## 4. Production reading order

| # | File | Use it to |
|---|---|---|
| 1 | [`deck-specification.md`](deck-specification.md) | Understand the whole deck — objective, narrative arc, design approach, and one specification per slide. **Start here** |
| 2 | [`slide-copy.md`](slide-copy.md) | Get the exact words that go **on** each slide. Nothing here is speaker script |
| 3 | [`asset-manifest.md`](asset-manifest.md) | Find each slide's visual source, its treatment, and what must not appear |
| 4 | [`presenter-cues.md`](presenter-cues.md) | Populate the speaker-notes pane. Fragments, not prose |
| 5 | [`production-checklist.md`](production-checklist.md) | Check the deck as it is built |
| 6 | [`review-checklist.md`](review-checklist.md) | Review the first assembled version, before rehearsal |

## 5. Producers must not

This module is about **authority**, and almost every visual convention available
carries an implicit authority claim. Five prohibitions matter more here than in
Module 1:

| Do not | Why |
|---|---|
| **Add authority** | Three authorities are unresolved. Assigning one — even plausibly — manufactures governance that does not exist |
| **Populate TBD role holders** | No holder is established anywhere. A placeholder that looks like a name *is* an invented holder |
| **Complete unresolved links** | Four visuals are deliberately incomplete. Tidying any of them is a content failure, not a style improvement |
| **Turn functional diagrams into hierarchies** | BEP §5.2 disclaims an appointment or organisation chart. If a layout has a top, it is wrong |
| **Replace source-supported wording with generic BIM role descriptions** | The exact terms are the teaching. *Lead Delivery Party*, not *lead appointed party*. *CDE Administration*, not *the BIM admin* |

## 6. What must survive assembly

| # | Must survive |
|---|---|
| 1 | **Exact Harrismith terminology** — Owner / Appointing Party · Lead Delivery Party · BIM Manager · BIM Coordinator · Task-Team Lead · Author · Checker · CDE Administration · Receiving / recipient function |
| 2 | **Function ≠ job title ≠ person** |
| 3 | **Organisation ≠ named role holder** |
| 4 | **Functional governance, not hierarchy** |
| 5 | **BIM Manager duties *and* limitations**, in balance |
| 6 | **BIM Coordinator duties *and* technical boundary** |
| 7 | **Author · Checker · Task-Team Lead separation** |
| 8 | **Responsibility before permission** |
| 9 | **All three unresolved authorities**, visibly unresolved |
| 10 | **Technical approval outside information-management authority** |
| 11 | **No unsupported Triviron fact** |
| 12 | **No claim the framework is operating live** |
| 13 | **The exact 20-minute planned allocation** |

## 7. Current status

| Field | Value |
|---|---|
| Module | Module 2 — BIM Management Roles and Responsibilities — **CURRENT — ACTIVE** |
| Content baseline | **Complete** — Slides 1–14 |
| Visual source | **Complete** — `M02-S01`–`M02-S14` |
| Rendered visual assets | **None** — no renderer available; source renders natively on GitHub |
| Assembly package | **Complete — this increment (T2-E)** |
| **PowerPoint production** | **Next** — performed by ChatGPT after this package is reviewed and accepted |
| **Presentation review** | Outstanding — follows production |
| **Rehearsal and measured timing** | Outstanding |
| Module 1 | Review and rehearsal remain **deferred** |
| Publication automation | **PAUSED** |

**No rehearsal has occurred and no timing has been measured.** The twenty-minute
allocation throughout this package is a *plan*, not an observation.
