---
layout: default
title: Projects
permalink: /projects/
---

# 🚀 Projects

Here is a selection of my Data Analytics, Data Engineering, Machine Learning, and Business Process projects.

---

## Project List

{% assign projects = site.projects | where_exp: "p", "p.published != false" | sort: "date" | reverse %}
{% for p in projects %}
- [{{ p.title }}]({{ p.url | relative_url }}) — {{ p.description | default: "" }}
{% endfor %}

---

Stay tuned — more projects will be added regularly!