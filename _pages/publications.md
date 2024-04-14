---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.inspirehep %}
  <div class="wordwrap">Below you can find selected articles in which I have been the main analyzer. You can find the full list of articles I am on the author list on <a href="{{site.author.inspirehep}}">my InspireHEP page</a>.</div>
{% endif %}

{% include base_path %}

<h2>Journal articles</h2>

{% for post in site.publications reversed %}
  {% if post.publicationtype == 'journal' %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

<h2>Conference proceedings</h2>

{% for post in site.publications reversed %}
  {% if post.publicationtype == 'conference' %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}
