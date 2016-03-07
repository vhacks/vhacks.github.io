---
layout: page2
title: Sample Articles
excerpt: "An archive of articles sorted by date."
search_omit: true
---

<ul class="try">
{% for post in site.categories.PowerCLI %}
  <li><article><a href="{{ site.url }}{{ post.url }}">{{ post.title }}</a></article></li>
{% endfor %}
</ul>