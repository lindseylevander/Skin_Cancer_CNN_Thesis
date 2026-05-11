# Skin Cancer Detection Using CNNs

## Project Overview

This project explores the use of deep learning and convolutional neural networks (CNNs) for automated skin cancer detection using dermoscopic imaging data from the ISIC 2024 dataset.

The objective of this research was to evaluate the effectiveness of ResNet50-based image classification models in detecting malignant skin lesions across different age groups while addressing challenges such as severe class imbalance and model interpretability.

This project was completed as part of a Master of Science in Data Science program with a specialization in AI Optimization and Machine Learning.

---

## Objectives

* Develop deep learning models for skin cancer classification
* Evaluate model performance across age-segmented populations
* Address class imbalance through image augmentation techniques
* Compare predictive performance using healthcare-focused evaluation metrics
* Improve model interpretability using explainable AI methods

---

## Dataset

Dataset Used:
ISIC 2024 Skin Cancer Dataset

Dataset Characteristics:

* Approximately 40,000 dermoscopic skin lesion images
* Binary classification:

  * Benign
  * Malignant
* Images segmented into two age groups:

  * 20–49
  * 50–79

---

## Languages and Tools

* Python
* TensorFlow / Keras
* ResNet50 CNN
* NumPy
* pandas
* matplotlib
* scikit-learn
* Google Colab
* Grad-CAM Explainability

---

## Methodology

### 1. Data Preprocessing

* Image resizing and normalization
* Dataset segmentation by age group
* Label preparation for binary classification

### 2. Class Imbalance Handling

The dataset contained significantly fewer malignant cases compared to benign cases.

To address imbalance:

* Image augmentation techniques were applied to malignant images
* Oversampling strategies improved training balance

### 3. Model Development

Implemented transfer learning using:

* ResNet50 convolutional neural network architecture

Training included:

* Feature extraction
* Fine-tuning
* Hyperparameter adjustment
* Validation monitoring

### 4. Model Evaluation

Performance was evaluated using:

* Accuracy
* Sensitivity
* Specificity
* AUC-ROC

### 5. Explainable AI

Grad-CAM visualization techniques were used to identify image regions influencing model predictions and improve interpretability.

---

## Results

Key findings included:

* Strong predictive performance across both age groups
* Improved classification performance after augmentation
* Grad-CAM visualizations highlighted clinically relevant image regions associated with malignant lesion detection

---

## Business and Healthcare Impact

This project demonstrates how deep learning and computer vision can support earlier skin cancer detection and assist healthcare professionals in identifying potentially malignant lesions more efficiently.

Potential applications include:

* Clinical decision support
* Early screening assistance
* Improved diagnostic workflows
* AI-assisted healthcare analytics

---

## Future Improvements

Potential future enhancements include:

* Multi-class lesion classification
* Ensemble deep learning architectures
* Expanded dataset balancing techniques
* Deployment as a clinical decision support application

---

## Author

Lindsey LeVander

MS Data Science – AI Optimization & Machine Learning

GitHub: https://github.com/lindseylevander
LinkedIn: https://www.linkedin.com/in/lindsey-levander-1b9874234/
