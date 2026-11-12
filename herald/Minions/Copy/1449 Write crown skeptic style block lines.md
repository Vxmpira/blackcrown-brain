# Copy: Write crown skeptic style block lines 1 to 20 only

Date: 2026-11-12
Task: Write Crown skeptic style block lines 1 to 20 only, no closing tag, no script
For [[Herald]].

<style>
:root{--accent:#ff2d8f;--bg:#07070b;--ink:#e9e9f1;--muted:#9a9ab0}
*{box-sizing:border-box}
html,body{margin:0;padding:0;background:var(--bg);color:var(--ink)}
body{font-family:system-ui,-apple-system,"Segoe UI",Roboto,sans-serif;line-height:1.6;min-height:100vh;position:relative;overflow-x:hidden}
body::before{content:"";position:fixed;inset:0;z-index:-2;pointer-events:none;background:radial-gradient(900px 520px at 12% -10%,rgba(255,45,143,.22),transparent 60%),radial-gradient(700px 480px at 92% 8%,rgba(255,45,143,.12),transparent 62%)}
body::after{content:"";position:fixed;inset:0;z-index:-1;pointer-events:none;background-image:radial-gradient(ellipse at center,transparent 55%,rgba(0,0,0,.6) 100%),linear-gradient(rgba(255,255,255,.015) 1px,transparent 1px),linear-gradient(90deg,rgba(255,255,255,.015) 1px,transparent 1px);background-size:100% 100%,56px 56px,56px 56px;background-position:0 0,-1px -1px,-1px -1px}
.wrap{max-width:1060px;margin:0 auto;padding:0 20px}
h1,h2{font-weight:700;line-height:1.15;letter-spacing:-.01em;margin:0 0 .6em}
h1{font-size:clamp(2rem,5vw,3.4rem)}
h2{font-size:clamp(1.4rem,3vw,2rem)}
.lede,.prose{max-width:68ch;color:var(--ink)}
.muted{color:var(--muted)}
.accent{color:var(--accent)}
.crown-head{display:flex;align-items:center;gap:12px;padding:28px 0 8px}
.crown-head svg{width:44px;height:44px;flex:0 0 auto}
.tablewrap{width:100%;overflow-x:auto;margin:24px 0;border:1px solid rgba(255,255,255,.08);border-radius:12px}
table{width:100%;border-collapse:collapse;min-width:520px}
th,td{padding:12px 14px;text-align:left;border-bottom:1px solid rgba(255,255,255,.06)}
th{color:var(--muted);font-weight:600;font-size:.85rem;text-transform:uppercase;letter-spacing:.06em}
