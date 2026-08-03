# BIM Management Teaching Programme — Roadmap

**Status:** Teaching plan. **Not governance.** Carries no authority and decides
nothing.

---

## 1. Purpose of the programme

To develop practical BIM Management capability using the Harrismith Fire Station
reference implementation as the worked example, so that the presenter can:

- explain BIM management to a mixed audience without relying on software demos;
- read, use and defend the Harrismith documentation set;
- facilitate the decisions a real project team must make;
- develop a BIM Execution Plan for a future **Triviron** multidisciplinary
  project.

The programme teaches **BIM Management**, not software operation. Revit,
Navisworks, Forma and ACC appear as the environment in which managed information
moves — not as the subject.

---

## 2. Module sequence — Foundation

| # | Module | Status |
|---|---|---|
| 1 | **What is a BIM Execution Plan?** | **CURRENT — ACTIVE** |
| 2 | BIM Management roles and responsibilities | Planned |
| 3 | ISO 19650 information-management principles | Planned |
| 4 | CDE workflows and information states | Planned |
| 5 | Responsibility matrices and information-delivery planning | Planned |
| 6 | Coordination, review, approval and assurance | Planned |
| 7 | Translating Harrismith into the Triviron BEP | Planned |
| 8 | Facilitating and presenting a BEP workshop | Planned |

### Module 1 — What is a BIM Execution Plan? — **CURRENT**

The active module. Deliverable: a 20-minute presentation using Harrismith as the
worked example. See
[`module-01-what-is-a-bep/README.md`](module-01-what-is-a-bep/README.md).

Only Module 1 has been developed. Modules 2–8 are recorded here as the intended
sequence; none of their material exists yet, and their scope may change as
Module 1 is delivered and reviewed.

### Modules 2–8 — intended scope

| # | Module | Intended subject | Principal expected sources |
|---|---|---|---|
| 2 | BIM Management roles and responsibilities | Functional roles, the difference between technical and information-management responsibility, delegation and role combination, why authority never comes from platform permission | BEP §5; `information-management-responsibility-matrix.md` |
| 3 | ISO 19650 information-management principles | The principles that inform the approach — purposeful exchange, originator/recipient separation, the state model — and the limits of what this implementation claims | BEP §13.4, §11.2; `guidance/BIM-Delivery-Guide.md` G12 |
| 4 | CDE workflows and information states | WIP, Shared, Published/Authorised, Record/Retained; controlled transitions; state versus folder; version, revision, status and suitability as four separate properties | BEP §6; `cde-workflow-state-strategy.md` |
| 5 | Responsibility matrices and information-delivery planning | The Perform/Check/Authorise/Coordinate/Accept/Consult/Inform grammar; container allocation; delivery events, purpose and suitability | Both matrices; `information-delivery-schedule.md` |
| 6 | Coordination, review, approval and assurance | Federation, findings, triage, Issues, the coordination cycle, verification; check ≠ authorise ≠ accept | BEP §8, §9; `coordination-review-strategy.md` |
| 7 | Translating Harrismith into the Triviron BEP | Which Harrismith positions transfer, which are Harrismith-specific, and which are project decisions Triviron must take for itself | The full set, plus Triviron project information when it exists |
| 8 | Facilitating and presenting a BEP workshop | Running the decision conversations; recording outcomes; converting agreement into governance | `working/README.md`; `working/workshops/workshop-template.md`; `governance-decision-register.md` |

**Module 7 has an external dependency.** No Triviron project information exists
in this repository. Module 7 cannot be developed beyond generic transfer
principles until Triviron project context is available.

---

## 3. How the programme advances

One module at a time, in bounded increments.

- A module is developed, delivered, and reviewed before the next is opened.
- A module's scope may be revised after delivery; the roadmap is a plan, not a
  commitment.
- Delivery experience feeds back into
  [`shared/presentation-principles.md`](shared/presentation-principles.md) and
  [`shared/glossary.md`](shared/glossary.md).
- No module edits a controlled document. Where teaching reveals a genuine defect
  in a controlled document, it is raised through the Working Process.

---

## 4. Publication automation — PAUSED

**Formal publication automation is deliberately paused.**

The following are **deferred and are not to be restarted, extended or
redesigned** as part of this teaching programme:

- the publication generator;
- the publication validator;
- the freeze protocol;
- package pinning;
- final package generation.

The publication-planning governance record remains as it stands. Nothing in this
teaching programme changes it, and in particular:

- **publication remains NOT AUTHORISED** and the publication hold remains
  active;
- the publication-package commit remains unpinned;
- no package is generated by any teaching activity.

**The pause is lifted only if the publication programme is explicitly
reopened**, by the controlled route — not by a teaching need, not by a
presentation deadline, and not incidentally.

Teaching material may *describe* the publication arrangement as a worked example
of governance under condition. Describing it neither advances nor reopens it.

---

## 5. Current position

| Field | Value |
|---|---|
| Active module | **Module 1 — What is a BIM Execution Plan?** |
| Module 1 deliverable | 20-minute presentation, in development — **not final** |
| Slides developed | Slides 1–3 as an initial teaching baseline |
| Expected final length | Approximately 12–14 slides |
| Modules 2–8 | Not started |
| Publication automation | **PAUSED** |
| Source material status | Training Baseline 0.1 — approved with conditions; publication NOT AUTHORISED |
