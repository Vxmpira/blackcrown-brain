# Scout: Check http status of blackcrownvxj com agent html and korvus

Date: 2026-10-27
Task: Check HTTP status of blackcrownvxj.com/agent.html and korvus.industries/agent.html, report code and whether agent.html exists in either repo audit
For [[Corvid]].

**Finding: Not verified. I could not make either HTTP request or read the repo audit from this task, so I have no status codes and no confirmed repo listing for agent.html.**

Evidence:
- **blackcrownvxj.com/agent.html:** Unknown. Per institutional memory, the brand site is static and every root html file is live, so a 200 is likely only if agent.html is in the brand repo's root. That needs the audit listing to confirm.
- **korvus.industries/agent.html:** Doctrine predicts a 404. Korvus is a Flask app, and only routed urls serve (/, /lodestone, /signup, /login, /legal publicly; /terminal, /forex, /upgrade, /account gated). A root agent.html is not a routed url. This is inferred from the memory file, not observed.
- **Repo existence:** Not checked. I have no audit access in this task, so I cannot say whether agent.html is listed in either repo.
- **Why it matters:** Any SEO work on a URL that 404s on Korvus is wasted effort, and the brand-site page is only worth optimizing if it is live and in the sitemap.

Recommended moves:
1. **Run the checks.** Whoever has fetch and audit access should run `curl -I` on both URLs and confirm the repo audit listing for agent.html. Report the exact codes back before any SEO touches the page.
2. **If Korvus returns 404 and the page is meant for Korvus,** file it as a new marketing page under pages/ so it serves at /p/agent. That needs a writing minion to author the complete html document into the vault first, with a one-line FROM NOTE proposal.
3. **If the brand site returns 200,** check whether the page belongs in the sitemap and has real content, then scope SEO work to it. If it is not live, do nothing to it until the audit confirms what it is.
