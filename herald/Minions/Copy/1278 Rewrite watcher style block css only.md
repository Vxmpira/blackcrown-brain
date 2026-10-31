# Copy: Rewrite watcher style block css only under 40 lines no

Date: 2026-10-31
Task: Rewrite Watcher style block: CSS only, under 40 lines, no script, ends with closing style tag.
For [[Herald]].

<style>
html{background:#07070b}
body{background:#07070b;color:#eceaf2;margin:0}
body::before{
  content:"";
  position:fixed;
  inset:0;
  z-index:-2;
  pointer-events:none;
  background:
    radial-gradient(ellipse 60% 50% at 0% 0%, rgba(255,45,143,.14), transparent 60%),
    radial-gradient(ellipse 55% 45% at 100% 0%, rgba(232,195,90,.10), transparent 60%),
    radial-gradient(ellipse 60% 50% at 50% 100%, rgba(255,45,143,.10), transparent 60%),
    linear-gradient(rgba(255,255,255,.015) 1px, transparent 1px) 0 0/56px 56px,
    linear-gradient(90deg, rgba(255,255,255,.015) 1px, transparent 1px) 0 0/56px 56px,
    radial-gradient(ellipse at center, transparent 55%, rgba(0,0,0,.55) 100%);
}
</style>
