# W11 · Slide 11 — `T4` and `TRN-E03`, two blocked objects

| Field | Value |
|---|---|
| **Slide-source identifier** | `M04-S11` |
| **Slide number** | 11 |
| **Slide title** | Why `Shared → Published` remains blocked |
| **Visual identifier** | **`W11`** |
| **Visual title** | `T4` and `TRN-E03`, two blocked objects |
| **Increment** | **Specified `T4-C` · source produced `T4-E-B`** |
| **Teaching purpose** | Show **two separate blocked objects** — a state transition and a delivery event — and that resolving one would not resolve the other. |
| **Principal sources** | **`S2` §3.1–§3.3, §11, §19**; **`S5` §5, §5.1**; `S1` §9.4, §9.7, §9.8; `S4` §9 |
| **Classification** | `SUPPORTING` + `CONTROLLED` + `DECISION-RECORD` |
| **Governance status** | **`BLOCKED`** — both. Two authorities **`UNRESOLVED`** |
| **Implementation status** | **Not reached.** *"No governed publication / exchange authority evidence was established"* |
| **Fixed visual form** | **Two panels, side by side, equal weight.** `T4` left, `TRN-E03` right |
| **Known limitation** | **`TRN-E03` exercises `T4`; they are not the same object.** Treating them as one is prohibition 27 and prohibition 46 in the module's register |
| **Overclaim risk** | **HIGH in both directions** — merged, it hides four dependencies; styled red, it reads as a defect |
| **Blocked or unresolved element** | **YES — the visual is two blocks**, plus an empty authority position on Panel 1 |
| **Mandatory on-slide warning** | **`Satisfying T4 alone would not automatically complete delivery.`** — on the slide, beneath both panels |
| **External imagery** | **None, and none is required.** A platform screenshot would assert implementation this module cannot evidence |
| **Rendered-asset status** | **`NONE`.** No rendering attempted; no renderer installed |

---

## 1. Purpose and five-second takeaway

Show **two separate blocked objects** — a state transition and a delivery event — and that resolving one would not resolve the other.

**If the audience takes one thing from this visual in five seconds:**

> Two different blocked things. Fixing the transition would not deliver anything.

## 2. Source and authority basis

`S2` §3.1–§3.3 give `T4`: **one blocking matter** — the publication-authorising function, which is `TBD`. **`S5` §5 and §5.1 give `TRN-E03`**: a delivery event, **`PROPOSED — BLOCKED`**, blocked on **five** matters — publication authority, acceptance authority, recipient identity, required formats and the deliverable set.

**`S2` §11 records the relationship: `TRN-E03` exercises `T4`.** They are **different controlled objects** — a state transition and a delivery event — and the difference is the slide.

`S1` §9.7 names the **BIM Manager, BIM Coordinator, CDE Administrator and Architect** as **not** holding publication authority; §9.8 leaves acceptance authority unresolved. `S4` §9: *"no governed publication / exchange authority evidence was established."*

Source identifiers `S1`–`S14` are defined in
[`source-inventory.md`](../../../module-04-cde-workflows-and-information-states/source-inventory.md).
Classification follows
[`source-map.md`](../../../module-04-cde-workflows-and-information-states/source-map.md) §1.

## 3. Governance and implementation status

| | |
|---|---|
| **Governance status** | **`BLOCKED`** — both. Two authorities **`UNRESOLVED`** |
| **Implementation status** | **Not reached.** *"No governed publication / exchange authority evidence was established"* |

**Both are shown on the slide.** A visual that depicts a control without its
status **asserts an operating system that has not been verified** — the rule in
[`visual-demonstration-plan.md`](../../../module-04-cde-workflows-and-information-states/visual-demonstration-plan.md) §1.1.

## 4. Fixed layout

**Two panels, side by side, equal weight.** `T4` left, `TRN-E03` right.

**Left panel** carries the state transition, the broken route, the **empty authority position**, the status and the consequence.

**Right panel** carries the delivery event, the `exercises T4` relationship, the **five blocking matters listed as unresolved**, and the status.

**Beneath both:** the one-versus-five contrast sentence.

**Give the two panels equal weight.** A large `T4` panel beside a small `TRN-E03` panel implies the delivery event is a detail of the transition. **It is a separate object with four additional unresolved matters, and the visual should say so.**

**The fixed form, carried from the `W11` specification:**

```text
  ┌── PANEL 1 · T4 ─────────────┐   ┌── PANEL 2 · TRN-E03 ──────────────┐
  │  INFORMATION-STATE          │   │  DELIVERY EVENT                   │
  │  TRANSITION                 │   │                                   │
  │                             │   │  exercises T4                     │
  │  Shared                     │   │                                   │
  │    ⇢  Published/Authorised  │   │  blocked on:                      │
  │                             │   │   1  publication authority        │
  │  Publication-authorising    │   │   2  acceptance authority         │
  │  function:                  │   │   3  recipient identity           │
  │  ┌───────────────────────┐  │   │   4  required formats             │
  │  │        TBD            │  │   │   5  deliverable set              │
  │  └───────────────────────┘  │   │                                   │
  │        ▲ empty, not omitted │   │  Status: PROPOSED — BLOCKED       │
  │                             │   │                                   │
  │  Status:  BLOCKED           │   │  Blocked by FIVE matters          │
  │  Information remains Shared │   │  T4 is blocked by ONE             │
  └─────────────────────────────┘   └───────────────────────────────────┘

     Satisfying T4 alone would not automatically complete delivery.
```

## 5. Exact visible wording

**Panel titles — exact:** `PANEL 1 · T4` / `INFORMATION-STATE TRANSITION` — `PANEL 2 · TRN-E03` / `DELIVERY EVENT`

**Left panel, exact:**

- `Shared  ⇢  Published/Authorised`
- `Publication-authorising function:`
- `TBD` — **inside the empty position**
- `▲ empty, not omitted`
- `Status:  BLOCKED`
- `Information remains Shared`

**Right panel, exact:**

- `exercises T4`
- `blocked on:` — then the five, **listed as unresolved, not filled**:
  `1  publication authority` · `2  acceptance authority` · `3  recipient identity` · `4  required formats` · `5  deliverable set`
- `Status: PROPOSED — BLOCKED`
- `Blocked by FIVE matters` · `T4 is blocked by ONE`

**Beneath both, exact:**

> Satisfying `T4` alone would not automatically complete delivery.

## 6. Geometry or spatial relationships

Reference canvas **960 × 540 pt**, side margins **48 pt**, minimum type **14 pt**.

**Spatial relationships — fixed:**

| Relationship | Rule |
|---|---|
| Panels | **Two, side by side, identical width and identical height** |
| Gutter | **One, centred, and empty** — **no connector crosses it** |
| Empty authority position | **Inside Panel 1**, bordered, at least two text lines tall, with its marker beside it |
| Five matters | **Inside Panel 2**, numbered one to five, each on its own line |
| Contrast sentence | **Beneath both panels**, full content width, centred |

**Equal panel size is a control.** A `TRN-E03` panel with five listed matters will want to be taller; **set both numerically to the same height** and let the left panel carry more white space.

## 7. Connector semantics

| Connector | Form | Meaning |
|---|---|---|
| `Shared ⇢ Published/Authorised`, inside Panel 1 | **Broken or visibly halted — never solid** | `T4` is blocked |
| Between the two panels | **Prohibited — draw none** | They are **two separate objects**, and a connector would make one a stage of the other |
| Into the empty authority position | **Prohibited** | No role is connected to it, because none holds it |

**No solid arrow anywhere on this visual.**

**The `exercises T4` relationship is carried in words, inside Panel 2** — **not as a line between the panels.** A drawn line would merge the two objects, which is exactly the error the slide exists to prevent.

## 8. Status and warning treatment

**Both panels carry their own status** — `BLOCKED` on the left, `PROPOSED — BLOCKED` on the right. **The two are not the same status and are not merged.**

**The publication-authority position appears and is empty.** **Omitting it implies no authority is required.**

**The five blocking matters are listed as unresolved, not filled.** **No invented authority, recipient, format or deliverable.**

**`Information remains Shared` appears on Panel 1.** **The one-versus-five contrast appears**, and is the slide's argument.

**No completion tick, and no red failure styling.** The block is **deliberate governance**.

## 9. Build or reveal sequence

**One frame — both panels appear together.**

**A staged reveal is prohibited.** Revealing `T4` first and `TRN-E03` second presents the delivery event as a consequence of the transition, **which is the merge the slide refuses.**

## 10. Mandatory omissions

**Any single merged object** · any solid arrow · **any connector between the panels** · any invented authority, recipient, format or deliverable · any completion tick · **any red failure styling** · any suggestion an administrator may proceed · any chain showing publication, delivery, receipt and acceptance as one sequence.

## 11. Accessibility and projection requirements

- **The separateness of the two objects is stated in words** — `exercises T4`, `Blocked by FIVE matters`, `T4 is blocked by ONE` — because an absent connector cannot be perceived by a screen reader.
- **The block is conveyed in words**, not by a dashed stroke alone.
- **No red and no green.** The block must not read as an error state.
- **The empty authority position is legible as empty**, not shaded or hatched.
- **Reading order** — Panel 1 title and contents, Panel 2 title and contents, then the contrast sentence.
- **Type: panel titles 20 pt, contents 16 pt, the five matters 14 pt minimum, contrast sentence 18 pt.**
- **Contrast ≥ 4.5:1** for text; **≥ 3:1** for panel borders and the broken route.

## 12. Screen-reader or presenter-notes description

> Two panels of equal size, side by side. **Nothing is drawn between them.** Panel one, T4, an information-state transition: Shared, **broken connector**, Published / Authorised. Publication-authorising function: **TBD**, marked **empty, not omitted**. Status: **blocked**. **Information remains Shared.** Panel two, TRN-E03, a delivery event: it **exercises T4**. Blocked on five matters — one, publication authority; two, acceptance authority; three, recipient identity; four, required formats; five, deliverable set. Status: **proposed, blocked**. Blocked by **five** matters; T4 is blocked by **one**. Beneath both: **satisfying T4 alone would not automatically complete delivery.**

## 13. Producer-failure test

The visual fails if a viewer can reasonably conclude:

- `T4` and `TRN-E03` are **the same object**;
- resolving `T4` would **complete delivery**;
- the blocks are a **project defect** rather than deliberate governance;
- publication, delivery, receipt and acceptance are **one chain**;
- an **administrator may proceed** in the absence of the authority.

## 14. STOP conditions

**Stop production and return to the `W11` specification if:**

- **the two panels are merged into one object**;
- **any connector is drawn between the panels**;
- any solid arrow appears;
- the publication-authority position is filled, shaded or removed;
- any of the five matters is filled with an invented value;
- a completion tick appears;
- **red failure styling is applied** to either panel;
- `Information remains Shared` is dropped;
- the one-versus-five contrast is removed;
- the panels become unequal in size.

## 15. Native PowerPoint reconstruction notes

**Reconstruct with native PowerPoint shapes, tables and text boxes.** **No image
is imported, and no diagram-rendering engine is used.**

**Two rectangles of identical size, one inner rectangle, one broken connector, one text box beneath.**

1. Draw both panels and **set width and height numerically to the same values.** The right panel's longer content must not be allowed to grow it.
2. Left panel: a **second rectangle for the authority position** — plain border, **no fill** — containing only `TBD`, with `▲ empty, not omitted` beside it.
3. The `Shared ⇢ Published` route is **inside Panel 1**: a short dashed connector with a visible break. **Do not extend it toward Panel 2.**
4. Right panel: the five matters as a numbered list in one text box, **each left as a name only** — no value, no candidate, no parenthetical.
5. **Draw nothing in the gutter.** After any layout change, verify no connector has been auto-added between the panels.
6. **Check the theme's accent colours** — if either panel is filled red or amber by default, clear it.
7. Contrast sentence as its own text box beneath, centred.
8. **No entrance animation**, and **no build revealing one panel before the other.**

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
