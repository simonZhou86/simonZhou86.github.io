---
title: "ClinicalFMamba: Mamba-based Multimodal Medical Image Fusion for Enhanced Clinical Diagnosis"
collection: publications
permalink: /publication/clinicalfmamba_3d
excerpt: 'Multimodal medical image fusion integrates complementary information from different imaging modalities to enhance diagnostic accuracy and treatment planning. While deep learning methods have advanced performance, existing approaches face critical limitations: Convolutional Neural Networks (CNNs) excel at local feature extraction but struggle to model global context effectively, while Transformers achieve superior long-range modeling at the cost of quadratic computational complexity, limiting clinical deployment. Recent State Space Models (SSMs) offer a promising alternative, enabling efficient long-range dependency modeling in linear time through selective scan mechanisms. Despite these advances, the extension to 3D volumetric data and the clinical validation of fused images remains underexplored. In this work, we propose ClinicalFMamba, a novel end-to-end CNN-Mamba hybrid architecture that synergistically combines local and global feature modeling for 2D and 3D images. We further design a tri-plane scanning strategy for effectively learning volumetric dependencies in 3D images. Comprehensive evaluations on three datasets demonstrate the superior fusion performance across multiple quantitative metrics while achieving real-time fusion. We further validate the clinical utility of our approach on downstream 2D/3D brain tumor classification tasks, achieving superior performance over baseline methods. Our method establishes a new paradigm for efficient multimodal medical image fusion suitable for real-time clinical deployment.'
date: 2025-07-31
venue: 'MICCAI MLMI'
paperurl: 'https://arxiv.org/abs/2508.03008'
---

Accepted to MICCAI MLMI 2025.

If you find our paper useful, please cite our paper:

```{bibtex}
Upcoming
```