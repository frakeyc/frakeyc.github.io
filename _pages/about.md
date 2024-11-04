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


I am now a PhD student in the [School of Computer Science and Engineering](https://www.scse.uestc.edu.cn/) of the [University of Electronic Science and Technology of China](https://www.uestc.edu.cn/) under the advisory of Prof. [Kai Zheng](https://zheng-kai.com/). I got my M.E. degree from the Beijing University of Posts and Telecommunications in 2023. My research interests include time series analysis and spatio-temporal data mining.





<!-- # 🔥 News
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

# 🔥 News
- *2024.09*: &nbsp;🎉🎉 One paper is accepted by NeurIPS 2024. 
- *2024.07*: &nbsp;🎉🎉 One paper is accepted by CIKM 2024. 
- *2024.02*: &nbsp;🎉🎉 One paper is accepted by ICDE 2024.

# 📝 Publications <img src="https://img.shields.io/endpoint?logo=Google%20Scholar&url=https%3A%2F%2Fcdn.jsdelivr.net%2Fgh%2Ffrakeyc%2Ffrakeyc.github.io@google-scholar-stats%2Fgs_data_shieldsio.json&labelColor=f6f6f6&color=9cf&style=flat&label=citations">
1. RAGraph: A General Retrieval-Augmented Graph Learning Framework.<br/>Xinke Jiang, Rihong Qiu, Yongxin Xu, WentaoZhang, Yichen Zhu, Ruizhe zhang, **Yuchen Fang**, Xu Chu, Junfeng Zhao, Yasha Wang.<br/>The Thirty-eighth Annual Conference on Neural Information Processing Systems. (Accepted, **NeurIPS 2024**)
2. Advancing Certified Robustness of Explanation via Gradient Quantization.<br/>Yang Xiao, Zijie Zhang, **Yuchen Fang**, Da Yan, Yang Zhou, Wei-Shinn Ku, Bo Hui<sup>#</sup>.<br/>The 33rd ACM International Conference on
Information and Knowledge Management. (**CIKM 2024**)
3. CDGNet: A Cross-Time Dynamic Graph-Based Deep Learning Model for Vehicle-Based Traffic Speed Forecasting.<br/>**Yuchen Fang**, Haiyong Luo<sup>#</sup>, Fang Zhao<sup>#</sup>, Poly ZH Sun, Yanjun Qin, Liang Zeng, Bo Hui, Chenxing Wang.<br/>IEEE Transactions on Intelligent Vehicles. (T-IV 2024)
4. Temporal-Frequency Masked Autoencoders for Time Series Anomaly Detection.<br/>**Yuchen Fang**, Jiandong Xie, Yan Zhao<sup>#</sup>, Lu Chen, Yunjun Gao, Kai Zheng<sup>#</sup>.<br/>The 40th IEEE International Conference on Data Engineering. (**ICDE 2024**) (**Accepted without Revision 19/962**) [![](https://img.shields.io/github/stars/LMissher/TFMAE?style=social)](https://github.com/LMissher/TFMAE)
5. Knowledge Distillation for Travel Time Estimation.<br/>Haichao Zhang, Fang Zhao<sup>#</sup>, Chenxing Wang, Haiyong Luo<sup>#</sup>, Haoyu Xiong, **Yuchen Fang**.<br/>IEEE Transactions on Intelligent Transportation Systems. (T-ITS 2024) 
6. Spatio-temporal graph neural networks for predictive learning in urban computing: A survey.<br/>Guangyin Jin, Yuxuan Liang<sup>#</sup>, **Yuchen Fang**, Zezhi Shao, Jincai Huang, Junbo Zhang, Yu Zheng.<br/>IEEE Transactions on Knowledge and Data Engineering. (**TKDE 2023**)
7. STWave+: A Multi-Scale Efficient Spectral Graph Attention Network With Long-Term Trends for Disentangled Traffic Flow Forecasting.<br/>**Yuchen Fang**, Yanjun Qin, Haiyong Luo, Fang Zhao, Kai Zheng<sup>#</sup>.<br/>IEEE Transactions on Knowledge and Data Engineering. (**TKDE 2023**)
8. Constrained Market Share Maximization by Signal-Guided Optimization.<br/>Bo Hui, **Yuchen Fang**<sup>+</sup>, Tian Xia, Sarp Aykent, Wei-Shinn Ku<sup>#</sup>.<br/>The 37th AAAI Conference on Artificial Intelligence. (**AAAI 2023**)
9. Spatio-temporal hierarchical MLP network for traffic forecasting.<br/>Yanjun Qin, Haiyong Luo, Fang Zhao, **Yuchen Fang**, Xiaoming Tao<sup>#</sup>, Chenxing Wang.<br/>Information Sciences. (IS 2023)
10. When spatio-temporal meet wavelets: Disentangled traffic forecasting via efficient spectral graph attention networks.<br/>**Yuchen Fang**, Yanjun Qin, Haiyong Luo<sup>#</sup>, Fang Zhao<sup>#</sup>, Bingbing Xu, Liang Zeng, Chenxing Wang.<br/>The 40th IEEE International Conference on Data Engineering. (**ICDE 2023**) [![](https://img.shields.io/github/stars/LMissher/STWave?style=social)](https://github.com/LMissher/STWave) <a href='https://scholar.google.com/citations?user=-adyoyIAAAAJ&hl'> <strong><span class='show_paper_citations' data='4FA6C0AAAAAJ:LkGwnXOMwfcC'></span></strong>
11. Learning All Dynamics: Traffic Forecasting via Locality-Aware Spatio-Temporal Joint Transformer.<br/>**Yuchen Fang**, Fang Zhao<sup>#</sup>, Yanjun Qin, Haiyong Luo<sup>#</sup>, Chenxing Wang.<br/>IEEE Transactions on Intelligent Transportation Systems. (T-ITS 2022) 
12. Next Point-of-Interest Recommendation with Auto-Correlation Enhanced Multi-Modal Transformer Network.<br/>Yanjun Qin, **Yuchen Fang**<sup>+</sup>, Haiyong Luo<sup>#</sup>, Fang Zhao<sup>#</sup>, Chenxing Wang.<br/>The 45th International ACM SIGIR Conference on Research and Development in Information Retrieval. (**SIGIR 2022**)
13. Fine-Grained Trajectory-Based Travel Time Estimation for Multi-City Scenarios Based on Deep Meta-Learning.<br/>Chenxing Wang, Fang Zhao<sup>#</sup>, Haichao Zhang, Haiyong Luo<sup>#</sup>, Yanjun Qin, **Yuchen Fang**.<br/>IEEE Transactions on Intelligent Transportation Systems. (T-ITS 2022)
14. NDGCN: Network in Network, Dilate Convolution and Graph Convolutional Networks Based Transportation Mode Recognition.<br/>Yanjun Qin, Haiyong Luo, Fang Zhao<sup>#</sup>, Chenxing Wang, **Yuchen Fang**.<br/>IEEE Transactions on Vehicular Technology. (TVT 2021)

&emsp; &emsp; &emsp; **Note**: <sup>#</sup> and <sup>+</sup> indicate the corresponding author and co-first author

# 📖 Educations

- *2016.09 - 2020.06*, Beijing Forestry University, Bachelor
  - Computer Science and Technology, School of Information
- *2020.09 - 2023.06*, Beijing University of Posts and Telecommunications, Master
  - Software Engineering, School of Computer Science (National Pilot Software Engineering School)
- *2024.09 - present*, University of Electronic Science and Technology of China, Ph.D.
  - Computer Science and Technology, School of Computer Science and Engineering

# 💻 Internships

- *2020.09 - 2022.06*, Institute of Computing Technology, Chinese Academy of Sciences, Beijing, China.
  - Spatio-Temporal Data Mining
  - Mentor: [Haiyong Luo](https://people.ucas.ac.cn/~luohaiyong)
- *2023.07 - 2024.06*, Huawei Cloud Database Innovation Lab, Huawei Technologies Co. Ltd., Chengdu, China.
  - Time Series Analysis
  - Mentor: [Jiandong Xie](https://dblp.org/pid/203/9483.html)

# 🎖 Honors and Awards
- The Outstanding Master Thesis of BUPT, 2023
- National Scholarship, 2022
- First-class People's Scholarship, (2020, 2021, 2022)
- Bronze Medal in the ACM-ICPC Asia-East Continent Final Programming Contest Xi'an Site, 2018

# ⏳ Professional Services

#### PC Member & Reviewer
- 2025: ICLR, CSCW, AISTATS
- 2024: NeurIPS
- 2023: WWW

#### Journal Invited Reviewer
- Data Mining: TKDE, Information Fusion, Information Sciences
- Artificial Intelligence: TNNLS, KBS, EAAI, Neurocomputing
- Interdiscipline: T-ITS
