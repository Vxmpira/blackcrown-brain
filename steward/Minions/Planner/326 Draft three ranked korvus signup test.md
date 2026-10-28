# Planner: Draft three ranked korvus signup test options

Date: 2026-10-28
Task: Draft three ranked Korvus signup test options
For [[Steward]].

## Korvus signup test options, ranked

**Baseline:** 33 visits in 7 days, 2 clicks, 0 signups. The biggest leak is visit to click (about 6%). Signups have not started, so the first test should fix the front of the funnel.

### 1. Live-wire hero test on the landing page (rank 1)

- **Hook:** Replace the generic hero with one concrete artifact: a scored Presidential Wire card showing impact, direction, confidence, and a one-line Korvus read. Mark the sample as *Illustration*. Single CTA: "Start with Observer, free."
- **Funnel stage:** Visit to click, then click to signup.
- **Why first:** It targets the largest leak with the smallest change. It edits an existing file (korvus_landing.html) through a proposal, so no new page is needed.
- **Measurement:** Split traffic by the existing UTM-tagged outbound Korvus links. Compare clicks per visit before and after the change, over the same 7-day window. Track signup rows by utm_source. If signup rows do not carry the UTM, the result is "not instrumented yet" and Steward gets a filing to fix it.
- **Owner:** Herald for copy and CTA direction. Steward for the proposal and deploy.
- **Done when:** The proposal is applied, the live page shows the card with an Illustration label, and seven days of clicks-per-visit data exists.

### 2. Free sampler page for search and ads (rank 2)

- **Hook:** "What the terminal saw today": a read-only sample of the daily USD economic agenda with Illustration-marked actuals, linking to /signup. Built for people already searching for index futures news.
- **Funnel stage:** Visit to click, with a stronger click to signup path.
- **Why second:** It adds a new surface for ads and search. It only ships after it is built. The writing minion must author the complete HTML into the vault first, and the proposal NEW line is a single FROM NOTE path. It goes in pages/ and serves at /p/<name>.
- **Measurement:** A dedicated UTM per channel pointing at the sampler page. Compare clicks and signups by utm_source against the landing page baseline. Pages with no traffic are not a result, so Herald needs a minimum spend or traffic window before judging.
- **Owner:** Corvid for slug and search intent. Herald for distribution. Steward for the proposal.
- **Done when:** The complete document is in the vault, the page serves at /p/<name>, and each channel has its own tagged link.

### 3. Eclipse-X to Korvus bridge (rank 3)

- **Hook:** A value-first post in the Eclipse-X korvus-industries channel: a real Wire read or a trade-education takeaway, then one tagged link to the signup page. No hype, no begging for activity.
- **Funnel stage:** Community traffic into visit, then click and signup.
- **Why third:** The Discord quota (100 joins) is a separate goal, and this option builds on it. It only works after the landing page converts clicks, or the traffic leaks at the same point.
- **Measurement:** Use a utm_source tag unique to Discord posts. Compare clicks and signups from that source against the other sources. Expect small numbers, so judge the trend, not one week.
- **Owner:** Herald, with Steward handling any channel posting.
- **Done when:** One value post is live with a tagged link, and the source has a full week of rows.

### Held until signups exist

An Operator annual-first offer test (LodeStone bundle framing against the computed savings label) stays on hold. It has no signups to act on yet. Prices stay in the server-side injection and are never typed into the page. Revisit once option 1 produces its first signups.
