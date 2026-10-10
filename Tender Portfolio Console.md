Checkpoint 2 · Stage 10 decision engine · i@work

# Which EU energy tenders should we bid on?

## Assumptions and constraints

Win and margin assumptions

Risk aversion

Score = expected profit − aversion × average of the worst 5% of outcomes.

Bid budget this cycle

Bids due within 14 days, max

Chance of winning more than we can deliver, max

Same 4,000 seeded scenarios as the Python engine. With the default settings, this page reproduces its selection exactly.

## Recommendation

## Total profit across 4,000 simulated outcomes

Recommended portfolio Bid on every eligible tender

## All 14 tenders from the live run

Select a row for reasons, conditions and the draft proposal outline. P5–P95 is the 5th to 95th percentile of profit for that bid on its own (dot: expected). \*Win chance is simulated and includes the chance of finishing the offer in time.

| Tender | Deadline | Value | Decision | Win chance\* | Exp. profit | P5–P95 | Loss | Portfolio |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |

## Bid authority approval

In production this step resumes the n8n Stage 10 Wait node. Nothing is submitted to the EU portal.

Rationale (required)

Waiting for a decision.

Gates: deadline after the assessment date, open procedure (not a prior-information notice), actionable status, value within the EUR 8M single-bid ceiling. Win probability and margin follow the Checkpoint 1 rules, or half the win probability and an 18% target margin in the conservative profile. Neither is calibrated with real bid outcomes yet.