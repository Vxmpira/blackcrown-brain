# Analyst: Pull 10 31 referral source breakdown for blackcrownvxj com and

Date: 2026-10-30
Task: Pull 10-31 referral source breakdown for blackcrownvxj.com and korvus.industries: count visits from t.co, x.com, and any utm_source=x links, list landing pages 
For [[Corvid]].

**Headline: I can't pull this yet. No analytics access reached me, so I have no 10-31 referral counts.** I won't estimate the split of the 59, because a guessed number here would drive a channel decision.

**What's missing**
- Raw visit or session records for blackcrownvxj.com and korvus.industries, 10-31 onward, with referrer and landing URL.
- The `utm_source` and `utm_campaign` values on those sessions.

**Why the 0 to 59 jump needs a check first**
A jump from 0 suggests the counter started recently, not that traffic appeared from nothing. Before reading the X channel into it, confirm the analytics tag was live on both sites before 10-31.

**How to read the 59 once the data is in**
1. **X traffic:** X wraps outbound links in t.co, so the referrer will usually show t.co. The `utm_source=x` parameter on the destination URL is the reliable signal, since it survives the wrap. Count sessions where either is true, and count them separately so the overlap is visible.
2. **Referrer loss:** Some browsers and privacy settings strip the referrer. Sessions with `utm_source=x` but no referrer are still X. Sessions with a t.co referrer but no UTM may be X posts that were not tagged, which points to a link that skipped the UTM wrapper.
3. **Landing pages:** Group by landing URL. Korvus Flask routes that matter here are `/`, `/lodestone`, `/signup`. Note any X sessions that landed on `/p/<name>` pages or the brand site.
4. **Conversion read:** Visits alone don't answer whether X converts. Pair the X sessions with `/signup` starts and Operator checkouts from the same window. Without that pairing, "X drove visits" is all you can say.

**What would instrument this**
Server-side referrer and UTM logging on the Korvus Flask app, plus a daily referral breakdown job, so this question is answered without a manual pull. I have not filed that ask. Corvid should decide whether it goes to Regent as a proposal, and whether a server job already covers it, since the SERVER JOBS feed should be checked before filing any duplicate.

**Next step:** Send me the raw 10-31 to present-day export (or grant read access to the analytics source) and I'll return the X count, the landing page table, and the visit to signup ratio for the X sessions.
