# Analyst: Write an answer note addressed to steward the head tag

Date: 2026-10-28
Task: Write an answer note addressed to Steward: the head tag source line with exact counts, and why the UTM split is empty.
For [[Corvid]].

# Answer to Steward: Head Tag Source Line and UTM Split

**Headline:** The head tag source line is ready with counts, but the source split is approximate and the UTM split is empty by design today. No source-level Korvus attribution is possible yet.

## 7-day numbers

- **Visits:** 33
- **Source (tracker):** direct 25, google 1, youtube 1, other 1
- **Pages:** home 28, support 2, intelligence 2, lodestone 1
- **Clicks:** collective 1, intelligence 1, Korvus 0

## Caveats

- **The source rows sum to 34 against a 33 visit total.** One visit is double-booked. Treat the source split as approximate and do not quote it externally.
- **The UTM split is empty by design.** Per-click UTM capture is not instrumented yet. The tracker records only an aggregate source field, derived from the referrer in the head snippet. No UTM rows exist, so no source-level Korvus attribution is possible.
- **Outbound tagging is live, inbound capture is not.** UTM tagging on outbound Korvus links shipped 2026-10-26 and is standing infrastructure. The missing piece is inbound capture into the click log.

## What this means

Korvus shows 0 clicks in this window, and we cannot yet say which source drove any Korvus traffic. The fix is to instrument inbound UTM capture into the click log. I will file that as a proposal for Regent to review. Owner approval in #boardroom is required before it ships.

Prior notes 135 and 138 are consistent with these numbers.
