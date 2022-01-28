# Titanic---Survival-Predictions
A predictive machine learning model is used to find the likelihood of a passenger's survival based on ticketed information - name, age, gender, socio-economic class, cabin, etc.
Data used:
1. 'Train.csv' contains the details of a subset of the passengers on board (891 to be exact) and importantly, will reveal whether they survived or not, also known as the “ground truth”.
2. 'Test.csv' dataset contains similar information but does not disclose the “ground truth” for each passenger. The ML model will predict these outcomes.

A few hypotheses are tested to understand how certain features may impact predictions:
1. Is the gender of a passenger linked to their survival?
2. Does their class of travel increase their likelihood to survive?

Multiple classification algorithms are used (k-nearest neighbours classifier, Decision Tree classifier, Random Forest classifier, Gaussian Naive Bayes classifier, Support vector machine) and each model is scored on prediction accuracy. The model with the highest accuracy is chosen to make survival predictions on unseen data, eg. Kaggle competition https://www.kaggle.com/c/titanic
