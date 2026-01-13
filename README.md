# 🌦️ KNN Weather Prediction App

![GitHub Repo Size](https://img.shields.io/github/repo-size/<YOUR_GITHUB_USERNAME>/<YOUR_REPO_NAME>)
![Streamlit](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)
![GitHub Top Language](https://img.shields.io/github/languages/top/<YOUR_GITHUB_USERNAME>/<YOUR_REPO_NAME>)
![Last Commit](https://img.shields.io/github/last-commit/<YOUR_GITHUB_USERNAME>/<YOUR_REPO_NAME>)

> A weather condition prediction app built with **K-Nearest Neighbors (KNN)** and deployed using **Streamlit**.

## 🚀 Live Demo

👉 **Try it online:**  
🔗 https://ml-project-gr9xfva5dyvdtz37tazwdd.streamlit.app/

---

## 📌 About

This project predicts weather conditions (e.g., **Sunny, Rainy, Cloudy**) using a **KNN Machine Learning model** trained on historical weather data.

Users can input features such as:
- Temperature
- Humidity
- Wind Speed
- Pressure

…and receive a prediction based on nearest neighbors.

---

## 📋 Features

✔ Interactive web UI with Streamlit  
✔ Real-time predictions  
✔ User-friendly input form  
✔ KNN model built with scikit-learn  
✔ Deployed on Streamlit Cloud

---

## 🧠 How It Works

1. Load weather dataset  
2. Preprocess features  
3. Train KNN classifier  
4. Host the app with interactive inputs  
5. Output weather prediction

---

## 📁 Repository Structure

```text
.
├── app.py                 # Main Streamlit app
├── model.py               # Model training & prediction logic
├── data/
│   └── weather_data.csv   # Weather dataset
├── requirements.txt
├── .gitignore
└── README.md

```

Installation & Setup (Local)
Clone repository

git clone https://github.com/<YOUR_GITHUB_USERNAME>/<YOUR_REPO_NAME>.git
cd <YOUR_REPO_NAME>

Requirements

streamlit>=1.0
scikit-learn
pandas
numpy

Usage
Visit the Live App link above or run locally.
Enter weather attributes in the sidebar.
Click Predict.
The predicted weather label will show on the screen.
