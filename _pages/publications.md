---
layout: archive
title: "Research"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

<h2> Works in Progress <h2/>
======

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
