---
title: Index
description: List of all pages
---

{% for item in site.info %}
  <h2><a href="{{ item.url }}">{{ item.title }}</a></h2>
  <p>{{ item.description }}</p>
{% endfor %}

