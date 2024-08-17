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
- **🔹 LightGBM Classifier**
- **🔹 Random Forest Classifier**
- **🔹 Decision Tree**
- **🔹 SVM**
- **🔹 Naive Bayes Classifier**
- **🔹 AdaBoost Classifier**
- **🔹 ANN**
- **🔹 Gradient Boosting (XGBoost)**

After tuning, **K-Nearest Neighbors** performed the best with an accuracy of **89%** 🏆.

## 🛠️ Installation

To set up this project locally, follow these steps 🛠️:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/shri11081999/Heart-Disease-prediction-using-AI.git
   cd Heart-Disease-prediction-using-AI

## 🖥️ Usage

1. Run the Jupyter notebook to explore the workflow

1. **Clone the repository:**

   ```bash
   jupyter notebook "Prediction of Heart disease using machine learning algorithm.ipynb"

2. Modify the notebook or script as needed to perform your analysis 🛠️.

3. Visualize the results using plots and charts 📊

## 📈 Results

| Model                      | Accuracy 🎯 |
| --------------------------- | ----------- |
| K-Nearest Neighbors         | 91% 🥇    |
| LightGBM Classifier         | 86% 🥈    |
| Logistic Regression         | 85% 🥉    |
| Random Forest               | 83%       |
| Decision Tree               | 75%       |
| SVM                         | 86%       |
| Naive Bayes Classifier      | 86%       | 
| AdaBoost Classifier         | 81%       | 
| ANN                         | 83%       |
| Gradient Boosting (XGBoost) | 78%       |

Among these, **K-Nearest Neighbors** emerged as the most accurate model with an accuracy of **91%**. 🌟

## 📸 Screenshots

Here is a comparison table showing the accuracy of the different machine learning models used in this project:

![comparison table](https://github.com/user-attachments/assets/9368c3e9-9810-4b25-af64-fb1273445351)

## 📚 Research Publication

For a deeper dive into the methods, results, and analysis, you can read the full research paper:

- **Title**: Prediction of Heart Disease Using Machine Learning Algorithms
- **Journal**: International Journal for Research in Applied Science & Engineering Technology (IJRASET)
- **DOI**: [10.22214/ijraset.2022.40768](https://doi.org/10.22214/ijraset.2022.40768)
- **Link**: [Read the Paper](https://doi.org/10.22214/ijraset.2022.40768)

## 🎯 Future Scope

🌐 Web Application: This project can be expanded into a web application to make predictions using the trained Logistic Regression model.

📈 Larger Dataset: Using a larger and more diverse dataset could further improve the model’s accuracy and generalizability.

## 📧 Contact
For any questions or issues, feel free to reach out via 📬 dixitshriniket976@gmail.com.

## 📜 License
This project is licensed under the MIT License - see the LICENSE file for details 📄.
