---
layout: archive
title: "Recent Projects"
modified:
excerpt: "The heart of data darkness
tags: []
image:
  feature:
  teaser:
---

<div class="tiles">
{% for post in site.categories.notebooks %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->
