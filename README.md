# Heart Disease Prediction using AI & ML

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)
[![Machine Learning](https://img.shields.io/badge/Focus-Machine%20Learning-orange.svg)]()
[![Scikit-Learn](https://img.shields.io/badge/Library-Scikit--Learn-green.svg)](https://scikit-learn.org/)

## 📌 Project Overview
This project focuses on predicting the presence of heart disease in patients based on various clinical health markers. Using the UCI Heart Disease dataset, I developed a classification system that compares multiple machine learning algorithms to identify the most accurate diagnostic tool.

The study covers the entire data science lifecycle: from data cleaning and outlier detection to model evaluation using Precision, Recall, and F1-Scores.

## 📊 Key Features
- **Exploratory Data Analysis (EDA):** Visualization of correlation matrices, age distributions, and gender-based risk factors.
- **Data Preprocessing:** Handling missing values, feature scaling (StandardScaler), and encoding categorical variables.
- **Algorithm Comparison:** Implementation and tuning of:
  - Logistic Regression
  - Decision Tree Classifier
  - Random Forest Classifier (Top Performing Model)
- **Evaluation Metrics:** Detailed analysis using Confusion Matrices and Classification Reports.

## 🛠️ Tech Stack
- **Language:** Python
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn
- **Environment:** Jupyter Notebook

## 📈 Performance Summary
The **Random Forest Classifier** achieved the highest accuracy, demonstrating robust performance in handling the non-linear relationships within the clinical data.

| Model | Accuracy |
| :--- | :--- |
| Random Forest | ~85-90% |
| Logistic Regression | ~82% |
| Decision Tree | ~78% |

## 🚀 How to Run
1. Clone the repository.
2. Install dependencies:
    pip install pandas numpy matplotlib seaborn scikit-learn
3. Open the Jupyter Notebook file.


## 📂 Project Structure
HeartDiseaseAIPredictionModel.ipynb: Main analysis and code.

heart_disease.csv: Clinical dataset used for training.

.gitignore: Files excluded from the repository.
