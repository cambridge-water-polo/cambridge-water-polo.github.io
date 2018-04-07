---
layout: page
title: 2017 Gallery
date: 2018-03-21
permalink: "/gallery/2017/"
---

<br>

<div class="container">

{% for i in (1..29) %}
{% assign mod = forloop.index | modulo: 3 %}

{% if mod == 0 %}
<div class="col-md-4 mb-4">
<a href="/assets/images/2017/CWP-2017-{{ i }}.jpg" data-lightbox="2017-set" data-title="caption">
    <img src="/assets/images/2017/CWP-2017-{{ i }}-thumb.jpg" alt="" style="width: 100%;"/>
</a>
</div>

</div>

{% elsif mod == 1 %}
<div class="row">

<div class="col-md-4 mb-4">
<a href="/assets/images/2017/CWP-2017-{{ i }}.jpg" data-lightbox="2017-set" data-title="caption">
    <img src="/assets/images/2017/CWP-2017-{{ i }}-thumb.jpg" alt="" style="width: 100%;"/>
</a>
</div>

{% if forloop.last == true %}
</div>
{% endif %}

{% elsif mod == 2 %}
<div class="col-md-4 mb-4">
<a href="/assets/images/2017/CWP-2017-{{ i }}.jpg" data-lightbox="2017-set" data-title="caption">
    <img src="/assets/images/2017/CWP-2017-{{ i }}-thumb.jpg" alt="" style="width: 100%;"/>
</a>
</div>

{% if forloop.last == true %}
</div>
{% endif %}

{% endif %}

{% endfor %}

</div>