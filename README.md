# Bird Species Classification

## Overview
This repository contains my work on creating and training machine learning models for the purpose of bird species classification. The goal is to accurately identify 20 different species of birds from images using deep learning techniques.

## Models
The project explores three different convolutional neural network (CNN) architectures, evaluating their performance in accurately classifying images of 20 different bird species. Here's a summary of their performance based on accuracy metrics obtained from the validation set:

1. **Custom CNN**: A CNN model designed and trained from scratch. This model serves as a baseline for comparison with more advanced architectures. It achieved an accuracy of **91.70%** on the validation set, demonstrating the effectiveness of even simple architectures for image classification tasks.

2. **ResNet**: Utilizing the power of residual networks, this model leverages deep learning to avoid the vanishing gradient problem commonly encountered in very deep networks. The ResNet model outperformed the baseline CNN, achieving an impressive accuracy of **95.92%** on the validation set.

3. **InceptionV3 (Inv3)**: The Inception model is known for its complex architecture that handles image data efficiently through a series of convolutional operations. However, in this project, the InceptionV3 model showed signs of overfitting with a lower accuracy of **100.0%** on the validation set. This indicates that the model might have learned to memorize the training data rather than generalize from it.

## Dataset
The dataset used for training and evaluating the models is the "[Birds 20 Species Image Classification](https://www.kaggle.com/datasets/umairshahpirzada/birds-20-species-image-classification)" available on Kaggle. It contains thousands of labeled images across 20 different bird species, providing a diverse set for robust training.

## Approach
Each of the three models underwent a series of preprocessing steps such as resizing, normalization, and augmentation to ensure effective training. The performances of the models were compared based on their accuracy and loss metrics on the validation set. The results highlight the importance of model selection and tuning in achieving high accuracy in image classification tasks, with the ResNet model showing the best performance among the architectures tested.
