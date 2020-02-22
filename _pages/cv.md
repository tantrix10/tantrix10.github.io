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
* MMath in Mathematics, Aberystwyth University, 2012-2016, 1st(hons)
* Msc in Physics, The University of Warwick, 2016-2017, Merit
* Ph.D in Quantum Information Theory, The University of Warwick, 2017-2020 (expected october finish)

Skills
======
* Mathematics
   *Linear Algebra
   *Differential Geometry
   *Quantum Information Theory
   *Parameter Estimation
* Problem solving
* Analytics
* Programming langauges
  * Python
  * C++
  * Rust
  * Mathematica (if you count this as a programming langauge...)
* Communication
* Algorithms


Projects
----

Academic
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Code
======
  <ul>{% for post in site.talks %}
    {% include archive-single-code-cv.html %}
  {% endfor %}</ul>
  
Hobbies
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
