---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======

* MPhys 1st class hons, Physics, University of Bath, UK 2015
* PhD in Nanoscale Physics, University of Birmingham, UK 2020

Professional experience
======

* 2020 - present: Postdoctoral researcher working on algorithm development for 3D reconstruction from 4D-SPED data
  * See [home page]{% link about.html %} for more details.
  
Skills
======

* Python-proficient: machine learning and image processing workflows (NumPy, Numba, PyTorch, SciPy, scikit-image, scikit-learn, OpenCV), n-dimensional data analysis (including 4D-diffraction data), optimization and inverse problems, model creation, computer vision, and simulations.
* Git: versioning, collaboration, CI, and test-driven development.
* Maintainer for orix quaternion-based orientation library written in Python.
* Object-Oriented Programming, Matlab, LabView, C, C++, SQL, Windows, Linux, and Mac. GUI creation: Qt and Tk.
* Document creation: LaTeX, Microsoft Office, Apple iWork.

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
