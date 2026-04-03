---
layout: archive
title: ""
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Ph.D in Safe AI, University of York, UK, 2029 (expected)
* M.S. in Computer Science, Technical University Munich, Germany, 2025
* B.S. in Computer Science, Technical University Berlin, Germany, 2022

Work experience
======

* 02/2026 – Present: Graduate Teaching Assistant at University of York, York
  * Teaching Theory 2 (Formal Languages and Automata)

* 04/2025 – 08/2025: Junior Research Scientist atFraunhofer IKS, Munich
  * Research on safety, reliability and alignment of LLMs

* 10/2023 – 04/2024: Thesis Student in Safe AI at LatticeFlow (ETH spin-off), Zurich
  * Master’s thesis on deep learning approaches to improve data quality

* 08/2023 – 09/2023: Research Intern in Robust Deep Learning at MIT, Manipal, India
  * Robustness analysis and boosting of motor imagery algorithms

* 04/2023 – 07/2023: Working Student in Safety Assurance at Siemens AG, Munich
  * Research on resilience to adversarial attacks in deep learning

* 04/2022 – 03/2023: Working Student in Trustworthy AI at Fraunhofer IKS, Munich
  * Bachelor’s thesis and projects in trustworthy autonomous mobility

* 06/2021 – 08/2021: Research Intern in Robotics at Ingeniarius Lda., Porto, Portugal
  * Drone communication, mapping and navigation in ROS for collaborative robotic systems in forest fire prevention
  
Skills
======

* Programming Skills
  * Python, R: Advanced
  * Java, SQL, C++: Intermediate

* Language Skills
  * German: Mother tongue
  * English: Advanced oral and written skills (TOEFL: 106, C1)
  * Spanish, French: Intermediate oral and written skills (B1)

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
