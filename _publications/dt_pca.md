---
title: "Domain Transfer Through Image-to-Image Translation in Prostate Cancer Detection"
collection: publications
permalink: /publication/dt_pca
excerpt: 'In this paper, we have presented a novel approach for unpaired image-to-image translation of prostate mp-MRI for classifying clinically significant PCa, to be applied in data-constrained settings. First, we introduce domain transfer, a novel pipeline to translate unpaired 3.0T multi-parametric prostate MRIs to 1.5T, to increase the number of training data. Second, we estimate the uncertainty of our models through an evidential deep learning approach; and leverage the dataset filtering technique during the training process. Furthermore, we introduce a simple, yet efficient Evidential Focal Loss that incorporates the focal loss with evidential uncertainty to train our model. Experiments have shown the superior performance of the proposed approach.'
date: 2022-03-01
venue: 'Abstract, 20th Annual Symposium of the Imaging Network of Ontario (ImNO)'
paperurl: 'https://www.imno.ca/sites/default/files/ImNO2022Proceedings.pdf'
---

We further extend our method by incoperating the uncertainty estimation to the model to improve the classification performance. To this end, we further propose the *Evidential Focal Loss* as a loss function for binary prostate cancer classification. The extended journal version is available at [here](https://arxiv.org/abs/2307.00479)

[Download paper here](http://simonZhou86.github.io/files/dt_pca.pdf)

Recommended citation:

```{bibtex}
@conference{Zhou2022,
title = {Domain Transfer through Image-to-Image Translation in Prostate Cancer Detection},
author = {Meng Zhou and Amoon Jamzad and Jason Izard and Alexandre Menard and Robert Siemens and Parvin Mousavi},
year = {2022},
date = {2022-03-22},
booktitle = {20th Annual Symposium of the Imaging Network of Ontario (ImNO) 2022},
keywords = {},
pubstate = {published},
tppubtype = {conference}
}
```

```{bibtex}
@article{zhou2023domain,
  title={Domain Transfer Through Image-to-Image Translation for Uncertainty-Aware Prostate Cancer Classification},
  author={Zhou, Meng and Jamzad, Amoon and Izard, Jason and Menard, Alexandre and Siemens, Robert and Mousavi, Parvin},
  journal={arXiv preprint arXiv:2307.00479},
  year={2023}
}
```