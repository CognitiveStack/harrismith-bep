# Module 1 — Presentation Assembly Package

**Status:** Production handoff. **Not governance. Not the final presentation.**

---

## 1. What this package is

A concise, traceable specification from which a 14-slide presentation can be
built **without reinterpreting the long-form teaching source**.

The teaching source for Module 1 runs to roughly 6,500 lines across outline,
speaker notes, exercises, source map, visual plan and fourteen visual-source
files. That volume is correct for developing and defending the material. It is
the wrong input for a producer building slides.

This package compresses it to what a producer actually needs: what goes on each
slide, what the presenter says around it, which visual belongs there, and what
must not be got wrong.

## 2. What this package is not

| It is not | Because |
|---|---|
| A controlled BEP deliverable | It carries **no governance authority** and decides nothing |
| A replacement for the teaching source | The detailed source remains authoritative; this is a derived view |
| The final PowerPoint | No binary presentation exists, and none is produced from this repository |
| A rehearsal record | **Rehearsal remains deferred** until an assembled deck exists |
| A publication artefact | Publication automation remains **paused** |

**Where this package and the teaching source differ, the teaching source is
correct** and this package is the thing to fix.

## 3. Relationship to the teaching source

```text
Detailed teaching source            →   This package            →   PowerPoint
presentation-outline.md                 deck-specification.md       (not yet built)
speaker-notes.md                        slide-copy.md
visual-demonstration-plan.md            presenter-cues.md
source-map.md                           asset-manifest.md
assets/module-01/source/ (14)           production-checklist.md
                                        review-checklist.md
```

| Derived from | Into |
|---|---|
| [`../presentation-outline.md`](../presentation-outline.md) | `deck-specification.md`, `slide-copy.md` |
| [`../speaker-notes.md`](../speaker-notes.md) | `presenter-cues.md` |
| [`../visual-demonstration-plan.md`](../visual-demonstration-plan.md) | `asset-manifest.md` |
| [`../source-map.md`](../source-map.md) | Evidence classifications throughout |
| [`../../assets/module-01/`](../../assets/module-01/) | `asset-manifest.md`, diagram references |

Nothing in the teaching source was altered to produce this package.

## 4. How a producer should use the six files

Read them in this order.

| # | File | Use it to |
|---|---|---|
| 1 | [`deck-specification.md`](deck-specification.md) | Understand the whole deck — objective, narrative arc, design approach, and a one-row specification per slide. **Start here.** |
| 2 | [`slide-copy.md`](slide-copy.md) | Get the exact words that go **on** each slide. Nothing here is speaker script |
| 3 | [`asset-manifest.md`](asset-manifest.md) | Find the visual for each slide, its source file, and what must not appear |
| 4 | [`presenter-cues.md`](presenter-cues.md) | Populate the speaker-notes pane. Fragments, not prose |
| 5 | [`production-checklist.md`](production-checklist.md) | Check the deck as it is built |
| 6 | [`review-checklist.md`](review-checklist.md) | Review the first assembled version, before rehearsal |

**Two rules for the producer:**

- **Do not add content that is not in this package.** If a slide feels thin, it
  is probably correct — the density limits are deliberate and are recorded in
  `deck-specification.md` §3.
- **Do not resolve anything marked unresolved.** Several slides show blocked or
  undecided matters on purpose. Completing them would misrepresent the source.

## 5. What must survive assembly

These are the things a compression pass most easily loses. Each is checked in
`production-checklist.md`.

| # | Must survive |
|---|---|
| 1 | **Harrismith terminology** — *Lead Delivery Party*, *Record / Retained*, the seven-term responsibility grammar. Never *Archived*, never RACI |
| 2 | **Unresolved matters shown honestly** — publication authority, acceptance authority, blocked transitions |
| 3 | **Teaching-synthesis labels** where a misreading is likely — Slides 5, 11, 12, 14 |
| 4 | **Agreed process ≠ observed implementation** — Slides 11, 12, 13 |
| 5 | **No invented fact** — no named holder, no date, no milestone, no Triviron claim, no fabricated image |
| 6 | **The 20-minute structure** — four blocks, exactly twenty minutes |

## 6. Current status

| Field | Value |
|---|---|
| Module | Module 1 — What is a BIM Execution Plan? — **CURRENT — ACTIVE** |
| Content baseline | **Complete** — Slides 1–14 |
| Visual source | **Complete** — `M01-S01`–`M01-S14` |
| Rendered visual assets | **None** — no renderer available; source renders natively on GitHub |
| Assembly package | **Complete — this increment (T1-E)** |
| **PowerPoint production** | **Outstanding** |
| **Presentation review** | **Outstanding** |
| **Rehearsal and measured timing** | **Outstanding — deliberately deferred until a deck exists** |
| Publication automation | **PAUSED** |

**No rehearsal has occurred and no timing has been measured.** The twenty-minute
allocation throughout this package is a *plan*, not an observation.
