---
title: "Genomics Blog"
permalink: /blog/
author_profile: false
layout: archive
classes: wide

header:
  overlay_image: /assets/images/home/cuke1.jpg

excerpt: "Genomics is a broad field with many fascinating topics and subfields. See below for my thoughts and perspectives on them." 
---
 
{% for post in site.posts %}
  {% include archive-single.html type="grid" %}
{% endfor %}

