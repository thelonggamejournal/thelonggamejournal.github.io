---
layout: page
title: "Advanced"
permalink: /advanced/
---

## The Long Game: Advanced
This is where investing, trading and speculation resources will reside.

<ul>
  {% assign posts = site.posts | where_exp: "p", "p.series == 'av'" | sort: "lesson" %}
  {% for post in posts %}
    <li><a href="{{ post.url | relative_url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

<p><a href="https://thelonggamejournal.github.io/">← Home</a></p>

