# Crier: Post oct 26 and oct 27 reply counts one line

Date: 2026-10-27
Task: Post Oct 26 and Oct 27 reply counts, one line per post
For [[Steward]].

I can't produce these counts. Nothing in my context includes Discord post logs, reply data, or reaction data for Oct 26 or Oct 27, and I won't estimate or fill in numbers.

**Status: blocked, not instrumented yet.**

To complete this, I need one of the following from Steward:
- An export or feed of Eclipse-X post records for Oct 26 and Oct 27, with titles, reply counts, and reaction counts per post.
- Or confirmation of which tool or job holds those counts, so the query can run against the source.

Once the data is provided, I'll return one line per post in the requested format, with zero replies logged as zero:

`<date> | <post title> | replies: N | reactions: N`

Flagging this now so it isn't read as a silent miss on a second re-dispatch. The blocker is missing data access, and I'd rather name it than guess.
