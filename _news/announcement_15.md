---
layout: post
date: 2025-10-17 07:59:00-0400
title: Code for our method <b>&#34;SMP-Attack&#58; Boosting the Transferability of Feature Importance-based Adversarial Attack with Semantics-aware Multi-granularity Patchout (ICCV 2025)&#34;</b> is released!
inline: false
related_posts: false
---

### <b>SMP-Attack&#58; Boosting the Transferability of Feature Importance-based Adversarial Attack with Semantics-aware Multi-granularity Patchout</b>

***

<b>Wen Yang, Guodong Liu, Di Ming&#42;</b>&#59; Proceedings of the IEEE&#47;CVF International Conference on Computer Vision (ICCV), 2025, pp. 4444-4454.

***

#### <b>Abstract</b>

Transfer-based attacks pose a significant security threat to deep neural networks (DNNs), due to their strong performance on unseen models in real-world black-box scenarios. Building on this, feature importance-based attacks further improve the transferability of adversarial examples by effectively suppressing model-specific feature patterns. However, existing methods primarily focus on single-granularity patch and single-stage training, leading to suboptimal solutions. To address these limitations, we propose a general multi-stage optimization framework based on Semantics-aware Multi-granularity Patchout, dubbed as SMP-Attack. Compared to the non-deformable/regular patch definition, we incorporate multi-granularity into the generation process of deformable/irregular patches, thereby enhancing the quality of the computed aggregate gradient. In contrast to conventional joint optimization of multi-layer losses, we introduce an effective multi-stage training strategy that systematically explores significant model-agnostic features from shallow to intermediate layers. Employing the ImageNet dataset, we conduct extensive experiments on undefended/defended CNNs and ViTs, which unequivocally demonstrate the superior performance of our proposed SMP-Attack over current state-of-the-art methods in black-box scenarios. Furthermore, we assess the compatibility of our multi-stage optimization, which supersedes single-stage training employed in existing feature-based methods, culminating in substantial performance improvement. Code is available at https&#58;&#47;&#47;github&#46;com&#47;AdvML-Group&#47;SMP-Attack.

***

#### <b>Related Material</b>

&#91;<a href="https://openaccess.thecvf.com/content/ICCV2025/html/Yang_SMP-Attack_Boosting_the_Transferability_of_Feature_Importance-based_Adversarial_Attack_with_ICCV_2025_paper.html">html<a>&#93;      &#91;<a href="https://openaccess.thecvf.com/content/ICCV2025/papers/Yang_SMP-Attack_Boosting_the_Transferability_of_Feature_Importance-based_Adversarial_Attack_with_ICCV_2025_paper.pdf">paper<a>&#93;      &#91;<a href="https://openaccess.thecvf.com/content/ICCV2025/supplemental/Yang_SMP-Attack_Boosting_the_ICCV_2025_supplemental.pdf">supp<a>&#93; &#91;<a href="https://github.com/AdvML-Group/SMP-Attack">code<a>&#93;      &#91;<a href="https://github.com/AdvML-Group/SMP-Attack">poster<a>&#93;      &#91;<a href="https://youtu.be/5p4LxrBjxV0">video<a>&#93;

***

#### <b>Citation</b>
```
@InProceedings{Yang_2025_ICCV,
    author    = {Yang, Wen and Liu, Guodong and Ming, Di},
    title     = {SMP-Attack: Boosting the Transferability of Feature Importance-based Adversarial Attack with Semantics-aware Multi-granularity Patchout},
    booktitle = {Proceedings of the IEEE/CVF International Conference on Computer Vision (ICCV)},
    month     = {October},
    year      = {2025},
    pages     = {4444-4454}
}
```

***

&#42;Corresponding Author&#58; Di Ming
