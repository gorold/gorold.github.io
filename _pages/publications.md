---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

**CoST: Contrastive Learning of Disentangled Seasonal-Trend Representations for Time Series Forecasting** 
**Gerald Woo**, Chenghao Liu, Doyen Sahoo, Akshat Kumar, Steven Hoi
The Tenth International Conference on Learning Representations (Poster)
[ICLR'22](https://openreview.net/forum?id=PilZY3omXV2) | [Code]()

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
