# Awesome Climate Agreement Negotiation with MARL 🌍🤖

> A curated list of resources at the intersection of climate agreement negotiation and Multi-Agent Reinforcement Learning (MARL).

Inspired by the [Awesome List Manifesto](https://github.com/sindresorhus/awesome/blob/main/awesome.md)

## Table of Contents
- [Introduction](#introduction)
- [Surveys & Reviews](#surveys--reviews)
- [Core Scientific Papers](#core-scientific-papers)
- [Papers with Code & Repositories](#papers-with-code--repositories)
- [Benchmarks, Datasets & Simulated Environments](#benchmarks-datasets--simulated-environments)
- [Libraries & Toolkits](#libraries--toolkits)
- [Use Cases & Applications](#use-cases--applications)
- [Tutorials & Courses](#tutorials--courses)
- [Books & Authoritative Texts](#books--authoritative-texts)
- [Communities, Conferences & Workshops](#communities-conferences--workshops)
- [Conclusion & Research Outlook](#conclusion--research-outlook)

---

## Introduction
Climate negotiations are complex multi-party interactions involving diverse national interests, long-term incentives, and uncertain outcomes. These interactions can be modeled as **multi-agent systems**, where agents learn cooperative strategies under various constraints. **Multi-Agent Reinforcement Learning (MARL)** offers powerful tools to simulate, analyze, and optimize such negotiations. From public goods games to global emission treaties, MARL helps model incentive structures, dynamic agreements, and emergent cooperation.

Key challenges MARL can help address:
- Incentive misalignment between sovereign actors
- Sustained long-term cooperation
- Agent heterogeneity in goals and capacities
- Partial observability and negotiation uncertainty

---

## Surveys & Reviews
1. **A Survey of Multi-Agent Reinforcement Learning** – [DOI:10.48550/arXiv.1810.05587](https://arxiv.org/abs/1810.05587)
2. **Learning in Multi-Agent Systems: A Survey from a Game-Theoretic Perspective** – [DOI:10.1016/S0004-3702(01)00052-5](https://doi.org/10.1016/S0004-3702(01)00052-5)
3. **Review of International Climate Agreements** – [DOI:10.1146/annurev-resource-110813-114509](https://doi.org/10.1146/annurev-resource-110813-114509)
4. **Reinforcement Learning for Social Dilemmas** – [DOI:10.1016/j.artint.2021.103516](https://doi.org/10.1016/j.artint.2021.103516)
5. **Agent-Based Modeling and Climate Negotiations** – [DOI:10.1016/j.gloenvcha.2016.02.009](https://doi.org/10.1016/j.gloenvcha.2016.02.009)
6. **AI for Climate Change: A Literature Review** – [DOI:10.48550/arXiv.2212.09372](https://arxiv.org/abs/2212.09372)

---

## Core Scientific Papers
### Foundational Papers
1. Leibo et al., 2017. **Multi-agent reinforcement learning in sequential social dilemmas.** – [DOI:10.1038/s41598-017-17236-4](https://doi.org/10.1038/s41598-017-17236-4)
2. Hughes et al., 2018. **Inequity aversion improves cooperation in intertemporal social dilemmas.** – [DOI:10.1038/s41586-018-0092-6](https://doi.org/10.1038/s41586-018-0092-6)
3. Wang et al., 2022. **Emergent conventions in multi-agent RL for climate treaty simulation.** – [DOI:10.48550/arXiv.2205.14176](https://arxiv.org/abs/2205.14176)
4. Dragan et al., 2020. **Towards Negotiation-aware MARL for Treaties** – [Conference Paper, AAAI](https://ojs.aaai.org/index.php/AAAI/article/view/5414)
5. Barrett, S. (2003). **Environment and Statecraft: The Strategy of Environmental Treaty-Making.** Oxford University Press. – ISBN: 9780199257332

### Related / Follow-Up Papers
6. Nguyen et al., 2020. **Multi-agent deep RL with curriculum learning for climate scenarios** – [DOI:10.48550/arXiv.2005.01900](https://arxiv.org/abs/2005.01900)
7. Chakraborty et al., 2021. **MARL for Public Goods under Uncertainty** – [DOI:10.1145/3442188.3445921](https://doi.org/10.1145/3442188.3445921)
8. Mnih et al., 2016. **Asynchronous Methods for Deep Reinforcement Learning** – [DOI:10.48550/arXiv.1602.01783](https://arxiv.org/abs/1602.01783)
9. Baker et al., 2020. **Emergent Tool Use in MARL** – [DOI:10.1038/s41586-019-1724-z](https://doi.org/10.1038/s41586-019-1724-z)
10. Liang et al., 2021. **On the Generalization of MARL** – [DOI:10.48550/arXiv.2107.12356](https://arxiv.org/abs/2107.12356)

---

## Papers with Code & Repositories
- [Papers with Code: Public Goods Game](https://paperswithcode.com/task/public-goods-game)
- [OpenMARL](https://github.com/OpenMARL/OpenMARL) – Scalable MARL framework with negotiation environments
- [MAgent](https://github.com/geek-ai/MAgent) – Many-agent environment platform for MARL
- [OpenAI CleanUp Environment](https://github.com/openai/multi-agent-emergence-environments)
- [Diplomacy MARL Project](https://github.com/facebookresearch/DiplomacyResearch)
- [Social Dilemma MARL Sim](https://github.com/eugenevinitsky/sequential_social_dilemma_games)

---

## Benchmarks, Datasets & Simulated Environments
- [SSD Environments – Sequential Social Dilemma](https://github.com/eugenevinitsky/sequential_social_dilemma_games)
- [AI Economist: Climate Tax Models](https://github.com/salesforce/ai-economist)
- [RDDL Benchmarks for Sustainability](https://github.com/AI-Planning/rddl-competition)
- [NetLogo Climate Game Models](https://ccl.northwestern.edu/netlogo/models/community/)
- [Commons Game Dataset – Behavioral Climate Simulation](https://osf.io/f9hmb/)

---

## Libraries & Toolkits
- [PettingZoo](https://www.pettingzoo.ml/) – Standard API for multi-agent environments
- [Ray RLlib](https://docs.ray.io/en/latest/rllib/index.html) – High-performance RL at scale
- [MELTINGPOT](https://github.com/deepmind/meltingpot) – Social dilemma testing suite
- [OpenSpiel](https://github.com/deepmind/open_spiel) – Learning in games
- [Gymnasium MARL Environments](https://github.com/Farama-Foundation/Gymnasium)
- [PyMARL](https://github.com/oxwhirl/pymarl) – Decentralized MARL baselines

---

## Use Cases & Applications
- [AI Economist for Sustainability](https://www.salesforceairesearch.com/research/ai-economist/) – Economic modeling with RL
- [AI4Climate Toolkit](https://www.climatechange.ai/projects) – Case studies for climate-focused AI
- [World Climate Simulation](https://www.climateinteractive.org/tools/world-climate-simulation/) – Role-play game on negotiations
- [MARL-based Emission Trading](https://dl.acm.org/doi/10.1145/3442188.3445921)
- [UNFCCC Climate Model Integration](https://unfccc.int/topics/science/workstreams/cooperation-with-the-ipcc/unfccc-and-ipcc-cooperation)

---

## Tutorials & Courses
- [DeepMind MARL Lecture Series](https://deepmind.com/learning-resources)
- [Multi-Agent RL by SpinningUp](https://spinningup.openai.com/en/latest/)
- [Coursera: AI for Climate Change](https://www.coursera.org/learn/ai-for-climate-change)
- [Hugging Face MARL Tutorials](https://huggingface.co/blog/deep-rl-marl)
- [YouTube: Public Goods & MARL](https://www.youtube.com/watch?v=EjsWtm3F5Ng)
- [Stanford CS 234: Reinforcement Learning](http://web.stanford.edu/class/cs234/)

---

## Books & Authoritative Texts
- Sutton & Barto – **Reinforcement Learning: An Introduction** – [Book Link](http://incompleteideas.net/book/the-book.html)
- Shoham & Leyton-Brown – **Multiagent Systems** – [Cambridge Press](https://www.cambridge.org/highereducation/books/multiagent-systems/579A6E498F92427C5573EFB6B4F1DA91)
- Ostrom, E. – **Governing the Commons** – ISBN: 9780521405997
- Barrett, S. – **Environment and Statecraft** – ISBN: 9780199257332
- Russell & Norvig – **Artificial Intelligence: A Modern Approach**

---

## Communities, Conferences & Workshops
- [NeurIPS MARL Workshop](https://marl-workshop.github.io/)
- [ICML Climate Change Workshop](https://www.climatechange.ai/events/icml2023)
- [AAAI & AAMAS MARL Tracks](https://aamas2025.conference.academy/)
- [ACM EAAMO – Equity and Access in Algorithms](https://eaamo.org/)
- [Earth System Governance Conference](https://www.earthsystemgovernance.org/)
- [ClimateChange.AI Community](https://www.climatechange.ai/)

---

## Conclusion & Research Outlook
MARL holds transformative promise for modeling, understanding, and improving global climate agreement dynamics. Through simulations of complex, strategic interaction among diverse agents, researchers and policymakers can explore new paradigms for equitable and efficient treaty formation.

### Promising Frontiers:
- Dynamic norm emergence in agent societies
- Human-AI collaborative treaty simulators
- Scalable cooperative MARL under partial observability
- Transparent and ethical AI governance for international cooperation

> Let’s build systems where agents not only learn to cooperate—but learn to do so for the benefit of our shared future. 🌍

---

**Contributions Welcome!** Pull requests and suggestions are encouraged. Please ensure all links are working and resources are verifiable.
