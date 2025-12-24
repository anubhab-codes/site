---
layout: page
title: DevOps
permalink: /devops/
---

## What is DevOps?

DevOps means building and running software as one continuous flow.

Instead of one team writing code and another team struggling to run it, the same group takes responsibility from development to production.

---

## Why do we need DevOps?

Earlier, software delivery involved many manual steps and hand-offs. This caused:
- Delays in releases  
- Errors during deployments  
- Confusion when something broke  

As systems became bigger and updates became frequent, this approach stopped working. DevOps helps reduce this friction.

---

## How is DevOps done?

DevOps is done by simplifying and automating how software is delivered. Teams usually:
- Automate build and deployment steps  
- Test changes early  
- Monitor systems to know what is happening  
- Fix issues quickly and improve the process  

DevOps is not a one-time setup. It improves gradually as teams learn and remove problems.

---

## DevOps posts

{% assign posts = site.categories.devops | sort: "date" | reverse %}

{% for post in posts %}
- [{{ post.title }}]({{ post.url | relative_url }})
{% endfor %}
