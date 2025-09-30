#  🌍 SDG#15. Detection of Deforestation Using CNN

> An evolving list of resources to empower researchers, developers, and activists to apply **CNN for deforestation detection**.
>
> Feel free to update and contribute !

---

## Table of Contents

- [Introduction](#introduction)
- [Surveys](#surveys)
- [Scientific Papers](#scientific-papers)
- [Datasets and Benchmarks](#datasets-and-benchmarks)
- [Use Cases](#use-cases)
- [Courses and Tutorials](#courses-and-tutorials)
- [Books](#books)
- [Communities and Conferences](#communities-and-conferences)
- [Conclusion](#conclusion)

---

## Introduction
Deforestation poses a significant threat to biodiversity, climate stability, and ecosystem services worldwide. Automated detection of deforestation from satellite imagery is critical for timely monitoring and intervention. Convolutional Neural Networks (CNNs) have emerged as powerful tools in this domain due to their ability to extract complex spatial features from high-resolution images. This document provides a comprehensive resource list and guidance on CNN-based deforestation detection, covering datasets, research, tools, and applications.


---


## Scientific Papers
1. Hansen et al. (2013). "High-Resolution Global Maps of 21st-Century Forest Cover Change." *Science*.  
   DOI: [10.1126/science.1244693](https://doi.org/10.1126/science.1244693)  
2. Li et al. (2020). "Deep Learning for Deforestation Detection Using Satellite Imagery." *Remote Sensing*.  
   DOI: [10.3390/rs12111819](https://doi.org/10.3390/rs12111819)  
3. Zhu et al. (2017). "Change Detection Based on Deep Neural Networks for Monitoring Forest Deforestation." *IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing*.  
   DOI: [10.1109/JSTARS.2017.2709838](https://doi.org/10.1109/JSTARS.2017.2709838)  
4. Belgiu & Csillik (2018). "Sentinel-2 Image Classification Using Random Forest and Deep Learning Algorithms." *Remote Sensing*.  
   DOI: [10.3390/rs10091455](https://doi.org/10.3390/rs10091455)  
5. Ienco et al. (2019). "Land Cover Classification via Multitemporal Spatial Data by Deep Recurrent Neural Networks." *IEEE Geoscience and Remote Sensing Letters*.  
   DOI: [10.1109/LGRS.2019.2923503](https://doi.org/10.1109/LGRS.2019.2923503)  
6. Other related papers can be found using platforms like [ResearchRabbit](https://researchrabbitapp.com/) or [Scispace](https://scispace.com/).

---

## Datasets and Benchmarks
- **Global Forest Change Dataset (Hansen et al.):** Annual forest loss data from Landsat, global coverage, 30m resolution.  
  [https://earthenginepartners.appspot.com/science-2013-global-forest](https://earthenginepartners.appspot.com/science-2013-global-forest)  
- **Amazon Deforestation Dataset:** High-resolution Sentinel-2 imagery covering Amazon rainforest with annotated deforestation patches.  
  [https://registry.opendata.aws/sentinel-2/](https://registry.opendata.aws/sentinel-2/)  
- **PRODES Dataset (Brazil):** Official annual deforestation mapping dataset for the Amazon region with labeled satellite imagery.  
  [http://terrabrasilis.dpi.inpe.br/en/home-page/](http://terrabrasilis.dpi.inpe.br/en/home-page/)  
- **LCZ (Local Climate Zones) Dataset:** Includes urban and vegetative land cover maps suitable for forest change detection.  
  [http://landscapepartnership.org/lcz-datasets/](http://landscapepartnership.org/lcz-datasets/)  
- **BigEarthNet:** Large-scale Sentinel-2 image archive with multi-label land use/land cover annotations including forest classes.  
  [https://bigearth.net/](https://bigearth.net/)

---

## Libraries and Tools
- **DeepForest:** Open-source Python package for tree crown detection in satellite imagery based on CNNs.  
  GitHub: [https://github.com/weecology/DeepForest](https://github.com/weecology/DeepForest)  
- **Deforestation Detection using U-Net:** Code repository with CNN-based semantic segmentation model applied to satellite images.  
  GitHub: [https://github.com/JohnDoe/deforestation-unet](https://github.com/JohnDoe/deforestation-unet) *(Example repository, verify before use)*  
- **Forest Change Detection CNN:** Includes training scripts and pretrained weights for detecting forest loss from Landsat imagery.  
  GitHub: [https://github.com/example/forest-change-cnn](https://github.com/example/forest-change-cnn) *(Example repository)*  
- Explore [Papers With Code](https://paperswithcode.com/task/deforestation-detection) for latest code-linked research.

---

## Use Cases and Deployed Systems
- **Global Forest Watch:** Real-time deforestation alerts leveraging CNN models for rapid detection.  
  [https://www.globalforestwatch.org/](https://www.globalforestwatch.org/)  
- **Brazil’s DETER System:** Uses satellite data and AI to monitor Amazon deforestation monthly.  
  [http://terrabrasilis.dpi.inpe.br/en/deter/](http://terrabrasilis.dpi.inpe.br/en/deter/)  
- **Conservation NGOs:** Employ CNN-based monitoring tools for illegal logging detection and forest management.  
- **Government agencies:** Integrate CNN-powered deforestation detection in environmental policy enforcement.

---

## Courses and Tutorials
- **Deep Learning for Satellite Image Analysis** by Coursera: [https://www.coursera.org/learn/deep-learning-satellite-imagery](https://www.coursera.org/learn/deep-learning-satellite-imagery)  
- **Remote Sensing and Environmental Monitoring with AI** by edX: [https://www.edx.org/course/remote-sensing-environmental-monitoring](https://www.edx.org/course/remote-sensing-environmental-monitoring)  
- **Semantic Segmentation with CNNs - Udemy:** [https://www.udemy.com/course/semantic-segmentation-with-cnn/](https://www.udemy.com/course/semantic-segmentation-with-cnn/)  
- **FastAI Practical Deep Learning for Coders (includes satellite imagery projects):** [https://course.fast.ai/](https://course.fast.ai/)  
- **YouTube Tutorial Series on CNNs for Remote Sensing:** [https://www.youtube.com/playlist?list=PLremoteSensingCNN](https://www.youtube.com/playlist?list=PLremoteSensingCNN) *(Example playlist)*

---

## Books and Authoritative References
- **"Deep Learning for the Earth Sciences"** by Gustau Camps-Valls et al.  
- **"Remote Sensing Digital Image Analysis"** by John A. Richards and Xiuping Jia  
- **"Deep Learning with Python"** by François Chollet (Keras author)  
- **"Convolutional Neural Networks for Visual Recognition"** by Fei-Fei Li, Justin Johnson, Serena Yeung (Stanford Lecture Notes)  
- **"Introduction to Remote Sensing"** by James B. Campbell and Randolph H. Wynne  

---

## Communities and Conferences
- **IEEE Geoscience and Remote Sensing Society (GRSS):** [https://www.grss-ieee.org/](https://www.grss-ieee.org/)  
- **Remote Sensing Special Interest Groups on LinkedIn and ResearchGate**  
- **International Geoscience and Remote Sensing Symposium (IGARSS)**  
- **Planetary Computer User Community:** [https://planetarycomputer.microsoft.com/community](https://planetarycomputer.microsoft.com/community)  
- **Kaggle Competitions and Forums on Satellite Image Analysis:** [https://www.kaggle.com/](https://www.kaggle.com/)  

---

## Conclusion
Detecting deforestation through CNNs applied to satellite imagery is a transformative approach to environmental monitoring. The fusion of advanced deep learning architectures with growing datasets empowers researchers and policymakers to act swiftly and accurately. Continued innovation in model design, data acquisition, and interpretability will drive the next generation of deforestation detection systems, playing a critical role in global conservation efforts.

---

