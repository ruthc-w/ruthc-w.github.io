---
layout: page
title: "Blog"
permalink: blog.html
---

![pink yellow calla lilies](images/pink-and-yellow-calla-lilies.jpg "Pink yellow calla lilies")

[Photo](https://www.publicdomainpictures.net/en/view-image.php?image=114983&picture=pink-and-yellow-calla-lilies) by [Linnaea Mallette](http://www.linnaeamallette.com/)

<h1>Latest Posts</h1>

<ul>
  {% for post in site.posts %}
    <li>
      <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>
