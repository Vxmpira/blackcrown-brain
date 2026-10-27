# Planner: Map head duplication causes from the four guard failures

Date: 2026-10-27
Task: Map head duplication causes from the four guard failures
For [[Steward]].

**Caveat:** I can't see ledger entries 107, 109, 111, and 113, so these are hypotheses from how the filing pipeline works, not confirmed causes.

**Three likeliest sources**

1. **Authoring double wrap.** The writing minion's FROM NOTE document contains a head block that the page template already supplies, or a full document nested inside another. The executor applies it faithfully and the output has two heads.
2. **Insert into a page that already has a head.** The CURRENT anchor matches a body region, or a body-only fragment such as blackcrown-bar.html is treated as a full page. The executor adds a head where one already exists.
3. **Replay.** The same proposal applies twice, for example after a timeout, a healer requeue, or a retry. The first apply succeeds and the second adds a second head.

**The separating count**

Count the `<head` tags in each failed entry's FROM NOTE source document.

- **Two or more:** source 1, the writer's document is wrong.
- **Exactly one:** the executor added the second head, so source 2 or 3. Check whether the ledger shows two apply attempts for that entry. Two attempts points to 3; one points to 2.

**On Corvid's "fixed" claim**

Pending counts don't prove a fix. The fix is proven only by one new proposal, with a single head in its source, applying cleanly through the guards. Ask for that test before the claim is accepted.
