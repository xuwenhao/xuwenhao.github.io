---
layout: default
title: Essays
---

<h1>Latest Posts</h1>

<ul>
  {% for post in site.posts reversed %}
    <li>
      <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
      <p>{{ post.excerpt }}</p>
    </li>
  {% endfor %}
</ul>