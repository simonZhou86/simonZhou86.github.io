---
title: "ClinicalFMamba: Mamba-based Multimodal Medical Image Fusion for Enhanced Clinical Diagnosis"
collection: publications
permalink: /publication/clinicalfmamba_2d
excerpt: 'In this work, we propose ClinicalFMamba, a novel end-to-end CNN-Mamba hybrid architecture that synergistically combines local and global feature modeling. Our approach introduces: Dilated Gated Convolution Blocks for hierarchical multiscale feature extraction, and a latent Mamba module that efficiently captures long-range spatial dependencies between feature regions and enabling cross-modal fusion in latent space. Comprehensive evaluations on three datasets demonstrate the superior fusion performance across multiple quantitative metrics while achieving real-time fusion. Notably, we validate the clinical utility of our approach on the downstream brain tumor classification, achieving up to 7% improvements on the AUC score. Our method establishes a new paradigm for efficient multimodal medical image fusion suitable for real-time clinical deployment.'
date: 2025-06-27
venue: 'International Conference on Machine Learning NewInML Workshop'
paperurl: 'http://simonZhou86.github.io/files/zhou2025clinicalfmamba.pdf'
---

Accepted to ICML NewInML 2025 Workshop as a poster paper, also see [here](https://icml.cc/virtual/2025/50490).

The extension of this work is accepted to MICCAI MLMI 2025, see [here](https://simonzhou86.github.io/publication/clinicalfmamba_3d) for more details.

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
@article{zhou2025clinicalfmamba,
  title={ClinicalFMamba: Advancing Clinical Assessment using Mamba-based Multimodal Neuroimaging Fusion},
  author={Zhou, Meng and Khalvati, Farzad},
  journal={arXiv preprint arXiv:2508.03008},
  year={2025}
}
```