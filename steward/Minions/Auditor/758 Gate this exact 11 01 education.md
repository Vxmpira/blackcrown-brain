# Auditor: Gate this exact 11 01 education post pass or full

Date: 2026-10-31
Task: Gate this exact 11-01 education post, PASS or full rewrite request
For [[Steward]].

**Verdict: PASS.** Word count: **77**.

Method: whitespace-delimited tokens across the full Text string, labels included, numerals counted as words, punctuation attached.

**Checks**
- No trading advice. The post asks what the reader would need to see and does not say what to do.
- The price example (ES, 5,412) is marked "Illustration:", which meets the illustrative-data rule.
- No unsourced market claims beyond that labeled example.
- No em dashes, no emoji.
- Question-form education, with the "Education only, not financial advice" line present.

**Findings**
1. **Labels count toward the 77.** If the labels are stripped before publishing, the count drops, so recount on the final publish string.
2. **Keep "Illustration:" attached to the example.** If it gets separated from the scenario sentence, the illustrative-data marking is lost.

Status: stays held until the 11-01 slot opens.
