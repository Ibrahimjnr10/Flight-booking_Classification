# Flight-booking_Classification
Building a 'Predictive Model' for classifying Customers bookings using various machine learning algorithms.

# Project Overview
This project aims to build a predictive model for classifying customer bookings using various machine learning algorithms. The dataset used is customer_booking.csv, which contains various features related to customer bookings. The primary goal is to accurately predict the booking_complete status.

Prerequisites
-Python 3.6 or higher
The following Python packages:
-pandas
-numpy
-matplotlib
-seaborn
-scikit-learn
-ydata_profiling
-Installation
To install the required packages, you can use pip:

!pip install pandas numpy matplotlib seaborn scikit-learn ydata_profiling
Usage

Load the dataset:
data = pd.read_csv('customer_booking.csv', encoding='latin')

# Data Cleaning and Preprocessing:

-Remove duplicates
-Handle outliers in purchase_lead and length_of_stay
-Convert flight_day to integers representing days of the week

# Model Training:

-Split the dataset into training and testing sets
-Use various classifiers including Logistic Regression, Decision Tree, Voting Classifier, and Random Forest
-Evaluate models using cross-validation
-Selecting best model

# Model Evaluation:

-Calculate accuracy and F1 score
-Display confusion matrix and ROC curve

#Example

# Assuming all necessary libraries and data are already loaded
pipe = make_pipeline(transformer, models['Random_forest'])
pipe.fit(X_train, y_train)
y_pred = pipe.predict(X_test)
train_score = pipe.score(X_train, y_train)
accuracy = accuracy_score(y_test, y_pred)
f1 = f1_score(y_test, y_pred)
print(f'Train score: {train_score}')
print(f'Accuracy: {accuracy}')
print(f'F1 score: {f1}')
