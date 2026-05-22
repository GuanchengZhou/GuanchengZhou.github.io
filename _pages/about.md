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

I am a first-year Ph.D. student at [Xi'an Jiaotong University](https://www.xjtu.edu.cn/) and [SII](https://www.sii.edu.cn/), advised by Prof. [Deyu Meng](https://gr.xjtu.edu.cn/en/web/dymeng/1) and Prof. [Xipeng Qiu](https://xpqiu.github.io/). I obtained my B.S. in [School of Mathematics and Statistics, Xi'an Jiaotong University](https://math.xjtu.edu.cn/).

I am interested in mech. interp., AI4SCI and computer vision. 
I used to intern at [MAPLE LAB](https://maple.lab.westlake.edu.cn/) advised by Prof. [Guojun Qi](http://maple-lab.net/gqi/).
I used to research Computer Vision under the guidance of Prof. [Zejian Yuan](https://ieeexplore.ieee.org/author/37399214700).

<!-- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. Suspendisse condimentum, libero vel tempus mattis, risus risus vulputate libero, elementum fermentum mi neque vel nisl. Maecenas facilisis maximus dignissim. Curabitur mattis vulputate dui, tincidunt varius libero luctus eu. Mauris mauris nulla, scelerisque eget massa id, tincidunt congue felis. Sed convallis tempor ipsum rhoncus viverra. Pellentesque nulla orci, accumsan volutpat fringilla vitae, maximus sit amet tortor. Aliquam ultricies odio ut volutpat scelerisque. Donec nisl nisl, porttitor vitae pharetra quis, fringilla sed mi. Fusce pretium dolor ut aliquam consequat. Cras volutpat, tellus accumsan mattis molestie, nisl lacus tempus massa, nec malesuada tortor leo vel quam. Aliquam vel ex consectetur, vehicula leo nec, efficitur eros. Donec convallis non urna quis feugiat. -->

<!-- My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->


# 🔥 News
- *2026.05*: &nbsp;🎉🎉 One co-authored work “Multivariate Neural Directional Total Variation” is accepted by **Pattern Recognition**.
- *2026.05*: &nbsp;🎉🎉 One first author work “ Distributional View for Visual Mechanistic Interpretability: KL-Minimal Soft-Constraint Principle” is accepted by **ICML 2026 Spotlight**.
- *2026.03*: &nbsp;🎉🎉 One co-authored work “SpatialCOC: an integrative framework for spatial continuous mapping and cross-omics correction in spatial multi-omics data” is accepted by **Nature Communications**. 
- *2026.01*: &nbsp;🎉🎉 One first author work “Tucker-FNO: Tensor Tucker-Fourier Neural Operator and its Universal Approximation Theory” is accepted by **ICLR 2026**. 
- *2025.08*: &nbsp;🎉🎉 One first author work “Efficient Arbitrary-Scale Image Super-Resolution via Functional Tensor Decomposition” is accepted by **TMM**. 
<!-- - *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

# 📝 Publications 

<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

 [Deep Residual Learning for Image Recognition](https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf)

**Kaiming He**, Xiangyu Zhang, Shaoqing Ren, Jian Sun

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
</div>
</div> -->

<!-- - [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020** --> 



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML 2026 spotlight</div><img src='images/energydps.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

 [A Distributional View for Visual Mechanistic Interpretability: KL-Minimal Soft-Constraint Principle](https://arxiv.org/abs/2605.17504)

**Guancheng Zhou**, Yisi Luo, Zhengfu He, Zhenyu Jin, Xuyang Ge, Wentao Shu, Deyu Meng, Xipeng Qiu

**ICML spotlight**, 2026

[**Code**](https://github.com/SII-ZhouGC/EnergyDPS) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2026</div><img src='images/main_pde9.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

 [Tucker-FNO: Tensor Tucker-Fourier Neural Operator and its Universal Approximation Theory](https://openreview.net/forum?id=UJvkXnuozY)

**Guancheng Zhou**, Zelin Zeng, Yisi Luo, Xie Qi, Deyu Meng

**ICLR**, 2026

[**Code**](https://github.com/GuanchengZhou/Tucker-FNO) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>

</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TMM 2026</div><img src='images/tmm_main.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

 [Efficient Arbitrary-Scale Image Super-Resolution via Functional Tensor Decomposition](https://ieeexplore.ieee.org/abstract/document/11370256)

**Guancheng Zhou**, Yisi Luo, Xile Zhao, Deyu Meng

**IEEE Transactions on Multimedia**, 2026

[**Code**](https://github.com/GuanchengZhou/FTD-LIIF) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Nature Communications 2026</div><img src='images/spatialcoc.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

 [SpatialCOC: an integrative framework for spatial continuous mapping and cross-omics correction in spatial multi-omics data](https://www.nature.com/articles/s41467-026-71882-2)

Mingxuan Li, Peisen Sun, Yisi Luo, **Guancheng Zhou**, Xiaofei Yang, Deyu Meng, Kai Ye

**Nature Communications**, 2026

[**Code**](https://github.com/xjtu-omics/SpatialCOC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">OpenMOSS Interpretability Posts</div><img src='images/post.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

 [Bridging the Attention Gap: Complete Replacement Models for Complete Circuit Tracing](https://interp.open-moss.com/posts/complete-replacement)

Wentao Shu, Xuyang Ge, **Guancheng Zhou**, Junxuan Wang, Rui Lin, Zhaoxuan Song, Jiaxing Wu, Zhengfu He, Xipeng Qiu

**OpenMOSS Interpretability Posts**, 2026

</div>
</div>

<!-- - [Efficient Arbitrary-Scale Image Super-Resolution via Functional Tensor Decomposition](https://github.com/GuanchengZhou/FTD-LIIF). **Guancheng Zhou**, Yisi Luo, Xile Zhao, Deyu Meng. **IEEE Transactions on Multimedia (JCR Q1)**.  -->
<!-- - [SpaKnit: correlation subspace learning for integrating spatial multi-omics data](https://www.researchsquare.com/article/rs-6345712/latest). Kai Ye, Mingxuan Li, Peisen Sun, Yisi Luo, **Guancheng Zhou**, Xiaofei Yang, Deyu Meng. **Nature Communications**. 2026. -->

- [Multivariate Neural Directional Total Variation](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=5276205). Zelin Zeng*, **Guancheng Zhou\*(Equal Distribution)**, Yisi Luo, Xi-Le Zhao, Qi Xie, Deyu Meng. **Pattern Recognition**.

- [Efficient Multi-branch Segmentation Network for Situation Awareness in Autonomous Navigation](https://www.sciencedirect.com/science/article/pii/S0029801824010783). **Guan-Cheng Zhou**, Chen Cheng, Yan-zhou Chen. **Ocean Engineering (JCR Q1)** 302, 117741. 2024.

<!-- SpaKnit: correlation subspace learning for integrating spatial multi-omics data, Mingxuan Li, Peisen Sun, Yisi Luo, **Guan-Cheng Zhou**, Xiaofeng Yang, Deyu Meng. under review. -->

<!-- Multivariate Neural Directional Total Variation, Zelin Zeng, **Guan-Cheng Zhou**, Yisi Luo, Deyu Meng. under review. -->

- [Design and implementation of STM32 communication transmission management system based on RTOS](https://kns.cnki.net/kcms2/article/abstract?v=xhAGsX4BfX7Y1lNpplHuupbZeS7rNsXUAdNrmI8a4BtKoDA3sEDNCA6WLAhI_dRAGQbvZCyiQVuKWJn_M25FEdi44BXdXU_z4HLg23Xgx99ivDrS4Mx5EBWRwMTN-2lV5eBMeQUP2bPeH2l1ACUZVDhlzcn2DZLSagmVfEhvZ7Ycu1FcXhpslQ==&uniplatform=NZKPT&language=CHS). **Guan-Cheng Zhou**, Dang-chao Li, Jia-ying Ye, Jian-lei Chang, Zhao-yang Hao. **Internet of Things Technologies**,2024,14(03). 2024.

- An unmanned ship surface cleaning device. **Guan-cheng Zhou**, Chen Cheng, Yan-zhou Chen, Yu-hang Wei, Zhao-yang Hao. **Utility Model Patent** (ZL 2023 2 2875376.4).  2023.

# 🎖 Honors and Awards
<!-- - *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->
- *2025.06* Outstanding Undergraduate Graduate.
- *2025.06* Outstanding Graduation Thesis. 
- *2021* Wuhan Donghu New Technology Development Zone Scholarship with Xi’an Jiaotong University.

# 📖 Educations
- *2025.06 - now*, Ph.D, Xi'an Jiaotong University.
- *2021.06 - 2025.06*, B.S., Xi'an Jiaotong University.

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

# 💻 Internships
- *2025.06 - now*, Shanghai Innovation Institute.
- *2024.06 - 2024.09*, [MAPLE LAB](https://maple.lab.westlake.edu.cn/), Westlake University.
