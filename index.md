---
layout: page
title: myliuduomenis.lt
tagline: 
---

{% include JB/setup %}

Įrašų sąrašas

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | localize: "%Y %B %d" }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

