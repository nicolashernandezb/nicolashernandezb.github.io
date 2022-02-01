---
layout: archive
title: "Research"
permalink: /publications/
author_profile: true
---

My main research is oriented to develop methods to tackle inferential problems in high-dimensional and functional data over different fields such as: energy, economics, the environment, demography, business, finance, health and genetics. I have mainly focused on predictive confidence bands for functional time series; domain selection and classification in the Functional Data context; and outlier detection for staochastic processes using Information Theory tools. For a complete list of publications, see my [Google Scholar](https://scholar.google.com/citations?hl=es&user=6IZOUNkAAAAJ) profile.

**Predictive confidence bands for functional time series forecasting**

I am interested in the discussion about pointwise vs simultaneous inference in the context of predictions for functional time series (FTS) using Autoregressive Hilbertian models (ARH). We have addressed the problem of constructing simultaneous predictive confidence bands for a stationary FTS. The method connect the inferential statistics world with the Information Theroy field using an entropy measure for stochastic processes to construct predictive bands. We consider a Reproducing Kernel Hilbert Spaces (RKHS) to represent the functions and define the minimum entropy regions that account for a given level of probability.

This project is under development jointly with [Jairo Cugliari](https://julienas.univ-lyon2.fr/jcugliari/) and [Julien Jacques](https://julienas.univ-lyon2.fr/jcugliari/).

- [Simultaneous predictive bands for functional time series using minimum entropy sets](https://arxiv.org/abs/2105.13627) - Under review in the International Journal of Forecasting.

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
