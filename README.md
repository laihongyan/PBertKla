# PBertKla: a protein large language model for predicting human lysine lactylation sites

Lactylation is a newly discovered type of post-translational modification, primarily occurring on lysine (K) residues of both histones and non-histones to exert diverse effects on target proteins. Here, we proposed a novel human Kla site predictor (named PBertKla) through curating a reliable benchmark dataset with proper sample length and sequence identity threshold to train a protein large language model with optimal hyperparameters. Extensive experimental results consistently demonstrated that our model possessed robust human Kla site prediction ability, achieving an AUC (area under receiver operating characteristic curve) value of over 0.880 on the independent validation data. Feature visualization analysis further validated the effectiveness of in feature learning and representation from Kla sequences. Moreover, we benchmarked PBertKla against other cutting-edge models on an independent testing dataset from different sources, highlighting its superiority and transferability.


# Usage:
Installation has been tested in Ubuntu 22.04 system with Python 3.7, and its working time was about 25 mins.

PBertKla uses the following dependencies:

tensorflow (2.4.0)

tensorflow_addons (0.12.1)

numpy (1.20.1)

pandas (1.2.3)

h5py (3.2.1)

lxml (4.3.2)

pyfaidx (0.5.8)

PBertKla is developed based on the ProteinBERT (https://github.com/nadavbra/protein_bert).
