---
layout: page
title: 2015 Gallery
date: 2018-03-21
permalink: "/gallery/2015/"
---

<br>

<div class="container">

{% for i in (1..44) %}
{% assign mod = forloop.index | modulo: 3 %}

{% if mod == 0 %}
<div class="col-md-4 mb-4">
<a href="/assets/images/gallery/2015/CWP-2015-{{ i }}.jpg" data-lightbox="2015-set" data-title="caption">
    <img src="/assets/images/gallery/2015/CWP-2015-{{ i }}-thumb.jpg" alt="" style="width: 100%;"/>
</a>
</div>

</div>

{% elsif mod == 1 %}
<div class="row">

<div class="col-md-4 mb-4">
<a href="/assets/images/gallery/2015/CWP-2015-{{ i }}.jpg" data-lightbox="2015-set" data-title="caption">
    <img src="/assets/images/gallery/2015/CWP-2015-{{ i }}-thumb.jpg" alt="" style="width: 100%;"/>
</a>
</div>

{% if forloop.last == true %}
</div>
{% endif %}

{% elsif mod == 2 %}
<div class="col-md-4 mb-4">
<a href="/assets/images/gallery/2015/CWP-2015-{{ i }}.jpg" data-lightbox="2015-set" data-title="caption">
    <img src="/assets/images/gallery/2015/CWP-2015-{{ i }}-thumb.jpg" alt="" style="width: 100%;"/>
</a>
</div>

{% if forloop.last == true %}
</div>
{% endif %}

{% endif %}

{% endfor %}

</div>