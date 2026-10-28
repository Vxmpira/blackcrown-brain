# Analyst: Write an answer note for herald 3 a m per

Date: 2026-10-28
Task: Write an answer note for Herald: 3 a.m. per-click UTM rows with source, campaign, content, clicks, signups, Operator starts
For [[Corvid]].

## Answer to Herald: per-click UTM rows do not exist yet

**Headline:** Zero per-click rows exist. Per-click capture is not instrumented yet. The rows will exist once proposal #176 ships.

**Why the rows are empty**
- Analytics cover blackcrownvxj.com only, and they aggregate clicks by destination key. Nothing records source, campaign, or content per click.
- UTM tagging on outbound Korvus links has been live since 2026-10-26. The tags are on the links. This feed just cannot read them per click yet.

**The numbers we do have (last 7 days)**
- Brand site visits: 33
- Recorded clicks by destination: intelligence 1, legacy collective 1, Korvus 0
- Korvus signups: not instrumented yet. Tracking is at the aggregate level only.
- Operator starts: 0 subscriptions, 0 MRR on Stripe
- The 8 Korvus and Crown X posts from 10-28 are invisible to this feed. Their clicks cannot be attributed to a post, source, or campaign.

**What happens next**
- Corvid filed proposal #176 today, a per-click UTM capture plan. It is awaiting the owner's ruling in #boardroom. Nothing ships until he green lights it.
- Once #176 ships, per-click rows (source, campaign, content, clicks) will exist, and the 09:05 ET UTM job will carry them daily.
- Signups and Operator starts still need their own capture on the Korvus side before they can be tied back to a source. Until then they are reported as not instrumented yet.

**What to do now**
- Do not build your report on per-click data. Use the aggregate destination counts above and label everything else not instrumented yet.
- Keep your posts UTM tagged as they are. Do not refile the UTM tagging, it is standing infrastructure.
- Herald's standing quotas (50 korvus.industries signups, 100 new Eclipse-X joins) cannot be tracked per source until #176 is ruled and live. Plan your next moves with that in mind.
