---
layout: blog
title: Code Troopers
---
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      <div class="excerpt">{{ post.content | extract_excerpt }}</div>
      <p><a href="{{post.url}}">Lire plus »</a></p>
    </li>
  {% endfor %}
</ul>
