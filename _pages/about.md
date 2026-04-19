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

<style>
/* 1. 让论文条目上下极度紧凑 */
.paper-box {
  margin-bottom: 5px !important;  /* 原本可能是 20px 或更多，将其调至极小 */
  padding-bottom: 0px !important; /* 去掉多余的下内边距 */
}

/* 2. 强制左侧图片区域统一大小 */
.paper-box-image {
  max-width: 220px;     /* 限制图片区域的最大宽度，防止像上次那样遮挡文字 */
  width: 100% !important;
}

/* 3. 核心：强制所有图片统一比例，裁切填充 */
.paper-box-image img {
  width: 100% !important;
  aspect-ratio: 16 / 9; /* 这里可以设置你想要的统一比例，截图看起来接近 16:9 */
  object-fit: cover;    /* 裁切多余部分，保证内容不拉伸 */
  border-radius: 4px;   /* 可选：加一点圆角，更精致 */
}
</style>

<span class='anchor' id='about-me'></span>
I am a CS Ph.D student at the [University of California, Davis](https://cs.ucdavis.edu/), advised by Prof. [Lifu Huang](https://wilburone.github.io/). Previously, I received my Master's Degree at [CS Department, Fudan University](https://cs.fudan.edu.cn/), advised by Prof. [Weifeng Ge](https://www.weifengge.net/), and Bachelor’s Degree in the [CS Department, Southeast University](https://cse.seu.edu.cn/), where I worked with Prof. [Ding Ding](https://dingdingseu.mystrikingly.com/). My research primarily focuses on **Multimodal Large Langauge Models** and their broad applications (Vision-Language Reasoning, Video Understanding, Embodied-AI, Unified Image/Video Generation, etc.).

# 📝 Publications and Preprints

<div class='paper-box'>
  <div class='paper-box-image'>
    <div><img src='images/tab.png' alt="Paper Image"></div>
  </div>
  <div class='paper-box-text'>
    </div>
</div>
  
[Think, Act, Build: An Agentic Framework with Vision Language Models for Zero-Shot 3D Visual Grounding](https://arxiv.org/abs/2604.00528)

**Haibo Wang**, Zihao Lin, Zhiyang Xu, Lifu Huang. 

<span style="color: #50ACC7"> **(Arxiv Preprint)** </span> [![arXiv](https://img.shields.io/badge/Arxiv-2604.00528-b31b1b.svg?logo=arXiv)](https://arxiv.org/abs/2604.00528) [![](https://img.shields.io/badge/Github-181717?style=flat&logo=github&logoColor=white)](https://github.com/WHB139426/TAB-Agent)
</div>
</div>



<div class='paper-box'>
  <div class='paper-box-image'>
    <div><img src='images/streambridge.png' alt="Paper Image"></div>
  </div>
  <div class='paper-box-text'>
    </div>
</div>
  
[StreamBridge: Turning Your Offline Video Large Language Model into a Proactive Streaming Assistant](https://www.arxiv.org/abs/2505.05467)

**Haibo Wang**, Bo Feng, Zhengfeng Lai, Mingze Xu, Shiyu Li, Weifeng Ge, Afshin Dehghan, Meng Cao, Ping Huang. 

<span style="color: #50ACC7"> **(NeurIPS 2025)** </span> [![arXiv](https://img.shields.io/badge/Arxiv-2505.05467-b31b1b.svg?logo=arXiv)](https://arxiv.org/abs/2505.05467)
</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><img src='images/grounded-videollm.png' alt="sym" width="400px"></div></div>
<div class='paper-box-text' markdown="1">
  
[Grounded-VideoLLM: Sharpening Fine-grained Temporal Grounding in Video Large Language Models](https://arxiv.org/abs/2410.03290)

**Haibo Wang**, Zhiyang Xu, Yu Cheng, Shizhe Diao, Yufan Zhou, Yixin Cao, Qifan Wang, Weifeng Ge, Lifu Huang. 

<span style="color: #50ACC7"> **(EMNLP 2025 Findings)** </span> [![arXiv](https://img.shields.io/badge/Arxiv-2410.03290-b31b1b.svg?logo=arXiv)](https://arxiv.org/abs/2410.03290) [![](https://img.shields.io/badge/Github-181717?style=flat&logo=github&logoColor=white)](https://github.com/WHB139426/Grounded-Video-LLM)
</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><img src='images/gcg.png' alt="sym" width="400px"></div></div>
<div class='paper-box-text' markdown="1">
  
[Weakly Supervised Gaussian Contrastive Grounding with Large Multimodal Models for Video Question Answering](https://arxiv.org/abs/2401.10711)

**Haibo Wang**, Chenghang Lai, Yixuan Sun, Weifeng Ge.

<span style="color: #50ACC7"> **(ACM MM 2024)** </span> [![arXiv](https://img.shields.io/badge/Arxiv-2401.10711-b31b1b.svg?logo=arXiv)](https://arxiv.org/abs/2401.10711) [![](https://img.shields.io/badge/Github-181717?style=flat&logo=github&logoColor=white)](https://github.com/WHB139426/GCG)
</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><img src='images/qaprompts.png' alt="sym" width="400px"></div></div>
<div class='paper-box-text' markdown="1">
  
[Q&A Prompts: Discovering Rich Visual Clues through Mining Question-Answer Prompts for VQA requiring Diverse World Knowledge](https://arxiv.org/abs/2401.10712)

**Haibo Wang**, Weifeng Ge. 

<span style="color: #50ACC7"> **(ECCV 2024)** </span> [![arXiv](https://img.shields.io/badge/Arxiv-2401.10712-b31b1b.svg?logo=arXiv)](https://arxiv.org/abs/2401.10712) [![](https://img.shields.io/badge/Github-181717?style=flat&logo=github&logoColor=white)](https://github.com/WHB139426/QA-Prompts)
</div>
</div>


[Adapting Multimodal Large Language Models for Video Question Answering by Capturing Question-critical and Coherent Moments](https://ieeexplore.ieee.org/document/11153868)

**Haibo Wang**, Chenghang Lai, Weifeng Ge. <span style="color: #50ACC7"> **(IEEE TMM 2025)** </span> 


[Pixel level Semantic Correspondence through Layout aware Representation Learning and Multi scale Matching Integration](https://openaccess.thecvf.com/content/CVPR2024/papers/Sun_Pixel-level_Semantic_Correspondence_through_Layout-aware_Representation_Learning_and_Multi-scale_Matching_CVPR_2024_paper.pdf)

Yixuan Sun\*, Zhangyue Yin\*, **Haibo Wang**, Yan Wang, Xipeng Qiu, Weifeng Ge, Wenqiang Zhang. <span style="color: #50ACC7"> **(CVPR 2024)** </span>


  
[Object-Centric Cross-Modal Knowledge Reasoning for Future Event Prediction in Videos](https://ieeexplore.ieee.org/document/10638077)

Chenghang Lai, **Haibo Wang**, Weifeng Ge, Xiangyang Xue. <span style="color: #50ACC7"> **(IEEE TCSVT 2024)** </span>


  
[IVRSandplay: An Immersive Virtual Reality Sandplay System Coupled with Hand Motion Capture and Eye Tracking](https://ieeexplore.ieee.org/document/10152562)

**Haibo Wang**, Ding Ding, Yuhao Liu, Chi Wang.  <span style="color: #50ACC7"> **(CSCWD 2023)** </span>



# 🎖 Honors and Awards
- *2026.03*, [Outstanding Master Thesis Award of the Shanghai Computer Society](http://scs.sh.cn/#/article/501)
- *2025.03*, [Shanghai Outstanding Graduates](https://cs.fudan.edu.cn/09/32/c24257a723250/page.htm)
- *2024.10*, [National Scholarship](https://cs.fudan.edu.cn/9d/f0/c24257a695792/page.htm)
  
# 👩‍💻 Academic Services
- Reviewer: ICLR 2025, 2026; NeurIPS 2026; COLM 2026

# 📖 Educations
<div style="display: flex; align-items: center; margin-bottom: 5px;">
  <img src="images/ucdavis.png" alt="UC Davis Logo" style="width: 70px; height: 70px; margin-right: 20px;">
  <div>
    <b>2025.08 - Now</b>, Doctoral student, University of California, Davis.
  </div>
</div>

<div style="display: flex; align-items: center; margin-bottom: 5px;">
  <img src="images/FDU.png" alt="Fudan University Logo" style="width: 70px; height: 70px; margin-right: 20px;">
  <div>
    <b>2022.09 - 2025.06</b>, Graduate student, Fudan University, Shanghai.
  </div>
</div>

<div style="display: flex; align-items: center; margin-bottom: 5px;">
  <img src="images/seu.png" alt="Southeast University Logo" style="width: 70px; height: 70px; margin-right: 20px;">
  <div>
    <b>2018.09 - 2022.06</b>, Undergraduate student, Southeast University, Nanjing.
  </div>
</div>

# 💻 Experience
<div style="display: flex; align-items: center; margin-bottom: 5px;">
  <img src="images/apple.png" alt="Apple Logo" style="width: 70px; height: 70px; margin-right: 20px;">
  <div>
    <b>2025.01 - 2025.07</b>, AI/ML Research intern, Apple, Beijing. Mentor: <a href="https://zjujefflai.github.io/">Jeff Lai</a>, Shiyu Li, Brian Feng
  </div>
</div>

<div style="display: flex; align-items: center; margin-bottom: 5px;">
  <img src="images/ucdavis.png" alt="UC Davis Logo" style="width: 70px; height: 70px; margin-right: 20px;">
  <div>
    <b>2024.05 - 2025.02</b>, Research intern, University of California, Davis. Mentor: Prof. <a href="https://wilburone.github.io/">Lifu Huang</a>
  </div>
</div>

<div style="display: flex; align-items: center; margin-bottom: 5px;">
  <img src="images/oppo.png" alt="OPPO" style="width: 90px; height: 60px; margin-right: 20px;">
  <div>
    <b>2024.05 - 2024.07</b>, Intern, OPPO AI Research, Shanghai. Mentor: <a href="https://scholar.google.com/citations?user=Wmnz-HYAAAAJ&hl=en">Jinjin Xu</a>
  </div>    
</div> 

# 🗺️ Visits
<script type='text/javascript' id='clustrmaps' src='//cdn.clustrmaps.com/map_v2.js?cl=ffffff&w=500&t=n&d=RfrlB4yHoGFLWWRKfUg--bpSN8T7BbPLW5zCwL9DcR0'></script>
