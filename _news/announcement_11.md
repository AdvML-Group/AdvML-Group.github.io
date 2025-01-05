---
layout: post
date: 2024-11-22 07:59:00-0400
title: Code for our method <b>&#34;Boosting the Transferability of Adversarial Attack on Vision Transformer with Adaptive Token Tuning (NeurIPS 2024)&#34;</b> is released!
inline: false
related_posts: false
---

### <a href="https://github.com/MisterRpeng/ATT"><b>Boosting the Transferability of Adversarial Attack on Vision Transformer with Adaptive Token Tuning</b><a>

***

<b>Di Ming, Peng Ren, Yunlong Wang, Xin Feng&#42;</b>&#59; The Thirty-Eighth Annual Conference on Neural Information Processing Systems (NeurIPS), 2024, pp. xxxxx-xxxxx.

***

#### <b>Abstract</b>


Vision transformers (ViTs) perform exceptionally well in various computer vision tasks but remain vulnerable to adversarial attacks. Recent studies have shown that the transferability of adversarial examples exists for CNNs, and the same holds true for ViTs. However, existing ViT attacks aggressively regularize the largest token gradients to exact zero within each layer of the surrogate model, overlooking the interactions between layers, which limits their transferability in attacking black-box models. Therefore, in this paper, we focus on boosting the transferability of adversarial attacks on ViTs through adaptive token tuning (ATT). Specifically, we propose three optimization strategies: an adaptive gradient re-scaling strategy to reduce the overall variance of token gradients, a self-paced patch out strategy to enhance the diversity of input tokens, and a hybrid token gradient truncation strategy to weaken the effectiveness of attention mechanism. We demonstrate that scaling correction of gradient changes using gradient variance across different layers can produce highly transferable adversarial examples. In addition, introducing attentional truncation can mitigate the overfitting over complex interactions between tokens in deep ViT layers to further improve the transferability. On the other hand, using feature importance as a guidance to discard a subset of perturbation patches in each iteration, along with combining self-paced learning and progressively more sampled attacks, significantly enhances the transferability over attacks that use all perturbation patches. Extensive experiments conducted on ViTs, undefended CNNs, and defended CNNs validate the superiority of our proposed ATT attack method. On average, our approach improves the attack performance by 10.1&#37; compared to state-of-the-art transfer-based attacks. Notably, we achieve the best attack performance with an average of 58.3&#37; on three defended CNNs. Code is available at https&#58;&#47;&#47;github.com&#47;MisterRpeng&#47;ATT.


***

#### <b>Related Material</b>

&#91;<a href="https://nips.cc/virtual/2024/poster/93393">html<a>&#93;      &#91;<a href="https://openreview.net/pdf?id=sNz7tptCH6">paper<a>&#93;      &#91;<a href="https://openreview.net/pdf?id=sNz7tptCH6">supp<a>&#93;      &#91;<a href="https://github.com/MisterRpeng/ATT">code<a>&#93;      &#91;<a href="https://drive.google.com/file/d/1wGvQEvVkAJseYPyJY5j3TEbqiWuhkiYX/view?usp=sharing">poster<a>&#93;      &#91;<a href="https://drive.google.com/file/d/1X5GE1ON2Fp02aCZiC-oKWczfvyDOtE80/view?usp=sharing">video<a>&#93;

***

#### <b>Citation</b>
```
@InProceedings{NeurIPS24_ATT_Attack,
    author    = {Ming, Di and Peng, Ren and Wang, Yunlong and Feng, Xin},
    title     = {Boosting the Transferability of Adversarial Attack on Vision Transformer with Adaptive Token Tuning},
    booktitle = {The Thirty-Eighth Annual Conference on Neural Information Processing Systems (NeurIPS)},
    month     = {Dec},
    year      = {2024},
    pages     = {xxxxx-xxxxx}
}
```

***

&#42;Corresponding Author&#58; Xin Feng
