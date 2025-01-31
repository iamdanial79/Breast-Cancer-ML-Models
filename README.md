# Breast Cancer ML Models

## Overview  
This repository contains two machine learning models designed for breast cancer classification. The models implemented are:
- **AdaBoost Classifier**
- **Random Forest Classifier**

Both models are trained and evaluated using the Breast Cancer dataset, aiming to improve prediction accuracy and compare the performance of ensemble learning techniques.

## Dataset  
The dataset used in this project is the **Breast Cancer dataset**, commonly available in machine learning repositories such as the UCI Machine Learning Repository or `sklearn.datasets`.

## Models Implemented  

### 1. AdaBoost Classifier  
AdaBoost (Adaptive Boosting) is an ensemble learning method that combines multiple weak learners (usually decision trees) to form a strong classifier. The model iteratively adjusts the weights of misclassified samples to improve accuracy.

### 2. Random Forest Classifier  
Random Forest is another ensemble method that builds multiple decision trees and merges their outputs for more robust and accurate predictions. It helps in reducing overfitting and improves generalization.

## Project Files  
- `Ada Boost.ipynb`: Jupyter notebook implementing AdaBoost for breast cancer classification.  
- `random forest.ipynb`: Jupyter notebook implementing the Random Forest model.  

## Installation & Dependencies  
To run these notebooks, ensure you have the following dependencies installed:  

```bash
pip install numpy pandas scikit-learn matplotlib seaborn
