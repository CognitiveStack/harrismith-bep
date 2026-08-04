# Module 3 — Visual source set

**Status:** Visual-source baseline complete. **No rendered assets exist.**
**Not governance.**

Text-based, reviewable visual source for all fourteen slides of
**Module 3 — ISO 19650 Information-Management Principles**.

---

## 1. Contents

```text
teaching/assets/module-03/
├── README.md               this file — design principles and conventions
├── visual-register.md      13 visual concepts and 14 slide sources, with status and warnings
├── slide-visual-map.md     Slides 1–14 mapped to their visuals
├── source/                 the slide visual source files (14)
│   ├── M03-S01-information-management-framework.md
│   ├── M03-S02-framework-versus-platform.md
│   ├── M03-S03-part-1-versus-part-2.md
│   ├── M03-S04-asset-life-cycle-ribbon.md
│   ├── M03-S05-requirements-before-production.md
│   ├── M03-S06-right-information-continuum.md
│   ├── M03-S07-function-to-assignment.md
│   ├── M03-S08-vocabulary-gap.md
│   ├── M03-S09-information-containers.md
│   ├── M03-S10-cde-states-blocked.md
│   ├── M03-S11-planned-delivery.md
│   ├── M03-S12-translation-chain.md
│   ├── M03-S13-mapping-four-bands.md
│   └── M03-S14-triviron-questions.md
└── rendered/
    └── README.md           records that nothing has been rendered
```

| Start here | For |
|---|---|
| [`visual-register.md`](visual-register.md) | What exists, its status, evidence and warnings |
| [`slide-visual-map.md`](slide-visual-map.md) | Which visual serves which slide, and what must be omitted |
| [`source/`](source/) | The visual source itself |

## 2. Two identifier spaces — thirteen and fourteen

| Space | Count | Meaning |
|---|---|---|
| **`V1`–`V13`** | **13 visual concepts** | The controlling specifications in the visual-demonstration plan |
| **`M03-S01`–`M03-S14`** | **14 slide-source files** | One per slide, in [`source/`](source/) |

**The counts differ because `V1` serves two slides.** It is one concept in two
states — the framework panel on Slide 1, completed with the platform panel on
Slide 2 — and **each state has its own source file**. Every other concept maps to
exactly one slide.

**`M03-S01`–`M03-S14` is fourteen files, not thirteen.** Describing the source
set as "thirteen files" is an error the register exists to prevent.

## 3. Controlling documents

This set **implements** the visual plan; it does not supersede it. **Where a
source file and the plan differ, the plan is authoritative and the source file is
the thing to correct.**

| Document | Role |
|---|---|
| [`../../module-03-iso-19650-principles/visual-demonstration-plan.md`](../../module-03-iso-19650-principles/visual-demonstration-plan.md) | **Authoritative** for `V1`–`V13`, their mandatory design requirements, classifications and risk ratings |
| [`../../module-03-iso-19650-principles/source-map.md`](../../module-03-iso-19650-principles/source-map.md) | **Authoritative** for statement classification, the Harrismith mapping method and the **52 prohibited claims** |
| [`../../module-03-iso-19650-principles/external-source-register.md`](../../module-03-iso-19650-principles/external-source-register.md) | **Authoritative** for `X1`–`X6`, `H1`–`H3` — what each source supports and what may not be inferred |
| [`../../module-03-iso-19650-principles/presentation-outline.md`](../../module-03-iso-19650-principles/presentation-outline.md) | Slide content and timing |
| [`../../module-03-iso-19650-principles/speaker-notes.md`](../../module-03-iso-19650-principles/speaker-notes.md) | What the speaker supplies that the visual cannot |
| [`../../shared/presentation-principles.md`](../../shared/presentation-principles.md) | The programme's standing presentation rules |

**Existing identifiers are not renumbered.** `V1`–`V13` retain their meanings.

## 4. The copyright rule — standing, and absolute

> **No ISO diagram, table or figure is reproduced, redrawn, adapted or
> reconstructed.**

The prohibition includes:

| Also prohibited |
|---|
| Diagrams **remembered** from previous exposure |
| Diagrams found in search results |
| Third-party reproductions |
| "Simplified" derivatives |
| Renamed copies |
| **Structural reconstructions with changed styling** |

**Two independent reasons, either sufficient.** ISO standards are copyrighted, so
redrawing a figure produces a derivative work — calling it "our version" changes
nothing. And **the standards have not been read for this programme**: a
reconstruction of a figure nobody has looked at is an invention wearing a
citation.

**Every visual here is an original teaching construction** built from public ISO
scope metadata, visibly labelled UK guidance, Harrismith project evidence,
supported interpretation, or labelled teaching synthesis.

## 5. Source-file conventions

Every source file is a `.md` file containing:

1. a **documentation header** — thirteen fields, listed in §5.1;
2. the visual source — a fenced ```mermaid block, a Markdown table, or an
   explicit text layout specification;
3. reading notes, omission guidance, and an overclaim-risk assessment.

**Why `.md` rather than `.mmd`.** The wrapper carries the header in readable
form, keeps the diagram diffable, and renders natively on GitHub.

### 5.1 The required header

| Field | |
|---|---|
| Slide-source identifier | `M03-Snn` |
| Related slide | 1–14 |
| Slide title | As in the outline |
| Related visual concept | `V1`–`V13` |
| Teaching purpose | The one thing the audience takes from it |
| Principal sources | `X1`–`X6`, `H1`–`H3`, or *none* |
| Evidence classification | Per `source-map.md` §1 |
| Jurisdiction | International · United Kingdom · This project · — |
| Known limitation | What the visual cannot show |
| Copyright risk | LOW · MEDIUM · MEDIUM-HIGH |
| Overclaim risk | MEDIUM · HIGH · HIGHEST |
| Mandatory presentation warning | The failure the visual invites |
| Increment | `T3-F` |

**All fourteen headers carry all thirteen fields.**

## 6. Format choice

**Mermaid where it represents the visual accurately; tables and layout
specifications where it would mislead.** No visual is forced into Mermaid.

| Format | Used for | Why |
|---|---|---|
| Mermaid `flowchart` | `S01`, `S02`, `S04`, `S05`, `S07`, `S09`, `S10`, `S11`, `S12` | Flows, blocked routes and container relationships where connections — or their absence — carry meaning |
| Markdown table | `S03`, `S06`, `S08`, `S13`, `S14`, and panels throughout | Comparisons and registers. A diagram would impose relationships that do not exist |
| Text layout spec | `S03`, `S06`, `S08`, `S13`, `S14` | Compositions — columns, continua and bands are arrangements, not graphs |

**Where a table or layout was chosen deliberately over Mermaid:**

| Visual | Reason |
|---|---|
| `S03` | A diagram between Part 1 and Part 2 would assert sequence, derivation or hierarchy. **They are two documents with different scopes, not two stages of anything** |
| `S06` | A continuum is a scale, not a graph. Mermaid would turn two failure directions into a flow |
| `S08` | **Mermaid would align rows and could add edges.** Alignment *is* the assertion this visual exists to refuse |
| `S13` | Four equal bands are a composition. Any graph layout implies progression, and progression here reads as a maturity ladder |
| `S14` | Questions have no relationships to draw. A flow would imply a required order |

## 7. Visual design principles

| # | Principle |
|---|---|
| 1 | **One principal message per visual.** If it needs an "and", split it |
| 2 | **Readable at projection scale.** Fewer nodes and larger type beat completeness |
| 3 | **Restrained professional style.** No gradients, shadows, icon sets or product chrome |
| 4 | **Source class visible wherever ambiguity exists** — an audience must never have to guess whether a panel is ISO's or ours |
| 5 | **Jurisdiction visible on every guidance statement** — `OFFICIAL IMPLEMENTATION GUIDANCE — UK CONTEXT` |
| 6 | **No ISO branding used as decoration**, and no ISO layout copied |
| 7 | **No platform screenshot. No product logo as evidence** |
| 8 | **No green conformity grammar, no scorecard, no maturity ladder** |
| 9 | **Arrows carry semantic meaning** — see §7.1 |
| 10 | **Absent evidence remains absent. Unanswered questions remain unanswered** |
| 11 | **Visual imbalance remains where the evidence is imbalanced** |
| 12 | **No invented completeness**, and no Triviron visual identity |

### 7.1 Line semantics

| Notation | Meaning | Example |
|---|---|---|
| `-->` solid | **Supported progression** — a source establishes it | `M03-S10` `WIP → Shared`, authorised by the Task-Team Lead |
| `-.->`  dashed arrow | **Blocked, unresolved or future** | `M03-S10` `Shared ⇢ Published`; `M03-S12` the evidence stage |
| `---` plain line | Relationship **without** authority, sequence or equivalence | `M03-S09` containers within one frame |
| `-.-` dashed line | Annotation or note attachment | Caption, warning and source-label nodes throughout |
| *(no line)* | **No established relationship** | `M03-S08` — the two vocabularies are never connected |

### 7.2 Where a tidier visual would be a governance failure

**Five visuals are deliberately incomplete, unbalanced or unconnected.
Completing any of them would assert something the evidence does not support.**

| Visual | Drawn how | Why it must stay that way |
|---|---|---|
| `M03-S08` | Rows **offset**, gutter labelled, `appointed party` facing empty space | **Alignment is the assertion.** `lead appointed party` opposite `Lead Delivery Party` commits prohibition 24 with no word spoken |
| `M03-S10` | `Shared ⇢ Published` **broken**; `Published ⇢ Record` unreachable | **T4 has no available authorising function.** A complete route claims a workflow this project cannot operate |
| `M03-S11` | Evidence-status column **empty for every event** | **Nothing has been delivered.** A populated column is a claim of executed delivery |
| `M03-S12` | Evidence stage **open**; conformity assessment **outside the chain** | Implementation evidence is incomplete, and **assessment is a separate act by someone else** |
| `M03-S13` | Band 1 holds **one item** beside a nine-item band 3 | **The imbalance is the finding.** Rebalancing it asserts alignment nobody evidenced |

**If a producer "fixes" any of these five, the fix is reverted.**

## 8. Standing prohibitions

1. **No ISO diagram, table or figure** — reproduced, redrawn, adapted or
   reconstructed, including from memory or from third-party versions.
2. **No clause number, and no ISO definition.** None has been read.
3. **No requirement acronym** — no client-, exchange-, asset- or project-level
   requirement abbreviation.
4. **No formal level-of-information-need definition**, and no geometric /
   alphanumeric / documentation breakdown.
5. **No vocabulary equivalence** between Harrismith and ISO-associated terms.
6. **No conformity or non-conformity claim**, and **no score, percentage,
   maturity level, tick, cross or traffic light** anywhere in the set.
7. **No named person, company, appointment or signatory.** Every Harrismith
   holder is TBD.
8. **No invented date, milestone, programme or recipient.**
9. **No Triviron project fact**, and no Triviron visual identity.
10. **No platform screenshot, fabricated image or product logo used as
    evidence.**
11. **No live Autodesk work.** Root [`../../../README.md`](../../../README.md)
    §2.1 applies unchanged.

## 9. Status

| Field | Value |
|---|---|
| Visual concepts specified | **13 — `V1`–`V13`, all complete** |
| Slide visual source | **Complete for Slides 1–14 — 14 files** |
| Rendered assets | **None** — see [`rendered/README.md`](rendered/README.md) |
| External evidence required | **None** — all fourteen slides are derivable from registered source alone |
| External imagery required | **None**, and counterproductive on `M03-S02`, `M03-S03` and `M03-S12` |
| Live observation required | **None**, and none is authorised |
| Module 3 | **CURRENT — ACTIVE**, not complete |
| Next | **Presentation assembly package** |
| Outstanding | Assembly package, PowerPoint production, review, rehearsal |
| Publication automation | **PAUSED** |
