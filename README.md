# Alpaca vs Not Alpaca Image Classifier

## Overview
This project is a deep learning image classification system that detects whether an image contains an alpaca or not.

Multiple deep learning approaches were tested:
- Custom CNN model
- Transfer Learning (InceptionV3)
- Transfer Learning (MobileNetV2)

The best model achieved high accuracy using MobileNetV2.

## Features
- Binary image classification (Alpaca / Not Alpaca)
- Data balancing using RandomOverSampler
- Data augmentation using ImageDataGenerator
- Multiple CNN architectures tested
- Transfer learning with pretrained models
- Confusion matrix + classification report

## Models Used

### 1) Custom CNN
- Conv2D layers
- MaxPooling
- Dense layers
- Sigmoid output

### 2) InceptionV3 (Transfer Learning)
- Pretrained on ImageNet
- Fine-tuned for binary classification

### 3) MobileNetV2 (Best Model)
- Lightweight pretrained model
- High accuracy with fast training

## Dataset
- Source: Kaggle Alpaca Dataset
- Two classes:
  - alpaca
  - not alpaca

Data preprocessing included:
- Oversampling for class balance
- Train/Test/Validation split

## Tech Stack
- Python
- TensorFlow / Keras
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- imbalanced-learn
- KaggleHub
  
## Results

### MobileNetV2 (Best Model)
- Accuracy: ~95%
- Strong generalization on test set
  
##  Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

## Confusion Matrix Example
(Add your plotted confusion matrix image here)

## How to Run
### 1) Install dependencies
```bash
pip install -r requirements.txt

### 1) Install dependencies
```bash
pip install -r requirements.txt
