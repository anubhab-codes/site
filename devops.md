---
layout: page
title: DevOps
permalink: /devops/
---

## What is DevOps?

DevOps means building and running software as one continuous flow.

The same team takes responsibility from development to production.

---

## Why do we need DevOps?

Manual hand-offs and separate teams caused:
- Slow releases  
- Deployment errors  
- Confusion during failures  

DevOps reduces friction and improves reliability.

---

## How is DevOps done?

DevOps is done by simplifying and automating delivery:
- Automating builds and deployments  
- Testing early  
- Monitoring systems  
- Improving continuously  

---

## DevOps posts

{% assign posts = site.categories.devops %}

{% if posts and posts.size > 0 %}
  {% assign posts = posts | sort: "date" | reverse %}
  {% for post in posts %}
- [{{ post.title }}]({{ post.url | relative_url }})
  {% endfor %}
{% else %}
_No DevOps posts yet._
{% endif %}
