# M01-S07 — Two responsibility matrices, two different questions

| Field | Value |
|---|---|
| **Visual identifier** | `M01-S07` |
| **Related slide** | Slide 7 — Two responsibility matrices, two different questions |
| **Purpose** | Separate process responsibility from model-content responsibility — verbs against roles, versus containers with originators |
| **Source format** | Markdown two-column comparison + two simplified matrix extracts. **Deliberately not Mermaid** |
| **Source documents** | `supporting/information-management-responsibility-matrix.md` purpose statement, §1, §2, §3.3; `supporting/model-information-responsibility-matrix.md` purpose statement, §3.1; `bep/Harrismith-Fire-Station-BEP.md` §5.12 |
| **Evidence classification** | **DIRECT** for both purpose statements, the seven-term grammar, the RACI exclusion and both extracts; **INTERPRETATION** for the "verbs versus things" structural description |
| **Known limitation** | **Every role holder is TBD.** All model-matrix allocations are **PROPOSED GOVERNANCE under TA-03** — no organisation appointed, none named. **RACI is expressly not adopted** and must not be introduced |
| **Last increment** | T1-D |

---

## 1. Why this is not a diagram

Both artefacts are tables in the source, and the teaching point is *how they are
structured differently*. Converting either into a flowchart would destroy the
very property being compared.

**This is the highest over-detail risk in the module.** Both source documents are
wide tables and unreadable when projected whole. The extracts below total six
rows.

## 2. Slide layout

```text
┌────────────────────────────────────┬────────────────────────────────────┐
│  INFORMATION MANAGEMENT            │  MODEL / INFORMATION               │
│  RESPONSIBILITY MATRIX             │  RESPONSIBILITY MATRIX             │
│                                    │                                    │
│  Who performs, checks, authorises, │  Which party and task team         │
│  coordinates and accepts each      │  produces and maintains each       │
│  process function?                 │  information container?            │
│                                    │                                    │
│  a grid — verbs × roles            │  a register — one per container    │
├────────────────────────────────────┼────────────────────────────────────┤
│  [extract: rows P1, P4]            │  [extract: MEC/ELE/PLM/FIR rows]   │
├────────────────────────────────────┴────────────────────────────────────┤
│  Process responsibility and model-content responsibility are related,   │
│  but they are not the same thing.                                       │
└─────────────────────────────────────────────────────────────────────────┘
```

## 3. Structural comparison

| | IM Responsibility Matrix | Model / Information Responsibility Matrix |
|---|---|---|
| Shape | A grid — **functions × roles** | A register — **one entry per container** |
| Rows | 25 process functions, grouped G / C / P / S / X / D / A | 6 discipline containers plus COORD-01 |
| Columns | 9 functional roles: AP, LDP, BM, BC, TTL, Aut, Chk, CDE, Rcp | Originating party, task team, discipline, purpose, format, intended states, interfaces |
| Cells say | Perform, Check, Authorise, Coordinate, Accept, Consult, Inform | Which party and task team — plus Lead and Contributors |
| Unit allocated | A **verb** | A **thing** |

## 4. Extract A — IM matrix, rows P1 and P4

Four columns only. Two rows.

| # | Function | Aut | Chk | TTL | BC |
|---|---|---|---|---|---|
| P1 | Author information in WIP | **P** | — | Co | — |
| P4 | Authorise WIP information for controlled sharing | — | Cs | **Au** | In |

**The message, in one line:** the Author performs the authoring and does not
appear in the authorisation row at all.

> An Author does not self-authorise merely because they authored the
> information.

## 5. Extract B — Model matrix, the MEP and Fire rows

Three columns. Four rows.

| Ref | Originating party | Task team |
|---|---|---|
| MEC-01 | **MEP Consultant** | Mechanical task team |
| ELE-01 | **MEP Consultant** | Electrical task team |
| PLM-01 | **MEP Consultant** | Plumbing task team |
| FIR-01 | **Fire Consultant** | Fire task team |

**The message, in one line:** one party, three task teams — and Fire is a
*separate* party, not an MEP sub-team. The first matrix cannot tell you this.

## 6. Simplification and omission

| Simplify | Omit |
|---|---|
| Two questions, enlarged — they are the slide | The full nine-column IM grid |
| Two rows × four columns; four rows × three columns | All seven IM sub-tables |
| One closing message line | **Any RACI letter or RACI mapping** |
| — | Any role holder name |
| — | The model matrix's format, state, interface and dependency columns |

## 7. RACI prohibition

BEP §5.12 states the seven-term grammar is used **instead of** RACI, because RACI
collapses checking from authorising and coordinating from performing —
distinctions the whole BEP depends on. **It is not to be introduced unless
explicitly approved later.**

Do not translate these cells into RACI on a slide, in a legend, or in an answer
to a question.

## 8. Overclaim risk

**Low.** Both extracts are verbatim from approved-with-conditions sources. The
only guard needed is the TA-03 note: the model-matrix allocations are proposed
governance, not appointments, and no organisation is named.
