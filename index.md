---
layout: page
title: Synthetic Data Generation 
subtitle: Quality, Privacy, Bias
use-site-title: true
---
<!--<div class="sharethis-inline-share-buttons"></div>
<meta name="thumbnail" content="./img/neurips-logo-new.jpg" /> -->

# Overview

Despite the substantial benefits from using synthetic data, the process of synthetic data generation is still an ongoing technical challenge. Although the two scenarios of limited data and privacy concerns share similar technical challenges such as quality and fairness, they are often studied separately.
This workshop aims at the intersection of these challenges of synthetic data generation, and hopes to shine a light on the solutions that address these challenges. The 1st Synthetic Data Generation workshop will be a [virtual workshop at ICLR 2021](https://iclr.cc/virtual/2021/workshop/2125), May 7, 2021. Our goal is to advance the general discussion of the topic by highlighting contributions proposing innovative approaches integrating quality, privacy and bias aspects of synthetic data generation.

**Announcements**
* [Link to the **live sessions** at ICLR website](https://iclr.cc/virtual/2021/workshop/2125). Note that registration to the ICLR main conference is required in order to access the website.
* Congratulations to winners of **best paper award**, "Leveraging Public Data for Practical Private Query Release", by Terrance Liu, Giuseppe Vietri, Thomas Steinke, Jonathan Ullman, and Steven Wu! The best paper award is generously sponsored by <a href='https://syntheticdata.community'>Synthetic Data's Community</a>.

| ------------- |:-------------:|
| **Submission** |March 5, 2021 (Anywhere on Earth) |
| **Notification** | March 31, 2021 |
| **Camera Ready** | April 16, 2021 |
| **Submission link**| [link](https://cmt3.research.microsoft.com/SDGICLRW2021) |
| **Workshop** | May 7, 2021 |

<!-- * Thank you Amazon for ing a best paper award!
* The 3 best papers will be presented in talks at the workshop! 
* <a href="schedule">The schedule is online now!</a> 
* <a href="papers">List of accepted papers available!</a>  -->
<!--* **NEW** Updates to existing submissions possible until October 12 (11:59pm Pacific Time) <br>New submissions close on October 09 (11:59pm Pacific Time)-->


<hr>

# Speakers & Panelists
<div class="container" style="margin-top: 20px;margin-bottom: 0px;">
  <div class="row">
  {% for p in site.data.speakers %}
  {% if forloop.index<=4 %}
  {% capture id %}{{ p[0] }}{% endcapture %}
  {% include profile.html p=p %}
  {% endif %}
  {% endfor %}
  </div>
  <div class="row">
  {% for p in site.data.speakers %}
  {% capture id %}{{ p[0] }}{% endcapture %}
  {% if forloop.index>4 and forloop.index<=8%}
  {% include profile.html p=p %}
  {% endif %}
  {% endfor %}
  </div>
  <div class="row">
  {% for p in site.data.speakers %}
  {% capture id %}{{ p[0] }}{% endcapture %}
  {% if forloop.index>10 %}
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
  {% if forloop.index>4 and forloop.index<=8%}
  {% include profile.html p=p %}
  {% endif %}
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

Contact: [email](mailto:saydore@amazon.com)
