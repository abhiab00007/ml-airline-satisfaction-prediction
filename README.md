# ✈Airline Passenger Satisfaction Prediction

##  Project Overview

This project builds and evaluates machine learning models to predict airline passenger satisfaction using demographic and in-flight service features. It covers the full machine learning pipeline including data cleaning, exploratory data analysis (EDA), feature engineering, model training, hyperparameter tuning, and performance evaluation.

---

##  Dataset

- Contains passenger reviews and ratings across various airline services.
- Features include both categorical and numerical variables.
- Target variable: `satisfaction` (Satisfied / Neutral or Dissatisfied).

---

##  Workflow Summary

1. **Data Loading and Exploration**
2. **Handling Missing Values**
3. **Outlier Detection and Correction (IQR method)**
4. **Exploratory Data Analysis (EDA)**
   - Univariate, Bivariate, and Multivariate Visualizations
5. **Feature Engineering**
6. **Encoding Categorical and Ordinal Features**
7. **Feature Scaling**
8. **Model Training and Evaluation**
   - Logistic Regression, Decision Tree, Random Forest, etc.
9. **Hyperparameter Tuning using GridSearchCV**
10. **Final Model Selection and Accuracy Reporting**

---

##  EDA Highlights

- **Univariate**: Count plots and histograms for individual feature distributions.
- **Bivariate**: Class preferences across flight distance and service ratings.
- **Multivariate**: Correlation heatmap between numeric variables.

---

##  Machine Learning Models

The following models were implemented and evaluated:

- Logistic Regression  
- Decision Tree Classifier  
- Random Forest Classifier  
- Gradient Boosting Classifier  
- Support Vector Classifier (SVC)  
- K-Nearest Neighbors (KNN)

Used **GridSearchCV** for tuning hyperparameters and selecting the best model.
