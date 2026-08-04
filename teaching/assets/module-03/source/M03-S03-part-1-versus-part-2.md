# M03-S03 — Part 1 and Part 2 answer different questions

| Field | Value |
|---|---|
| **Slide-source identifier** | `M03-S03` |
| **Related slide** | Slide 3 |
| **Slide title** | Part 1 and Part 2 answer different questions |
| **Related visual concept** | `V3` |
| **Teaching purpose** | Show two published parts answering **two different questions**, with revision status visible but subordinate |
| **Principal sources** | `X1`, `X2` — published scope and edition currency; `X3`, `X4` — **draft status only** |
| **Evidence classification** | **`PUBLIC-SOURCE`** for both columns and both statuses; **`INTERP`** for the one-line summary |
| **Jurisdiction** | **International** |
| **Known limitation** | **Neither part has been read.** Every line is *published scope* or *edition status*. **Nothing here describes a requirement**, and the complete requirements are not available to this programme |
| **Copyright risk** | **MEDIUM-HIGH — the highest in the module.** This is the visual closest to reproducing document structure |
| **Overclaim risk** | **HIGH** — a tidy two-column table looks like a summary of the standards' *contents* |
| **Mandatory presentation warning** | **The label `Published scope — not a summary of requirements` appears on the slide.** Do not add detail to fill the columns: there is none available, and anything added is invented. **No clause number. No process-activity list. No third column for drafts** |
| **Increment** | `T3-F` |

---

## 1. Format decision — a table and a layout, deliberately not Mermaid

**A diagram between Part 1 and Part 2 would assert a relationship** — sequence,
derivation, or parent-and-child — that **no registered source establishes**. They
are two documents with different scopes, not two stages of anything.

**No nested boxes, no part-of-a-whole graphic, no structural diagram.**

## 2. Layout specification

```text
┌──────────────────────────────┐   ┌──────────────────────────────┐
│  ISO 19650-1:2018            │   │  ISO 19650-2:2018            │
│                              │   │                              │
│  "What is this about, and    │   │  "How is information managed │
│   on what principles?"       │   │   while an asset is          │
│                              │   │   delivered?"                │
│                              │   │                              │
│  · concepts and principles   │   │  · an information-management │
│  · an information-management │   │    process for the           │
│    framework                 │   │    DELIVERY PHASE            │
│  · exchanging, recording,    │   │  · the information exchanges │
│    versioning and organising │   │    within that phase         │
│    information               │   │  · applicable across asset   │
│  · the WHOLE ASSET           │   │    types, organisations and  │
│    LIFE CYCLE                │   │    procurement strategies    │
└──────────────────────────────┘   └──────────────────────────────┘
        equal width, equal weight, side by side

   ── Part 1 explains the conceptual framework;
      Part 2 applies an information-management process to asset delivery.
      (supported interpretation — neither part states it in these words)

   ── FOOTER, subordinate:
      Both published editions are under revision. A draft is not a current
      published requirement. The 2018 editions are current. (X3, X4)

   ── ON-SLIDE LABEL:
      Published scope — not a summary of requirements
```

## 3. Column content — the only permitted lines

**Every line below traces to a registered source's *information available*
field.** If a line cannot be traced there, it does not go on the slide.

| | **`ISO 19650-1:2018`** | **`ISO 19650-2:2018`** |
|---|---|---|
| **Question** | *What is this about, and on what principles?* | *How is information managed while an asset is delivered?* |
| **Scope** | Concepts and principles; an information-management framework | An information-management process for the **delivery phase** of assets |
| **Covers** | Exchanging, recording, versioning and organising information | The **information exchanges** within that phase |
| **Reach** | The **whole asset life cycle** | Applicable across asset types, organisations and procurement strategies |
| **Register entry** | `X1` — A1, public metadata only | `X2` — A1, public metadata only |

**Summary line, beneath both columns:**

> Part 1 explains the conceptual framework; Part 2 applies an
> information-management process to asset delivery.

*(**Supported interpretation** — `M3-S3-07`. Neither part states it in these
words.)*

## 4. The footer — revision status, subordinate

```text
Both published editions are under revision.
A draft is not a current published requirement.
The 2018 editions are current.
```

**One footer line, not a third column.** A third column gives the drafts equal
visual weight, which is exactly the status error the slide exists to prevent.

**Nothing about the drafts' content, stage or timing appears** — none is
established, and none is to be invented (`M3-S3-09`).

## 5. Simplify and omit

| Simplify | Omit |
|---|---|
| One question per column, three or four scope points each | **Any clause number** — none has been read |
| Two columns, equal width, equal weight | **Any ISO heading, section name or structural term** beyond the registered titles and part numbers |
| One summary line, one footer, one on-slide label | **Any Part 2 process-activity list** |
| — | **Any third column for the drafts** |
| — | **Any other part of the `ISO 19650` series** — not registered |
| — | Any nested, hierarchical or part-of-a-whole graphic |

## 6. Overclaim and copyright risk

**Copyright: MEDIUM-HIGH.** Everything here is metadata about two documents, and
metadata is one short step from the documents' own structure. The safeguard is
absolute: **only registered titles, edition years and public scope summaries may
appear.**

**Overclaim: HIGH.** The visual will read as a contents summary. The on-slide
label is the control, and it must be legible at projection scale — not a footnote.

**The temptation is to fill the columns.** Four bullets a side looks thin, and the
only available expansion is clause detail, of which there is none. **A thin,
honest column is the correct output.**
