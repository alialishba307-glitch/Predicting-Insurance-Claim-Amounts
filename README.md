# Predicting-Insurance-Claim-Amounts

#  Task Objective

The objective of this project is to build a regression model that predicts medical insurance claim charges based on personal attributes such as age, BMI, smoking status, and other demographic factors. The goal is to understand the key drivers of insurance costs and develop a predictive model that can assist insurance companies in pricing and risk assessment.

# Approach

The project follows a structured end-to-end regression workflow:

# Data Understanding & Exploration

Loaded and inspected the Medical Cost Personal dataset.

Analyzed dataset structure, feature types, and summary statistics.

Performed exploratory data analysis (EDA) to identify relationships between personal attributes and insurance charges.

# Data Preprocessing

Checked for missing values and data inconsistencies.

Encoded categorical variables using One-Hot Encoding.

Selected relevant features for modeling.

Split the dataset into training and testing sets.

# Model Development

Trained a Linear Regression model to predict insurance charges.

Generated predictions on the test dataset.

# Model Evaluation

Evaluated model performance using Mean Absolute Error (MAE).

Calculated Root Mean Squared Error (RMSE).

Interpreted model coefficients to understand feature impact.

# Results & Insights

Smoking status showed the strongest impact on insurance charges.

Age and BMI demonstrated a positive correlation with medical costs.

The Linear Regression model captured meaningful patterns in the data.

Proper feature encoding significantly improved model performance.

# Conclusion

This project demonstrates a complete regression modeling workflow for predicting insurance claim amounts. By applying proper preprocessing, feature encoding, and evaluation metrics, the model provides valuable insights into cost-driving factors. The results emphasize the importance of lifestyle and demographic attributes in determining medical insurance expenses.

# Future Improvements

Apply advanced regression models such as Random Forest Regressor or Gradient Boosting.

Perform hyperparameter tuning and cross-validation.

Explore polynomial regression to capture non-linear relationships.

Conduct residual analysis for deeper model diagnostics.

Deploy the model as an API for real-world insurance cost estimation.

# Tools & Technologies

Python

Pandas

NumPy

Scikit-learn

Matplotlib

Seaborn

Jupyter Notebook

