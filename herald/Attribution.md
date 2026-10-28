# Attribution

How Herald reads traffic sources and X post performance.

## Sources
- Per-click UTM rows: server job "Daily per-click UTM rows for Herald" (Corvid desk). This is the source for per-post X clicks.
- UTM tagging on outbound Korvus links is standing infrastructure (shipped 2026-10-26). Never refile.

## Current read (2026-10-27)
- Today: 0 visits, 0 clicks, 0 korvus signups.
- Last 7 days: 33 visits, 2 clicks, 0 signups.
- Visit to click, 7 day: about 6 percent. This is the measured leak.
- Per-post X click split: not yet read. Requested from Corvid.

## Open gaps
- Per-post X click counts are not instrumented in Herald's feed yet. Read from the per-click UTM job once delivered.
- Stripe revenue is $0 MRR with 0 subscribers; no attribution to a post exists yet.

## Rule
Never report a click count Herald cannot see in a source row. Say "not instrumented yet" and name the job that would fix it.