---
layout: default
title: Home
---

# Welcome to My Blog 🎉
This is my GitHub Pages blog powered by Jekyll.

## 📝 Latest Posts

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }}) - _{{ post.date | date: "%B %d, %Y" }}_
{% endfor %}

