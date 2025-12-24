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

{% assign posts = site.categories.authn | sort: "date" | reverse %}

{% for post in posts %}
- [{{ post.title }}]({{ post.url | relative_url }})
{% endfor %}
