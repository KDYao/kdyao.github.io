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

<meta name="google-site-verification" content="bShjw1ei40KAMWn3QAJ9jMWVq90WQJk0bztUqs5_Le4" />

<span class='anchor' id='about-me'></span>

# About Me

I am an Assistant Professor at the Faculty of Engineering and Applied Science, [Ontario Tech University](https://ontariotechu.ca/).
Prior to that, I was a Postdoctoral Research Fellow at the University of Waterloo.
I received my Ph.D. from [Software Analysis and Intelligence Lab (SAIL)](https://sail.cs.queensu.ca/index.html) at Queen’s University under the supervision of Prof. [Ahmed E. Hassan](https://www.cs.queensu.ca/people/Ahmed%20E./Hassan). 
I obtained my Master’s degree from Concordia University under the supervision of Prof. [Weiyi Shang](https://ece.uwaterloo.ca/~wshang/).
<!-- My research primarily focuses on streamlining and optimizing today's log management process. -->
My research interests include AIOps, software log management, log analytics, performance engineering, software testing, empirical software engineering, and mining software repositories. Contact me at [kundi.yao@ontariotechu.ca](mailto:kundi.yao@ontariotechu.ca)
<!-- 
My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->


<!-- # 🔥 News
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

<!-- # 📝 Publications  -->
<span class='anchor' id='publications'></span>

# Publications 

- [World of Logs: A Dataset of Logs from Online Documents]()
  
  Xiaohui Wang, **Kundi Yao**, Lizhi Liao, Pengyu Nie, Xuan Zhang, Weiyi Shang.

  The 23rd International Mining Software Repositories Conference (MSR 2026), Data Track

- [LPB-Gen: Systematic Large Log-Parsing Benchmarks Generation]()
  
  Hetong Dai, **Kundi Yao**, Felix Li, Jianxin You, Qianyun Shen, Weiyi Shang. 
  
  ACM Transactions on Software Engineering and Methodology (TOSEM)

- [Towards Secure Logging: Characterizing and Benchmarking Logging Code Security Issues with LLMs]()
  
  He Yang Yuan, Xin Wang, **Kundi Yao**, An Ran Chen, Zishuo Ding, Zhenhao Li
  
  The 34th ACM SIGSOFT Conference on the Foundations of Software Engineering (FSE 2026)

- [LLM4JMH: Studying the Use of LLMs for Generating Java Performance Microbenchmarks]()
  
  Zongxiong Chen, Derui Zhu, **Kundi Yao**, Weiyi Shang, Jinfu Chen, Jiahui Geng, Alexander Pretschner, Jens Grossklags, Manfred Hauswirth, Sonja Schimmler
  
  The 48th IEEE/ACM International Conference on Software Engineering (ICSE 2026)

- [An Empirical Study of Privacy Leakage Vulnerability in Third-Party Android Logs Libraries]()
  
  Yixi Zhao, **Kundi Yao**, Yiming Tang, Weiyi Shang
  
  The 33rd IEEE International Conference on Software Analysis, Evolution and Reengineering (SANER 2026)

- [Detecting DTC Requirement-Implementation Inconsistencies Using LLMs: An Experience Report]()
  
  Tongwei Zhang, **Kundi Yao**, Hanyang Hu, Pengyu Nie, Krishna Koravadi, Weiyi Shang

  IEEE Software

- [Who's to Blame? Rethinking the Brittleness of Automated Web GUI Testing from a Pragmatic Perspective](https://conf.researchr.org/details/ase-2025/ase-2025-papers/243/Who-s-to-Blame-Rethinking-the-Brittleness-of-Automated-Web-GUI-Testing-from-a-Pragma)

  Haonan Zhang, **Kundi Yao**, Zishuo Ding, Lizhi Liao, Weiyi Shang

  The 40th IEEE/ACM International Conference on Automated Software Engineering (ASE 2025)

- [MEMCAIN: A Memory-Enhanced Hybrid CNN-Attention Model for Network Anomaly Detection](https://www.nature.com/articles/s41598-025-18951-6)

  Lan Liu, Tingfeng Cai, Chiyu Zhou, Fengwei Guo, **Kundi Yao**, Jianhao Zhou

  Springer Nature Scientific Reports (SREP 2025)

- [An Empirical Study of Logging Practice in CUDA-based Deep Learning Systems](https://ece.uwaterloo.ca/~wshang/pubs/QRS2025_AnChen.pdf)

  An Chen, **Kundi Yao**, Haonan Zhang, Yiming Tang, Weiyi Shang

  The 25th IEEE International Conference on Software Quality, Reliability, and Security (QRS 2025)

- [Improving QA System Testing Efficiency Through White-Box Test Prioritization](https://ece.uwaterloo.ca/~wshang/pubs/QRS2025_ANNA.pdf)

  Hanying Shao, Zishuo Ding, **Kundi Yao**, Haonan Zhang, Weiyi Shang.

  The 25th IEEE International Conference on Software Quality, Reliability, and Security (QRS 2025)  

- [Batch Execution of Microbenchmarks for Efficient Performance Testing](../resources/papers/Mostafa_ICST2025.pdf)
  
  Mostafa Jangali, **Kundi Yao**, Yiming Tang, Diego Elias Costa, and Weiyi Shang.

  The 18th IEEE International Conference on Software Testing, Verification and Validation (ICST 2025), Vision and Emerging Results.

- [Finding associations between natural and computer languages: A case-study of bilingual LDA applied to the bleeping computer forum posts](../resources/papers/Kundi_JSS2023.pdf)
  
  **Kundi Yao**, Gustavo A Oliva, Ahmed E. Hassan, Muhammad Asaduzzaman, Andrew J. Malton, Andrew Walenstein

  Journal of Systems and Software (JSS)

- [Improving state-of-the-art compression techniques for log management tools](../resources/papers/Kundi_TSE_2021.pdf)
  
  **Kundi Yao**, Mohammed Sayagh, Weiyi Shang, and Ahmed E. Hassan

  IEEE Transactions on Software Engineering (TSE)
  
- [A study of the performance of general compressors on log files](../resources/papers/Kundi_EMSE2020.pdf)
  
  **Kundi Yao**, Heng Li, Weiyi Shang, Ahmed E. Hassan

  Empirical Software Engineering (EMSE)

- [Log4Perf: Suggesting and updating logging locations for web-based systems’ performance monitoring](../resources/papers/Kundi_EMSE2019.pdf)
  
  **Kundi Yao**, Guilherme B. de Pádua, Weiyi Shang, Catalin Sporea, Andrei Toma, Sarah Sajedi

  Empirical Software Engineering (EMSE)

- [Log4perf: Suggesting logging locations for web-based systems' performance monitoring](../resources/papers/Kundi_ICPE2018.pdf)
  
  **Kundi Yao**, Guilherme B. de Pádua, Weiyi Shang, Catalin Sporea, Andrei Toma, Sarah Sajedi

  The 9th ACM/SPEC International Conference on Performance Engineering (ICPE 2018). Best paper nomination.

<!-- # 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

<!-- <span class='anchor' id='teaching'></span>

# Teaching

### Guest Lecturer at University of Waterloo
- ECE 750: Special Topics in Computer Software (2025 Winter)
  
  Title: Code analysis tutorial – How to create an Eclipse plugin to extract AST (abstract syntax tree) information
  

- SE 464: Software Design and Architectures (2024 Fall)
  
  Title: Nonfunctional Requirements & Twitter Design Excercise

### Guest Lecturer at North Carolina State University
- [Generative AI for Software Engineering (GAI4SE)](https://github.com/gai4se/GAI4SE-Course) (2024 Fall)
  
  Title: Improving analytical capabilities and storage efficiencies of modern log management solutions 

### Teaching Assistant at Queen's University
- CISC 326: Software/Game Architecture (2021 Winter)
- CISC 235: Data Structures (2021 Winter)
- CISC 351: Advanced Data Analytics (2020 Winter)
- CISC 102: Discrete Mathematics For Computing (2019 Winter) -->


# Academic Services
- **Program chair**: 
  - [LTB 2026](https://ltb2026.github.io/)
- **Program committee member**: 
  - [ICPC 2026 (RENE Track)](https://conf.researchr.org/track/icpc-2026/icpc-2026-replications-and-negative-results--rene-)
  - [FSE 2026 (Industry Track)](https://conf.researchr.org/committee/fse-2026/fse-2026-industry-papers-program-committee)
  - [LLM4Code 2026](https://llm4code.github.io/pc/)
  - [SANER 2026 (Research Track)](https://conf.researchr.org/track/saner-2026/saner-2026-papers)
  - [ISSRE 2025 (Artifact Evaluation Track)](https://issre.github.io/2025/committee_artifact-evaluation-PC.html)
  - [AIware 2025 (Main Track)](https://2025.aiwareconf.org/track/aiware-2025-papers)
  - [SANER 2025 (Tool Demo Track)](https://conf.researchr.org/committee/saner-2025/saner-2025-tool-demo-track--program-commitee)
  - [ICPC 2025 (RENE Track)](https://conf.researchr.org/track/icpc-2025/icpc-2025-replications-and-negative-results--rene-)
  - [LTB 2025](https://ltb2025.github.io/)
  - [PROMISE 2025](https://conf.researchr.org/committee/promise-2025/promise-2025-papers-program-committee)
- **Reviewer:** ASE, SPE, ICPE, SANER, ICPC, EMSE, PROMISE, IEEE Software, LTB, AIware.


<!-- # Mentoring

## PhD students
- Hetong Dai
- Haonan Zhang
- Jianchen Zhao
- Tongwei Zhang
- Xiaohui Wang
- Yuanjie Xia

## Master students
- An Chen
- Mostafa Jangali
- Xiaoyu Cheng
- Yixi Zhao -->
  

<!-- # 📖 Educations -->

<!-- <span class='anchor' id='educations'></span>

# Educations

- Ph.D. in Software Engineering, Queen's University, 2024
- M.A.Sc in Software Engineering, Concordia University, 2018 -->
<!-- - B.Eng. in Internet of Things (IoT) Engineering, Wuhan University of Technology, 2015 -->



<!-- # 💻 Industrial experiences -->
<span class='anchor' id='industrial_expriences'></span>

# Industrial experiences

- **Research Collaborator** (2024.04 - 2025.03)
  
  [Wind River](https://www.windriver.com/) (Remote)

  Topics: Large language model (LLM), Requirement Engineering

- **Research Intern** (2023.01 - 2023.08) 
  
  [Blackberry Ltd](https://www.blackberry.com/), Waterloo, ON, Canada

  Topics: Large language model (LLM), RAG-based Code Generation, Predictive Analytics, Personally Identifiable Information (PII) Detection

- **Research Intern** (2020.05 - 2020.08)
  
  [Blackberry Ltd](https://www.blackberry.com/) (Remote)

  Topics: Natural Lanugage Processing (NLP), Log Analysis

- **Research Intern** (2017.01 - 2018.08)  
  
  [ERA Environmental Management Solutions](https://www.era-environmental.com/), Montreal, QC, Canada

  Topics: Performance Modeling, Performance Testing




<!-- # 💬 Invited Talks -->
<span class='anchor' id='invited-talks'></span>

# Invited Talks


- Consortium for Software Engineering Research (CSER 2024), Kingston, Canada. *Improving state-of-the-art compression techniques for log management tools*
- Blackberry Ltd, Waterloo, Canada (2021). *Log Compression Techniques: Evaluation of Compression Options and New Approach to Preprocessing for Improved Compression*
- The 9th ACM/SPEC International Conference on Performance Engineering (ICPE 2018), Berlin, Gemany. *Log4perf: Suggesting logging locations for web-based systems' performance monitoring*
  