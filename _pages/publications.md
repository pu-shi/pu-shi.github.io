---
layout: archive
title: ""
permalink: /publications/
author_profile: true
---

Journal Papers and Preprints
Z. Song, L. Shi, S. Pu and M. Yan, Compressed Gradient Tracking for Decentralized Optimization over General Directed Networks, preprint.
Y. Liao, Z. Li, K. Huang and S. Pu, Compressed Gradient Tracking Methods for Decentralized Optimization with Linear Convergence, submitted.
K. Huang and S. Pu, Improving the Transient Times for Distributed Stochastic Gradient Methods, submitted.
S. Pu, A. Olshevsky and I.C. Paschalidis, A Sharp Estimate on the Transient Time of Distributed Stochastic Gradient Descent,  submitted.
R. Xin, S. Pu, A. Nedić and U. Khan. A General Framework for Decentralized Optimization with First-order Methods. Proceedings of the IEEE, 108(11):1869-1889, 2020.
S. Pu and A. Nedić. Distributed Stochastic Gradient Tracking Methods. Mathematical Programming, 187(1):409-457, 2021. [arxiv]
S. Pu, A. Olshevsky and I.C. Paschalidis, Asymptotic Network Independence in Distributed Stochastic Optimization for Machine Learning: Examining Distributed and Centralized Stochastic Gradient Descent, IEEE Signal Processing Magazine, 37(3):114-122, 2020. [arxiv].
S. Pu, W. Shi*, J. Xu and A. Nedić. Push-Pull Gradient Methods for Distributed Optimization in Networks. IEEE Transactions on Automatic Control, 66(1):1-16, 2021. [arxiv]
S. Pu, J.J. Escudero-Garzas, A. Garcia and S. Shahrampour. An Online Mechanism for Resource Allocation in Networks. IEEE Transactions on Control of Network Systems, 7(3):1140-1150, 2020.
S. Pu and A. Garcia. Swarming for Faster Convergence in Stochastic Optimization. SIAM Journal on Control and Optimization, 56(4):2997-3020, 2018. [arxiv]
S. Pu and A. Garcia. A Flocking-based Approach for Distributed Stochastic Optimization. Operations Research, 66(1):267-281, 2018. [arxiv]
S. Pu, A. Garcia and Z. Lin. Noise Reduction by Swarming in Social Foraging. IEEE Transactions on Automatic Control, 61(12):4007-4013, 2016.
(*co-first author)

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
