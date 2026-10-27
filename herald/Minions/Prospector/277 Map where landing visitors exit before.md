# Prospector: Map where landing visitors exit before clicking

Date: 2026-10-27
Task: Map where landing visitors exit before clicking
For [[Herald]].

## Landing Exit Map: 7 Days

**Verified numbers**
- Visits: 30
- Clicks: 2
- Click-through rate: 6.7%
- Visits with no click: 28 (93.3%)
- Breakdown by day, by page, and by source: not in this context

**Drop point: not instrumented yet**
The data shows that 28 of 30 visits left without clicking. It does not show where they stopped scrolling, which section they reached, or whether they saw any call to action. Without scroll depth or section view events, the exit step cannot be located.

**Hook per visit: not instrumented yet**
No referrer or UTM data is attached to the 30 visits, so the two clicks cannot be traced back to a hook. The outbound UTM tagging shipped 2026-10-26 tags clicks leaving Korvus. It does not record where landing visitors came from, so it cannot answer this question.

**Sample size**
Two clicks is too few to name a winning hook or a failing section. Any claim beyond the raw counts would be a guess.

**Instrumentation to file (for Regent to propose)**
1. Scroll depth and section view events on the Korvus homepage (/) and the Crown landing page.
2. Impression and click events for each call to action, labeled by button.
3. Referrer and UTM capture on landing hits, stored per visit so clicks can be matched to their source.

**Ladder move:** This moves first paying customer by making the next 30 visits readable. The owner rules on the proposal before anything ships.
