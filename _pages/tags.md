---
layout: default
title: Tags
permalink: /tags/
---

# 🏷️ Tags

Here are tags for my projects and posts — click to explore related work:

<ul>
{% assign sorted_tags = site.tags | sort %}
{% for tag in sorted_tags %}
  <li>
    <a href="#{{ tag[0] | slugify }}">{{ tag[0] }} ({{ tag[1].size }})</a>
  </li>
{% endfor %}
</ul>

---

## Tag Index

{% for tag in sorted_tags %}
### <a name="{{ tag[0] | slugify }}"></a> {{ tag[0] }}

{% for post in tag[1] %}
- [{{ post.title }}]({{ post.url }})
{% endfor %}

---
{% endfor %}