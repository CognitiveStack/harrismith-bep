# BEP Working Register

## Document purpose and status

**Purpose.** The lightweight incoming record for contributions moving through
the Working Process — questions, proposals, problems, clarifications,
improvements, training needs and exception requests.

| Field | Value |
|---|---|
| Document status | **Controlled Draft / Working Record** |
| Authority | None. Supports the Working Process |
| Approval | **Not approved** as part of BEP Training Baseline 0.1 |
| Supports | `working/README.md` — the Working Process |

## What this register is not

**This is not the authoritative governance decision register.** Governance
decisions are recorded in `supporting/governance-decision-register.md`, and
nowhere else. A status of **APPROVED** here means this process reached an
approved outcome or route — it does **not** create APPROVED GOVERNANCE.

**This is not an Issue database.** Operational coordination and model actions
requiring assignment, tracking, resolution and verification belong in governed
project Issues (Working Process WP10).

**Working IDs are working-process identifiers.** `WP-001` and similar are not
Governance Register decision IDs, not Forma Issue IDs, and not contractual
document numbers.

## Register fields

| Field | Note |
|---|---|
| Working ID | `WP-nnn` |
| Type | QUESTION / PROPOSAL / PROBLEM / CLARIFICATION / IMPROVEMENT / TRAINING NEED / EXCEPTION REQUEST |
| Topic | Short subject |
| Raised By Role | **Role or function — never a person's name** |
| Description | What was asked or observed |
| Why It Matters | Consequence if unaddressed |
| Affected Area | Process, document or platform affected |
| Suggested Outcome | Optional |
| Status | NEW / UNDER REVIEW / DECISION REQUIRED / APPROVED / REJECTED / DEFERRED / IMPLEMENTING / VERIFICATION REQUIRED / CLOSED |
| Triage Function | Which function triages it |
| Governance Decision Required? | Yes / No / To be determined |
| Related Governance ID | Governance Register reference, where one exists |
| Related Issue | Governed project Issue reference, where one exists |
| Implementation / Verification Note | What was applied, and what was checked |
| Outcome / Closure Note | Why it closed |

**Dates are recorded only where actually known.** None is invented.

---

## 1. Active register

| Working ID | Type | Topic | Status |
|---|---|---|---|
| — | — | — | — |

***No active entries.*** The Working Process is defined and ready to receive
contributions; none has been raised.

---

## 2. Illustrative training example

> ### ⚠ ILLUSTRATIVE TRAINING EXAMPLE — NOT AN ACTIVE REGISTER ENTRY
>
> The record below is **not** an active contribution, **not** a historical
> record, and **did not occur**. It exists to show how a contribution moves
> through the Working Process and hands over to the governance route. It is
> deliberately held outside the active register in section 1.

| Field | Illustrative value |
|---|---|
| Working ID | `WP-EX-01` — example identifier, deliberately outside the `WP-nnn` active series |
| Type | **QUESTION** |
| Topic | Intended Design Collaboration team-space mapping |
| Raised By Role | Task-Team Lead function |
| Description | *"What should the intended MEP / Structural Design Collaboration team-space mapping be?"* |
| Why It Matters | Until the intended mapping is decided, the observed configuration cannot be assessed, corrected or verified, and coordination routing remains uncertain |
| Affected Area | Design Collaboration team-space configuration; BEP 4.5 and 4.7; CDE Workflow & State Strategy |
| Suggested Outcome | None offered — the contributor asks the question rather than proposing an answer |
| Status | **DECISION REQUIRED** |
| Triage Function | **BIM Manager** — this is a governance matter, not a platform administration task |
| Governance Decision Required? | **Yes** |
| Related Governance ID | **UD-001** — already recorded and **already unresolved** |
| Related Issue | None |
| Implementation / Verification Note | None. No decision exists, so nothing can be implemented or verified |
| Outcome / Closure Note | Not closed. Remains with the governance route |

**How the handover works in this example:**

```
Working contribution (QUESTION)
  → triage by BIM Manager function
  → DECISION REQUIRED
  → hands over to the Governance & Decision Register
  → UD-001 (existing, unresolved)
```

**What this example deliberately does not do:**

- **It does not resolve UD-001.** UD-001 remains **UNRESOLVED**.
- **It does not propose the intended mapping.** No replacement binding is
  suggested here or anywhere else in this repository.
- **It does not duplicate UD-001 as a new governance decision.** The contribution
  *points at* the existing register entry; it does not create a second record of
  the same matter.
- **It does not imply this record existed historically.** Nobody raised this
  question; it is a teaching device.
- **It carries no date and no participant name.**

**The governance point being illustrated:** a participant can raise a governance
question through an easy, low-friction route, and that question reaches the
governance system without the participant acquiring any authority to answer it.
The contribution ends at **DECISION REQUIRED**. The decision belongs elsewhere,
and has not been taken.
