---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

WaggleNet: Learn to Track and Follow Bees Figure-eight Motion


Neuromorphic Colour Event Camera: A Detailed Characterisation


Neuromorphic Engineering Needs Closed-Loop Benchmarks


Characterization of Coated Piezo-resistive Fabric for Respiration Sensing



Characterisation of morphic sensors for body volume and shape applications



{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
