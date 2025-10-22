---
layout: default
title: Windows Yazıları
---

# 🪟 Windows Yazıları

Burada tüm **Windows** hatalarına ve çözümlerine ait yazılar listelenir:

{% for post in site.categories.windows %}
- [{{ post.title }}]({{ post.url }}) — {{ post.date | date: "%d.%m.%Y" }}
{% endfor %}
