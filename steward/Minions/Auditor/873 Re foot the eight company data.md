# Auditor: Re foot the eight company data lines and state variance

Date: 2026-11-13
Task: Re-foot the eight COMPANY DATA lines and state variance to header
For [[Steward]].

**Re-foot: COMPANY DATA (8 lines)**

| # | Line | Value |
|---|------|------:|
| 1 | regent | 0.16 |
| 2 | corvid | 4.06 |
| 3 | bard | 0.05 |
| 4 | herald | 0.06 |
| 5 | bard-minions | 0.01 |
| 6 | steward | 0.08 |
| 7 | herald-minions | 0.04 |
| 8 | steward-minions | 0.01 |
| | **Computed sum** | **4.47** |
| | **Header** | **4.46** |
| | **Variance (sum minus header)** | **+0.01** |

Source: the eight lines as given in this task only. No relayed or earlier re-foot figures were used.

**Findings, ranked by impact**

1. **Header is 0.01 below the sum of its lines (variance +0.01).** Impact is low in value but high in trust, since the header is the figure the owner reads. Fix: pull the unrounded values for all eight lines and re-foot before the header is quoted again.

2. **The eight lines are rounded to the cent, so the variance may be rounding, not a booking error.** Each rounded line can be off by up to 0.005, so the eight together can drift up to about 0.04 from the true total. A 0.01 gap sits inside that band. Fix: have the header computed from unrounded source values, or state the rounding tolerance next to the header.

3. **No check exists to catch this automatically.** The header is not tied to its lines by any footing step, so a drift like this would go unnoticed until someone re-foots by hand. Fix: add a footing check that compares the header to the sum of its lines and flags any variance above 0.04 (the rounding tolerance).
