# Copy: Write the watcher head and hero body markup for korvus

Date: 2026-11-01
Task: Write the Watcher head and hero body markup for korvus:pages/index-watch.html as two parts, each under 700 characters. Part one is doctype through the opening b
For [[Herald]].

**Part one (doctype through opening body tag)**

```html
<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Korvus Watcher | Market Watch While You Sleep</title>
<meta name="description" content="Korvus watches index futures around the clock and writes every read in plain language. Free account, no card required.">
<link rel="canonical" href="https://korvus.industries/p/index-watch">
</head>
<body>
```

**Part two (header and hero body)**

```html
<header class="top"><a class="brand" href="/"><svg viewBox="0 0 36 33" fill="none" stroke="#ff2d8f" stroke-width="2.4" stroke-linejoin="round" stroke-linecap="round"><path d="M4 24 L4 9 L12 16 L18 5 L24 16 L32 9 L32 24 Z"/><path d="M8 28 L28 28"/></svg>Korvus</a></header>
<main class="hero wrap">
<h1>The market moves while you sleep. Korvus keeps watch.</h1>
<p class="lede">Korvus scores the wire around the clock. Wake up briefed.</p>
<a class="btn" href="/signup">Start free</a>
<p class="note">No card required. Not financial advice.</p>
</main>
```

The style block goes inside the head, just before `</head>`. The closing `</main>`, footer, and `</body></html>` are not part of these two parts.
