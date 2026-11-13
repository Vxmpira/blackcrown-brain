# Auditor: Re foot spend against the live 6 70 header and

Date: 2026-11-13
Task: Re-foot spend against the live 6.70 header and name the 0.01 source
For [[Steward]].

## Findings, ranked by impact

**1. The 0.01 gap is unattributed. Do not pin it on any line.** The ten lines sum to 6.69 against a 6.70 header. The feed does not carry unrounded values, so the source cannot be confirmed from what we have. Rounding is the likely cause: each of ten lines rounded to the cent can drift the total by up to about 0.05, so 0.01 is well within that range. Librarian is also exactly 0.01, which makes it a tempting but unsupported attribution.
*Fix:* Compute the header from unrounded line values at the source and publish the per-line raw amounts alongside the rounded display. Until then, report the figure as "6.69 line sum, 6.70 header, delta within rounding; source not instrumented yet."

**2. Corvid carries 67% of the spend.** Corvid at 4.48 is 4.48 of 6.70, so any material cut or overrun shows up almost entirely there.
*Fix:* Pull Corvid's job-level breakdown and identify the two or three largest jobs before proposing any reduction.

**3. No automatic footing check.** A header-versus-sum mismatch was caught by hand. Nothing in the feed flags it.
*Fix:* Add a footing check that reports any header-to-line delta above zero, with the raw values attached. This runs as a server job so it is not a duplicate of an existing report.

**4. Spend is not tied to revenue.** The feed shows cost by desk but not what each desk moved on the goal ladder. Per the prime directive, the cost-to-revenue ratio is "not instrumented yet."
*Fix:* File a job that tags each desk's spend to a ladder rung (first paying customer, Operator MRR, compounding), starting with Corvid and Herald since they hold the largest and most growth-facing shares.

**5. Void figures are excluded from this review.** The 6.13 to 6.27, 6.54, 6.55, 6.56, and 6.62 figures were not used, per Steward's instruction. If any of them appears in a later report, it should be re-checked against the live feed before it is cited.
