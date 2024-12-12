# CTC-prediction-using-Machine-Learning
In this project a machine learning regression task was conducted to develop a predictive model for estimating the salaries of newly hired employees. The dataset included features such as college, city, role, previous CTC, marks, experience, and current CTC. City and college data were categorized into tiers (tier 1, tier 2, and tier 3) to simplify and standardize these attributes. The data preprocessing phase involved filling missing values, removing duplicates, and creating dummy variables for categorical columns to make the data suitable for machine learning models. Outliers were identified and handled using the interquartile range (IQR) method to improve data quality and robustness.

To identify significant predictors for the target variable, a correlation matrix was used to select independent variables with a strong relationship to salary. The dataset was then split into training and testing sets in an 80:20 ratio. Various regression models were applied, including Linear Regression, Ridge Regression, Lasso Regression, Random Forest, Gradient Boosting, AdaBoost, and XGBoost. Each model was trained and fine-tuned to optimize predictive performance.

The models were evaluated using adjusted R² scores, and mean square error, which measure predictive accuracy while accounting for the complexity of the model. The comparison revealed the best-performing algorithm for predicting salaries of newly hired employees. This approach demonstrated the effective use of machine learning techniques, from data preprocessing to model selection, providing insights into salary determinants and enabling the organization to make data-driven decisions for recruitment.
