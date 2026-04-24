# Competitor Monitoring Agent: Concept and Scoring Model

## 1) Purpose
This agent is designed to convert competitor change detection into practical commercial response for premium, design-led HVAC diffuser markets.

The agent is not a news feed. It is a signal filter.
Its value is in identifying strategic moves early and linking them to actions.

## 2) Concept model
The operating model follows a simple pipeline:

1. **Observe**
   - Track defined competitor sources weekly.
2. **Validate**
   - Confirm each finding with primary evidence.
3. **Score**
   - Rank signal quality and urgency.
4. **Translate**
   - Convert high-priority signals into marketing and sales actions.
5. **Review**
   - Align stakeholders on top 3 moves in a short weekly call.

## 3) Signal taxonomy
Classify findings into these categories:
- Product and portfolio change
- Pricing and commercial packaging
- Positioning and value proposition
- Design and architecture narrative
- Sustainability and certification claims
- Channel, distribution, and partnerships
- Campaigns and launch messaging
- Sales process and buyer journey content

## 4) What counts as meaningful change
A finding is meaningful when at least one applies:
- It changes customer decision criteria.
- It alters perceived premium or design differentiation.
- It impacts deal velocity, win-rate risk, or margin pressure.
- It introduces a claim likely to appear in sales conversations.
- It can trigger a campaign or enablement response within 30 days.

Non-meaningful changes should be archived without escalation.

## 5) Evidence model
### Required evidence fields
- Competitor
- Source URL
- Source type
- Observation date
- Change excerpt (quoted text/spec/price)
- Previous state reference where available
- Analyst confidence level

### Confidence guidance
- **High**: primary source with direct before/after evidence
- **Medium**: primary source present, before state partial or indirect
- **Low**: weak or incomplete support; keep on watchlist only

## 6) Priority scoring framework (0-100)
Use weighted sub-scores:

| Factor | Weight | Scoring question |
|---|---:|---|
| Strategic relevance | 30 | Is this directly relevant to premium, design-led HVAC diffusers? |
| Commercial impact | 25 | Could this affect revenue, margin, conversion, or deal dynamics? |
| Evidence quality | 20 | Is the evidence robust, current, and unambiguous? |
| Competitive urgency | 15 | Does this require response now or soon? |
| 30-day actionability | 10 | Can marketing/sales take concrete action quickly? |

Formula:

`Priority score = sum(weighted factor scores)`

Where each factor is scored on a 0-1 scale then multiplied by its weight.

## 7) Priority thresholds
- **High (80-100)**: escalate immediately, include in top 3
- **Medium (60-79)**: monitor actively and prepare assets/messages
- **Low (0-59)**: archive and revisit only if repeated pattern appears

## 8) Action conversion framework
For every high-priority finding, define two action tracks.

### Marketing action track
- Message response (website, campaign, content)
- Proof reinforcement (case studies, spec comparisons, design evidence)
- Offer response (bundle, launch, positioning shift)

### Sales enablement action track
- Talk-track update
- Objection-handling note
- Competitive battlecard update
- Opportunity targeting instruction

Each action must include:
- Owner role
- Immediate next step
- Deadline
- Expected outcome

## 9) Weekly operating cycle
1. Ingest and validate all new signals.
2. De-duplicate with prior reports.
3. Score and rank validated findings.
4. Select top 3 strategic moves.
5. Publish weekly summary and action tracker.
6. Review in 15-minute stakeholder call.

## 10) Quality controls
The report should fail quality review if any top finding:
- lacks a source URL,
- lacks a clear factual change statement,
- lacks score rationale, or
- lacks a defined owner for action.

## 11) Example scoring card
| Finding | Strat. (30) | Comm. (25) | Evidence (20) | Urgency (15) | Actionable (10) | Total |
|---|---:|---:|---:|---:|---:|---:|
| Competitor launches architect-focused premium diffuser line | 26 | 21 | 18 | 12 | 8 | 85 |
| Competitor updates brand video style only | 8 | 4 | 15 | 3 | 2 | 32 |

## 12) Implementation notes
- Keep source tracking centralised in one spreadsheet or table.
- Maintain an archive of low-priority items for trend detection.
- Recalibrate factor scoring quarterly based on win/loss learning.
