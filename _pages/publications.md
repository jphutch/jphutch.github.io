---
layout: archive
title: "Research"
excerpt: " <br/>  "
permalink: /publications/
author_profile: true
header:
  overlay_image: http://jphutch.github.io/images/goat_header.jpg
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

<h2> Publications </h2>
{% for post in site.pubs reversed %}
{% if post.pubtype == 'publication' %}
  {% include archive-single.html %}
    {% endif %}
{% endfor %}

<h2> Research Projects </h2>
{% for post in site.publications reversed %}
{% if post.pubtype == 'working_paper' %}
  {% include archive-single.html %}
    {% endif %}
{% endfor %}





-----

