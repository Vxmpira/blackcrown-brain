# Scout: Fetch korvus industries sitemap open every p guide page list

Date: 2026-10-30
Task: Fetch korvus.industries sitemap, open every /p/ guide page, list each page url plus every clock time, timezone, UTC, or session-offset mention verbatim.
For [[Corvid]].

**Finding: the audit did not run. I have no fetch tool in this session and no page contents were supplied, so I have zero verified URLs, times, or flags to report.** I'm not listing pages from memory, because a made-up inventory would look like an audit.

**What I could not do**
- Fetch `korvus.industries/sitemap.xml` or any `/p/` page.
- Confirm which guide pages exist, or quote any time, timezone, UTC, or session-offset line.

**Flag rules, ready for the run**
- **ES hours:** correct is Sun 6:00pm ET to Fri 5:00pm ET. Flag any other open or close time.
- **Daily halt:** correct is 5:00 to 6:00pm ET. The ground truth note reads "5:00pm-4:00pm CT," which has the order reversed. Correct form: 4:00 to 5:00pm CT. Flag any copy that gets this wrong.
- **UTC or GMT:** flag every mention. Winter Sunday open is 23:00 UTC. Flag 22:00 UTC, and flag any UTC time in summer months unless it is labeled as such.
- **London open:** should read 3:00am ET. US and UK DST don't switch on the same dates, so for a few weeks each spring and fall the London open moves to 2:00am or 4:00am ET. Flag any London time that doesn't match 3:00am ET outside those gap weeks. Flag gap-week copy only as a note, not an error.
- **Unlabeled times:** any clock time with no timezone attached gets flagged.
- ET and CT references are fine as written.

**Recommended moves**
1. Re-run the audit on a fetch-capable desk, or paste the sitemap XML and the HTML of each `/p/` page into the task. I'll apply the rules above and return flags only, with URL and verbatim quote.
2. Make the halt line and the London-open line their own checks in the audit, since those are the two most likely to drift after a DST change.
3. Once the first run is clean, schedule it as a server job so it recurs after each DST transition instead of relying on a manual pass.
