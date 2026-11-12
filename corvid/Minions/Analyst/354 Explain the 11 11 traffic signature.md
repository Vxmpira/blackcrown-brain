# Analyst: Explain the 11 11 traffic signature and whether it is

Date: 2026-11-11
Task: Explain the 11-11 traffic signature and whether it is human
For [[Corvid]].

## Headline: Probably not human-led, but not proven. The 01:00 ET desktop spike is the tell.

## The numbers behind it

| Signal | Value | Read |
|---|---|---|
| Visits (7d) | 90 vs 39 prior (+131%) | Real lift, but the cause is unlabeled |
| Desktop share | 89 of 90 (99%) | Very unusual for social-driven traffic |
| No source key | 45 of 90 (50%) | Half the traffic is unattributed |
| Hour 01:00 ET | 25 visits (28%) | One off-peak hour holds more than a quarter of the week |
| Hours 10:00, 12:00, 01:00 | 53 of 90 (59%) | Heavy clustering, rest is single digits |
| Clicks to Korvus | 1 (1.1%) | Almost nothing progressed to the product |

## Answers

**1) Is this consistent with crawler or link-preview traffic from X posts?**
Yes, it is consistent with it. Link-preview fetchers and crawlers hit a URL once without a human click, usually send no referrer, and produce desktop-heavy, clustered hits that don't follow a human day curve. The combination of 99% desktop, 50% no source, a single 01:00 ET spike, and one click through to Korvus fits that pattern better than a human audience from 8 posts. Caveats: the data has no post timestamps, so I cannot tie the 01:00 spike to any specific post, and I cannot rule out a genuine overseas or late-night audience.

Slices that look more human: the 12:00 and 10:00 ET hours (17 and 11 visits, a plausible daytime pattern), and the 1 mobile visit, which is the only result that resembles a phone user. Treat these as possibly human, not confirmed. The facebook and other single visits are too small to read.

**2) Fields the tracker should capture to separate bots from humans:**
- User agent class (bot, crawler, desktop browser, mobile browser), since the current data shows only a device label
- Referrer, stored raw, including empty and t.co values
- UTM presence and values on landing (Korvus outbound links carry UTM since 2026-10-26, so a Korvus-bound human click from X should show a source; the 45 keyless visits are worth checking against that)
- Hit timestamp and gap to the previous hit from the same IP or session
- Pages per visit and session duration
- Whether JavaScript executed (bots that fetch HTML often never run scripts)
- Datacenter or ASN flag on the IP

Status: not instrumented yet for user agent class, raw referrer, and session behavior. File the instrumentation job before drawing conclusions from these numbers again.

**3) Verdict for the owner:**
Week 7 traffic reads as mostly automated, not as a human audience reacting to the X posts. The 90 visits (up from 39) are 99% desktop, half carry no source, and 28% landed in one off-peak hour at 01:00 ET, a shape that matches link-preview and crawler activity rather than people scrolling X. Only one visit clicked through to Korvus, so the posts have not yet produced measurable product interest. We cannot confirm the split between human and bot traffic because the tracker does not yet capture user agent class, raw referrer, or session behavior; that instrumentation is the next step, and the X post timestamps should be matched against the hour data before anyone credits the posts with the lift.
