# Skin Cancer Classification Using CNN

A deep learning project for classifying skin lesion images into two categories: benign and malignant.

## Overview

This project uses a Convolutional Neural Network (CNN) built with PyTorch to classify skin lesion images.

The model learns visual patterns from the images and predicts whether a lesion belongs to the benign or malignant class.

This project was developed for educational and research purposes.

## Dataset

The dataset contains two image classes:

- Benign
- Malignant

The images were processed and prepared for training, validation, and testing.

## Technologies Used

- Python
- PyTorch
- Torchvision
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Pillow
- OpenCV

## Model Architecture

The CNN architecture includes:

- Convolutional layers
- ReLU activation functions
- Max Pooling layers
- Fully Connected layers
- Dropout for reducing overfitting

## Evaluation Metrics

The model was evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

## Results

The model achieved an accuracy of 93.75% on the test dataset.

| Class | Precision | Recall | F1-Score |
|-------|-----------|--------|----------|
| Benign | 95% | 94% | 94% |
| Malignant | 93% | 93% | 93% |

The results show relatively balanced performance between the two classes.

## Project Structure

```text
skin-cancer-classification/
│
├── skin-cancer-classification.ipynb
├── README.md
├── requirements.txt
└── dataset/
    ├── benign/
    └── malignant/
