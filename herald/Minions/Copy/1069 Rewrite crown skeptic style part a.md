# Copy: Rewrite crown skeptic style part a root variables and base

Date: 2026-10-30
Task: Rewrite Crown skeptic style part A: :root variables and base reset only, under 700 characters, ending with the closing style tag.
For [[Herald]].

<style>
:root{--bg:#07070c;--ink:#e9e7f2;--accent:#ff2d8f;--muted:#9a97ab;--wrap:1060px}
*,*::before,*::after{box-sizing:border-box}
html,body{margin:0;padding:0}
body{background:var(--bg);color:var(--ink);font-family:system-ui,-apple-system,"Segoe UI",Roboto,sans-serif;line-height:1.6;-webkit-font-smoothing:antialiased}
img,svg{max-width:100%;height:auto}
a{color:var(--accent)}
h1{font-size:clamp(2rem,5vw,3.2rem);line-height:1.1;margin:0 0 .5em}
h2{font-size:clamp(1.4rem,3.2vw,2rem);line-height:1.2;margin:1.4em 0 .5em}
p{color:var(--muted)}
</style>
