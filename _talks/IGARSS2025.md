---
title: "IGARSS 2025 — Oral Presentation: FusionNet for Multimodal Plant Detection with Landsat-8"
collection: talks
type: "Conference Presentation"
venue: "IEEE International Geoscience and Remote Sensing Symposium (IGARSS)"
date: 2025-08-05
permalink: /talks/igarss-2025/
excerpt: "First author oral presentation at IGARSS 2025 on FusionNet, a physics-informed multi-temporal and multi-spectral deep learning approach for cement plant detection using Landsat-8."
---

[IEEE International Geoscience and Remote Sensing Symposium 2022 — First Author Presentation](https://2025.ieeeigarss.org/view_paper.php?PaperNum=3165&SessionID=1500)
======

I delivered a first author oral presentation at IGARSS 2025 on my work titled "Detecting Cement Plants with Landsat-8: A Physics-Informed, Multi-Temporal, and Multi-Spectral Deep Learning Fusion Approach". The presentation summarised the development of FusionNet, a deep learning model that integrates thermal and short-wave infrared signatures for enhanced cement plant detection.

Paper:
"[Detecting Cement Plants with Landsat-8: A Physics-Informed, Multi-Temporal, and Multi-Spectral Deep Learning Fusion Approach](https://ieeexplore.ieee.org/document/11243713)"  
IEEE IGARSS 2025  
DOI: 10.1109/IGARSS55030.2025.11243713

The presentation covered:

* Challenges of detecting cement plants using remote sensing.
* Use of the Global Database of Cement Production Assets to build a comprehensive dataset.
* Extraction of 1 km2 cement and landcover chips using multi-temporal Landsat-8 imagery.
* Thermal Infrared (Bands 10 and 11) analysis for operational status detection.
* Short Wave Infrared (Bands 6 and 7) analysis for soil moisture and mineralogical changes.
* Introduction of the novel SWIR Band 7:6 ratio for enhanced discriminative power.
* State-of-the-art performance with 90.6 percent accuracy using the Band 7:6 ratio.

FusionNet architecture:

* A signal-processing-parameterised convolutional layer that improves feature extraction from complex spectral patterns.
* Mix Pooling (combined average and max pooling) to capture both global and local spatial statistics.
* Dilated convolutional layers to provide a wider receptive field while preserving fine detail.
* Five unimodal backbones trained on Bands 11, 10, 7, 6, and the Band 7:6 ratio.
* Channel attention mechanism to adaptively reweight spectral contributions.
* CNN5 decoder for final cement/landcover classification.

Key findings:

* SWIR Band 7:6 ratio provides superior discriminative features compared to thermal bands.
* FusionNet consistently outperforms baseline models across all spectral combinations.
* Soil moisture and organic composition changes are more informative than temperature alone.
* Physics-informed multi-spectral fusion significantly improves cement plant detection accuracy.
