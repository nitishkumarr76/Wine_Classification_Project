# 🍷 Wine Classification Using Apache Spark MLlib

## 📌 Project Overview

This project implements a Wine Classification system using **Apache Spark MLlib** and Scala. It uses machine learning algorithms to classify wines into different cultivars based on their chemical properties.

The project demonstrates distributed data processing, feature engineering, machine learning model training, and performance evaluation using Apache Spark.

## 🎯 Objectives

- Analyze the Wine dataset containing 178 records and 13 numerical features.
- Perform data preprocessing and feature transformation.
- Apply feature scaling using StandardScaler.
- Train and evaluate Decision Tree and Logistic Regression models.
- Compare model performance using classification metrics.
- Identify important features influencing wine classification.

## 🛠️ Technologies Used

- Apache Spark 3.5.8
- Scala 2.12.18
- Java 11
- Spark MLlib
- Docker Desktop
- Visual Studio Code
- Python (Data Visualization)

## 📂 Dataset Information

The project uses the Wine dataset with:

- Total Records: 178
- Number of Features: 13
- Target Variable: Cultivar
- Classification Classes: 3

Features include Alcohol, Malic Acid, Ash, Magnesium, Flavanoids, Color Intensity, Proline, and other chemical properties.

## 🤖 Machine Learning Algorithms

### 1. Decision Tree Classifier
A supervised learning algorithm that classifies wine samples using decision rules based on input features.

### 2. Logistic Regression
A classification algorithm used to predict the wine cultivar based on the chemical characteristics of each sample.

## ⚙️ Project Workflow

1. Dataset loading into Apache Spark.
2. Data preprocessing and column naming.
3. Feature selection using VectorAssembler.
4. Feature scaling using StandardScaler.
5. Splitting data into training and testing sets.
6. Training Decision Tree and Logistic Regression models.
7. Making predictions.
8. Evaluating model performance.
9. Feature importance analysis.
10. Saving trained models and CSV outputs.

## 📊 Model Performance

| Evaluation Metric | Decision Tree | Logistic Regression |
|---|---:|---:|
| Accuracy | 93.10% | 100% |
| Precision | — | 100% |
| Recall | — | 100% |
| F1-Score | — | 100% |

*Note: Metrics shown are from the recorded project evaluation. Results depend on the train-test split and evaluation setup.*

## 📈 Feature Importance

The Decision Tree model identified the following important features:

1. Proline
2. OD280/OD315
3. Flavanoids
4. Alcalinity of Ash
5. Alcohol
6. Malic Acid

Proline and OD280/OD315 were the two most influential features in the trained Decision Tree model.

## 📁 Project Outputs

- Trained Decision Tree model
- Trained Logistic Regression model
- Decision Tree predictions (CSV)
- Logistic Regression predictions (CSV)
- Feature importance (CSV)
- Model performance evaluation
- Data visualizations

## 🚀 Applications

- Wine quality and classification research.
- Chemical composition analysis.
- Machine learning model comparison.
- Distributed data processing demonstrations.
- Big Data analytics using Apache Spark.

## 👨‍💻 Author

**Nitish Kumar**

B.Tech (Hons.) – Computer Science and Engineering

Lovely Professional University

## 📌 Conclusion

This project demonstrates how Apache Spark MLlib can be used to perform machine learning classification on structured datasets. Both Decision Tree and Logistic Regression achieved strong classification performance, with Logistic Regression achieving 100% accuracy in the recorded test evaluation.

The project provides practical experience in Big Data processing, machine learning, feature engineering, and model evaluation.
