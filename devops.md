---
layout: page
title: DevOps
permalink: /devops/
---

## What is DevOps?

DevOps means building and running software as one continuous flow. The same team takes responsibility from development to production.
---

## Learning Path

- **Prerequisites**
  - **Linux**
    {% assign posts = site.posts | where_exp: "p", "p.categories contains 'devops'" | where: "topic", "linux" %}
    {% if posts %}
      {% for post in posts %}
    - [{{ post.title }}]({{ post.url | relative_url }})
      {% endfor %}
    {% else %}
    - _No posts yet._
    {% endif %}

  - **Networking**
    {% assign posts = site.posts | where_exp: "p", "p.categories contains 'devops'" | where: "topic", "networking" %}
    {% if posts %}
      {% for post in posts %}
    - [{{ post.title }}]({{ post.url | relative_url }})
      {% endfor %}
    {% else %}
    - _No posts yet._
    {% endif %}
