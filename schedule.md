---
layout: page
title: Synthetic Data Generation
subtitle: Quality, Privacy, Bias
use-site-title: true
---

# Schedule

#### Friday, May 7, 2021 
#### All times are in PT 

#### [Link to the live sessions at ICLR website](https://iclr.cc/virtual/2021/workshop/2125). Note that registration to the ICLR main conference is required in order to access the website.

<!-- #### Location: West 109 + 110, Area West Level 1 -->
<!-- #### Live Video Stream: [link](https://XXX) -->


<div class="container">
  <div class="row">
    <table class="table">
        {% for s in site.data.schedule %}
        <tr>
        <td>{{ s[1].start }}</td>
        {% if s[1].type == "General" %}
          <td>{{ s[1].event }}</td>
          <td></td>
        {% elsif s[1].type == "Invited" %}
          <td >Invited Talk</td>
          {% assign speaker_id = s[1].event %}
          {% assign speaker = site.data.speakers[speaker_id] %}
          <td >
            <i>{{ s[1].title }}</i><br>
          <a href="{{speaker.url}}">{{ speaker.name }}</a>, {{speaker.affiliation}}
          {% if speaker.title == "TBA" %}
          {% else %}
          <br><i><b>{{ speaker.title }}</b></i>
          {% endif %}
          </td>
        {% elsif s[1].type == "Contributed" %}
          <td>Contributed Talk</td>
          <td ><i>{{ s[1].event }}</i><br>{{ s[1].author }}</td>
        {% elsif s[1].type == "Spotlights" %}
          <td>Spotlights</td>
          <td><a href="#{{s[0]}}">{{ s[1].event }}</a></td>
        {% elsif s[1].type == "Break" %}
          <td class="info">{{ s[1].event }}</td>
          <td class="info"></td>
        {% elsif s[1].type == "Session" %}
          <td><b>{{ s[1].event }}</b></td>
          <td></td>
        {% elsif s[1].type == "None" %}
          <td ></td>
          <td >{{ s[1].event }}</td>
        {% elsif s[1].type == "Panel" %}
          <td >Discussion Panel</td>
          <td ><i>{{ s[1].event }}</i><br>{{ s[1].speakers }}</td>
        {% endif %}

        <!-- <td>
            {% capture id %}{{ p[0] }}{% endcapture %}
            {{ s }}
        </td> -->
        </tr>
        {% endfor %}
    </table>
  </div>
