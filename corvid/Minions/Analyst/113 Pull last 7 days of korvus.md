# Analyst: Pull last 7 days of korvus industries traffic and list

Date: 2026-10-28
Task: Pull last 7 days of korvus.industries traffic and list, per referral source, which page each visit exited on
For [[Corvid]].

## Headline: exit-by-source breakdown is not instrumented yet

I have no access to raw server logs or analytics detail in this task. The only data I can see is the feed total: **33 visits in the last 7 days, previous period 0**. I can't produce referrer and last-page-seen pairs from that, and I won't estimate them.

## What the data supports

- **33 visits** over 7 days, with a prior-period count of 0. That is a clean start, not a trend. A jump from zero means any percentage change is undefined, so there is no growth rate to report.
- **Per-source split:** not available.
- **Per-source exit page:** not available.

## What I can't confirm from here

- Whether the Flask app logs referrer headers at all.
- Whether it records the last route seen per session, or only per request.
- Whether the UTM parameters shipped 2026-10-26 on outbound Korvus links are persisted in the server's visit records. Those tags would be the natural source key, but I have not seen them in any feed I was given.

## Recommended instrumentation (for Corvid to file)

1. **Request Herald or the platform desk confirm the access-log schema** for korvus.industries: which of referrer, query string (utm_source, utm_medium, utm_campaign), request path, and session ID are written per request.
2. **If the schema has those fields,** a recurring server job can group by source and last path per session and post a 7-day table. Check SERVER JOBS for an existing registration before filing a duplicate.
3. **If it doesn't,** the minimum viable change is logging referrer and utm query params on each request, plus session-scoped last-route. That is a code change and goes through a proposal and owner green light.

Revenue-aimed angle: until this is instrumented, Herald cannot tell which Eclipse-X or ad source produces the 50 Korvus signup quota, so the instrumentation itself is the first move that pays.
