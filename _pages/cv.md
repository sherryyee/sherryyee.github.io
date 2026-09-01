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
* Ph.D in Computer Science, Dalian University of Technology, 2019
* B.S. in Software Engineering, Dalian University of Technology, 2011

Work experience
======
* 2024.08 --: Lecturer
  * Tianjin University of Commerce

* 2019.09-2024.08: Lecturer
  * Dalian Maritime University
 
* 2019.04-2019.08: Postdoc
  * Muroran Institute of Technology

  
Skills
======
* Programming Languages: Python, Java, C++
* Research Interests: Computer Science, Software Engineering

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
  
