# Module 4 — Speaker Notes, Slides 1–7

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

## Slides 8–14

**Not developed.** No notes exist. Developing them is a later increment.
