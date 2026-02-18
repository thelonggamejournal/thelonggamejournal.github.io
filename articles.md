---
layout: page
title: "Articles and Comments"
permalink: /articles/
---

## The Long Game: Case Stdies
This is the fountain of knowledge

<ul>
  {% assign posts = site.posts | where_exp: "p", "p.series == 'ar'" | sort: "lesson" %}
  {% for post in posts %}
    <li><a href="{{ post.url | relative_url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

<p><a href="https://thelonggamejournal.github.io/">← Home</a></p>

