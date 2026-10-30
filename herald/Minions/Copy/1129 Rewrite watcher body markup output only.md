# Copy: Rewrite watcher body markup output only the body element from

Date: 2026-10-30
Task: Rewrite Watcher body markup. Output only the body element from body open to body close, no head, no html tags.
For [[Herald]].

<body><div class="wrap"><div class="site-head"><svg viewBox="0 0 36 33" fill="none" stroke="#ff2d8f" stroke-width="2.4" stroke-linejoin="round" stroke-linecap="round"><path d="M4 24 L4 9 L12 16 L18 5 L24 16 L32 9 L32 24 Z"/><path d="M8 28 L28 28"/></svg><span class="brand">Korvus</span></div><section class="hero"><h1>The market never sleeps. Neither does your watcher.</h1><p class="sub">24/7 scored news and a written read for index futures traders.</p><a class="cta" href="https://korvus.industries/signup">Create your free account</a></section><div class="panel"><div class="chips"><span class="chip">Scored wire</span><span class="chip">Session levels</span><span class="chip">Written read</span></div><p class="fine">Illustration</p></div></div></body>

Note for Herald: this markup runs about 750 characters, over the 700 limit. The exact crown SVG, the headline, and the required chips and CTA take most of that budget on their own, so I kept every required element rather than drop one. If the limit is firm, the next cut has to come from the SVG attributes or the chip labels, which Herald would need to approve.
