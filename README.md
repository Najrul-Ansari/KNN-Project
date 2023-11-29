# Prediction with Regression

## iPhone Purchase Prediction
Project 5 - iphone_prj5
Iphone Purchases are getting increased day by day and many stores wants to predict whether a customer will purchase an Iphone 
from thier store given their gender, age and salary.
+ Dataset name - iphone_purchase_records.csv

+ Objective  - Whether Customer will purchase or not

+ Tools - Python code in Jupyter notebook, Tableau for vizualization, Powerpoint, Excel.

+ Tableau Dashboard - https://public.tableau.com/app/profile/najrul.ansari/viz/iphonepurchasedashboard/Dashboard1?publish=yes

+ Algorithm Used- KNeighborsClassifier, Decision Tree, Random Forest, LogisticRegression.

  + KNeighborsClassifier - KNeighborsClassifier is a classification algorithm based on the K-Nearest Neighbors (KNN) approach. 
It is part of the scikit-learn library in Python and is used for solving classification problems. 
KNN is a simple and intuitive algorithm that classifies a new data point based on the majority class of its k-nearest neighbors in the feature space.

  + Decision Tree - A decision tree is a supervised machine learning algorithm used for both classification and regression tasks. 
It works by recursively partitioning the dataset into subsets based on the values of different features. 
The objective is to create a tree-like structure of decisions, where each node represents a decision based on a particular feature, 
and each leaf node represents the predicted outcome.

  + Random Forest - A Random Forest is an ensemble learning method that operates by constructing a multitude of decision trees during training and 
outputting the class that is the mode of the classes (classification) or the mean prediction (regression) of the individual trees. 
It is a powerful and versatile machine learning algorithm known for its high accuracy and robustness.

  + LogisticRegression - Logistic Regression is a statistical method used for binary classification. 
Despite its name, it is a classification algorithm rather than a regression algorithm. 
It's commonly used in machine learning for predicting the probability that an instance belongs to a particular category.

+ Methodology:
  
  •	Data Collection - The data used to build the model was provided in the csv format. It has gender, age, salary and whether the said person purchased the phone or not in 1 and 0 
    format, where 1 stands for yes and 0 for no.

  •	Data Pre-processing - Data pre-processing is a crucial step to ensure the quality and suitability of the dataset for training machine learning models.

  •	Feature Selection - Feature selection is a critical step to identify the most relevant variables that contribute to the predictive power of the model.

  •	Model Selection - In the model selection section, provide a detailed overview of the machine learning algorithms chosen for the predictive analysis. Explain the rationale behind the 
    selection of each algorithm and discuss how they align with the project objectives.
  
  •	Model Training - In the model training section, the processed data is fit to train the selected model so that it is able to predict the future entered data.

  •	Model Evaluation - In the model evaluation section, the performance of the trained machine learning models is assessed to select the best suited model for deployment.



## Bangalore House Price Prediction
Project 6 - houseprice_prj6
+ Dataset name - bangalore house price prediction OHE-data.csv
+ Objective - Predict the Price of Bangalore House

+ Tools - Python code in Jupyter notebook, Tableau for vizualization, Powerpoint, Excel.

+ Tableau Dashboard - 

+ Algorith Used - KNeighborsRegressor, Linear Regression, Ridge, Lasso, Polynomial Regression.

  + KNeighborsRegressor - KNeighborsRegressor is a machine learning algorithm used for regression tasks. It is part of the scikit-learn library in Python and is based on the K-Nearest Neighbors (KNN) approach, similar to the KNeighborsClassifier for classification tasks. The KNN algorithm works by predicting the target variable of a new data point based on the average (or weighted average) of the target values of its k-nearest neighbors in the feature space.

  + Linear Regression - Linear Regression is a statistical method and a fundamental machine learning algorithm used for predicting a continuous outcome variable (also called the dependent variable) based on one or more predictor variables (independent variables). The relationship between the variables is assumed to be linear, meaning that a change in the predictor variables is associated with a linear change in the outcome.

  + idge - Ridge Regression, also known as Tikhonov regularization or L2 regularization, is a linear regression variant that introduces a regularization term to the standard linear regression objective function. The purpose of Ridge Regression is to prevent overfitting and handle multicollinearity, which occurs when predictor variables are highly correlated.

  + Lasso - Lasso Regression, short for Least Absolute Shrinkage and Selection Operator, is a linear regression technique that introduces a regularization term to the standard linear regression objective function. Like Ridge Regression, Lasso aims to prevent overfitting and handle multicollinearity in the presence of highly correlated predictor variables.

  + Polynomial Regression - Polynomial Regression is a type of linear regression in which the relationship between the independent variable (predictor variable) and the dependent variable is modeled as an nth-degree polynomial. It extends the simple linear regression model, allowing for a more flexible representation of the relationship between variables.
 
+ Methodology:
  
  •	Data Collection: The data used to build the model was provided in the csv format. It has different columns such as price, price per square foot, location, availability, area type, 
    number of bedrooms and bathrooms, etc.

  •	Data Pre-processing: Data pre-processing is a crucial step to ensure the quality and suitability of the dataset for training machine learning models. Checked for missing values.         Handled categorical data (if any).

  •	Feature Selection: Feature selection is a critical step to identify the most relevant variables that contribute to the predictive power of the model.

  •	Model Selection: In the model selection section, provide a detailed overview of the machine learning algorithms chosen for the predictive analysis. Explain the rationale behind the      selection of each algorithm and discuss how they align with the project objectives.  Used KNeighborsRegressor, Linear Regression, Ridge, Lasso, and Polynomial Regression.
  
  •	Model Training: In the model training section, the processed data is fit to train the selected model so that it is able to predict the future entered data. Split the dataset into        training and testing sets. Trained each model on the training set.

  •	Model Evaluation: In the model evaluation section, the performance of the trained machine learning models is assessed to select the best suited model for deployment. Evaluated the       models using accuracy, precision, recall, and F1-score.
 

