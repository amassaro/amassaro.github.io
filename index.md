---
layout: home
title: Anthony Massaro
tags: [blog, code, csharp, javascript, programming]
image:
  feature: home.jpg
  credit: Anthony Massaro
  creditlink:
---

<div id="home">
  <h1>The Pipe</h1>
  <ul class="posts">
    {% for post in site.posts %}
      {% unless post.draft %}
        <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ post.url }}">{{ post.title }}</a></li>
      {% endunless %}
    {% endfor %}
  </ul>
</div>