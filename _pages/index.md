---
title: Index
description: This page :-)
permalink: /pages/index.html
---

{% for item in site.pages %}
  <h2><a href="{{ item.url }}">{{ item.title }}</a></h2>
  <p>{{ item.description }}</p>
{% endfor %}

