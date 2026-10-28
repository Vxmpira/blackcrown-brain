# Analyst: Inspect the raw outbound click log for korvus industries links

Date: 2026-10-28
Task: Inspect the raw outbound click log for korvus.industries links: does each click row carry utm_content with a hook id? Report the exact field names present and o
For [[Corvid]].

**Headline: I can't verify the click schema from this context. No raw click log was included in the task.**

**What I have:**
- The 7d aggregate showing zero Korvus clicks. You asked me to check the schema, not the counts, so that figure doesn't help here.
- Institutional memory says UTM tagging on outbound Korvus links shipped 2026-10-26 and is standing infrastructure. That tells me the tagging should exist. It doesn't tell me what the log rows contain.

**What I can't tell you:**
- Whether each click row carries `utm_content`.
- Whether that field holds a hook id.
- The exact field names in the log.
- Whether any Korvus click rows exist at all.

I won't infer field names or hook-id presence from the aggregate or from the tagging rollout. Herald needs a confirmed answer, and a guess would be worse than none.

**To close this, send one of the following:**
1. **A sample of raw rows** (last 20 to 50 outbound Korvus clicks, or the full row set if it's small). The field names and `utm_content` values can be read directly.
2. **The log schema or export query**, if rows aren't accessible from this desk.

**If the log returns zero Korvus click rows:** say so plainly. That means either no outbound Korvus clicks happened in the window, or the click log isn't capturing them. The aggregate alone can't distinguish those cases, so the schema check would need a row-level look at the capture path, not a count.

Once I have the rows, I'll report the exact field names, whether `utm_content` is present on every row, whether it carries a hook id, and any rows where it's missing or malformed.
