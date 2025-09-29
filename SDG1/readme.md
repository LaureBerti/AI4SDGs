
# 🌍 Estimation of Poverty from Satellite Images Using Transformers

> An evolving list of resources, datasets, tools, and papers at the intersection of **poverty mapping**, **remote sensing**, and **transformer-based deep learning models**. Feel free to update and contribute !

---

## 📌 Introduction

Estimating poverty using satellite imagery is a powerful approach to track socioeconomic development in regions lacking reliable census data. Traditional poverty assessments are often expensive, infrequent, and logistically complex—especially in low-income or politically unstable regions. Satellite-based approaches offer scalable, repeatable, and globally consistent methods to infer indicators of wealth and development.

With the advent of **Transformer architectures**, originally developed for natural language processing, we can now model long-range dependencies in spatial imagery and learn better contextual representations. These models have the potential to outperform traditional convolutional neural networks in tasks such as land use classification, asset estimation, and poverty prediction.

This non-exhaustive list gathers available tools, data, and references to help researchers and practitioners harness the power of Transformers for poverty estimation from Earth Observation and make a positive social impact.

---
## Table of Contents

- [Introduction](#introduction)
- [Surveys](#surveys)
- [Scientific Papers](#scientific-papers)
- [Datasets and Benchmarks](#datasets-and-benchmarks)
- [Libraries and Tools](#libraries-and-tools)
- [Use Cases & Projects](#use-cases)
- [Courses and Tutorials](#courses-and-tutorials)
- [Books](#books)
- [Communities and Conferences](#communities-and-conferences)
- [Conclusion](#conclusion)

---

## 📚 Scientific Papers

- Jean, N. et al. (2016). [Combining satellite imagery and machine learning to predict poverty](https://doi.org/10.1126/science.aaf7894). *Science*, 353(6301), 790–794.
- Ayush, K. et al. (2021). [Efficient Poverty Mapping from High-Resolution Satellite Imagery](https://arxiv.org/abs/2101.03489). *arXiv preprint arXiv:2101.03489*.
- Tingzon, I. et al. (2021). [Mapping Poverty in the Philippines Using Satellite Imagery, Survey Data, and Machine Learning](https://cdn.aaai.org/ojs/16072/16072-13-19566-1-2-20210518.pdf). *The Thirty-Fifth AAAI Conference on Artificial Intelligence (AAAI-21*.
- Yeh, C. et al. (2020). [Using publicly available satellite imagery and deep learning to understand economic well-being in Africa](https://www.nature.com/articles/s41467-020-16185-w). *Nature Communications*, 11(1), 2583.
- Steele, J. E. et al. (2017). [Mapping poverty using mobile phone and satellite data](https://royalsocietypublishing.org/doi/10.1098/rsif.2016.0690). *Royal Society Open Science*, 4(10), 170667.

---

## 🧾 [Surveys](#surveys)

- Rolnick, D. et al. (2022). [Tackling Climate Change with Machine Learning](https://arxiv.org/abs/1906.05433). *arXiv:1906.05433*.
- Miller, L. et al. (2024). [Review of Deep Learning Applications in Satellite Imagery](https://ieeexplore.ieee.org/document/10529247). *IEEE Geoscience and Remote Sensing Magazine*.
- Wang, R. et al. (2024). [Transformers for Remote Sensing: A Systematic Review and Analysis](https://www.mdpi.com/1424-8220/24/11/3495). *Sensors, MDPI*.
- Zhu, X. X. et al. (2017). [Deep Learning in Remote Sensing: A Comprehensive Review and List of Resources](https://ieeexplore.ieee.org/document/8113128). *IEEE GRSM*.
- Kamilaris, A. & Prenafeta-Boldú, F. X. (2018). [Deep learning in agriculture: A survey](https://www.sciencedirect.com/science/article/abs/pii/S0168169917308803). *Computers and Electronics in Agriculture*.
- UN Research Dive (2023) [The Seventh Research Dive on
Artificial Intelligence and Machine
Learning for Estimating Poverty](https://www.unglobalpulse.org/wp-content/uploads/2023/12/Technical-Report-Research-Dive-7_AI-and-Machine-Learning-for-Estimating-Poverty_2018.pdf). *UN Global Pulse Tech. Report*.

---

## 🛰️ [Datasets and Benchmarks](#datasets-and-benchmarks)

- [World Bank LSMS Data](https://www.worldbank.org/en/programs/lsms) – Survey-based socioeconomic data across developing countries.
- [XView2 Dataset](https://xview2.org/) – Satellite imagery for disaster response, often used as proxy for infrastructure damage and poverty.
- [NASA Nighttime Lights (VIIRS)](https://ngdc.noaa.gov/eog/viirs/) – Proxy data for economic activity.
- [OpenStreetMap](https://www.openstreetmap.org/) – Spatial features relevant for infrastructure mapping.
- [UP42](https://up42.com/) – High resolution satellite imagery.
- [Datasets for Deep Learning in Earth Observation](https://arxiv.org/abs/2310.19231) - review of EO datasets for Deep Learning.
- [OpenPop](https://www.worldpop.org/) – Satellite and survey data to estimate population and poverty.
  
---

## 🛠️ [Libraries and Tools](#libraries-and-tools)

- [Hugging Face Transformers](https://huggingface.co/transformers/) – State-of-the-art Transformer models.
- [Raster Vision](https://github.com/azavea/raster-vision) – Computer vision models on satellite images.
- [Google Earth Engine](https://earthengine.google.com/) – Planet-scale geospatial analysis.
- [GeoAI](https://github.com/opengeos/geoai) – Framework for geospatial deep learning.
- [satellite-image-deep-learning](https://github.com/satellite-image-deep-learning/techniques) - Resources on deep learning for satellite and aerial image processing.

---

## 🌍 [Use Cases & Projects](#use-cases)


- [AI for Earth (Microsoft)](https://www.microsoft.com/en-us/ai/ai-for-earth) – API & Tools for sustainable development and poverty estimation.
- [Radiant Earth Foundation](https://www.radiant.earth/) – Provides open geospatial training data and tools.
- [UN Global Platform](https://unstats.un.org/bigdata/) – AI and big data initiatives for development goals.


---

## 🎓 [Courses and Tutorials](#courses-and-tutorials)

- [Deep learning Workshop for Satellite Imagery (youtube)](https://www.youtube.com/watch?v=3Xn21RT-y7Y)
- [Google Earth Engine 101: An Introduction for Complete Beginners (youtube)](https://www.youtube.com/watch?v=oAElakLgCdA)
- [Spatial Thoughts OpenCourseWare](https://courses.spatialthoughts.com/end-to-end-gee.html)
- [Transformers (Hugging Face)](https://huggingface.co/learn/computer-vision-course/en/unit7/video-processing/transformers-based-models#video-vision-transformer-vivit)
- [Earth Observation from Space: the Optical View (FutureLearn)](https://www.futurelearn.com/courses/optical-earth-observation)
- [GeoAI with Python (GitHub)](https://www.youtube.com/watch?v=teqyY8GNYRU)

---

## 📖 [Books](#books)

- "Deep Learning for Remote Sensing Images with Open Source Software" by Rémi Cresson, CRC Press, 2020, ISBN 9 780367 858483.
- "Explainable Machine Learning for Geospatial Data Analysis" by Courage Kamusoko,  CRC Press, 2024. [eBook ISBN 9781003398257](https://doi.org/10.1201/9781003398257) 
- "Handbook of Geospatial Artificial Intelligence" by Song Gao, Yingjie Hu, Wenwen Li, CRC Press 2024, ISBN 9781032311661.


---

## 👥 [Communities and Conferences](#communities-and-conferences)

- [ML4EO](https://ml4eo.org/)
- [EarthVision @ CVPR](https://earthvision.site/)
- [AI for Good Global Summit](https://aiforgood.itu.int/)
- [IEEE GRSS Community](https://www.grss-ieee.org/)
- [Radiant MLHub](https://www.radiant.earth/)
- [NeurIPS Climate Change Workshop](https://www.climatechange.ai/)

---

## 🌱 [Conclusion](#conclusion)

Transformer models and deep learning techniques represent a major leap forward in the analysis of satellite imagery for poverty estimation. With their ability to model global spatial relationships, they offer unprecedented accuracy and scalability in extracting socioeconomic insights from complex geospatial data.

Future directions include **multimodal models**, **temporal change detection**, and **explainable AI for policy impact**.



---
