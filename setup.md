# Setup and Operating Steps

## Prerequisites
- Defined competitor list in the premium, design-led HVAC diffuser segment
- Access to competitor websites, product pages, and public collateral
- Weekly owner for report generation and stakeholder review

## Recommended file set
- `competitor-monitoring-agent-master.md`
- `competitor-monitoring-agent-concept.md`
- `setup.md`
- `tod.md`
- `.cursor/rules/*.mdc`

## Setup steps
1. Confirm monitored competitors (3-10 companies).
2. Define source list per competitor:
   - Product pages
   - Press/news pages
   - Campaign/landing pages
   - Downloadable brochures/spec sheets
3. Create a tracking table with fields:
   - Week
   - Competitor
   - Finding headline
   - Evidence URL
   - Observation date
   - Category
   - Priority score
   - Confidence
   - Marketing action
   - Sales action
   - Status
4. Install the master prompt as the operating prompt.
5. Apply Cursor rules from `.cursor/rules`.
6. Run a pilot cycle and quality-check outputs.

## Weekly operating steps
1. Run monitoring once per week.
2. Capture only net-new competitor changes.
3. Validate evidence for each candidate finding.
4. Score findings using the concept model.
5. Select top 3 strategic moves.
6. Produce weekly summary and action tracker.
7. Run 15-minute stakeholder review call.
8. Assign action owners and deadlines.

## Weekly quality gate checklist
Before distribution, confirm:
- [ ] Every top finding has a primary source URL
- [ ] Evidence excerpt is included
- [ ] Priority score is shown with rationale
- [ ] Confidence level is shown
- [ ] Marketing and sales actions have owners
- [ ] Top 3 list is strategically meaningful, not noisy

## Operating cadence (recommended)
- Monitoring run: weekly
- Stakeholder review: weekly, 15 minutes
- Strategy calibration: monthly review of scoring quality

## Escalation rules
Escalate immediately if a finding is:
- Score >= 80
- High confidence
- Likely to affect active opportunities or upcoming campaign windows

## Minimal weekly output package
- 1-page weekly summary
- Top 3 ranked strategic moves
- Action tracker table with owners and due dates
- Watchlist of medium-priority signals
