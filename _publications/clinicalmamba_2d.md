---
title: "ClinicalFMamba: Mamba-based Multimodal Medical Image Fusion for Enhanced Clinical Diagnosis"
collection: publications
permalink: /publication/clinicalfmamba_2d
excerpt: 'Multimodal medical image fusion integrates complementary information from different imaging modalities to enhance diagnostic accuracy and treatment planning.   While deep learning methods have advanced fusion performance, existing approaches face critical limitations: CNNs excel at local feature extraction but struggle to model  global context effectively, while Transformers achieve superior long-range modeling at the cost of quadratic computational complexity in self-attention mechanisms, limiting clinical deployment. Recent State Space Models (SSMs) offer a promising alternative, enabling efficient long-range dependency modeling in linear time through selective mechanisms. Despite these advances, clinical validation of fused images remains underexplored. In this work, we propose ClinicalFMamba, a novel end-to-end CNN-Mamba hybrid architecture that synergistically combines local and global feature modeling. Our approach introduces: Dilated Gated Convolution Blocks for hierarchical multiscale feature extraction, and a latent Mamba module that efficiently captures long-range spatial dependencies between feature regions and enabling cross-modal fusion in latent space. Comprehensive evaluations on three datasets demonstrate the superior fusion performance across multiple quantitative metrics while achieving real-time fusion. Notably, we validate the clinical utility of our approach on the downstream brain tumor classification, achieving up to 7% improvements on the AUC score. Our method establishes a new paradigm for efficient multimodal medical image fusion suitable for real-time clinical deployment.'
date: 2024-06-27
venue: 'ICML NewInML Workshop'
paperurl: 'http://simonZhou86.github.io/files/zhou2025clinicalfmamba.pdf'
---

Accepted to ICML NewInML Workshop 2025 as a poster paper.

This paper is also submitted to MICCAI MIML Workshop for possible publication.

If you find our paper useful, please cite our paper:

```{bibtex}
@inproceedings{
  zhou2025clinicalfmamba,
  title={Clinical{FM}amba: Mamba-based Multimodal Medical Image Fusion for Enhanced Clinical Diagnosis},
  author={Zhou, Meng and Khalvati, Farzad},
  booktitle={ICML 2025 Workshop NewInML},
  year={2025},
  url={https://openreview.net/forum?id=FVHqDXsH63}
}
```