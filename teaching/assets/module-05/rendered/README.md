# Module 5 — Rendered Assets

**Status: NONE.**

**Teaching material. Not governance.**

---

## 1. What is here

**Nothing but this file.**

| Field | Value |
|---|---|
| Rendered assets | **NONE** |
| Rendering attempted | **No** |
| Renderer installed | **None** |
| Image converter installed | **None** |
| Diagramming dependency installed | **None** |
| Network rendering service used | **No** |

**No SVG, PNG, JPG, PDF, PowerPoint or office file exists in this directory or
anywhere in the Module 5 asset set.**

## 2. Why there is nothing to render

**The fourteen Module 5 source files are native-layout Markdown
specifications.** They record geometry in points, exact visible wording,
connector semantics, build sequences, mandatory omissions and STOP conditions.

**They contain no Mermaid.** They also contain no Graphviz and no PlantUML.

That is a **design decision, not a gap**, and it was taken concept by concept in
the accepted plan. Every one of the fourteen visuals carries at least one hazard
that automatic layout would misrepresent:

| Hazard | What a renderer would do |
|---|---|
| A **blocked** route | Normalise the broken `TRN-E03` → `T4` connector into a solid edge, completing a route the module exists to show as halted |
| **Eight controlled steps** | Sequence them, asserting eight transitions where only `T1` and `T4` change state |
| **Three delivery events** | Order them, asserting a mandatory sequence the sources do not state |
| **Three separate resources** | Connect or nest them, implying one merged structure |
| **A boundary-preserving overlap** | Render a merge or a parent node, asserting exactly the collapse Slide 8 denies |
| **Five closed gates** | Chain them, implying that clearing one leads to the next |
| **A Harrismith example beside a Triviron question** | Draw an edge — which is a recommendation, regardless of the label on it |

**There is therefore no diagram source a renderer could consume.**

## 3. How the slides are built instead

**Future slides are reconstructed with native PowerPoint objects** —
rectangles, tables, text boxes, simple call-outs and deliberately controlled
connectors. Each source file carries its own §15 reconstruction note.

**No SmartArt.** Its automatic layouts imply the hierarchy and sequence this
module spends fourteen slides denying.

**No imported image of any kind** — no screenshot, no logo, no stock photography,
no live CDE capture.

## 4. If rendering is ever undertaken

**A render is derivative.** It acquires no authority by existing.

```text
accepted visual-demonstration plan
  ↓
Module 5 slide-source file
  ↓
any future render or PowerPoint          ← derivative, never authoritative
```

**The accepted plan and the source files remain authoritative.** Where a render
and a source differ, **the source wins**; where a source and the plan differ,
**the plan wins**.

**The absolute rule.** **No empty, blocked, broken or refused element may be
completed by a renderer.** In particular:

- the **broken `TRN-E03` → `T4` connector** stays broken;
- the **unpopulated matrix skeleton** on Slide 4 stays unpopulated;
- the **five closed gates** on Slide 12 stay closed, and none acquires a sixth;
- the **`D4` row** keeps all nine cells — **five `TBD`, four `—`** — and is never
  completed or abbreviated;
- the **five empty answer areas** on Slide 14 stay empty apart from
  `NOT YET ESTABLISHED`;
- the **gutter** on Slide 6 stays empty and uncrossed.

**A renderer that tidies any of these has manufactured governance that does not
exist.**

## 5. Scope

**`T5-H` owns external PowerPoint production — not this increment, and not this
directory.** When it happens, the deck is produced **outside this repository**
and **is not committed here**, as for Modules 1 to 4.

**`T5-G` — the presentation assembly package — comes first, and does not exist.**

**Timing remains `20.0 minutes allocated — not measured`.**
