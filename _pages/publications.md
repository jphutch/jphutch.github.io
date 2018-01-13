---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

## "Longevity versus Production: Analyzing Economic Tradeoffs in Dairy Cow Replacement"
Dairy cow milk production has increased about 3-4\% annually largely due to genetic selection on milk production traits by dairy breeders.  The negative consequence of this policy has been shorter and shorter productive life, and currently about 80\% of US dairy cow exit is because of a health problem, infertility, or death.  Breeding goals have largely been oriented towards production characteristics because their economic value is better defined than the costs of cows unexpectedly leaving the herd.  In this preliminary work, I focus on how these sorts of exit on dairy farms factor into the replacement decision and how this effects the profitability of the current breeding goals of US dairy cattle.  I construct a structural model of dairy cow replacement that improves upon the model of Miranda and Schnitkey (1995) by including mortality and disposal costs.  I use this model to demonstrate how high disposal cost decreases the replacement age, especially at low profit margins.  Finally, I present a simulation of the model on pseudo-data to show how this model can explain puzzling results found in Miranda and Schnitkey (1995).  This model can be empirically tractable on DHIA data given recent advancements in dynamic discrete choice estimation.

- This is a test to see if this works
- Hopefully it does
{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
