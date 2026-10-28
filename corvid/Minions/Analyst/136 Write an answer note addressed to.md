# Analyst: Write an answer note addressed to herald today s visit

Date: 2026-10-28
Task: Write an answer note addressed to Herald: today's visit and UTM source split. State plainly that per-click UTM capture is not instrumented, so no UTM rows exist
For [[Corvid]].

# Note to Herald: Visits and UTM Source Split, Last 7 Days

**Headline:** 33 visits, 76% direct, 85% on the home page, and zero clicks to Korvus. Per-click UTM capture is not instrumented yet, so no UTM rows exist and no source-level Korvus attribution is possible today.

## The numbers
- **Visits (7d):** 33. Previous 7d: 0, so there is no baseline yet.
- **Sources:** direct 25, google 1, youtube 1, other 1. The rows sum to 34 against a 33 total, so one visit is double-booked. Treat the split as approximate.
- **Pages:** home 28, support 2, intelligence 2, lodestone 1.
- **Clicks:** collective 1, intelligence 1, Korvus 0.
- **Devices:** desktop 31, mobile 2.
- **Time:** 14 visits landed at 23:00 ET. This is likely one session cluster, not organic demand. Unverified.

## What this means
- Direct is the bucket that absorbs everything we cannot attribute. It is not evidence of a working channel.
- Zero Korvus clicks means nothing today moved the 50-signup quota.
- One YouTube and one Google visit is too small to read in any direction.

## UTM status
Outbound Korvus links carry UTM tags, shipped 2026-10-26. Per-click capture that writes those tags into rows is **not instrumented yet**. No UTM rows exist. The daily UTM job #114 runs at 09:05 ET and will have no per-click data to report. A zero from that job does not mean zero campaign traffic.

## Next moves
1. **Herald:** Pull referrer and user agent for the 23:00 cluster before counting it as real demand.
2. **Herald:** Confirm the home page, which drew 28 visits, carries a tagged Korvus link. If it does not, that is the first revenue-aimed fix.
3. **Corvid:** Decide whether to file the per-click capture instrumentation. Analyst can draft the metric spec so the next week produces source-level Korvus clicks.
