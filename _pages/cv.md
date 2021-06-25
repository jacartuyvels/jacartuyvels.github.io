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
* Bachelor Civil Engineering, Université Catholique de Louvain, 2014-2017
  * Major in applied mathematics
  * Minor in economics
* Master in Applied Mathematics cum laude, Université Catholique de Louvain, 2017-2019
  * Major in optimization and operation research engineering
  * Master thesis: "A stochastic equilibrium approach to the reserve capacity market under the risk-aversion paradigm" under the supervision of Anthony Papavasiliou
* Ph.D in Power System Economics, Université Catholique de Louvain, 2019-2023 (expected)
  * Supervised by Anthony Papavasiliou

Work experience
======
* 2018-2019: Programmer for the EUCalc european calculator
  * Climact, Louvain-la-Neuve
  * I participated in the implementation of a Knime to Python converter to improve the computationnal time of the calculator

* Fall 2017: Teaching Assistant for the class LEPL1501
  * Université Catholique de Louvain
  * I oversaw and guided a class of engineering student for their first project at university

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
