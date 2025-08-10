# EduPredict

AI-powered **student performance prediction** and **personalized learning recommendations** using machine learning.

---

## Overview
EduPredict analyzes academic and demographic factors such as **study time**, **attendance**, **previous grades**, and **support programs** to:
- Predict final grades and academic performance
- Classify students as *"At Risk"* or *"On Track"*
- Generate **personalized recommendations** to improve learning outcomes

The system is designed for **schools, teachers, and education analysts** to make data-driven decisions and provide targeted support to students.

---

## Features
- **Grade Prediction** — Forecast student performance using regression and classification models.
- **Risk Assessment** — Identify students needing intervention.
- **Actionable Recommendations** — Suggest steps to improve performance.
- **Explainable AI** — Transparent predictions using SHAP values.
- **Interactive Dashboard** — Built with Streamlit for real-time predictions.

---

## Tech Stack
**Languages & Libraries**
- Python (pandas, numpy, scikit-learn, XGBoost, SHAP)
- Matplotlib, Seaborn (data visualization)
- Streamlit (deployment)

**Tools**
- Git & GitHub (version control)
- Jupyter Notebooks (EDA & experimentation)

---

## Project Structure
```
EduPredict/
├── data/ # datasets 
│ ├── raw/
│ └── processed/
├── notebooks/ # Jupyter notebooks
│ └── 01_EDA.ipynb
├── src/ # source code
│ ├── __init__.py
│ ├── config.py
│ ├── preprocessing.py
│ ├── train_model.py
│ ├── recommend.py
│ └── utils.py
├── models/ # saved ML models 
├── tests/ # unit tests
├── requirements.txt # dependencies
├── .gitignore
└── README.md
```
