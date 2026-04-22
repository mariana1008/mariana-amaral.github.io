---
layout: page
title: Journal
---

Here are my notes, thoughts, and progress logs.

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> — {{ post.date | date: "%b %d, %Y" }}
    </li>
  {% endfor %}
</ul>