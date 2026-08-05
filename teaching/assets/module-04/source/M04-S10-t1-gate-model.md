# W10 · Slide 10 — The `T1` gate model

| Field | Value |
|---|---|
| **Slide-source identifier** | `M04-S10` |
| **Slide number** | 10 |
| **Slide title** | Gates, authority and evidence |
| **Visual identifier** | **`W10`** |
| **Visual title** | The `T1` gate model |
| **Increment** | **Specified `T4-C` · source produced `T4-E-B`** |
| **Teaching purpose** | Unpack **one** controlled transition — trigger, checks, authority, evidence, permitted use. |
| **Principal sources** | **`S2` §3.1–§3.3, §9**; `S1` §7.7, §9.4, §9.11; `S4` §7, §8 |
| **Classification** | `SUPPORTING` + `CONTROLLED` + `DECISION-RECORD` |
| **Governance status** | **`CONTROLLED GOVERNANCE`** — the only transition with an established authority |
| **Implementation status** | **`IMPLEMENTATION UNVERIFIED`** — no complete cycle demonstrated |
| **Fixed visual form** | **One transition, five stages, four side labels.** Nothing else |
| **Known limitation** | **`ARC-01` is one qualified observation, not a complete cycle** (`S4` §7, §8). `T1` is **controlled and unverified at the same time**, and the visual must show both |
| **Overclaim risk** | **MEDIUM-HIGH** — a fully populated example reads as a running procedure |
| **Blocked or unresolved element** | **The evidence field is the mandatory element.** It is what distinguishes a governed transition from a file move, and it may not be abbreviated away |
| **Mandatory on-slide warning** | **`Governance definition ≠ live implementation evidence`** — on the slide |
| **External imagery** | **None, and none is required.** A platform screenshot would assert implementation this module cannot evidence |
| **Rendered-asset status** | **`NONE`.** No rendering attempted; no renderer installed |

---

## 1. Purpose and five-second takeaway

Unpack **one** controlled transition — trigger, checks, authority, evidence, permitted use.

**If the audience takes one thing from this visual in five seconds:**

> A transition needs checks, an authority and evidence. Not one of the three is optional.

## 2. Source and authority basis

`S2` §3.1–§3.3 supply `T1`'s anatomy — trigger, required checks, gate conditions, authority, evidence, permitted use. **`S1` §9.4 establishes the authority: the Task-Team Lead** (or another allocated role where governance assigns it) — **`T1` is the only transition in the module with an established authorising function.**

`S1` §7.7 is why the gate conditions are not a checklist: **no numeric quality thresholds are set.** The readiness list is a judgement set, and **eight boxes would make it look otherwise** — show three or four.

`S1` §9.11 and `S2` §9 place **CDE Administration beside the chain**: it implements the permission arrangement and **does not decide**. `S4` §7–§8 give the implementation limit — one qualified container observation, **no complete traceable cycle**.

Source identifiers `S1`–`S14` are defined in
[`source-inventory.md`](../../../module-04-cde-workflows-and-information-states/source-inventory.md).
Classification follows
[`source-map.md`](../../../module-04-cde-workflows-and-information-states/source-map.md) §1.

## 3. Governance and implementation status

| | |
|---|---|
| **Governance status** | **`CONTROLLED GOVERNANCE`** — the only transition with an established authority |
| **Implementation status** | **`IMPLEMENTATION UNVERIFIED`** — no complete cycle demonstrated |

**Both are shown on the slide.** A visual that depicts a control without its
status **asserts an operating system that has not been verified** — the rule in
[`visual-demonstration-plan.md`](../../../module-04-cde-workflows-and-information-states/visual-demonstration-plan.md) §1.1.

## 4. Fixed layout

**One horizontal chain from `WIP` to `SHARED`**, with four side labels above it and the stage content beneath it.

**Four side labels, distinctly placed:** `Author` · `Checker` · `Task-Team Lead` · `receiving user`.

**`CDE Administration` sits beside the chain, not in it** — on its own line, below, labelled as implementer.

**Beneath: the failure route, then the governance-versus-implementation line.**

**The fixed form, carried from the `W10` specification:**

```text
                  Author        Checker      Task-Team Lead    receiving user
                    │              │               │                 │
   WIP ─────────────┴──────────────┴───────────────┴─────────────────┴──► SHARED
        required checks    gate conditions    AUTHORITY      EVIDENCE     for the
        · technical /      · information      Task-Team      · version    defined
          content            present            Lead           history    purpose
        · information-     · checking         (or another    · checking
          quality /          complete          allocated       record
          readiness        · purpose of        role)         · share /
                             sharing known                     exchange
                                                               record

   CDE Administration — implements the permission arrangement; does not decide

   Failure route:  information remains in, or returns to, WIP.
                   NO PARTIAL PROGRESSION.

   Governance definition  ≠  live implementation evidence
```

## 5. Exact visible wording

**Chain ends — exact:** `WIP` … `SHARED` … `for the defined purpose`

**Side labels — exact, four:** `Author` · `Checker` · `Task-Team Lead` · `receiving user`

**Stage content — exact:**

- `required checks: · technical / content · information-quality / readiness`
- `gate conditions: · information present · checking complete · purpose of sharing known`
- `AUTHORITY: Task-Team Lead (or another allocated role)`
- `EVIDENCE: · version history · checking record · share / exchange record`

**CDE Administration line — exact:**

> CDE Administration — implements the permission arrangement; does not decide

**Failure route — exact:**

> Failure route: information remains in, or returns to, WIP. **NO PARTIAL PROGRESSION.**

**Closing line — exact:**

> Governance definition ≠ live implementation evidence

**`T4` gets one sentence only** — *"and the next slide is where this breaks down"*.

## 6. Geometry or spatial relationships

Reference canvas **960 × 540 pt**, side margins **48 pt**, minimum type **14 pt**.

**Spatial relationships — fixed:**

| Relationship | Rule |
|---|---|
| Chain | **One horizontal line**, left to right, `WIP` at the left end, `SHARED` at the right |
| Side labels | **Above the chain**, four of them, each above the stage it belongs to |
| Stage content | **Beneath the chain**, in four columns aligned to the stages |
| Evidence column | **Aligned to the chain like the others** — never smaller, never a footnote |
| CDE Administration | **On its own line beneath the stage columns**, clearly outside the chain |
| Failure route | Beneath that |
| Closing line | At the foot |

**The evidence column is the same width and weight as the others.** **If space is short, cut a gate condition — never the evidence.**

**Show three or four gate conditions, not all eight.** The readiness list is a judgement set, and eight boxes make it look like a checklist.

## 7. Connector semantics

| Connector | Form | Meaning |
|---|---|---|
| `WIP` → `SHARED` | **One solid horizontal line with a filled arrowhead at the Shared end** | The `T1` transition, whose authority is established |
| Side labels → chain | **Short plain drop lines, no arrowheads** | Which function acts at which stage |
| Failure route | **A return line to WIP, or a labelled statement** | Information remains in, or returns to, WIP |
| CDE Administration → chain | **Prohibited — draw none** | It implements; it does not decide, and a connector would place it in the decision |
| Any publication path | **Prohibited — draw none** | `T4` is Slide 11 |

**No completion marker at the Shared end**, and **no green approval tick anywhere.**

## 8. Status and warning treatment

**Both statuses appear, and the visual states their coexistence explicitly** — `T1` is `CONTROLLED GOVERNANCE` **and** `IMPLEMENTATION UNVERIFIED` at the same time. **The closing line carries it:** `Governance definition ≠ live implementation evidence`.

**`ARC-01` is not presented as a complete cycle.** If implementation is annotated, it is the qualified form only.

**The evidence field is visible and is not abbreviated away.** It is the field that distinguishes a governed transition from a file move.

## 9. Build or reveal sequence

**One frame preferred.** If built, the permitted order is **chain, then stage content left to right, then CDE Administration, then the failure route and closing line.**

**The evidence column may not be the last-revealed element if the slide might be cut short**, and it may never be omitted from a shortened build. If the deck animates, **evidence appears no later than authority.**

## 10. Mandatory omissions

Any publication path · any `T4` content beyond one sentence · **any green approval tick** · any completion marker at the Shared end · any claim of complete live execution · the full eight-item readiness list · any numeric quality threshold · **any connector placing CDE Administration in the chain** · any folder-location icon standing in for the evidence field.

## 11. Accessibility and projection requirements

- **The evidence field is text, and is named** — a folder icon or a document glyph in its place would be unreadable and would assert a location.
- **CDE Administration's position outside the chain is stated in words** — *implements the permission arrangement; does not decide* — not carried by placement alone.
- **The failure route is stated in words**, including `NO PARTIAL PROGRESSION`.
- **No meaning depends on colour**, and no green appears.
- **Reading order** — WIP, the four side labels in order, the four stage columns in order, Shared and its defined purpose, CDE Administration, the failure route, then the closing line.
- **Type: chain-end labels 20 pt, side labels 16 pt, stage content 14 pt minimum, closing line 16 pt.**
- **Contrast ≥ 4.5:1** for text; **≥ 3:1** for the chain and drop lines.

## 12. Screen-reader or presenter-notes description

> One horizontal transition from WIP to Shared, for the defined purpose. Above the chain, four functions in order: Author; Checker; Task-Team Lead; receiving user. Beneath the chain, four columns. Required checks: technical and content; information-quality and readiness. Gate conditions: information present; checking complete; purpose of sharing known. **Authority: Task-Team Lead, or another allocated role.** **Evidence: version history; checking record; share or exchange record.** Beside the chain, not in it: CDE Administration implements the permission arrangement; **it does not decide**. Failure route: information remains in, or returns to, WIP — **no partial progression**. At the foot: **governance definition is not live implementation evidence.**

## 13. Producer-failure test

The visual fails if a viewer can reasonably conclude:

- `T1` is **running live** as drawn;
- the gate conditions are a **checklist with thresholds**;
- **CDE Administration decides** the transition;
- **partial progression** is possible;
- the evidence requirement is **satisfied by a folder location**.

## 14. STOP conditions

**Stop production and return to the `W10` specification if:**

- **the evidence field is compressed, omitted, or converted into a folder-location icon**;
- a green approval tick or completion marker appears at the Shared end;
- a publication path is drawn;
- CDE Administration is placed **inside** the chain, or connected to it;
- all eight readiness conditions are shown as a checklist;
- a numeric quality threshold is introduced;
- the failure route is dropped;
- the governance-versus-implementation line is removed;
- `ARC-01` is described as a complete cycle.

## 15. Native PowerPoint reconstruction notes

**Reconstruct with native PowerPoint shapes, tables and text boxes.** **No image
is imported, and no diagram-rendering engine is used.**

**One horizontal connector, four column text boxes, four label text boxes, three lines of text.**

1. Chain as a single straight connector, solid, **arrowhead at the Shared end only.**
2. Stage content as **four text boxes of equal width**, aligned to the chain. **Set the evidence box to the same width as the others** — do not let autofit shrink it.
3. **Turn off "shrink text on overflow" for the evidence box.** If it overflows, remove a gate condition from the adjacent box instead.
4. Side labels as four text boxes above, with **short plain drop lines, arrowheads set to none.**
5. CDE Administration as a text box **clearly below the columns**, with **no connector to the chain.**
6. **Insert no icon in the evidence column.** PowerPoint's icon library offers folder and document glyphs, and either would replace an evidence requirement with a location.
7. **Use no green fill and no tick glyph.**
8. If animating, group authority and evidence so evidence cannot be left un-revealed.

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
