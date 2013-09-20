---
layout: page
title: 追逐理想
tagline: 性格决定命运，气度影响格局
---
{% include JB/setup %}

## 小记

懒散不可怕，可怕的是不够专注和卓越

## 缘起

对当前的我来说，这里本是一个终点，但也可以看做是一个起点，暂时放下你，慢慢的完善你。

本站基于[Jekyll Bootstrap](http://jekyllbootstrap.com),在此表示感谢。

    
## 文章列表22


<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>