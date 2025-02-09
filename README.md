# Diabetes-Prediction

Overview
This project focuses on predicting whether a person has diabetes based on various medical features, such as glucose levels, BMI, age, and more. The goal is to create a machine learning model that can accurately predict the likelihood of diabetes for individuals, helping healthcare professionals with early detection and prevention strategies.

Project Objective
The primary objective of this project is to build and evaluate a Logistic Regression model that predicts diabetes status based on patient data. The model will be trained using historical medical records and tested for performance based on accuracy, precision, recall, and other evaluation metrics.

Data
The dataset used in this project contains various medical attributes that are commonly associated with diabetes risk. The columns include:

Pregnancies: Number of pregnancies
Glucose: Plasma glucose concentration
BloodPressure: Diastolic blood pressure
SkinThickness: Thickness of the skin fold
Insulin: Insulin level
BMI: Body mass index
DiabetesPedigreeFunction: A function indicating family history of diabetes
Age: Age of the patient
Outcome: Target variable (1 = Diabetic, 0 = Non-Diabetic)
Approach
The data is preprocessed to handle missing values and scale numerical features.
We use Logistic Regression as the machine learning algorithm to classify patients into diabetic and non-diabetic categories.
To address class imbalance in the dataset, class weights are used to improve model performance.
Model performance is evaluated using standard metrics such as accuracy, precision, recall, and F1-score.
Key Results
The trained model achieved an accuracy of 73%, demonstrating its ability to predict diabetes status effectively. Further evaluation using precision, recall, and F1-score helped assess the model’s performance in distinguishing between diabetic and non-diabetic cases.

