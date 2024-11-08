---
layout: default
title: "Blog"
---

# Blog

Welcome to my blog! Here are some of the things I've been working on and learning.

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> - <small>{{ post.date | date: "%B %d, %Y" }}</small>
      <p>{{ post.excerpt }}</p>
    </li>
  {% endfor %}
</ul>