# Module 4 — Speaker Notes, Slides 1–14

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

## Slide 4 — Work in Progress: authoring inside the task team · 1.0 min

### Purpose

Explain WIP as the controlled working context in which the originating task team
develops and checks its own information — before any controlled sharing.

### Essential message

1. WIP is the **task team's working state** — drafting, iterations, correction,
   checking preparation.
2. It **remains under the originating task team's responsibility**.
3. It may hold **incomplete, provisional or uncoordinated** work, and **many
   versions**.
4. **It is not authorised for broader project reliance.**
5. **Visibility is not permission.**

### Suggested wording

> "Everything starts here. WIP is the task team's working state — drafting,
> modelling, internal iterations, local coordination inside the team, correction,
> getting ready to be checked.
>
> Two things about it. It stays **under the originating task team's
> responsibility** — they author it, they check it, they assess readiness, and
> where governance gives them the authority, they authorise it to progress. And
> it may be **incomplete, provisional or uncoordinated**, and that's fine. That's
> what the state is for. Our BEP says WIP may contain many versions — and that
> **WIP versions are not project exchanges**. A new version in WIP is a working
> step. Not a share, not an issue, not something anyone else is expected to act
> on.
>
> Now the sentence I'd put on the slide if I could only keep one. **Visibility is
> not permission.** Being able to see or open another team's WIP — through folder
> access, a platform permission, or any other means — **does not constitute
> authority to use it. Permission to read is not authorisation to rely.**
>
> That's ours, verbatim. And it matters because on most projects the access is
> wide open and everyone quietly assumes that means something."

### Shorter fallback

> "WIP is the task team's working state — drafting, iteration, internal checking,
> correction. It stays their responsibility, it may be incomplete, and it may
> hold many versions — which are working steps, not exchanges. And the rule that
> matters: **visibility is not permission**. Being able to see another team's WIP
> is not authority to rely on it."

### Controlled Harrismith source basis

| Statement | Source |
|---|---|
| *"WIP is the task team's **working state**"* — drafting, iterations, local coordination, correction, checking preparation | **`S1` §7.5** |
| *"Information under originator / task-team control. **Not authorised for general project reliance**"* | **`S1` §6.3**; `S2` §1 |
| Originating task team responsible for authoring, internal checking, readiness assessment, authorisation for progression | **`S1` §6.4** |
| *"**WIP versions are not project exchanges**"* | **`S1` §7.5** |
| *"**Visibility is not permission**… Permission to read is not authorisation to rely"* | **`S1` §7.5** |
| *"A team space is a platform construct… **Membership confers no authority**"* | **`S1` §6.4** |

### Permitted-use boundary

**Nobody outside the originating task team may rely on WIP** — *"Other parties do
not rely on WIP unless an explicitly governed exception exists"* (`S1` §7.5,
§7.11).

### Authority boundary

**Author** authors · **Checker** checks · **Task-Team Lead** may authorise the
controlled `WIP → Shared` transition **where the approved governance establishes
it** (`S1` §9.4). **Four lines — Module 2 holds the full role model.**

### Implementation-status warning

**One qualified observation exists, and it proves less than it appears to.** `S4`
§7 records `ARC-01` as *"Live equivalent observed"* — **a container observation,
not a workflow demonstration**. The other five containers were *"not observed as
a live direct coordination input at the inspected level"*.

**Do not label WIP as fully implemented. Do not label it as failing** —
*"absence of observation is not observation of absence"*.

### Likely question

**"Can another consultant see WIP?"**

> "Possibly — it depends on how permissions happen to be configured, and that's a
> platform question rather than a governance one. What I can tell you is that
> whether they *can* see it and whether they *may* use it are two different
> questions, and the second one is the one that matters."

**Second likely question — "If they can see it, can they use it?"**

> "No. Our BEP is exact about this: **visibility is not permission. Permission to
> read is not authorisation to rely.** Other parties do not rely on WIP unless
> there's an explicitly governed exception. So if you can open another team's
> work in progress, what you've got is access — not authority, and not a version
> anyone has said is fit for anything."

### Transition to Slide 5

> "So information sits in WIP until somebody deliberately does something about
> it. That deliberate act takes it to the next state."

### Evidence classification

**`CONTROLLED`** — the working-state definition; task-team responsibility; not
authorised for general reliance; versions are not exchanges; visibility is not
permission; membership confers no authority (`M4-S4-01`–`M4-S4-08`).
**`DECISION-RECORD`** — `01. WIP (Work in Progress)` maps to the state;
progression requires the governed transition (`M4-S4-09`, `M4-S4-10`).
**Controlled validation evidence** — the qualified `ARC-01` observation
(`M4-S4-12`).
**`INTERP`** — the responsibility chain as a four-line summary (`M4-S4-11`).
**`SYNTH`** — the required message (`M4-S4-14`).
**`IMPLEMENTATION UNVERIFIED`** — the WIP workflow as a whole (`M4-S4-13`).

### Delivery warning

**Do not draw or describe the route out of WIP.** *That* a governed route exists
may be named; **how it works is Slides 8–11.** If you start explaining the check
and the authorisation, you have spent Slide 5's time on Slide 8's content.

**And do not imply every task team has a live WIP area.** One container was
observed. **Five were not.**

---

## Slide 5 — Shared: controlled use for a defined purpose · 1.5 min

### Purpose

Explain Shared as a controlled state made available for a **defined project
purpose** — not as approval, publication or unrestricted reliance.

### Essential message

1. Shared is **available beyond the originating task team, for an identified
   purpose, after required checking and authorisation**.
2. **It has a stated purpose, and reliance is bounded by it.**
3. **Responsibility stays with the originator.**
4. **Shared is not approved.** Not published, not delivered, not accepted.
5. **Placing a file in `02. Shared` does not make it Shared.**

### Suggested wording

> "Shared is the state most people get wrong, and they get it wrong in one
> specific way: they hear it as *signed off*.
>
> Here's what it actually is. Information made available beyond the originating
> task team **for an identified purpose** — and, crucially, **after required
> checking and authorisation**. Both halves. Something checked but not authorised
> isn't Shared. Something authorised but unchecked shouldn't be.
>
> And it comes with a purpose attached. That's the part that bounds your
> reliance. If it was shared for coordination, you may coordinate against it. That
> doesn't make it suitable for setting out, or for pricing, or for anything else
> you might find convenient.
>
> Two more from our BEP, and they're the ones that protect the originator.
> **Availability is not consumption** — information being visible or present in a
> shared location doesn't mean any team has adopted it. Nobody consumes
> information by accident. And **consumption does not transfer technical
> ownership** — a receiving team that consumes a model does not acquire
> responsibility for its content. The originator remains responsible for what it
> produced.
>
> So the formulation I'd put on the slide: **Shared means authorised for a defined
> use. It does not mean approved for every use.**
>
> Last thing. We have an area called `02. Shared`, and it supports this state. But
> our structure decision says it plainly — **placement alone does not evidence
> that checking or authorisation occurred.** Dragging a file in doesn't share it.
> The check and the authorisation share it; the folder is just where it ends up."

### Shorter fallback

> "Shared means available beyond the originating team, for an identified purpose,
> after required checking and authorisation. Your reliance is bounded by that
> purpose. Responsibility stays with the originator — consumption doesn't
> transfer ownership. **Shared means authorised for a defined use; it does not
> mean approved for every use.** And putting a file in the Shared folder doesn't
> make it Shared."

### Controlled Harrismith source basis

| Statement | Source |
|---|---|
| *"made available beyond the originating task team for an identified purpose, **after required checking and authorisation**"* | **`S1` §6.3** |
| *"**Shared does not mean** published, accepted, or suitable for every purpose"* | **`S2` §1** |
| *"**Availability is not consumption**… Nobody consumes information by accident"* | **`S1` §6.5** |
| *"**Consumption does not transfer technical ownership**… The originator remains responsible for what it produced"* | **`S1` §6.5** |
| *"Coordination inputs come from appropriate Shared information, **not from uncontrolled WIP**"* | **`S1` §6.6** |
| *"**Placement alone does not evidence that checking or authorisation occurred**"* | **`S3` §3.3** |

### Permitted-use boundary

**For the stated purpose, and no further.** Coordination, controlled review, or
reference by another task team where the share established it. **Not approval,
not publication, not delivery, not acceptance.**

### Authority boundary

| | |
|---|---|
| **Task-Team Lead** authorises `T1` | **Established** — `S1` §9.4; `S2` §3.2 |
| That authority creates **no publication authority** | `S1` §9.7 |
| **BIM Coordinator** may use Shared information for coordination **without becoming the designer or originator** | `S1` §5.6, §8.10; `S2` §3.2 |
| **CDE Administration** may implement permissions; **it does not authorise the transition** | `S1` §6.9; `S2` §14 |

### Implementation-status warning

*"Only Architecture currently demonstrable as a Shared input"* (`S4` §7). **One
discipline, one observation.** Not a working multidisciplinary share, and not a
failure — nobody has checked the rest.

### Likely question

**"Does Shared mean approved?"**

> "No — and it's the single most common misreading in this whole area. Shared
> means it's been checked, someone with the authority authorised the share, and
> it's available beyond the originating team **for a stated purpose**. That's it.
> Our CDE strategy says it directly: Shared does not mean published, accepted, or
> suitable for every purpose. Approval — and more precisely acceptance — is a
> different act by a different party, and on this project nobody currently holds
> that authority."

**Second likely question — "Can Shared information be used for coordination?"**

> "Yes — and that's exactly what it's for. Our BEP says coordination inputs come
> from **appropriate Shared information, not from uncontrolled WIP**. But note the
> two qualifiers. *Appropriate* — for that coordination purpose. And using it for
> coordination carries no technical endorsement: including a container in a
> coordination cycle isn't design approval, and the coordinator doesn't become the
> originator by coordinating with it."

### Transition to Slide 6

> "So Shared gets information usefully into other people's hands, for a stated
> purpose. Publishing is a different act altogether — and this is where our
> project stops."

### Evidence classification

**`CONTROLLED`** — the definition; availability is not consumption; consumption
does not transfer ownership; coordination inputs come from Shared
(`M4-S5-01`–`M4-S5-08`).
**`SUPPORTING`** — *Shared does not mean published, accepted or suitable*; `T1`'s
authorising function (`M4-S5-09`, `M4-S5-10`).
**`DECISION-RECORD`** — `02. Shared` maps to the state; **placement evidences
nothing** (`M4-S5-11`, `M4-S5-12`).
**Controlled validation evidence** — only Architecture demonstrable
(`M4-S5-14`).
**`INTERP`** — the authority boundary summary (`M4-S5-15`).
**`SYNTH`** — the required message (`M4-S5-16`).

### Delivery warning

**The word *approved* must not pass your lips describing this state**, even
casually — *"so it's approved for coordination"* is exactly the collapse the
slide exists to prevent. Say **authorised for a defined use**.

**And do not teach the route in.** `T1`'s gate, checks and evidence are **Slide
10**. Naming the Task-Team Lead as the authorising function is enough here.

---

## Slide 6 — Published / Authorised: a separate decision and authority · 1.5 min

### Purpose

Explain Published / Authorised as a separate state requiring a **distinct
authorising function** — and show that this project cannot currently reach it.

### Essential message

1. **Shared does not automatically progress to Published.**
2. Publication requires an authority **distinct from sharing authority**.
3. **The publication-authorising function is UNRESOLVED**, and is **not**
   automatically the BIM Manager, BIM Coordinator, CDE Administrator or
   Architect.
4. **`T4` has no available authorising function; information remains Shared.**
5. **Published is not delivered, received, accepted or technically approved.**

### Suggested wording

> "Publication is a separate decision, and it needs a separate authority.
>
> What Published means, when it happens: information that has passed the required
> preparation, review and authorisation **for an identified purpose**. And our BEP
> has a table of what it doesn't mean, which I like a great deal. Not **perfect** —
> authorisation confirms fitness for a stated purpose, not absence of error. Not
> **forever final** — published information can be superseded. Not **universally
> suitable** — suitability is bounded by the purpose it was authorised for. And
> not **accepted by everyone** — acceptance is a separate act by an identified
> recipient.
>
> Now the part that matters for us. **The role holding publication and exchange
> authority is unresolved.** That's our BEP's own wording. And it goes further —
> it says the authority is **not** automatically held by the BIM Manager, the BIM
> Coordinator, the CDE Administrator, or the Architect. It stays TBD, and — I'll
> quote this because it's the best sentence in the document — the BEP **says so
> rather than defaulting it to whichever role is nearest**.
>
> The consequence is precise. Transition T4, Shared to Published, **has no
> available authorising function. Information remains Shared.**
>
> So this field on the slide stays empty. Not omitted — **empty**. Because leaving
> it out would suggest no authority is needed, and that's the opposite of true."

### Shorter fallback

> "Publication is a separate decision needing a separate authority. Published
> means authorised for an identified purpose — not perfect, not final, not
> universally suitable, not accepted. And on this project **the publication
> authority is unresolved** — explicitly not the BIM Manager, Coordinator, CDE
> Administrator or Architect. So T4 has no available authorising function, and
> **information remains Shared**. The authority field stays empty, not omitted."

### Controlled Harrismith source basis

| Statement | Source |
|---|---|
| *"passed the required preparation, review and authorisation **for an identified purpose**"* | **`S1` §6.7** |
| The **Published does not mean** table — perfect · forever final · universally suitable · accepted by everyone | **`S1` §6.7** |
| *"**Authorisation is purpose-specific.** Information authorised for one purpose is not thereby authorised for another"* | **`S1` §6.7** |
| *"**The role holding publication and exchange authority is UNRESOLVED**"*; not automatically the BIM Manager, BIM Coordinator, CDE Administrator or Architect | **`S1` §9.7** |
| *"**Platform write permission is not publication authority.** Being able to place a file in a published location is a software capability, **not a decision anyone made**"* | **`S1` §9.7** |
| *"`T4` therefore has **no available authorising function**, and information remains **Shared**"* | **`S2` §3** |
| *"**Putting a file in `03. Published` does not publish it.** Publication is a chain of governed events, not a location"* | **`S3` §3.4** |

### Permitted-use boundary

**Bounded by the authorised purpose** — and unreachable on this project.
`S4` §9: *"**No governed publication / exchange authority evidence was
established.**"*

### Authority boundary

**The field appears and is empty:**

> ### Publication-authorising function: **TBD / unresolved**

**Omitting it would imply no authority is required.** An empty field shows
accurately that authority **is required and unassigned**.

**No substitution.** Not the BIM Manager, not the Coordinator, **not the CDE
Administrator** — administrative capability is not authority.

### Implementation-status warning

**Not reached.** `T4` cannot proceed, so nothing downstream of it has been
implemented or observed. **This is not a technical fault** — it is governance
declining to complete a route it cannot authorise.

### Likely question

**"Who publishes the model?"**

> "On this project, **nobody** — and that's a recorded position rather than an
> oversight. The role holding publication and exchange authority is unresolved.
> It depends on the approved delivery arrangement, and that doesn't exist yet.
> Until it does, the authority stays TBD."

**Second likely question — "Can the BIM Manager publish it?"**

> "Not automatically, no. Our BEP names four roles that do **not** hold it by
> default, and the BIM Manager is the first of them — along with the BIM
> Coordinator, the CDE Administrator and the Architect. The BEP is deliberate
> about that: it says the authority stays TBD rather than defaulting it to
> whichever role is nearest."

**Third likely question — "Can the CDE Administrator publish it?"**

> "No — and this one is worth being firm about. The CDE Administrator can almost
> certainly *perform the action*: place a file, change a permission, execute a
> transmittal. Our BEP's line is that **platform write permission is not
> publication authority** — being able to place a file in a published location is
> a software capability, not a decision anyone made. Capability and authority are
> different things, and the administrator has the first without the second."

**Fourth likely question — "Does Published mean issued to the client?"**

> "No. Published means authorised for a defined purpose. **Delivery is a separate
> event** — an act with a recipient. Receipt is another event. Acceptance is a
> recipient's decision. Four different things, and our sources keep them apart
> deliberately. Something can be Published and never sent to anyone."

### Transition to Slide 7

> "One state left — and it's the one people expect me to point at a folder for."

### Evidence classification

**`CONTROLLED`** — the definition; the four *does not mean* rows;
purpose-specific authorisation; **the unresolved authority and the four excluded
roles**; platform permission is not publication authority
(`M4-S6-01`–`M4-S6-09`).
**`SUPPORTING`** — `T4` has no available authorising function; information
remains Shared (`M4-S6-10`, `M4-S6-11`).
**`DECISION-RECORD`** — placing a file in `03. Published` does not publish it;
no publication authority evidence established (`M4-S6-12`, `M4-S6-13`).
**`BLOCKED`** — the `Shared → Published` route (`M4-S6-14`).
**`UNRESOLVED`** — the authorising function (`M4-S6-15`).
**`SYNTH`** — the required message (`M4-S6-16`).
**`EXCLUDED`** — `TRN-E03` as the transition itself (`M4-S6-17`).

### Delivery warning

**Do not invent a holder, and do not accept one offered.** Someone will suggest
the BIM Manager or the client. **The BEP names four roles that do not hold it**;
naming a fifth from the floor is worse.

**Do not present the block as a defect.** It is governance declining to complete
a route it cannot authorise — the alternative is completing it by borrowing an
authority nobody granted.

**And `TRN-E03` is not the transition.** One line naming it as a later delivery
event that depends on `T4` is enough. **The event logic is Slides 8–11.**

---

## Slide 7 — Record / Retained: preservation without an Archive folder · 1.0 min

### Purpose

Explain Record / Retained as a **preservation and traceability obligation whose
implementation method remains unresolved**.

### Essential message

1. It concerns **preserving information, maintaining traceability and retaining
   evidence**.
2. **It is a state or obligation — not automatically a folder.**
3. **No `04 Archive` root is approved, required or created.**
4. **The retention method is TBD** — location, period, holder, implementation.
5. **One area maps to no state; one state maps to no area.**

### Suggested wording

> "Last state, and the one everyone expects me to point at a folder for.
>
> Record or Retained is about preserving what has to be preserved. Keeping
> traceability. Retaining evidence and authoritative records. Protecting
> information against uncontrolled change or loss. Our BEP already applies that in
> places you may not have noticed: superseded information is **marked as
> superseded, not deleted**. Prior versions and rejected submissions are
> **preserved** — history isn't overwritten to remove the failures, and those are
> usually the instructive part.
>
> Now — where does it go? And here's the honest answer: **we haven't decided.**
>
> Record / Retained is a **conceptual state and a retention requirement — not
> necessarily a folder**. Three of our documents say that independently. There is
> **no mandatory `04 Archive` root approved or required**, none has been created,
> and the retention approach is still to be decided. If you ever see an Archive
> folder appear, somebody invented it.
>
> So on this slide there are two panels. **The obligation** — preserve, protect,
> trace, retain the evidence. That's established. And **the method** — location,
> retention period, who holds it, how it's implemented. That panel is **empty**,
> and it stays empty, because filling it in would be me deciding something the
> project hasn't.
>
> One last thing, and it's a nice observation. We adopted four root areas and we
> have four states — and they **don't line up**. `0. Common Files` is an area
> that maps to no state. Record / Retained is a state that maps to no area. The
> mismatch isn't untidiness; it's what happens when you keep concepts and folders
> as separate things."

### Shorter fallback

> "Record / Retained is about preserving information, keeping traceability and
> retaining evidence — superseded material is marked superseded, not deleted. But
> it is **a state or obligation, not automatically a folder**. There's no
> `04 Archive` approved or required, none has been created, and the retention
> method — location, period, holder — is **TBD**. And note that our four areas and
> four states don't line up: one area maps to no state, one state maps to no
> area."

### Controlled Harrismith source basis

| Statement | Source |
|---|---|
| *"Historical evidence retained for traceability, **according to the project's retention approach**"* | **`S1` §6.3** |
| *"**Record / Retained is a conceptual state and a retention requirement — not necessarily a folder**"* | **`S2` §1** |
| *"**States are not folders**… no `04 Archive` project root requirement is confirmed… The project's retention approach is not yet defined"* | **`S1` §6.3** |
| *"Record / Retained is approved as a **conceptual requirement, not as a mandatory `04 Archive` root**"* | **`CGD-C06`** |
| *"Superseded information is marked as superseded, **not deleted**"* | **`S1` §7.10** |
| *"**Prior versions and exchanges are preserved for traceability.** History is not overwritten to remove failed submissions"* | **`S1` §9.9** |
| *"**History is not deleted because governance changed**"* | **`S1` §12.10** |

### Permitted-use boundary

**Traceability and later reference.** Not a working state, and not a substitute
for the record of what was decided — `S1` §12.10 keeps **Git** (technical change
history) and **the Governance & Decision Register** (decision history) as two
complementary histories, and *"neither substitutes for the other."*

### Authority boundary

| Question | Answer |
|---|---|
| Who determines retention requirements? | **Not established.** No controlled source assigns it |
| Who holds retained records? | **Not established** |
| Is there a records manager or archive administrator? | **No such function exists in the Harrismith set** |

**Invent none of them.**

### Implementation-status warning

**Nothing in `S4` addresses retention at all.** It is not verified, not observed,
and not demonstrated — because the method has not been decided, so there is
nothing to implement yet. **That is a sequence, not a failure.**

### Likely question

**"Where do retained records go?"**

> "We haven't decided. Record / Retained is a conceptual state and a retention
> requirement — three of our documents say so — and the retention approach is
> still to be defined. What's established is the **obligation**: superseded
> information is marked superseded rather than deleted, prior versions and
> exchanges are preserved, history isn't overwritten. Where and how that is
> implemented is an open decision."

**Second likely question — "Why don't we create an Archive folder now?"**

> "Because creating one would be making the decision by accident. Our structure
> decision is explicit: **no mandatory `04 Archive` root is approved or
> required**, and a later approved retention and technical implementation route is
> still needed. A folder created now would be configuration without a decision
> behind it — which is exactly the failure the model exists to prevent. And it may
> not turn out to be a folder at all."

**Third likely question — "Is Record / Retained already implemented?"**

> "No, and nothing claims it is. There's no verification evidence about retention
> in our validation record — because the method hasn't been decided, so there's
> nothing yet to verify. Parts of the obligation are already met in practice: our
> decision register and our version history preserve a good deal. But the CDE
> retention approach itself is open."

### Transition to Slide 8

> "So — four states, four different permissions to rely, and two of them we can't
> currently reach. Which brings us to the interesting question: what actually has
> to happen for information to move between them?"

### Evidence classification

**`CONTROLLED`** — the definition; states are not folders; no `04 Archive`
requirement confirmed; superseded not deleted; prior versions preserved; history
not deleted (`M4-S7-01`–`M4-S7-08`).
**`SUPPORTING`** — *a conceptual state and a retention requirement, not
necessarily a folder* (`M4-S7-09`).
**`DECISION-RECORD`** — `CGD-C06`; Record / Retained has no approved area;
`0. Common Files` is an area, not a state (`M4-S7-10`–`M4-S7-12`).
**`UNRESOLVED`** — retention approach, method, location, period, holder
(`M4-S7-13`).
**`SYNTH`** — the required message (`M4-S7-14`).
**`IMPLEMENTATION UNVERIFIED`** — retention is not addressed in any validation
record (`M4-S7-15`).
**`EXCLUDED`** — `04 Archive` in any form; any invented period or holder
(`M4-S7-16`).

### Delivery warning

**Do not say `04 Archive` aloud except to refuse it**, and never write it — not
as a proposal, an example, a placeholder or a future suggestion. **Naming it
creates the expectation the sources decline to create.**

**Do not let the method panel be filled.** *"Presumably it'll end up somewhere
in the CDE"* is a guess, and it will be repeated as a plan.

**And do not force the four states onto four areas.** The mismatch is a
controlled finding, and tidying it would invent a mapping nobody approved.

---

## Slide 8 — A transition is more than moving a file · 1.5 min

### Purpose

Explain that an information-state transition is a **governed change in permitted
use**, not a technical action performed in the platform.

### Essential message

1. **File movement ≠ authorised information-state transition.**
2. A user may upload, move, copy, rename, change permissions or create a version
   — **none of that establishes a transition**.
3. A transition needs **input, checks, gate conditions, an authorised decision,
   recorded evidence, and a changed permitted use**.
4. **Platform write access does not create governance authority.**
5. **Moving the file before the decision is not a substitute for the decision.**

### Suggested wording

> "We've named four states. Now — what actually moves information between them?
>
> And the first answer is what doesn't. **Moving a file is not a transition.**
>
> Our structure decision says it in one sentence: **movement or placement between
> platform areas must not be treated as sufficient evidence of a WIP-to-Shared,
> Shared-to-Published or other information-state transition.** Each transition
> requires the applicable governed checks, authorisation and evidence.
>
> Think about what you can technically do in the platform. Upload. Move. Copy.
> Rename. Change a permission. Save a new version. Every one of those is
> available to somebody right now. And **not one of them establishes** the
> required checks, the required evidence, transition authority, a changed
> permitted use, a changed suitability, publication, delivery, receipt or
> acceptance.
>
> So what does a transition actually consist of? Six things. A **required
> input**. **Checks**. **Gate conditions** — what must be true before it can
> proceed. An **authorised decision** by a function that holds that authority.
> **Recorded evidence**. And then, and only then, a **changed permitted use**.
>
> One more, because it's where this goes wrong in practice. CDE Administration
> configures the arrangement — that's their job, and they do it well. But our CDE
> strategy is precise: **CDE Administration implements governance; it does not
> define it.** Changing the software does not make a decision. And our validation
> record puts the same point at its sharpest: **being able to perform an action in
> the software says nothing about who was authorised to decide it.**"

### Shorter fallback

> "Moving a file is not a transition. Upload, move, copy, rename, permission
> change, new version — none establishes checks, evidence, authority or a changed
> permitted use. A transition is input, checks, gate conditions, an authorised
> decision, recorded evidence, then a changed permitted use. And CDE
> Administration implements governance; it doesn't define it."

### Controlled source basis

| Statement | Source |
|---|---|
| *"**Movement or placement between platform areas must not be treated as sufficient evidence**… Each transition requires the applicable governed checks, authorisation and evidence"* | **`CGD-C03`** — `docs/CDE-Structure-Governance-Decision.md` |
| *"Every arrow is a controlled transition. Each has its own trigger, its own criteria and its own responsible function"* | **`S2` §2** |
| *"**Permission ≠ authority**"*; *"CDE Administration implements governance; **it does not define it**"* | **`S2` §14**; `S1` §6.9 |
| *"Governance decision precedes configuration change"* | **`S2` §17** rule 1 |
| *"**Being able to perform an action in the software says nothing about who was authorised to decide it**"* | **`S4` §9** |

### Transition classification

**None yet — Slide 9 classifies.** This slide establishes only that a transition
is a **governed act**, not a technical one.

### Authority boundary

**Technical capability sits entirely outside the authority model.** Whoever can
perform the action and whoever may decide it are two different questions, and
only the second is governance.

### Evidence boundary

**Evidence is part of the transition, not a by-product.** The six-step anatomy
places **recorded evidence before the changed permitted use** — deliberately.

### Implementation-status warning

**The anatomy is teaching structure.** `S2` §2 and §3 establish that every
transition has a trigger, criteria, a responsible function and evidence; **the
six-step form is the presenter's arrangement of that**, and should be labelled so.

### Likely question

**"If I move the file into Shared, hasn't it transitioned?"**

> "No. What's happened is that a file is now in a different place. Whether the
> **information** is Shared depends on whether the required check happened and
> whether someone with the authority authorised the share. Our structure decision
> is explicit that placement must not be treated as sufficient evidence of a
> transition — and our BEP adds that placement alone doesn't evidence that
> checking or authorisation occurred. The move is a consequence of the decision,
> not the decision."

**Second likely question — "Does the platform log count as evidence?"**

> "It's *part* of the evidence, not the whole of it. Version history is on our
> evidence list — alongside checking records, authorisation records, review
> records and so on. What our BEP says is that evidence must be **sufficient and
> traceable**, and needn't come from any particular software function. And there's
> a specific caution worth knowing: **Git history proves authorship, not issue.**
> A log shows something changed. It doesn't show that anyone was authorised to
> change its permitted use."

### Transition to Slide 9

> "So a transition is a governed act. Which raises an obvious question — how many
> of them are there? And the answer surprises most people."

### Evidence classification

**`DECISION-RECORD`** — `CGD-C03`; platform ability is not authority
(`M4-S8-01`, `M4-S8-13`).
**`CONTROLLED`** — permission ≠ authority; decision precedes configuration
(`M4-S8-09`–`M4-S8-12`).
**`SUPPORTING`** — every arrow is a controlled transition; CDE Administration
implements but does not define (`M4-S8-05`, `M4-S8-11`).
**`INTERP`** — the six-step anatomy; the technical-action list (`M4-S8-06`,
`M4-S8-02`).
**`SYNTH`** — the required message (`M4-S8-15`).
**`EXCLUDED`** — movement as transition; a platform log as the governance
decision (`M4-S8-16`, `M4-S8-17`).

### Delivery warning

**Do not populate the anatomy here.** Six labels, no fields. **Slide 10 unpacks
one controlled example**, and filling the fields now spends its time.

**And keep the tone off CDE Administration.** They configure what was decided —
correctly, and usually well. **The point is that configuring is not deciding.**

---

## Slide 9 — The eight controlled steps, and the two that change state · 1.5 min

### Purpose

Correct the belief that `T1`–`T8` are eight sequential information-state
transitions.

### Essential message

1. **Only `T1` and `T4` change information state.**
2. `T2` is an **action**; `T3` is a **use or context**; `T5` and `T6` are
   **events**; `T7` is a **decision or status**; `T8` is a **rework route**.
3. **They are not a sequence**, and not a mandatory order.
4. **`T1`'s authority is established; `T4`'s is unresolved and blocked.**
5. Check, authorisation, review, coordination and acceptance are **five acts
   never collapsed into one another**.

### Suggested wording

> "You'll see eight identifiers in our CDE strategy — T1 to T8 — and the natural
> reading is that information marches through all eight. It doesn't.
>
> Our strategy says it plainly: **only T1 and T4 are information-state
> transitions.** T8 returns information to the originator's WIP for rework.
>
> So what are the others? **T2 is an action** — a receiving team deciding to
> consume shared information. The state doesn't change; the receiver's knowledge
> does. **T3 is a use or context** — including a container in a coordination
> cycle. Again, still Shared. **T5 and T6 are events** — delivery executed,
> receipt registered. The information stays Published. **T7 is a decision and
> status** — the recipient accepts or rejects for a stated purpose. Still
> Published. And **T8 is a rework route** — it takes information back to WIP,
> and then re-uses T1 or T4 on the way out.
>
> Which is why you won't see me draw these as a chain with seven arrows. That
> picture would assert four things that aren't true: one mandatory order, eight
> sequential transitions, automatic progression, and a complete operating route.
>
> One more from our strategy, and it's worth memorising. **Five acts that are
> never collapsed into one another**: check, authorisation, review, coordination,
> acceptance. **Checking does not authorise. Coordination does not approve
> design. Publication does not constitute acceptance.**"

### Shorter fallback

> "Eight identifiers, **two state transitions** — T1 and T4. T2 is an action, T3
> a use, T5 and T6 events, T7 a decision and status, T8 a rework route. They are
> not a sequence and not a mandatory order. T1's authority is established; T4's is
> unresolved. And five acts never collapse: check, authorisation, review,
> coordination, acceptance."

### Controlled source basis

| Statement | Source |
|---|---|
| *"Of the eight steps below, **only `T1` and `T4` are information-state transitions**. `T8` returns information to the originator's WIP for rework"* | **`S2` §3** |
| The kind, state-before, action, state-after and result of each step | **`S2` §3.1** |
| Trigger, required check, decision and performing function for each step | **`S2` §3.2** |
| *"**Checking does not authorise. Coordination does not approve design. Publication does not constitute acceptance.**"* | **`S2` §2** |
| *"Consumed, coordination input, delivered, received and accepted are **not** information states"* | **`S2` §3** |

### Transition classification

**The whole slide is the classification.** Reproduce `S2` §3.1's *kind* column
exactly — state transition · action · use / context · state transition · event ·
event · decision / status · rework.

### Authority boundary

| | |
|---|---|
| **`T1`** | **Task-Team Lead — established** |
| **`T3`** | BIM Coordinator, as a **process** function |
| **`T4`** | **UNRESOLVED — TBD** |
| **`T7`** | **UNRESOLVED — TBD / recipient-dependent** |

**Not every step has an authorising function**, and two of those that need one do
not have it.

### Evidence boundary

`S2` §3.3 records evidence per step. **It is not reproduced on this slide** —
Slide 10 unpacks one. **Naming that each step has its own evidence is enough.**

### Implementation-status warning

**No complete cycle has been demonstrated.** `S4` §8: *"PARTIALLY TRACEABLE /
NOT YET DEMONSTRATED AS A COMPLETE CYCLE."* **Say it if the table looks
authoritative** — a tidy eight-row register invites the assumption that all eight
run.

### Likely question

**"Why are `T1`–`T8` not eight transitions?"**

> "Because six of them don't change the information state. Our strategy is
> explicit — only T1 and T4 are information-state transitions. The others are
> different kinds of object: an action, a use, two events, a decision and status,
> and a rework route. They're all controlled, they all matter, and they're all
> recorded — but recording that a delivery happened doesn't change what state the
> information is in. It stays Published."

**Second likely question — "Are `T1`–`T8` performed in order?"**

> "No. They're identifiers for different controlled acts, not steps in a queue.
> Most information on most projects goes through T1 and stops there. T2 and T3
> happen or don't depending on whether anyone consumes or coordinates with it. T5
> to T7 only arise where a delivery event applies — and on this project they
> can't, because T4 is blocked. T8 only arises when something needs rework."

**Third likely question — "Why is `T8` not a state transition?"**

> "Because it's a **route** rather than a new kind of state change. T8 returns
> information to the originator's WIP for correction — and then, coming back out,
> it uses T1 or T4 again. It doesn't introduce a third way of changing state; it
> reuses the two we have. Which also means the T4 half of T8 is blocked in exactly
> the same way."

### Transition to Slide 10

> "Two of the eight change state. One of those two has an authority we can point
> at. Let's take it apart."

### Evidence classification

**`SUPPORTING`** — the eight classifications; the only-two statement; the five
never-collapsed acts; the non-states list (`M4-S9-01`–`M4-S9-13`).
**`CONTROLLED`** — `T1`'s authorising function (`M4-S9-14`).
**Controlled validation evidence** — no complete cycle demonstrated
(`M4-S9-15`).
**`INTERP`** — the required message; the grouping by kind (`M4-S9-16`,
`M4-S9-17`).
**`BLOCKED`** — `T4` (`M4-S9-11`). **`UNRESOLVED`** — `T7` (`M4-S9-12`).
**`EXCLUDED`** — any sequential rendering; `T8` as a third state transition
(`M4-S9-18`, `M4-S9-19`).

### Delivery warning

**Never draw the chain.** `T1 → T2 → … → T8` asserts a mandatory order, eight
transitions, automatic progression and a complete operating route. **A grouped
table is the required form**, and if a producer converts it to a flow, revert it.

**And do not teach the operational detail of `T2`, `T3`, `T5`, `T6` or `T7`.**
Classify them, explain each in a sentence, and move. **The coordination cycle is
Module 6; delivery-event mechanics are Module 5.**

---

## Slide 10 — Gates, authority and evidence · 1.5 min

### Purpose

Use **`T1`** as the worked example of a controlled transition — the only one
whose authorising function is established.

### Essential message

1. `T1`: **WIP → Shared**, triggered by information being ready for controlled
   sharing.
2. **Two checks** — task-team technical/content **and** information-quality /
   readiness.
3. **The Task-Team Lead authorises** — or another role explicitly allocated the
   function.
4. **Evidence: version history, checking record, share record.**
5. **`T1` authority creates no publication authority**, and complete live
   operation is **unverified**.

### Suggested wording

> "T1 is the one we can actually show you working as a design, because its
> authority is established.
>
> It starts in **WIP** and ends in **Shared**. The trigger is information being
> ready for controlled sharing. The **checks** are two, and both are required: a
> task-team technical and content check, and an information-quality and readiness
> check.
>
> The **gate conditions** come from our BEP's readiness list — is the required
> information present, is checking complete, is the container identity clear, are
> coordinates and reference context appropriate, are known interfaces and issues
> identified, is the **purpose of sharing known**, is the receiving audience
> understood, has the required authorisation occurred. Note there's no score in
> that list — our BEP says explicitly that no numeric threshold is set. Readiness
> is a judgement against the purpose, made by the role authorised to make it.
>
> The **authority** is the Task-Team Lead — or another role explicitly allocated
> that function by approved governance.
>
> And then the part that gets left off every diagram I've ever seen: the
> **evidence**. Version history. The checking record. The share or exchange
> record. Our BEP's position is that evidence must be **sufficient and
> traceable**, and needn't come from any particular software function.
>
> Two closing points. **Authorisation to share is not authorisation to publish or
> exchange** — our BEP's words, and it's the boundary the next slide depends on.
> And if it fails? Information **remains in, or returns to, WIP. No partial
> progression.**
>
> Last thing, and it's the honest one. All of that is the **governance
> definition**. Whether a complete T1 cycle has ever run in the platform is a
> different question — and the answer is that only Architecture is currently
> demonstrable as a Shared input. One container. Not a demonstrated cycle."

### Shorter fallback

> "T1: WIP to Shared. Trigger — ready for controlled sharing. Two checks —
> technical/content and information-quality/readiness. Gate — the readiness list,
> with no numeric threshold. Authority — **Task-Team Lead**. Evidence — version
> history, checking record, share record. Permitted use — suitable for the stated
> sharing purpose, and no further. Failure — back to WIP, no partial progression.
> And **authorisation to share is not authorisation to publish**."

### Controlled source basis

| Field | Source |
|---|---|
| Kind, states, action and result | **`S2` §3.1** |
| Trigger, required check, decision, performing function | **`S2` §3.2** |
| **Evidence and failure route** | **`S2` §3.3** |
| The eight readiness confirmations; *"no numeric quality thresholds are set"* | **`S1` §7.7** |
| *"The **Task-Team Lead** — or another role explicitly allocated that function by approved governance — authorises information to progress from WIP to Shared"* | **`S1` §9.4** |
| *"**Authorisation to share is not authorisation to publish or exchange**"* | **`S1` §9.4** |
| Evidence *"must be sufficient and traceable"*; *"**Git history proves authorship, not issue**"* | **`S1` §9.11**; `S2` §16 |
| The `TRN-E01` worked chain, suitability *"coordination use only"* | **`S2` §9** |

### Transition classification

**`T1` — information-state transition.** One of two.

### Authority boundary

**Seven distinctions**, and the seventh is the one to say aloud:

| # | |
|---|---|
| 1 | Author **produces** |
| 2 | Checker **checks** — *"checking is not authorising"* |
| 3 | Task-Team Lead **authorises `T1`** |
| 4 | CDE Administration **implements the permission arrangement** |
| 5 | BIM Coordinator **may consume for coordination**, without becoming originator |
| 6 | **None of those transfers technical responsibility** |
| 7 | **`T1` authority creates no publication authority** |

### Evidence boundary

**The evidence field appears and is not abbreviated away.** It must be sufficient
to demonstrate that the **required checks occurred**, the **authorised function
made the decision**, the **new permitted use was established**, and the
**originator and container remain traceable**.

**Two things that are not evidence of a transition:** folder location
(*"authorship is not inferred from folder location"* — `S1` §7.2) and Git history
alone (*"proves authorship, not issue"*).

### Implementation-status warning

```text
Governance definition   ≠   Live implementation evidence
```

**`T1` is `CONTROLLED GOVERNANCE` and `IMPLEMENTATION UNVERIFIED` at the same
time.** The `ARC-01` observation is a **container observation** — it does not
prove a complete `T1` cycle, and `S4` §8 records no complete traceable cycle at
all.

### Likely question

**"Who authorises `T1`?"**

> "The **Task-Team Lead** — or another role explicitly allocated that function by
> approved governance. That's our BEP's wording, and it's one of the few
> authorities in this area that is actually established. Which is why T1 is the
> example I can take apart for you."

**Second likely question — "What evidence is needed for `T1`?"**

> "Version history, the checking record, and a share or exchange record as
> appropriate. And the principle behind it matters more than the list: the
> evidence must be **sufficient and traceable**, and it needn't be produced by any
> particular software function. What it has to show is that the checks happened,
> that the authorised function decided, that a new permitted use was established,
> and that the originator and the container are still traceable."

**Third likely question — "Has `T1` been tested live?"**

> "Not as a complete cycle. Our validation record observed one container —
> Architecture — as demonstrable in a Shared context, and recorded that no
> complete traceable cycle was observed. So T1 is well-defined governance with
> partial observation behind it. I'd rather say that than imply we've run it."

### Transition to Slide 11

> "That's what a transition looks like when the authority exists. Now the one
> where it doesn't."

### Evidence classification

**`SUPPORTING`** — every `S2` §3 field: kind, states, trigger, check, decision,
function, evidence, failure route (`M4-S10-01`–`M4-S10-09`).
**`CONTROLLED`** — the readiness gate; no numeric threshold; the Task-Team Lead
authority; **authorisation to share is not authorisation to publish**; the
evidence principle; Git proves authorship not issue (`M4-S10-10`–`M4-S10-16`).
**Controlled validation evidence** — no complete cycle; `ARC-01` qualified
(`M4-S10-17`).
**`SYNTH`** — the required message (`M4-S10-18`).
**`IMPLEMENTATION UNVERIFIED`** — the complete `T1` cycle (`M4-S10-17`).
**`EXCLUDED`** — the evidence field omitted; folder location as evidence;
`ARC-01` as proof of a full cycle (`M4-S10-19`, `M4-S10-20`).

### Delivery warning

**The evidence field is the one that gets cut for space.** It is the field that
distinguishes a governed transition from a file move. **If something must go, cut
a gate condition, never the evidence.**

**And do not drift into the matrix.** Naming the four functions is enough;
**who holds which allocation across twenty-five process functions is Module 5**.

---

## Slide 11 — Why `Shared → Published` remains blocked · 1.5 min

### Purpose

Explain why **`T4`** cannot operate, and why **`TRN-E03`** is a separate and more
extensively blocked delivery event.

### Essential message

1. `T4` is the **Shared → Published / Authorised** state transition.
2. **Publication needs an authority distinct from sharing authority**, and it is
   **unresolved**.
3. **`T4` has no available authorising function. Information remains Shared.**
4. **`TRN-E03` is a delivery event**, blocked by **five** matters, not one.
5. **Published ≠ Delivered ≠ Received ≠ Accepted.**

### Suggested wording

> "Two panels, because these are two different things and everyone merges them.
>
> **Panel one — T4.** It's the state transition from Shared to Published or
> Authorised. It needs a delivery readiness review, and then a publication or
> exchange authorisation. And that authorisation needs an authority which our BEP
> records as **unresolved** — it depends on the approved delivery arrangement,
> which does not yet exist. So our strategy's conclusion is exact: **T4 has no
> available authorising function, and information remains Shared.**
>
> Notice the box on the slide with nothing in it. That's the
> publication-authorising function. It stays there and it stays empty, because
> leaving it out would suggest no authority is needed — and the opposite is true.
>
> **Panel two — TRN-E03.** This is a **delivery event**, not the transition.
> It *exercises* T4. And it's blocked by more than T4 is. Five matters, from our
> delivery schedule: publication authority, acceptance authority, **recipient
> identity**, **required formats**, and the **deliverable set**. So even if
> somebody resolved publication authority tomorrow, TRN-E03 would still be
> blocked on four other things.
>
> That's the point I'd take away. **Satisfying T4 alone would not automatically
> complete delivery.**
>
> And while we're here — four words that are not the same word. **Published** is a
> state. **Delivered** is an event. **Received** is an event. **Accepted** is a
> recipient's decision and status. Only the first is an information state; the
> other three are recorded *against* information whose state hasn't changed.
>
> Our delivery schedule has the sentence I'd close on: an entry that cannot
> proceed is recorded as blocked, because **assigning a plausible authority to
> make the row look finished would manufacture governance that does not exist.**"

### Shorter fallback

> "T4 — Shared to Published. Needs a publication authority distinct from sharing
> authority, and that authority is **unresolved**. So T4 has **no available
> authorising function** and **information remains Shared**. TRN-E03 is a separate
> **delivery event** that exercises T4, blocked by **five** matters: publication
> authority, acceptance authority, recipient identity, formats and deliverable
> set. Resolving T4 alone would not complete delivery. And Published, Delivered,
> Received and Accepted are four different things."

### Controlled source basis

| Statement | Source |
|---|---|
| *"`T4` therefore has **no available authorising function**, and information remains **Shared**"* | **`S2` §3.1, §11** |
| *"**The role holding publication and exchange authority is UNRESOLVED**"*; not automatically the BIM Manager, BIM Coordinator, CDE Administrator or Architect | **`S1` §9.7** |
| *"**Authorisation to share is not authorisation to publish or exchange**"* | **`S1` §9.4** |
| `TRN-E03` — **PROPOSED — BLOCKED PENDING GOVERNANCE DECISIONS**, with **five** blocking matters | **`S5` §5, §5.1** |
| *"**Assigning a plausible authority to make the row look finished would manufacture governance that does not exist**"* | **`S5` §5.1** |
| Published · Delivered · Received · Accepted as four distinct things | **`S2` §3, §13**; `S1` §10.11 |
| *"**No governed publication / exchange authority evidence was established**"* | **`S4` §9** |
| *"The block is represented deliberately and is a feature of the model, not a gap in it"* | **`S2` §11** |

### Transition classification

**`T4` — information-state transition, blocked. `TRN-E03` — delivery event,
blocked.** They are different controlled objects and **must not be used
interchangeably**.

### Authority boundary

**Two unresolved authorities, not one.** Publication / exchange authority (`T4`,
`S1` §9.7) and recipient acceptance authority (`T7`, `S1` §9.8). **Neither may be
assigned from the front of a room**, and `S1` §9.7 names four roles that do not
hold the first by default.

### Evidence boundary

`S2` §3.3 for `T4`: *"Delivery review record; publication authorisation record"*
— and *"**Currently blocked** — no authorisation can be given while the authority
is unresolved. Information remains Shared."* **The evidence cannot be produced,
because the decision cannot be made.**

### Implementation-status warning

**Nothing downstream of `T4` has been implemented or observed**, and `S4` §9
found **no publication or acceptance authority evidence**. **This is not a
technical fault** — it is governance declining to complete a route it cannot
authorise.

### Likely question

**"Who authorises `T4`?"**

> "Nobody, currently. The role holding publication and exchange authority is
> **unresolved** — it depends on an approved delivery arrangement that doesn't
> exist yet. And our BEP names four roles it is **not** automatically: the BIM
> Manager, the BIM Coordinator, the CDE Administrator and the Architect. It stays
> TBD rather than being defaulted to whichever role is nearest."

**Second likely question — "Is `T4` the same as `TRN-E03`?"**

> "No — and it's worth being precise. **T4 is a state transition**: Shared to
> Published. **TRN-E03 is a delivery event** — a controlled design review or
> project-facing exchange. TRN-E03 *exercises* T4; it isn't T4. And they're
> blocked differently: T4 by one matter, TRN-E03 by five."

**Third likely question — "Would assigning publication authority unblock
delivery?"**

> "It would unblock **T4** — the state transition. It would not unblock TRN-E03.
> That event is also waiting on recipient acceptance authority, recipient
> identity, required formats and a defined deliverable set. Four more decisions,
> none of them made. **Satisfying T4 alone would not automatically complete
> delivery.**"

**Fourth likely question — "Why can't the CDE Administrator publish it?"**

> "They can almost certainly perform the action — place the file, run the
> transmittal. Our BEP's line is that **platform write permission is not
> publication authority**: being able to place a file in a published location is a
> software capability, not a decision anyone made. And the BEP names the CDE
> Administrator specifically among the roles that do not hold that authority by
> default."

**Fifth likely question — "What happens while `T4` is blocked?"**

> "Information **remains Shared** — which is a perfectly usable state. Teams can
> coordinate against it, review it, reference it for the stated purpose. What
> can't happen is a project-facing exchange that depends on publication. So work
> continues; the route that needs an unheld authority doesn't."

### Transition to Slide 12

> "So the states and the transitions are defined, and two of them are waiting on
> decisions. What holds all of it together in practice? Properties and evidence."

### Evidence classification

**`SUPPORTING`** — `T4`'s no-available-function conclusion; the deliberate block;
the four distinct concepts (`M4-S11-01`–`M4-S11-06`).
**`CONTROLLED`** — publication authority unresolved; the four excluded roles;
sharing authority is not publication authority; platform write permission is not
publication authority (`M4-S11-07`–`M4-S11-11`).
**`SUPPORTING`** — `TRN-E03` blocked; the five blocking matters; the
manufacture-governance line (`M4-S11-12`–`M4-S11-15`).
**Controlled validation evidence** — no authority evidence established
(`M4-S11-16`).
**`INTERP`** — the empty-position requirement; the `T4`/`TRN-E03` distinction
table (`M4-S11-17`, `M4-S11-19`).
**`SYNTH`** — the required message (`M4-S11-18`).
**`BLOCKED`** — both `T4` and `TRN-E03`. **`UNRESOLVED`** — both authorities.
**`EXCLUDED`** — the identifiers used interchangeably; any invented authority,
recipient, format or deliverable (`M4-S11-20`).

### Delivery warning

**Two panels, never one object.** Merging `T4` and `TRN-E03` is the error the
slide exists to prevent, and a single merged diagram commits it silently.

**Do not accept an offered authority.** Someone will suggest a role. **Four are
already excluded by name**, and naming a fifth from the floor is worse.

**And do not describe the block as a system failure.** The software is fine. The
decision has not been made — and the model stopping is the model working.

---

## Slide 12 — Naming, revision, suitability and metadata support control · 1.5 min

### Purpose

Show what container properties **do for control** — identification, permitted
use, traceability, transition evidence — **without teaching a code that does not
exist**.

### Essential message

1. **Six properties, six different control questions.**
2. **A code identifies; it does not authorise, and it does not prove a process
   ran.**
3. **Metadata supports governance. It does not create authority.**
4. **Harrismith has none of these standards yet** — naming, revision, suitability
   and metadata schema are all **not established**.
5. **That is a decision still to be made, stated as a decision still to be made.**

### Suggested wording

> "Six properties. Each answers a different question, and that's the whole slide.
>
> **Name** — which container is this? Our BEP asks for **unambiguous identity**.
> **Version** — which stored platform occurrence? **Revision** — which managed
> issue, *where project convention requires one*. **Status** — what condition is
> declared? **Suitability** — what may this be relied on for? And **metadata** —
> which structured attributes support identity, filtering, responsibility, state,
> delivery purpose, interoperability?
>
> Now the distinctions, because these get merged constantly. A **filename may
> identify a container but does not prove its state**. A **platform version does
> not automatically create a revision** — our BEP's line is that a new platform
> version creates none of the others. A **revision does not authorise a
> transition**. **Status is not suitability.** **Suitability is not acceptance.**
> And **metadata supports governance; it does not create authority**.
>
> Then the four boxes on the right, and I want you to look at them properly.
>
> **Naming standard — not established. Revision convention — not established.
> Suitability codes — not established. Metadata schema — not established.**
>
> All four of our standards directories are empty. Our BEP says the Naming
> Standard **does not yet exist**, that **no final naming syntax is created**
> there — no field order, no separators, no permitted values — and that **no ISO
> 19650 filename pattern is imposed**. On classification it's just as direct: **no
> classification system is adopted.** Uniclass, OmniClass, MasterFormat — all
> unadopted.
>
> I'm not going to invent an example code to fill those boxes. If I put a
> plausible filename up there, half of you would write it down and it would become
> the project's naming standard by accident. **The boxes stay empty because the
> decision hasn't been made.**
>
> One sentence to take away, and it's the BEP's, not mine: the project's metadata
> requirements are **defined by governance, not inherited from whatever fields a
> tool happens to provide.**"

### Shorter fallback

> "Six properties, six questions: which container, which occurrence, which issue,
> what condition, what may I rely on it for, what attributes support control. A
> code **identifies**; it doesn't **authorise**, and it doesn't prove the process
> behind it happened. And Harrismith has **no naming standard, no revision
> convention, no suitability codes and no metadata schema** — all four
> directories are empty, and I'm not inventing one from the front of a room."

### Controlled source basis

| Statement | Source |
|---|---|
| *"Information containers require **unambiguous identity**"* | **`S1` §11.3** |
| Version = *"a platform or file history instance"*; revision = *"a controlled issue identifier, **where project convention requires one**"* | **`S1` §6.8** |
| Status = *"a workflow or decision condition"*; suitability = *"what the information may be used for"* | **`S1` §6.8** |
| *"A new platform version creates none of the others"* | **`S1` §6.8** |
| Metadata should support identity, filtering and search, responsibility, state and status, delivery purpose, interoperability | **`S1` §11.4** |
| *"**Platform folder placement alone is not identification** — a container must remain identifiable when moved, copied or exchanged"* | **`S1` §11.3** |
| *"**No final naming syntax is created here**"*; **no ISO 19650 filename pattern is imposed**; the Naming Standard *"does not yet exist"* | **`S1` §11.3** |
| *"**No classification system is adopted**"* — Uniclass, OmniClass, MasterFormat unadopted | **`S1` §11.4** |
| *"**Software-native metadata is not the project standard**"*; requirements *"defined by governance, not inherited from whatever fields a tool happens to provide"* | **`S1` §11.4** |
| Folder placement does not determine information state | **`CGD-C01`, `CGD-C03`** |
| The five properties named and kept distinct | **`S2` §13** |

### Governance-status boundary

**The concepts are governed. The codes are not.** `S1` §6.8 and §11.3–§11.4 are
**`CONTROLLED GOVERNANCE`** for what each property *means* and *must support*.
Every actual code set is **`UNRESOLVED`** — `standards/naming/`,
`standards/coordinates/`, `standards/templates/` and `standards/titleblocks/`
each contain only a `.gitkeep`.

**Say both halves.** "We have decided what naming must achieve; we have not
decided what naming looks like." Saying only the first implies a standard exists.

### Invention boundary

**No coded example is offered, from the front or from the floor.** Prohibited: an
ISO 19650 filename; a South African filename; a revision code; a suitability
code; a status code; a metadata field set; a model-container name; **any
fire-station example code**.

A conceptual placeholder such as `[identifier]` is permitted **only** if visibly
labelled illustrative. **Preferring none at all is the safer choice** — the
project has explicitly declined to create the thing an example would imply.

### Evidence boundary

The properties **contribute to** transition evidence — identity, originator,
version history, checked condition, declared permitted use, transition record,
traceability. That is a **supported interpretation** built from `S1` §9.11 and
`S2` §3.3.

**Metadata alone proves no authorisation.** A complete, well-formed set of
attributes is consistent with a transition that was never authorised.

### Likely question

**"So what naming convention should we use?"**

> "I can't answer that here, and I'd be doing you damage if I improvised one. Our
> BEP is explicit — the Naming Standard **does not yet exist**, and it deliberately
> creates **no field order, no separator set and no permitted-value list**. What I
> *can* tell you is what it has to achieve: unambiguous identity, origin and
> discipline context, information type, consistency for retrieval, and — this is
> the one people miss — it must stay identifiable **when the container is moved,
> copied or exchanged**. Folder placement is not identification."

**Second likely question — "Can't we just use ISO 19650 naming?"**

> "That's a governance decision, and it hasn't been made. Our BEP says in terms
> that **no ISO 19650 filename pattern is imposed**. Adopting one is available to
> the project — it just has to be *adopted*, by whoever holds that decision, and
> recorded. Not assumed because it's the familiar pattern."

**Third likely question — "Revit already has parameters. Isn't that our
metadata?"**

> "No — and the BEP has a sentence for exactly this: **software-native metadata is
> not the project standard.** The project's metadata requirements are defined by
> governance, not inherited from whatever fields a tool happens to provide. Those
> parameters may end up carrying the metadata. They don't get to *define* it."

**Fourth likely question — "If a file is named correctly, is it Shared?"**

> "No. Naming identifies; it doesn't declare state, and it certainly doesn't
> authorise the transition. Same trap as the folder — a correct name and a correct
> location can both be true of information nobody authorised anyone to rely on."

### Transition to Slide 13

> "So properties support control, and the codes behind them are decisions we
> haven't made. Which raises the obvious question — in what order do these
> decisions happen?"

### Evidence classification

**`CONTROLLED`** — the property definitions; version-does-not-create-revision;
naming principles; folder placement is not identification; no syntax created; no
ISO pattern imposed; no classification adopted; software-native metadata is not
the standard; **the four unestablished standards** (`M4-S12-01`,
`M4-S12-03`–`M4-S12-05`, `M4-S12-07`–`M4-S12-14`, `M4-S12-18`).
**`SUPPORTING`** — the five properties named and kept distinct in the CDE strategy
(`M4-S12-06`).
**`INTERP`** — the six control questions; the distinctions as a set; the
evidence-contribution list (`M4-S12-02`, `M4-S12-15`–`M4-S12-17`).
**`SYNTH`** — the required message (`M4-S12-19`).
**`UNRESOLVED`** is the *governance status* carried by `M4-S12-11`–`M4-S12-13` and
`M4-S12-18` — naming standard, revision convention, suitability code set,
metadata schema, classification system.
**`EXCLUDED`** — any invented code, syntax, field order, permitted value, code
set or schema; any claim that a correct name proves state, authorisation or
process (`M4-S12-20`).

### Delivery warning

**The four empty boxes are the slide.** If they are filled, softened, greyed into
a "future example" or replaced by a plausible pattern, the slide teaches the
opposite of what it exists to teach.

**Do not accept a naming convention offered from the floor.** Someone will have a
good one. It is still not this project's, and repeating it approvingly is how an
unadopted standard becomes the assumed standard.

**And do not let this become a coding-standards workshop.** It is 1.5 minutes on
what the properties *control*. The standard itself is a governance decision, made
elsewhere, by someone with the authority to make it.

---

## Slide 13 — Governance first; permissions and configuration follow · 1.0 min

### Purpose

State the **direction of authority** once, in one minute. **Not a re-argument of
Slides 1, 8 or 10.**

### Essential message

1. **Governance decision → process rule → permission or configuration →
   implementation evidence.**
2. **The reverse does not hold.** A platform setting creates no authority.
3. **CDE Administration implements governance; it does not create it.**
4. **A configuration that was never approved is a deviation, however competently
   it was applied.**
5. **Document, process and platform must stay aligned.**

### Suggested wording

> "One arrow, one minute.
>
> **Governance decides. The process records the decision. CDE Administration
> configures the platform. Evidence shows the two agree.** That's the direction of
> travel, and it only runs one way — a platform setting never creates governance
> authority.
>
> Two sentences from our BEP, and they're the whole slide.
>
> First: **CDE Administration implements governance; it does not create it.**
> Configuring folders, spaces, roles, permissions, workflow — all of that is
> implementation of something already decided. Holding administrative rights over
> a folder confers **the technical ability to change it and nothing more**.
>
> Second — and this is the one I'd write down: **a configuration that was never
> approved is a deviation, however competently it was applied.** Competence isn't
> the test. Authorisation is. And our BEP distinguishes a **deviation** — knowingly
> permitted — from a **non-conformance** — unintended. The difference is *intent
> and authorisation*, not severity.
>
> Which is why document, process and platform configuration have to stay aligned.
> Change one and not the others and you get, in the BEP's words, **a governance
> system that describes something the project is not doing** — the most common way
> controlled documentation ends up ignored.
>
> Three callbacks and I'm done. A CDE is a process, not a folder tree. A technical
> action is not a transition. Authority and evidence are required. Same principle,
> three times."

### Shorter fallback

> "Governance decides, process records, configuration implements, evidence
> confirms. Never backwards. **CDE Administration implements governance; it does
> not create it** — and **a configuration that was never approved is a deviation,
> however competently it was applied.** Admin rights give you the technical ability
> to change something and nothing more."

### Controlled source basis

| Statement | Source |
|---|---|
| *"**CDE Administration implements governance; it does not create it**"* | **`S1` §5.9** |
| *"**A configuration that was never approved is a deviation, however competently it was applied**"* | **`S1` §5.9** |
| *"Holding administrative rights over a folder, space or team confers **the technical ability to change it and nothing more**"* | **`S1` §5.9** |
| *"**Platform permission is not BEP authority**"*; administrator rights do not substitute for an appointment | **`S1` §5.9** |
| CDE Administration **holder: TBD** | **`S1` §5.9** |
| **Deviation** = knowingly permitted departure; **non-conformance** = unintended departure; *"the difference is intent and authorisation, not severity"* | **`S1` §12.6** |
| *"**Document, process and platform configuration must remain aligned**"*; misalignment produces *"a governance system that describes something the project is not doing"* | **`S1` §12.8** |
| *"This BEP does not itself authorise any live platform change"* | **`S1` §12.8** |
| Configuration is not complete because a setting was applied | **`S1` §12.9** |
| Access rights support but do not create authority | **`S1` §6.9**; `S2` §14 |
| Governance responsibility for change | **`S1` §12.1, §12.7** |
| Intended-versus-implemented must be evidenced | **`S2` §6, §17** |

### Authority boundary

**CDE Administration may** configure folders, spaces, roles, permissions and
platform workflow **where authorised**, implement approved changes, and check
configuration afterwards.

**CDE Administration does not** determine the information-state model, assign
publication authority, assign acceptance authority, or approve technical design.

**The holder is TBD.** No name is spoken, and no one in the room is identified as
holding it.

### Scope boundary

**This slide is direction, not verification.** *How* a project proves that
configuration matches governance — sampling, audit, review cycles — is **Module
6**. State the requirement; do not teach the method.

**And do not re-open Slides 1, 8 or 10.** They are named as callbacks, in three
lines, and then the slide ends. Re-arguing any of them costs the module its
closing time.

### Implementation-status warning

**Nothing here asserts that Harrismith's configuration is aligned.** `S2` §6
records intended-versus-implemented as a **four-layer** question, and `S4` found
most controls **`IMPLEMENTATION UNVERIFIED`**. The slide teaches the required
direction, not an achieved state.

**And `S1` §12.8 is explicit that the BEP does not itself authorise any live
platform change.** Nothing said here authorises anyone to configure anything.

### Likely question

**"We configured it before the document was written. Is that a problem?"**

> "It's a **deviation** — and that's a defined word here, not an insult. Our BEP
> separates a **deviation**, which is a knowingly permitted departure, from a
> **non-conformance**, which is unintended. The difference is intent and
> authorisation, not severity. What the BEP won't allow is the third option:
> pretending the sequence happened correctly. Record it, and decide whether to
> approve it or correct it."

**Second likely question — "The CDE Administrator has full rights. Doesn't that
make them the authority?"**

> "No — and the BEP addresses that role by name. Administrative rights confer
> **the technical ability to change something and nothing more**. **Platform
> permission is not BEP authority**, and administrator rights don't substitute for
> an appointment. They can change the folder. They can't decide who may rely on
> what's in it."

**Third likely question — "Who is the CDE Administrator on Harrismith?"**

> "**TBD.** It's recorded as unassigned, and I'm not going to fill it in from up
> here. That's the same discipline as the publication authority on the last slide
> — an unassigned role stays visibly unassigned."

### Transition to Slide 14

> "So: decide, record, configure, evidence — in that order. Which means for
> Triviron the useful question isn't *how do we set up the CDE*. It's *what do we
> have to decide before we're allowed to*."

### Evidence classification

**`CONTROLLED`** — implements-not-creates; the CDE Administration responsibility
list; the never-approved-configuration sentence; administrative rights confer
technical ability only; platform permission is not BEP authority; holder TBD;
deviation versus non-conformance; alignment of document, process and
configuration; the BEP authorises no live change; configuration is not complete
because a setting was applied; the responsible governance function
(`M4-S13-03`, `M4-S13-05`–`M4-S13-14`).
**`SUPPORTING`** — access follows approved responsibility, divergence recorded as
a deviation; intended-versus-implemented as a four-layer question (`M4-S13-15`,
`M4-S13-16`).
**`INTERP`** — the four-step arrow as a single model; the refused reverse arrow;
the may/does-not table (`M4-S13-01`, `M4-S13-02`, `M4-S13-04`).
**`SYNTH`** — the required message (`M4-S13-17`).
**`DECISION-RECORD`** — Harrismith's own alignment is **`IMPLEMENTATION
UNVERIFIED`** (`M4-S13-18`).
**`EXCLUDED`** — any named CDE Administrator; any claim that configuration
confers authority; any claim that Harrismith's configuration has been verified as
aligned; any authorisation of a live platform change (`M4-S13-19`).

### Delivery warning

**One minute. It is the only slide in the module that can be delivered in one
minute, and the two after it need their time.** If Slide 12 ran long, recover
here — not on Slide 14.

**The reverse arrow must stay visibly refused.** A diagram showing only the
forward chain is a diagram someone can read in either direction.

**And do not name anyone.** Not the CDE Administrator, not the publication
authority, not "well, realistically it would be…". The slide's own subject is why
that instinct is the failure mode.

---

## Slide 14 — What Triviron must define before configuring its CDE · 2.0 min

### Purpose

Convert the module into **the decisions a future project must make before it
configures anything** — as **questions only**.

### Essential message

1. **No Triviron facts exist.** Nothing here asserts anything about that project.
2. **Five decision areas**: purpose and scope; states and permitted use;
   transitions, gates and authority; properties; configuration and evidence.
3. **Two questions appear verbatim and stay unanswered** — publication authority
   and acceptance authority.
4. **Configure only after the decisions are made.**
5. **`CDE configuration basis — not yet established`** is the correct current
   position, not a failure.

### Suggested wording

> "Last slide, and it's entirely questions. I want to be clear why.
>
> **We hold no facts about Triviron.** No jurisdiction, no project type, no
> client, no procurement route, no appointments, no platform, no folder structure,
> no states, no naming convention, no dates. If I put an answer on this slide I'd
> be inventing a project. So: questions.
>
> **Purpose and scope.** What information must the CDE govern? Which teams and
> organisations? Which uses must be controlled? Which phases? What evidence will
> show the process actually operates?
>
> **States and permitted use.** Which states will you adopt? What is each one
> *for*? Who may rely on each? Is each conceptual, physical, or both? Which folder
> relationship implements each one — and this is the Harrismith lesson —
> **how will you stop folder location being mistaken for state?**
>
> **Transitions, gates and authority.** Which actions actually change state? Who
> initiates, who checks, who authorises? And then two questions I want on the
> record.
>
> **Who holds publication authority?**
>
> **Who holds acceptance authority?**
>
> I'm not going to answer either. Harrismith has both recorded as **unresolved**,
> and those are precisely the two that a new project assumes into existence in
> week one. What happens when an authority is unassigned? And which transitions
> must stay blocked?
>
> **Properties.** What naming standard, what revision convention, which status and
> suitability codes, what metadata schema, who assigns and checks them — and how
> will you keep the code distinct from evidence that the process behind it
> happened?
>
> **Configuration and evidence.** Which platform? Who may configure it? How is a
> change authorised? How are deviations recorded? How will you verify that
> configuration matches governance, and who may declare the CDE ready for use?
>
> One sentence to close on: **configure the platform only after the states,
> purposes, authorities, gates and evidence requirements have been decided.**
>
> And the honest status line for a project at this point — **CDE configuration
> basis: not yet established.** That's not a warning. It's simply where you are
> before the decisions are made, and saying so is better than a configured
> platform that nobody authorised."

### Shorter fallback

> "Questions only — we hold no Triviron facts. Five areas: what the CDE governs;
> which states and what each permits; which actions change state and **who
> authorises** them; naming, revision, suitability and metadata; and platform
> configuration with the evidence that it matches governance. Two questions I
> won't answer: **who holds publication authority, and who holds acceptance
> authority.** Both are unresolved on Harrismith, and both get assumed on new
> projects. Configure after the decisions — not before. Right now: **CDE
> configuration basis, not yet established.**"

### Controlled source basis

| Statement | Source |
|---|---|
| Publication / exchange authority **unresolved** | **`S1` §9.7**; `S2` §3.1, §11 |
| Recipient acceptance authority **unresolved** | **`S1` §9.8**; `S2` §3 |
| States require defined purpose and permitted reliance | **`S1` §6.3**; `S2` §1 |
| Folder location does not determine state | **`S1` §6.1**; **`CGD-C01`, `CGD-C03`** |
| A transition requires initiation, checking, authorisation, record and evidence | **`S2` §2, §3.3** |
| Blocked routes are recorded as blocked rather than completed with a plausible value | **`S2` §19**; `S5` §5.1 |
| Naming, revision, suitability and metadata requirements are governance decisions | **`S1` §11.3, §11.4** |
| Configuration implements governance; unapproved configuration is a deviation | **`S1` §5.9, §12.6** |
| Document, process and configuration must remain aligned and be evidenced | **`S1` §12.8**; `S2` §6, §17 |
| Structural adoption carries conditions that must be satisfied before reliance | **`CGD-C01`–`CGD-C08`** |
| Demonstrability is judged on evidence, not intent | **`S4` §7, §11** |

**Every row supports the *question*. None supplies an answer for Triviron.**

### Invention boundary

**No Triviron project fact is asserted anywhere on this slide or in these notes.**
Prohibited: jurisdiction; project type; client; asset; procurement route;
appointment structure; named roles; CDE platform; folder structure; information
states; naming convention; suitability codes; metadata schema; dates; team names;
any claim of live implementation.

**And no question is answered by implication.** "Who holds publication authority?
— well, usually the…" completes the question. The slide's value is that it does
not.

### Authority boundary

**The two compulsory questions appear verbatim and unanswered:**

> **Who holds publication authority?**
> **Who holds acceptance authority?**

`S1` §9.7 names four roles that do **not** hold the first by default — BIM
Manager, BIM Coordinator, CDE Administrator, Architect. **Do not name a fifth**,
and do not accept one offered from the floor. A suggestion repeated approvingly
from the front of a room is how an unassigned authority becomes an assumed one.

### End-state boundary

**`CDE configuration basis — not yet established`** is a **neutral future
position**, not a failure warning and not a criticism of Harrismith. It is the
correct status for any project that has not yet made these decisions, and it is
the status Triviron will start from.

**Do not soften it into a plan, a date or a commitment.** No sequencing, no
"by the end of…", no ownership. Those are decisions, and this slide asks
questions.

### Likely question

**"Can you give us your recommended answer to any of these?"**

> "Not from here, no — and that's a discipline rather than modesty. Every one of
> these is a decision that belongs to the project's governance, and an answer
> offered from the front of a room has a way of becoming the answer. What I'd
> point at instead is the Harrismith evidence: the two authorities that are still
> unresolved are the two that stopped a route working. Start there."

**Second likely question — "Isn't this just a long list of things we don't
know?"**

> "It's a list of things that have to be *decided*, which is different. Most of
> them aren't hard — they're just usually skipped, because the platform lets you
> start without them. Then six months later nobody can say what Shared means or
> who published something. Twenty minutes of decisions now, or that."

**Third likely question — "Which of these matters most?"**

> "The two authority questions. Everything else can be corrected later without
> much damage — a naming convention can be migrated, a folder can be restructured.
> An authority that was never assigned means information was relied on without
> anyone deciding it could be. That's the one that doesn't correct cleanly."

**Fourth likely question — "How long does all this take?"**

> "I genuinely don't know, and I'd be guessing at a number that people would plan
> against. What I can say is that Harrismith reached a governed, conditionally
> adopted structure with two authorities still open — so the decisions are not all
> the same size, and the ones left open were the ones nobody had the standing to
> make."

### Closing

> "That's Module 4. Four states, two of them currently unreachable. Eight
> controlled steps, two of which change information state. And four coding
> standards everyone assumes exist, which don't. **The CDE is the process. The
> folders are where it shows up.**"

**Then stop.** Do not add a summary of the whole programme, a preview of Module
5, or a reassurance that Harrismith is nearly finished.

### Evidence classification

**`INTERP`** — the evidence boundary; the five decision areas as a structure; the
ordering of the questions; the folder-versus-state question; the
code-versus-evidence question; the end state (`M4-S14-01`–`M4-S14-11`,
`M4-S14-14`, `M4-S14-15`).
**`CONTROLLED`** — the two unresolved authorities and the four excluded roles
(`M4-S14-12`).
**`SYNTH`** — the required closing message (`M4-S14-13`).
**No status class is asserted for Triviron at all** — the project has no entry in
any register, because no controlled source describes it. It is recorded in
[`source-map.md`](source-map.md) §8.5 as **undescribed**, which is a different
thing from unresolved.
**`EXCLUDED`** — any Triviron fact; any answered question; any named authority;
any recommended convention, code set, schema or platform; any implementation
claim; any ISO conformity claim (`M4-S14-16`).

### Delivery warning

**Questions only. Two full minutes of them.** The instinct to be helpful — to
answer one, to offer "what most projects do", to suggest a role — is the single
failure mode of this slide, and it undoes the module.

**The two authority questions must be spoken, not skimmed.** They are the ones
the audience will otherwise assume, and they are why Harrismith's `T4` is
blocked.

**And the end state stays as written.** `CDE configuration basis — not yet
established`. Not "in progress", not "being developed", not a date.
