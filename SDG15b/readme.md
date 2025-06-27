# 🦜 Awesome Acoustic Biodiversity Assessment with VAE

*A curated knowledge resource on using Variational Autoencoders for ecoacoustic monitoring and biodiversity assessment.*

---

## Table of Contents

- [Introduction](#introduction)
- [Surveys and Review Papers](#surveys-and-review-papers)
- [Key Scientific Papers](#key-scientific-papers)
- [Papers with Code](#papers-with-code)
- [Datasets and Benchmarks](#datasets-and-benchmarks)
- [Open Source Tools and Libraries](#open-source-tools-and-libraries)
- [Use Cases and Applications](#use-cases-and-applications)
- [Tutorials and Courses](#tutorials-and-courses)
- [Books and Authoritative References](#books-and-authoritative-references)
- [Communities and Conferences](#communities-and-conferences)
- [Conclusion and Future Directions](#conclusion-and-future-directions)

---

## Introduction

Biodiversity is increasingly threatened by climate change, habitat loss, and human activity. Acoustic monitoring offers a scalable, non-invasive way to assess ecological health by capturing the rich soundscapes of natural environments. Variational Autoencoders (VAEs) provide a powerful, unsupervised framework to extract latent structure from large-scale ecoacoustic data. This guide aggregates the most relevant resources—papers, datasets, tools, and communities—at the intersection of bioacoustics and generative machine learning.

---

## Surveys and Review Papers

1. Towsey, M., Zhang, L., Cottman-Fields, M., et al. (2014). *Visualization of Long-duration Acoustic Recordings of the Environment.* https://doi.org/10.1007/s13735-014-0056-7
2. Gibb, R., Browning, E., Glover-Kapfer, P., & Jones, K. E. (2019). *Emerging opportunities and challenges for passive acoustics in ecological assessment and monitoring.* Methods in Ecology and Evolution. https://doi.org/10.1111/2041-210X.13281
3. Stowell, D., & Wood, M. (2018). *Automatic acoustic identification of birds: A review.* Journal of the Royal Society Interface. https://doi.org/10.1098/rsif.2018.0032
4. Lerch, A. (2021). *Deep Learning for Audio: A Review.* https://arxiv.org/abs/2107.03974
5. Kahl, S., et al. (2021). *BirdNET: A deep learning solution for avian diversity monitoring.* Ecological Informatics. https://doi.org/10.1016/j.ecoinf.2021.101236

---

## Key Scientific Papers

### Foundational Works

1. Hershey, S., Chaudhuri, S., Ellis, D. P., et al. (2017). *CNN architectures for large-scale audio classification.* https://arxiv.org/abs/1609.09430
2. Kong, Q., Cao, Y., Iqbal, T., Wang, Y., Wang, W., & Plumbley, M. D. (2020). *PANNs: Large-Scale Pretrained Audio Neural Networks for Audio Pattern Recognition.* https://arxiv.org/abs/1912.10211
3. Stowell, D., Wood, M., & Stylianou, Y. (2019). *Automatic acoustic monitoring of biodiversity using unsupervised learning.* https://arxiv.org/abs/1904.03895
4. Lostanlen, V., et al. (2019). *Per-channel energy normalization: Why and how.* https://arxiv.org/abs/1911.07034
5. Cohen, Y., et al. (2022). *An unsupervised method for ecoacoustic monitoring with VAE-based clustering.* (via Scispace)

<details>
<summary>Additional Related Papers</summary>

- Piczak, K. J. (2015). *ESC: Dataset for Environmental Sound Classification.* https://doi.org/10.1145/2733373.2806390  
- Salamon, J., Bello, J. P. (2017). *Deep convolutional neural networks and data augmentation for environmental sound classification.* https://arxiv.org/abs/1608.04363  
- Lostanlen, V., et al. (2020). *Learning latent representations of soundscapes with VAE.* (Find on ResearchRabbit)  
- Eliezer, N., et al. (2022). *Latent acoustic features for habitat monitoring.* (via Scispace)

</details>

---

## Papers with Code

1. [Unsupervised Bioacoustic Embeddings via VAE](https://paperswithcode.com/paper/unsupervised-representation-learning-of-1)
2. [BirdCLEF Species Classification Challenge](https://paperswithcode.com/sota/audio-classification-on-birdclef-2021)
3. [SoundNet](https://github.com/cvondrick/soundnet)
4. [Autoencoders for Bird Sound Separation](https://paperswithcode.com/paper/unsupervised-feature-learning-for-bird)
5. [Ecoacoustic VAE Audio Anomaly Detection](https://github.com/jmichaelross/ecoacoustic-vae)

---

## Datasets and Benchmarks

1. **Rainforest Connection (RFCx)**: [rfcx.org](https://www.rfcx.org/)
2. **BirdCLEF**: [https://www.kaggle.com/competitions/birdclef-2023](https://www.kaggle.com/competitions/birdclef-2023)
3. **QUT Ecoacoustics**: [https://research.qut.edu.au/ecoacoustics/](https://research.qut.edu.au/ecoacoustics/)
4. **UrbanSound8K**: [https://urbansounddataset.weebly.com/urbansound8k.html](https://urbansounddataset.weebly.com/urbansound8k.html)
5. **SONYC Urban Sound Monitoring**: [https://zenodo.org/record/3675233](https://zenodo.org/record/3675233)
6. **Arbimon Platform**: [https://www.arbimon.org](https://www.arbimon.org)

---

## Open Source Tools and Libraries

- [Librosa](https://librosa.org/)
- [OpenSoundscape](https://github.com/kitzeslab/opensoundscape)
- [scikit-maad](https://github.com/scikit-maad/scikit-maad)
- [PANNs](https://github.com/qiuqiangkong/audioset_tagging_cnn)
- [PyTorch-VAE](https://github.com/AntixK/PyTorch-VAE)

---

## Use Cases and Applications

- 🌍 [Nature Sound Map](https://www.naturesoundmap.com/)
- 🐦 [Arbimon Monitoring Platform](https://www.arbimon.org/)
- 🐘 [WWF Bioacoustic Monitoring](https://www.wwf.org/)
- 🐾 [Rainforest Connection Projects](https://www.rfcx.org/)
- 🔊 [Soundscapes to Landscapes (S2L)](https://soundscapestolandscapes.org/)

---

## Tutorials and Courses

<details>
<summary>Expand to view list</summary>

1. [VAE for Audio in PyTorch – GitHub](https://github.com/haofuml/cvpr2021-vae-audio)
2. [Colab: Intro to VAE with Audio](https://colab.research.google.com/github/tensorflow/probability/blob/main/tensorflow_probability/examples/jupyter_notebooks/VAE_in_TFP.ipynb)
3. [Coursera: Audio Signal Processing for ML](https://www.coursera.org/learn/audio-signal-processing)
4. [Medium: Deep Learning for Environmental Sounds](https://towardsdatascience.com/audio-deep-learning-made-simple-automatic-speech-recognition-asr-an-overview-bf72030dcbf4)
5. [VAE Concepts Explained – Towards Data Science](https://towardsdatascience.com/intuitively-understanding-variational-autoencoders-1bfe67eb5daf)

</details>

---

## Books and Authoritative References

- *Ecoacoustics: The Ecological Role of Sounds* – Farina & Gage (Springer)
- *Deep Learning for the Life Sciences* – O’Reilly
- *Bioacoustics: A Comparative Approach* – Lewis (Academic Press)
- *Pattern Recognition and Machine Learning* – Bishop
- *Hands-On Generative Deep Learning* – David Foster (O’Reilly)

---

## Communities and Conferences

- [ML4Wildlife](https://ml4wildlife.org/)
- [Acoustic Society of America](https://acousticalsociety.org/)
- [ISMSM Bioacoustics Working Group](https://www.ismsm.org/)
- [IEEE ICASSP](https://2024.ieeeicassp.org/)
- [CEC Conference (EAA)](https://cecconference.org/)

---

## Conclusion and Future Directions

Acoustic biodiversity assessment is not only a technological challenge, but a mission-critical frontier in preserving global ecosystems. VAEs offer a scalable, unsupervised toolset for mapping complex acoustic environments into interpretable, generative latent spaces. Looking ahead, future research will likely explore:

- 🎯 Self-supervised acoustic embeddings using contrastive learning
- 🤖 Hybrid generative architectures (e.g., VAE-GANs)
- 🌎 Transferable ecoacoustic models across biomes
- ⏱ Real-time monitoring and edge deployment
- 🧬 Integrating acoustic and non-acoustic sensor modalities

Get involved, contribute to open datasets, and help shape the future of sound-driven biodiversity science.

---
