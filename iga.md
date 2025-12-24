---
layout: page
title: Identity Governance & Administration (IGA)
permalink: /identity/iga/
---

## What is IGA?

Identity Governance and Administration focuses on managing who has access to what, and why.

It ensures access is given correctly, reviewed regularly, and removed when no longer needed.

---

## Why do we need IGA?

As organizations grow, access becomes messy. Without governance:
- People keep access they no longer need  
- Compliance becomes manual and risky  
- Joiner, mover, and leaver processes break  

IGA brings structure and visibility.

---

## How is IGA done?

IGA is implemented using identity lifecycles, access reviews, and policies connected to HR systems and directories.

---

## IGA posts

{% assign posts = site.categories.iga %}

{% if posts and posts.size > 0 %}
  {% assign posts = posts | sort: "date" | reverse %}
  {% for post in posts %}
- [{{ post.title }}]({{ post.url | relative_url }})
  {% endfor %}
{% else %}
_No IGA posts yet._
{% endif %}
