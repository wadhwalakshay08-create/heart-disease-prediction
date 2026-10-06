# Heart Disease Prediction

A Machine Learning project that predicts the presence of heart disease using patient health-related data.

## Project Overview

The goal of this project is to use Machine Learning to predict whether a patient is likely to have heart disease based on different health and clinical features.

The project includes data preprocessing, feature scaling, Random Forest Classification, model evaluation, and user input-based prediction.

## Dataset

The dataset contains health-related features such as:

- Age
- Gender
- Chest Pain Type
- Resting Blood Pressure
- Cholesterol
- Fasting Blood Sugar
- Resting ECG
- Maximum Heart Rate
- Exercise Induced Angina
- ST Depression
- ST Slope
- Major Vessels
- Thalassemia

Target variable:

- `Heart_Disease`

## Machine Learning Workflow

1. Load the dataset
2. Explore the data
3. Handle missing values
4. Remove duplicate records
5. Prepare the features and target
6. Split the dataset into training and testing sets
7. Apply StandardScaler
8. Train the Random Forest Classifier
9. Evaluate the model
10. Generate classification results
11. Make predictions using user input

## Model Used

### Random Forest Classifier

Random Forest is an ensemble Machine Learning algorithm that combines multiple decision trees to make predictions.

It was used to classify whether the given patient data indicates the presence of heart disease.

## Model Performance

- Test Accuracy: **85%**

The model achieved an accuracy of approximately 85% on the test data.

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- StandardScaler
- Random Forest Classifier

## Key Features

- Data loading and exploration
- Data preprocessing
- Handling missing values
- Feature scaling
- Random Forest model training
- Model evaluation
- Classification report
- Confusion matrix
- User input-based prediction

## Project Structure

```text
heart-disease-prediction/
│
├── Heart Disease Prediction.ipynb
├── heart_readable_columns.csv
└── README.md
