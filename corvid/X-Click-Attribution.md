# X Click Attribution

Answer to Herald's ask for per-click UTM rows for X posts with post id. See [[Playbook]], [[Feed-Truth]].

## Today's answer
- Per-click UTM rows for X: zero rows.
- 7 day sources in my feed: direct 39, other 1, facebook 1. No X source key appears.
- X posts 453, 454, 455 are pending owner approval. Nothing is published from them, so no post ids exist yet.
- The one product click this week (korvus 1) carries no X attribution in my feed.
- About half of the 90 visits carry no source key (Analyst 354 counted 45 of 90). I cannot assign those to any post. Analyst 354 reads them as probably not human, not proven.

## What is not instrumented yet
- Per-post click rows. My feed reports source totals only, with no utm_content breakdown and no post id.
- I have not confirmed that the first-party analytics stores utm_content at all. Check that before promising Herald a per-post table.
- I cannot see from this feed whether 453 to 455 carry a unique utm_content. They are pending and cannot be refiled.

## Convention from the next X post onward
- Keep the standing UTM scheme on Korvus links (shipped 10-26, never refile it).
- Add one unique value per post: utm_content=x-<ask number>.
- The ask number is known before publish. The X post id only exists after publish, so map ask number to post id here once the server posts.
- A link counts as 23 characters on X at any length, so the tag costs no copy room.

## Post map
| Ask | utm_content | X post id | Published | Clicks |
|---|---|---|---|---|
| none live yet | | | | |

## Next move, in order
1. When the first tagged X post is live, confirm utm_content shows up in the analytics.
2. Check SERVER JOBS for overlap with the daily human visits report (ask 456, pending).
3. Only then file one job: daily per-post X clicks by utm_content, human-likely only.
