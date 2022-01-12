# MALT90-Clumps-Classification-Deep-Learning

## Classification of Molecular Clumps and Uncertain Clumps Assignment


### 1. Dataset
We use the MALT90 Dataset (Rathborne et al., 2016), downloaded from [Swinburne HPC data portal](https://data-portal.hpc.swin.edu.au/dataset/the-malt90-line-catalog/resource/f97a614b-7163-4b0a-93cc-c827b5128f50?inner_span=True)

### 2. Data Cleaning
We use the Gim images, assigned into classes for model training, and preprocessed by eliminating the border and split into train, validation, and test dataset. 

### 3. Data Augmentation
We use albumentation for training data augmentation

### 4. Training
Keras is used to train deep learning model
