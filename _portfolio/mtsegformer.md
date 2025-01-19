---
title: "Multitask Learning for Brain Tumor Segmentation using Transformer"
excerpt: "We present MTSegFormer, a learning framework for 2D brain tumor segmentation using latent transformer through the Multi-task learning paradigm.<br/><img src='/images/mtseg_cover.png'>"
collection: portfolio
---

Accurate brain tumor segmentation in MRI images is crucial for effective diagnosis and treatment planning. However, traditional U-Net architecture faces challenges in
capturing long-range dependencies and preserving features of small-sized tumors, which limits its performance. In this work, we present MTSegFormer, a novel learning
framework for 2D brain tumor segmentation using latent transformer through the Multi-task learning paradigm. We use a UNet-like structure with a latent space
transformer, and a self-supervised image decoder to build up the overall framework. We also introduce the Breath-wise Cross Attention module that aims to refine the
skip connection features. Experiment shows our proposed framework achieves superior performance compared to other baselines by up to 11% in Dice and 10% in
IoU score. The code is available at [this url](https://github.com/simonZhou86/csc2516_proj)

[Download project report here](http://simonZhou86.github.io/files/multisegformer.pdf)

If you want to use the code, or find our project useful, you can set as follows:

```{bibtex}
@misc{zhou23mtseg,
    author = {Zhou, Meng and Liu, Xudong and Wu, Reyna},
    title = {MTSegFormer: A Multitask Learning Approach for Brain Tumor Segmentation using Transformer},
    year = {2023},
    howpublished = {\url{https://simonzhou86.github.io/portfolio/mtsegformer}},
}
```