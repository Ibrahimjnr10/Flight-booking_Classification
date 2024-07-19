# Flight-booking_Classification
Building a 'Predictive Model' for classifying Customers bookings using various machine learning algorithms.

# Project Overview
This project aims to build a predictive model for classifying customer bookings using various machine learning algorithms. The dataset used is customer_booking.csv, which contains various features related to customer bookings. The primary goal is to accurately predict the booking_complete status.
# Objective
 Primary goal is to develop a machine learning model that can accurately predict the likelihood of booking completion

### Key Files
Customer_behaviour_prediction.: Script for bulding pridiction model algorithm.

Prerequisites
- Python 3.6 or higher
The following Python packages:
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- ydata_profiling
- Installation
To install the required packages, you can use pip:

!pip install pandas numpy matplotlib seaborn scikit-learn ydata_profiling
Usage

## Steps
### Load the dataset:
data = pd.read_csv('customer_booking.csv', encoding='latin')

### Data Cleaning and Preprocessing:

- Remove duplicates
- Handle outliers in purchase_lead and length_of_stay
- Convert flight_day to integers representing days of the week

### Model Training:

- Split the dataset into training and testing sets
- Use various classifiers including Logistic Regression, Decision Tree, Voting Classifier, and Random Forest
- Evaluate models using cross-validation
- Selecting best model

### Model Evaluation:

- Calculate accuracy and F1 score
- Display confusion matrix and ROC curve

## Link to the presentation
https://bit.ly/3SgPfu5

## Link to the documentation
https://bit.ly/4fbqERb

# Recommndation 
The Random Forest model, although having a high train score, shows signs of overfitting. The low F1 score indicates poor performance in predicting the minority class. Future work should focus on addressing class imbalance, possibly through techniques such as SMOTE, and further tuning model hyperparameters

# Conclusion
This project underscores the transformative potential of machine learning in predicting customer booking behavior. By leveraging advanced analytics, airlines can gain deeper insights into customer behavior, optimize their operational strategies, and enhance overall service quality. The ongoing focus will be on refining the model to handle class imbalance effectively, ensuring that predictions are both accurate and actionable.
By integrating data-driven approaches into their decision-making processes, airlines can not only improve customer engagement but also gain a competitive edge in an increasingly dynamic industry.


### How to Run
- Clone this repository.
- Install the required dependencies.
- Run the scripts for each project as described in their respective sections.
bash
- Copy code
- git clone <repository_url>
- cd <repository_name>
- pip install -r requirements.txt
- python <script_name.py>

License
This repository is licensed under the MIT License. See the LICENSE file for more details.
