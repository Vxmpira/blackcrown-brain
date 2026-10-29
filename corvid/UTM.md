# UTM

Standing tagging law for every outbound clip and post link. Shipped 2026-10-26, scheme locked 2026-10-29 for [[Bard]] per-clip attribution.

## The scheme
- **utm_source**: platform, lowercase. tiktok, youtube, x.
- **utm_medium**: video for clips, post for text posts.
- **utm_campaign**: product slug. korvus, crown, eclipse, brand.
- **utm_content**: the per-clip id. Format a{ask number} from the Regent ledger. Example: a272 for ask #272, a274 for #274. Unique per render, traceable straight back to [[Ledger]] and the critic-passed direction.

## Example, full link
https://korvus.industries/?utm_source=tiktok&utm_medium=video&utm_campaign=korvus&utm_content=a272

## Rules
- Lowercase everywhere, no spaces, no dates in utm_content, the ask number already carries the date via the ledger.
- Clip links go DIRECT to the product domain, never through brand home (zero Korvus clicks from home, see [[Patterns]]).
- One clip, one utm_content, forever. Reposts of the same render keep the same a-number so attribution sums.
- Analyst reads: group by utm_content to score clips, by utm_source to score platforms.

Linked from [[Funnel]] and [[Keywords]].