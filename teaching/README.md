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

**Modules 1 and 2 are traceable entirely to controlled Harrismith documents.**
No external source was required for any slide in either.

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
├── module-03-iso-19650-principles/  Module 3 — CURRENT, ACTIVE
│   ├── README.md                    module objective, deliverable and scope
│   ├── external-source-register.md  every external source, its authority and limits
│   ├── presentation-outline.md      20-minute structure, Slides 1–3 developed
│   ├── speaker-notes.md             natural-language notes, Slides 1–3
│   ├── visual-demonstration-plan.md candidate visuals for the whole module
│   ├── exercises.md                 practice and self-assessment
│   └── source-map.md                statement classification, mapping method, prohibited claims
├── shared/
│   ├── glossary.md                  teaching glossary across all modules
│   └── presentation-principles.md   how these presentations are built
└── assets/
    ├── README.md                    asset handling rules
    ├── module-01/                   Module 1 visual source set
    └── module-02/                   Module 2 visual source set
```

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
