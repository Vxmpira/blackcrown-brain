# Planner: Draft a 19 00 raven contingency if wire c misses

Date: 2026-10-29
Task: Draft a 19:00 raven contingency if Wire C misses 17:45
For [[Steward]].

# Raven Watcher 19:00 Contingency: Wire C Miss

**Ledger:** #274 | **Ship target:** YouTube, 19:00 same day | **Trigger case:** Wire C source from Herald due 17:45, arrival not confirmed
**Moves:** First paying customer (Korvus signups), via a timely watcher post that stays on schedule.

## Timeline

| Time | Action | Owner | Done when |
|---|---|---|---|
| 17:45 | Wire C source due from Herald | Herald | Source is in the vault, or the miss is logged |
| 17:50 | Confirm arrival or miss. Post miss note to Herald as a task. | Steward | Miss logged in #274 with timestamp. Herald task filed. |
| 18:00 | Last safe start for a fresh Bard render. Bard checks whether Wire C arrived late. | Bard | Bard states "fresh render started" or "reuse path selected" |
| 18:15 | Planner selects fallback A, B, or C and sends the choice to Steward | Planner | Steward has one named fallback in writing |
| 18:20 | Regent reviews the proposal for the chosen fallback | Regent | Proposal cleared or returned with notes |
| 18:30 | Owner green light in #boardroom (only approval desk) | Owner | Green light posted, with the exact trigger stated |
| 18:45 | Final render passes Bard's critic gate, with overlay lines baked by the forge | Bard | Render link exists and critic gate passed |
| 18:50 | Bard files YouTube post ask carrying the render link | Bard | Ask filed with MEDIA link |
| 19:00 | Ship via owner's Make publisher | Steward | Video is live, link logged in #274 |

## Fallback A: Reuse Verified Footage and Reframe

**Use when:** Wire C has not arrived by 18:15, and Bard has approved footage already paid for in the Furnace.

- **Content:** Reframe the watcher piece around the last verified items from Wire A and Wire B. Do not invent a Wire C item. The all seeing watcher angle carries the piece: the market keeps running while the trader sleeps.
- **Owner:** Bard (render and overlay), Corvid (title and description), Steward (approval routing).
- **Trigger time:** 18:15 decision.
- **Done when:** Render link filed by 18:50, title and description carry the not advice disclaimer, live at 19:00.
- **Cost:** Reuse of existing footage. No new Bloom spend, so the daily video ceiling holds.

## Fallback B: Evergreen Watcher Education

**Use when:** Wire C is missing and no suitable footage exists to reuse, but a fresh render can still start by 18:00.

- **Content:** An education piece on how session levels are read, using the concepts behind LodeStone (session levels, prior day and week levels, premium and discount). No news claim, no direction, no levels that imply a trade. Mark any example chart as Illustration.
- **Owner:** Bard (creative and render), Corvid (title, description, not advice disclaimer), Steward (routing).
- **Trigger time:** 18:15 decision. Fresh render must have started by 18:00.
- **Done when:** Render passes critic gate, overlay lines are exact and spelled by the forge, render link filed by 18:50, live at 19:00.
- **Cost:** One fresh render, counted against the one video a day ceiling.

## Fallback C: Hold and Slip

**Use when:** Neither A nor B can clear the owner's green light and critic gate by 18:45.

- **Content:** No video at 19:00. The watcher ships at the next 19:00 slot. Herald reruns Wire C sourcing for the next cycle.
- **Owner:** Steward (ledger update and owner note), Herald (rerun sourcing and Wire C fix).
- **Trigger time:** 18:30 if no green light is posted, or 18:45 if no render has passed the critic gate.
- **Done when:** #274 records the slip with reason and new target time, owner has a one line note, Herald's rerun task is filed.
- **Cost:** No spend. The miss is the cost, and it is logged honestly rather than covered with weak content.

## Decision Rules

1. Default to A if verified footage exists. It keeps the schedule with the least spend.
2. Choose B only if a fresh render can start by 18:00 and A has no usable footage.
3. Choose C if neither clears approval and the critic gate by the trigger time. Do not force a weak post to hit 19:00.
4. Whatever runs, every title, description, and overlay keeps the not advice disclaimer. No profit promises, no direction calls.

## Ownership of the Miss

The Wire C miss lands on Herald as a task. Herald owns the fix and the rerun. Steward owns the ledger entry. The owner rules on which fallback runs and does not debug the source.

## Not Instrumented Yet

- Render duration for a fresh 15 second clip is not measured in this ledger. Bard should record actual start and finish times on this run so the 18:00 safe start can be checked against real data next time.
- Watch-time or click data for Fallback A versus B versus C is not instrumented yet. Steward should file a job to tag each variant in #274 so the next contingency can be ranked by result.
