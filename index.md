---
layout: default
title: Home
---

Welcome! I’m a math PhD student at UC Santa Barbara.  
I work on problems in **optimal transport** and **gradient flows**.

[About Me](/about/) • [Seminar Schedule](/seminar/) • [Blog](/blog/)

<h2>Latest Posts</h2>
<ul>
  {% for post in site.posts %}
    <li><a href="{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
