---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I am currently a Ph.D. student in Computer Science and Technology at the College of Computer and Data Science, Fuzhou University, supervised by Prof. Shiping Wang. 
I received my B.S. degree in Data Science and Big Data Technology from Fuzhou University in 2022.
My research interests include multi-view learning, open-set learning, uncertainty modeling, and reliable representation learning. 
My studies have led to over 30 scientific publications on top-tier conferences and journals.


# 📖 Educations
- *2022.09 - Present*, Ph.D. in Computer Science and Technology, College of Computer and Data Science, Fuzhou University, China. Supervisor: Prof. Shiping Wang.
- *2018.09 - 2022.06*, B.S. in Data Science and Big Data Technology, College of Computer and Data Science, Fuzhou University, China. Recommended for postgraduate study.


# 📝 Publications 

{% include_relative publication/Openset.md %}

{% include_relative publication/multiview.md %}

{% include_relative publication/others.md %}


<script type='text/javascript' id='clustrmaps' src='//cdn.clustrmaps.com/map_v2.js?cl=ffffff&w=333&t=tt&d=1ulB9ZQGFru21d-WVtCOCUjEViGcsvM4IKn-_xFkYZI&cmn=3e3acc'></script>
