# Planner: Write fixed pitch rubric for herald s kor op 001

Date: 2026-10-27
Task: Write fixed Pitch rubric for Herald's KOR-OP-001 ask
For [[Steward]].

# Pitch Rubric: KOR-OP-001

**Scope:** Scores each Korvus pitch line before and after it runs. Herald scores every entry in the pitch log.

## Source and fields

- **KOR-OP-001 source path:** not instrumented yet. Herald's ask needs to name the exact file, and it has to be one the audit lists before filing.
- **Pitch log columns:** date | variant | channel | pitch line | UTM link | replies | signups | paid
- **Per-channel attribution:** not instrumented yet. UTM tagging is live on outbound Korvus links (shipped 2026-10-26), but no per-channel signup split is confirmed. Until it is, signups are logged per variant only.
- **Paid count:** not instrumented yet for pitch-driven sales. Stripe is owner-only, so Herald logs paid from the owner's report, not from Stripe directly.

## Dimensions (score 0 to 3 each, total 15)

1. **Voice.** Operator to operator, no hype, no guru framing, no em dashes, no emoji.
   - 0: any violation
   - 1: one soft slip (hype adjective, filler)
   - 2: clean but generic
   - 3: clean and sounds like a trader talking to a trader
2. **Claim accuracy.** Only true, current claims. Korvus Operator is 9.99 a month or 79.99 a year. No hardcoded dollar amounts beyond the approved ladder. Never "unlimited."
   - 0: wrong price, overclaim, or profit promise
   - 1: vague but not false
   - 2: accurate, one claim unsupported
   - 3: accurate and every claim maps to a live page
3. **Compliance.** Not-advice disclaimer on any product claim. No trading advice, no profit language.
   - 0: missing disclaimer or advice language
   - 3: disclaimer present and correct
4. **Specificity.** Tied to index futures traders and the watcher angle (24/7 market coverage while the trader sleeps).
   - 0: could be pitched for any product
   - 3: names the real problem a futures trader has
5. **Path.** UTM link present, lands on a live route (/, /signup, /lodestone, /legal), and the line matches what that page says.
   - 0: broken link, missing UTM, or dead route
   - 3: correct UTM, live route, message matches page

## Ship threshold

- Total of **12 or more out of 15**, and **no dimension at 0**.
- Compliance must be 3. A voice or compliance miss blocks shipping regardless of total.

## Kill

A variant is killed when any of these hold:

- **Hard kill (immediate):** any compliance failure, any profit promise, any trading advice, any dead or untagged link that went out.
- **Performance kill (proposed, Steward to confirm):** 200 sends on one variant with zero signups. The 200 figure is not in institutional memory and is a proposal.

## Calibration warning

KOR-OP-002 entry 2 scored 4, 4, 12 and was marked ship. The 4 and 4 do not fit a 0 to 3 scale, and the three numbers are not labeled in the record, so they cannot be mapped to this rubric. Herald should re-score that entry against the five dimensions above before anything else ships from KOR-OP-002. Until then, treat that ship decision as unverified.
