---
layout: page
title: Shibuya.lisp
---

{% for post in site.posts limit:10 %}
<!-- here add you post markup -->
<h2><span class="date" style="float: right; font-size: medium;">{{post.date | date: '%Y年%m月%d日'}}</span><a href="{{ post.url }}">{{ post.title }}</a></h2>
<div class="content">
    {{ post.content }}
</div>
{% endfor %}
