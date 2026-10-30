# Scout: Capture the exact cme group url for equity index futures

Date: 2026-10-30
Task: Capture the exact CME Group URL for equity index futures trading hours (ES, NQ). Return full https URL, exact page title, and the stated hours, stamped capture 
For [[Corvid]].

**Finding: I could not capture the live CME page, so there is no verified URL, title, or dated stamp yet. The hours below are from general knowledge and must not be cited until someone confirms them on the page.**

**Evidence**
- **Capture status:** Not performed. I have no live browsing in this run, and the task requires a verified load. No capture timestamp is included because none was taken.
- **Candidate URL (unverified):** `https://www.cmegroup.com/trading-hours.html` is CME's general trading hours hub. A product page for E-mini S&P 500 (ES) is likely under `cmegroup.com/markets/equity/...`. Confirm the exact path by loading it, since I cannot confirm it from here.
- **Exact page title:** Unknown. I will not guess it.
- **Hours as I understand them (general knowledge, unverified):** CME Globex equity index futures trade Sunday through Friday, roughly 6:00 p.m. to 5:00 p.m. Eastern the next day, with a daily maintenance break around 5:00 to 6:00 p.m. ET. CME revises these schedules and holiday exceptions, so the page itself must be the source for any stated figures.
- **Scope check:** ES and NQ share the Globex equity schedule, but NQ's product page should be checked separately in case its listed hours differ.
- **Citation rule:** Korvus content needs an official cmegroup.com source with a dated capture. Third party summaries do not qualify, so none were used here.

**Recommended moves**
1. **Re-run as a capture task on a fetch-capable desk** (or have the owner open the URLs manually). Record the final URL, the exact `<title>`, the listed ET hours and holiday notes for both ES and NQ, and a UTC capture timestamp. This is the only way to satisfy the citation requirement.
2. **Hold any Korvus session-hours copy** that cites CME until that capture lands. Using the general-knowledge hours in public copy would risk a wrong figure on a trader-facing page, which costs more trust than the delay.
3. **Set a recurring check** on the CME trading-hours page, if the SERVER JOBS feed has no existing coverage, so the citation stays current when CME changes its schedule. Check the feed first to avoid a duplicate.
