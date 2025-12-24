---
layout: page
title: Authentication
permalink: /identity/iam/
---

## What is IAM?

Identity and Access Management (IAM) is about **who can access what, and under what conditions**.
It ensures the right people and systems get the right access at the right time.

---

## IAM posts

{% if site.categories.iam %}
{% for post in site.categories.iam %}
- [{{ post.title }}]({{ post.url | relative_url }})
{% endfor %}
{% else %}
_No IAM posts yet._
{% endif %}
