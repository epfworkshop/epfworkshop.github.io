---
layout: single
title: "EPF Workshop"
---

# EPF Workshop
Exoplanet and Planet Formation Workshop

- [Philosophy](/philosophy/)
- [History](/history/)

# News

{% for post in site.posts limit:5 %}
- **[{{ post.title }}]({{ post.url | relative_url }})**  
  <small>{{ post.date | date: "%Y-%m-%d" }}</small>  
  {{ post.excerpt }}
{% endfor %}
