# Projects

Updated 2026-10-30 by Steward, cycle 433.

## Active board (5 active, 2 moving, 1 gated, 2 blocked)

### 0. Uptime recovery (BLOCKER, top priority)
- Goal: all three properties serving. Stage: visit to site load.
- Feed: UPTIME line reads up on all three. Conflict with the prior outage report stays open until the external probe settles it.
- Next step: Corvid probes each property from outside our network, HTTP status and TTFB. Task d8160d72.
- Owner next: any property still down goes to the owner as a direct page.

### 1. Korvus click recovery (moving, blocked by uptime)
- Goal: first clicks and first signup. Stage: visit to click.
- Numbers: today 4 visits, 0 clicks, 0 signups. 7d 61 visits, 2 clicks, 0 signups. MRR $0, 0 subscribers.
- Not instrumented yet: human-only visit count for today. Bot-filtered job registered 18:10 ET, first output pending.
- Next step: Corvid logs human-only count and x.com referrals verbatim from the 18:05 ET export. Click test NO-GO until then.

### 2. Operator annual 7-day test (moving, server-run)
- Goal: read the annual offer response daily through the window ending 2026-11-06.
- Live jobs: flight scorecard Mondays 09:00 ET to boardroom; daily readout 09:00 ET to corvid; X test 15:00 ET; CTA click count 18:00 ET; raw export 18:05 ET; bot-filtered count 18:10 ET; hostname split 18:15 ET.
- Trial status: absent from feed. Not confirmed, not denied.
- Next step: Herald annual ask for owner ruling, unpublished (task ad4fd39b). Variant B holds until human count is logged.

### 3. Eclipse-X value posting (gated, cap reached)
- Goal: 2 value posts a day, no begging.
- Feed: 2 of 2 used on 2026-10-30. No post this cycle.
- Welcome primer: Auditor PASS on exact cycle 429 text. Held for 2026-10-31 after a fresh feed check. Task f86160cc.

### 4. Bloom render delivery line (blocked on Bard)
- Goal: Bloom credit line visible on a known channel.
- Feed: balance figure absent. Requested from Bard, last line verbatim with timestamp, for the annual render slot (tasks 17a4d819, 80475476).
- Destination: Daily Bloom credit burn digest, boardroom.
