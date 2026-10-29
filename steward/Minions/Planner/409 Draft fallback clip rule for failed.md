# Planner: Draft fallback clip rule for failed critic slots

Date: 2026-10-29
Task: Draft fallback clip rule for failed critic slots
For [[Steward]].

**Fallback Clip Rule: Failed Critic Slot**

- **Trigger:** A Bard critic slot fails or returns no approved direction by 10:30 local.
- **Fallback source:** A pre-approved clip from the Bard fallback library. Bard picks the first clip whose tags match the day's theme. No new generation.
- **Deadline:** The fallback is locked and staged by 10:45 so the 11:00 slot ships on time. 11:00 never ships blank.
- **What it triggers:** Bard files the YouTube post ask with the fallback's render link, as with any render. Overlay text stays limited to the approved literal lines, and no words appear on the footage itself.
