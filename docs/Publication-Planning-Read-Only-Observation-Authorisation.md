# ROA-001 — Publication Planning Read-Only Observation Authorisation

| Field | Value |
|---|---|
| Document status | **CONTROLLED READ-ONLY OBSERVATION AUTHORISATION** |
| Decision ID | **ROA-001** |
| Decision outcome | **AUTHORISE WITH CONSTRAINTS** |
| Authorising function | **Training Implementation Owner** |
| Decision date | **2026-08-01** |
| Increment | 8C-A — Refine and Authorise Read-Only Observation Questions |
| Baseline context | Training Baseline 0.1 — **APPROVED WITH CONDITIONS** (**AD-001**, 2026-08-01) |

> **PUBLICATION REMAINS NOT AUTHORISED — PUBLICATION HOLD ACTIVE.**

> **This authorisation permits one bounded, read-only observation and nothing
> else.** It authorises no publication, no upload, no exchange, no delivery, no
> receipt and no acceptance, and it assigns no authority to any person or
> function.

---

## 1. What is authorised

| Field | Value |
|---|---|
| Questions authorised | **`PPQ-001` to `PPQ-007` only**, in the exact wording recorded in the register at §10.2 as at this decision |
| Sessions authorised | **One** fresh Claude Desktop observation session |
| Mode | **Read-only inspection only** |
| Subject | **The Harrismith Fire Station project only** |
| Visibility | **The connector and account visibility available during that session only** |
| Evidence class expected | **EC-3** — live-system observational evidence |

**Nothing outside this table is authorised.** A question not in the set, a
project not named, a second session, or an inspection route beyond what that
session's account can already see is **outside this authorisation**.

## 2. Authority basis

The authority basis for ROA-001 is the **explicit instruction represented by
receipt of the Increment 8C-A prompt**, limited to:

- operation of the **training reference implementation**; and
- **read-only evidence gathering** in support of Publication Planning.

### 2.1 What this authority basis is not

This basis is stated narrowly and must not be read wider. It is:

| Not | |
|---|---|
| **Not inferred from ACC access** | Being able to reach the environment is not authority to act in it |
| **Not inferred from permissions** | **Permission is not authority** |
| **Not inferred from project membership** | Membership records participation in a system, not authority |
| **Not publication / exchange authority** | That authority remains **UNRESOLVED** (BEP 9.7; AD-001 §6, Condition 5) |
| **Not recipient acceptance authority** | That authority remains **UNRESOLVED** (BEP 9.8, 10.11) |

And it does **not** authorise:

- any external information exchange;
- publication, upload, issue, distribution, delivery, receipt or acceptance;
- creation, modification or deletion of any Autodesk item, version, folder,
  permission, issue, review, transmittal or model set;
- file download, content retrieval, translation or export;
- any change to the repository by the observing session.

**ROA-001 creates no appointment.** No functional holder is appointed or
nominated for any unresolved authority, and holding this authorisation confers
none of them.

## 3. Constraints

| # | Constraint |
|---|---|
| 1 | **Read-only.** No state-changing operation may be invoked, including for testing |
| 2 | **One session only.** No repeat session is authorised |
| 3 | **No elevated credential**, alternative account, or workaround route |
| 4 | **No sample expansion** beyond §4 |
| 5 | **No version may be created** to make a question answerable |
| 6 | **No PPER identifier may be allocated** by the observing session |
| 7 | **No evidence may be assessed** by the observing session |
| 8 | **No governance decision, recommendation or arrangement selection** may be made or implied |
| 9 | Where a fact cannot be obtained through the authorised route, the correct outcome is a recorded limitation — **never a workaround** |

## 4. Controlled observation sample

**The sample contains no more than three items.** It is an **observation-control
mechanism only**.

> **The sample is not a publication selection.** No item is approved, governed,
> suitable, preferred or recommended by being sampled.

### 4.1 Selection rule

| # | Rule |
|---|---|
| 1 | Include the existing drawing PDF referenced by **PPER-001** if it remains visible and identifiable |
| 2 | Add **at most one** additional item, only where necessary to observe a materially different **declared file type or metadata surface** |
| 3 | Add **at most one** item with **at least two visible versions**, only where necessary for **PPQ-006** |
| 4 | **One item may satisfy more than one purpose** — prefer that over adding items |
| 5 | **Record the exact item and version identifiers before detailed inspection** |
| 6 | Do not describe a sampled item as approved, governed, suitable or preferred merely because it was selected |
| 7 | **Do not expand the sample merely to increase completeness** |
| 8 | If no eligible multi-version item is visible, **PPQ-006 returns `NOT OBSERVABLE WITH AVAILABLE TOOLING`**. **No version may be created** |

### 4.2 If PPER-001's item is no longer visible

Record that fact as a limitation and proceed under rules 2 to 4. **Its absence
from view is not evidence that it was moved, withdrawn or deleted** — absence of
observation is not observation of absence.

## 5. Expiry

This authorisation **expires** on the earlier of:

1. **the first authorised observation session having produced its completion
   report**; or
2. **withdrawal through a later controlled increment.**

**Expiry is automatic on the first condition.** It does not require a further
decision, and the authorisation does not renew. Any further observation requires
a **new** authorisation record with its own identifier.

## 6. Explicit non-effects

ROA-001 does **not**:

- authorise publication, or lift or vary the publication hold;
- resolve **GCR-005** or define any of its seven matters;
- close **GCR-006**;
- resolve **UD-001**;
- resolve **PM-1** to **PM-7**, all of which remain **UNRESOLVED**;
- resolve **PM-2**, which remains **GOVERNANCE DECISION REQUIRED** and is
  excluded from observation entirely (register §6, §10.3);
- select, prepare or recommend a publication arrangement;
- establish publication / exchange or recipient acceptance authority;
- establish any project standard;
- assess **PPER-001** to **PPER-003**;
- create any evidence entry — evidence is recorded only by a **later controlled
  increment**;
- create a tag, release or publication package.

## 7. What an answer will and will not establish

| An answer establishes | An answer does not establish |
|---|---|
| What was **visibly present or absent** at the time of observation | What is intended, governed, authorised or approved |
| What the tooling exposed or refused | That an unexposed capability is absent from the platform |
| A bounded, dated, account-limited factual record | Anything about authority, ownership or acceptance |

**Observation informs; decisions resolve.** No matter is resolved by this
authorisation or by anything it produces (register §5.2).

## 8. Decision statement

> ## **ROA-001 — AUTHORISE WITH CONSTRAINTS**
>
> One bounded, read-only Claude Desktop observation session is authorised for
> `PPQ-001` to `PPQ-007`, on the Harrismith Fire Station project, under the
> constraints in §3 and the sample rule in §4, expiring under §5.
>
> **No publication authority and no acceptance authority is assigned.**
>
> ## **PUBLICATION REMAINS NOT AUTHORISED — PUBLICATION HOLD ACTIVE.**

**Related records.** Register — `docs/Publication-Planning-Evidence-and-Observation-Control-Register.md`.
Brief — `docs/Claude-Desktop-Publication-Planning-Read-Only-Observation-Brief.md`.
Framework — `docs/Publication-Planning-Control-Framework.md`.
