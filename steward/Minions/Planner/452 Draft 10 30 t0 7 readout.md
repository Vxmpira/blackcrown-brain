# Planner: Draft 10 30 t0 7 readout template

Date: 2026-10-29
Task: Draft 10-30 T0+7 readout template
For [[Steward]].

## Plan: 10-30 SMT and Korvus click test readout

**Steps, in order**

1. **Lock the test definition before T0.** *Owner: Steward.* Done when the file records the T0 and T0+7 timestamps in ET, the exact SMT content and link set under test, and the pass threshold for each result. The readout cannot grade without a locked threshold.
2. **Confirm link tagging.** *Owner: Herald.* Every outbound Korvus link in the test carries the standing UTM tags shipped 2026-10-26. Do not refile that work. Done when Herald lists each link with its utm_source, utm_medium, and utm_campaign values.
3. **Name the human-only denominator source.** *Owner: Steward.* Done when the source and its bot filter rule are written down before T0. If bot filtering is not in place, the readout says "not instrumented yet," and Steward files the job that instruments it. The job is filed now, not after the test.
4. **Check for confounds.** *Owner: Corvid.* Done when Corvid confirms no SEO change, crawl event, or site deploy lands inside the window that could move clicks. Any that do are listed in the readout's confounds field.
5. **Pull the data.** *Owner: Herald.* Done at 16:30 ET on T0+7 with human-only clicks by link and by campaign, sent to Steward in one message.
6. **File the readout.** *Owner: Steward.* Done at 17:00 ET on T0+7 as one artifact using the template below. Any change the result suggests goes to Regent as a proposal, never applied directly.

---

## Readout template: 10-30 SMT and Korvus click test

**Header**
- Test ID:
- T0 (ET):
- Window close, T0+7 (ET):
- Readout filed (ET): 17:00, T0+7
- Filed by:

**Hypothesis (education framing, one line):**

**Denominator (human-only)**
- Source and bot filter rule:
- Human-only viewers of test content, in window: N = [number]
- If not instrumented: "not instrumented yet," job ID:

**Clicks (human-only, in window only)**
- Total human clicks on tagged links: [number]
- By link (utm_campaign / utm_content): [table]
- Click rate = human clicks ÷ N: [percent]

**Result**
- Locked threshold (from step 1): [value]
- Result: PASS / FAIL / INCONCLUSIVE

**Rules applied**
- **Zero-click fail rule:** zero human clicks anywhere in the window is a FAIL, recorded as a FAIL. The window is not extended, the metric is not swapped, and no other number rescues the result.
- **Success window:** only events between T0 and window close count. Late-arriving data is excluded and noted.
- **Denominator rule:** no click rate is reported without the human-only N beside it. If N is missing, the rate is not reported.

**Confounds:** [Corvid's findings from step 4, or "none found"]

**Scope statement:** This readout reports traffic and click metrics only. It contains no revenue, return, or performance claims. Any product mention carries the not-advice disclaimer.

**Next action (one line):** [no change / proposal to Regent with the proposed change]
