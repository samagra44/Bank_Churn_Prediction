# Bank_Churn_Prediction
The aim of this project to analyze the bank customer's demographics and financial information which inculdes customer's age, gender. country, credit score, balance and many others to predict whether the customer will leave the bank or not.

About the dataset
The dataset is taken from Kaggle. It contains 10000 rows and 14 columns. The objective of the dataset is to predict whether the customer will leave the bank or not, based on the customer's demographics and financial information included in the dataset.
The dataset has several factors that can influence the customer to leave the bank, which are termed as independent variables. The target variable is the customer's decision to leave the bank, which is termed as dependent variable.

# Conclusion
From the exploratory data analysis, I have concluded that the churn count of the customersdepends upon the following factors:

->Age
->Geography
->Tenure
->Balance
->Number of Products
->Has Credit Card
->Is Active Member
Coming to the classification models, I have used the following models:

->Decision Tree Classifier
->Random Forest Classifier
Both the models were hyperparameter tuned using GridSearchCV. Both the models have nearly equal accuracy score. But, the Random Forest Classifier has a better accuracy and precision score than the Decision Tree Classifier.

