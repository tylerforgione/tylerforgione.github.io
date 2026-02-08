---
layout: page
title: Projects
subtitle: "Some of my projects."
---

{% for proj in site.data.projects %}
  {% include project_card.html project=proj %}
{% endfor %}