# Module 4 — Presentation Assembly Package

**Status:** PowerPoint-production handoff. **Not governance.** **Not the
PowerPoint.**

Everything required to build the fourteen-slide Module 4 deck **without
reopening or reinterpreting the full teaching baseline**.

---

## 1. What this package is

A **handoff**. It carries the deck specification, the on-slide copy, the
presenter cues, the asset manifest and two checklists — enough to build the
presentation, and not enough to change what it claims.

**The PowerPoint is produced externally and is not committed to this
repository.**

## 2. What this package is not

| It is not | Because |
|---|---|
| Governance | Nothing here decides, approves, authorises or amends anything |
| The PowerPoint | No `.pptx` exists, here or anywhere in this repository |
| A rendered asset set | **No SVG, PNG, JPG or PDF exists.** None is required |
| A re-specification of the visuals | `W1`–`W14` and `M04-S01`–`M04-S14` govern; this package carries them forward |
| Evidence of rehearsal | **No delivery has been measured.** Every timing figure is an allocation |
| Evidence of implementation | Explaining a governed process is not evidence that it is running |

## 3. Authority — and it runs one way

```text
Controlled Harrismith sources
  → Module 4 teaching source        (outline · speaker notes · source map)
    → visual-demonstration plan     (W1–W14, authoritative for every visual)
      → M04-S01–M04-S14             (slide-source files)
        → this assembly package
          → external PowerPoint     (derivative; not in this repository)
```

**Each layer implements the one above it and may not override it.** Where this
package and a slide source differ, **the slide source is correct and this
package is the thing to fix.** Where a slide source and the visual plan differ,
**the plan is correct.**

| Layer | Location |
|---|---|
| Controlled sources | [`source-inventory.md`](../source-inventory.md) — `S1`–`S14` with exact paths |
| Statement classification | [`source-map.md`](../source-map.md) — 244 statements, seven registers, 99 prohibited claims |
| Slide content and timing | [`presentation-outline.md`](../presentation-outline.md) |
| What the presenter says | [`speaker-notes.md`](../speaker-notes.md) |
| Visual specifications | [`visual-demonstration-plan.md`](../visual-demonstration-plan.md) — **authoritative for `W1`–`W14`** |
| Slide sources | [`../../assets/module-04/source/`](../../assets/module-04/source/) — `M04-S01`–`M04-S14` |
| Visual register and map | [`../../assets/module-04/visual-register.md`](../../assets/module-04/visual-register.md) · [`../../assets/module-04/slide-visual-map.md`](../../assets/module-04/slide-visual-map.md) |

## 4. Reading order

| # | File | For |
|---|---|---|
| 1 | [`deck-specification.md`](deck-specification.md) | The whole deck — structure, design rules, and all fourteen slide specifications |
| 2 | [`slide-copy.md`](slide-copy.md) | **Visible wording only.** What goes on the slide |
| 3 | [`asset-manifest.md`](asset-manifest.md) | Every visual, its source file, and its **native PowerPoint treatment** |
| 4 | [`presenter-cues.md`](presenter-cues.md) | What the presenter says — cues, not a script |
| 5 | [`production-checklist.md`](production-checklist.md) | Build checks, STOP failures, accessibility |
| 6 | [`review-checklist.md`](review-checklist.md) | Reviewing the first deck, and the automatic fails |

**Read [`deck-specification.md`](deck-specification.md) §3 before building
anything.** It carries the design rules that make the rest of the package
coherent.

## 5. Every visual is rebuilt natively

**No rendered visual exists, and none is required.** All fourteen slide sources
are **Markdown native-layout specifications** — geometry in points, exact
labels, connector semantics.

**Build with native PowerPoint shapes, text boxes, tables, lines, borders and
connectors.** Do not import SVG, PNG, JPG, PDF, a Mermaid rendering, a
screenshot, platform imagery, or an external icon implying folders, archives,
approval or software implementation.

**No visual in Module 4 is Mermaid**, and the deck must not reintroduce one.

## 6. Seventeen things the producer must not do

1. **Treat the platform as the CDE.**
2. **Move a governance status into the speaker notes only.**
3. **Remove an implementation-status label.**
4. **Convert equal cards into a sequence.**
5. **Complete `Shared → Published`.**
6. **Fill the publication-authority field.**
7. **Add `04 Archive`**, in any form.
8. **Turn Record / Retained into a folder.**
9. **Connect technical action to governed transition.**
10. **Convert `T1`–`T8` into an eight-stage journey.**
11. **Omit the `T1` evidence field.**
12. **Merge `T4` and `TRN-E03`.**
13. **Populate a code set or a metadata schema.**
14. **Reverse governance and configuration.**
15. **Answer a Triviron question.**
16. **Import an image or a rendered diagram.**
17. **Claim a measured delivery time.**

## 7. The nine that must not be tidied

**Each looks unfinished. Each is finished.**

*(The visual-demonstration plan's summary ranks **eight** visuals by completion
risk. This production list adds **Slide 8's empty gutter** — the plan places it
outside that ranking because its risk is* conversion *rather than* completion*,
but in production it is a space a producer fills.)*

| Slide | What stays | If it is "fixed" |
|---|---|---|
| 2 | Three `not established` code-set lines | An invented standard enters the project |
| 3 | The `T4` break · the empty authority · the unreachable retention stub | A working publication lifecycle is claimed |
| 6 | The empty publication-authority position | An authority nobody holds is assigned |
| 7 | The empty retention-method panel | A folder decision is made from the front of a room |
| 8 | The empty gutter between the panels | Technical action is shown producing a transition |
| 11 | Two separate panels, both blocked | Four unresolved matters disappear |
| 12 | Four empty `not established` boxes | Four standards are taught that do not exist |
| 13 | The refused reverse arrow, and `Holder: TBD` | The chain becomes readable in both directions |
| 14 | Two unanswered authority questions, and the open end state | The module's single worst failure |

**A producer who removes, fills, shades or completes any of them has changed the
claim — not the styling.**

## 8. Status

| Field | Value |
|---|---|
| Package | **Complete (T4-F)** |
| Slides specified | **14** |
| Allocated duration | **`20.0 minutes allocated — not yet measured`** |
| Rendered assets | **None. None required** |
| PowerPoint | **Does not exist.** Produced externally, not committed here |
| Review | **Outstanding** |
| Rehearsal | **Outstanding.** No complete run has been measured |
| Module 4 | **`CURRENT — ACTIVE`** |
| Publication automation | **PAUSED** |

**This package carries no governance authority.** It is teaching material, and
being referenced from it approves, publishes or issues nothing.
