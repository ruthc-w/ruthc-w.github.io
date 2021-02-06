---
layout: page
title: "Blog"
permalink: /docs/blog.html/
---

![pink yellow calla lilies](/docs/images/pink-and-yellow-calla-lilies.jpg "Pink yellow calla lilies")

<h1>Latest Posts</h1>

<ul>
  {% for post in site.posts %}
    <li>
      <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>
