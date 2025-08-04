---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<!-- Please also find my publications on [Google Scholar](https://scholar.google.com/citations?user=yXOpclkAAAAJ) ( <a href='https://scholar.google.com/citations?user=yXOpclkAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a> ). -->
†Authors contributed equally to this research.
∗Corresponding Author.

# Papers

- Liangbo Ning†, **Ziran Liang**†, Zhuohang Jiang, Haohao Qu, Yujuan Ding, Wenqi Fan\*, Xiao-yong Wei, Shanru Lin, Hui Liu, Philip S. Yu, Qing Li\*. A Survey of WebAgents: Towards Next-Generation AI Agents for Web Automation with Large Foundation Models [[PDF]](https://liangzrtvjivo.github.io/files/2025.kdd.webagentsurvey.pdf) [[DOI]](https://dl.acm.org/doi/10.1145/3711896.3736555) [[Tutorial]](https://biglemon-ning.github.io/WebAgents/). Proceedings of the 31st ACM SIGKDD Conference on Knowledge Discovery and Data Mining V.2 (KDD), 2025. (CCF-A) 

- Zhuohang Jiang†, Pangjing Wu†, **Ziran Liang**†, Peter Q. Chen†, Xu Yuan†, Ye Jia†, Jiancheng Tu†, Chen Li, Peter H.F. Ng, Qing Li*. HiBench: Benchmarking LLMs capability on hierarchical structure reasoning [[PDF]](https://liangzrtvjivo.github.io/files/2025.kdd.hibench.pdf) [[DOI]](https://dl.acm.org/doi/10.1145/3711896.3737378) [[GitHub]](https://github.com/jzzzzh/HiBench). Proceedings of the 31st ACM SIGKDD Conference on Knowledge Discovery and Data Mining V.2 (KDD), 2025. (CCF-A)  

- **Ziran Liang**, Yuyin Lu, Hegang Chen, Yanghui Rao*. Graph-based relation mining for context-free out-of-vocabulary
word embedding learning [[PDF]](https://liangzrtvjivo.github.io/files/2023.acl-long.grm.pdf) [[DOI]](https://aclanthology.org/2023.acl-long.790/) [[GitHub]](https://github.com/liangzrtvjivo/GRM). Proceedings of the 61st Annual Meeting of the Association for Computational Linguistics (ACL), 2023. (CCF-A) (Oral)

- Zhongyu Zhuang, **Ziran Liang**, Yanghui Rao*, Haoran Xie, Fu Lee Wang. Out-of-vocabulary word embedding learning based on reading comprehension mechanism [J] [[PDF]](https://liangzrtvjivo.github.io/files/2023.nlpj.rcm.pdf) [[DOI]](https://www.sciencedirect.com/science/article/pii/S2949719123000353). Natural Language Processing Journal, 2023.

- Shurui Chen, **Ziran Liang**, Yanghui Rao*. Fine-grained semantic knowledge graph enhanced Chinese OOV word
embedding learning [J] [[PDF]](https://liangzrtvjivo.github.io/files/2023.jsjkx.graph.pdf) [[DOI]](https://www.jsjkx.com/EN/abstract/abstract21404.shtml). Computer Science, 2023. (CCF-B, 中文期刊)

- Yuyin Lu, Xin Cheng, **Ziran Liang**, Yanghui Rao*. Graph-based dynamic word embeddings [[PDF]](https://liangzrtvjivo.github.io/files/2022.ijcai.gdwe.pdf) [[DOI]](https://www.ijcai.org/proceedings/2022/594) [[GitHub]](https://github.com/luyy9apples/GDWE). Proceedings of the 31st International Joint Conference on Artificial Intelligence (IJCAI), 2022. (CCF-A)


# Preprints

- Rui An, Yifeng Zhang, **Ziran Liang**, Wenqi Fan, Yuxuan Liang, Xuequn Shang\*, Qing Li\*. Damba-ST: Domain-Adaptive Mamba for Efficient Urban Spatio-Temporal Prediction [[PDF]](https://liangzrtvjivo.github.io/files/2025.arxiv.damba.pdf) [[arXiv]](https://arxiv.org/abs/2506.18939). 2025. 

- **Ziran Liang**, Rui An, Wenqi Fan*, Yanghui Rao, Yuxuan Liang. iTFKAN: Interpretable Time Series Forecasting with Kolmogorov-Arnold Network [[PDF]](https://liangzrtvjivo.github.io/files/2025.arxiv.itfkan.pdf) [[arXiv]](https://arxiv.org/abs/2504.16432). 2025. 


<!-- # Other Available Works

- Sichuan University - Huawei MindSpore Application Case Implementation Project: Swin Transformer [[GitHub]](https://github.com/EchoChou990919/mindspore_swin_transformer)  
**Yi Zhou**, Xiyao Li, Wanjing Zhang  

- DLMV: A Visual Analytic System for LncRNA-Disease Association Prediction [[Poster]](https://echochou990919.github.io/files/DLMV_Poster.pdf) [[Online Demo]](https://rna-disease.pages.dev/)  
**Yi Zhou**, Jiamin Zhu, Meixuan Wu   -->


<!-- {% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %} -->
