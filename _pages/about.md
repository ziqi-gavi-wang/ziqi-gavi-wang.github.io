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

I am currently a master student at [the State Key Laboratory of Robotics and Systems](http://robot.hit.edu.cn) at [Harbin Institute of Technology](https://www.hit.edu.cn) , mainly engaged in the research of exoskeleton robots and soft robots.

I earned my bachelor’s degree at [School of Mechanical and Aerospace Engineering](https://mae.jlu.edu.cn) at [Jilin University](https://www.jlu.edu.cn) , under the guidance of [Prof. Zhihui Zhang](https://cbae.jlu.edu.cn/info/1221/3883.htm?eqid=ce15c342000be4c00000000364413dba). Now, I am pursuing a master's degree in the research group of [Prof. Jie Zhao](https://homepage.hit.edu.cn/zhaojie), Director of the Robotics Institute of Harbin Institute of Technology, under the guidance of [Prof. Yanhe Zhu](https://homepage.hit.edu.cn/zhuyanhe).

My research interest includes preference-based optimizations of exoskeleton assistance during walking 🚶 and anti-interference soft manipulator with precise motion controller 🐙 . I have published 4 papers in top international journals and 2 papers in top international robotics conferences with total <a href='https://scholar.google.com/citations?user=uQ24fEgAAAAJ'>google scholar citations <strong><span id='total_cit'>40+</span></strong></a> .


# 🔥 News
- *2024.06.30*: &nbsp;🎉🎉🎉My paper has been accepted for publication in the Proceedings of the 2024 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS 2024) as oral pitch and interactive presentation.


# 📖 Educations
- *2022.06 - now*, Robotics Engineering, [the State Key Laboratory of Robotics and Systems](http://robot.hit.edu.cn), [Harbin Institute of Technology](https://www.hit.edu.cn), Harbin. 
- *2018.09 - 2022.06*, Mechanical Engineering, [School of Mechanical and Aerospace Engineering](https://mae.jlu.edu.cn), [Jilin University](https://www.jlu.edu.cn), Changchun.


# 💻 Internships
- *2024.07 - 2024.08*, [Institute of Automation，Chinese Academy of Sciences](http://www.ia.cas.cn), Beijing, China.


# 📝 Publications 

<!-- Paper 2024.7 -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE Transactions on Robotics</div><img src='images/elephant.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**Disturbance-Adaptive Tapered Soft Manipulator with Precise Motion Controller for Enhanced Task Performance**](https://ieeexplore.ieee.org/document/10577463)

Xianglong Li, Quan Xiong, Dongbao Sui, Qinghua Zhang, Hongwu Li, **Ziqi Wang**, Tianjiao Zheng, Hesheng Wang, Jie Zhao, Yanhe Zhu

[**Paper**](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10577463)
- A novel cable–pneumatic hybrid-driven tapered soft manipulator (TSM) design and control scheme to enhance the performance in actual tasks.
- Experimental results [spatial point positioning error (mean error of stable region: 0.17 mm), circular trajectory tracking error (mean and standard deviation (SD) of 100 trials: 0.87 ± 0.57 mm), orientation control error (less than 1 ∘ )].

[**YouTube**](https://www.youtube.com/watch?v=-eOcdWlXXww) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>

</div>
</div>

<!-- Paper 2024.5 -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">2024 IEEE International Conference on Robotics and Automation (ICRA)</div><img src='images/preference.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**Human-Exoskeleton Locomotion Interaction Experience Transfer: Speeding up and Improving the Performance of Preference-based Optimizations of Exoskeleton Assistance During Walking**](https://ieeexplore.ieee.org/abstract/document/10611497)

Hongwu Li, Junchen Liu, **Ziqi Wang**, Haotian Ju, Tianjiao Zheng, Yongsheng Gao, Jie Zhao, Yanhe Zhu

[**Paper**](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10611497)
- A novel preference-based human-exoskeleton locomotion interaction experience transfer (LIET) framework, which could speed up the exploration of human-preferred parameters and acquire more satisfying results for naive wearers via the HELIE acquired from knowledgeable wearers.
- Established the mathematical expression of the HELIE transfer during exoskeleton assistance based on the proposed LIET framework.

[**YouTube**](https://www.youtube.com/watch?v=vJgKvAGbhEc&t=31s) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>

</div>
</div>

<!-- Paper 2023.11 -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Biomimetics</div><img src='images/force.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**Ground Contact Force and Moment Estimation for Human–Exoskeleton Systems Using Dynamic Decoupled Coordinate System and Minimum Energy Hypothesis**](https://www.mdpi.com/2313-7673/8/8/558)

Hongwu Li, Haotian Ju, Junchen Liu, **Ziqi Wang**, Qinghua Zhang, Xianglong Li, Yi Huang, Tianjiao Zheng, Jie Zhao, Yanhe Zhu

- A novel method for estimating CFMs based on a proposed dynamic decoupled coordinate system (DDCS) and the minimum energy hypothesis.
- By decomposing CFMs into a DDCS, the number of unknowns can be significantly reduced from twelve to two. 

</div>
</div>

<!-- Paper 2023.11 -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Materials Today Chemistry</div><img src='images/hydrogel.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**A bioinspired 4D printed hydrogel capsule for smart controlled drug release**](https://www.sciencedirect.com/science/article/pii/S2468519422000180)

S. Zu, Z. Wang, S. Zhang, Y. Guo, C. Chen, Q. Zhang, **Z. Wang**, T. Liu, Q. Liu, Z. Zhang

- Through a 4D printing method to produce bioinspired hydrogel capsules for smart controlled drug release.
- The 4D printed capsules featured with PNIPAM hydrogel as the shell, and the types and doses of drugs can be freely loaded.
- Drug release profiles can be well programmed by adjusting the internal pore size of the hydrogel capsules.
- In contrast to common 4D external shape change, we used 4D printing to produce change in internal material structure.

</div>
</div>

# 🎖 Honors and Awards
- *2022.12* First Prize in the National Undergraduate Electronic Design Competition. 
- *2023.12* First Prize of Harbin Institute of Technology Space Station Space Science and Payload Creative Innovation Design Competition.
- *2024.07* Second Prize of China Postgraduate Robot Innovation Design Competition.


