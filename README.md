# Student Performance Prediction

## Overview

This project focuses on predicting student performance categories (**High**, **Medium**, and **Low**) using machine learning techniques. The goal is to analyze student-related factors and build a classification model capable of identifying performance levels accurately.

## Dataset

The dataset contains information related to students, including:

* Demographic attributes
* Learning preferences
* Mental state indicators
* Study habits
* Sleep patterns
* Social media usage
* Academic-related features

Target Variable:

* High
* Medium
* Low

## Project Workflow

### 1. Data Preprocessing

* Handling missing values using SimpleImputer
* Encoding categorical variables using OneHotEncoder
* Train-test split
* Feature transformation using ColumnTransformer and Pipeline

### 2. Exploratory Data Analysis (EDA)

* Distribution analysis
* Missing value inspection
* Feature relationship analysis
* Automated profiling using YData Profiling

### 3. Model Building

Model Used:

* Logistic Regression (Multiclass Classification)

Pipeline Components:

* Data preprocessing
* Feature encoding
* Classification model

### 4. Evaluation Metrics

The model was evaluated using:

* Accuracy Score
* Precision
* Recall
* F1 Score
* Confusion Matrix

## Results

Classification Report:

| Class  | Precision | Recall | F1-Score |
| ------ | --------- | ------ | -------- |
| High   | 0.93      | 0.82   | 0.87     |
| Low    | 0.97      | 0.97   | 0.97     |
| Medium | 0.91      | 0.96   | 0.93     |

Overall Accuracy:

93.8%

Confusion Matrix:

```text
[[ 75   0  17]
 [  0 222   8]
 [  6   6 266]]
```

Key Findings:

* High and Low performers were clearly separated.
* Most classification errors occurred between High and Medium categories.
* The model achieved strong overall performance with high precision and recall.

## Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Scikit-learn
* YData Profiling
* Jupyter Notebook

## Future Improvements

* Compare multiple machine learning models
* Perform hyperparameter tuning
* Add feature importance analysis
* Deploy the model as a web application

## Author

Uday Gupta
Aspiring Data Scientist | Machine Learning Enthusiast
