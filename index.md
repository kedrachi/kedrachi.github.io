---
layout: default
---

# 文章列表

<ul>
  {% for post in site.posts %}
    <li style="list-style: none; margin-bottom: 20px;">
      <span style="color: #666;">{{ post.date | date: "%Y-%m-%d" }}</span> &raquo; 
      <a href="{{ post.url }}" style="color: #111; font-size: 1.2em; text-decoration: none; font-weight: bold;">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
