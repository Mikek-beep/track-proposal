# Lesson 3.3 - Finding Important Features - sample exercise 

### Objectives
1. Learn to apply `feature_importances_` attribure
2. Interpret feature's importance results and apply to real-life business challenge


### Context
Sklearn instance of Random forest has the `feature_importances_` attribute that returns an array of each feature's importance to predict your dependent variable. It's hard to overestimate how useful this is to interpret and tweak your model, but also to draw insights from your data! In this exercise, using data from several marketing projects, we will train a random forest model like we did in previous exercises and will determine the features that most significantly affect our target variable - the project revenue in our case!   

### Instructions:
1. From sklearn.cross_validation import train_test_split
2. Create a test set with 30% of your data. In this exercise data is already scaled for you
3. Fit train data to the Random Forest Regressor using 100 trees in the forest 
4. Create a pandas series with the most important features 
5. Plot the features sorted based on their importance. Use vertical barplot with red colour and don't forget to add a title to your plot

```python

# Split your data in train and test sets
from ____ import _____
X_train, X_test, y_train, y_test = train_test_split(X, y, ____ = ____, random_state = 1)

# Random forest
from sklearn.ensemble import RandomForestRegressor
rf =RandomForestRegressor(______ = ______, random_state=1)
rf = rf.___(X_train,y_train)

# Calculate feature importances
f_importances = pd.Series(data=rf.____, index= X_train.____)

# Sort importances
f_importances_sorted = f_importances.sort_values()

# Dra of importances_sorted
f_importances_sorted.plot(kind=____, color=______)
plt.____('Features Importances')
plt._____()

```
### Single choice test
Based on the results, which feature affects the marketing project revenue the most?
* Project lead
* Marketing tool
* Customer industry
