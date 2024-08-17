# ❤️🔍 Heart Disease Prediction Using Machine Learning

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Python](https://img.shields.io/badge/Python-3.x-brightgreen.svg)](https://www.python.org/)

Welcome to the **Heart Disease Prediction Using Machine Learning** project! This repository contains code and research aimed at predicting heart disease using various machine learning algorithms. Early detection can save lives, and this project compares different models to find the most accurate prediction method. 🩺✨

![sa](https://github.com/user-attachments/assets/39daf173-8b1d-4491-92e8-4a6286b9d47a)

## 📝 Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Methodology](#methodology)
- [Models Used](#models-used)
- [Results](#results)
- [Screenshots](#screenshots)
- [Installation](#installation)
- [Usage](#usage)
- [Future Scope](#future-scope)
- [Contributors](#contributors)
- [Contact](#contact)
- [License](#license)

## 🚀 Introduction

Heart disease is one of the leading causes of death globally 🌍, and early detection is crucial to saving lives 💓. This project leverages machine learning algorithms to predict heart disease based on various medical features 🧠. The goal is to classify whether a patient has heart disease (1️⃣) or not (0️⃣), using predictive models that can assist healthcare professionals 👩‍⚕️👨‍⚕️.

This project evaluates the performance of different machine learning algorithms including **Logistic Regression**, **K-Nearest Neighbors (KNN)**, and **Random Forest** to determine the most accurate model 📊.

## 📊 Dataset

We used the **UCI Heart Disease Dataset** 💽, which contains 303 records with 14 attributes (e.g., age, gender, cholesterol level) that can be used to predict the presence of heart disease in a patient 🏥.

- **Source**: [UCI Heart Disease Dataset](https://archive.ics.uci.edu/ml/datasets/heart+disease)
- **Target Variable**: `1` for the presence of heart disease, `0` for the absence of heart disease.

## 🛠️ Methodology

This project follows these steps 🔄:

1. **Data Preprocessing**: Data cleaning 🧼, normalization, and splitting into training and testing sets.
2. **Model Training**: Training several machine learning models on the preprocessed data 🎯.
3. **Hyperparameter Tuning**: Optimizing the models using grid search to get the best performance ⚙️.
4. **Evaluation**: Assessing models based on accuracy, precision, recall, and F1 score 🏅.

## 🤖 Models Used

The following machine learning models were implemented and compared:

- **🔹 Logistic Regression**
- **🔹 K-Nearest Neighbors (KNN)**
- **🔹 Random Forest Classifier**

After tuning, **Logistic Regression** performed the best with an accuracy of **89%** 🏆.

## 📈 Results

| Model                      | Accuracy 🎯 |
| --------------------------- | ----------- |
| Logistic Regression         | 89% 🥇      |
| Random Forest               | 83% 🥈      |
| K-Nearest Neighbors         | 75% 🥉      |

Among these, **Logistic Regression** emerged as the most accurate model with an accuracy of **89%**. 🌟

## 📸 Screenshots

Here is a comparison table showing the accuracy of the different machine learning models used in this project:

![Model Comparison](https://via.placeholder.com/800x300.png?text=Insert+Comparison+Table+Screenshot+Here)

*(Replace the placeholder image above with your actual comparison table screenshot)*

## 🛠️ Installation

To set up this project locally, follow these steps 🛠️:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/heart-disease-prediction.git
   cd heart-disease-prediction
