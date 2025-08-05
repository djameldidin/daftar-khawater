---
layout: archive
title: "مقالات ورؤى"
---

<div class="entries-{{ page.entries_layout | default: 'list' }}">
  {% for post in site.articles %}
    {% include archive-single.html type=page.entries_layout %}
  {% endfor %}
</div>