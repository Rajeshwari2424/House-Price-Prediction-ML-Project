# House-Price-Prediction-ML-Project
This project predicts house prices based on features like area, bedrooms, bathrooms, and floor number. It involves data cleaning, exploratory data analysis, and comparing three regression models, Linear Regression, Ridge Regression, and Random Forest, with Random Forest giving the best performance.

🏠 House Price Prediction Using Machine Learning
📌 Problem Statement

The goal of this project is to build a regression model that predicts residential property prices based on structural and location-related features. This can assist buyers, sellers, and real estate analysts in estimating fair market value.

📊 Dataset Overview

964 property records

20 original features

Included numerical and categorical variables

Contained missing values and text-based numerical fields

🛠 Tools & Technologies

Python

Pandas

NumPy

Matplotlib / Seaborn

Scikit-learn

🔎 Data Cleaning & Feature Engineering

Removed irrelevant text-heavy columns

Extracted numeric values from text-based area field

Handled missing values using median imputation

Applied one-hot encoding to categorical features

🤖 Models Trained

Linear Regression

Decision Tree Regressor

Random Forest Regressor

📈 Model Evaluation
Model	R² Score	MAE	MSE
Linear Regression	0.368154146057574	2.4586873122083692	3.1929196084793996
Decision Tree	0.3681500311216237	2.4586592365181423	3.1929300055075753
Random Forest	0.6294187668207185	1.6255678176659263	2.4452548278379584

(Random Forest performed best.)

🔥 Key Insights

Property area(Society) is the strongest predictor of price.

Independent houses generally command higher prices.

Non-linear relationships exist between features and price.

📌 Conclusion

Random Forest achieved the highest predictive performance, indicating complex relationships in the housing dataset. Feature importance analysis revealed that size and structural attributes.
