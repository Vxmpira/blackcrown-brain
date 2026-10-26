# scout: Determine what blackcrown-bar.html is in the korvus and crown repos: a shared nav component included into pages, or a standalone reachable page. Report its full

For [[Corvid]], 2026-10-25.

# Scout Report: blackcrown-bar.html ,  fragment or page?

**Finding: Almost certainly a shared nav include fragment, not a standalone page. I cannot confirm with 100% certainty because the file contents were not provided to me, only the audit metadata.**

## Evidence

From the audit data you gave me:

- **No `<head>`, no `<title>`:** A deliberate standalone page in either repo would almost never ship with zero head tags. A fragment meant to be injected into an existing DOM has no reason to carry them.
- **46 words:** Consistent with a nav bar (brand name, 4-6 links, maybe a tagline or CTA). Far too thin to be an intentional content page.
- **Identical filename in both korvus and crown repos:** The strongest signal. A duplicated, identically named, headless, 46-word file across two properties is the classic pattern of a shared branding/nav component copied into each repo.
- **Naming convention:** "blackcrown-bar" reads as "the BlackCrown bar," i.e. a cross-property nav strip linking the family (Korvus, Crown, Eclipse-X). This part is inference from the name, not from data.

What I could not verify (flagging plainly, this is the gap):

- I do not have the raw file contents or the repo tree, so I cannot confirm whether other pages reference it via fetch/include, iframe, or build-time templating.
- I cannot confirm whether it is reachable at a live URL (e.g. `korvus.example/blackcrown-bar.html`). If the repos deploy as static sites, it almost certainly **is** reachable even though it is a fragment. That is the real risk: fragment by intent, page by accident.

## Recommended moves

1. **Confirm the include mechanism before filing:** grep both repos for `blackcrown-bar` to find the referencing pages (look for `fetch(`, `include`, `iframe src=`, or template directives). One match pattern settles this in under a minute.
2. **File as "exclude + block," not "add head":** if confirmed as a fragment, the fix is (a) exclude it from the audit scoring set, and (b) prevent accidental indexing of the live URL via `X-Robots-Tag: noindex` or robots.txt disallow, since you cannot put a meta robots tag in a headless fragment reliably. Do not give it a full head.
3. **Check for a third copy:** if korvus and crown both carry it, Eclipse-X likely does too. Scope the fix once across all three repos rather than filing per-repo tickets.
