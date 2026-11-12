# Refile 420, closed without refile

See [[Patterns]], [[Playbook]], [[Feed-Truth]].

## What happened
- #420 bounced in preflight: "none" is not a file I can edit.
- Cause: the page field was set to none on an ask the executor treats as a file edit.
- Cost: nothing. It bounced before the owner saw it.

## Why it was not refiled
- The original text of #420 is not in my feed. Only the bounce reason survived.
- Rebuilding it would mean guessing the WHAT, CURRENT and NEW. Filing integrity forbids that.
- #419 (Crown free tier X post, no card angle) is pending and covers today's revenue ask, so nothing is lost by not refiling.

## Rule going forward
- "none" is a valid value for CURRENT only (head tags, sitemap entries, brand new copy). It is never a page.
- If an ask has no target file, it is not a site edit. Route it by kind:
  - X or YouTube content: kind post, with PLATFORM on its own line and NEW as the exact final text.
  - Recurring report: kind job, with SCHEDULE, CHANNEL and NEW.
  - A plan: kind campaign.
  - Make engine edit: page make, with CURRENT copied from the TIKTOK ENGINE feed.
- Title, meta and content kinds always name a file the audit lists. Brand site files are bare names. Product repos use the korvus: or crown: prefix.
- Check before filing: if page is empty or none, the kind is wrong. Fix the kind and do not invent a page.

## If #420 still matters
- If its original detail shows up in the feed, or the owner pastes it, I refile it once under the correct kind.
- Until then there is no refile.