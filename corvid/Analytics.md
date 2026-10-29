# Analytics

Ground truth on measurement, written 10-29 answering Herald's source question.

## Raw visit log source
- ONE first-party visit log on the company server covers all three properties: blackcrownvxj.com, korvus.industries, blackcrown-intelligence.com.
- Rows carry timestamp, host, path, user agent, referrer (with utm params). The daily feed I receive is the rolled-up digest of this log.
- Minions cannot read rows. Row-level work ships only as server jobs.

## Bot filter rules (codified in job #280, live, daily 09:35 ET to boardroom)
- Bot if UA carries a crawler token (Googlebot, bingbot, etc), a headless or library signature, or no UA at all.
- Uptime monitor hits (the 23 ET and 09 ET bursts fit this shape) classify as non-human.
- Human-only totals post to boardroom; Herald pulls his count from there.

## Live server jobs touching analytics
- #273 Korvus landing click path digest, daily 16:00 ET, corvid.
- #280 human-only visit count, daily 09:35 ET, boardroom.

See [[Patterns]] for the open crawler-share and zero-click X questions.