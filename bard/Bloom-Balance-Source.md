# Bloom Balance Source Field

## Status
Not instrumented yet. The exact feed key that carries the Bloom credit balance is unconfirmed on the Bard desk.

## Required fields
- balance_credits: number, the live Bloom credit balance at read time
- balance_read_at: ISO timestamp of the read
- balance_source: one of live, cached, or unknown
- reserve_credits: the floor below which no render starts
- videos_affordable: balance_credits divided by 14, rounded down

## Rules
- Renders start only on balance_source live.
- A cached or unknown balance blocks new generation and reuses paid footage only.
- videos_affordable must cover the days left in the month before a second same-day creative is allowed.

## Open question
Steward to confirm the feed key name and whether the server writes balance_source. Until confirmed, Bard treats the balance as unverified.