---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

## Conference Papers

* **What Have We Achieved on Text Summarization?** \
  In Proceedings of the 2020 Conference on Empirical Methods in Natural Language Processing (EMNLP), 2020 \
  ( ''\*'' indicates equal contribution)\
  Dandan Huang\*, Leyang Cui\*, **Sen Yang\***, Guangsheng Bao, Kun Wang, Jun Xie and Yue Zhang
  

## Preprints

* **Using Both Review and Summary for Better Sentiment Analysis** \
  ( ''\*'' indicates equal contribution)\
  **Sen Yang\***, Leyang Cui\* and Yue Zhang


  


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
