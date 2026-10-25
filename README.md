# diabetes-prediction

Predicting whether a person has diabetes from health and demographic data, using Python and scikit-learn.

## Dataset

Diabetes prediction dataset from Kaggle. Columns: gender, age, hypertension, heart disease, smoking history, BMI, HbA1c level, blood glucose level and diabetes (the target).

## What I did

- Explored the data with histograms, count plots and a correlation heatmap
- Encoded the text columns and split the data into train and test sets
- Trained three classifiers: Random Forest, KNN and Logistic Regression
- Compared them using precision, recall and F1, because most people in the data do not have diabetes

## Conclusion

- HbA1c level and blood glucose level were the most important predictors. These are the measures used to diagnose diabetes.
- Age and BMI are risk factors associated with a higher chance of diabetes.
- Hypertension, smoking history, heart disease and gender contributed much less.
