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

<div id='about-me'>

<p><em>Last updated: 20 July 2026</em></p>

<p>I am a first-year Ph.D. student in Computer Science at <strong><a href="https://home.dartmouth.edu">Dartmouth College</a></strong>. I am a member of the <strong><a href="https://www.sahaslab.com/">Science and Art of Human-AI Systems (SAHAS) Lab</a></strong>, where I am honored to be advised by Prof. <strong><a href="https://nsingh1.host.dartmouth.edu/">Nikhil Singh</a></strong> (he's pretty nice) and work on the intersection of AI Agents and Multimodal Large Language Models.</p>

<p>I worked as a research intern at Alibaba DAMO Academy, mentored by Dr. <strong><a href="https://scholar.google.com/citations?user=9o5r8bUAAAAJ&hl=zh-CN">Tian Zhou</a></strong>. I also served as a Visiting Student with Prof. <strong><a href="https://scholar.google.com/citations?user=p9-ohHsAAAAJ&hl=zh-CN">Ming-Hsuan Yang</a></strong> at UC Merced and Google DeepMind and Prof. <strong><a href="https://scholar.google.com/citations?user=syoPhv8AAAAJ&hl=zh-CN">Chao Ma</a></strong> at Shanghai Jiao Tong University. I have previously collaborated with Prof. <strong><a href="https://scholar.google.com.hk/citations?user=SSI90d4AAAAJ&hl=en">Lu Qi</a></strong> and Dr. <strong><a href="https://scholar.google.com/citations?user=FL3ReD0AAAAJ&hl=zh-CN">Xiangtai Li</a></strong> at TikTok, as well as with Prof. <strong><a href="https://scholar.google.com/citations?user=bMedjfUAAAAJ&hl=en">Junwei Liang</a></strong> at AI Thrust, HKUST(GZ).</p>

<p>My Ph.D. research interests lie in <strong>AI Agents</strong>:</p>

<ul>
<li>(1) agent memory mechanisms and architectures</li>
<li>(2) multimodal learning and reasoning</li>
<li>(3) long-horizon reasoning and decision-making</li>
</ul>

</div>

<!-- <div style="margin: 2em 0; padding: 1.5em; background: linear-gradient(135deg, #fff5f5 0%, #fff1f1 100%); border-left: 4px solid #f56565; border-bottom: 1px solid #f56565; border-radius: 8px; box-shadow: 0 2px 8px rgba(245, 101, 101, 0.1);">
    <strong style="color: #c53030; font-size: 1.1em; display: block; margin-bottom: 0.5em;">🤝 Open for Collaboration & Internship Opportunities</strong>
    <p style="margin: 0; color: #742a2a; line-height: 1.6;">I'm open for academic collaborations and actively seeking <span style="background-color: #fed7d7; padding: 2px 6px; border-radius: 4px; font-weight: 700; color: #c53030;">AI Agent-related </span> summer internship opportunities based in the U.S. for 2027. Please feel free to email me at <a href="mailto:tangyujin0275@gmail.com" style="color: #c53030; font-weight: 600; text-decoration: none; border-bottom: 1px solid #c53030;">tangyujin0275@gmail.com</a> or <a href="mailto:yujin.tang.gr@dartmouth.edu" style="color: #c53030; font-weight: 600; text-decoration: none; border-bottom: 1px solid #c53030;">yujin.tang.gr@dartmouth.edu</a>.</p>
</div> -->

# News

{: #news .section-title .section-title-news}

<div class="news-scroll-container">
<ul class="news-list">
<li><em>2026.07</em>:  🚀🚀 DMV-Bench is online, the first interactive benchmark for multimodal-agent visual memory. <a href="https://arxiv.org/abs/2606.27499"><strong>Paper</strong></a> <a href="https://github.com/yyyujintang/DMV-Bench"><strong>Code</strong></a> <a href="https://huggingface.co/datasets/yyyujintang/DMV-Bench-Images"><strong>HuggingFace</strong></a></li>
<li><em>2026.06</em>:  🎉🎉 PDR / PredGS is accepted by ECCV 2026. <a href="https://arxiv.org/abs/2606.31050"><strong>Paper</strong></a></li>
<li><em>2026.06</em>:  📄📄 Our <a href="https://github.com/TROUBADOUR000/Awesome-Agentic-Time-Series/blob/main/The%20Landscape%20of%20Agentic%20Time%20Series%20Systems.pdf">survey</a> <strong>The Landscape of Agentic Time Series Systems: Architectures, Reliability, and Frontiers</strong> is released! See the PDF in the <a href="https://github.com/TROUBADOUR000/Awesome-Agentic-Time-Series">repository</a> <img src="https://img.shields.io/github/stars/TROUBADOUR000/Awesome-Agentic-Time-Series" alt="Stars">.</li>
<li><em>2026.04</em>:  📚📚 Yujin created <a href="https://github.com/yyyujintang/Awesome-Agent-Memory-Papers">Awesome-Agent-Memory-Papers</a> <img src="https://img.shields.io/github/stars/yyyujintang/Awesome-Agent-Memory-Papers.svg" alt="Stars">, a curated list of papers on agent memory research. A companion <a href="https://yyyujintang.github.io/Awesome-Agent-Memory-Papers/">website</a> provides organized and filterable browsing of the papers. Also synced to my <a href="https://jenny-blog-eight.vercel.app/">blog</a>. Hope it helps!</li>
<li><em>2026.01</em>:  🎉🎉 One paper is accepted by ICLR 2026.</li>
<li><em>2026.01</em>:  🎉🎉 PredFormer is accepted by TMLR 2026.</li>
<li><em>2025.09</em>:  🎓🎓 Yujin enrolled in Dartmouth College as a Ph.D. student in Computer Science.</li>
<li><em>2025.03</em>:  🔬🔬 Yujin joined Alibaba DAMO Academy as a research intern.</li>
<li><em>2024.10</em>:  🎉🎉 PredFormer is available! This is the first pure-transformer based model in spatial-temporal predictive learning, which is recurrent-free and convolution-free, outperforming previous models by large margins with superior efficiency. <a href="https://arxiv.org/abs/2410.04733"><strong>Paper</strong></a> <a href="https://github.com/yyyujintang/PredFormer"><strong>Code</strong></a> <img src="https://img.shields.io/github/stars/yyyujintang/PredFormer" alt="Stars"></li>
<li><em>2024.04</em>:  🎉🎉 VMRNN is accepted by CVPRW 2024.</li>
<li><em>2024.03</em>:  🎉🎉 PostRainBench is accepted by ICLRW 2024.</li>
<li><em>2024.01</em>:  🎉🎉 Yujin created Awesome-Mamba-Papers repository. <strong>This is the first Awesome Mamba repository and promotes Mamba related research</strong>. <a href="https://github.com/yyyujintang/Awesome-Mamba-Papers">Link</a> <img src="https://img.shields.io/github/stars/yyyujintang/Awesome-Mamba-Papers" alt="Stars"></li>
</ul>
</div>

# Publications

{: #publications .section-title .section-title-publication}

<p><sup>*</sup>: equal contribution.</p>

<div class="publication-list">

<div class="pub-item">
<div class="pub-title"><a href="https://doi.org/10.1109/ACCESS.2026.3650927">An Improved Small Defect Classification System Using Image Patching Methodology on Aluminum Car Doors</a> [<strong style='color: blue'>SCIE</strong>]</div>
<div class="pub-authors">Ugur Ercelik, <strong>Hyeonseok Jin</strong>, Longfei Li, Kyungbaek Kim.</div>
<div class="pub-venue"><em>IEEE Access</em>, 2026.</div>
</div>

<div class="pub-item">
<div class="pub-title"><a href="https://doi.org/10.1177/20552076251393380">Enhancing deep learning models for predicting smoking status using clinical data in patients with chronic obstructive pulmonary disease</a> [<strong style='color: blue'>SCIE</strong>]</div>
<div class="pub-authors">Sehun Cho, <strong>Hyeonseok Jin</strong>, Kyungbaek Kim, Sola Cho, Ja Yun Choi.</div>
<div class="pub-venue"><em>Digital Health</em>, 2025.</div>
</div>

<div class="pub-item">
<div class="pub-title"><a href="https://doi.org/10.1109/ACCESS.2025.3623702">A Data-Driven Model to Predict Regular Strength Exercise Patterns in Patients With Chronic Obstructive Pulmonary Disease</a> [<strong style='color: blue'>SCIE</strong>]</div>
<div class="pub-authors"><strong>Hyeonseok Jin</strong>, Ja Yun Choi, Sehyun Cho, Kyungbaek Kim.</div>
<div class="pub-venue"><em>IEEE Access</em>, 2025.</div>
</div>

<div class="pub-item">
<div class="pub-title"><a href="https://scholar.google.com/scholar?oi=bibs&cluster=791506653268956817&btnI=1&hl=ko">A Study of Leaf Disease Classification via Token-guided GNN</a></div>
<div class="pub-authors"><strong>Hyeonseok Jin</strong><sup>*</sup>, David J. Richter<sup>*</sup>, Kyungbaek Kim.</div>
<div class="pub-venue"><em>The 14th International Conference on Smart Media & Applications</em> (SMA 2025), 2025.</div>
</div>

<div class="pub-item">
<div class="pub-title"><a href="https://doi.org/10.48550/arXiv.2507.11550">Deformable Dynamic Convolution for Accurate yet Efficient Spatio-Temporal Traffic Prediction</a></div>
<div class="pub-authors"><strong>Hyeonseok Jin</strong>, Geonmin Kim, Kyungbaek Kim.</div>
<div class="pub-venue"><em>arXiv prepreint</em>, 2025.</div>
</div>

<div class="pub-item">
<div class="pub-title"><a href="https://doi.org/10.1109/ACCESS.2025.3573639">DATC-STP: Towards Accurate yet Efficient Spatiotemporal Prediction with Transformer-style CNN</a> [<strong style='color: blue'>SCIE</strong>]</div>
<div class="pub-authors"><strong>Hyeonseok Jin</strong> and Kyungbaek Kim.</div>
<div class="pub-venue"><em>IEEE Access</em>, 2025.</div>
</div>

</div>

# Educations

{: #educations .section-title .section-title-education}

<div class="education-item">
  <div class="logo-container">
    <img src="images/KENTECH_logo.svg" alt="KENTECH Logo" loading="lazy">
  </div>
  <div class="content">
    <div class="title">Korea Institute of Energy Technology (KENTECH)</div>
    <div class="subtitle">Ph.D. in Energy AI</div>
    <div class="date">2025.09 - Present</div>
    <div class="description">Advised by Prof. <a href="https://scholar.google.co.kr/citations?user=MP9FW-YAAAAJ&hl=en">Seokju Lee</a>, <a href="https://view.kentech.ac.kr/">View Lab</a></div>
  </div>
</div>

<div class="education-item">
  <div class="logo-container">
    <img src="images/CNU_logo.svg" alt="CNU Logo" loading="lazy">
  </div>
  <div class="content">
    <div class="title">Chonnam National University</div>
    <div class="subtitle">M.S. in AI Convergence</div>
    <div class="date">2023.09 - 2025.08</div>
    <div class="description">Advised by Prof. <a href="https://scholar.google.co.kr/citations?user=hRITYcMAAAAJ&hl=en&oi=ao">Kyungbaek Kim</a>, DNS Lab</div>
  </div>
</div>

<div class="education-item">
  <div class="logo-container">
    <img src="images/CNU_logo.svg" alt="CNU Logo" loading="lazy">
  </div>
  <div class="content">
    <div class="title">Chonnam National University</div>
    <div class="subtitle">B.S. in Computer Engineering</div>
    <div class="date">2016.03 - 2023.02</div>
  </div>
</div>

# Internships

{: #internships .section-title .section-title-internship}

<div class="internship-item highlight">
  <div class="logo-container">
    <img src="images/alibaba-logo.png" alt="Alibaba DAMO Academy Logo" loading="lazy">
  </div>
  <div class="content">
    <div class="title">Alibaba DAMO Academy</div>
    <div class="subtitle">Algorithm Engineer Intern</div>
    <div class="date">2025.03 - 2025.07</div>
    <div class="description">Research intern for 5 wonderful months. Working on cutting-edge AI research and development. Mentored by Dr. <a href="https://scholar.google.com/citations?user=9o5r8bUAAAAJ&hl=zh-CN">Tian Zhou</a> and Dr. <a href="https://scholar.google.com/citations?user=D_cOMBgAAAAJ&hl=en">Liang Sun</a></div>
  </div>
</div>

<div class="internship-item">
  <div class="logo-container">
    <img src="images/ucmerced-logo.png" alt="UC Merced Logo" loading="lazy">
  </div>
  <div class="content">
    <div class="title">UC Merced & Shanghai Jiao Tong University</div>
    <div class="subtitle">Remote Visiting Student @ UC Merced & Onsite Visiting Student @ SJTU</div>
    <div class="date">2024.06 - 2025.03</div>
    <div class="description">Working with Prof. <a href="https://scholar.google.com/citations?user=p9-ohHsAAAAJ&hl=zh-CN">Ming-Hsuan Yang</a> at UC Merced, Prof. <a href="https://scholar.google.com/citations?user=syoPhv8AAAAJ&hl=zh-CN">Chao Ma</a> at <a href="https://ai.sjtu.edu.cn">AI Institute, SJTU</a>, and Prof. <a href="https://scholar.google.com.hk/citations?user=SSI90d4AAAAJ&hl=en">Lu Qi</a> at WHU.</div>
  </div>
</div>

<div class="internship-item">
  <div class="logo-container">
    <img src="images/hkust-gz-logo.png" alt="HKUST-GZ Logo" loading="lazy">
  </div>
  <div class="content">
    <div class="title">The Hong Kong University of Science and Technology (Guangzhou)</div>
    <div class="subtitle">Research Assistant at AI Thrust</div>
    <div class="date">2023.02 - 2024.05</div>
    <div class="description">Supervised by Prof. <a href="https://scholar.google.com/citations?user=bMedjfUAAAAJ&hl=en">Junwei Liang</a>. </div>
  </div>
</div>

<!-- # Academic Service

{: #academic-service .section-title .section-title-service}

* **2026:** Reviewer for *International Journal of Computer Vision (IJCV)* x2, *ICLR 2026 Workshop MemAgents* x3, *IEEE Transactions on Multimedia (TMM)* x3, *COLM 2026 Workshop on Agent Behavior* x2
* **2025:** Reviewer for *Transactions on Machine Learning Research (TMLR)* and *International Journal of Computer Vision (IJCV)*
* **2024:** Reviewer for *IEEE Transactions on Neural Networks and Learning Systems (TNNLS)*

# Teaching

{: #teaching .section-title .section-title-teaching}

* **Spring/Summer 2026:** Teaching Assistant for CS50: Software Design and Implementation, <strong><a href="https://home.dartmouth.edu">Dartmouth College</a></strong>
* **Winter 2026:** Head Teaching Assistant for Principles of Machine Learning, <strong><a href="https://home.dartmouth.edu">Dartmouth College</a></strong>
* **Fall 2025:** Teaching Assistant for Video Understanding, <strong><a href="https://home.dartmouth.edu">Dartmouth College</a></strong>
* **Spring 2023:** Teaching Assistant for AIAA 5032: Foundations of Artificial Intelligence, <strong><a href="https://www.hkust-gz.edu.cn/">The Hong Kong University of Science and Technology (Guangzhou)</a></strong>

# Resources for Researchers

{: #resources-for-cv-researchers .section-title .section-title-resources}

[Ming-Hsuan Yang-UCM](https://scholar.google.com/citations?user=syoPhv8AAAAJ&hl=en): How to Get Your CVPR Paper Rejected? [Link](https://vision.sjtu.edu.cn/files/How-to-get-your-CVPR-paper-rejected.pdf)

[Bill Freeman-MIT](https://scholar.google.com/citations?user=0zZnyMEAAAAJ&hl=zh-CN): How to Write Papers [Link](https://faculty.cc.gatech.edu/~parikh/citizenofcvpr/static/slides/freeman_how_to_write_papers.pdf) Advice for Graduate Student  [Link](https://people.csail.mit.edu/billf/talks/10minFreeman2013.pdf)

# More About Me

{: #more-about-me .section-title .section-title-about}

- I was born in Dazhou, Sichuan Province. It is where my life began, and where my roots are.
- My MBTI is INTJ (Introverted, Intuitive, Thinking, Judging).

<script type="text/javascript" id="mapmyvisitors" src="https://mapmyvisitors.com/map.js?d=DpZkNL3LsLmeQRxUKn0lTTI5TvgkpddDlnJpErWoftQ&cl=ffffff&w=a"></script> -->
