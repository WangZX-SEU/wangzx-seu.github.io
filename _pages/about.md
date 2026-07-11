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

<style>
  /* 这里的样式会直接注入到当前页面，优先级最高 */
  .pub-block {
    margin-bottom: 2rem !important;
    text-align: left !important;
  }
  .p-title {
    font-size: 1.125rem !important; /* 约 24px */
    font-weight: bold !important;
    line-height: 1.2 !important;
    display: block !important;
    margin-bottom: 0.4rem !important;
    border: none !important; /* 彻底去掉可能出现的横线 */
    color: var(--global-text-color) !important;
  }
  .p-author {
    font-size: 1.125rem !important; /* 约 16px */
    display: block !important;
    margin-bottom: 0.2rem !important;
    color: var(--global-text-color) !important;
  }
  .p-firstauthor {
      font-size: 1.125rem !important;
      display: inline !important; 
      margin-bottom: 0.2rem !important;
      color: #003399 !important; 
      font-weight: bold !important;
      text-decoration: underline !important;
  }
  .p-journal {
    font-size: 1rem !important; /* 约 16px */
    display: block !important;
    color: var(--global-text-color) !important;
  }
  .hr-lbold {
    border: 0 !important;
    border-top: 0.2px solid #ccc !important; /* 2px 粗细，颜色可改 */
    margin: 2rem 0 !important;
  }
  .hr-bold {
    border: 0 !important;
    border-top: 0.5px solid #ccc !important; /* 2px 粗细，颜色可改 */
    margin: 2rem 0 !important;
  }
  .hrr-bold {
    border: 0 !important;
    border-top: 2px solid #ccc !important; /* 2px 粗细，颜色可改 */
    margin: 2rem 0 !important;
  }
</style>

# 🙋‍ Who am I
I am Zhuoxuan Wang, a third-year Ph.D. candidate at Southeast University, Nanjing, China, supervised by Professor Shuguo Pan.  

My research interests include **robot autonomous exploration**, **motion planning**, **RL-based decision making**, and **data-driven system identification**. Additionally, I am exploring topics related to **semantic recognition**, **VLM**, and **embodied intelligence**.  

I am also exploring the ways to work with **AI agents**, which is very interesting 😊. Embracing the trends, seizing the momentum! 

# 📖 Educations
- **2021.09 — Present**: Ph.D. candidate in an **Integrated Master–Ph.D. Program** at Southeast University, Nanjing, China. Doctoral Advisor: Shuguo Pan. Master’s Advisor: Lihui Wang. 
- **2017.09 — 2021.06**: B.E. in Measurement and Control Technology and Instrumentation from Harbin Engineering University. 

# 📰 News
## 2026
- **2026.07.07**: My latest co-authored work "C2GS-Loc: Confidence Guided Gaussian Splatting Map for Visual Localization" has been submmited to *IEEE Internet of Things Journal (IoTJ)*.
- **2026.07.06**: My latest work "SEKIRO: A Structure-Enhanced and Koopman-Integrated Deep Reinforcement Learning Framework for Robot Exploration" has been submmited to *IEEE Transactions on Industrial Informatics (TII)*.
- **2026.06.28**: My co-first author work entitled "PACE: Passability and Memory Integrated Exploration for UAVs in Large-scale and Cluttered Environments" has been acceped by *IEEE Robotics and Automation Letters (RAL)* 🎉🎉.
- **2026.05.28**: I have officially received funding from CSC and expect to start my visiting in **Sapienza University of Rome** in *2026.09* 🎉🎉.
- **2026.05.10**: My latest co-authored work "A Novel LiDAR-Inertial Integrated Implicit Localization Framework via Uncertainty-Aware Scene Coordinate Regression" has been submmited to *IEEE Transactions on Industrial Informatics (TII)*.
- **2026.03.23**: The work co-authored with my collaborator **Aohua Liu** entitled "Learning Physics-Aware Sensorimotor Model with Visual-Tactile Sensing for Deformable Linear Object Manipulation" has been accepted by *IEEE/ASME Transactions on Mechatronics (T-MECH)* 🎉🎉.
- **2026.02.01**: My work entitled "TIPS: Tiered Information-Rich Planning Strategy for Efficient AGV Autonomous Exploration" published on *IEEE Robotics and Automation Letters (RAL)* has been transferred to and accpeted by *IEEE International Conference on Robotics and Automation (ICRA) 2026, Vienna* 🎉🎉.
- **2026.01.19**: My co-authored work entitled "Hierarchical active path-planning based on edge-and-corner region guidance for unmanned platform" has been acceped by *Chinese Journal of Scientific Instrument* 🎉🎉.
- **2026.01.04**: My work entitled "Data-driven Modeling with Deep Koopman Operator for Robust Path Tracking of Autonomous Vehicles" has been acceped by *IEEE Transactions on Industrial Electronics (TIE)* 🎉🎉.

## 2025
- **2025.12.01**: I have received an invitation from **Sapienza University of Rome** for a one-year CSC visiting program (*2026.09 — 2027.10*).  
  My host professor will be <a href="https://scholar.google.com/citations?hl=zh-CN&user=xZwripcAAAAJ" target="_blank"><strong>Daniele Nardi</strong></a>.  
  My research topic will focus on **semantic exploration and navigation for humanoid robots**.
- **2025.10.16**: Our paper entitled "TIPS: Tiered Information-Rich Planning Strategy for Efficient AGV Autonomous Exploration" has been acceped by *IEEE Robotics and Automation Letters (RAL)* 🎉🎉.
- **2025.05.06**: I have been awarded the "Postgraduate Research＆Practice Innovation Program of Jiangsu Province" (*2025.05 — 2028.09*).

# 📝 Publications

## 🔹 Student First Author († indicates equal contribution)
<br>
<img align="left" width="360" src="/images/2026-TII.png" style="margin-right:15px; margin-top:5px; object-fit:cover; border-radius:4px;">

<div class="pub-block">
  <span class="p-title">SEKIRO: A Structure-Enhanced and Koopman-Integrated Deep Reinforcement Learning Framework for Robot Exploration (Under Review)</span>
  <span class="p-author"> <span class="p-firstauthor">Zhuoxuan Wang</span>, Yuxiang Gao, Shuguo Pan*, Jinle Xu, Aohua Liu, Hong Liu, Xianlu Tao.</span>
  <span class="p-journal"><i>IEEE Transactions on Industrial Informatics (<strong>Q1, IF=9.9</strong>)</i>, 2026.<br>
  <img align="absmiddle" width="16" src="/images/pdf.png" style="margin-right:4px;"> [Paper] &nbsp;&nbsp;&nbsp;
  <img align="absmiddle" width="16" src="/images/homepage.png" style="margin-right:4px;"> [Project Page]</span>
</div>
<div style="clear:both;"></div>

<hr class="hr-bold">

<img align="left" width="360" src="/images/2026-RAL.png" style="margin-right:15px; margin-top:5px; object-fit:cover; border-radius:4px;">

<div class="pub-block">
  <span class="p-title">PACE: Passability and Memory Integrated Exploration for UAVs in Large-scale and Cluttered Environments. (Under Review)</span>
  <span class="p-author">Yuxiang Gao†, <span class="p-firstauthor">Zhuoxuan Wang†</span>, Xianlu Tao*, Jinle Xu, Shuguo Pan.</span>  
  <span class="p-journal"><i>IEEE Robotics and Automation Letters (<strong>Q1, IF=5.3</strong>)</i>, 2026. <br>
  <img align="absmiddle" width="16" src="/images/pdf.png" style="margin-right:4px;"> <a href="https://ieeexplore.ieee.org/document/11600998">[Paper]</a> &nbsp;&nbsp;&nbsp;
  <img align="absmiddle" width="16" src="/images/homepage.png" style="margin-right:4px;"> <a href="https://github.com/gaoyuxiang-seu/PACE">[Project Page]</a></span>
</div>
<div style="clear:both;"></div>

<hr class="hr-bold">

<img align="left" width="360" src="/images/2026-TIE.png" style="margin-right:15px; margin-top:5px; object-fit:cover; border-radius:4px;">

<div class="pub-block">
  <span class="p-title">Data-driven Modeling with Deep Koopman Operator for Robust Path Tracking of Autonomous Vehicles</span>
  <span class="p-author"> <span class="p-firstauthor">Zhuoxuan Wang</span>, Shuguo Pan*, Kegen Yu, Wang Gao and Zongliang Chen.</span>
  <span class="p-journal"><i>IEEE Transactions on Industrial Electronics (<strong>Q1, IF=7.2</strong>)</i>, 2026. <br>
  <img align="absmiddle" width="16" src="/images/pdf.png" style="margin-right:4px;"> <a href="https://ieeexplore.ieee.org/document/11373019">[Paper]</a> &nbsp;&nbsp;&nbsp;
  <img align="absmiddle" width="16" src="/images/homepage.png" style="margin-right:4px;"> <a href="https://github.com/WangZX-SEU/SST-Rev-DKN">[Project Page]</a></span>
</div>
<div style="clear:both;"></div>

<hr class="hr-bold">

<img align="left" width="360" src="/images/2025-RAL-TIPS.png" style="margin-right:15px; margin-top:5px; object-fit:cover; border-radius:4px;">

<div class="pub-block">
  <span class="p-title">TIPS: Tiered Information-Rich Planning Strategy for Efficient UGV Autonomous Exploration</span>
  <span class="p-author"><span class="p-firstauthor">Zhuoxuan Wang</span>, Shuguo Pan*, Jinle Xu, Xianlu Tao, Wang Gao and Qiang Wang.</span>
  <span class="p-journal"><i>IEEE Robotics and Automation Letters (<strong>Q1, IF=5.3</strong>)</i>, 2025 && <I>IEEE <strong>ICRA 2026</strong></I>. <br>
  <img align="absmiddle" width="16" src="/images/pdf.png" style="margin-right:4px;"> <a href="https://ieeexplore.ieee.org/document/11214391">[Paper]</a> &nbsp;&nbsp;&nbsp;
  <img align="absmiddle" width="16" src="/images/homepage.png" style="margin-right:4px;"> <a href="https://github.com/WangZX-SEU/TIPS">[Project Page]</a></span>
</div>
<div style="clear:both;"></div>

<hr class="hr-bold">

<img align="left" width="360" src="/images/2024-TIV.png" style="margin-right:15px; margin-top:5px; object-fit:cover; border-radius:4px;">

<div class="pub-block">
  <span class="p-title">A Path Planning Framework Based on an Improved Weighted Heuristic RRT and Optimization Strategy</span>
  <span class="p-author">Lihui Wang*, <span class="p-firstauthor">Zhuoxuan Wang</span>, Zehua Ying, Xiao Bai, Ninghui Xu.</span>
  <span class="p-journal"><i>IEEE Transactions on Intelligent Vehicles (<strong>Q1, IF=14.3</strong>)</i>, 2023. <br>
  <img align="absmiddle" width="16" src="/images/pdf.png" style="margin-right:4px;"> <a href="https://ieeexplore.ieee.org/document/10266793">[Paper]</a></span>
</div>
<div style="clear:both;"></div>

<hr class="hr-bold">

<img align="left" width="360" src="/images/2023-JIRS.png" style="margin-right:15px; margin-top:5px; object-fit:cover; border-radius:4px;">

<div class="pub-block">
  <span class="p-title"> Full Coverage Path Planning Methods of Harvesting Robot with Multi-Objective Constraints</span>
  <span class="p-author">Lihui Wang*, <span class="p-firstauthor">Zhuoxuan Wang</span>, Mingjie Liu, Zehua Ying, Ninghui Xu, Qian Meng.</span>
  <span class="p-journal"><i>Journal of Intelligent & Robotic Systems (<strong>Q3, IF=2.8</strong>)</i>, 2022. <br>
  <img align="absmiddle" width="16" src="/images/pdf.png" style="margin-right:4px;"> <a href="https://link.springer.com/article/10.1007/s10846-022-01722-0">[Paper]</a></span>
</div>
<div style="clear:both;"></div>

<hr class="hr-bold">

<br>

## 🔸 Co-author
<br>
<img align="left" width="360" src="/images/2026-IoTJ.png" style="margin-right:15px; margin-top:5px; object-fit:cover; border-radius:4px;">

<div class="pub-block">
  <span class="p-title">C2GS-Loc: Confidence Guided Gaussian Splatting Map for Visual Localization (Under Review)</span>
  <span class="p-author">Jinle Xu, Wang Gao*, Min Wei, <span class="p-firstauthor">Zhuoxuan Wang</span>, Hong Liu, Shuguo Pan, Bernard De Baets.</span>
  <span class="p-journal"><i>IEEE Internet of Things Journal (<strong>Q1, IF=8.7</strong>)</i>, 2026. <br>
  <img align="absmiddle" width="16" src="/images/pdf.png" style="margin-right:4px;">[Paper]</span>
</div>
<div style="clear:both;"></div>

<hr class="hr-bold">

<img align="left" width="360" src="/images/2026-TII-L.png" style="margin-right:15px; margin-top:5px; object-fit:cover; border-radius:4px;">

<div class="pub-block">
  <span class="p-title">A Novel LiDAR-Inertial Integrated Implicit Localization Framework via Uncertainty-Aware Scene Coordinate Regression (Under Review)</span>
  <span class="p-author">Hong Liu, Wang Gao*, Shuguo Pan, Jinle Xu, Feixuan Huang, <span class="p-firstauthor">Zhuoxuan Wang</span>.</span>
  <span class="p-journal"><i>IEEE Transactions on Industrial Informatics (<strong>Q1, IF=9.9</strong>)</i>, 2026. <br>
  <img align="absmiddle" width="16" src="/images/pdf.png" style="margin-right:4px;">[Paper]</span>
</div>
<div style="clear:both;"></div>

<hr class="hr-bold">

<img align="left" width="360" src="/images/2026-TMECH.png" style="margin-right:15px; margin-top:5px; object-fit:cover; border-radius:4px;">

<div class="pub-block">
  <span class="p-title">Learning Physics-Aware Sensorimotor Model with Visual-Tactile Sensing for Deformable Linear Object Manipulation</span>
  <span class="p-author">Aohua Liu, Kun Qian*, Zhaokun Yue, <span class="p-firstauthor">Zhuoxuan Wang</span>, Boyi Duan, Shan Luo.</span>
  <span class="p-journal"><i>IEEE/ASME Transactions on Mechatronics (<strong>Q1, IF=7.3</strong>)</i>, 2026. <br>
  <img align="absmiddle" width="16" src="/images/pdf.png" style="margin-right:4px;"> <a href="https://ieeexplore.ieee.org/document/11482717">[Paper]</a></span>
</div>
<div style="clear:both;"></div>

<hr class="hr-bold">

<img align="left" width="360" src="/images/2026-YQYB.png" style="margin-right:15px; margin-top:5px; object-fit:cover; border-radius:4px;">

<div class="pub-block">
  <span class="p-title"> Hierarchical active path-planning based on edge-and-corner region guidance for unmanned platform.</span>
  <span class="p-author">Xianlu Tao*, Jiaxuan Liu, <span class="p-firstauthor">Zhuoxuan Wang</span>, Shuguo Pan, Jinle Xu.</span>
  <span class="p-journal"><i>Chinese Journal of Scientific Instrument (<strong>EI</strong>)</i>, 2026. <br>
  <img align="absmiddle" width="16" src="/images/pdf.png" style="margin-right:4px;"> <a href="https://kns.cnki.net/kcms2/article/abstract?v=A2Z-m-A1gclQAKwazEiLRF2GXCvVztBoxaWAU1l-OFyJGEsUdUqjmLhzSVjC7GWX2-CPvX5INAebGU8p7W8lskZ1X5j8d4fPvxWyGyt84LOOKInsiXwB-gyxWLmZLtTtX6W7h23iuZE7hGJNKPLxErNBzp4bGoqK&uniplatform=NZKPT">[Paper]</a></span>
</div>
<div style="clear:both;"></div>

<hr class="hr-bold">

<img align="left" width="360" src="/images/2025-TITS.png" style="margin-right:15px; margin-top:5px; object-fit:cover; border-radius:4px;">

<div class="pub-block">
  <span class="p-title">Fusion Control Tracking Strategy for Autonomous Vehicles: A Fast PPO Reinforcement Learning Based on Attention Mechanism and Physical</span>
  <span class="p-author"> Zongliang Chen, Shuguo Pan*, Kegen Yu, Yuting Wu, Wang Gao, <span class="p-firstauthor">Zhuoxuan Wang</span>, Xiaolin Meng.</span>
  <span class="p-journal"><i>IEEE Transactions on Intelligent Transportation Systems (<strong>Q1, IF=8.4</strong>)</i>, 2025. <br>
  <img align="absmiddle" width="16" src="/images/pdf.png" style="margin-right:4px;"> <a href="https://ieeexplore.ieee.org/document/11173260">[Paper]</a></span>
</div>
<div style="clear:both;"></div>

<hr class="hr-bold">

<img align="left" width="360" src="/images/RAL-2025.png" style="margin-right:15px; margin-top:5px; object-fit:cover; border-radius:4px;">

<div class="pub-block">
  <span class="p-title">A Fast PPO Reinforcement Learning Based on Attention Mechanism and Physical Information</span>
  <span class="p-author">Yuting Wu, Shuguo Pan*, Zongliang Chen, <span class="p-firstauthor">Zhuoxuan Wang</span>, Wang Gao, Xianlu Tao.</span>
  <span class="p-journal"><i>IEEE Robotics and Automation Letters (<strong>Q1, IF=5.3</strong>)</i>, 2025. <br>
  <img align="absmiddle" width="16" src="/images/pdf.png" style="margin-right:4px;"> <a href="https://ieeexplore.ieee.org/document/11184172">[Paper]</a></span>
</div>
<div style="clear:both;"></div>

<hr class="hr-bold">

<img align="left" width="360" src="/images/2022-JIRS.png" style="margin-right:15px; margin-top:5px; object-fit:cover; border-radius:4px;">

<div class="pub-block">
  <span class="p-title"> The sliding mode controller with improved reaching law for harvesting robots Constraints</span>
  <span class="p-author">Nan Qiao, Lihui Wang*,  Mingjie Liu, <span class="p-firstauthor">Zhuoxuan Wang</span>.</span>
  <span class="p-journal"><i>Journal of Intelligent & Robotic Systems (<strong>Q3, IF=2.8</strong>)</i>, 2022. <img align="absmiddle" width="16" src="/images/pdf.png" style="margin-right:4px;"> <a href="https://link.springer.com/article/10.1007/s10846-021-01536-6">[Paper]</a></span>
</div>
<div style="clear:both;"></div>

<hr class="hr-bold">

# 🎖 Honors and Awards
- **2025.10**: &nbsp; Third-Class Scholarship for Doctoral Students of Southeast University (￥10,000).
- **2023.10**: &nbsp; Outstanding Student of Southeast University.
- **2022.11**: &nbsp; National Scholarship (￥20,000). 
- **2022.09**: &nbsp; Individual Advanced in Academic Transcript of Southeast University.
- **2022.09**: &nbsp; First-Class Scholarship for Postgraduate Students of Southeast University (￥12,000).
- **2021.09**: &nbsp; Second-Class Scholarship for Postgraduate Students of Southeast University (￥10,000).
- **2018.05 — 2020.11**: &nbsp; First-Class Scholarship for Undergraduate Students of Harbin Engineering University ×6 (￥400).

# 🔧 Interesting Tools Developed with AI Agents
I have mainly used **Claude Code** and **Cursor**, and currently have developed two projects with the help of AI agents:  
- **OpenClaw Virtual Machine Isolation Installation Guide** &nbsp;&nbsp;<img align="absmiddle" width="16" src="/images/homepage.png" style="margin-right:4px;"> [[Project page]](https://github.com/WangZX-SEU/openclaw-guide)  
A detailed OpenClaw virtual machine isolation installation guide designed specifically for running OpenClaw through VirtualBox on Ubuntu 24.04 hosts. It includes detailed steps, precautions, and is very suitable for users who want to use OpenClaw on Ubuntu but are concerned about contaminating local files.  
_(Based on this guidance, I have configured two 🦐 workers on my **Feishu** app for paper summary and daily AI news organization)_ 😀.
- **ArXiv Paper Crawler** &nbsp;&nbsp;&nbsp;<img align="absmiddle" width="16" src="/images/homepage.png" style="margin-right:4px;"> [[Project page]](https://github.com/WangZX-SEU/wangzx-seu.github.io)  
Forked from <a href="https://github.com/RayeRen/acad-homepage.github.io" target="_blank">RayeRen's project</a>, added daily automated crawling, daily report generation, and the function of summarizing papers by specific authors.  

# 🏃‍ Activities
- **2026.06**: &nbsp; Attending the *IEEE International Conference on Robotics and Automation (ICRA) 2026* at Vienna, Austria (Poster).
- **2025.10**: &nbsp; Attending the *IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS) 2025* at Hangzhou, China.
- **2024.11**: &nbsp; Attending the *Autonomous Robotic Technology Seminar (ARTS) 2024* at Shenzhen, China.

# ✒ Peer Review Services
- Reviewer of *IEEE T-IE, IEEE RA-L*.

# 🤝 Collaborators
- [Aohua Liu](https://orcid.org/0000-0002-2526-5879), Ph.D. candidate in the School of Automation, Southeast University, Nanjing, China.
