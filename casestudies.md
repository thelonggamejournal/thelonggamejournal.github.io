---
layout: page
title: "Case Studies "
permalink: /casestudies/
---

## The Long Game: Case Stdies
Here are some success stories for you - there is hope! <span style="color:rgb(200,0,0);">Still Under Construction</span>

<ul>
  {% assign posts = site.posts | where_exp: "p", "p.series == 'cs'" | sort: "lesson" %}
  {% for post in posts %}
    <li><a href="{{ post.url | relative_url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

<p><a href="https://thelonggamejournal.github.io/">← Home</a></p>

