---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

📄 **[Download my CV (PDF)](/files/CV_mayuharada.pdf)**

Education
======
* B.S. in Biology, Kyoto University, 2027 (expected)

Research experience
======
* Spring 2024: Academic Pages Collaborator
  * GitHub University
  * Duties includes: Updates and improvements to template
  * Supervisor: The Users

Skills
======
* Molecular biology (plasmid design and cloning, PCR, bacterial transformation, mammalian cell transfection)
* Protein biochemistry (protein expression and purification, SDS-PAGE)
* Gas chromatography
* Fluorescence microscope
* Project management

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
  
