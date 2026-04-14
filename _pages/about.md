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

I am currently a researcher at [Beijing Institute for General Artificial Intelligence (BIGAI)](https://www.bigai.ai/). Prior to that, I interned at the Tencent Robotics X Lab, under the guidance of [Yu Zheng](https://scholar.google.com/citations?user=oBXTTesAAAAJ&hl=en) and [Yonggen Ling](https://ygling2008.github.io/). I obtained the Ph.D degree from Queen Mary, University of London (QMUL), U.K., jointly supervised by Prof. [Kaspar Althoefer](https://www.sems.qmul.ac.uk/staff/k.althoefer) and Prof. [Akram Alomainy](http://www.eecs.qmul.ac.uk/~akram/). I obtained my BEng degree from Beijing University of Posts and Telecommunications (BUPT) and QMUL, supervised by Prof. [Khalid Z Rajab](https://www.qmul.ac.uk/eecs/people/profiles/rajabkhalid.html).<br>
<br>

My research interests mainly focus on force and tactile sensing. I have published papers in top-tier robotic international journals and conferences such as NMI, T-RO, RA-L, IEEE Sensors, RSS, ICRA, IROS, RoboSoft.<br>
<br>


<br>
🔥 News
- 2025.06   two IROS papers accepted!
- 2025.06   one NMI paper [F-Tac Hand](https://www.nature.com/articles/s42256-025-01053-3) accepted!
- 2025.05   one [TCE paper](https://ieeexplore.ieee.org/abstract/document/11039652) accepted!
- 2025.04   one RSS paper [PP-Tac](https://peilin-666.github.io/projects/PP-Tac/) accepted!
- 2025.03   [PP-Tac](https://peilin-666.github.io/projects/PP-Tac/) is accepted to ICLR 7th Robot Learning Workshop as a oral paper!
- 2024.11   one TRO paper [Tac-Man](https://tacman-aom.github.io/) accepted!
- 2024.10   one RA-L paper [MiniTac](https://ieeexplore.ieee.org/document/10737431) accepted!


<br>
# 📝 Selected Publications 
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Nature Machine Intelligence</div><img src='images/NMI_Hand.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Embedding high-resolution touch across robotic hands enables adaptive human-like grasping](https://www.nature.com/articles/s42256-025-01053-3)

Zihang Zhao<sup>*</sup>, **Wanlin Li<sup>*</sup>**, Yuyang Li<sup>*</sup>, Tengyu Liu<sup>*</sup>, Boren Li, Meng Wang, Kai Du, Hangxin Liu<sup>†</sup>, Yixin Zhu<sup>†</sup>, Qining Wang, Kaspar Althoefer<sup>†</sup>, Song-Chun Zhu

**Nature Machine Intelligence <span style="color: blue;">(NMI)</span>**
- [Video](https://vimeo.com/1039184307)
</div>
</div>

<!--
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2026</div><img src='images/ICLR2026.gif' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[DexMove: Learning Tactile-Guided Non-Prehensile Manipulation with Dexterous Hands](https://peilin-666.github.io/projects/DexMove/)

Pei Lin<sup>*</sup>, Yuzhe Huang<sup>*</sup>, **Wanlin Li<sup>*</sup>**, Chenxi Xiao<sup>†</sup>, Ziyuan Jiao<sup>†</sup>

**The Fourteenth International Conference on Learning Representations <span style="color: blue;">(ICLR 2026)</span>** 
</div>
</div>
-->



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">RSS 2025</div><img src='images/RSS2025.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[PP-Tac: Paper Picking Using Tactile Feedback in Dexterous Robotic Hands](https://peilin-666.github.io/projects/PP-Tac/)

Pei Lin<sup>*</sup>, Yuzhe Huang<sup>*</sup>, **Wanlin Li<sup>*</sup>**, Jianpeng Ma, Chenxi Xiao<sup>†</sup>, Ziyuan Jiao<sup>†</sup>

**Robotics: Science and Systems 2025 <span style="color: blue;">(RSS 2025)</span>**

**7th Robot Learning Workshop in ICLR 2025, <span style="color: blue;">oral</span>**
- [R-Tac Sensor Fabrication Video](https://www.youtube.com/watch?v=-npk0cRKWGI&t=32s)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IROS 2025</div><img src='images/RTac0.gif' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[R-Tac0: A Rounded High-Frequency Transferable Monochrome Vision-based Tactile Sensor for Shape Reconstruction](https://ieeexplore.ieee.org/document/11246144)

**Wanlin Li<sup>*</sup>**, Pei Lin<sup>*</sup>, Meng Wang, Chenxi Xiao, Kaspar Althoefer, Yao Su<sup>†</sup>, Ziyuan Jiao<sup>†</sup>, Hangxin Liu<sup>†</sup>

**2025 IEEE/RSJ International Conference on Intelligent Robots and Systems <span style="color: blue;">(IROS 2025)</span>**

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">T-RO</div><img src='images/T-RO.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Tac-Man: Tactile-Informed Prior-Free Manipulation of Articulated Objects](https://tacman-aom.github.io/)

Zihang Zhao<sup>*</sup>, Yuyang Li<sup>*</sup>, **Wanlin Li**, Zhenghao Qi, Lecheng Ruan<sup>†</sup>, Yixin Zhu<sup>†</sup>, Kaspar Althoefer

**IEEE Transactions on Robotics <span style="color: blue;">(T-RO)</span>**
- [Video](https://vimeo.com/1026777549)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">RA-L</div><img src='images/RALMiniTac.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[MiniTac: An Ultra-Compact 8 mm Vision-Based Tactile Sensor for Enhanced Palpation in Robot-Assisted Minimally Invasive Surgery](https://arxiv.org/abs/2410.22691)

**Wanlin Li<sup>*</sup>**, Zihang Zhao<sup>*</sup>, Leiyao Cui<sup>*</sup>, Weiyi Zhang<sup>*</sup>, Hangxin Liu, Li-An Li<sup>†</sup>, Yixin Zhu<sup>†</sup>

**IEEE Robotics and Automation Letters <span style="color: blue;">(RA-L)</span>**
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">RA-L</div><img src='images/RALL3FTOUCH.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[L3 F-TOUCH: A Wireless GelSight with
Decoupled Tactile and Three-axis Force Sensing](https://www.researchgate.net/publication/372136046_L3_F-TOUCH_A_Wireless_GelSight_with_Decoupled_Tactile_and_Three-axis_Force_Sensing)

**Wanlin Li<sup>*</sup>**, Meng Wang<sup>*</sup>, Jiarui Li, Yao Su<sup>†</sup>, Devesh K. Jha, Xinyuan Qian,
Kaspar Althoefer and Hangxin Liu<sup>†</sup>

**IEEE Robotics and Automation Letters <span style="color: blue;">(RA-L)</span>**
</div>
</div>


# 💬 Reviewer
- Reviewer of T-RO, RA-L, IEEE Sensors Journal, ICRA, IROS, AIM



<!-- Google Analytics -->
<script async src="https://catherine-qian.github.io/"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'GA_MEASUREMENT_ID');
</script>
<!-- End Google Analytics -->




