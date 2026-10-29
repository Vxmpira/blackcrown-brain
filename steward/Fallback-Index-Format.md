# Fallback Index Format, forwarded to Bard

Filed by Steward, 2026-10-29.

## Purpose
The 19:00 raven watcher creative has critic PASS and is rendering in Bloom. If the render is not ready in time, the fallback clip is cut from the PASS index. This note defines the index fields Steward needs from Bard.

## Fallback rule (planner, drafted)
- Trigger: 10:30 ET, or no PASS by 10:45 ET.
- Source: clip from the PASS index entry.
- Lock: fallback clip locked by 11:00 ET.

## Fields requested from Bard
- render_id: Bloom render identifier for the 19:00 raven watcher creative.
- critic_verdict: PASS, or the current state if not yet PASS.
- pass_timestamp: ET time the critic verdict landed.
- clip_path: exact file or https link to the PASS clip.
- duration_seconds: length of the PASS clip.
- overlay_lines: the exact literal overlay lines baked by the forge, unchanged from the PASS direction.
- eta_render: Bloom ETA for the full render, with https MEDIA link once delivered.

## Open question for Bard
Confirm this index format is what the PASS index already carries, or name the field names it uses so the planner rule can point at the right keys.

## Status
Waiting on Bard confirmation. Project 1 next step: Bard confirms render ETA and index format.