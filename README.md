# IPL-Score-Predictor-using-ML
# 🏏 IPL Cricket Score Prediction using Machine Learning

This repository contains a machine learning-based project to predict the final score of an IPL (Indian Premier League) cricket innings based on real-time match data. Created by **Satyajit Pathanayak**, the project aims to provide quick, data-driven estimates of a team’s final score using historical IPL match data and machine learning algorithms.

## 📌 Project Objective

The main objective of this project is to build a predictive model that can estimate the **final total score** a batting team might reach in an IPL match, based on:

- Current runs
- Overs bowled
- Wickets fallen
- Batting and bowling teams
- Recent run rate
- Match conditions

This can help analysts, broadcasters, and fans get real-time projections during a live match.

---

## 🚀 Features

- Data cleaning and preprocessing of IPL dataset
- Exploratory Data Analysis (EDA) to identify key features
- Implementation of multiple regression models
- Evaluation using metrics like MAE, RMSE, R²
- Final model deployment ready (e.g., Flask or Streamlit UI — optional)

---

## 📊 Tech Stack

- **Python 3.8+**
- **Pandas**
- **NumPy**
- **Scikit-learn**
- **Matplotlib / Seaborn** (for EDA)
- **Streamlit / Flask** (optional - for web app interface)

---

## 📁 Dataset

The dataset used in this project contains ball-by-ball information from past IPL matches. It includes features such as:

- Batting team
- Bowling team
- Runs scored per ball
- Overs
- Wickets
- Venue (if used)
- Match outcome (if used for future enhancements)

> Note: Dataset source - [Kaggle IPL Dataset](https://www.kaggle.com/) 

---

## 📈 Model Development

The following steps were followed:

1. **Data Cleaning:** Removed unnecessary columns, handled null values.
2. **Feature Engineering:** Created features like current run rate, wickets in hand, etc.
3. **Model Training:** Trained multiple regression models including:
    - Linear Regression
    - Decision Tree Regressor
    - Random Forest Regressor
4. **Model Evaluation:** Compared models using performance metrics and chose the best one.

---

## 🧪 Results

- **Best Model:** Random Forest Regressor (example)
- **R² Score:** 0.92
- **MAE:** ~10 runs
> *(Modify with your actual results)*

---


    ```

---



---

## 📌 Future Work

- Include live data from APIs for real-time score prediction
- Add classification models to predict match outcomes
- Deploy the model using Flask/Streamlit on platforms like Heroku or Render

---

## 🙌 Acknowledgements

- IPL Dataset from Kaggle
- Inspired by real-time sports analytics use cases
- Machine learning techniques from Scikit-learn and data visualization via Seaborn/Matplotlib

---



---

## 📝 License

This project is licensed under the MIT License. 
