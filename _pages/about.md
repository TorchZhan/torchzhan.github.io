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


I am a 2nd-year Phd student from the Macao Polytechnic University (MPU). My research interests include protein-peptide interaction and peptide design.

<!-- My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->

# 🔥 News
- *2025.08*: &nbsp;🎉🎉 A paper is accepted by **Digital Discovery** (IF:5.6, JCR Q1).
- *2022.07*: &nbsp;🎉🎉 A conference paper is accepted by **the 2025 International Conference on Intelligent
Computing (ICIC 2025, CCF-C)**.

# 📝 Publications 
Selected publications are listed below, focusing on some research tasks: Drug-target interaction prediction, anticancer peptide prediction....

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Digital Discovery</div><img src='images/MAARDTI.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[MAARDTI: A multi-perspective attention aggregating model for the prediction of drug-target interactions](waiting)
**Xinke Zhan**, Tiantao Liu, Changqing Yu, Yu-An Huang, Zhuhong You, Shirley W. I. Siu

[**Code**](https://github.com/TorchZhan/MAARDTI) [**Zenodo**](https://zenodo.org/records/16936305)

- MAAR module that providing a more comprehensive representation of the interactions between drugs and proteins.
- The superior prediction results of our method demonstrate the effectiveness of MAARDTI in predicting DTIs. 
  
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">the 2025 International Conference on Intelligent
Computing</div><img src='images/CALM.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[CALM-AcPEP:Predicting Anticancer Peptides Using Cross-Attention and Pre-Trained Language Model](https://link.springer.com/chapter/10.1007/978-981-95-0030-7_19)
**Xinke Zhan**, Tiantao Liu, Pratiti Bhadra, Yu-An Huang, Zhuhong You, Shirley W. I. Siu

- A deep learning framework based on the ACmix module,Evolutionary Scale Modeling 2 (ESM2) and cross-attention.
- The results of our proposed method shows improved performance in ACP prediction.
  
</div>
</div>

<!-- - [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020** -->

# 🎖 Honors and Awards
- *2024.08* Half-scholarship of the Macao Polytechnic University (2024-2027).
<!-- - *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

# 📖 Educations
- *2024.09 - (now)*, Ph.D. Macao Polytechnic University, Macau, China.
- *2019.09 - 2021.01*, M.S. Xijing University, Xi'an, Shaanxi, China.
- *2014.09 - 2018.06*, B.S. Hubei Polytechnic University, Huangshi, Hubei, China.

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)

# 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China. -->