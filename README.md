# Histopathology-BreastCancer-Classification
# Breast Tumor Classification using Histopathology Images

## Overview
This project focuses on the classification of breast tumors based on histopathology images. The goal is to distinguish between different tumor types using deep learning techniques, particularly CNNs, ViTs, and Few-Shot Learning models. The dataset used for this study is the **BACH (Breast Cancer Histology) dataset**.

## Dataset
- **Name**: BACH (Breast Cancer Histology)
- **Source**: [BACH Dataset](https://www.kaggle.com/datasets/truthisneverlinear/bach-breast-cancer-histology-images)
- **Classes**:
  - Normal
  - Benign
  - In Situ Carcinoma
  - Invasive Carcinoma

## Methodology
1. **Preprocessing**
   - Stain Normalization
   - Data Augmentation (Flipping, Rotation, Cropping)
2. **Model Selection**
   - CNN Architectures (ResNet)
3. **Loss functions used**
   - Cross Entropy
   - Weighted Cross Entropy 
4. **Training & Evaluation**
   - Performance Metrics: Accuracy, Precision, Recall, F1-Score
   - Comparison of two loss functions

## Results
- **Best Performing Model:** ResNet50 with CrossEntropy Loss
- **Accuracy:** 88 %

## Future Work
- Implementation of self-supervised learning for better feature extraction
- Experimenting with different loss functions and ensembling learning
- Implementing of Few-Shot Learning models

## Contributors
- Your Name @ShankarOmmi

## License
This project is licensed under the Apache License 2.0 - see the LICENSE file for details.

