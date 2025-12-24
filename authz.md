---
layout: page
title: Authorization
permalink: /identity/authz/
---

## What is Authorization?

Authorization answers the question: what are you allowed to do?

It controls actions and access after identity is verified.

---

## Why do we need Authorization?

Not everyone should have access to everything. Authorization ensures:
- Least privilege  
- Separation of duties  
- Controlled access to sensitive actions  

---

## How is Authorization done?

Authorization is implemented using roles, permissions, and policies enforced by applications and platforms.

---

## Authorization posts

{% assign posts = site.categories.authz %}

{% if posts and posts.size > 0 %}
  {% assign posts = posts | sort: "date" | reverse %}
  {% for post in posts %}
- [{{ post.title }}]({{ post.url | relative_url }})
  {% endfor %}
{% else %}
_No Authorization posts yet._
{% endif %}
