---
layout: page
title: Posts
description: This is the page description.
background: '/PATH_TO_IMAGE'
---

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
