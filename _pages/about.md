---
permalink: /
# title: "Georgios Voulgaris"
excerpt: "About me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---


I am a [Postdoctoral researcher](https://www.biology.ox.ac.uk/people/georgios-voulgaris) in Deep Learning and Computer Vision at the University of Oxford, working with [Prof Ben Sheldon](https://www.biology.ox.ac.uk/people/professor-ben-sheldon).

<!--My research focuses on designing innovative deep learning architectures that advance feature representation learning — particularly for extracting salient features in complex, densely populated scenes.

Additionally, I investigate multimodal deep learning and data fusion techniques, exploring how combining diverse modalities — such as RGB, hyperspectral, and thermal imagery — can improve model generalisation across domains. By advancing deep learning architectures, my work drives methodological innovation, validated through remote sensing.

**My current research portfolio includes:**
* Introducing a novel semantic segmentation architecture featuring custom convolutional layers that enhance feature extraction in complex visual domains, advancing segmentation robustness beyond standard methods.
* Developing hybrid CNN-Transformer architectures that redefine feature attention mechanisms, optimising the synergy between convolutional feature locality and Transformer-based global context modelling.
*	Designing multimodal mid-level data fusion architectures for industrial monitoring using multi-temporal and multi-spectral remotely sensed data.
*	Creating robust segmentation models for UAV-based waterbody semantic segmentation, resilient to occlusion and shadowing.
*	Enhancing deep learning robustness to seasonal domain shifts through invariant feature representation.

To advance deep learning model development, I curate high-quality datasets for various computer vision tasks across diverse environments. -->

My research investigates how inductive biases derived from visual perception and physical signal formation shape representation learning in deep neural networks. I focus on embedding principles such as frequency selectivity, texture shape decomposition, and modality aware priors into learnable architectures, with the aim of improving robustness, interpretability, and generalisation under real world conditions.

A central theme of my work is the design of novel convolutional and hybrid CNN–Transformer architectures that explicitly encode perceptual and physical priors. Rather than treating non-RGB sensing modalities as domain specific applications, I use them as stress tests for modern deep learning, exposing systematic failure modes in texture biased models and motivating principled architectural corrections.

I also study multimodal and multi-spectral learning, where I treat the physical properties of sensed data as a source of inductive bias rather than nuisance variability. By grounding model design in the physics of image formation, I develop data fusion strategies that improve cross-sensor generalisation and failure-mode interpretability, particularly in visually complex and densely populated scenes.

My methodological contributions are validated on challenging real world datasets, including satellite and UAV imagery, where uncontrolled conditions such as occlusions, reflections, shadows, seasonal variation, and domain shifts are unavoidable. These settings provide a rigorous testbed for advancing representation learning beyond synthetic or overly curated benchmarks.

<!--My research advances deep learning by integrating principles of visual perception, such as texture, shape, and frequency analysis, into novel network architectures. I design and validate new convolutional and hybrid CNN–Transformer models that enhance feature representation and robustness in complex, densely populated scenes.

I also investigate multimodal deep learning and data fusion, developing models informed by the physical properties of remotely sensed data to improve generalisation and interpretability across environmental domains. By advancing deep learning architectures, my work drives methodological innovation validated through real-world remote sensing challenges. -->

**Current research themes:**
* Representation learning with explicit inductive biases, including frequency aware and perceptually grounded convolutional operators.
* Semantic segmentation architectures featuring custom convolutional layers for complex visual domains.
* Hybrid CNN–Transformer models that optimise the synergy between local feature extraction and global context modelling.
* Multimodal and multi-spectral data fusion as a testbed for robust learning under physical constraints.
* UAV based segmentation models resilient to occlusions, reflections, shadows, and illumination variability.
* Domain-invariant feature learning for improved cross-sensor and cross-season generalisation.

<!--* Semantic segmentation architectures featuring custom convolutional layers for complex visual domains.
* Hybrid CNN–Transformer architectures optimising the synergy between local and global feature representations.
* Multimodal and multi-spectral data fusion for environmental and industrial monitoring.
* UAV-based segmentation models resilient to occlusions, shadows, and light variation.
* Domain-invariant feature learning for improved cross-sensor and cross-season performance.

To support deep learning model development, I curate high-quality datasets for computer vision and remote sensing applications. -->

**Datasets and Experimental Infrastructure**
To support and stress test methodological development, I curate high quality datasets that expose real world failure modes in computer vision and remote sensing models. These datasets are designed not as standalone contributions, but as measurement instruments for analysing representation robustness, inductive bias, and generalisation behaviour under physically grounded variability.

<!-- Part of my research creating high-quality datasets tailored for classification, semantic segmentation, and instance segmentation tasks, enabling robust and scalable solutions across diverse domains. -->

<!-- My research aims to improve feature representation learning in deep networks, focusing on salient feature extraction for segmentation tasks in dense scenes. My work bridges theoretical advancements in feature representation learning with practical applications in remote sensing, environmental monitoring, and industrial scene understanding.-->

**Background:**

I completed an EPSRC-funded PhD at the University of Sussex supervised by [Prof. Andy Philippides](https://profiles.sussex.ac.uk/p23611-andy-philippides) and [Prof. Novi Quadrianto](https://profiles.sussex.ac.uk/p335583-novi-quadrianto), where my research focused on salient feature representation, domain adaptation, and semantic segmentation. This work laid the foundations of my current research agenda by investigating how feature representations degrade under domain shift and how architectural design choices influence generalisation.

<!-- Prior to that I was an EPSRC funded PhD candidate, working on Deep Learning for Remote Sensing systems at the University of Sussex, advised by [Prof. Andy Philippides](https://profiles.sussex.ac.uk/p23611-andy-philippides) and [Prof. Novi Quadrianto](https://profiles.sussex.ac.uk/p335583-novi-quadrianto). My research focused on developing novel Deep Learning models that extract salient feature representations for domain adaptation and semantic segmentation tasks. -->

As part of the [Predictive Analytics Lab](https://wearepal.ai/) (PAL), I contributed to a [British Academy-funded project on Satellite/Aerial Image Scene Segmentation](https://wearepal.ai/projects/ssrp)on satellite and aerial image scene segmentation. In this context, I designed deep learning models for land use classification and multi-domain, multi-temporal data integration, using large scale real world imagery to study robustness under heterogeneous sensing conditions. Please see the [demo](https://www.youtube.com/watch?v=AFC0Z3B0lzY) below.
<!-- Being part of the [Predictive Analytics Lab](https://wearepal.ai/) (PAL) – an interdisciplinary research team, I was involved in a British Academy funded project focused on Satellite/Aerial Image Scene Segmentation, where I designed novel Deep Learning models that classify land use from satellite/aerial images. For more details please see: - [PAL](https://wearepal.ai/projects/ssrp). The aim of the project was to apply deep learning techniques, to map peri-urban agriculture in Ghaziabad India, and research ways of integrating multiple types of data through a web-based mapping and visualisation tool. This project contributed to the [SDG 11: Sustainable Cities and Communities](https://sdgs.un.org/goals/goal11). Please see the [demo](https://www.youtube.com/watch?v=AFC0Z3B0lzY) below.-->
![demo](https://gvsam7.github.io/images/Deep_Learning_Satellite_Image_Scene_Classification_Demo.gif)
During my research internship at Satellite Applications Catapult (supervised by [Dr Cristian Rossi](https://ieeexplore.ieee.org/author/37590354100)), I applied physics aware machine learning to industrial remote sensing, developing models that leveraged physical properties such as temperature and soil moisture to detect and characterise cement production facilities in China. This experience directly informed my subsequent work on embedding physical signal properties as inductive bias in deep learning architectures. <!-- This project contributes to the [SDG 9: Industry, Innovation and Infrastructure](https://sdgs.un.org/goals/goal9). -->

**Industrial Experience:**

Prior to my doctoral studies, I worked as a Control and Automation Design Engineer in the oil and gas industry. This role provided hands-on experience with sensor driven systems, signal acquisition, control architectures, and safety critical software development, shaping my long standing interest in how physical processes, sensing constraints, and system design interact with data driven models.

**Open to Collaboration:**

I am always interested in discussing new research directions and potential collaborations, particularly around representation learning, inductive bias, and robust perception under real world sensing constraints. Feel free to get in touch!

## Recent News

* June 2025: Paper *Bridging Classical and Modern Computer Vision...* accepted as a spotlight and a poster at Greeks in AI'25 Symposium!  
* May 2025: Gave a seminar in Embedding Differential Signal Processing Priors to Deep Learning models at [Oxford Mathematical Institute Machine Learning and Data Science Seminar](https://www.maths.ox.ac.uk/node/71163)!
* April 2025: Paper *Bridging Classical and Modern Computer Vision...* got into EarthVision CVPR'25!
* March 2025: Paper *Detecting Cement Plants with Landsat-8...* got into IGARSS'25 Oral!
* March 2025: [Computer Vision for Ecological and Biodiversity Monitoring](https://cvebm.blogs.lincoln.ac.uk/) ICIP Workshop Organising Committee!
* March 2025: [EarthVision](https://www.grss-ieee.org/events/earthvision-2025/?tab=people) CVPR Workshop Technical Committee!
* March 2024: [EarthVision](https://www.grss-ieee.org/events/earthvision-2024/?tab=people) CVPR Workshop Technical Committee!
* November 2023: Postdoctoral Researcher - Sheldon Lab [University of Oxford](https://www.biology.ox.ac.uk/people/georgios-voulgaris)!
* August 2023: Passed my PhD Viva!
* July 2023: Chaired session *Image Analysis for the Remote Sensing of Water Bodies* on IGARSS'23!
* July 2023: Presented my paper *Physics Aware Semantic Segmentation...* on IGARSS'23!
* June 2023: Presented my paper *Seasonal Domain Shift...* on EarthVision CVPR'23!
* May 2023: Submitted my Thesis!
* April 2023: Paper *Seasonal Domain Shift in the Global South...* got into EarthVision CVPR'23!
* April 2023: Paper *Physics Aware Semantic Segmentation...* got into IGARSS'23 Oral!
* July 2022: Presented my paper *Deep Learning Robustness to Domain Shifts...* on IGARSS'22!
* May 2022: Presented my internship research *Remote Sensing & Deep Learning Polluting Plant Detection...* on DISCnet consortium!
* April 2022: Paper *Deep Learning Robustness to Domain Shifts...* got into IGARSS'22!
* April 2022: Paper *Detection and Characterisation of Pollutant Assets...* got into IGARSS'22 Oral!
* January 2022: Research Internship Satellite Applications Catapult!
* January 2021: Awarded DISCnet Scholarship!
* August 2020: Machine Learning Summer School Indonesia (Awards Received: Most Active Participant, Best Research Proposal)!
* January 2020: Joined British Academy funded project, *Aerial Image Scene Segmentation*!
* November 2019: Presented a demo for Detecting Water Bodies from UAVs to National Rail!
