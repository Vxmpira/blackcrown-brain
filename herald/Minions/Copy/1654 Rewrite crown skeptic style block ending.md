# Copy: Rewrite crown skeptic style block ending with the closing style

Date: 2026-11-13
Task: Rewrite Crown skeptic style block, ending with the closing style tag
For [[Herald]].

<style>
.skeptic{position:relative;isolation:isolate;background:#0d0c16;color:#e8e6ee;padding:clamp(48px,8vw,96px) 0;overflow:hidden;box-shadow:inset 0 0 160px rgba(0,0,0,.6)}
.skeptic::before{content:"";position:absolute;inset:0;z-index:-2;background:radial-gradient(640px 360px at 12% 8%,rgba(255,45,143,.16),transparent 70%),radial-gradient(520px 320px at 92% 30%,rgba(255,45,143,.10),transparent 70%),radial-gradient(700px 420px at 50% 110%,rgba(255,45,143,.12),transparent 70%)}
.skeptic::after{content:"";position:absolute;inset:0;z-index:-1;background-image:linear-gradient(rgba(255,255,255,.015) 1px,transparent 1px),linear-gradient(90deg,rgba(255,255,255,.015) 1px,transparent 1px);background-size:56px 56px}
.skeptic-wrap{max-width:1060px;margin:0 auto;padding:0 20px}
.skeptic h2{font-size:clamp(1.6rem,4vw,2.4rem);line-height:1.15;margin:0 0 14px;letter-spacing:-.01em;color:#fff}
.skeptic-lede{max-width:64ch;color:#b9b6c6;font-size:clamp(1rem,2.2vw,1.1rem);line-height:1.6;margin:0}
.skeptic-grid{display:grid;grid-template-columns:repeat(3,1fr);gap:16px;margin-top:28px}
@media (max-width:700px){.skeptic-grid{grid-template-columns:1fr}}
.skeptic-card{background:#15141f;border:1px solid rgba(255,45,143,.22);border-radius:14px;padding:22px}
.skeptic-card h3{margin:0 0 8px;font-size:1.05rem;color:#fff}
.skeptic-card p{margin:0;color:#b9b6c6;font-size:.95rem;line-height:1.55}
.skeptic-chip{display:inline-block;margin-top:14px;padding:4px 10px;border-radius:999px;background:rgba(255,45,143,.12);color:#ff2d8f;font-size:.78rem;letter-spacing:.04em}
.skeptic-quote{margin-top:28px;padding:18px 22px;border-left:3px solid #ff2d8f;background:#12111b;border-radius:0 12px 12px 0;color:#e8e6ee}
.skeptic-foot{margin-top:18px;font-size:.8rem;color:#8d8a9c}
.skeptic a{color:#ff2d8f}
.tablewrap{width:100%;overflow-x:auto}
</style>
