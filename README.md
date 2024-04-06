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

## Usage
The repository is structured as follows:

- `models/`: Contains the saved models and their weights.
- `notebooks/`: Jupyter notebooks with the entire workflow from data preprocessing to model training and evaluation.
- `scripts/`: Helper scripts for data preparation, training, and evaluation.
- `requirements.txt`: A list of Python dependencies required to run the code.

To replicate the results or to train the models on new data, clone the repository, install the dependencies from `requirements.txt`, and run the notebooks.

## Results
The results section will provide a detailed comparison of each model's performance. This includes training and validation accuracy, loss curves, and confusion matrices to understand where the models succeed and where they can be improved.

## Acknowledgments
Credit goes to [Umair Shah](https://www.kaggle.com/umairshahpirzada) for providing the dataset that made this project possible.

## Contact
For any queries regarding the models or the project, feel free to connect with me on [Kaggle](<Your-Kaggle-Profile-URL>) or [LinkedIn](<Your-LinkedIn-Profile-URL>).

---

I am constantly working on improving the models and exploring new techniques. Suggestions and contributions are welcome!

