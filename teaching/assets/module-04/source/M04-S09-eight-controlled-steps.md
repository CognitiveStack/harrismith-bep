# W9 · Slide 9 — The eight controlled steps, classified

| Field | Value |
|---|---|
| **Slide-source identifier** | `M04-S09` |
| **Slide number** | 9 |
| **Slide title** | The eight controlled steps, and the two that change state |
| **Visual identifier** | **`W9`** |
| **Visual title** | The eight controlled steps, classified |
| **Increment** | **Specified `T4-C` · source produced `T4-E-B`** |
| **Teaching purpose** | Show all eight steps **grouped by kind** — and that **only `T1` and `T4` change information state**. |
| **Principal sources** | **`S2` §3.1, §3.2**; `S2` §2, §3; `S1` §9.4, §9.7, §9.8; `S4` §8 |
| **Classification** | `SUPPORTING` throughout, with `CONTROLLED` for `T1`'s authority |
| **Governance status** | **Mixed** — `T1` controlled · `T4` **`BLOCKED`** · `T7` **`UNRESOLVED`** · the rest proposed |
| **Implementation status** | **`IMPLEMENTATION UNVERIFIED`** — *"no complete traceable cycle"* |
| **Fixed visual form** | **A table grouped by kind.** Five groups, eight rows — **never a flowchart, never Mermaid** |
| **Known limitation** | **The grouping by kind is `SUPPORTING`, drawn from `S2` §3.1–§3.2.** No source presents the eight as a table; the *classification* of each step is sourced, the *table* is the teaching form |
| **Overclaim risk** | **HIGHEST, jointly with `W3`** — eight identifiers in a row read as an eight-step state machine |
| **Blocked or unresolved element** | **YES** — `T4` blocked and `T7` unresolved, both in the same table |
| **Mandatory on-slide warning** | **`Only T1 and T4 change information state.`** — as a prominent headline, on the slide |
| **External imagery** | **None, and none is required.** A platform screenshot would assert implementation this module cannot evidence |
| **Rendered-asset status** | **`NONE`.** No rendering attempted; no renderer installed |

---

## 1. Purpose and five-second takeaway

Show all eight steps **grouped by kind** — and that **only `T1` and `T4` change information state**.

**If the audience takes one thing from this visual in five seconds:**

> Eight controlled steps. Only two of them change the information state.

## 2. Source and authority basis

**`S2` §3.1 and §3.2 classify each step**, and the classification — not the order — is what this visual carries. `S1` §9.4 establishes `T1`'s authority as the **Task-Team Lead**; `S1` §9.7 and §9.8 leave `T4`'s and `T7`'s authorities **unresolved**. `S4` §8 records that **no complete traceable cycle has been demonstrated**.

**A rendering of `T1 → T2 → … → T8` would assert four things the sources deny:**

| It would assert | The source says |
|---|---|
| One mandatory order | They are identifiers for **different controlled acts** |
| Eight sequential transitions | **Only `T1` and `T4` are information-state transitions** |
| Automatic progression | Every step has *"its own trigger, its own criteria and its own responsible function"* |
| A complete operating route | **`T4` is blocked; no complete cycle has been demonstrated** |

Source identifiers `S1`–`S14` are defined in
[`source-inventory.md`](../../../module-04-cde-workflows-and-information-states/source-inventory.md).
Classification follows
[`source-map.md`](../../../module-04-cde-workflows-and-information-states/source-map.md) §1.

## 3. Governance and implementation status

| | |
|---|---|
| **Governance status** | **Mixed** — `T1` controlled · `T4` **`BLOCKED`** · `T7` **`UNRESOLVED`** · the rest proposed |
| **Implementation status** | **`IMPLEMENTATION UNVERIFIED`** — *"no complete traceable cycle"* |

**Both are shown on the slide.** A visual that depicts a control without its
status **asserts an operating system that has not been verified** — the rule in
[`visual-demonstration-plan.md`](../../../module-04-cde-workflows-and-information-states/visual-demonstration-plan.md) §1.1.

## 4. Fixed layout

**A table grouped by kind — five groups, eight rows.**

| Group | Steps |
|---|---|
| `INFORMATION-STATE TRANSITIONS` | `T1`, `T4` |
| `ACTIONS AND USES — state unchanged` | `T2`, `T3` |
| `EVENTS — state unchanged` | `T5`, `T6` |
| `DECISION OR STATUS — state unchanged` | `T7` |
| `REWORK ROUTE` | `T8` |

**Grouping is by kind, not by journey.** **Resist numbering the groups** — `T1`–`T8` already look like a sequence, and adding *group 1, group 2* compounds it. **Label the groups by kind, and let the identifiers sit inside them.**

**The headline sits prominently on the slide**, not as a caption.

**The fixed form, carried from the `W9` specification:**

```text
  ── INFORMATION-STATE TRANSITIONS ──────────────────────────
     T1   WIP → Shared            authority: Task-Team Lead   ESTABLISHED
     T4   Shared → Published      authority: TBD              BLOCKED

  ── ACTIONS AND USES — state unchanged ─────────────────────
     T2   consume decision        Shared → Shared
     T3   coordination input      Shared → Shared

  ── EVENTS — state unchanged ───────────────────────────────
     T5   delivery executed       Published → Published
     T6   receipt registered      Published → Published

  ── DECISION OR STATUS — state unchanged ───────────────────
     T7   accept or reject        Published → Published       authority: TBD

  ── REWORK ROUTE ───────────────────────────────────────────
     T8   return to originator's WIP, then reuse T1 or T4

  ── HEADLINE, prominent:
     Only T1 and T4 change information state.
```

## 5. Exact visible wording

**Group headings and rows — exact:**

```text
── INFORMATION-STATE TRANSITIONS ──────────────────────────
   T1   WIP → Shared            authority: Task-Team Lead   ESTABLISHED
   T4   Shared → Published      authority: TBD              BLOCKED

── ACTIONS AND USES — state unchanged ─────────────────────
   T2   consume decision        Shared → Shared
   T3   coordination input      Shared → Shared

── EVENTS — state unchanged ───────────────────────────────
   T5   delivery executed       Published → Published
   T6   receipt registered      Published → Published

── DECISION OR STATUS — state unchanged ───────────────────
   T7   accept or reject        Published → Published       authority: TBD

── REWORK ROUTE ───────────────────────────────────────────
   T8   return to originator's WIP, then reuse T1 or T4
```

**Headline — exact, prominent:**

> Only `T1` and `T4` change information state.

**Implementation line — exact:** `no complete traceable cycle demonstrated`

## 6. Geometry or spatial relationships

Reference canvas **960 × 540 pt**, side margins **48 pt**, minimum type **14 pt**.

**Spatial relationships — fixed:**

| Relationship | Rule |
|---|---|
| Form | **A table**, five group bands, eight step rows |
| Columns | **Identifier · what it is · state effect · authority**, in that order |
| State-effect column | **Present on every row** — it is the slide's teaching |
| Group bands | **Full table width**, labelled by kind |
| Headline | **Above or below the table, prominent**, at heading size |
| Implementation line | Beneath the table, 14 pt |

**The state-effect column may not be dropped for space.** If the table will not fit, **shorten the descriptions**, never remove the column that shows six rows unchanged.

## 7. Connector semantics

**Not applicable — no connector, and this is absolute.**

**No Mermaid. No flowchart. No arrow chain. No left-to-right sequence. No numbering that implies order.**

**The `→` inside a row is a state-effect notation, not a connector** — it reads *WIP to Shared* within that one step, and it never joins one row to another.

**A grouped table is the only permitted form.** A producer who converts this to a flowchart has committed the module's prohibition 58.

## 8. Status and warning treatment

**`T4` is marked blocked and `T7` unresolved, in the same table** as the steps that are neither.

**`T1` and `T4` are visually distinguished — neutrally.** **Weight or a rule, not colour**, and **never green-for-`T1` / red-for-`T4`**. `T1` is not a success and `T4` is not a failure; one has an authority and one does not.

**Implementation status is visible** — *no complete traceable cycle demonstrated*.

**The six non-transitions show their state as unchanged, in their own column.** That column is the slide's teaching.

## 9. Build or reveal sequence

**One frame — the whole table appears together.**

**A group-by-group reveal is prohibited.** Revealing `INFORMATION-STATE TRANSITIONS` first and the rest afterwards re-creates the sequence the table exists to refuse.

## 10. Mandatory omissions

**Any flowchart** · **any arrow chain** · **any Mermaid block** · any left-to-right sequence · any numbering that implies order · any group numbering · any compliance colour · any green-for-`T1` or red-for-`T4` · any maturity styling · any suggestion of chronology.

## 11. Accessibility and projection requirements

- **The table is a real table**, with a header row and grouped body rows — not a picture of a table, and not a set of aligned text boxes.
- **`T1` and `T4` are distinguished by weight or a rule, never by colour**, so the distinction survives monochrome and colour-blind viewing.
- **The state-effect column carries words** — `Shared → Shared`, `WIP → Shared` — so the *unchanged* rows are readable rather than inferred from a blank cell. **No cell in that column is left empty.**
- **Reading order** — headline, then group by group, each group heading followed by its rows.
- **Type: headline 22 pt, group headings 16 pt, row text 14 pt minimum.**
- **Contrast ≥ 4.5:1** for text; **≥ 3:1** for table rules.

## 12. Screen-reader or presenter-notes description

> A table of eight controlled steps, **grouped by kind and not in a sequence**. Group one, information-state transitions: T1, WIP to Shared, authority Task-Team Lead, **established**; T4, Shared to Published, authority TBD, **blocked**. Group two, actions and uses, state unchanged: T2, consume decision, Shared to Shared; T3, coordination input, Shared to Shared. Group three, events, state unchanged: T5, delivery executed, Published to Published; T6, receipt registered, Published to Published. Group four, decision or status, state unchanged: T7, accept or reject, Published to Published, authority TBD. Group five, rework route: T8, return to the originator's WIP, then reuse T1 or T4. Headline: **only T1 and T4 change information state.** Implementation: no complete traceable cycle demonstrated. **There are no arrows between the steps.**

## 13. Producer-failure test

The visual fails if a viewer can reasonably conclude:

- the eight steps run in **one mandatory order**;
- there are **eight sequential transitions**;
- progression through them is **automatic**;
- the set describes a **complete operating route**.

## 14. STOP conditions

**Stop production and return to the `W9` specification if:**

- **the table is converted to a flowchart, an arrow chain or a Mermaid diagram** — this is the module's absolute case;
- the groups are numbered, or reordered into a journey;
- the state-effect column is dropped or left blank on any row;
- `T1` is coloured green or `T4` coloured red;
- the headline is removed or reduced to a caption;
- the implementation line is dropped;
- any row is presented as chronologically following another.

## 15. Native PowerPoint reconstruction notes

**Reconstruct with native PowerPoint shapes, tables and text boxes.** **No image
is imported, and no diagram-rendering engine is used.**

**One native PowerPoint table. No SmartArt, no shapes, no connectors.**

1. Insert a table with four columns — identifier, what it is, state effect, authority — and eight body rows plus five group rows.
2. **Group rows are merged full-width cells** with the group name in them. **Do not number them.**
3. **Distinguish `T1` and `T4` with a heavier rule or bold weight, not a fill colour.** If the table style applies banded fills, **turn banding off** — banded rows imply an order.
4. **Fill every cell in the state-effect column.** Empty cells read as *not applicable* rather than *unchanged*.
5. Headline as a separate text box at 22 pt.
6. **Do not convert the table to SmartArt at any point.** PowerPoint offers a "convert to SmartArt" action on tables and every available layout inserts a sequence.
7. **No entrance animation on rows or groups.**

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
