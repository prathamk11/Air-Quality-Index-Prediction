# 🌫️ Air Quality Index (AQI) Prediction System

## 📌 Project Overview

Air pollution is a serious environmental issue that affects human health and climate. This project predicts the *Air Quality Index (AQI)* using various environmental and climate parameters such as temperature, humidity, wind speed, and atmospheric pressure.

The system uses *Machine Learning (Random Forest Regression)* to analyze climate data and predict the *PM2.5 AQI value. A **Flask web application* is used to allow users to input climate conditions and instantly receive AQI predictions.

This project demonstrates the *complete lifecycle of a Data Science and Machine Learning project*, from data collection to deployment.

---

# 🚀 Live Demo

🔗 [https://air-quality-index-mumbai-predi.herokuapp.com/](https://air-quality-index-mumbai-predi.herokuapp.com/)

---

# 🧠 Motivation

This project was inspired by *Krish Naik's Air Quality Index Prediction Project*, which demonstrates real-world Machine Learning implementation.

Reference Project:
[https://github.com/krishnaik06/AQI-Project](https://github.com/krishnaik06/AQI-Project)

---

# 🧪 Machine Learning Workflow

The project follows a *complete Data Science lifecycle*:

### 1️⃣ Data Collection

Climate data was collected using a *web scraping script* that extracts weather data from:

[https://en.tutiempo.net/](https://en.tutiempo.net/)

The scraper collects data from *2013–2018* and stores it in HTML format for each month.

---

### 2️⃣ Data Preprocessing

AQI data from an external dataset was combined with the scraped climate data.

The AQI dataset originally contained *hourly AQI values, which were converted into **daily AQI values* and organized by year.

The climate dataset and AQI dataset were then merged into a single CSV dataset.

---

### 3️⃣ Data Cleaning

The combined dataset was cleaned by:

* Removing null values
* Fixing improper data
* Formatting numerical values

The cleaned dataset was saved as:


Real_Combine.csv


---

### 4️⃣ Feature Engineering & Model Training

Several regression algorithms were tested:

* Linear Regression
* Lasso Regression
* Ridge Regression
* Decision Tree Regressor
* Random Forest Regressor
* XGBoost Regressor

After performance comparison:

✅ *Random Forest Regressor* provided the best prediction accuracy and was selected as the final model.

The trained model was saved using *Pickle serialization*.

---

# 🖥️ Web Application

A *Flask web application* was built to interact with the trained machine learning model.

Users can input climate parameters such as:

* Temperature
* Humidity
* Wind Speed
* Atmospheric Pressure
* Visibility

The Flask backend sends the data to the trained model and returns the predicted *Air Quality Index (AQI)*.

---

# 🏗️ Tech Stack

### Programming Language

* Python

### Machine Learning Libraries

* NumPy
* Pandas
* Scikit-learn

### Web Framework

* Flask

### Frontend

* HTML
* CSS

### Model Serialization

* Pickle

### Deployment

* Heroku

---

# 📁 Project Structure


AirQualityIndex-Prediction
│
├── app.py                 # Flask web application
├── model.py               # Machine learning model training
├── model.pkl              # Saved trained model
├── Real_Combine.csv       # Cleaned dataset
├── requirements.txt       # Project dependencies
├── Procfile               # Heroku deployment configuration
│
├── templates
│   └── index.html         # Web interface
│
├── static
│   └── css
│       └── style.css
│
├── Machine Learning Models
│   └── Regression_Ridge_Lasso.ipynb
│
├── Python Scrapping Files
│   ├── Extract_combine.py
│   ├── Html_script.py
│   └── Plot_AQI.py
│
└── Scrapped Data
    └── Real-Data


---

# ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

bash
git clone https://github.com/your-username/AirQualityIndex-Prediction.git


---

### 2️⃣ Navigate to Project Folder

bash
cd AirQualityIndex-Prediction


---

### 3️⃣ Install Dependencies

bash
pip install -r requirements.txt


---

### 4️⃣ Train the Model

bash
python model.py


This will generate:


model.pkl


---

### 5️⃣ Run the Flask Application

bash
python app.py


---

### 6️⃣ Open in Browser


http://127.0.0.1:5000


---

# 📊 Sample Application Output

Users can input climate data and receive a predicted *Air Quality Index (AQI)* value instantly.

---

# 📌 Future Improvements

* Add *real-time weather API integration*
* Improve prediction using *Deep Learning models*
* Add *interactive data visualization*
* Deploy using *Docker and cloud platforms*
* Convert frontend to *React.js*

---

# 👨‍💻 Author

Developed by *Prathamesh Kulkarni*
