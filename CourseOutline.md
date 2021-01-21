# Case study: Building Project analytics and revenue prediction models in Python 

## 1. Exploring the data

### Lesson 1.1 - Introduction to the problem
Learning objective: Using the pre-imported sample datasets remind the student about the key types of business metrics. 
Some functions and packages used: `pandas`, `numpy`

### Lesson 1.2 - Exploring the data
Learning objective: Introduce the student to the datasets. Clean up and merge the data. Using pandas aggregation and summary functions.
Some functions and packages used: `pd.merge()`, `DataFrame.info`, `DataFrame.describe`, `map()` + lambda functions 

### Lesson 1.3 - Defining the challenge
Learning objective: Analyse and visualise the cleaned up data. Define the business challenge
Some functions and packages used: `seaborn`, `matplotlib`

## 2. Introduction to regression models

### Lesson 2.1 - Introduction to linear regression
Learning objective: Familiarise with the key concepts of machine learning algorithms: classification and regression. Introduce linear regression, dependent and independent variables.
Some functions and packages used: `scikit-learn`, `LinearRegression`

### Lesson 2.2 - Train and evaluate linear regression model 
Learning objective: Perform basic regression model evaluation: test/train split, MAE, MSE
Some functions and packages used: `sklearn.model_selection`, `train_test_split`, `.fit()`, `.predict()`, `metrics.mean_absolute_error`, `metrics.mean_squared_error`

### Lesson 2.3 - Decision tree for regression 
Learning objective: Train basis regression model using random forest algorithm
Some functions and packages used: `sklearn.tree`, `DecisionTreeRegressor`

### Lesson 2.4 - Evaluate the model error
Learning objective: Evaluate random tree model performance, compare with linear regression
Some functions and packages used: `metrics.mean_squared_error`

## 3. Improving your model

Lesson 3.1 - Bagging
Learning objective: Familiarise with ensemble algorithms for machine learning.
Some functions and packages used: `BaggingClassifier`, `DecisionTreeClassifier`, `sklearn.ensemble.BaggingRegressor`, `sklearn.tree.DecisionTreeRegressor`

Lesson 3.2 - Random forests 
Learning objective: Enhance student's model performance by using random forests algorithm
Some functions and packages used: `sklearn.ensemble.RandomForestRegressor`, `RandomForestClassifier`

Lesson 3.3 - Finding Important Features
Learning objective: Evaluate importance of certain independent variable on the dependent variable. Interpret that from business perspective.
Some functions and packages used: `feature_importances_`, `matplotlib`

Lesson 3.4 - Evaluate the optimal forest 
Learning objective: Evaluate the new model 
Some functions and packages used: `metrics.mean_squared_error`, `sklearn.metrics.accuracy_score`, `sklearn.metrics.roc_curve`

## 4. Bringing it all together

Lesson 4.1 - Training the model on the projects dataset 
Learning objective: Apply the acquired skills to train the model on the main course dataset
Some functions and packages used: `sklearn.ensemble.RandomForestRegressor`, `RandomForestClassifier`

Lesson 4.2 - Evaluating the model
Learning objective: Apply the new skills to evaluate the model performance
Some functions and packages used: `metrics.mean_squared_error`, `sklearn.metrics.accuracy_score`, `sklearn.metrics.roc_curve`

Lesson 4.3 - Enterpeting the results - what makes a project successful?
Learning objective: Analyse the data and the machine learning algorithm predictions and important features. Suggest improvements for business.
Some functions and packages used: `seaborn.regplot`, `seaborn.pairplot`, `matplotlib.pyplot`, `feature_importances_`

Lesson 4.4  - Next steps!
Learning objective: Summarise the course results. Discover other machine learning algorithms and metrics that were not covered in this course.
