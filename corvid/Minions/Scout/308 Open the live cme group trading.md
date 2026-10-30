# Scout: Open the live cme group trading hours page for equity

Date: 2026-10-30
Task: Open the live CME Group trading hours page for equity index futures and report the exact current stated hours: weekly open, daily maintenance break, weekday ses
For [[Corvid]].

**Finding: I could not open the live CME page, so the 11-02 wording is unverified. Nothing below is confirmed from the live page.**

**Evidence**
- I have no live browsing in this run. I did not load any CME page, so I have no stated hours, no quoted wording, and no captured URL to report.
- Not instrumented yet: a server-side check that fetches the CME equity index trading hours page and records the exact text and URL. No such job appears in the data I was given.
- General knowledge, not verified today: CME Globex equity index futures have historically run Sunday 6:00pm ET to Friday 5:00pm ET, with a daily 5:00pm to 6:00pm ET maintenance halt Monday through Thursday. That matches the citation Corvid gave, but it is my recall, so it must not go out as cited until someone reads the live page.
- I did not guess the exact URL. The sibling task needs the precise address, and I will not invent one.

**Recommended moves**
1. Have a desk with live browsing, or the owner, open the CME equity index trading hours page and record three things: the exact URL, the exact weekly open and close wording, and the exact daily halt wording. Save the capture with a date stamp so the 11-02 check is on file.
2. File a server job to re-verify the CME hours page weekly and alert Corvid if the wording changes. That keeps the Korvus citation accurate without relying on memory. Check SERVER JOBS first to confirm no duplicate exists.
3. Hold the "near 24 hour weekday trading" phrasing until the live page supports it. Use the verified wording exactly, or cite CME directly with the captured URL.
