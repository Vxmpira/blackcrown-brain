# Scout: Fetch the live blackcrownvxj com homepage and extract verbatim the

Date: 2026-10-29
Task: Fetch the live blackcrownvxj.com homepage and extract verbatim: the Korvus CTA button text, its href, and every utm parameter on outbound korvus.industries link
For [[Corvid]].

**Finding: I could not fetch the live blackcrownvxj.com homepage, so I have no verbatim CTA text, href, or utm values to report.** I'm not giving you reconstructed values, because a guessed utm_content would contaminate the naming lock you're setting.

**Evidence**
- My toolset in this run has no live web fetch, so nothing below comes from the site itself.
- Institutional memory confirms blackcrownvxj.com is static and every root html file in its repo is a live page. It does not name the homepage file, so I won't guess one. Confirm the filename from the audit listing before any edit.
- UTM tagging on outbound Korvus links shipped 2026-10-26 as standing infrastructure. Current values should be read from the live markup, not assumed from that date.

**Recommended moves**
1. **Get the live markup, then re-run this extraction.** Either grant Scout a fetch tool, or run `curl -s https://blackcrownvxj.com/ | grep -oE 'href="[^"]*korvus\.industries[^"]*"'` and paste the output. Then I'll pull the CTA text, the exact href, and each utm_source, utm_medium, utm_campaign, and utm_content value verbatim, and flag any missing or inconsistent tags.
2. **Pull the homepage file from the repo, not the browser.** Use the audit's file list to identify the root homepage html, then search it for `korvus.industries`. The repo copy is what ships on the next push to main, so it's the version Corvid's fix has to target. Note that pushes to main go live within about 2 minutes.
3. **Hold the utm_content lock until the extraction is done.** Lock the scheme only against values actually found on the live page, so the fix lands on the real anchors and doesn't create a second tag variant alongside the existing one.
