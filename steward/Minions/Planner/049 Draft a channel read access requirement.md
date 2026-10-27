# Planner: Draft a channel read access requirement for eclipse x reply

Date: 2026-10-27
Task: Draft a channel read-access requirement for Eclipse-X reply counts
For [[Steward]].

# Spec: Eclipse-X Reply Count Read Access

**For:** Regent
**From:** Planner, on Steward's task
**Status:** Draft for review. Not filed. Owner green light required in #boardroom before any change.

## Purpose
Crier returned no data on two runs, so reply counts for Eclipse-X posts are not instrumented yet. This spec defines the minimum read access the bot needs to count replies, and the output format for the report.

## Access required
- **View Channel** on each channel in scope.
- **Read Message History** on each channel in scope.
- **Message Content intent:** not needed to count replies if the counter uses message IDs and reply references. Regent to confirm whether Crier's current build reads content. If it does, the privileged intent becomes a separate decision for the owner, since it expands what the bot can see.
- No send, manage, or moderation permissions. Read only.

## Channels in scope (proposed)
Channel names come from the server layout in memory. **Channel IDs are not in memory and must be pulled from the live server.** Do not file with guessed IDs.

| Wing | Channel | Why |
|---|---|---|
| Stock Market | korvus-industries | Korvus engagement |
| Stock Market | korvus-indicator | LodeStone buy path, conversion signal |
| Stock Market | presidential-news | Highest volume, scored Wire posts |
| Artificial Intelligence | crowned-intelligence | Crown engagement |
| Artificial Intelligence | ai-information | Crown education |
| E-Commerce | marketing | Growth feedback |
| Server Information | suggestions | Community signal |

Out of scope for now: Entrance Hall, memes, off topic lounges. Regent may widen the list.

## Report format
One line per post, no prose:

`YYYY-MM-DD HH:MM UTC | #channel | message_id | replies=N | post_type=wire|community|other`

Example, illustrative only:
`2026-11-02 14:05 UTC | #korvus-indicator | 000000000000000001 | replies=4 | post_type=community`

Counts are per post, not per user, so no member names appear in the report. Message IDs make each line traceable.

## Open items
1. Live channel IDs for the seven channels above, pulled by Steward or the server admin.
2. Crier's error log for the two empty runs. Without it, the root cause of the failure is unknown and the read access alone may not fix it. Per filing integrity, the fix lands back on the desk that filed the original task.
3. Regent decision on whether Message Content intent is required.
4. Owner green light in #boardroom. The approval must state what it triggers: the bot gains read only access to the listed channels and begins writing the report.
