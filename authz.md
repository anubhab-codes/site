---
layout: page
title: Authorization
permalink: /identity/authz/
---

## What is Authorization?

Authorization answers the question: **What are you allowed to do?**  
It determines access after identity has been verified.

---

## Why is Authorization needed?

Even authenticated users should not have unrestricted access. Authorization ensures:
- Least privilege
- Separation of duties
- Controlled access to sensitive actions

---

## How is Authorization implemented?

Authorization is implemented using roles, policies, permissions, scopes, and access decisions enforced by applications and platforms.

---

## Posts on Authorization

{% assign posts = site.categories.authz | sort: "date" | reverse %}

{% for post in posts %}
- [{{ post.title }}]({{ post.url | relative_url }})
{% endfor %}
