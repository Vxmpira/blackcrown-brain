# Copy: Write watcher style part two a single style block under

Date: 2026-10-30
Task: Write Watcher style part two: a single style block under 40 lines covering .wrap, .hero, .panel, .chips, .chip, .cta and figure styling at desktop and mobile wi
For [[Herald]].

<style>
.wrap{max-width:1060px;margin:0 auto;padding:0 20px;position:relative;z-index:1}
.hero{padding:clamp(48px,9vw,110px) 0 clamp(32px,6vw,72px);display:grid;gap:clamp(20px,3vw,32px)}
.hero h1{font-size:clamp(2rem,5.2vw,3.6rem);line-height:1.08;margin:0;color:var(--text);letter-spacing:-.02em;max-width:18ch}
.hero p{font-size:clamp(1rem,1.6vw,1.12rem);color:var(--muted);max-width:62ch;margin:0}
.panel{background:rgba(255,255,255,.02);border:1px solid var(--line);border-radius:14px;padding:clamp(18px,3vw,28px)}
.chips{display:flex;flex-wrap:wrap;gap:8px;margin:0;padding:0;list-style:none}
.chip{font-size:.8rem;color:var(--text);border:1px solid var(--line);border-radius:999px;padding:6px 12px;background:rgba(255,45,143,.06)}
.cta{display:inline-flex;align-items:center;justify-content:center;min-height:44px;padding:0 22px;border-radius:10px;background:var(--pink);color:var(--ink);font-weight:700;text-decoration:none;box-shadow:0 0 24px rgba(255,45,143,.35)}
.cta:hover{filter:brightness(1.08)}
.cta:focus-visible{outline:2px solid var(--text);outline-offset:3px}
figure{margin:0;border:1px solid var(--line);border-radius:14px;overflow:hidden;background:rgba(255,255,255,.015)}
figure img,figure svg{display:block;width:100%;height:auto}
figcaption{font-size:.8rem;color:var(--muted);padding:10px 14px;border-top:1px solid var(--line)}
@media (min-width:700px){.hero{grid-template-columns:1.1fr .9fr;align-items:center}.hero .cta{justify-self:start}figure{min-height:280px}}
@media (max-width:699px){.wrap{padding:0 16px}.hero .cta{width:100%}.chip{font-size:.76rem}}
</style>
