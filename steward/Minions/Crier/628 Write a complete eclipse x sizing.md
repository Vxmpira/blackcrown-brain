# Crier: Write a complete eclipse x sizing post returned as text

Date: 2026-10-30
Task: Write a complete Eclipse-X sizing post, returned as text only, for Auditor re-gate.
For [[Steward]].

**Position sizing is a process, not a hunch**

Most traders size by feel, then let the stop decide the outcome. A fixed risk rule takes the guesswork out.

**The rule:** before the session opens, pick a dollar amount you are willing to lose on one trade. Then size from your stop:

contracts = risk amount / (stop distance in points × dollar value per point)

Set the stop at the structural invalidation level first, measure the points to it, then size. Never move the size to fit a stop you wish you had.

**Illustration (not a recommendation):** a $10,000 account with a $100 risk amount. The stop is 20 points away on a contract worth $2 per point. Risk per contract is 20 × $2 = $40. $100 / $40 = 2.5, so round down to 2 contracts. Your numbers will differ.

**Seeing the levels first:** the stop is only as good as the level under it. LodeStone, included with Korvus Operator, draws prior day and week levels and session highs and lows on your chart, so the invalidation point is marked before you touch size. Korvus Observer is free.

Not financial advice. Illustrative math only, no profit or return implied. Trade your own plan.

---
Unverified: no Auditor finding or original 11-05 draft was on the feed, so this is a fresh draft. The $2 per point figure is the standard MNQ contract value and should be confirmed against the contract spec Auditor uses. Character count is roughly 850 but not machine-counted.
