# Pitch: Rerun click test sizing with the full table two funded

Date: 2026-11-13
Task: Rerun click test sizing with the full table, two funded options
For [[Herald]].

# Click Test Sizing: Full Table, Two Funded Options

**Status:** Sizing only. No spend is approved. Organic credit is **unverified** until Corvid's human-only count lands.

**Assumptions** (the truncated gist did not preserve the option definitions, so confirm these with Herald):
- Two variants (A and B), each needs **300 human visits** in a **14-day window**.
- Option A counts funded traffic only. Option B also credits organic baseline, assumed at about 13 visits per day and split evenly between variants.

## Option A: Funded Traffic Only

| Variant | Target human visits | Funded plan (14 days) | Funded per day | Organic credit | Net planned |
|---|---|---|---|---|---|
| A | 300 | 308 | 22 | 0 (not counted) | 308 |
| B | 300 | 308 | 22 | 0 (not counted) | 308 |
| **Total** | **600** | **616** | **44** | **0** | **616** |

Buffer: 2.7% above the 300-per-variant target, to absorb bot filtering and tracking loss.

## Option B: Funded Plus Organic (Organic Unverified)

| Variant | Target human visits | Organic credit (unverified) | Funded needed | Funded plan | Funded per day | Net planned |
|---|---|---|---|---|---|---|
| A | 300 | 91 (13/day x 14 x 50%) | 209 | 210 | 15 | 301 |
| B | 300 | 91 (13/day x 14 x 50%) | 209 | 210 | 15 | 301 |
| **Total** | **600** | **182** | **418** | **420** | **30** | **602** |

**Fallback:** If Corvid's count shows organic at zero, Option B reverts to the Option A plan of 616 funded visits (22 per variant per day).

## Detectable Lift at 300 Per Variant

Two-sided test, alpha 0.05, power 0.80. These are absolute percentage-point differences in click rate.

| Baseline click rate | Minimum detectable difference |
|---|---|
| 5% | about 5 points |
| 10% | about 7 points |
| 20% | about 9 points |

At 300 per arm, the test only reliably detects large swings. Small creative improvements will read as noise.

## Cost Line

Spend formula: funded visits x cost per visit. Cost per visit is **not instrumented yet**, so no dollar figures are quoted. Nothing is approved.

**Summary:** Option A plans 616 funded visits (44 per day total) with no organic credit. Option B plans 420 funded visits (30 per day total) plus 182 unverified organic visits, and falls back to Option A's 616 if organic does not verify. No spend is approved.
