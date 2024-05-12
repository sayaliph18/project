# ML - project
Goal: 
Build a Machine Learning (ML) model to predict whether users get defaulted or not.


The approach used in building a machine learning (ML) model typically involves several key steps:

Dataset contains sample loan data, sample user transaction, sample profile data

1)EDA: Exploratory Data Analysis (EDA) is a crucial initial step in the data analysis process, aimed at understanding the characteristics of the dataset and uncovering insights that may guide subsequent modeling decisions.

2)Data Preprocessing : This step involves gathering, cleaning, and preprocessing the data. It includes tasks such as handling missing values, encoding categorical variables, and splitting the data into training and testing sets.
first of all merge the dataset.

missing value:
For some column missing value greater than 50% hence we drop this irrelevant column.
for categorical column, place missing value using mode
For some rows has missing value hence we drop this irrelevant rows.

removing outliers:
Used mean imputation for removing outliers

For converting categorical column used label encoder and oneHot encoder.

Target column is replace with 0 and 1.

3)Feature Scaling : This is classification problem we used Standard Scaler

4)Feature Importance: For this SelectKBest with f_classif is used and only select 10 features out of 13 features.

4)Model Selection: We choose Logistic Regression, Random Forest, Support Vector Machine, Decision Tree, XGBoost. This involve experimenting with multiple algorithms and evaluating their performance using appropriate metrics.






