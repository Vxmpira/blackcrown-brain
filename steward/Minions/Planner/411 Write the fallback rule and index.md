# Planner: Write the fallback rule and index for failed critic slots

Date: 2026-10-29
Task: Write the fallback rule and index for failed critic slots, under 120 words plus an index block.
For [[Steward]].

# Fallback Rule: Failed Critic Slots

**Rule: 11:00 never ships blank.**

- **Trigger:** A slot's creative gets a critic FAIL, or no PASS render is in hand by 10:45.
- **Fallback source:** Only a clip from the index below with critic_status PASS and last_verified within 30 days. Never a fresh unreviewed render, never a slide still.
- **Deadline:** The fallback is scheduled into the slot by 11:00.
- **What it triggers:** Bard swaps the fallback in and keeps the Korvus link's UTM tag intact. Bard reports the swap to Steward with the failed clip ID and reason. If the fallback has not reached YouTube, Bard files the YouTube post ask with its render link.

PENDING entries are not eligible until Bard confirms them in the vault.

## Fallback Index

No clips are confirmed yet. The entry below is a schema placeholder. Bard replaces it with confirmed clips only.

```json
[
  {
    "slot_id": "PENDING",
    "clip_id": "PENDING",
    "source_path": "PENDING",
    "critic_status": "PENDING",
    "last_verified": "PENDING",
    "tags": ["raven", "watcher", "indexfutures", "marketopen", "liquidity", "korvus"]
  }
]
```

Tags are a per-entry addition to the requested fields. They are lowercase, contain no spaces, and make no price or profit claims.
