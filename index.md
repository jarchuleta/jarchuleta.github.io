---
layout: default
title: Home
---

# Welcome to My Jekyll Site

This is the home page of my site, built with Jekyll and hosted on GitHub Pages.

## Latest Posts

<ul>
  {% for post in site.posts %}
    <li><a href="{{ post.url }}">{{ post.title }}</a> - {{ post.date | date: "%B %d, %Y" }}</li>
  {% endfor %}
</ul>
