---
layout: default
title: Home
---

# RyanS974.github.io

Home Page

## Recent Blog Posts

{% for post in site.posts limit:5 %}
- [{{ post.title }}]({{ post.url }}) <small>{{ post.date | date: "%Y-%m-%d" }}</small>
{% endfor %}
