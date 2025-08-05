---
layout: archive
title: "دفتر الخواطر"
---

<div class="entries-{{ page.entries_layout | default: 'list' }}">
  {% for post in site.thoughts %}
    {% include archive-single.html type=page.entries_layout %}
  {% endfor %}
</div>