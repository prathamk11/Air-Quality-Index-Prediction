<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Air Quality Index Prediction - Mumbai</title>

<style>

body{
    font-family: Arial, sans-serif;
    margin:0;
    background:#f4f7fb;
    color:#333;
}

/* HEADER */

header{
    background: linear-gradient(135deg,#2b5876,#4e4376);
    color:white;
    padding:60px 20px;
    text-align:center;
}

header h1{
    font-size:42px;
    margin-bottom:10px;
}

header p{
    font-size:18px;
}

/* BUTTON */

.demo-btn{
    margin-top:20px;
    padding:12px 25px;
    border:none;
    background:#00c6ff;
    color:white;
    font-size:16px;
    border-radius:25px;
    cursor:pointer;
    transition:0.3s;
}

.demo-btn:hover{
    background:#0072ff;
    transform:scale(1.05);
}

/* SECTION */

section{
    padding:50px 10%;
}

/* CARDS */

.card{
    background:white;
    padding:25px;
    margin:20px 0;
    border-radius:10px;
    box-shadow:0 10px 20px rgba(0,0,0,0.08);
    transition:0.3s;
}

.card:hover{
    transform:translateY(-5px);
}

/* GRID */

.grid{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:20px;
}

/* TECH STACK */

.tech{
    text-align:center;
    font-weight:bold;
    padding:15px;
    border-radius:8px;
    background:#eef2ff;
}

/* FOOTER */

footer{
    text-align:center;
    padding:25px;
    background:#2b5876;
    color:white;
}

</style>
</head>

<body>

<header>

<h1>🌍 Air Quality Index (AQI) Prediction – Mumbai</h1>

<p>Machine Learning Web Application for Predicting Air Pollution Levels</p>

<a href="https://air-quality-index-mumbai-predi.herokuapp.com/" target="_blank">
<button class="demo-btn">🚀 Try Live Demo</button>
</a>

</header>

<section>

<h2>📌 Project Overview</h2>

<div class="card">

<p>
Air pollution is one of the most critical environmental issues affecting urban populations.
The <b>Air Quality Index (AQI)</b> helps measure pollution levels and indicates how safe the air
is for public health.
</p>

<p>
This project presents a <b>Machine Learning based web application</b> that predicts
the AQI of the Mumbai region using environmental and climatic parameters.
</p>

<p>
It demonstrates the complete lifecycle of a Data Science project including
data collection, preprocessing, model training, and deployment.
</p>

</div>

</section>

<section>

<h2>🧠 Project Workflow</h2>

<div class="grid">

<div class="card">
<h3>📥 Data Collection</h3>
<p>
Custom web scraping pipeline was used to collect climate data
from <b>2013 – 2018</b>.
</p>
</div>

<div class="card">
<h3>🔄 Data Preprocessing</h3>
<p>
Raw scraped data was converted into structured datasets
by extracting climate parameters and aggregating daily records.
</p>
</div>

<div class="card">
<h3>🧹 Data Cleaning</h3>
<p>
Missing values removed, inconsistent records fixed,
and outliers handled to improve model accuracy.
</p>
</div>

<div class="card">
<h3>⚙ Feature Engineering</h3>
<p>
Important climate features were selected and used
for machine learning model training.
</p>
</div>

<div class="card">
<h3>🌐 Deployment</h3>
<p>
The trained model was deployed using <b>Flask</b>
and hosted on <b>Heroku</b>.
</p>
</div>

</div>

</section>

<section>

<h2>🤖 Machine Learning Models Tested</h2>

<div class="grid">

<div class="tech">📈 Linear Regression</div>

<div class="tech">📉 Lasso Regression</div>

<div class="tech">📊 Ridge Regression</div>

<div class="tech">🌳 Decision Tree Regressor</div>

<div class="tech">🌲 Random Forest Regressor</div>

<div class="tech">⚡ XGBoost Regressor</div>

</div>

<div class="card">

<b>Best Performing Model:</b> Random Forest Regressor

</div>

</section>

<section>

<h2>🛠 Tech Stack</h2>

<div class="grid">

<div class="tech">🐍 Python</div>

<div class="tech">📊 Pandas</div>

<div class="tech">🔢 NumPy</div>

<div class="tech">🤖 Scikit-learn</div>

<div class="tech">⚡ XGBoost</div>

<div class="tech">🕸 BeautifulSoup</div>

<div class="tech">🌐 Flask</div>

<div class="tech">🎨 HTML / CSS</div>

<div class="tech">☁ Heroku</div>

</div>

</section>

<footer>

<p>© 2026 AQI Prediction Project | Machine Learning Deployment</p>

</footer>

</body>
</html>
