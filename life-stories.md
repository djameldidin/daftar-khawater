---
layout: archive
title: "قصص من الحياة"
permalink: /life-stories/
---

<div class="entries-{{ page.entries_layout | default: 'list' }}">
  {% for post in site.life_stories %}
    {% include archive-single.html type=page.entries_layout %}
  {% endfor %}
</div>