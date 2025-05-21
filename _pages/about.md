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

I am a Ph.D. candidate at [X-Lance Lab](https://x-lance.sjtu.edu.cn/en),
Shanghai Jiao Tong University, under supervision of [Prof. Kai
Yu](https://x-lance.github.io/kaiyu/), majoring in computer science and
technology. Before that, I received my B.S. degree from the Department of
Automation, Tsinghua University in 2020. In the first four months of 2024, I
worked as a research assisstant with [Prof. Tao Yu](https://taoyds.github.io/)
at [XLANG Lab](https://www.xlang.ai/), the University of Hong Kong.

My research interest focuses on text-rich visual UI interaction. Currently, I'm
working on constrution of realistic, complex interaction benchmark for GUI
interaction. I'm also studying how to design smarter GUI agents with
reinforcement learning (RL) and large language models (LLM), or by combining
both.

<!-- My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->


<!-- # 🔥 News
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. -->

# 📝 Publications 

<div class='paper-box'>
    <div class='paper-box-image'>
        <div>
            <div class="badge">NeurIPS 2023</div>
            <img src='images/rememberer.png' alt="Rememberer [NeurIPS 2023]" width="100%">
        </div>
    </div>

<div class='paper-box-text' markdown="1">

[Large Language Models Are Semi-Parametric Reinforcement Learning Agents](https://papers.nips.cc/paper_files/paper/2023/hash/f6b22ac37beb5da61efd4882082c9ecd-Abstract-Conference.html)

**Danyang Zhang**, Lu Chen, Situo Zhang, Hongshen Xu, Zihan Zhao, Kai Yu \\
NeurIPS 2023 | [**Code**](https://github.com/OpenDFM/Rememberer)

<!-- [**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> -->

- We designed Rememberer, a novel evolvable LLM-based agent framework, by
  equipping the LLM with a long-term experience memory, so as to enable the LLM
  to exploit the interaction experiences to improve performance.
- We proposed Reinforcement Learning with Experience Memory (RLEM) to update
  the memory, so that the agent can learn from both success and failure, and
  evolve its capability without fine-tuning LLM parameters.
- Rememberer demonstrates superior performance and robustness on both WebShop
  and WikiHow task set.

</div>
</div>

<div class="paper-box">
    <div class="paper-box-image">
        <div>
            <img src="images/Mobile-Env-Platform.png" alt="Mobile-Env" width="100%">
        </div>
    </div>

<div class="paper-box-text" markdown="1">

[Mobile-Env: An Evaluation Platform and Benchmark for Interactive Agents in LLM Era](https://arxiv.org/abs/2305.08144)

**Danyang Zhang**, Lu Chen, Zihan Zhao, Ruisheng Cao, Kai Yu \\
[**Project**](https://github.com/X-LANCE/Mobile-Env) | [**Task Set**](https://huggingface.co/datasets/zdy023/WikiHow-taskset)

We designed an easily-extensible, adaptable, and close-to-reality interaction
platform based on Android Mobile.

</div>
</div>

<div class="paper-box">
    <div class="paper-box-image">
        <div>
            <div class="badge">NeurIPS 2024</div>
            <img src="images/osworld.png" alt="OSWorld" width="100%">
        </div>
    </div>

<div class="paper-box-text" markdown="1">

[OSWorld: Benchmarking Multimodal Agents for Open-Ended Tasks in Real Computer Environments](https://papers.nips.cc/paper_files/paper/2024/hash/5d413e48f84dc61244b6be550f1cd8f5-Abstract-Datasets_and_Benchmarks_Track.html)

Tianbao Xie, **Danyang Zhang**, Jixuan Chen, Xiaochuan Li, Siheng Zhao, Ruisheng Cao, Toh Jing Hua, Zhoujun Cheng, Dongchan Shin, Fangyu Lei, Yitao Liu, Yiheng Xu, Shuyan Zhou, Silvio Savarese, Caiming Xiong, Victor Zhong, Tao Yu \\
NeurIPS 2024 D&B Track | [**Project**](https://os-world.github.io/) | [**Code**](https://github.com/xlang-ai/OSWorld)

We designed a unified interaction benchmark for real-world desktop tasks.

</div>
</div>

- [Spider2-V: How Far Are Multimodal Agents From Automating Data Science and Engineering Workflows?](https://papers.nips.cc/paper_files/paper/2024/hash/c2f71567cd53464161cab3336e8fc865-Abstract-Datasets_and_Benchmarks_Track.html)<br>
  Ruisheng Cao, Fangyu Lei, Haoyuan Wu, Jixuan Chen, Yeqiao Fu, Hongcheng Gao, Xinzhuang Xiong, Hanchong Zhang, Wenjing Hu, Yuchen Mao, Tianbao Xie, Hongshen Xu, **Danyang Zhang**, Sida I. Wang, Ruoxi Sun, Pengcheng Yin, Caiming Xiong, Ansong Ni, Qian Liu, Victor Zhong, Lu Chen, Kai Yu, Tao Yu.<br>
  NeurIPS 2024 D&B Track | [**Project**](https://spider2-v.github.io/) <span class="show_paper_citations" data="CMHormkAAAAJ:zYLM7Y9cAGgC"></span>
- [WebSRC: A Dataset for Web-Based Structural Reading Comprehension](https://aclanthology.org/2021.emnlp-main.343/)<br>
  Xingyu Chen, Zihan Zhao, Lu Chen, JiaBao Ji, **Danyang Zhang**, Ao Luo, Yuxuan Xiong, Kai Yu<br>
  EMNLP 2021 | [**Project**](https://x-lance.github.io/WebSRC/) <span class="show_paper_citations" data="CMHormkAAAAJ:qjMakFHDy7sC"></span>
- [Rotation-robust Intersection over Union for 3D Object Detection](https://link.springer.com/chapter/10.1007/978-3-030-58565-5_28)<br>
  Yu Zheng, **Danyang Zhang**, Sinan Xie, Jiwen Lu, Jie Zhou<br>
  ECCV 2020 <span class="show_paper_citations" data="CMHormkAAAAJ:u5HHmVD_uO8C"></span>
- [COIN: A Large-scale Dataset for Comprehensive Instructional Video Analysis](https://openaccess.thecvf.com/content_CVPR_2019/html/Tang_COIN_A_Large-Scale_Dataset_for_Comprehensive_Instructional_Video_Analysis_CVPR_2019_paper.html)<br>
  Yansong Tang, Dajun Ding, Yongming Rao, Yu Zheng, **Danyang Zhang**, Lili Zhao, Jiwen Lu, Jie Zhou<br>
  CVPR 2019 | [**Project**](https://coin-dataset.github.io/) <span class="show_paper_citations" data="CMHormkAAAAJ:u-x6o8ySG0sC"></span>
- [MobA: Multifaceted Memory-Enhanced Adaptive Planning for Efficient Mobile Task Automation](https://aclanthology.org/2025.naacl-demo.43/). Zichen Zhu, Hao Tang, Yansi Li, Dingye Liu, Hongshen Xu, Kunyao Lan, **Danyang Zhang**, Yixuan Jiang, Hao Zhou, Chenrun Wang, Situo Zhang, Liangtai Sun, Yixiao Wang, Yuheng Sun, Lu Chen, Kai Yu. NAACL 2025 Demo.
- [ChemDFM-X: Towards Large Multimodal Model for Chemistry](https://link.springer.com/article/10.1007/s11432-024-4243-0). Zihan Zhao, Bo Chen, Jingpiao Li, Lu Chen, Liyang Wen, Pengyu Wang, Zichen Zhu, **Danyang Zhang**, Ziping Wan, Yansi Li, Zhongyang Dai, Xin Chen, Kai Yu. SCIS 2024.
- [Technical Report of MoGUI and MoCon](https://huggingface.co/datasets/OpenDFM/MoCon/blob/main/MoGUI_Paper_v0.1.pdf). Zichen Zhu, Liangtai Sun, **Danyang Zhang**, Ziyuan Li, Guangpeng Li, Lu Chen, Kai Yu.
- [CAM-GUI: A Conversational Assistant on Mobile GUI](https://link.springer.com/chapter/10.1007/978-981-97-0601-3_26). Zichen Zhu, Liangtai Sun, Jingkai Yang, Yifan Peng, Weilin Zou, Ziyuan Li, Wutao Li, Lu Chen, Yingzi Ma, **Danyang Zhang**, Shuai Fan, Kai Yu. NCMMSC 2023.
- [Learning from Temporal Spatial Cubism for Cross-Dataset Skeleton-based Action Recognition](https://dl.acm.org/doi/10.1145/3472722). Yansong Tang, Xingyu Liu, Xumin Yu, **Danyang Zhang**, Jiwen Lu, Jie Zhou. TOMM 2022.
- [Uncertainty-Aware Score Distribution Learning for Action Quality Assessment](https://openaccess.thecvf.com/content_CVPR_2020/html/Tang_Uncertainty-Aware_Score_Distribution_Learning_for_Action_Quality_Assessment_CVPR_2020_paper.html). Yansong Tang, Zanlin Ni, Jiahuan Zhou, **Danyang Zhang**, Jiwen Lu, Ying Wu, Jie Zhou. CVPR 2020.

# 📖 Educations

- *2020.9-(2025.6)*, Ph.D., School of Computer Science, Shanghai Jiao Tong University
- *2016.8-2020.6*, B.S., Department of Automation, Tsinghua University

# 🎖 Honors and Awards

- *2020.9-2025.6*, The 2nd Wu Wenjun AI Honorary Doctoral Progam
- *2020.9-2025.6*, Zhang Xu Scholarship
- *2018.10*, Academic Excellence Scholarship 2017~2018
- *2017.10*, Academic Excellence Scholarship 2016~2017

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)

# 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China. -->
