---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---




## Published

  ( * indicates equal contribution)

* **Template-Based Named Entity Recognition Using BART** [[pdf](https://ringos.github.io/publications/)] [[bib](https://ringos.github.io/publications/)] \
  in Findings of the 59th Annual Meeting of the Association for Computational Linguistics (ACL), 2021 \
  Leyang Cui, Yu Wu, Jian Liu, **Sen Yang** and Yue Zhang

* **Making the Best Use of Review Summary for Sentiment Analysis** [[pdf](https://www.aclweb.org/anthology/2020.coling-main.15.pdf)] [[bib](https://www.aclweb.org/anthology/2020.coling-main.15.bib)] \
  in Proceedings of the 28th International Conference on Computational Linguistics (COLING), 2020 \
  **Sen Yang\***, Leyang Cui\*, Jun Xie and Yue Zhang

* **What Have We Achieved on Text Summarization?** [[pdf](https://www.aclweb.org/anthology/2020.emnlp-main.33.pdf)] [[bib](https://www.aclweb.org/anthology/2020.emnlp-main.33.bib)] \
  in Proceedings of the 2020 Conference on Empirical Methods in Natural Language Processing (EMNLP), 2020 \
  Dandan Huang\*, Leyang Cui\*, **Sen Yang\***, Guangsheng Bao, Kun Wang, Jun Xie and Yue Zhang


## Preprint

  ( * indicates equal contribution)

* **Investigating Non-local Features for Neural Constituency Parsing** [[pdf](https://arxiv.org/abs/2109.12814)]  \
  arXiv prepreint \
  Leyang Cui\*, **Sen Yang\*** and Yue Zhang


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
