---
layout: default
---

<div style="text-align: center; padding: 80px 0 100px 0;">
  <h1 style="font-size: 2.2em; font-weight: bold; color: #111; margin-bottom: 20px;">
    “那些疯狂到以为自己能够改变世界的人，才能真正改变世界。”
  </h1>
  <p style="font-size: 1.1em; color: #555; letter-spacing: 2px;">
    苹果“非同凡想”广告，1997
  </p>
</div>

<hr style="border: 0; border-top: 1px solid #ddd; margin: 0 auto 60px auto; width: 50%;">

<h2 style="text-align: center; margin-bottom: 40px; color: #111;">最新日志</h2>

<ul style="list-style: none; padding: 0;">
  {% for post in site.posts %}
    <li style="margin-bottom: 30px; text-align: center;">
      <span style="color: #888; font-family: monospace;">{{ post.date | date: "%Y-%m-%d" }}</span>
      <br>
      <a href="{{ post.url }}" style="font-size: 1.5em; font-weight: bold; color: #111; text-decoration: none;">
        {{ post.title }}
      </a>
    </li>
  {% endfor %}
</ul>
