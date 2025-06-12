## Overview

This repository presents a comprehensive study on the application of machine learning methods to classify and cluster EEG signals associated with motor imagery tasks. Motor imagery, the mental rehearsal of movement without actual execution, is a key area of research for Brain-Computer Interfaces (BCIs).

## 🎯 Project Objectives
* Acquire and preprocess EEG data related to motor imagery.
* Apply advanced feature extraction methods to enhance signal quality.
* Evaluate and compare multiple machine learning algorithms for classification and clustering.
* Analyze and interpret the results using a variety of performance metrics.

## 💾 Dataset
The analysis is based on benchmark datasets provided by the **Berlin Brain-Computer Interface (BCI) group**.

## ⚙️ Preprocessing Pipeline
To ensure high-quality input for our machine learning models, the following preprocessing steps were implemented:
* **Bandpass Filtering:** Removes unwanted frequency components and noise.
* **Common Average Referencing (CAR):** Reduces artifacts by referencing each channel to the average signal.
* **Laplacian Filtering:** Enhances the spatial resolution of the EEG data.
* **Principal Component Analysis (PCA):** Reduces dimensionality and highlights key signal components.
* **Normalization:** Standardizes data for improved model performance.

## ✨ Feature Extraction Methods
The following algorithms were used to extract meaningful features from the preprocessed EEG signals:
* **Independent Component Analysis (ICA):** Separates mixed sources in the EEG data.
* **Common Spatial Patterns (CSP):** Maximizes the variance between different motor imagery classes.

## 🤖 Classification Algorithms
A range of machine learning classifiers were trained and evaluated for this task:
* **Logistic Regression**
* **Support Vector Machines (SVM)**
* **K-Nearest Neighbors (KNN)**
* **Multi-Layer Perceptron (MLP)**
* **AdaBoost**
* **XGBoost**

### Classification Evaluation Metrics
Model performance was assessed using:
* **Accuracy**
* **Confusion Matrix**
* **Receiver Operating Characteristic (ROC) Curve**


## 🧩 Clustering Approaches
For unsupervised analysis, the following clustering algorithms were applied:
* **DBSCAN**
* **K-Means**
* **Kernel K-Means**

### Clustering Evaluation Metrics
Clustering performance was evaluated using:
* **Silhouette Score**
* **Homogeneity Score**
