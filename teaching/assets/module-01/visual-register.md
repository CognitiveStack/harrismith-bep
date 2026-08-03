# Module 1 — Visual Register

**Status:** Visual-source baseline. **Not governance.** No rendered assets exist.

Controlling document:
[`../../module-01-what-is-a-bep/visual-demonstration-plan.md`](../../module-01-what-is-a-bep/visual-demonstration-plan.md).
Its visual identifiers `V1`–`V10`, evidence classifications and overclaim
warnings are authoritative and are **not renumbered here**.

---

## 1. Two identifier spaces

The visual plan uses two kinds of entry, and this register preserves both.

| Space | Meaning |
|---|---|
| **`V1`–`V10`** | **Evidence sources** identified in the plan's §2 — candidate material drawn from the repository or requiring external capture |
| **`M01-S01`–`M01-S14`** | **Slide visual sources** created in this increment, one per slide, keyed to the plan's §2A and §2B slide-specific entries |

The two are related but not interchangeable. `V3`, for example, is the
information-management responsibility matrix as an *evidence source*; `M01-S07`
is the *slide visual* that uses an extract of it.

## 2. Status definitions

| Status | Meaning |
|---|---|
| **`SOURCE COMPLETE`** | Reviewable text-based source exists and is sufficient to produce the visual |
| **`SOURCE PARTIAL`** | Source exists but a decision or element is deliberately left open |
| **`EXTERNAL EVIDENCE REQUIRED`** | Cannot be produced from the repository; needs material that does not exist here |
| **`OPTIONAL LIVE OBSERVATION`** | Repository-derivable, but a later bounded read-only observation could add value |
| **`DEFERRED`** | Recorded, not developed in this increment |
| **`EXCLUDED`** | Deliberately not produced; reason recorded |

**No status in this register implies that a rendered image exists.** See
[`rendered/README.md`](rendered/README.md).

---

## 3. Slide visual sources — `M01-S01` to `M01-S14`

| ID | Slide | Title | Format | Source file | Rendered | Status |
|---|---|---|---|---|---|---|
| `M01-S01` | 1 | Title slide layout | Layout spec | [`source/M01-S01-title-layout.md`](source/M01-S01-title-layout.md) | — | **SOURCE COMPLETE** (layout); V1 image **EXTERNAL EVIDENCE REQUIRED** |
| `M01-S02` | 2 | The coordination problem | Mermaid | [`source/M01-S02-coordination-problem.md`](source/M01-S02-coordination-problem.md) | — | **SOURCE COMPLETE** |
| `M01-S03` | 3 | The six BEP actions | Mermaid + table | [`source/M01-S03-six-actions.md`](source/M01-S03-six-actions.md) | — | **SOURCE COMPLETE** |
| `M01-S04` | 4 | BEP governance functions | Mermaid | [`source/M01-S04-governance-functions.md`](source/M01-S04-governance-functions.md) | — | **SOURCE COMPLETE** |
| `M01-S05` | 5 | Template vs project-specific | Table | [`source/M01-S05-template-vs-project.md`](source/M01-S05-template-vs-project.md) | — | **SOURCE COMPLETE** |
| `M01-S06` | 6 | Seven-document architecture | Mermaid | [`source/M01-S06-document-architecture.md`](source/M01-S06-document-architecture.md) | — | **SOURCE COMPLETE** |
| `M01-S07` | 7 | Two responsibility matrices | Table + extracts | [`source/M01-S07-matrix-comparison.md`](source/M01-S07-matrix-comparison.md) | — | **SOURCE COMPLETE** |
| `M01-S08` | 8 | Information-delivery planning | Table | [`source/M01-S08-delivery-planning.md`](source/M01-S08-delivery-planning.md) | — | **SOURCE COMPLETE** |
| `M01-S09` | 9 | CDE states and transitions | Mermaid + table | [`source/M01-S09-cde-states.md`](source/M01-S09-cde-states.md) | — | **SOURCE COMPLETE** |
| `M01-S10` | 10 | Folder vs governed status | Mermaid ×2 + table | [`source/M01-S10-folder-vs-status.md`](source/M01-S10-folder-vs-status.md) | — | **SOURCE COMPLETE** |
| `M01-S11` | 11 | Coordination-review cycle | Mermaid | [`source/M01-S11-coordination-cycle.md`](source/M01-S11-coordination-cycle.md) | — | **SOURCE COMPLETE** |
| `M01-S12` | 12 | Issue lifecycle | Mermaid | [`source/M01-S12-issue-lifecycle.md`](source/M01-S12-issue-lifecycle.md) | — | **SOURCE COMPLETE** |
| `M01-S13` | 13 | Approval vs implementation | Table + Mermaid | [`source/M01-S13-approval-vs-implementation.md`](source/M01-S13-approval-vs-implementation.md) | — | **SOURCE COMPLETE** |
| `M01-S14` | 14 | Harrismith-to-Triviron transfer | Mermaid + table | [`source/M01-S14-harrismith-to-triviron.md`](source/M01-S14-harrismith-to-triviron.md) | — | **SOURCE COMPLETE** |

### 3.1 Evidence, classification and risk

| ID | Repository evidence | Evidence classification | External dependency | Later observation? | Overclaim risk |
|---|---|---|---|---|---|
| `M01-S01` | BEP §1.1, §1.2, §2.1, §2.2 | DIRECT status wording; SYNTHESIS framing line | **Yes — V1 hero image** | Yes, for V1 | Low (high if an image is fabricated) |
| `M01-S02` | BEP §1.1, §5.1; Coord §1 | INTERPRETATION; teaching statement SYNTHESIS | No | No | Low |
| `M01-S03` | BEP §1.1 and section architecture | **SYNTHESIS** — six-verb framing | No | No | Low as diagram; moderate as attribution |
| `M01-S04` | IM matrix §3.1 G1, §3.7 A2–A4, §4; BEP §5.2, §5.5, §5.9, §9.10, §12.7 | DIRECT + INTERPRETATION framing | No | No | Low |
| `M01-S05` | IM matrix §6; Model matrix §4, §6; IDS §7; BEP §9.7, §11.12 | **TEACHING SYNTHESIS** (left column has no source) | No | No | Moderate — attribution |
| `M01-S06` | BEP §1.4, §5.12, §13.1, §13.2; CDE §18; IM matrix §7 | DIRECT + INTERPRETATION arrangement | No | No | Moderate |
| `M01-S07` | IM matrix purpose, §1, §2, §3.3; Model matrix purpose, §3.1; BEP §5.12 | DIRECT + INTERPRETATION structure | No | No | Low |
| `M01-S08` | IDS §1, §2, §3, §5.1, §5.3, §7; BEP §10.1, §10.13 | DIRECT + INTERPRETATION grouping + SYNTHESIS message | No | No | Low if timing shown |
| `M01-S09` | CDE §1, §2, §3, §13; BEP §6.1, §6.3, §6.7, §6.8 | DIRECT + INTERPRETATION message | No | Adds little | **Medium** |
| `M01-S10` | CDE §3.1–3.3, §13, §14, §17; BEP §1.5, §5.9, §6.9, §9.7, §9.8 | DIRECT + SYNTHESIS message | No | **Counterproductive** | Low if T4 blocked; high if not |
| `M01-S11` | Coord §1, §6, §7, §8, §12, §17, §21, §26; Model matrix §3.4 | DIRECT + INTERPRETATION compression | No | Possibly later | **High** |
| `M01-S12` | Coord §12, §13, §15, §16, §18, §19, §22, §27 | DIRECT + INTERPRETATION functions | No | **No** | **High — highest in module** |
| `M01-S13` | AD-001 §3, §8, §11; BEP §9.11, §12.3, §12.8, §12.9; CDE §6, §16; Coord §22 | DIRECT + INTERPRETATION + SYNTHESIS message | No | No | **Inverted — risk is underclaiming** |
| `M01-S14` | Unresolved sections across all seven sources; source-map subject 10 | **SYNTHESIS** + DIRECT derivations | **No Triviron source exists** | Not applicable | **High — Triviron-specific** |

### 3.2 Presentation-use warnings

| ID | Warning |
|---|---|
| `M01-S01` | Never fabricate, AI-generate or substitute an image presented as a Harrismith project view |
| `M01-S02` | Never caption as *what went wrong on Harrismith*. These are generic uncertainties, not recorded failures |
| `M01-S03` | Do not attribute "the six verbs" to any Harrismith document. Do not number them as a sequence |
| `M01-S04` | Do not draw a hierarchy — BEP §5.2's model is functional, not an appointment or organisation chart. No named holders |
| `M01-S05` | Say the teaching-synthesis status. No Harrismith source discusses BEP templates |
| `M01-S06` | Plain lines, not arrowheads. Register alongside, not beneath. No completion indicators |
| `M01-S07` | **No RACI terminology**, in the diagram, a legend or an answer. No role holder names |
| `M01-S08` | **No calendar, Gantt fragment, stage sequence or month label.** Show TRN-E03 blocked |
| `M01-S09` | **`Archived` must not appear.** Caption as the governed model, not current behaviour |
| `M01-S10` | **T4 must be shown blocked with its authority unresolved.** Never draw a complete sequence |
| `M01-S11` | Present the tool connection as *how this would work*, never *how this is running* |
| `M01-S12` | If it could be mistaken for an ACC screenshot, redraw it. Closure is not design approval |
| `M01-S13` | **No publication-planning history.** Minimum evidence only; the paused programme is not reopened |
| `M01-S14` | **No Triviron fact.** Final box drawn as visibly not-yet-real |

---

## 4. Evidence sources — `V1` to `V10`

Carried forward from the visual plan §2 without renumbering. These are candidate
*evidence sources*, several of which are consumed by the slide visuals above.

| ID | Title | Consumed by | From repo? | Status |
|---|---|---|---|---|
| `V1` | Harrismith Fire Station project or model image | `M01-S01` | **No** | **EXTERNAL EVIDENCE REQUIRED** |
| `V2` | Extract from the principal BEP | `M01-S06` | Yes | **SOURCE COMPLETE** — via `M01-S06` |
| `V3` | Information-management responsibility matrix | `M01-S07` | Yes | **SOURCE COMPLETE** — via `M01-S07` extract A |
| `V4` | Model / information responsibility matrix | `M01-S07` | Yes | **SOURCE COMPLETE** — via `M01-S07` extract B |
| `V5` | Information-delivery schedule | `M01-S08` | Yes | **SOURCE COMPLETE** — via `M01-S08` |
| `V6` | CDE workflow-state strategy | `M01-S09`, `M01-S10` | Yes | **SOURCE COMPLETE** |
| `V7` | Coordination-review strategy | `M01-S11`, `M01-S12` | Yes | **SOURCE COMPLETE** |
| `V8` | Governance-decision register | `M01-S13` | Yes | **SOURCE PARTIAL** — see note below |
| `V9` | Representative ACC CDE folder or workflow view | — | **No** | **EXTERNAL EVIDENCE REQUIRED** / **OPTIONAL LIVE OBSERVATION** |
| `V10` | Representative Revit or federated-model view | — | **No** | **EXTERNAL EVIDENCE REQUIRED** / **OPTIONAL LIVE OBSERVATION** |

### 4.1 Notes on the evidence sources

**`V8` is SOURCE PARTIAL by design.** The visual plan recommends the **UD-001
evidence table** rather than the register summary, because the summary runs to
more than twenty rows with long status strings, several of which name
publication-planning decisions that are irrelevant to Module 1 and would pull
questions off-topic. `M01-S13` implements the UD-001 lifecycle strip. The register
summary itself is **not** developed as a visual, deliberately.

**`V1`, `V9` and `V10` require material that does not exist in this repository.**
None is a prerequisite for delivering any of the fourteen slides. See §5.

---

## 5. External dependencies — honest position

| ID | What it would need to show | Presentation deliverable without it? |
|---|---|---|
| `V1` | A recognisable building; clean 3D or elevation view; no UI chrome, filenames, user names or dates | **Yes.** `M01-S01` specifies a text-and-space title treatment that works without it |
| `V9` | A representative CDE folder or workflow view, reviewed and cropped | **Yes.** `M01-S09` and `M01-S10` are complete without it — and for `M01-S10` a permissions view would be counterproductive |
| `V10` | Two or three disciplines at one interface, not the whole federated model | **Yes.** `M01-S11` is complete without it |

**All three are optional enrichments, not prerequisites.** Each would require a
separately authorised, bounded, read-only observation — **nothing in this
register authorises one**, and no live Autodesk work was performed in this
increment.

Three standing prohibitions apply to all three:

1. Do not fabricate the image.
2. Do not AI-generate an image and present it as project evidence.
3. Do not substitute a stock or unrelated image captioned as Harrismith.

---

## 6. Register summary

| Measure | Count |
|---|---|
| Slide visual sources created | **14** (`M01-S01`–`M01-S14`) |
| `SOURCE COMPLETE` | **14** slide visuals; 6 evidence sources |
| `SOURCE PARTIAL` | 1 (`V8`, deliberately) |
| `EXTERNAL EVIDENCE REQUIRED` | 3 (`V1`, `V9`, `V10`) |
| `OPTIONAL LIVE OBSERVATION` | 2 (`V9`, `V10`) |
| Rendered assets | **0** — see [`rendered/README.md`](rendered/README.md) |
| Slides deliverable without external material | **14 of 14** |
