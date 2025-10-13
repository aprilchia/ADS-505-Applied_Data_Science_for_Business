# Predictive Modeling: Credit Card Fraud Classification
This project is a part of the ADS-505 course in the Applied Data Science Program at the University of San Diego.

#### -- Project Status: [In Progress]

## Installation
To use the project:
1. Clone the repository using the following commands:
```
git init
```
```
git clone https://github.com/aprilchia/ADS-505-Applied_Data_Science_for_Business.git
```
2. Run the [Final Project Notebook](https://github.com/aprilchia/ADS-505-Applied_Data_Science_for_Business/blob/main/Final_Notebook.ipynb)

## Project Introduction
Credit card fraud poses a major challenge for financial institutions, leading to significant financial losses and diminished customer trust. Traditional rule-based detection systems often struggle to adapt to evolving fraud patterns which results in either too many false positives (legitimate transactions flagged as fraud) or missed detections of real fraudulent activity. This project applies machine learning techniques to detect fraudulent credit card transactions. The dataset contains over 284,000 transactions, of which only 0.17% are fraudulent, making this a highly imbalanced classification problem that reflects real-world financial data challenges.

## Project Objective
The primary objective of this project is to build and evaluate machine learning models that can accurately identify fraudulent credit card transactions while minimizing false positives:
* Develop and compare 7 models (Logistic Regression, Linear SVM, Neural Network (MLP), Naive Bayes, Random Forest, Decision Tree, XGBoost).
* Address the class imbalance using techniques such as SMOTE (Synthetic Minority Oversampling Technique).
* Evaluate performance using metrics suited for imbalanced data: Precision, Recall, F1-score, ROC-AUC, and PR-AUC.
* Select the best-performing model based on both predictive accuracy and business relevance.

## Partner(s)/Contributor(s)
* [April Chia](https://github.com/aprilchia)
* [Luisa Gonzalez](https://github.com/luisavgonzalez27)
* [Paul Matta](https://github.com/paulmatta)

## Methods
* Exploratory Data Analysis
* Data Visualization
* Data Preprocessing
* Predictive Modeling

## Technologies
* Python

## Project Description
### Data Sources
* The [creditcard.csv](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud?select=creditcard.csv) dataset is provided by Kaggle.
### Models Used
* Logistic Regression
* Neural Network (MLP)
* Linear Support Vector Machine (SVM)
* Naive Bayes (Gaussian)
* Decision Trees
* Random Forest
* Boosted Trees (XGBoost)
