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
* Doctor of Philosophy in physics, University of Jyväskylä, 2017
  * Specialization in experimental high energy heavy ion physics
  * <a href="https://jyx.jyu.fi/handle/123456789/56142">Link to my PhD thesis</a>
* Master of Science in theoretical physics, University of Jyväskylä, 2012
  * Minor: French language and culture
  * <a href="https://jyx.jyu.fi/handle/123456789/40192">Link to my master's thesis</a>
* Bachelor of Science in physics, University of Jyväskylä, 2010
  * Minors: Mathematics and computer science

Work experience
======
* Spring 2024: Academic Pages Collaborator
  * Github University
  * Duties includes: Updates and improvements to template
  * Supervisor: The Users

* Fall 2015: Research Assistant
  * Github University
  * Duties included: Merging pull requests
  * Supervisor: Professor Hub

* Summer 2015: Research Assistant
  * Github University
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

Below you can find selected articles in which I have been the main analyzer. You can find the full list of articles I am on the author list on <a href="{{site.author.inspirehep}}">my InspireHEP page</a>.

Journal articles
------
  <ul>{% for post in site.publications reversed %}
    {% if post.publicationtype == 'journal' %}
      {% include archive-single-cv.html %}
    {% endif %} 
  {% endfor %}</ul>
  
Conference proceedings
------
  <ul>{% for post in site.publications reversed %}
    {% if post.publicationtype == 'conference' %}
      {% include archive-single-cv.html %}
    {% endif %}
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
