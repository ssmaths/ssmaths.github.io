---
layout: home
title: "Home"
---

# Hi, I'm Your Name
**Elevator pitch:** I build backend systems and developer tools that scale.

## Selected projects
- [Project A](/projects/project-a) — short one-line summary.
- [Project B](/projects/project-b) — short one-line summary.

## Latest posts
{% for post in site.posts limit:5 %}
- [{{ post.title }}]({{ post.url }}) — {{ post.date | date: "%b %-d, %Y" }}
{% endfor %}
