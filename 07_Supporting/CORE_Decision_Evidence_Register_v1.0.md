# CORE™ DECISION + EVIDENCE REGISTER
## Version 1.0

## Status

**Operational register.**

This document records the decisions, evidence requirements, evidence generated, and decisions resulting from CORE work.

It does not replace the **CORE Evidence Selection Architecture** or the **CORE Golden Thread — Strategic Thinking OS**. Those documents govern the method and logic. This register governs the **record of what was decided, why evidence was required, what evidence was generated, and what changed as a result**.

---

# 1. PURPOSE

The Decision + Evidence Register answers six questions:

1. What decision are we trying to make?
2. What uncertainty prevents a responsible decision?
3. What evidence do we already have?
4. What evidence is missing?
5. How will the required evidence be generated?
6. What decision changed because of the evidence?

The core discipline is:

> **Do not start with a test. Start with the decision and the evidence required to make it.**

---

# 2. GOVERNING LOGIC

CORE uses the following sequence:

```text
DECISION
   ↓
PROBLEM / OPPORTUNITY
   ↓
WHAT WOULD HAVE TO BE TRUE?
   ↓
CRITICAL UNCERTAINTY
   ↓
CURRENT EVIDENCE
   ↓
EVIDENCE GAP
   ↓
EVIDENCE REQUIRED
   ↓
EVIDENCE METHOD
   ↓
EVIDENCE GENERATED
   ↓
INTERPRETATION
   ↓
DECISION
   ↓
NEXT COMMITMENT
```

A test is therefore one possible **evidence-generation method**, not the starting point of the process.

---

# 3. RECORD TYPES

| Record type | Purpose |
|---|---|
| **Decision Record** | States the decision that needs to be made and the governing context |
| **Evidence Selection Record** | Defines the uncertainty, evidence requirement and selected evidence method |
| **Evidence Record** | Captures the evidence generated or retrieved |
| **Learning Record** | Captures what the evidence changed in our understanding |
| **Decision Outcome Record** | Captures the decision taken and the next commitment |
| **Proof Record** | Captures an outcome that may later become proof, a testimonial, case or teaching asset |

---

# 4. DECISION RECORD

Every material CORE decision should have a concise decision record.

### Minimum fields

```text
Decision ID:
Date:
Owner:
Context:
Problem / Opportunity:
Decision to be made:
Why the decision matters:
Decision horizon:
Current position:
What would have to be true?
Critical uncertainty:
Existing evidence:
Evidence gap:
Decision deadline / trigger:

Status:
- OPEN
- EVIDENCE IN PROGRESS
- READY FOR DECISION
- DECIDED
- PARKED
- CLOSED
```

### Decision quality gate

A decision is not sufficiently framed when it is only expressed as:

- “Should we launch?”
- “Do customers like it?”
- “Should we invest?”
- “Does this idea work?”

The record should identify the specific choice and the uncertainty that can materially change it.

---

# 5. EVIDENCE SELECTION RECORD

The detailed method is governed by the **CORE Evidence Selection Architecture**. The register stores the resulting case-specific record.

### Required fields

```text
Decision ID:
Problem:
Opportunity:
What Would Have To Be True?:
Critical Uncertainty:
Current Evidence:
Evidence Gap:
Evidence Required:
Evidence Source:
Method Options:
Selected Method:
Why This Method:
Evidence Generation Plan:
Evidence Standard:
Acceptance Criteria:
Decision Rule:
Stop Condition:
Owner:
Date:
```

### Governing question

> **What is the most credible way to generate the evidence required for this decision?**

---

# 6. EVIDENCE RECORD

Each material evidence item should be traceable to a decision and an uncertainty.

| Field | Record |
|---|---|
| Evidence ID | Unique identifier |
| Decision ID | Decision supported |
| Uncertainty | Critical uncertainty addressed |
| Evidence source | Where evidence came from |
| Evidence method | How it was generated/retrieved |
| Date | When obtained |
| Population / context | Who/what/context it relates to |
| Observation / result | What was actually observed |
| Interpretation | What the evidence means |
| Confidence / limitation | Important limitation or qualification |
| Relevance | Why it matters to the decision |
| Acceptance status | Meets / does not meet evidence standard |
| Link / reference | Source or supporting artifact |

The register should distinguish clearly between:

**observation → interpretation → implication**.

Do not record an interpretation as though it were an observation.

---

# 7. EVIDENCE METHOD TAXONOMY

CORE does not use a universal test catalogue. Evidence method selection is driven by the uncertainty and the required evidence.

Possible evidence-generation methods include:

| Method family | Typical use |
|---|---|
| Existing internal evidence | Use evidence already available inside the organisation |
| Secondary research | Industry, competitor, market, policy, technical or other existing evidence |
| Regulatory / policy research | Determine implications of rules, approvals, policy or institutional conditions |
| Expert interpretation | Access domain expertise where direct evidence is difficult or expensive |
| Customer / buyer conversation | Understand needs, priorities, constraints, language and stated behaviour |
| Observation | Examine behaviour in context rather than relying only on what people say |
| Commercial behaviour | Examine actual actions such as enquiries, responses, commitments or purchases |
| Technical demonstration | Establish whether a capability can perform in a relevant setting |
| Controlled experiment | Examine a causal relationship where experimental control is appropriate |
| Prototype / demonstration | Generate evidence around a concrete proposed solution |
| Field test | Generate evidence under realistic operating conditions |
| Pilot | Generate evidence through limited real-world deployment |

This list is illustrative, not mandatory.

The decision, uncertainty, evidence standard and feasibility determine the appropriate method.

---

# 8. EVIDENCE QUALITY GATE

Before evidence is treated as decision-relevant, check:

```text
□ The decision is explicit.
□ The critical uncertainty is explicit.
□ Existing evidence was checked first.
□ The evidence is relevant to the actual decision.
□ The evidence source is credible for the question.
□ The method is appropriate to the uncertainty.
□ The evidence standard is explicit.
□ Acceptance criteria are explicit where applicable.
□ The evidence could change the decision.
□ Important limitations are recorded.
□ The evidence was generated or interpreted with sufficient discipline.
```

The standard is not “more evidence”.

The standard is **decision-useful evidence**.

---

# 9. DECISION RULE

Every material evidence exercise should connect to a decision rule.

A decision rule states what the evidence will cause us to do.

Examples of decision categories:

```text
GO
PIVOT
PARK
STOP
REFINE
INVEST FURTHER
SEEK ANOTHER EVIDENCE SOURCE
```

These are decision outcomes, not a mandatory sequence.

The exact rule must be defined before evidence is interpreted when doing so is practical and appropriate.

---

# 10. STOP CONDITION

A stop condition prevents open-ended evidence gathering.

Possible bases include:

- the evidence threshold has been met;
- the uncertainty has been sufficiently reduced;
- a disconfirming condition has been observed;
- additional evidence would not materially change the decision;
- the cost of additional evidence exceeds its decision value;
- the opportunity has been parked or stopped.

A stop condition should be proportionate to the importance of the decision.

---

# 11. LEARNING RECORD

After evidence is generated, record what changed.

```text
Learning ID:
Decision ID:
Evidence IDs:
Initial belief:
Evidence observed:
What changed:
What did not change:
New uncertainty:
Implication:
Confidence:
Decision impact:
```

The learning record should answer:

> **What do we know now that we did not know before?**

and:

> **What decision does that knowledge change?**

---

# 12. DECISION OUTCOME RECORD

```text
Decision ID:
Evidence IDs:
Decision date:
Decision:
Rationale:
What was accepted as true enough:
What remains uncertain:
Next commitment:
Owner:
Review trigger / date:
Result status:
```

A decision is not complete merely because a meeting occurred. The register should capture the resulting commitment or deliberate non-commitment.

---

# 13. PROOF RECORD

Where a decision and its resulting action produce a meaningful outcome, create a proof record.

```text
Proof ID:
Decision ID:
Client / case context:
Starting condition:
Intervention / action:
Evidence:
Outcome:
Time period:
Business significance:
Permission status:
Potential proof use:
- Testimonial
- Case study
- Decision Autopsy
- Teaching case
- Executive Brief
- Other
```

Proof should be based on an observable result or credible evidence, not merely positive sentiment.

---

# 14. FOUR-CASE STRESS-TEST LENS

CORE has already stress-tested the evidence-selection logic across four problem dimensions:

```text
1. Startup / New Product
2. Existing Customer Problem
3. Technology Problem
4. Policy / Regulatory Problem
```

The purpose of the four-case lens is to prevent the system from assuming that all uncertainty should be addressed through customer interviews, prototypes or experiments.

Different uncertainty types require different evidence sources and methods.

The register should therefore always record **why the selected evidence method is appropriate**.

---

# 15. RELATIONSHIP TO THE GOLDEN THREAD

The register is one operating mechanism inside the broader CORE Golden Thread.

```text
STRATEGIC CHOICE
      ↓
PROBLEM / OPPORTUNITY
      ↓
WHAT WOULD HAVE TO BE TRUE?
      ↓
CRITICAL UNCERTAINTY
      ↓
EVIDENCE
      ↓
DECISION RULE
      ↓
DECISION
      ↓
COMMITMENT
      ↓
EXECUTION
      ↓
FEEDBACK
```

The register therefore records the portion of the Golden Thread where uncertainty is converted into evidence and evidence is converted into a decision.

---

# 16. RELATIONSHIP TO ₹499

The ₹499 **CORE Essentials — The Business Thinking Canvas™ System** prepares a signal into a structured opportunity and makes it ready for deeper testing.

The Decision + Evidence Register is primarily useful after the signal has been structured enough to define a meaningful decision and uncertainty.

It can therefore support the transition:

```text
SIGNAL
 ↓
CANVAS
 ↓
OPPORTUNITY
 ↓
DECISION / UNCERTAINTY
 ↓
EVIDENCE
```

It does not replace the ₹499 product.

---

# 17. RELATIONSHIP TO ₹39,999

The ₹39,999 Idea → Market system uses evidence to move a focal idea into real-market contact, learning and decision.

The Decision + Evidence Register should capture that operating trail:

```text
FOCAL IDEA
 ↓
WHAT WOULD HAVE TO BE TRUE?
 ↓
CRITICAL UNCERTAINTY
 ↓
EVIDENCE REQUIRED
 ↓
EVIDENCE METHOD
 ↓
EVIDENCE
 ↓
DECISION
 ↓
NEXT MARKET COMMITMENT
```

The register should not convert the programme into a generic experiment log. Its purpose is decision traceability.

---

# 18. RELATIONSHIP TO ₹5L / GOLDEN THREAD MANAGEMENT SYSTEM

At organisational level, the decision/evidence record becomes part of the management feedback loop.

```text
STRATEGIC CHOICE
 ↓
POLICY / DECISION RULE
 ↓
METRIC / SIGNAL
 ↓
VARIANCE / UNCERTAINTY
 ↓
EVIDENCE
 ↓
MANAGEMENT DECISION
 ↓
FRONTLINE ACTION
 ↓
FEEDBACK
```

Where the organisation uses Golden Thread dashboards, the register can provide the underlying decision and evidence history.

The exact dashboard implementation remains governed by the Golden Thread dashboard specification.

---

# 19. REGISTER TABLE

A master index can use the following columns:

| ID | Date | Client / Case | Transformation | Decision | Critical Uncertainty | Evidence Required | Method | Status | Resulting Decision | Next Commitment | Proof Potential |
|---|---|---|---|---|---|---|---|---|---|---|---|

Recommended status values:

```text
OPEN
EVIDENCE IN PROGRESS
READY FOR DECISION
DECIDED
PARKED
CLOSED
```

---

# 20. LINKED ARTEFACTS

Each register record should link where available to the relevant working artefacts:

- Business Thinking Canvas
- Evidence Selection Card
- research sources / secondary research
- interview / conversation notes
- observation notes
- prototype / demonstration material
- pilot / field-test records
- analysis
- decision record
- outcome record
- proof record

The register should remain a **control and traceability layer**, not a replacement for those detailed artefacts.

---

# 21. LEARNING LOOP

The value of the register compounds when repeated records are reviewed across cases.

```text
INDIVIDUAL DECISION
      ↓
EVIDENCE
      ↓
LEARNING
      ↓
PATTERN ACROSS CASES
      ↓
METHOD / OFFER / CONTENT IMPROVEMENT
      ↓
NEW CLIENT WORK
      ↓
NEW EVIDENCE
```

Potential learning categories include:

- recurring uncertainty;
- recurring evidence gaps;
- effective evidence methods;
- weak evidence methods;
- common decision errors;
- recurring opportunity patterns;
- recurring customer/buyer behaviour;
- recurring organisational constraints.

Patterns should only be promoted into CORE methodology when supported by sufficient experience or evidence.

---

# 22. GOVERNANCE RULES

1. Every material decision should have one identifiable Decision ID.
2. Evidence should be linked to the decision it informs.
3. Do not confuse evidence with interpretation.
4. Do not treat activity as evidence merely because an activity occurred.
5. Record limitations and uncertainty honestly.
6. Prefer existing credible evidence before generating new evidence when appropriate.
7. Select the method after identifying the evidence requirement.
8. Define the decision rule before interpreting evidence when practical.
9. Capture what changed because of the evidence.
10. Convert material outcomes into proof only when the evidence supports the claim.
11. Feed useful learning back into the Strategic Thinking, Offer, Content and Delivery systems.

---

# 23. MASTER PRINCIPLE

> **Evidence has value only when it helps make a better decision.**

CORE therefore does not optimise for the number of tests conducted, interviews completed, surveys collected or experiments run.

It optimises for the chain:

**Right Problem → Right Decision → Right Uncertainty → Right Evidence → Right Evidence Method → Better Decision.**
