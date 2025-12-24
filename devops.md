---
layout: page
title: DevOps
permalink: /devops/
---

## Latest DevOps posts

{% assign devops_posts = site.tags.devops %}

{% if devops_posts %}
  {% for post in devops_posts %}
- [{{ post.title }}]({{ post.url | relative_url }}) <small>({{ post.date | date: "%d %b %Y" }})</small>
  {% endfor %}
{% else %}
No DevOps posts yet. Add `tags: [devops]` to your posts.
{% endif %}

---
