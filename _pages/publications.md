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

{{ author.googlescholar }}

<h2>2022</h2>
***CoST: Contrastive Learning of Disentangled Seasonal-Trend Representations for Time Series Forecasting*** <br>
**Gerald Woo**, Chenghao Liu, Doyen Sahoo, Akshat Kumar, Steven Hoi <br>
The Tenth International Conference on Learning Representations (ICLR), 2022 <br>
[ICLR'22](https://openreview.net/forum?id=PilZY3omXV2) | [arXiv](https://arxiv.org/abs/2202.01575) | [Code](https://github.com/salesforce/CoST)

***Model agnostic defence against backdoor attacks in machine learning*** <br>
Sakshi Udeshi, Shanshan Peng, **Gerald Woo**, Lionell Loh, Louth Rawshan, Sudipta Chattopadhyay <br> 
IEEE Transactions on Reliability, 2022 <br>
[IEEE](https://ieeexplore.ieee.org/abstract/document/9754562) | [arXiv](https://arxiv.org/abs/1908.02203) | [Code](https://github.com/sakshiudeshi/Neo)

<h2>Preprints</h2>
***ETSformer: Exponential Smoothing Transformers for Time-series Forecasting*** <br>
**Gerald Woo**, Chenghao Liu, Doyen Sahoo, Akshat Kumar, Steven Hoi <br>
[arXiv](https://arxiv.org/abs/2202.01381) | [Code](https://github.com/salesforce/ETSformer)

***Merlion: A machine learning library for time series*** <br>
Aadyot Bhatnagar, Paul Kassianik, Chenghao Liu, Tian Lan, Wenzhuo Yang, Rowan Cassius, Doyen Sahoo, Devansh Arpit, Sri Subramanian, **Gerald Woo**, Amrita Saha, Arun Kumar Jagota, Gokulakrishnan Gopalakrishnan, Manpreet Singh, KC Krithika, Sukumar Maddineni, Daeki Cho, Bo Zong, Yingbo Zhou, Caiming Xiong, Silvio Savarese, Steven Hoi, Huan Wang <br>
[arXiv](https://arxiv.org/abs/2109.09265) | [Code](https://github.com/salesforce/Merlion)

<!-- {% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %} -->
