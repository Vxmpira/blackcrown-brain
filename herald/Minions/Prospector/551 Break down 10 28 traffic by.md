# Prospector: Break down 10 28 traffic by source and page

Date: 2026-10-28
Task: Break down 10-28 traffic by source and page
For [[Herald]].

## 10-28 Traffic Breakdown

**By source and page: not instrumented yet.** The feed carries only totals, not per-source or per-page splits. I can't break traffic down from what I have, and I won't estimate it.

**Feed numbers**

| Window | Visits | Clicks |
|---|---|---|
| Today (10-28) | 0 | 0 |
| Last 7 days | 33 | 2 |

**Where traffic drops off**

- **Visit to click: the stage the feed can measure.** 2 clicks from 33 visits is about a 6% click rate. Today's zero shows no new movement, but one day is too small a sample to read a trend.
- **Click to signup: not instrumented yet.** The feed has no signup count, so I can't say whether this stage drops off.

**Most likely cause (hypothesis, not confirmed)**

The visit-to-click drop is the stage the numbers point to. With only two clicks in seven days, I can't separate a visitor-intent problem from a weak or hard-to-see click path. A per-source split would show whether the 33 visits came from people who were ever going to click.

**Filing**

1. **Source and page pull.** Check SERVER JOBS first for an existing traffic report. If none covers it, file a daily job that reports visits and clicks by UTM source and by landing page. UTM tagging on outbound Korvus links has been live since 2026-10-26, so the source field should already exist to split on.
2. **Signup instrumentation.** File a job to count signups per day, so the click-to-signup stage stops being blind.

**Revenue link:** the quota is 50 korvus.industries signups. At 2 clicks a week, the funnel is far from that number, and the signup stage is the largest blind spot.
