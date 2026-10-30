# Copy: Write the watcher style block only opening style tag through

Date: 2026-10-30
Task: Write the Watcher style block only, opening style tag through closing style tag, 40 lines or fewer.
For [[Herald]].

<style>
:root{--bg:#07060b;--tx:#ece9f4;--mut:#9c97ab;--pink:#ff2d8f;--vio:#7b5cff}
*{box-sizing:border-box}
html,body{margin:0;padding:0}
body{background-color:var(--bg);color:var(--tx);font-family:system-ui,-apple-system,"Segoe UI",Roboto,sans-serif;line-height:1.6;min-height:100vh;position:relative;overflow-x:hidden}
body::before{content:"";position:fixed;inset:0;z-index:-2;pointer-events:none;background:radial-gradient(860px 520px at 12% -6%,rgba(255,45,143,.16),transparent 62%),radial-gradient(760px 480px at 92% 8%,rgba(123,92,255,.17),transparent 60%),radial-gradient(640px 420px at 50% 112%,rgba(123,92,255,.10),transparent 65%)}
body::after{content:"";position:fixed;inset:0;z-index:-1;pointer-events:none;background-image:linear-gradient(rgba(255,255,255,.015) 1px,transparent 1px),linear-gradient(90deg,rgba(255,255,255,.015) 1px,transparent 1px);background-size:56px 56px;-webkit-mask-image:radial-gradient(ellipse at center,#000 40%,transparent 92%);mask-image:radial-gradient(ellipse at center,#000 40%,transparent 92%);box-shadow:inset 0 0 180px 40px rgba(0,0,0,.72)}
.wx-top{max-width:1060px;margin:0 auto;padding:28px clamp(18px,4vw,40px) 8px;display:flex;align-items:center;gap:14px}
.wx-top svg{width:34px;height:34px;flex:0 0 auto}
.wx-name{font-size:clamp(15px,2vw,17px);font-weight:700;letter-spacing:.14em;text-transform:uppercase;color:var(--tx)}
.wx-name span{color:var(--pink)}
.wx-hero{max-width:1060px;margin:0 auto;padding:clamp(28px,6vw,72px) clamp(18px,4vw,40px) 24px}
.wx-hero h1{font-size:clamp(30px,5.4vw,58px);line-height:1.08;margin:0 0 18px;font-weight:800;letter-spacing:-.02em}
.wx-hero h1 em{font-style:normal;background:linear-gradient(90deg,var(--pink),var(--vio));-webkit-background-clip:text;background-clip:text;color:transparent}
.wx-hero p{max-width:75ch;color:var(--mut);font-size:clamp(16px,1.6vw,18px);margin:0}
.wx-chips{max-width:1060px;margin:0 auto;padding:6px clamp(18px,4vw,40px) 40px;display:grid;grid-template-columns:repeat(4,1fr);gap:12px}
.wx-chips div{border:1px solid rgba(123,92,255,.35);background:rgba(20,17,31,.6);border-radius:12px;padding:14px 16px;font-size:14px;color:var(--tx)}
.wx-chips div b{display:block;color:var(--pink);font-size:12px;letter-spacing:.1em;text-transform:uppercase;margin-bottom:4px}
@media (max-width:700px){.wx-chips{grid-template-columns:1fr 1fr}.wx-top{padding-top:20px}}
@media (max-width:420px){.wx-chips{grid-template-columns:1fr}}
</style>
