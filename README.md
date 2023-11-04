# Parkinson's Disease Classification using Data Mining

## Project Overview

This project involves the application of multiple data mining techniques to classify Parkinson's disease from voice recordings. The dataset used consists of voice measurements from individuals diagnosed with Parkinson's disease and healthy controls.

## Dataset

The dataset for this project is sourced from the UCI Machine Learning Repository, specifically the Parkinson's Disease Classification dataset which can be accessed here: [Parkinson's Disease Classification Dataset](https://archive.ics.uci.edu/ml/datasets/Parkinson%27s+Disease+Classification).

### Dataset Description

The dataset includes numerous voice feature measurements from both Parkinson's disease patients and healthy individuals. Our script processes this data to prepare it for analysis by various classification algorithms.

## Getting Started

### Prerequisites

- Python 3.x
- Scikit-learn
- NumPy

Usage
The script parkinsons_classification.py implements the following classifiers:

K-Nearest Neighbors (KNN)
Random Forest
Multilayer Perceptron (MLP)
Support Vector Machine (SVM)
Gaussian Naive Bayes
AdaBoost
Voting Classifier
The data is first normalized, and PCA is applied to reduce dimensionality. The classification is performed using k-fold cross-validation to ensure the robustness of the results.



