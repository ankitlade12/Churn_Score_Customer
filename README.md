**Problem Statement**

* One of the key metrics to measure a business success is by measuring its customer churn rate - the lower the churn, the more loved the company is.
* Typically, every user of a product or a service is assigned a prediction value that estimates their state of churn at any given time. This value may be based on multiple factors such as the user’s demographic, their browsing behavior and historical purchase data, among other details.
* This value factors in unique and proprietary predictions of how long a user will remain a customer and is updated every day for all users who have purchased at least one of the products/services and values assigned are between 1 and 5.


**Goal**

The goal of this competition was to develop a machine learning model to predict the churn score of a customer based on different features.


**Machine Learning Model**

XGBoost Classifier to get to a score of 63.04918 and it was evaluated by score = 100 x metrics.f1_score(actual, predicted, average="macro").


**Rank**

315/4189.
