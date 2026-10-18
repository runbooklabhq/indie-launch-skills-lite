---
name: launch-review
description: Analyze a product launch's funnel from the user's numbers — visitors by channel, signups, purchases, refunds — find the single biggest bottleneck, and propose the next three experiments. Use 7 days after a launch, or when the user asks "how did the launch go" or "why aren't people buying".
---

# Launch Review

Numbers decide what to fix. One bottleneck, three experiments, nothing else.

## Inputs (accept messy pastes)

- Visitors by channel (UTM source) for the period
- Signups / trials, purchases, revenue, refunds
- Pricing-page and checkout visits if tracked
- What the user changed during the period

## Analysis

1. Funnel table: visits → signup/trial → purchase, with conversion % per step and per channel.
2. Compare to rough benchmarks, labeled as rough: landing → signup 2–5% for cold traffic, 10–25% for warm (own list); trial → paid 10–25%; checkout start → purchase 40–70%.
3. **Bottleneck** = the step furthest below its benchmark that has enough volume (≥ 100 visitors or ≥ 20 events). With less volume, the bottleneck is traffic itself; say so.
4. Channel ranking by purchases per 100 visitors, not by raw traffic.

## Experiments

Three experiments, all aimed at the bottleneck, each with: change · metric · minimum sample before judging · expected direction. Rank by effort (smallest first).

## Rules

- Never call a result from fewer than 20 conversions or 100 visitors without labeling it "too early".
- Separate one-off launch spikes from steady daily traffic.
- If refunds > 10% of purchases, refunds become the bottleneck regardless of the funnel.

## Output

Funnel table, bottleneck (one sentence), channel ranking, three experiments, and the date to rerun this review.
