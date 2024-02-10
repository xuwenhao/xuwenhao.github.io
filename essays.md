---
layout: default
title: Essays
---

<h1>Latest Posts</h1>

<ul>
{% for post in site.posts %}
  <li>
    <a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
    <p>{{ post.date | date_to_string }} - {{ post.excerpt }}</p>
  </li>
{% endfor %}
</ul>