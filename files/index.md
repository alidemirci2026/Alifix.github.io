---
layout: default
title: Downloadable Fix Files
---

# 💾 Downloadable Fix Files

Below is the list of uploaded **tools and repair utilities**.  
All files are shared in **ZIP** format.

{% assign files = site.static_files | where_exp: "f", "f.path contains '/files/'" %}
{% if files.size > 0 %}
{% for f in files %}
- [{{ f.name }}]({{ f.path }})
{% endfor %}
{% else %}
No files yet. You can upload your first file via **Add file → Upload files → files/**.
{% endif %}
