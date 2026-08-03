# M01-S08 — Information-delivery planning

| Field | Value |
|---|---|
| **Visual identifier** | `M01-S08` |
| **Related slide** | Slide 8 — Information-delivery planning |
| **Purpose** | Show how a responsibility becomes a planned delivery — and what a delivery plan looks like when no dates exist |
| **Source format** | Markdown field/value extract + a three-row event table. **Deliberately not Mermaid** |
| **Source documents** | `supporting/information-delivery-schedule.md` §1, §2, §3, §3.1, §3.2, §5.1, §5.3, §7; `bep/Harrismith-Fire-Station-BEP.md` §10.1, §10.13 |
| **Evidence classification** | **DIRECT** for the sixteen fields, the three events, TRN-E01's conditions and TRN-E03's five blocking matters; **INTERPRETATION** for the seven-way field grouping; **SYNTHESIS** for the required message |
| **Known limitation** | **No calendar dates, frequencies or contractual milestones exist and none may be drawn.** No calendar, Gantt fragment, stage sequence or month label — not even as decoration |
| **Last increment** | T1-D |

---

## 1. Why this is not a diagram

A delivery schedule is a record with fields. A flowchart would suggest a process
where the source records a *plan*, and it would need arrows between rows that do
not exist.

**The visual is one row, turned on its side.** Eight field/value pairs read
better at projection scale than a sixteen-column table read sideways.

## 2. Primary visual — one TRN-E01 row, vertical

```text
┌─────────────────────────────────────────────────────────────┐
│  TRN-E01-MEC                                                │
├────────────────────────┬────────────────────────────────────┤
│  Information container │  MEC-01                            │
│  Originating party     │  MEP Consultant                    │
│  Task team             │  Mechanical task team              │
│  Recipient             │  BIM Coordinator; participating    │
│                        │  coordination task teams           │
│  Purpose               │  Controlled multidisciplinary      │
│                        │  coordination                      │
│  State / suitability   │  Shared — coordination use only    │
│  Checking requirement  │  Task-team technical/content check │
│                        │  AND information-quality check     │
│  Authorisation         │  Task-Team Lead authorisation      │
│                        │  to share                          │
│  Format                │  TBD — no format is mandated       │
│  ▶ TIMING              │  ▶ EVENT-TRIGGERED / TBD           │
└────────────────────────┴────────────────────────────────────┘
```

**The `TIMING` row is enlarged deliberately.** Saying "there are no dates" is
weaker than letting the audience read the field and see its value. It converts an
apparent omission into a visible, deliberate position.

## 3. The questions a row answers

The schedule uses sixteen fields, approved in BEP §10.13. Grouped for teaching —
**the grouping is teaching structure; the fields are source**.

| The question | Fields |
|---|---|
| **What** must be delivered? | Information Container, Format |
| **Who** is responsible? | Originating Party, Task Team, Discipline, Lead |
| **For whom, and why?** | Recipient, Purpose |
| **At which event?** | Exchange / Milestone, Delivery ID |
| **In what state, usable for what?** | State / Suitability |
| **Under what control?** | Checking Requirement, Authorisation Requirement, Acceptance Criteria |
| **Depending on what?** | Dependencies, Status |

## 4. Secondary visual — the three events

| Event | Concept | Status |
|---|---|---|
| **TRN-E01** | Design coordination share — six containers, six separate exchanges | PROPOSED |
| **TRN-E02** | Coordination reshare after a finding | PROPOSED — **conditional**, per affected container, no calendar frequency |
| **TRN-E03** | Controlled design review / project-facing exchange | **PROPOSED — BLOCKED** |

**TRN-E03 must be visibly blocked.** Show at most two of its five blocking
matters; state the count in speech.

| Blocking matter | Status |
|---|---|
| Publication / exchange authorisation authority | **UNRESOLVED — TBD** |
| Recipient acceptance authority | **UNRESOLVED — TBD** |

*(Three further: recipient identity, required formats, deliverable set.)*

Quotable, from the source:

> Assigning a plausible authority to make the row look finished would
> manufacture governance that does not exist.

## 5. Optional third element — four states routinely conflated

| Published | Delivered | Received | Accepted |
|---|---|---|---|
| Authorised for a defined purpose | Sent to an identified recipient | Arrived and registered | Acknowledged as suitable for the stated purpose |

Use only if time allows; it is repeated on Slide 10 in a different form.

## 6. Required message

> A responsibility without a planned delivery is only an allocation of work; the
> delivery schedule turns it into a coordinated commitment.

**Teaching wording. Not source wording.**

## 7. Simplification and omission

| Simplify | Omit |
|---|---|
| One container's row, vertical, eight to ten lines | All sixteen fields as a horizontal table |
| Three events, three lines | All six TRN-E01 rows |
| Two blocking matters shown, five stated | The TRN-E02 conditional template rows |
| — | **Any calendar, Gantt fragment, stage sequence or month label** |
| — | The full five-row blocking table |

## 8. Prohibition specific to this visual

No date. No month. No quarter. No stage name. No duration. No programme bar.
**Anything that looks like a programme will be read as one**, and the identifiers
`TRN-E01-MEC` and similar are training references, not contractual document
numbers — no naming standard exists.

## 9. Overclaim risk

**Low if the timing field is shown; high if it is cropped out.** A delivery row
without its TBD timing reads as an extract from a real project programme.
