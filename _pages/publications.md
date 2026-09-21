---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

<ul>{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>

<h2 class="page__title">Preprints and Working Papers</h2>

<ul>{% for post in site.preprints reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>
