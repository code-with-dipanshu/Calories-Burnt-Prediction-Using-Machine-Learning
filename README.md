
<h1 align="center"> Calories Burnt Prediction using Machine Learning </h1>

<p align="center">
  <img src="https://img.shields.io/badge/Python-ML-blue.svg" />
  <img src="https://img.shields.io/badge/Model-XGBoost-green.svg" />
  <img src="https://img.shields.io/badge/UI-Tkinter-orange.svg" />
  <img src="https://img.shields.io/badge/Accuracy-99%25-brightgreen.svg" />
</p>

<p align="center">
  A machine learning project that predicts the number of calories burnt during exercise based on key biometric features using regression models. Built with 🐍 Python, 🔢 Scikit-learn, 🌲 Random Forest, and 🚀 XGBoost. Includes a user-friendly GUI built in 🖼️ Tkinter.
</p>

---

## 📊 Project Overview

This project involves:
- Merging two datasets: `calories.csv` and `exercise.csv`
- Performing EDA (Exploratory Data Analysis)
- Preprocessing using `ColumnTransformer` and `Pipeline`
- Comparing models: Linear Regression, Random Forest, and XGBoost
- Saving the best model
- Creating a GUI for real-time prediction

---

## 💡 Features

- 🔍 EDA & Null Value Checks
- 📈 Multiple ML Models with R² Score Comparison
- 💾 Model Saving using `pickle`
- 🧠 Best performing model: **XGBoost Regressor**
- 🖥️ GUI for real-time calorie prediction using `tkinter`

---

## 🛠 Technologies Used

| Component | Description |
|----------|-------------|
| `pandas`, `numpy` | Data manipulation |
| `seaborn`, `matplotlib` | Visualization |
| `scikit-learn` | Preprocessing, model pipeline |
| `xgboost` | Advanced regression |
| `pickle` | Model serialization |
| `tkinter` | GUI interface |

---

## 📷 GUI Preview

<img src="https://user-images.githubusercontent.com/your-username/your-image.gif" width="500">

*Real-time calorie prediction using input fields in a simple GUI*

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/code-with-dipanshu/Calories-Burnt-Prediction-Using-Machine-Learning.git
cd Calories-Burnt-Prediction-Using-Machine-Learning
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

Or manually:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost
```

 
## 📁 Project Structure

```
Calories-Burnt-Prediction-Using-Machine-Learning/
│
├── calories.csv
├── exercise.csv
├── pipeline.pkl          # Trained ML model
├── Calories_Burnt_ Prediction.ipynb   # Code for EDA + ML pipeline                
├── requirements.txt
└── README.md
```

---

## ✅ Model Performance

| Model             | R² Score | MAE     | CV Score |
|------------------|----------|---------|----------|
| Linear Regression| 0.9672   | 8.44    | 0.9671   |
| Random Forest     | 0.9983   | 1.68    | 0.9979   |
| XGBoost           | **0.9987** | **1.51** | **0.9987** |

> ✅ Final model used in GUI: **XGBoostRegressor**

---

## 🧪 Sample Input for GUI

```
Gender: male
Age: 68
Height: 190.0
Weight: 94.0
Duration: 29.0
Heart Rate: 105.0
Body Temp: 40.8
```

**Predicted Calories Burnt:** `~231 kcal`

---

## 🙌 Connect with Me

<a href="https://github.com/code-with-dipanshu" target="_blank">GitHub</a> 

---

> Made with ❤️ by Dipanshu
