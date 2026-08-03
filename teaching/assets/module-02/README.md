# Module 2 — Visual source set

**Status:** Visual-source baseline complete. **No rendered assets exist.**
**Not governance.**

Text-based, reviewable visual source for all fourteen slides of
**Module 2 — BIM Management Roles and Responsibilities**.

---

## 1. Contents

```text
teaching/assets/module-02/
├── README.md               this file — design principles and conventions
├── visual-register.md      every visual, its status, evidence and warnings
├── slide-visual-map.md     Slides 1–14 mapped to their visuals
├── source/                 the visual source files (14)
│   ├── M02-S01-decisions-explicit.md
│   ├── M02-S02-role-not-job-title.md
│   ├── M02-S03-function-organisation-person.md
│   ├── M02-S04-functional-map.md
│   ├── M02-S05-bim-manager-does.md
│   ├── M02-S06-bim-manager-does-not.md
│   ├── M02-S07-coordinator-process.md
│   ├── M02-S08-coordination-not-design.md
│   ├── M02-S09-separation-of-duties.md
│   ├── M02-S10-administration-implements.md
│   ├── M02-S11-decision-chain.md
│   ├── M02-S12-authority-map.md
│   ├── M02-S13-functions-not-holders.md
│   └── M02-S14-triviron-assignments.md
└── rendered/
    └── README.md           records that nothing has been rendered
```

| Start here | For |
|---|---|
| [`visual-register.md`](visual-register.md) | What exists, its status, evidence and warnings |
| [`slide-visual-map.md`](slide-visual-map.md) | Which visual serves which slide, and what must be omitted |
| [`source/`](source/) | The visual source itself |

## 2. Controlling documents

This set **implements** the visual plan; it does not supersede it.

| Document | Role |
|---|---|
| [`../../module-02-roles-and-responsibilities/visual-demonstration-plan.md`](../../module-02-roles-and-responsibilities/visual-demonstration-plan.md) | **Authoritative** for evidence identifiers `R1`–`R11`, classifications and overclaim warnings |
| [`../../module-02-roles-and-responsibilities/presentation-outline.md`](../../module-02-roles-and-responsibilities/presentation-outline.md) | Slide content and timing |
| [`../../module-02-roles-and-responsibilities/speaker-notes.md`](../../module-02-roles-and-responsibilities/speaker-notes.md) | What the speaker supplies that the visual cannot |
| [`../../module-02-roles-and-responsibilities/source-map.md`](../../module-02-roles-and-responsibilities/source-map.md) | Role inventory, authority inventory and statement classification |
| [`../../shared/presentation-principles.md`](../../shared/presentation-principles.md) | The programme's standing presentation rules |

**Existing identifiers are not renumbered.** `R1`–`R11` retain their meanings;
`M02-S01`–`M02-S14` is a new space for slide visual sources.

## 3. Source-file conventions

Every source file is a `.md` file containing:

1. a **documentation header** — visual identifier, related slide, slide title,
   teaching purpose, principal sources, evidence classification, known
   limitation, mandatory presentation warning, evidence source consumed, and
   increment;
2. the visual source — a fenced ```mermaid block, a Markdown table, or a text
   layout specification;
3. reading notes, simplification and omission guidance, and an overclaim-risk
   assessment.

**Why `.md` rather than `.mmd`.** The wrapper carries the header in readable
form, keeps the diagram diffable, and renders natively on GitHub.

## 4. Format choice

**Mermaid where it represents the visual accurately; tables and layouts where it
would mislead.** No visual is forced into Mermaid.

| Format | Used for | Why |
|---|---|---|
| Mermaid `flowchart` | `S01`–`S05`, `S07`–`S11`, `S13`, `S14` | Relationships, sequences, swimlanes and functional maps where connections carry meaning |
| Markdown table | `S02`, `S03`, `S05`, `S06`, `S12`, `S13`, `S14` panels | Comparisons and registers. A diagram would impose relationships that do not exist |
| Text layout spec | `S06` | A balanced two-column comparison is a composition, not a graph |

**Where a table was chosen deliberately over Mermaid:**

| Visual | Reason |
|---|---|
| `S06` | A flowchart between "does" and "does not automatically hold" would imply a derivation. They are two lists about one function |
| `S12` | Sixteen authorities against nine functions is unreadable at projection scale, and any node arrangement implies a relationship the register does not assert |
| `S13` comparison | The two columns are contrasted, not connected; a diagram would imply a transformation |

## 5. Visual design principles

| # | Principle |
|---|---|
| 1 | **One principal message per visual.** If it needs an "and", split it |
| 2 | **Readable at projection scale.** Fewer nodes and larger type beat completeness |
| 3 | **Consistent terminology and shapes** — the same form means the same thing on every slide |
| 4 | **Arrows carry semantic meaning** — see §5.1 |
| 5 | **Unresolved matters remain visible.** Never omitted to tidy a diagram |
| 6 | **No decorative completeness** — no gradients, shadows, icon sets or product chrome |
| 7 | **No corporate hierarchy invented** — BEP §5.2 disclaims an appointment or organisation chart |
| 8 | **No platform interface used to imply governance** |
| 9 | **No icon representing technical approval inside IM authority** — it is allocated to no IM function |
| 10 | **No fabricated role holders** and **no fabricated project evidence** |
| 11 | **Adequate whitespace** |
| 12 | **Restrained professional BIM-management style.** No Triviron visual identity is established in this increment |

### 5.1 Line semantics

| Notation | Meaning | Example |
|---|---|---|
| `-->` solid | Allocated or governed progression | `M02-S09` Author → Checker → Task-Team Lead |
| `==>` thick | Direction of derivation, emphasised | `M02-S10` responsibility → decision → permission |
| `---` plain line | Relationship without authority or sequence | `M02-S04` functions around the process |
| `-.->` dashed arrow | **Unresolved, blocked, future or not-yet-real** | `M02-S11` publication; `M02-S14` stage 7 |
| `-.-` dashed line | Annotation or note attachment | Caption and warning nodes throughout |

### 5.2 Where a tidier diagram would be a governance failure

Four visuals are deliberately incomplete. Completing any of them would assert an
authority the sources decline to assign.

| Visual | Drawn incomplete | Why |
|---|---|---|
| `M02-S09` | `Published` unreached, dashed | Publication authority **UNRESOLVED**; the transition is **BLOCKED** |
| `M02-S11` | Two links dashed and marked unheld | Publication and acceptance authority both unresolved |
| `M02-S13` | Layers 2 and 3 progressively weakened | No organisation appointed; every holder TBD |
| `M02-S14` | Stage 7 outline-only | No Triviron implementation exists or is scheduled |

## 6. Standing prohibitions

1. **No named person, company or signatory.** Every role holder is TBD.
2. **No name-shaped placeholder** — a bracketed name token or initial-and-surname
   reads as a name.
3. **No invented date, milestone, duration or programme.**
4. **No RACI terminology** — expressly not adopted (BEP §5.12; IM matrix §1).
5. **No ISO role terminology** — `lead appointed party` and `appointed party`
   appear nowhere in the sources.
6. **No vertical hierarchy**, and the BIM Manager is never placed at the top.
7. **No claim that a proposed workflow is configured, implemented or verified.**
8. **No fabricated or AI-generated image**, and no platform screenshot.
9. **No Triviron project fact**, and no Triviron visual identity.
10. **No live Autodesk work.** Root `README.md` §2.1 applies unchanged.

## 7. Status

| Field | Value |
|---|---|
| Visual source | **Complete for Slides 1–14** |
| Rendered assets | **None** — see [`rendered/README.md`](rendered/README.md) |
| External evidence required | **None** — all fourteen slides are repository-derivable |
| Live observation required | **None**, and counterproductive for `M02-S07` and `M02-S10` |
| Module 2 | **CURRENT — ACTIVE**, not complete |
| Outstanding | Presentation assembly package, PowerPoint production, review, rehearsal |
| Publication automation | **PAUSED** |
