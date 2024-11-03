# customer_churn_telecom
The telecommunications (telecom) sector in India is rapidly changing, with more and more telecom businesses being created and many customers deciding to switch between providers. "Churn" refers to the process where customers or subscribers stop using a company's services or products. Understanding the factors that influence keeping a customer as a client in predicting churn is crucial for telecom companies to enhance their service quality and customer satisfaction. As the data scientist on this project, you aim to explore the intricate dynamics of customer behavior and demographics in the Indian telecom sector in predicting customer churn.

-> "telecom_demographics.csv" contains information related to Indian customer demographics
-> "telecom_usage.csv" contains information about the usage patterns of Indian customers

The goal is to find out which model produces higher accuracy predicting the customer churn: Logistic Regression or Random Forest.

Tasks:
1. Load the two CSV files into separate DataFrames. Merge them into a DataFrame named churn_df. Calculate and print churn rate, and identify the categorical variables in churn_df.
2. Convert categorical features in churn_df into features_scaled. Perform feature scaling separating the appropriate features and scale them. Define your scaled features and target variable for the churn prediction model.
3. Split the processed data into training and testing sets giving names of X_train, X_test, y_train, and y_test using an 80-20 split, setting a random state of 42 for reproducibility.
4. Train Logistic Regression and Random Forest Classifier models, setting a random seed of 42. Store model predictions in logreg_pred and rf_pred.
5. Assess the models on test data. Assign the model's name with higher accuracy ("LogisticRegression" or "RandomForest") to higher_accuracy.
