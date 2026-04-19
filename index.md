---
layout: default
title: Home
---

# RyanS974.github.io

Home Page of [RyanS974](http://github.com/RyanS974 "My main GitHub repo site") containing mainly articles on AI, Python, and School, and various blog posts on site updates or other topics.

## Recent Blog Posts

{% for post in site.posts limit:5 %}
- [{{ post.title }}]({{ post.url }}) <small>{{ post.date | date: "%Y-%m-%d %H:%M" }}</small>
{% endfor %}
