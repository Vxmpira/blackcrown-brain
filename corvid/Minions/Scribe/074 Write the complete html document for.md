# Scribe: Write the complete html document for a new korvus seo

Date: 2026-10-26
Task: Write the COMPLETE html document for a new Korvus SEO page targeting the keyword futures news terminal, doctype through closing html, no placeholders.
For [[Corvid]].

<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Futures News Terminal for Index Traders | Korvus</title>
<meta name="description" content="A futures news terminal built for beginner index traders. Scored news, futures board, cross index SMT and session context in one feed. Free Observer account.">
<link rel="canonical" href="https://korvus.industries/p/futures-news-terminal">
<meta property="og:type" content="website">
<meta property="og:title" content="Futures News Terminal for Index Traders | Korvus">
<meta property="og:description" content="Scored news, futures board, cross index SMT and session context in one terminal. Stop juggling tabs. Free Observer account.">
<meta property="og:url" content="https://korvus.industries/p/futures-news-terminal">
<meta property="og:site_name" content="Korvus">
<meta name="twitter:card" content="summary_large_image">
<meta name="twitter:title" content="Futures News Terminal for Index Traders | Korvus">
<meta name="twitter:description" content="Scored news, futures board, cross index SMT and session context in one terminal. Free Observer account.">
<style>
  :root {
    --bg: #07070b;
    --panel: #0d0d15;
    --panel-2: #12121c;
    --line: #1f1f2e;
    --text: #e9e7f2;
    --muted: #9a98ab;
    --royal: #5b3cff;
    --royal-soft: #8b7bff;
    --pink: #ff2d8f;
    --green: #3ddc97;
    --red: #ff5d6c;
    --amber: #f5b942;
  }
  * { box-sizing: border-box; }
  html, body { margin: 0; padding: 0; background: var(--bg); color: var(--text); }
  body {
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Inter, Roboto, Helvetica, Arial, sans-serif;
    line-height: 1.6;
    -webkit-font-smoothing: antialiased;
  }
  a { color: var(--royal-soft); text-decoration: none; }
  a:hover { text-decoration: underline; }
  .wrap { max-width: 1080px; margin: 0 auto; padding: 0 24px; }

  header.site {
    border-bottom: 1px solid var(--line);
    background: rgba(7,7,11,0.92);
    position: sticky; top: 0; z-index: 10;
    backdrop-filter: blur(6px);
  }
  header.site .wrap {
    display: flex; align-items: center; justify-content: space-between;
    height: 64px;
  }
  .brand { display: flex; align-items: center; gap: 12px; color: var(--text); font-weight: 700; letter-spacing: 0.08em; text-transform: uppercase; font-size: 15px; }
  .brand:hover { text-decoration: none; }
  .brand svg { width: 36px; height: 33px; display: block; }
  nav.site-nav { display: flex; gap: 22px; font-size: 14px; }
  nav.site-nav a { color: var(--muted); }
  nav.site-nav a:hover { color: var(--text); text-decoration: none; }

  .hero { padding: 88px 0 56px; position: relative; overflow: hidden; }
  .hero::before {
    content: "";
    position: absolute; inset: -20% -10% auto -10%; height: 520px;
    background: radial-gradient(closest-side, rgba(91,60,255,0.28), rgba(91,60,255,0) 70%);
    pointer-events: none;
  }
  .eyebrow {
    display: inline-block;
    font-size: 12px; letter-spacing: 0.16em; text-transform: uppercase;
    color: var(--royal-soft);
    border: 1px solid rgba(139,123,255,0.35);
    padding: 6px 12px; border-radius: 999px;
    margin-bottom: 22px;
  }
  h1 {
    font-size: clamp(34px, 5.2vw, 56px);
    line-height: 1.08;
    margin: 0 0 20px;
    letter-spacing: -0.02em;
    max-width: 820px;
  }
  h1 .accent { color: var(--royal-soft); }
  .lede { font-size: 19px; color: var(--muted); max-width: 680px; margin: 0 0 32px; }

  .cta-row { display: flex; flex-wrap: wrap; gap: 14px; align-items: center; }
  .btn {
    display: inline-block;
    padding: 14px 24px;
    border-radius: 10px;
    font-weight: 600;
    font-size: 15px;
    border: 1px solid transparent;
  }
  .btn-primary {
    background: linear-gradient(135deg, var(--royal), #7a4dff);
    color: #fff;
    box-shadow: 0 10px 30px rgba(91,60,255,0.35);
  }
  .btn-primary:hover { text-decoration: none; filter: brightness(1.08); }
  .btn-ghost { border-color: var(--line); color: var(--text); background: var(--panel); }
  .btn-ghost:hover { text-decoration: none; border-color: var(--royal-soft); }
  .micro { font-size: 13px; color: var(--muted); }

  section { padding: 64px 0; border-top: 1px solid var(--line); }
  h2 { font-size: 30px; letter-spacing: -0.01em; margin: 0 0 14px; line-height: 1.2; }
  h3 { font-size: 18px; margin: 0 0 8px; }
  .sub { color: var(--muted); max-width: 680px; margin: 0 0 36px; }

  .chips { display: flex; flex-wrap: wrap; gap: 10px; margin: 0 0 8px; }
  .chip {
    background: var(--panel);
    border: 1px solid var(--line);
    color: var(--text);
    padding: 8px 14px;
    border-radius: 999px;
    font-size: 13px;
  }
  .chip b { color: var(--royal-soft); font-weight: 600; margin-right: 6px; }

  .grid-3 { display: grid; grid-template-columns: repeat(3, 1fr); gap: 18px; }
  .card {
    background: linear-gradient(180deg, var(--panel-2), var(--panel));
    border: 1px solid var(--line);
    border-radius: 14px;
    padding: 24px;
  }
  .card p { margin: 0; color: var(--muted); font-size: 15px; }
  .card .tag { font-size: 12px; letter-spacing: 0.12em; text-transform: uppercase; color: var(--royal-soft); margin-bottom: 10px; display: block; }

  .problem-list { list-style: none; padding: 0; margin: 0; display: grid; gap: 12px; }
  .problem-list li {
    padding: 16px 18px;
    background: var(--panel);
    border: 1px solid var(--line);
    border-radius: 10px;
    color: var(--muted);
    display: flex; gap: 14px; align-items: flex-start;
  }
  .problem-list li .x { color: var(--red); font-weight: 700; }

  .figure { margin: 0; }
  .figure-label {
    display: flex; justify-content: space-between; align-items: center;
    font-size: 12px; letter-spacing: 0.12em; text-transform: uppercase;
    color: var(--muted); margin-bottom: 12px;
  }
  .figure-label .illus {
    color: var(--amber);
    border: 1px solid rgba(245,185,66,0.4);
    padding: 3px 10px; border-radius: 999px;
  }
  .panel {
    background: var(--panel);
    border: 1px solid var(--line);
    border-radius: 16px;
    overflow: hidden;
    box-shadow: 0 30px 60px rgba(0,0,0,0.5), 0 0 0 1px rgba(91,60,255,0.12);
  }
  .panel-head {
    display: grid; grid-template-columns: 90px 1fr 110px 120px 110px;
    gap: 12px; padding: 12px 20px;
    background: var(--panel-2);
    border-bottom: 1px solid var(--line);
    font-size: 11px; letter-spacing: 0.12em; text-transform: uppercase; color: var(--muted);
  }
  .row {
    display: grid; grid-template-columns: 90px 1fr 110px 120px 110px;
    gap: 12px; padding: 18px 20px;
    border-bottom: 1px solid var(--line);
    align-items: center;
    font-size: 14px;
  }
  .row:last-child { border-bottom: none; }
  .row .time { color: var(--muted); font-variant-numeric: tabular-nums; }
  .row .headline { color: var(--text); }
  .row .headline small { display: block; color: var(--muted); font-size: 13px; margin-top: 4px; }
  .pill {
    display: inline-block; padding: 4px 10px; border-radius: 999px;
    font-size: 12px; font-weight: 600; text-align: center;
  }
  .impact { color: var(--amber); font-variant-numeric: tabular-nums; }
  .impact i { font-style: normal; color: var(--line); }
  .dir-bear { background: rgba(255,93,108,0.14); color: var(--red); }
  .dir-bull { background: rgba(61,220,151,0.14); color: var(--green); }
  .dir-mixed { background: rgba(245,185,66,0.14); color: var(--amber); }
  .conf { font-variant-numeric: tabular-nums; color: var(--text); }
  .conf-bar { height: 4px; background: var(--line); border-radius: 4px; margin-top: 6px; overflow: hidden; }
  .conf-bar span { display: block; height: 100%; background: linear-gradient(90deg, var(--royal), var(--royal-soft)); }
  .read {
    padding: 18px 20px;
    background: linear-gradient(180deg, rgba(91,60,255,0.10), rgba(91,60,255,0.02));
    border-top: 1px solid var(--line);
    font-size: 14px; color: var(--muted);
  }
  .read strong { color: var(--text); }
  .figure-note { font-size: 13px; color: var(--muted); margin-top: 12px; }

  .steps { counter-reset: step; display: grid; gap: 14px; padding: 0; margin: 0; list-style: none; }
  .steps li {
    counter-increment: step;
    background: var(--panel);
    border: 1px solid var(--line);
    border-radius: 12px;
    padding: 20px 22px 20px 70px;
    position: relative;
    color: var(--muted);
  }
  .steps li::before {
    content: counter(step, decimal-leading-zero);
    position: absolute; left: 22px; top: 18px;
    font-weight: 700; color: var(--royal-soft); font-size: 18px;
  }
  .steps li strong { color: var(--text); display: block; margin-bottom: 4px; font-size: 16px; }

  .faq details {
    border-bottom: 1px solid var(--line);
    padding: 18px 0;
  }
  .faq details:first-child { border-top: 1px solid var(--line); }
  .faq summary { cursor: pointer; font-weight: 600; color: var(--text); list-style: none; }
  .faq summary::-webkit-details-marker { display: none; }
  .faq summary::after { content: "+"; float: right; color: var(--royal-soft); }
  .faq details[open] summary::after { content: "-"; }
  .faq details p { color: var(--muted); margin: 12px 0 0; font-size: 15px; }

  .closing {
    text-align: center;
    padding: 80px 0;
    background: radial-gradient(60% 80% at 50% 0%, rgba(91,60,255,0.22), rgba(7,7,11,0) 70%);
    border-top: 1px solid var(--line);
