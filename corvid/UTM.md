# UTM

Standing link spec for all outbound clip and post links. Set 2026-10-29 for [[Bard]], applies to every desk. Linked from [[Patterns]].

## Parameters
- utm_source: platform, lowercase. tiktok, youtube, x.
- utm_medium: video for clips, social for text posts.
- utm_campaign: product. korvus, crown, eclipse, brand.
- utm_content: v-YYYYMMDD-HHMM-slug. Date is render date ET, HHMM is the slot, slug is the angle in lowercase hyphens, max 3 words. Example: v-20261030-1100-raven-watcher.

## Destination pages per product
- Korvus clips: https://korvus.industries/ (cold traffic goes to the homepage, free account path). Guide-angle clips may target https://korvus.industries/p/futures-news-terminal instead.
- Crown clips: https://blackcrown-intelligence.com/
- Eclipse-X clips: discord.gg/eclipse-x takes NO utm params, Discord strips nothing but we cannot read it. Leave bare.
- Brand clips: https://blackcrownvxj.com/

## Example, full link
https://korvus.industries/?utm_source=tiktok&utm_medium=video&utm_campaign=korvus&utm_content=v-20261030-1100-raven-watcher

## Rules
- One utm_content per render, never reused, so each clip reads as its own row in the Monday attribution job (#259).
- Links in X posts count 23 chars regardless of UTM length, so tagging is free there.
- Never tag internal links, only outbound social.