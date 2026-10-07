---
title: Foundations of Spatial AI for Earth Observation
description: A complete, open-access curriculum bridging fundamental data theory with deep learning deployment for applied scientists.
permalink: /teaching/spatial-ai-course/
date: 2024-01-01
---

# Foundations of Spatial AI for Earth Observation
### An Open‑Access Curriculum for Interdisciplinary Environmental Scientists

**Instructor:** Georgios Voulgaris  
**Audience:** Ecologists, geographers, environmental scientists, and other non‑CS researchers working with spatial data.  
**Prerequisites:** None. The course is designed to onboard researchers from first principles through to model deployment and verification.

---

## Contents
1. Pedagogical Rationale  
2. Phase 1 — Foundational Data Theory  
3. Phase 2 — Curation, Annotation, Engineering  
4. Phase 3 — Deep Learning Deployment  
5. Open‑Source Code Repositories  

---

## Pedagogical Rationale

Modern environmental science increasingly relies on complex sensor data and machine‑learning workflows, yet most domain scientists receive little formal training in data engineering or spatial AI. This curriculum was developed during my postdoctoral work in the Sheldon Group (University of Oxford), where recurring gaps in computational foundations were evident among researchers applying AI to ecological and remote‑sensing problems.

The course provides a **rigorous, architecture‑aware introduction to spatial AI**, emphasising:

- Correct data representation and structural validation  
- Reproducible engineering practices  
- Safe and interpretable deployment of deep learning models  
- Avoidance of methodological pitfalls such as spatial autocorrelation leakage  

The aim is to equip non‑CS researchers with the conceptual and practical grounding required to use modern AI methods responsibly.

---

## Phase 1 — Foundational Data Theory & Representation

### 1. Data Theory and the Digital Image

**Topics:**
- Pixels as physical measurements  
- Bit‑depth constraints (8‑bit vs 16‑bit)  
- Tensor structure: \(H \times W \times C\)  
- Differences between geospatial rasters (GeoTIFF) and standard graphics formats (JPEG/PNG)

**Outcome:**  
Understanding an image as a structured numerical matrix rather than a visual artefact.

---

### 2. Computer Vision Paradigms

**Topics:**
- Classification (image‑level labels)  
- Semantic segmentation (pixel‑level mapping)  
- Object detection (bounding‑box regression)  
- Instance segmentation (object‑specific masks)

**Outcome:**  
Ability to identify the correct computer‑vision paradigm for a given environmental application.

---

## Phase 2 — Curation, Annotation, and Engineering Rigor

### 3. Annotation Architecture

**Topics:**
- Structure of COCO JSON, Pascal VOC XML, YOLO text formats  
- Mathematical parsing of label files  
- Consistency checks and schema validation

---

### 4. Annotation Tools & Human‑in‑the‑Loop Workflows

**Topics:**
- CVAT, Label Studio  
- Weak‑label generation using foundation models  
- Expert auditing and iterative refinement  
- Designing scalable HITL pipelines for environmental datasets

---

### 5. Data Processing for Deep Learning

**Topics:**
- Interpolation, cropping, tiling, and normalisation  
- Handling extreme aspect ratios  
- Radiometric and geometric augmentation  
- Mitigating sensor and illumination biases

---

## Phase 3 — Practical Deep Learning Deployment

### 6. Deep Learning Fundamentals: Image Classification

**Topics:**
- Data loaders and training loops  
- Backbone initialisation  
- Optimisers (Adam, SGD)  
- Cross‑Entropy loss  
- Training/validation/testing structure  
- Geographic partitioning to avoid spatial autocorrelation leakage

---

### 7. Semantic Segmentation

**Topics:**
- Loading binary and multi‑class masks  
- Spatial loss functions (Dice, IoU)  
- Evaluating geographic coverage and spatial consistency

---

### 8. Object Detection & Instance Segmentation

**Topics:**
- Anchor‑box mechanics  
- Coordinate regression losses  
- Mask generation  
- Mean Average Precision (mAP) evaluation

---

## Open‑Source Code Repositories

The course is supported by modular, object‑oriented PyTorch implementations designed for reproducibility and clarity.

- **Core PyTorch Architecture Templates**  
  <https://github.com>

- **Spatial Cross‑Validation Frameworks**  
  <https://github.com>

---
