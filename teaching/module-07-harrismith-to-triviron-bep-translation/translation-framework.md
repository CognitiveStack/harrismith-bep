# Module 7 — Translation Framework

**Status:** **`ARCHITECTURE BASELINE — PENDING CHATGPT GOVERNANCE REVIEW`.**
**Teaching material. Not governance.**

This file defines the conceptual method by which the Harrismith reference
implementation is translated into the evidence requirements and governed
decisions needed for a future project-specific Triviron BEP.

**The method is the deliverable. No translation is performed in this file, and
no Triviron answer appears anywhere in it.**

---

## 1. The principal sequence

```text
reference pattern
  → translation question
  → Triviron evidence required
  → evidence available / missing
  ─── STOP RULE ───
  → candidate decision
  → authority required
  → recorded status
  → candidate BEP / matrix / schedule / appendix destination
```

**The arrows indicate analytical progression only.** They record the order in
which the translation problem is worked, not a pipeline through which content
flows. **Nothing moves along these arrows: no Harrismith value becomes a
Triviron answer by traversing them.** Every step can — and today does — end in
a typed absence.

## 2. Purpose of each step

### 2.1 Reference pattern

Identify **exactly** what Harrismith establishes, from a controlled source at
its own declared status: a governed distinction, a structural choice, a
recorded refusal, a typed absence. The pattern is cited by exact path and
section, with its source class from
[`source-inventory.md`](source-inventory.md). **A pattern is what Harrismith
did or deliberately left open — never a recommendation.**

### 2.2 Translation question

Convert the pattern into the question a Triviron project must answer for
itself. The question inherits the pattern's **structure**, not its content:
*"Harrismith allocates check and authorise to different functions — which
functions will Triviron separate, and who decides that?"* The Modules 1–6
Slide 14 question sets are prior worked examples of this step.

### 2.3 Triviron evidence required

State which controlled Triviron source, fact or decision record would be needed
before the question can be responsibly framed for decision: an appointment, an
organisational fact, a client requirement, a platform decision, a governance
decision record. **This step defines what class F of the source inventory must
eventually contain.**

### 2.4 Evidence available / missing

Record what class F currently holds against that requirement. **Current
position for every question: class F is `NONE IDENTIFIED`**, so this step
records typed absence — and records it visibly rather than skipping ahead.

### 2.5 — STOP RULE —

**No Triviron candidate decision may be derived solely from a populated
Harrismith value.**

A candidate decision requires **an independently established Triviron basis**
(class F evidence, recorded at steps 2.3–2.4) **and a later expressly
authorised proposal stage**. If the only support for a candidate is that
Harrismith did it, the sequence stops here and the matter is recorded as
`METHOD` or `EVIDENCE REQUIRED` — it does not proceed.

### 2.6 Candidate decision

Only after the STOP rule is satisfied: frame the candidate Triviron
arrangement, labelled **`PROPOSED — NOT APPROVED`**, with its evidence basis
cited. **This step is schema-only in the current baseline — no candidate
decision exists, and none may be written in this increment.**

### 2.7 Authority required

Identify which authority must take the decision — from an exact source-grounded
Triviron value, or record **`NOT YET ESTABLISHED`**. Authority is never
inferred from job titles, software permissions, Harrismith allocations,
teaching architecture, industry practice, company names or tool availability
(see the schema's authority rules).

### 2.8 Recorded status

Type the matter's current position using the controlled status vocabulary in
[`translation-decision-register-schema.md`](translation-decision-register-schema.md)
§4. **The status is part of the record, not a formality** — an untyped gap is
the failure mode this framework exists to prevent.

### 2.9 Candidate destination

Identify the **conceptual destination class** in the future Triviron BEP
architecture — main BEP clause, matrix, schedule, strategy, appendix, register
— per the schema's destination rule. **No Triviron section number, clause
number, filename or template name has been established in this programme**, so
the exact destination remains `NOT YET ESTABLISHED`.

## 3. Seven kinds of thing, kept apart

The framework fails when these are blurred. Every Module 7 statement is one of
these and is labelled accordingly:

| Kind | What it is | What it is not |
|---|---|---|
| **Source evidence** | A controlled source's own content, at its own declared status | Truth about anything the source does not cover |
| **Interpretation** | A reading of source evidence, traceable to it | New evidence |
| **Reference method** | A reusable question, distinction or pattern extracted from Harrismith | A recommendation or a default answer |
| **Proposal** | A candidate arrangement, expressly authorised for development, `PROPOSED — NOT APPROVED` | A decision; an observed arrangement |
| **Decision** | An authorised governance act by an identified authority, recorded | Evidence that anything was implemented |
| **Observed implementation** | What a bounded, authorised observation actually found, at its level and time | Governance; proof of anything unobserved |
| **Teaching synthesis** | Explanation constructed for the audience | Governance, evidence or a source |

Two consequences already in force elsewhere in the programme carry into
Module 7 unchanged: **a responsibility allocation is not evidence the activity
occurred**, and **a status label is not technical evidence**.

## 4. Worked shape — with no content

The only worked example this baseline permits is the empty shape:

```text
reference pattern:        <exact path §ref — declared status — source class>
translation question:     <question derived from the pattern's structure>
evidence required:        <the class F source that would be needed>
evidence available:       NONE IDENTIFIED (no class F source is currently identified)
─ STOP rule applies — no candidate may be derived from the Harrismith value ─
candidate decision:       (schema-only; none may be written in this increment)
authority required:       NOT YET ESTABLISHED
recorded status:          <from the controlled status vocabulary>
candidate destination:    <conceptual class only> — exact destination NOT YET ESTABLISHED
```

**Populating this shape with real Triviron content is register work, governed
by the schema, and requires its own authorised increments.**
