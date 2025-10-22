# BreastCancerClassificationLR
# Breast Cancer Classification using Logistic Regression

A **machine learning project** to classify breast cancer as malignant or benign using **Logistic Regression**.

## Overview

This project demonstrates a classic **supervised learning workflow** with the **Breast Cancer dataset** from `sklearn`. The goal is to predict the type of tumor based on its features.

## Features

- Load and explore the **Breast Cancer dataset** using pandas  
- Scale features using **StandardScaler**  
- Split data into training and testing sets  
- Train a **Logistic Regression** model with **GridSearchCV** for hyperparameter tuning  
- Evaluate model performance with **accuracy, precision, recall, and F1-score**  

## Results

- Best hyperparameters found: `{'C': 3}`  
- Best F1 Score from GridSearchCV: `0.983`  
- Test Accuracy: `97.37%`  
- High precision and recall for both malignant and benign classes  

## Usage

1. Clone the repository:  
   ```bash
   git clone <repo-url>
