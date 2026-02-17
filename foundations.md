---
layout: page
title: "Foundations"
permalink: /foundations/
---

## The Long Game: Foundations

Practical financial discipline for stability before wealth.

<ul>
  {% assign posts = site.posts | where_exp: "p", "p.series == 'foundations'" | sort: "lesson" %}
  {% for post in posts %}
    <li><a href="{{ post.url | relative_url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
