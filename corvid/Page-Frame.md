# The Page Frame

Owner law, 10-30. Every new page on any property is built INSIDE this skeleton. Copy it whole, replace only the UPPERCASE slots and the content inside the two CONTENT markers. Never invent your own scaffolding, head, or background. Preflight rejects pages missing the viewport meta, the atmosphere, or a bare table outside a tablewrap.

Korvus pages use accent #FF2D95 with the gold #E8C77F as secondary. Brand and Crown pages swap --accent to their palette but keep every structure.

```html
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>PAGE TITLE, UNDER 60 CHARS</title>
<meta name="description" content="ONE SENTENCE, UNDER 155 CHARS">
<link rel="canonical" href="https://korvus.industries/p/SLUG">
<meta property="og:title" content="PAGE TITLE">
<meta property="og:description" content="SAME SENTENCE">
<meta property="og:type" content="article">
<link rel="preconnect" href="https://fonts.googleapis.com"><link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=JetBrains+Mono:wght@400;500&family=Manrope:wght@400;500;700&family=Space+Grotesk:wght@500;600;700&display=swap" rel="stylesheet">
<style>
:root{--ink:#000000;--panel:#0D0D11;--panel2:#111118;--white:#FFFFFF;--bone:#E8E8EF;--mute:#85838F;--faint:#55545E;
--accent:#FF2D95;--accent-soft:#FF6FB6;--accent-deep:#C81E73;--gold:#E8C77F;
--line:rgba(255,45,149,.2);--line-soft:rgba(255,255,255,.08)}
*{box-sizing:border-box;margin:0;padding:0}
html{scroll-behavior:smooth;-webkit-text-size-adjust:100%}
body{background:var(--ink);color:var(--bone);font-family:'Manrope',system-ui,sans-serif;font-size:17px;line-height:1.7;position:relative;z-index:0}
body::before{content:"";position:fixed;inset:0;z-index:-1;pointer-events:none;background:
 radial-gradient(60% 45% at 50% -10%, rgba(232,199,127,.08), transparent 70%),
 radial-gradient(45% 40% at 88% 88%, rgba(255,45,149,.06), transparent 70%),
 repeating-linear-gradient(0deg, rgba(255,255,255,.015) 0 1px, transparent 1px 56px),
 repeating-linear-gradient(90deg, rgba(255,255,255,.015) 0 1px, transparent 1px 56px),
 radial-gradient(130% 95% at 50% 35%, transparent 55%, rgba(0,0,0,.55) 100%)}
.wrap{max-width:1060px;margin:0 auto;padding:0 clamp(18px,4vw,32px)}
header.top{border-bottom:1px solid var(--line-soft);padding:16px 0}
.brand{display:flex;align-items:center;gap:10px;text-decoration:none;color:var(--white)}
.brand svg{width:30px;height:27px}
.brand b{font-family:'Space Grotesk',sans-serif;letter-spacing:.14em;font-size:.95rem}
.brand span{font-family:'JetBrains Mono',monospace;font-size:.68rem;letter-spacing:.22em;color:var(--accent)}
main{padding:clamp(1.8rem,5vw,3.5rem) 0 4rem}
.eyebrow{display:inline-block;font-family:'JetBrains Mono',monospace;font-size:.68rem;letter-spacing:.24em;text-transform:uppercase;color:var(--gold);border:1px solid rgba(232,199,127,.35);border-radius:999px;padding:.3rem .8rem;margin-bottom:1.1rem}
h1{font-family:'Space Grotesk',sans-serif;font-size:clamp(1.9rem,4.2vw,3.1rem);line-height:1.12;color:var(--white);margin-bottom:.9rem;max-width:21ch}
.lede{font-size:clamp(1.02rem,1.5vw,1.2rem);color:var(--mute);max-width:72ch;margin-bottom:1.2rem}
.chips{display:flex;flex-wrap:wrap;gap:.5rem;margin:0 0 2.2rem}
.chips span{font-size:.78rem;color:var(--mute);border:1px solid var(--line-soft);border-radius:999px;padding:.28rem .75rem}
h2{font-family:'Space Grotesk',sans-serif;font-size:clamp(1.3rem,2.4vw,1.7rem);color:var(--white);margin:2.6rem 0 .8rem}
p{max-width:72ch;margin-bottom:1rem}
p b{color:var(--white)}
ul,ol{max-width:70ch;margin:0 0 1rem 1.2rem}
li{margin-bottom:.45rem}
a{color:var(--accent-soft)}
.panel{background:linear-gradient(180deg,var(--panel),var(--panel2));border:1px solid var(--line-soft);border-radius:14px;padding:clamp(1rem,2.5vw,1.6rem);margin:1.4rem 0}
.panel .tag{font-family:'JetBrains Mono',monospace;font-size:.64rem;letter-spacing:.24em;color:var(--accent);margin-bottom:.8rem}
.tablewrap{overflow-x:auto;-webkit-overflow-scrolling:touch;margin:1.1rem 0;max-width:100%}
.tablewrap table{width:100%;min-width:540px;border-collapse:collapse;font-size:.95rem}
th{text-align:left;font-family:'JetBrains Mono',monospace;font-size:.7rem;letter-spacing:.16em;text-transform:uppercase;color:var(--mute);padding:.6rem .8rem;border-bottom:1px solid var(--line-soft)}
td{padding:.65rem .8rem;border-bottom:1px solid rgba(255,255,255,.05)}
.note{font-size:.86rem;color:var(--faint);max-width:72ch}
.cta{display:inline-block;background:var(--accent);color:#000;font-weight:700;text-decoration:none;border-radius:999px;padding:.8rem 1.6rem;margin:1.6rem 0;box-shadow:0 0 18px rgba(255,45,149,.35)}
footer{border-top:1px solid var(--line-soft);padding:1.4rem 0 2.2rem;font-size:.85rem;color:var(--faint)}
@media(max-width:700px){.chips{gap:.4rem}h1{max-width:none}}
</style>
</head>
<body>
<header class="top"><div class="wrap">
<a class="brand" href="https://korvus.industries">
<svg viewBox="0 0 36 33" fill="none" stroke="#ff2d8f" stroke-width="2.4" stroke-linejoin="round" stroke-linecap="round"><path d="M4 24 L4 9 L12 16 L18 5 L24 16 L32 9 L32 24 Z"/><path d="M8 28 L28 28"/></svg>
<b>KORVUS</b> <span>GUIDES</span>
</a>
</div></header>
<main><div class="wrap">
<span class="eyebrow">EDUCATION</span>
<h1>PAGE H1</h1>
<p class="lede">ONE OR TWO SENTENCE SUMMARY.</p>
<div class="chips"><span>Beginner level</span><span>Index futures</span><span>Education only</span></div>
<!-- CONTENT STARTS: h2 sections, p, ul, .panel blocks for reference data,
     every table inside <div class="tablewrap">, at least one visual element
     (a .panel data mock, an inline svg figure, or the chips row above).
     Mark illustrative data with a .panel .tag reading ILLUSTRATION. -->

<!-- CONTENT ENDS -->
<a class="cta" href="https://korvus.industries/signup?utm_source=korvus&utm_medium=page&utm_campaign=SLUG">Start free on Observer</a>
<p class="note">Education only, not financial advice. Korvus watches index futures while you sleep.</p>
</div></main>
<footer><div class="wrap">BlackCrownVxJ LLC &middot; <a href="https://korvus.industries">korvus.industries</a></div></footer>
</body>
</html>
```
