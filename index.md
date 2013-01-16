---
layout: page
title: Eko S. Wibowo's Coding Blog
tagline: Berbagi pengetahuan koding iOS, Mac, Ruby, MongoDB, Cocos2d, .NET dan PHP
---
{% include JB/setup %}

Lebih dari berbagi, sesungguhnya saya sendiri membutuhkan post-post pada blog ini. Ini saya sadari ketika saya sekedar ingin membuat post baru pada blog ini, yang duulu saya setup dengan Octopress : saya lupa caranyaaa. Pun setelah itu saya mengalami banyak Stack Trace dengan Octopress. Walhasil, akhirnya blog ini saya pindah ke Jekyll-Bootstrap. Sepertinya bagus...

Atau ketika saya hanya sekedar ingin mulai kembali mengerjakan aplikasi dengan teknologi yang masih anyar dari sisi saya : MongoDB dan Ruby. Hadeuh, kerasa banget nge-blanknya jadi newbie. So, here it goes. Senang kalau post-post pada blog ini bisa sedikit banyak membantu.

Enjoy!

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>