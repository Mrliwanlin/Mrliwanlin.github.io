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

I am currently a research scientist at [Beijing Institute for General Artificial Intelligence (BIGAI)](https://www.bigai.ai/). Prior to that, I obtained the Ph.D degree from Queen Mary, University of London (QMUL), U.K., jointly supervised by Prof. [Kaspar Althoefer](https://www.sems.qmul.ac.uk/staff/k.althoefer) and Prof. [Akram Alomainy](http://www.eecs.qmul.ac.uk/~akram/). I obtained my BEng degree from Beijing University of Posts and Telecommunications (BUPT) and QMUL, supervised by Prof. [Khalid Z Rajab](https://www.qmul.ac.uk/eecs/people/profiles/rajabkhalid.html).<br>
<br>

My research interests mainly focus on force and tactile sensing. I have published papers in top-tier robotic international journals and conferences such as NMI, TRO, RA-L, IEEE Sensors, RSS, ICRA, IROS, RoboSoft.<br>
<br>


<br>
🔥 News
- 2025.06   two IROS papers accepted!
- 2025.06   one NMI paper [F-Tac Hand](https://www.nature.com/articles/s42256-025-01053-3) accepted!
- 2025.05   one IEEE Transactions on Consumer Electronics (TCE) paper accepted!
- 2025.04   one RSS paper [PP-Tac](https://peilin-666.github.io/projects/PP-Tac/) accepted!
- 2025.03   [PP-Tac](https://peilin-666.github.io/projects/PP-Tac/) is accepted to ICLR 7th Robot Learning Workshop as a oral paper!
- 2024.11   one TRO paper [Tac-Man](https://tacman-aom.github.io/) accepted!
- 2024.10   one RA-L paper [MiniTac](https://ieeexplore.ieee.org/document/10737431) accepted!

<!-- 
# 📜 Research Area
<table style="border-collapse: collapse; border: none;">
  <tr style="border: none;">
    <td style="border: none;"> <font color="#0b5394"> Speech Processing </font>: <BR>&nbsp;&nbsp; 
      Speaker recognition and verification 说话人识别；Speech separation and extraction 语音分离；Key-word spotting 关键词检测；
    Automatic Speech Recognition 语音识别</td>
    <td style="border: none;"> <font color="#0b5394"> Computer Vision </font>: <BR>&nbsp;&nbsp; Face detection and recognition 人脸检测及识别; Lip reading 唇读；Gesture synthesis 姿态生成</td>
  </tr>
  <tr style="border: none;">
    <td style="border: none;"> <font color="#0b5394"> Multi-modal Processing </font>: <BR>&nbsp;&nbsp; Audio-visual active speaker detection 说话人活跃检测; Text-to-speech Synthesis 语音合成；Speaker Localization and Tracking 声源定位及追踪</td>
    <td style="border: none;"> <font color="#0b5394"> Self-supervised Learning </font>: <BR>&nbsp;&nbsp; Self-supervised speech processing 自监督学习 </td>
  </tr>
</table>


# 💻 Research Experiences
- *2022.10 - Present*, Associate Professor, University of Science and Technology of Beijing (USTB), Beijing, China.
- *2022.03 - 2022.09*, Visiting Scholar, Chinese University of Hong Kong (CUHKSZ), Shenzhen, China.
- *2020.02 - 2022.02*, Research Fellow, National University of Singapore (NUS), Singapore.
- *2017.04 - 2018.12*, Research Asistant, Fondazione Bruno Kessler (FBK), Trento, Italy.
- *2014.06 - 2014.08*, Research Asistant, Heriot-Watt University (HWU), Edinburgh, United Kingdom.

# 📖 Educations
- *2015.11 - 2019.11*, Ph.D. in Computer Scicence, Queen Mary, University of London (QMUL), London, U.K. 
- *2014.08 - 2015.08*, M.Sc. in Signal Processing and Communications, University of Edinburgh (UoE), U.K.  (Distinction，卓越) 
- *2012.09 - 2014.06*, B.Eng. in Electronics and Electrical Engineering, University of Edinburgh (UoE), U.K. (First Class Honors，一等荣誉) 
- *2010.09 - 2012.06*, B.Eng. in Information Engineering, Nanjing University of Aeronautics and Astronautics (NUAA), Nanjing, China. (Top: 3%)
 -->

# 📝 Selected Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Nature Machine Intelligence</div><img src='images/NMI_Hand.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Embedding high-resolution touch across robotic hands enables adaptive human-like grasping](https://www.nature.com/articles/s42256-025-01053-3)

Zihang Zhao, **Wanlin Li**, Yuyang Li, Tengyu Liu, Boren Li, Meng Wang, Kai Du, Hangxin Liu, Yixin Zhu, Qining Wang, Kaspar Althoefer, Song-Chun Zhu

**Nature Machine Intelligence**
- [Video](https://vimeo.com/1039184307)
</div>
</div>
<!-- # 📝 Representative Publications
 -- **Representative Works** --
- **Xinyuan Qian**, Zhengdong Wang, Jiadong Wang, Guohui Guan, Haizhou Li, [Audio-Visual Cross-Attention Network for Robotic Speaker Tracking](https://ieeexplore.ieee.org/document/9968308)，**IEEE/ACM Transactions on Audio, Speech and Language Processing**, 2022.
- **Xinyuan Qian**, Alessio Brutti, Oswald Lanz, Maurizio Omologo, Andrea Cavallaro, [Audio-visual tracking of concurrent speakers](https://ieeexplore.ieee.org/document/9362311), **IEEE Transactions on Multimedia**,2021.
- **Xinyuan Qian**, Alessio Brutti, Oswald Lanz, Maurizio Omologo, Andrea Cavallaro, [Multi-speaker tracking from an audio–visual sensing device](https://ieeexplore.ieee.org/document/8656587), **IEEE Transactions on Multimedia**, 2019.
- **Xinyuan Qian**, Qi Liu, Jiadong Wang, Haizhou Li, [Three-Dimensional Speaker Localization: Audio-Refined Visual Scaling Factor Estimation](https://ieeexplore.ieee.org/document/9466446), **IEEE Signal Processing Letters**, 2021.
- **Xinyuan Qian**, Qiquan Zhang, Guohui Guan and Wei Xue, [Deep Audio-visual Beamforming for Speaker Localization](https://ieeexplore.ieee.org/document/9750883), **IEEE Signal Processing Letters**, 2022.
- **Xinyuan Qian**, Bidisha Sharma, Amine El Abridi, Haizhou Li, [SLoClas: A Database for Joint Sound Localization and Classification](https://arxiv.org/abs/2108.02539), **COCOSDA**, 2021, **Best Paper Award**.
- **Xinyuan Qian**, Maulik Madhavi, Zexu Pan, Jiadong Wang, Haizhou Li, [Multi-target DoA estimation with an audio-visual fusion mechanism](https://ieeexplore.ieee.org/document/9413776), **ICASSP**, 2021.
- **Xinyuan Qian**, Alessio Xompero, Alessio Brutti, Oswald Lanz, Maurizio Omologo, Andrea Cavallaro, [3D mouth tracking from a compact microphone array co-located with a camera](https://ieeexplore.ieee.org/document/8461323), **ICASSP**，2018.
- **Xinyuan Qian**, Alessio Brutti,  Maurizio Omologo, Andrea Cavallaro, [3D audio-visual speaker tracking with an adaptive particle filter](https://ieeexplore.ieee.org/abstract/document/7952686), **ICASSP**，2017.
- **Xinyuan Qian**, Jichen Yang, Alessio Brutti, [Speaker Front-back Disambiguity using Multi-channel Speech Signals](https://ietresearch.onlinelibrary.wiley.com/doi/full/10.1049/ell2.12666?af=R), **Electronics Letters** 2022.
 -->

<!--
-- **2025** --
- Tianhao Zhang, Jiawei Zhang, Jun wang, **Xinyuan Qian<sup>`*`</sup>**, Xucheng Yin, [FaceSpeak: Expressive and High-Quality Speech Synthesis from Human Portraits of Different Styles](https://arxiv.org/pdf/2501.03181), **AAAI**, 2025
- Wei Zhang, Tian-Hao Zhang, Chao Luo, Hui Zhou, Chao Yang, **Xinyuan Qian<sup>`*`</sup>**, Xu-Cheng Yin, [Breaking Through the Spike: Spike Window Decoding for Accelerated and Precise Automatic Speech Recognition](https://arxiv.org/pdf/2501.03257), **ICASSP**, 2025
- Ruijie Tao, **Xinyuan Qian**, Yidi Jiang, Junjie Li, Jiadong Wang, Haizhou Li, [Audio-Visual Target Speaker Extraction with Selective Auditory Attention](https://ieeexplore.ieee.org/abstract/document/10835186), **TASLP**, 2025
- Jiadong Wang, **Xinyuan Qian<sup>`*`</sup>**, Haizhou Li, [Audio-Visual Target Speaker Extraction with Selective Auditory Attention](https://arxiv.org/pdf/2209.01768), **TASLP**, 2025

-- **2024** --
- **Xinyuan Qian**, Xianghu Yue, Jiadong Wang, Huiping Zhuang, Haizhou Li, [Analytic Class Incremental Learning for Sound Source Localization with Privacy Protection](https://arxiv.org/pdf/2409.07224), **SPL**, 2025
- Miao Liu, Jing Wang, **Xinyuan Qian**, Haizhou Li, [RListenFormer: Responsive Listening Head Generation with Generated Listening HGeeandesrated Listening Heads Non-autoregressive Transformers], **ACM MM**, 2024
- Xianghu Yue, Xueyi Zhang, Yiming Chen, Chengwei Zhang, Mingrui Lao, Huiping Zhuang, **Xinyuan Qian<sup>`*`</sup>**, Haizhou Li, [MMAL: Multi-Modal Analytic Learning for Exemplar-Free Audio-Visual Class Incremental Tasks], **ACM MM**, 2024
- **Xinyuan Qian**, Jingkai Xu, Yuxuan Gao, Minshu Li, Wanlin Li, Xu-Cheng Yin, [Understanding Dynamic Auditory Perception for
Water Filling Level Estimation], **IJSR**, 2024
- **Xinyuan Qian**, Hao Tang, Jichen Yang, Hongxu Zhu, Xu-Cheng Yin, [Dual-Path Transformer-Based GAN for Co-speech Gesture Synthesis](https://link.springer.com/article/10.1007/s12369-024-01136-y), **IJSR**, 2024
- Yan Liu; Li_fang Wei; **Xinyuan Qian<sup>`*`</sup>**; Tianhao Zhang; Songlu Chen; Xucheng Yin, [M3TTS: Multi-Modal Text-to-Speech of Multi-Scale Style Control for Dubbing](https://elsevier-ssrn-document-store-prod.s3.amazonaws.com/prletters/c88b9fd1-51a4-460e-a720-2ef628f60be8-meca.pdf?response-content-disposition=inline&X-Amz-Security-Token=IQoJb3JpZ2luX2VjENn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLWVhc3QtMSJGMEQCIFMqyV8AhJXpSjKDL2wwqhxKsquUvfQKAT9ATxs53bhCAiACa%2BB6HtyTHcDRuUE1NiefCvwDrzYQIFe3zhl%2Br2tE4SrGBQix%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAQaDDMwODQ3NTMwMTI1NyIMqGMe2eGr8ErOIPD9KpoF6gCT7eO4kMNbY5KFy5TF0eivao%2F9t4VOQ%2BQYPFL2xdIQd2hg0xe5l6M4sq4RS10fuwhJXItyA%2FtPuE%2BAXznaAFDrNEGP0uK78Qyem5TxGC3WQYRlVyGBcGm%2F4ebqtcEx1nxn%2F3wj2XqeY0WN67zfJAwMfVwpn%2FcrlGHESCtflJUZcViLybwovoreAx582GqfrqxX7rIr9PyrDGUKmW1D2mfIY94Sr5v2b0lzUAe%2BILdv5B0BKIGBEZ6NBjAmo85%2F1KYoJ43PY4D2zAhAZYxM0o%2BbL7I14wGgMWW822PWF1gWjTLJEN3QG2U3r8m34%2BScn0qx0oEC%2BZoWSGEmwymVOt5yzv8mWefYV2pA8mSmWBrdM9j5ts%2Bch2O%2FSbibyZFgjZiCdNPjBu29uOZq2reAnFkqBTU1fdealNkU4x4kRzQ5BRJi6EXtUCqcOlRXtxTgzq014FGvD1T2dEYeZCR%2BtcBjoyvuNDb9vb%2BjehTzT3wwD72Ryex38efR4LqmaytawnTQIdZH5OHgsWpl4x6mQpw8XLi0zBLgfBiW1Ti6cSgZxYoqSv%2FTgYdecIi%2BVupxr3HbqDYdyV6T0xP0v61aGr8QJo0OzhujH1qZErJlGzo%2Fal0PKDIq8c82%2FqeCwnb3zYq%2FujQvzrzx4jPKVy4k71kvfbofzjak5bhbIml1xZA9UuWHR1wwreEnEGOJvMy5oc6Te5kNfYyQY99jmMIzwcnNM6kx1YZyfvaIweP8u21dTbBhMZXByOMvB139AF8I5OX98BHMeHqpQ70FgsQ9luRM9Qh%2FT3IR%2FzCeWlfyLrtGBjCy4q6QZ%2Fs3wCu1rpJ3P%2FfVAn09lof7GknmI%2BFFyNLlj0cZywuDx%2BFCzGgqz10Kes6x8znJdoA6MN2vhrUGOrIBmHZ9fOQJux11cpSTU1yMmpqcjzicsBoYZu0KcaH5GCnnMX0TSnaEgjxyMHLU%2FU8Zc5iqgldXeMY9N5fyY%2FIIDEUOsZX2%2FXKGRf0iTXFlTF2MrqYzOF9aWBwDItU5NQLfLugsYgT3%2F%2BfZu1es27jZ9ouEjOnxQxKivDzSO7j6fCEOG6f4FGASIH0gkSHv9yguGiSQCOwyIR3h4LwIo%2FWnI4YQJJd6SO0PHLBtFvgRm2eB7g%3D%3D&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Date=20240725T010847Z&X-Amz-SignedHeaders=host&X-Amz-Expires=300&X-Amz-Credential=ASIAUPUUPRWE6VPFLJLM%2F20240725%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Signature=94bbbea5716ea603623bc3eb37d6f60a81764820acf8b558b7a9b574f2b4e1ab), **PRL**, 2024
- Miao Liu, Jing Wang, **Xinyuan Qian**, Xiang Xie, [Visually Guided Binaural Audio Generation with Cross-Modal Consistency](https://ieeexplore.ieee.org/abstract/document/10446399/), **PRL**, 2024
- Yu Chen, **Xinyuan Qian<sup>`*`</sup>**, Zexu Pan, Kainan Chen, Haizhou Li, [LocSelect: Target Speaker Localization with an Auditory Selective Hearing Mechanism](https://arxiv.org/pdf/2310.10497.pdf), **ICASSP**, 2024
- **Xinyuan Qian**, Zexu Pan, Qiquan Zhang, Kainan Chen, Shoufeng Lin, [GLMB 3D speaker tracking with video-assisted multi-channel audio optimization functions](https://ieeexplore.ieee.org/abstract/document/10446460), **ICASSP**, 2024

-- **2023** --
- Miao Liu, Jing Wang, **Xinyuan Qian**, Haizhou Li, [Audio-Visual Temporal Forgery Detection Using Embedding-Level Fusion and Multi-Dimensional Contrastive Loss](https://ieeexplore.ieee.org/abstract/document/10290956), *TCSVT*, 2023
- **Xinyuan Qian**, Wei Xue, Qiquan Zhang, Ruijie Tao, Yiming Wang, Kainan Chen, Haizhou Li, [Bi-directional Image-Speech Retrieval Through Geometric Consistency]， **ICCVW**, 2023
- **Xinyuan Qian**, Wei Xue, Qiquan Zhang, Ruijie Tao, Haizhou Li, [Deep Cross-modal Retrieval Between Spatial Image
and Acoustic Speech](https://ieeexplore.ieee.org/document/10285477)， **TMM**, 2023
- Tian-Hao Zhang, Hai-Bo Qin, Zhi-Hao Lai, Song-Lu Chen, Qi Liu, Feng Chen, **Xinyuan Qian<sup>`*`</sup>**, Xu-Cheng Yin [Rethinking Speech Recognition with A Multimodal Perspective via Acoustic and Semantic Cooperative Decoding](https://arxiv.org/abs/2305.14049), **INTERSPEECH**, 2023
- Longting Xu, Jichen Yang<sup>`*`</sup>, Chang Huai You, **Xinyuan Qian<sup>`*`</sup>**, Daiyu Huang, [Device Features Based on Linear Transformation With Parallel Training Data for Replay Speech Detection](https://ieeexplore.ieee.org/abstract/document/10103148), **TASLP**, 2023.
- Jiadong Wang, **Xinyuan Qian<sup>`*`</sup>**, Malu Zhang, Robby T Tan, Haizhou Li, [Seeing What You Said: Talking Face Generation Guided by a Lip Reading Expert](https://arxiv.org/pdf/2303.17480.pdf), **CVPR**, 2023.
- Tian-Hao Zhang, Qi Liu, **Xinyuan Qian<sup>`*`</sup>**, Song-Lu Chen, Feng Chen, Xu-Cheng Yin<sup>`*`</sup>, [Self-Convolution for Automatic Speech Recognition](https://ieeexplore.ieee.org/document/10095330/), **ICASSP**, 2023.
- Moran Chen, Qiquan Zhang, Qi Song, **Xinyuan Qian**, Ruijin Guo, Mingjiang Wang, Deying Chen [Neural-Free Attention for Monaural Speech Enhancement Towards Voice User Interface for Consumer Electronics](https://ieeexplore.ieee.org/abstract/document/10070570), **TCE**, 2023.
- Kaspar Althoefer, Yonggen Ling, Wanlin Li, **Xinyuan Qian**, Wang Wei Lee, Peng Qi, [A Miniaturised Camera-based Multi-Modal Tactile Sensor](https://arxiv.org/pdf/2303.03093.pdf), **ICRA**, 2023.


-- **2022** --
- **Xinyuan Qian**, Zhengdong Wang, Jiadong Wang, Guohui Guan, Haizhou Li, [Audio-Visual Cross-Attention Network for Robotic Speaker Tracking](https://ieeexplore.ieee.org/document/9968308)，**TASLP**, 2022.
- **Xinyuan Qian**, Qiquan Zhang, Guohui Guan and Wei Xue, [Deep Audio-visual Beamforming for Speaker Localization](https://ieeexplore.ieee.org/document/9750883), **SPL**, 2022.
- **Xinyuan Qian**, Jichen Yang, Alessio Brutti, [Speaker Front-back Disambiguity using Multi-channel Speech Signals](https://ietresearch.onlinelibrary.wiley.com/doi/full/10.1049/ell2.12666?af=R), **Electronics Letters** 2022.
- Zexu Pan, **Xinyuan Qian<sup>`*`</sup>**, Haizhou Li, [Speaker Extraction with Co-Speech Gestures Cue](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9774925), **SPL**, 2022.
- Qiquan Zhang, **Xinyuan Qian<sup>`*`</sup>**, Zhaoheng Ni, Aaron Nicolson, Eliathamby Ambikairajah, Haizhou Li, [TFA-SE: A Time-Frequency Attention Module for Neural Speech Enhancement](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9966661), **TASLP**, 2022.
- Hongxu Zhu, Qiquan Zhang, Peng Gao, **Xinyuan Qian**, [Speech-Oriented Sparse Attention Denoising for Voice User Interface Toward Industry 5.0](https://ieeexplore.ieee.org/abstract/document/9893339/), **TII**, 2022.
- Yanjie Fu, Meng Ge, Haoran Yin, **Xinyuan Qian**, Longbiao Wang, Gaoyan Zhang, Jianwu Dang, [Iterative Sound Source Localization for Unknown Number of Sources](https://arxiv.org/abs/2206.12273), **TNTERSPEECH**, 2022.

-- **2021** --
- **Xinyuan Qian**, Alessio Brutti, Oswald Lanz, Maurizio Omologo, Andrea Cavallaro, [Audio-visual tracking of concurrent speakers](https://ieeexplore.ieee.org/document/9362311), **TMM**,2021.
- **Xinyuan Qian**, Qi Liu, Jiadong Wang, Haizhou Li, [Three-Dimensional Speaker Localization: Audio-Refined Visual Scaling Factor Estimation](https://ieeexplore.ieee.org/document/9466446), **SPL**, 2021.
- **Xinyuan Qian**, Bidisha Sharma, Amine El Abridi, Haizhou Li, [SLoClas: A Database for Joint Sound Localization and Classification](https://arxiv.org/abs/2108.02539), **COCOSDA**, 2021, **Best Paper Award**.
- **Xinyuan Qian**, Maulik Madhavi, Zexu Pan, Jiadong Wang, Haizhou Li, [Multi-target DoA estimation with an audio-visual fusion mechanism](https://ieeexplore.ieee.org/document/9413776), **ICASSP**, 2021.
- Jiadong Wang, **Xinyuan Qian<sup>`*`</sup>**, Zihan Pan, Malu Zhang, Haizhou Li, [GCC-PHAT with Speech-oriented Attention for Robotic Sound Source Localization](https://ieeexplore.ieee.org/document/9561885), **ICRA**, 2021.
- Ruijie Tao, Zexu Pan, Rohan Kumar Das, **Xinyuan Qian**, Mike Zheng Shou, Haizhou Li, [Is Someone Speaking? Exploring Long-term Temporal Features for Audio-visual Active Speaker Detection](https://arxiv.org/abs/2107.06592), **ACM MM**, 2021.

-- **2020 and Before** --
- Shoufeng Lin<sup>`#`</sup>, **Xinyuan Qian<sup>`#`</sup>**, [Audio-Visual Multi-Speaker Tracking Based on the GLMB Framework](https://www.isca-speech.org/archive_v0/Interspeech_2020/pdfs/1969.pdf), **INTERSPEECH**, 2020.
- **Xinyuan Qian**, Alessio Brutti, Oswald Lanz, Maurizio Omologo, Andrea Cavallaro, [Multi-speaker tracking from an audio–visual sensing device](https://ieeexplore.ieee.org/document/8656587), **TMM**, 2019.
- **Xinyuan Qian**, Alessio Xompero, Alessio Brutti, Oswald Lanz, Maurizio Omologo, Andrea Cavallaro, [3D mouth tracking from a compact microphone array co-located with a camera](https://ieeexplore.ieee.org/document/8461323), **ICASSP**，2018.
- Oswald Lanz, Alessio Brutti, Alessio Xompero, **Xinyuan Qian**, Maurizio Omologo, Andrea Cavallaro, [Accurate Target Annotation in 3D from Multimodal Streams](https://ieeexplore.ieee.org/document/8682619), **ICASSP**，2018.
- **Xinyuan Qian**, Alessio Brutti,  Maurizio Omologo, Andrea Cavallaro, [3D audio-visual speaker tracking with an adaptive particle filter](https://ieeexplore.ieee.org/abstract/document/7952686), **ICASSP**，2017.
- Deepayan Bhowmik, Andrew Wallace, Robert Stewart, **Xinyuan Qian**, Greg Michaelson, [Profile driven dataflow optimisation of mean shift visual tracking](https://ieeexplore.ieee.org/document/7032066), **GlobalSIP**，2014. 


# 🎖 Certifications and Awards
- Best Paper Award, COCOSDA, 2021
- The 3rd place winner in the ActivityNet Challenge (Speaker), CVPR Workshop, 2021
- Outstanding international research associatant,  FBK, Trento, Italy, 2019
- Full Ph.D. scholarship in QMUL, London, U.K., 2015-2019
- Outstanding Youth Female Research Engineer Scholarship, Edinburgh, U.K., 2014
- Excellent international student scholarship, Edinburgh, U.K., 2013-2014
- Shanghai 801 scholarship, 2011
- First-Class Scholarship Award, NUAA, Nanjing, China, 2010-2011
 -->

<!--
# 👔 Projects
- Young Scientists Fund of the National Natural Science Foundation of China 国家自然科学基金青年项目 (PI), 2023
- CCF-Tencent AI-Lab Open Fund 腾讯 AI Lab犀牛鸟专项（PI), 2023
- Fundamental Research Funds for the Central Universities 中央高校基本科研业务经费 （PI), 2023
- Eigenspace Audio Technology Project (PI), 2023
- Beijing Municipal Natural Science Foundation - Xiaomi 北京市自然科学基金——小米创新联合基金项目 (Co-PI), 2023

- Human Robot Interaction Project-Phase 1, Singapore, 2020-2022
- Huawei Research&Design Project, Shenzhen, China, 2022
- Shenzhen Research Institute of Big Data Internal Project (SRIBD), Shenzhen, China, 2022
 -->

# 💬 Reviewer
- Reviewer of TRO, RA-L, IEEE Sensors Journal, IROS



<!-- Google Analytics -->
<script async src="https://catherine-qian.github.io/"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'GA_MEASUREMENT_ID');
</script>
<!-- End Google Analytics -->




