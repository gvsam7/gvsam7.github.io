---
title: "IGARSS 2023 — Oral Presentation: Water Physics Aware Semantic Segmentation"
collection: talks
type: "Conference Presentation"
venue: "IEEE International Geoscience and Remote Sensing Symposium (IGARSS)"
date: 2023-07-19
permalink: /talks/igarss-2023/
excerpt: "First author oral presentation at IGARSS 2023 on physics-aware, texture-biased U-Net architectures for water segmentation; chaired the session."
---

IGARSS 2023 — Oral Presentation (First Author & Session Chair)
======

I delivered a first author oral presentation at IGARSS 2023 and chaired the session "Image Analysis for Remote Sensing of Water Bodies" . The talk presented our work titled "Water Physics Aware Semantic Segmentation Through Texture-Biased U-Net Architectures", which investigates how the physical properties of water can be exploited to improve semantic segmentation performance in aerial imagery.

Paper:  
"[Water Physics Aware Semantic Segmentation Through Texture-Biased U-Net Architectures](https://ieeexplore.ieee.org/abstract/document/10281796)"  
IEEE IGARSS 2023

The presentation covered:

* Physical properties of water that influence its appearance, including surface tension, cohesion, adhesion, and vibrational colour origins.
* Why colour is unreliable for water segmentation due to reflections, impurities, scattering, and illumination changes.
* Motivation for texture-biased segmentation based on water’s consistent surface texture.
* Introduction of two texture-biased architectures:
  * **GUNet** — U-Net with a Gabor-implemented convolutional first layer and Mix Pooling.
  * **GMACUNet** — MACUNet with the same texture-biased modifications.
* Construction of a diverse water dataset with varying seasons, lighting, atmospheric conditions, snow/ice, and reflections.
* Evaluation across three benchmark aerial datasets: Landcover.AI, WHDLD, and UAVid.

Key findings:

* Texture-biased architectures outperform standard U-Net and MACUNet across all datasets.
* Gabor-based convolutional layers improve robustness to shadows, canopy occlusion, and light variation.
* The proposed models retrieve scene information hidden beneath canopy and shadows more effectively.
* The approach generalises strongly beyond water segmentation to multi-class aerial scene segmentation.

Session role:

* Chaired the IGARSS 2023 session "Image Analysis for Remote Sensing of Water Bodies" in which the paper was presented, coordinating speakers and discussion.
