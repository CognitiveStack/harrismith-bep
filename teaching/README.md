# Harrismith BIM Management Teaching Programme

Teaching and presentation material built on the Harrismith Fire Station BIM
Execution Plan reference implementation.

**Status:** Teaching material under development. **Not governance.**

---

## 1. What this directory is

`teaching/` turns the controlled Harrismith material into a practical BIM
Management teaching and presentation resource. Its purpose is to prepare the
presenter to develop a BIM Execution Plan for a future **Triviron**
multidisciplinary project, using Harrismith as the worked example.

It holds modules, presentation outlines, speaker notes, exercises, visual plans
and source maps. It does not hold project information, and it produces no
project artefact.

## 2. What this directory is not

| It is not | Because |
|---|---|
| Governance | Nothing here decides, approves, authorises or amends anything |
| A BEP | The BEP is `bep/Harrismith-Fire-Station-BEP.md`, and it governs |
| A supporting management resource | Those are in `supporting/`, and each declares its own status |
| A substitute for the controlled wording | Teaching wording is simplified by design; the controlled documents are authoritative |
| Evidence of implementation | Explaining a process is not evidence that the process is running |

**Teaching wording never overrides controlled wording.** Where a teaching
definition and a controlled document differ, the controlled document is correct
and the teaching file is the thing to fix.

This mirrors the distinction already drawn in BEP section 1.4 between the BEP
(which governs), the BIM Delivery Guide (which explains), the Working Process
(which has no authority) and project standards (which govern within their
subject). Teaching material sits alongside the BIM Delivery Guide: **it explains
only.**

## 3. Relationship to the controlled source

Everything taught here is traceable to a recorded source, and each module holds
its own `source-map.md` — for example
[`module-01-what-is-a-bep/source-map.md`](module-01-what-is-a-bep/source-map.md).

**Modules 1, 2, 4 and 5 are traceable entirely to controlled Harrismith
documents.** No external source is required for any slide in any of them.

Modules 4 and 5 each additionally hold a `source-inventory.md` —
[Module 4's](module-04-cde-workflows-and-information-states/source-inventory.md)
and
[Module 5's](module-05-responsibility-matrices-and-information-delivery-planning/source-inventory.md)
— recording the **exact path** of every relevant controlled source, its **own
declared status**, the precedence between them, and **where they differ**.
Differences are recorded, never harmonised by invention. Module 5's inventory
also records the sources it **considered and excluded**, with the reason for each
exclusion.

**Module 3 is not, and cannot be.** Its subject — ISO 19650 — is a copyrighted
international standard that is **not held in this repository and has not been
read for this programme**. It therefore adds a second control alongside its
source map:
[`module-03-iso-19650-principles/external-source-register.md`](module-03-iso-19650-principles/external-source-register.md),
which records every external source with its authority level, jurisdiction,
permitted teaching use and prohibited inference. Published standards, draft
revisions, jurisdiction-bound implementation guidance and Harrismith evidence are
kept explicitly apart, and **no ISO text is reproduced anywhere in this
directory**.

The seven principal package-source documents are:

| # | Document |
|---|---|
| 1 | [`bep/Harrismith-Fire-Station-BEP.md`](../bep/Harrismith-Fire-Station-BEP.md) |
| 2 | [`supporting/information-management-responsibility-matrix.md`](../supporting/information-management-responsibility-matrix.md) |
| 3 | [`supporting/model-information-responsibility-matrix.md`](../supporting/model-information-responsibility-matrix.md) |
| 4 | [`supporting/information-delivery-schedule.md`](../supporting/information-delivery-schedule.md) |
| 5 | [`supporting/cde-workflow-state-strategy.md`](../supporting/cde-workflow-state-strategy.md) |
| 6 | [`supporting/coordination-review-strategy.md`](../supporting/coordination-review-strategy.md) |
| 7 | [`supporting/governance-decision-register.md`](../supporting/governance-decision-register.md) |

Each of those is separately controlled and declares its own status. **Being
referenced from teaching material does not approve, publish or issue any of
them** (BEP 13.6).

## 4. Status of the source material

At the time this programme was established:

- the management-document system is **APPROVED WITH CONDITIONS** as **Training
  Baseline 0.1** (AD-001, 2026-08-01), with conditions still active;
- **publication remains NOT AUTHORISED** and nothing has been issued to the CDE;
- **publication automation remains paused** — see
  [`roadmap.md`](roadmap.md) section 4;
- the implementation is non-contractual and confers no professional authority.

A presentation built from this material must say so. Presenting Harrismith as an
issued, live, contractual BEP would misrepresent it.

## 5. Contents

```text
teaching/
├── README.md                        this file
├── roadmap.md                       the eight-module programme and current position
├── module-01-what-is-a-bep/         Module 1 — produced; review and rehearsal deferred
│   ├── README.md                    module objective, deliverable and scope
│   ├── presentation-outline.md      20-minute structure, Slides 1–14
│   ├── speaker-notes.md             natural-language notes, Slides 1–14
│   ├── visual-demonstration-plan.md candidate visual evidence and its risks
│   ├── exercises.md                 practice and self-assessment
│   ├── source-map.md                each subject mapped to controlled sources
│   └── presentation/                assembly package — production handoff
├── module-02-roles-and-responsibilities/   Module 2 — produced; review and rehearsal deferred
│   ├── README.md                    module objective, deliverable and scope
│   ├── presentation-outline.md      20-minute structure, Slides 1–14
│   ├── speaker-notes.md             natural-language notes, Slides 1–14
│   ├── visual-demonstration-plan.md candidate visuals for the whole module
│   ├── exercises.md                 practice and self-assessment
│   ├── source-map.md                role inventory, authority inventory, classification
│   └── presentation/                assembly package — production handoff
├── module-03-iso-19650-principles/  Module 3 — produced; review and rehearsal deferred
│   ├── README.md                    module objective, deliverable and scope
│   ├── external-source-register.md  every external source, its authority and limits
│   ├── presentation-outline.md      20-minute structure, Slides 1–14
│   ├── speaker-notes.md             natural-language notes, Slides 1–14
│   ├── visual-demonstration-plan.md candidate visuals for the whole module
│   ├── exercises.md                 practice and self-assessment
│   ├── source-map.md                statement classification, mapping method, prohibited claims
│   └── presentation/                assembly package — production handoff
├── module-04-cde-workflows-and-information-states/   Module 4 — produced; review and rehearsal deferred
│   ├── README.md                    module objective, deliverable and scope
│   ├── source-inventory.md          exact source paths, precedence and four registers
│   ├── presentation-outline.md      20-minute structure, Slides 1–14 developed
│   ├── speaker-notes.md             notes for Slides 1–14, plus closing and recovery
│   ├── visual-demonstration-plan.md all fourteen visuals specified, W1–W14
│   ├── exercises.md                 practice and self-assessment — 71 exercises
│   ├── source-map.md                244 statements, seven registers, 99 prohibited claims
│   └── presentation/                assembly package — production handoff
├── module-05-responsibility-matrices-and-information-delivery-planning/   Module 5 — produced and accepted; rehearsal deferred
│   ├── README.md                    module objective, central question, scope, increment status
│   ├── source-inventory.md          exact source paths, own declared statuses, precedence, exclusions
│   ├── resource-comparison.md       the three principal resources analysed separately
│   ├── source-map.md                267 statements, six registers, 103 prohibited claims, final reconciliation
│   ├── presentation-outline.md      20-minute structure; all fourteen slides developed
│   ├── speaker-notes.md             notes for all fourteen slides, plus both closings
│   ├── exercises.md                 practice and self-assessment — 79 exercises
│   ├── visual-demonstration-plan.md fourteen visual specifications, M5V-01 to M5V-14, accepted
│   └── presentation/                assembly package — production handoff
├── module-06-coordination-review-approval-and-assurance/   Module 6 — CURRENT, ACTIVE
│   ├── README.md                    module objective, central question, scope, increment status
│   ├── source-inventory.md          S1–S14 with exact paths and declared statuses; E1–E9 exclusions
│   ├── resource-comparison.md       the four principal resources analysed separately
│   ├── source-map.md                218 statements, nine registers, 93 prohibited claims, final reconciliation
│   ├── presentation-outline.md      20-minute structure; all fourteen slides developed
│   ├── speaker-notes.md             notes for all fourteen slides, plus both closings
│   └── exercises.md                 practice and self-assessment — 91 exercises
├── shared/
│   ├── glossary.md                  teaching glossary across all modules
│   └── presentation-principles.md   how these presentations are built
└── assets/
    ├── README.md                    asset handling rules
    ├── module-01/                   Module 1 visual source set
    ├── module-02/                   Module 2 visual source set
    ├── module-03/                   Module 3 visual source set
    ├── module-04/                   Module 4 visual source set — 14 native-layout sources
    └── module-05/                   Module 5 visual source set, fourteen native-layout sources
```

**Module 5's teaching-content baseline, visual specifications, visual-source
baseline and assembly package are complete, and it is still smaller than the
modules before it.** The module directory holds **eight teaching files**. Its
visual sources live in [`assets/module-05/`](assets/module-05/) and its
production handoff in
[`module-05-responsibility-matrices-and-information-delivery-planning/presentation/`](module-05-responsibility-matrices-and-information-delivery-planning/presentation/)
— **neither is a module teaching file**, and the tree above lists only what
exists.

**All fourteen slides are developed**, with presenter notes for every one, both
closings, **79 exercises**, and **fourteen accepted visual specifications**
(`M5V-01`–`M5V-14`). **T5-F-A-R2 closed the last teaching-to-controlled-source
contradiction**, so all eight files now agree with the controlled `D4` row.

**The visual source set is complete** — fourteen native-layout sources
`M05-S01`–`M05-S14`, a visual register and a slide-visual map, in
[`assets/module-05/`](assets/module-05/). **It is a visual source set, not a
module file.** **No rendered asset exists.**

**The assembly package is complete (T5-G)** — **seven production-handoff files**
in
[`module-05-.../presentation/`](module-05-responsibility-matrices-and-information-delivery-planning/presentation/):
package README, deck specification, slide copy, presenter cues, asset manifest,
production checklist and review checklist. **It is a PowerPoint-production
handoff, not a produced presentation.**

**The external PowerPoint is produced and accepted.** `REV01` was built in
**T5-H**, corrected in **T5-H-R1** — four bounded visual-production defects on
Slides 2–5 only — and **ACCEPTED** by governance review. **It is held outside
this repository and is not committed.**

**A produced, accepted deck is still not a rehearsed one:** there is **no
rendered asset and no PowerPoint committed**, and Module 5 **has not been
rehearsed and its timing is allocated, never measured**.

**Rehearsal and measured timing are `DEFERRED` by governance decision (T5-I-D)** —
**rehearsal `DEFERRED — NOT PERFORMED`**, **measured timing `DEFERRED — NONE`**.
The deck is **presenter-controlled**: the per-slide times are **pacing
allocations**, **automatic slide progression is `NOT REQUIRED`**, and **the
presenter advances each slide manually when ready**.

**Module 5's teaching-production phase is COMPLETE, and Module 6 —
Coordination, Review, Approval and Assurance — is the current active module.**

**`T6-A` to `T6-D` are COMPLETE, and the Module 6 teaching-content baseline is
COMPLETE.** Module 6 holds **seven files** — objective and
scope, a source inventory of **`S1`–`S14`** with **`E1`–`E9`** excluded, a
separate comparison of the **four principal resources**, a source map carrying
**218 classified statements**, **18 hypotheses**, **six terminology variances**,
**14 unresolved matters**, **93 prohibited claims** and a **module-wide final
reconciliation**, a **fourteen-slide
architecture** at **`20.0 minutes allocated — not measured`**, and presenter
notes.

**All fourteen slides are developed**, with presenter notes for every one, both
closings and **91 exercises**. **No visual-demonstration plan, no visual source,
no asset directory, no presentation package and no PowerPoint exist**, and no
review or rehearsal has been performed. **`GCR-006` remains OPEN — no complete
governed coordination cycle has been demonstrated.** **`T6-E` — specify Module 6
visuals — is next.**

**`T5-F-B-R` reconciled the Module 5 production-state records** across the module
and programme files. **No teaching claim, statement classification, count or
prohibited claim was changed.**

**No `.pptx` file is committed anywhere in this repository**, for any module.
[`roadmap.md`](roadmap.md) carries the authoritative position for every module.

## 6. Safety boundary

The repository safety boundary in root `README.md` section 2.1 applies to this
directory without modification.

No teaching activity reads from, writes to, or changes anything in the Autodesk
Desktop Connector / ACCDocs tree, or any Autodesk Forma, ACC, Revit or
Navisworks configuration. Where a module proposes a live observation, that
observation is a **separately authorised, bounded, read-only** activity — it is
not authorised by appearing in a teaching file.

## 7. How to work in this directory

- **Teaching files may be revised freely.** They carry no authority, so
  revising them changes no governance.
- **Controlled documents are read-only from here.** A teaching need is never a
  reason to edit the BEP, a supporting resource or a governance record.
- **A contradiction is reported, not patched.** If teaching material appears to
  conflict with a controlled document, raise it through the Working Process
  (`working/README.md`) rather than adjusting either file to agree.
- **Unsupported claims are marked, not smoothed over.** Where a teaching point
  has no explicit source wording, `source-map.md` says so.
- **External sources are registered before they are taught.** Where a module
  draws on material outside this repository, it records the source, its
  authority level, its jurisdiction and what may **not** be inferred from it —
  see
  [`module-03-iso-19650-principles/external-source-register.md`](module-03-iso-19650-principles/external-source-register.md).
  **No copyrighted standards text is reproduced here**, and an unregistered
  external claim is not taught.
