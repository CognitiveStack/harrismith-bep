# NPRA-001 — Training Baseline Naming and Presentation Control Readiness Assessment

| Field | Value |
|---|---|
| Assessment ID | **NPRA-001** |
| Document status | **CONTROLLED ASSESSMENT** |
| Classification | **ASSESSMENT RECORD — NOT A GOVERNANCE DECISION** |
| Assessment date | **2026-08-02** |
| Source | **Orchestrator-directed `Authority: None` assessment — Increment 8H-D** |
| Assessment subject | **NPC-001 — Training Baseline Naming and Presentation Control Candidate** |
| Assessment scope | **Readiness of NPC-001 for consideration by AG-005 only** |
| **Authority** | **None** |
| Assessment function | **Non-decisional readiness assessment under the orchestrator-directed three-record workflow** |
| Candidate-coordination function | **Training Baseline Publication Owner under AG-004** |
| Future decision function | **Training Publication Naming and Presentation Approver under AG-005** |
| Candidate source repository state | `09c04ff9d84e79d95317206b393e217e3fb209a5` |
| Candidate preparation commit | `08aa680026aebf9bcd7ab67fdc7a46bee48310a3` |
| Documentary correction commit assessed | `5075677224587e6291ac880d5af6a464471b48fc` |
| **Assessment outcome** | **READY FOR AG-005 DECISION WITH CONDITIONS** |
| Status | **ASSESSMENT COMPLETE — ELIGIBLE FOR A SEPARATE AG-005 DECISION AFTER EXACT REVIEW; AG-005 NOT EXERCISED** |
| Phase / increment | Phase 8 — Publication Planning; Increment 8H-D |
| Training basis | **TA-02** — simulated role participation |

> **None of the three commits above is the publication-package commit.** **No
> publication-package commit is proposed or pinned.**

> **PUBLICATION REMAINS NOT AUTHORISED — PUBLICATION HOLD ACTIVE.**

---

## 0. Assessment boundary

> ## **NPRA-001 IS AN ASSESSMENT, NOT A DECISION.**

**NPRA-001 carries `Authority: None`.** It:

- **does not approve, reject, defer or conditionally approve NPC-001**;
- **does not exercise AG-005**;
- **does not establish a naming or presentation control**;
- **does not satisfy C5**;
- **does not satisfy P6 step 3**;
- **does not authorise implementation**;
- **does not establish a project-wide standard**;
- **does not authorise PE-3**;
- **does not authorise publication**.

> **Readiness is eligibility to be decided, not a decision.** The outcome at §23
> states that NPC-001 **may be put to AG-005**, subject to an exact review of
> this assessment. **It does not state what AG-005 should decide.**

---

## 1. What this assessment is

**A controlled `Authority: None` readiness assessment of NPC-001**, performed as
the **second record** of the orchestrator-directed three-record workflow:

```text
NPC-001                  candidate               Authority: None   ✓ exists
        ↓
NPRA-001                 readiness assessment    Authority: None   ✓ this record
        ↓
AG-005 decision          approve / reject / defer / approve with conditions
                                                                   ✗ not taken
```

**Only the assessment occurs in Increment 8H-D.**

### 1.1 Finding classifications used

Following the PRA-001 and PRA-002 structural precedent, each finding separates:

| Layer | Meaning |
|---|---|
| **Repository fact** | What a controlling record states |
| **Mechanical verification** | What was independently computed from repository content |
| **Governance interpretation** | What the records mean read together |
| **Unresolved matter** | What no record determines |
| **Readiness consequence** | Whether it affects eligibility for an AG-005 decision |
| **Implementation consequence** | Whether it affects assembly, pinning or later events |
| **PE-event consequence** | Whether it affects any PE event |

### 1.2 The three kinds of finding

| Kind | Meaning |
|---|---|
| **PASS** | Adequate for an AG-005 decision as it stands |
| **PASS WITH DECISION CONDITION** | Adequate for consideration, **but the later AG-005 decision must record something explicitly**. Recorded at §22 as `A1`…`An` |
| **BLOCKER** | Prevents a controlled decision until NPC-001 is amended or a record is created |

**No BLOCKER is recorded by this assessment** (§20).

### 1.3 What was not treated as evidence

Per the assessment method, **none of the following was treated as independent
evidence**:

- NPC-001's own §13 collision and ambiguity table;
- the Increment 8H-C completion report;
- the Increment 8H-C-R exact review;
- the Increment 8H-C-R-A completion report;
- the Increment 8H-C-R-A-R corrective review;
- the orchestrator prompt directing this increment.

**Those records identified investigation targets.** **Every finding below was
established afresh from repository records and from mechanical verification
performed during this increment.** Where a prior review reached the same
conclusion, that agreement is noted but is not the basis of the finding.

---

## 2. Assessment input snapshot

| Input | Exact value |
|---|---|
| Repository branch | `main` |
| Current assessed commit | `5075677224587e6291ac880d5af6a464471b48fc` |
| Worktree at assessment | **Clean** |
| Candidate identifier | **NPC-001** |
| Candidate classification | **PROPOSED GOVERNANCE — NOT APPROVED** |
| Candidate status | **CANDIDATE PREPARED — NOT ASSESSED — NOT APPROVED** |
| Candidate Authority | **None** |
| Candidate source state | `09c04ff9d84e79d95317206b393e217e3fb209a5` |
| Candidate preparation commit | `08aa680026aebf9bcd7ab67fdc7a46bee48310a3` |
| Current correction commit | `5075677224587e6291ac880d5af6a464471b48fc` |
| **AG-004** | **Established**; coordination function; not exercised as approval |
| **AG-005** | **Established; NOT EXERCISED** |
| **C5** | **CARRIED FORWARD** |
| **P6 step 3** | **PENDING** |
| Project-wide standards | **Not established** — naming, coordinate, titleblock, template |
| Package artefact | **None** |
| **Publication** | **NOT AUTHORISED** |
| **Publication hold** | **ACTIVE** |

> **No publication-package commit is pinned**, and **none is proposed**. The
> three commits recorded in this assessment's header identify **repository
> states considered**, not package commits.

---

## 3. Independent fifteen-file verification

**Mechanical verification performed during this increment**, by extracting every
filename from NPC-001 §7 and computing against it.

| # | Verification | Method | Result |
|---|---|---|---|
| 1 | Exactly seven PDF filenames | Extension count | **7** |
| 2 | Exactly one manifest filename | Extension count | **1** |
| 3 | Exactly seven Markdown companion filenames | Extension count | **7** |
| 4 | Exactly fifteen total | Deduplicated count | **15** |
| 5 | Uniqueness case-sensitively | `sort -u` | **15 distinct** |
| 6 | Uniqueness case-insensitively | Lower-cased `sort -u` | **15 distinct** |
| 7 | Filename lengths | Measured each | **21–52 characters**; all within the 120 limit |
| 8 | Grammar compliance — renditions | Pattern `^HFS-TB0P1-[A-Z0-9-]+-AWC\.pdf$` | **7 of 7** |
| 9 | Grammar compliance — manifest | Pattern `^HFS-TB0P1-MANIFEST-AWC\.json$` | **1 of 1** |
| 10 | Grammar compliance — companions | Pattern `^HFS-TB0P1-[A-Z0-9-]+-AWC-SOURCE\.md$` | **7 of 7** |
| 11 | Permitted-character compliance | Stem scanned for `[^A-Z0-9-]` | **0 violations** |
| 12 | Separator compliance | Spaces, underscores, leading/trailing/consecutive hyphens | **0 / 0 / 0 / 0 / 0** |
| 13 | Extension compliance | Lowercase, class-fixed | **15 of 15** |
| 14 | Single period per filename | Field count on `.` | **0 names with ≠ 1 period** |
| 15 | Token-order compliance | Token 1 and token 2 on every name; terminal token per class | **`HFS` then `TB0P1` on 15 of 15**; `AWC` terminal on all 8 authoritative; `AWC-SOURCE` terminal on all 7 companions |
| 16 | One rendition and one companion per source | Seven token pairs | **7 renditions, 7 companions, bijective** |
| 17 | Companion→rendition transform | Replaced `-SOURCE.md` with `.pdf`, tested membership | **7 of 7 yield a listed rendition** |
| 18 | No manifest companion | Searched for `MANIFEST…SOURCE` | **0** |
| 19 | `SOURCE` only on subordinate names | Counted `SOURCE` names not ending `.md` | **0** |
| 20 | Source paths exist at current HEAD | `git cat-file -e HEAD:<path>` ×7 | **7 of 7 EXIST** |
| 21 | No source path duplicated | Deduplication on the §6 map | **0 duplicates** |
| 22 | No document token reused | Deduplication on the §6 map | **0 duplicates; 7 tokens** |

**Measured lengths:**

| Chars | Filename |
|---:|---|
| 21 | `HFS-TB0P1-BEP-AWC.pdf` |
| 27 | `HFS-TB0P1-BEP-AWC-SOURCE.md` |
| 27 | `HFS-TB0P1-MANIFEST-AWC.json` |
| 32 | `HFS-TB0P1-IM-RESP-MATRIX-AWC.pdf` |
| 38 | `HFS-TB0P1-IM-RESP-MATRIX-AWC-SOURCE.md` |
| 40 | `HFS-TB0P1-INFO-DELIVERY-SCHEDULE-AWC.pdf` |
| 40 | `HFS-TB0P1-MODEL-INFO-RESP-MATRIX-AWC.pdf` |
| 45 | `HFS-TB0P1-CDE-WORKFLOW-STATE-STRATEGY-AWC.pdf` |
| 46 | `HFS-TB0P1-COORDINATION-REVIEW-STRATEGY-AWC.pdf` |
| 46 | `HFS-TB0P1-GOVERNANCE-DECISION-REGISTER-AWC.pdf` |
| 46 | `HFS-TB0P1-INFO-DELIVERY-SCHEDULE-AWC-SOURCE.md` |
| 46 | `HFS-TB0P1-MODEL-INFO-RESP-MATRIX-AWC-SOURCE.md` |
| 51 | `HFS-TB0P1-CDE-WORKFLOW-STATE-STRATEGY-AWC-SOURCE.md` |
| 52 | `HFS-TB0P1-COORDINATION-REVIEW-STRATEGY-AWC-SOURCE.md` |
| 52 | `HFS-TB0P1-GOVERNANCE-DECISION-REGISTER-AWC-SOURCE.md` |

> **All twenty-two mechanical verifications returned the expected result.** This
> verification supports questions 2, 3, 4, 7, 8 and 13. **It does not by itself
> establish governance adequacy**, which each question addresses separately.

---

## 4. The eleven AG-005 candidate-precondition matters

**AG-005 §6 requires a controlled candidate covering eleven minimum matters
before the approval authority may be exercised.** Each is assessed below.

| # | Matter | NPC-001 § | Content present | Mechanically complete | Substantively adequate | Unresolved issue | Readiness consequence | AG-005 can resolve later | Amendment required first |
|---|---|---|---|---|---|---|---|---|---|
| 1 | Seven `PDF/A-2b` renditions | §7.1, §3, §5.1 | Seven named renditions and their grammar | **Yes** — 7 verified | **Yes** | None | **PASS** | n/a | **No** |
| 2 | One authoritative `UTF-8 JSON` manifest | §7.2, §5.2, §11 | One named manifest; eleven-item identity rule | **Yes** — 1 verified | **Yes** | None | **PASS** | n/a | **No** |
| 3 | Seven subordinate Markdown companions | §7.3, §5.3, §12 | Seven named companions; byte-faithfulness rule | **Yes** — 7 verified | **Yes** | None | **PASS** | n/a | **No** |
| 4 | Companion-to-rendition relationships | §8, §8.1 | Six rules; seven-row reconciliation | **Yes** — 7 pairs, transform verified | **Yes** | None | **PASS** | n/a | **No** |
| 5 | PM-1 proposed child container | §9 | Exact name; eight controls; non-effect block | **Yes** | **Yes, with one interpretive point** | Container form differs from filename grammar; §9 explains but does not decide | **PASS WITH DECISION CONDITION** — `A3` | **Yes** — §4 items 11, 12 | **No** |
| 6 | Package identity | §4, §10.1 item 7, §11 items 6, 8 | `HFS-TB0P1` defined and required in filenames, markings and manifest | **Yes** | **Yes** | None as to identity itself | **PASS** | n/a | **No** |
| 7 | Baseline / version / status representation | §4, §5.4 rule 13, §11.1 | `TB0P1` baseline; `AWC` status | **Yes** | **Adequate for consideration; two carrier questions open** | `TB0P1` carries PM-4 fields 2 and 4 without saying so; `AWC` adds PM-4 field 5 to the filename | **PASS WITH DECISION CONDITIONS** — `A1`, `A2` | **Yes** — §4 item 13 names *version* and *status* expressly | **No** |
| 8 | Filename characters, separators, case, extensions, ordering | §5.4 | Fourteen numbered rules | **Yes** — all verified against the fifteen names | **Yes** | None internal to filenames | **PASS** | n/a | **No** |
| 9 | Minimum presentation markings | §10.1, §10.2, §10.3 | Nine-item block; footer; five limitations | **Yes** | **Yes** | Items 8 and 9 unpopulatable until pinning and generation — recorded as deliberate | **PASS** | n/a | **No** |
| 10 | Collision and ambiguity risks | §13 | Thirteen statements; longest-name measure; untested-platform caveat | **Yes** | **Yes, subject to independent verification** | The candidate assesses itself; platform untested | **PASS** — verified independently at §3 and §16; platform carried as residual `R1` | n/a | **No** |
| 11 | Package-specific vs project-wide distinction | §14, §4, §5.4 r14, §6, §9, §10.3 | Categorical block; `NOT ESTABLISHED`; six bars | **Yes** | **Yes** | Residual de facto reuse risk on common tokens | **PASS WITH DECISION CONDITION** — `A4` | **Yes** — §4.1 | **No** |

**Assessment finding on coverage.** **All eleven matters are covered with
substantive, non-placeholder content.** Four matters (5, 7, 10, 11) carry
interpretive points; **three of those four give rise to decision conditions**
(`A1`–`A4`) and one (matter 10's platform limb) is a residual technical
prerequisite (`R1`). **None is a gap in coverage**, and **none requires
amendment of NPC-001 before AG-005 may consider it.**

---

## 5. Question 1 — candidate completeness

> **Does NPC-001 cover all eleven AG-005 candidate-precondition matters?**

### Finding

> ## **YES, WITH QUALIFICATIONS**

**Coverage.** Each of the eleven matters maps to identified NPC-001 sections
(§4), and every mapped section contains substantive content rather than a
placeholder or a forward reference.

**Adequacy.** Seven matters are adequate without qualification. Four carry
qualifications, all of which are **interpretive rather than absent**:

| Matter | Qualification |
|---|---|
| 5 — child container | The container label's form differs from the filename grammar; §9 gives a rationale but takes no position on whether the difference is acceptable |
| 7 — baseline/version/status | `TB0P1` is not expressly stated to carry PM-4 field 4; `AWC` places PM-4 field 5 in the filename, which PAC-001 §5.1 did not mark |
| 10 — collision and ambiguity | §13 is the candidate's statement about itself; platform compatibility is expressly untested |
| 11 — project-wide distinction | Common tokens (`HFS`, `BEP`, `AWC`) carry residual de facto reuse risk that scope wording controls but cannot eliminate |

**Does missing or ambiguous treatment require amendment?** **No.** Nothing is
missing. Each qualification concerns **how an existing proposal should be
construed**, and **PAD-001 §4.4 expressly reserves "final filename composition"
to the required naming controls (C5)** — the very matter AG-005 decides.
**AG-005 §4 items 11, 12, 13 and 15 confer authority over container naming,
token ordering, identity/version/status tokens and internal coherence**, which
between them reach every qualification.

**Decision-readiness consequence.** NPC-001 is **sufficiently complete for
AG-005 consideration**. The qualifications become **conditions on the later
decision** (`A1`–`A4`), not preconditions on submission.

---

## 6. Question 2 — filename completeness and uniqueness

> **Are all fifteen filenames complete and unique?**

### Finding

> ## **YES, WITH ONE QUALIFICATION CARRIED TO `A1`**

| Aspect | Assessment |
|---|---|
| Total count | **15** — verified (§3) |
| Class count | **7 / 1 / 7** — verified |
| Grammar | **15 of 15 conform** to their class pattern |
| Uniqueness | **Distinct case-sensitively and case-insensitively** |
| Lengths | **21–52 characters**, all within the candidate's own 120 limit |
| Mapping completeness | **Every one of the seven source documents yields exactly one rendition and one companion**; the manifest is unpaired by design |

**Whether any expected PM-4 carrier is missing or ambiguous.** **One is
ambiguous, none is missing.** PAC-001 §5.1 marks fields 1–4 as filename-carried.
The proposed stem carries four tokens:

| Stem token | PM-4 field |
|---|---|
| `HFS` | 1 — project identifier |
| `TB0P1` | 2 — package / baseline identifier |
| document token | 3 — document title |
| `AWC` | **5 — status** *(not marked filename-carried by PAC-001)* |

**No token is dedicated to field 4 (revision / version).** `TB0P1` expands to
"Training Baseline 0.1", which contains the version value. **Whether that
constitutes filename carriage of field 4 is not stated by NPC-001** and is
assessed at §11 and §21.

> **Mechanical uniqueness is not treated as complete governance readiness.** The
> fifteen names are demonstrably distinct and well-formed; **what they must
> carry is a separate question**, and it is the one that produces `A1`.

---

## 7. Question 3 — companion pairing

> **Is every source companion paired unambiguously with one rendition?**

### Finding

> ## **YES**

| Aspect | Assessment |
|---|---|
| Shared stems | **Verified for all seven pairs** — each companion's stem is its rendition's stem plus `-SOURCE` |
| `SOURCE` placement | **Terminal in every case**, immediately before `.md`; absent from all eight authoritative names |
| Extension conversion | **Verified mechanically** — removing `-SOURCE` and substituting `.pdf` yields a listed rendition in **7 of 7** cases |
| Manifest relationship requirement | **Required** — §8 bullet 4 and §11 items 3, 4 and 5 |
| Authoritative / subordinate distinction | **Preserved** — §8 bullet 5 ("filename similarity does not make the source companion authoritative"), §8 bullet 6, §12 bullet 4 |
| Ambiguity | **None found.** The relationship is expressed by a deterministic, reversible transform and is independently recorded in the manifest |

**Readiness consequence: PASS.** No condition arises.

---

## 8. Question 4 — manifest coherence

> **Does the manifest filename and role remain coherent?**

### Finding

> ## **YES**

| Aspect | Assessment |
|---|---|
| Exact filename | `HFS-TB0P1-MANIFEST-AWC.json` — conforms to its own grammar; unique |
| Authoritative role | **Preserved** — §11 item 2; consistent with PAD-001 §4.3.1, which counts the manifest among the eight authoritative files |
| Lack of companion | **Coherent.** The manifest is a generated package artefact, not an authored source; **no source document maps to it** in the §6 token map, so no companion could exist |
| Fifteen-file inventory requirement | **Required** — §11 item 3 |
| Relationship records | **Required** — §11 items 4 and 5 |
| PM-4 metadata use | **Required unchanged** — §11 items 9 and 10 |
| Later pinned commit | **Required** — §11 item 8, deferred to P6 step 4 |

**Whether any manifest requirement exceeds C5.** **No.** Items 1 and 6 are
naming; item 7 is status presentation; items 3, 4 and 5 are identity and
relationship records that C5's "presentation controls" limb reaches. Items 2, 9
and 10 **restate PAD-001 rather than adding to it**, and item 8 **defers to P6**
rather than deciding it. **Nothing in §11 asserts a control outside C5's
subject-matter.**

**Readiness consequence: PASS.**

---

## 9. Question 5 — `TB0P1` representation

> **Is `TB0P1` an unambiguous representation of Training Baseline 0.1?**

### Finding

> ## **YES AS TO TEXTUAL MEANING; ITS PM-4 CARRIER ROLE IS UNRESOLVED AND IS CARRIED TO CONDITION `A1`**

Assessed on the eight limbs required:

| # | Limb | Assessment |
|---|---|---|
| 1 | Textual meaning | **Unambiguous.** §4 defines `TB0P1` as "Training Baseline 0.1" in a controlled token dictionary. No competing expansion is proposed anywhere in the repository |
| 2 | Use of `P` for the decimal point | **Explained and internally justified.** §4 records that `P` represents the decimal point in `0.1`, "to avoid an additional period inside the filename stem", which §5.4 rule 7 requires. **The convention is stated, not merely used** |
| 3 | Package / baseline identity | **Carried.** `TB0P1` is the baseline identifier component of the package identifier `HFS-TB0P1` (§4, §10.1 item 7, §11 item 6) |
| 4 | Version value | **Present within the token.** The `0P1` element encodes `0.1`, which is the baseline's version designation |
| 5 | May one token legitimately carry both PM-4 field 2 and field 4? | **Nothing in the controlling records forbids it.** PAC-001 §5.1 marks fields 2 and 4 each as filename-carried but **does not require separate tokens**, and its own field-2 label — "Package / baseline identifier" — already denotes a versioned baseline. **PAD-001 §4.4 reserves final filename composition to C5.** **A single token carrying both is therefore an available construction** — but it is a construction, not a stated fact |
| 6 | Does NPC-001 state the dual carriage explicitly? | **No.** §4 defines the token's expansion. §11.1 recites PAC-001's field list, including "revision / version", **only as context for the status matter**. **No NPC-001 statement asserts that `TB0P1` discharges field 4** |
| 7 | May AG-005 resolve the interpretation? | **Yes.** §4 item 13 empowers AG-005 to "define minimum package-specific identity, **version**, status and relationship tokens" — the word *version* is express. §4 item 12 covers token ordering, and §4 item 15 covers internal coherence |
| 8 | Is candidate amendment required? | **No.** The token exists, is defined, and carries the value. What is absent is a **statement of its dual role**, which **the deciding record can supply**, and which §4 item 13 authorises it to supply |

> **Neither assumption invited by the task is adopted.** It is **not** assumed
> that separate PM-4 fields require separate filename tokens; it is **not**
> assumed that one token automatically satisfies both. **The records do not
> settle it, so it is recorded as unresolved and routed to `A1`.**

**Readiness consequence: PASS WITH DECISION CONDITION `A1`.**

---

## 10. Question 6 — `AWC` token control

> **Is `AWC` adequately controlled by its token definition?**

### Finding

> ## **YES — THE DEFINITION IS INTERNALLY ADEQUATE**

| Aspect | Assessment |
|---|---|
| Exact expansion | **`Approved With Conditions`** — §4 |
| Uniqueness of meaning | **Single meaning.** §4 requires that it "must always be expanded in this token dictionary as `Approved With Conditions`". No alternative expansion appears anywhere in NPC-001 or the repository |
| Use in every filename | **Verified** — present in all fifteen names, in fixed position |
| Use in the PDF footer | **Present** — §10.2, `HFS-TB0P1 \| <DOCUMENT> \| AWC \| Page <x> of <y>` |
| Package-specific limitation | **Stated** — §4 ("package-specific tokens only… not project-wide naming standards") and §5.4 rule 14 |
| Human-readable status retained | **Yes** — §5.4 rule 13 keeps the full `APPROVED WITH CONDITIONS`; §10.1 item 4 places it in the first-page block; §11 item 7 requires it in the manifest. **The abbreviation supplements; it does not replace** |
| Risk of de facto project-wide reuse | **Residual and non-zero.** A three-letter status abbreviation is inherently reusable. **Controlled by scope wording, not by construction** — carried to `A4` |
| Internal adequacy of the definition | **Adequate.** A controlled expansion, a fixed position, a retained long form and an express scope limit |

> **The separate question — whether adding `AWC` to filenames is within C5's
> authority — is not answered here.** It belongs to question 15 and is assessed
> at §21, producing condition `A2`.

**Readiness consequence: PASS**, with the authority limb carried to `A2` and the
reuse limb to `A4`.

---

## 11. Question 7 — document-token traceability

> **Are the document tokens distinct and traceable to the seven source documents?**

### Finding

> ## **YES**

| # | Source path | Token | Path exists at HEAD | Token unique |
|---|---|---|---|---|
| 1 | `bep/Harrismith-Fire-Station-BEP.md` | `BEP` | **Yes** | **Yes** |
| 2 | `supporting/information-management-responsibility-matrix.md` | `IM-RESP-MATRIX` | **Yes** | **Yes** |
| 3 | `supporting/model-information-responsibility-matrix.md` | `MODEL-INFO-RESP-MATRIX` | **Yes** | **Yes** |
| 4 | `supporting/information-delivery-schedule.md` | `INFO-DELIVERY-SCHEDULE` | **Yes** | **Yes** |
| 5 | `supporting/cde-workflow-state-strategy.md` | `CDE-WORKFLOW-STATE-STRATEGY` | **Yes** | **Yes** |
| 6 | `supporting/coordination-review-strategy.md` | `COORDINATION-REVIEW-STRATEGY` | **Yes** | **Yes** |
| 7 | `supporting/governance-decision-register.md` | `GOVERNANCE-DECISION-REGISTER` | **Yes** | **Yes** |

| Test | Result |
|---|---|
| Any token ambiguous | **No.** Each names its document recognisably |
| Any token duplicated | **No** — verified by deduplication |
| Any token misleading | **No.** `IM-RESP-MATRIX` and `MODEL-INFO-RESP-MATRIX` are distinct strings, and neither is a hyphen-delimited token-prefix of the other — `INFO-RESP-MATRIX` ≠ `IM-RESP-MATRIX` |
| Any token incorrectly mapped | **No.** All seven paths resolve at HEAD and each maps to the document its token names |
| Any token improperly presented as a reusable project code | **No.** §6 states the map "is exhaustive for this package and does not create reusable project document codes" |

**One factual observation, not a defect.** `BEP` is a generic industry
abbreviation, and `GOVERNANCE-DECISION-REGISTER` names a document that is
**simultaneously a package source and a live governance register**. Neither
affects traceability; the second is relevant to package-content freezing and is
addressed at §15 and §16.

**Readiness consequence: PASS.**

---

## 12. Question 8 — format-rule coherence

> **Are the character, case, separator and extension rules internally coherent?**

### Finding

> ## **YES — AND THE FILENAME / CONTAINER FORM DIFFERENCE IS COHERENT BECAUSE THEY ARE DIFFERENT OBJECT CLASSES, SUBJECT TO CONDITION `A3`**

| Rule | Verified against the fifteen names |
|---|---|
| Uppercase filename stems | **0 violations** |
| Lowercase extensions | **15 of 15** |
| Hyphens as sole separator | **Conforms** |
| No spaces | **0** |
| No underscores | **0** |
| No extra periods | **0 names with ≠ 1 period** |
| No consecutive hyphens | **0** |
| No leading or trailing hyphen | **0 / 0** |
| Fixed ordering | **15 of 15** conform to their class order |
| 120-character limit | **Max 52** |
| Case-insensitive uniqueness | **15 distinct** |

**No rule contradicts another**, and **no proposed filename violates any rule**.
The fourteen rules are jointly satisfiable and jointly satisfied.

### 12.1 The filename / container form difference

```text
Package filename form:   HFS-TB0P1-<DOCUMENT>-AWC.ext
Container label:         Training Baseline 0.1
```

The container label uses **spaces** and a **period**, both of which §5.4
prohibits **in package filenames**.

| Limb | Assessment |
|---|---|
| Is the difference a rule conflict? | **No.** §5.4 rule 14 confines those rules to "the Training Baseline 0.1 package", and §5.4 rules 1–13 speak of "filename stems" and "package filenames". **A CDE container label is not a package filename**, so no rule is breached |
| Is the different treatment reasoned? | **Yes.** §9 records that these are "deliberately different objects" and that the container form follows the as-found `03. Published` convention adopted by CGD-001 — whose naming **CGD-C05 records as provisional** |
| Is the reasoning decisive? | **No.** §9 explains the choice; **it does not state a rule governing container-label form**, nor does it record that the two rule-sets are intentionally disjoint as a control |

**Determination: coherent because they are different object classes — but
coherent *only with a condition*.** The candidate supplies a rationale where a
**control** is what C5 requires ("minimum controls… for… the proposed child
container"). **AG-005 §4 item 11 empowers it to "define the minimum controlled
name or naming rule for the proposed PM-1 child container"**, which is precisely
the instrument needed. **Carried to `A3`.**

**Readiness consequence: PASS WITH DECISION CONDITION `A3`.**

---

## 13. Question 9 — container scope

> **Does the proposed container name remain package-specific?**

### Finding

> ## **YES**

| Aspect | Assessment |
|---|---|
| Exact name | `Training Baseline 0.1` — a single controlled string |
| Direct-child position | **Beneath `03. Published`** — §9; consistent with PAD-001 §4.1's approved PM-1 position |
| No subfolder authorisation | **Stated** — "no additional child or subfolder is authorised" |
| Provisional CGD-001 naming context | **Correctly reflected.** CGD-C05 records that root labels "may continue to identify the adopted areas" and that "their adoption does not establish a project naming standard". §9 relies on this without overstating it |
| Distinction from project-wide naming | **Stated twice** — "the name is package-specific"; "the name does not establish a project-wide CDE naming standard" |
| Implementation authority | **Absent, and correctly recorded as absent** — §9 requires CDE administration or implementation authority (P7), which remains unestablished |
| C6, P7, P8 status | **All recorded as continuing** — §9 states C6 unverified and "P7 and P8 remain active" |
| Form difference acceptability | **Assessed at §12.1**; carried to `A3` |

**The name is inherently baseline-specific** — it names this baseline, not a
class of containers — so the package-specific claim is supported by the name's
own content, not only by the surrounding wording.

**Readiness consequence: PASS**, with the form limb at `A3`.

---

## 14. Question 10 — PDF presentation markings

> **Do the PDF presentation markings identify the document and governance status adequately?**

### Finding

> ## **YES**

| # | First-page item | Availability |
|---|---|---|
| 1 | `Harrismith Fire Station` | **Available now** |
| 2 | `Training Baseline 0.1` | **Available now** |
| 3 | Document's full human-readable title | **Available now** |
| 4 | `APPROVED WITH CONDITIONS` | **Available now** — AD-001 status |
| 5 | `AD-001` | **Available now** |
| 6 | `PAD-001` | **Available now** |
| 7 | `HFS-TB0P1` | **Available now** |
| 8 | Exact source repository commit | **Unavailable until P6 step 4 pinning** — recorded as such |
| 9 | Rendition-generation date | **Unavailable until authorised generation** — recorded as such |

**Footer:** `HFS-TB0P1 | <DOCUMENT> | AWC | Page <x> of <y>` — carries package
identity, document token, status abbreviation and pagination.

| Distinction | Assessment |
|---|---|
| Fields available now | **Seven of nine** |
| Fields unavailable until commit pinning | **One** — item 8 |
| Fields unavailable until generation | **One** — item 9 |
| Package-specific control marking | **Yes** — §10 opening and §10.3 bullet 1 |
| Project-titleblock / reusable-sheet implications | **Expressly disclaimed** — §10.3 bullets 2 and 3 |
| Sufficient for a later AG-005 decision | **Yes** |

**Why the two unpopulatable fields do not impair readiness.** They are
**specified now and populated later**, which is the correct sequencing: item 8
depends on P6 step 4, which C5 must precede, and item 9 depends on generation,
which C2 and P2 gate. **Requiring them to be populated before the C5 decision
would invert the controlling sequence.**

**One observation, not a condition.** The first-page block carries the **full**
status string while the footer carries the **abbreviation**. Both are defined and
neither contradicts the other.

**Readiness consequence: PASS.**

---

## 15. Question 11 — source-companion fidelity

> **Does the source-companion rule preserve byte-faithful subordinate sources?**

### Finding

> ## **YES**

| Aspect | Assessment |
|---|---|
| No inserted heading | **Required** — §12 bullet 2 |
| No front matter | **Required** — §12 bullet 2 |
| No footer | **Required** — §12 bullet 2 |
| No content mutation | **Required** — §12 bullet 2 |
| `SOURCE` token | **Carries subordinate status externally** — §12 bullet 3 |
| `.md` extension | **Carries class externally** — §12 bullet 3 |
| Manifest role field | **Carries role externally** — §12 bullet 3; §11 item 4 |
| Inability to override the rendition | **Stated** — §12 bullet 4 |

**The rule is internally consistent by construction.** Because subordinate
status is signalled **entirely outside the file content** — filename token,
extension and manifest role — **byte-faithfulness and role-signalling do not
compete**. §12's closing note records exactly this: "Byte-faithfulness is why no
marking is proposed inside the Markdown."

**Completeness for decision: adequate.** The rule states what must be true of the
companions and what must not be done to them. **What "byte-faithful to the later
pinned source" resolves to depends on P6 step 4**, which is correctly deferred.

**Readiness consequence: PASS.**

---

## 16. Question 12 — package-boundary preservation

> **Do the controls preserve PAD-001's package boundary?**

### Finding

> ## **YES**

| Element | PAD-001 §4.3.1 | NPC-001 | Result |
|---|---|---|---|
| Authoritative files | **8** | **8** | **Preserved** |
| Subordinate files | **7** | **7** | **Preserved** |
| Total | **15** | **15** — verified | **Preserved** |
| Merged authoritative PDF | Prohibited | Barred at §3 | **Preserved** |
| Authoritative ZIP | Prohibited | Barred at §3 | **Preserved** |
| Added class | — | Barred at §3 | **Preserved** |
| Removed class | — | Barred at §3 | **Preserved** |
| Promoted companion | Prohibited | Barred at §3, §8, §12 | **Preserved** |

### 16.1 Boundary preservation is not content freezing

**These are different things, and only the first is C5's concern.**

| | Package **boundary** | Package **content** |
|---|---|---|
| What it fixes | Which classes, how many files, which is authoritative | The bytes inside each source at a chosen instant |
| Owned by | **PAD-001**; C5 names within it | **P6 step 4** commit pinning |
| Affected by NPC-001 | **No** — verified above | **No** — NPC-001 names files, it does not freeze them |

**Repository fact.** NPC-001 records its source repository state as `09c04ff…`.
**The Governance & Decision Register — source document 7 — has changed twice
since that state**: at `08aa680` (recording NPC-001 itself) and at `5075677…`
(the documentary corrections). Both changes are recorded in the register's own
change log.

**Governance interpretation.** This does **not** disturb the boundary: the class
counts and roles are untouched, and the §6 token map keys on **repository paths**,
all seven of which resolve at HEAD. **It confirms that package content is not
yet frozen** — which is the condition **P6 step 4 exists to resolve**, and which
PRA-002's P6 entry anticipated when it recorded that "the register has since
accumulated AG-002, CGD-001 and AG-003 entries, so the package contents have
moved again".

**Readiness consequence: PASS.** The content-drift observation is **not a C5
matter** and is **not a decision condition**; it is inherent to the sequence
C5 → P6 step 3 → P6 step 4 and is recorded as residual `R7`.

---

## 17. Question 13 — collision and ambiguity

> **Are collision and ambiguity risks adequately addressed?**

### Finding

> ## **YES, SUBJECT TO RESIDUAL `R1`**

**Every mechanically testable statement in NPC-001 §13 was independently
reperformed during this increment** (§3). **§13 was not treated as evidence**;
these are this assessment's own results.

| §13 # | Statement | Independent result | Classification |
|---|---|---|---|
| 1 | Fifteen filenames unique | 15 extracted, 15 after deduplication | **Resolved mechanically** |
| 2 | Unique case-insensitively | 15 after lower-casing | **Resolved mechanically** |
| 3 | One companion per rendition | 7 pairs; transform verified 7 of 7 | **Resolved mechanically** |
| 4 | Manifest has no companion | 0 `MANIFEST…SOURCE` names | **Resolved mechanically** |
| 5 | `IM-RESP-MATRIX` / `MODEL-INFO-RESP-MATRIX` distinct | Distinct strings; not token-prefixes | **Resolved mechanically** |
| 6 | `TB0P1` not confusable with an extension | Exactly one period per name, before the extension | **Resolved mechanically** |
| 7 | `SOURCE` only on companions | 0 `SOURCE` names outside `.md` | **Resolved mechanically** |
| 8 | `AWC` has one controlled meaning | One expansion; no alternative in the repository | **Resolved mechanically** within NPC-001; **governance interpretation** as to adequacy (§10) |
| 9 | One period per filename | 0 names with ≠ 1 period | **Resolved mechanically** |
| 10 | Extensions identify the class | 7 / 1 / 7 matching the three grammars | **Resolved mechanically** |
| 11 | Container name distinct from the four root areas | Distinct from `0. Common Files`, `01. WIP`, `02. Shared`, `03. Published` | **Resolved mechanically** |
| 12 | Boundary unchanged | 8 + 7 = 15 matches PAD-001 | **Resolved mechanically** |
| 13 | No project-wide standard established | Six scope bars present | **Governance interpretation** (§18) |
| — | Longest name 52 characters | Two names at 52 | **Resolved mechanically** |
| — | Platform compatibility untested | No test performed; none authorised | **Technical platform testing required** |

**Eleven of thirteen statements are resolved mechanically and were independently
confirmed. Two require governance interpretation** (items 8 and 13), both
addressed under their own questions. **None was found inaccurate.**

### 17.1 The self-assessment limitation

**Repository fact.** §13 is a statement by the candidate about itself, and
NPC-001 §15 twice disclaims it — "It is not an answer to question 13, and it is
not a readiness finding."

**Assessment finding.** **The limitation is real but is discharged here, not by
NPC-001.** A self-statement cannot establish its own adequacy; **an independent
reperformance can**, and §3 supplies one. **The disclaimers are correctly drawn
and were honoured.** **No condition arises** — the limitation is answered by this
assessment's own verification rather than carried forward.

### 17.2 Platform compatibility

**Repository fact.** §13 records: "Platform compatibility has not been tested. No
claim is made that any platform accepts, preserves or displays these names.
Testing would require acts NPC-001 does not authorise."

**Controlling records.** **PAD-001 §5.5 requires C5's minimum controls "before
package assembly"** — it does **not** require platform testing before the
control decision. **P2** (PDF/A toolchain, "Not selected, not tested") is
required "before package assembly and PE-3"; **P8** (destination verification) is
required "before publication execution". **AG-005 §7 expressly withholds from the
deciding function any authority to select or test the toolchain or the upload
mechanism** — so **AG-005 could not perform such a test even if it wished to**.

**Classification and finding:**

| Question | Finding |
|---|---|
| Does platform compatibility **block AG-005 consideration**? | **No.** No controlling record requires the test before the governance decision, and AG-005 is barred from performing it |
| May it be **carried as a later technical prerequisite**? | **Yes** — under **P2** and **P8**, which already exist and remain active. Recorded as residual `R1` |
| Does it **require candidate amendment**? | **No.** NPC-001 states the limitation accurately and claims nothing it has not tested |

> **Lack of platform testing is not equated with failure of C5 readiness**,
> because the controlling records do not require that test before the decision.

**Readiness consequence: PASS**, with `R1` carried as a residual prerequisite.

---

## 18. Question 14 — project-wide scope control

> **Are the controls clearly barred from becoming project-wide standards?**

### Finding

> ## **YES — SUBJECT TO CONDITION `A4` ON RESIDUAL REUSE RISK**

**Scope-limiting statements located in NPC-001:**

| § | Statement |
|---|---|
| §1.1 | NPC-001 is not "a project-wide naming, coordinate, titleblock or template standard" |
| §4 | "these are package-specific tokens only… not project-wide naming standards" |
| §5.4 rule 14 | "These controls apply only to the Training Baseline 0.1 package" |
| §6 | "does not create reusable project document codes" |
| §9 | "the name does not establish a project-wide CDE naming standard" |
| §10.3 | "not a project titleblock standard"; "does not establish a reusable sheet standard" |
| §14 | The categorical six-item block, plus `NOT ESTABLISHED` for the four project standards |
| §19 | "Project standards \| Not established — unchanged" |

| Limb | Assessment |
|---|---|
| Is the candidate clearly package-specific? | **Yes.** Eight independent statements across seven sections, covering tokens, filenames, document codes, container names and markings |
| Would future reuse require a separate decision? | **Yes**, on the records as they stand: the four project standards remain **Not established**, and **AG-005 §7 withholds authority to establish them**. Reuse would need an instrument that does not exist |
| Do common tokens create residual de facto-standard risk? | **Yes, and this is a real exposure.** `HFS` is a project abbreviation, `BEP` a generic industry term and `AWC` a status abbreviation. Each is inherently reusable, and **a pattern applied to fifteen files can be copied informally without any decision being taken** |
| Does that risk block decision or remain controlled by explicit scope? | **It does not block decision.** It is controlled by scope wording, which is the only instrument available at the governance level — but **wording controls citation, not habit**. Carried to `A4` so the deciding record restates the bar rather than relying solely on the candidate's |

**Readiness consequence: PASS WITH DECISION CONDITION `A4`.**

---

## 19. Question 15 — authority sufficiency

> **Does any proposed rule require authority that NPC-001 does not possess?**

**This question produces the assessment's two principal findings.**

### 19.1 Candidate authority

**Repository fact.** NPC-001 carries **`Authority: None`** and is classified
**PROPOSED GOVERNANCE — NOT APPROVED**. Its §1.1 disclaims being a decision, an
approval or an instruction, and its §1.2 disclaims satisfying C5 or P6 step 3.

**Assessment finding.** **A candidate with `Authority: None` may legitimately
propose rules without establishing them.** That is the settled repository
pattern: **PAC-001** proposed seven PM positions with `Authority: None` and was
later approved by PAD-001; **AG-005 §6 requires a candidate to exist** before its
approval authority may be exercised, which presupposes that candidates are
prepared by something other than the deciding function. **Proposing is not
establishing**, and NPC-001 nowhere asserts otherwise.

> **No proposed rule in NPC-001 is stated as being in force.** Every rule is
> framed as "proposed", and the header banner records that nothing "becomes
> governing merely because it appears in NPC-001".

### 19.2 AG-005 authority over each proposed matter

| Matter | Within AG-005's §4 scope | Basis |
|---|---|---|
| Filename composition | **Yes** | §4 items 7–9, 12 |
| `AWC` as an additive status carrier | **Yes** | §4 item 13 — "identity, version, **status**… tokens" |
| Combined `TB0P1` package/baseline and revision/version representation | **Yes** | §4 item 13 — "identity, **version**… tokens"; §4 item 12 token ordering |
| Source-companion naming | **Yes** | §4 items 9, 10 |
| Container naming | **Yes** | §4 item 11 |
| PDF presentation markings | **Yes** | §4 item 14 |
| C5 satisfaction | **Yes** | §4 item 16 |
| P6 step 3 consequence | **Yes** | §4 item 17 |

**Assessment finding.** **AG-005's authority scope reaches every matter NPC-001
proposes.** No proposed rule falls outside it, and **no proposed rule requires an
authority that neither NPC-001 nor AG-005 holds** — with the express carve-outs
at AG-005 §7 (implementation, toolchain, upload, CGD-001 verification, pinning,
project-wide standards) **which NPC-001 does not trespass upon**, because it
proposes controls rather than acts.

### 19.3 PM-4 status carrier — explicit finding

**Repository facts.**

- **PAC-001 §5.1 field 5 (Status)** — "In document" ●, "In filename" **empty**,
  "In manifest" ●.
- **PAD-001 §4.4** approved the fourteen-field set and recorded that "**final
  filename composition remains subject to the required naming controls (C5)**".
- **NPC-001 §5.4 rule 13** — "The status token is `AWC`; the full human-readable
  status remains `APPROVED WITH CONDITIONS`."
- **NPC-001 §11.1** records the divergence as "**additive**, not substitutive"
  and states it "is not determined here".

**Determination, limb by limb:**

| Limb | Finding |
|---|---|
| Is adding `AWC` within C5's authority over final filename composition? | **Yes.** PAD-001 §4.4 reserves final filename composition to C5 without limiting it to the four originally-marked fields, and **AG-005 §4 item 13 expressly names *status* among the tokens the function may define** |
| Does it change a PM-4 field? | **No.** All fourteen fields remain; none is added, removed or redefined |
| Does it change the required document or manifest carriers? | **No.** §10.1 item 4 keeps the full status on the first page; §11 item 7 keeps it in the manifest. **Both original carriers are retained** |
| Does it merely add an additional carrier? | **Yes.** The filename becomes a **third** carrier of a field already carried in two approved places |
| Must AG-005 resolve it explicitly? | **Yes.** PAC-001's table is the approved metadata position; a filename carrier it did not mark **should not be introduced silently**. Recorded as **`A2`** |
| Must NPC-001 be amended first? | **No.** The proposal is complete and the divergence is disclosed at §11.1. What is required is an **express decision**, which AG-005 is empowered to make |

### 19.4 PM-4 revision/version carrier — explicit finding

**Repository facts.**

- **PAC-001 §5.1 field 4 (Revision / version)** — "In filename" **● marked**.
- **NPC-001's stem carries four tokens** — `HFS`, `TB0P1`, document token, `AWC`.
- **`TB0P1` is defined only as "Training Baseline 0.1"** (§4).
- **The words "revision" and "version" appear exactly once in NPC-001** — at
  §11.1, inside a recital of PAC-001's field list, offered as context for the
  *status* matter. **Independently verified during this increment.**

**Determination, limb by limb:**

| Limb | Finding |
|---|---|
| May `TB0P1` carry both field 2 and field 4? | **Yes, as an available construction.** No controlling record requires one token per field, and PAC-001's own field-2 label — "Package / **baseline** identifier" — denotes a versioned object. `TB0P1` demonstrably contains the value `0.1` |
| Is the candidate's lack of an explicit dual-carrier statement material? | **Yes — materially, though not fatally.** PAC-001 marks field 4 as filename-carried; **a reader of NPC-001 alone cannot tell whether field 4 is carried, or overlooked.** The construction is available but **unstated**, and C5 is the control that is supposed to settle final filename composition |
| May AG-005 resolve the interpretation in its decision? | **Yes.** §4 item 13 empowers it to define "identity, **version**, status and relationship tokens", and §4 item 15 to confirm internal coherence. **Stating that `TB0P1` discharges PM-4 fields 2 and 4 is squarely within that power** |
| Must NPC-001 be amended first? | **No.** Nothing needs to be added to the proposal — the token exists and carries the value. What is missing is a **statement of effect**, which the deciding record supplies. Recorded as **`A1`** |
| Is a separate token required? | **Not on the records as they stand.** No record requires one field per token. **If AG-005 concludes otherwise, that is a decision it is empowered to take** — and it would then be approving with a condition or rejecting, both within §4 |

### 19.5 Question 15 finding

> ## **NO — NO PROPOSED RULE REQUIRES AUTHORITY THAT NEITHER NPC-001 NOR AG-005 POSSESSES**

**But two proposed rules require AG-005 to exercise its authority *expressly*
rather than by implication** — the `TB0P1` dual carriage (`A1`) and the `AWC`
additive carrier (`A2`). **Neither requires candidate amendment.**

---

## 20. Blocker check

**No BLOCKER is recorded.**

| Test | Result |
|---|---|
| Does NPC-001 require substantive amendment? | **No.** Every qualification is resolvable in the deciding record |
| Is there an unresolved contradiction preventing a controlled decision? | **No.** No rule contradicts another; no proposed name violates any rule; the boundary matches PAD-001 exactly |
| Is a required candidate-precondition matter absent? | **No.** All eleven are covered (§4) |
| Does AG-005 lack authority to resolve a required matter? | **No.** Every matter maps to an AG-005 §4 item (§19.2) |
| Can this assessment determine the governance consequence safely? | **Yes** for all eighteen questions |

### 20.1 Nothing is concealed or downgraded

**Four matters could have been recorded as blockers and are deliberately not:**

| Matter | Why not a blocker |
|---|---|
| `TB0P1` dual carriage unstated | The token and value exist; only a statement of effect is missing, and AG-005 §4 item 13 supplies it |
| `AWC` additive carrier | PAD-001 §4.4 reserves filename composition to C5; both approved carriers are retained |
| Container/filename form difference | No rule is breached; §5.4 is confined to filenames by its own rule 14 |
| Platform compatibility untested | No controlling record requires the test before the decision, and AG-005 §7 bars the deciding function from performing it |

**Each is recorded as a condition or a residual, in the open, with its basis
stated.** **None is resolved by assertion.**

---

## 21. Question 16 — decision readiness

> **Is NPC-001 ready to be submitted to AG-005 for a decision?**

### Finding

> ## **YES — READY WITH CONDITIONS**

Based on questions 1–15:

| Statement | Finding |
|---|---|
| Is candidate amendment required? | **No.** No question produced an amendment requirement |
| Are explicit AG-005 decision conditions required? | **Yes — four**, recorded as `A1` to `A4` (§22) |
| May technical residuals remain? | **Yes — seven**, recorded as `R1` to `R7` (§22.1). None belongs to C5 |
| Assessment outcome | **READY FOR AG-005 DECISION WITH CONDITIONS** |

**Decisive findings.** All eleven precondition matters covered with substantive
content; twenty-two mechanical verifications returned the expected result; every
proposed matter falls within AG-005's authority; no rule conflicts; the PAD-001
boundary is preserved exactly; **and the four open matters are all of a kind that
a deciding record resolves by saying so.**

---

## 22. Assessment conditions

**Local assessment labels only.** **`A1`–`A4` are not repository-wide governance
identifiers**, allocate nothing, and bind no one. They record what **this
assessment finds the later AG-005 decision would need to address expressly**.

### A1 — `TB0P1` as a dual PM-4 carrier

| Field | Value |
|---|---|
| **Exact issue** | NPC-001 provides no filename token distinct from `TB0P1` for **PM-4 field 4 (revision / version)**, which PAC-001 §5.1 marks as filename-carried. `TB0P1` contains the value `0.1` but **is nowhere stated to discharge field 4** |
| **Controlling record** | PAC-001 §5.1 row 4; PAD-001 §4.4; AG-005 §4 items 13, 15 |
| **Why it matters** | C5 is the control that settles final filename composition. Leaving field 4's carriage implicit would carry an unstated assumption into an approved control |
| **Can AG-005 resolve it?** | **Yes** — §4 item 13 names *version* expressly |
| **Required decision treatment** | The AG-005 decision should state expressly whether `TB0P1` discharges **PM-4 fields 2 and 4 together**, or whether a distinct revision/version token is required |
| **Candidate amendment required?** | **No** |
| **Consequence if omitted** | An approved naming control whose satisfaction of an approved metadata requirement rests on inference; a later reader could not tell whether field 4 was carried or overlooked |

### A2 — `AWC` as an additive status carrier

| Field | Value |
|---|---|
| **Exact issue** | `AWC` places **PM-4 field 5 (status)** in every filename. PAC-001 §5.1 marks field 5 as document- and manifest-carried, with the filename cell **empty** |
| **Controlling record** | PAC-001 §5.1 row 5; PAD-001 §4.4; NPC-001 §5.4 rule 13, §11.1; AG-005 §4 item 13 |
| **Why it matters** | It adds a carrier the approved metadata table did not mark. NPC-001 discloses this as "additive, not substitutive" but expressly does not determine it |
| **Can AG-005 resolve it?** | **Yes** — §4 item 13 names *status* expressly; PAD-001 §4.4 reserves final filename composition to C5 |
| **Required decision treatment** | The decision should record expressly that the filename status token is **additive**, that the **document and manifest remain the approved carriers**, and that **PM-4 is neither changed nor enlarged** |
| **Candidate amendment required?** | **No** |
| **Consequence if omitted** | A filename-carried metadata field with no express approval, sitting alongside an approved table that does not mark it |

### A3 — Container-label form versus filename grammar

| Field | Value |
|---|---|
| **Exact issue** | `Training Baseline 0.1` uses spaces and a period; §5.4 prohibits both **in package filenames**. §9 explains the difference as an object-class distinction but **states no control governing container-label form** |
| **Controlling record** | NPC-001 §5.4 rule 14, §9; CGD-001 CGD-C05; PAD-001 §5.5; AG-005 §4 item 11 |
| **Why it matters** | C5 requires minimum controls **for the proposed child container**, not only a rationale. Two co-existing form regimes in one approved control should be intentional on the record |
| **Can AG-005 resolve it?** | **Yes** — §4 item 11 permits defining "the minimum controlled name or naming rule for the proposed PM-1 child container" |
| **Required decision treatment** | The decision should record that the container-label rules and the package-filename rules are **deliberately distinct, apply to different object classes, and neither governs the other** |
| **Candidate amendment required?** | **No** |
| **Consequence if omitted** | An approved control containing two unreconciled form regimes, readable as an inconsistency |

### A4 — Scope bar against de facto project-wide reuse

| Field | Value |
|---|---|
| **Exact issue** | `HFS`, `BEP` and `AWC` are inherently reusable abbreviations. NPC-001 bars project-wide status in eight places, but **a bar inside a candidate does not travel with an approved control** |
| **Controlling record** | NPC-001 §4, §5.4 rule 14, §6, §9, §10.3, §14; AG-005 §4.1, §7 |
| **Why it matters** | Once controls are approved, the approving record is what is cited. The four project standards remain **Not established**, and AG-005 §7 withholds authority to establish them |
| **Can AG-005 resolve it?** | **Yes** — §4.1 already binds every item to this package |
| **Required decision treatment** | The decision should restate in its own terms that the approved controls are **package-specific**, **establish no project-wide naming, coordinate, titleblock or template standard**, and **may not be cited as one** |
| **Candidate amendment required?** | **No** |
| **Consequence if omitted** | Package-specific controls could be reused informally as a de facto project convention with no decision ever taken |

### 22.1 Residual technical and implementation prerequisites

**These do not block AG-005 consideration and do not belong to C5.** They remain
under their existing PAD-001 prerequisites and conditions.

| # | Residual | Existing control | Blocks package assembly | Blocks PE-3 | Blocks PE-4 |
|---|---|---|---|---|---|
| **R1** | Platform / toolchain compatibility of the proposed filenames untested | **P2** — "Not selected, not tested"; **C2** | **Yes** | **Yes** | **Yes** |
| **R2** | CGD-001 live correspondence unverified | **C6** | No | No | **Yes** |
| **R3** | CDE administration / implementation authority not established | **P7** | No | No | **Yes** |
| **R4** | Technical executor unassigned | **P7** | No | No | **Yes** |
| **R5** | Upload route unconfirmed | **P1** | No | No | **Yes** |
| **R6** | Destination verification not performed | **P8** | No | No | **Yes** |
| **R7** | Publication-package commit not pinned; package content not frozen | **P6 step 4** | **Yes** | **Yes** | **Yes** |

> **Decision conditions and technical residuals are not collapsed.** `A1`–`A4`
> are matters the **AG-005 decision** must address in its own words. `R1`–`R7`
> are matters **no naming decision can resolve**, already controlled by C1–C6 and
> P1–P8, and unchanged by this assessment.

---

## 23. Question 17 — prospective C5 consequence

> **Would approval satisfy C5?**

**AG-005 is not exercised.** This is a prospective assessment of what an approval
would need to contain.

**What AG-005 would need to approve expressly**, on the records as they stand:

1. the naming controls for the seven renditions, the manifest and the seven
   companions;
2. the companion-to-rendition relationship rule;
3. the container name or naming rule;
4. the minimum presentation markings;
5. the four matters at `A1`–`A4`.

**Would a straightforward approval suffice?** **No.** A bare approval would leave
`A1` and `A2` — both concerning approved PM-4 metadata carriage — resolved only
by implication.

**Would approval with conditions suffice?** **Yes**, if the decision records
`A1`–`A4` expressly.

**Would any residual naming or presentation matter keep C5 open?** **No matter
identified by this assessment would.** All four conditions are resolvable within
the decision itself.

**Are technical implementation prerequisites separate from C5?** **Yes.** PAD-001
§5.5 requires C5's minimum controls "before package assembly"; **producing** the
files is governed by C2, P2 and P6. `R1`–`R7` are therefore outside C5.

### Prospective finding

> ## **`YES, PROVIDED THE AG-005 DECISION RECORDS THE LISTED CONDITIONS`**

---

## 24. Question 18 — prospective P6 step 3 consequence

> **Would approval satisfy P6 step 3, or would a residual condition remain?**

**Relationship between C5 and P6 step 3.** PAD-001 §8 states the pinning sequence
may proceed "only after… **any required naming and presentation controls are
established**". **P6 step 3 is the establishment of exactly the controls C5
requires** — the two are the same subject matter viewed from the condition side
and the prerequisite side. **AG-005 §4 item 17 recognises this**, empowering the
function to determine whether P6 step 3 is satisfied "**as a consequence of the
approved C5 controls**".

| Limb | Assessment |
|---|---|
| Would approved controls complete step 3? | **Yes**, if C5 is satisfied — step 3 asks for nothing beyond established naming and presentation controls |
| Is commit pinning step 4 rather than a residual part of step 3? | **Step 4.** PAD-001 §8 lists the three "only after" conditions and then states separately that "**pinning occurs before generation and before PE-3**". Pinning is the **act the sequence gates**, not a component of step 3 |
| Does technical route testing belong to other prerequisites? | **Yes** — **P2** (toolchain), **P1** (upload), **P8** (destination). None is a step-3 component |
| Would any unresolved naming/presentation condition keep step 3 pending? | **Only if `A1`–`A4` were left unaddressed.** If the decision records them, no naming or presentation matter identified here would remain open |

### Prospective finding

> ## **`APPROVAL COULD SATISFY P6 STEP 3 SUBJECT TO THE LISTED DECISION CONDITIONS`**

> **P6 overall would remain `ACTIVE`** even then, because **step 4 — commit
> pinning — would still be unperformed**, and **step 5's sequencing rule would
> continue to apply**.

---

## 25. Overall readiness outcome

> ## **`READY FOR AG-005 DECISION WITH CONDITIONS`**

| Element | Position |
|---|---|
| **Basis** | All eleven AG-005 §6 precondition matters are covered with substantive content; twenty-two independent mechanical verifications returned the expected result; every proposed matter lies within AG-005's §4 authority; no internal rule conflict exists; PAD-001's package boundary is preserved exactly |
| **Decisive findings** | **No candidate amendment is required** (§21); **four matters require express treatment in the decision** (`A1`–`A4`); **seven technical matters are residual and outside C5** (`R1`–`R7`); **no blocker exists** (§20) |
| **Conditions** | `A1` `TB0P1` dual carriage; `A2` `AWC` additive status carrier; `A3` container/filename form distinction; `A4` project-wide scope bar restated in the decision |
| **Blockers** | **None** |
| **Matters expressly not treated as blockers** | Untested platform compatibility (`R1`); package content not yet frozen (`R7`); NPC-001's self-assessment at §13 — independently reperformed and confirmed at §3 and §17 |
| **Authority boundary** | **NPRA-001 carries `Authority: None`.** It approves nothing, exercises no function, satisfies no condition or prerequisite, and reaches no PE event. **AG-005 remains unexercised.** **C5 remains `CARRIED FORWARD`.** **P6 step 3 remains pending.** **Publication remains NOT AUTHORISED.** |
| **Next controlled gate** | **`Exact read-only review of NPRA-001`** |

> **AG-005 may not be exercised until the exact review of NPRA-001 is completed
> and accepted by the governance orchestrator.** **This assessment does not
> authorise the decision; it records that the candidate is eligible to be put to
> it.**

---

## 26. Answers index

| # | Question | Finding | § |
|---|---|---|---|
| 1 | Covers all eleven precondition matters? | **YES, WITH QUALIFICATIONS** | §5 |
| 2 | Fifteen filenames complete and unique? | **YES**, one qualification → `A1` | §6 |
| 3 | Companion pairing unambiguous? | **YES** | §7 |
| 4 | Manifest filename and role coherent? | **YES** | §8 |
| 5 | `TB0P1` unambiguous? | **YES** textually; carrier role → `A1` | §9 |
| 6 | `AWC` adequately controlled? | **YES** internally; authority → `A2`; reuse → `A4` | §10 |
| 7 | Document tokens distinct and traceable? | **YES** | §11 |
| 8 | Format rules internally coherent? | **YES**; container form → `A3` | §12 |
| 9 | Container name package-specific? | **YES** | §13 |
| 10 | PDF markings adequate? | **YES** | §14 |
| 11 | Source-companion fidelity preserved? | **YES** | §15 |
| 12 | Package boundary preserved? | **YES**; content freezing → `R7` | §16 |
| 13 | Collision and ambiguity addressed? | **YES**, subject to `R1` | §17 |
| 14 | Barred from project-wide standards? | **YES**, subject to `A4` | §18 |
| 15 | Any rule requiring absent authority? | **NO**; two require express exercise → `A1`, `A2` | §19 |
| 16 | Ready for submission to AG-005? | **YES — READY WITH CONDITIONS** | §21 |
| 17 | Would approval satisfy C5? | **`YES, PROVIDED THE AG-005 DECISION RECORDS THE LISTED CONDITIONS`** | §23 |
| 18 | Would approval satisfy P6 step 3? | **`APPROVAL COULD SATISFY P6 STEP 3 SUBJECT TO THE LISTED DECISION CONDITIONS`** | §24 |

**All eighteen NPC-001 readiness questions are answered by this assessment.**
**Answering them here does not alter NPC-001**, whose §15 table continues to
record them as the questions this assessment was convened to address.

---

## 27. Effect on current governance matters

| Matter | Effect of NPRA-001 |
|---|---|
| **NPC-001** | **Unchanged in substance** — a dated subsequent-status note only. **Remains PROPOSED GOVERNANCE — NOT APPROVED, `Authority: None`** |
| **AG-005** | **Unchanged in substance** — a dated subsequent-status note only. **NOT EXERCISED** |
| **AG-004** | **Unchanged**; not exercised |
| **PAD-001, PAC-001, PRA-001, PRA-002, CGD-001, AD-001, GD-001, AG-001–AG-003** | **Unchanged** |
| **PM-1 … PM-7** | **APPROVED WITH CONDITIONS BY PAD-001 — unchanged** |
| **C1** | **SATISFIED BY AG-004 — unchanged** |
| **C2, C4, C6** | **CARRIED FORWARD — unchanged** |
| **C3** | **SATISFIED AT PE-2 — unchanged** |
| **C5** | **CARRIED FORWARD** — assessed, **not satisfied** |
| **P1 … P8** | **Active — unchanged.** **P6 step 3 remains pending** |
| **GCR-005** | **CLOSED at the governance-definition level — unchanged** |
| **GCR-006** | **OPEN — unchanged** |
| **UD-001** | **Unresolved — unchanged** |
| **CGD-001 verification** | **Pending — unchanged** |
| Publication / exchange authority | **UNRESOLVED — unchanged** |
| Technical executor | **Unassigned — unchanged** |
| Recipient acceptance authority | **UNRESOLVED — unchanged** |
| CDE implementation authority | **Not established — unchanged** |
| Project standards | **Not established — unchanged** |
| **PE-2** | **Reached — unchanged** |
| **PE-3 … PE-S** | **Not reached — unchanged** |
| Package artefact | **None** |
| Publication-package commit | **Not proposed, not pinned** |
| **Publication** | **NOT AUTHORISED — unchanged** |
| **Publication hold** | **ACTIVE — unchanged** |

---

## 28. Identifier-family note

**NPRA-001 opens the `NPRA-` family** — *Naming and Presentation Readiness
Assessment*. **`NPRA-001` was unused before this record**, and the prefix
collides with none of the nineteen established families: `AD-`, `AG-`, `CGD-`,
`EC-`, `GCR-`, `GD-`, `NPC-`, `OC-`, `OF-`, `PAC-`, `PAD-`, `PE-`, `PM-`,
`PPER-`, `PPQ-`, `PRA-`, `ROA-`, `TA-`, `UD-`. **It is distinct from `PRA-`,
which denotes publication-arrangement readiness assessments, and from `NPC-`,
which denotes naming and presentation control candidates.**

**The family is expressly limited to non-decisional readiness assessments of
package-specific naming and presentation control candidates.**

> **`NPRA-` is an assessment family only.** **It carries no authority, approves
> nothing, decides nothing and reaches no PE event.**

**Later use of the family still requires a controlled scope and collision
review** — **no future assessment belongs to it automatically.**

---

## 29. Assessment statement

> ## **NPRA-001 — TRAINING BASELINE NAMING AND PRESENTATION CONTROL READINESS ASSESSMENT**
>
> ## **`READY FOR AG-005 DECISION WITH CONDITIONS`**
>
> **Classification: ASSESSMENT RECORD — NOT A GOVERNANCE DECISION.
> Authority: None.**
>
> **NPC-001 covers all eleven AG-005 candidate-precondition matters and requires
> no amendment before consideration.** **Four matters — `A1` to `A4` — require
> express treatment in the later AG-005 decision.** **Seven technical matters —
> `R1` to `R7` — remain residual under existing conditions and prerequisites and
> are outside C5.** **No blocker is recorded.**
>
> **NPRA-001 approves nothing and rejects nothing.** **AG-005 is not exercised.
> NPC-001 remains PROPOSED GOVERNANCE — NOT APPROVED. C5 remains `CARRIED
> FORWARD`. P6 step 3 remains pending and P6 remains ACTIVE. No package commit
> is proposed or pinned. No package exists. No project-wide standard is
> established.**
>
> **The next controlled gate is an exact read-only review of NPRA-001.**
>
> ## **PUBLICATION REMAINS NOT AUTHORISED — PUBLICATION HOLD ACTIVE.**

**Related records.** Candidate — [`docs/Training-Baseline-Naming-and-Presentation-Control-Candidate.md`](Training-Baseline-Naming-and-Presentation-Control-Candidate.md).
AG-005 — [`docs/Training-Publication-Naming-and-Presentation-Approver-Function-Decision.md`](Training-Publication-Naming-and-Presentation-Approver-Function-Decision.md).
AG-004 — [`docs/Training-Baseline-Publication-Owner-Function-Decision.md`](Training-Baseline-Publication-Owner-Function-Decision.md).
Arrangement decision — [`docs/Publication-Arrangement-Approval-Decision.md`](Publication-Arrangement-Approval-Decision.md).
Arrangement candidate — [`docs/Publication-Arrangement-Candidate-0.1.md`](Publication-Arrangement-Candidate-0.1.md).
Readiness precedents — [`docs/Publication-Arrangement-Readiness-Assessment.md`](Publication-Arrangement-Readiness-Assessment.md)
and [`docs/Publication-Arrangement-Readiness-Reassessment.md`](Publication-Arrangement-Readiness-Reassessment.md).
CGD-001 — [`docs/CDE-Structure-Governance-Decision.md`](CDE-Structure-Governance-Decision.md).
