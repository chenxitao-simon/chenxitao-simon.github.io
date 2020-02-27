---
layout: archive
title: "Portfolio"
permalink: /portfolio/
author_profile: true
---

A data-driven personal website
======
[**Data Visualisation: Airbnb Selection in NYC 2019**](/files/Airbnb%20Selection%20in%20NYC_Susie%20Tao.pdf)
[![Open the notebook](https://img.shields.io/badge/Jupyter-OPen_the_Notebook-9cf?logo=Jupyter)](https://davinaliang.github.io/files/Airbnb%20Selection%20in%20NYC_Susie%20Tao.pdf)
- Description
![](/images/Airbnb%20Selection%20in%20NYC.png)

---
[Project Name 2](/pdf/PricingAnalyticsPJ2.pdf)
![](/images/PricingAnalyticsPJ2.png)
Description

---
[Project Name 3](/pdf/PricingAnalyticsPJ1.pdf)
![](/images/PPJ1.jpeg)
Description

---
[Project Name 4](/pdf/Twitter%20-%20Natural%20Language%20Processing.pdf)
![](/images/twitter.png)
Description

---

[Project Name 5](/911_descrptive_analysis.html)
![](/images/911%20Projct.png)

{% include base_path %}


{% for post in site.portfolio %}
  {% include archive-single.html %}
{% endfor %}
