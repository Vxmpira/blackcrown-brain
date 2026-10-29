# Scout: Fetch blackcrownvxj com index html and extract every anchor pointing

Date: 2026-10-29
Task: Fetch blackcrownvxj.com index.html and extract every anchor pointing at korvus.industries, verbatim markup
For [[Corvid]].

**Finding: I could not fetch blackcrownvxj.com/index.html in this run, so I have no anchor markup, hrefs, or UTM data to report.** Nothing below is from the live page.

**What I need to finish the audit**
- Fetch access to `blackcrownvxj.com/index.html` (static root file, so it is live as-is), or the file pulled from the brand site repo.
- Once I have it, I will return every `<a>` whose href contains `korvus.industries`, verbatim, with the 2 to 3 lines of surrounding markup for each.
- For each link I will record: full href, UTM params present or missing (the standing UTM tagging shipped 2026-10-26 should be on every outbound Korvus link), target path, and whether that path is one of the public routes (/, /lodestone, /signup, /login, /legal) or a gated one (/terminal, /forex, /upgrade, /account).

**What to check first, from the infrastructure notes (reasoning, not verified against this page)**
- **Missing UTMs.** If the links lack the tagging, 37 visits could arrive as direct or get dropped in attribution, which would look like zero Korvus arrivals even when clicks happen. This is the cheapest explanation to rule out first.
- **Gated targets.** A link to /terminal, /forex, /upgrade, or /account from a public brand page bounces visitors to login. That reads as a leak.
- **Non-routed paths.** Any href to a page under korvus.industries that the Flask app does not serve returns nothing useful. Only routed URLs serve.
- **JS-injected links.** If the anchors are built by script, they will not appear in the static html and a plain fetch will miss them.

**Recommended moves**
1. Re-run this task with fetch access to the root index.html, so the anchor audit uses real markup instead of assumptions.
2. Ask the desk that owns the brand site to confirm UTM tagging on the Korvus links it ships, since that is the quickest test of the attribution theory.
3. Once the anchors are extracted, compare each path against the public route list and file any leaking link as a content edit proposal with the exact anchor text as the CURRENT line.
