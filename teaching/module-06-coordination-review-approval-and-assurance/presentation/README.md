# Module 6 — Presentation Assembly Package

**Teaching material. Not governance. Not the PowerPoint.**

**`T6-G` COMPLETE.** **`PACKAGE COMPLETE — PENDING CHATGPT GOVERNANCE REVIEW`.**

> **This package is a compression layer.** It lets an external producer build the
> fourteen-slide Module 6 deck **without reopening the complete teaching
> baseline** — and **without changing what any slide claims**.

---

## 1. Status

| Field | Value |
|---|---|
| Increment | **`T6-G` — COMPLETE** |
| Package status | **`PACKAGE COMPLETE — PENDING CHATGPT GOVERNANCE REVIEW`** |
| Package accepted | **NO.** Not accepted, not approved, not reviewed, not production-tested, not rehearsed, not timing-verified |
| Package files | **Seven** |
| Teaching content | **ACCEPTED** — eight Module 6 teaching files |
| Visual specifications | **`T6-E — ACCEPTED after T6-E-R`** — `M6V-01`–`M6V-14` |
| Visual sources | **`T6-F — ACCEPTED after T6-F-R`** — `M06-S01`–`M06-S14`, eighteen asset files |
| Rendered visual asset | **NONE.** No renderer, converter or dependency installed |
| Module 6 PowerPoint | **NONE.** No `.pptx` is committed to this repository |
| Deck review | **NOT PERFORMED** |
| Rehearsal | **NOT PERFORMED** |
| Measured timing | **NONE** — `20.0 minutes allocated — not measured` |
| Slide advancement | **Presenter controlled; no automatic timing** |
| Complete governed coordination cycle | **NOT DEMONSTRATED.** **`GCR-006` OPEN** |
| `T4` / `TRN-E03` | **BLOCKED** |
| Publication / acceptance authority | **UNRESOLVED** |
| Next increment | **`T6-H` — external PowerPoint production** |
| `T6-H` state | **`NOT STARTED — BLOCKED PENDING T6-G ACCEPTANCE`** |
| Publication automation | **`PAUSED`** |

## 2. What this package is

**A bounded production handoff.** Seven Markdown files from which the external
Module 6 PowerPoint can later be built:

```text
teaching/module-06-coordination-review-approval-and-assurance/presentation/
├── README.md                 this file — status, authority, STOP registers
├── deck-specification.md     global details, arc, design, fourteen slide specifications
├── slide-copy.md             visible slide wording only
├── presenter-cues.md         condensed delivery cues — fragments, not a script
├── asset-manifest.md         one-to-one slide/visual/source map and import restrictions
├── production-checklist.md   the build instrument
└── review-checklist.md       the review instrument and automatic-fail register
```

**It exists so a producer can work without:**

- reopening the complete teaching baseline;
- reinterpreting the source architecture;
- changing what any slide claims;
- inventing missing information;
- hiding unresolved or undemonstrated conditions;
- importing visual assets;
- changing the accepted visual forms.

## 3. What this package is not

**It is not:**

- **governance** — it decides nothing and approves nothing;
- **a new teaching baseline** — it adds no statement, source or claim;
- **a new visual specification** — the accepted plan and sources control;
- **a rendered asset set** — nothing here is an image;
- **a PowerPoint** — no `.pptx` exists or is committed;
- **implementation evidence** — it records no project performance;
- **coordination evidence**;
- **review evidence** — no review has been performed;
- **rehearsal evidence** — no rehearsal has been performed;
- **authority to publish** — publication remains **NOT AUTHORISED**, and
  publication automation remains **`PAUSED`**.

## 4. Authority chain and precedence

```text
controlled Harrismith sources
  ↓
accepted Module 6 teaching content
  ↓
accepted Module 6 visual-demonstration plan
  ↓
accepted Module 6 slide-source files
  ↓
T6-G presentation assembly package          ← this directory
  ↓
future external Module 6 PowerPoint
```

**The order runs downward and never upward.**

**Precedence, in order:**

1. **controlled Harrismith sources;**
2. **accepted teaching content;**
3. **accepted visual-demonstration plan;**
4. **accepted slide-source files;**
5. **this assembly package;**
6. future external PowerPoint.

- **Where the package and a slide-source file differ — the slide source is
  correct, and the package must be corrected.**
- **Where a slide source and the visual plan differ — the visual plan is
  correct.**
- **Where teaching material conflicts with a controlled Harrismith source — the
  controlled source wins.**
- **A later PowerPoint never becomes authoritative merely because it looks
  finished.**

## 5. Authoritative source locations

| Layer | Location |
|---|---|
| Controlled governance | [`../../../bep/Harrismith-Fire-Station-BEP.md`](../../../bep/Harrismith-Fire-Station-BEP.md) §8, §9 |
| Supporting resources | [`../../../supporting/`](../../../supporting/) |
| Module objective and scope | [`../README.md`](../README.md) |
| Slide content | [`../presentation-outline.md`](../presentation-outline.md) |
| Presenter notes — **authoritative over the cues here** | [`../speaker-notes.md`](../speaker-notes.md) |
| Statement classification and registers | [`../source-map.md`](../source-map.md) |
| Exercises | [`../exercises.md`](../exercises.md) |
| Visual specifications | [`../visual-demonstration-plan.md`](../visual-demonstration-plan.md) |
| Visual sources | [`../../assets/module-06/`](../../assets/module-06/) |

## 6. Mapping to the fourteen slide-source files

| Slide | Exact title | Time | Visual | Source |
|---:|---|---:|---|---|
| 1 | Module 6 — from who is responsible to what actually happened | 1.0 | `M6V-01` | [`M06-S01.md`](../../assets/module-06/M06-S01.md) |
| 2 | Nine objects, and the words that collapse them | 1.5 | `M6V-02` | [`M06-S02.md`](../../assets/module-06/M06-S02.md) |
| 3 | The governed coordination cycle — and the evidence gap | 1.5 | `M6V-03` | [`M06-S03.md`](../../assets/module-06/M06-S03.md) |
| 4 | Federation — a lens, not an author | 1.5 | `M6V-04` | [`M06-S04.md`](../../assets/module-06/M06-S04.md) |
| 5 | Inputs and readiness — what may enter a cycle | 1.5 | `M6V-05` | [`M06-S05.md`](../../assets/module-06/M06-S05.md) |
| 6 | Checks are chosen, not exhaustive | 1.5 | `M6V-06` | [`M06-S06.md`](../../assets/module-06/M06-S06.md) |
| 7 | Finding, clash, Issue — and the decision between them | 1.5 | `M6V-07` | [`M06-S07.md`](../../assets/module-06/M06-S07.md) |
| 8 | Triage — seven dispositions, one dangerous word | 1.0 | `M6V-08` | [`M06-S08.md`](../../assets/module-06/M06-S08.md) |
| 9 | Assignment and technical response — who owns the fix | 1.5 | `M6V-09` | [`M06-S09.md`](../../assets/module-06/M06-S09.md) |
| 10 | The Issue status model is not an information state | 1.5 | `M6V-10` | [`M06-S10.md`](../../assets/module-06/M06-S10.md) |
| 11 | Verification — after reshare, against controlled information | 1.5 | `M6V-11` | [`M06-S11.md`](../../assets/module-06/M06-S11.md) |
| 12 | Completion is not zero clashes | 1.5 | `M6V-12` | [`M06-S12.md`](../../assets/module-06/M06-S12.md) |
| 13 | Evidence, escalation, and what a closed Issue does not prove | 1.0 | `M6V-13` | [`M06-S13.md`](../../assets/module-06/M06-S13.md) |
| 14 | What Triviron must decide about coordination | 2.0 | `M6V-14` | [`M06-S14.md`](../../assets/module-06/M06-S14.md) |
| | **Total** | **20.0** | **14** | **14** |

**Strictly one-to-one. No identifier is renamed, renumbered or reused.**

## 7. Reading order

1. [`deck-specification.md`](deck-specification.md)
2. [`slide-copy.md`](slide-copy.md)
3. [`asset-manifest.md`](asset-manifest.md)
4. [`presenter-cues.md`](presenter-cues.md)
5. [`production-checklist.md`](production-checklist.md)
6. [`review-checklist.md`](review-checklist.md)

## 8. Native reconstruction rule

**Every Module 6 visual is a native-layout construction specification. There is
no diagram source to render, and nothing to import.**

Permitted: rectangles · text boxes · simple tables · native warning strips ·
simple labelled connectors · unfilled checklist boxes · deliberately incomplete
grids · native call-outs.

**Prohibited: SmartArt · Mermaid · Graphviz · PlantUML · SVG · PNG · JPG · PDF
import · screenshots · external icons · logos · platform imagery · stock
photography · simulated interfaces · live-evidence capture · automatic diagram
layout or graph routing.**

**`External imagery: NONE REQUIRED × 14`. `Live evidence: NONE REQUIRED × 14`.
`Mermaid PROHIBITED × 14`.**

## 9. The 75 accepted Module 6 STOP conditions

**Accepted module-wide visual-production controls**, carried without
renumbering, merging, weakening or paraphrase from
[`../visual-demonstration-plan.md`](../visual-demonstration-plan.md) §3.

**These are not package inventions.** They were accepted as part of `T6-E` and
`T6-E-R`.

| # | A visual must not… |
|---|---|
| 1 | Imply the **complete governed coordination cycle has been executed** |
| 2 | Close, date, soften or weaken **`GCR-006`** |
| 3 | Convert **`PARTIALLY TRACEABLE`** into implemented, in progress or nearly complete |
| 4 | Convert **platform activity into a valid governed decision** |
| 5 | Convert a **status label into technical evidence** |
| 6 | Collapse **Finding, Clash and Issue** |
| 7 | Turn a finding or clash **automatically** into an Issue |
| 8 | Collapse **Check, Review, Coordinate, Authorise, Accept or Reject** into "approval" |
| 9 | Present **`Accepted condition`** as recipient **`Accept`** |
| 10 | Present **`Accepted condition`** as publication authorisation, technical approval or regulatory acceptance |
| 11 | Transfer **authorship or technical ownership into a federation** |
| 12 | Make the **BIM Coordinator the design author** or the owner of the fix |
| 13 | Represent **`COORD-01`** as automatically jointly authored, or as a formal deliverable |
| 14 | Call the federation a **"single source of truth"** |
| 15 | Treat **uploaded or visible information as ready** |
| 16 | Treat **exclusion from one cycle as absence from the project** |
| 17 | Turn **permission to read into authority to rely** |
| 18 | Present all **twelve proposed checks as mandatory or exhaustive** |
| 19 | Insert **any numeric tolerance**, anywhere |
| 20 | Present a **software default as a project requirement** |
| 21 | Present **zero clashes** as coordination success or completion |
| 22 | Mark any proposed check as **executed, passed or failed** |
| 23 | Show **fewer or more than seven triage dispositions** |
| 24 | **Rename or merge** a triage disposition |
| 25 | Merge a **triage disposition with an Issue status** |
| 26 | Invent an **Issue identifier, due date, target, priority, person or organisation** |
| 27 | Transfer **technical authorship through assignment** |
| 28 | Show **`Deferred` and `Escalated` as seventh and eighth sequential status stages** |
| 29 | Change the **six-status order** |
| 30 | Present the status model as **configured in Forma, ACC or another platform** |
| 31 | Treat an **Issue status** as an information state, suitability code, acceptance or publication authority |
| 32 | Treat **`Ready for Verification` as verified** |
| 33 | Treat **`Closed`** as proof of correction, verification, approval, publication, acceptance, certification or compliance |
| 34 | Treat a **WIP response as verification** |
| 35 | Present **verification as mandatory in every cycle** |
| 36 | Resolve the **`H18` variance** |
| 37 | Present any of the **nine completion conditions as performed** |
| 38 | **Tick a completion box** |
| 39 | Convert the nine completion conditions into an **unconditional universal checklist** |
| 40 | Present **every evidence output as produced** |
| 41 | Duplicate the **Issue database in a second report** |
| 42 | Present **escalation as resolving a matter or creating authority** |
| 43 | Fill an **unknown decision owner with a plausible role** |
| 44 | Invent an **assurance-sampling population, size, frequency, method, threshold or report form** |
| 45 | Present **`A1`–`A5` as an assurance-sampling procedure** |
| 46 | Present **assurance as certification, guarantee or regulatory proof** |
| 47 | **Answer a Slide 14 Triviron question** |
| 48 | Transfer a Harrismith **role, check, tolerance, taxonomy, status model or platform decision** to Triviron |
| 49 | Release **`T4`** |
| 50 | Unblock **`TRN-E03`** |
| 51 | Resolve **publication or recipient-acceptance authority** |
| 52 | Convert a **role into a person or organisation** |
| 53 | Rely on **colour alone** |
| 54 | Import **external imagery or a screenshot** |
| 55 | Imply the **specification baseline is a visual source, asset, package or produced PowerPoint** |
| 56 | Imply an **exercise or a specification records project performance** |
| 57 | Create **automatic slide-transition timing** |
| 58 | Present a **clash or finding as a proven design error or fault** — claim 3 |
| 59 | Present **six discipline domains as six organisations, six platform teams or six appointments** — claim 14 |
| 60 | Present a **platform-native label as overriding, replacing or ranking above the governed meaning** — claims 30, 61 |
| 61 | Convert **absence of observation into observation of absence** — draw any discipline, container or activity as missing, inactive or behind — claim 34, `H13` |
| 62 | Show **checking as automatically authorising sharing**, or **authorisation to share as authorisation to publish or exchange** — claims 16, 17 |
| 63 | Show **verification, acceptance or closure transferring technical or design responsibility away from the originating task team** — claims 22, 29 |
| 64 | Show a **verbal agreement, meeting or discussion modifying controlled information** — claim 57 |
| 65 | Show the **federated coordination view being edited** to implement a fix — claim 58 |
| 66 | Show **`COORD-01` replacing, superseding or standing in for** the six discipline containers — claim 12 |
| 67 | Draw the **observed implementation fragments as connected stages of one run**, or as progress toward a cycle — claim 33 |
| 68 | Present the **seven Issue types as Autodesk system-native labels** or platform-provided objects — claim 7 |
| 69 | **Harmonise a recorded terminology variance** — the two cycle-step wordings (variance 1) or the two Issue scopes (variance 3) |
| 70 | Use a **coloured chip, badge, dot or traffic light in place of a status word** |
| 71 | Place a **tick, percentage, progress bar, score or completion mark** against any Module 6 list, grid, output or condition |
| 72 | Name a **holder, organisation or appointment** for any coordination, checking, reviewing, authorising, accepting or assurance function — claim 20, `H14` |
| 73 | **Add, merge, rename or reorder a Slide 14 question group**, or reduce the seven answer areas |
| 74 | Present Module 6 teaching material as **governance**, or as changing Harrismith governance — standing prohibition **C** |
| 75 | Imply a Module 6 visual has been **reviewed, rehearsed, produced or timed** — claim 93, standing prohibition **D** |

## 10. Package-level production additions

**These are production-stage additions.** **They are not new teaching claims, and
they are not additions to the accepted 75.** They exist because compression into
a deck creates risks the visual specifications did not have to anticipate.

**Forty package-level additions. The count emerged from complete coverage of the
fourteen slides and the deck-wide risks. No count was targeted, and no condition
was merged merely to produce a smaller number.**

| # | A producer must not… | Slide |
|---:|---|---|
| 1 | Reduce the full-width status strip to a footnote, footer or caption | 1 |
| 2 | Merge the two source vocabularies, or use nine identical cards | 2 |
| 3 | Connect the governed route to the implementation-evidence panel | 3 |
| 4 | Close the governed route into a loop | 3 |
| 5 | Reverse any `assembled from` connector | 4 |
| 6 | Give the federation an author | 4 |
| 7 | Make the two outcomes unequal | 5 |
| 8 | Fill an intentionally empty interface cell | 6 |
| 9 | Introduce a numeric project criterion | 6 |
| 10 | Turn the finding decision into an automatic Issue conveyor | 7 |
| 11 | Add an eighth disposition | 8 |
| 12 | Style `Accepted condition` as a recommendation | 8 |
| 13 | Add any return connector | 9 |
| 14 | Abbreviate either qualifying phrase | 9 |
| 15 | Place `Deferred` or `Escalated` on the six-status sequence | 10 |
| 16 | Remove `where required` | 11 |
| 17 | Hide or resolve `H18` | 11 |
| 18 | Tick a completion box | 12 |
| 19 | Reduce condition 8's visual weight | 12 |
| 20 | Mark an output as produced | 13 |
| 21 | Make the assurance warning weaker than the three upper blocks | 13 |
| 22 | Populate an answer area | 14 |
| 23 | Draw a Harrismith-to-Triviron transfer arrow | 14 |
| 24 | Move a load-bearing status into presenter notes | all |
| 25 | Claim measured timing or automatic progression | all |
| 26 | Import or render a graphic | all |
| 27 | Omit either source heading, so the two vocabularies lose their attribution | 2 |
| 28 | Summarise the evidence panel into a count instead of its bounded records | 3 |
| 29 | Move the exclusion warning outside the excluded exit's visual group | 5 |
| 30 | Relegate `PROPOSED` and `TBD` to a legend instead of every marked cell | 6 |
| 31 | Style either Issue scope as preferred | 7 |
| 32 | Add a platform-native label column | 10 |
| 33 | Enlarge the `H18` warning into a fourth finding, or shrink it below legibility | 11 |
| 34 | Move the four global qualifiers below the list | 12 |
| 35 | Omit the `does cover` heading, so the ten limits read as an indictment | 13 |
| 36 | Resize a question block, or fill the deliberately empty grid position | 14 |
| 37 | Drop a screen-reader description or an explicit reading order | all |
| 38 | Rebuild a native layout as SmartArt "for tidiness" | all |
| 39 | Change a slide title, its allocated time, or the slide order | all |
| 40 | Treat this package as the deck, or as evidence of review or rehearsal | all |

## 11. Elements that must not be "tidied"

**Every row below is deliberate.** The right-hand column records **the false
claim that "fixing" it would introduce**.

| Slide | Deliberate condition that must survive | The false claim a "fix" would introduce |
|---:|---|---|
| 1 | **Full-width status strip as a principal object** | That the governed route has been demonstrated, and that `GCR-006` is a formality |
| 2 | **Two visibly separate vocabulary domains** | That the six decision acts and the three coordination objects are one vocabulary from one source, with one status |
| 3 | **Open route, unconnected evidence panel and visible gap** | That the cycle turns, that the observed fragments are stages of one run, and that the environment evidences execution |
| 4 | **Upward-only connectors and unauthored federation** | That ownership flows into the federation, and that someone authored the federated view |
| 5 | **Two geometrically identical outcomes** | That exclusion is a failure rather than a governed outcome |
| 6 | **Incomplete grid with visible empty cells** | That the twelve checks are exhaustive, that the unbuilt pairs were overlooked, and that the marked pairs have been run |
| 7 | **Two equal outcomes after one decision point** | That every finding becomes an Issue, and that detection alone creates a governed record |
| 8 | **Exactly seven rows and a caution — not a highlighted recommendation** | That an eighth disposition exists, and that `Accepted condition` is acceptance, approval or authorisation |
| 9 | **Exactly one downward connector and no return** | That assignment transfers authorship, and that technical ownership returns to coordination |
| 10 | **Two alternate dispositions detached from the six-stage sequence** | That the model has eight mandatory stages, and that it is configured in a platform |
| 11 | **Conditional verification gate and near-misses outside it** | That verification is mandatory in every cycle — resolving `H18`, which the sources leave `NOT ESTABLISHED` |
| 12 | **Nine empty boxes and equal condition weighting** | That the conditions were performed, that the list is an unconditional universal checklist, and that carrying a matter forward is concealment |
| 13 | **No output marked produced and a heavier assurance-absence strip** | That the evidence outputs exist, and that an assurance-sampling method is established |
| 14 | **Seven unanswered areas and no transfer connector** | That Module 6 has answered Triviron's questions, and that Harrismith's arrangements transfer automatically |

## 12. Timing and slide progression

| Field | Position |
|---|---|
| Allocated duration | **20.0 minutes** |
| Measured duration | **NONE** |
| Timing status | **`20.0 minutes allocated — not measured`** |
| Section totals | **A 2.5 · B 3.0 · C 5.5 · D 6.0 · E 3.0 = 20.0** |
| Slide progression | **Presenter controlled.** **No automatic slide-transition timing exists or may be created** |
| Rehearsal | **`NOT PERFORMED`** — `E91` defines a full run and records no result |

**The per-slide times are pacing allocations, never measured results.**

## 13. Package validation

| Check | Result |
|---|---|
| Package files | **Seven** |
| Slides covered in every applicable file | **14** |
| Title sequence | **Exact and unaltered** |
| Timing total | **20.0**; section totals reconcile |
| Deck slide specifications | **14, each with all 22 fields** |
| Slide copy | **Visible wording only**; 53 mandatory strings registered |
| Presenter cues | **Fragments, not a script**; accepted closings and Module 7 bridge retained verbatim |
| Asset manifest | **14 one-to-one entries**; **14 unique group names**; import and screenshot **`NO` × 14** |
| Production checklist | **All fourteen slides**; **no box ticked** |
| Review checklist | **All fourteen slides**; **56 automatic fails** |
| Accepted STOP conditions | **75, carried without renumbering, merging, weakening or paraphrase** |
| Package-level additions | **40, separately numbered** |
| External imagery | **`NONE REQUIRED × 14`** |
| Live evidence | **`NONE REQUIRED × 14`** |
| Mermaid | **`PROHIBITED × 14`** |
| Rendered visual asset | **NONE** |
| Renderer, converter or dependency | **None installed** |
| Binary, image, PDF or Office file | **None in this package** |
| Module 6 PowerPoint | **NONE.** No `.pptx` committed |
| Deck review / rehearsal / measured timing | **None performed** |
| Module 6 teaching-file count | **8** — **this package is not a teaching-baseline file** |
| Module 6 asset-set count | **18** |
| Package file count | **7** |

## 14. Residual production work

**The teaching, specification, source and package baselines are complete.
Production is not, and the package is not yet accepted.**

- **ChatGPT governance review of `T6-G` — required before `T6-H` may begin.**
- **No rendered visual asset exists**, and **no renderer or dependency is
  installed**.
- **No Module 6 PowerPoint exists**, and **no `.pptx` is committed to this
  repository**. Earlier-module PowerPoints are **external derivative outputs**,
  produced outside this repository and **outside this increment**.
- **No deck review has been performed.**
- **No rehearsal has been performed**, and **timing has never been measured**.

## 15. Next increment

**`T6-H` — external PowerPoint production.**

## 16. `T6-H` state

**`NOT STARTED — BLOCKED PENDING T6-G ACCEPTANCE`.**

**Nothing in this package authorises a deck, a render, a review or a rehearsal.**
