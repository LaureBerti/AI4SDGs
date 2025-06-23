
# 🌍 Awesome: Estimation of Poverty from Satellite Images Using Transformers

> A curated list of resources, datasets, tools, and papers at the intersection of **poverty mapping**, **remote sensing**, and **Transformer-based deep learning models**.

---

## 📌 Introduction

Estimating poverty using satellite imagery is a powerful approach to track socioeconomic development in regions lacking reliable census data. Traditional poverty assessments are often expensive, infrequent, and logistically complex—especially in low-income or politically unstable regions. Satellite-based approaches offer scalable, repeatable, and globally consistent methods to infer indicators of wealth and development.

With the advent of **Transformer architectures**, originally developed for natural language processing, we can now model long-range dependencies in spatial imagery and learn better contextual representations. These models have the potential to outperform traditional convolutional neural networks in tasks such as land use classification, asset estimation, and poverty prediction.

This list gathers the best available tools, data, and references to help researchers and practitioners harness the power of Transformers for poverty estimation and make a positive social impact.

---

## 📚 Scientific Papers

- Jean, N. et al. (2016). [Combining satellite imagery and machine learning to predict poverty](https://doi.org/10.1126/science.aaf7894). *Science*, 353(6301), 790–794.
- Ayush, K. et al. (2021). [Efficient Poverty Mapping from High-Resolution Satellite Imagery](https://arxiv.org/abs/2101.03489). *arXiv preprint arXiv:2101.03489*.
- Tingzon, I. et al. (2021). [Mapping Poverty in the Philippines Using Satellite Imagery, Survey Data, and Machine Learning](https://arxiv.org/abs/2101.10761). *arXiv preprint arXiv:2101.10761*.
- Yeh, C. et al. (2020). [Using publicly available satellite imagery and deep learning to understand economic well-being in Africa](https://www.nature.com/articles/s41467-020-16185-w). *Nature Communications*, 11(1), 2583.
- Steele, J. E. et al. (2017). [Mapping poverty using mobile phone and satellite data](https://doi.org/10.1098/rsos.170667). *Royal Society Open Science*, 4(10), 170667.

---

## 🧾 Surveys and Literature Reviews

- Rolnick, D. et al. (2022). [Tackling Climate Change with Machine Learning](https://arxiv.org/abs/1906.05433). *arXiv:1906.05433*.
- Singh, K. et al. (2021). [Review of Deep Learning Applications in Satellite Imagery](https://arxiv.org/abs/2104.03988). *arXiv preprint arXiv:2104.03988*.
- Li, X. et al. (2022). [A Review of Transformer Models in Remote Sensing](https://arxiv.org/abs/2206.08564). *arXiv preprint arXiv:2206.08564*.
- Zhu, X. X. et al. (2017). [Deep Learning in Remote Sensing: A Comprehensive Review](https://ieeexplore.ieee.org/document/8063443). *IEEE GRSM*.
- Kamilaris, A. & Prenafeta-Boldú, F. X. (2018). [Deep learning in agriculture: A survey](https://doi.org/10.1016/j.compag.2018.01.009). *Computers and Electronics in Agriculture*.

---

## 🛰️ Datasets and Benchmarks

- [World Bank LSMS Data](https://www.worldbank.org/en/programs/lsms) – Survey-based socioeconomic data across developing countries.
- [XView2 Dataset](https://xview2.org/) – Satellite imagery for disaster response, often used as proxy for infrastructure damage and poverty.
- [NASA Nighttime Lights (VIIRS)](https://ngdc.noaa.gov/eog/viirs/) – Proxy data for economic activity.
- [OpenStreetMap](https://www.openstreetmap.org/) – Spatial features relevant for infrastructure mapping.
- [SpaceNet Dataset](https://spacenet.ai/) – Labeled satellite imagery for building and road detection.

---

## 🛠️ Libraries and Tools

- [Hugging Face Transformers](https://huggingface.co/transformers/) – State-of-the-art Transformer models.
- [PyTorch Lightning](https://www.pytorchlightning.ai/) – Simplifies training for Transformer models.
- [Raster Vision](https://github.com/azavea/raster-vision) – Deep learning on satellite imagery.
- [Google Earth Engine](https://earthengine.google.com/) – Planet-scale geospatial analysis.
- [GeoTorch](https://github.com/ai4geo/geo-torch) – Framework for geospatial deep learning.

---

## 🌍 Use Cases & Projects

- [OpenPop](https://www.worldpop.org/) – Uses satellite and survey data to estimate population and poverty.
- [AI for Earth (Microsoft)](https://www.microsoft.com/en-us/ai/ai-for-earth) – Tools for sustainable development and poverty estimation.
- [Radiant Earth Foundation](https://www.radiant.earth/) – Provides open geospatial training data and tools.
- [UN Global Platform](https://unstats.un.org/bigdata/) – AI and big data initiatives for development goals.
- [Facebook Data for Good](https://dataforgood.facebook.com/) – Mobility and connectivity data used in social science applications.

---

## 🎓 Courses and Tutorials

- [Deep Learning with Satellite Imagery (Coursera)](https://www.coursera.org/learn/deep-learning-satellite-imagery)
- [Remote Sensing with Google Earth Engine (YouTube Playlist)](https://www.youtube.com/playlist?list=PLzudUcx7bEwhEnLnzR4nKpknK1QNA2Rza)
- [Transformers from Scratch (Hugging Face)](https://huggingface.co/transformers/course/index.html)
- [Earth Observation 101 (FutureLearn)](https://www.futurelearn.com/courses/earth-observation)
- [GeoAI with Python (GitHub)](https://github.com/developmentseed/geoai)

---

## 📖 Books

- "Deep Learning for Satellite Image Analysis" by Pierre Soille et al.
- "Geospatial Deep Learning" by Daniel A. Griffith
- "Transformers for Natural Language Processing" by Denis Rothman (conceptual overlap)
- "Machine Learning for Earth Observation" by Gustavo Camps-Valls
- "Artificial Intelligence for Earth Systems" by Peter Atkinson

---

## 👥 Communities & Conferences

- [EarthVision @ CVPR](https://earthvision.site/)
- [AI for Good Global Summit](https://aiforgood.itu.int/)
- [IEEE GRSS Community](https://www.grss-ieee.org/)
- [Radiant MLHub](https://www.radiant.earth/mlhub/)
- [NeurIPS Climate Change Workshop](https://www.climatechange.ai/)

---

## 🌱 Conclusion

Transformer models represent a major leap forward in the analysis of satellite imagery for poverty estimation. With their ability to model global spatial relationships, they offer unprecedented accuracy and scalability in extracting socioeconomic insights from complex geospatial data.

Whether you're a researcher, policymaker, or developer, these resources will help you dive into one of the most promising intersections of AI and global development. Future directions include **multimodal models**, **temporal change detection**, and **explainable AI for policy impact**.

> 🚀 Let’s harness these technologies to build a fairer, data-informed, and more equitable world.

---
