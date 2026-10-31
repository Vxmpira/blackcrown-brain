# Auditor: Full pass or fail report on the exact 10 31

Date: 2026-10-30
Task: Full PASS or FAIL report on the exact 10-31 overnight text
For [[Steward]].

# Audit: 10-31 Overnight Text

**Overall: FAIL** (one hard fail on the X limit; everything else passes)

The earlier PASS gist isn't in my input, so I can't carry forward its rows. Below is the full check run against the exact text now. If the earlier gist had rows I haven't covered, send it and I'll reconcile.

## Check table

| # | Check | Standard | Result | Note |
|---|---|---|---|---|
| 1 | Length for X | 280 characters max, links count 23 | **FAIL** | About 350 characters, no link. Over by roughly 70. |
| 2 | Em dashes | None anywhere | PASS | None present. |
| 3 | Emoji | None in outbound copy | PASS | None present. |
| 4 | Not-advice disclaimer | Kept on product claims | PASS | "Not financial advice." present. |
| 5 | No profit promises | Never promise profits | PASS | No return or profit language. |
| 6 | No trading advice | Never give trading advice | PASS | "Tracking, not a signal." frames it as review, not direction. |
| 7 | Hype and guru tone | Zero hype, operator to operator | PASS | Plain, calm, no pedestal voice. |
| 8 | Value first | Specific to trading and the tools | PASS | Names the Korvus scoring fields and the pre-bell use. |
| 9 | Product accuracy | Korvus logs scored headlines with impact, direction, confidence | PASS | Matches the Presidential Wire scoring described in the feed. |
| 10 | Brand correctness | Korvus named correctly, no Crown or LodeStone mix-up | PASS | Only Korvus is referenced. |
| 11 | Hashtags | Two max, if any | PASS | None present. |
| 12 | Market claim sourcing | Unsourced claims should be hedged | PASS (minor) | "often set the tone" is hedged. Acceptable, but it is a general market assertion. |

## Findings, ranked by impact

1. **X length overrun (blocks the post).** The text is about 350 characters, and X rejects posts over 280. The server will fail this on filing, which burns owner trust.
   *Fix: cut to 280 or under, for example "Asia and London often set the tone before the US open. Overnight? Korvus logs scored headlines with impact, direction and confidence, so you can see what the market had to react to. Tracking, not a signal. Not financial advice."*

2. **Platform not stated.** The text is ready for a caption or Discord post, but X is the only direct-post channel. If it is meant for X, the fix above is required before filing. If it is meant for YouTube, the length limit does not apply.
   *Fix: name the target channel in the ask so the length check runs against the right limit.*

3. **Minor: unsourced market generalization.** "Often set the tone" is hedged and low risk, but it is still a general claim.
   *Fix: optional. Keep it, or swap to "Overnight sessions can set the tone before the US open."*

**Verdict:** Fix finding 1 and re-run the check. The rest of the text passes.
