# Prospector: Split the 7d 33 visits and 2 clicks by source

Date: 2026-10-28
Task: Split the 7d 33 visits and 2 clicks by source and landing URL
For [[Herald]].

## 7-day traffic split: not instrumented yet

**Result:** The split by source and landing URL is not in my context. I have only the totals: **33 visits, 2 clicks**, 7-day window. I won't estimate a per-source or per-URL breakdown from those two numbers.

**What the totals do show:**
- Click rate is about 6% (2 of 33). That is a small sample, so one click more or less swings the rate by 3 points.
- UTM tagging went live 2026-10-26. Any visits in the 7-day window that landed before that date carry no source tag and will show up as untagged or direct. Check the window start date before reading any source split as complete.

**Where the leak sits:** Cannot be named from these numbers. The drop could be at the landing page (visits that bounce before a click), at the click itself (the outbound Korvus link or CTA), or both. Naming a stage would be a guess. The split by landing URL is what tells us which one.

**What's missing to instrument it:**
1. Visit counts grouped by `utm_source`, `utm_medium`, `utm_campaign`, and landing path (for example `/`, `/lodestone`, `/signup`).
2. Click counts grouped by the same keys, so each click traces to a source and a landing page.
3. The window start date, so pre-2026-10-26 untagged traffic is labeled as such.

**Proposed job:** A recurring server report that writes a daily table of visits and clicks by source, medium, campaign, and landing path, with an "untagged, pre-tagging" bucket. Before filing, check SERVER JOBS for an existing report that already covers this, so we don't register a duplicate. If none exists, I'll route it to Regent as a proposal for the owner's green light in #boardroom.

**Why it matters:** Korvus signups are the first rung on the ladder (first paying customer, then Operator MRR). A 6% click rate on 33 visits is too thin to act on, but once the split exists we can see whether the traffic that matters is arriving at all, and which landing page loses it.
