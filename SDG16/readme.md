# 🕊️ Awesome Prediction of Social Conflicts Using GNNs

> A curated list of resources, datasets, papers, and tools for predicting social conflicts using Graph Neural Networks (GNNs). Inspired by the [Awesome List Manifesto](https://github.com/sindresorhus/awesome/blob/main/awesome.md). Contributions welcome!

## Table of Contents

- [Introduction](#introduction)
- [Surveys and Review Papers](#surveys-and-review-papers)
- [Key Scientific Papers](#key-scientific-papers)
  - [Foundational Papers](#foundational-papers)
  - [Follow-Up and Related Papers](#follow-up-and-related-papers)
- [Papers with Code](#papers-with-code)
- [Datasets and Benchmarks](#datasets-and-benchmarks)
- [Open Source Tools and Libraries](#open-source-tools-and-libraries)
- [Use Cases and Applications](#use-cases-and-applications)
- [Tutorials and Courses](#tutorials-and-courses)
- [Books and Authoritative References](#books-and-authoritative-references)
- [Communities and Conferences](#communities-and-conferences)
- [Conclusion and Future Directions](#conclusion-and-future-directions)

## Introduction

Predicting social conflicts—ranging from protests and civil unrest to broader geopolitical instability—is a growing field that leverages machine learning to inform peacebuilding and preventive action. Graph Neural Networks (GNNs) offer powerful tools for modeling relational and dynamic structures common in socio-political data (e.g., actor networks, temporal sequences, geographic clustering). By learning from both network structure and node attributes, GNNs enable fine-grained forecasting of social phenomena at scale.

## Surveys and Review Papers

1. [A Survey on Event Forecasting using Text and Graph Neural Networks (2023)](https://arxiv.org/abs/2303.00105)
2. [Early Warning and Conflict Prediction with Machine Learning (2021)](https://journals.sagepub.com/doi/full/10.1177/0022343321995540)
3. [Graph Neural Networks: A Review of Methods and Applications (2021)](https://arxiv.org/abs/1812.08434)
4. [Deep Learning for Political Science (2020)](https://www.annualreviews.org/doi/10.1146/annurev-polisci-052918-020807)
5. [Social Network Analysis and Conflict Forecasting: A Review (2019)](https://www.cambridge.org/core/journals/international-organization/article/abs/forecasting-political-conflict-and-violence/)

## Key Scientific Papers

### Foundational Papers

1. **[Graph Neural Networks for Predicting Social Unrest (2022)](https://arxiv.org/abs/2206.04533)** - Nguyen et al. introduce a GNN-based method for protest forecasting using temporal and network data.  
2. **[Forecasting Protests with GNNs and News Data (2021)](https://aclanthology.org/2021.acl-long.498/)** - Explores social signals and graph dynamics for unrest prediction.  
3. **[A Deep Learning Approach to Predict Civil Unrest Using News (2019)](https://ieeexplore.ieee.org/document/8715564)** - Early integration of GNNs and NLP for social instability forecasting.  
4. **[Spatiotemporal Graph Neural Networks for Forecasting Social Events (2020)](https://arxiv.org/abs/2001.03055)**  
5. **[Using Heterogeneous Graphs for Protest Prediction (2022)](https://arxiv.org/abs/2205.09845)** - GNNs on event networks, embeddings, and hybrid architectures.

### Follow-Up and Related Papers

- [Deep Learning Forecasting Models for Conflict Events (2023)](https://arxiv.org/abs/2305.01234)  
- [GNN-based Crisis Mapping from News and Tweets (2022)](https://arxiv.org/abs/2211.03672)  
- [Multi-modal Early Warning Systems for Conflict using GNN + LLM (2023)](https://arxiv.org/abs/2307.12918)  
- [Forecasting Ethnic Violence with Topological Graph Models (2021)](https://www.sciencedirect.com/science/article/pii/S0261379421001576)  
- [Temporal Graph Attention Networks for Forecasting Instability (2022)](https://arxiv.org/abs/2212.01475)

## Papers with Code

1. [Social Unrest Prediction with GNNs](https://paperswithcode.com/paper/graph-neural-networks-for-predicting-social) [[GitHub](https://github.com/socialsensor/GNN-unrest)]
2. [Protest Event Forecasting Using ST-GCN](https://paperswithcode.com/paper/forecasting-social-unrest-events-using)  
3. [Conflict Prediction on Dynamic Graphs](https://paperswithcode.com/task/conflict-prediction)  
4. [Temporal GNN for Social Systems](https://paperswithcode.com/paper/tgn-temporal-graph-networks-for-deep-learning)  
5. [Heterogeneous Graphs for Event Prediction](https://github.com/social-events/heteroGNN-conflict)

## Datasets and Benchmarks

1. [ACLED - Armed Conflict Location & Event Dataset](https://acleddata.com/) - Political violence and protest events globally.  
2. [UCDP - Uppsala Conflict Data Program](https://ucdp.uu.se/) - Comprehensive conflict event data.  
3. [GDELT - Global Database of Events, Language, and Tone](https://www.gdeltproject.org/)  
4. [ICEWS - Integrated Conflict Early Warning System](https://dataverse.harvard.edu/dataverse/icews)  
5. [PHEME Dataset](https://figshare.com/articles/dataset/PHEME_dataset_for_rumour_detection_and_veracity_classification/6392078) - Social media interactions during crises.  
6. [Global Twitter Graphs for Crisis Events](https://crisisnlp.qcri.org/)  
7. [Open Graph Benchmark - Social Datasets](https://ogb.stanford.edu/)

## Open Source Tools and Libraries

1. [PyTorch Geometric](https://pytorch-geometric.readthedocs.io/)  
2. [DGL - Deep Graph Library](https://www.dgl.ai/)  
3. [networkx](https://networkx.org/) - General-purpose graph modeling.  
4. [graph-tool](https://graph-tool.skewed.de/)  
5. [Snorkel](https://www.snorkel.org/) - Weak supervision for noisy conflict data.  
6. [SocioPatterns](http://www.sociopatterns.org/)  
7. [ConflictNet Toolkit](https://github.com/conflictnet)

## Use Cases and Applications

1. [UN Global Pulse](https://www.unglobalpulse.org/) - Conflict forecasting pilots with ML.  
2. [ACLED Early Warning Research Hub](https://acleddata.com/early-warning-research-hub/)  
3. [WWIC’s Tech for Peace Initiative](https://www.wilsoncenter.org/)  
4. [Armed Conflict Prediction via AI at ETH Zurich](https://css.ethz.ch/)  
5. [DARPA KAIROS](https://www.darpa.mil/program/kairos)  
6. [AI for Peace at NeurIPS ML4Good](https://ml4good.github.io/)  
7. [GNN Unrest Forecaster by USC](https://github.com/socialsensor/GNN-unrest)

## Tutorials and Courses

1. [Stanford CS224W - Machine Learning with Graphs](https://web.stanford.edu/class/cs224w/)  
2. [Graph ML for Crisis Analysis - DeepMind YouTube](https://www.youtube.com/@DeepMind)  
3. [FastAI Course on Graphs](https://course.fast.ai/Lessons/graph.html)  
4. [Conflict Data Analysis with R (Uppsala)](https://ucdp.uu.se/tutorials)  
5. [DGL Official Tutorials](https://docs.dgl.ai/en/0.6.x/tutorials/index.html)  
6. [Pytorch Geometric Tutorials](https://pytorch-geometric.readthedocs.io/en/latest/notes/colabs.html)  
7. [GNNs for Social Forecasting (YouTube Playlist)](https://www.youtube.com/results?search_query=gnn+conflict+prediction)

## Books and Authoritative References

1. *Graph Representation Learning* by William L. Hamilton  
2. *Networks, Crowds, and Markets* by David Easley & Jon Kleinberg  
3. *Deep Learning on Graphs* by Yao Ma & Jiliang Tang  
4. *Understanding Civil War* by Paul Collier and Nicholas Sambanis  
5. *Machine Learning for Social and Behavioral Research* by A. Smaldino  
6. *Artificial Intelligence and Global Security* by J. Allen  
7. *Forecasting Political Events* by Bruce Bueno de Mesquita

## Communities and Conferences

1. [NeurIPS ML for Peace Workshop](https://ml4peace.github.io/)  
2. [ICWSM - Int’l Conf. on Web and Social Media](https://www.icwsm.org/)  
3. [Complexity & Conflict Network](https://conflictnetworks.org/)  
4. [PeaceTech Lab](https://www.peacetechlab.org/)  
5. [AAAI Symposium on AI for Social Good](https://aaai.org/conference/)  
6. [Data Science for Social Good](https://www.dssgfellowship.org/)  
7. [ML4D (Machine Learning for Development)](https://ml4d.github.io/)

## Conclusion and Future Directions

Predicting social conflict using Graph Neural Networks represents one of the most impactful frontiers in machine learning for social good. By modeling human interaction as evolving networks, we can generate early warnings, understand root causes, and drive informed policy. The future promises even greater potential with advances in:

- Dynamic heterogeneous graphs for longitudinal conflict prediction  
- Hybrid LLM + GNN architectures for multimodal data synthesis  
- Real-time GNN inference for global monitoring and early warning  
- Equity-driven AI systems for peacebuilding interventions

Let’s build systems that not only predict violence but help prevent it.

---

**Want to contribute?** Feel free to open an issue or submit a pull request! 🎯