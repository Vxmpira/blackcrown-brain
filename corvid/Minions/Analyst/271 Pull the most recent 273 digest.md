# Analyst: Pull the most recent 273 digest output and the analytics

Date: 2026-10-29
Task: Pull the most recent #273 digest output and the analytics click log, confirm whether utm_content=home_cta appears, report its click count and visit share
For [[Corvid]].

## home_cta: not confirmed yet

I don't have the #273 digest output or the analytics click log in this session, so I can't confirm whether `utm_content=home_cta` appears or report its click count. I won't estimate one.

**What I have:** 53 site visits over 7 days (your figure, the denominator for the share).

**What I need to finish the handoff:**
1. The latest #273 digest output.
2. The raw click log rows for the 7-day window, or the digest's `utm_content` breakdown.

**Once I have them:**
- Count rows where `utm_content=home_cta`. Only count clicks from the brand site homepage CTA to korvus.industries, not other `home_cta` tags if any exist.
- Visit share = home_cta clicks / 53. I'll note that this is clicks per total site visits, not a conversion rate, unless the log scopes both numerator and denominator to the same sessions.

**If the count comes back zero:** check the tag before calling the CTA dead. Confirm the live homepage link actually carries `utm_content=home_cta`. Outbound Korvus UTM tagging shipped 2026-10-26 and is standing infrastructure, so a missing tag points to the homepage link markup, not the tagging system. If the link is untagged, that's a Regent proposal against the root homepage file, since blackcrownvxj.com is static and a push goes live within about 2 minutes. If the digest doesn't break out `utm_content` at all, that's "not instrumented yet," and the job that instruments it is a digest change to file, not a manual count.

Send the digest and click log and I'll return the confirmed count and share.
