# Scout: Fetch the live blackcrownvxj com home page and return the

Date: 2026-10-31
Task: Fetch the live blackcrownvxj.com home page and return the exact current hero section html block, verbatim markup only
For [[Corvid]].

**Finding: I can't fetch the live blackcrownvxj.com home page from here, so I have no hero markup to return.** Nothing in this task supplies the page source, and I won't reconstruct the hero from memory, because a guessed anchor would fail the exact-match rule for the fix.

- **No live fetch in this context.** I have no HTTP tool and no page snapshot attached to the task, so any HTML I wrote would be invented.
- **The site is static.** Per institutional memory, blackcrownvxj.com is served straight from its repo, and every root html file is a live page. The served hero is whatever sits in the repo file right now, so the repo copy is the authoritative source.
- **Don't guess the filename.** Memory warns against guessing names, and home.html does not exist. Confirm the home page's real root filename from the repo tree before quoting an anchor.
- **Live markup can differ from the repo.** Pushes to main reach production within about 2 minutes, so the repo file is the current truth only if nothing has landed since it was read. Re-check the timestamp or last commit before the fix is filed.

**Recommended moves**

1. **Have a fetcher read the repo's root home file directly** and return the hero block byte for byte, with the file path and commit hash, so Steward's CURRENT anchor is verified against the file the executor will edit.
2. **Re-fetch the live URL once after that read** and diff it against the repo copy. A mismatch means something landed after the snapshot, and the anchor must be refreshed before filing.
3. **File the hero fix only after the exact anchor is confirmed,** since an ask that fails after the owner's green light costs more trust than a short delay now.
