# CORE™ Automation Register v1.0

## 1. Purpose

The CORE Automation Register is the control document for the automations currently associated with the CORE demand, content and LinkedIn operating system.

It records what each automation does, where it sits in the wider CORE system, what it takes as input, what it produces, and where human judgment remains necessary.

This is a register, not a redesign of the automations.

---

## 2. Current Automation Set

The current CORE automation set identified in the existing architecture contains six LinkedIn/content-related workflows:

1. LinkedIn Post Generation & Approval on Gmail
2. LinkedIn Post Creator from Newsletter
3. LinkedIn Post Engagement Counter
4. LinkedIn AI Content Automation — Agentic Vibe
5. LinkedIn Post Commentors Scraper using Apify
6. LinkedIn Post Creator by Researching Other Creators' Posts

These remain separate automations unless and until the source workflows themselves are intentionally redesigned.

---

## 3. Automation Register

| ID | Automation | Primary Job | Inputs | Output | Human Judgment | CORE Layer |
|---|---|---|---|---|---|---|
| A01 | LinkedIn Post Generation & Approval on Gmail | Generate, review, approve and publish LinkedIn content | Scheduled trigger, content inputs, Google Sheets data, AI generation | Draft post, approval action, published post, tracking data | Approval / regenerate decision | Demand / Visibility |
| A02 | LinkedIn Post Creator from Newsletter | Convert newsletter material into LinkedIn content | Newsletter content and selected news items | LinkedIn post drafts | Selection and final editorial approval | Content + Demand |
| A03 | LinkedIn Post Engagement Counter | Record post engagement | Published-post records / Google Sheets rows | Engagement metrics appended to tracking sheet | Interpretation of performance | Demand / Visibility |
| A04 | LinkedIn AI Content Automation — Agentic Vibe | Produce and publish AI-assisted LinkedIn content | Topic inputs, generated content, image/SEO/hashtag inputs | LinkedIn post and associated creative | Topic/content approval where required | Content + Demand |
| A05 | LinkedIn Post Commentors Scraper using Apify | Surface people who comment on relevant posts | Target LinkedIn post URLs / Apify data | Profile name, profile URL, post URL, comment captured in Google Sheets | Decide relevance and whether/how to engage | Demand / Visibility |
| A06 | LinkedIn Post Creator by Researching Other Creators' Posts | Research external creator content for content intelligence | Other creators' posts / research inputs | Research material and post ideas | Strategic interpretation and adaptation | Demand / Visibility |

---

## 4. Automation Boundaries

Automation should perform repetitive processing, not replace CORE strategic judgment.

The following remain human-led unless explicitly redesigned:

- Which ICPs matter.
- Which signals are strategically meaningful.
- Which external conversations deserve attention.
- What the market observation means.
- Which idea is worth developing.
- Whether a piece of research supports a CORE point of view.
- Whether a post should be published.
- How a comment should be answered.
- Whether an engagement signal merits a relationship action.
- Whether evidence changes a decision.

---

## 5. Automation Flow

The current automations can be understood as a partial flow:

**RESEARCH / INPUT → CONTENT GENERATION → HUMAN APPROVAL → PUBLISH → ENGAGEMENT CAPTURE → INTELLIGENCE**

with two additional inputs:

**NEWSLETTER / MARKET MATERIAL → CONTENT**

and

**EXTERNAL CREATOR POSTS → CONTENT INTELLIGENCE**

The complete CORE visibility system may eventually place an orchestration layer above these automations, but that orchestration is a future architectural layer rather than an assumption that it already exists.

---

## 6. Relationship to the CORE Visibility Objective

The existing LinkedIn objective is meaningful visibility among high-fit ICPs.

The automations support three visibility lanes:

### Own Content
Use A01, A02 and A04 to create and distribute CORE content.

### Borrowed Attention
Use A05 to discover relevant conversations and participants around other people's posts.

### Relationship Visibility
Use engagement and conversation signals to determine where human interaction is warranted.

A03 provides measurement input rather than visibility by itself.

---

## 7. Measurement

The automation system should distinguish between:

### Observable Metrics

Metrics that the workflows can directly record, where available:

- Posts published
- Likes
- Comments
- Other available engagement fields
- Commenter profiles captured
- Profile URLs captured
- Post URLs captured

### Strategic Metrics

Metrics requiring interpretation beyond raw automation output:

- Quality of ICP exposure
- Relevance of conversations
- Strength of market signal
- Quality of relationship development
- Whether content is attracting the intended audience
- Whether engagement is creating meaningful conversations
- Whether visibility is contributing to demand

Do not treat engagement volume as equivalent to business impact.

---

## 8. Automation → Intelligence Loop

The strategic role of automation is not merely to publish more.

The intended learning loop is:

**AUTOMATE → OBSERVE → INTERPRET → DECIDE → ADAPT**

Examples:

- Engagement data can reveal which ideas attract attention.
- Comments can reveal language, beliefs, disagreement and problems.
- Creator research can reveal themes and framing patterns.
- Newsletter-derived content can surface market developments worth interpreting.

The interpretation step remains part of CORE judgment.

---

## 9. Human Approval Principle

Where an automation creates externally visible CORE communication, the system should preserve a clear human approval point unless the underlying operating specification explicitly authorizes autonomous publishing.

The objective is not maximum automation.

The objective is dependable execution without losing:

- judgment,
- positioning,
- credibility,
- contextual relevance,
- and relationship quality.

---

## 10. Current Architecture Status

### Existing

- Six LinkedIn/content automation workflows.
- Engagement tracking workflow.
- Commenter discovery workflow.
- Content generation workflows.
- External creator research workflow.

### Architectural Layer Still Needed

A higher-level **CORE Visibility Orchestrator** can eventually coordinate:

**ICP Intelligence → Visibility Priority → Content / Conversation Selection → Automation → Human Approval → Execution → Response → Relationship Update**

This should only be built after the underlying workflows and their inputs/outputs are clearly documented.

---

## 11. Governance

For every future automation, record:

- Automation ID
- Name
- Purpose
- Trigger
- Inputs
- Processing
- Outputs
- Destination
- Human approval point
- Failure / exception condition
- Measurement
- Upstream dependency
- Downstream dependency
- CORE OS layer
- Current status
- Owner

No automation should be treated as part of the CORE operating system merely because it exists technically. It must have a defined role in the architecture.

---

## 12. Source Discipline

This register records the existing automation architecture at a control level.

It does not assume undocumented capabilities, integrations, autonomous decisions, or performance outcomes.

Where implementation details are not established in the source material, they should be documented only after inspecting the underlying workflow.
