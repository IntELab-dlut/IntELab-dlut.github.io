---
layout: page
title: RESEARCH-PROJECTS
description: 没有链接的博客是孤独的
keywords: 友情链接
comments: true
menu: 链接
permalink: /links/
---

> DLUT SHU LAB PROJECTS

<ul>
{% for link in site.data.links %}
  {% if link.src == 'life' %}
  <li><a href="{{ link.url }}" target="_blank">{{ link.name}}</a></li>
  {% endif %}
{% endfor %}
</ul>

> 相关链接

<ul>
{% for link in site.data.links %}
  {% if link.src == 'www' %}
  <li><a href="{{ link.url }}" target="_blank">{{ link.name}}</a></li>
  {% endif %}
{% endfor %}
</ul>