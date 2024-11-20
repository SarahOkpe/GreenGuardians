# GreenGuardians

Plant disease detection using Support Vector Machines (SVM) and feature extraction.

## Overview
Green Guardians is a machine learning-based project aimed at identifying plant diseases through image analysis. The project leverages SVM for classification and extracts key visual features such as color, texture, and shape from leaf images to enhance detection accuracy and efficiency.

## Features
1. **Automated Detection**:
   - Upload an image of a plant leaf (healthy or diseased).
   - Automated feature extraction and classification.
2. **Feature Extraction**:
   - **Color**: Mean RGB values.
   - **Texture**: Gray Level Co-occurrence Matrix (GLCM).
   - **Shape**: Geometric properties like area and perimeter.
3. **Performance Metrics**:
   - **Accuracy**: 81% on test data.
   - Class-level precision, recall, and F1-score included in the analysis.

## Dataset
- **Source**: [PlantVillage Dataset on Kaggle](https://www.kaggle.com/datasets/emmarex/plantdisease)
- This dataset contains approximately 87,000 RGB images of healthy and diseased plant leaves.
- Sample classes:
  - `Pepper__bell___healthy`
  - `Tomato_Early_blight`
  - `Tomato_Septoria_leaf_spot`
- The dataset includes various crops, such as apple, tomato, rice, and potato, making it diverse and robust for training the model.

## Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/SarahOkpe/GreenGuardians.git
