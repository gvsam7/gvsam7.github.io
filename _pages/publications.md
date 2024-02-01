---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

## PhD Thesis
_____
This research focuses on domain adaptation, semantic segmentation and feature extraction in processing aerial scene data using convolutional neural networks. The impact of popular data augmentation techniques on model performance was investigated, with experiments conducted on networks of varying depths and complexity. Data compression, geometric transformations, regional dropout strategies, and pooling augmentations were assessed, with the best-performing models found to be those with deeper architectures trained on full-sized images. Additionally, the research explores transferable features between domains, proposes an architecture that combines salient feature extraction with a wider receptive field and highlights the importance of choosing appropriate feature priors for better model generalisation. The proposed architecture implements an initial Gabor convolutional layer with a mixture of maximum and average pooling layers and dilated convolution layer to reduce the impact of seasonal variations on the feature space distributions. This research provides insights into improving model performance in aerial scene classification by addressing feature bias combined with a widened receptive field and domain shifts. Finally, the impact of the proposed solutions on semantic segmentation was investigated, particularly in detecting water bodies from aerial images. The research explored the unique physical properties of water, namely colour and texture, to identify the features that make water distinguishable. This approach proved to be effective in increasing the semantic segmentation performance of water bodies, even in the presence of light variations and canopy and shadow occlusions.

* Georgios Voulgaris (2023). "[*Deep Learning Aerial Scene Analysis: Extracting Salient Features for Domain Adaptation and Semantic Segmentation Tasks.*](https://sussex.figshare.com/articles/thesis/Deep_learning_aerial_scene_analysis_extracting_salient_features_for_domain_adaptation_and_semantic_segmentation_tasks/24573301)"


## Domain Adaptation
_____
These works provide an overview of my research on domain shifts in aerial scenes due to seasonal variations between wet and dry seasons in the Global South. The aim of this work is to perform an aerial scene analysis and investigate which features Deep Learning models rely on when classifying aerial scenes. Based on the findings, we propose Deep Learning architectures that extract invariant feature representations across wet and dry season domains.

* **Georgios Voulgaris**, Andy Philippides, Jonathan Dolley, Jeremy Reffin, Fiona Marshall, Novi Quadrianto. (2023). "[*Seasonal Domain Shift in the Global South: Dataset and Deep Features Analysis.*](https://openaccess.thecvf.com/content/CVPR2023W/EarthVision/html/Voulgaris_Seasonal_Domain_Shift_in_the_Global_South_Dataset_and_Deep_CVPRW_2023_paper.html)"
<i>Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR) Workshops. </i> Full text available at <a href="https://openaccess.thecvf.com/content/CVPR2023W/EarthVision/html/Voulgaris_Seasonal_Domain_Shift_in_the_Global_South_Dataset_and_Deep_CVPRW_2023_paper.html"> CVPR'23 </a>.

  <span style="color:red;">Poster:</span>
[![Poster](https://gvsam7.github.io/images/Poster_GeorgiosVoulgaris.png)](https://gvsam7.github.io/images/Poster_GeorgiosVoulgaris.png)

* **Georgios Voulgaris**, Andy Philippides, Novi Quadrianto. (2022). "[*Deep Learning Robustness to Domain Shifts During Seasonal Variations.*](https://ieeexplore.ieee.org/abstract/document/9883940)"
<i>International Geoscience and Remote Sensing Symposium (IGARSS). </i> Full text available at <a href="https://ieeexplore.ieee.org/abstract/document/9883940"> IGARSS'22 </a>.

  <span style="color:red;">Poster:</span>
[![Poster](https://gvsam7.github.io/images/Poster_GeorgiosVoulgaris_IGARSS2022.png)](https://gvsam7.github.io/images/Poster_GeorgiosVoulgaris_IGARSS2022.png)


  <span style="color:red;">Presentation:</span>
[![Presentation](https://img.youtube.com/vi/Zci4eASXmkQ/maxresdefault.jpg)](https://www.youtube.com/watch?v=Zci4eASXmkQ)

## Semantic Segmentation
_____
These works provide an overview of my research in semantic segmentation of aerial scenes.

* [Update] 1 more paper (first author) under blind peer-review.

* **Georgios Voulgaris**, Andy Philippides, Novi Quadrianto. (2023). "[*Water Physics Aware Semantic Segmentation Through Texture-Biased U-Net Architectures.*](https://ieeexplore.ieee.org/abstract/document/10281796)"
<i>International Geoscience and Remote Sensing Symposium (IGARSS). </i> Full text available at <a href="https://ieeexplore.ieee.org/abstract/document/10281796"> IGARSS'23 </a>.

## Remote Sensing Scene Classification
_____
These works provide an overview of my research in using remote sensing data and Deep Learning architectures to detect pollutant plants in China. I used Landsat-8 remote sensors (Thermal Infrared and Operational Land Imager) to create datasets consisting of thermal infrared (bands 10 and 11), short wave infrared (bands 6 and 7), and a geological ratio of the short-wave infrared image chips for two classes (cement plants and the surrounding land cover). I then trained and validated various state-of-the-art deep learning architectures (VGG, ResNet, EfficientNet) on the created datasets.  

* Cristian Rossi, Nataliya Tkachenko, Maral Bayaraa, Peter Foster, Steven Reece, Kimberly Scott, **Georgios Voulgaris**, Christophe Christiaen, Matthew McCarten. (2022). "[*Detection and Characterisation of Pollutant Assets with AI and EO to Prioritise Green Investments: The Geoasset Framework.*](https://ieeexplore.ieee.org/abstract/document/9883772)"
<i>International Geoscience and Remote Sensing Symposium (IGARSS). </i> Full text available at <a href="https://ieeexplore.ieee.org/abstract/document/9883772"> IGARSS'22 </a>.

    <span style="color:red;">Presentation:</span>
[![Presentation](https://img.youtube.com/vi/0xkWbdjljWk/maxresdefault.jpg)](https://www.youtube.com/watch?v=0xkWbdjljWk)

<!-- {% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %} -->
