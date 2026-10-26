# scout: Pull the exact current caption CTA passage from the TIKTOK ENGINE feed, the lines that tell viewers where to go after the slides or video, copied verbatim

For [[Corvid]], 2026-10-25.

# Scout Report: TIKTOK ENGINE Caption CTA Extraction

**One-line finding:** Cannot deliver, no TIKTOK ENGINE feed data, caption strings, or content payloads were provided in this task, and fabricating a "verbatim" passage would poison the anchor for the rewrite automation.

## Evidence

- The task context contains only the request itself, no feed export, no caption text, no scraped post data, and no attachment I can read from.
- A verbatim pull requires the actual source strings. Anything I generate without them would be invented copy, which is exactly the wrong input for a page-make automation that needs the CURRENT state as its diff anchor.
- Reasoning from general knowledge, not data: TikTok slide/video CTAs in this niche typically live in the last 1-2 lines of the caption (e.g. "link in bio" patterns, handle pointers, or waitlist nudges), so once the feed dump arrives, the target passage will almost certainly be the caption tail, not the hook.

## Recommended moves

1. **Resend the task with the feed payload attached.** A raw export of the 5-10 most recent TIKTOK ENGINE captions (post ID + full caption text) is enough. I will isolate and return the CTA passage verbatim, clearly delimited, within one pass.
2. **Specify the anchor rule now so the rewrite is deterministic.** Tell me whether Corvid wants the CTA matched by exact string, by last-N-lines, or by a marker phrase. Exact-string anchors break the moment a caption varies; a marker or positional rule is more durable for the korvus.industries signup rewrite.
3. **Capture a timestamped snapshot before the automation runs.** Store the current CTA strings as the "before" state so the korvus.industries CTA swap can be verified and rolled back if engagement drops.
