---
layout: default
title: Telefon Hataları
---

# 📱 Telefon Hataları

{% for post in site.categories.phone %}
- [{{ post.title }}]({{ post.url }}) — {{ post.date | date: "%d.%m.%Y" }}
{% endfor %}
