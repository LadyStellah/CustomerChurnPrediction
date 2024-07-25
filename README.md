# Customer Churn Prediction

![Customer_Churn_Prediction_Models Pic](https://github.com/user-attachments/assets/70174468-6397-4dd5-8437-780f385a63a4)

## Table of Content
- [Project Overview](#project-overview)
- [Project Objective](#project-objective)
- [Data Source](#data-source)
- [Data Preprocessing](#data-preprocessing)
- [Machine Learning](#machine-learning)
- [Evaluation Metrics](#evaluation-metrics)
- [Key Insights](#key-insights)
- [Conclusion](#conclusion)

## Project Overview
This Customer Churn Prediction project aims to develop a predictive model that identifies customers who are likely to discontinue using our services. By leveraging historical customer data and advanced machine learning techniques, the project seeks to proactively address churn risk, enhance customer retention strategies, and ultimately improve customer loyalty and business profitability.

## Project Objective
Here are list of our project objectives:

- **Develop robust machine learning model to predict customer churn.**
- **To identify key factors and patterns that contribute to customer churn.**
- **To integrate the predictive model into the customer relationship management (CRM) system for real-time monitoring and alerts.**
- **To develop actionable insights and strategies to mitigate churn risks.**
- **To also enhance customer retention and satisfaction.**

## Data Source
The data used in this project was provided by 10Alytics. The dataset contains a collection of features which includes customer demographic details, usage patterns, service plans, and payment history.

## Data Preprocessing
To gain insights and carry out a well precise machine learning prediction for the customer churn, an effective data preprocessing is crucial. These includes collecting of relevant data such as customer demographics, handling missing values, identifying outliers using statistical methods, identifying and removing duplicates, converting categorical data into numerical format, perform feature engineering and train, test and split the dataset for machine learning.

## Machine Learning
The customer churn prediction model is trained and built using several supervised machine learning approach. Training and test data was split 60:40 and several classification algorithms were experimented with

- **Logistic Regression**
- **Decision Tree**
- **Naive Bayes**
- **SVC**
- **SGD Classifier**
- **K-Nearest Neighbors**
- **Random Forest**
- **XGB Classifier**

After an extensive experimentation and hyperparameter tuning, the best performing machine learning model is Logistic Regression. This was chosen based on its performance and general capabilities.

##  Evaluation Metrics
To access the performance of the machine learning model, the following evaluation metrics were used

- **Accuracy Score:** The ratio of correctly predicted instances (both churn and non-churn) to the total instances.
- **Precision:** The ratio of correctly predicted positive instances (churn) to all instances predicted as positive.
- **Recall:** The ratio of correctly predicted positive instances(churn) to all actual positive instances.
- **ROC AUC:** The models ability to distinguish between classes across different threshold settings.

## Key Insights

- The purpose of this customer churn prediction is to Identify customers who are most likely to churn based on the prediction model.
- Identify key factors contributing to churn by understanding customer behavior, demographic factors and service experience.
- Group customers into segments based on their likelihood to churn and tailor retention strategies based on specific need and behavior.
- To develop targeted communication plans for high-risk customers such as personalized offer, discounts or loyalty programs.
- Identify and address common service issues or pain points that contribute to churn.
- Understand the performance of the prediction model through the evaluation metrics and identify features that are most influential in    predicting churn.
- To analyze feedback from churned customers to identify frequent complaint or issues and to implement improvements based on feedback to reduce churn.
- Finally, to identify if there are churn patterns, specific times of the year or business cycle when churn rates are higher and to develop targeted campaigns to address churn during these critical period.

## Conclusion
In summary, leveraging these insights, the company can develop effective retention strategies, improve customer satisfaction, and ultimately enhance profitability. Understanding why customers churn and proactively addressing these factors can lead to significant reduction in churn rates and better overall customer relationships.
