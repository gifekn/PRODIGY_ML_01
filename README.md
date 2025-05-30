PRODIGY_ML_01
Implement a linear regression model to predict the prices of houses based on their square footage and the number of bedrooms and bathrooms

Project Overview:
This project involves implementing and evaluating a Linear Regression model to predict house prices based on key features such as square footage, number of bedrooms, and number of bathrooms. 

Dataset
GrLivArea (Above ground living area in square feet)

BedroomAbvGr (Number of bedrooms above ground)

FullBath and HalfBath (Used to calculate TotalBaths)

SalePrice (Target variable)

Source:https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data

Files Included:

train.csv – Training data containing features and target values (sale prices)

data_description.txt – Detailed explanation of each feature

sample_submission.csv – Template for submission of predictions


Technologies & Libraries Used
Python – Core programming language
Pandas – Data manipulation and preprocessing
NumPy – Numerical operations
Matplotlib – Data visualization
Seaborn – Statistical plotting
scikit-learn – Implementation of machine learning models and metrics

Methodology
Selected features: GrLivArea, BedroomAbvGr, FullBath, HalfBath
Created a new feature: TotalBaths = FullBath + 0.5 × HalfBath
Dropped the original FullBath and HalfBath columns

Inspected missing values and feature distributions

Data Splitting

Model Training

Model Evaluation
Metric	Value
R-squared Score	0.505
Mean Squared Error	3.42 × 10⁹
Root Mean Squared Error	58,440.87

This indicates the model explains roughly 50.5% of the variance in house prices,in house prices is explained by the model based on the selected features.

Conclusion
This project demonstrates a foundational application of Linear Regression for predictive modeling in real estate.
