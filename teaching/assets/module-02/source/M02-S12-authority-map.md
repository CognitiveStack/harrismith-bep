# M02-S12 — One process, several distinct authorities

| Field | Value |
|---|---|
| **Visual identifier** | `M02-S12` |
| **Related slide** | Slide 12 |
| **Slide title** | One process, several distinct authorities |
| **Teaching purpose** | Answer "who may decide each kind of information action?" — including where the answer is nobody |
| **Principal sources** | `supporting/information-management-responsibility-matrix.md` §3.1–3.7, §6; `bep/Harrismith-Fire-Station-BEP.md` §9.4, §9.7, §9.8, §12.7, §12.9; `supporting/cde-workflow-state-strategy.md` §3.2; `supporting/coordination-review-strategy.md` §19 |
| **Evidence classification** | **DIRECT** for each allocation; **INTERPRETATION** for the status vocabulary and the distribution; **SYNTHESIS** for the required message |
| **Known limitation** | Three authorities are **UNRESOLVED**, one is **OUTSIDE IM AUTHORITY**, and **allocated does not mean contractually established** |
| **Presentation warning** | **No vertical hierarchy. BIM Manager not at the top. No unresolved row hidden.** If space forces a cut, drop allocated rows — never unresolved ones |
| **Evidence source consumed** | `R4` |
| **Increment** | T2-D |

---

## 1. Status classes — six, defined on the slide

| Class | Meaning |
|---|---|
| **`ALLOCATED`** | The matrix assigns it to a named function |
| **`CONDITIONAL`** | Held only where governance expressly allocates it, or varies by case |
| **`UNRESOLVED`** | Recorded as TBD; no function holds it |
| **`BLOCKED`** | Cannot currently be exercised at all |
| **`RECIPIENT-DEPENDENT`** | Depends on a delivery arrangement that does not yet exist |
| **`OUTSIDE IM AUTHORITY`** | Not allocated to any information-management function |

**Do not collapse these into one "approved" status.** Six distinct labels, six
distinct meanings.

## 2. Full authority register — all sixteen

**Table form, not Mermaid.** A diagram of sixteen authorities against nine
functions is unreadable at projection scale, and any node arrangement implies a
relationship the register does not assert.

| # | Authority | Held by | Status |
|---|---|---|---|
| 1 | Authoring | Author | `ALLOCATED` |
| 2 | Task-team technical / content checking | Checker | `ALLOCATED` |
| 3 | Information-quality / readiness checking | Checker | `ALLOCATED` |
| 4 | Coordination (process) | BIM Coordinator | `ALLOCATED` |
| **5** | **Authorisation for controlled sharing** | **Task-Team Lead** | **`ALLOCATED` — the clearest established authority** |
| 6 | Authorisation to consume Shared information | Task-Team Lead | `ALLOCATED` |
| **7** | **Publication / exchange** | **—** | **`UNRESOLVED` · `BLOCKED`** |
| **8** | **Technical / design approval** | Originating task team retains technical responsibility | **`OUTSIDE IM AUTHORITY`** |
| **9** | **Governance change, by class** | **—** | **`UNRESOLVED`** |
| 10 | Receipt of exchange | Receiving / recipient function | `ALLOCATED` |
| **11** | **Acceptance for a stated purpose** | **—** | **`UNRESOLVED` · `RECIPIENT-DEPENDENT`** |
| 12 | Issue-response verification | BIM Coordinator | `ALLOCATED` — expressly **not** design approval |
| 13 | Issue closure | Per governed criteria, after re-coordination | `CONDITIONAL` |
| 14 | Implementation verification | Varies by change type | `CONDITIONAL` — no universal verifier |
| 15 | Escalation of unresolved interfaces | BIM Coordinator | `ALLOCATED` |
| 16 | Platform configuration implementation | CDE Administration | `ALLOCATED` — implements only |

**Ten allocated · two conditional · three unresolved · one outside.**

## 3. Simplified primary visual — eight to ten rows

The full sixteen-row register is dense for a one-minute slide. **The primary
visual carries the distribution and the exceptions; the full register becomes a
presenter-only or appendix layout.**

Recommended slide set — **all four non-allocated rows plus four representative
allocated ones**:

| Authority | Status |
|---|---|
| Authoring · checking · coordination | `ALLOCATED` |
| **Authorisation for controlled sharing** | **`ALLOCATED` — established** |
| Platform configuration implementation | `ALLOCATED` — implements only |
| **Issue closure · implementation verification** | **`CONDITIONAL`** |
| **Publication / exchange** | **`UNRESOLVED` · `BLOCKED`** |
| **Governance change, by class** | **`UNRESOLVED`** |
| **Acceptance for a stated purpose** | **`UNRESOLVED` · `RECIPIENT-DEPENDENT`** |
| **Technical / design approval** | **`OUTSIDE IM AUTHORITY`** |

**Do not delete unresolved authorities to save space.** Ten allocated
authorities are unsurprising; three unresolved ones are the teaching.

## 4. Mandatory design requirements

| # | Requirement |
|---|---|
| 1 | **No vertical hierarchy** — BEP §5.2: not an appointment or organisation chart |
| 2 | **BIM Manager not at the top**, and not in a distinguished position. It holds none of the sixteen as a decision right |
| 3 | **Unresolved rows always visible** |
| 4 | **Technical / design approval clearly outside IM authority** — a distinct visual class, not an empty allocated row |
| 5 | **`ALLOCATED` does not mean contractually established.** Only row 5 is described by the sources as established |
| 6 | **Row 5 identified as the clearest established authority** |

## 5. The sourced line that carries the slide

IM matrix §3.7, A2 note:

> **No single universal approver exists**, and **unlimited authority is not
> assigned to the BIM Manager**.

The required authority *corresponds to the nature of the decision*.

## 6. Simplification and omission

| Simplify | Omit |
|---|---|
| Eight to ten rows on the slide; sixteen in the appendix | The full nine-column matrix grid |
| Six status labels, consistently styled | **Any RACI letter** |
| — | Any single status colour covering everything |
| — | Any holder name |

## 7. Required message

> A mature BIM governance model does not search for one universal approver; it
> defines the correct authority for each decision.

**Teaching synthesis.** The no-universal-approver position is sourced; the
maturity framing is not.

## 8. Overclaim risk

**High if unresolved rows are cut for space.** A register showing only allocated
authorities asserts a complete authority model, which is precisely what the
sources decline to claim.
