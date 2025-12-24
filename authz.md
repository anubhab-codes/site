---
layout: page
title: Authorization
permalink: /identity/authz/
---

## What is Authorization?

Authorization defines what you are allowed to do.

---

## Authorization posts

{% if site.categories.authz %}
{% for post in site.categories.authz %}
- [{{ post.title }}]({{ post.url | relative_url }})
{% endfor %}
{% else %}
_No Authorization posts yet._
{% endif %}
