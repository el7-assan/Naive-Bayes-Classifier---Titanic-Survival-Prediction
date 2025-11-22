# Naive-Bayes-Classifier---Titanic-Survival-Prediction
This simple project applies Naive Bayes classification to the famous Titanic dataset to predict passenger survival based on features such as passenger class, age, fare, and gender.
It demonstrates a complete machine learning workflow, including data cleaning, feature encoding, training, and evaluation.

  Tools & Libraries:

Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

  Key Concepts:

Data preprocessing (dropping irrelevant columns, handling missing values)

Encoding categorical data using LabelEncoder

Feature-target separation (X and y)

Splitting the dataset into training and testing subsets

Training a Gaussian Naive Bayes model

Model evaluation based on the number of mislabeled predictions

 Data Preprocessing Steps

1 Removed irrelevant columns: PassengerId, Name, Ticket, Cabin, Embarked, etc.
2 Converted the Sex column to numeric using LabelEncoder.
3️ Filled missing values in the Age column with the mean age.
4️ Split data into x_train, x_test, y_train, and y_test.
