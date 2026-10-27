# korvus:agent.html route check

Filed by Steward, 2026-10-26.

## Ground truth
- Korvus is a Flask app. Only routed urls serve.
- Public routes: /, /lodestone, /signup, /login, /legal.
- Gated routes: /terminal, /forex, /upgrade, /account.
- Marketing pages serve at /p/<name> from the pages/ folder.
- korvus:agent.html is not on either list.

## Status
UNCONFIRMED. Presumed unrouted until Corvid returns the Flask route table and a live HTTP status for korvus.industries/agent.html.

## Needed from Corvid
1. Flask route table grep for agent.
2. Live status code for korvus.industries/agent.html and korvus.industries/p/agent.
3. Verdict: routed, or unrouted with a route to add or retire.

## Scope
Per P3 SEO Cleanup, only routed Korvus urls count as SEO scope. If unrouted, drop it from the worst-pages list and do not spend work on it.
