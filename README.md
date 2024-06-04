# Salary Prediction Model for New Hires

## Project Overview:
The Salary Prediction Model for New Hires aims to accurately predict the starting salary of new employees based on a variety of factors using advanced regression techniques. The model leverages multiple datasets and incorporates multiple regression models including Simple Linear Regression, Multi-Linear Regression, Ridge Regression, Lasso Regression, and Ensemble Learning techniques. The performance of these models will be evaluated using several metrics such as R Squared Score, Mean Squared Error (MSE), Mean Absolute Error (MAE), and Root Mean Squared Error (RMSE).

## Datasets:
### Cities Dataset:
This dataset includes a list of cities categorized into metro and non-metro cities. This categorization helps in understanding the geographical impact on salary variations.

### Colleges Dataset:
This dataset consists of a list of colleges classified into Tier 1, Tier 2, and Tier 3 institutions. The tier classification helps in determining the influence of educational background on the salary.

### Employees Dataset:
This dataset contains detailed information about employees, including their educational background, city of employment, job role, previous salary (CTC), previous job changes, graduation marks, total experience in months, and current salary (CTC).

#### Fields:
College Name, City, Role, Previous CTC, Previous Job Changes, Graduation Marks, Experience in Months, Current CTC

## Model Development:
The development of the salary prediction model involves several steps:

### Data Preprocessing:
Cleaning and merging the datasets based on common fields such as College Name and City. Handling missing values, encoding categorical variables (e.g., Metro/Non-Metro, College Tiers), and normalizing numerical features.

### Feature Engineering:
Creating new features that could improve model performance, such as combining Experience and Graduation Marks, or encoding the number of job changes. Model Training and Selection:

### Implementing various regression models:
#### Simple Linear Regression:
Linear Regression is a fundamental and widely used statistical and machine learning model that's employed to find a linear relationship between one or more independent variables (features) and a dependent variable (target). The model estimates the coefficients of the linear equation that represents the best relationship.

#### Multi-Linear Regression:
Multiple Linear Regression is an extension of the simple linear regression model. This model is designed to find a linear relationship between a dependent variable and twao or more independent variables by fitting a linear equation to the observed data. It is used to understand and predict how changes in multiple predictors affect the target variable.

#### Ridge Regression:
Ridge Regression is traditional linear regression model that aims to find a linear relationship between a dependent variable and multiple independent variables while minimizing the sum of squared errors just like in multiple linear Regression. However, it adds a regularization term to the optimization objective. It is also used to prevent overfitting and improve the stability of the model. It is particularly useful when dealing with high-dimensional datasets where multicollinearity is present.

#### Lasso Regression:
Lasso Regression which stands for Least Absolute Shrinkage and Selection Operator. It is a traditional linear regression model that aims to find a linear relationship between a dependent variable and multiple independent variables while minimizing the sum of squared errors just like in multiple linear Regression. However, it adds a regularization term with a unique property that encourages sparsity in the coefficient estimates. It is especially useful when dealing with high dimensional datasets where the feature selection is essential.

#### Decision Tree using Regression:
These Regression trees are designed to predict continuous numerical values rather than discrete class labels. The Regression Trees are hierarchial structure consisting of nodes and branches. The trees are constructed by recursively partitioning the data into subsets based on the values of the independent variables, with the goal of minimizing the variance of the target variable within each partition.

#### Bagging:
Bagging stands for Bootstrap Aggregating, is an ensemble machine learning technique used to improve the performance and robustness of predictive models. It is particulary effective for reducing the variance of a model, making it less sensitive to noise in the data and increasing its predictive accuracy. It is a widely used technique in machine learning, and it can be applied to various types of base models, including decision trees, regression models, and classifiers.

#### Random Forest:
It is an ensemble machine learning technique that builds on the concept of bagging (Bootstrap Aggregating) and is primarily used for both classification and regression tasks. It is known for its high predictive accuracy, robustness, and resistance to overfitting. Random Forest is a widely used and versatile ensemble method in the field of machine learning.

#### Gradient Boosting:
Gradient Boosting is a powerful and versatile machine learning technique that falls under the category of ensemble learning methods. It is used for both classification and regression tasks and has gained widespread popularity due to its exceptional predictive performance. It is employed to build predictive models by combining the preditions of multiple weak learners in a sequential manner to create a strong and accurate ensemble model.

#### Ada Boosting:
Adaptive Boosting is a machine learning ensemble technique that is used to improve the performance of weak learners by combining them into a strong learner. Ada Boost is primarily used for both the classification and regression tasks, and it is one of the earliest and most influential boosting algorithms. The main objective of AdaBoost is to create a strong regressors in a way that focuses on the misclassified data points and assigning them more importance in the training process.

#### XGBoost Regressor:
XGBoost Regressor is designed to predict continuous numerical values based on the values of one or more independent variables. It is advanced implementation of the gradient boosting framework and is known for its accuracy, efficiency, and ability to handle complex regression problems.

## Model Evaluation:
Assessing the performance of each model using the following metrics:

### R Squared Score:
Measures the proportion of variance in the dependent variable that is predictable from the independent variables.

### Mean Squared Error (MSE):
The average of the squares of the errors, indicating the average squared difference between the estimated and actual values.

### Mean Absolute Error (MAE):
The average of the absolute errors, providing a measure of the average magnitude of the errors.

### Root Mean Squared Error (RMSE):
The square root of MSE, giving a measure of the standard deviation of the residuals.

## Project Goals:
To develop a robust model capable of accurately predicting the starting salary for new hires based on their background and experience. To understand the impact of various factors like educational institution, city, job role, and previous salary on the new salary. To provide insights to HR departments for better decision-making in the hiring process.

## Conclusion:
This project will culminate in a comprehensive salary prediction model that combines multiple datasets and leverages various regression techniques to deliver accurate salary predictions. The model's effectiveness will be validated through rigorous performance metrics, ensuring that it can be a valuable tool for organizations in making informed hiring and compensation decisions.
