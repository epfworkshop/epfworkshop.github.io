---
layout: single
title: "EPF Workshop"
---

The Exoplanet and Planet Formation Workshop (EPF workshop) is a series of workshop held in the East Asia regions to discuss the exoplanet and planet formation researches. See [Philosophy page]({{ "/philosophy/" | relative_url }}) for the concept of the workshop. The latest information will follow in this page.

# News

{% for post in site.posts limit:5 %}
- **[{{ post.title }}]({{ post.url | relative_url }})**  
  <small>{{ post.date | date: "%Y-%m-%d" }}</small>  
  {{ post.excerpt }}
{% endfor %}
