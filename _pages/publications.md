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

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

### Scalable and Efficient Temporal Graph Representation Learning via Forward Recent Sampling.
**Yuhong Luo** and Pan Li. In *Learning on Graphs*, 2024.

[Download paper here.](https://arxiv.org/abs/2402.01964)


### Neighborhood-aware Scalable Temporal Network Representation Learning.
**Yuhong Luo** and Pan Li. In *Learning on Graphs*, 2022. Oral (4.6%), *Best Paper Award*.

[Download paper here.](https://proceedings.mlr.press/v198/luo22a/luo22a.pdf)

## Priprint

### Learning Fair Representations with High-Confidence Guarantees.
**Yuhong Luo**, Austin Hoag and Philip S. Thomas. *arXiv preprint arXiv:2310.15358*, 2023.

[Download paper here.](https://arxiv.org/pdf/2310.15358.pdf)
