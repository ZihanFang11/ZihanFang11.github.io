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

I am currently a Postdoc at the Department of Computer Science, Hong Kong Baptist University, working with [Prof. Hong-Ning Dai](https://www.comp.hkbu.edu.hk/~henrydai/), [Prof. Byron Choi](https://www.comp.hkbu.edu.hk/~bchoi/), [Prof. William Kwok-Wai Cheung](https://www.comp.hkbu.edu.hk/~william/) and [Prof. Jiming Liu](https://www.comp.hkbu.edu.hk/~jiming/).
I received my Ph.D. degree from the College of Computer and Data Science, Fuzhou University, in 2024, supervised by [Prof. Wenzhong Guo](https://ccds.fzu.edu.cn/info/1202/4993.htm) and [Prof. Shiping Wang](https://ccds.fzu.edu.cn/info/1202/8958.htm). Before that, I majored in software engineering and obtained my B.E. degree from the College of Mathematics and Computer Science, Fuzhou University, in 2019. From Oct 2022 to Oct 2023, I was also a joint Ph.D. student in Faculty of Computer Science, University of Vienna, Austria, supervised by [Prof. Claudia Plant](https://dm.cs.univie.ac.at/team/person/59835/). My research interests include graph neural networks, multi-view learning, optimization-inspired deep learning and their applications (e.g., time series anomaly detection, intelligent power systems, social networks). My studies have led to over 30 scientific publications <a href='https://scholar.google.com/citations?user=LM0QNdQAAAAJ'><img src="https://img.shields.io/endpoint?logo=Google%20Scholar&url=https%3A%2F%2Fcdn.jsdelivr.net%2Fgh%2Fchenzl23%2Fchenzl23.github.io@google-scholar-stats%2Fgs_data_shieldsio.json&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a> on top-tier conferences and journals, including AAAI, KDD, ACM MM, IEEE TPAMI, IEEE TKDE, IEEE TNNLS, IEEE TMM, IEEE TSP, ACM TKDD, Information Fusion, etc.


# 📖 Educations
- *2022.09 - Present*, Ph.D. in Computer Science and Technology, College of Computer and Data Science, Fuzhou University, China. Supervisor: Prof. Shiping Wang.
- *2018.09 - 2022.06*, B.S. in Data Science and Big Data Technology, College of Computer and Data Science, Fuzhou University, China. Recommended for postgraduate study.


# 📝 Publications 
<p style="font-size:0.9em; color:#666; margin-top:-10px; margin-bottom:5px;">
<sup>†</sup> indicates co-first author; * indicates corresponding author. <a href="https://scholar.google.com/citations?user=naPgEh4AAAAJ" target="_blank">Full List</a>
</p>

{% include_relative publication/GNNs.md %}

{% include_relative publication/multiview.md %}

{% include_relative publication/matrixCompletion.md %}

{% include_relative publication/others.md %}


<script type='text/javascript' id='clustrmaps' src='//cdn.clustrmaps.com/map_v2.js?cl=ffffff&w=333&t=tt&d=1ulB9ZQGFru21d-WVtCOCUjEViGcsvM4IKn-_xFkYZI&cmn=3e3acc'></script>
