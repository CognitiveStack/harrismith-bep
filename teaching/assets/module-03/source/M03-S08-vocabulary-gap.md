# M03-S08 — The parties, the teams and the vocabulary gap

| Field | Value |
|---|---|
| **Slide-source identifier** | `M03-S08` |
| **Related slide** | Slide 8 |
| **Slide title** | The parties, the teams and the vocabulary gap |
| **Related visual concept** | `V6` |
| **Teaching purpose** | Show two vocabularies side by side **without asserting any mapping between them** |
| **Principal sources** | **`X6` — UK guidance** (two terms only); `H1` §4.2, §4.3, §4.6, §5.4–§5.9; verified occurrence counts |
| **Evidence classification** | **`GUIDANCE` — UK** for the two registered terms; **`UNRESOLVED`** for *appointed party*, *delivery team* and *task team* as ISO-associated terms — **named, not defined**; **`HARRISMITH`** for every right-hand term |
| **Jurisdiction** | **UNITED KINGDOM** (left) · **This project** (right) — **the distinction is the visual's subject** |
| **Known limitation** | **No relationship in the register is `ESTABLISHED`.** Mapping would require the appointment structure, the contractual context **and** the standard's definitions — **none of the three is available** |
| **Copyright risk** | **LOW** for the layout; **MEDIUM** for the terms — used **as terminology, never with definitions attached** |
| **Overclaim risk** | **HIGHEST IN THE MODULE, jointly with `M03-S13`.** **The layout can commit the error with no word spoken** |
| **Mandatory presentation warning** | **Rows stay offset. `lead appointed party` is never drawn opposite `Lead Delivery Party`.** No arrow, no colour matching, no equals sign, no tick. The warning `Terminology mapping not established` appears **on the slide** |
| **Increment** | `T3-F` |

---

## 1. Format decision — a layout, deliberately not Mermaid

**Mermaid would align rows, and could add edges.** Alignment *is* the assertion
this visual exists to refuse. The offset is not decoration — **it is the content**.

**No graph, no connectors, no shared container.** Two columns, a labelled gutter,
and nothing crossing it.

## 2. Layout specification

```text
  ISO-ASSOCIATED / UK-GUIDANCE            │  HARRISMITH PROJECT
  VOCABULARY                              │  VOCABULARY
  ── UK context ──                        │  ── this project ──
                                          │
  appointing party            [X6]        │
    registered guidance                   │      Owner / Appointing Party
                                          │      Appointing Party          19×
                                          │
  lead appointed party        [X6]        │
    registered guidance                   │
                                          │      Lead Delivery Party       20×
                                          │
  appointed party                         │
    named, not defined            0×  ────┼──►   ( nothing )
                                          │
  delivery team                           │
    named, not defined                    │      1× incidental prose only
                                          │      — not a defined term
  task team                               │
    named, not defined                    │      task team               164×
                                          │        a defined structure (BEP §4.3)
                                          │
                                          │      BIM Manager
                                          │      BIM Coordinator
                                          │      Task-Team Lead
                                          │      Author · Checker
                                          │      CDE Administration
                                          │
            ▲ GUTTER, labelled:  "Mapping not established"
            ▲ ON-SLIDE WARNING:  Terminology mapping not established
```

**Eight mandatory layout requirements.**

1. **Rows do not align across the gutter.** Deliberately offset. **In particular,
   `lead appointed party` is never drawn directly opposite `Lead Delivery
   Party`.**
2. **The gutter is labelled `Mapping not established`.**
3. **`appointed party` faces empty space.** Harrismith has no such term, and
   **the empty space is the teaching**.
4. **No arrows between unverified terms.** None. An arrow is an assertion.
5. **Neutral spacing, not colour-coded matching.** No colour pairs terms; no
   green, no ticks, no equivalence symbols.
6. **A visible terminology warning on the slide** — not in the notes.
7. **The left column distinguishes *registered* from *named*.** `appointing
   party` and `lead appointed party` carry the UK-guidance label; the other three
   carry **named, not defined**.
8. **Occurrence counts may appear — they are the evidence.** `0×` does more work
   than any annotation, and the **`1×`** against *delivery team* matters
   precisely because it is not zero.

## 3. Vocabulary relationship register

**Reproduced from [`../../module-03-iso-19650-principles/source-map.md`](../../../module-03-iso-19650-principles/source-map.md) §4, Slide 8. Authoritative there.**

| ISO-associated term | Harrismith term | Relationship |
|---|---|---|
| appointing party | `Owner / Appointing Party` · `Appointing Party` | **POSSIBLE** — wording close, **not identical; equivalence not established** |
| lead appointed party | `Lead Delivery Party` | **UNVERIFIED** — conceptually adjacent; **identity excluded** |
| appointed party | *(none)* | **NO COUNTERPART** — zero occurrences; **absence shown, not filled** |
| delivery team | *(none defined)* | **NO COUNTERPART** — one incidental prose use is not a defined term |
| task team | `task team` | **SHARED WORD, UNVERIFIED** — same word, different defined content |
| *(none registered)* | `BIM Manager` · `BIM Coordinator` · `Task-Team Lead` · `Author` · `Checker` · `CDE Administration` | **NOT COMPARED** — no ISO-associated counterpart is registered |

**None is `ESTABLISHED`.** That is the finding, and the slide exists to make it
visible rather than to resolve it.

## 4. The governing rule, shown on the slide

```text
Possible conceptual relationship
  ≠ verified terminological identity
```

## 5. One nuance, for the notes rather than the slide

`task team` is the single word appearing in both columns — **and even that is not
an established identity.** Harrismith's is defined in `H1` §4.3 and carries this
project's structure, including that Mechanical, Electrical and Plumbing are
**three task teams within one MEP Consultant party**, not three companies.
**Shared vocabulary, different content.**

## 6. Simplify and omit

| Simplify | Omit |
|---|---|
| Two columns, offset rows, one labelled gutter | **Every connecting line, arrow or equals sign between the columns** |
| Occurrence counts where they carry evidence | **Any colour-coded pairing, tick or equivalence symbol** |
| One on-slide warning, one governing rule | Any person, organisation or job title |
| — | **Any inferred contractual mapping** |

## 7. Overclaim risk

**HIGHEST.** A two-column layout invites the eye to pair rows, and pairing
`Lead Delivery Party` with *lead appointed party* commits prohibition 24 **without
a word being spoken**. The offset, the gutter and the empty space are recorded as
**content, not styling** — and if a producer aligns the rows, the change is
reverted.

**Any conceptual similarity belongs in the speaker notes, not in the visual.** The
presenter may say *"these may well be related"*; the slide may not draw it.
