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
* January 2022 - Current: Postdoctoral researcher
  * Vanderbilt University
  * Nashville, Tennessee, USA
  * Duties include:
    * Analysis on energy-energy correlators
    * Analysis on dijet azimuthal asymmetry
    * Convener of the high \\(p_{\mathrm{T}}\\) physics interest group within the CMS heavy ion group
    * Producing rapid validation datasets during the 2023 heavy ion run
    * Maintaining the common analysis code (HiForest) for the CMS heavy ion group
    * Helping to supervise students
  * Supervisor: Julia Velkovska

* March 2018 - September 2021: Postdoctoral researcher
  * University of Illinois at Chicago
  * Chicago, Illinois, USA
  * Duties included:
    * Analysis on jet shapes from dijet events
    * Analysis on dijet azimuthal asymmetry
    * Control room shifts in the CMS experiment
    * Alignment validation for tracker during 2018 heavy ion run
    * Updating alignment validation tool to include a tracker validation method for high \\(p_{\mathrm{T}}\\) tracks
  * Supervisor: Olga Evdokimov

* November 2012 - December 2017: PhD Student
  * University of Jyväskylä
  * Jyväskylä, Finland and CERN, Switzerland/France
  * Duties included:
    * Analysis on jet fragmentation transverse momentum
    * Run manager for the ALICE experiemnt for one month
    * Updating the firmware in the EMCal trigger for run2
    * Control room shifts at the ALICE experiment
    * Being teaching assistant in particle physics and heavy ion physics courses
  * Supervisor: Jan Rak
  
* June 2008 - August 2008: Summer intern
  * Stresstech Oy
  * Vaajakoski, Finland
  * Duties included measuring residual stresses from metal pieces

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
  
Leadership experience and positions of trust
======
* 2022 - current: Convener of the high-\\(p_{\mathrm{T}}\\) physics interest group within the CMS heavy ion group
* April 2017 - May 2017: Run manager in the ALICE experiment, two weeks both in April and May
* October 2015 -  March 2018: Junior ambassador of Finland in the ALICE experiment
* November 2012 - November 2014: President of the residents' committee in at KOAS Ristonmaa student housing association
* September 2012 - November 2012: Member of the students' union at the University of Jyväskylä
* November 2010 - November 2012: Member of the residents' committee in at KOAS Ristonmaa student housing association


Skills
======
* Languages (<a href="https://europass.europa.eu/en/common-european-framework-reference-language-skills">CEFR levels</a>: A1 and A2: Basic user; B1 and B2: Independent user; C1 and C2: Proficient user)
  * Finnish: Mother tongue
  * English: C2
  * French: B1
  * Swedish: A2
* Programming languages
  * C++ and root libraries
  * Python
  * bash
  * Java
* Other digital skills
  * Proficient user of LaTeX
  * Experience in working with MacOS, Linux/Unix and Windows operating systems
  * Experience with Git and GitHub

<!---
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>  
--->
