# SDG#3 Prediction of Air Pollution using CNN-LSTM

> An evolving list of resources, tools, datasets, papers, and communities focused on **CNN-LSTM for air pollution prediction**. This collection aims to  cover methodological advances, real-world applications, benchmarking studies, and best practices for spatiotemporal air quality forecasting.
> 
> Feel free to update and contribute !

---

## Table of Contents

- [Introduction](#introduction)
- [Scientific Papers](#scientific-papers)
- [Datasets and Benchmarks](#datasets-and-benchmarks)
- [Libraries and Tools](#libraries-and-tools)
- [Courses and Tutorials](#courses-and-tutorials)
- [Books](#books)
- [Communities and Conferences](#communities-and-conferences)
- [Conclusion](#conclusion)
  
## Introduction

CNN–LSTM (Convolutional Neural Network–Long Short-Term Memory) models are hybrid deep learning architectures that integrate spatial feature extraction with temporal sequence modeling. In air pollution prediction, where pollutant concentrations depend on complex interactions among meteorological variables, emission sources, and historical trends, CNNs effectively capture spatial and local patterns from multivariate sensor data, while LSTMs model long-term temporal dependencies. By leveraging both spatial and temporal information, CNN–LSTM frameworks improve forecasting accuracy for pollutants such as PM2.5, PM10, NO₂, and O₃. Although these models show strong potential for supporting early warning systems, policy-making, and public health protection, their effectiveness depends on data quality, interpretability, and robustness under varying environmental conditions.

## Scientific Papers

- **Li et al.  (2020)** - *A Hybrid CNN-LSTM Model for Forecasting Particulate Matter (PM2.5)*, * IEEE Access*.[DOI](https://doi.org/10.1109/ACCESS.2020.2971348)
- **Bekkar et al.  (2021)** -  *Air-pollution prediction in smart city, deep learning approach*, *J Big Data*.[DOI](https://link.springer.com/article/10.1186/s40537-021-00548-1) 
- **J. Zhang & S. Li (2022)** -  *Air quality index forecast in Beijing based on CNN-LSTM multi-model*, *Chemosphere*.[DOI](https://doi.org/10.1016/j.chemosphere.2022.136180)
- **R. Bao, Y. Zhou & W. Jiang (2022)** – *FL-CNN-LSTM: Indoor Air Quality Prediction Using Fuzzy Logic and CNN-LSTM Model*, *C2022 2nd International Conference on Electrical Engineering and Control Science (IC2ECS)*, [DOI](https://doi.org/10.1109/IC2ECS57645.2022.10088050)
- **Yuan et al. (2025)** – *GAN-based synthetic medical image augmentation for increased CNN performance in liver lesion classificationAttention mechanism based CNN-LSTM hybrid deep learning model for atmospheric ozone concentration prediction*, *Scientific Reports*, [DOI](https://www.nature.com/articles/s41598-025-05877-2)
- **E. Mohapatra, M. Das & S. Rath (2025)** – *Deep learning-based AQI forecasting: a CNN-LSTM model with visual insights from SHAP-LIME and PDP*, *Computer Methods and Programs in Biomedicine*, [DOI](https://link.springer.com/article/10.1007/s42452-025-07845-x)  
- **E. A. Hashim & T.S. Atia (2025)** – *The efficiency of using CNN-LSTM in air quality prediction: A review*, *AIP Conf. Proc.*, [DOI](https://doi.org/10.1063/5.0259070)  


## Datasets and Benchmarks

- **Kaggle Dataset**  
  [https://www.kaggle.com/datasets/eashelfatima/synthetic-healthcare-dataset-for-ai-and-ml](https://www.kaggle.com/datasets/eashelfatima/synthetic-healthcare-dataset-for-ai-and-ml)
- **MIMIC IV** [https://www.nature.com/articles/s41597-022-01899-x](https://www.nature.com/articles/s41597-022-01899-x)
- **Electronic Health Record Datasets** [https://statsupai.org/pages/data_ehr.html](https://statsupai.org/pages/data_ehr.html)
- **Open datasets of the US Office of the National Coordinator (ONC) for Health IT** [https://www.healthit.gov/data/data](https://www.healthit.gov/data/data)
  
## Libraries and Tools

- **Data Sifter** [https://github.com/SOCR/DataSifter](https://github.com/SOCR/DataSifter)
- **Synthetic Data Vault (SDV)** [https://docs.sdv.dev/sdv](https://docs.sdv.dev/sdv)


## Courses and Tutorials

- **AI for Healthcare** (Coursera) [https://www.coursera.org/specializations/ai-healthcare](https://www.coursera.org/specializations/ai-healthcare)
- **AI Applications in Healthcare** [https://www.mygreatlearning.com/academy/learn-for-free/courses/ai-in-healthcare](https://www.mygreatlearning.com/academy/learn-for-free/courses/ai-in-healthcare)
- **Generative AI for Healthcare** (Google) [https://www.skills.google/course_templates/1081](https://www.skills.google/course_templates/1081)

  
## Books

- *Accelerating AI with Synthetic Data* —  Khaled El Emam, 2020 [https://www.oreilly.com/library/view/accelerating-ai-with/9781492045991/](https://www.oreilly.com/library/view/accelerating-ai-with/9781492045991/)
- *Augmented Intelligence in Healthcare: A Pragmatic and Integrated Analysis (Studies in Computational Intelligence, 1024) 1st ed. 2022 Edition* -  Sushruta Mishra, Hrudaya Kumar Tripathy, Pradeep Mallick, Khaled Shaalan (Editors) 2022 [https://link.springer.com/book/10.1007/978-981-19-1076-0](https://link.springer.com/book/10.1007/978-981-19-1076-0)
- *GANs for Data Augmentation in Healthcare* -  Arun Solanki, Mohd Naved (Ed), 2023 [https://link.springer.com/book/10.1007/978-3-031-43205-7](https://link.springer.com/book/10.1007/978-3-031-43205-7)

## Communities and Conferences

- **NEURIPS Workshop on GenAI for Health
Potential, Trust, and Policy Compliance Coral Reef Monitoring Network (GCRMN)**   [https://genai4health.github.io/](https://genai4health.github.io/)
- **International Conference on Generative AI in Healthcare & Science** [https://scientificwisdom.org/conferences/generative-AI-healthcare.html](https://scientificwisdom.org/conferences/generative-AI-healthcare.html)
- **International Conference on AI in Healthcare** [https://aiih.cc/](https://aiih.cc/)
  
## Conclusion

CNN–LSTM–based air pollution prediction is a powerful approach for capturing the spatiotemporal dynamics of atmospheric pollutants, addressing the limitations of traditional statistical models. However, challenges related to data sparsity, model interpretability, and generalization across regions must be carefully managed. The future lies in attention-enhanced CNN–LSTM architectures, transfer and federated learning, and multimodal data fusion (combining sensor data, meteorology, satellite imagery, and traffic information). Collaborative efforts among environmental scientists, data engineers, policymakers, and public health experts will be essential to develop reliable and actionable air quality forecasting systems.

---
**Want to contribute?** Feel free to open an issue or submit a pull request! 🎯
