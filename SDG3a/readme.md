# SDG#3 Augmentation of Healthcare Data Using GANs

> An evolving list of resources, tools, datasets, papers, and communities focused on **GAN-based augmentation of healthcare data**. This collection aims to empower biomedical scientists, machine learning researchers, healthcare specialists, and students to leverage cutting-edge AI for Healthcare.

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

GANs (Generative Adversarial Networks) are deep neural architectures where two networks—a generator and a discriminator—compete, enabling realistic synthetic data creation. In healthcare, where labeled medical data are scarce, expensive, and privacy-sensitive, GANs can generate realistic images (e.g., X-rays, MRIs), time-series, and electronic health records (EHR), boosting model performance. While GAN-generated data offer potential to improve diagnostics, training robustness, and equity, they require careful validation to avoid clinical misinterpretation and protect patient privacy.

## Scientific Papers

- **Patki, N., Wedge, R. & Veeramachaneni, K. (2016)** -  *The synthetic data vault*, *2016 IEEE International Conference on Data Science and Advanced Analytics (DSAA)*.[DOI](https://ieeexplore.ieee.org/document/7796926)
- **Frid-Adar et al. (2018)** – *GAN-based synthetic medical image augmentation for increased CNN performance in liver lesion classification*, *Neurocomputing*, [DOI](https://doi.org/10.1016/j.neucom.2018.09.013)
- **Barile et al. (2021)** – *Data augmentation using generative adversarial neural networks on brain structural connectivity in multiple sclerosis*, *Computer Methods and Programs in Biomedicine*, [DOI](https://doi.org/10.1016/j.cmpb.2021.106113)  
- **Chen et al. (2022)** – *Generative Adversarial Networks in Medical Image Augmentation: A RevieGenerative Adversarial Networks in Medical Image augmentation: A review*, *Computers in Biology and Medicine*, [DOI](https://www.sciencedirect.com/science/article/abs/pii/S0010482522001743)
- **Kebaili et al. (2023)** – *Deep Learning Approaches for Data Augmentation in Medical Imaging: A Review*, *J. Imaging*, [DOI](https://doi.org/10.3390/jimaging9040081)  
- **Pezoulas et al. (2024)** – *Synthetic data generation methods in healthcare: A review on open-source tools and methods*, *Computational and Structural Biotechnology Journal*, [DOI](https://doi.org/10.1016/j.csbj.2024.07.005)  
- **Islam et al. (2024)** – *A systematic review of deep learning data augmentation in medical imaging: Recent advances and future research directions*, *Healthcare Analytics*, [DOI](https://doi.org/10.1016/j.health.2024.100340)
- **Goveri (2024)** – *Medical image data augmentation: techniques, comparisons and interpretations*, *Artif Intell Rev*, [DOI](https://link.springer.com/article/10.1007/s10462-023-10453-z)
- **Marino et al. (2025)** – *Medical data sharing and synthetic clinical data generation – maximizing biomedical resource utilization and minimizing participant re-identification risks*, *npj Digital Medicine volume*, [DOI](https://www.nature.com/articles/s41746-025-01935-1)
- **Rujas et al. (2025)** - *Synthetic data generation in healthcare: A scoping review of reviews on domains, motivations, and future applications*, *International Journal of Medical Informatics*, [DOI](https://www.sciencedirect.com/science/article/pii/S138650562400426X)



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

GAN-based augmentation of healthcare data is a transformative force, addressing data scarcity while supporting improved model accuracy and equity. However, clinical validity, privacy, and bias must be carefully managed. The future lies in **differentially private GANs, federated model training**, and **multimodal data synthesis** (combining imaging, vitals, and genomics). Collaborative efforts among clinicians, data scientists, ethicists, and regulators will be essential to build trustworthy, impactful solutions. 

---
**Want to contribute?** Feel free to open an issue or submit a pull request! 🎯
