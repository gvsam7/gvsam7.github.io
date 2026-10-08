---
title: "IGARSS 2022 — Oral Presentation: Deep Learning Robustness to Domain Shifts During Seasonal Variations"
collection: talks
type: "Conference Presentation"
venue: "IEEE International Geoscience and Remote Sensing Symposium (IGARSS)"
date: 2022-07-20
permalink: /talks/igarss-2022/
excerpt: "First author oral presentation at IGARSS 2022 on deep learning robustness to seasonal domain shifts in satellite imagery."
---

IEEE International Geoscience and Remote Sensing Symposium 2022 — First Author Presentation
======

I delivered a first author oral presentation at IGARSS 2022 on my work titled "Deep Learning Robustness to Domain Shifts During Seasonal Variations". The talk examined how dramatic landscape changes between wet and dry seasons in South Asia affect the performance of deep learning models trained on satellite imagery, and how feature priors can improve robustness under domain shift.

**[YouTube recording:](https://www.youtube.com/watch?v=Zci4eASXmkQ)**  

Paper:  
"[Deep Learning Robustness to Domain Shifts During Seasonal Variations](https://ieeexplore.ieee.org/abstract/document/9883940)"  
IEEE IGARSS 2022

The presentation covered:

* Seasonal variation in South Asian landscapes and its impact on satellite-based classification.
* How spurious correlations arise when training on single-season data (e.g. green vegetation in wet season vs brown terrain in dry season).
* Comparison between a standard 5-layer CNN (CNN5) and a Gabor-parameterised CNN (GCNN).
* Evaluation on mixed-season, wet-only, and dry-only datasets.
* Use of grey-scale preprocessing to remove colour cues and reduce reliance on season-specific features.
* Class Activation Mapping (CAM) analysis to understand model focus and feature saliency.

Key findings:

* GCNN focuses on more salient, season-invariant features than CNN5.
* Removing colour information improves generalisation between wet and dry seasons.
* GCNN trained on grey-scale images achieves the strongest robustness under seasonal domain shift.
* CAM visualisations show GCNN is often “wrong for the right reasons”, focusing on meaningful structures even when misclassifying.

Impact:

* Demonstrated that careful selection of initial feature priors (e.g. Gabor filters) can significantly improve robustness to environmental domain shifts.
* Provided early evidence for the importance of physics- and texture-aware architectures in remote sensing; work that later evolved into FusionNet and PerceptiveNet.
