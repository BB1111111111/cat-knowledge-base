---
layout: default
title: CAT Knowledge Base
permalink: /
---
# CAT Knowledge Base

Search the published CAT preparation notes. This website is public.

<input id="q" type="search" placeholder="Search concepts, formulas and examples..." style="width:100%;padding:12px;font-size:1rem;margin:1rem 0;">
<div id="results">Loading notes...</div>
<script>
(async function () {
  const root = "/cat-knowledge-base";
  const data = await (await fetch(root + "/search.json")).json();
  const q = document.getElementById("q");
  const out = document.getElementById("results");
  function esc(s) {
    return s.replace(/[&<>"']/g, c => ({"&":"&amp;","<":"&lt;",">":"&gt;",'"':"&quot;","'":"&#39;"}[c]));
  }
  function render() {
    const term = q.value.trim().toLowerCase();
    const hits = data.filter(n => !term || (n.title + " " + n.path + " " + n.text).toLowerCase().includes(term));
    out.innerHTML = hits.length
      ? hits.map(n => `<p><a href="${root}/notes/${encodeURI(n.path.replace(/\.md$/,''))}/"><strong>${esc(n.title)}</strong></a><br><small>${esc(n.path)}</small></p>`).join("")
      : "<p>No matching notes.</p>";
  }
  q.addEventListener("input", render);
  render();
})().catch(() => { document.getElementById("results").textContent = "Search index unavailable."; });
</script>

## Published sections
- Quantitative Aptitude
- VARC
- DILR
- Formula Book
