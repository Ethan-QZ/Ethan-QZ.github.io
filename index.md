---
layout: home
title: "我的AI转型之旅"
nav_order: 1
---

# 欢迎来到我的AI转型之旅

这里是记录我从传统程序员向AI工程师转型的历程。

## 最新文章

<ul>
{% for post in site.posts limit: 5 %}
  <li>
    <h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
    <p>{{ post.excerpt }}</p>
  </li>
{% endfor %}
</ul>
