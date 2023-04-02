---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* B.S. in Mathematics, Universitat Politècnica de Catalunya (Barcelona, Spain), 2014
* Engineer Degree in Computer Science, Universitat Politècnica de Catalunya (Barcelona, Spain), 2014
* M.S. in Mathematics, Rheinische Friedrich-Wilhelms-Universität Bonn (Germany), 2016
* Ph.D in Information and Communication Technologies, Universitat Pompeu Fabra (Barcelona, spain), 2019

  
Skills
======
* Cardiovascular image analysis
* Mesh processing
* Physiological modelling


Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
