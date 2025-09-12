# AQ-10-Autism-Spectrum-Disorder-Synthetic-Dataset

# Description
Contains synthetic dataset generated using
Gaussian Copula Synthesizer (GCS), Conditional Tabular GAN (CTGAN), and Tabular Variational Autoencoder (TVAE)

As published in "Modeling tabular data using conditional GAN"
By: Lei Xu, Maria Skoularidou, Alfredo Cuesta-Infante, Kalyan Veeramachaneni

Preprocessed: Contained the processed version of the synthethic dataset
Preprocessing steps:
  1. Removing duplicates
  2. Fixed the values of the "Class" column according to https://docs.autismresearchcentre.com/tests/AQ10.pdf
     by ensuring Class = 1 if and only if the sum of A1 - A10 columns are at least 6


The original dataset is available in Kaggle: https://share.google/iLobyvRoQ8K5fu872
