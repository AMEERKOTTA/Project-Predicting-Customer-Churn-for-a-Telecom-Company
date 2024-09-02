# Project-Predicting-Customer-Churn-for-a-Telecom-Company

## Objective:
The goal of this project is to predict whether a customer will churn (i.e., leave the service) based on their usage patterns, demographic information, and other relevant features.

## Column Explanations

1. `customerID`: Unique identifier assigned to each customer.
2. `gender`: The gender of the customer (e.g., Male, Female).
3. `SeniorCitizen`: Indicates whether the customer is a senior citizen (1 if Yes, 0 if No).
4. `Partner`: Indicates whether the customer has a partner or not (Yes or No).
5. `Dependents`: Indicates whether the customer has dependents (children or other family members) (Yes or No).
6. `tenure`: The number of months the customer has been with the company.
7. `PhoneService`: Indicates if the customer has a phone service subscription (Yes or No).
8. `MultipleLines`: Indicates if the customer has multiple lines for phone service (Yes, No, or "No phone service").
9. `InternetService`: Indicates the type of internet service the customer has (e.g., DSL, Fiber optic, or No).
10. `OnlineSecurity`: Indicates whether the customer has an online security add-on (Yes, No, or "No internet service").
11. `OnlineBackup`: Indicates whether the customer has an online backup add-on (Yes, No, or "No internet service").
12. `DeviceProtection`: Indicates whether the customer has a device protection plan (Yes, No, or "No internet service").
13. `TechSupport`: Indicates whether the customer has a technical support plan (Yes, No, or "No internet service").
14. `StreamingTV`: Indicates whether the customer has a streaming TV service (Yes, No, or "No internet service").
15. `StreamingMovies`: Indicates whether the customer has a streaming movies service (Yes, No, or "No internet service").
16. `Contract`: The type of contract the customer has (Month-to-month, One year, Two year).
17. `PaperlessBilling`: Indicates if the customer has chosen paperless billing (Yes or No).
18. `PaymentMethod`: The method of payment chosen by the customer (e.g., Electronic check, Mailed check, Bank transfer, Credit card).
19. `MonthlyCharges`: The amount charged to the customer monthly.
20. `TotalCharges`: The total amount charged to the customer over their tenure with the company.
21. `Churn`: The target variable indicating whether the customer has churned (left the company) or not (Yes or No).

The dataset is typically used to analyze factors that influence customer churn, which can help in building a predictive model to identify customers who are likely to churn in the future.

### Column Data Types and Explanations:
+ customerID (object): Unique identifier for each customer. No preprocessing needed for modeling but useful for tracking.
+ gender (object): Categorical variable representing the customer's gender. Needs encoding (e.g., Male = 0, Female = 1).
+ SeniorCitizen (int64): Numerical representation (0 = No, 1 = Yes) indicating if the customer is a senior citizen. Already suitable for modeling.
+ Partner (object): Categorical variable indicating if the customer has a partner (Yes/No). Requires encoding.
+ Dependents (object): Categorical variable showing if the customer has dependents (Yes/No). Requires encoding.
+ tenure (int64): Numerical data showing the number of months the customer has been with the company. Ready for use in modeling.
+ PhoneService (object): Categorical variable indicating if the customer has phone service (Yes/No). Needs encoding.
+ MultipleLines (object): Categorical variable (Yes, No, or "No phone service") indicating multiple phone lines. Requires encoding.
+ InternetService (object): Categorical variable representing the type of internet service (DSL, Fiber optic, or No). Needs encoding.
+ OnlineSecurity, OnlineBackup, DeviceProtection, TechSupport, StreamingTV, StreamingMovies (object): Categorical variables indicating whether the customer has these add-ons (Yes, No, or "No internet service"). All require encoding.
+ Contract (object): Categorical variable for contract type (Month-to-month, One year, Two year). Requires encoding.
+ PaperlessBilling (object): Categorical variable indicating if the customer uses paperless billing (Yes/No). Needs encoding.
+ PaymentMethod (object): Categorical variable representing the payment method (e.g., Electronic check, Mailed check). Needs encoding.
+ MonthlyCharges (float64): Numerical variable representing the monthly charges. Suitable for modeling.
+ TotalCharges (object): Potential Issue: Should be numeric but is currently an object type. Needs conversion to a numeric type after handling any non-numeric or missing values.
+ Churn (object): Target variable indicating customer churn (Yes/No). Requires encoding (e.g., No = 0, Yes = 1).

### Handling Missing Values
There is no Missing Values in the dataset.
