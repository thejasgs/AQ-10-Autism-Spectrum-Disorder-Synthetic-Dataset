# AQ-10-Autism-Spectrum-Disorder-Synthetic-Dataset

# Description
Contains synthetic dataset generated using
Gaussian Copula Synthesizer (GCS), Conditional Tabular GAN (CTGAN), and Tabular Variational Autoencoder (TVAE).

As published in "Modeling tabular data using conditional GAN"
By: Lei Xu, Maria Skoularidou, Alfredo Cuesta-Infante, Kalyan Veeramachaneni

Link: https://dl.acm.org/doi/10.5555/3454287.3454946

Preprocessed: Contained the processed version of the synthethic dataset
Preprocessing steps:
  1. Removing duplicates.
  2. Fixed the values of the "Class" column according to https://docs.autismresearchcentre.com/tests/AQ10.pdf
     by ensuring Class = 1 if and only if the sum of A1 - A10 columns are at least 6.


The original dataset is available in Kaggle: https://share.google/iLobyvRoQ8K5fu872

## Permission
Should you use this synthetic dataset, please cite our work

@INPROCEEDINGS{Sola2511:Synthetic,
AUTHOR="Nathanael P Solagratia and Thejas {G.S}",
TITLE="Synthetic Data Review Using Generative Adversarial Networks and Transformer
Models in {AQ-10} Autism Spectrum Disorder Dataset",
BOOKTITLE="2025 International Conference on Artificial Intelligence and Technological
Solutions (ICAITech) (ICAITech 2025)",
ADDRESS="virtual, Indonesia",
PAGES=6,
DAYS=18,
MONTH=nov,
YEAR=2025,
KEYWORDS="Deep learning; Synthetic dataset; ASD",
}
