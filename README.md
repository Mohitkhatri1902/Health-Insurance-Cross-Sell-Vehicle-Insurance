# Health-Insurance-Cross-Sell-Vehicle-Insurance

**Problem Statement**

Our client, an insurance company, seeks assistance in developing a model to forecast whether policyholders from the previous year would exhibit interest in the Vehicle Insurance offered by the company. As an insurance policy entails a guarantee of compensation for specified loss, damage, illness, or death in exchange for a premium payment, the client aims to extend its services to customers who might consider purchasing Vehicle Insurance.

The objective is to predict customer interest in Vehicle Insurance to enable targeted communication strategies, optimizing the company's business model and revenue generation. Leveraging demographic data (gender, age, region code type), vehicle information (vehicle age, damage), and policy details (premium, sourcing channel), the model aims to identify potential customers receptive to Vehicle Insurance offerings.

**Project Summary -**


Our project revolves around assisting an insurance company in enhancing its business model by predicting customer interest in Vehicle Insurance. The company, which already provides Health Insurance to its customers, seeks to diversify its offerings and tap into the market for Vehicle Insurance. By leveraging predictive modeling techniques, we aim to identify potential customers from the previous year who are likely to show interest in purchasing Vehicle Insurance.

The significance of this project lies in its potential to optimize the company's revenue generation and communication strategies. By accurately predicting customer interest in Vehicle Insurance, the company can tailor its marketing efforts and outreach campaigns, thereby maximizing the effectiveness of its resources. Additionally, by expanding its portfolio to include Vehicle Insurance, the company can capitalize on additional revenue streams and strengthen its competitive position in the insurance market.

To achieve our goal, we will employ various data science methodologies and techniques. We will start by acquiring and preprocessing the necessary data, which includes demographic information (such as gender, age, and region code type), vehicle details (including vehicle age and damage), and policy-related data (such as premium amount and sourcing channel). Through careful data cleaning and feature engineering, we will ensure that the dataset is suitable for model training and evaluation.

Next, we will explore and analyze the dataset to gain insights into the underlying patterns and relationships between different variables. This exploratory data analysis (EDA) phase will help us understand the characteristics of the data and identify potential predictors of customer interest in Vehicle Insurance.

Following the EDA phase, we will proceed to model development and evaluation. We will experiment with various machine learning algorithms, such as logistic regression, decision trees, random forests, and gradient boosting, to build predictive models. These models will be trained on historical data containing information about past customers and their purchasing behavior. We will evaluate the performance of each model using appropriate evaluation metrics, such as accuracy, precision, recall, F1-score, and ROC AUC.

Once we have identified the best-performing model, we will fine-tune its hyperparameters using techniques like grid search or random search to optimize its predictive performance further. The final model will then be deployed into production, where it will be used to predict customer interest in Vehicle Insurance for the upcoming year.

In conclusion, our project aims to leverage data science and predictive modeling techniques to help the insurance company identify potential customers interested in Vehicle Insurance. By accurately predicting customer behavior, the company can enhance its business strategies, improve customer satisfaction, and drive revenue growth in the competitive insurance market.

**Conclusion**

- We started by loading the dataset and conducted checks for null values and duplicates, finding none.
Through Exploratory Data Analysis (EDA), we observed that younger customers show more interest in vehicle insurance, particularly those aged below 30.
Customers with vehicles older than 2 years and those with damaged vehicles were more likely to express interest in vehicle insurance.
Key variables such as Age, Previously_Insured, and Annual_Premium were found to have significant impact on the target variable.
Feature selection using the Mutual Information technique identified Previously_Insured as the most influential feature, indicating no correlation between it and the target variable.
To address the highly imbalanced target variable, we applied Random Over Sample resampling technique.
Feature scaling techniques were employed to normalize the data for uniform processing by ML algorithms.
Machine Learning Algorithms were applied to predict customer interest in Vehicle Insurance, with Logistic Regression yielding an accuracy of 78%, and XGBClassifier achieving an accuracy of 81%.
Notably, the Random Forest model outperformed others with an accuracy of approximately 93% and ROC_AUC score of 94%.
In conclusion, Random Forest emerges as the superior model compared to others evaluated.
