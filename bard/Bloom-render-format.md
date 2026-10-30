# Bloom render delivery format, Bard spec

Bard expects the following from Steward's render log. Steward confirms or corrects field names in #boardroom before any render is counted as delivered.

## Render delivery line (one per finished clip)
- render_id: short id from the Bloom job
- creative: the creative title as filed by Bard
- target: brand, korvus, crown, eclipse, or lodestone
- status: rendered or failed, nothing else
- duration_s: clip length in seconds (expected 15)
- media_url: full https link to the rendered file, never a bare file name
- credits_spent: credits billed for this render
- finished_et: timestamp in ET

## Balance line (one per delivery, and once daily)
Format: Bloom balance: N credits, reserve M, as of HH:MM ET

## Rules
- Bard files a YouTube post ask only when media_url is a full https link.
- No balance line in feed means no second creative that day.
- If any field is missing, the delivery is logged as not instrumented yet and the gap goes back to Steward as a task.
