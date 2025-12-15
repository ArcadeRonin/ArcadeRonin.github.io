---
title: Zine
permalink: /zine/
---

{% for post in site.posts %}
- **[{{ post.title }}]({{ post.url }})** — {{ post.date | date: "%Y-%m-%d" }}
  {% if post.excerpt %}{{ post.excerpt | strip_html | strip }}{% endif %}
{% endfor %}
