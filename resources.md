---
layout: page
title: "Resources"
permalink: /resources/
---

## The Long Game: Resources
Tools, Tips and Tricks (Or should I use the Oxford Comma?)
Tools, Tips, and Tricks for the budding investor 

<ul>
  {% assign posts = site.posts | where_exp: "p", "p.series == 'rs'" | sort: "lesson" %}
  {% for post in posts %}
    <li><a href="{{ post.url | relative_url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

<p><a href="https://thelonggamejournal.github.io/">← Home</a></p>

