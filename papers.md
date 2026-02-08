---
layout: page
title: Papers
subtitle: "You can read my papers in PDF format on this site!"
---

{% for paper in site.data.papers %}
  {% include paper_entry.html paper=paper %}
{% endfor %}

<!-- <div class="card" style="margin-top:14px;">
  <h3>Notes</h3>
  <p class="muted">
    Place PDFs in <span class="tag">assets/pdfs/</span> and update paths in
    <span class="tag">_data/papers.yml</span>.
  </p>
</div> -->