---
layout: page
title: VALORANT
permalink: /valorant/
---

<ul>
{% for post in site.categories["valorant"] %}
  <li><a href="{{ post.url | relative_url }}">{{ post.title }}</a>（{{ post.date | date: "%Y/%m/%d" }}）</li>
{% endfor %}
</ul>
