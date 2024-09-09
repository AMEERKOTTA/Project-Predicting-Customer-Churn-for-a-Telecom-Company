# Project: Customer Churn Prediction for a Telecom Company
## Objective:
To build a machine learning model to accurately predict customer churn for a telecom company, enabling the company to take proactive measures to retain high-risk customers.

## Project Details:
### Data Collection:

Utilized a dataset containing customer demographics, account information, service usage patterns, and payment details to understand customer behavior and identify churn indicators.
### Data Preprocessing:

+ Cleaned and prepared the data by handling missing values and outliers.
+ Converted the target variable (‘Churn’) to a numeric format.
+ Encoded categorical variables using Label Encoding.
+ Scaled numerical features to normalize the data.
+ Applied SMOTE (Synthetic Minority Over-sampling Technique) to balance the classes and improve model performance.
### Exploratory Data Analysis (EDA):

+ Conducted EDA to identify key patterns, correlations, and features influencing customer churn.
+ Visualized the relationships between different features using histograms, bar charts, and correlation matrices.
### Feature Engineering:

+ Selected important features for the model using methods like feature importance from tree-based models and Recursive Feature Elimination (RFE).
### Model Development:

+ Trained multiple machine learning models, including Logistic Regression, Random Forest, and TabNet, to predict customer churn.
+ Used Optuna for hyperparameter tuning to find the best model configuration.
+ Evaluated model performance using cross-validation and metrics such as accuracy, precision, recall, and F1-score.
+ Selected the TabNet model for its superior performance on the evaluation metrics.
### Model Deployment:

+ Developed a REST API using Flask to serve the churn prediction model and handle incoming data for real-time predictions.
+ Implemented an endpoint to accept customer data, preprocess it, and return the churn prediction.
### Testing and Evaluation:

+ Tested the deployed API with multiple customer profiles to ensure it provided accurate and reliable predictions.
+ Used Python scripts to automate testing of the model with a wide range of input data.

**Key Technologies Used:**
+ Data Processing and Modeling: Python (Pandas, NumPy, Scikit-Learn, PyTorch, TabNet, XGBoost), Optuna.
+ Deployment: Flask for REST API.
