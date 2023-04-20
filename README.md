# Descision-Tree-on-fraud_check
This is a Python code for building and evaluating decision tree models using the scikit-learn library. The code starts by importing the necessary libraries, including pandas, numpy, scikit-learn's decision tree classifier, train_test_split, classification_report, accuracy_score, confusion_matrix, and matplotlib.

Next, the code reads in a CSV file containing data on taxable income and various other features. The taxable income column is then converted to a categorical variable, where any income less than or equal to 30,000 is classified as "Risky" and anything above is classified as "Good". The pandas get_dummies function is then used to convert the categorical variables in the dataset into dummy variables.

The data is split into training and testing sets, and a decision tree classifier is built using the entropy criterion. The model is then fit on the training data, and the resulting decision tree is plotted using matplotlib. Predictions are made on the test set, and the model's performance is evaluated using classification_report, accuracy_score, and confusion_matrix.

The code also builds a decision tree classifier using the Gini criterion and evaluates its performance on the test set. Finally, a decision tree regression model is built using the same dataset and evaluated using mean_squared_error, mean_absolute_error, and r2_score.

In summary, this code demonstrates how to build and evaluate decision tree models using scikit-learn, including both classification and regression problems.
