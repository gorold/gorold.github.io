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

<h2>2024</h2>
***Unified Training of Universal Time Series Forecasting Transformers*** <br>
**Gerald Woo**, Chenghao Liu, Akshat Kumar, Caiming Xiong, Silvio Savarese, Doyen Sahoo<br>
The Forty-first International Conference on Machine Learning (ICML), 2024 <br>
[arXiv](https://arxiv.org/abs/2402.02592) | [Code](https://github.com/SalesforceAIResearch/uni2ts) | [Blog](https://blog.salesforceairesearch.com/moirai/)

<h2>2023</h2>
***Learning Deep Time-index Models for Time Series Forecasting*** <br>
**Gerald Woo**, Chenghao Liu, Doyen Sahoo, Akshat Kumar, Steven Hoi <br>
The Fortieth International Conference on Machine Learning (ICML), 2023 <br>
[ICML'23](https://proceedings.mlr.press/v202/woo23b.html) | [arXiv](https://arxiv.org/abs/2207.06046) | [Code](https://github.com/salesforce/DeepTIMe) | [Blog](https://blog.salesforceairesearch.com/deeptime-meta-learning-time-series-forecasting/) | [Slides](http://gorold.github.io/files/DeepTime_ICML.pdf)

***Merlion: A machine learning library for time series*** <br>
Aadyot Bhatnagar, Paul Kassianik, Chenghao Liu, Tian Lan, Wenzhuo Yang, Rowan Cassius, Doyen Sahoo, Devansh Arpit, Sri Subramanian, **Gerald Woo**, Amrita Saha, Arun Kumar Jagota, Gokulakrishnan Gopalakrishnan, Manpreet Singh, KC Krithika, Sukumar Maddineni, Daeki Cho, Bo Zong, Yingbo Zhou, Caiming Xiong, Silvio Savarese, Steven Hoi, Huan Wang <br>
The Journal of Machine Learning Research (JMLR), Volume 24 <br>
[JMLR](https://www.jmlr.org/papers/v24/22-0809.html) | [arXiv](https://arxiv.org/abs/2109.09265) | [Code](https://github.com/salesforce/Merlion)

<h2>2022</h2>

***CoST: Contrastive Learning of Disentangled Seasonal-Trend Representations for Time Series Forecasting*** <br>
**Gerald Woo**, Chenghao Liu, Doyen Sahoo, Akshat Kumar, Steven Hoi <br>
The Tenth International Conference on Learning Representations (ICLR), 2022 <br>
[ICLR'22](https://openreview.net/forum?id=PilZY3omXV2) | [arXiv](https://arxiv.org/abs/2202.01575) | [Code](https://github.com/salesforce/CoST) | [Slides](http://gorold.github.io/files/ICLR_2022_CoST.pdf)

***Model agnostic defence against backdoor attacks in machine learning*** <br>
Sakshi Udeshi, Shanshan Peng, **Gerald Woo**, Lionell Loh, Louth Rawshan, Sudipta Chattopadhyay <br> 
IEEE Transactions on Reliability, 2022 <br>
[IEEE](https://ieeexplore.ieee.org/abstract/document/9754562) | [arXiv](https://arxiv.org/abs/1908.02203) | [Code](https://github.com/sakshiudeshi/Neo)

<h2>Preprints</h2>
***Pushing the Limits of Pre-training for Time Series Forecasting in the CloudOps Domain*** <br>
**Gerald Woo**, Chenghao Liu, Doyen Sahoo, Akshat Kumar <br>
[arXiv](https://arxiv.org/abs/2310.05063) | [Code](https://github.com/SalesforceAIResearch/pretrain-time-series-cloudops)

***ETSformer: Exponential Smoothing Transformers for Time-series Forecasting*** <br>
**Gerald Woo**, Chenghao Liu, Doyen Sahoo, Akshat Kumar, Steven Hoi <br>
[arXiv](https://arxiv.org/abs/2202.01381) | [Code](https://github.com/salesforce/ETSformer) | [Blog](https://blog.salesforceairesearch.com/etsformer-time-series-forecasting/)

***AI for IT Operations (AIOps) on Cloud Platforms: Reviews, Opportunities and Challenges*** <br>
Qian Cheng, Doyen Sahoo, Amrita Saha, Wenzhuo Yang, Chenghao Liu, **Gerald Woo**, Manpreet Singh, Silvio Saverese, Steven Hoi <br>
[arXiv](https://arxiv.org/abs/2304.04661)

<!-- {% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %} -->
