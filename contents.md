---
layout: page
title: "Contents"
permalink: /contents/
---

# Contents
A curated list of posts and topics.

## Blog posts
{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }}) — {{ post.excerpt | strip_html | truncate: 120 }}
{% endfor %}
