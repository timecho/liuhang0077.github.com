---
layout: page
title: Hang
header: Hang
---

这是 Hang 的个人网站的最新版本，使用  [Jekyll](https://github.com/mojombo/jekyll)  搭建。

事实证明每次快过年的时候就闹心！~~
嗯，，这个不该是介绍页面么。。 妈的！



---
###最近发布的文章
<ul>
  {% assign pages_list = site.pages %}
  {% assign group = 'project' %}
  {% include helpers/pages_list.html %}
</ul>