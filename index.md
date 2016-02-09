---
layout: default
title: SLACKHA
---

# Welcome to SLACKHA!

Site under development---please check back soon!

# Updates

{% for post in site.posts %}
## <a href="{{ post.url }}">{{ post.title }}</a>
  {{ post.excerpt }}
{% endfor %}
