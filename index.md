---
layout: default
title: SLACKHA
---

<span style="font-family:Avant Garde">SLACKHA</span>
====================================================

Site under development---please check back soon!

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>
