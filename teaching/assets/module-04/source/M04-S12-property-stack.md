# W12 · Slide 12 — The property stack and the four unestablished standards

| Field | Value |
|---|---|
| **Slide-source identifier** | `M04-S12` |
| **Slide number** | 12 |
| **Slide title** | Naming, revision, suitability and metadata support control |
| **Visual identifier** | **`W12`** |
| **Visual title** | The property stack and the four unestablished standards |
| **Increment** | **Specified `T4-D` · source produced `T4-E-B`** |
| **Teaching purpose** | Show the six properties as **six different control questions**, and that **four of the standards behind them do not exist**. |
| **Principal sources** | **`S1` §6.8, §11.3, §11.4**; `S2` §13; `S12`; **`CGD-C01`, `CGD-C03`** |
| **Classification** | `CONTROLLED` + `INTERP` |
| **Governance status** | **`CONTROLLED GOVERNANCE`** — what each property must support. **`UNRESOLVED`** — every code set and the schema |
| **Implementation status** | **No standard established.** All four `standards/` directories hold only `.gitkeep` |
| **Fixed visual form** | **Two zones.** Left: six property rows, each with its control question. Right: four boxes, all **empty** |
| **Known limitation** | **The six control questions are the presenter's framing.** The property *definitions* are `S1` §6.8 and §11.3–§11.4; the *questions* are how this module teaches them |
| **Overclaim risk** | **HIGH** — a populated property stack teaches four standards that do not exist |
| **Blocked or unresolved element** | **YES — four empty boxes, shown and unfilled** |
| **Mandatory on-slide warning** | **`A code identifies. It does not authorise, and it does not prove the process behind it occurred.`** — on the slide |
| **External imagery** | **None, and none is required.** A platform screenshot would assert implementation this module cannot evidence |
| **Rendered-asset status** | **`NONE`.** No rendering attempted; no renderer installed |

---

## 1. Purpose and five-second takeaway

Show the six properties as **six different control questions**, and that **four of the standards behind them do not exist**.

**If the audience takes one thing from this visual in five seconds:**

> The properties control identification and permitted use. Four of the standards behind them have not been decided.

## 2. Source and authority basis

**This visual uses `W12`'s six-property stack, not `W2`'s five-card row.** The two are different visuals answering different questions, and the layouts are not interchangeable — `W2` compares five properties as peers; `W12` sets six control questions against four missing standards.

`S1` §11.3 records that the **Naming Standard does not yet exist**, that **no final naming syntax is created**, that **no ISO 19650 filename pattern is imposed**, and that **platform folder placement alone is not identification**. `S1` §11.4 records that **no classification system is adopted** and that **software-native metadata is not the project standard** — metadata is *"defined by governance, not inherited from whatever fields a tool happens to provide"*.

**`S12` is the physical finding:** all four `standards/` subdirectories contain **only `.gitkeep`**. `CGD-C01` and `CGD-C03` supply the code-versus-evidence boundary the slide closes on.

Source identifiers `S1`–`S14` are defined in
[`source-inventory.md`](../../../module-04-cde-workflows-and-information-states/source-inventory.md).
Classification follows
[`source-map.md`](../../../module-04-cde-workflows-and-information-states/source-map.md) §1.

## 3. Governance and implementation status

| | |
|---|---|
| **Governance status** | **`CONTROLLED GOVERNANCE`** — what each property must support. **`UNRESOLVED`** — every code set and the schema |
| **Implementation status** | **No standard established.** All four `standards/` directories hold only `.gitkeep` |

**Both are shown on the slide.** A visual that depicts a control without its
status **asserts an operating system that has not been verified** — the rule in
[`visual-demonstration-plan.md`](../../../module-04-cde-workflows-and-information-states/visual-demonstration-plan.md) §1.1.

## 4. Fixed layout

**Two zones, stacked.**

**Upper zone:** six property rows, each with its control question — `PROPERTY` and `CONTROL QUESTION` as column headings.

**Lower zone, under an `ON THIS PROJECT:` heading:** four labelled boxes, **all empty**, each with `not established` beside it, and a marker beneath: `▲ four positions, shown and empty — not omitted`.

**Beneath: the code-versus-authority line.**

**Give the empty zone at least equal area to the property list.** A producer's instinct is to shrink an empty element and grow a populated one — **which inverts the teaching.**

**The fixed form, carried from the `W12` specification:**

```text
  PROPERTY              CONTROL QUESTION
  ────────────────────  ──────────────────────────────────────────
  Name / identifier     Which container is this?
  Version               Which stored platform occurrence?
  Revision              Which managed issue applies?
  Status                What condition is declared?
  Suitability           For what purpose may it be relied upon?
  Metadata              Which structured attributes support control?

  ───────────────────────────────────────────────────────────────

  ON THIS PROJECT:

  Naming standard        ┌──────────────────────┐   not established
                         └──────────────────────┘
  Revision convention    ┌──────────────────────┐   not established
                         └──────────────────────┘
  Suitability code set   ┌──────────────────────┐   not established
                         └──────────────────────┘
  Metadata schema        ┌──────────────────────┐   not established
                         └──────────────────────┘

           ▲ four positions, shown and empty — not omitted

  A code identifies. It does not authorise, and it does not
  prove the process behind it occurred.
```

## 5. Exact visible wording

**Upper zone — exact, six rows:**

| Property | Control question |
|---|---|
| `Name / identifier` | `Which container is this?` |
| `Version` | `Which stored platform occurrence?` |
| `Revision` | `Which managed issue applies?` |
| `Status` | `What condition is declared?` |
| `Suitability` | `For what purpose may it be relied upon?` |
| `Metadata` | `Which structured attributes support control?` |

**Lower zone — exact, four boxes, all empty:**

- `Naming standard` — `not established`
- `Revision convention` — `not established`
- `Suitability code set` — `not established`
- `Metadata schema` — `not established`

**Marker — exact:** `▲ four positions, shown and empty — not omitted`

**Closing line — exact:**

> A code identifies. It does not authorise, and it does not prove the process behind it occurred.

**`not established` is the label on each.** **Not *TBD in progress*, not *to follow*, not a date.**

## 6. Geometry or spatial relationships

Reference canvas **960 × 540 pt**, side margins **48 pt**, minimum type **14 pt**.

**Spatial relationships — fixed:**

| Relationship | Rule |
|---|---|
| Upper zone | Six rows, two columns — property left, question right |
| Divider | A single rule between the zones, full content width |
| `ON THIS PROJECT:` | A heading above the four boxes |
| Four boxes | **Stacked, identical size, all empty**, label left, `not established` right |
| Box height | **At least one full text line each** — they must read as positions, not gaps |
| Marker | Centred beneath the four boxes |
| Closing line | At the foot, full content width |

**The empty zone has at least equal area to the property list.** Set both zones numerically; do not let the six-row table take two thirds of the slide.

## 7. Connector semantics

**Not applicable — no connector, by requirement.**

**No arrows implying progression.** The six properties are not a sequence and not a maturity ladder.

**No connector between a property row and a box**, even where the names correspond — a line from `Revision` to `Revision convention` would imply the standard follows automatically from the property, which is the opposite of the slide.

**No arrow into or out of any empty box.**

## 8. Status and warning treatment

**Governance `CONTROLLED GOVERNANCE` for what each property must support; `UNRESOLVED` for every code set and the schema** — both stated.

**All four boxes appear, and all four are empty.** **Omitting them implies no decision is needed; filling any one invents a standard.**

**No tick, no red, no warning triangle on the empty boxes.** They are **an undecided decision, not a defect.**

**No date, and no *in progress* wording** — **no source records any standards work in progress**, and a date reads as *already in hand*.

## 9. Build or reveal sequence

**One frame — both zones appear together.**

**A staged reveal is prohibited.** Revealing the six properties first and the four empty boxes second makes the absence a punchline, and **the frame before the reveal shows a complete-looking property standard.**

## 10. Mandatory omissions

Any coding standard · **any example code, filename, revision, suitability or status value** · any metadata field set · **any classification system** — Uniclass, OmniClass and MasterFormat are unadopted (`S1` §11.4) and naming one implies otherwise · **any software field list or properties-palette screenshot** · any fire-station example · any model-container name · any maturity or progress model · any tick, red or warning triangle on the empty boxes · Module 5's suitability-in-delivery-planning.

## 11. Accessibility and projection requirements

- **The emptiness of the four boxes is carried in words** — `not established` — not by whitespace, which a screen reader would skip.
- **No meaning depends on colour.** The empty boxes are **not** shaded, hatched or greyed.
- **The six rows are a real two-column table**, with property and question as paired cells, so the pairing survives linearisation.
- **Reading order** — the six property rows in order, then `ON THIS PROJECT:`, the four boxes in order, the marker, then the closing line.
- **Type: column headings 16 pt, rows 16 pt, box labels 16 pt, `not established` 14 pt minimum, closing line 16 pt.**
- **Contrast ≥ 4.5:1** for text; **≥ 3:1** for box borders and the divider rule.

## 12. Screen-reader or presenter-notes description

> Two zones. Upper zone, six properties and the control question each answers. Name or identifier: which container is this? Version: which stored platform occurrence? Revision: which managed issue applies? Status: what condition is declared? Suitability: for what purpose may it be relied upon? Metadata: which structured attributes support control? Lower zone, headed **on this project**: four bordered boxes, **all empty**. Naming standard — **not established**. Revision convention — **not established**. Suitability code set — **not established**. Metadata schema — **not established**. Marked: four positions, **shown and empty — not omitted**. At the foot: a code identifies; it does not authorise, and it does not prove the process behind it occurred. **No code, filename, field name or schema appears anywhere on this visual.**

## 13. Producer-failure test

The visual fails if a viewer can reasonably conclude:

- **a naming, revision, suitability or metadata standard exists** on this project;
- one is **in progress** or **due on a date**;
- **a code proves** the process behind it occurred;
- **metadata creates authority**;
- the six properties are a **maturity sequence**.

## 14. STOP conditions

**Stop production and return to the `W12` specification if:**

- **any of the four boxes is filled, shaded, greyed or removed**;
- an example code, filename, field name or schema appears — **including as "something like"**;
- a classification system is named;
- a properties-palette screenshot or software field list is introduced;
- `not established` is replaced by *TBD in progress*, *to follow*, or a date;
- a tick, red styling or warning triangle appears on an empty box;
- an arrow or connector is drawn between properties or into a box;
- the empty zone is shrunk below the area of the property list.

## 15. Native PowerPoint reconstruction notes

**Reconstruct with native PowerPoint shapes, tables and text boxes.** **No image
is imported, and no diagram-rendering engine is used.**

**One two-column table, four rectangles, three text boxes. No icons, no SmartArt.**

1. Upper zone as a **native two-column table**, six rows, banding **off**.
2. Four boxes as rectangles of identical size, **plain border, no fill**, each at least one text line tall. **Leave the interior genuinely empty** — the label sits to the left and `not established` to the right, **outside the box.**
3. **Apply no theme fill to the boxes.** A filled or shaded box reads as answered or as failed.
4. **Insert no icon.** No warning triangle, no tick, no document glyph.
5. Marker as a small centred text box beneath the boxes.
6. Set the two zones' heights numerically so the lower zone is **at least equal in area** to the upper one.
7. **No entrance animation** — one frame.
8. **Do not reuse the Slide 2 card layout.** `W2` and `W12` are different visuals; five cards here would drop metadata and lose the four empty positions.

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
