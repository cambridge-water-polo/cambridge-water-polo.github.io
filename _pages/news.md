---
layout: page
title: News
date: 2018-01-30 01:05:01 -0600
permalink: "/news/"
---


{% for post in site.posts %}
<a style="font-size: 30px" class="text-xl-left" href="{{ post.url }}">{{ post.title }}</a>
{% endfor %}