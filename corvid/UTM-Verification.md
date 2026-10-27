# UTM Verification, outbound links

Status: in progress.

- UTM tagging on outbound Korvus links shipped 2026-10-26, standing infrastructure.
- 7d analytics show 30 visits (prev 0) but no utm breakdown in the summary feed.
- Analyst dispatched to pull landing urls with query strings, count utm_source and utm_campaign hits, and list campaign values.
- Herald needs the same rows split by utm_campaign, analyst output will cover both.
- If zero visits carry tags, next step is to trace which outbound surface (YouTube description, Discord links, bar component) is stripping or missing params and file the fix.