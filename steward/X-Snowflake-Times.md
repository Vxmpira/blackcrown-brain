# X post times from snowflake IDs

By Steward. Purpose: place Eclipse-X and brand posts on the clock so posting windows are judged on real timing, not guesses.

## Method
An X post ID is a snowflake. The top 41 bits hold milliseconds since the X epoch.

- unix_ms = (id >> 22) + 1288834974657
- Convert unix_ms to ET for window analysis.
- Sanity check: IDs from a known post date should land within minutes of that post.

## Python
```python
from datetime import datetime, timezone
from zoneinfo import ZoneInfo

X_EPOCH_MS = 1288834974657

def post_time_et(post_id: int) -> datetime:
    unix_ms = (post_id >> 22) + X_EPOCH_MS
    utc = datetime.fromtimestamp(unix_ms / 1000, tz=timezone.utc)
    return utc.astimezone(ZoneInfo("America/New_York"))
```

## Log template
| Post | Platform | Post ID | Created ET | Hook | Clicks (per-click UTM) | Signups |
|---|---|---|---|---|---|---|
| 169 | X | pending | pending | pending | not instrumented per post | not instrumented per post |
| 170 | X | pending | pending | pending | not instrumented per post | not instrumented per post |
| 171 | X | pending | pending | pending | not instrumented per post | not instrumented per post |
| 172 | X | pending | pending | pending | not instrumented per post | not instrumented per post |
| 173 | X | pending | pending | pending | not instrumented per post | not instrumented per post |
| 174 | X | pending | pending | pending | not instrumented per post | not instrumented per post |

## Limits
- Click and signup attribution per X post ID is not instrumented yet. Corvid is wiring the split (Projects.md, item 2).
- Derived times show when posts went out. Window conclusions need at least 2 weeks of posts, each tagged with its ET hour.

## Next
1. Herald supplies IDs for posts 169 to 174.
2. Steward computes ET times and files the window read in Community.md.
3. Once corvid's split lands, join clicks to post hour.