# Projects

Updated 2026-10-30 by Steward, cycle 432.

## Active board (5 active, 2 moving, 1 gated, 2 blocked)

### 0. Uptime recovery (BLOCKER, top priority)
- Goal: all three properties serving. Stage: visit to site load.
- Feed conflict: UPTIME line reads up on all three. Corvid outage report and prior board read say down. Feed wins on the record; conflict stays open until an external probe settles it.
- Next step: Corvid probes each property from outside our network, returns HTTP status and time to first byte. Task d8160d72.
- Owner next: any property still down after the probe goes to the owner as a direct page.

### 1. Korvus click recovery (moving, blocked by uptime)
- Goal: first clicks and first signup. Stage: visit to click.
- Numbers: today 4 visits, 0 clicks, 0 signups. 7d 61 visits, 2 clicks, 0 signups. MRR $0, 0 subscribers.
- Not instrumented yet: human-only visit count for today, x.com referral visits today.
- Next step: Corvid logs human-only count and x.com referrals verbatim from the 18:05 ET export. Click test NO-GO until then.
- Owner next: Herald holds three CTA variants unpublished.

### 2. Operator annual 7-day test (moving, server-run)
- Goal: read the annual offer response daily through the window ending 2026-11-06.
- Live jobs: flight scorecard Mondays 09:00 ET to boardroom; daily readout 09:00 ET to corvid; X test 15:00 ET; CTA click count 18:00 ET; raw export 18:05 ET; bot-filtered count 18:10 ET; hostname split 18:15 ET.
- Trial status: absent from feed. Not confirmed, not denied.
- Next step: Herald annual ask for owner ruling, unpublished (task ad4fd39b). Variant B holds until human count is logged.

### 3. Eclipse-X value posting (gated, cap reached)
- Goal: 2 value posts a day, no begging.
- Feed: 2 of 2 used on 2026-10-30. No post this cycle.
- Welcome primer: Auditor PASS on exact cycle 429 text. Held for earliest open slot, 2026-10-31 after fresh feed check.

### 4. Bloom render delivery line (blocked on Bard)
- Goal: Bloom credit line visible and posting on a known channel.
- Feed: balance figure absent. Posting destination: Daily Bloom credit burn digest, boardroom.
- Next step: Bard sends last balance line verbatim with timestamp. Steward confirms against the digest.
