# Module 2 — Visual Register

**Status:** Visual-source baseline. **Not governance.** No rendered assets exist.

Controlling document:
[`../../module-02-roles-and-responsibilities/visual-demonstration-plan.md`](../../module-02-roles-and-responsibilities/visual-demonstration-plan.md).
Its evidence identifiers `R1`–`R11`, classifications and overclaim warnings are
authoritative and are **not renumbered here**.

---

## 1. Two identifier spaces

| Space | Meaning |
|---|---|
| **`R1`–`R11`** | **Evidence visuals** from the plan's §2 — candidate material drawn from the controlled sources |
| **`M02-S01`–`M02-S14`** | **Slide visual sources** created in this increment, one per slide |

They are related but not interchangeable. `R7` is the author/check/authorise
relationship as an *evidence visual*; `M02-S09` is the *slide visual* built from
it.

**Slides 1 and 4 consume no `R` identifier.** The plan's §2 evidence visuals
begin at Slide 2; Slide 1's opening argument and Slide 4's functional map are
built directly from BEP sections and the responsibility matrix.

## 2. Status definitions

| Status | Meaning |
|---|---|
| **`SOURCE COMPLETE`** | Reviewable text-based source exists and is sufficient to produce the visual |
| **`SOURCE PARTIAL`** | Source exists but an element is deliberately left open |
| **`EXTERNAL EVIDENCE REQUIRED`** | Cannot be produced from the repository |
| **`OPTIONAL LIVE OBSERVATION`** | Repository-derivable, but a later bounded read-only observation could add value |
| **`DEFERRED`** | Recorded, not developed in this increment |
| **`EXCLUDED`** | Deliberately not produced; reason recorded |

**No status implies a rendered image exists.** See
[`rendered/README.md`](rendered/README.md).

---

## 3. Slide visual sources

### 3.1 Identity, format and status

| ID | Slide | Title | Format | Source file | Rendered | Status |
|---|---|---|---|---|---|---|
| `M02-S01` | 1 | BIM roles exist to make decisions explicit | Mermaid | [`source/M02-S01-decisions-explicit.md`](source/M02-S01-decisions-explicit.md) | — | `SOURCE COMPLETE` |
| `M02-S02` | 2 | A role is not the same as a job title | Mermaid + table | [`source/M02-S02-role-not-job-title.md`](source/M02-S02-role-not-job-title.md) | — | `SOURCE COMPLETE` |
| `M02-S03` | 3 | Function, organisation and named person | Mermaid + table | [`source/M02-S03-function-organisation-person.md`](source/M02-S03-function-organisation-person.md) | — | `SOURCE COMPLETE` |
| `M02-S04` | 4 | Who governs the project information process? | Mermaid (ring) | [`source/M02-S04-functional-map.md`](source/M02-S04-functional-map.md) | — | `SOURCE COMPLETE` |
| `M02-S05` | 5 | What does the BIM Manager actually do? | Mermaid + tables | [`source/M02-S05-bim-manager-does.md`](source/M02-S05-bim-manager-does.md) | — | `SOURCE COMPLETE` |
| `M02-S06` | 6 | What the BIM Manager does not automatically do | Layout + table | [`source/M02-S06-bim-manager-does-not.md`](source/M02-S06-bim-manager-does-not.md) | — | `SOURCE COMPLETE` |
| `M02-S07` | 7 | What does the BIM Coordinator do? | Mermaid + tables | [`source/M02-S07-coordinator-process.md`](source/M02-S07-coordinator-process.md) | — | `SOURCE COMPLETE` |
| `M02-S08` | 8 | Coordination responsibility is not design responsibility | Mermaid (swimlane) | [`source/M02-S08-coordination-not-design.md`](source/M02-S08-coordination-not-design.md) | — | `SOURCE COMPLETE` |
| `M02-S09` | 9 | Task-Team Leads, Authors and Checkers | Mermaid + extract | [`source/M02-S09-separation-of-duties.md`](source/M02-S09-separation-of-duties.md) | — | `SOURCE COMPLETE` |
| `M02-S10` | 10 | CDE Administration implements governance | Mermaid ×2 + table | [`source/M02-S10-administration-implements.md`](source/M02-S10-administration-implements.md) | — | `SOURCE COMPLETE` |
| `M02-S11` | 11 | Check, authorise, publish, receive and accept | Mermaid + table | [`source/M02-S11-decision-chain.md`](source/M02-S11-decision-chain.md) | — | `SOURCE COMPLETE` |
| `M02-S12` | 12 | One process, several distinct authorities | Table register | [`source/M02-S12-authority-map.md`](source/M02-S12-authority-map.md) | — | **`SOURCE PARTIAL`** — see §3.4 |
| `M02-S13` | 13 | Harrismith names functions but not role holders | Table + Mermaid | [`source/M02-S13-functions-not-holders.md`](source/M02-S13-functions-not-holders.md) | — | `SOURCE COMPLETE` |
| `M02-S14` | 14 | What must Triviron assign before delivery begins? | Mermaid + tables | [`source/M02-S14-triviron-assignments.md`](source/M02-S14-triviron-assignments.md) | — | `SOURCE COMPLETE` |

### 3.2 Purpose, evidence and classification

| ID | Teaching purpose | Evidence source | Classification |
|---|---|---|---|
| `M02-S01` | Interface decisions get made either way — deliberately or by assumption, access or habit | BEP §1.1, §1.5, §4.8, §5.1, §5.4 | DIRECT + SYNTHESIS (framing) |
| `M02-S02` | Function ≠ job title ≠ person; combining functions does not merge them | BEP §4.6, §5.4, §5.5, §5.11 | **DIRECT** |
| `M02-S03` | Three layers, with the third deliberately empty | BEP §4.2, §4.6, §5.2; IM matrix §2, §5 | DIRECT + INTERP (stack) + SYNTHESIS (planning value) |
| `M02-S04` | Functional map, not hierarchy; seven separated concerns | BEP §4.6, §5.2, §5.4, §5.7; IM matrix §2 | DIRECT + INTERP (arrangement) |
| `M02-S05` | Positive account anchored on row G1 | BEP §5.5; IM matrix §3.1, §3.2, §3.7 | **DIRECT** |
| `M02-S06` | Ten exclusions, balanced against the positive duties | BEP §5.4, §5.5, §5.11, §9.7, §9.8, §12.7; IM matrix §4, §3.7; Coordination §3 | DIRECT ×9 + INTERP ×1 + SYNTHESIS (message) |
| `M02-S07` | Coordinator at the process centre; task teams retain ownership | BEP §5.6; Coordination §3, §8, §12; IM matrix §3.5; Model matrix §3.1, §3.4 | **DIRECT** |
| `M02-S08` | Responsibility crosses to the task team and returns | Coordination §16–§19, §27; IM matrix §3.5 | DIRECT + INTERP (compression) |
| `M02-S09` | Three functions, one container, three acts — stopping at Shared | IM matrix §3.3; BEP §5.7, §5.8, §7.6, §9.3, §9.4; IDS §3.2 | **DIRECT** |
| `M02-S10` | Responsibility → decision → permission; access ≠ authority | BEP §4.6, §5.9, §5.11, §6.9, §9.7; CDE §14, §17; IM matrix §3.2, §3.7 | **DIRECT** |
| `M02-S11` | The decision chain with two links visibly unheld | BEP §9.2–9.8, §10.10, §10.11; CDE §3, §13; IM matrix §3.3, §3.6 | DIRECT + INTERP (message) |
| `M02-S12` | Who may decide each action — including where nobody may | IM matrix §3.1–3.7, §6; BEP §9.4, §9.7, §9.8, §12.7, §12.9; CDE §3.2; Coordination §19 | DIRECT + INTERP (vocabulary) + SYNTHESIS (message) |
| `M02-S13` | Governance framework versus implemented appointment structure | BEP §4.2, §4.6, §5.1, §5.2, §5.11, §6.9, §9.10, §10.11, §12.9; IM matrix §2, §4, §6 | DIRECT + INTERP + SYNTHESIS |
| `M02-S14` | The model as a startup checklist, in questions | Unresolved records across all seven sources; BEP §6.9 | SYNTHESIS + DIRECT derivations |

### 3.3 Risk, dependency and mandatory warning

| ID | Unresolved dependency | Live observation | Overclaim risk | Mandatory presentation warning |
|---|---|---|---|---|
| `M02-S01` | — | No | Low | Never caption any route as a recorded Harrismith failure |
| `M02-S02` | All holders TBD | No | Low | No name, avatar, silhouette or photograph |
| `M02-S03` | Layer 2 unappointed; layer 3 TBD | No | Medium | **No name-shaped placeholder in layer 3**; caption *defined, not yet operating* |
| `M02-S04` | AP identity; acceptance authority | No | Medium | **If the diagram has a visual top role, it is wrong.** TBD must be visible |
| `M02-S05` | Holder TBD | No | Low | **No exclusions** — Slide 6 owns them. Preserve the G4 nuance |
| `M02-S06` | Publication and acceptance **UNRESOLVED for everyone** | No | Low content, moderate tone | **Equal column weight.** Do not make the function appear marginal |
| `M02-S07` | Not evidenced as configured (`OF-005`) | Possibly later — but see risk | **High** | Caption as governed model, not operating process. No product name or screenshot |
| `M02-S08` | Not evidenced as configured | No | **High** | Technical response stays in the task-team lane. Label the §27 example as educational |
| `M02-S09` | Publication authority **UNRESOLVED / BLOCKED** | No | Low if it stops at Shared | **No solid Shared → Published arrow. No RACI letters** |
| `M02-S10` | Holder TBD | **No — counterproductive** | Low if arrow one-way | **No ACC permissions screenshot.** One direction, no return path |
| `M02-S11` | Publication **BLOCKED**; acceptance **RECIPIENT-DEPENDENT** | No | **High if drawn complete** | Unresolved steps shown, never omitted. No complete solid route |
| `M02-S12` | Three unresolved; one outside IM authority | No | **High if unresolved rows cut** | No hierarchy · BIM Manager not at top · no unresolved row hidden |
| `M02-S13` | All nine holders; three authorities | No | **Inverted, both directions** | Neither "broken" nor "running". No name-shaped placeholder |
| `M02-S14` | **No Triviron source exists** | Not applicable | **High** | No Triviron fact. Stage 7 outline-only. Permissions fifth |

### 3.4 `M02-S12` — why `SOURCE PARTIAL`

The full sixteen-authority register is too dense for a one-minute slide. The
source file therefore carries **two** layouts: a simplified eight-to-ten-row
primary visual for the slide, and the complete sixteen-row register as a
presenter-only or appendix layout.

**This is a deliberate split, not an incomplete source.** Both layouts are fully
specified. The status records that the slide visual is a documented subset rather
than the whole register — and that **unresolved rows are retained in the subset,
never cut for space**.

---

## 4. Evidence visuals — `R1` to `R11`

Carried forward from the plan §2 without renumbering.

| ID | Title | Slides | Consumed by | From repo? | Status |
|---|---|---|---|---|---|
| `R1` | Function versus person | 2, 3 | `M02-S02`, `M02-S03` | Yes | `SOURCE COMPLETE` |
| `R2` | Three-layer model | 3 | `M02-S03`, `M02-S13` | Yes | `SOURCE COMPLETE` |
| `R3` | Role-boundary diagram | 5–8 | `M02-S05`, `M02-S06`, `M02-S07`, `M02-S08` | Yes | `SOURCE COMPLETE` |
| `R4` | Role-and-authority map | 12 | `M02-S12` | Yes | **`SOURCE PARTIAL`** — split into slide and appendix layouts |
| `R5` | BIM Manager does / does not | 5, 6 | `M02-S05`, `M02-S06` | Yes | `SOURCE COMPLETE` |
| `R6` | BIM Coordinator workflow | 7, 8 | `M02-S07`, `M02-S08` | Yes | `SOURCE COMPLETE` |
| `R7` | Author / check / authorise | 9 | `M02-S09` | Yes | `SOURCE COMPLETE` |
| `R8` | CDE Administration vs authority | 10 | `M02-S10` | Yes | `SOURCE COMPLETE` |
| `R9` | Check → accept chain | 11 | `M02-S11` | Yes | `SOURCE COMPLETE` |
| `R10` | Unresolved-role register | 13 | `M02-S13` | Yes | `SOURCE COMPLETE` |
| `R11` | Triviron assignment questions | 14 | `M02-S14` | Yes | SYNTHESIS framing; `SOURCE COMPLETE` |

**All eleven evidence visuals are consumed by at least one slide source.** None
is deferred or excluded.

---

## 5. External evidence

**None required.**

Unlike Module 1 — where `V1`, `V9` and `V10` needed a project image, a CDE view
and a model view that do not exist — **Module 2 requires no external material at
all**. The module is about functions and authorities, and the controlled sources
state them in text.

Two visuals would be **actively harmed** by external material:

| Visual | Why |
|---|---|
| `M02-S07` | Platform imagery would imply a coordination process that is **not evidenced as configured** |
| `M02-S10` | A permissions view invites exactly the access-equals-authority inference the slide refutes |

**No live Autodesk observation is required, and none is requested.** The safety
boundary in root [`README.md`](../../../README.md) §2.1 applies unmodified.

---

## 6. Register summary

| Measure | Value |
|---|---|
| Slide visual sources created | **14** (`M02-S01`–`M02-S14`) |
| `SOURCE COMPLETE` | **13** slide visuals; 10 evidence visuals |
| `SOURCE PARTIAL` | **1** (`M02-S12` / `R4`, deliberately split) |
| `EXTERNAL EVIDENCE REQUIRED` | **0** |
| `OPTIONAL LIVE OBSERVATION` | **0** |
| `DEFERRED` / `EXCLUDED` | **0** |
| Rendered assets | **0** — see [`rendered/README.md`](rendered/README.md) |
| **Slides deliverable from repository source alone** | **14 of 14** |
| Slides with a mandatory presentation warning | **14 of 14** |
