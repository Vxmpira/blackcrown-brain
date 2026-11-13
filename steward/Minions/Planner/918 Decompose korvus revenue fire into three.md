# Planner: Decompose korvus revenue fire into three steps for the 11

Date: 2026-11-13
Task: Decompose Korvus revenue fire into three steps for the 11-14 lock
For [[Steward]].

## Korvus Revenue Fire: 11-14 Lock

**Baseline:** 92 visits, 1 click (about 1.1% visit-to-click), 1 signup. Signup source is not instrumented yet in the feed.

### Step 1: Restore the 7-day signup source row (Steward)
- Check SERVER JOBS first. If a job already reports signup source, do not register a duplicate. Confirm the row is missing from the feed and why.
- If no job covers it, file the smallest instrumentation job that surfaces signup source by UTM, using the UTM tagging already live since 2026-10-26. Do not refile the tagging itself.
- **Done when:** the 7-day signup source row appears in the feed for the 11-14 window, or Steward has a written reason and a filed job with a date.

### Step 2: Rule on and ship the Observer CTA variant (Herald, then owner)
- Herald puts the Observer CTA variant to the owner in #boardroom. The proposal must state exactly what it changes on korvus.industries, including the anchor text and the page it touches, and what it triggers.
- Once approved, Regent files it as a proposal, and the executor applies it with exact CURRENT anchors on the public landing at /.
- **Done when:** the owner has ruled, the variant is live or explicitly declined, and the decision is logged with its date.

### Step 3: Audit the landing click path and read out at lock (Corvid)
- Corvid checks the public landing at / on desktop and phone for CTA visibility above the fold, tap target size, and whether the Observer path is reachable in one click. Corvid files a fix only if the file is in the audit list.
- At 11-14 lock, Corvid and Steward report visit-to-click against the 92 visit and 1 click baseline, split by before and after the variant, and state the signup count from Step 1.
- **Done when:** the audit is filed, and the 11-14 readout shows click rate, signup count, and source, or says "not instrumented yet" for any missing number.
