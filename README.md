# Healthcare Premium Prediction (Regression)

This project focuses on predicting annual healthcare premiums using demographic, lifestyle, and medical history data. It combines machine learning techniques, data visualization, and a user-friendly Streamlit app to deliver actionable insights.

Table of Contents
1) Project Overview
2) Key Features
3) Technologies Used
4) Dataset Description
5) Methodology
6) Streamlit App
7) Results
8) How to Run the Project
9) Future Enhancements

## Project Overview

The project aims to predict healthcare premiums for individuals using machine learning models. It emphasizes data preprocessing, feature engineering, and model evaluation to ensure accurate predictions.

### Objective
Predict annual premiums based on features like age, region, BMI category, employment status, and genetic risks.
Provide insights into factors influencing premiums to support decision-making in the healthcare insurance domain.

## Key Features
* Comprehensive Data Cleaning and Exploratory Data Analysis (EDA).
* Implementation of regression models: Linear Regression, Ridge, and Lasso.
* Interactive Streamlit App for real-time predictions.
* Detailed visualizations to understand trends and correlations.

## Technologies Used

* Programming Language: Python
* Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
* Deployment: Streamlit

## Dataset Description

The dataset includes features such as:

* Demographics: Age, Gender, Region, Marital Status
* Lifestyle Factors: BMI Category, Smoking Status, Employment Status
* Medical Information: Medical History, Genetic Risks
* Insurance Details: Income Level, Insurance Plan, Annual Premium Amount

#### Data Cleaning Steps

* Handling missing values and outliers.
* Standardizing and encoding categorical variables.

## Methodology

1) Data Preprocessing:
Handled missing values, outliers, and categorical encoding.
Created new features like genetic risk factors.

2) Exploratory Data Analysis (EDA):
Analyzed correlations and trends.
Visualized key factors affecting premiums.

3) Model Development:
Trained regression models: Linear Regression, Ridge, Lasso.
Used cross-validation and hyperparameter tuning for optimization.

4) Evaluation Metrics:
R² Score, Mean Squared Error (MSE), Mean Absolute Error (MAE).

## Streamlit App

The Streamlit app provides an interactive interface for users to:
* Input demographic and lifestyle data.
* Predict healthcare premiums instantly.
  
### How to Access
* [[Deployed Streamlit App Link](https://onkaramurthysk-ml-project-premium-prediction.streamlit.app/)] (if applicable)
* Run locally using the command
   streamlit run app.py

## Results

Achieved an R² score of [98] with minimal error margins.
Visualized key factors influencing premiums: age, region, BMI, and genetic risks.

## How to Run the Project

1) Clone the repository:
git clone https://github.com/your-username/healthcare-premium-prediction](https://github.com/Onkaramurthysk/ML-Project-premium-prediction.git
cd healthcare-premium-prediction
2) Install the required dependencies:
pip install -r requirements.txt
3) Run the Streamlit app:
streamlit run app.py

## Future Enhancements

* Add support for more advanced models like Gradient Boosting or Neural Networks.
* Enhance the dataset with real-world data.
* Integrate additional features like geospatial analysis.

## Contributors

[Onkaramurthy S K] - Data Scientist | Developer
