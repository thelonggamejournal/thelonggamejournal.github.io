---
layout: page
title: "About"
permalink: /articles/
---

## The Long Game: About
Information about your illustrious author
Contact info
Legal credits, discloures and such

<ul>
  {% assign posts = site.posts | where_exp: "p", "p.series == 'ab'" | sort: "lesson" %}
  {% for post in posts %}
    <li><a href="{{ post.url | relative_url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

<p><a href="https://thelonggamejournal.github.io/">← Home</a></p>

