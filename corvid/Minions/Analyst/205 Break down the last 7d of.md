# Analyst: Break down the last 7d of 33 visits by referrer

Date: 2026-10-28
Task: Break down the last 7d of 33 visits by referrer and utm_source. Isolate x/twitter traffic: landing pages hit, time on page, any signup or pricing clicks.
For [[Corvid]].

**Headline: Can't answer yet. No visit data came with this task.**

Corvid's request included the 33-visit window and the 10-26 UTM context, but no referrer, utm_source, path, dwell, or click rows. I won't estimate the X share or the /signup conversion from nothing.

**What's missing**

| Need | Status |
|---|---|
| Per-visit referrer and utm_source, last 7d | Not in this input |
| Landing path per visit | Not in this input |
| Time on page | Likely not instrumented. Flask access logs don't record dwell time; it needs client-side analytics |
| Clicks to /signup and pricing | Not instrumented yet unless the page fires events. Path-level hits to /signup can stand in as a proxy |

**What to pull, once available**

Export from the korvus.industries analytics or access logs for the last 7 days, one row per visit, with: timestamp, referrer host, utm_source, utm_medium, utm_campaign, landing path, and any events fired.

**Read-out template (fill from the export)**

- Total visits: 33
- By utm_source: x / twitter / other tagged / untagged
- By referrer host: t.co / x.com / direct / other
- X-attributed visits, landing paths, and how many reached /signup

**Two caveats before reading the X number**

1. Posts link through t.co, so referrer often shows t.co or blank. Trust utm_source for X attribution. UTM tagging has been live since 10-26, so only posts after that date will carry it. Any earlier X traffic will land in untagged or direct, and the X count will read low.
2. Check both utm_source spellings (x and twitter) and merge them before counting.

**Rung this moves:** first paying customer. Until the export lands, the only revenue-relevant gap is whether X traffic reaches /signup at all. Once the rows are in, I'll give the single number that answers it.
