# BetaGroup_JC_DS_FT_JKT_26_FinalProject

# Data-Driven Analysis and Prediction of Term Deposit Subscription in Bank Marketing 

This repository contains a Jupyter Notebook analyzing and predicting the success of term deposit subscriptions in a bank marketing campaign. The analysis is part of a collaborative project by students of Purwadhika Digital Technology School, Batch 2604.

## Authors

- [Vina Valentia](https://www.linkedin.com/in/vina-valentia-87616823b/)
- [Rafli Fauzan Andara](https://www.linkedin.com/in/fauzandarafli/)
- [Nuraini Septiana](https://www.linkedin.com/in/nuraini-septiana-nynk2709/)

## Project Overview

Caixa Geral de Depósitos (CGD) is Portugal's largest state-owned bank, established in 1876. One of its key offerings is term deposits, which provide customers with secure investment options and fixed returns. Term deposits require customers to deposit a specific amount that can only be withdrawn after a predetermined period, during which they earn a fixed interest rate. These products are particularly attractive for individuals and businesses seeking low-risk investments.

To remain competitive in the financial market, CGD relies on effective marketing strategies, including telemarketing campaigns. This method involves contacting potential customers via phone to promote term deposit products. However, designing an impactful telemarketing campaign is challenging due to the diversity of customer preferences and financial goals.

The objective of this project is to analyze data from CGD’s telemarketing campaigns, understand customer behavior, and build a predictive model to identify individuals likely to subscribe to term deposits. This approach enables more targeted marketing, improves campaign efficiency, and optimizes resource allocation.
The project focuses on utilizing data from a bank marketing campaign to understand customer behavior and predict the likelihood of a customer subscribing to a term deposit. The notebook combines exploratory data analysis, preprocessing, and machine learning modeling to derive actionable insights and build a predictive solution.

## Business Formulation

- **Problem**:  
  - CGD struggles to effectively target potential customers for term deposit products through telemarketing campaigns.  
  - Lack of a data-driven approach reduces campaign efficiency and conversion rates.  

- **Data**:  
  Historical telemarketing campaign data, including:  
    - Demographic characteristics (e.g., age, job, marital status).  
    - Transaction history and previous campaign outcomes.  
    - Social and economic indicators (e.g., employment variation rate, consumer confidence index).  

- **ML Objective**:  
  - Develop a predictive model to forecast the likelihood of customers subscribing to term deposits.  

- **Action**:  
  - Analyze historical campaign data to identify key customer segments.  
  - Use machine learning to predict and implement targeted marketing strategies.  

- **Value**:  
  - Improve conversion rates and optimize marketing budgets.  
  - Secure third-party funds to support lending activities, increasing bank revenue.  
  - Empower the Chief Marketing Officer (CMO) with actionable insights for decision-making.

- **Stakeholder**:
  - Chief Marketing Officer (CMO), responsible for driving revenue growth through effective marketing strategies.

## Dataset  

The dataset is related to direct marketing campaigns (phone calls) conducted by a Portuguese banking institution. It was originally created by Sérgio Moro (ISCTE-IUL), Paulo Cortez (Univ. Minho), and Paulo Rita (ISCTE-IUL) in 2014 and is based on the "Bank Marketing" dataset available at the [UCI Machine Learning Repository](http://archive.ics.uci.edu/ml/datasets/Bank+Marketing).  

The dataset has been enriched with five additional social and economic features derived from nationwide indicators in Portugal, sourced from the Banco de Portugal and publicly available at [https://www.bportugal.pt/estatisticasweb](https://www.bportugal.pt/estatisticasweb). These additions enhance the dataset by providing macroeconomic context.  

The dataset, `bank-additional-full.csv`, contains 41,188 examples with 20 input features, spanning a period from May 2008 to November 2010. The attributes include:  

- **Demographics:** Age, job, marital status, education level.  
- **Campaign-related Data:** Communication type, number of contacts, and duration.  
- **Previous Campaign Data:** Outcomes of past campaigns for each client.  
- **Social and Economic Indicators:** Features such as employment variation rate, consumer price index, and confidence indicators.  
- **Target Variable:** Subscription status (`yes` or `no`).  

This comprehensive dataset provides valuable insights for understanding customer behavior and improving telemarketing campaign strategies.  

## Notebook Contents

### Part I: Business Problem Understanding
- **Context:** Understanding the background of bank company and importance of bank marketing campaigns for depositor acquisition.
- **Problem Statement:** How to improve the success rate of term deposit subscriptions.
- **Goal:** Deeper analysis and build a predictive model to identify high-probability customers.
- **Evaluation Metric:** Use F2 Score metrics for performance evaluation.

### Part II: Data Understanding
- Dataset exploration and importing libraries.

### Part III: Data Cleaning for Data Analysis
- Explorating data distribution.
- Handling duplicate data, missing values, and outliers.

### Part IV: Deeper Data Analysis
- Analysis of key variables, distributions, and relationships/correlation between each feature and target.

### Part V: Data Preprocessing for Machine Learning
- Handling missing values and outliers.
- Feature engineering to enhance model input

### Part VI: Machine Learning Model Training
- Benchmarking with baseline models.
- Modeling, Resampling, and Model Class Weight.
- Hyperparameter tuning and cross-validation.
- Choosing the final model and evaluation.

### Part VII: Evaluating Business Impact and Interpreting ML Models
- Business impact analysis of the predictions.
- Interpreting the machine learning model.

### Part VIII: Model Deployment
- Deployment the model with generated new data.
- Predictive script of model deployment.

### Part VI: Conclusion and Recommendations
- Summarizing findings and providing actionable insights for bank marketing campaign optimization.

## Analysis Visualization with Tableau Dashboard

## Model Deployment

## Requirements

- Python 3.8+
- Jupyter Notebook
- Libraries:
  - **Pandas**: For data manipulation and analysis.
  - **Numpy**: For numerical operations.
  - **Missingno**: For visualizing missing data.
  - **Scipy**: For statistical functions, such as Spearman correlation and Chi-squared test.
  - **Matplotlib**: For creating data visualizations.
  - **Seaborn**: For statistical data visualizations.
  - **Pickle**: For saving and loading Python objects.
  - **SHAP**: For explainable AI (SHAP values).
  - **Statsmodels**: For statistical models, including variance inflation factor.
  - **Scikit-learn**: For machine learning algorithms.
  - **Category_encoders**: For encoding categorical variables.
  - **Catboost**: For gradient boosting using the CatBoost model.
  - **XGBoost**: For Extreme Gradient Boosting model.
  - **LightGBM**: For Light Gradient Boosting model.
  - **IMBLearn**: For handling imbalanced datasets.
  - **Faker**: For generating fake data for testing.
