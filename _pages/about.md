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

# About Me
Hi there 👋 I am Jiting Liu, currently a research assistant at Microsoft Research Asia, advised by [Prof. Lili Qiu](https://www.microsoft.com/en-us/research/people/liliqiu/). My research interests are around ubiquitous and mobile computing, specifically exploring wearable sensors and sensor-based system development.

I received my master's degree in Computer Science from Columbia University, where I was fortunate to be advised by [Prof. Xia Zhou](https://www.cs.columbia.edu/~xia/). I received my bachelor‘s degree in Computer Science from Northeastern University (China) in 2022.

# News
- *2024.06*: **“Joey”** wins the Best Paper Award!
- *2024.03*: Our paper **“Joey”** is accepted to MobiSys 2024!

# Publications 
<div style="display: flex; align-items: flex-start; justify-content: space-between; margin-bottom: 20px;">
  <!-- Left: Image -->
  <div style="flex-basis: 19%; padding-right: 20px;">
    <img src="images/Joey_MobiSys24.png" style="width: 100%;" alt="Joey MobiSys24">
  </div>

  <!-- Right: Text -->
  <div style="flex-basis: 81%;">
    <h3 style="margin-top: 0;"> Joey: Supporting Kangaroo Mother Care with Computational Fabrics
      <a href='https://dl.acm.org/doi/10.1145/3643832.3661867'>[PDF]</a> 
      <a href='https://youtu.be/67KQlB9G-lk'>[Video]</a>
    </h3>
    <p>
      Qijia Shao, <strong>Jiting Liu</strong>, Emily Bejerano, Ho Man Colman Leung, Jingping Nie, Xiaofan Jiang, and Xia Zhou <br>
      <em>Proceedings of the 22nd Annual International Conference on Mobile Systems, Applications and Services (MobiSys), June 2024 </em><br>
      <p style="color: red;">Best Paper Award. People's Choice Demo Award.</p>
    </p>
  </div>
</div>

# Internships
- *2024.03 - 2024.08*, Research Assistant, Wireless Group, Microsoft Research Asia, Shanghai, China.
- *2022.04 - 2022.07*, Software Engineer Intern, NetEase Games, Hangzhou, China.