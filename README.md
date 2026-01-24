# 🏥 Heart Disease Prediction App

## 📌 Project Overview

The **Heart Disease Prediction App** is a machine learning–powered web application built using **Streamlit** that predicts the risk of heart disease based on patient health metrics. The app uses a **Logistic Regression model** trained on a heart disease dataset and provides both prediction results and confidence scores in an interactive and user-friendly interface.

This project demonstrates the complete ML lifecycle — from data preprocessing and model training to deployment using Streamlit.

---

## 🎯 Objectives

* Predict whether a patient is at **high risk** or **low risk** of heart disease
* Provide **probability-based confidence scores** for predictions
* Offer an **interactive UI** for real-time predictions
* Deploy a trained ML model using **Streamlit**

---

## 🧠 Machine Learning Model

* **Algorithm Used:** Logistic Regression

* **Reason for Choice:**

  * Simple and interpretable
  * Effective for binary classification problems
  * Performs well on structured medical data

* **Target Variable:**

  * `0` → No Heart Disease
  * `1` → Heart Disease Present

---

## 📂 Project Structure

```
📁 Heart Disease Prediction App
│── app.py                         # Streamlit application
│── heart.csv.xls                  # Dataset used for training
│── heart_data_logistic.ipynb      # Model training & analysis notebook
│── logistic_regression_model.pkl  # Saved trained model
│── README.md                      # Project documentation
```

---

## ⚙️ Technologies Used

* **Python**
* **Pandas** – Data manipulation
* **NumPy** – Numerical operations
* **Scikit-learn** – Model building
* **Joblib** – Model serialization
* **Streamlit** – Web app deployment

---

## 🧾 Features

* Dynamic input fields generated from dataset
* Automatic min, max, and mean-based input ranges
* Risk classification (High / Low)
* Prediction confidence percentage
* Probability distribution visualization
* Patient input summary table

---

## ▶️ How to Run the Project

### 1️⃣ Install Required Libraries

```bash
pip install streamlit pandas numpy scikit-learn joblib
```

### 2️⃣ Run the Streamlit App

```bash
streamlit run app.py
```

### 3️⃣ Open in Browser

The app will run locally and open automatically in your browser.

---

## 📊 Output Explanation

* **Risk Level:** Indicates whether the patient has a high or low risk of heart disease
* **Confidence Score:** Probability of the predicted class
* **Probability Breakdown:** Bar chart showing prediction probabilities
* **Patient Input Summary:** Displays all entered values for transparency

---

## 🚀 Future Enhancements

* Add more ML models for comparison
* Include feature importance visualization
* Improve UI with custom styling
* Deploy the app on cloud platforms (AWS / Heroku / Streamlit Cloud)

---

## 🧑‍💻 Author

**Kalyani Konatham**
Data Science & Machine Learning Enthusiast

---

## 📜 Disclaimer

This application is intended for **educational purposes only** and should not be used as a substitute for professional medical advice.

---

✨ *Feel free to fork, modify, and enhance this project!*
# logistic_regression
