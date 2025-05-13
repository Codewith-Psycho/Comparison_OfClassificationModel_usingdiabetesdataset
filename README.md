# Diabetes Classification Models

This repository contains a Python script for building, training, evaluating, and comparing multiple machine learning classification models to predict diabetes using the PIMA Indians Diabetes Dataset.

---

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Requirements](#requirements)
- [Usage](#usage)
- [Model Details](#model-details)
- [Output & Visualization](#output--visualization)
- [Customization](#customization)
- [License](#license)

---

## Overview

The script (`ClassificationModels.py.py`) demonstrates a full machine learning workflow for diabetes prediction. It covers data loading, exploratory analysis, preprocessing, model training, evaluation, and comparison of several popular classification algorithms.

The models implemented include:
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)
- Logistic Regression
- Random Forest
- XGBoost
- Naive Bayes
- Gradient Boosting

---

## Features

- Loads and analyzes the PIMA Diabetes dataset
- Visualizes dataset correlations and feature relationships
- Standardizes features for optimal model performance
- Splits data into training and testing subsets
- Trains and evaluates multiple classifiers
- Computes and displays key metrics: Accuracy, Precision, Recall, F1-Score, ROC AUC
- Plots ROC curves, confusion matrices, and model performance summaries
- Compares all models in a consolidated table

---

## Requirements

- Python 3.7+
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn
- xgboost

Install dependencies with:

