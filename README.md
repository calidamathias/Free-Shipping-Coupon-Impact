# Free-Shipping Coupon Impact (RCT Benchmark + Matching)

## Goal
Estimate the causal effect of an intervention using an RCT benchmark and compare it to an observational approach using matching.

## What’s inside
- **report.qmd**: Full analysis in Quarto (R)
- Matching + balance diagnostics
- Treatment effect estimation and interpretation

## How to run
1. Open `report.qmd` in RStudio
2. Render:
   - In terminal: `quarto render`
   - Or click **Render** in RStudio

## Methods used
RCT, Matching, balance checks, ATE estimation

## Key Takeaways
- RCT benchmark provides a clean causal estimate.
- Matching reduces imbalance compared to naive observational comparisons.

## Assumptions & Diagnostics
- RCT: balance checks confirm randomization.
- Matching: overlap + covariate balance checked post-match.

## Reproducibility
Run `quarto render` to reproduce the report end-to-end.
