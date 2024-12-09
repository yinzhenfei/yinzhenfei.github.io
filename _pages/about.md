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

Hi! I’m currently a Ph.D. student at [the University of Sydney](https://www.sydney.edu.au/), working under the guidance of Prof. [Wanli Ouyang](https://wlouyang.github.io/) and Prof. Zhiyong Wang. I’m also a researcher at the [Shanghai AI Lab](https://www.sensetime.com/en), where I collaborate with outstanding researchers like Dr. [Amanda Shao](https://amandajshao.github.io/). Before starting my Ph.D., I was part of [SenseTime](https://www.sensetime.com/en)’s AGI group, working closely with Dr. [Junjie Yan](https://scholar.google.com/citations?user=rEYarG0AAAAJ&hl=zh-CN). I earned my bachelor’s degree from [HUST](https://www.hust.edu.cn/), where I had the honor of being the [ACM-ICPC](https://icpc.global/) team captain, guided by Prof. [Kun Hu](https://scholar.google.com/citations?user=YTQnGJsAAAAJ&hl=en).

<!-- My research interest includes multi-modal foundation models and embodied agents. I have published 10+ papers at the top international AI conferences and journals such as NeurIPS, ICLR, ECCV, and CVPR, with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->


# News
- I'm on the job market in 2025.
- To junior students seeking advice on early academic careers: If you’d like to chat about your career, research ideas, or potential collaborations, feel free to email me to schedule a meeting. I’d be happy to help recommend some opportunities for internships or studies as well.
- *2024.12*: &nbsp; I will be giving a talk at the NeurIPS 2024 Workshop on [Open-World Agents](https://sites.google.com/view/open-world-agents), titled "Building AI Society with Foundation-Model Agents." 
- *2024.11*: Thrilled to announce [OASIS](https://oasis.camel-ai.org/), a simulation platform supporting interactions among over one million LLM agents.
- *2024.07*: I co-organized the ICML 2024 workshop on [Multi-modal Foundation Models Meet Embodied AI (MFM-EAI)](https://icml-mfm-eai.github.io/).
- *2024.07*: I co-organized the ICML 2024 workshop on [Trustworthy Multi-modal Foundation Models and AI Agents (TiFA)](https://icml-mfm-eai.github.io/).
- *2024.05*: I co-hosted the [EgoPlan](https://chenyi99.github.io/ego_plan_challenge/) Challenge to evaluate embodied agents' complex planning capabilities.
- *2023.11*: Excited to release [LAMM](https://openlamm.github.io/), a comprehensive framework for VLM training, evaluation, and applications in embodied agents.
- *2021.11*: Excited to release [Intern](https://github.com/OpenGVLab), a series of multi-modal foundation models focusing on visual representation learning.
- *2020.07*: Achieved Rank 4 of 2265 in Meta's [DFDC](https://www.kaggle.com/competitions/deepfake-detection-challenge) competition, which focused on identifying videos with facial or voice manipulations. Our [solution](https://github.com/yinzhenfei/RobustForensics) is open-sourced.
- *2018.05*: As a student coach, I led a team to the ACM-ICPC World Finals, achieving 31st place.

# Research Highlights

My research is driven by the ambition to develop AI agents capable of operating in both physical and virtual environments. To address this challenge, my work focuses on leveraging generative AI and is centered around two key areas. The first is multi-modal foundation models, encompassing topics such as multi-modal representation learning, architecture design, and multi-sensory alignment. The second is the systematic agents, with an emphasis on practical applications, including but not limited to embodied agents, multi-agent systems, and large-scale simulations.

# Selected Publications 
Topics: Multi-Modal Representation Learning / Embodied Agents / Multi-Agent System

(*: indicates equal contribution; ✉: indicates corresponding; †: indicates project lead)

Visit [Google Scholar](https://scholar.google.com/citations?user=ngPR1dIAAAAJ&hl) for the complete list of publications.

<!-- ------------------------------------------------------------- -->

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS-W 2025</div><img src='/images/MineDreamer_2000x1200_src.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**MineDreamer: Learning to Follow Instructions via Chain-of-Imagination for Simulated-World Control**

Enshen Zhou<sup>*</sup>, Yiran Qin<sup>*</sup>, **Zhenfei Yin**, Yuzhou Huang, Ruimao Zhang<sup>✉</sup>, Lu Sheng<sup>✉</sup>, Yu Qiao, Jing Shao<sup>†</sup>

[NeurIPS Workshop on Open-World Agents](https://sites.google.com/view/open-world-agents), 2024

[**Paper**](https://arxiv.org/pdf/2403.12037) **|** [**Project Page**](https://sites.google.com/view/minedreamer/main) **|** [**Code**](https://github.com/Zhoues/MineDreamer)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2024</div><img src='/images/MP5_2000x1200_src.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**MP5: A Multi-modal Open-ended Embodied System in Minecraft via Active Perception**

Yiran Qin<sup>*</sup>, Enshen Zhou<sup>*</sup>, Qichang Liu<sup>*</sup>, **Zhenfei Yin**, Lu Sheng<sup>✉</sup>, Ruimao Zhang<sup>✉</sup>, Yu Qiao, Jing Shao<sup>†</sup>

[The IEEE/CVF Conference on Computer Vision and Pattern Recognition](https://cvpr.thecvf.com/Conferences/2024), CVPR 2024

[**Paper**](https://arxiv.org/pdf/2312.07472) **|** [**Project Page**](https://iranqin.github.io/MP5.github.io/) **|** [**Code**](https://github.com/IranQin/MP5)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint 2024</div><img src='/images/CH^3EF_2000x1200_src.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Assessment of Multimodal Large Language Models in Alignment with Human Values**

Zhelun Shi<sup>*</sup>, Zhipin Wang<sup>*</sup>, Hongxing Fan<sup>*</sup>, Zaibin Zhang, Lijun Li, Yongting Zhang, **Zhenfei Yin**, Lu Sheng<sup>✉</sup>, Yu Qiao, Jing Shao<sup>✉</sup>

Preprint, 2024

[**Paper**](https://arxiv.org/pdf/2403.17830) **|** [**Project Page**](https://openlamm.github.io/ch3ef/) **|** [**Code**](https://github.com/OpenGVLab/LAMM)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV 2024</div><img src='/images/DQA_2000x1200_src.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Depicting Beyond Scores: Advancing Image Quality Assessment through Multi-modal Language Models**

Zhiyuan You<sup>*</sup>, Zheyuan Li<sup>*</sup>, Jinjin Gu<sup>*</sup>, **Zhenfei Yin**, Tianfan Xue<sup>✉</sup>, Chao Dong<sup>✉</sup>

[The 18th European Conference on Computer Vision](https://eccv.ecva.net/Conferences/2024), ECCV 2024

[**Paper**](https://arxiv.org/pdf/2312.08962) **|** [**Project Page**](https://depictqa.github.io/) **|** [**Code**](https://github.com/XPixelGroup/DepictQA)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2024</div><img src='/images/Octavius_1092x720_src.gif' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Octavius: Mitigating Task Interference in MLLMs via LoRA-MoE**

Zeren Chen<sup>*</sup>, Ziqin Wang<sup>*</sup>, Zhen Wang, Huayang Liu, **Zhenfei Yin<sup>†</sup>**, Si Liu, Lu Sheng<sup>✉</sup>, Wanli Ouyang, Jing Shao<sup>✉</sup>

[The Twelfth International Conference on Learning Representations](https://iclr.cc/Conferences/2024), ICLR 2024

[**Paper**](https://openreview.net/pdf?id=rTDyN8yajn) **|** [**Code**](https://github.com/OpenGVLab/LAMM)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2023</div><img src='/images/LAMM_2000x1200_src.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**LAMM: Language-Assisted Multi-Modal Instruction-Tuning Dataset, Framework, and Benchmark**

**Zhenfei Yin<sup>*</sup>**, Jiong Wang<sup>*</sup>, Jianjian Cao<sup>*</sup>, Zhelun Shi<sup>*</sup>, Dingning Liu, Mukai Li, Xiaoshui Huang, Zhiyong Wang, Lu Sheng, Lei Bai<sup>✉</sup>, Jing Shao<sup>✉</sup>, Wanli Ouyang

[The Thirty-Seventh Annual Conference on Neural Information Processing Systems](https://neurips.cc/Conferences/2023), Datasets and Benchmarks Track, NeurIPS 2023

[**Paper**](https://proceedings.neurips.cc/paper_files/paper/2023/file/548a41b9cac6f50dccf7e63e9e1b1b9b-Paper-Datasets_and_Benchmarks.pdf) <strong><span class='show_paper_citations' data='ngPR1dIAAAAJ:WF5omc3nYNoC'></span></strong> **|** [**Project Page**](https://openlamm.github.io/) **|** [**Code**](https://github.com/OpenGVLab/LAMM)
<!-- - The multi-modal instruction tuning dataset, benchmark evaluation codebase, and training framework have all been open-sourced, along with projects expanding applications on embodied agents. -->
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV 2022</div><img src='/images/OmniBenchmark_2000x1200_src.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Benchmarking Omni-Vision Representation Through the Lens of Visual Realms**

Yuanhan Zhang, **Zhenfei Yin**, Jing Shao<sup>✉</sup>, Ziwei Liu

[European Conference on Computer Vision](https://eccv2022.ecva.net/), 2024

[**Paper**](https://arxiv.org/pdf/2207.07106) **|** [**Project Page**](https://zhangyuanhan-ai.github.io/OmniBenchmark/) **|** [**Code**](https://github.com/ZhangYuanhan-AI/OmniBenchmark)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Tech. Report</div><img src='/images/Bamboo_2000x1200_src.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Bamboo: Building Mega-Scale Vision Dataset Continually with Human-Machine Synergy**

Yuanhan Zhang, Qinghong Sun, Yichun Zhou, Zexin He, **Zhenfei Yin**, Kun Wang, Lu Sheng, Yu Qiao, Jing Shao, Ziwei Liu<sup>✉</sup>

Preprint, 2022

[**Paper**](https://arxiv.org/pdf/2111.08687) **|** [**Code**](https://github.com/ZhangYuanhan-AI/Bamboo)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Tech. Report</div><img src='/images/INTERN_2000x1200_src.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**INTERN: A New Learning Paradigm Towards General Vision**

Jing Shao<sup>*</sup>, Siyu Chen<sup>*</sup>, Yangguang Li<sup>*</sup>, Kun Wang<sup>*</sup>, **Zhenfei Yin<sup>*</sup>**, Yinan He<sup>*</sup>, Jianing Teng<sup>*</sup>, Qinghong Sun<sup>*</sup>, Mengya Gao<sup>*</sup>, Jihao Liu<sup>*</sup>, Gengshi Huang<sup>*</sup>, Guanglu Song, Yichao Wu, Yuming Huang, Fenggang Liu, Huan Peng, Shuo Qin, Chengyu Wang, Yujie Wang, Conghui He, Ding Liang, Yu Liu, Fengwei Yu, Junjie Yan, Dahua Lin, Xiaogang Wang, Yu Qiao<sup>✉</sup>

Technical Report, 2021

[**Paper**](https://arxiv.org/pdf/2111.08687) **|** [**Code**](https://github.com/OpenGVLab)
</div>
</div>

<!-- ------------------------------------------------------------- -->

# Professional Service
- *2024.07*, Workshop Organizer, ICML 2024 workshop on [Multi-modal Foundation Model meets Embodied AI (MFM-EAI)](https://icml-mfm-eai.github.io/)
- *2024.07*, Workshop Organizer, ICML 2024 workshop on [Trustworthy Multi-modal Foundation Models and AI Agents (TiFA)](https://icml-tifa.github.io/)
- *2024 Spring*, Guest Lecture, [ELEC5304](https://www.sydney.edu.au/units/ELEC5304): Intelligent Visual Signal Understanding, USYD
- *2024 Spring*, Teaching Assistant, [COMP 5425](https://www.sydney.edu.au/units/COMP5425): Multimedia Retrieval, USYD
- Peer Review and Program Committee, [ICLR](https://iclr.cc/), [NeurIPS](https://neurips.cc/), [ICML](https://icml.cc/), [AAAI](https://aaai.org/), [ECCV](https://eccv.ecva.net/), [CVPR](https://cvpr.thecvf.com/), and [TPAMI](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=34)

<!-- # 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 📖 Educations
- *2019.06 - 2022.04 (now)*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2015.09 - 2019.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)

# 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China. -->
