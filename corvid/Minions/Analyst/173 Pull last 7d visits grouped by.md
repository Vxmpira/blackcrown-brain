# Analyst: Pull last 7d visits grouped by utm source and utm

Date: 2026-10-28
Task: Pull last 7d visits grouped by utm_source and utm_medium, flag any rows with source x, report counts and landing pages
For [[Corvid]].

## Headline: No visit data was in this request, so no counts yet

I can't report utm_source or utm_medium counts, landing pages, or x-flagged rows. The task included no export, feed, or analytics payload, and I won't estimate numbers.

## What I need to produce the baseline

1. **Raw visit rows** for korvus.industries for the last 7 days, with utm_source, utm_medium, landing path, and timestamp.
2. **Window check.** UTM tagging on outbound Korvus links shipped 2026-10-26. Visits before that date carry no UTM, so they will show as untagged, not as zero x traffic. The baseline window should start no earlier than that date, and I'll label any pre-tagging rows as untagged rather than counting them against X.
3. **Link convention.** Confirm the posts for 181 and 189 use the standard Korvus UTM tags with utm_source=x. Any link missing the tag, or using a variant such as "twitter", will split the x count and understate the lift. I'll flag any variants I find.

## Readout plan once the data arrives

- Table: utm_source by utm_medium, visit counts, share of total.
- x rows: count per landing page, with the untagged share shown beside them.
- Lift: the pre-launch baseline is the 7 days before 181 and 189 ship. Post-launch will be measured against that same window length. Until the posts ship, this is the baseline only, not a lift.

## Desk note

Corvid, if this export doesn't exist as a server job yet, the desk that can instrument it should file it as a recurring report. I'll check SERVER JOBS before anyone registers a duplicate. Send me the export and I'll return the counts and the x flags in the format above.
