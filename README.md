# Breast Cancer Prediction using Logistic Regression

This project implements a breast cancer prediction model using the **Logistic Regression** algorithm, based on the well-known **Breast Cancer dataset** from scikit-learn. The model classifies the cases into two categories: **Malignant** (0) and **Benign** (1).

## Table of Contents
1. [Introduction](#introduction)
2. [Libraries Used](#libraries-used)
3. [Dataset Overview](#dataset-overview)
4. [Data Exploration](#data-exploration)
5. [Model Training](#model-training)
6. [Model Evaluation](#model-evaluation)
7. [Feature Importance](#feature-importance)
8. [Predictive System](#predictive-system)
9. [Conclusion](#conclusion)

## Introduction

This project demonstrates how to train a machine learning model to predict breast cancer diagnoses using Logistic Regression. The dataset consists of various features describing cell nuclei, and the goal is to classify whether the cancer is malignant or benign based on these features.

## Libraries Used

- **NumPy**: For numerical operations
- **Pandas**: For data manipulation and analysis
- **scikit-learn**: For implementing Logistic Regression, cross-validation, and evaluation metrics
- **Matplotlib**: For data visualization
- **Seaborn**: For advanced visualizations, especially heatmaps

## Dataset Overview

The dataset used is the **Breast Cancer Wisconsin dataset**, which contains information about the characteristics of cell nuclei from breast cancer biopsies. The dataset has the following attributes:
- **Features**: 30 different numerical measurements about the cell nuclei.
- **Label**: Binary target variable indicating whether the tumor is benign (1) or malignant (0).

### Features:
- Mean radius
- Mean texture
- Mean perimeter
- Mean area
- And more...

### Target:
- 1: Benign
- 0: Malignant

## Data Exploration

The dataset is first loaded and basic exploratory analysis is performed:
- Distribution of benign vs malignant cases is visualized.
- A correlation matrix of features is plotted to understand the relationships between them.

## Model Training

- The data is split into training and testing sets (80% training, 20% testing).
- **Logistic Regression** is used to build the model.
- **Cross-validation** is performed to evaluate the model's generalizability.
  
## Model Evaluation

After training the model:
- The accuracy on both the training and testing datasets is calculated.
- A **Classification Report** is generated to assess performance metrics like precision, recall, and F1-score.
- A **Confusion Matrix** is displayed for further insights into model performance.

## Feature Importance

The importance of each feature is calculated using the model's coefficients. The top 10 most important features are visualized to understand what drives the classification decision.

## Predictive System

A simple predictive system is built where new data points (like the measurements of a biopsy) can be input, and the model will predict whether the tumor is malignant or benign.

## Conclusion

This project demonstrates a practical application of **Logistic Regression** for breast cancer classification. By evaluating different aspects of model performance and feature importance, we gain insights into both the data and the model's decision-making process.

The model shows good accuracy and can be further tuned or extended to use more advanced machine learning algorithms.

---

### Future Work:
- Explore other classification models (e.g., Random Forest, SVM).


