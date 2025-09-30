#  🌍 SDG#15. Detection of Deforestation Using CNN

> An evolving list of resources to empower researchers, developers, and activists to apply **CNN for deforestation detection**.
>
> Feel free to update and contribute !

---

## Table of Contents

- [Introduction](#introduction)
- [Scientific Papers](#scientific-papers)
- [Datasets and Benchmarks](#datasets-and-benchmarks)
- [Libraries and Tools](#libraries-and-tools)
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
- N.Thulasi Chitra, et al., (2021). [Satellite Imagery for Deforestation Prediction using Deep Learning](https://ieeexplore.ieee.org/document/9432087), *International Conference on ent Computing and Control Systems (ICICCS)*
- T. Yathesh, T., et al. (2025). [Satellite Image-Based Deforestation Detection Using Deep Learning](https://doi.org/10.1007/978-981-96-3939-7_2), *SCI 2024 Lecture Notes in Networks and Systems*, vol. 1318.
- I. Md Jelas, et al., (2024). [Deforestation detection using deep learning-based semantic segmentation techniques: a systematic review](https://doi.org/10.3389/ffgc.2024.1300060), *Front. For. Glob. Change*, Sec. Forest Management, vol. 7.
- L. Shumilo, et al. (2021). [Automatic Deforestation Detection based on the Deep Learning in Ukraine](https://ieeexplore.ieee.org/document/9661008)," *IEEE International Conference on Intelligent Data Acquisition and Advanced Computing Systems: Technology and Applications (IDAACS)*.
- U. S. Guimarães, et al., (2025).[ Deep learning models to map deforestation based on Sentinel 1 coherent features in the southern border of Amazon](https://www.sciencedirect.com/science/article/pii/S2666017225000859), *Science of Remote Sensing*, vol. 12.
- P. Soto Vega, et al., (2023). [Weakly Supervised Domain Adversarial Neural
Network for Deforestation Detection in Tropical Forests](), *IEEE Journal of Selected Topics in Applied
Earth Observations and Remote Sensing*, 2023, vol. 16.
- M. C. Hansen, et al., (2013).[High-Resolution Global Maps of 21st-Century Forest Cover Change](https://www.science.org/doi/10.1126/science.1244693), *Science*, vol. 342, no. 6160.
- M.O. Adarme, et al., (2020). [Evaluation of Deep Learning Techniques for Deforestation Detection in the Brazilian Amazon and Cerrado Biomes From Remote Sensing Imagery](https://www.mdpi.com/2072-4292/12/6/910), *Remote Sensing*, vol. 12, no. 6.

---

## Datasets and Benchmarks
- **Global Forest Change Dataset (Hansen et al.):** Annual forest loss data from Landsat, global coverage, 30m resolution.  [https://glad.earthengine.app/view/global-forest-change)](https://glad.earthengine.app/view/global-forest-change)
- **Amazon Deforestation Dataset:** High-resolution Sentinel-2 imagery covering Amazon rainforest with annotated deforestation patches.  
  [https://registry.opendata.aws/sentinel-2/](https://registry.opendata.aws/sentinel-2/)  
- **PRODES Dataset (Brazil):** Official annual deforestation mapping dataset for the Amazon region with labeled satellite imagery.  
  [http://terrabrasilis.dpi.inpe.br/en/home-page/](http://terrabrasilis.dpi.inpe.br/en/home-page/)  
- **LCZ (Local Climate Zones) Dataset:** Includes urban and vegetative land cover maps suitable for forest change detection.  
  [https://lcz-generator.rub.de/global-lcz-map](https://lcz-generator.rub.de/global-lcz-map)  
- **BigEarthNet:** Large-scale Sentinel-2 image archive with multi-label land use/land cover annotations including forest classes.  
  [https://bigearth.net/](https://bigearth.net/)

---

## Libraries and Tools
- **DeepForest:** Open-source Python package for tree crown detection in satellite imagery based on CNNs.  
  GitHub: [https://github.com/weecology/DeepForest](https://github.com/weecology/DeepForest)  
- **ForestTools:** R Code repository for Analyzing Remote Sensing Forest Data. 
  GitHub: [https://github.com/andrew-plowright/ForestTools](https://github.com/andrew-plowright/ForestTools)  
- **Remote Sensing Change Detection:** compilation of datasets, tools, methods (including foundation models, diffusion models, transformers, and CNNs) 
  GitHub: [https://github.com/wenhwu/awesome-remote-sensing-change-detection](https://github.com/wenhwu/awesome-remote-sensing-change-detection)


---

## Use Cases
- **Global Forest Watch:** Real-time deforestation alerts leveraging CNN models for rapid detection.  
  [https://www.globalforestwatch.org/](https://www.globalforestwatch.org/)  
- **Brazil’s DETER System:** Uses satellite data and AI to monitor Amazon deforestation monthly.  
  [http://terrabrasilis.dpi.inpe.br/en/deter/](http://terrabrasilis.dpi.inpe.br/en/deter/)  

---

## Courses and Tutorials
- **Deep Learning for Satellite Image Analysis:** by Coursera: [https://www.coursera.org/learn/spatial-analysis-satellite-imagery-in-a-gis](https://www.coursera.org/learn/spatial-analysis-satellite-imagery-in-a-gis)  
- **Introduction to Remote Sensing (Geo University):** by edX: [https://www.geo.university/courses/introduction-to-remote-sensing](https://www.geo.university/courses/introduction-to-remote-sensing)  
- **Semantic Segmentation:** [https://www.classcentral.com/subject/semantic-segmentation](https://www.classcentral.com/subject/semantic-segmentation)  
- **FastAI Practical Deep Learning for Coders (includes satellite imagery projects):** [https://course.fast.ai/](https://course.fast.ai/)  
- **YouTube Tutorial Series on Deep Learning for Remote Sensing:** [https://www.youtube.com/results?search_query=deep+learning+for+remote+sensing](https://www.youtube.com/results?search_query=deep+learning+for+remote+sensing)

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
- **International Geoscience and Remote Sensing Symposium (IGARSS):**[https://ieeexplore.ieee.org/xpl/conhome/1000307/all-proceedings](https://ieeexplore.ieee.org/xpl/conhome/1000307/all-proceedings)
- **Planetary Computer User Community:** [https://planetarycomputer.microsoft.com](https://planetarycomputer.microsoft.com)  
- **Kaggle Competitions and Forums on Satellite Image Analysis:** [https://www.kaggle.com/search?q=Satellite+Image+Analysis](https://www.kaggle.com/search?q=Satellite+Image+Analysis)  

---

## Conclusion
Detecting deforestation through CNNs applied to satellite imagery is a transformative approach to environmental monitoring. The fusion of advanced deep learning architectures with growing datasets empowers researchers and policymakers to act swiftly and accurately. Continued innovation in model design, data acquisition, and interpretability will drive the next generation of deforestation detection systems, playing a critical role in global conservation efforts.

---

