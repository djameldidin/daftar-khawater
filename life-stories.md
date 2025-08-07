---
layout: archive
title: "قصص من الحياة"
permalink: /life-stories/
comments: true
---

<div class="entries-{{ page.entries_layout | default: 'list' }}">
  {% for post in site.life_stories %}
    {% include archive-single.html type=page.entries_layout %}
  {% endfor %}
</div>

{% if page.comments %}
  {% include comments.html %}
{% endif %}
