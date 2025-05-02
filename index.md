---
layout: default
title: "Kyona's Poetry Archive"
---

Welcome to my mythic little corner of the web.  
Explore my poems and themes of memory, gender, transformation, and self-invention.

<ul>
  {% for post in site.posts %}
    <li><a href="{{ post.url }}">{{ post.title }}</a> — <em>{{ post.date | date: "%B %d, %Y" }}</em></li>
  {% endfor %}
</ul>