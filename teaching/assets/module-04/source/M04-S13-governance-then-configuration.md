# W13 · Slide 13 — Governance, then configuration

| Field | Value |
|---|---|
| **Slide-source identifier** | `M04-S13` |
| **Slide number** | 13 |
| **Slide title** | Governance first; permissions and configuration follow |
| **Visual identifier** | **`W13`** |
| **Visual title** | Governance, then configuration |
| **Increment** | **Specified `T4-D` · source produced `T4-E-B`** |
| **Teaching purpose** | Show the **direction of authority** — decision, process, configuration, evidence — and that the reverse does not hold. |
| **Principal sources** | **`S1` §5.9, §6.9, §12.1, §12.6, §12.8, §12.9**; `S2` §6, §14, §17; **`CGD-C07`, `CGD-C08`** |
| **Classification** | `CONTROLLED` + `SUPPORTING` + `DECISION-RECORD` |
| **Governance status** | **`CONTROLLED GOVERNANCE`** |
| **Implementation status** | **`IMPLEMENTATION UNVERIFIED`** — `S2` §6 records alignment as a four-layer question |
| **Fixed visual form** | **One forward chain, one visibly refused reverse arrow, one may/does-not table** |
| **Known limitation** | **How alignment is *proven* is Module 6.** This visual states the requirement only, and asserts nothing about the live platform |
| **Overclaim risk** | **MEDIUM-HIGH** — a forward-only chain can be read in either direction, and a permissions image makes configuration the concrete thing |
| **Blocked or unresolved element** | **YES — the refused reverse arrow, and `Holder: TBD`** |
| **Mandatory on-slide warning** | **`A configuration that was never approved is a deviation, however competently it was applied.`** — `S1` §5.9, verbatim, on the slide |
| **External imagery** | **None, and none is required.** A platform screenshot would assert implementation this module cannot evidence |
| **Rendered-asset status** | **`NONE`.** No rendering attempted; no renderer installed |

---

## 1. Purpose and five-second takeaway

Show the **direction of authority** — decision, process, configuration, evidence — and that the reverse does not hold.

**If the audience takes one thing from this visual in five seconds:**

> Configuration implements governance. It does not create it.

## 2. Source and authority basis

**`S1` §5.9 is the controlling source** and supplies both the boundary and the takeaway sentence: **CDE Administration implements governance; it does not create it**; *"a configuration that was never approved is a deviation, however competently it was applied"*; the administrator has *"the technical ability to change it and nothing more"*; **`Platform permission is not BEP authority`**; **`Holder: TBD`**.

`S1` §12.6 distinguishes **deviation from non-conformance** — the difference is *"intent and authorisation, not severity"*. `S1` §12.8 requires that **document, process and platform configuration remain aligned**, and records that **this BEP does not itself authorise any live platform change**.

`S2` §6 records alignment as a four-layer question, which is why the implementation status is **unverified** rather than absent.

Source identifiers `S1`–`S14` are defined in
[`source-inventory.md`](../../../module-04-cde-workflows-and-information-states/source-inventory.md).
Classification follows
[`source-map.md`](../../../module-04-cde-workflows-and-information-states/source-map.md) §1.

## 3. Governance and implementation status

| | |
|---|---|
| **Governance status** | **`CONTROLLED GOVERNANCE`** |
| **Implementation status** | **`IMPLEMENTATION UNVERIFIED`** — `S2` §6 records alignment as a four-layer question |

**Both are shown on the slide.** A visual that depicts a control without its
status **asserts an operating system that has not been verified** — the rule in
[`visual-demonstration-plan.md`](../../../module-04-cde-workflows-and-information-states/visual-demonstration-plan.md) §1.1.

## 4. Fixed layout

**Three stacked elements:**

1. **The forward chain**, left to right: `Governance decision` → `Process rule` → `Permission / configuration` → `Implementation evidence`.
2. **The refused reverse arrow**, beneath a divider: `Platform setting ──✕──▶ governance authority`, with the marker `▲ shown and refused — not omitted`.
3. **The may / does-not table**, two boxes of equal weight, with `Holder: TBD` in the left box.

**Beneath: the `S1` §5.9 sentence, verbatim.**

**The four-box chain is deliberately plain.** If it is styled into a process-maturity graphic — numbered stages, gradients, a loop back to the start — **it acquires a completeness this slide does not claim, and the loop reintroduces the reverse arrow the visual exists to refuse.**

**The fixed form, carried from the `W13` specification:**

```text
  Governance      Process         Permission /       Implementation
  decision   ──▶  rule      ──▶   configuration ──▶  evidence

  ┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄

  Platform setting   ──✕──▶   governance authority

        ▲ shown and refused — not omitted

  ┌─ CDE ADMINISTRATION MAY ────┐  ┌─ DOES NOT ────────────────┐
  │ configure folders, spaces,  │  │ determine the information-│
  │ roles, permissions, workflow│  │ state model               │
  │   — where authorised        │  │ assign publication        │
  │ implement approved changes  │  │ authority                 │
  │ check configuration after   │  │ assign acceptance         │
  │ an approved change          │  │ authority                 │
  │                             │  │ approve technical design  │
  │ Holder: TBD                 │  │                           │
  └─────────────────────────────┘  └───────────────────────────┘

  A configuration that was never approved is a deviation,
  however competently it was applied.
```

## 5. Exact visible wording

**Forward chain — exact, four stages:**

`Governance decision` → `Process rule` → `Permission / configuration` → `Implementation evidence`

**Refused reverse — exact:**

`Platform setting   ──✕──▶   governance authority`

**Marker — exact:** `▲ shown and refused — not omitted`

**Left box — `CDE ADMINISTRATION MAY`, exact:**

- `configure folders, spaces, roles, permissions, workflow — where authorised`
- `implement approved changes`
- `check configuration after an approved change`
- `Holder: TBD`

**Right box — `DOES NOT`, exact:**

- `determine the information-state model`
- `assign publication authority`
- `assign acceptance authority`
- `approve technical design`

**Closing sentence — verbatim, `S1` §5.9:**

> A configuration that was never approved is a deviation, however competently it was applied.

**`Holder: TBD` appears, and no name does.** Not the CDE Administrator, not a role standing in for one.

## 6. Geometry or spatial relationships

Reference canvas **960 × 540 pt**, side margins **48 pt**, minimum type **14 pt**.

**Spatial relationships — fixed:**

| Relationship | Rule |
|---|---|
| Forward chain | **One row**, four stages of equal width, three arrows between them |
| Divider | A dotted rule beneath the chain, full content width |
| Refused reverse | **One row beneath the divider**, its own line, with the strike mark at the centre |
| Marker | Directly beneath the refused arrow, pointing at it |
| May / does-not boxes | **Two, side by side, equal width and equal height** |
| Closing sentence | Full content width at the foot |

**The `may` and `does not` columns carry equal weight.** A large *may* beside a small *does not* teaches that the exclusions are footnotes.

## 7. Connector semantics

| Connector | Form | Meaning |
|---|---|---|
| Between the four chain stages | **Solid, left to right, filled arrowheads** | The one supported direction |
| `Platform setting` → `governance authority` | **Drawn, and visibly refused** — the stroke is **interrupted by a strike mark**, and the arrowhead is retained so the refused claim is legible as a claim | The reverse **does not hold** |
| Any loop back to the start | **Prohibited — draw none** | A loop reintroduces the reverse direction the visual refuses |

**The refused arrow must not read as traversable.** The strike is **a break in the stroke with a cross at the break**, not a small mark laid over a continuous line — a continuous line with a decoration on it still reads as a route.

**Never Mermaid.** A renderer draws the refused reverse edge as a real edge, and a strike-through is styling a graph engine may drop. **`S1` §5.9's boundary must not depend on a stylesheet.**

## 8. Status and warning treatment

**Governance `CONTROLLED GOVERNANCE` and implementation `IMPLEMENTATION UNVERIFIED` both appear.**

**The reverse arrow appears and is visibly refused.** A forward-only chain is a chain someone can read backwards; **the refusal must be on the slide.**

**`Holder: TBD` appears in the left box**, and **no name appears anywhere.**

**The never-approved-configuration sentence appears verbatim.** It is `S1` §5.9's wording and it is the slide's takeaway.

**Evidence remains the required final stage of the chain** — it is not optional and not abbreviated.

## 9. Build or reveal sequence

**One frame preferred.** If built, the permitted order is **forward chain, then the refused reverse with its marker, then the two boxes.**

**The refused reverse may not be omitted from a shortened build.** A frame showing only the forward chain is a frame that can be read in either direction — **which is the entire failure this visual exists to prevent.**

## 10. Mandatory omissions

**Any permissions screenshot, matrix or platform UI** · any named administrator · **any org-chart shape or reporting line** · any loop back to the start · any numbered stages or gradient styling · any process-maturity graphic · any conformity claim · any claim that configuration proves live operation · **Module 6's verification method** — *how* alignment is proven is not this slide.

## 11. Accessibility and projection requirements

- **The refusal is carried in text as well as in the stroke** — the reverse row is labelled and marked `shown and refused — not omitted`, so a viewer who cannot resolve the strike still reads it as refused.
- **No meaning depends on colour**, and the refusal is **not** red — it is a governance boundary, not an error.
- **The refused arrow is legible in monochrome**: a break in the stroke plus a cross at the break.
- **The two boxes use the same border weight and type scale**, so the exclusions do not read as footnotes.
- **Reading order** — the four chain stages in order, the refused reverse and its marker, the *may* box, the *does not* box, then the closing sentence.
- **Type: chain stages 18 pt, box contents 16 pt, `Holder: TBD` 16 pt, marker 14 pt minimum, closing sentence 16 pt.**
- **Contrast ≥ 4.5:1** for text; **≥ 3:1** for strokes and box borders.

## 12. Screen-reader or presenter-notes description

> A left-to-right chain of four stages: governance decision, then process rule, then permission or configuration, then implementation evidence. Beneath a divider, a second arrow running the other way, from platform setting toward governance authority — **the stroke is broken and marked with a cross, and the arrow is labelled shown and refused, not omitted. This direction does not hold.** Below, two boxes of equal size. CDE Administration **may**: configure folders, spaces, roles, permissions and workflow where authorised; implement approved changes; check configuration after an approved change. **Holder: TBD.** CDE Administration **does not**: determine the information-state model; assign publication authority; assign acceptance authority; approve technical design. At the foot: a configuration that was never approved is a deviation, however competently it was applied.

## 13. Producer-failure test

The visual fails if a viewer can reasonably conclude:

- **configuration creates** governance authority;
- **platform permissions assign** publication or acceptance authority;
- the chain **may be read in either direction**;
- **configuring first and documenting later** is acceptable practice;
- a **platform setting proves** live implementation;
- the project **conforms** to something.

## 14. STOP conditions

**Stop production and return to the `W13` specification if:**

- **the reverse arrow is removed**, or is drawn as a real traversable arrow with a decoration on it;
- the visual is rebuilt in Mermaid or any graph renderer;
- a name appears in place of `Holder: TBD`;
- the *may* and *does not* boxes become unequal;
- the `S1` §5.9 sentence is paraphrased or dropped;
- a permissions screenshot, matrix or platform UI is introduced;
- an org chart or reporting line appears;
- a loop back to the start is added;
- the evidence stage is dropped from the chain;
- a verification method is added — that is Module 6.

## 15. Native PowerPoint reconstruction notes

**Reconstruct with native PowerPoint shapes, tables and text boxes.** **No image
is imported, and no diagram-rendering engine is used.**

**Four rectangles in a row, three arrows, one refused arrow, two boxes, one text box.** No SmartArt.

1. Chain as four rectangles of equal width with **three straight connectors, arrowheads at the right end of each.**
2. **Refused reverse: draw it as two short connector segments with a visible gap**, and place a cross glyph in the gap. **Keep the arrowhead** on the left-pointing end so the refused claim is legible as a claim. **Do not draw one continuous line with a cross on top** — that still reads as a route.
3. Marker text box directly beneath, pointing at the gap.
4. Two boxes of **identical width and height**, set numerically. `Holder: TBD` as the last line of the left box.
5. **Do not use a SmartArt process layout.** Every one of them offers a "cycle" variant, and a cycle is the reverse arrow reintroduced.
6. **Insert no screenshot, permissions matrix or platform UI image.**
7. Closing sentence as its own text box at the foot, **quoted verbatim.**
8. **After any theme change, verify the gap in the refused arrow is still visible** — some themes thicken connectors enough to close a small gap.

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
