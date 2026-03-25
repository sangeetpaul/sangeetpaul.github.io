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
* PhD in Physics, University of Oregon, 2025
* MSc in Physics, NISER, 2018

Skills
======
* Bayesian statistics
* Machine learning
* GPU acceleration

Work experience
======
* 2019-2025: Research Assistant
  * University of Oregon
  * Supervisor: Ben Farr

* 2019-2025: Teaching Assistant
  * University of Oregon

* 2018-2019: Research Fellow
  * NISER

* 2013-2018: Research Scholar
  * NISER

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Vice-President, Graduate Student Council, Dept of Physics, U Oregon
* PhD Admissions Committee, Dept of Physics, U Oregon
* Graduate Support Group, Dept of Physics, U Oregon
