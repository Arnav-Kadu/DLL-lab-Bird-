# Bird Species Classification

## Overview
This repository contains my work on creating and training machine learning models for the purpose of bird species classification. The goal is to accurately identify 20 different species of birds from images using deep learning techniques.

## Models
The project explores three different convolutional neural network (CNN) architectures:

1. **ResNet**: Leveraging the power of residual networks to train deeper models without the vanishing gradient problem.
2. **InceptionV3**: Utilizing the Inception model's complex architecture for handling image data more efficiently.
3. **Custom CNN**: Designing and training a CNN from scratch to serve as a baseline for comparison with the advanced architectures.

## Dataset
The dataset used for training and evaluating the models is the "[Birds 20 Species Image Classification](https://www.kaggle.com/datasets/umairshahpirzada/birds-20-species-image-classification)" available on Kaggle. It contains thousands of labeled images across 20 different bird species, providing a diverse set for robust training.

## Approach
Each of the three models is trained on the dataset after performing necessary preprocessing steps like resizing, normalization, and augmentation to make the training more effective. The models' performances are then compared based on their accuracy and loss metrics on a validation set.
