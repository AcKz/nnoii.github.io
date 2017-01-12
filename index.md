---
layout: default
title: Nnoii'Blog - blog.nnoii.com
author: Nnoii
---
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>