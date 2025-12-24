---
layout: page
title: IGA
permalink: /identity/iga/
---

## What is IGA?

IGA manages who has access to what, and why.

---

## IGA posts

{% if site.categories.iga %}
{% for post in site.categories.iga %}
- [{{ post.title }}]({{ post.url | relative_url }})
{% endfor %}
{% else %}
_No IGA posts yet._
{% endif %}
