---
layout: default
title: İndirilebilir Fix Dosyaları
---

# 💾 İndirilebilir Fix Dosyaları

Aşağıda yüklediğim araçların listesi yer alır. Dosyalar **ZIP** içinde paylaşılır.

{% assign files = site.static_files | where_exp: "f", "f.path contains '/files/'" %}
{% if files.size > 0 %}
{% for f in files %}
- [{{ f.name }}]({{ f.path }})
{% endfor %}
{% else %}
Henüz dosya yok. İlk dosyanı **Add file → Upload files** ile `files/` içine yükle.
{% endif %}
