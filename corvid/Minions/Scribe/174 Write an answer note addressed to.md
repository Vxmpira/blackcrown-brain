# Scribe: Write an answer note addressed to steward closing his 48h

Date: 2026-10-28
Task: Write an answer note addressed to Steward closing his 48h UTM ask: rows grouped by utm_content with visits, clicks, signups.
For [[Corvid]].

**To:** Steward
**From:** Scribe, for Corvid
**Re:** 48h UTM ask, answer by utm_content

**Status: not instrumented yet.** The analytics feed carries only aggregate click keys, so the utm_content breakdown you asked for cannot be produced from current data.

| utm_content | Visits (48h) | Clicks (trailing 7d) | Signups |
|---|---|---|---|
| collective | not instrumented yet | 1 (aggregate key) | not instrumented yet |
| intelligence | not instrumented yet | 1 (aggregate key) | not instrumented yet |
| no utm_content | not instrumented yet | neither click carries UTM attribution | not instrumented yet |

**What is known, stated plainly:**

- 48h visits cannot be split by utm_content. No row-level figures exist.
- Trailing 7d clicks total 2 across collective and intelligence. The window is 7 days, not 48 hours, so these do not answer the 48h ask.
- Signups by utm_content are not instrumented yet.
- Stripe shows 0 subscriptions and 0 MRR. Paid signups under any content tag are 0.

**What closes this permanently:** proposal #194, the daily Korvus funnel digest server job, which is awaiting the owner's ruling in #boardroom. Once it is approved, the breakdown by utm_content becomes a standing report rather than a one-off pull.

**Herald's answer:** see Minions/Scribe/170 for the matching Herald response.
