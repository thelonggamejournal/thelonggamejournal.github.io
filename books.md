---
layout: page
title: "Book Reviews"
permalink: /books/
---

## The Long Game: Book Reviews
I am currently doing the book a week promise. This is the list of books I have read with annotaions for non fiction
<ul>
  {% assign posts = site.posts | where_exp: "p", "p.series == 'bk'" | sort: "lesson" %}
  {% for post in posts %}
    <li><a href="{{ post.url | relative_url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

<p><a href="https://thelonggamejournal.github.io/">← Home</a></p>

