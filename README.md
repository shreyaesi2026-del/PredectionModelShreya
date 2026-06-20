# Heart Disease Prediction System

## Project Overview

This project uses Machine Learning to predict whether a person has heart disease or not based on medical parameters such as age, sex, chest pain type, blood pressure, cholesterol level, maximum heart rate, and other health indicators. The model is developed using the Random Forest Classifier algorithm.

## Technologies Used

* Python
* NumPy
* Pandas
* Scikit-learn
* Google Colab / Jupyter Notebook

## Dataset

The project uses the Heart Disease Dataset containing medical information of patients and their heart disease status.

## Methodology

### 1. Importing Required Libraries

The necessary Python libraries are imported for data manipulation, preprocessing, model training, and evaluation.

### 2. Data Collection

The heart disease dataset is loaded into the project environment for analysis and prediction.

### 3. Data Understanding and Exploration

The dataset is examined using functions such as `head()`, `info()`, and `describe()` to understand its structure, dimensions, data types, and statistical properties.

### 4. Data Preprocessing

The dataset is cleaned by removing duplicate records and handling missing values to improve data quality and model performance.

### 5. Label Encoding

Categorical features are converted into numerical values using Label Encoding. This enables the machine learning algorithm to process categorical data effectively.

Example:

* Male → 1
* Female → 0

### 6. Feature and Target Selection

Input attributes are separated from the target variable. The medical parameters act as features, while the heart disease status acts as the target.

### 7. Data Splitting

The dataset is divided into training and testing sets for model development and evaluation.

### 8. Model Training

A Random Forest Classifier is trained using the training dataset to learn patterns associated with heart disease.

### 9. Model Evaluation

The trained model is evaluated using accuracy metrics on the testing dataset to assess its prediction capability.

### 10. Prediction

New patient data is provided to the model, and the system predicts whether the patient has heart disease or not.

### 11. Result Generation

The final prediction result is displayed based on the patient's medical information.

## Features

* Data cleaning and preprocessing
* Label Encoding for categorical data
* Machine Learning-based prediction
* Random Forest Classifier
* Model accuracy evaluation
* Heart disease prediction for new patient data

## Conclusion

This project demonstrates the application of Machine Learning in healthcare. By analyzing patient health parameters, the system can predict the likelihood of heart disease and assist in early detection, diagnosis support, and informed healthcare decision-making.
# Wine Quality Prediction System

## Project Overview

This project uses Machine Learning to predict the quality of wine based on its physicochemical properties such as acidity, sugar content, chlorides, sulphates, alcohol content, and pH value. The model is developed using the Random Forest Regressor algorithm.

## Technologies Used

* Python
* NumPy
* Pandas
* Scikit-learn
* Google Colab / Jupyter Notebook

## Dataset

The project uses the Wine Quality Dataset containing various chemical properties of wine along with its quality score.

## Methodology

### 1. Importing Required Libraries

The necessary Python libraries are imported for data manipulation, preprocessing, model training, and evaluation.

### 2. Data Collection

The wine quality dataset is loaded into the project environment for analysis and prediction.

### 3. Data Understanding and Exploration

The dataset is examined using functions such as `head()`, `shape()`, and `describe()` to understand its structure, dimensions, and statistical properties.

### 4. Data Preprocessing

The dataset is cleaned by handling missing values and preparing the data for model training.

### 5. Missing Value Handling

Missing values in the dataset are replaced using the median value of the respective column to improve data quality and maintain consistency.

### 6. Outlier Removal

Outliers in the quality column are identified and removed using the Interquartile Range (IQR) method. This helps reduce the impact of extreme values on model performance.

### 7. Feature and Target Selection

Input attributes are separated from the target variable. The physicochemical properties act as features, while wine quality acts as the target.

### 8. Feature Standardization

The input features are standardized using StandardScaler to ensure that all features are on a similar scale and contribute equally during model training.

### 9. Data Splitting

The dataset is divided into training and testing sets for model development and evaluation.

### 10. Model Training

A Random Forest Regressor is trained using the training dataset to learn relationships between wine characteristics and quality scores.

### 11. Model Evaluation

The trained model is evaluated using the R² Score on both training and testing datasets to measure prediction performance.

### 12. Prediction

New wine data is provided to the model, and the system predicts the expected wine quality score.

### 13. Result Generation

The final predicted wine quality score is displayed based on the input parameters.

## Features

* Data cleaning and preprocessing
* Missing value handling
* Outlier detection and removal
* Feature standardization using StandardScaler
* Machine Learning-based prediction
* Random Forest Regressor
* Model evaluation using R² Score
* Wine quality prediction for new samples

## Conclusion

This project demonstrates the application of Machine Learning in quality assessment. By analyzing various physicochemical properties of wine, the system can accurately predict wine quality. Data preprocessing techniques such as missing value handling, outlier removal, and feature standardization help improve model performance and prediction accuracy. 


# Diabetes Prediction System

## Project Overview

This project uses Machine Learning to predict whether a person is diabetic or non-diabetic based on medical parameters such as glucose level, blood pressure, BMI, insulin level, and age. The model is developed using the Support Vector Machine (SVM) algorithm.

## Libraries Used

* Python
* NumPy
* Pandas
* Scikit-learn

## Dataset

The project uses the Diabetes Dataset containing medical information of patients and their diabetes status.

## Steps to train the model

### 1. Importing Required Libraries

The necessary Python libraries are imported for data manipulation, preprocessing, model training, and evaluation.

### 2. Data Collection

The diabetes dataset is loaded into Google colab and read using pd.read_csv()

### 3. Data Understanding and Exploration

The dataset is examined to understand its structure, dimensions, data types, and statistical properties.

### 4. Data Preprocessing

The dataset is organized and prepared for training. The values are scaled so that all features can be used by machine learning model.

### 5. Feature and Target Selection

Input attributes are separated from the target variable. The medical parameters act as features, while the diabetes outcome acts as the target.

### 6. Data Splitting

The dataset is divided into training and testing sets for model development and evaluation.

### 7. Model Training

A Support Vector Machine (SVM) classifier is trained using the training dataset to learn patterns associated with diabetes.

### 8. Model Evaluation

The trained model is evaluated using accuracy metrics on both training and testing datasets.

### 9. Prediction

New patient data is provided to the model, and the system predicts whether the patient is diabetic or non-diabetic.

### 10. Result Generation

The final prediction result is displayed based on the patient's medical information.


## Conclusion

This project demonstrates the application of Machine Learning in healthcare. By analyzing patient health parameters, the system can predict diabetes and assist in early detection and decision-making.








# House Price Prediction System

## Project Overview
This project uses Machine Learning to predict house prices based on various features such as area, number of bedrooms, bathrooms, stories, age of the house, and other property-related attributes.

## Technologies Used
- Python
- NumPy
- Pandas
- Scikit-learn

## Dataset
The project uses a house price dataset containing information about different houses and their selling prices.

## Workflow

### 1. Importing python libraries
Before working with the dataset,the python libraries needed for data handling, visualization, preprocessing, model training, and evaluation are imported in colab.These libraries provide the tools required to analyze the dataset and build the prediction model.

### 2. Data Collection
The house price dataset is loaded into the system. The dataset contains information about various houses, including their features and corresponding prices.In this dataset the target feild is house prices which are going to be predicted by the model based on different parameters

### 3. Understanding the Data
The dataset is explored to understand its structure and the information it contains using head(),describe() and various other functions.This helps in identifying the important characteristics of the data before building the model.

### 4. Data Preparation
The dataset is prepared for machine learning by handling missing values and removing inconsistencies. Outliers are identified and treated to reduce their impact on the model's performance and improve prediction accuracy.

### 5. Feature Selection
The important house details are chosen as input features, while the house price is selected as the target value.

### 6. Data Splitting

The dataset is divided into training and testing sets.The training set is used to teach the model, while the testing set is used to evaluate how well the model performs on unseen data.

### 7. Model training
A Random Forest Regression model is trained using the training dataset. The model learns the relationship between house features and their market value. During training, the model studies patterns in the historical data and learns how various factors affect house prices.

### 8. Evaluating Performance
The trained model is evaluated using performance metrics such as the R2 score. This helps determine how accurately the model can predict house prices.


### 9.Predicting New House Prices
New house information is entered in the form of a list. This list is converted into a suitable format for prediction and passed to the trained model, which then calculates the estimated house price.

### 10.Final outcome
The House Price Prediction System provides an estimated house price by combining data analysis and machine learning techniques.