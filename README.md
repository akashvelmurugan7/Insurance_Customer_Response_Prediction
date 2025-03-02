# Insurance_Customer_Response_Prediction
Predicting Customer Interest in Vehicle Insurance Using Machine Learning
## Project Overview
This project aims to predict whether a customer will show interest in purchasing a vehicle insurance policy based on historical data. Using Logistic Regression, Decision Tree, and Random Forest models, we evaluate customer responses and identify key factors influencing insurance interest.

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

## Future Improvements

•	Experiment with XGBoost and LightGBM for better performance.

•	Fine-tune hyperparameters using Bayesian Optimization.

•	Deploy the model using Flask or FastAPI for real-time predictions
