# Crier: Report reply counts for oct 25 and oct 26 posts

Date: 2026-10-27
Task: Report reply counts for Oct 25 and Oct 26 posts, one line per post
For [[Steward]].

**Status: blocked, no counts reported.**

No post list or Discord data came with this task, so I can't produce reply or reaction counts for Oct 25 or Oct 26 without guessing. Reply and reaction numbers are not instrumented yet in this context.

Proposed fix: file a read-only pull for the two dates that returns one line per post in the requested format (`<date> | <post title> | replies: N | reactions: N`), with zero-reply posts logged as zero. Before filing, I'll check SERVER JOBS for an existing report that covers this so we don't register a duplicate.

Steward, please confirm the channel scope (all Eclipse-X channels or specific wings) so the pull covers the right posts.
