# ICSSR Tech Round 1: Predicting Customer Churn in the Telco Industry

## Objective
The objective of this project is to forecast customer churn (the likelihood of a customer remaining or departing) utilising the Telco dataset. We did this by doing Exploratory Data Analysis (EDA) and comparing a baseline model to a better machine learning model.

## Information about the submission- **Track:** Track 1 (Tabular ML)
- **Split for Training and Validation:** 80% for Training and 20% for Testing
- **Metrics Reported:** Accuracy, Precision, Recall, and F1-Score

## Comparing Models and Results
The evaluation code shows the following results for the test set:

### Examination- **Best Result:** The **Random Forest Classifier** is the best model, with an overall **Accuracy of 79%** and a **Macro F1-Score of 0.71**.
- **Looking at mistakes:** The Improved model has a slightly better Macro Average F1-score (0.71 vs. 0.70), which means it does a slightly better job of balancing "Churn" and "No Churn" predictions.

How to Run
1. In Google Colab, open the file with the extension ".ipynb."
2. Make sure you have `kagglehub` installed so you can download the dataset directly from Kaggle.
3. Run all of the cells to see the reports on how well the model works, the data cleaning process, and the EDA visualisations.
