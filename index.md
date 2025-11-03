---
layout: default
title:  Home
---

# Welcome

Below are my recent posts:

<ul class="post-list">
  {% for post in site.posts %}
  <li>
    <a href="{{ post.url }}">{{ post.title }}</a> — {{ post.date | date: "%B %e, %Y" }}
  </li>
  {% endfor %}
</ul>
