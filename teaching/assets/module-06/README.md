# Module 6 — Visual Source Set

**Status:** Teaching material. **Not governance.** This set explains and
specifies; it decides nothing, approves nothing and changes no Harrismith
governance.

**Visual-source baseline COMPLETE — `SOURCE COMPLETE — PENDING CHATGPT
GOVERNANCE REVIEW`.** Fourteen sources, `M06-S01`–`M06-S14`, produced in
**`T6-F`** from the specification baseline accepted as **`T6-E — ACCEPTED after
T6-E-R`**.

> **A source file is a complete construction specification.**
> **It is not a picture. It is not a rendered asset. It is not a deck.**
> **No source file records project implementation, and no visual source creates
> authority.**
> **No visual is rendered.**
> **The source baseline remains pending ChatGPT governance review.**

**The source baseline is `ACCEPTED after T6-F-R`.** **`T6-G` produced the
seven-file presentation assembly package —
[`../../module-06-coordination-review-approval-and-assurance/presentation/`](../../module-06-coordination-review-approval-and-assurance/presentation/) —
which is `PENDING CHATGPT GOVERNANCE REVIEW` and not accepted. `T6-H` — external
PowerPoint production — is `NOT STARTED — BLOCKED PENDING T6-G ACCEPTANCE`.**

---

## 1. What this directory holds

```text
teaching/assets/module-06/
├── README.md                this file
├── visual-register.md       fourteen concepts, fourteen sources, provenance and risk
├── slide-visual-map.md      Slides 1–14 mapped to concepts and sources
├── M06-S01.md               Slide 1 visual source
├── M06-S02.md               Slide 2 visual source
├── M06-S03.md               Slide 3 visual source
├── M06-S04.md               Slide 4 visual source
├── M06-S05.md               Slide 5 visual source
├── M06-S06.md               Slide 6 visual source
├── M06-S07.md               Slide 7 visual source
├── M06-S08.md               Slide 8 visual source
├── M06-S09.md               Slide 9 visual source
├── M06-S10.md               Slide 10 visual source
├── M06-S11.md               Slide 11 visual source
├── M06-S12.md               Slide 12 visual source
├── M06-S13.md               Slide 13 visual source
├── M06-S14.md               Slide 14 visual source
└── rendered/
    └── README.md            why nothing is rendered, and the rules if it ever is
```

**Eighteen files. The fourteen sources sit directly under `module-06/`; there is
no `source/` subdirectory.** That is the path the accepted plan reserved.

## 2. What a visual-source baseline is

A **visual-source baseline** is the complete set of construction specifications
from which a producer could build every slide visual in the module **without
consulting anything outside this repository**.

**Each source file states:** the fixed layout · the exact visible wording · the
geometry in points · connector count, direction and labels · the build sequence ·
the mandatory omissions · the overclaim risk · a producer-failure test · the
applicable STOP-condition numbers · accessibility and reading order · a
screen-reader description · and the native PowerPoint reconstruction method.

**What it is not:**

- **not a picture** — nothing here is an image;
- **not a rendered asset** — nothing has been rendered, and no renderer is
  installed;
- **not a deck** — the `T6-G` assembly package is a production handoff, not a
  deck, and **no Module 6 PowerPoint exists**;
- **not a record of project implementation** — no source file records that any
  coordination act was performed;
- **not a source of authority** — no visual source creates, resolves or
  transfers any authority.

## 3. Authority chain and precedence

```text
controlled Harrismith sources
  ↓
accepted Module 6 teaching content
  ↓
accepted Module 6 visual-demonstration plan
  ↓
Module 6 visual-source files                 ← T6-F, this directory
  ↓
presentation assembly package (T6-G)
  ↓
future external PowerPoint
```

**Precedence, in order:**

1. **controlled Harrismith sources;**
2. **accepted Module 6 teaching content** —
   [`../../module-06-coordination-review-approval-and-assurance/presentation-outline.md`](../../module-06-coordination-review-approval-and-assurance/presentation-outline.md),
   [`speaker-notes.md`](../../module-06-coordination-review-approval-and-assurance/speaker-notes.md),
   [`source-map.md`](../../module-06-coordination-review-approval-and-assurance/source-map.md);
3. **accepted Module 6 visual-demonstration plan** —
   [`visual-demonstration-plan.md`](../../module-06-coordination-review-approval-and-assurance/visual-demonstration-plan.md);
4. **Module 6 visual-source files** — this directory;
5. later presentation assembly package;
6. later external PowerPoint.

**Where a source file differs from the accepted visual plan, the plan wins.**
**Where the plan differs from accepted teaching content, the teaching content
wins.** **Where any teaching material conflicts with a controlled source, the
controlled source wins.**

**A later package, render or PowerPoint never becomes authoritative over its
source.**

## 4. Identifier spaces — strictly one-to-one

```text
14 visual concepts  =  14 slides  =  14 visual-source files
```

| Visual | Slide | Source |
|---|---:|---|
| `M6V-01` | 1 | [`M06-S01.md`](M06-S01.md) |
| `M6V-02` | 2 | [`M06-S02.md`](M06-S02.md) |
| `M6V-03` | 3 | [`M06-S03.md`](M06-S03.md) |
| `M6V-04` | 4 | [`M06-S04.md`](M06-S04.md) |
| `M6V-05` | 5 | [`M06-S05.md`](M06-S05.md) |
| `M6V-06` | 6 | [`M06-S06.md`](M06-S06.md) |
| `M6V-07` | 7 | [`M06-S07.md`](M06-S07.md) |
| `M6V-08` | 8 | [`M06-S08.md`](M06-S08.md) |
| `M6V-09` | 9 | [`M06-S09.md`](M06-S09.md) |
| `M6V-10` | 10 | [`M06-S10.md`](M06-S10.md) |
| `M6V-11` | 11 | [`M06-S11.md`](M06-S11.md) |
| `M6V-12` | 12 | [`M06-S12.md`](M06-S12.md) |
| `M6V-13` | 13 | [`M06-S13.md`](M06-S13.md) |
| `M6V-14` | 14 | [`M06-S14.md`](M06-S14.md) |

**No identifier may be renamed, renumbered or reused** to suit a later render,
tool or deck.

**Controlled and teaching identifiers remain quoted content only.**
`CI-01`–`CI-12`, `X1`–`X5`, `A1`–`A5`, `COORD-01`, `ARC-01`–`FIR-01`,
`TRN-E01`–`TRN-E03`, `T1`–`T8`, `OF-002`–`OF-008`, `GCR-006`, `AD-001`, `TA-02`,
`TA-03`, `UD-001`, `U1`–`U14`, `H1`–`H18`, `E1`–`E9` and `M6-S<slide>-<n>` belong
to the controlled sources or the teaching registers, and **none is used as a
visual or source identifier.**

## 5. Reading order

1. [`../../module-06-coordination-review-approval-and-assurance/visual-demonstration-plan.md`](../../module-06-coordination-review-approval-and-assurance/visual-demonstration-plan.md)
   — the accepted specification, which controls everything here
2. [`slide-visual-map.md`](slide-visual-map.md) — which visual belongs to which
   slide
3. [`visual-register.md`](visual-register.md) — what each visual is, and what it
   must not assert
4. `M06-S01.md` – `M06-S14.md` — how to build each one
5. [`rendered/README.md`](rendered/README.md) — why nothing is rendered

## 6. Native layout only

**Every Module 6 visual is a native-layout specification. There is no diagram
source to render.**

Permitted: rectangles · text boxes · simple tables · native warning strips ·
simple labelled connectors · unfilled checklist boxes · deliberately incomplete
grids · native call-outs.

**Prohibited throughout: SmartArt · imported infographics · Mermaid · automatic
diagram layouts · automatic process diagrams · decorative three-dimensional
effects · software-interface replicas.**

**`Mermaid PROHIBITED × 14`**, decided visual by visual in the accepted plan §2.5
and restated in each source file §15. Automatic graph layout could falsely imply
hierarchy · ownership transfer · a completed cycle · an automatic Issue · a
mandatory status sequence · an approved tolerance · verification in every cycle ·
closure as proof · a Triviron answer.

**`External imagery: NONE REQUIRED × 14`** and **`Live evidence: NONE REQUIRED
× 14`.** No stock photograph, platform screenshot, model screenshot, logo,
observed folder capture, interface capture or downloaded diagram appears
anywhere, and **no new observation is needed or authorised**. Existing
observations appear only as bounded text carrying their accepted qualification.

## 7. Geometry and accessibility conventions

| Parameter | Requirement |
|---|---|
| Canvas | **960 × 540 pt**, 16:9 |
| Origin | Top left; `x` increases right, `y` increases down |
| Title zone | **`y = 0–72` — reserved** |
| Side margins | **≥ 48 pt** |
| Minimum visible type | **14 pt** |
| Principal labels | **≥ 18 pt** |
| Text contrast | **≥ 4.5 : 1** |
| Border and connector contrast | **≥ 3 : 1** |

**Every source file carries:** logical reading order · a screen-reader
description · status meaning **in words** · **no information by colour alone** ·
the minimums above · connector meaning carried by **direction and label** ·
warnings legible at projection scale · and an alternative verbal description of
the visual's principal relationship.

**Anything a sighted reader takes from separation, enclosure, weight or position
is also said in words** — the Slide 3 gap, the Slide 4 upward direction and
missing author label, the Slide 5 exit equality, the Slide 9 absent return
connector, the Slide 10 detachment, the Slide 12 empty boxes and the Slide 14
block equality — **because none of those survive audio.**

## 8. Module 6 STOP conditions — all seventy-five

**Carried without renumbering, merging or paraphrase from the accepted plan §3.**
**A producer must stop and refer back** if any Module 6 visual does any of the
following.

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

**Seventy-five module-wide STOP conditions.** They control production. **They add
nothing to the prohibited-claims register in
[`source-map.md`](../../module-06-coordination-review-approval-and-assurance/source-map.md)
§8, which is unchanged.**

## 9. Fixed source-file conventions

**Every source file in this set carries, without exception:**

**An eighteen-field header** — slide-source identifier · slide number · exact
slide title and allocated time · visual identifier · visual title · increment ·
teaching purpose · principal sources · classification profile · governance
status · implementation status · fixed visual form · known limitation · overclaim
risk · blocked, unresolved or deliberately absent element · mandatory on-slide
warning · external imagery · rendered-asset status.

**Sixteen sections, in this order** — 1 purpose and five-second takeaway ·
2 source and authority basis · 3 governance and implementation status · 4 fixed
layout · 5 exact visible wording · 6 geometry or spatial relationships ·
7 connector semantics · 8 status and warning treatment · 9 build or reveal
sequence · 10 mandatory omissions · 11 accessibility and projection requirements ·
12 screen-reader or presenter-notes description · 13 producer-failure test ·
14 STOP conditions · 15 native PowerPoint reconstruction notes · 16 rendered-asset
status.

**No section is omitted.** Where something does not apply, the file says so
explicitly.

**A four-row completion table** closing every file:

| Field | Required value |
|---|---|
| Source status | `SOURCE COMPLETE — ACCEPTED after T6-F-R` |
| Rendered status | `NONE` |
| Renderer used | `None` |
| Format | `Markdown native-layout specification — not Mermaid` |

## 10. Rendered status

**Rendered assets: `NONE`. Rendering attempted: `NO`. Renderer: `NONE`.
Dependencies: `NONE`. Network rendering service: `NOT USED`.**

Full detail, and the rules that would apply if rendering were ever undertaken,
are in [`rendered/README.md`](rendered/README.md).

**A render never becomes authoritative over its source.**

## 11. Safety boundary

The repository safety boundary in root
[`README.md`](../../../README.md) section 2.1 applies to this directory **without
modification**.

**Nothing in this set was read from, written to or copied out of the Autodesk
Desktop Connector / ACCDocs tree.** No Autodesk, ACC, Forma, Revit or Navisworks
configuration was accessed or changed. **No live observation was performed**, and
none is authorised by anything written here.

**No external imagery was browsed for or downloaded.** **No renderer, dependency
or network rendering service was installed or used.**

## 12. Current source-set validation

| Check | Result |
|---|---|
| Files in this directory | **Eighteen** |
| Visual-source files | **Fourteen — `M06-S01.md`–`M06-S14.md`** |
| `source/` subdirectory | **None.** Sources sit directly under `module-06/` |
| Concept-to-slide-to-source mapping | **Strictly one-to-one, 14 = 14 = 14** |
| Eighteen-field header | **Present in all fourteen** |
| Sixteen sections | **Present in all fourteen** |
| Four-row completion table | **Present in all fourteen** |
| Source status | **`SOURCE COMPLETE — ACCEPTED after T6-F-R` × 14** |
| Source acceptance | **GIVEN — `T6-F — ACCEPTED after T6-F-R`** |
| External imagery | **`NONE REQUIRED` × 14** |
| Live evidence | **`NONE REQUIRED` × 14** |
| Mermaid | **`PROHIBITED` × 14 — no Mermaid block exists in this set** |
| Native reconstruction method | **Specified × 14** |
| Rendered assets | **`NONE`** |
| Renderer or dependency installed | **None** |
| Image, SVG, PNG, JPG, PDF or Office file | **None in this set** |
| Visual register | **Complete** — [`visual-register.md`](visual-register.md) |
| Slide-visual map | **Complete** — [`slide-visual-map.md`](slide-visual-map.md) |
| Presentation assembly package | **Complete (`T6-G`)** — [`../../module-06-coordination-review-approval-and-assurance/presentation/`](../../module-06-coordination-review-approval-and-assurance/presentation/), **seven files**; **`PENDING CHATGPT GOVERNANCE REVIEW`** |
| Module 6 PowerPoint | **None.** No `.pptx` is committed to this repository |
| Presentation review | **NOT PERFORMED** |
| Rehearsal | **NOT PERFORMED** |
| Timing | **`20.0 minutes allocated — not measured`** |
| Slide progression | **Presenter-controlled manual advancement.** No automatic slide-transition timing |
| Complete governed coordination cycle | **NOT DEMONSTRATED.** **`GCR-006` OPEN** |
| Publication automation | **`PAUSED`** |

## 13. Next stage

**`T6-H` — external PowerPoint production.**

**State: `NOT STARTED — BLOCKED PENDING T6-G ACCEPTANCE`.**

**`T6-G` produced the presentation assembly package**, which is **`PENDING
CHATGPT GOVERNANCE REVIEW` and not accepted**. **`T6-H` may not begin until that
review accepts it.** Nothing in this directory authorises a PowerPoint, a render,
a review or a rehearsal.
