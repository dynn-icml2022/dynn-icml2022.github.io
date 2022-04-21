---
layout: page
title: Workshop on Dynamic Neural Networks
subtitle: Friday, July 22 - 2022 International Conference on Machine Learning - Baltimore, MD
use-site-title: true
header-img: "https://dynn-icml2022.github.io/img/logo.jpg"
share-img: "https://dynn-icml2022.github.io/img/logo.jpg"
---


# Speakers
<div class="container" style="margin-top: 25px;margin-bottom: 40px;">
  {% for p in site.data.speakers %}
  {% if forloop.index<8 %}
  <div class="row">
    <div class="col-sm">
    {% capture id %}{{ p[0] }}{% endcapture %}
    {% include profile.html p=p %}
    </div>
    <div class="col">
    {% capture id %}{{ p[1] }}{% endcapture %}
    {% include profile_detail.html p=p %}
    </div>
  </div>
  <br>
  {% endif %}
  {% endfor %}
</div>
