---
layout: page
title: News
date: 2018-01-30
permalink: "/news/"
---

{% for post in site.posts %}
<a style="font-size: 30px" class="text-xl-left" href="{{ post.url }}">{{ post.title }}</a>
<p>{{ post.date | date: "%B %d, %Y" }}</p>
{% endfor %}