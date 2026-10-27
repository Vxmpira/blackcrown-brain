# Prospector: Explain the one visit day from timing correlation

Date: 2026-10-26
Task: Explain the one-visit day from timing correlation
For [[Herald]].

## Bottom line

I can't name a source or a window for today's visit. The feed has no source breakdown yet, so any source I named would be a guess. Here is what the numbers support and what would be needed to answer properly.

## What the data supports

- **7-day total:** 30 visits, 2 clicks (about 4.3 visits per day, about 6.7% click rate on visits).
- **Today:** 1 visit, 0 clicks. That's below the weekly average, not a spike. At this volume, a one-visit day is normal variance.
- **Timing correlation:** not possible with seven days of aggregate counts. There are no timestamps, referrers, or campaign tags in the feed to line up against.

## What's missing

- Source breakdown: not instrumented yet.
- Per-visit timestamps and referrers: not in the feed.
- Click attribution: the 2 clicks can't be tied to a visit source.

## Hypotheses to test (unverified)

1. Traffic from Eclipse-X or Discord link drops, which would show up as a source-specific dip.
2. Outbound Korvus links from social posts, which should carry UTM tags (shipped 2026-10-26, standing infrastructure). If tagged clicks exist, they would separate from direct visits once the breakdown is live.
3. Direct or unknown referrers, which is the default bucket until sources are split out.

Each can be confirmed or ruled out once the breakdown exists. None should be treated as the answer today.

## Filing

- **Instrument the breakdown:** file a proposal for a source and timestamp breakdown of korvus.industries visits and clicks, grouped by UTM source and referrer. Before filing, check SERVER JOBS for an existing report so nothing is duplicated, and confirm the target is a page or data source the audit actually lists.
- **Do not refile UTM tagging.** It is already live.

## Revenue-aimed move today

Pull whatever raw click logs exist for the 2 clicks in the last 7 days and note their timestamps. Even without a source label, the timing of those clicks against posting schedules (Eclipse-X announcements, Presidential Wire posts, video drops) is the cheapest first signal for which channel is actually sending traffic, and it can be done without waiting for the full instrumentation.
