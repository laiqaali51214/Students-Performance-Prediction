# Students-Performance-Prediction

## Overview
This project focuses on predicting students' academic performance using a dataset obtained from Kaggle. The dataset contains various features related to students' demographics, family background, and academic history. The goal is to analyze the data, preprocess it, and build a predictive model to estimate students' final grades (G3).

## Dataset
The dataset used in this project is titled "Student Performance Data" and is available on Kaggle. It includes 395 entries with 33 features, such as:

- **Demographics**: School, gender, age, address, family size, parents' cohabitation status.
- **Academic Background**: Mother's and father's education, mother's and father's job, reason for choosing the school, guardian, travel time to school, weekly study time, past failures, school support, family support, extra paid classes, extracurricular activities, nursery attendance, desire for higher education, internet access, romantic relationship, family relationship quality, free time after school, going out frequency, workday alcohol consumption, weekend alcohol consumption, health status, absences.
- **Grades**: First period grade (G1), second period grade (G2), final grade (G3).

## Project Steps
1. **Data Importing and Unzipping**:
   - The dataset is downloaded from Kaggle and unzipped for use in the project.

2. **Importing Necessary Libraries**:
   - Essential libraries such as NumPy, Pandas, Seaborn, Matplotlib, and Scikit-learn are imported for data manipulation, visualization, and model building.

3. **Loading and Understanding the Data**:
   - The dataset is loaded into a Pandas DataFrame, and initial exploration is conducted to understand the structure and features of the data.

4. **Data Preparation and Cleaning**:
   - **Missing Values**: The dataset is checked for missing values.
   - **Duplicate and Low Variation Data**: Duplicate rows and columns with low variation are identified and handled.
   - **Incorrect and Irrelevant Data**: Any incorrect or irrelevant data is addressed.
   - **Categorical Data**: Categorical features are encoded using LabelEncoder.
   - **Outliers**: Outliers are identified and managed.
   - **Feature Scaling**: Features are scaled to ensure uniformity.
   - **Feature Engineering/Selection**: Relevant features are selected or engineered for the model.
   - **Validation Split**: The dataset is split into training and testing sets.

5. **Exploratory Data Analysis (EDA)**:
   - Various visualizations are created to understand the relationships between different features and the target variable (G3).

6. **Model Building**:
   - A Linear Regression model is built using the training data.
   - The model is evaluated using metrics such as Mean Squared Error (MSE) and R-squared (R2) score.

7. **Cross-Validation**:
   - K-Fold cross-validation is performed to assess the model's performance.

8. **Model Evaluation**:
   - The model's performance is evaluated on the test set, and the results are analyzed.

9. **Visualization of Results**:
   - The results are visualized to provide insights into the model's predictions.

## Requirements
- Python 3.x
- Libraries: NumPy, Pandas, Seaborn, Matplotlib, Scikit-learn


## Results
The project aims to build a predictive model that can estimate students' final grades based on various features. The model's performance is evaluated using metrics such as MSE and R2 score, and the results are visualized to provide insights.
