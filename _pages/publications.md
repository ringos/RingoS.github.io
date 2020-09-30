---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---




## Published Paper

  ( * indicates equal contribution)

* **Making the Best Use of Review Summary for Sentiment Analysis** \
  In Proceedings of the 28th International Conference on Computational
               Linguistics (COLING), 2020 \
  **Sen Yang\***, Leyang Cui\*, Jun Xie and Yue Zhang

* **What Have We Achieved on Text Summarization?** \
  In Proceedings of the 2020 Conference on Empirical Methods in Natural Language Processing (EMNLP), 2020 \
  Dandan Huang\*, Leyang Cui\*, **Sen Yang\***, Guangsheng Bao, Kun Wang, Jun Xie and Yue Zhang


## Preprint

  ( * indicates equal contribution)



{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
