# Copy: Rewrite the full style element closing style as the last

Date: 2026-10-29
Task: Rewrite the full style element, closing </style> as the last characters.
For [[Herald]].

<style>
body{margin:0;background:#07070b;color:#e8e8f0;font:16px system-ui}
body::before{content:"";position:fixed;inset:0;z-index:-1;background:radial-gradient(at 85% 0,#ff2d8f33,transparent 40%),radial-gradient(at 0 100%,#ff2d8f1a,transparent 45%),linear-gradient(#ffffff04 1px,transparent 1px) 0 0/56px 56px,linear-gradient(90deg,#ffffff04 1px,transparent 1px) 0 0/56px 56px}
.wrap{max-width:1060px;margin:auto;padding:0 20px}
h1{font-size:clamp(28px,5vw,56px)}
.wrap>*{display:flex;flex-direction:column;align-items:start;gap:12px}
.chip{padding:8px 14px;border:1px solid #ff2d8f}
.grid{display:grid;grid-template-columns:repeat(3,1fr);gap:16px}
@media(max-width:700px){.grid{grid-template-columns:1fr}}
</style>
