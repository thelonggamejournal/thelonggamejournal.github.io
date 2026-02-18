---
layout: page
title: "Case Studies "
permalink: /Casestudies/
---

## The Long Game: Case Stdies
Here are some success stories for you - there is hope!

<ul>
  {% assign posts = site.posts | where_exp: "p", "p.series == 'casestudies'" | sort: "lesson" %}
  {% for post in posts %}
    <li><a href="{{ post.url | relative_url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

<p><a href="https://thelonggamejournal.github.io/">← Home</a></p>
