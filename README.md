# Insurance_Customer_Response_Prediction
Develop a robust machine learning model to accurately predict customer responses to insurance policy offers. By utilizing this model, the company aims to improve targeted marketing, optimize their sales channel strategy, and increase the efficiency of their policy sales process.
## Project Overview
This project aims to enhance the understanding of customer behavior and improve the policy sales process in the insurance industry. By leveraging machine learning, the project seeks to predict customer responses to insurance policy offers based on various customer and policy characteristics. The goal is to develop a robust machine learning model that accurately forecasts customer responses, enabling improved targeted marketing, optimized sales channel strategies, and increased efficiency in the policy sales process.

## Project Benefits: 

Customer Insights:  The model will help identify factors influencing customer decisions, allowing for more targeted marketing strategies. 
Sales Channel Optimization: Understanding which channels are most effective for different customer segments can improve resource allocation. 
Improved Conversion Rates: Predicting customer responses can lead to more personalized offers and higher conversion rates. 

## Deliverables: 

A documented machine learning model specifically designed for predicting customer responses to insurance policy offers. 
Comprehensive data visualizations illustrating relationships between various customer features and their likelihood to respond positively. 
A comparative analysis of different machine learning algorithms for this classification task. 

## Dataset Description
•	The dataset contains customer details, vehicle information, and past insurance status.

* Here's a brief description of each column:

   •	id: unique identifier for each record
  
   •	Gender: Gender of the policyholder

   •	Age: Age of the policyholder

   •	Driving_License: Indicates if the person has a driving license

   •	Region_Code: Code representing the geographic region

   •	Previously_Insured: Whether the person was previously insured

   •	Vehicle_Age: Age of the vehicle

   •	Vehicle_Damage: Indicates if the vehicle has been damaged

   •	Annual_Premium: The yearly insurance premium amount

   •	Policy_Sales_Channel: The channel through which the policy was sold

   •	Vintage: length of time as a customer or policy age

   •	Response: Indicating policy renewal or claim filing

* The target variable is Response (1 = Interested, 0 = Not Interested).

## Project Workflow

1.	Data Preprocessing
   
     Handled missing values, encoded categorical features, and performed feature scaling.
Created new features such as Age_License, Damage_NoInsurance, and Policy_Interest.

3.	Exploratory Data Analysis (EDA) 

    Visualized feature distributions and customer response trends.

4.	Model Training & Evaluation
    Applied SMOTE to balance the dataset.

  	Trained and compared three models: Logistic Regression, Decision Tree, and Random Forest.

    Tuned hyperparameters and adjusted class weights to improve performance.

## Steps :
1. Import libraries
2. Read the dataset
3. check missing values
4. EDA Analysis
5. Correlation Analysis
6. Feature Engineering
7. Evaluate models
8. Test the best model

## Future Improvements

•	Experiment with XGBoost and LightGBM for better performance.

•	Fine-tune hyperparameters using Bayesian Optimization.

•	Deploy the model using Flask or FastAPI for real-time predictions


### And also i have upload the POWER BI Dashboard
