---
layout: default
title: Whitney Bullock Portfolio
---

# IS-6812-Project 
This is a repo for the practice capstone project completed by Group 5 during Fall semester 2025 for IS 6812 

---
## Highlights 
⭐Business Problem

⭐Solution to Business Problem 

⭐Personal Contribution

⭐Business Value of Solution

⭐Difficulties During Project

⭐Key Takeaways 


## Business Problem 
Home Credit is a financial services provider specializing in lending to individuals with little or no credit history, empowering them with easy and safe access to financing. It is crucial for Home Credit to accurately assess a customer’s ability to repay in order to identify reliable target customers. By effectively predicting repayment capability, Home Credit can responsibly extend credit to a larger customer base while minimizing financial risk to the company and its investors.

## Solution to Business Problem 
To address Home Credit's need for reliable and responsible lending decisions, our project will develop a machine learning model to use as a risk assessment to predict whether a customer is likely to default on a loan.  By anlayzing various variables provided in the loan-application process our models will quantify the customer's repayment capability when standard credit history is limited. 

## Personal Contribution 
My personal contributions to the project include Business Problem statement, Exploratory Data Analysis, Logistic Regression Model, Decision Tree Model, and Presentation slide deck.  

## Business Value of Solution 
There is three objectives in our solution to add value to the business: 

✔️Maximize Customer Base 

✔️Minimize Financial Risk 

✔️Empower Financial Freedom 

✔️Enhance Operation Efficiency 

By accurately predicting customer's likelihood of defaulting on a loan with limited credit history Home Credit can make more informed lending decisions.  This will enable Home Credit to responsibly extend credit to a broader range of customers while reducing their risk of default.  Our solution supports responsible lending for Home Credit and financial inclusion for it's customers, who generally are underserved.  A bi-product of the decision tree model is the ability generate automated approval / rejection processes based on specific loan application responses.  Overall, our predictive models empower Home Credit to balance financial inclusion with risk mitigation, strengthening Home Credit's customer reach and sustainability.  

## Difficulties During Project 
The main difficulty during the project was combatting class imbalance. Only about 8% of the target variable represented loan defaults, which caused the models to be biased toward predicting non-defaulters.

To address this challenge:

In the decision tree model, the minority class (loan defaults) was given a higher weight of 5:1 during training, helping the model pay more attention to default cases.

Cross-validation techniques were applied to improve model performance and ensure more robust and generalizable predictions.

Despite these measures, handling the class imbalance remained a key challenge, highlighting the importance of careful preprocessing, evaluation, and tuning for predictive modeling in imbalanced datasets.

