# Student Score Prediction

A machine learning regression project that predicts students' exam scores based on study habits, attendance, and socio-demographic factors.

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)

## 📋 Project Overview

This project builds a **supervised regression model** to predict student exam scores using academic and personal factors. The goal is to identify students who may need extra academic support.

## 📊 Dataset

The dataset includes features such as:
- Study habits
- Attendance records  
- Socio-demographic information
- **Target Variable**: `Exam_Score`

## 🛠️ Technologies Used

- **Python**
- **Pandas** & **NumPy** — Data manipulation and analysis
- **Scikit-learn** — Model building and evaluation (Ridge Regression)
- **Matplotlib** & **Seaborn** — Data visualization

## 🔍 Methodology

1. **Data Preprocessing** – Cleaning, encoding categorical variables
2. **Exploratory Data Analysis** – Understanding feature relationships
3. **Modeling** – Train/Test split (80/20) + Ridge Regression (α = 0.5)
4. **Evaluation** – Multiple regression metrics

## 📈 Results

| Metric                      | Score   |
|----------------------------|---------|
| **Mean Absolute Error**     | 0.77    |
| **Mean Squared Error**      | 2.77    |
| **Root Mean Squared Error** | **1.67** |
| **R² Score**                | **0.79** |

The model explains **79%** of the variance in exam scores.

## 🚀 How to Run

```bash
git clone https://github.com/Funmi36/Students-score-prediction.git
cd Students-score-prediction
pip install pandas numpy scikit-learn matplotlib seaborn
jupyter notebook Student_Score_Prediction.ipynb
