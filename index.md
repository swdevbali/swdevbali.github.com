---
layout: page
title: Eko S. Wibowo's Coding Blog
tagline: Berbagi pengetahuan koding iOS, Mac, Ruby, .NET dan PHP
---
{% include JB/setup %}

Post yang tersedia : 

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>