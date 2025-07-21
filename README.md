# Deep-Learning-Model-for-Roundabout-Safety-Perception-Prediction
# 🧠 TabTransformer Model - 1000 Epochs

This repository contains the implementation of a deep learning model using the **TabTransformer architecture** to predict outcomes from tabular data — trained for a full **1000 epochs** for robust performance and detailed learning analysis.

## 📌 Overview

Traditional models like XGBoost and Random Forest are strong contenders for tabular data, but what happens when transformers meet tables?  
This project explores that very idea using **TabTransformer**, a novel DL architecture that applies the attention mechanism to categorical embeddings for enhanced feature interactions.

> 🚀 **Use Case**: Predicting user safety perceptions at roundabouts based on socio-demographic and behavioral data collected through questionnaires.

## 🛠 Features

- ⚙️ **TabTransformer** deep learning architecture
- 📊 Clean and preprocessed tabular dataset (categorical + continuous)
- 🔁 **1000 epochs** of training for deep representation learning
- 📈 Robust evaluation metrics: Precision, Recall, F1-score, MCC, AUC
- 📉 Training & validation visualizations using loss and accuracy curves

## 🧪 Model Highlights

- 📌 **Model**: TabTransformer (categorical embeddings + transformer blocks)
- 🏋️ **Epochs**: 1000
- 📊 **Macro-Averaged Metrics**:
  - Precision: **78%**
  - Recall: **72%**
  - F1-Score: **72%**
  - MCC: **0.65**
  - AUC: **93%**

These metrics reflect the model’s ability to identify nuanced safety perception patterns among varied user profiles — supporting intelligent urban planning.

## 📁 Files

- `tabtransformer model 1000 epochs.ipynb`: The main notebook containing model building, training, evaluation, and analysis.

## 🧠 About TabTransformer

Originally introduced by **Huang et al. (2020)**, TabTransformer integrates **self-attention** with **MLP layers** to better handle categorical features in tabular data. Unlike traditional approaches, it learns contextual relationships between feature values — making it ideal for complex datasets.

