# Harrismith Fire Station — BIM Management / BIM Execution Plan

Controlled authoring repository for the Harrismith Fire Station BIM Management
and BIM Execution Plan (BEP) training implementation.

**Status:** Implementation Increment 1 — repository scaffold only.
No substantive BEP policy has been drafted.

---

## 1. Purpose

This repository is the **authoring source** for the Harrismith Fire Station BIM
Execution Plan and its supporting information-management resources.

It exists to:

- hold the approved document architecture under version control;
- provide a reviewable history of how information-management governance was
  developed;
- separate *drafting and review* from *issue and publication*;
- support a training implementation in which the reasoning behind each
  governance decision is explicit and traceable.

---

## 2. Authoring source vs issued CDE artefacts

This is the single most important distinction in this repository.

| | Authoring source | Issued artefact |
|---|---|---|
| **Location** | this Git repository | Autodesk Common Data Environment |
| **Nature** | drafts, working text, proposals | approved, issued, controlled deliverables |
| **Authority** | none until approved | contractual / project authority |
| **Change control** | Git commits and review | CDE state and revision control |

Content in this repository carries **no project authority** until it has been
reviewed, approved, and published into the CDE through the controlled route
described in section 4.

### 2.1 Prohibition on direct CDE writes

The Autodesk Desktop Connector / ACCDocs tree is **out of bounds** for this
repository and for any tooling operating on it.

There must be **no** symlink, junction, bind mount, automatic synchronisation,
or other filesystem link between this repository and the Autodesk CDE.

Specifically prohibited from this repository:

- reading from, writing to, creating, renaming, moving or deleting anything in
  the Desktop Connector / ACCDocs tree;
- any automated or scripted synchronisation into the CDE;
- any change to Autodesk Forma, ACC, Desktop Connector, Revit, Navisworks or
  other external project systems.

Publication into the CDE is a **manual, controlled, human-performed** act.

---

## 3. Repository architecture

```
harrismith-bep/
├── README.md        repository governance and safety boundary
├── bep/             the main BIM Execution Plan
├── supporting/      the six supporting management resources
├── working/         working process, workshop material, in-progress thinking
├── guidance/        the BIM Delivery Guide
├── standards/       referenced project standards
├── output/          generated / project-facing artefacts (NOT authoring source)
└── docs/            repository-level documentation and process notes
```

### 3.1 Main BIM Execution Plan — `bep/`

Approved section architecture (Architecture Baseline v1):

1. Document Purpose and Status
2. Project Information
3. BIM and Information Management Objectives
4. Project Organisation and Task Teams
5. Information Management Roles and Responsibilities
6. Common Data Environment Strategy
7. Information Production and Sharing
8. Model and Information Coordination
9. Review, Approval and Authorisation
10. Information Delivery and Exchange
11. Standards and Project Conventions
12. Governance, Change and Exceptions
13. Controlled References

### 3.2 Supporting management resources — `supporting/`

1. Information Management Responsibility Matrix
2. Model / Information Responsibility Matrix
3. Information Delivery Schedule
4. CDE Workflow & State Strategy
5. Coordination & Review Strategy
6. Governance & Decision Register

### 3.3 Working, guidance and standards

- `working/` — the Working Process and workshop material. Working thinking,
  not governance.
- `guidance/` — the BIM Delivery Guide: practical, explanatory support for
  delivery teams.
- `standards/` — referenced project standards for Naming, Coordinates,
  Titleblocks, and Templates / authoring conventions.

### 3.4 Output — `output/`

`output/` holds **generated and project-facing artefacts** produced from the
authoring source.

`output/` is **not** the authoring source. It is never edited directly, and
nothing in it is authoritative merely by being present.

---

## 4. Controlled route to the CDE

```
local Git authoring source
    → review
    → approved baseline
    → manual controlled publication to Autodesk Forma / Data Management
```

Each arrow is a deliberate, recorded step. No step is automated in this
repository.

---

## 5. Gate status

| Gate | Status |
|---|---|
| Discovery Gate A | Complete |
| Architecture Gate B | Complete — frozen as **Architecture Baseline v1** |
| Implementation Increment 1 | This increment — repository scaffold |

Architecture Baseline v1 is **frozen**. The document architecture recorded in
section 3 is not to be redesigned during implementation increments. Proposed
changes to the architecture are raised as an UNRESOLVED DECISION in
`supporting/governance-decision-register.md` and resolved through an explicit
gate, not through incremental editing.

---

## 6. Statement classification

All content in this repository classifies its statements using these terms,
consistently and explicitly:

| Term | Meaning |
|---|---|
| **OBSERVED FACT** | Verified from the live project or a controlled source. |
| **TRAINING ASSUMPTION** | Adopted for the training implementation; not verified as project truth. |
| **PROPOSED GOVERNANCE** | Drafted for consideration. Carries no authority. |
| **APPROVED GOVERNANCE** | Reviewed and approved. Carries authority within its scope. |
| **UNRESOLVED DECISION** | Known open question. Explicitly not answered. |

Two standing rules:

- **Assumptions are never silently converted into facts.** A TRAINING
  ASSUMPTION is promoted to OBSERVED FACT only by verification, and the
  promotion is recorded.
- **Known live-project discrepancies are never silently corrected.** Where the
  live project differs from what governance would suggest, the discrepancy is
  recorded as an OBSERVED FACT and carried as an UNRESOLVED DECISION until it
  is deliberately resolved.

---

## 7. Development approach

Substantive drafting begins in **later controlled increments**, each with an
explicitly approved scope.

In this increment the document files contain only titles, purpose/status
statements, the approved heading scaffold, and `TBD` / *To be developed*
placeholders. Empty placeholder content is intentional and is not an omission
to be filled in opportunistically.

No increment beyond the one currently approved is to be started without
explicit approval.
