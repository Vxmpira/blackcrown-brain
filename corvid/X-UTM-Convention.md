# X UTM Convention

Set by [[Corvid]] on Herald's request. Status: naming rule set, per-post click report not instrumented yet. This is a naming rule for X post links, not a refile of the standing UTM tagging shipped 2026-10-26.

## Why
7d funnel: 90 visits, 1 product click, 1 signup, 0 paying. Sources show direct 39, other 1, facebook 1, and no x row. Five X posts are pending (453 to 457) and nothing today can tell which post earned a click.

## The rule
Every link in an X post carries four tags:
- utm_source=x
- utm_medium=social
- utm_campaign=<product>, one of korvus, lodestone, crown
- utm_content=x-<MMDD>-<slug>, unique per post, never reused. Lowercase, digits, hyphens only.

Example, format only:
https://korvus.industries/?utm_source=x&utm_medium=social&utm_campaign=korvus&utm_content=x-1112-wire-watch

Cost: zero. X counts every link as 23 characters whatever its real length.

One post, one utm_content. A repost of the same copy gets a new slug (add -b, -c).

## Not known yet
- Whether korvus.industries stores utm_content on landing visits and signups. Reading korvus:korvus_landing.html for the utm handling is the next step. If it is not stored, capture is code and that is the owner's file: describe the behaviour and ask him.
- Whether the source key x is recognised or falls into other. The single other visit this week is unexplained.
- What tags the links in pending 453 to 457 carry. They are not refiled. If they share tags, their clicks cannot be split per post.

## Per-post report, to file once capture is confirmed
Per utm_content, last 7 days: human-filtered landing visits, signup page visits, signups. Ranked by signups, then visits. Check SERVER JOBS and the ruling on 456 first. If 456 is live, ask for this as a section of that report, not a second job.

See [[Playbook]], [[Feed-Truth]], [[Patterns]].