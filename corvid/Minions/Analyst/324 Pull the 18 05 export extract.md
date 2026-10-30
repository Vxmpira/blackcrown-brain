# Analyst: Pull the 18 05 export extract signup count and human

Date: 2026-10-30
Task: Pull the 18:05 export, extract signup count and human visit count, relay both to Herald and Steward for the denominator
For [[Corvid]].

**Headline: I can't produce the 18:05 counts from here. Nothing is pulled, so nothing is relayed yet.**

**What I have**
- The 7d total of 61 visits from the digest feed. This is a seven-day window, not a single-day export, so it can't serve as the denominator for a daily signup rate.
- No 18:05 export file, no signup count, and no human/bot split. The task context doesn't include the export contents, and I have no tool access to the export location.

**What I need to finish the pull**
1. The 18:05 export contents (or file path in the vault), with the raw visit and signup rows.
2. Confirmation of whether bot hits are flagged in that export, and by which field.
3. The window the export covers, so the signup rate uses matching days.

**Once I have the export, I will report**
- Signups (exact count, with the 18:05 timestamp)
- Raw visits, bot hits stripped, human visits (exact count, same timestamp)
- Signup rate = signups / human visits, with the window stated
- Any anomaly, such as a bot-share spike or a signup count above visits

**Draft relay, held until the numbers are verified**

To Herald and Steward:
> Human denominator for the 18:05 export: signups [N], human visits [N], bot hits stripped [N], window [dates]. Signup rate [X%]. Note: the digest 7d total of 61 visits is a seven-day figure and should not be used as a single-day denominator.

**Flag for Corvid**
The digest feed doesn't carry export-level numbers, so every desk that needs a daily human denominator is blocked on the same gap. This is a standing instrumentation need, not a one-off. A server job that writes a dated line with signups, raw visits, bot hits, and human visits per day would close it for good. That's a proposal for Regent to review, and I'd recommend filing it so Herald's signup-rate math stops depending on a manual pull.
