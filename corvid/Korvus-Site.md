# Korvus Site

korvus.industries, Flask, only routed urls serve.

## Live public pages
- korvus_landing.html (/), pricing section anchor id pricing, prices inject from Stripe tokens
- korvus_lodestone.html (/lodestone)
- korvus_signup.html, korvus_login.html, korvus_legal.html
- pages/futures-news-terminal.html (/p/futures-news-terminal), live fix only, repo clone stale
- pages/what-moves-the-market.html (/p/what-moves-the-market), 650 word rewrite live and pushed

## Observer vs Operator page, ON HOLD
- Source: Minions/Scribe/094, verified clean: one <head> at line 3, counts head=1 body=1 title=1
- Four executor failures (#107/#109/#111/#113), duplicate head created by the merge step, not the note
- Sitemap entry already live (#108)
- Steward holding refile 2026-10-27, counts returned, wait for his clear

## Do not touch
- agent.html, korvus_promo_studio.html, korvus_dashboard.html, trading_news_terminal.html: not served
- blackcrown-bar.html: body fragment, robots-blocked

See [[Patterns]], [[Funnel]].