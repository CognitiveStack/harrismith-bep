# Module 1 — Visual source set

**Status:** Visual-source baseline complete. **No rendered assets exist.**
**Not governance.**

Text-based, reviewable visual source for all fourteen slides of
**Module 1 — What is a BIM Execution Plan?**

---

## 1. Contents

```text
teaching/assets/module-01/
├── README.md               this file — design principles and conventions
├── visual-register.md      every visual, its status, evidence and warnings
├── slide-visual-map.md     Slides 1–14 mapped to their visuals
├── source/                 the visual source files (14)
│   ├── M01-S01-title-layout.md
│   ├── M01-S02-coordination-problem.md
│   ├── M01-S03-six-actions.md
│   ├── M01-S04-governance-functions.md
│   ├── M01-S05-template-vs-project.md
│   ├── M01-S06-document-architecture.md
│   ├── M01-S07-matrix-comparison.md
│   ├── M01-S08-delivery-planning.md
│   ├── M01-S09-cde-states.md
│   ├── M01-S10-folder-vs-status.md
│   ├── M01-S11-coordination-cycle.md
│   ├── M01-S12-issue-lifecycle.md
│   ├── M01-S13-approval-vs-implementation.md
│   └── M01-S14-harrismith-to-triviron.md
└── rendered/
    └── README.md           records that nothing has been rendered
```

| Start here | For |
|---|---|
| [`visual-register.md`](visual-register.md) | What exists, its status, its evidence and its warnings |
| [`slide-visual-map.md`](slide-visual-map.md) | Which visual serves which slide, and what must be omitted |
| [`source/`](source/) | The visual source itself |

## 2. Controlling documents

This set **implements** the visual plan; it does not supersede it.

| Document | Role |
|---|---|
| [`../../module-01-what-is-a-bep/visual-demonstration-plan.md`](../../module-01-what-is-a-bep/visual-demonstration-plan.md) | **Authoritative** for visual identifiers `V1`–`V10`, evidence classifications and overclaim warnings |
| [`../../module-01-what-is-a-bep/presentation-outline.md`](../../module-01-what-is-a-bep/presentation-outline.md) | Slide content and timing |
| [`../../module-01-what-is-a-bep/speaker-notes.md`](../../module-01-what-is-a-bep/speaker-notes.md) | What the speaker supplies that the visual cannot |
| [`../../module-01-what-is-a-bep/source-map.md`](../../module-01-what-is-a-bep/source-map.md) | Statement-level evidence classification |
| [`../../shared/presentation-principles.md`](../../shared/presentation-principles.md) | The programme's standing presentation rules |

**Existing identifiers are not renumbered.** `V1`–`V10` retain their meanings
from the plan; `M01-S01`–`M01-S14` are new identifiers for slide visual sources.

## 3. Source-file conventions

Every source file is a `.md` file containing:

1. a **documentation header table** — visual identifier, related slide, purpose,
   source format, source documents, evidence classification, known limitation,
   last increment;
2. the visual source itself — a fenced ```mermaid block, a Markdown table, or a
   text layout specification;
3. reading notes, simplification and omission guidance, and an overclaim-risk
   assessment.

**Why `.md` rather than `.mmd`.** A Markdown wrapper carries the documentation
header in readable form, keeps the diagram reviewable in a Git diff, and renders
natively on GitHub — so the diagrams are viewable without any local tooling.

## 4. Format choice

**Mermaid is used where it represents the visual accurately; Markdown tables and
text layouts are used where Mermaid would mislead.** No visual is forced into
Mermaid.

| Format | Used for | Why |
|---|---|---|
| Mermaid `flowchart` | `S02`, `S03`, `S04`, `S06`, `S09`, `S10`, `S11`, `S12`, `S14` | Relationships, sequences and cycles where the connections carry meaning |
| Markdown table | `S05`, `S07`, `S08`, `S13` | Comparisons and record extracts. A flowchart would impose relationships that do not exist — `S05` in particular, where a template does not *become* a project BEP through any recorded process |
| Text layout spec | `S01` | A title slide has no diagram; it has a composition |

## 5. Visual design principles

Recorded here and followed throughout the set.

| # | Principle |
|---|---|
| 1 | **One principal message per visual.** If it needs an "and", split it |
| 2 | **Readable at presentation scale.** Fewer nodes and larger type beat completeness |
| 3 | **Avoid dense document screenshots.** Extract the rows that carry the message |
| 4 | **Simplify without changing governance meaning.** Compression is allowed; alteration is not |
| 5 | **Use consistent terminology.** Harrismith's terms, exactly — *Lead Delivery Party*, *Record / Retained*, the seven-term responsibility grammar |
| 6 | **Show unresolved matters visibly rather than completing them aesthetically** |
| 7 | **Distinguish evidence from teaching synthesis**, in the header and where it matters on the slide |
| 8 | **Distinguish proposed workflow from observed implementation** |
| 9 | **Avoid decorative complexity.** No gradients, shadows, icon sets or product chrome |
| 10 | **Preserve whitespace.** A crowded diagram is an unread diagram |
| 11 | **Make arrows semantically meaningful.** `-->` means *progresses to*; `---` means *holds detail for*; dashed means *unreached, unresolved or not-yet-real* |
| 12 | **Do not imply automatic workflow where human authority is required** |

### 5.1 Principle 6 in practice

Three visuals would look better if they were drawn as complete. All three are
deliberately not:

| Visual | What is drawn incomplete | Why |
|---|---|---|
| `M01-S04` | The `controlled publication` node, dashed | Harrismith reached *authorised training baseline*; it has not reached publication |
| `M01-S10` | The **T4** transition, dashed and marked **BLOCKED** | Publication authority is unresolved; a clean chain would invent it |
| `M01-S14` | The `implemented Triviron BEP` box, outline only | It does not exist, and nobody has started it |

**A tidier diagram in any of these three would be a governance failure**, not a
design improvement.

### 5.2 Arrow semantics

| Notation | Meaning | Example |
|---|---|---|
| `-->` solid | Progresses to, by a decision | `M01-S09` WIP → Shared |
| `---` plain line | Holds the detail for | `M01-S06` BEP to its supporting resources |
| `-.->` dashed arrow | Unresolved, blocked, or not-yet-real | `M01-S10` T4; `M01-S14` final box |
| `-.-` dashed line | Records decisions about; annotates | `M01-S06` register; note attachments |
| `==>` thick | Direction of derivation, emphasised | `M01-S10` authority → permission |

## 6. Standing prohibitions

Applying to every file in this directory:

1. **No fabricated or AI-generated image** presented as a Harrismith project
   view, model, CDE view or screenshot.
2. **No named person, company or signatory.** Every role holder is **TBD**.
3. **No invented date, milestone, programme or duration.**
4. **No RACI terminology** — expressly not adopted (BEP §5.12).
5. **`Archived` is not a Harrismith state.** The fourth state is
   **`Record / Retained`**.
6. **No claim that a proposed workflow is configured, implemented or verified.**
7. **No ISO definition attributed to ISO 19650** — none is verifiable here.
8. **No Triviron project fact.**
9. **No corporate or Triviron brand identity** — not chosen in this increment.
10. **No live Autodesk work.** The root `README.md` §2.1 safety boundary applies
    unchanged.

## 7. Status

| Field | Value |
|---|---|
| Visual source | **Complete for Slides 1–14** |
| Rendered assets | **None** — see [`rendered/README.md`](rendered/README.md) |
| Slides deliverable without external material | **14 of 14** |
| External dependencies | `V1`, `V9`, `V10` — all optional enrichments |
| Module 1 | **CURRENT — ACTIVE**, not complete |
| Assembly package | Complete — [`../../module-01-what-is-a-bep/presentation/`](../../module-01-what-is-a-bep/presentation/) |
| Outstanding | PowerPoint production, presentation review, rehearsal, measured timing, refinement |
| Publication automation | **PAUSED** |

**Producing the deck?** The asset mapping for each slide — source file, type,
rendering need, warnings and proposed rendered filename — is in
[`../../module-01-what-is-a-bep/presentation/asset-manifest.md`](../../module-01-what-is-a-bep/presentation/asset-manifest.md).
