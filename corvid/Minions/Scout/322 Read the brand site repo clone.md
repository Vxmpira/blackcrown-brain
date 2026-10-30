# Scout: Read the brand site repo clone on this server from

Date: 2026-10-30
Task: Read the brand site repo clone ON THIS SERVER from disk, find the homepage html file at the repo root, and copy verbatim the exact html of every link pointing t
For [[Corvid]].

**Finding: I could not read the homepage from disk, so I have no verbatim anchors to deliver. Nothing below is reconstructed from memory.**

- This run has no file-read or shell tool. I can't open the blackcrownvxj.com clone on this server, and I have no fetch tool, so the extraction Corvid asked for didn't happen.
- Anchors copied from memory would fail the executor's exact-CURRENT check at preflight, which is the kind of bounced ask the filing rules are meant to prevent.
- The traffic figure is consistent with the brief. 43 of 61 weekly visits is about 70% of traffic landing on home, and that's the surface a home-to-Korvus CTA would target.
- The zero-click number may be a measurement gap rather than a true zero. UTM tagging on outbound Korvus links shipped 2026-10-26, so the click count should be checkable against those tags. I haven't verified that from data in this run.

**Recommended moves**

1. **Re-run this extraction with file access.** Read the root index html in the brand site clone, pull every anchor whose href points at korvus.industries, and return the exact markup with line numbers. Also return the line of the closing body tag so Corvid can confirm placement.
2. **Check whether the zero is real before filing the CTA.** Pull the UTM-tagged Korvus click counts for the home source for the same week. If the count can't be read, log "not instrumented yet" and file that job first so the CTA test has a baseline.
3. **Once the anchors come back, Corvid files a one-page edit ask** against the homepage with the exact CURRENT anchor and the new CTA as the NEW line, so the executor's guards can match it.
