🌫️ Air Quality Index (AQI) Prediction – Mumbai

A Machine Learning web application that predicts the Air Quality Index (AQI) for the Mumbai region using climate conditions. This project demonstrates a complete Data Science workflow, from data collection and preprocessing to model deployment.

🔗 Live Demo: AQI Prediction – Mumbai

🚀 Project Overview

This project predicts AQI values based on climate parameters using machine learning. Users can input climate details through an interactive web interface and instantly receive a predicted AQI value for Mumbai. The goal is to provide an accessible tool to monitor air quality based on environmental conditions.

🧠 My Workflow
1️⃣ Data Collection

Collected historical climate data for Mumbai from Tutiempo
.

Dataset spans 2013 – 2018, including hourly AQI and weather parameters.

2️⃣ Data Preprocessing

Aggregated hourly AQI data into daily AQI values.

Merged AQI data with climate parameters to create a consolidated dataset.

3️⃣ Data Cleaning

Removed missing or inconsistent values.

Filtered out anomalies to ensure high-quality, reliable training data.

4️⃣ Model Training & Evaluation

Explored multiple algorithms:

Linear Regression

Lasso & Ridge Regression

Decision Tree

Random Forest

XGBoost

Random Forest Regressor achieved the best performance in predicting AQI.

🌐 Web Application

Developed a Flask-based web app to deploy the trained model.

Users can input climate parameters via a simple and intuitive HTML/CSS frontend.

Predictions are generated in real-time and displayed instantly.

🛠️ Tech Stack

Backend: Python, Flask, Scikit-Learn, Pandas, NumPy
Frontend: HTML, CSS, JavaScript

💡 Key Takeaways

Hands-on experience with full ML pipeline: data scraping, cleaning, feature engineering, model selection, and deployment.

Gained practical experience in predictive modeling and integrating ML models with a web interface.

Learned how to handle real-world environmental data with missing values and inconsistencies.
