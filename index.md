---
layout: default
title: Home
---

# RyanS974.github.io

Home Page of <a href="http://github.com/ryans974">RyanS974</a> containing mainly articles on AI, Python, and School, and various blog posts on site updates or other topics.

## Recent Blog Posts

{% for post in site.posts limit:5 %}
- [{{ post.title }}]({{ post.url }}) <small>{{ post.date | date: "%Y-%m-%d" }}</small>
{% endfor %}
