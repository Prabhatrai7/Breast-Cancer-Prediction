# Breast Cancer Prediction Web App

A **Machine Learning powered web application** to predict whether a patient is likely to have **Breast Cancer** based on clinical measurements.  
This project uses **Python**, **scikit-learn**, and **Flask** to build and serve a predictive model through a simple web interface.

---

## 🧠 Project Overview

The goal of this project is to create an intuitive web application that predicts whether a tumor is **malignant (cancerous)** or **benign (non-cancerous)** based on user-input clinical data. The prediction model is trained using the famous *Breast Cancer Wisconsin (Diagnostic) dataset* and deployed using a Flask web server that renders an HTML form for user inputs.

---

## 🚀 Features

✔ Simple and responsive web UI built with HTML & Bootstrap  
✔ Predicts breast cancer likelihood using a machine learning model  
✔ Displays prediction outcome along with confidence  
✔ Easy to run locally or deploy on cloud services like AWS, Heroku, or Render

---

## 🛠️ Technologies Used

| Category | Technology |
|----------|------------|
| Language | Python |
| Web framework | Flask |
| ML library | scikit-learn |
| Data handling | pandas, numpy |
| Frontend | HTML, Bootstrap |

---

## 📁 Repository Structure

Breast-Cancer-Prediction/
├── app.py
├── README.md
├── home.html
└── (optional) model files


- `app.py`: Main Flask application  
- `home.html`: Frontend template for user input  
- `README.md`: Project documentation

---

## 🎯 How It Works

1. User visits the homepage and enters clinical measurements  
2. The Flask server receives the form data  
3. The input is passed to a trained machine learning model  
4. A prediction is generated: **Benign** or **Malignant**  
5. The result is shown back on the web page

---

## 💻 Running the Application (Local)

### 
1️⃣ Clone the repository

git clone https://github.com/Prabhatrai7/Breast-Cancer-Prediction.git
cd Breast-Cancer-Prediction

2️⃣ Create and activate a virtual environment (optional but recommended)

python3 -m venv venv
source venv/bin/activate

3️⃣ Install dependencies

pip install pandas scikit-learn flask

4️⃣ Run the Flask app

python app.py

5️⃣ Open in your browser

http://127.0.0.1:5000

## 📊 Model Prediction Logic

The model is trained using key features related to breast cancer measurements. It predicts whether the tumor is:

  Malignant (Cancerous)

  Benign (Non-cancerous)

The prediction logic resides in the Flask backend and computes the result based on form inputs.
