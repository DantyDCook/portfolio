---
layout: default
title: Essays
permalink: /essays/
---

# ✍️ Essays

A collection of my essays on data, technology, and business.

---

{% assign essays = site.essays | sort: "date" | reverse %}
{% for e in essays %}
- [{{ e.title }}]({{ e.url | relative_url }}) — {{ e.description | default: "" }}
{% endfor %}