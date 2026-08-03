# M01-S01 — Title slide layout specification

| Field | Value |
|---|---|
| **Visual identifier** | `M01-S01` |
| **Related slide** | Slide 1 — What Is a BIM Execution Plan? |
| **Purpose** | Establish the BEP as an operating agreement, introduce Harrismith as the worked example, and identify Triviron as the transfer context |
| **Source format** | Layout specification (no diagram) |
| **Source documents** | `bep/Harrismith-Fire-Station-BEP.md` §1.1, §1.2, §2.1, §2.2 |
| **Evidence classification** | **DIRECT** for the status wording; **SYNTHESIS** for the framing line |
| **Known limitation** | **The hero image `V1` does not exist in this repository.** No Harrismith model image, render or photograph is committed. This specification therefore defines a deliverable slide *without* it |
| **Last increment** | T1-D |

---

## 1. Why this is a specification and not a diagram

The visual plan's **V1 — Harrismith Fire Station project or model image** is an
**external dependency**. No image asset exists in this repository, and none may
be fabricated.

Three things are therefore prohibited for this slide:

- generating an AI image and presenting it as a Harrismith project view;
- substituting a stock building photograph captioned as Harrismith;
- implying that any image shown is evidence of the project's model content.

**Slide 1 is deliverable without V1.** The layout below works as a text-and-space
treatment and is upgraded, not rescued, if a genuine project view later becomes
available.

## 2. Layout — without V1 (the deliverable default)

```text
┌─────────────────────────────────────────────────────────────┐
│                                                             │
│                                                             │
│     What Is a BIM Execution Plan?                           │
│     ────────────────────────────────                        │
│     The Harrismith Fire Station as a worked example         │
│                                                             │
│                                                             │
│     An operating agreement for how a project team           │
│     handles information                                     │
│                                                             │
│                                                             │
│                                    Training and reference   │
│                                    implementation           │
└─────────────────────────────────────────────────────────────┘
```

| Element | Content | Notes |
|---|---|---|
| Title | `What Is a BIM Execution Plan?` | Largest element on the slide |
| Subtitle | `The Harrismith Fire Station as a worked example` | Directly beneath, clearly subordinate |
| Framing line | `An operating agreement for how a project team handles information` | **Teaching synthesis.** Not the BEP's own purpose wording |
| Status note | `Training and reference implementation` | Small, low-contrast, bottom corner |

**The definition does not appear on this slide.** It is spoken, and lands on
Slide 3 once the problem has been established — see
[`presentation-outline.md`](../../../module-01-what-is-a-bep/presentation-outline.md).

## 3. Layout — with V1, if a genuine project view later exists

```text
┌─────────────────────────────────────────────────────────────┐
│                                     ┌─────────────────────┐ │
│  What Is a BIM                      │                     │ │
│  Execution Plan?                    │   V1 — project or   │ │
│  ──────────────                     │   model view        │ │
│  The Harrismith Fire Station        │                     │ │
│  as a worked example                │   clean 3D view     │ │
│                                     │   no UI chrome      │ │
│  An operating agreement for how     │                     │ │
│  a project team handles information │                     │ │
│                                     └─────────────────────┘ │
│  Training and reference implementation                      │
└─────────────────────────────────────────────────────────────┘
```

### What V1 would need to demonstrate

| Requirement | Reason |
|---|---|
| A recognisable building, not an abstract model fragment | The slide's job is to anchor an abstraction in a real project |
| A clean 3D or elevation view | Establishes "this is a project" in under two seconds |
| **No** view tabs, browser trees, ribbons or toolbars | Software chrome converts a project slide into a software slide |
| **No** legible filenames, user names or dates | Incidental detail that should not be projected |
| Captioned as a project view, never as evidence of coordination | Presence of a model proves nothing about how information is governed |

### What V1 would **not** license

Showing a model does not establish that six discipline models exist, that any
are coordinated, or that the governed workflow is operating. Only Architecture
was observed as a populated direct production stream at the level inspected
(`OF-002`), and **absence of observation is not observation of absence**.

## 4. Status honesty on this slide

The status note is not decoration. Three facts must reach the audience in the
first minute, and the slide carries the first of them:

1. Harrismith is a **training and reference implementation** — non-contractual,
   no appointment behind it.
2. The documentation is **approved with conditions**, and **publication is not
   authorised**.
3. Agreement is not implementation.

Items 2 and 3 are spoken rather than printed here; item 3 is delivered by Slide
13.

## 5. Prohibited on this slide

- Any fabricated or AI-generated image presented as a Harrismith project view.
- Any company name, logo or brand identity — **no corporate or Triviron brand
  identity is chosen in this increment**.
- Any named person, role holder or signatory. Every holder is **TBD**.
- Any date other than a sourced governance date, and none is needed here.
- Any claim of ISO compliance or certification.
