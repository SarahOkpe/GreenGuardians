# GreenGuardians

Plant disease detection using multiple machine learning models and feature extraction.

## Overview
Green Guardians is a machine learning-based project aimed at identifying plant diseases through image analysis. The project leverages multiple classification algorithms, including SVM, Random Forest, k-NN, Logistic Regression, and XGBoost, along with extracted visual features such as color, texture, and shape from leaf images to enhance detection accuracy and efficiency.

## Features
1. **Automated Detection**:
   - Upload an image of a plant leaf (healthy or diseased).
   - Detect plant diseases using trained machine learning models.
2. **Comprehensive Model Comparison**:
   - Evaluated multiple models with cross-validation for robust results.
3. **Results Visualization**:
   - Confusion matrices and classification reports provided for each model.
4. **Best Model**:
   - XGBoost achieved the highest accuracy of 96%.

## Results
- **Accuracy Summary**:
  - SVM: 94%
  - Random Forest: 95%
  - k-NN: 93%
  - Logistic Regression: 90%
  - XGBoost: 96%
- **Conclusion**:
  XGBoost outperformed all models with the highest accuracy and consistent results across multiple data splits.

## Future Work
- Expand the dataset for broader generalization.
- Explore deep learning models (e.g., CNNs) for automated feature extraction.
- Develop a mobile or web application for real-time use.
