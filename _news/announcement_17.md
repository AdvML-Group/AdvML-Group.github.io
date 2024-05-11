---
layout: post
date: 2024-5-10 07:59:00-0400
title: Code for our method <b>&#34;Transferable Structural Sparse Adversarial Attack Via Exact Group Sparsity Training (CVPR 2024)&#34;</b> is released!
inline: false
related_posts: false
---

### <b>Transferable Structural Sparse Adversarial Attack Via Exact Group Sparsity Training</b>

***

<b>Di Ming, Peng Ren, Yunlong Wang, Xin Feng&#42;</b>&#59; Proceedings of the IEEE&#47;CVF International Conference on Computer Vision and Pattern Recognition (CVPR), 2024, pp. xxxx-xxxx.

***

#### <b>Abstract</b>


Deep neural networks (DNNs) are vulnerable to highly transferable adversarial attacks. Especially, many studies have shown that sparse attacks pose a significant threat to DNNs on account of their exceptional imperceptibility. Current sparse attack methods mostly limit only the magnitude and number of perturbations while generally overlooking the location of the perturbations, resulting in decreased performances on attack transferability. A subset of studies indicates that perturbations existing in the significant regions with rich classification-relevant features are more effective. Leveraging this insight, we introduce the structural sparsity constraint in the framework of generative models to limit the perturbation positions. To ensure that the perturbations are generated towards classification-relevant regions, we propose an exact group sparsity training method to learn pixel-level and group-level sparsity. For purpose of improving the effectiveness of sparse training, we further put forward masked quantization network and multi-stage optimization algorithm in the training process. Utilizing CNNs as surrogate models, extensive experiments demonstrate that our method has higher transferability in image classification attack compared to state-of-the-art methods at approximately same sparsity levels. In cross-model ViT, object detection, and semantic segmentation attack tasks, we also achieve a better attack success rate. Code is available at https&#58;&#47;&#47;github&#46;com&#47;MisterRpeng&#47;EGS-TSSA.


***

#### <b>Related Material</b>

&#91;<a href="https://github.com/MisterRpeng/EGS-TSSA">html<a>&#93;      &#91;<a href="https://github.com/MisterRpeng/EGS-TSSA">paper<a>&#93;      &#91;<a href="https://github.com/MisterRpeng/EGS-TSSA">supp<a>&#93; &#91;<a href="https://github.com/MisterRpeng/EGS-TSSA">code<a>&#93;      &#91;<a href="https://github.com/MisterRpeng/EGS-TSSA">poster<a>&#93;      &#91;<a href="https://github.com/MisterRpeng/EGS-TSSA">video<a>&#93;

***

#### <b>Citation</b>
```
@InProceedings{CVPR24_EGS_TSSA,
    author    = {Ming, Di and Peng, Ren and Wang, Yunlong and Feng, Xin},
    title     = {Transferable Structural Sparse Adversarial Attack Via Exact Group Sparsity Training},
    booktitle = {Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)},
    month     = {June},
    year      = {2024},
    pages     = {xxxx-xxxx}
}
```

***

&#42;Corresponding Author&#58; Xin Feng
