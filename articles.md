---
layout: page
title: "Articles and Comments"
permalink: /articles/
---

## The Long Game: Articles
This is where interesting articles will go. <span style="color:rgb(200,0,0);">Still Under Construction</span>

<ul>
  {% assign posts = site.posts | where_exp: "p", "p.series == 'ar'" | sort: "lesson" %}
  {% for post in posts %}
    <li><a href="{{ post.url | relative_url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

<p><a href="https://thelonggamejournal.github.io/">← Home</a></p>

