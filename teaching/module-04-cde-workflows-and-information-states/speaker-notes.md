# Module 4 — Speaker Notes, Slides 1–3

**Status:** Working notes. **Not a script, and not final.**

These support speaking in your own words. The *essential message* must be
communicated; the *suggested wording* is one route to it and should be replaced
if it does not sound like you.

**No rehearsal has occurred, and no timing has been measured.** Every figure
below is a planned allocation.

**One rule specific to this module.** Every workflow statement carries **two**
statuses — what is **governed**, and what is **implemented**. They are not the
same, and `S2` says so on its own first page. **If you state that a control
works, be sure you mean *is approved* rather than *is running*.**

---

## Slide 1 — A CDE is a governed process, not a folder tree · 1.5 min

### Purpose

Establish the CDE as an information-management process supported by technology,
and separate the process from the folders and permissions implementing part of
it.

### Essential message

1. A CDE is **a process**, not a folder tree.
2. It controls how information is **developed, checked, shared, authorised,
   delivered and retained**.
3. **Technology supports the process** — a folder structure implements part of
   it.
4. **A folder alone establishes no state, no authority and no permitted use.**
5. **Our workflow is proposed governance, not a description of the live
   platform.**

### Suggested wording

> "Module 4 is the detailed one. Modules 1 to 3 built up to it — the BEP records
> the method, functions hold the authorities, and principles become
> project-specific governance. Now we look at the machinery.
>
> And the first thing to say is what a common data environment actually is,
> because most of us have one and most of us would describe it as a folder
> structure.
>
> Our BEP is blunt about that. The CDE is an information-management process
> supported by technology. **It is not a folder tree.** A folder structure is one
> way of implementing part of the process — it is not the process, and
> reorganising folders does not change how information is governed.
>
> So what does it control? Six things. How information gets developed — authored
> and iterated inside a task team. How it gets checked. How it gets shared —
> deliberately, for a stated purpose. How it gets authorised, which is a separate
> decision. How it gets delivered. And how it gets retained so someone can trace
> it later.
>
> Notice that none of those is *where the file sits*. Our CDE structure decision
> says it directly: the existence or name of an area does not by itself establish
> an information state.
>
> One more thing, and it's the honest framing for the whole module. **What I'm
> about to show you is proposed governance.** Our CDE strategy classifies itself
> that way, and says on its first page that it does not describe the live
> platform. It's what we've decided should happen. Whether the software currently
> does it is a separate question, and mostly an open one."

### Shorter fallback

> "A CDE is a process, not a folder tree — our BEP's words. It controls how
> information is developed, checked, shared, authorised, delivered and retained.
> Folders and permissions implement part of it; they don't define authority or
> permitted use. And what I'm showing you is **proposed** governance — our own
> strategy says it doesn't describe the live platform."

### Harrismith source basis

| Statement | Source |
|---|---|
| *"an information-management process supported by technology… **It is not a folder tree**"* | **`S1` §6.1** — `bep/Harrismith-Fire-Station-BEP.md` |
| *"The CDE is a process, not a folder tree… the presence or absence of a folder proves nothing about state"* | **`S2`** purpose statement — `supporting/cde-workflow-state-strategy.md` |
| *"The existence or name of an area does not by itself establish an information state"* | **`CGD-C01`** — `docs/CDE-Structure-Governance-Decision.md` |
| *"Permission ≠ authority"* | **`S2` §14**; `S1` §6.9 |
| *"Being able to perform an action in the software says nothing about who was authorised to decide it"* | **`S4` §9** — `docs/Increment-7C-Live-Validation-Record.md` |

**All Harrismith project wording. None is an ISO definition**, and none should be
attributed to a standard.

### Earlier-module callback

**Four lines, roughly fifteen seconds. Do not re-teach any of them.**

> "Module 1: the BEP is where the method gets written down. Module 2: someone has
> to hold each function. Module 3: principles become project-specific governance,
> then configuration, then evidence. Module 4: now the workflow itself."

### Likely question

**"Is ACC the CDE?"**

### Safe answer

> "No — it's a platform that can support one. Our BEP's line is that a CDE is an
> information-management process supported by technology, and specifically not a
> folder tree. ACC can host the process, record it, and enforce parts of it. It
> can also host no process at all, which is the more common outcome. Buying it
> gets you capability, not governance."

**Second likely question — "Is our folder structure the CDE?"**

> "No. We have adopted a four-area root topology, and we've mapped three of those
> areas to information states — that mapping is a governance decision, recorded
> in CGD-001. But the decision is explicit that **the existence or name of an area
> does not by itself establish an information state.** The folders implement part
> of the arrangement. The arrangement is the CDE."

**Third likely question — "Are these states already configured in ACC?"**

> "The four root areas were observed, and they correspond to the topology we
> adopted. But CGD-001 says a later controlled verification must confirm the live
> topology before the mapping is relied on operationally — and that verification
> hasn't happened. So: observed, adopted, **not verified**. I'd rather tell you
> that than imply we've checked."

### Transition to Slide 2

> "So the CDE governs how information moves. Before we look at the moving, we
> need the vocabulary — because there are five different properties people treat
> as one."

### Evidence classification

**`CONTROLLED GOVERNANCE`** — the CDE-as-process statement; permission ≠
authority (`M4-S1-01`, `M4-S1-06`).
**`PROPOSED GOVERNANCE`** — the workflow that implements the principles
(`M4-S1-10`).
**Controlled decision record** — states are not folders; folder placement
establishes nothing (`M4-S1-05`).
**Controlled validation record** — platform ability is not authority
(`M4-S1-07`).
**`INTERP`** — the six things a CDE controls; the earlier-module callback
(`M4-S1-04`, `M4-S1-08`).
**`SYNTH`** — the required message (`M4-S1-09`).
**`IMPLEMENTATION UNVERIFIED`** — the four-area topology (`M4-S1-11`).

### Implementation-status warning

**Say the proposed-governance framing on this slide, not later.** `S2`
classifies its own workflow as **`PROPOSED GOVERNANCE`** and states it **does not
describe the live platform**. An audience that spends thirteen slides believing
they are being shown a running system has learned the wrong thing, and Slide 11
will land as a defect report rather than as governance working.

### Delivery warning

**The likeliest misunderstanding is that you are describing ACC.** You are
describing a governed process. Two guards: say *"our BEP's words"* when quoting
`S1`, and **never point at a folder while saying the word *state***.

**The second warning is tone.** *"It is not a folder tree"* can sound like a
rebuke to whoever built the folder tree. It is not — the folders are a correct
partial implementation of an adopted topology. **The point is what they do not
prove.**

---

## Slide 2 — State, version, revision, status and suitability are different · 1.5 min

### Purpose

Stop the audience treating every change-related property as interchangeable.
Sections B and C depend on this vocabulary.

### Essential message

1. Five properties, **five different governance questions**.
2. **State** — where may it be used. **Version** — which stored occurrence.
   **Revision** — which managed issue. **Status** — what condition is declared.
   **Suitability** — for what use.
3. **A new platform version creates none of the others.**
4. **Status is not suitability; suitability is not acceptance.**
5. **Folder location creates none of the five.**

### Suggested wording

> "Five words that get used as if they were one. They are not, and every one of
> them answers a different question.
>
> **State** — where may this be used? WIP, Shared, Published, Record. That's the
> governed context.
>
> **Version** — which stored occurrence is this? Our BEP calls it a platform or
> file history instance. Every save is a version.
>
> **Revision** — which managed issue is this? A controlled issue identifier —
> and note the qualifier in our BEP: *where project convention requires one*. We
> don't have a convention yet, so we have the concept and not the code.
>
> **Status** — what condition is declared? A workflow or decision condition.
>
> **Suitability** — what may it actually be used for? The permitted intended
> use.
>
> Now the rule, and our BEP states it flatly: **a new platform version creates
> none of the others.** Saving a new version doesn't create a revision, doesn't
> change the information state, doesn't constitute approval, and doesn't make the
> information suitable for a new purpose. Each is a separate act with its own
> decision and its own responsible role.
>
> And two more that catch people out. **Status isn't suitability** — a thing can
> be marked *reviewed* and still not be suitable for the use you have in mind.
> And **suitability isn't acceptance** — acceptance is a recipient's decision
> against a stated purpose, and it's somebody else's to make.
>
> Last one. **None of the five is created by where the file sits.**"

### Shorter fallback

> "Five properties, five questions. State — where may it be used. Version —
> which stored occurrence. Revision — which managed issue, where a convention
> requires one. Status — what condition is declared. Suitability — for what use.
> A new version creates none of the others. Status isn't suitability, suitability
> isn't acceptance, and folder location creates none of the five."

### Harrismith source basis

| Statement | Source |
|---|---|
| The five definitions, verbatim | **`S1` §6.8**, with **`S2` §13** |
| *"A new platform version creates none of the others"* | **`S1` §6.8** |
| *"These are never used interchangeably"* | **`S2` §13** |
| A Published container does not automatically mean delivered, received, accepted, or suitable for a different purpose | **`S2` §13** |
| Folder location establishes nothing | **`CGD-C01`** |

**The five questions are the presenter's framing**, not source wording.

### Earlier-module callback

**One line if needed:** *"Module 3 touched this — five separate properties. This
is the version with the definitions attached."* **Do not re-run Module 3's
platform argument.**

### Likely question

**"What is the difference between version and revision?"**

### Safe answer

> "A version is a platform fact — an occurrence in the file history. It happens
> because someone saved. A revision is a **controlled issue identifier** — it
> exists because someone decided to issue something and recorded which issue it
> was. One is automatic, the other is a decision. And our BEP adds a qualifier
> worth noticing: a revision applies **where project convention requires one** —
> and we haven't established a convention, so we have the concept without the
> code set."

**Second likely question — "Is suitability the same as approval?"**

> "No. Suitability says what the information may be used for. Approval — and more
> precisely **acceptance** — is a recipient's decision that it's suitable **for
> their stated purpose**. They're different acts by different parties. A container
> can carry a suitability designation and be rejected by a recipient, and the
> rejection doesn't change the suitability designation. It records a decision
> against a purpose."

### Transition to Slide 3

> "So a container carries five properties at once. The first of them — state — is
> the one this module is really about, so let's look at ours."

### Evidence classification

**`CONTROLLED GOVERNANCE`** — the five definitions; the new-version rule; the
Published-does-not-mean table (`M4-S2-01`–`M4-S2-06`).
**Controlled decision record** — folder location creates none of the five
(`M4-S2-11`).
**`INTERP`** — the five questions; the six relationships (`M4-S2-07`,
`M4-S2-08`).
**`SYNTH`** — the required message (`M4-S2-12`).
**`UNRESOLVED`** — no revision convention; **no suitability code set**
(`M4-S2-09`, `M4-S2-10`).

### Implementation-status warning

**The properties are defined; their code sets are not.** No naming standard, no
revision convention and no suitability code set exists — all four `standards/`
directories are empty. **Teach the five distinctions; teach no codes.**

### Delivery warning

**Do not draw the five as a sequence.** A container has all five at once, and an
arrow between them implies a progression the sources deny — *a new version
creates none of the others*.

**And do not invent an example code.** *"So this might be revision P02,
suitability S2"* is the fastest way to teach a standard this project does not
have.

---

## Slide 3 — The Harrismith information-state model · 1.5 min

### Purpose

Introduce the four states and the purpose of each, **without teaching
transitions**. Transitions are Section C.

### Essential message

1. Four states: **WIP · Shared · Published / Authorised · Record / Retained**.
2. Each defines **a different permitted purpose and a different reliance**.
3. **Shared is not Published. Published is not Delivered.**
4. **Record / Retained is not a folder**, and no `04 Archive` exists or is
   required.
5. **A state is not created by moving a file.**

### Suggested wording

> "Four states. Each says something different about who may rely on the
> information and for what.
>
> **WIP.** Information under originator or task-team control, and — our BEP's
> words — **not authorised for general project reliance**. It's where authoring,
> iteration and internal checking happen. It may hold many versions. And
> visibility of WIP is not permission to rely on it: you being able to see it
> doesn't mean you may use it.
>
> **Shared.** Information deliberately made available beyond the originating task
> team, for an identified purpose — **after required checking and
> authorisation**. Both of those words matter. And Shared does **not** mean
> published, accepted, or suitable for every purpose.
>
> **Published or Authorised.** Information authorised for a defined delivery or
> use purpose. That's a separate decision by a function holding that authority —
> and I'll come back to that, because on this project nobody holds it.
>
> **Record or Retained.** Historical evidence retained for traceability. And
> here's the one people expect me to point at a folder for: **it isn't a folder.**
> Our BEP, our CDE strategy and our structure decision all say the same thing —
> it's a conceptual state and a retention requirement, there's no mandatory
> `04 Archive` root approved or required, and our retention approach is still to
> be decided.
>
> Now the thing that ties this to the folders. We've adopted four root areas, and
> we've mapped three of them to states. But the mapping is the governance, not
> the folder. Our structure decision is explicit — **putting a file in
> `03. Published` does not publish it.** Publication is a chain of governed
> events, not a location.
>
> And the honest caption for the whole slide: this is a **conceptual state model**.
> It is not proof of live platform implementation."

### Shorter fallback

> "WIP — under task-team control, not authorised for general reliance. Shared —
> available beyond the originating team for an identified purpose, after checking
> and authorisation; not published, not accepted. Published/Authorised —
> authorised for a defined purpose, by a separate decision. Record/Retained —
> historical evidence for traceability, and **not a folder**; there's no
> `04 Archive` and our retention approach is TBD. And putting a file in a folder
> doesn't create a state."

### Harrismith source basis

| Statement | Source |
|---|---|
| The four state definitions | **`S1` §6.3** — the governing definition table |
| Elaboration of each; *"Shared does not mean published, accepted, or suitable for every purpose"* | **`S2` §1** |
| *"visibility of WIP is not permission to rely on it"* | **`S1` §7.5**; `S2` §1 |
| *"States are not folders"* | **`S1` §6.3**; **`CGD-C01`** |
| *"no mandatory CDE root named `04 Archive` is required or approved"* | **`S1` §6.3**; **`S2` §1**; **`CGD-C06`** |
| *"Putting a file in `03. Published` does not publish it"* | **`S3` §3.4** |
| *"Placement alone does not evidence that checking or authorisation occurred"* | **`S3` §3.3** |

**One terminology note, if the audience is reading closely.** Four label forms
for the fourth state exist across our sources — `Record / Retained` is the
majority form, and the governing table at `S1` §6.3 writes `Record / retained`.
**Casing and abbreviation, not meaning.** If asked, say exactly that; do not
declare one form correct.

### Earlier-module callback

**One line:** *"Module 3 named these states in passing and stopped. This is where
they get their definitions."*

### Likely question

**"Does moving a file into Shared make it Shared?"**

### Safe answer

> "No — and this is the single most important sentence in the module. Our
> structure decision says it directly: **movement or placement between platform
> areas must not be treated as sufficient evidence of a WIP-to-Shared,
> Shared-to-Published or other information-state transition.** Each transition
> requires the applicable governed checks, authorisation and evidence. So the
> file being in `02. Shared` tells you where the file is. Whether the information
> is Shared depends on whether the check happened and whether someone with the
> authority authorised the share."

**Second likely question — "Where is the Archive folder?"**

> "There isn't one, and there doesn't need to be. Record / Retained is a
> conceptual state and a retention requirement — three of our documents say so.
> **No mandatory `04 Archive` root is approved or required**, none has been
> created, and our retention approach is still to be decided. If you see one
> appear, someone invented it."

**Third likely question — "Why is Published blocked?"**

> "Because nobody holds the authority to publish. It's recorded as unresolved —
> and the consequence in our CDE strategy is precise: the transition **has no
> available authorising function, and information remains Shared**. I'll come back
> to it properly in Section C, because the interesting part isn't that it's
> blocked — it's that being blocked is the system working."

**Fourth likely question — "Is the state model an ISO requirement?"**

> "I can't tell you that. This is our project's state model, from our BEP and our
> CDE strategy. Module 3 covered why: ISO 19650 is a copyrighted standard we
> don't hold and I haven't read, so I can describe what **we** decided and not
> what a standard requires. Our states resemble practice associated with the
> standard — resemblance isn't conformity, and nobody has assessed us."

### Transition to Slide 4

> "So — four states, four different permissions to rely. Let's take them one at a
> time, starting where everything starts."

### Evidence classification

**`CONTROLLED GOVERNANCE`** — the four definitions; WIP visibility; Shared not
Published; Published not final (`M4-S3-01`–`M4-S3-07`).
**Controlled decision record** — the four adopted areas and their mapping;
placement proves nothing; no `04 Archive` (`M4-S3-08`–`M4-S3-11`).
**`INTERP`** — the terminology-variance position (`M4-S3-12`).
**`SYNTH`** — the required message (`M4-S3-14`).
**`BLOCKED`** — `Shared → Published` (`M4-S3-15`).
**`UNRESOLVED`** — retention approach; `04 Archive` status (`M4-S3-13`).
**`IMPLEMENTATION UNVERIFIED`** — the topology and every state's live
realisation (`M4-S3-16`).

### Implementation-status warning

**The state model is a concept, not an observation.** The mandatory on-slide
label — **`Conceptual state model — not proof of live platform
implementation`** — carries it in writing, and it must be legible.

`S4` records what was actually observed: only Architecture demonstrable as a
Shared input, `COORD-01` partially demonstrable, no complete coordination cycle,
and **no publication or acceptance authority evidence established**. **Say
none of that as a failure** — *absence of observation is not observation of
absence*.

### Delivery warning

**Do not complete the route through Published.** `T4` has no available
authorising function. A four-state chain with three solid arrows claims a
workflow this project cannot operate.

**Do not draw Record / Retained as a folder**, and do not invent `04 Archive`.
Three controlled sources say it is not required.

**And do not let the four areas become the four states.** They are three areas
mapped to states, one area (`0. Common Files`) mapped to none, and one state with
no area at all. **The mismatch is the teaching.**

---

## Slides 4–14

**Not developed.** No notes exist. Developing them is a later increment.
