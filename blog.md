---
layout: splash
title: Blog
---
# Scrillionaires Blog it Up!

{% for post in site.posts %}
  - <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
    {{ post.excerpt }}
{% endfor %}
