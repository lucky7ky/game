---
layout: page
title: エターナルリターン
permalink: /eternal-return/
---

<ul>
{% for post in site.categories["eternal-return"] %}
  <li><a href="{{ post.url | relative_url }}">{{ post.title }}</a>（{{ post.date | date: "%Y/%m/%d" }}）</li>
{% endfor %}
</ul>
