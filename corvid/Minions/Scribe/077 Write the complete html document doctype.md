# Scribe: Write the complete html document doctype through closing html tag

Date: 2026-10-26
Task: Write the COMPLETE html document, doctype through closing html tag with full head, title, and body, for the Korvus SEO page at korvus.industries/p/futures-news-
For [[Corvid]].

<!doctype html>
<!-- Slug note for Corvid: the task slug is futures-news- (trailing hyphen) but the canonical given is /p/futures-news-terminal. Confirm the served path matches the canonical before filing. -->
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Index Futures News, Scored | Korvus</title>
<meta name="description" content="Scored index futures news, a live futures board, cross index SMT divergence, and session context. Korvus is a 24/7 terminal. Free Observer tier, Operator from 9.99 a month.">
<link rel="canonical" href="https://korvus.industries/p/futures-news-terminal">
<meta property="og:type" content="website">
<meta property="og:site_name" content="Korvus">
<meta property="og:title" content="Index Futures News, Scored | Korvus">
<meta property="og:description" content="Scored index futures news, a live futures board, cross index SMT divergence, and session context. Built for beginners who want to read the market before they trade it.">
<meta property="og:url" content="https://korvus.industries/p/futures-news-terminal">
<meta property="og:image" content="https://korvus.industries/static/og-korvus.png">
<meta name="twitter:card" content="summary_large_image">
<meta name="twitter:title" content="Index Futures News, Scored | Korvus">
<meta name="twitter:description" content="Scored index futures news and session context for index futures traders. Free Observer tier.">
<style>
  :root {
    --bg: #07080a;
    --panel: #0d0f13;
    --panel-2: #12151b;
    --line: #22262e;
    --text: #e8e9ec;
    --muted: #9aa0ab;
    --accent: #ff2d8f;
    --ok: #3ddc97;
    --warn: #f5b84a;
  }
  * { box-sizing: border-box; }
  html, body { margin: 0; padding: 0; background: var(--bg); color: var(--text); }
  body {
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
    line-height: 1.6;
    font-size: 16px;
  }
  a { color: var(--accent); text-decoration: none; }
  a:hover { text-decoration: underline; }
  .wrap { max-width: 1040px; margin: 0 auto; padding: 0 20px; }

  header.site {
    border-bottom: 1px solid var(--line);
    padding: 16px 0;
    background: var(--bg);
  }
  .brand { display: flex; align-items: center; gap: 10px; font-weight: 700; letter-spacing: 0.04em; color: var(--text); }
  .brand svg { width: 32px; height: 29px; }
  .brand span.tag { color: var(--muted); font-weight: 400; font-size: 13px; margin-left: 6px; }
  nav.top { float: right; margin-top: 6px; }
  nav.top a { color: var(--muted); margin-left: 18px; font-size: 14px; }
  nav.top a.cta-small { color: var(--bg); background: var(--accent); padding: 6px 12px; border-radius: 4px; }
  header.site::after { content: ""; display: block; clear: both; }

  .hero { padding: 64px 0 40px; }
  .eyebrow { color: var(--accent); font-size: 13px; letter-spacing: 0.12em; text-transform: uppercase; margin: 0 0 14px; }
  h1 { font-size: clamp(30px, 5vw, 46px); line-height: 1.12; margin: 0 0 18px; font-weight: 750; max-width: 760px; }
  .lede { color: var(--muted); font-size: 18px; max-width: 680px; margin: 0 0 28px; }
  .btn {
    display: inline-block; background: var(--accent); color: #0b0b0d; font-weight: 700;
    padding: 14px 22px; border-radius: 6px; font-size: 16px;
  }
  .btn:hover { text-decoration: none; filter: brightness(1.08); }
  .btn-ghost {
    display: inline-block; border: 1px solid var(--line); color: var(--text);
    padding: 13px 20px; border-radius: 6px; margin-left: 10px; font-size: 15px;
  }
  .btn-ghost:hover { text-decoration: none; border-color: var(--muted); }
  .micro { color: var(--muted); font-size: 13px; margin-top: 12px; }

  .chips { display: flex; flex-wrap: wrap; gap: 10px; margin: 26px 0 0; padding: 0; list-style: none; }
  .chips li {
    background: var(--panel-2); border: 1px solid var(--line); color: var(--text);
    padding: 7px 12px; border-radius: 999px; font-size: 13px;
  }

  section { padding: 44px 0; border-top: 1px solid var(--line); }
  h2 { font-size: 26px; margin: 0 0 14px; font-weight: 700; }
  h3 { font-size: 17px; margin: 0 0 8px; font-weight: 700; }
  p { margin: 0 0 14px; }
  .muted { color: var(--muted); }

  .grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(240px, 1fr)); gap: 16px; margin-top: 22px; }
  .card { background: var(--panel); border: 1px solid var(--line); border-radius: 8px; padding: 20px; }
  .card .num { color: var(--accent); font-size: 13px; letter-spacing: 0.1em; margin-bottom: 8px; }

  .figure { background: var(--panel); border: 1px solid var(--line); border-radius: 10px; overflow: hidden; }
  .figure-head {
    display: flex; justify-content: space-between; align-items: center;
    padding: 12px 16px; border-bottom: 1px solid var(--line); background: var(--panel-2);
    font-size: 13px; color: var(--muted);
  }
  .figure-head strong { color: var(--text); font-weight: 600; }
  .badge-illus {
    font-size: 11px; letter-spacing: 0.1em; text-transform: uppercase;
    border: 1px solid var(--warn); color: var(--warn); padding: 3px 8px; border-radius: 4px;
  }
  .feed { list-style: none; margin: 0; padding: 0; }
  .feed li { padding: 14px 16px; border-bottom: 1px solid var(--line); display: grid; grid-template-columns: 1fr auto; gap: 6px 14px; align-items: start; }
  .feed li:last-child { border-bottom: none; }
  .feed .time { color: var(--muted); font-size: 12px; font-variant-numeric: tabular-nums; }
  .feed .headline { font-size: 15px; }
  .feed .read { grid-column: 1 / -1; color: var(--muted); font-size: 13px; margin: 0; }
  .score { display: flex; gap: 6px; flex-wrap: wrap; justify-content: flex-end; }
  .pill { font-size: 11px; padding: 3px 7px; border-radius: 4px; border: 1px solid var(--line); color: var(--text); white-space: nowrap; }
  .pill.high { border-color: var(--accent); color: var(--accent); }
  .pill.up { border-color: var(--ok); color: var(--ok); }
  .pill.down { border-color: var(--warn); color: var(--warn); }
  .board { display: grid; grid-template-columns: repeat(3, 1fr); border-top: 1px solid var(--line); }
  .board div { padding: 12px 14px; border-right: 1px solid var(--line); font-size: 13px; }
  .board div:last-child { border-right: none; }
  .board .sym { color: var(--muted); font-size: 11px; letter-spacing: 0.08em; }
  .board .px { font-size: 18px; font-weight: 700; font-variant-numeric: tabular-nums; }
  .board .chg-up { color: var(--ok); }
  .board .chg-dn { color: var(--warn); }

  .tiers { display: grid; grid-template-columns: repeat(auto-fit, minmax(280px, 1fr)); gap: 16px; margin-top: 22px; }
  .tier { background: var(--panel); border: 1px solid var(--line); border-radius: 10px; padding: 24px; }
  .tier.featured { border-color: var(--accent); }
  .tier .price { font-size: 30px; font-weight: 750; margin: 6px 0 4px; }
  .tier .price small { font-size: 14px; color: var(--muted); font-weight: 400; }
  .tier ul { padding-left: 18px; margin: 14px 0 0; color: var(--muted); font-size: 15px; }
  .tier ul li { margin-bottom: 6px; }
  .tier .save { color: var(--ok); font-size: 13px; }

  .faq details { border-bottom: 1px solid var(--line); padding: 14px 0; }
  .faq summary { cursor: pointer; font-weight: 600; font-size: 16px; }
  .faq details p { color: var(--muted); margin: 10px 0 0; }

  .disclaimer {
    border: 1px solid var(--line); background: var(--panel); border-radius: 8px;
    padding: 18px 20px; color: var(--muted); font-size: 13px; margin-top: 8px;
  }
  .final { text-align: left; padding: 56px 0 72px; }
  footer.site { border-top: 1px solid var(--line); padding: 26px 0 40px; color: var(--muted); font-size: 13px; }
  footer.site a { color: var(--muted); margin-right: 14px; }

  @media (max-width: 720px) {
    nav.top { float: none; margin-top: 12px; }
    nav.top a { margin-left: 0; margin-right: 14px; }
    .board { grid-template-columns: 1fr; }
    .board div { border-right: none; border-bottom: 1px solid var(--line); }
    .btn-ghost { margin-left: 0; margin-top: 10px; display: inline-block; }
    .feed li { grid-template-columns: 1fr; }
    .score { justify-content: flex-start; }
  }
</style>
</head>
<body>

<header class="site">
  <div class="wrap">
    <a class="brand" href="https://korvus.industries/" aria-label="Korvus home">
      <svg viewBox="0 0 36 33" fill="none" stroke="#ff2d8f" stroke-width="2.4" stroke-linejoin="round" stroke-linecap="round"><path d="M4 24 L4 9 L12 16 L18 5 L24 16 L32 9 L32 24 Z"/><path d="M8 28 L28 28"/></svg>
      <span>KORVUS<span class="tag">by BlackCrown</span></span>
    </a>
    <nav class="top">
      <a href="https://korvus
