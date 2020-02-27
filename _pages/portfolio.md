---
layout: archive
title: "Portfolio"
permalink: /portfolio/
author_profile: true
---

[Project Name 1](/Humana_May_Case_Competition.html)
![](/images/humana-mays.png)
Description

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
