---
layout: page
title: Workshop on Dynamic Neural Networks
subtitle: 2022 International Conference on Machine Learning
use-site-title: true
header-img: "/img/share.png"
share-img: "/img/share.png"
---

<!-- <div class="sharethis-inline-share-buttons"></div>
<meta name="thumbnail" content="./img/logo.png" /> -->

# Overview
Deep networks have shown outstanding scaling properties both in terms of data and model sizes: larger performs better. Unfortunately, the computational cost of current state-of-the-art methods is prohibitive. A number of new techniques have recently arisen to address and improve this fundamental quality-cost trade-off. Methods like conditional computation, adaptive computation, dynamic model sparsification, and early-exit approaches aim to address the above mentioned quality-cost trade off. This workshop explores such exciting and practically-relevant research avenues. As part of contributed content we will invite high-quality papers on the following topics: dynamic routing, mixture-of-experts models, early-exit methods, conditional computations, capsules and object-oriented learning, reusable components, online network growing and pruning, online neural architecture search and applications of dynamic networks (continual learning, wireless/embedded devices and similar topics).

The 1st Dynamic Neural Networks workshop will be a [hybrid workshop at ICML 2022](https://icml.cc/Conferences/2022/Schedule?showEvent=13451) on July 23, 2022. Our goal is to advance the general discussion of the topic by highlighting contributions proposing innovative approaches regarding dynamic neural networks.


**Announcements**
* [Microsoft CMT Submission portal](https://cmt3.research.microsoft.com/DyNN2022/) is now open! 

<!-- * [Link to the **live sessions** at ICML website](https://www.youtube.com). Note that registration to the ICML main conference is required in order to access the website. -->
<!-- * Congratulations to winners of **best paper award**, "Placeholder paper title", by Placeholder Placeholder and Placeholder Placeholder! -->


**Submission Deadline:** May 25, 2022 (Anywhere on Earth) <br>
**Author Notification:** June 13, 2022 <br>
**Video Deadline:** June 28th, 2022 <br>
**Camera Ready Deadline:** July 9, 2022 <br>
**Workshop Day:** July 23, 2022

<hr>

# Speakers
<div class="container" style="margin-top: 20px;margin-bottom: 0px;">
  <div class="row">
  <h2> Keynote Speakers </h2>
  {% for p in site.data.speakers %}
  {% if forloop.index<=2 %}
  {% capture id %}{{ p[0] }}{% endcapture %}
  {% include profile.html p=p %}
  {% endif %}
  {% endfor %}
  </div>
  <h2> Invited Speakers </h2>
  <div class="row">
  {% for p in site.data.speakers %}
  {% capture id %}{{ p[0] }}{% endcapture %}
  {% if forloop.index>2%}
  {% include profile.html p=p %}
  {% endif %}
  {% endfor %}
  </div>
<a href="speakers">More Info</a>
</div>

<hr>

# Organizers
<!-- prettier-ignore -->
<div class="container" style="margin-top: 20px;margin-bottom: 0px;">
  <div class="row">
    {% for p in site.data.organizers %}
    {% capture id %}{{ p[0] }}{% endcapture %}
    {% if forloop.index<=4 %}
    {% include profile.html p=p %}
    {% endif %}
    {% endfor %}
  </div>
  <div class="row">
  {% for p in site.data.organizers %}
  {% capture id %}{{ p[0] }}{% endcapture %}
  {% if forloop.index>4 and forloop.index<=6%}
  {% include profile.html p=p %}
  {% endif %}
  {% endfor %}
  </div>
  <h1> Panel Chairs </h1>
  <div class="row">
  {% for p in site.data.panelchairs %}
  {% capture id %}{{ p[0] }}{% endcapture %}
  {% include profile.html p=p %}
  {% endfor %}
  </div>
</div>
<hr>


# Program Committee
<!-- prettier-ignore -->
<!-- original list class in the template
  <ul class="list-group list-group-flush">
      <li class="list-group-item col-xs-6 col-sm-4 col-md-3">{{ p }}</li> 
<h3>Confirmed:</h3>-->
<div class="container">
  <ul class="mb-3">
    {% for p in site.data.pc.people %}
      <li class="mb-3">{{ p }}</li>
    {% endfor %}
  </ul>
</div>
<hr>

<!-- # Related Venues

<div class="container" style="margin-bottom: 10px;"></div>

- [Automated Knowledge Base Construction (AKBC'20)](http://www.akbc.ws/2020/)
- [Workshop on Semantic Deep Learning (SemDeep'20)](http://www.dfki.de/~declerck/semdeep-6/)
- [Workshop on Deep Learning for Knowledge Graphs (DL4KG'20)](https://alammehwish.github.io/dl4kg_eswc_2020/)
- [Workshop on Semantic Explainability (SEMEX'20)](http://www.semantic-explainability.com/)
- [Workshop on Statistical Relational AI (StarAI'20)](http://www.starai.org/2020/)
- [Workshop on Neural-Symbolic Learning and Reasoning (NeSys'19)](https://sites.google.com/view/nesy2019/home), see more on <http://www.neural-symbolic.org/>

<div class="container" style="margin-bottom: 10px;"></div> -->

<hr>

Contact: [email](mailto:icmldynamicnn@gmail.com)
