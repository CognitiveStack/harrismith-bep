# Module 3 — Visual Register

**Status:** Visual-source baseline. **Not governance.** **No rendered assets
exist.**

Controlling document:
[`../../module-03-iso-19650-principles/visual-demonstration-plan.md`](../../module-03-iso-19650-principles/visual-demonstration-plan.md).
Its identifiers `V1`–`V13`, mandatory design requirements, classifications and
risk ratings are **authoritative and are not renumbered here**.

---

## 1. Two identifier spaces — thirteen and fourteen

| Space | Count | Meaning |
|---|---|---|
| **`V1`–`V13`** | **13 visual concepts** | The plan's entries — controlling specifications |
| **`M03-S01`–`M03-S14`** | **14 slide-source files** | One per slide, in [`source/`](source/) |

**The counts differ because `V1` serves two slides.** One concept, two states:
the framework panel on Slide 1 (`M03-S01`), completed with the platform panel on
Slide 2 (`M03-S02`). **Each state has its own source file.**

**`M03-S01`–`M03-S14` is fourteen files, not thirteen.**

## 2. Status definitions

| Status | Meaning |
|---|---|
| **`SOURCE COMPLETE`** | Reviewable text-based source exists and is sufficient to produce the visual |
| **`SOURCE PARTIAL`** | Source exists but an element is deliberately left open |
| **`EXTERNAL EVIDENCE REQUIRED`** | Cannot be produced from registered material |
| **`DEFERRED`** | Recorded, not developed in this increment |
| **`EXCLUDED`** | Deliberately not produced; reason recorded |

**No status implies a rendered image exists.** See
[`rendered/README.md`](rendered/README.md).

---

## 3. Visual concepts — `V1`–`V13`

### 3.1 Identity, slides, sources and status

| `V` | Title | Slides | Source basis | Classification | Jurisdiction | Format | Source path(s) | Status |
|---|---|---|---|---|---|---|---|---|
| `V1` | Framework versus software platform | **1 and 2** | `X1`; `H1` §6.1, §6.8, §6.9, §12.1 | `PUBLIC-SOURCE` + `HARRISMITH` + `INTERP` | International · This project | Mermaid | [`M03-S01`](source/M03-S01-information-management-framework.md) · [`M03-S02`](source/M03-S02-framework-versus-platform.md) | **`SOURCE COMPLETE`** |
| `V2` | Asset-life-cycle ribbon | 4 | `X1`; `H1` §3.3 | `PUBLIC-SOURCE` + `INTERP` + `SYNTH` | International · This project | Mermaid + layout | [`M03-S04`](source/M03-S04-asset-life-cycle-ribbon.md) | **`SOURCE COMPLETE`** |
| `V3` | Part 1 versus Part 2 | 3 | `X1`, `X2`; `X3`, `X4` status | `PUBLIC-SOURCE` + `INTERP` | International | Table + layout | [`M03-S03`](source/M03-S03-part-1-versus-part-2.md) | **`SOURCE COMPLETE`** |
| `V4` | Requirements before production | 5 | `X1`; **`X5`/`X6`**; `H1` §7.1, §7.3, §10.1 | `INTERP` + **`GUIDANCE` — UK** + `HARRISMITH` | International · **UK** · This project | Mermaid | [`M03-S05`](source/M03-S05-requirements-before-production.md) | **`SOURCE COMPLETE`** |
| `V5` | Right information — continuum | 6 | `X1`; `X5`; `H1` §6.1, §7.3; `H2` matrix §4 | `INTERP` + `SYNTH` + `HARRISMITH` | International · **UK** · This project | Layout + table | [`M03-S06`](source/M03-S06-right-information-continuum.md) | **`SOURCE COMPLETE`** |
| `V6` | The vocabulary gap | 8 | **`X6`**; `H1` §4.2, §4.3, §4.6; verified counts | **`GUIDANCE` — UK** + `UNRESOLVED` + `HARRISMITH` | **UK** · This project | Layout + table | [`M03-S08`](source/M03-S08-vocabulary-gap.md) | **`SOURCE COMPLETE`** |
| `V7` | Separately owned containers | 9 | `X1`; `H1` §6.6, §7.2, §7.9, §8.5, §10.4; `H2` §3.1 | `HARRISMITH` + `INTERP` | This project | Mermaid | [`M03-S09`](source/M03-S09-information-containers.md) | **`SOURCE COMPLETE`** |
| `V8` | CDE state and purpose, block visible | 10 | `H1` §6.1, §6.3, §6.9, §7.2, §9.4, §12.1; **`H2` §11** | `HARRISMITH` + `INTERP` | This project | Mermaid | [`M03-S10`](source/M03-S10-cde-states-blocked.md) | **`SOURCE COMPLETE`** |
| `V9` | Planned information delivery | 11 | `X2`; `H1` §10.1, §10.11; **`H2` schedule §5, §7** | `PUBLIC-SOURCE` + `HARRISMITH` + `INTERP` | International · This project | Table + Mermaid | [`M03-S11`](source/M03-S11-planned-delivery.md) | **`SOURCE COMPLETE`** |
| `V10` | The translation chain | 12 | `H1` §1.1, §2.4, §4.7, §12.1, §12.9; `H2` IM matrix §3.7 | `SYNTH` + `HARRISMITH` + `INTERP` | This project | Mermaid + table | [`M03-S12`](source/M03-S12-translation-chain.md) | **`SOURCE COMPLETE`** |
| `V11` | Harrismith mapping, four equal bands | 13 | `H1` §11.2, §13.4; `H2`; `H3`; source-map §5, §9 | `HARRISMITH` (all four sub-categories) + `INTERP` | This project | Layout | [`M03-S13`](source/M03-S13-mapping-four-bands.md) | **`SOURCE COMPLETE`** |
| `V12` | Triviron verification questions | 14 | **None** | **`SYNTH`** — no evidence basis | **None asserted** | Layout | [`M03-S14`](source/M03-S14-triviron-questions.md) | **`SOURCE COMPLETE`** |
| `V13` | Function-to-assignment chain | 7 | **`X6`**; `H1` §4.6, §5.11 | **`GUIDANCE` — UK** + `HARRISMITH` + `INTERP` | **UK** · This project | Mermaid | [`M03-S07`](source/M03-S07-function-to-assignment.md) | **`SOURCE COMPLETE`** |

### 3.2 Risk, dependency and warnings

| `V` | Copyright risk | Overclaim risk | Unresolved dependency | Mandatory warning | Prohibited inference |
|---|---|---|---|---|---|
| `V1` | LOW | **HIGH** | None | Attribute the platform panel aloud — **our BEP's wording, not the standard's** | That the platform panel states ISO requirements |
| `V2` | **MEDIUM** | **HIGH** | No stage vocabulary is available | *"My words, not official phase names"* — and **never number them** | That the six phases are ISO-defined stages |
| `V3` | **MEDIUM-HIGH — highest** | **HIGH** | Neither part has been read | **`Published scope — not a summary of requirements`**, on the slide | That the columns summarise the standards' contents |
| `V4` | **MEDIUM** | **HIGH** | No definition-level source for requirement documents | **No requirement acronym.** Production never precedes requirement | That the sequence is Part 2's process |
| `V5` | LOW | MEDIUM-HIGH | **Level of information need is not defined** on this project | **Say the *too little* half aloud** | That less information is better |
| `V6` | MEDIUM (terms) | **HIGHEST** | **No terminology mapping exists**, and three ISO-associated terms are undefined here | **Rows stay offset. `Terminology mapping not established`** on the slide | That `Lead Delivery Party` is *lead appointed party* |
| `V7` | LOW | MEDIUM-HIGH | No ISO definition of *information container* | **Say *illustrative* aloud.** No state-transition arrow | That the working description is ISO's definition |
| `V8` | **MEDIUM** | **HIGH** | **Publication authority UNRESOLVED**; `T4` has no authorising function | **The broken arrow must not be "fixed."** Record / Retained is not a folder | That the workflow is configured and running |
| `V9` | LOW | **HIGH** | **Recipient and acceptance authority not established**; no real dates | **`Planned — not evidence of delivery`.** Evidence column stays empty | That any delivery has occurred |
| `V10` | LOW | **HIGH** | **`A2` TBD across every function**; implementation evidence incomplete | **`Translation model — not a conformity assessment`** | That completing the chain proves conformity |
| `V11` | LOW | **HIGHEST** | **No conformity assessment exists in either direction** | **Band 1 holds one item and stays near-empty.** `Mapping — not assessment` | That the mapping is a score or a result |
| `V12` | LOW | **HIGH (Triviron)** | **No Triviron project fact exists** | **Questions only.** No answer, no placeholder, no jurisdiction | That any Triviron position is known |
| `V13` | LOW | **HIGH** | The standard's position on titles has not been read | **Do not say ISO requires a BIM Manager — or that it requires none** | That the chain is the standard's assignment process |

**Rendered asset status — every concept: `NONE`.** No image file exists for any
visual in this module.

---

## 4. Slide visual sources — `M03-S01`–`M03-S14`

### 4.1 Identity, format and status

| Slide | `M03` source | `V` | Format | Intended PowerPoint treatment | Status |
|---|---|---|---|---|---|
| 1 | [`M03-S01-information-management-framework.md`](source/M03-S01-information-management-framework.md) | `V1` state 1 | Mermaid + table | Native shapes — four acts, one anchor, two labels | **`SOURCE COMPLETE`** |
| 2 | [`M03-S02-framework-versus-platform.md`](source/M03-S02-framework-versus-platform.md) | `V1` state 2 | Mermaid + table | Native shapes — two panels, one gutter, one dashed connector | **`SOURCE COMPLETE`** |
| 3 | [`M03-S03-part-1-versus-part-2.md`](source/M03-S03-part-1-versus-part-2.md) | `V3` | Table + layout | Native two-column composition, equal widths | **`SOURCE COMPLETE`** |
| 4 | [`M03-S04-asset-life-cycle-ribbon.md`](source/M03-S04-asset-life-cycle-ribbon.md) | `V2` | Mermaid + layout | Native ribbon, continuity band, bracket, struck-through annotation | **`SOURCE COMPLETE`** |
| 5 | [`M03-S05-requirements-before-production.md`](source/M03-S05-requirements-before-production.md) | `V4` | Mermaid | Native left-to-right chain with two annotation callouts | **`SOURCE COMPLETE`** |
| 6 | [`M03-S06-right-information-continuum.md`](source/M03-S06-right-information-continuum.md) | `V5` | Layout + table | Native continuum with a movable band; optional two-column build | **`SOURCE COMPLETE`** |
| 7 | [`M03-S07-function-to-assignment.md`](source/M03-S07-function-to-assignment.md) | `V13` | Mermaid | Native chain, detached job-title label, UK callout | **`SOURCE COMPLETE`** |
| 8 | [`M03-S08-vocabulary-gap.md`](source/M03-S08-vocabulary-gap.md) | `V6` | Layout + table | **Native two-column composition with offset rows** — not a table object | **`SOURCE COMPLETE`** |
| 9 | [`M03-S09-information-containers.md`](source/M03-S09-information-containers.md) | `V7` | Mermaid | Native frame with six unconnected container shapes | **`SOURCE COMPLETE`** |
| 10 | [`M03-S10-cde-states-blocked.md`](source/M03-S10-cde-states-blocked.md) | `V8` | Mermaid | Native chain — **one solid connector, the rest dashed** | **`SOURCE COMPLETE`** |
| 11 | [`M03-S11-planned-delivery.md`](source/M03-S11-planned-delivery.md) | `V9` | Table + Mermaid | Native table with an **empty evidence column**, plus a dashed dependency fragment | **`SOURCE COMPLETE`** |
| 12 | [`M03-S12-translation-chain.md`](source/M03-S12-translation-chain.md) | `V10` | Mermaid + table | Native chain in four bands; assessment shape **outside** the chain | **`SOURCE COMPLETE`** |
| 13 | [`M03-S13-mapping-four-bands.md`](source/M03-S13-mapping-four-bands.md) | `V11` | Layout | **Four identical native bands** — not a table, not a SmartArt list | **`SOURCE COMPLETE`** |
| 14 | [`M03-S14-triviron-questions.md`](source/M03-S14-triviron-questions.md) | `V12` | Layout | Native five-group question list, end state, then takeaways | **`SOURCE COMPLETE`** |

**Fourteen files. All `SOURCE COMPLETE`. None rendered.**

### 4.2 Classification, jurisdiction and warnings

| Slide | Classification | Jurisdiction | Mandatory warning | Rendered |
|---|---|---|---|---|
| 1 | `PUBLIC-SOURCE` + `INTERP` | International | Not the ISO model — published scope, paraphrased. **No platform on this slide** | **None** |
| 2 | `PUBLIC-SOURCE` + `HARRISMITH` + `INTERP` | International · This project | **Attribute the platform panel aloud.** Panels never touch | **None** |
| 3 | `PUBLIC-SOURCE` + `INTERP` | International | **`Published scope — not a summary of requirements`.** No clause, no process list, no third column | **None** |
| 4 | `PUBLIC-SOURCE` + `INTERP` + `SYNTH` + `HARRISMITH` gap | International · This project | **Not a standard stage model. No numbering. No single travelling model** | **None** |
| 5 | `INTERP` + **`GUIDANCE` — UK** + `HARRISMITH` | International · **UK** · This project | **No requirement acronym. Production never first** | **None** |
| 6 | `INTERP` + `SYNTH` + `HARRISMITH` gap | International · **UK** · This project | **Both ends are failures. No green, no tier, no fire-station detail requirement** | **None** |
| 7 | **`GUIDANCE` — UK** + `HARRISMITH` + `INTERP` | **UK** · This project | **No claim that ISO requires — or forbids — a BIM Manager. No hierarchy, no names** | **None** |
| 8 | **`GUIDANCE` — UK** + `UNRESOLVED` + `HARRISMITH` | **UK** · This project | **Offset rows. Labelled gutter. `appointed party` faces empty space. No arrows** | **None** |
| 9 | `PUBLIC-SOURCE` + `HARRISMITH` + `INTERP` | International · This project | **Working description, not a definition. Mixed container types. No transitions** | **None** |
| 10 | `HARRISMITH` + `INTERP` | This project | **The broken arrow must not be "fixed." No `04 Archive`** | **None** |
| 11 | `PUBLIC-SOURCE` + `HARRISMITH` + `INTERP` | International · This project | **`Planned — not evidence of delivery`. Empty evidence column. No dates** | **None** |
| 12 | `SYNTH` + `HARRISMITH` + `INTERP` | This project | **Translation model, not conformity. Evidence stage open. Assessment outside the chain** | **None** |
| 13 | `HARRISMITH` (four sub-categories) + `INTERP` | This project | **Four equal bands. Band 1 holds one item. No colour, no score, no conclusion either way** | **None** |
| 14 | **`SYNTH`** only | **None asserted** | **Questions only. No Triviron fact. Licensed-copy question visible and unanswered** | **None** |

---

## 5. Reconciliation

| Count | Value |
|---|---|
| Visual **concepts** registered | **13** — `V1`–`V13` |
| Slide **source files** created | **14** — `M03-S01`–`M03-S14` |
| Concepts serving more than one slide | **1** — `V1` (Slides 1 and 2) |
| Sources at `SOURCE COMPLETE` | **14 of 14** |
| Sources at `EXTERNAL EVIDENCE REQUIRED` | **0** |
| Sources `DEFERRED` or `EXCLUDED` | **0** |
| **Rendered assets** | **0** |
| External imagery required | **None** |
| Live observation required | **None**, and none authorised |

**Every slide is deliverable from registered source material alone.**

## 6. What this register does not do

- It does **not** supersede the visual-demonstration plan. **The plan is
  authoritative**; a source file that differs from it is the thing to correct.
- It does **not** claim any rendered file exists.
- It does **not** authorise external imagery, a live observation, or any
  Autodesk activity.
- It carries **no governance authority.**
