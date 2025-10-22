---
layout: default
title: All Posts
---

# 🧾 All Posts

Here is the complete list of all published posts:

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }}) — {{ post.date | date: "%d.%m.%Y" }}
{% endfor %}
