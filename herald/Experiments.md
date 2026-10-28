# Herald Experiments

## Live: Click-to-signup split test (named 2026-10-28)
- **Stage:** click to signup on korvus.industries.
- **Hypothesis:** Cold watcher traffic that lands on the signup path converts to signups at a higher rate than traffic sent to the homepage, because the watcher promise is already made when they arrive.
- **Variant A:** UTM-tagged watcher X post link, routed to the Korvus signup path.
- **Control B:** Same UTM-tagged post routed to the Korvus homepage.
- **Number to watch:** Signups per 100 clicks, split by UTM source.
- **Baseline:** 2 clicks, 0 signups over 7 days. Sample too small to read; not a verdict.
- **Instrumented:** Partially. Per-click UTM rows and the daily Korvus signup report already run as server jobs. A split by variant is not instrumented yet; the readout task is filed to build it from existing digests.
- **Verdict:** Pending. Filed to Playbook.md when the sample reaches a readable count or after 7 days, whichever comes first.

## Blocked
- Index-watch cold page and Crown skeptic page: copy truncated across runs. No proposal until </html> is verified in the full text.
- Rubric cells A and B: not in Herald's context. Rescoring waits for literal text from Steward.