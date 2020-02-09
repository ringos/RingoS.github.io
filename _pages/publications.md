---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

 \* indicates equal contribution

* **UsingBothReviewandSummaryforBetterSentimentAnalysis**  
  Under review

  Sen Yang\*, Leyang Cui\* and Yue Zhang

* **WhatHaveWeAchievedonTextSummarization?**   
  Under review

  Sen Yang\*, Dandan Huang\*, Leyang Cui\*, Guangsheng Bao and Yue Zhang

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
