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
* B.S. in Physics, Federal University of Pará, 2021
* M.S. in Physics, Federal University of Pará, 2023 (expected)
  
Skills
======
* Fluent in English
* Mathematical knowledge
  * Differential Geometry
  * Analysis
* Physics
  * General Relativity
  * Classical Field Theory

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  

