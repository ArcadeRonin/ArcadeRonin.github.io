---
layout: page
title: The Zine
permalink: /zine/
---

Welcome to the Zine.

{% assign zine_posts = site.categories.zine | sort: "date" | reverse %}

{% if zine_posts and zine_posts.size > 0 %}
<ul>
  {% for post in zine_posts %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      — {{ post.date | date: "%Y-%m-%d" }}
    </li>
  {% endfor %}
</ul>
{% else %}
<p><em>No zine posts yet.</em> (Make sure your post has <code>categories: [zine]</code> in its front matter.)</p>
{% endif %}
