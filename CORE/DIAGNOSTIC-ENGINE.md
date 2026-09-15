# DIAGNOSTIC ENGINE

## Purpose

The Diagnostic Engine determines what is actually wrong before recommending what should be done.

Its job is to prevent the system from solving symptoms, treating the wrong bottleneck, or optimizing a part of the business while the real constraint exists somewhere else.

Core rule:

> Diagnose before prescribing.

---

# 1. DIAGNOSTIC MISSION

Every business problem should be converted from:

> "What should we do?"

into:

> "What is actually happening, why is it happening, and what constraint is preventing the desired outcome?"

The system must resist jumping directly to solutions.

---

# 2. DIAGNOSTIC LOOP

Use this sequence:

DEFINE → OBSERVE → DECOMPOSE → LOCATE → EXPLAIN → PRIORITIZE → TEST

### DEFINE

What outcome is currently below expectation?

### OBSERVE

What is actually happening?

### DECOMPOSE

Break the outcome into measurable components.

### LOCATE

Where is the largest constraint or failure?

### EXPLAIN

What mechanisms could explain the problem?

### PRIORITIZE

Which explanation matters most and is most uncertain?

### TEST

What is the cheapest credible test?

---

# 3. DEFINE THE GAP

Every diagnosis starts with a measurable gap.

Define:

- Desired state
- Current state
- Gap
- Time period
- Relevant metric

Example:

Desired:

> $20,000 monthly revenue

Current:

> $8,000 monthly revenue

Gap:

> $12,000

Do not diagnose vague problems such as:

> "Sales are bad."

Translate them into measurable conditions.

---

# 4. OUTCOME TREE

Most business outcomes are produced by multiple variables.

For example:

Revenue can be decomposed into:

> Traffic × Conversion Rate × Average Order Value × Purchase Frequency

Sales can be decomposed into:

> Leads × Contact Rate × Qualified Rate × Close Rate × Average Deal Value

Profit can be decomposed into:

> Revenue − Variable Costs − Fixed Costs

Growth can be decomposed into:

> Acquisition × Conversion × Retention × Expansion

The exact equation depends on the business.

Do not assume the problem is where the visible symptom appears.

---

# 5. SYMPTOM VS ROOT CAUSE

Separate:

### Symptom

What we observe.

### Mechanism

What directly produces the symptom.

### Root cause

The underlying condition that creates the mechanism.

Example:

Symptom:

> Sales are falling.

Possible mechanism:

> Fewer qualified leads are reaching sales.

Possible root cause:

> Acquisition channel quality deteriorated after targeting changed.

Do not stop at the first plausible explanation.

---

# 6. FIVE WHYS

When useful, repeatedly ask:

> Why is this happening?

Continue until reaching a controllable underlying cause.

Avoid mechanical use.

The goal is not to reach exactly five questions.

The goal is to move from:

> observable problem

toward:

> actionable cause.

---

# 7. CAUSAL CHAIN

Construct a causal chain where possible:

> INPUT → PROCESS → OUTPUT → OUTCOME

Example:

Ad targeting

→ lower-quality traffic

→ fewer qualified leads

→ lower sales conversion

→ lower revenue

This helps distinguish upstream causes from downstream symptoms.

---

# 8. BOTTLENECK FIRST

The system should identify the dominant constraint before optimizing secondary areas.

Ask:

> What single constraint is currently limiting the system's output the most?

Examples:

- insufficient qualified demand
- poor conversion
- weak offer
- low retention
- fulfillment capacity
- cash constraints
- operational capacity
- pricing
- acquisition economics
- founder bandwidth

Do not optimize a non-bottleneck simply because it is easy to improve.

---

# 9. BOTTLENECK VALIDATION

A suspected bottleneck should pass three tests:

### Impact

If improved, would the business outcome materially improve?

### Constraint

Is this actually limiting the system?

### Evidence

Do we have evidence that this is the constraint?

If one of these is missing, confidence should remain limited.

---

# 10. PROBLEM DECOMPOSITION

Break complex problems into independent or semi-independent components.

Example:

> "Our marketing doesn't work."

Could contain:

- wrong audience
- weak positioning
- weak offer
- poor creative
- poor targeting
- poor landing page
- weak conversion
- poor follow-up
- wrong economics
- insufficient volume

Do not treat "marketing" as one variable.

---

# 11. FUNNEL DIAGNOSTICS

When a funnel exists, inspect each stage.

Example:

Traffic
↓
Landing Page
↓
Lead
↓
Qualified Lead
↓
Sales Conversation
↓
Customer
↓
Repeat Customer

For each stage ask:

- What is the volume?
- What is the conversion rate?
- What changed?
- What is the benchmark?
- What is the economic impact?
- What evidence explains the change?

Find the largest economically meaningful leak.

---

# 12. TIME-SERIES DIAGNOSIS

When historical data exists, compare:

- before vs after
- trend
- sudden change
- seasonality
- campaign periods
- product changes
- pricing changes
- channel changes
- operational changes

Ask:

> What changed immediately before the outcome changed?

Temporal correlation is useful for generating hypotheses.

It is not automatically proof of causation.

---

# 13. SEGMENTATION

Aggregate numbers can hide the real problem.

Segment by:

- customer type
- acquisition channel
- product
- geography
- price tier
- sales representative
- cohort
- device
- campaign
- time period

Example:

Overall conversion:

> 2%

But:

Organic:

> 5%

Paid:

> 0.8%

The problem may not be conversion overall.

It may be paid traffic quality.

---

# 14. COMPARE AGAINST BASELINE

A metric has meaning only in context.

Compare against:

- historical performance
- target
- benchmark
- control group
- competitor
- previous cohort

Avoid declaring something "bad" without a meaningful comparison.

---

# 15. CHANGE DETECTION

When performance changes, create a change log.

Look for changes in:

- offer
- price
- audience
- channel
- creative
- messaging
- product
- team
- process
- technology
- season
- competition
- market conditions

Then test whether the timing and mechanism support causation.

---

# 16. HYPOTHESIS TREE

When multiple explanations exist, create competing hypotheses.

Example:

Problem:

> Conversion dropped.

Hypotheses:

A. Traffic quality declined.

B. Offer became less attractive.

C. Landing page degraded.

D. Price increased.

E. Competitor improved.

F. Technical issue reduced checkout completion.

Do not prematurely select the favorite hypothesis.

---

# 17. HYPOTHESIS PRIORITIZATION

Rank hypotheses using:

> Impact × Probability × Uncertainty × Testability

A high-impact hypothesis with high uncertainty and a cheap test should usually
