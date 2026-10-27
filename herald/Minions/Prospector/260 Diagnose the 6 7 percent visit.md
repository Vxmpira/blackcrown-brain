# Prospector: Diagnose the 6 7 percent visit to click leak on

Date: 2026-10-27
Task: Diagnose the 6.7 percent visit-to-click leak on Korvus
For [[Herald]].

## Visit-to-click diagnosis: 7 days

**The leak: 93.3% of visitors leave without clicking** (28 of 30). The click rate is 6.7% (2 of 30), which matches the reported figure.

**Data I could not check**
- **UTM rows:** not in my context, so I cannot say which entry path or source loses visitors. I cannot rank paths.
- **Current korvus landing:** not supplied. I cannot audit the hook, headline, or CTA placement against the live page.

Per-path attribution is **not instrumented yet** in this report, and I will not guess at it.

**Sample size caveat:** 2 clicks out of 30 visits gives a 95% confidence interval of roughly 0% to 19%. A week of this traffic cannot separate a real problem from noise. Treat the 6.7% as a starting signal, not a verdict.

**Most likely single cause (hypothesis, unverified):** the first screen does not show the product in use. Cold visitors arrive, read copy, and cannot see the live terminal feed within a few seconds, so they have no reason to click. This fits the pattern of a near-total drop before any click. It is the first thing to confirm against the live page's above-the-fold content.

**Second leak to check next:** 0 of 2 clicks converted to signups. Once the pre-click problem is measured, check whether those 2 clicks reached /signup and where they dropped.

**Not instrumented yet, and the jobs that would fix that:**
1. Per-UTM visit and click breakdown. Needs the UTM rows pulled into one table (UTM tagging is already live, so this is a read, not a new build).
2. Definition of "click." It is unclear whether this counts the main CTA, the price button, or any link. Without a defined event, the 6.7% cannot be compared week to week.
3. Scroll depth on the landing, to see whether visitors reach the CTA at all.

**Next move:** pull the UTM rows for the same 7 days and split visits by source. If one source carries most of the 30 visits with zero clicks, that source is the leak and the hook fix targets that audience. Confirm the click event definition before any change ships, so the next week's number is comparable.

Ladder rung: first paying customer, through the Korvus signup quota (50 signups).
