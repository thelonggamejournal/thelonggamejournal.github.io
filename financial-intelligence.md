---
layout: page
title: "Financial-Intelligence"
permalink: /foundations/
---

## The Long Game: Financial-Intelligence
Practical financial discipline for stability before wealth.

<ul>
  {% assign posts = site.posts | where_exp: "p", "p.series == 'financial-intelligence'" | sort: "lesson" %}
  {% for post in posts %}
    <li><a href="{{ post.url | relative_url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
