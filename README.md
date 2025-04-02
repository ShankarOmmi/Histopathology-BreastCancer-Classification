# Histopathology-BreastCancer-Classification
# Breast Tumor Classification using Histopathology Images

## Overview
This project focuses on the classification of breast tumors based on histopathology images. The goal is to distinguish between different tumor types using deep learning techniques, particularly CNNs, ViTs, and Few-Shot Learning models. The dataset used for this study is the **BACH (Breast Cancer Histology) dataset**. This project also evaluates the effectiveness of different loss functions in improving classification performance.

## Dataset
- **Name**: BACH (Breast Cancer Histology)
- **Source**: [BACH Dataset](https://www.kaggle.com/datasets/truthisneverlinear/bach-breast-cancer-histology-images)
- **Classes**:
  - Normal
  - Benign
  - In Situ Carcinoma
  - Invasive Carcinoma

## Methodology
### 1. **Preprocessing**
   - Resizing images to be compatible with ResNet architecture.
   - Data Augmentation techniques such as flipping, rotation, and cropping to improve generalization.

### 2. **Model Selection**
   - Convolutional Neural Networks (CNNs): ResNet50 was chosen due to its strong feature extraction capabilities.
   
### 3. **Loss Functions Used**
   - **Cross Entropy Loss**: Standard loss function for classification tasks.
   - **Weighted Cross Entropy Loss**: Applied to handle class imbalance in the dataset.

### 4. **Training & Evaluation**
   - Performance Metrics: Accuracy, Precision, Recall, F1-Score.
   - Comparative analysis of different loss functions to determine their impact on model performance.

## Results
- **Best Performing Model:** ResNet50 with Cross Entropy Loss
- **Accuracy:** 88%
- **Findings:** The standard Cross Entropy Loss provided better generalization compared to Weighted Cross Entropy for this dataset.



## Future Work
- Implementation of self-supervised learning for better feature extraction.
- Experimenting with different loss functions and ensemble learning to improve performance.
- Incorporating Few-Shot Learning models to enhance classification with limited data.
- Extending the study to other histopathology datasets for broader applicability.

## Contributors
- **[Shankar Ommi](https://github.com/ShankarOmmi)**

## License
This project is licensed under the **Apache License 2.0** - see the [LICENSE](LICENSE) file for details.

