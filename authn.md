---
layout: page
title: Authentication
permalink: /identity/authn/
---

## What is Authentication?

Authentication answers one simple question: who are you?

---

## Authentication posts

{% if site.categories.authn %}
{% for post in site.categories.authn %}
- [{{ post.title }}]({{ post.url | relative_url }})
{% endfor %}
{% else %}
_No Authentication posts yet._
{% endif %}
