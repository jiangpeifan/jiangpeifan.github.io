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
* Ph.D. in Earth Exploration and Information Technology, Chengdu University of Technology, 2027 (expected)
* M.S. in Computer Technology, Chengdu University of Technology, 2023



Skills
======
* Programming
* Calligraphy



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
