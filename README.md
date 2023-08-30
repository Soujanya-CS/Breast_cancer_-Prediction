# Breast Cancer Prediction using Machine Learning

This repository contains a data analysis project for predicting breast cancer using machine learning techniques. The goal is to build predictive models to classify whether a patient has breast cancer or not based on cell nucleus details from breast mass.

## Project Overview

The project involves the following steps:

1. **Data Loading and Exploratory Data Analysis (EDA):** Load the dataset, perform initial exploration, handle missing values, and visualize the data distribution.

2. **Data Pre-processing:** Prepare the data for modeling by encoding categorical variables, splitting the dataset into training and testing sets.

3. **Model Building:**
   - Build a Random Forest Classifier to predict breast cancer.
   - Build a Gradient Boosting Classifier for breast cancer prediction.
   - SVM

4. **Model Evaluation:** Evaluate the models using various performance metrics beyond accuracy, including precision, recall, F1 score, and ROC AUC.

5. **GitHub Repository Structure:**
   - `breast_cancer_dataset.csv`: The dataset used for analysis.
   - `breast_cancer_analysis.ipynb`: Jupyter Notebook containing the data analysis code.
   - `requirements.txt`: List of required Python packages.

## Requirements

Make sure you have the following libraries installed. You can install them using the following command:

```bash
pip install -r requirements.txt

**requirements**:

-pandas
-numpy
-matplotlib
-seaborn
-scikit-learn

## Conclusion

This project demonstrates the process of data analysis, preprocessing, building machine learning models, and evaluating their performance for breast cancer prediction. By considering various performance metrics, we gain a better understanding of how well the models are performing in detecting breast cancer.

