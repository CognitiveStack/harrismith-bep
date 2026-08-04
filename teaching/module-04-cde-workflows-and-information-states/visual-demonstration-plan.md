# Module 4 — Visual Demonstration Plan

**Status:** Visual specifications for the whole Module 4 presentation. **No
visual source file and no rendered image asset exists.** Nothing here is a final
asset, and creating assets is the next increment.

**All fourteen visuals are now specified in full** — `W4`–`W7` (T4-B),
`W8`–`W11` (T4-C), `W12`–`W14` (T4-D) and **`W1`–`W3` (T4-E-A)**, the Section A
opening visuals that carried the module's teaching argument before any state,
transition or property had been introduced.

**A specification is authoritative. A rendered or PowerPoint version is
derivative of the source file, which is itself derivative of the entry here.**

**No visual in this module is Mermaid.** Every specified form is a layout
specification, for the reason given in section 2 and restated in the summary.

Source identifiers `S1`–`S14` are defined in
[`source-inventory.md`](source-inventory.md). Classification follows
[`source-map.md`](source-map.md) §1.

---

## 1. Two rules that govern every entry

### 1.1 Governance status and implementation status are both shown

**Every visual that depicts a control must make clear whether it is governed,
proposed, blocked or unverified.** `S2` classifies its own workflow as
**`PROPOSED GOVERNANCE`** and states it **does not describe the live platform**.

A visual that shows a workflow without its status **asserts an operating system
that has not been verified**.

### 1.2 Nothing that is blocked, empty or unresolved is completed

Five things stay visibly incomplete throughout the module:

| | Stays | Because |
|---|---|---|
| **`Shared → Published`** | **Broken** | `T4` has **no available authorising function**; information **remains Shared** |
| **`TRN-E03`** | **Blocked** | **PROPOSED — BLOCKED**, on five matters |
| **Record / Retained** | **Not a folder** | **No `04 Archive` root is approved or required** |
| **Publication and acceptance authority** | **Unheld** | `S4` §9 — **no evidence established** |
| **Code sets and metadata schema** | **Absent** | All four `standards/` directories are empty |

**A producer who completes any of these introduces the module's most misleading
claims.**

## 2. Mermaid caution

**Mermaid is used only where it cannot misrepresent the model.** It is
**avoided** where it would:

| Risk | Affected visuals |
|---|---|
| **Auto-complete a blocked route** | `W3`, `W9`, `W11` |
| Imply hierarchy where none exists | `W1`, `W13` |
| Imply that states progress automatically | `W3`, `W9` |
| **Hide evidence fields** | `W10` |
| Convert a conceptual model into an operating workflow | `W3`, `W9`, `W11` |
| Arrange non-sequential properties as a sequence | `W2`, `W12` |
| **Draw a refused edge as a real edge** | `W13` |
| Balance a deliberately sparse question set with generated structure | `W14` |

**A native-layout specification is preferable wherever deliberate incompleteness
matters** — and in this module it matters on more visuals than not. **The outcome
of applying that test to all fourteen is that none of them is Mermaid.**

## 3. How to read this plan

| Field | Meaning |
|---|---|
| **Slide** | Where it is used |
| **Teaching purpose** | The one thing the audience should take from it |
| **Source basis** | The `S`-identifiers behind it |
| **Classification** | Per [`source-map.md`](source-map.md) §1 |
| **Governance status** | Controlled · proposed · planned · blocked · unresolved |
| **Implementation status** | Verified · unverified · not reached |
| **Simplify** | What must be compressed |
| **Omit** | What must not reach the slide |
| **Overclaim risk** | The risk of asserting more than the sources support |
| **Blocked element visible?** | Whether something must stay incomplete |
| **Live evidence required?** | Whether a platform observation would be needed |
| **External imagery** | Whether an external image would add value |

**On live evidence.** The answer is **no** for every visual. `S4` is an
**existing controlled record**, read as evidence. **No new observation is
requested, and none is authorised** — root [`README.md`](../../README.md) §2.1
applies unmodified.

**On external imagery.** **No** for every visual. A platform screenshot would
assert implementation this module cannot evidence.

### 3.1 Reference canvas and geometry conventions

**`W1`, `W2` and `W3` carry fixed point geometry.** It is expressed on a single
reference canvas so that three specifications cannot drift apart:

| Convention | Value |
|---|---|
| **Reference canvas** | **960 × 540 pt** — 13.333 × 7.5 in, standard 16:9 |
| **Origin** | Top left. `x` increases right, `y` increases down |
| **Side margins** | **48 pt** (`W1`, `W2`) · **40 pt** (`W3`, which carries four panels) |
| **Title zone** | `y` 0–72, reserved. No visual element enters it |
| **Minimum type size** | **14 pt.** Status labels, source labels and connector labels never go below it |
| **Minimum text contrast** | **4.5:1** |
| **Minimum stroke and border contrast** | **3:1** |

**Geometry is a control, not a preference.** Equal panels, equal gutters and a
fixed minimum type size are how these three visuals stop a producer from
enlarging what is populated and shrinking what is deliberately empty — the
failure §1.2 exists to prevent.

**`W4`–`W14` state form, labels and mandatory requirements without point
geometry.** A producer applies **this same canvas and these same minimums** to
them; their fixed forms and design requirements remain authoritative unchanged.

---

## 4. Visual specifications

### W1 — Governance → workflow → platform · **specified (T4-E-A)**

| Field | Value |
|---|---|
| **Slide** | 1 — *A CDE is a governed process, not a folder tree* |
| **Teaching purpose** | Show **three ordered layers**, governance above configuration, **each carrying its own status** |
| **Source basis** | `S1` §6.1, §6.9, §12.1; `S2` §1, §14, §17; `S3` §2, §3; `S4` §9; **`CGD-C01`, `CGD-C07`** |
| **Classification** | `CONTROLLED` + `INTERP` — the layering is the presenter's framing; every band item is sourced |
| **Governance status** | Band 1 **`CONTROLLED GOVERNANCE`** · Band 2 **`PROPOSED GOVERNANCE`** · Band 3 topology adopted (`S3` §2) |
| **Implementation status** | Band 3 **`IMPLEMENTATION UNVERIFIED`** (`CGD-C07`). Bands 1 and 2 make no implementation claim |
| **Fixed form** | **Three stacked horizontal bands of equal width and equal height, top to bottom.** Never side by side |
| **Simplify** | **Four items per band, maximum.** No fifth item, on any band |
| **Omit** | **Any platform logo, screenshot or product name. Any upward connector or feedback loop. Any equals sign between CDE and platform.** Any suggestion that acquiring software creates the process. Any claim of live implementation. Any person, role or reporting line |
| **Overclaim risk** | **HIGH** — three tidy bands read as *this is how it runs* |
| **Blocked element visible?** | No blocked route on this visual. **The three status labels are the mandatory element** — without them the diagram asserts a verified operating architecture |
| **Live evidence required?** | No |
| **External imagery** | **No.** A platform screenshot on the bottom band would make configuration the concrete thing and governance the abstraction |
| **Rendered asset status** | **None exists.** No source file, no SVG, no PNG. Production is T4-E-B |

**The fixed form:**

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

**Fixed visible labels.** Band titles exactly as above. Status labels exactly
`CONTROLLED GOVERNANCE`, `PROPOSED GOVERNANCE`, `IMPLEMENTATION UNVERIFIED`.
Connector labels exactly `decides and authorises` and `implemented through`.
Closing message exactly as above — it is `M4-S1-09`, **teaching synthesis**,
consistent with `S1` §6.1 and `S2`'s purpose statement.

**Layout geometry — fixed.** Reference canvas per §3.1.

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

**All three bands are 864 × 92.** Equal width and equal height are mandatory:
unequal bands rank the layers, and the layers are not ranked — they are ordered.

**Panel relationships.** The bands are **layers of decision**, not organisational
tiers and not a sequence in time. Band 2 exists because Band 1 authorised it;
Band 3 exists because Band 2 specified it. **Nothing flows upward.**

**Connector semantics — fixed.**

| Connector | Form | Meaning |
|---|---|---|
| Band 1 → Band 2 | **Solid stem, filled arrowhead, downward only** | Governance **decides and authorises** the workflow |
| Band 2 → Band 3 | **Solid stem, filled arrowhead, downward only** | The workflow is **implemented through** the platform |
| Any upward arrow | **Prohibited — draw none** | Would assert that configuration changes governance |

**Build and reveal sequence — fixed.** Three steps, one per band, top to bottom.
**Each band appears together with its own status label and its connector** — no
frame ever shows a band without its status. If a static export is produced for
the assembly package, **it is the final frame only.**

**Source-label placement.** Right-aligned on the status row inside each band, 14
pt, in the form `CONTROLLED GOVERNANCE · S1 §6.1, §6.9`. **Status and source
travel together** so a producer cannot delete one and keep the other.

**Mandatory on-slide warning.** None beyond the three status labels — **but
`PROPOSED GOVERNANCE` on Band 2 is doing the warning's work** and is not
optional, not abbreviated and not moved to the notes.

**Six mandatory design requirements.**

1. **Governance appears above configuration.** The vertical order is the content.
   **Never three columns** — side by side implies equality between a decision and
   its implementation.
2. **Arrows point downward only.** A return arrow asserts that configuration
   changes governance — the exact failure `S2` §17 rule 1 exists to prevent.
3. **Each band carries its status label, on the slide.** Notes are not a
   substitute. A three-layer diagram without statuses looks like a verified
   operating architecture, which is the module's central overclaim.
4. **No hierarchy of people.** These are layers of decision, not an org chart:
   no names, no roles, no boxes-and-reporting-lines styling.
5. **No named software anywhere**, including on the bottom band. The band names a
   *class* of implementation — folders, permissions, settings, metadata.
6. **Four items per band, and the bands stay equal.** A crowded Band 3 beside a
   sparse Band 1 teaches that configuration is where the substance is.

**Mandatory omissions.** No platform logo · no screenshot · no product name · no
upward or bidirectional connector · no feedback loop · no equals sign between CDE
and platform · no completion tick · no maturity or progress styling · no person
or role · no claim that the workflow is operating.

**Accessibility and projection readability.**

- **Reading order is top to bottom**, in one column. Assistive-technology order
  follows band 1 → connector 1 → band 2 → connector 2 → band 3 → message.
- **Status meaning never depends on colour.** Each status is a word, spelled
  out. If the bands are tinted, the tint may not be the only difference between
  `CONTROLLED` and `PROPOSED`.
- **Band separation ≥ 28 pt** so the three do not read as one block; band border
  contrast ≥ 3:1 against the background.
- **Text contrast ≥ 4.5:1.** Band titles 22 pt, items 16 pt, **status and source
  labels never below 14 pt.**
- **Connector labels are set beside the arrow, not on it**, so they remain
  readable at projection scale and do not sit over a stroke.
- **No meaning carried by an icon**, platform or otherwise.

**Producer failure test.** The visual fails if a viewer can reasonably conclude:

- the platform **is** the CDE;
- configuration **defines** governance;
- the workflow is **verified live**;
- the three layers are **organisational ranks**.

**STOP conditions.** Stop production and return to this specification if:

- any arrow points upward, or any connector becomes bidirectional;
- any platform logo, screenshot or product name is introduced;
- any band loses its status label, or a status is moved to the notes;
- the workflow band is labelled operational, live, implemented or verified;
- the bands acquire unequal size, numbering, or an org-chart appearance;
- the three bands are rearranged side by side.

**Source-file production notes for T4-E-B.** One Markdown source file,
`M04-S01-governance-workflow-platform.md`, carrying: the fixed form above as a
text block; the geometry table; the three status labels as literal strings; the
two connector labels as literal strings; the closing message with its `M4-S1-09`
classification; and the STOP conditions copied verbatim. **This specification
remains authoritative** — the source file is derivative, and a later rendered or
PowerPoint version is derivative of that.

### W2 — The five-property comparison · **specified (T4-E-A)**

| Field | Value |
|---|---|
| **Slide** | 2 — *State, version, revision, status and suitability are different* |
| **Teaching purpose** | Show **five properties answering five different governance questions**, all describing one container **at the same time** |
| **Source basis** | `S1` §6.8, §11.3; `S2` §13; `S12` |
| **Classification** | `CONTROLLED` + `INTERP` — the definitions are controlled; the five questions are the presenter's framing (`M4-S2-07`) |
| **Governance status** | **`CONTROLLED GOVERNANCE`** — all five definitions. **`UNRESOLVED`** — the revision, status and suitability code sets |
| **Implementation status** | Not applicable. **This visual makes no implementation claim, and must not appear to** |
| **Fixed form** | **Five equal cards in a single row.** Not a grid, not columns, not a stack |
| **Simplify** | **One property, one question, one code-status line per card.** Nothing else on a card |
| **Omit** | **Any connector between cards. Any arrow, rule, bar or number. Any example code, filename or field name. Metadata as a sixth card** |
| **Overclaim risk** | **MEDIUM-HIGH** — five cards in a row read as five stages, and a single invented code teaches a standard this project does not have |
| **Blocked element visible?** | **YES — the three absent code sets**, named on their cards |
| **Live evidence required?** | No |
| **External imagery** | **No.** A properties-palette screenshot would assert that software-native fields are the project's schema |
| **Rendered asset status** | **None exists.** Production is T4-E-B |

**Form decision — fixed: five equal cards in one row.** At the §3.1 canvas each
card is 156 pt wide, which carries a four-word property name and a six-word
question at 16 pt without compromise. **A three-plus-two grid is rejected and is
not an alternative:** unequal rows imply that three properties group together and
two are a remainder, and a two-row layout adds a second reading direction to a
visual whose entire purpose is to have none.

**The fixed form:**

```text
   ONE INFORMATION CONTAINER — ALL FIVE AT ONCE

   ┌───────────┐ ┌───────────┐ ┌───────────┐ ┌───────────┐ ┌───────────┐
   │ STATE     │ │ VERSION   │ │ REVISION  │ │ STATUS    │ │SUITABILITY│
   │           │ │           │ │           │ │           │ │           │
   │ Where may │ │ Which     │ │ Which     │ │ What      │ │ For what  │
   │ it be     │ │ stored    │ │ managed   │ │ condition │ │ use is it │
   │ used?     │ │ occurrence│ │ issue is  │ │ is        │ │ suitable? │
   │           │ │ is this?  │ │ this?     │ │ declared? │ │           │
   │           │ │           │ │           │ │           │ │           │
   │ governed  │ │ platform- │ │ no        │ │ no        │ │ no        │
   │ concept   │ │ native;   │ │ convention│ │ code set  │ │ code set  │
   │           │ │ no project│ │ established│ │ established│ │ established│
   │           │ │ convention│ │           │ │           │ │           │
   └───────────┘ └───────────┘ └───────────┘ └───────────┘ └───────────┘

   A new platform version creates none of the others.        — S1 §6.8
```

**Fixed visible labels — the five questions, one per card:**

| Card | Question | Code-set line |
|---|---|---|
| **State** | Where may it be used? | **governed concept** |
| **Version** | Which stored occurrence is this? | **platform-native; no project convention** |
| **Revision** | Which managed issue is this? | **no convention established** |
| **Status** | What condition is declared? | **no code set established** |
| **Suitability** | For what use is it suitable? | **no code set established** |

**Only three cards carry a *not established* line.** State is a governed concept
and Version is platform-native — **neither has an unestablished project code set,
and neither may be labelled as though it did.** Marking all five uniformly would
invent an unresolved matter the sources do not record.

**Layout geometry — fixed.** Reference canvas per §3.1.

| Element | x | y | Size |
|---|---|---|---|
| Caption `ONE INFORMATION CONTAINER — ALL FIVE AT ONCE` | 48 | 128 | 864 wide, 18 pt |
| Card 1 | 48 | 168 | 156 × 208 |
| Card 2 | 225 | 168 | 156 × 208 |
| Card 3 | 402 | 168 | 156 × 208 |
| Card 4 | 579 | 168 | 156 × 208 |
| Card 5 | 756 | 168 | 156 × 208 |
| Controlled-wording line | 48 | 412 | 864 wide |
| Source label `— S1 §6.8`, right-aligned | → 912 | 412 | 14 pt |

**Gutters are 21 pt and identical.** `5 × 156 + 4 × 21 = 864`. **Equal gutters
are mandatory** — a wider gap anywhere groups the cards, and grouping implies an
order the properties do not have.

**Card relationships.** **None is drawn.** All five describe the same container
simultaneously; the relationship is stated in the caption as text, and **nowhere
as geometry**. Cards are identical in width, height, border weight, fill and type
scale. **No card is emphasised**, including State.

**Connector semantics — fixed: there are none.** No arrow, line, rule, bracket,
progression bar, chevron, numbered step or connecting stroke may appear between,
above or beneath the cards. **The caption is set as free text with no rule under
it**, because a full-width rule above a row of cards reads as a spanning
connector. `S1` §6.8 is explicit: *a new platform version creates none of the
others* — any drawn relationship contradicts the governing source.

**Build and reveal sequence — fixed: none. All five cards appear together, in a
single frame.** A staged reveal teaches sequence no matter what the presenter
says over it, and this is the one visual in the module where the reveal itself
would carry the error.

**Source-label placement.** One source label only, right-aligned at the end of
the controlled-wording line: `— S1 §6.8`. **No per-card source labels** — five
small attributions would fill the card space the questions need, and all five
definitions share the same source pair.

**Mandatory on-slide warning.** The three `established` negatives are the
warning. **They stay on the cards** and are not collected into a footnote, where
they would read as a caveat rather than as the project's position.

**Six mandatory design requirements.**

1. **Cards are equal in size and carry no ordering.** A container has all five at
   once — **not a sequence**.
2. **No connector of any kind.** `S1` §6.8: *a new platform version creates none
   of the others*.
3. **The three unestablished code sets are named on their own cards**, and State
   and Version are **not** marked as unresolved.
4. **No example codes, filenames or field names.** One invented code teaches a
   standard this project does not have.
5. **The controlled sentence appears verbatim** — *A new platform version creates
   none of the others* — attributed to `S1` §6.8. It is the slide's argument in
   the source's own words.
6. **Metadata does not appear.** Six properties belong to Slide 12 and `W12`;
   adding a sixth card here duplicates that visual and breaks this one's row
   geometry.

**Mandatory omissions.** No filename · no revision code · no status code · no
suitability code · no metadata field set · no maturity level · no progress
indicator · no approval tick · no traffic-light or red-amber-green treatment · no
folder path · no numbering on the cards · no ISO attribution — **these are this
project's definitions, not ISO definitions.**

**Accessibility and projection readability.**

- **All five cards carry equal semantic weight**, and are marked up as peers —
  not as a list with a first item, and not as a table with a header row.
- **No meaning depends on card colour or fill.** If cards are tinted, all five
  are tinted identically. The three *not established* lines are text.
- **Consistent heading hierarchy**: property name is the card heading, question
  is body, code-set line is a footer at the same level on every card.
- **Separation ≥ 21 pt** between cards so they cannot merge visually into a
  process chain; card border contrast ≥ 3:1.
- **Type: property name 20 pt, question 16 pt, code-set line 14 pt minimum.**
  Questions wrap to a maximum of three lines at 156 pt.
- **Contrast ≥ 4.5:1** for all text.

**Producer failure test.** The visual fails if a viewer can reasonably read it as:

- five **sequential stages**;
- one property **automatically causing** another;
- a **code standard**;
- a **progression toward approval**.

**STOP conditions.** Stop production and return to this specification if:

- an arrow, rule, bracket or connecting line appears anywhere in the card row;
- a card becomes visually dominant, or the cards become unequal;
- an example code, filename or field name is added to any card;
- a maturity, progress or completion grammar appears;
- **metadata is added as a sixth card**;
- State or Version acquires a *not established* label;
- the row is rebuilt as a three-plus-two grid.

**Source-file production notes for T4-E-B.** One Markdown source file,
`M04-S02-five-properties.md`, carrying: the fixed form; the five-question table
with its code-set column exactly as above; the geometry table; the controlled
sentence with its `S1` §6.8 attribution; the no-connector rule stated as a
prohibition rather than a preference; and the STOP conditions verbatim. **The
single-row form is a recorded decision, not a default** — the source file must
carry the rejection of the three-plus-two grid with it, or a later producer will
re-open a question this increment closed.

### W3 — The Harrismith four-state model · **specified (T4-E-A)**

| Field | Value |
|---|---|
| **Slide** | 3 — *The Harrismith information-state model* |
| **Teaching purpose** | Show **four governed state concepts, four distinct purposes — and one route that cannot presently proceed** |
| **Source basis** | `S1` §6.3, §6.7, §7.5, §9.4; `S2` §1, §3, §13; `S3` §2, §3, §3.1; `S4` §7, §9; **`CGD-C01`, `CGD-C03`, `CGD-C06`** |
| **Classification** | `CONTROLLED` + `SUPPORTING` + `DECISION-RECORD` |
| **Governance status** | **Per panel** — two `CONTROLLED GOVERNANCE`, one **`BLOCKED`**, one **`UNRESOLVED`** |
| **Implementation status** | **Per panel** — two `IMPLEMENTATION UNVERIFIED`, one **Not reached**, one **Not addressed** |
| **Fixed form** | **Four concept panels in one horizontal row**, equal size, with three connectors in the gutters and their labels beneath |
| **Simplify** | **Five lines per panel** — name, purpose, who may rely, governance status, implementation status |
| **Omit** | **Any complete green lifecycle. Any completion tick. `04 Archive`. Any folder icon. Any four-area row beneath the four panels. Delivery, receipt or acceptance as states** |
| **Overclaim risk** | **HIGHEST IN THE MODULE** — a four-state chain reads as an operating system |
| **Blocked element visible?** | **YES — mandatory.** The `T4` break, the empty publication authority, and an unreachable third connector |
| **Live evidence required?** | No |
| **External imagery** | **No.** Any platform image beside this model asserts the live implementation the warning denies |
| **Rendered asset status** | **None exists.** Production is T4-E-B |

**Format decision: a native layout, not Mermaid.** Mermaid renders a chain, and a
chain implies traversal. **The deliberate break must be a drawn decision, not a
line style a renderer may normalise.**

**The fixed form:**

```text
  ┌─ WIP ─────────┐  ┌─ SHARED ──────┐  ┌─ PUBLISHED /  ┐  ┌─ RECORD /     ┐
  │               │  │               │  │   AUTHORISED  │  │   RETAINED    │
  │ authoring,    │  │ controlled use│  │ authorised use│  │ preservation  │
  │ iteration,    │  │ beyond the    │  │ or delivery,  │  │ and           │
  │ internal      │  │ originating   │  │ for a defined │  │ traceability  │
  │ checking      │──│ team, for a   │╌╌│ purpose       │  │               │
  │               │  │ stated purpose│  │               │  │               │
  │ May rely:     │  │ May rely:     │  │ May rely:     │  │ May rely:     │
  │ the           │  │ receiving     │  │ whoever the   │  │ anyone needing│
  │ originating   │  │ teams, for the│  │ authorised    │  │ traceability  │
  │ task team     │  │ stated purpose│  │ purpose names │  │               │
  │ only          │  │               │  │               │  │               │
  │               │  │               │  │               │  │               │
  │ CONTROLLED    │  │ CONTROLLED    │  │ BLOCKED       │  │ UNRESOLVED    │
  │ GOVERNANCE    │  │ GOVERNANCE    │  │               │  │               │
  │ IMPLEMENTATION│  │ IMPLEMENTATION│  │ Not reached   │  │ Not addressed │
  │ UNVERIFIED    │  │ UNVERIFIED    │  │               │  │               │
  └───────────────┘  └───────────────┘  └───────────────┘  └───────────────┘
          │                   │                  │
      ────┴────           ╌╌╌╌✕╌╌╌╌          ╌╌╌╌○ (open)
                                                 no arrowhead
   T1                   T4  BLOCKED           Retention approach:
   Task-Team Lead       Publication-          unresolved
   authority            authorising           Not reachable while
   established          function: TBD         T4 is blocked
                        Information
                        remains Shared

   Conceptual state model — not proof of live platform implementation

   Areas and information states do not map one to one.
   0. Common Files — an area mapped to no state.
   Record / Retained — a state with no approved area.
```

**Fixed visible labels.** Panel titles `WIP`, `SHARED`, `PUBLISHED / AUTHORISED`,
`RECORD / RETAINED`. Status labels exactly as registered in
[`source-map.md`](source-map.md) §5.1: `CONTROLLED GOVERNANCE`, `BLOCKED`,
`UNRESOLVED`, `IMPLEMENTATION UNVERIFIED`, `Not reached`, `Not addressed`. **No
other status wording is permitted**, and *unverified* may not be substituted for
*Not reached* or *Not addressed* — they mean different things and the register
distinguishes them.

**On the fourth state's label.** Four label forms exist across the controlled
sources; **the majority teaching form `Record / Retained` is used**, and the
governing `S1` §6.3 table's lower-case *retained* is recorded in
[`source-inventory.md`](source-inventory.md) §6. **Neither is presented as *the*
correct label**, and the visual does not adjudicate the variance.

**Layout geometry — fixed.** Reference canvas per §3.1.

| Element | x | y | Size |
|---|---|---|---|
| Panel 1 — WIP | 40 | 120 | 193 × 250 |
| Panel 2 — SHARED | 269 | 120 | 193 × 250 |
| Panel 3 — PUBLISHED / AUTHORISED | 498 | 120 | 193 × 250 |
| Panel 4 — RECORD / RETAINED | 727 | 120 | 193 × 250 |
| Connector lane — all three | gutter centres 251, 480, 709 | **245** | 36 wide |
| Label block 1 — `T1` | 156 | 378 | 190 × 52 |
| Label block 2 — `T4 BLOCKED` | 385 | 378 | 190 × 76 |
| Label block 3 — retention | 614 | 378 | 190 × 76 |
| Mandatory warning, centred | 40 | 462 | 880 wide |
| Area-mismatch annotation, left block | 40 | 496 | 560 × 32 |

**Gutters are 36 pt and identical; panels are 193 × 250 and identical.** Equal
panels are mandatory: a large WIP panel beside a small Record panel implies the
states differ in importance rather than in purpose.

**How the blocked connector avoids crossing a panel.** **All three connectors sit
in a single horizontal lane at y 245 — panel mid-height — and occupy only the 36
pt gutters.** No connector enters, overlaps or passes behind a panel, and no
connector is routed above or below the row. The `T4` break mark sits at the
centre of gutter 2, in clear space, **not against the Shared panel edge** where it
would read as a fault in Shared rather than a halt between two states.

**Connector semantics — fixed.**

| Connector | Line | Arrowhead | Label block | Meaning |
|---|---|---|---|---|
| **WIP → Shared** | **Solid** | **Filled, at the Shared edge** | `T1` · `Task-Team Lead authority established` | **Supported.** The only supported state progression on this visual — and only because the authorising function is established (`S1` §9.4) |
| **Shared ⇢ Published / Authorised** | **Broken, with a visible break mark at the gutter centre** | **Filled, but the stroke is interrupted before it** | `T4 BLOCKED` · `Publication-authorising function: TBD` · `Information remains Shared` | **Halted.** A route that exists in governance and cannot presently be traversed |
| **Published ⇢ Record / Retained** | **Broken, terminating in an open stub** | **None — no arrowhead at all** | `Retention approach: unresolved` · `Not reachable while T4 is blocked` | **Unreachable.** Not merely halted — it cannot be entered, because its origin state has not been reached |

**The second and third connectors are drawn differently, and the difference is
the teaching.** `T4` is a *blocked* route with a named unresolved authority; the
third is *unreachable* and additionally has no resolved method. **Drawing them
identically implies both are waiting on the same thing.** Drawing the third as
merely delayed — a faded arrow, a dotted line reading as *in progress*, a
"coming soon" treatment — asserts a retention approach that does not exist.

**Build and reveal sequence — fixed: none. The whole visual appears in one
frame,** including all three connectors, all eight status labels, the warning and
the annotation. **A staged reveal is prohibited**: any frame showing four panels
and a solid or absent set of connectors is a frame that claims an operating
four-state lifecycle, and a presenter cannot un-show it.

**Source-label placement.** Panel sources are **not** printed on the panels —
five lines per panel is already the density limit. **One source line, bottom
right of the annotation band**, 14 pt: `S1 §6.3 · S2 §1, §3 · S3 §3 · S4 §7`.
**The status labels stay on the panels**, because they are content, not
attribution.

**Mandatory on-slide warning — exact wording, no substitution:**

> ### `Conceptual state model — not proof of live platform implementation`

**It belongs on the visual**, centred beneath the connector labels, at body size
— **not in the footer, not in the notes, and not shrunk to a caption.**

**Area-versus-state mismatch — fixed treatment.** A **compact two-line
annotation**, left-aligned, in the band beneath the warning:

```text
   Areas and information states do not map one to one.
   0. Common Files — an area mapped to no state.
   Record / Retained — a state with no approved area.
```

**It is never drawn as a parallel four-folder row.** Four areas aligned beneath
four states is the exact false correspondence `CGD-C01` and `CGD-C03` exist to
prevent, and a producer's instinct is to build it because it looks tidy. **The
annotation is deliberately not aligned to any panel**: it is a left-aligned text
block spanning less than two panel widths, so no reader can pair a line with a
column.

**Nine mandatory design requirements.**

1. **`WIP → Shared` is solid** — and only because the authorising function is
   established. Drawing every connector broken reads as *non-functional* rather
   than *deliberately halted*.
2. **`Shared ⇢ Published` is broken or visibly halted.** Never solid, never a
   faded arrow that reads as *in progress*.
3. **`Published ⇢ Record / Retained` is unreachable, and drawn so** — open stub,
   **no arrowhead**, and distinct from the `T4` break.
4. **Publication authority appears on the visual and is empty** — `Publication-
   authorising function: TBD`. Omitting it implies no authority is required.
5. **`Information remains Shared` appears** on the `T4` label block. It is the
   consequence, and without it a blocked route reads as information in limbo.
6. **Record / Retained is not drawn as a folder, and `04 Archive` appears
   nowhere** — not as a state, folder, example, grey placeholder, future option
   or destination label.
7. **The mandatory on-slide warning appears, verbatim.**
8. **All eight status labels appear** — four governance, four implementation —
   in the registered wording.
9. **Delivery, receipt and acceptance appear nowhere.** They are events, actions
   and statuses, **not states** (`S2` §3, §13), and a fifth panel or an extra
   connector for any of them breaks the model.

**Mandatory omissions.** No `04 Archive` in any form · no folder icon as a state
panel · no four-area row beneath the four panels · no completion tick · no green
lifecycle · no red failure styling on the blocked route · no progress bar · no
date on any unresolved item · no named publication authority · no fifth state ·
no delivery, receipt or acceptance object · no platform image.

**Accessibility and projection readability.**

- **Connector meaning is carried in text as well as line style.** `T1` says
  `authority established`; `T4` says `BLOCKED`; the third says `Not reachable`.
  **A viewer who cannot resolve a dashed stroke still reads the state of every
  route.**
- **No reliance on red or green.** The block is not red and the supported route
  is not green — the block is **deliberate governance, not a fault**, and red
  styling teaches that something has gone wrong.
- **The model is fully legible in monochrome**: solid versus broken stroke,
  arrowhead versus open stub, plus the text labels.
- **Screen-reader and notes description for the broken route**, to be carried in
  the source file: *"From Shared to Published / Authorised: a broken connector.
  Transition T4 is blocked; the publication-authorising function is TBD;
  information remains Shared. From Published / Authorised to Record / Retained:
  an open stub with no arrowhead; not reachable."*
- **Reading order** — panel 1, its outgoing connector and label, panel 2, its
  connector and label, panel 3, its connector and label, panel 4, then the
  warning, then the annotation.
- **Type: panel title 20 pt, purpose and reliance 14 pt, status labels 14 pt
  minimum, connector labels 14 pt, warning 18 pt.** **Status labels may not be
  shrunk below 14 pt to win space** — if the panel will not hold five lines at
  that size, shorten the purpose line, never the status.
- **Contrast ≥ 4.5:1** for text; **≥ 3:1** for panel borders and connector
  strokes.

**Producer failure test.** The visual fails if it implies:

- **automatic progression** through all four states;
- a **working publication transition**;
- a **four-state / four-folder correspondence**;
- **Record / Retained as a folder**;
- **live platform implementation**;
- **delivery or acceptance as a state**.

**STOP conditions.** Stop production and return to this specification if:

- `Shared → Published` becomes solid, or its break mark is removed;
- the third connector gains an arrowhead, or is styled as merely delayed;
- the publication-authority field disappears or is filled;
- **`04 Archive` is added anywhere**;
- four folders or four areas are aligned beneath the four states;
- a completion tick, green lifecycle or red failure styling appears;
- the mandatory warning is removed, moved to the footer or reduced to a caption;
- Record / Retained is presented as reached, or drawn as a folder;
- any status label is dropped, reworded or shrunk below 14 pt;
- a fifth panel appears for delivery, receipt or acceptance.

**Source-file production notes for T4-E-B.** One Markdown source file,
`M04-S03-four-state-model.md`, carrying: the fixed form; the geometry table; the
connector-semantics table **in full, because the three connectors differ and the
differences are the content**; the eight registered status labels as literal
strings; the mandatory warning as a literal string; the area-mismatch annotation
as a literal string; the screen-reader description of the broken route; and the
STOP conditions verbatim. **This is the module's highest-risk visual** — the
source file should carry the producer failure test at the top, not the bottom.

**Design note.** Every instinct a competent producer has will damage this visual.
Tidiness wants a four-to-four area alignment; completeness wants the third
connector finished; helpfulness wants a candidate publication authority; visual
hygiene wants the warning moved to the footer where it will not interrupt the
composition. **Each of those is the module's central error, committed in good
taste.** The panels are equal, the connectors are unequal, and the untidiness is
the argument.

### W4 — The WIP task-team boundary · **specified (T4-B)**

| Field | Value |
|---|---|
| **Slide** | 4 |
| **Teaching purpose** | Show WIP as bounded by the task team, and that **visibility is not permission to rely** |
| **Source basis** | `S1` §6.4, §7.5; `S2` §1; `S3` §3.2; `S4` §7 |
| **Classification** | `CONTROLLED` + `DECISION-RECORD` |
| **Governance status** | **Controlled** |
| **Implementation status** | **`IMPLEMENTATION UNVERIFIED`** — one qualified container observation |
| **Simplify** | One boundary, three functions inside, several versions inside, one observer outside |
| **Omit** | **Any named person. Any team-space screenshot. Any automatic arrow to Shared.** Any suggestion the boundary is a permission setting. Any green approval tick |
| **Overclaim risk** | **MEDIUM-HIGH** — a boundary with a gate on it invites the eye to follow the route out |
| **Blocked element visible?** | No — but **no route out is drawn** |
| **Live evidence required?** | No |
| **External imagery** | No |

**The fixed form:**

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

**Six mandatory design requirements.**

1. **No automatic arrow to Shared.** The Task-Team Lead gate may be **visible on
   the boundary**, but **no connector leaves it** — transition mechanics are
   Slides 8–11.
2. **The observer outside can see and may not rely.** Both halves are drawn — a
   sight line in, and a refusal marker on reliance.
3. **Originating responsibility is visible inside the boundary**, and stays
   there.
4. **Multiple versions are shown inside**, annotated as **working steps, not
   project exchanges**.
5. **No green approval tick, anywhere.**
6. **No claim that every task team has a verified live area.** If implementation
   is annotated at all: *"`ARC-01` — one qualified observation; five containers
   not observed at the inspected level"*.

**Design note.** Draw the boundary as a **responsibility boundary, not a
permission boundary**. `S1` §6.4: *"A team space is a platform construct…
**Membership confers no authority**."* A boundary drawn as a padlock teaches the
opposite.

### W5 — Shared: permitted use for a defined purpose · **specified (T4-B)**

| Field | Value |
|---|---|
| **Slide** | 5 |
| **Teaching purpose** | Show that Shared carries a **stated purpose**, that reliance is bounded by it, and that **responsibility stays with the originator** |
| **Source basis** | `S1` §6.3, §6.5, §6.6, §7.7; `S2` §1, §3; `S3` §3.3; `S4` §7 |
| **Classification** | `CONTROLLED` + `SUPPORTING` + `DECISION-RECORD` |
| **Governance status** | **Controlled** — `T1`'s authorising function is established |
| **Implementation status** | **`IMPLEMENTATION UNVERIFIED`** — *"only Architecture currently demonstrable as a Shared input"* |
| **Simplify** | One central container, **two or three purpose call-outs**, one retained-responsibility line |
| **Omit** | **Any approval stamp. Any publication symbol. Any client-acceptance symbol. Any green compliance treatment.** Any platform screenshot |
| **Overclaim risk** | **HIGH** — Shared is the state most often read as *signed off* |
| **Blocked element visible?** | No |
| **Live evidence required?** | No |
| **External imagery** | No |

**The fixed form:**

```text
                    ┌──────────────────────┐
   originating      │   SHARED CONTAINER   │      purpose call-outs:
   task team  ══════│                      │────  · coordination
   RESPONSIBILITY   │  stated purpose:     │────  · controlled review
   RETAINED         │  ……………………            │────  · reference by another
                    └──────────────────────┘         task team

   ── ON-SLIDE WARNING:
      Shared means authorised for A DEFINED USE.
      It does not mean approved for EVERY use.
```

**Six mandatory design requirements.**

1. **Purpose labels are visible**, and each permitted use is attached to one.
2. **The responsibility line stays attached to the originator** — drawn as a
   persistent connection, not a handover arrow.
3. **A visible warning that Shared is not Published.**
4. **No approval stamp, publication symbol, acceptance symbol or tick.**
5. **No green.** Green reads as *cleared*, which is the misreading the slide
   exists to refuse.
6. **`02. Shared` may be referenced, with `S3` §3.3 attached** — *"placement
   alone does not evidence that checking or authorisation occurred"*.

**Design note.** The purpose call-outs must look like **conditions**, not
**benefits**. A fan of arrows radiating outward reads as distribution; the same
arrows terminating in labelled purposes read as bounded permission.

### W6 — The publication-authority gate · **specified (T4-B)**

| Field | Value |
|---|---|
| **Slide** | 6 |
| **Teaching purpose** | Show publication as a **separate decision by a separate authority** — and that the authority is **required and unassigned** |
| **Source basis** | `S1` §6.7, §9.7; `S2` §1, §3.1, §3.2, §11; `S3` §3.4; `S4` §9; `S6` `D4` |
| **Classification** | `CONTROLLED` + `SUPPORTING` + `DECISION-RECORD` |
| **Governance status** | **`BLOCKED`** — the authority is **UNRESOLVED** |
| **Implementation status** | **Not reached** |
| **Simplify** | One Shared input, one gate, **one empty authority position**, one blocked output |
| **Omit** | **Any named or implied authority holder. Any solid `Shared → Published` arrow. Any checkmark.** Any suggestion an administrator may substitute. Any red failure styling |
| **Overclaim risk** | **HIGH in both directions** — an empty gate invites the audience to fill it; a red gate reads as a defect |
| **Blocked element visible?** | **YES — the authority position is drawn empty, and the output is broken** |
| **Live evidence required?** | No |
| **External imagery** | No |

**The fixed form:**

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

**Seven mandatory design requirements.**

1. **No solid `Shared → Published` connector.** Broken or visibly halted —
   never solid, never a faded arrow reading as *in progress*.
2. **The authority position appears and is empty.** **Omitting it would imply no
   authority is required**, which is the opposite of true.
3. **Three labels, all present:** **`T4 blocked`** · **`No available authorising
   function`** · **`Information remains Shared`**.
4. **No name in the authority position** — and **no substitution**. `S1` §9.7
   names the BIM Manager, BIM Coordinator, CDE Administrator and Architect as
   **not** holding it automatically.
5. **No checkmark, and no red failure styling.** The block is **deliberate
   governance**, not a technical fault.
6. **`TRN-E03` is not drawn as the transition.** It may be named in a single
   annotation as *a later delivery event that depends on `T4`* — **the event
   logic is Slides 8–11**.
7. **`S3` §3.4 appears on the slide** — *"Putting a file in `03. Published` does
   not publish it."*

**Design note — the hardest instruction on this visual.** An empty box looks
unfinished, and a designer will want to fill it, shade it, or remove it. **All
three are wrong.** Filled invents an authority; removed implies none is needed;
shaded reads as failure. **A plain, labelled, empty position is the only accurate
rendering.**

### W7 — Retention obligation versus method · **specified (T4-B)**

| Field | Value |
|---|---|
| **Slide** | 7 |
| **Teaching purpose** | Show retention as an **established obligation** with an **undecided method** |
| **Source basis** | `S1` §6.3, §7.10, §9.9, §12.10; `S2` §1, §19; **`S3` §3.1, §3.5, `CGD-C06`** |
| **Classification** | `CONTROLLED` + `SUPPORTING` + `DECISION-RECORD` |
| **Governance status** | **Controlled** — the obligation. **`UNRESOLVED`** — the method |
| **Implementation status** | **Not addressed in any validation record** |
| **Simplify** | **Two panels, side by side** — obligation established, method unresolved |
| **Omit** | **`04 Archive` in any form. Any folder icon. Any placeholder folder name. Any destination arrow. Any completed storage icon. Any green check. Any invented retention period. Any invented named holder** |
| **Overclaim risk** | **MEDIUM-HIGH** — the audience expects a folder and will read one in |
| **Blocked element visible?** | **YES — the method panel is visibly empty** |
| **Live evidence required?** | No |
| **External imagery** | No |

**The fixed form:**

```text
  ┌── OBLIGATION — ESTABLISHED ──┐   ┌── METHOD — UNRESOLVED ──────┐
  │                              │   │                             │
  │  · preserve required         │   │  location:            TBD   │
  │    project information       │   │  retention period:    TBD   │
  │  · protect against           │   │  responsible holder:  TBD   │
  │    uncontrolled change       │   │  implementation                │
  │    or loss                   │   │    evidence:     unavailable   │
  │  · maintain traceability     │   │                             │
  │  · retain required evidence  │   │                             │
  │                              │   │                             │
  │  superseded ≠ deleted        │   │      ← stays empty →        │
  └──────────────────────────────┘   └─────────────────────────────┘

  ── ON-SLIDE STATEMENT:
     Record / Retained is a state or obligation.
     It is NOT automatically a folder.

  ── STATE-VERSUS-AREA MISMATCH:
     0. Common Files   — an area mapped to NO state
     Record / Retained — a state mapped to NO approved area
```

**Seven mandatory design requirements.**

1. **`04 Archive` appears nowhere** — not as a label, an example, a grey
   placeholder, a future suggestion or a visual destination.
2. **The method panel appears and stays empty.** **An omitted method panel reads
   as complete**; an empty one shows the open decision.
3. **No destination arrow** from the obligation panel to anywhere. There is
   nowhere to point.
4. **No completed storage icon, no green check, no archive imagery.**
5. **No invented retention period** — none exists in any controlled source.
6. **No invented named holder** — **no records manager or archive administrator
   exists in the Harrismith set**.
7. **The state-versus-area mismatch is shown**, both directions. **Do not force a
   four-state-to-four-area alignment.**

**Design note.** The two panels are the **same size**. A large obligation panel
beside a small method panel implies the method is a detail. It is an undecided
governance matter, and the panels should look equally consequential.

### W8 — File movement versus authorised transition · **specified (T4-C)**

| Field | Value |
|---|---|
| **Slide** | 8 |
| **Teaching purpose** | Show the two side by side, and that **one does not produce the other** |
| **Source basis** | **`CGD-C03`**; `S2` §2, §3, §14, §17; `S1` §6.9, §12.1; `S4` §9 |
| **Classification** | `DECISION-RECORD` + `SUPPORTING` + `CONTROLLED` + `INTERP` |
| **Governance status** | **Controlled** — `CGD-C03` is an active condition |
| **Implementation status** | — |
| **Simplify** | **Two panels.** Left: what a user can technically do. Right: what a transition requires |
| **Omit** | **Any connector between the panels. Any equals sign. Any causal arrow.** Any permission screenshot, product logo or green completion treatment |
| **Overclaim risk** | **HIGH** — a two-panel layout invites the eye to pair them, and pairing them asserts that the left produces the right |
| **Blocked element visible?** | No |
| **Live evidence required?** | No |
| **External imagery** | No |

**The fixed content:**

```text
  ┌── TECHNICAL ACTION ─────────┐      ┌── GOVERNED TRANSITION ────────────┐
  │                             │      │                                   │
  │  upload                     │      │  required input                   │
  │  move                       │      │    → checks                       │
  │  copy                       │      │    → gate conditions              │
  │  rename                     │      │    → authorised decision          │
  │  change permissions         │      │    → recorded evidence            │
  │  create a new version       │      │    → changed permitted use        │
  │                             │      │                                   │
  │  establishes NONE of:       │      │  "Each transition requires the    │
  │  checks · evidence ·        │      │   applicable governed checks,     │
  │  authority · permitted use ·│      │   authorisation and evidence"     │
  │  suitability · publication ·│      │                    — CGD-C03      │
  │  delivery · receipt ·       │      │                                   │
  │  acceptance                 │      │                                   │
  └─────────────────────────────┘      └───────────────────────────────────┘

              ▲ NO CONNECTOR. The left does not produce the right.
```

**Five mandatory design requirements.**

1. **No connector, arrow or equals sign between the panels.** A connector asserts
   causation — the exact claim `CGD-C03` refuses.
2. **The left panel lists what it establishes: nothing.** The negative list is
   the panel's content, not a footnote.
3. **The right panel is a labelled sequence, not populated.** Six steps, no
   fields — `W10` unpacks one.
4. **The six-step anatomy carries a `Teaching structure` label**, because the
   form is the presenter's arrangement of `S2` §2 and §3.
5. **No permission screenshot, folder tree, product logo or green treatment.**

**Design note.** Draw the panels **the same size**. A large governance panel
beside a small technical one turns an accurate distinction into a lecture; equal
panels say *these are two different things*, which is the point.

### W9 — The eight controlled steps, classified · **specified (T4-C)**

| Field | Value |
|---|---|
| **Slide** | 9 |
| **Teaching purpose** | Show all eight steps **grouped by kind** — and that **only `T1` and `T4` change information state** |
| **Source basis** | **`S2` §3.1, §3.2**; `S2` §2, §3; `S1` §9.4, §9.7, §9.8; `S4` §8 |
| **Classification** | `SUPPORTING` throughout, with `CONTROLLED` for `T1`'s authority |
| **Governance status** | **Mixed** — `T1` controlled · `T4` **blocked** · `T7` **unresolved** · the rest proposed |
| **Implementation status** | **`IMPLEMENTATION UNVERIFIED`** — *"no complete traceable cycle"* |
| **Simplify** | **A table grouped by kind.** Five groups, eight rows, four or five columns |
| **Omit** | **Any flowchart. Any arrow chain. Any left-to-right sequence. Any numbering that implies order. Any compliance colour. Any maturity styling** |
| **Overclaim risk** | **HIGHEST, jointly with `W3`** — eight identifiers in a row read as an eight-step state machine |
| **Blocked element visible?** | **YES** — `T4` blocked, `T7` unresolved |
| **Live evidence required?** | No |
| **External imagery** | No |

**Format decision — absolute: a table, and never Mermaid.**

A rendering of `T1 → T2 → T3 → T4 → T5 → T6 → T7 → T8` would assert **four
things the sources deny**:

| It would assert | The source says |
|---|---|
| One mandatory order | They are identifiers for **different controlled acts** |
| Eight sequential transitions | **Only `T1` and `T4` are information-state transitions** |
| Automatic progression | Every step has *"its own trigger, its own criteria and its own responsible function"* |
| A complete operating route | **`T4` is blocked; no complete cycle has been demonstrated** |

**The fixed grouping:**

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

**Six mandatory design requirements.**

1. **No Mermaid. No flowchart. No arrow chain.** A grouped table is the only
   permitted form.
2. **The headline appears prominently** — *Only `T1` and `T4` change information
   state.*
3. **`T1` and `T4` are visually distinguished — neutrally.** Weight or a rule,
   **not colour**, and never green-for-`T1` / red-for-`T4`.
4. **`T4` is marked blocked and `T7` unresolved**, in the same table.
5. **The six non-transitions show their state as unchanged**, in their own
   column. That column is the slide's teaching.
6. **Implementation status is visible** — *no complete traceable cycle
   demonstrated*.

**Design note.** Resist numbering the groups. `T1`–`T8` already look like a
sequence; adding *group 1, group 2* compounds it. **Label the groups by kind, and
let the identifiers sit inside them.**

### W10 — The `T1` gate model · **specified (T4-C)**

| Field | Value |
|---|---|
| **Slide** | 10 |
| **Teaching purpose** | Unpack **one** controlled transition — trigger, checks, authority, evidence, permitted use |
| **Source basis** | **`S2` §3.1–§3.3, §9**; `S1` §7.7, §9.4, §9.11; `S4` §7, §8 |
| **Classification** | `SUPPORTING` + `CONTROLLED` + `DECISION-RECORD` |
| **Governance status** | **`CONTROLLED GOVERNANCE`** — the only transition with an established authority |
| **Implementation status** | **`IMPLEMENTATION UNVERIFIED`** — no complete cycle demonstrated |
| **Simplify** | **One transition, five stages, four side labels.** Nothing else |
| **Omit** | **Any publication path. Any `T4` content beyond one sentence. Any green approval tick. Any claim of complete live execution.** The full readiness list — three or four conditions maximum |
| **Overclaim risk** | **MEDIUM-HIGH** — a fully populated example reads as a running procedure |
| **Blocked element visible?** | The **`T4` contrast** is worth one line |
| **Live evidence required?** | No |
| **External imagery** | No |

**The fixed form:**

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

**Six mandatory design requirements.**

1. **The evidence field is visible and is not abbreviated away.** It is the field
   that distinguishes a governed transition from a file move. **If space is
   short, cut a gate condition — never the evidence.**
2. **Four side labels, distinctly placed**: Author · Checker · CDE Administration
   · receiving user. **CDE Administration sits beside the chain, not in it.**
3. **No publication path on this slide.** `T4` gets **one sentence** — *"and the
   next slide is where this breaks down"*.
4. **No green approval tick**, and no completion marker at the Shared end.
5. **The failure route is shown** — back to WIP, **no partial progression**.
6. **A visible governance-versus-implementation line**, because `T1` is
   controlled and unverified at the same time.

**Design note.** Show **three or four** gate conditions, not all eight. The
readiness list is a judgement set, not a checklist, and eight boxes make it look
like one — `S1` §7.7: *"no numeric quality thresholds are set."*

### W11 — `T4` and `TRN-E03`, two blocked objects · **specified (T4-C)**

| Field | Value |
|---|---|
| **Slide** | 11 |
| **Teaching purpose** | Show **two separate blocked objects** — a state transition and a delivery event — and that resolving one would not resolve the other |
| **Source basis** | **`S2` §3.1–§3.3, §11, §19**; **`S5` §5, §5.1**; `S1` §9.4, §9.7, §9.8; `S4` §9 |
| **Classification** | `SUPPORTING` + `CONTROLLED` + `DECISION-RECORD` |
| **Governance status** | **`BLOCKED`** — both. Two authorities **UNRESOLVED** |
| **Implementation status** | **Not reached.** *"No governed publication / exchange authority evidence was established"* |
| **Simplify** | **Two panels, side by side.** `T4` left, `TRN-E03` right |
| **Omit** | **Any single merged object. Any solid arrow. Any invented authority, recipient, format or deliverable. Any completion tick. Any red failure styling.** Any suggestion an administrator may proceed |
| **Overclaim risk** | **HIGH in both directions** — merged, it hides four dependencies; styled red, it reads as a defect |
| **Blocked element visible?** | **YES — the visual is two blocks** |
| **Live evidence required?** | No |
| **External imagery** | No |

**The fixed form:**

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

**Eight mandatory design requirements.**

1. **Two panels. Never a single merged object.** Merging them is the error the
   slide exists to prevent, and a merged diagram commits it silently.
2. **No solid arrow anywhere.** `Shared ⇢ Published` is broken or visibly halted.
3. **The publication-authority position appears and is empty.** Omitting it
   implies no authority is required.
4. **No invented authority, recipient, format or deliverable** — the five
   blocking matters are listed **as unresolved**, not filled.
5. **No completion tick, and no red failure styling.** The block is **deliberate
   governance**.
6. **`Information remains Shared` appears on Panel 1.**
7. **The one-versus-five contrast appears**, and is the slide's argument.
8. **No suggestion that an administrator may proceed** — `S1` §9.7 names the CDE
   Administrator among those who do **not** hold the authority.

**Design note.** Give the two panels **equal weight**. A large `T4` panel beside a
small `TRN-E03` panel implies the delivery event is a detail of the transition.
It is a separate object with four additional unresolved matters, and the visual
should say so.

### W12 — The property stack and the four unestablished standards · **specified (T4-D)**

| Field | Value |
|---|---|
| **Slide** | 12 |
| **Teaching purpose** | Show the six properties as **six different control questions**, and that **four of the standards behind them do not exist** |
| **Source basis** | **`S1` §6.8, §11.3, §11.4**; `S2` §13; `S12`; **`CGD-C01`, `CGD-C03`** |
| **Classification** | `CONTROLLED` + `INTERP` |
| **Governance status** | **`CONTROLLED GOVERNANCE`** — what each property must support. **`UNRESOLVED`** — every code set and the schema |
| **Implementation status** | **No standard established.** All four `standards/` directories hold only `.gitkeep` |
| **Simplify** | **Two zones.** Left: six property rows, each with its control question. Right: four boxes, all **empty** |
| **Omit** | **Any coding standard. Any example code, filename, revision, suitability or status value. Any metadata field set. Any classification system.** Module 5's suitability-in-delivery-planning |
| **Overclaim risk** | **HIGH** — a populated property stack teaches four standards that do not exist |
| **Blocked element visible?** | **YES — four empty boxes, shown and unfilled** |
| **Live evidence required?** | No |
| **External imagery** | No |

**The fixed form:**

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

**Nine mandatory design requirements.**

1. **Six properties, six questions, one row each.** The question is the point;
   a bare property list teaches nothing.
2. **All four boxes appear, and all four are empty.** Omitting them implies no
   decision is needed; filling any one invents a standard.
3. **`not established` is the label on each.** Not *TBD in progress*, not *to
   follow*, not a date.
4. **No example code of any kind** — no ISO 19650 filename, no South African
   filename, no revision, suitability or status value, no metadata field set, no
   model-container name, **no fire-station example**.
5. **A conceptual placeholder such as `[identifier]` is permitted only if
   visibly labelled illustrative.** **Preferring none at all is the safer
   choice.**
6. **No classification system appears** — Uniclass, OmniClass and MasterFormat
   are **unadopted** (`S1` §11.4) and naming one implies otherwise.
7. **No software field list.** *"Software-native metadata is not the project
   standard"*; a screenshot of a properties palette asserts the opposite.
8. **The code-versus-authority line appears**, or the visual becomes a form
   design exercise.
9. **No tick, no red, no warning triangle** on the empty boxes. They are an
   undecided decision, not a defect.

**Design note.** Resist making the four boxes small. They are the argument of the
slide, and a producer's instinct will be to shrink an empty element and grow a
populated one — which inverts the teaching. **Give the empty zone at least equal
area to the property list.**

### W13 — Governance, then configuration · **specified (T4-D)**

| Field | Value |
|---|---|
| **Slide** | 13 |
| **Teaching purpose** | Show the **direction of authority** — decision, process, configuration, evidence — and that the reverse does not hold |
| **Source basis** | **`S1` §5.9, §6.9, §12.1, §12.6, §12.8, §12.9**; `S2` §6, §14, §17; **`CGD-C07`, `CGD-C08`** |
| **Classification** | `CONTROLLED` + `SUPPORTING` + `DECISION-RECORD` |
| **Governance status** | **`CONTROLLED GOVERNANCE`** |
| **Implementation status** | **`IMPLEMENTATION UNVERIFIED`** — `S2` §6 records alignment as a four-layer question |
| **Simplify** | **One forward chain, one visibly refused reverse arrow, one may/does-not table** |
| **Omit** | **Any permissions screenshot or table. Any named administrator. Any org-chart shape.** Module 6's verification method |
| **Overclaim risk** | **MEDIUM-HIGH** — a forward-only chain can be read in either direction, and a permissions image makes configuration the concrete thing |
| **Blocked element visible?** | **YES — the refused reverse arrow, and `Holder: TBD`** |
| **Live evidence required?** | No |
| **External imagery** | **No.** A permissions screenshot would prove the opposite point |

**The fixed form:**

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

**Eight mandatory design requirements.**

1. **The reverse arrow appears and is visibly refused.** A forward-only chain is
   a chain someone can read backwards; the refusal must be on the slide.
2. **Never Mermaid.** A renderer draws the refused reverse edge as a real edge,
   and a strike-through is styling a graph engine may drop. **`S1` §5.9's
   boundary must not depend on a stylesheet.**
3. **`Holder: TBD` appears, and no name does.** Not the CDE Administrator, not a
   role standing in for one.
4. **The `may` and `does not` columns carry equal weight.** A large *may* beside
   a small *does not* teaches that the exclusions are footnotes.
5. **The never-approved-configuration sentence appears verbatim.** It is `S1`
   §5.9's wording and it is the slide's takeaway.
6. **No permissions screenshot, matrix or platform UI.** It would make
   configuration the concrete thing and governance the abstraction — exactly
   backwards.
7. **No org chart.** The boxes are a function's boundary, not a reporting line.
8. **No verification method.** *How* alignment is proven is **Module 6**; this
   visual states the requirement only.

**Design note.** The four-box chain is deliberately plain. If it is styled into a
process-maturity graphic — numbered stages, gradients, a loop back to the start —
it acquires a completeness this slide does not claim, and the loop reintroduces
the reverse arrow the visual exists to refuse.

### W14 — Triviron CDE-definition questions · **specified (T4-D)**

| Field | Value |
|---|---|
| **Slide** | 14 |
| **Teaching purpose** | Convert the module into **questions Triviron must answer before configuring anything** |
| **Source basis** | **No Triviron source exists.** The question *structure* draws on `S1` §6.1, §6.3, §9.7, §9.8, §11.3, §11.4, §5.9, §12.6, §12.8; `S2` §2, §3.3, §19; `S4` §7, §11; `S5` §5.1; `CGD-C01`–`CGD-C08` |
| **Classification** | `INTERP` + `SYNTH` |
| **Governance status** | **None asserted for Triviron** — the project has no entry in any register |
| **Implementation status** | **None asserted for Triviron** |
| **Simplify** | **Five grouped question sets**, then two isolated authority questions, then the end state |
| **Omit** | **Every Triviron fact** — jurisdiction, project type, client, asset, procurement route, appointments, named roles, platform, folder structure, states, naming, codes, schema, dates, teams. **Every answer, default, placeholder, example and recommendation** |
| **Overclaim risk** | **HIGH — about Triviron, not about Harrismith** |
| **Blocked element visible?** | **YES — the two authority questions stay unanswered, and the end state stays open** |
| **Live evidence required?** | No |
| **External imagery** | No |

**The fixed form:**

```text
  1  CDE PURPOSE AND SCOPE
     What information? Which teams? Which uses? Which phases?
     What evidence that the process operates?

  2  INFORMATION STATES AND PERMITTED USE
     Which states? What is each for? Who may rely on each?
     Conceptual, physical or both? Which folder relationship?
     How will folder location be prevented from meaning state?

  3  TRANSITIONS, GATES AND AUTHORITY
     Which actions change state? Who initiates? Who checks?
     Who authorises? What if an authority is unassigned?
     Which transitions must stay blocked?

           ┌───────────────────────────────────────┐
           │  Who holds publication authority?     │
           │                                       │
           │  Who holds acceptance authority?      │
           └───────────────────────────────────────┘
                    ▲ asked, and not answered

  4  NAMING, REVISION, SUITABILITY AND METADATA
     Which standard? Which convention? Which codes? What schema?
     Who assigns and checks? How are codes kept distinct from
     evidence that the process occurred?

  5  PLATFORM CONFIGURATION AND IMPLEMENTATION EVIDENCE
     Which platform? Who may configure? How authorised?
     How are deviations recorded? How is configuration verified
     against governance? Who declares the CDE ready for use?

  ───────────────────────────────────────────────────────────
       CDE configuration basis — not yet established
```

**Nine mandatory design requirements.**

1. **Every item ends in a question mark.** A statement anywhere on this slide is
   an invented Triviron fact.
2. **The two authority questions appear verbatim, together, and set apart.**
   `Who holds publication authority?` and `Who holds acceptance authority?`
3. **Neither is answered, hinted at or paired with a candidate role.** `S1` §9.7
   already excludes four by name; a fifth must not appear.
4. **No Triviron fact of any kind**, including a placeholder project name, a
   plausible platform, a folder tree or a date.
5. **No answer column, no "typical practice" column, no worked example.**
6. **The five groups keep their order.** Purpose precedes states; states precede
   transitions; configuration is last — because the order *is* the argument.
7. **`CDE configuration basis — not yet established` appears as the end state**,
   in neutral styling.
8. **The end state carries no warning colour, no icon, no date and no owner.** It
   is a correct starting position, not a defect.
9. **No Harrismith status is transferred onto Triviron.** Harrismith's blocked
   `T4` is the *reason the question is asked*, not a prediction about a project
   nobody here has described.

**Design note.** This slide will look sparse, and a producer will want to balance
it — an illustrative answer, a sample state model, a suggested platform, a
progress bar under the end state. **Each of those invents the project.** The
sparseness is the deliverable: the audience should leave holding questions, not a
template someone drew for a project that does not yet exist.

---

## 5. Summary

| ID | Slide | Format | Overclaim risk | Blocked element visible |
|---|---|---|---|---|
| `W1` | 1 | **Layout — specified; three stacked bands** | **HIGH** | **Three status labels, on the slide** |
| `W2` | 2 | **Layout — specified; five cards, one row** | MEDIUM-HIGH | **YES — three absent code sets** |
| `W3` | 3 | **Layout — specified; never Mermaid** | **HIGHEST** | **YES — blocked route, empty authority, unreachable connector** |
| `W4` | 4 | **Layout — specified** | MEDIUM-HIGH | **No route out drawn** |
| `W5` | 5 | **Layout — specified** | **HIGH** | No |
| `W6` | 6 | **Layout — specified** | **HIGH** | **YES — empty authority position** |
| `W7` | 7 | **Layout — specified** | MEDIUM-HIGH | **YES — empty method panel** |
| `W8` | 8 | **Layout — specified** | **HIGH** | **No connector between panels** |
| `W9` | 9 | **Table — specified; never Mermaid** | **HIGHEST** | **YES — `T4` blocked, `T7` unresolved** |
| `W10` | 10 | **Layout — specified** | MEDIUM-HIGH | **Evidence field mandatory** |
| `W11` | 11 | **Layout — specified; two panels** | **HIGH** | **YES — the visual is two blocks** |
| `W12` | 12 | **Layout — specified** | **HIGH** | **YES — four empty boxes** |
| `W13` | 13 | **Layout — specified; never Mermaid** | MEDIUM-HIGH | **YES — refused reverse arrow; `Holder: TBD`** |
| `W14` | 14 | **Layout — specified** | **HIGH (Triviron)** | **YES — two authority questions; end state open** |

**Fourteen visual concepts. All fourteen are now specified in full** — `W4`–`W7`
(T4-B), `W8`–`W11` (T4-C), `W12`–`W14` (T4-D) and `W1`–`W3` (T4-E-A). **Nine
carry HIGH or HIGHEST overclaim risk, and thirteen of the fourteen must keep
something visibly incomplete, mandatory or unfilled — `W5` alone has no such
element.**

*(An earlier revision of this summary counted six HIGH-or-HIGHEST and eight
incomplete-element visuals. Both were undercounts against the table above, and
the table is the authority.)*

**All fourteen are native layout specifications.** **No source file and no
rendered asset exists** — not for `W1`–`W3`, and not for any of the eleven
specified before them. **Visual-source production is the next increment**, and
the specification remains authoritative over anything it produces.

**Eight visuals carry the highest completion risk** — a mandatory empty, blocked
or refused element that a producer is most likely to "fix":

| Visual | What stays incomplete | Why |
|---|---|---|
| `W2` | **The three absent code sets** | A producer's instinct is to show *an example*, and one example is a standard this project has not adopted |
| `W3` | **The blocked route, the empty publication authority, and the unreachable third connector** | The module's highest-risk visual: completing any one of the three asserts a working publication lifecycle |
| `W6` | The publication-authority position | Omission reads as *no authority needed*; a filled field invents a decision |
| `W7` | The retention-method panel | The obligation is governed; the method is not |
| `W11` | Both blocked objects | The block is a feature of the model, not a gap in it |
| `W12` | **Four `not established` boxes** | Filling any one invents a standard the project has explicitly declined to create |
| `W13` | **The refused reverse arrow, and `Holder: TBD`** | A forward-only chain can be read backwards; a named holder assigns an unassigned role |
| `W14` | **The two authority questions, and the end state** | Answering either is the module's single worst failure |

**This is a ranked judgement, not a count.** `W4`, `W8` and `W9` also carry
mandatory absences — a route out of WIP that must not be drawn, a connector that
must not appear between two panels, and two register cells that stay blocked and
unresolved. They sit outside the table because the risk there is **conversion**
— a producer turning a table into a flowchart — rather than **completion**.

**A producer who removes, fills, shades or completes any of them has changed the
claim.**

**No visual in Module 4 is Mermaid, and `W1`–`W3` were the last three that could
have been.** **`W1` moved in T4-E-A** — a three-node chain is exactly what a
graph renderer draws well, but the renderer chooses the layout direction, and on
`W1` the **vertical order is the content**: a horizontal rendering of governance,
workflow and platform states that the three are peers. **`W2` moved in T4-E-A**
— any graph of five properties draws edges between them, and the whole visual
exists to have none. **`W3` moved in T4-E-A** — Mermaid renders a chain, a chain
implies traversal, and its three connectors must differ from one another in ways
a renderer normalises away. **`W13` moved in T4-D**: it must show a reverse arrow
that is *visibly refused*, and a graph renderer draws a refused edge as a real
edge while a strike-through is styling it may silently drop. **`W4` moved in
T4-B** — a Mermaid boundary with a gate renders an outbound edge, and the route
out of WIP must not be drawn. **`W10` moved in T4-C** — a renderer laying out a
five-stage chain normalises side labels into the chain, and CDE Administration
must sit beside it, not in it.

**`W9` is the absolute case.** A Mermaid rendering of `T1`–`T8` produces eight
sequential transitions no matter what the caption says. **A grouped table is the
only permitted form**, and a producer who converts it has committed prohibition
58. **Everything that depicts a state, a transition set, a direction of authority
or an absent control is a layout specification**, because a renderer that
normalises a broken line into a solid one commits the module's central error.

**No external imagery is required. No live observation is required, and none is
authorised.**

## 6. What this plan does not do

- It creates **no asset**. No source file, no rendered image.
- It authorises **no live Autodesk observation, read or configuration act.**
  Root [`README.md`](../../README.md) §2.1 applies unmodified.
- It does **not** resolve any unresolved matter.
- It carries **no governance authority.**
