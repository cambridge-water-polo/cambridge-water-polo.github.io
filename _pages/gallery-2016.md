---
layout: page
title: 2016 Gallery
date: 2018-03-21
permalink: "/gallery/2016/"
---

<br>

<div class="container">

{% for i in (1..93) %}
{% assign mod = forloop.index | modulo: 3 %}

{% if mod == 0 %}
<div class="col-md-4 mb-4">
<a href="/assets/images/gallery/2016/CWP-2016-{{ i }}.jpg" data-lightbox="2016-set" data-title="caption">
    <img src="/assets/images/gallery/2016/CWP-2016-{{ i }}-thumb.jpg" alt="" style="width: 100%;"/>
</a>
</div>

</div>

{% elsif mod == 1 %}
<div class="row">

<div class="col-md-4 mb-4">
<a href="/assets/images/gallery/2016/CWP-2016-{{ i }}.jpg" data-lightbox="2016-set" data-title="caption">
    <img src="/assets/images/gallery/2016/CWP-2016-{{ i }}-thumb.jpg" alt="" style="width: 100%;"/>
</a>
</div>

{% if forloop.last == true %}
</div>
{% endif %}

{% elsif mod == 2 %}
<div class="col-md-4 mb-4">
<a href="/assets/images/gallery/2016/CWP-2016-{{ i }}.jpg" data-lightbox="2016-set" data-title="caption">
    <img src="/assets/images/gallery/2016/CWP-2016-{{ i }}-thumb.jpg" alt="" style="width: 100%;"/>
</a>
</div>

{% if forloop.last == true %}
</div>
{% endif %}

{% endif %}

{% endfor %}

</div>