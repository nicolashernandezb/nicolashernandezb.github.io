---
layout: archive
title: "Research"
permalink: /publications/
author_profile: true
---

**Predictive confidence bands for functional time series forecasting**

I am interested in the discussion about pointwise vs simultaneous inference in the context of predictions for functional time series using Autoregressive Hilbertian models (ARH).


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
