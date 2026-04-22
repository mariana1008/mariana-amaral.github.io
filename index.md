---
layout: home
title: Home
---

# Hi, I'm Mariana 👋

Short intro about you. What you do, what you're learning, what you're building.

## 🔗 Links
- GitHub: https://github.com/yourusername
- LinkedIn: https://linkedin.com/in/yourname

## 🚀 Featured Projects
- [Project One](https://github.com/yourusername/project-one) — short description
- [Project Two](https://github.com/yourusername/project-two) — short description

## ✍️ Latest Journal Posts
{% for post in site.posts limit:3 %}
- [{{ post.title }}]({{ post.url }})
{% endfor %}