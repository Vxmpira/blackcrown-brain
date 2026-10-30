# Projects

Updated 2026-10-30 by Steward, cycle 430.

## Active board (5 active, 2 moving, 1 gated, 2 blocked)

### 0. Uptime recovery (BLOCKER, top priority)
- Goal: all three properties serving. Stage: visit to site load.
- Status: feed reads DOWN on blackcrownvxj.com, korvus.industries, blackcrown-intelligence.com.
- Next step: Corvid probes each property from outside our network and returns HTTP status and time to first byte. Task d8160d72.
- Owner next: if any property stays down after the probe, the outage goes to the owner as a direct page, not a proposal.

### 1. Korvus click recovery (moving, blocked by uptime)
- Goal: first clicks and first signup. Stage: visit to click.
- Numbers: today 4 visits, 0 clicks, 0 signups. 7d 61 visits, 2 clicks, 0 signups. MRR $0, 0 subscribers.
- Not instrumented yet: human-only visit count for today, x.com referral visits for today. CTA click count runs 18:00 ET, raw analytics export 18:05 ET.
- Next step: Corvid logs the human-only count and x.com referrals verbatim from the 18:05 export. Click test stays NO-GO until then.
- Owner next: Herald holds three CTA variants unpublished, awaiting the human count.

### 2. Operator annual 7-day test (moving, server-run)
- Goal: read the annual offer response daily through the window ending 2026-11-06.
- Live jobs: flight scorecard Mondays 09:00 ET to boardroom; daily readout 09:00 ET to corvid; X test 15:00 ET to corvid; CTA click count 18:00 ET; raw analytics export 18:05 ET; hostname split 18:15 ET; bot-filtered count 18:10 ET.
- Live X posts: Observer claim (2116133695371223336), Korvus watcher wire (2116133698407952571), Korvus watcher post no price claims (2116154077792883105).
- Operator 7-day trial status: absent from feed. Not confirmed, not denied.
- Next step: Herald annual ask for owner ruling, unpublished (task ad4fd39b). Variant B holds until the human count is logged.

### 3. Eclipse-X value posting (gated, cap reached)
- Goal: 2 value posts a day, no begging. Stage: community to Discord join.
- Status: feed reads 2 of 2 used today. Cap reached. No post this cycle.
- Welcome primer: Auditor PASS on the exact cycle 429 text. Held for the next open slot, earliest tomorrow after a fresh feed check.
- 11-05 position sizing post stays gated. Blocker: full draft absent from vault. Librarian locating (task 4267ba23).

### 4. Bard render delivery and slot
- Goal: one render a day reaches YouTube the same day. Stage: content to views.
- Status: Bloom render format fields absent. Verbatim values requested from Bard (task 4cc334fd).