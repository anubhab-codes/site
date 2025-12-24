---
layout: page
title: Authentication
permalink: /identity/authn/
---

## What is Authentication?

Authentication answers a simple question: **Who are you?**  
It verifies the identity of a user or system before access is granted.

---

## Why is Authentication important?

Passwords alone are no longer sufficient. Modern systems require:
- Stronger verification
- Protection against credential theft
- Secure access for humans and machines

Authentication is the first security gate.

---

## How is Authentication implemented?

Authentication is implemented using mechanisms like passwords, MFA, certificates, tokens, and federated identity providers.

---

## Posts on Authentication

{% assign posts = site.categories.authn %}

{% if posts and posts.size > 0 %}
  {% assign posts = posts | sort: "date" | reverse %}
  {% for post in posts %}
- [{{ post.title }}]({{ post.url | relative_url }})
  {% endfor %}
{% else %}
_No posts yet. Add a post under `_posts/identity/authn/` (or set `categories: [identity, authn]`)._
{% endif %}

