---
title: Index
description: List of all pages
lang: ru
---

{% for item in site.info %}
  <h2><a href="{{ item.url }}">{{ item.title }}</a></h2>
  <p>{{ item.description }}</p>
{% endfor %}

