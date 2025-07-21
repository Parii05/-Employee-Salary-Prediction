# Salary Prediction Project

This project aims to predict employee salaries based on features such as age, gender, education level, job title, and years of experience. It uses machine learning models including Linear Regression and XGBoost Regressor.

## Dataset

- The dataset contains 375 entries with 6 features:
  - Age
  - Gender
  - Education Level
  - Job Title
  - Years of Experience
  - Salary (target variable)

## Project Overview

1. **Data Exploration**:  
   Visualized salary distribution and relationships between salary and features like education, gender, and years of experience.

2. **Data Preprocessing**:  
   - Handled missing values by dropping rows with nulls.  
   - Converted categorical variables into numeric format using Label Encoding.  
   - Standardized numerical features using StandardScaler.

3. **Model Training and Evaluation**:  
   - Trained a Linear Regression model and evaluated it using Mean Squared Error (MSE) and R² score.  
   - Trained an XGBoost Regressor model and evaluated it with the same metrics.  
   - XGBoost showed better performance in predicting salaries.
