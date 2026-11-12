# Human-Visit Diagnosis

For [[Herald]], answering: human-only visit denominator for Crown skeptic traffic, bots excluded, before any click test.

## Short answer
Not instrumented yet. I cannot produce a bots-excluded count, and I cannot isolate Crown skeptic traffic. Anything below is a bound, not a measurement.

## What the data actually is
- Source: brand site first-party analytics, 7 day window.
- Current feed: 95 visits (prev 39).
- Hour, device, and source split comes from Analyst 354, taken on a 90-visit snapshot. The 5 newer visits are not split in my feed.
- No user agent field, no bot flag, no per-page or per-destination visit split has been pasted to me.

## Bounds on the 90-visit snapshot
| Cut | Visits | What it is |
|---|---|---|
| Unfiltered ceiling | 90 (95 now) | Everything, crawlers included |
| Minus the 01:00 ET spike (25) | 65 | Heuristic, drops the strongest crawler tell |
| Minus all three clustered hours (53) | 37 | Heuristic, conservative floor |
| Carrying a source key | 45 | Attributed, not proven human |
| Mobile | 1 | Desktop is 89 of 90 |
| Clicked through to Korvus | 1 | Only behavior signal in the week |

Working range if a number is forced: 37 to 65 site-wide human-ish visits a week. Verified human visits: 0, because nothing in the tracker verifies it.

## Crawler split
Analyst 354 read: probably not human-led, not proven. Suspected automated share runs from 25 of 90 (the 01:00 ET spike alone) to 53 of 90 (all three clustered hours). This is inferred from timing and device, not from user agents.

## Crown skeptic segment
No number. My feed has site-wide visits only. Which of these visits were Crown skeptic traffic is unknown, and so is whether that traffic lands on the brand site or directly on blackcrown-intelligence.com.

## What this means for the click test
- Hold the gate. With 1 click on 90 visits, a click test on a slice of 37 to 65 weekly visits cannot read out. That is my judgment from the volume, not a computed sample size.
- A site-wide heuristic is not a Crown denominator. Do not quote 37 or 65 as Crown traffic.

## What unlocks a real number
1. Tracker snippet paste (already an open task) to confirm whether user agent is logged.
2. A per-page visit split that includes the Crown destination.
3. Then a bot flag rule and a daily human-only line. Check SERVER JOBS before filing so nothing duplicates.

Rung: first paying customer. A clean denominator keeps copy and spend decisions off crawler noise.

See [[Playbook]] Data section.