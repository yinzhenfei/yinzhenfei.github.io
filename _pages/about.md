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

Hi there! I'm currently a postdoctoral researcher at the University of Oxford, supervised by Prof. [Philip Torr](https://eng.ox.ac.uk/people/philip-torr/). I'm also visiting [Le Cong](https://profiles.stanford.edu/186687) and [Mengdi Wang](https://ece.princeton.edu/people/mengdi-wang)'s Lab at Stanford and Princeton. I did my Ph.D. at the University of Sydney, working with Prof. [Wanli Ouyang](https://wlouyang.github.io/) and Prof. [Zhiyong Wang](https://www.sydney.edu.au/engineering/about/our-people/academic-staff/zhiyong-wang.html).  Previously, I was a rising star research fellow at the Shanghai AI Lab selected by Prof. [Xiaoou Tang](https://www.ie.cuhk.edu.hk/faculty/tang-xiaoou-sean/), where I collaborated with outstanding researchers like Dr. [Lei Bai](http://leibai.site/), and Dr. [Amanda Shao](https://amandajshao.github.io/). I also had a wonderful time as a visitor at the Chinese University of Hong Kong. Before starting my Ph.D., I was part of SenseTime’s AGI group, working closely with Dr. [Junjie Yan](https://scholar.google.com/citations?user=rEYarG0AAAAJ&hl=zh-CN). I earned my bachelor’s degree from HUST, where I had the honor of being the [ACM-ICPC](https://icpc.global/) team captain, guided by Prof. [Kun He](https://scholar.google.com/citations?user=YTQnGJsAAAAJ&hl=en).

<!-- My research interest includes multi-modal foundation models and embodied agents. I have published 10+ papers at the top international AI conferences and journals such as NeurIPS, ICLR, ECCV, and CVPR, with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->

<span class='anchor' id='-news'></span>


# News
- I'm on the academic job market in 2026. <a href="CV_Zhenfei%20(Jeremy)%20Yin_2601.pdf" target="_blank">Curriculum Vitae</a>
- To junior students seeking advice on early academic careers: If you’d like to chat about your career, research ideas, or potential collaborations, feel free to email me to schedule a meeting. I’d be happy to recommend some internship or study opportunities as well.
- I’m looking for motivated students to work with me on topics such as agentic AI, multi-agent systems, embodied agents, post-training of multi-modal large language models, and related areas. A strong background in these fields is a plus, but not a must; curiosity, commitment, and a willingness to learn matter most. If you’re interested, please email me with your CV and a short note about your research interests.
- *2026.06*: I am organizing four CVPR 2026 workshops: [2nd Workshop on Multi-Modal Reasoning for Agentic Intelligence (MMRAgI)](https://mmragi.github.io/mmragi/), [ScaleBot: The First Workshop on Scalable Robot Learning Systems](https://scalebot-workshop.github.io/), [Agentic AI for Visual Media](https://agentic-visual-media.insait.ai/), and the [6th Workshop on Adversarial Machine Learning on Computer Vision: Safety of Vision-Language Agents](https://cvpr26-advml.github.io/).
- *2026.04*: I am organizing two ICLR 2026 workshops: [Lifelong Agents: Learning, Aligning, Evolving](https://lifelongagent.github.io/) and the [First Workshop on Efficient Spatial Reasoning](https://sites.google.com/ucsd.edu/efficient-spatial-reasoning/home).
- *2026.04*: I will give an invited talk on "Agents and World Models in Wet Lab" at the ICLR 2026 workshop on [World Models: Understanding, Modelling, and Scaling](https://sites.google.com/view/iclr-2026-workshop-world-model/home).
- *2026.04*: I will participate in a panel discussion at the ICLR 2026 workshop on [AI with Recursive Self-Improvement](https://recursive-workshop.github.io/).
- *2025.10*: We are organizing the [SFE Challenge](https://prismax-team.github.io/sfe-competition-2025/), focusing on advancing the capabilities of foundation models as AI Scientist base models. The competition has just begun, and everyone is warmly invited to participate and contribute innovative ideas!
- *2025.08*: We are organizing a competition on multi-agent embodied intelligence. All relevant details, datasets, and the platform have been released; please visit the [official website](https://mars-eai.github.io/MARS-Challenge-Webpage/) for further information.
- *2025.10*: I organized the ICCV 2025 workshop on [Reliable and Interactable World Models: Geometry, Physics, Interactivity and Real-World Generalization](https://riwm-2025.github.io/RIWM-2025/).
- *2025.10*: I organized the ICCV 2025 workshop on [Multi-Modal Reasoning for Agentic Intelligence](https://agent-intelligence.github.io/agent-intelligence/).
- *2025.09*: Thrilled to release our survey + position paper on [LLM Agent Reinforcement Learning](https://arxiv.org/pdf/2509.02547), where we systematically define and outline the emerging paradigms of LLM RL and LLM Agent RL. Check it out on [Hugging Face](https://huggingface.co/papers/2509.02547), and explore our curated [Awesome paper list](https://github.com/xhyumiracle/Awesome-AgenticLLM-RL-Papers). If you find it helpful, please consider an upvote or a star!
- *2025.07*: Our work [VirSci](https://open-sciencelab.github.io/Social_Science/) was featured in [Nature Feature](https://www.nature.com/articles/d41586-025-02028-5) [[PDF](https://yinzhenfei.github.io/Nature%20Feature%20-%20d41586-025-02028-5.pdf)]! The concept of Co-AI Scientists is gaining wide attention.
- *2025.07*: Our paper “[Revealing the Risks of Utilizing Large Language Models in Scholarly Peer Review](https://rui-ye.github.io/BadLLMReviewer)” was covered by [The Washington Post](https://www.washingtonpost.com/nation/2025/07/17/ai-university-research-peer-review/) [[PDF](https://yinzhenfei.github.io/washingtonpost.com-Researchers%20are%20cheating%20peer%20review%20by%20hiding%20AI%20prompts%20in%20papers.pdf)]. The piece discusses the potential impact of LLM-based reviewing on the future of the peer review ecosystem.
- *2025.07*: Honored to be selected as a [WAIC 2025 Yunfan Award Rising Star](https://www.thegaiaa.org/en/awards_mrzx#mrzx) nominee, recognizing emerging researchers in the field of AI.
- *2025.07*: I organized the ICML 2025 workshop on [Multi-Agent Systems in the Era of Foundation Models: Opportunities, Challenges, and Futures (MAS-2025)](https://mas-2025.github.io/MAS-2025/), which was one of the most well-attended events of the entire conference!
- 2025.04: Thrilled to release [MARS (Multi-Agent Robotics System)](https://mars-eai.github.io/MARS-System/), an open-source framework focusing on embodied intelligence in multi-agent settings. MARS aims to support almost all approaches based on foundation model embodied agents, spatial intelligence, and compositional intelligence (generalization and constraints). You're welcome to follow and contribute!
- 2025.04: Excited to announce [MASWorks/MASLab](https://github.com/MASWorks/MASLab) (a nod to MathWorks/Matlab!), an open-source framework dedicated to multi-agent systems based on LLM agents, providing all essential components for MAS research, datasets, benchmarks, codebases, and more. We’ll also be releasing a series of new research projects based on this platform. Join us in building the community!
- *2024.12*: I gave a talk at the NeurIPS 2024 Workshop on [Open-World Agents](https://sites.google.com/view/open-world-agents), titled "Building AI Society with Foundation-Model Agents." 
- *2024.11*: Thrilled to announce [OASIS](https://oasis.camel-ai.org/), a simulation platform supporting interactions among over one million LLM agents.
- *2024.07*: I organized the ICML 2024 workshop on [Multi-modal Foundation Models Meet Embodied AI (MFM-EAI)](https://icml-mfm-eai.github.io/).
- *2024.07*: I organized the ICML 2024 workshop on [Trustworthy Multi-modal Foundation Models and AI Agents (TiFA)](https://icml-mfm-eai.github.io/).
- *2024.05*: I co-hosted the [EgoPlan](https://chenyi99.github.io/ego_plan_challenge/) Challenge to evaluate embodied agents' complex planning capabilities.
- *2023.11*: Excited to release [LAMM](https://openlamm.github.io/), a comprehensive framework for VLM training, evaluation, and applications in embodied agents.
- *2023.08*: I began organizing a weekly academic talk series, [Echo AI Talk](https://www.echoaitalk.com/), inviting young researchers from around the world who are well-known for their work in generative AI, foundation models, and AI agents. Everyone is welcome to join!
- *2021.11*: Excited to release [Intern](https://github.com/OpenGVLab), a series of multi-modal foundation models focusing on visual representation learning.
- *2020.07*: Achieved Rank 4 of 2265 in Meta's [DFDC](https://www.kaggle.com/competitions/deepfake-detection-challenge) competition, which focused on identifying videos with facial or voice manipulations. Our [solution](https://github.com/yinzhenfei/RobustForensics) is open-sourced.
- *2018.05*: As a student coach, I led a team to the ACM-ICPC World Finals, [achieving 31st place](/Scoreboard.html).

# Research Highlights

My research aims to develop general-purpose AI agents capable of operating in both physical and virtual environments. My work primarily focuses on foundation model post-training, multi-agent systems, self-evolving agents, and embodied agents and robotics, with the goal of improving the autonomy, adaptability, and coordination capabilities of intelligent systems in complex environments.

A central application of this research is the development of a General AI Scientist for scientific discovery across both natural sciences and social sciences. These systems leverage AI agents and embodied robotic agents to autonomously explore research problems, generate hypotheses, conduct simulations or experiments, and discover new knowledge. Through this framework, my research aims to uncover new scaling laws of agent-based intelligence and automated scientific discovery in large-scale interactive environments.

<span class='anchor' id='-publications'></span>

# Selected Publications 
Topics: Foundation Model Agents / Robotics / AI Scientists

(*: indicates equal contribution; ‡: indicates corresponding; †: indicates project lead)

Visit [Google Scholar](https://scholar.google.com/citations?user=ngPR1dIAAAAJ&hl) for the complete list of publications.

<!-- ===================== 2026 Papers ===================== -->

<!-- ------------------------------------------------------------- -->

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint</div><img src='images/placeholder_2000x1200_src.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**SciAgentGym: Benchmarking Multi-Step Scientific Tool-use in LLM Agents**

Yujiong Shen, Yajie Yang, Zhiheng Xi, Binze Hu, Huayu Sha, Jiazheng Zhang, Qiyuan Peng, Junlin Shang, Jixuan Huang, Yutao Fan, Jingqi Tong, Shihan Dou, Ming Zhang, Lei Bai, **Zhenfei Yin<sup>‡</sup>**, Tao Gui, Xingjun Ma, Qi Zhang, Xuanjing Huang, Yu-Gang Jiang

Preprint 2026

[**PDF**](https://arxiv.org/abs/2602.12984)

</div>
</div>

<!-- ------------------------------------------------------------- -->

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint</div><img src='images/placeholder_2000x1200_src.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Charting Empirical Laws for LLM Fine-Tuning in Scientific Multi-Discipline Learning**

Lintao Wang, Zhuqiang Lu, Yilin Zhu, Kun Hu, **Zhenfei Yin<sup>‡</sup>**, Shixiang Tang, Zhiyong Wang, Wanli Ouyang, Xinzhu Ma

Preprint 2026

[**PDF**](https://arxiv.org/abs/2602.11215)

</div>
</div>

<!-- ------------------------------------------------------------- -->

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint</div><img src='images/placeholder_2000x1200_src.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**TodoEvolve: Learning to Architect Agent Planning Systems**

Jiaxi Liu, Yanzuo Jiang, Guibin Zhang, Zihan Zhang, Heng Chang, **Zhenfei Yin<sup>‡</sup>**, Qibing Ren, Junchi Yan

Preprint 2026

[**PDF**](https://arxiv.org/abs/2602.07839)

</div>
</div>

<!-- ------------------------------------------------------------- -->

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint</div><img src='images/placeholder_2000x1200_src.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**LatentChem: From Textual CoT to Latent Thinking in Chemical Reasoning**

Xinwu Ye, Yicheng Mao, Jia Zhang, Yimeng Liu, Li Hao, Fang Wu, Zhiwei Li, Yuxuan Liao, Zehong Wang, Zhiyuan Liu, **Zhenfei Yin<sup>‡</sup>**, Li Yuan, Philip Torr, Huan Sun, Xiangxiang Zeng, Mengdi Wang, Le Cong, Shenghua Gao, Xiangru Tang

Preprint 2026

[**PDF**](https://arxiv.org/abs/2602.07075)

</div>
</div>

<!-- ------------------------------------------------------------- -->

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2026 Findings</div><img src='images/placeholder_2000x1200_src.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Behavioral Consistency Validation for LLM Agents: An Analysis of Trading-Style Switching through Stock-Market Simulation**

Zeping Li, Guancheng Wan, Keyang Chen, Yu Chen, Yiwen Zhao, Philip Torr, Guangnan Ye, **Zhenfei Yin<sup>‡</sup>**, Hongfeng Chai

[Findings of the Association for Computational Linguistics](https://2026.aclweb.org/), ACL 2026

[**PDF**](https://arxiv.org/abs/2602.07023)

</div>
</div>

<!-- ------------------------------------------------------------- -->

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint</div><img src='images/placeholder_2000x1200_src.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">


**Vision-deepresearch benchmark: Rethinking visual and textual search for multimodal large language models**

Yu Zeng, Wenxuan Huang, Zhen Fang, Shuang Chen, Yufan Shen, Yishuo Cai, Xiaoman Wang, **Zhenfei Yin**, Lin Chen, Zehui Chen, Shiting Huang, Yiming Zhao, Xu Tang, Yao Hu, Philip Torr, Wanli Ouyang, Shaosheng Cao

Preprint 2026

[**PDF**](https://arxiv.org/abs/2602.02185)

</div>
</div>

<!-- ------------------------------------------------------------- -->

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2026</div><img src='images/placeholder_2000x1200_src.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">


**Rethinking the Role of Entropy in Optimizing Tool-Use Behaviors for Large Language Model Agents**

Zeping Li, Hongru Wang, Yiwen Zhao, Guanhua Chen, Yixia Li, Keyang Chen, Yixin Cao, Guangnan Ye, Hongfeng Chai, **Zhenfei Yin<sup>‡</sup>**

[The 64th Annual Meeting of the Association for Computational Linguistics](https://2026.aclweb.org/), Main Conference, ACL 2026

[**PDF**](https://arxiv.org/abs/2602.02050)

</div>
</div>

<!-- ------------------------------------------------------------- -->

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint</div><img src='images/placeholder_2000x1200_src.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Why Reasoning Fails to Plan: A Planning-Centric Analysis of Long-Horizon Decision Making in LLM Agents**

Zehong Wang, Fang Wu, Hongru Wang, Xiangru Tang, Bolian Li, **Zhenfei Yin**, Yijun Ma, Yiyang Li, Weixiang Sun, Xiusi Chen, Yanfang Ye

Preprint 2026

[**PDF**](https://arxiv.org/abs/2601.22311)

</div>
</div>

<!-- ------------------------------------------------------------- -->

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint</div><img src='images/placeholder_2000x1200_src.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Vision-deepresearch: Incentivizing deepresearch capability in multimodal large language models**

Wenxuan Huang, Yu Zeng, Qiuchen Wang, Zhen Fang, Shaosheng Cao, Zheng Chu, Qingyu Yin, Shuang Chen, **Zhenfei Yin**, Lin Chen, Zehui Chen, Xu Tang, Yao Hu, Philip Torr, Feng Zhao, Wanli Ouyang

Preprint 2026

[**PDF**](https://arxiv.org/abs/2601.22060)

</div>
</div>

<!-- ------------------------------------------------------------- -->

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint</div><img src='images/placeholder_2000x1200_src.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**TouchGuide: Inference-Time Steering of Visuomotor Policies via Touch Guidance**

Zhemeng Zhang, Jiahua Ma, Xincheng Yang, Xin Wen, Yuzhi Zhang, Boyan Li, Yiran Qin, Jin Liu, Can Zhao, Li Kang, Haoqin Hong, **Zhenfei Yin**, Philip Torr, Hao Su, Ruimao Zhang, Daolin Ma

Preprint 2026

[**PDF**](https://arxiv.org/abs/2601.20239)

</div>
</div>

<!-- ------------------------------------------------------------- -->

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Tech. Report</div><img src='images/placeholder_2000x1200_src.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Advances and Innovations in the Multi-Agent Robotic System (MARS) Challenge**

Li Kang, Heng Zhou, Xiufeng Song, Rui Li, Bruno NY Chen, Ziye Wang, Ximeng Meng, Stone Tao, Yiran Qin, Xiaohong Liu, Ruimao Zhang, Lei Bai, Yilun Du, Hao Su, Philip Torr, **Zhenfei Yin<sup>‡</sup>**

Technical Report, 2026

[**PDF**](https://arxiv.org/abs/2601.18733)

</div>
</div>

<!-- ------------------------------------------------------------- -->

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint</div><img src='images/placeholder_2000x1200_src.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Think3D: Thinking with Space for Spatial Reasoning**

Zaibin Zhang, Yuhan Wu, Lianjie Jia, Yifan Wang, Zhongbo Zhang, Yijiang Li, Binghao Ran, Fuxi Zhang, Zhuohan Sun, **Zhenfei Yin<sup>‡</sup>**, Lijun Wang, Huchuan Lu

Preprint 2026

[**PDF**](https://arxiv.org/abs/2601.13029)

</div>
</div>

<!-- ===================== 2025 Papers ===================== -->

<!-- ------------------------------------------------------------- -->

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2026 Workshop</div><img src='images/placeholder_2000x1200_src.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**RoboSafe: Safeguarding Embodied Agents via Executable Safety Logic**

Le Wang, Zonghao Ying, Xiao Yang, Quanchen Zou, **Zhenfei Yin**, Tianlin Li, Jian Yang, Yaodong Yang, Aishan Liu, Xianglong Liu

[The First Workshop on Efficient Spatial Reasoning](https://sites.google.com/ucsd.edu/efficient-spatial-reasoning/home), ICLR 2026, Oral Presentation, Best Paper Award

[**PDF**](https://arxiv.org/abs/2512.21220)

</div>
</div>

<!-- ------------------------------------------------------------- -->

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2026</div><img src='images/placeholder_2000x1200_src.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**From Word to World: Can Large Language Models be Implicit Text-based World Models?**

Yixia Li, Hongru Wang, Jiahao Qiu, **Zhenfei Yin**, Dongdong Zhang, Cheng Qian, Zeping Li, Pony Ma, Guanhua Chen, Heng Ji, Mengdi Wang

[The 64th Annual Meeting of the Association for Computational Linguistics](https://2026.aclweb.org/), Main Conference, ACL 2026

[**PDF**](https://arxiv.org/abs/2512.18832)

</div>
</div>

<!-- ------------------------------------------------------------- -->

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint</div><img src='images/placeholder_2000x1200_src.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Memory in the Age of AI Agents**

Yuyang Hu<sup>*</sup>, Shichun Liu<sup>*</sup>, Yanwei Yue<sup>*</sup>, Guibin Zhang<sup>*</sup>, Boyang Liu, Fangyi Zhu, Jiahang Lin, Honglin Guo, Shihan Dou, Zhiheng Xi, Senjie Jin, Jiejun Tan, Yanbin Yin, Jiongnan Liu, Zeyu Zhang, Zhongxiang Sun, Yutao Zhu, Hao Sun, Boci Peng, Zhenrong Cheng, Xuanbo Fan, Jiaxin Guo, Xinlei Yu, Zhenhong Zhou, Zewen Hu, Jiahao Huo, Junhao Wang, Yuwei Niu, Yu Wang, **Zhenfei Yin**, Xiaobin Hu, Yue Liao, Qiankun Li, Kun Wang, Wangchunshu Zhou, Yixin Liu, Dawei Cheng, Qi Zhang, Tao Gui, Shirui Pan, Yan Zhang, Philip Torr, Zhicheng Dou, Ji-Rong Wen, Xuanjing Huang, Yu-Gang Jiang, Shuicheng Yan

Preprint 2025

[**PDF**](https://arxiv.org/abs/2512.13564)
</div>
</div>

<!-- ------------------------------------------------------------- -->

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint</div><img src='images/placeholder_2000x1200_src.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**LiveSearchBench: An Automatically Constructed Benchmark for Retrieval and Reasoning over Dynamic Knowledge**

Heng Zhou<sup>*</sup>, Ao Yu<sup>*</sup>, Yuchen Fan<sup>*</sup>, Jianing Shi, Li Kang, Hejia Geng, Yongting Zhang, Yutao Fan, Yuhao Wu, Tiancheng He, Yiran Qin, Lei Bai<sup>‡</sup>, **Zhenfei Yin<sup>‡</sup>**

Preprint 2025

[**PDF**](https://arxiv.org/abs/2511.01409)
</div>
</div>

<!-- ------------------------------------------------------------- -->

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2026</div><img src='images/SecureWebArena_2000x1200_src.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**SecureWebArena: A Holistic Security Evaluation Benchmark for LVLM-based Web Agents**

Zonghao Ying<sup>*</sup>, Yangguang Shao<sup>*</sup>, Jianle Gan, Gan Xu, Junjie Shen, Wenxin Zhang, Quanchen Zou, Junzheng Shi, **Zhenfei Yin**, Mingchuan Zhang, Aishan Liu, Xianglong Liu

[Findings of the Association for Computational Linguistics](https://2026.aclweb.org/), ACL 2026

[**PDF**](https://arxiv.org/abs/2510.10073)
</div>
</div>

<!-- ------------------------------------------------------------- -->

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2026</div><img src='images/CoMAS_2000x1200_src.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**CoMAS: Co-Evolving Multi-Agent Systems via Interaction Rewards**

Xiangyuan Xue, Yifan Zhou, Guibin Zhang, Zaibin Zhang, Yijiang Li, Chen Zhang, **Zhenfei Yin<sup>‡</sup>**, Philip Torr, Wanli Ouyang, Lei Bai<sup>‡</sup>

[The Fourteenth International Conference on Learning Representations](https://iclr.cc/Conferences/2026), ICLR 2026

[**PDF**](https://arxiv.org/abs/2510.08529)
</div>
</div>

<!-- ------------------------------------------------------------- -->

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint</div><img src='images/A-MemGuard_2000x1200_src.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**A-MemGuard: A Proactive Defense Framework for LLM-Based Agent Memory**

Qianshan Wei<sup>*</sup>, Tengchao Yang<sup>*</sup>, Yaochen Wang<sup>*</sup>, Xinfeng Li<sup>‡</sup>, Lijun Li, **Zhenfei Yin**, Yi Zhan, Thorsten Holz, Zhiqiang Lin, XiaoFeng Wang

Preprint 2025

[**PDF**](https://arxiv.org/abs/2510.02373)
</div>
</div>

<!-- ------------------------------------------------------------- -->

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint</div><img src='images/LatentEvolve_2000x1200_src.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**LatentEvolve: Self-Evolving Test-Time Scaling in Latent Space**

Guibin Zhang, Fanci Meng, Guancheng Wan, Zherui Li, Kun Wang, **Zhenfei Yin**, Lei Bai, Shuicheng Yan

Preprint 2025

[**PDF**](https://arxiv.org/abs/2509.24771)
</div>
</div>

<!-- ------------------------------------------------------------- -->

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2026</div><img src='images/ScalingRL_2000x1200_src.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Scaling Behaviors of LLM Reinforcement Learning Post-Training: An Empirical Study in Mathematical Reasoning**

Zelin Tan, Hejia Geng, Mulei Zhang, Xiaohang Yu, Guancheng Wan, Yifan Zhou, Qiang He, Xiangyuan Xue, Heng Zhou, Yutao Fan, Zhongzhi Li, Zaibin Zhang, Guibin Zhang, Chen Zhang<sup>‡</sup>, **Zhenfei Yin<sup>‡</sup>**, Lei Bai

[The 64th Annual Meeting of the Association for Computational Linguistics](https://2026.aclweb.org/), Main Conference, ACL 2026, Oral Presentation

[**PDF**](https://arxiv.org/abs/2509.25300)
</div>
</div>

<!-- ------------------------------------------------------------- -->

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint</div><img src='images/DLAMAS_2000x1200_src.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Diagnose, Localize, Align: A Full-Stack Framework for Reliable LLM Multi-Agent Systems under Instruction Conflicts**

Guancheng Wan<sup>*</sup>, Leixin Sun<sup>*</sup>, Longxu Dou, Zitong Shi, Fang Wu, Eric Hanchen Jiang, Wenke Huang, Guibin Zhang, Hejia Geng, Xiangru Tang, **Zhenfei Yin<sup>‡</sup>**, Yizhou Sun, Wei Wang

Preprint 2025

[**PDF**](https://arxiv.org/abs/2509.23188)

</div>
</div>

<!-- ------------------------------------------------------------- -->

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2026</div><img src='images/Eigen-1_2000x1200_src.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Eigen-Agent: Adaptive Multi-Agent Scientific Reasoning with Monitor-Based RAG**

Xiangru Tang<sup>*</sup>, Wanghan Xu<sup>*</sup>, Yujie Wang<sup>*</sup>, Zijie Guo<sup>*</sup>, Daniel Shao, Jiapeng Chen, Cixuan Zhang, Ziyi Wang, Lixin Zhang, Guancheng Wan, Wenlong Zhang, Lei Bai, **Zhenfei Yin<sup>‡</sup>**, Philip Torr, Hanrui Wang, Di Jin

[The Fourteenth International Conference on Learning Representations](https://iclr.cc/Conferences/2026), ICLR 2026

[**PDF**](https://arxiv.org/abs/2509.21193)
</div>
</div>

<!-- ------------------------------------------------------------- -->

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2026</div><img src='images/IRG_2000x1200_src.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Interleaving Reasoning for Better Text-to-Image Generation**

Wenxuan Huang, Shuang Chen, Zheyong Xie, Shaosheng Cao<sup>‡</sup>, Shixiang Tang, Yufan Shen, Qingyu Yin, Wenbo Hu, Xiaoman Wang, Yuntian Tang, Junbo Qiao, Yue Guo, Yao Hu, **Zhenfei Yin<sup>‡</sup>**, Philip Torr, Yu Cheng, Wanli Ouyang, Shaohui Lin<sup>‡</sup>

[The Fourteenth International Conference on Learning Representations](https://iclr.cc/Conferences/2026), ICLR 2026

[**PDF**](https://arxiv.org/abs/2509.06945)
</div>
</div>

<!-- ------------------------------------------------------------- -->

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TMLR</div><img src='images/AgenticRL_2000x1200_src.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**The Landscape of Agentic Reinforcement Learning for LLMs: A Survey**

Guibin Zhang<sup>*</sup>, Hejia Geng<sup>*</sup>, Xiaohang Yu<sup>*</sup>, **Zhenfei Yin<sup>‡</sup>**, Zaibin Zhang, Zelin Tan, Heng Zhou, Zhongzhi Li, Xiangyuan Xue, Yijiang Li, Yifan Zhou, Yang Chen, Chen Zhang, Yutao Fan, Zihu Wang, Songtao Huang, Yue Liao, Hongru Wang, Mengyue Yang, Heng Ji, Michael Littman, Jun Wang, Shuicheng Yan, Philip Torr, Lei Bai<sup>‡</sup>

[Transactions on Machine Learning Research](https://jmlr.org/tmlr/), TMLR 2026

[**PDF**](https://arxiv.org/abs/2509.02547)
</div>
</div>

<!-- ------------------------------------------------------------- -->

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2025</div><img src='images/BMMR_2000x1200_src.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**BMMR: A Large-Scale Bilingual Multimodal Multi-Discipline Reasoning Dataset**

Zhiheng Xi<sup>*</sup>, Guanyu Li<sup>*</sup>, Yutao Fan<sup>*</sup>, Honglin Guo<sup>*</sup>, Yufang Liu, Xiaoran Fan, Jiaqi Liu, Jingchao Ding, Wangmeng Zuo, **Zhenfei Yin<sup>‡</sup>**, Lei Bai, Tao Ji, Tao Gui<sup>‡</sup>, Qi Zhang, Philip Torr, Xuanjing Huang

[The Thirty-Ninth Annual Conference on Neural Information Processing Systems](https://neurips.cc/Conferences/2025), Datasets and Benchmarks Track, NeurIPS 2025

[**PDF**](https://arxiv.org/abs/2507.03483) **|** [**Project Page**](https://bmmr.pages.dev/) **|** [**Code**](https://github.com/WooooDyy/BMMR/)
</div>
</div>

<!-- ------------------------------------------------------------- -->

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint</div><img src='images/VeriGUI_2000x1200_src.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**VeriGUI: Verifiable Long-Chain GUI Dataset**

Shunyu Liu<sup>*</sup>, Minghao Liu<sup>*</sup>, Huichi Zhou, Zhenyu Cui, Yang Zhou, Yuhao Zhou, Wendong Fan, Ge Zhang, Jiajun Shi, Weihao Xuan, Jiaxing Huang, Shuang Luo, Fang Wu, Heli Qi, Qingcheng Zeng, Ziqi Ren, Jialiang Gao, Jindi Lv, Junjie Wang, Aosong Feng, Heng Zhou, Wangchunshu Zhou, **Zhenfei Yin**, Wenlong Zhang, Guohao Li, Wenhao Yu, Irene Li, Lei Ma, Lei Bai, Qunshu Lin, Mingli Song, Dacheng Tao

Preprint 2025

[**PDF**](https://arxiv.org/abs/2508.04026) **|** [**Code**](https://github.com/VeriGUI-Team/VeriGUI)
</div>
</div>


<!-- ------------------------------------------------------------- -->

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2025</div><img src='images/VIKI-R_2000x1200_src.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**VIKI-R: Coordinating Embodied Multi-Agent Cooperation via Reinforcement Learning**

Li Kang<sup>*</sup>, Xiufeng Song<sup>*</sup>, Heng Zhou<sup>*</sup>, Yiran Qin<sup>‡</sup>, Jie Yang, Xiaohong Liu, Philip Torr, Lei Bai<sup>‡</sup>, **Zhenfei Yin<sup>‡</sup>**

[The Thirty-Ninth Annual Conference on Neural Information Processing Systems](https://neurips.cc/Conferences/2025), Datasets and Benchmarks Track, NeurIPS 2025

[**PDF**](https://arxiv.org/abs/2506.09049)
</div>
</div>

<!-- ------------------------------------------------------------- -->

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2025</div><img src='images/LabUtopia_2000x1200_src.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**LabUtopia: High-Fidelity Simulation and Hierarchical Benchmark for Scientific Embodied Agents**

Rui Li<sup>*</sup>, Zixuan Hu<sup>*</sup>, Wenxi Qu<sup>*</sup>, Jinouwen Zhang, **Zhenfei Yin**, Sha Zhang, Xuantuo Huang, Hanqing Wang, Tai Wang, Jiangmiao Pang, Wanli Ouyang, Lei Bai, Wangmeng Zuo, Ling-Yu Duan, Dongzhan Zhou<sup>‡</sup>, Shixiang Tang<sup>‡</sup>

[The Thirty-Ninth Annual Conference on Neural Information Processing Systems](https://neurips.cc/Conferences/2025), Datasets and Benchmarks Track, NeurIPS 2025

[**PDF**](https://arxiv.org/abs/2505.22634)
</div>
</div>

<!-- ------------------------------------------------------------- -->

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint</div><img src='images/X-MAS_2000x1200_src.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**X-MAS: Towards Building Multi-Agent Systems with Heterogeneous LLMs**

Rui Ye<sup>*</sup>, Xiangrui Liu<sup>*</sup>, Qimin Wu, Xianghe Pang, **Zhenfei Yin**, Lei Bai, Siheng Chen<sup>‡</sup>

Preprint 2025

[**PDF**](https://arxiv.org/abs/2505.16997)
</div>
</div>

<!-- ------------------------------------------------------------- -->

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint</div><img src='images/MASLab_2000x1200_src.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**MASLab: A Unified and Comprehensive Codebase for LLM-based Multi-Agent Systems**

Rui Ye, Keduan Huang, Qimin Wu, Yuzhu Cai, Tian Jin, Xianghe Pang, Xiangrui Liu, Jiaqi Su, Chen Qian, Bohan Tang, Kaiqu Liang, Jiaao Chen, Yue Hu, **Zhenfei Yin**, Rongye Shi, Bo An, Yang Gao, Wenjun Wu, Lei Bai<sup>‡</sup>, Siheng Chen<sup>‡</sup>

Preprint 2025

[**PDF**](https://arxiv.org/abs/2505.16988)
</div>
</div>

<!-- ------------------------------------------------------------- -->

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint</div><img src='images/PositionAISoS_2000x1200_src.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**AI-Driven Automation Can Become the Foundation of Next-Era Science of Science Research**

Renqi Chen<sup>*</sup>, Haoyang Su<sup>*</sup>, Shixiang Tang, **Zhenfei Yin**, Qi Wu, Hui Li, Ye Sun, Nanqing Dong<sup>‡</sup>, Wanli Ouyang, Philip Torr

Preprint 2025

[**PDF**](https://arxiv.org/abs/2505.12039)
</div>
</div>

<!-- ------------------------------------------------------------- -->

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2025</div><img src='images/RoboFactory_2000x1200_src.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**RoboFactory: Exploring Embodied Agent Collaboration with Compositional Constraints**

Yiran Qin<sup>*</sup>, Li Kang<sup>*</sup>, Xiufeng Song<sup>*</sup>, **Zhenfei Yin<sup>‡</sup>**, Xiaohong Liu, Xihui Liu, Ruimao Zhang<sup>‡</sup>, Lei Bai<sup>‡</sup>

[International Conference on Computer Vision](https://iccv.thecvf.com/Conferences/2025), ICCV 2025

[**PDF**](https://arxiv.org/abs/2503.16408) **|** [**Project Page**](https://iranqin.github.io/robofactory/)
</div>
</div>

<!-- ------------------------------------------------------------- -->

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">EMNLP 2025</div><img src='images/ReSo_2000x1200_src.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**ReSo: A Reward-driven Self-organizing LLM-based Multi-Agent System for Reasoning Tasks**

Heng Zhou<sup>*</sup>, Hejia Geng<sup>*</sup>, Xiangyuan Xue, Li Kang, Yiran Qin, Zhiyong Wang, **Zhenfei Yin<sup>‡</sup>**, Lei Bai<sup>‡</sup>

[Empirical Methods in Natural Language Processing](https://2025.emnlp.org/), EMNLP 2025, Oral Presentation, SAC Highlight Award, Outstanding Paper Candidates(Top 1%)

[**PDF**](https://arxiv.org/abs/2503.02390) **|** [**Code**](https://github.com/hengzzzhou/ReSo)
</div>
</div>
<!-- ------------------------------------------------------------- -->

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2025</div><img src='images/VLIPP_2000x1200_src.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**VLIPP: Towards Physically Plausible Video Generation with Vision and Language Informed Physical Prior**

Xindi Yang, Baolu Li, Yiming Zhang, **Zhenfei Yin<sup>‡</sup>**, Lei Bai<sup>‡</sup>, Liqian Ma, Zhiyong Wang, Jianfei Cai, Tien-Tsin Wong, Huchuan Lu, Xu Jia<sup>‡</sup>

[International Conference on Computer Vision](https://iccv.thecvf.com/Conferences/2025), ICCV 2025

[**PDF**](https://arxiv.org/abs/2503.23368) **|** [**Project Page**](https://madaoer.github.io/projects/physically_plausible_video_generation/)
</div>
</div>

<!-- ------------------------------------------------------------- -->

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML 2025</div><img src='images/masgpt_2000x1200_src.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**MAS-GPT: Training LLMs to Build LLM-based Multi-Agent Systems**

Rui Ye, Shuo Tang, Rui Ge, Yaxin Du, **Zhenfei Yin**, Siheng Chen<sup>‡</sup>, Jing Shao<sup>‡</sup>

[Forty-Second International Conference on Machine Learning](https://icml.cc/), ICML 2025

[ICLR 2025 Workshop on Reasoning and Planning for Large Language Models](https://workshop-llm-reasoning-planning.github.io/), 2025

[**PDF**](https://arxiv.org/abs/2503.03686)
</div>
</div>

<!-- ------------------------------------------------------------- -->

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint</div><img src='images/BadLLMReview_2000x1200_src.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Are We There Yet? Revealing the Risks of Utilizing Large Language Models in Scholarly Peer Review**

Rui Ye<sup>*</sup>, Xianghe Pang<sup>*</sup>, Jingyi Chai, Jiaao Chen, **Zhenfei Yin**, Zhen Xiang, Xiaowen Dong, Jing Shao, Siheng Chen<sup>‡</sup>

Preprint, 2024

[**PDF**](https://arxiv.org/abs/2412.01708) **|** [**Project Page**](https://rui-ye.github.io/BadLLMReviewer)
</div>
</div>

<!-- ------------------------------------------------------------- -->

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2025</div><img src='images/B-VLLM_2000x1200_src.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**B-VLLM: A Vision Large Language Model with Balanced Spatio-Temporal Tokens**

Zhuqiang Lu, **Zhenfei Yin<sup>‡</sup>**, Mengwei He, Zhihui Wang, Zicheng Liu, Zhiyong Wang, Kun Hu<sup>‡</sup>

[International Conference on Computer Vision](https://iccv.thecvf.com/Conferences/2025), ICCV 2025

[**PDF**](https://arxiv.org/abs/2412.09919) **|** [**Code**](https://github.com/zhuqiangLu/B-VLLM)
</div>
</div>

<!-- ------------------------------------------------------------- -->

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS-W 2024</div><img src='/images/oasis_1134x680_src.PNG' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**OASIS: Open Agents Social Interaction Simulations on One Million Agents**

Ziyi Yang<sup>*</sup>, Zaibin Zhang<sup>*</sup>, Zirui Zheng, Yuxian Jiang, Ziyue Gan, Zhiyu Wang, Zijian Ling, Jinsong Chen, Martz Ma, Bowen Dong, Prateek Gupta, Shuyue Hu, **Zhenfei Yin<sup>‡</sup>**, Guohao Li<sup>‡</sup>, Xu Jia, Lijun Wang, Bernard Ghanem, Huchuan Lu, Wanli Ouyang, Yu Qiao, Philip Torr, Jing Shao<sup>‡</sup>

[NeurIPS Workshop on Open-World Agents](https://sites.google.com/view/open-world-agents), 2024

[**PDF**](https://arxiv.org/abs/2411.11581) **|** [**Project Page**](https://oasis.camel-ai.org/) **|** [**Code**](https://github.com/camel-ai/oasis)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML 2025</div><img src='/images/worldsimbench_1134x680_src.PNG' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**WorldSimBench: Towards Video Generation Models as World Simulators**

Yiran Qin<sup>*</sup>, Zhelun Shi<sup>*</sup>, Jiwen Yu, Xijun Wang, Enshen Zhou, Lijun Li, **Zhenfei Yin<sup>†</sup>**, Xihui Liu, Lu Sheng, Jing Shao<sup>‡</sup>, Lei Bai<sup>‡</sup>, Wanli Ouyang, Ruimao Zhang<sup>‡</sup>

[Forty-Second International Conference on Machine Learning](https://icml.cc/), ICML 2025

[**PDF**](https://arxiv.org/abs/2410.18072) **|** [**Project Page**](https://iranqin.github.io/WorldSimBench.github.io/)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2025</div><img src='/images/sciteam_1134x680_src.PNG' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Two Heads Are Better Than One: A Multi-Agent System Has the Potential to Improve Scientific Idea Generation**

Haoyang Su<sup>*</sup>, Renqi Chen<sup>*</sup>, Shixiang Tang<sup>‡</sup>, Xinzhe Zheng, Jingzhe Li, **Zhenfei Yin**, Wanli Ouyang, Nanqing Dong<sup>‡</sup>

[The 63rd Annual Meeting of the Association for Computational Linguistics](https://2025.aclweb.org/), Main Conference, ACL 2025

[**PDF**](https://arxiv.org/abs/2410.09403) **|** [**Project Page**](https://open-sciencelab.github.io/Social_Science/)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint</div><img src='images/GenderBiaVLM_2000x1200_src.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**GenderBias-VL: Benchmarking Gender Bias in Vision Language Models via Counterfactual Probing**

Yisong Xiao, Aishan Liu, QianJia Cheng, **Zhenfei Yin**, Siyuan Liang, Jiapeng Li, Jing Shao, Xianglong Liu<sup>‡</sup>, Dacheng Tao

Preprint, 2024

[**PDF**](https://arxiv.org/abs/2407.00600)
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2025</div><img src='/images/spavl_1134x680_src.PNG' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**SPA-VL: A Comprehensive Safety Preference Alignment Dataset for Vision Language Model**

Yongting Zhang<sup>*</sup>, Lu Chen<sup>*</sup>, Guodong Zheng, Yifeng Gao, Rui Zheng, Jinlan Fu, **Zhenfei Yin**, Senjie Jin, Yu Qiao, Xuanjing Huang, Feng Zhao, Tao Gui<sup>‡</sup>, Jing Shao<sup>‡</sup>

[The IEEE/CVF Conference on Computer Vision and Pattern Recognition](https://cvpr.thecvf.com/), CVPR 2025

[**PDF**](https://arxiv.org/abs/2406.12030) **|** [**Code**](https://github.com/EchoseChen/SPA-VL-RLHF)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IROS 2025</div><img src='/images/RH20T-P_1134x680_src.PNG' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**RH20T-P: A Primitive-Level Robotic Dataset Towards Composable Generalization Agents**

Zeren Chen<sup>*</sup>, Zhelun Shi<sup>*</sup>, Xiaoya Lu<sup>*</sup>, Lehan He<sup>*</sup>, Sucheng Qian, Hao Shu Fang, **Zhenfei Yin<sup>†</sup>**, Wanli Ouyang, Jing Shao<sup>‡</sup>, Yu Qiao, Cewu Lu, Lu Sheng<sup>‡</sup>

[IEEE/RSJ International Conference on Intelligent Robots and Systems](https://www.iros25.org/), IROS 2025

[NeurIPS Workshop on Open-World Agents](https://sites.google.com/view/open-world-agents), 2024

[**PDF**](https://arxiv.org/abs/2403.19622) **|** [**Project Page**](https://sites.google.com/view/rh20t-primitive/main)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint</div><img src='/images/CH^3EF_2000x1200_src.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Assessment of Multimodal Large Language Models in Alignment with Human Values**

Zhelun Shi<sup>*</sup>, Zhipin Wang<sup>*</sup>, Hongxing Fan<sup>*</sup>, Zaibin Zhang, Lijun Li, Yongting Zhang, **Zhenfei Yin**, Lu Sheng<sup>‡</sup>, Yu Qiao, Jing Shao<sup>‡</sup>

Preprint, 2024

[**PDF**](https://arxiv.org/abs/2403.17830) **|** [**Project Page**](https://openlamm.github.io/ch3ef/) **|** [**Code**](https://github.com/OpenGVLab/LAMM)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IROS 2025</div><img src='/images/MineDreamer_2000x1200_src.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**MineDreamer: Learning to Follow Instructions via Chain-of-Imagination for Simulated-World Control**

Enshen Zhou<sup>*</sup>, Yiran Qin<sup>*</sup>, **Zhenfei Yin**, Yuzhou Huang, Ruimao Zhang<sup>‡</sup>, Lu Sheng<sup>‡</sup>, Yu Qiao, Jing Shao<sup>†</sup>

[IEEE/RSJ International Conference on Intelligent Robots and Systems](https://www.iros25.org/), IROS 2025

[NeurIPS Workshop on Open-World Agents](https://sites.google.com/view/open-world-agents), 2024

[**PDF**](https://arxiv.org/abs/2403.12037) **|** [**Project Page**](https://sites.google.com/view/minedreamer/main) **|** [**Code**](https://github.com/Zhoues/MineDreamer)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2024</div><img src='/images/tracing360_1134x680_src.PNG' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Towards Tracing Trustworthiness Dynamics: Revisiting Pre-training Period of Large Language Models**

Chen Qian<sup>*</sup>, Jie Zhang<sup>*</sup>, Wei Yao<sup>*</sup>, Dongrui Liu, **Zhenfei Yin**, Yu Qiao, Yong Liu<sup>‡</sup>, Jing Shao<sup>‡</sup>

[The 62nd Annual Meeting of the Association for Computational Linguistics](https://2024.aclweb.org/), Findings, ACL 2024

[**PDF**](https://arxiv.org/abs/2402.19465) **|** [**Code**](https://github.com/ChnQ/TracingLLM)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Tech. Report</div><img src='/images/308p_2000x1200_src.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**From GPT-4 to Gemini and Beyond: Assessing the Landscape of MLLMs on Generalizability, Trustworthiness and Causality through Four Modalities**

Chaochao Lu, Chen Qian, Guodong Zheng, Hongxing Fan, Hongzhi Gao, Jie Zhang, Jing Shao<sup>‡</sup>, Jingyi Deng, Jinlan Fu, Kexin Huang, Kunchang Li, Lijun Li, Limin Wang, Lu Sheng, Meiqi Chen, Ming Zhang, Qibing Ren, Sirui Chen, Tao Gui, Wanli Ouyang, Yali Wang, Yan Teng, Yaru Wang, Yi Wang, Yinan He, Yingchun Wang, Yixu Wang, Yongting Zhang, Yu Qiao<sup>‡</sup>, Yujiong Shen, Yurong Mou, Yuxi Chen, Zaibin Zhang, Zhelun Shi, **Zhenfei Yin<sup>†</sup>**, Zhipin Wang

Technical Report, 2024

[**PDF**](https://arxiv.org/abs/2401.15071)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV 2024</div><img src='/images/DQA_2000x1200_src.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Depicting Beyond Scores: Advancing Image Quality Assessment through Multi-modal Language Models**

Zhiyuan You<sup>*</sup>, Zheyuan Li<sup>*</sup>, Jinjin Gu<sup>*</sup>, **Zhenfei Yin**, Tianfan Xue<sup>‡</sup>, Chao Dong<sup>‡</sup>

[The 18th European Conference on Computer Vision](https://eccv.ecva.net/Conferences/2024), ECCV 2024

[**PDF**](https://arxiv.org/abs/2312.08962) **|** [**Project Page**](https://depictqa.github.io/) **|** [**Code**](https://github.com/XPixelGroup/DepictQA)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2024</div><img src='/images/MP5_2000x1200_src.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**MP5: A Multi-modal Open-ended Embodied System in Minecraft via Active Perception**

Yiran Qin<sup>*</sup>, Enshen Zhou<sup>*</sup>, Qichang Liu<sup>*</sup>, **Zhenfei Yin**, Lu Sheng<sup>‡</sup>, Ruimao Zhang<sup>‡</sup>, Yu Qiao, Jing Shao<sup>†</sup>

[The IEEE/CVF Conference on Computer Vision and Pattern Recognition](https://cvpr.thecvf.com/Conferences/2024), CVPR 2024

[**PDF**](https://arxiv.org/abs/2312.07472) **|** [**Project Page**](https://iranqin.github.io/MP5.github.io/) **|** [**Code**](https://github.com/IranQin/MP5)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Tech. Report</div><img src='images/ChEF_2000x1200_src.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**ChEF: A Comprehensive Evaluation Framework for Standardized Assessment of Multimodal Large Language Models**

Zhelun Shi<sup>*</sup>, Zhipin Wang<sup>*</sup>, Hongxing Fan<sup>*</sup>, **Zhenfei Yin**, Lu Sheng<sup>‡</sup>, Yu Qiao, Jing Shao<sup>‡</sup>

Technical Report, 2024

[**PDF**](https://arxiv.org/abs/2311.02692) **|** [**Code**](https://github.com/OpenGVLab/LAMM)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2024</div><img src='/images/Octavius_1092x720_src.gif' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Octavius: Mitigating Task Interference in MLLMs via LoRA-MoE**

Zeren Chen<sup>*</sup>, Ziqin Wang<sup>*</sup>, Zhen Wang, Huayang Liu, **Zhenfei Yin<sup>†</sup>**, Si Liu, Lu Sheng<sup>‡</sup>, Wanli Ouyang, Jing Shao<sup>‡</sup>

[The Twelfth International Conference on Learning Representations](https://iclr.cc/Conferences/2024), ICLR 2024

[**PDF**](https://arxiv.org/abs/2311.02684) **|** [**Code**](https://github.com/OpenGVLab/LAMM)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2023</div><img src='/images/LAMM_2000x1200_src.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**LAMM: Language-Assisted Multi-Modal Instruction-Tuning Dataset, Framework, and Benchmark**

**Zhenfei Yin<sup>*</sup>**, Jiong Wang<sup>*</sup>, Jianjian Cao<sup>*</sup>, Zhelun Shi<sup>*</sup>, Dingning Liu, Mukai Li, Xiaoshui Huang, Zhiyong Wang, Lu Sheng, Lei Bai<sup>‡</sup>, Jing Shao<sup>‡</sup>, Wanli Ouyang

[The Thirty-Seventh Annual Conference on Neural Information Processing Systems](https://neurips.cc/Conferences/2023), Datasets and Benchmarks Track, NeurIPS 2023

[**PDF**](https://arxiv.org/abs/2306.06687) <strong><span class='show_paper_citations' data='ngPR1dIAAAAJ:WF5omc3nYNoC'></span></strong> **|** [**Project Page**](https://openlamm.github.io/) **|** [**Code**](https://github.com/OpenGVLab/LAMM)
<!-- - The multi-modal instruction tuning dataset, benchmark evaluation codebase, and training framework have all been open-sourced, along with projects expanding applications on embodied agents. -->
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICME 2024</div><img src='/images/pointclip_1134x680_src.PNG' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**3D Point Cloud Pre-Training with Knowledge Distilled from 2D Images**

Yuan Yao, Yuanhan Zhang, **Zhenfei Yin**, Jiebo Luo, Wanli Ouyang, Xiaoshui Huang<sup>‡</sup>

[IEEE International Conference on Multimedia and Expo](https://2024.ieeeicme.org/), 2024

[**PDF**](https://arxiv.org/abs/2212.08974)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV 2022</div><img src='/images/OmniBenchmark_2000x1200_src.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Benchmarking Omni-Vision Representation Through the Lens of Visual Realms**

Yuanhan Zhang, **Zhenfei Yin<sup>†</sup>**, Jing Shao<sup>‡</sup>, Ziwei Liu

[European Conference on Computer Vision](https://eccv2022.ecva.net/), 2022

[**PDF**](https://arxiv.org/abs/2207.07106) **|** [**Project Page**](https://zhangyuanhan-ai.github.io/OmniBenchmark/) **|** [**Code**](https://github.com/ZhangYuanhan-AI/OmniBenchmark)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV 2022</div><img src='/images/xlearner_1134x680_src.PNG' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**X-Learner: Learning Cross Sources and Tasks for Universal Visual Representation**

Yinan He<sup>*</sup>, Gengshi Huang<sup>*</sup>, Siyu Chen<sup>*</sup>, Jianing Teng<sup>*</sup>, Kun Wang, **Zhenfei Yin**, Lu Sheng, Ziwei Liu, Yu Qiao, Jing Shao<sup>‡</sup>

[European Conference on Computer Vision](https://eccv2022.ecva.net/), 2022

[**PDF**](https://arxiv.org/abs/2203.08764)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IJCV</div><img src='/images/Bamboo_2000x1200_src.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Bamboo: Building Mega-Scale Vision Dataset Continually with Human-Machine Synergy**

Yuanhan Zhang<sup>*</sup>, Qinghong Sun<sup>*</sup>, Yichun Zhou<sup>*</sup>, Zexin He<sup>*</sup>, **Zhenfei Yin<sup>†</sup>**, Kun Wang, Lu Sheng, Yu Qiao, Jing Shao<sup>‡</sup>, Ziwei Liu

International Journal of Computer Vision 10.1007/s11263-025-02450-2

[**PDF**](https://arxiv.org/abs/2203.07845) **|** [**Code**](https://github.com/ZhangYuanhan-AI/Bamboo)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Tech. Report</div><img src='/images/INTERN_2000x1200_src.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**INTERN: A New Learning Paradigm Towards General Vision**

Jing Shao<sup>*</sup>, Siyu Chen<sup>*</sup>, Yangguang Li<sup>*</sup>, Kun Wang<sup>*</sup>, **Zhenfei Yin<sup>*</sup>**, Yinan He<sup>*</sup>, Jianing Teng<sup>*</sup>, Qinghong Sun<sup>*</sup>, Mengya Gao<sup>*</sup>, Jihao Liu<sup>*</sup>, Gengshi Huang<sup>*</sup>, Guanglu Song, Yichao Wu, Yuming Huang, Fenggang Liu, Huan Peng, Shuo Qin, Chengyu Wang, Yujie Wang, Conghui He, Ding Liang, Yu Liu, Fengwei Yu, Junjie Yan, Dahua Lin, Xiaogang Wang, Yu Qiao<sup>‡</sup>

Technical Report, 2021

[**PDF**](https://arxiv.org/abs/2111.08687) **|** [**Code**](https://github.com/OpenGVLab)
</div>
</div>
<!-- ------------------------------------------------------------- -->

<span class='anchor' id='-professional-service'></span>

# Professional Service
- *2023.08-Present*, Academic-Talk Event Organizer, [Echo AI Talk](https://www.echoaitalk.com/)
- *2024.07*, Workshop Organizer, ICML 2024 workshop on [Multi-modal Foundation Model meets Embodied AI (MFM-EAI)](https://icml-mfm-eai.github.io/)
- *2024.07*, Workshop Organizer, ICML 2024 workshop on [Trustworthy Multi-modal Foundation Models and AI Agents (TiFA)](https://icml-tifa.github.io/)
- *2024 Spring*, Guest Lecture, [ELEC5304](https://www.sydney.edu.au/units/ELEC5304): Intelligent Visual Signal Understanding, USYD
- *2024 Spring*, Teaching Assistant, [COMP 5425](https://www.sydney.edu.au/units/COMP5425): Multimedia Retrieval, USYD
- Peer Review and Program Committee, [ICLR](https://iclr.cc/), [NeurIPS](https://neurips.cc/), [ICML](https://icml.cc/), [ARR](https://aclrollingreview.org/), [AAAI](https://aaai.org/), [ICCV](https://iccv.thecvf.com/), [ECCV](https://eccv.ecva.net/), [CVPR](https://cvpr.thecvf.com/), [ACMMM](https://acmmm2025.org/), and [TPAMI](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=34)

<!-- #  Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

#  Educations
- *2019.06 - 2022.04 (now)*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2015.09 - 2019.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

#  Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)

#  Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China. -->
