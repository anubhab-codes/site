---
layout: page
title: Identity Governance & Administration (IGA)
permalink: /identity/iga/
---

## What is IGA?

Identity Governance and Administration focuses on **who should have access to what, and why**.  
It ensures identities, accounts, and entitlements are properly governed across systems.

---

## Why is IGA needed?

As organizations grow, access sprawl becomes inevitable. Without governance:
- Excess access accumulates
- Compliance becomes manual and risky
- Joiner, mover, and leaver events break

IGA brings control, visibility, and accountability.

---

## How is IGA implemented?

IGA is implemented using lifecycle workflows, access reviews, policies, and integrations with authoritative sources like HR systems and directories.

---

## Posts on IGA

{% assign posts = site.categories.iga | sort: "date" | reverse %}

{% for post in posts %}
- [{{ post.title }}]({{ post.url | relative_url }})
{% endfor %}
