# W1 · Slide 1 — Governance → workflow → platform

| Field | Value |
|---|---|
| **Slide-source identifier** | `M04-S01` |
| **Slide number** | 1 |
| **Slide title** | A CDE is a governed process, not a folder tree |
| **Visual identifier** | **`W1`** |
| **Visual title** | Governance → workflow → platform |
| **Increment** | **Specified `T4-E-A` · source produced `T4-E-B`** |
| **Teaching purpose** | Show **three ordered layers**, governance above configuration, **each carrying its own status**. |
| **Principal sources** | `S1` §6.1, §6.9, §12.1; `S2` §1, §14, §17; `S3` §2, §3; `S4` §9; **`CGD-C01`, `CGD-C07`** |
| **Classification** | `CONTROLLED` + `INTERP` — the layering is the presenter's framing; every band item is sourced |
| **Governance status** | Band 1 **`CONTROLLED GOVERNANCE`** · Band 2 **`PROPOSED GOVERNANCE`** · Band 3 topology adopted (`S3` §2) |
| **Implementation status** | Band 3 **`IMPLEMENTATION UNVERIFIED`** (`CGD-C07`). Bands 1 and 2 make no implementation claim |
| **Fixed visual form** | **Three stacked horizontal bands of equal width and equal height, top to bottom.** Never side by side |
| **Known limitation** | The three-layer arrangement is the presenter's framing. **No controlled source draws these as layers** — each band's *content* is sourced, the *stacking* is `INTERP` |
| **Overclaim risk** | **HIGH** — three tidy bands read as *this is how it runs* |
| **Blocked or unresolved element** | No blocked route. **The three status labels are the mandatory element** — without them the diagram asserts a verified operating architecture |
| **Mandatory on-slide warning** | **`PROPOSED GOVERNANCE` on Band 2 does the warning's work.** It is not optional, not abbreviated and not moved to the notes |
| **External imagery** | **None, and none is required.** A platform screenshot would assert implementation this module cannot evidence |
| **Rendered-asset status** | **`NONE`.** No rendering attempted; no renderer installed |

---

## 1. Purpose and five-second takeaway

Show **three ordered layers**, governance above configuration, **each carrying its own status**.

**If the audience takes one thing from this visual in five seconds:**

> Governance decides; the platform implements. Never the other way round.

## 2. Source and authority basis

`S1` §6.1 gives the governing statement — the CDE is *"an information-management process supported by technology"*, and *"a folder structure is one way of implementing part of the process; it is not the process"*. `S2` states it independently: *"The CDE is a process, not a folder tree… the presence or absence of a folder proves nothing about state."*

**Band 2's status comes from `S2` itself**, which classifies its own workflow as `PROPOSED GOVERNANCE` and records that it **does not describe the live platform**. **Band 3's status comes from `CGD-C07`** — the four-area topology is adopted, and its implementation is unverified.

`S1` §6.9 and `S2` §14 supply the boundary that the reverse direction violates: **permission is not authority.** `S4` §9 puts it at its sharpest — *"being able to perform an action in the software says nothing about who was authorised to decide it."*

Source identifiers `S1`–`S14` are defined in
[`source-inventory.md`](../../../module-04-cde-workflows-and-information-states/source-inventory.md).
Classification follows
[`source-map.md`](../../../module-04-cde-workflows-and-information-states/source-map.md) §1.

## 3. Governance and implementation status

| | |
|---|---|
| **Governance status** | Band 1 **`CONTROLLED GOVERNANCE`** · Band 2 **`PROPOSED GOVERNANCE`** · Band 3 topology adopted (`S3` §2) |
| **Implementation status** | Band 3 **`IMPLEMENTATION UNVERIFIED`** (`CGD-C07`). Bands 1 and 2 make no implementation claim |

**Both are shown on the slide.** A visual that depicts a control without its
status **asserts an operating system that has not been verified** — the rule in
[`visual-demonstration-plan.md`](../../../module-04-cde-workflows-and-information-states/visual-demonstration-plan.md) §1.1.

## 4. Fixed layout

**Three stacked horizontal bands, top to bottom, in one column.**

The vertical order is **the content**, not a presentation preference:

1. **Governance and authority**
2. **CDE workflow and information states**
3. **Platform, folders, permissions and metadata**

**Never three columns.** Side by side implies equality between a decision and its implementation. **Never reordered.** A platform band above a governance band inverts the module's argument.

**The fixed form, carried from the `W1` specification:**

```text
  ┌──────────────────────────────────────────────────────────────────┐
  │  GOVERNANCE AND AUTHORITY                                        │
  │   · which function holds each authority                          │
  │   · what must be checked before information is shared            │
  │   · authorisation as a separate decision                         │
  │   · the obligation to retain traceably                           │
  │                        CONTROLLED GOVERNANCE  ·  S1 §6.1, §6.9   │
  └──────────────────────────────────────────────────────────────────┘
                        │
                        ▼   decides and authorises
  ┌──────────────────────────────────────────────────────────────────┐
  │  CDE WORKFLOW AND INFORMATION STATES                             │
  │   · the four states, and what each permits                       │
  │   · who may rely on information in each                          │
  │   · the transitions between them, and their gates                │
  │   · the evidence each transition must leave                      │
  │                        PROPOSED GOVERNANCE    ·  S2 §1, §3       │
  └──────────────────────────────────────────────────────────────────┘
                        │
                        ▼   implemented through
  ┌──────────────────────────────────────────────────────────────────┐
  │  PLATFORM, FOLDERS, PERMISSIONS AND METADATA                     │
  │   · root areas and folders                                       │
  │   · permissions and roles                                        │
  │   · platform settings and workflow configuration                 │
  │   · metadata fields                                              │
  │                   IMPLEMENTATION UNVERIFIED   ·  S3 §2 · CGD-C07 │
  └──────────────────────────────────────────────────────────────────┘

   The CDE is the governed process; the platform and folders are tools
   used to implement it.
```

## 5. Exact visible wording

**Band titles — exact:**

- `GOVERNANCE AND AUTHORITY`
- `CDE WORKFLOW AND INFORMATION STATES`
- `PLATFORM, FOLDERS, PERMISSIONS AND METADATA`

**Status labels — exact, no substitution:**

- `CONTROLLED GOVERNANCE`
- `PROPOSED GOVERNANCE`
- `IMPLEMENTATION UNVERIFIED`

**Connector labels — exact:**

- `decides and authorises`
- `implemented through`

**Closing message — exact.** It is `M4-S1-09`, **teaching synthesis**:

> The CDE is the governed process; the platform and folders are tools used to implement it.

**Four items per band, maximum. No fifth item, on any band.**

## 6. Geometry or spatial relationships

Reference canvas **960 × 540 pt**, origin top left, side margins **48 pt**, title zone `y` 0–72 reserved.

| Element | x | y | Size |
|---|---|---|---|
| Band 1 | 48 | 96 | 864 × 92 |
| Connector 1 — stem and arrowhead | 480 (centred) | 188 → 216 | 28 tall |
| Connector 1 label, left-aligned | 500 | 195 | — |
| Band 2 | 48 | 216 | 864 × 92 |
| Connector 2 — stem and arrowhead | 480 (centred) | 308 → 336 | 28 tall |
| Connector 2 label, left-aligned | 500 | 315 | — |
| Band 3 | 48 | 336 | 864 × 92 |
| Message, left-aligned | 48 | 452 | 864 wide, 2 lines |
| Status + source line, right-aligned inside each band | → 896 | band foot | 14 pt |

**All three bands are 864 × 92 pt.** Equal width and equal height are mandatory — unequal bands rank layers that are **ordered, not ranked**.

**Band separation ≥ 28 pt** so the three do not read as one block.

## 7. Connector semantics

| Connector | Form | Meaning |
|---|---|---|
| Band 1 → Band 2 | **Solid stem, filled arrowhead, downward only** | Governance **decides and authorises** the workflow |
| Band 2 → Band 3 | **Solid stem, filled arrowhead, downward only** | The workflow is **implemented through** the platform |
| Any upward arrow | **Prohibited — draw none** | Would assert that configuration changes governance |

**Exactly two connectors. Both downward. Neither bidirectional.** A return arrow asserts that configuration changes governance — the failure `S2` §17 rule 1 exists to prevent.

Connector labels sit **beside** the arrow, not on it, so they stay readable and do not overlap a stroke.

## 8. Status and warning treatment

**All three status labels are on the slide.** Notes are not a substitute — a three-layer diagram without statuses looks like a verified operating architecture, which is the module's central overclaim.

**Status and source travel together** in one right-aligned label at the foot of each band, so a producer cannot delete one and keep the other:

- `CONTROLLED GOVERNANCE · S1 §6.1, §6.9`
- `PROPOSED GOVERNANCE · S2 §1, §3`
- `IMPLEMENTATION UNVERIFIED · S3 §2 · CGD-C07`

## 9. Build or reveal sequence

**Three steps, one per band, top to bottom.**

**Each band appears together with its own status label and its incoming connector.** No frame ever shows a band without its status.

If a static export is produced for the assembly package, **it is the final frame only.**

## 10. Mandatory omissions

No platform logo · no screenshot · no product name · no upward or bidirectional connector · no feedback loop · no equals sign between CDE and platform · no completion tick · no maturity or progress styling · no person, role or reporting line · no claim that the workflow is operating.

## 11. Accessibility and projection requirements

- **Reading order is top to bottom**, in one column: band 1 → connector 1 → band 2 → connector 2 → band 3 → message.
- **Status meaning never depends on colour.** Each status is a word, spelled out. If bands are tinted, the tint may not be the only difference between `CONTROLLED` and `PROPOSED`.
- **Text contrast ≥ 4.5:1.** Band titles 22 pt, items 16 pt, **status and source labels never below 14 pt.**
- **Band border contrast ≥ 3:1** against the background.
- **No meaning carried by an icon**, platform or otherwise.

## 12. Screen-reader or presenter-notes description

> Three stacked bands, read top to bottom. Band one, Governance and authority: which function holds each authority; what must be checked before information is shared; authorisation as a separate decision; the obligation to retain traceably. Status: controlled governance. A downward arrow labelled *decides and authorises*. Band two, CDE workflow and information states: the four states and what each permits; who may rely on information in each; the transitions between them and their gates; the evidence each transition must leave. Status: proposed governance. A downward arrow labelled *implemented through*. Band three, Platform, folders, permissions and metadata: root areas and folders; permissions and roles; platform settings and workflow configuration; metadata fields. Status: implementation unverified. **There is no arrow in the upward direction.**

## 13. Producer-failure test

The visual fails if a viewer can reasonably conclude:

- the platform **is** the CDE;
- configuration **defines** governance;
- the workflow is **verified live**;
- the three layers are **organisational ranks**.

## 14. STOP conditions

**Stop production and return to the `W1` specification if:**

- any arrow points upward, or any connector becomes bidirectional;
- any platform logo, screenshot or product name is introduced;
- any band loses its status label, or a status is moved to the notes;
- the workflow band is labelled operational, live, implemented or verified;
- the bands acquire unequal size, numbering, or an org-chart appearance;
- the three bands are rearranged side by side.

## 15. Native PowerPoint reconstruction notes

**Reconstruct with native PowerPoint shapes, tables and text boxes.** **No image
is imported, and no diagram-rendering engine is used.**

**Three rectangles, one text box each, two straight connectors.** No SmartArt.

1. Insert three rectangles at the geometry above. **Set width and height numerically** — do not size by eye, because the equality is a control.
2. Band text: title in 22 pt, four bullets in 16 pt, status-and-source line right-aligned in 14 pt at the band foot.
3. Two straight connectors, **arrowhead at the lower end only**. Set arrow style explicitly; PowerPoint's default connector has no head.
4. Connector labels as separate text boxes at x 500 — **not as connector labels**, which PowerPoint centres on the line.
5. **Do not use a SmartArt process or hierarchy layout.** Both re-flow on edit, and the hierarchy layouts add reporting-line semantics this visual prohibits.
6. Three animation steps if animating; otherwise one static build. **Never animate a band separately from its status label.**

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
