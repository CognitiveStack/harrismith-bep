# Module 7 — Translation Decision Register Schema

**Status:** **`ARCHITECTURE BASELINE — PENDING CHATGPT GOVERNANCE REVIEW`.**
**Teaching material. Not governance.**

**This file defines the future Translation Decision Register. It is not the
register.** No register exists, no row exists, and no row may be created under
this schema until register population is expressly authorised as its own
increment.

---

## 1. What the register will be

A controlled record, one row per translation decision, tracking each matter
from Harrismith reference pattern to a governed Triviron position — with every
unknown typed and visible. It implements the sequence in
[`translation-framework.md`](translation-framework.md) and is bounded by the
STOP register in [`README.md`](README.md) §9.

**What the register is not:** a Triviron BEP; a source of authority; a place
where a Harrismith value may quietly become a Triviron answer.

## 2. Field definitions

| # | Field | Semantics | Constraints |
|---|---|---|---|
| 1 | **Decision ID** | Stable identifier for the translation matter, unique within the register | Identifies the row only. Not a Triviron document or clause reference |
| 2 | **Decision domain** | One of the seven accepted domains (README §7) | Exactly one; no eighth domain without governance review |
| 3 | **Decision topic** | One sentence naming the matter Triviron must decide | Phrased as a matter to decide, never as an answer |
| 4 | **Harrismith reference pattern** | The controlled pattern the question derives from | **Exact repository path; exact section/identifier where practical; the source's own declared status; its source class** (see §6) |
| 5 | **What transfers as method** | The question, distinction or analytical pattern that is reusable | Method only — never a value, allocation, identifier, tolerance or platform |
| 6 | **What explicitly does not transfer** | The Harrismith-specific content excluded from transfer | Stated positively per row; the README §6 exclusions apply to every row in addition |
| 7 | **Triviron evidence required** | The class F source/fact/decision needed before the matter can be responsibly framed | Names the kind of controlled source required, not a guessed content |
| 8 | **Triviron evidence currently available** | What class F actually holds against field 7 | Currently `NONE IDENTIFIED` in all cases; only controlled sources count |
| 9 | **Triviron evidence missing** | The gap between fields 7 and 8 | Typed; never blank |
| 10 | **Current translation classification** | One value from §3 | May not be `ESTABLISHED` for any populated Triviron answer under the current evidence position |
| 11 | **Candidate decision** | A future, expressly authorised candidate arrangement | **Schema-only in T7-B.** Population rules in §7. Always labelled `PROPOSED — NOT APPROVED` until approved |
| 12 | **Decision authority required** | The authority that must take the decision | **Exact source-grounded Triviron value, or a typed absence** (§5). Never inferred |
| 13 | **Decision owner** | The holder responsible for progressing the matter | Same rule as field 12. No simulated function may be invented to fill it |
| 14 | **Candidate BEP destination** | Conceptual destination class in the future Triviron BEP architecture | **Class only** (§8): no section numbers, clause numbers, filenames, schedule identifiers or template names. Exact destination `NOT YET ESTABLISHED` |
| 15 | **Dependent matrix / schedule / appendix** | Other future controlled artefacts the decision would populate or constrain | Conceptual class only, as field 14 |
| 16 | **Implementation dependency** | What must exist or be decided before the decision could be implemented | A dependency is not evidence the dependency is met |
| 17 | **Open question** | The sharpest unresolved question on the row | Preserved, not smoothed; conflicts recorded as conflicts |
| 18 | **Status** | One value from the status vocabulary in §4 | The vocabulary's distinctions are mandatory; terms are not interchangeable |
| 19 | **Source / decision references** | Every source and decision record the row relies on | Paths and identifiers; teaching sources cited only as `TEACHING INTERPRETATION — NOT GOVERNANCE` |
| 20 | **Notes / boundary warning** | Row-specific overclaim risks and boundary reminders | Carries the applicable `M7-S` STOP conditions where relevant |

## 3. Current translation classification

A controlled enumeration for field 10. It is **distinct from** source authority
class (source-inventory §1), Harrismith statement classification (root
`README.md` §6), any Issue status, and any decision status — none of those
vocabularies may be substituted for it.

| Value | Meaning |
|---|---|
| **`METHOD`** | A Harrismith question, distinction or analytical pattern is reusable, but **no Triviron answer follows from it** |
| **`EVIDENCE REQUIRED`** | A Triviron fact/source is required before a decision can be responsibly framed |
| **`DECISION REQUIRED`** | The necessary context may be available, but an authorised Triviron governance decision remains outstanding |
| **`PROPOSAL`** | A candidate Triviron arrangement has been **expressly authorised for proposal development** but is not approved |
| **`ESTABLISHED`** | A controlled Triviron source or authorised governance decision establishes the position |

**Standing constraint:** because `T7-A` found
`NO CONTROLLED TRIVIRON GOVERNANCE FACT`, **no Module 7 architecture file may
currently claim any Triviron decision is `ESTABLISHED`**, and no `PROPOSAL`
content is created in this increment.

## 4. Status vocabulary

Controlled values for field 18 and for status statements across Module 7.
**These terms are not interchangeable**, and using one where another is meant
is itself a defect.

| Value | Meaning | Not to be used when |
|---|---|---|
| **`NOT YET ESTABLISHED`** | The programme does not currently possess sufficient controlled evidence and/or authorised decision to establish the matter | Evidence positively shows the arrangement does not exist — that is `NOT ESTABLISHED` |
| **`NOT ESTABLISHED`** | Controlled evidence **positively establishes** that the relevant arrangement does not currently exist or has explicitly not been established | No evidence was found either way — **absence of evidence is `NOT YET ESTABLISHED`, never `NOT ESTABLISHED`** |
| **`UNRESOLVED`** | The matter is recognised and has been considered, but remains open, conflicting, dependent or undecided | The matter has simply not been examined yet |
| **`TBD`** | The matter lies **within an established governance scope** but its value has intentionally been deferred for later determination | There is no established scope to defer within — **`TBD` is not a generic blank** |
| **`PROPOSED — NOT APPROVED`** | A candidate governance arrangement exists but carries no approved authority | No authorised candidate exists |
| **`ESTABLISHED`** | A controlled Triviron source or authorised decision positively establishes the position | **Currently prohibited for any populated Triviron answer** — class F is empty |

Worked contrast, from the existing controlled record: Harrismith's
assurance-sampling method is **`NOT ESTABLISHED`** because sources were
examined and positively record that no method is defined; a Triviron
publication authority is **`NOT YET ESTABLISHED`** because no Triviron source
exists to examine. The two must never be swapped.

## 5. Authority and owner field rules — fields 12 and 13

These fields may contain **only**:

- an **exact source-grounded Triviron value** — cited to a class F controlled
  source or an authorised governance decision record; or
- a **typed absence/status** from §4.

Authority and ownership are **never inferred** from:

- a job title;
- software permissions;
- a Harrismith role allocation;
- teaching architecture;
- likely industry practice;
- a company name;
- tool availability.

**No simulated Triviron authority function may be created merely to populate
these fields.** If the programme later needs a simulated/training Triviron
decision function — as Harrismith's publication planning needed `AG-001`–
`AG-005` — that requires a **separate expressly authorised governance
increment**, and until then the fields carry the current unsupported state:

**`NOT YET ESTABLISHED`**

## 6. Harrismith reference rule — field 4

Every future `Harrismith reference pattern` entry must identify:

- the **exact repository path**;
- the **exact section/identifier** where practical;
- the source's **own declared status**;
- the **source class** from [`source-inventory.md`](source-inventory.md).

A teaching source may be used only as
**`TEACHING INTERPRETATION — NOT GOVERNANCE`**. **A Module 1–6 PowerPoint must
never be used as authority over its Markdown source** — the external decks are
derivative outputs. **Where a controlled Harrismith source and a teaching
synthesis differ, the controlled source governs what Harrismith actually
establishes.**

## 7. Candidate decision rule — field 11

The `Candidate decision` field must not become a route for smuggling Harrismith
values into Triviron. In the future it may be populated **only** when all five
conditions hold:

1. relevant **Triviron evidence has been identified** (fields 7–9 reconciled);
2. that evidence's **status and authority are recorded**;
3. the **proposal stage has been expressly authorised** by governance;
4. the candidate is labelled **`PROPOSED — NOT APPROVED`**;
5. the **required decision authority is identified**, or its absence explicitly
   recorded under §5.

**For T7-B the field is schema-only. No candidate decision may be written, and
none has been.** The framework's STOP rule applies in addition: no candidate
may be derived solely from a populated Harrismith value.

## 8. Candidate BEP destination rule — fields 14 and 15

The future target is a **project-specific Triviron BEP**, but its exact
document architecture has **not been established**. These fields may therefore
identify **only a conceptual destination class**, for example:

- main BEP clause;
- responsibility matrix;
- information-delivery schedule;
- CDE strategy;
- coordination / review strategy;
- controlled appendix;
- decision register;
- other controlled project schedule.

The following may **not** be invented: Triviron section numbers; Triviron
clause numbering; document filenames; schedule identifiers; corporate template
names. **The exact destination remains `NOT YET ESTABLISHED` until a future
Triviron BEP architecture is controlled.**

## 9. Empty-shape sample — field names and typed placeholders only

The only permitted sample. **It contains no Triviron governance, illustrative
or otherwise, and must not be extended into one.**

| # | Field | Typed placeholder |
|---|---|---|
| 1 | Decision ID | `<identifier — assigned at authorised population>` |
| 2 | Decision domain | `<one of the seven domains>` |
| 3 | Decision topic | `<matter to decide — phrased as a question owner, not an answer>` |
| 4 | Harrismith reference pattern | `<exact path §ref — declared status — source class>` |
| 5 | What transfers as method | `<question / distinction / pattern only>` |
| 6 | What explicitly does not transfer | `<the Harrismith-specific content excluded>` |
| 7 | Triviron evidence required | `<kind of controlled class F source needed>` |
| 8 | Triviron evidence currently available | `NONE IDENTIFIED` |
| 9 | Triviron evidence missing | `<typed gap>` |
| 10 | Current translation classification | `METHOD` or `EVIDENCE REQUIRED` *(the only values presently reachable)* |
| 11 | Candidate decision | *(schema-only — may not be written in this increment)* |
| 12 | Decision authority required | `NOT YET ESTABLISHED` |
| 13 | Decision owner | `NOT YET ESTABLISHED` |
| 14 | Candidate BEP destination | `<conceptual class only>` — exact destination `NOT YET ESTABLISHED` |
| 15 | Dependent matrix / schedule / appendix | `<conceptual class only>` |
| 16 | Implementation dependency | `<typed dependency>` |
| 17 | Open question | `<preserved question>` |
| 18 | Status | `<one §4 value>` |
| 19 | Source / decision references | `<paths and identifiers>` |
| 20 | Notes / boundary warning | `<applicable M7-S STOP conditions>` |
