# W4 · Slide 4 — The WIP task-team boundary

| Field | Value |
|---|---|
| **Slide-source identifier** | `M04-S04` |
| **Slide number** | 4 |
| **Slide title** | Work in Progress: authoring inside the task team |
| **Visual identifier** | **`W4`** |
| **Visual title** | The WIP task-team boundary |
| **Increment** | **Specified `T4-B` · source produced `T4-E-B`** |
| **Teaching purpose** | Show WIP as bounded by the task team, and that **visibility is not permission to rely**. |
| **Principal sources** | `S1` §6.4, §7.5; `S2` §1; `S3` §3.2; `S4` §7 |
| **Classification** | `CONTROLLED` + `DECISION-RECORD` |
| **Governance status** | **`CONTROLLED GOVERNANCE`** |
| **Implementation status** | **`IMPLEMENTATION UNVERIFIED`** — one qualified container observation |
| **Fixed visual form** | **One boundary**, three functions inside, several versions inside, one observer outside |
| **Known limitation** | **One qualified observation only.** `ARC-01` was observed; **five containers were not observed at the inspected level.** No claim is made that every task team has a verified live area |
| **Overclaim risk** | **MEDIUM-HIGH** — a boundary with a gate on it invites the eye to follow the route out |
| **Blocked or unresolved element** | **No route out is drawn.** The Task-Team Lead gate is visible on the boundary and **no connector leaves it** |
| **Mandatory on-slide warning** | **`Visibility is not permission. Permission to read is not authorisation to rely.`** — `S1` §7.5, on the slide |
| **External imagery** | **None, and none is required.** A platform screenshot would assert implementation this module cannot evidence |
| **Rendered-asset status** | **`NONE`.** No rendering attempted; no renderer installed |

---

## 1. Purpose and five-second takeaway

Show WIP as bounded by the task team, and that **visibility is not permission to rely**.

**If the audience takes one thing from this visual in five seconds:**

> You may be able to see it. That is not permission to use it.

## 2. Source and authority basis

`S1` §7.5 supplies the slide's sentence: *"visibility is not permission"*, and *"permission to read is not authorisation to rely"*. `S1` §6.4 supplies the boundary's nature: *"a team space is a platform construct… **membership confers no authority**."*

`S2` §1 defines WIP as *"information under originator / task-team control, **not authorised for general project reliance**"*. `S3` §3.2 maps the `01. WIP (Work in Progress)` area to the state — **and the mapping is the governance, not the folder.**

`S4` §7 is the implementation limit: **one qualified container observation (`ARC-01`)**, with five containers not observed at the inspected level.

Source identifiers `S1`–`S14` are defined in
[`source-inventory.md`](../../../module-04-cde-workflows-and-information-states/source-inventory.md).
Classification follows
[`source-map.md`](../../../module-04-cde-workflows-and-information-states/source-map.md) §1.

## 3. Governance and implementation status

| | |
|---|---|
| **Governance status** | **`CONTROLLED GOVERNANCE`** |
| **Implementation status** | **`IMPLEMENTATION UNVERIFIED`** — one qualified container observation |

**Both are shown on the slide.** A visual that depicts a control without its
status **asserts an operating system that has not been verified** — the rule in
[`visual-demonstration-plan.md`](../../../module-04-cde-workflows-and-information-states/visual-demonstration-plan.md) §1.1.

## 4. Fixed layout

**One boundary rectangle** containing, in order: the three functions on one line, the working versions beneath, and the retained-responsibility line at the foot.

**One observer marker outside the boundary**, with two labels — a sight line in, and a refusal marker on reliance.

**The Task-Team Lead gate sits on the boundary edge.** **No connector leaves it.**

**The fixed form, carried from the `W4` specification:**

```text
┌─ TASK-TEAM WIP ──────────────────────────────────┐
│                                                  │
│   Author  →  Checker  →  [ Task-Team Lead gate ] │
│                                                  │
│   v1  v2  v3  v4 …   working steps,              │
│                      NOT project exchanges       │
│                                                  │
│   originating responsibility — retained          │
└──────────────────────────────────────────────────┘

        ●  another team — CAN SEE
           ✗ MAY NOT RELY

   "Visibility is not permission.
    Permission to read is not authorisation to rely."  (BEP §7.5)
```

## 5. Exact visible wording

**Boundary title — exact:** `TASK-TEAM WIP`

**Inside, exact:**

- `Author  →  Checker  →  [ Task-Team Lead gate ]`
- `v1  v2  v3  v4 …   working steps, NOT project exchanges`
- `originating responsibility — retained`

**Outside, exact, both halves:**

- `another team — CAN SEE`
- `MAY NOT RELY`

**On-slide quotation — exact, with attribution:**

> Visibility is not permission. Permission to read is not authorisation to rely. — `S1` §7.5

**If implementation is annotated at all, exact:** `ARC-01 — one qualified observation; five containers not observed at the inspected level`

## 6. Geometry or spatial relationships

Reference canvas **960 × 540 pt**, side margins **48 pt**, minimum type **14 pt** — the conventions in the visual plan §3.1.

**Spatial relationships — fixed, dimensions at the producer's discretion within them:**

| Relationship | Rule |
|---|---|
| Boundary | **One rectangle**, occupying the left two thirds of the content width |
| Functions | **One line, inside, near the top** — Author, Checker, Task-Team Lead gate |
| Versions | **Inside, beneath the functions**, as a horizontal run |
| Responsibility line | **Inside, at the foot of the boundary** — it must be *within* the boundary, because that is its meaning |
| Observer | **Outside the boundary, to the right**, clearly separated |
| Gate | **On the boundary edge**, not floating inside it and **not opening onto anything** |

**The observer must be unambiguously outside.** An observer drawn on the boundary line reads as partial membership, which is not a thing the sources describe.

## 7. Connector semantics

| Connector | Form | Meaning |
|---|---|---|
| Author → Checker → Task-Team Lead gate | **Solid, inside the boundary only** | The internal working sequence |
| Observer → boundary | **A sight line** — thin, unweighted, terminating at the boundary | Another team **can see** |
| Reliance | **A refusal marker on the sight line**, drawn and labelled | Another team **may not rely** |
| Boundary → Shared | **Prohibited — draw none** | **No automatic arrow to Shared.** Transition mechanics are Slides 8–11 |

**The gate is visible and leads nowhere.** That is deliberate: the audience must see that a gate exists without being shown a route through it on this slide.

## 8. Status and warning treatment

**Governance status `CONTROLLED GOVERNANCE` and implementation status `IMPLEMENTATION UNVERIFIED` both appear.**

**The implementation annotation, if used, is the qualified form only** — `ARC-01`, one observation, five containers not observed. **It is never generalised** into *"the WIP areas are set up"*.

**No green approval tick anywhere**, and no completion marker on the gate.

## 9. Build or reveal sequence

**One frame preferred.** If the slide is built in two steps, the permitted split is: **boundary and its contents**, then **the outside observer with both labels together**.

**`CAN SEE` and `MAY NOT RELY` must appear in the same step.** A frame showing an observer who can see, before the refusal appears, teaches the opposite of the slide.

## 10. Mandatory omissions

Any named person · any team-space screenshot · **any automatic arrow to Shared** · any suggestion the boundary is a permission setting or a padlock · any green approval tick · any claim that every task team has a verified live area · any folder tree.

## 11. Accessibility and projection requirements

- **The boundary's meaning is stated in text**, not only by enclosure — `originating responsibility — retained` is inside it and says so.
- **The refusal is a labelled marker, not a colour.** `MAY NOT RELY` is words; a red line alone would not survive monochrome projection.
- **Reading order** — boundary title, functions, versions, responsibility line, then the observer and its two labels, then the quotation.
- **Type: boundary title 20 pt, contents 16 pt, observer labels 16 pt, quotation 16 pt, implementation annotation 14 pt minimum.**
- **Contrast ≥ 4.5:1** for text; **≥ 3:1** for the boundary and the sight line.

## 12. Screen-reader or presenter-notes description

> A single bounded area titled Task-Team WIP. Inside: Author, then Checker, then a Task-Team Lead gate on the boundary edge. Inside: versions one, two, three, four and continuing — working steps, not project exchanges. Inside, at the foot: originating responsibility, retained. **Outside the boundary**, another team: can see, **may not rely**. Quotation: visibility is not permission; permission to read is not authorisation to rely — project BEP section 7.5. **No arrow leaves the boundary.**

## 13. Producer-failure test

The visual fails if a viewer can reasonably conclude:

- the boundary is a **permission setting** rather than a responsibility boundary;
- WIP **automatically progresses** to Shared;
- being able to see WIP **permits relying** on it;
- every task team has a **verified live WIP area**.

## 14. STOP conditions

**Stop production and return to the `W4` specification if:**

- **any connector leaves the boundary** toward Shared or anywhere else;
- the boundary is drawn as a **padlock, lock icon or permission shield**;
- a named person appears;
- a team-space screenshot is introduced;
- a green approval tick appears anywhere;
- the observer is drawn inside or on the boundary;
- `MAY NOT RELY` is dropped, softened or reduced to a colour;
- the `ARC-01` annotation is generalised beyond one qualified observation.

## 15. Native PowerPoint reconstruction notes

**Reconstruct with native PowerPoint shapes, tables and text boxes.** **No image
is imported, and no diagram-rendering engine is used.**

**One large rectangle, one marker shape, several small text boxes.**

1. Draw the boundary rectangle. **Use a plain border** — no shadow, no 3-D, no lock or shield graphic.
2. Functions as a single text box with two arrow glyphs, or three small boxes with two short connectors **entirely inside** the rectangle.
3. Versions as one text box. Responsibility line as one text box at the rectangle's foot, **inside it**.
4. Observer as a small marker shape outside the rectangle, with two labels beneath — **both in the same text box**, so neither can be animated or deleted alone.
5. Sight line as a thin straight connector from the observer to the rectangle edge, **no arrowhead**, with a refusal marker over it.
6. **Draw no connector out of the rectangle.** After any layout change, check that none has been auto-added by a SmartArt conversion.
7. Quotation as a text box beneath, 16 pt.

## 16. Rendered-asset status

**No rendered asset exists for this visual.** No SVG, PNG, JPG, PDF or PowerPoint
file has been produced from it, and **no rendering was attempted** — see
[`../rendered/README.md`](../rendered/README.md).

**This Markdown file is the authority.** A later rendered image or PowerPoint
slide is **derivative of it**, and derivative of the controlling specification in
[`visual-demonstration-plan.md`](../../../module-04-cde-workflows-and-information-states/visual-demonstration-plan.md).

**Where this file and the visual-demonstration plan differ, the plan is
authoritative and this file is the thing to correct.**

| Field | Value |
|---|---|
| Source status | **`SOURCE COMPLETE`** |
| Rendered status | **`NONE`** |
| Renderer used | **None. No renderer was installed and no network rendering service was used** |
| Format | **Markdown native-layout specification. Not Mermaid** |
