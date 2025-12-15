---
layout: page
title: The Zine
permalink: /zine/
---

Welcome to the Zine.

{% assign zine_posts = site.posts | where_exp: "post", "post.categories contains 'zine'" %}

<ul>
  {% for post in zine_posts %}
    <li><a href="{{ post.url | relative_url }}">{{ post.title }}</a> — {{ post.date | date: "%Y-%m-%d" }}</li>
  {% endfor %}
</ul>
