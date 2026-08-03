# Module 2 — BIM Management Roles and Responsibilities

**Status:** Active module. Structure and Slides 1–3 baseline only. **Not
governance, and not a complete module.**

---

## 1. Objective

Enable a multidisciplinary audience to understand who does what on a project's
information — and, more importantly, **who is permitted to decide what**.

The module must make these things clear:

| # | The audience should understand |
|---|---|
| 1 | Why BIM roles must be explicit |
| 2 | The difference between a function, an organisation and a named role holder |
| 3 | Who prepares and maintains the BEP |
| 4 | Who contributes technical and project decisions |
| 5 | Who checks information |
| 6 | Who coordinates interfaces |
| 7 | Who authorises information for controlled sharing |
| 8 | Who may publish or exchange information |
| 9 | Who receives and accepts information |
| 10 | What the BIM Manager does |
| 11 | **What the BIM Manager does not automatically do** |
| 12 | What the BIM Coordinator does |
| 13 | **Why coordination responsibility is not design responsibility** |
| 14 | What Task-Team Leads, Authors and Checkers do |
| 15 | What CDE Administration does |
| 16 | **Why platform permissions do not create project authority** |
| 17 | Which Harrismith role holders and authorities remain unresolved |
| 18 | What a future Triviron project must assign for itself |

Items 11, 13 and 16 are the three the audience is most likely to get wrong, and
the module is structured around defeating them.

## 2. Central teaching message

> BIM Management separates production, checking, coordination, authorisation,
> delivery and acceptance so that each project function has clear authority and
> accountability.

**Teaching wording.** No single source sentence says this. It is consistent with
BEP §5.1's responsibility principles and §9.2's decision terminology, both of
which keep these acts deliberately apart — see
[`source-map.md`](source-map.md).

## 3. Primary deliverable

A **20-minute presentation**, using Harrismith as the worked example.

| Field | Value |
|---|---|
| Length | 20 minutes |
| Expected slide count | Approximately 13–14 slides |
| Worked example | Harrismith Fire Station |
| Transfer context | A future Triviron multidisciplinary project |
| Current state | **Content baseline complete — Slides 1–14.** Module not complete |

**The full Slides 1–14 working content baseline exists.** All ten sections of the
timing structure are covered, and the module can be delivered end to end from
this source.

| Slides | Sections covered | Time | State |
|---|---|---:|---|
| 1–3 | Why roles must be explicit; function, organisation and person | 4 min | Drafted |
| 4–9 | Project authority structure; BIM Manager; BIM Coordinator; task-team separation of duties | 10 min | Drafted |
| 10–14 | CDE Administration; the authority chain; the authority map; unresolved holders; Triviron transfer | 6 min | Drafted |

**This presentation does not exist yet, and Module 2 is not complete.** What
remains:

| Outstanding | Note |
|---|---|
| **PowerPoint production** | **Next.** No binary presentation exists; the assembly package in [`presentation/`](presentation/) specifies it |
| **Review** | Follows production — see [`presentation/review-checklist.md`](presentation/review-checklist.md) |
| **Rehearsal and measured timing** | The 20-minute total has never been measured |
| **Rendered visual assets** | **None.** Visual *source* exists for all fourteen slides in [`../assets/module-02/`](../assets/module-02/); no renderer was available |

**Presentation assembly package complete (T2-E).** A concise production handoff
in [`presentation/`](presentation/) — deck specification, on-slide copy,
presenter cues, asset manifest, and production and review checklists. It
condenses roughly 7,000 lines of teaching and visual source into what a producer
needs. **It carries no project governance authority and is not the final
presentation.**

**Visual-source baseline complete (T2-D).** Fourteen reviewable source files,
`M02-S01`–`M02-S14`, with a register, a slide map and recorded design
principles. **All fourteen slides are deliverable from repository source
alone** — Module 2 needs no external evidence at all.

## 4. Scope

**In scope:**

- the role and authority vocabulary the Harrismith sources actually use;
- the boundaries of each function — what it holds and what it does not;
- the separation of authoring, checking, coordinating, authorising, publishing,
  receiving and accepting;
- which holders and authorities Harrismith leaves unresolved;
- what a real project must assign before delivery begins.

**Out of scope for Module 2:**

- ISO 19650 role terminology in its own right — Module 3;
- CDE state mechanics — Module 4;
- reading the matrices row by row — Module 5;
- the coordination cycle in detail — Module 6;
- Triviron BEP development — Module 7;
- workshop facilitation — Module 8.

## 5. Module files

| File | Holds |
|---|---|
| [`presentation-outline.md`](presentation-outline.md) | The 20-minute structure and the developed slides |
| [`speaker-notes.md`](speaker-notes.md) | Delivery notes for Slides 1–3 |
| [`visual-demonstration-plan.md`](visual-demonstration-plan.md) | Candidate visuals for the whole module |
| [`exercises.md`](exercises.md) | Practice and self-assessment |
| [`source-map.md`](source-map.md) | **Role inventory, authority inventory** and statement classification |
| [`../assets/module-02/`](../assets/module-02/) | The visual **source set** — register, slide map and fourteen source files |
| [`presentation/`](presentation/) | The **assembly package** — production handoff for building the deck |

[`source-map.md`](source-map.md) is the load-bearing file in this increment. It
records every role term the sources actually use, with its exact wording, its
boundaries and its unresolved status.

## 6. Relationship to Module 1

Module 1 established three positions that Module 2 depends on and does **not**
re-derive:

| Carried forward | From |
|---|---|
| Preparing, contributing, reviewing, approving and implementing are five distinct functions | Module 1, Slide 4 |
| Permission is not authority; CDE Administration implements governance and does not create it | Module 1, Slide 10 |
| Approval is not implementation, and implementation is not verification | Module 1, Slide 13 |

Module 2 opens them up. Where Module 1 said *these are different*, Module 2 says
*here is each one, here is its boundary, and here is who holds it — or that
nobody does yet*.

**Module 1's conclusions were re-checked against the sources for this increment
rather than copied.** One correction and two refinements resulted — see
[`source-map.md`](source-map.md) §5.

## 7. Terminology control

The module uses the sources' exact terms. Two constraints matter enough to state
here:

**`lead appointed party` and `appointed party` appear nowhere in the Harrismith
sources.** A search of `bep/`, `supporting/` and `docs/` returns zero
occurrences. The sources use **Owner / Appointing Party** and **Lead Delivery
Party**. Those ISO-associated terms belong to Module 3 and must not be
attributed to Harrismith.

**RACI is expressly not adopted.** BEP §5.12 and the IM matrix §1 both state it,
and both give the same reason: RACI collapses checking from authorising and
coordinating from performing — distinctions this BEP depends on. It is not to be
introduced unless explicitly approved later.

The full inventory of terms, with exact source wording, is in
[`source-map.md`](source-map.md) §2.

## 8. Honesty constraints on delivery

Three things must be said, or the module misrepresents its example:

1. **Every project role holder is TBD.** Harrismith establishes functions and
   allocates them; it names nobody, and no organisation is appointed.
2. **Several authorities remain unresolved** — publication/exchange, recipient
   acceptance, and governance-change approval by change class.
3. **A framework that names functions without holders is not thereby invalid.**
   It is a normal planning state. Implementation eventually requires named
   holders, and Harrismith records that it has not reached that point.

Point 3 matters: an audience told only points 1 and 2 will conclude the
framework is unfinished rather than deliberately staged.

## 9. Status

| Field | Value |
|---|---|
| Module 2 | **CURRENT — ACTIVE**, not complete |
| Structure | **Established (T2-A)** |
| Slides developed | **1–14** — the full content baseline (T2-A, T2-B, T2-C) |
| Role inventory | **Complete** — `source-map.md` §2 |
| Authority inventory | **Complete** — `source-map.md` §3 |
| Statement classification | Slides 1–3 (§4), 4–9 (§7), 10–14 (§9) — **201 statements, 140 direct** |
| Frame reconciliation | Five-function vs four-function documented — `source-map.md` §8 |
| Module-wide reconciliation | Roles, authorities, gaps and synthesis — `source-map.md` §10 |
| Visual source | **Complete (T2-D)** — `M02-S01`–`M02-S14` in [`../assets/module-02/`](../assets/module-02/) |
| Assembly package | **Complete (T2-E)** — [`presentation/`](presentation/) |
| Rendered visual assets | **None** — no renderer available; source committed instead |
| Outstanding | **PowerPoint production, review, rehearsal** |
| Module 1 | Review and rehearsal remain **deferred** |
| Publication automation | **PAUSED** |
