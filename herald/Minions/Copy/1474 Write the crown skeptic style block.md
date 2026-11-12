# Copy: Write the crown skeptic style block as css only under

Date: 2026-11-12
Task: Write the Crown skeptic style block as CSS only, under 40 lines, under 700 characters, no script
For [[Herald]].

.skeptic{max-width:1060px;margin:0 auto;padding:clamp(20px,4vw,44px);background:radial-gradient(circle at 10% 0,rgba(255,45,143,.12),transparent 42%),#0c0c12;border:1px solid #24242e}
.skeptic h2{font-size:clamp(1.4rem,3vw,2rem);color:#f4f4f7}
.skeptic p{max-width:68ch;color:#b8b8c4;line-height:1.6}
.skeptic .chips{display:flex;flex-wrap:wrap;gap:8px}
.skeptic .chip{border:1px solid #ff2d8f;color:#ff2d8f;padding:4px 10px;border-radius:99px;font-size:.85rem}
.skeptic .tablewrap{overflow-x:auto}
.skeptic .grid{display:grid;grid-template-columns:1fr 1fr;gap:16px}
@media(max-width:700px){.skeptic .grid{grid-template-columns:1fr}}
