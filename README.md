# 🧠 Machine Learning Projects Portfolio

This repository contains two machine learning projects built with Python and powerful libraries such as Scikit-learn, Pandas, Matplotlib, Streamlit, and Gradio. Each project demonstrates key ML workflows including data preprocessing, model training, evaluation, and deployment.

---

## 📊 Project 1: California Housing Price Prediction

### 📌 Overview
A regression project that predicts housing prices in California using the **California Housing Dataset**. It includes data exploration, feature engineering, model comparison, and deployment using Streamlit.

### 🔧 Technologies & Tools
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Streamlit

### 🧪 Workflow

1. **Dataset Loading**
   - Loaded using: `fetch_california_housing()` from `sklearn.datasets`.

2. **Exploratory Data Analysis**
   - Histograms for all features.
   - Scatter matrix for key attributes to study relationships.

3. **Data Preprocessing**
   - **Missing Values**: Handled with `SimpleImputer`.
   - **Feature Engineering**: Created "rooms per household".
   - **Feature Scaling**: Used `StandardScaler` for normalization.

4. **Model Training**
   - Trained three regression models:
     - Linear Regression
     - Decision Tree Regressor
     - Random Forest Regressor

5. **Evaluation**
   - Metrics used: **RMSE** (Root Mean Squared Error) and **MAE** (Mean Absolute Error).
   - Selected the best-performing model based on evaluation scores.

6. **Deployment**
   - Deployed with **Streamlit** for an interactive web interface.





# 🔢 📊 Project 1MNIST Digit Recognition Project

A complete machine learning pipeline to classify handwritten digits from the popular MNIST dataset. This project demonstrates how to load, process, train, evaluate, and deploy digit classifiers using Python and open-source libraries.

---

## 📌 Overview

This is a classification project that focuses on recognizing handwritten digits (0–9) using the **MNIST dataset**. It covers the full ML lifecycle from loading data to deployment. The model is served using a **Gradio-based web interface**, allowing real-time digit predictions through a friendly UI.

---

## 🔧 Technologies & Tools

- 🐍 Python  
- 🔢 Scikit-learn  
- 📊 Pandas, NumPy  
- 📈 Matplotlib  
- 🌐 Gradio  

---



