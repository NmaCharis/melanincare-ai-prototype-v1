# MelaninCare AI Prototype v1

AI skin-image classification prototype exploring fairness and representation challenges in dermatology datasets.

## Overview
This project demonstrates a simple AI model for skin image classification using transfer learning (MobileNetV2).

## Tools Used
- Python
- TensorFlow / Keras
- Google Colab
- HAM10000 dataset

## Model
- MobileNetV2 (pretrained)
- Global Average Pooling
- Dense layers + Dropout
- Softmax output

## Results
- Validation Accuracy: ~44%
- Model shows learning capability but is limited by dataset imbalance

## Key Insight
The dataset lacks sufficient diversity, which affects performance and highlights fairness challenges in dermatology AI systems.

## Important Note
This is an educational prototype and not a medical diagnostic tool.

## Visual Results

### Training Performance
![Training Accuracy](training_accuracy.png)

### Validation Result
![Validation Result](validation_result.png)

### Model Architecture
![Model Architecture](model_architecture.png)
