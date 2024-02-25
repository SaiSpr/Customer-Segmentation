Customer Segmentation and Propensity Modeling 📊


Predicting user behavior and segmenting customers in an e-commerce platform is crucial for targeted marketing and personalized user experiences. This guide covers all aspects of the project, from problem statement to model deployment.

<br><br>
Table of Contents

    Problem Statement
    Project Aims
    Dataset Overview
    Feature Engineering and Transformation
    Modelling
    Evaluation Metrics
    Conclusion
    APP Deployment
    Notebooks Overview
    Code Structure
    License

<br><br>
Problem Statement

The primary goal of this project is to gain actionable insights into user behavior within an e-commerce platform during January 2020. Through a combination of exploratory data analysis (EDA), feature engineering, and machine learning models, our aim is to uncover patterns, preferences, and purchasing dynamics that can inform targeted marketing strategies.
Project Aims

Aim 1: User Interaction Analysis:
To conduct comprehensive exploratory data analysis (EDA) on user interactions within the e-commerce platform, unraveling patterns and trends that characterize user engagement.

Aim 2: User Behavior Understanding:
To comprehensively understand user interactions, preferences, and engagement within the e-commerce platform.

Aim 3: Action-Based Insights:
To understand user actions through univariate analysis, with a focus on the 'Action' column, providing insights into how customers interact with products.

Aim 4: RFM Feature Utilization:
To employ Recency, Frequency, and Monetary (RFM) analysis for customer segmentation, creating a personalized understanding of user behavior for targeted marketing strategies.

Aim 5: Machine Learning Model Deployment:
To apply and rigorously evaluate machine learning models, including logistic regression, Naive Bayes, Random Forest, XGBoost, and LightGBM, with the aim of predicting user actions and selecting the most effective model for deployment.
Dataset Overview

The dataset used for the project contains e-commerce data from January 2020. It provides an extensive amount of data on user interactions within an e-commerce platform. Key attributes include 'User_id,' 'Session_id,' 'Event_Time,' 'Main_Category,' 'Sub_Category,' 'Brand,' 'Action,' and 'Total_Price.'

Data Set Size: 5,596,704 Rows and Nine Columns
Feature Engineering and Transformation

RFM Feature Extraction:

    Recency: Number of days between the latest date in the dataset and the last purchase date for each individual customer.
    Frequency: Total number of purchases made by each customer.
    Monetary: Total amount spent by each customer.

Modelling

The project involves a binary classification task to predict user actions, classifying users into two classes: Class 1 (single purchase) and Class 2 (more than one purchase). The following models were employed:

    Logistic Regression
    Naive Bayes
    Random Forest
    XGBoost
    LightGBM

Evaluation Metrics

Evaluation was based on various metrics, including Confusion Matrix, Precision, Recall, F1 Score, and ROC-AUC Score.
Conclusion

The project successfully built predictive models to determine the likelihood of customer churning, providing actionable insights into user behavior, preferences, and purchasing dynamics.
APP Deployment

Streamlit App: Customer Segmentation and Propensity Modeling
Notebooks Overview
1. PropensityData_EDA.ipynb

Description: This notebook conducts exploratory data analysis (EDA) on user interactions within the e-commerce platform, unraveling patterns and trends that characterize user engagement.
2. PropensityData_RFM_Features.ipynb

Description: This notebook employs Recency, Frequency, and Monetary (RFM) analysis for customer segmentation, creating a personalized understanding of user behavior for targeted marketing strategies.
3. RFM Modeling.ipynb

Description: This notebook conducts RFM modeling, including feature extraction, preprocessing, and model training, to predict user actions and select the most effective model for deployment.
4. Propensity Modeling.ipynb

Description: This notebook applies and evaluates machine learning models, including logistic regression, Naive Bayes, Random Forest, XGBoost, and LightGBM, for propensity modeling and deployment.
Code Structure

css

.
├── README.md                     - provides an overview of the project

├── notebooks                    - exploratory and developmental Jupyter notebooks.
│   ├── PropensityData_EDA.ipynb
│   ├── PropensityData_RFM_Features.ipynb
│   ├── RFM Modeling.ipynb
│   └── Propensity Modeling.ipynb

├── models                        - machine learning models.

└── img                           - images used in the readme.

