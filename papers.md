---
layout: page
title: Workshop on Dynamic Neural Networks
subtitle: Friday, July 22 - 2022 International Conference on Machine Learning - Baltimore, MD
use-site-title: true
header-img: "https://dynn-icml2022.github.io/img/logo.jpg"
share-img: "https://dynn-icml2022.github.io/img/logo.jpg"
---

# Accepted Papers (Oral Presentation)

<div class="container">
  <ol>
    {% for p in site.data.spotlight %}
        <li id="{{ p[0] }}">
            <b>{{ p[1].title }}</b>
            <br>
            <i>{{ p[1].authors }}</i>
            <!-- {% if p[1].alt_url == "" %}
              (<a href="{{ site.baseurl }}/papers/DynNN_{{ p[0] }}.pdf">PDF</a>)
            {% elsif p[1].alt_url == "NONE" %}
              (PDF not available)
            {% else %}
              (<a href="{{ p[1].alt_url }}">PDF</a>)
            {% endif %} -->
        </li>
    {% endfor %}

<br>  
  </ol>
</div>

<hr>

# Accepted Papers (Poster Presentation)

<div class="container">
  <ol>
    {% for p in site.data.papers %}
        <li id="{{ p[0] }}">
            <b>{{ p[1].title }}</b>
            <br>
            <i>{{ p[1].authors }}</i>
            <!-- {% if p[1].alt_url == "" %}
              (<a href="{{ site.baseurl }}/papers/DynNN_{{ p[0] }}.pdf">PDF</a>)
            {% elsif p[1].alt_url == "NONE" %}
              (PDF not available)
            {% else %}
              (<a href="{{ p[1].alt_url }}">PDF</a>)
            {% endif %} -->
        </li>
    {% endfor %}

<br>  
  </ol>
</div>
