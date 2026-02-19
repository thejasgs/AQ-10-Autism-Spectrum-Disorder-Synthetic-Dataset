#**Synthetic Data Review Using Generative Adversarial Networks and Transformer Models in AQ-10 Autism Spectrum Disorder Dataset**
# AQ-10-Autism-Spectrum-Disorder-Synthetic-Dataset

# Description
Contains synthetic dataset generated using
Gaussian Copula Synthesizer (GCS), Conditional Tabular GAN (CTGAN), and Tabular Variational Autoencoder (TVAE).


Preprocessed: Contained the processed version of the synthethic dataset
Preprocessing steps:
  1. Removing duplicates.
  2. "Adjust" the values of the "Class" column according to https://docs.autismresearchcentre.com/tests/AQ10.pdf
     by ensuring Class = 1 if and only if the sum of A1 - A10 columns are at least 6.


The original dataset is available in Kaggle: https://share.google/iLobyvRoQ8K5fu872

The Datasets directory contains 3 GAN generated datasets.
Datasets under Datasets/Preprocessed directory are the ones used in our study: DOI: 10.1109/ICAITech66481.2025.11387099.

Datasets are publicly available and if you do use them, please cite our work:

## Permission
@INPROCEEDINGS{11387099,
  author={Solagratia, Nathanael P. and Thejas, G.S.},
  booktitle={2025 International Conference on Artificial Intelligence and Technological Solutions (ICAITech)}, 
  title={Synthetic Data Review Using Generative Adversarial Networks and Transformer Models in AQ-10 Autism Spectrum Disorder Dataset}, 
  year={2025},
  volume={},
  number={},
  pages={7-13},
  keywords={Deep learning;Training;Autism;Accuracy;Computational modeling;Medical services;Transformers;Generative adversarial networks;Data models;Synthetic data;ASD;Deep Learning;Neural Network;Synthetic Dataset;Generative Adversarial Networks;Transformer},
  doi={10.1109/ICAITech66481.2025.11387099}}

  or

[1] N. P. Solagratia and G. S. Thejas, "Synthetic Data Review Using Generative Adversarial Networks and Transformer Models in AQ-10 Autism Spectrum Disorder Dataset," 2025 International Conference on Artificial Intelligence and Technological Solutions (ICAITech), Palembang, Indonesia, 2025, pp. 7-13, doi: 10.1109/ICAITech66481.2025.11387099.
  
keywords: {Deep learning;Training;Autism;Accuracy;Computational modeling;Medical services;Transformers;Generative adversarial networks;Data models;Synthetic data;ASD;Deep Learning;Neural Network;Synthetic Dataset;Generative Adversarial Networks;Transformer},

Abstract: Autism spectrum disorder (ASD) is a neurodevelopmental disorder which affects person’s social interaction. Recently, there has been a rise in ASD diagnosis observed among children. Previous research has relied on publicly available datasets that consist of screening questions. However, most of these datasets only provide a small sample of the population. This study explores advanced synthetic data generation techniques and their application in binary classification tasks in ASD dataset. This study also compares the traditional machine learning models such as Decision Tree, Logistic Regression, and others, along with deep learning models such as transformer model. Our findings reveal that Generative Adversarial Networks do not consistently produce high-fidelity replicas of real-world datasets, even with a relatively simple, binary dataset. This highlights the crucial need for human oversight and domain expertise to validate the quality and accuracy of synthetic data, especially for sensitive applications. The research demonstrates that traditional machine learning models perform comparably to the more complex and computationally expensive transformer models on this specific task. In our case, these results suggest that simpler, traditional approaches can be a more efficient and cost-effective solution for ASD classification problems, challenging the assumption that state-of-the-art models are always the superior choice.
keywords: {Deep learning;Training;Autism;Accuracy;Computational modeling;Medical services;Transformers;Generative adversarial networks;Data models;Synthetic data;ASD;Deep Learning;Neural Network;Synthetic Dataset;Generative Adversarial Networks;Transformer},
URL: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=11387099&isnumber=11387038


