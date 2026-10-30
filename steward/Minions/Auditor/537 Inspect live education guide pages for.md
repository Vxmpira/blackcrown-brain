# Auditor: Inspect live education guide pages for cta and click path

Date: 2026-10-30
Task: Inspect live education guide pages for CTA and click path
For [[Steward]].

**Audit status: blocked, no live inspection performed**

I can't fetch or render live pages from this desk, and no page HTML or URLs came with the task. Rather than guess at CTA presence, I haven't reported any page as having or lacking a CTA. Nothing below is a finding about the live pages.

**What I need to run the audit**

1. **Exact URLs or file paths** for each item. "#333", "#336", "#340", "#338", "#339", and "#341" read as task or ticket IDs, not page names. I can't map them to files without a list.
2. **Which domain each lives on.** Brand site root html files are live directly. Korvus pages serve only at routed urls, with new marketing pages under `/p/<name>`. The same guide could sit on either, and the CTA target differs.

**Checks I'll apply to each page once I have the URLs**

- **CTA present:** at least one above-the-fold and one closing action.
- **CTA target:** Korvus CTAs should point to `/signup` or the Operator path (9.99 a month or 79.99 a year, annual listed first). Crown CTAs go to blackcrown-intelligence.com. A CTA that dead-ends on the page itself is a miss.
- **UTM tagging:** every outbound Korvus link should carry the UTM tagging shipped 2026-10-26.
- **Not-advice disclaimer:** present wherever the page makes product or performance claims.
- **Doctrine basics:** no em dashes, inline crown SVG in the header, at least one real visual element, Illustration label on any mock data, and the page fits both desktop and phone.
- **Click path:** guide to CTA reachable within one click from the content, with no gated or broken hop on the way.

**Ranking rule:** findings will be ranked by revenue impact, meaning missing or broken CTAs on the highest-traffic guides first, and each will carry a one-line fix.

**If a fix is needed later:** it goes to Regent as a proposal, not a direct edit. The owner approves in #boardroom. Pages and the target file must already be confirmed in the audit before filing.

Send the URLs or file paths and I'll run the full pass.
