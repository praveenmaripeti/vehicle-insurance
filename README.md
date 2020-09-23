# vehicle-insurance
Predictive modelling for vehicle insurance purchase

# Problem Overview
An insurance company that has provided Health Insurance to its customers now wants to offer Vehicle insurance also. We are required to develop a model that helps predict whether the policyholders (customers) from past year will also be interested in purchasing Vehicle Insurance provided by the company.

The following data is given for building the model:

id - Unique cust id
Gender
Cust age
Has Driving License - Yes or No
Region Code
Previously insured - Yes or No
Vehicle Age
Vehicle Damage - Yes or No
Annual Premium
Policy Sales Channel
Vintage - Days of association between company and customer
Target variable:

Response - Intersted or Not interested
Building a model to predict whether a customer would be interested in Vehicle Insurance is extremely helpful for the company because it can then accordingly plan its communication strategy to reach out to those customers and optimise its business model and revenue.

# In this Notebook, I will

Perform EDA
Do some data cleaning
Prepare features for feeding to the model
Evaluate 3 classification algorithms with default parameters first
Perform Hyperparameter tuning using RandomizedSearchCV
Generate predictions using the best model
Make submission
