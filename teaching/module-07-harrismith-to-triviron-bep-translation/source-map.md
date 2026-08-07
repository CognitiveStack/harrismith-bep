# Module 7 — Source Map

**Status:** **`ARCHITECTURE BASELINE — ACCEPTED after T7-B-R`.** The
acceptance covers the Module 7 teaching-architecture baseline (`T7-B`) only —
it is not Triviron governance and does not accept `T7-C`.
**Teaching material. Not governance.**

How Modules 1–6 and the controlled Harrismith sources feed Module 7 as
**teaching inputs and reference patterns** — without any of them becoming
Triviron governance.

---

## 1. Three relationships, never merged

Every mapping in this file carries exactly one of three relationship labels:

| Label | Meaning |
|---|---|
| **`GOVERNS HARRISMITH`** | The source governs (or records governance of) the Harrismith training implementation, at its own declared status. Its authority stops at Harrismith |
| **`TEACHES METHOD`** | The source supplies a question, distinction or analytical pattern reusable in the translation framework. It governs nothing |
| **`REQUIRED TO ESTABLISH TRIVIRON`** | The class of controlled Triviron source or authorised decision that would be needed to establish a Triviron position. **Currently `NONE IDENTIFIED`** |

**No arrow in this file — and no arrow anywhere in Module 7 — may mean
`HARRISMITH VALUE → TRIVIRON VALUE`.** Arrows carry questions and method
downstream; they never carry answers.

## 2. Modules 1–6 as Module 7 inputs

Each module feeds Module 7 as **`TEACHES METHOD`** only.

| Teaching input | Feeds Module 7 with | What would be `REQUIRED TO ESTABLISH TRIVIRON` in that area |
|---|---|---|
| **Module 1** → BEP purpose and document status | What a BEP is for; status/authority discipline; the transfer-chain pattern (worked example → questions → decisions not yet taken → a Triviron BEP not yet developed by this programme) | A Triviron appointment context and a governed decision to develop a Triviron BEP with a controlled status scheme |
| **Module 2** → roles, functions, holders and authority | Function ≠ organisation ≠ person; authority from governance, not permission; the assignment-sequence discipline (permissions after authorities) | Triviron organisational facts, appointments and authority decisions, from controlled Triviron sources |
| **Module 3** → information-management / ISO 19650 evidence discipline | External-source registration; jurisdiction limits; `No conformity conclusion supported`; never teaching a draft as a requirement | A Triviron decision on applicable standards and any conformity claims, plus the licensed source basis for them |
| **Module 4** → CDE states and transition governance | State ≠ folder; transition ≠ file movement; governance before configuration; governance status ≠ implementation status | Triviron CDE governance decisions and platform facts, from controlled Triviron sources |
| **Module 5** → responsibility allocation and information delivery | Allocation ≠ performance; delivery event ≠ state transition; the typed-absence discipline; two matrices never merged | Triviron parties, task teams, containers, events and recipient facts |
| **Module 6** → coordination, review, authorisation, acceptance, verification and assurance | The seven decision domains; check ≠ authorise ≠ accept; completion ≠ zero clashes; verification/authorisation/publication/acceptance as distinct acts; the accepted transfer / does-not-transfer table | Triviron coordination-governance decisions, check/tolerance decisions, taxonomy decisions and authority decisions |

## 3. Controlled Harrismith families beneath the teaching layer

The modules above interpret these controlled families. Each family is
**`GOVERNS HARRISMITH`** (at its own declared status) and simultaneously
**`TEACHES METHOD`** to Module 7. **Neither label ever amounts to establishing
a Triviron fact.**

| Controlled family | Path | Declared status | Method it teaches |
|---|---|---|---|
| Main BEP | `bep/Harrismith-Fire-Station-BEP.md` | APPROVED WITH CONDITIONS — Training Baseline 0.1; Authority: None (training) | Reference architecture; classification; vocabularies; separations |
| Responsibility matrices | `supporting/information-management-responsibility-matrix.md` · `supporting/model-information-responsibility-matrix.md` | APPROVED WITH CONDITIONS; allocations largely proposals | Allocation grammar; typed absence; complementary matrices |
| Delivery schedule | `supporting/information-delivery-schedule.md` | APPROVED WITH CONDITIONS; entries `PROPOSED GOVERNANCE` | Event-based planning; typed blockers |
| CDE strategy | `supporting/cde-workflow-state-strategy.md` | APPROVED WITH CONDITIONS; `PROPOSED GOVERNANCE` | State/transition governance |
| Coordination & review strategy | `supporting/coordination-review-strategy.md` | APPROVED WITH CONDITIONS; `PROPOSED GOVERNANCE` unless stated | Cycle, checks, triage, verification as governed choices |
| Governance & decision register | `supporting/governance-decision-register.md` | Controlled register, approved with conditions | Decision/observation/assumption typing; discrepancies recorded, not corrected |
| Decision, validation and observation records | `docs/` | Each declares its own status; several `Authority: None` | Candidate → readiness → decision → condition; bounded authorised observation |
| Project standards | `standards/` | **Not established** | An absence recorded as an absence |

## 4. The map, drawn once

```text
controlled Harrismith sources ──────────────── GOVERNS HARRISMITH (only)
        │
        │  interpreted by
        ▼
Modules 1–6 teaching material ──────────────── TEACHES METHOD (only)
        │
        │  questions · distinctions · discipline
        ▼
Module 7 translation framework ─────────────── TEACHES METHOD (only)
        │
        │  defines evidence requirements
        ▼
class F: controlled Triviron sources ───────── REQUIRED TO ESTABLISH TRIVIRON
        │      may establish Triviron FACTS —   (currently NONE IDENTIFIED)
        │      the controlled evidence basis
        │
        │  informs — evidence does not itself decide
        ▼
authorised Triviron governance decisions ───── may establish governed Triviron
                                               DECISIONS and ARRANGEMENTS
                                               (none currently recorded in
                                               this programme)
```

**Reading rule:** the first three tiers can never produce an `ESTABLISHED`
Triviron position, however complete they become. Only the last two tiers can,
and they establish **different kinds of thing**:

- a **controlled Triviron source** may establish a Triviron **fact** — the
  controlled evidence basis;
- an **authorised Triviron governance decision** may establish a **governed
  Triviron decision or arrangement**.

**Either may support an `ESTABLISHED` register position where semantically
appropriate** — a factual matter rests on a controlled source; a governed
arrangement rests on an authorised decision. **Evidence does not automatically
create a governance decision; a governance decision is not needed to establish
every factual matter; and a factual source never authorises an arrangement.**
No class F source is currently identified, and no authorised Triviron decision
is currently recorded in this programme. **No edge in this diagram carries a
value from the Harrismith side to the Triviron side.**

## 5. Boundary restatements

- **`GOVERNS HARRISMITH` is not `TEACHES METHOD`**: a source's authority over
  Harrismith adds nothing to its weight as method — method is judged by
  usefulness, authority by the source's own declaration.
- **`TEACHES METHOD` is not `REQUIRED TO ESTABLISH TRIVIRON`**: no quantity of
  method substitutes for a single controlled Triviron source.
- The STOP register in [`README.md`](README.md) §9 applies to every mapping in
  this file.
- The `T7-A` census position stands:
  **`NO CONTROLLED TRIVIRON GOVERNANCE FACT IDENTIFIED IN T7-A`** — the
  repository holds Triviron teaching questions and placeholders, and no
  controlled Triviron source.
