---
layout: post
date: 2023-9-28 07:59:00-0400
title: Code for our method <b>&#34;TRM-UAP&#58; Enhancing the Transferability of Data-Free Universal Adversarial Perturbation via Truncated Ratio Maximization (ICCV 2023)&#34;</b> is released!
inline: false
related_posts: false
---

### <b>TRM-UAP&#58; Enhancing the Transferability of Data-Free Universal Adversarial Perturbation via Truncated Ratio Maximization</b>

***

<b>Yiran Liu, Xin Feng, Yunlong Wang, Wu Yang, Di Ming&#42;</b>&#59; Proceedings of the IEEE&#47;CVF International Conference on Computer Vision (ICCV), 2023, pp. 4762-4771

***

#### <b>Abstract</b>

Aiming at crafting a single universal adversarial perturbation (UAP) to fool CNN models for various data samples, universal attack enables a more efficient and accurate evaluation for the robustness of CNN models. Early universal attacks craft UAPs depending on data priors. For more practical applications, the data-free universal attacks that make UAPs from random noises have aroused much attention recently. However, existing data-free UAP methods perturb all the CNN feature layers equally via the maximization of the CNN activation, leading to poor transferability. In this paper, we propose a novel data-free universal attack without depending on any real data samples through truncated ratio maximization, which we term as TRM-UAP. Specifically, different from the maximization of the positive activation in convolution layers, we propose to optimize the UAP generation from the ratio of positive and negative activations. To further enhance the transferability of universal attack, TRM-UAP not only performs the ratio maximization merely on low-level generic features via the truncation strategy, but also incorporates a curriculum optimization algorithm that can effectively learn the diversity of artificial images. Extensive experiments on the ImageNet dataset verify that TRM-UAP achieves a state-of-the-art average fooling rate and excellent transferability on different CNN models as compared to other data-free UAP methods. Code is available at https&#58;&#47;&#47;github&#46;com&#47;RandolphCarter0&#47;TRMUAP.

***

#### <b>Related Material</b>

&#91;<a href="https://openaccess.thecvf.com/content/ICCV2023/html/Liu_TRM-UAP_Enhancing_the_Transferability_of_Data-Free_Universal_Adversarial_Perturbation_via_ICCV_2023_paper.html">html<a>&#93;      &#91;<a href="https://openaccess.thecvf.com/content/ICCV2023/papers/Liu_TRM-UAP_Enhancing_the_Transferability_of_Data-Free_Universal_Adversarial_Perturbation_via_ICCV_2023_paper.pdf">paper<a>&#93;      &#91;<a href="https://openaccess.thecvf.com/content/ICCV2023/supplemental/Liu_TRM-UAP_Enhancing_the_ICCV_2023_supplemental.pdf">supp<a>&#93; &#91;<a href="https://github.com/RandolphCarter0/TRMUAP">code<a>&#93;      &#91;<a href="https://drive.google.com/file/d/16ljA-MjlF8dHHp5NVcHUtUjFX1u7HI8B/view?usp=sharing">poster<a>&#93;      &#91;<a href="https://drive.google.com/file/d/16Rdu6pGuSuaK14H1MK7acxatkHMjj_oL/view">video<a>&#93;

***

#### <b>Citation</b>
```
@InProceedings{Liu_2023_ICCV,
    author    = {Liu, Yiran and Feng, Xin and Wang, Yunlong and Yang, Wu and Ming, Di},
    title     = {TRM-UAP: Enhancing the Transferability of Data-Free Universal Adversarial Perturbation via Truncated Ratio Maximization},
    booktitle = {Proceedings of the IEEE/CVF International Conference on Computer Vision (ICCV)},
    month     = {October},
    year      = {2023},
    pages     = {4762-4771}
}
```

***

&#42;Corresponding Author&#58; Di Ming &#60;diming&#64;cqut.edu.cn&#62;
