# W6 · Slide 6 — The publication-authority gate

| Field | Value |
|---|---|
| **Slide-source identifier** | `M04-S06` |
| **Slide number** | 6 |
| **Slide title** | Published / Authorised: a separate decision and authority |
| **Visual identifier** | **`W6`** |
| **Visual title** | The publication-authority gate |
| **Increment** | **Specified `T4-B` · source produced `T4-E-B`** |
| **Teaching purpose** | Show publication as a **separate decision by a separate authority** — and that the authority is **required and unassigned**. |
| **Principal sources** | `S1` §6.7, §9.7; `S2` §1, §3.1, §3.2, §11; `S3` §3.4; `S4` §9; `S6` `D4` |
| **Classification** | `CONTROLLED` + `SUPPORTING` + `DECISION-RECORD` |
| **Governance status** | **`BLOCKED`** — the authority is **`UNRESOLVED`** |
| **Implementation status** | **Not reached** |
| **Fixed visual form** | **One Shared input, one gate, one empty authority position, one blocked output** |
| **Known limitation** | **The block is a governance position, not an observed platform failure.** No live platform state is asserted or denied here |
| **Overclaim risk** | **HIGH in both directions** — an empty gate invites the audience to fill it; a red gate reads as a defect |
| **Blocked or unresolved element** | **YES — the authority position is drawn empty, and the output is broken** |
| **Mandatory on-slide warning** | **`T4 BLOCKED` · `No available authorising function` · `INFORMATION REMAINS SHARED`** — all three on the slide |
| **External imagery** | **None, and none is required.** A platform screenshot would assert implementation this module cannot evidence |
| **Rendered-asset status** | **`NONE`.** No rendering attempted; no renderer installed |

---

## 1. Purpose and five-second takeaway

Show publication as a **separate decision by a separate authority** — and that the authority is **required and unassigned**.

**If the audience takes one thing from this visual in five seconds:**

> Publication needs an authority. Nobody holds it. So the information stays Shared.

## 2. Source and authority basis

`S2` §3.1 records that `T4` has **no available authorising function** and that **information remains Shared**. `S1` §6.7 establishes publication as a separate decision; `S2` §1 adds that *"Published does not mean universally suitable, forever final, or automatically accepted"*.

**`S1` §9.7 is the reason no name may appear.** It names the **BIM Manager, BIM Coordinator, CDE Administrator and Architect** as **not** holding publication authority automatically. `S4` §9 confirms *"no governed publication / exchange authority evidence was established"*.

`S3` §3.4 supplies the placement caution the slide displays: ***"Putting a file in `03. Published` does not publish it.** Publication is a chain of governed events, not a location."*

`S2` §11 relates `TRN-E03` to `T4` — **the event logic itself is Slides 8–11**, and appears here in a single annotation at most.

Source identifiers `S1`–`S14` are defined in
[`source-inventory.md`](../../../module-04-cde-workflows-and-information-states/source-inventory.md).
Classification follows
[`source-map.md`](../../../module-04-cde-workflows-and-information-states/source-map.md) §1.

## 3. Governance and implementation status

| | |
|---|---|
| **Governance status** | **`BLOCKED`** — the authority is **`UNRESOLVED`** |
| **Implementation status** | **Not reached** |

**Both are shown on the slide.** A visual that depicts a control without its
status **asserts an operating system that has not been verified** — the rule in
[`visual-demonstration-plan.md`](../../../module-04-cde-workflows-and-information-states/visual-demonstration-plan.md) §1.1.

## 4. Fixed layout

**Vertical arrangement**, top to bottom:

1. `SHARED` input;
2. a **downward solid connector into the gate** — the input is not in question;
3. the **publication gate**, containing the required check, the required evidence, and the **empty authority position**;
4. a **broken output** carrying three labels;
5. `PUBLISHED / AUTHORISED`, marked **(not reached)**.

**The empty authority position sits inside the gate**, plainly bordered, plainly labelled, plainly empty.

**The fixed form, carried from the `W6` specification:**

```text
   SHARED
     │
     ▼
  ┌─────────────────────────────────────────────┐
  │  PUBLICATION GATE                           │
  │                                             │
  │  required check:  delivery readiness review │
  │  required evidence: review + authorisation  │
  │                       record                │
  │                                             │
  │  Publication-authorising function:          │
  │  ┌───────────────────────────────────┐      │
  │  │        TBD / UNRESOLVED           │      │   ← EMPTY, not omitted
  │  └───────────────────────────────────┘      │
  └─────────────────────────────────────────────┘
     ⇢     T4 BLOCKED
           No available authorising function
           INFORMATION REMAINS SHARED
     ⇢
   PUBLISHED / AUTHORISED        (not reached)
```

## 5. Exact visible wording

**Exact, in order:**

- `SHARED`
- `PUBLICATION GATE`
- `required check:  delivery readiness review`
- `required evidence: review + authorisation record`
- `Publication-authorising function:`
- `TBD / UNRESOLVED` — **inside the empty position**
- `EMPTY, not omitted` — the marker beside it
- `T4 BLOCKED`
- `No available authorising function`
- `INFORMATION REMAINS SHARED`
- `PUBLISHED / AUTHORISED        (not reached)`

**`S3` §3.4 appears on the slide, exact:**

> Putting a file in `03. Published` does not publish it.

**No name appears in the authority position, and no substitute role appears anywhere.**

## 6. Geometry or spatial relationships

Reference canvas **960 × 540 pt**, side margins **48 pt**, minimum type **14 pt**.

**Spatial relationships — fixed:**

| Relationship | Rule |
|---|---|
| Arrangement | **Single vertical column**, centred |
| Gate | **The largest element**, occupying the middle band of the slide |
| Authority position | **Inside the gate**, full gate width less its padding, **at least two text lines tall** |
| Empty marker | **Beside the authority position**, pointing at it |
| Output | **Broken, beneath the gate**, with its three labels beside it |
| Published | **At the foot**, with `(not reached)` attached |

**The authority position must not be small.** A producer's instinct is to shrink an empty element and grow a populated one — which inverts the teaching. **Give it at least the height of two text lines**, so it reads as a position rather than a gap.

## 7. Connector semantics

| Connector | Form | Meaning |
|---|---|---|
| `SHARED` → gate | **Solid, downward, filled arrowhead** | The input reaches the gate. That part is not in question |
| Gate → `PUBLISHED / AUTHORISED` | **Broken or visibly halted — never solid** | `T4` is blocked |
| Anything → the authority position | **Prohibited** | No role is connected to it, because none holds it |

**Never a faded arrow reading as *in progress*.** The route is not slow; it is **stopped for a reason**, and fading it teaches that time will resolve it.

## 8. Status and warning treatment

**Governance `BLOCKED` and implementation `Not reached` both appear.**

**Three labels are all present** — `T4 blocked`, `No available authorising function`, `Information remains Shared`. **The third is the consequence**, and without it a blocked route reads as information in limbo.

**No checkmark, and no red failure styling.** The block is **deliberate governance**, not a technical fault. **This is the hardest instruction on the visual:** an empty box looks unfinished, and a designer will want to fill it, shade it or remove it. **All three are wrong** — filled invents an authority; removed implies none is needed; shaded reads as failure. **A plain, labelled, empty position is the only accurate rendering.**

## 9. Build or reveal sequence

**One frame preferred.** If built, the **empty authority position appears with the gate**, never later — a gate revealed before its empty position reads as a complete gate.

**The three output labels appear together**, in one step. `Information remains Shared` may not lag the block.

## 10. Mandatory omissions

Any named or implied authority holder · **any solid `Shared → Published` arrow** · any checkmark · any suggestion an administrator may substitute · **any red failure styling** · any grey shading of the authority position · any date attached to the block · `TRN-E03` drawn as the transition — it may be named in **one annotation** as a later delivery event that depends on `T4`.

## 11. Accessibility and projection requirements

- **The block is conveyed in words** — `T4 BLOCKED`, `No available authorising function` — so it survives monochrome and does not depend on a dashed stroke being resolvable.
- **No red and no green.** The block must not read as an error state.
- **The empty position is legible as empty**, not as a shaded or hatched region that could be mistaken for a fill.
- **Reading order** — Shared, gate title, required check, required evidence, authority position and its empty marker, the three block labels, then Published (not reached).
- **Type: gate title 20 pt, gate contents 16 pt, authority label 16 pt, block labels 16 pt, status labels 14 pt minimum.**
- **Contrast ≥ 4.5:1** for text; **≥ 3:1** for the gate border and the broken connector.

## 12. Screen-reader or presenter-notes description

> Shared, at the top, with a solid arrow down into a publication gate. The gate lists a required check — delivery readiness review — and required evidence — review and authorisation record. Inside the gate, a bordered position labelled publication-authorising function contains the words **TBD, unresolved**, marked as **empty, not omitted**. Below the gate, **a broken connector**, labelled T4 blocked; no available authorising function; **information remains Shared**. At the foot, Published / Authorised, marked **not reached**. Also on the slide: putting a file in 03. Published does not publish it. **No role or person is named anywhere.**

## 13. Producer-failure test

The visual fails if a viewer can reasonably conclude:

- **someone in the room holds** the publication authority;
- the block is a **technical fault** or a **project failure**;
- an **administrator may proceed** in the absence of the authority;
- the route is **merely delayed** and will resolve with time;
- placing a file in `03. Published` **publishes it**.

## 14. STOP conditions

**Stop production and return to the `W6` specification if:**

- **the authority position is filled, shaded, hatched or removed**;
- any name or substitute role appears — including "the BIM Manager, realistically";
- the `Shared → Published` connector becomes solid, or is faded to read as in progress;
- a checkmark appears anywhere;
- **red failure styling is applied** to the gate or the output;
- `Information remains Shared` is dropped;
- a date or owner is attached to the block;
- `TRN-E03` is drawn as the transition rather than named in one annotation.

## 15. Native PowerPoint reconstruction notes

**Reconstruct with native PowerPoint shapes, tables and text boxes.** **No image
is imported, and no diagram-rendering engine is used.**

**One column: two labelled shapes, one large gate rectangle, two connectors.**

1. Gate as a large rectangle. Inside it, **a second rectangle for the authority position** — plain 1 pt border, **no fill**, at least two lines tall, containing only `TBD / UNRESOLVED`.
2. **Do not apply a theme fill to the inner rectangle.** Many themes fill shapes by default, and a filled position reads as answered.
3. Input connector: straight, solid, arrowhead at the gate.
4. Output connector: straight, **dashed**, arrowhead at the Published end, with a visible break or gap. **Do not set it to a light grey** — faded reads as *in progress*.
5. Three block labels in **one text box** beside the output connector, so none can be deleted alone.
6. `(not reached)` in the same text box as `PUBLISHED / AUTHORISED`.
7. **Check the theme's colour set before finishing:** if the accent applied to the gate or output is red, change it. The block is not an error.

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
