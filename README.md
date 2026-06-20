# 🌧️ Predicting Next-Day Rainfall

> A binary classification model that predicts whether it will rain tomorrow, trained on 10 years of historical Australian weather data — enabling accurate, data-driven weather forecasting.

[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)](https://scikit-learn.org/)
[![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)](https://numpy.org/)
[![License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)](LICENSE)

---

## 📌 Overview

Accurate next-day rainfall prediction is critical for agriculture, transportation, event planning, and disaster preparedness. Manual or rule-based forecasting often fails to capture complex, non-linear weather patterns.

This project builds a **Logistic Regression classification model** trained on a decade of weather observations — temperature, humidity, wind speed, pressure, and more — to predict whether it will rain the next day (`RainTomorrow`: Yes/No).

---

## 🎯 Objectives

- Build a binary classifier to predict next-day rainfall accurately
- Identify which weather conditions most strongly influence rainfall
- Demonstrate a complete, real-world classification ML pipeline
- Provide a foundation for more advanced weather forecasting systems

---

## 🗂️ Dataset

10 years of daily weather observations across multiple Australian locations, including:

| Feature | Description |
|---|---|
| `MinTemp`, `MaxTemp` | Daily temperature range |
| `Rainfall` | Rainfall recorded that day (mm) |
| `Humidity9am`, `Humidity3pm` | Humidity readings |
| `WindSpeed9am`, `WindSpeed3pm` | Wind speed readings |
| `Pressure9am`, `Pressure3pm` | Atmospheric pressure |
| `RainToday` | Whether it rained today |
| `RainTomorrow` | 🎯 Target variable — Yes/No |

---

## 🔄 ML Pipeline

```
Understand Problem → Clean Data → Handle Null Values → Handle Outliers
   → Encoding → Scaling → Train-Test Split → Choose Algorithm
   → Train Model → Predict → Evaluate → Check Overfitting → Improve Model
```

---

## ⚙️ What Was Done

1. **Data Cleaning** — Handled missing values across weather measurement columns
2. **Exploratory Data Analysis** — Distribution analysis, correlation checks across weather variables
3. **Outlier Treatment** — Statistical capping on skewed numerical features
4. **Encoding** — Categorical variables (`RainToday`, location, wind direction) label/one-hot encoded
5. **Scaling** — Standardized numerical features using `StandardScaler`
6. **Model Training** — Logistic Regression for binary classification
7. **Evaluation** — Accuracy, Confusion Matrix, Precision, Recall, F1-Score
8. **Overfitting Check** — Compared training vs. test performance for generalization

---

## 🛠️ Tech Stack

`Python` · `Pandas` · `NumPy` · `Scikit-Learn` · `Matplotlib` · `Seaborn`

**Algorithm:** Logistic Regression (Binary Classification)

---

## 📁 Project Structure

```
predicting-next-day-rainfall/
├── predicting-next-day-rainfall.ipynb   # Full analysis & model notebook
└── README.md
```

---

## 🚀 Run This Project Locally

```bash
git clone https://github.com/vishnu-chaithanya-ds/predicting-next-day-rainfall.git
cd predicting-next-day-rainfall
pip install pandas numpy scikit-learn matplotlib seaborn
jupyter notebook predicting-next-day-rainfall.ipynb
```

---

## 👤 About Me

**Tadipatri Vishnu Chaithanya**
Aspiring Data Scientist | B.Tech — CSE (AI & ML)

[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://vishnuchaithanya.netlify.app/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/tadipatri-vishnu-chaithanya-52817037b)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/vishnu-chaithanya-ds)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:tadipatrivishnuchaithanya@gmail.com)

---

⭐ **If you found this project useful, consider giving it a star!**
