---
layout: post     # <-- wrap the index in a window too (optional)
title:  Home
---

# Welcome to the Script Editor Blog

Below are my recent posts:

<ul class="post-list">
  {% for post in site.posts %}
  <li>
    <a href="{{ post.url | relative_url }}">{{ post.title }}</a> — {{ post.date | date: "%B %-d, %Y" }}
  </li>
  {% endfor %}
</ul>
