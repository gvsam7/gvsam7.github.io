---
title: "CVPR EarthVision 2025 — Spotlight Presentation: PerceptiveNet for Tree Crown Semantic Segmentation"
collection: talks
type: "Spotlight Presentation"
venue: "Greeks in AI Symposium — CVPR EarthVision Spotlight"
date: 2025-07-17
permalink: /talks/earthvision-spotlight-2025/
excerpt: "Single-author spotlight presentation at Greeks in AI 2025 on PerceptiveNet, a novel signal processing-parameterised convolutional backbone for complex scene semantic segmentation."
---

CVPR EarthVision 2025 — [Spotlight Presentation](https://www.greeksin.ai/) (Single Author)
======

I delivered a single-author spotlight presentation at the Greeks in AI 2025 Symposium, presenting my CVPR EarthVision paper titled "Bridging Classical and Modern Computer Vision: PerceptiveNet for Tree Crown Semantic Segmentation". The talk introduced PerceptiveNet, a novel backbone architecture designed to address the unique spatial and spectral challenges of dense forest aerial imagery.

Paper:  
"[Bridging Classical and Modern Computer Vision: PerceptiveNet for Tree Crown Semantic Segmentation](https://openaccess.thecvf.com/content/CVPR2025W/EarthVision/html/Voulgaris_Bridging_Classical_and_Modern_Computer_Vision_PerceptiveNet_for_Tree_Crown_CVPRW_2025_paper.html)"  
CVPR EarthVision 2025

The presentation covered:

* Challenges of tree crown semantic segmentation in dense forests, including shadows, occlusions, scale variation, and subtle spectral differences.
* Limitations of standard CNNs and fixed Gabor filters, including texture bias and restricted adaptability.
* Introduction of a trainable Log-Gabor-parameterised convolutional layer for improved shape-based and frequency-aware feature extraction.
* A new backbone architecture combining:
  * a signal-processing-parameterised convolutional layer,
  * Mix Pooling (average and max pooling) for richer spatial statistics,
  * averaged dilated convolutional layers for a wider receptive field.
* Ablation studies demonstrating the complementary benefits of each architectural component.
* Integration of PerceptiveNet into a hybrid CNN-Transformer model (PerceptiveNeTr) for long-range dependency modelling.
* Extensive evaluation across three aerial datasets: TreeCrown, Landcover.AI, and UAVid.

Key findings:

* Log-Gabor-parameterised convolutional layers outperform standard and Gabor-based layers across all datasets.
* PerceptiveNet achieves state-of-the-art performance, improving mIoU by 10.5 percent on TreeCrown compared to ResUNet.
* The architecture generalises strongly to diverse aerial scene segmentation tasks.
* Class Activation Maps show more focused and discriminative feature extraction compared to standard CNNs.
* The hybrid PerceptiveNeTr model further enhances performance by capturing global context and long-range dependencies.
