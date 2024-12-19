---
title: "Generating 3D Brain Tumor Regions in MRI using Vector-Quantization Generative Adversarial Networks"
collection: publications
permalink: /publication/brain_tumor_gen 
excerpt: 'In this work, we present a novel framework that uses vector-quantization GAN and a transformer incorporating masked token modeling to generate high-resolution and diverse 3D brain tumor ROIs that can be directly used as augmented data for the classification of brain tumor ROI. We apply our method to two imbalanced datasets where we augment the minority class: (1) the Multimodal Brain Tumor Segmentation Challenge (BraTS) 2019 dataset to generate new low-grade glioma (LGG) ROIs to balance with high-grade glioma (HGG) class; (2) the internal pediatric LGG (pLGG) dataset tumor ROIs with BRAF V600E Mutation genetic marker to balance with BRAF Fusion genetic marker class. We show that the proposed method outperforms various baseline models in both qualitative and quantitative measurements.'
date: 2024-11-27
venue: 'Computers in Biology and Medicine'
paperurl: 'https://arxiv.org/abs/2310.01251'
---

Accepted by Computers in Biology and Medicine Journal (IF=7)

Link:
[Download paper here](https://www.sciencedirect.com/science/article/abs/pii/S0010482524015877)

Arxiv(Not updated) Link:
[Preprint](https://arxiv.org/abs/2310.01251)


If you find our paper useful, please cite our paper:

```{bibtex}
@article{zhou2023generating,
  title={Generating 3D Brain Tumor Regions in MRI using Vector-Quantization Generative Adversarial Networks},
  author={Zhou, Meng and Wagner, Matthias W and Tabori, Uri and Hawkins, Cynthia and Ertl-Wagner, Birgit B and Khalvati, Farzad},
  journal={arXiv preprint arXiv:2310.01251},
  year={2023}
}

@Article{Zhou2025gen,
  author   = {Meng Zhou and Matthias W. Wagner and Uri Tabori and Cynthia Hawkins and Birgit B. Ertl-Wagner and Farzad Khalvati},
  journal  = {Computers in Biology and Medicine},
  title    = {Generating 3D brain tumor regions in MRI using vector-quantization Generative Adversarial Networks},
  year     = {2025},
  issn     = {0010-4825},
  pages    = {109502},
  volume   = {185},
  doi      = {https://doi.org/10.1016/j.compbiomed.2024.109502},
  keywords = {Deep learning, Generative Adversarial Networks, Transformer, Image generation, Brain MRI, Pediatric low grade glioma},
  url      = {https://www.sciencedirect.com/science/article/pii/S0010482524015877},
}
```