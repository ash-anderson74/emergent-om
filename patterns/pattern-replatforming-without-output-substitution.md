# Pattern: Replatforming Without Output Substitution

### Context

An organisation is undertaking a **replatforming or core system replacement** initiative.

* The customer-facing behaviour is intentionally unchanged
* The primary goals are risk reduction, resilience, adaptability, or future optionality
* The work involves high uncertainty due to new architecture, integrations, data movement, or operational models

In this context, teams experience strong pressure to default to **output-based tracking** (features delivered, systems migrated, milestones achieved) because customer behaviour does not change and learning is harder to see.

***

### Problem

When replatforming work is framed primarily in terms of outputs:

* Progress appears binary (done / not done)
* Learning is postponed until late integration phases
* Risk remains opaque until cutover
* Schedules become proxies for confidence
* Leaders receive reassurance signals rather than risk signals

This often recreates deterministic planning dynamics _inside_ a change that is inherently uncertain.

***

### Forces

* Leaders want assurance that a critical system replacement is “on track”
* Teams feel compelled to demonstrate momentum
* Customers cannot provide behavioural feedback
* Failure modes are severe but delayed
* Success may look like “nothing happened”

These forces make feature delivery and migration counts feel like the safest available signals—even when they are misleading.

***

### Solution (EOM-Aligned)

Reframe replatforming **outcomes** away from delivered scope and toward **demonstrated system properties**.

In EOM terms:

* Outputs are treated as _means_
* Outcomes are defined as _changes in system risk, constraints, and future options_
* Learning is made visible through evidence of capability, not completion

The pattern replaces “how much did we deliver?” with:

> **What can the system now safely and reliably do that it could not do before?**

***

### Outcome Categories That Work for Replatforming

Valid outcomes typically relate to:

* **Risk retired** (known failure modes invalidated)
* **Resilience demonstrated** (safe degradation, rollback, recovery)
* **Reversibility achieved** (ability to pause or undo change)
* **Future speed enabled** (faster integration, change, or compliance)
* **Invariants preserved** (customer experience remains stable during change)

***

### OKR Examples (Good, Better, and Risky)

#### ❌ Output-Substituting Objective (Avoid)

**Objective**\
Migrate customers from the legacy platform to the new platform

**Key Results**

* Migrate 40% of customers
* Complete integrations A, B, and C
* Decommission legacy subsystem X

**Why this is weak in EOM terms**

* Assumes migration equals value
* Hides risk until late
* Rewards irreversible progress over learning
* Encourages speed over safety

This is a _project plan expressed as OKRs_.

***

#### ⚠️ Transitional (Sometimes Acceptable)

**Objective**\
Reduce dependency on the legacy platform without customer impact

**Key Results**

* Customers migrated in small, reversible cohorts
* No increase in customer-reported incidents during migration
* Rollback successfully exercised in production-like conditions

This is better—but still mixes outputs with learning signals.

***

#### ✅ Strong EOM-Aligned OKRs (Recommended)

**Example 1: Risk & Resilience Focus**

**Objective**\
Reduce systemic risk in the payments platform while preserving customer experience

**Key Results**

* Demonstrate failover to new platform without transaction loss
* Prove rollback can be executed within X minutes under load
* Validate parallel run accuracy within acceptable variance
* Zero net increase in customer support contacts during controlled migrations

Here, migration may happen—but it is not the _success measure_.

***

**Example 2: Future Optionality Focus**

**Objective**\
Enable safe and faster evolution of payment capabilities

**Key Results**

* Reduce time to onboard a new integration from X months to Y weeks
* Demonstrate independent deployment without coordination with legacy release cycles
* Successfully swap one integration partner without customer-visible impact

This makes replatforming legible as _capability creation_, not delivery.

***

**Example 3: Learning-Centred Objective (Early Phase)**

**Objective**\
Collapse uncertainty in the new platform before irreversible migration

**Key Results**

* Top 5 integration risks either validated or retired
* Data migration assumptions tested with real production subsets
* Regulatory and audit assumptions reviewed against actual platform behaviour
* Decision log shows at least one materially changed architectural decision

Notice: **no volume targets**, but plenty of evidence.

***

### So… Is “Number of Customers Migrated” a Valid KR?

#### Short answer: **sometimes, but rarely on its own**

#### It is valid **only if**:

* Migration is **incremental and reversible**
* It is explicitly framed as a _learning vehicle_, not progress
* It is paired with safety, rollback, and experience constraints
* Stopping or slowing migration is treated as a _success_, not failure

#### It becomes dangerous when:

* It is interpreted as value delivered
* Bonuses or status depend on hitting migration numbers
* It creates pressure to continue despite emerging evidence
* It substitutes for risk visibility

**Better phrasing if used at all:**

> “Customers migrated safely in cohorts sufficient to validate platform assumptions”

This keeps the KR subordinate to learning.

***

### Resulting System Behaviour (Why This Works)

When this pattern is applied:

* Bad news surfaces earlier
* Migration slows down before it becomes dangerous
* Leadership confidence becomes evidence-based
* Cutovers stop being acts of faith
* Teams optimise for safety and learning instead of momentum

Most importantly, **flow improves later**—because risk was collapsed early.

***

### Summary

Replatforming does not remove the need for outcomes.\
It changes _where outcomes live_.

In EOM:

* Customer behaviour may remain static
* But system behaviour must change measurably
* And learning, not delivery volume, is the honest progress signal

Migration is an activity.\
Risk reduction, resilience, and future adaptability are outcomes.

That distinction is what keeps replatforming truthful.
