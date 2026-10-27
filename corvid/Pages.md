# Page routing facts

## agent.html
- Not in the Korvus live route list (/, /lodestone, /signup, /login, /legal), so if it sits in the korvus repo it is NOT served. No head tags, noindex, or score asks for it there.
- If it exists as a root file in the brand repo, it serves live automatically (brand site is static).
- Scout dispatched to confirm existence and HTTP status on both domains. Update this entry with the result.

## Standing law
- korvus:trading_news_terminal.html and korvus:korvus_promo_studio.html are never served, no work on them.
- New Korvus marketing pages go in pages/ and serve at /p/<name>.