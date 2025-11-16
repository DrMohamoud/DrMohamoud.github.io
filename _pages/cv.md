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
* Postdoctoral Fellowship {% if site.author.googlescholar %}
  <div class="wordwrap"> <a href="{{https://soradi.org/}}"> SORADI</a>.</div>
{% endif %} Hargeisa, Somaliland  / Roskilde University / Danish Fellowship Center, Denmark

{% include base_path %}
* Postdoctoral Fellowship, SORADI, Hargeisa, Somaliland  / Roskilde University / Danish Fellowship Center, Denmark
  * Supervisors : Dr. Mohamed Osman Fadal, Louise Wiuff Moe
* Ph.D in Applied Mathematics, Eskisehir Technical University, Turkey, 2023
* M.Sc. in Mathematical Sciences, African Institute for Mathematical Sciences (AIMS), The University of Western Cape, South Africa, 2018
* B.Sc. in Mathematics and Statistics, University of Hargeisa, Somaliland, 2016

Work experience
======
* Spring 2024: Academic Pages Collaborator
  * GitHub University
  * Duties includes: Updates and improvements to template
  * Supervisor: The Users

* Fall 2015: Research Assistant
  * GitHub University
  * Duties included: Merging pull requests
  * Supervisor: Professor Hub

* Summer 2015: Research Assistant
  * GitHub University
  * Duties included: Tagging issues
  * Supervisor: Professor Git
  
Skills
======
* Skill 1
* Skill 2
  * Sub-skill 2.1
  * Sub-skill 2.2
  * Sub-skill 2.3
* Skill 3

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
* Currently signed in to 43 different slack teams
