---
layout: archive
title: "Research"
excerpt: " <br/>  "
permalink: /publications/
author_profile: true
header:
  overlay_image: http://jhutchinswisc.github.io/images/goat_header.jpg
---
[Click here to view my research statement.](http://jhutchinswisc.github.io/files/Jared_Hutchins_Research_Statement.pdf)

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}
<h2> Research Projects </h2>
{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}





-----

