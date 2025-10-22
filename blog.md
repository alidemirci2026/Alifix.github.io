---
layout: default
title: Blog
---

# 🧾 Tüm Yazılar

Aşağıda bilgisayar ve cep telefonu hatalarıyla ilgili tüm çözüm rehberleri listelenir.

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }}) — {{ post.date | date: "%d.%m.%Y" }}
{% endfor %}
