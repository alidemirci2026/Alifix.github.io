---
layout: default
title: Phone Posts
---

# 📱 Phone Posts

Here are all posts about **Android and iOS issues**:

{% for post in site.categories.phone %}
- [{{ post.title }}]({{ post.url }}) — {{ post.date | date: "%d.%m.%Y" }}
{% endfor %}
