# Watcher hero, verbatim for Steward

Status: style block and body markup both returned with closing tags seen. Page not assembled: wrapper text still needs verification in full before any proposal.

## Style block

<style>
:root{--accent:#ff2d8f;--bg:#07060b;--ink:#ece9f2;--mute:#9a95a8}
body{margin:0;color:var(--ink);background:radial-gradient(at 12% 8%,rgba(255,45,143,.16),#0000 40%) var(--bg),linear-gradient(rgba(255,255,255,.015) 1px,#0000 1px) 0 0/56px 56px,linear-gradient(90deg,rgba(255,255,255,.015) 1px,#0000 1px) 0 0/56px 56px;overflow-x:hidden}
body::after{content:"";position:fixed;inset:0;pointer-events:none;background:radial-gradient(#0000 55%,rgba(0,0,0,.7))}
.hero{max-width:1060px;margin:0 auto;padding:80px 20px;position:relative}
.hero h1{font-size:clamp(2rem,6vw,3.6rem);line-height:1.1;margin:0 0 16px}
.hero p{max-width:62ch;color:var(--mute)}
</style>

## Body markup

<header>
<svg viewBox="0 0 36 33" fill="none" stroke="#ff2d8f" stroke-width="2.4" stroke-linejoin="round" stroke-linecap="round"><path d="M4 24 L4 9 L12 16 L18 5 L24 16 L32 9 L32 24 Z"/><path d="M8 28 L28 28"/></svg>
<span>KORVUS</span>
</header>
<section class="hero">
<h1>The all seeing watcher.</h1>
<p>Index futures never sleep, and neither does Korvus. 24/7 market watch while you rest, so the open finds you ready.</p>
<div class="chips"><span>Illustration</span><span>Overnight watch</span><span>Scored news</span><span>Market intelligence</span></div>
<p>Illustration: sample overnight watch panel, not live data.</p>
</section>
</body>
