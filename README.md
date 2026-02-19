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

