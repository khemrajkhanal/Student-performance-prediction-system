# 🎓 Student Performance Prediction System

> A machine learning project to predict student academic performance based on study habits, attendance, and class participation.

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![scikit-learn](https://img.shields.io/badge/scikit--learn-1.3+-orange.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)

---

## 👥 Team Members

- **Khem Raj Khanal** 
- **Bikash Kumar Bhusal** 

---

## 📖 Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Dataset](#dataset)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [License](#license)

---

## 🎯 Project Overview

This project aims to predict student academic performance using machine learning algorithms. By analyzing three key factors:
- **Weekly self-study hours**
- **Attendance percentage**
- **Class participation score**

The system can:
1. **Predict exact scores** (0-100) using regression models
2. **Predict letter grades** (A, B, C, D, F) using classification models
3. **Provide actionable recommendations** for improvement

### 🎓 Academic Context
- **Course**: [Your Course Name]
- **Institution**: [Your University/College]
- **Semester**: [Semester/Year]

---

## ✨ Features

- 🔮 **Dual Prediction System**
  - Score prediction (Regression)
  - Grade prediction (Classification)

- 📊 **Multiple ML Algorithms**
  - Decision Trees
  - Random Forest
  - Gradient Boosting
  - K-Nearest Neighbors

- 📈 **Comprehensive Analysis**
  - Model comparison and evaluation
  - Feature importance analysis
  - Confusion matrix visualization
  - Performance metrics (R², MAE, RMSE, Accuracy, F1-Score)

- 💾 **Model Persistence**
  - Save trained models for reuse
  - Fast predictions without retraining

- 🎨 **Interactive Prediction**
  - User-friendly input system
  - Detailed performance assessment
  - Personalized recommendations

---

## 📊 Dataset

- **Size**: 1,000,000 students (sampled to 100,000 for efficiency)
- **Features**: 3 input variables
  - `weekly_self_study_hours` (0-40 hours)
  - `attendance_percentage` (0-100%)
  - `class_participation` (0-10 scale)
- **Targets**: 2 prediction tasks
  - `total_score` (0-100 points) - Regression
  - `grade` (A, B, C, D, F) - Classification
- **Split**: 80% training, 20% testing


---

## 🛠️ Technologies Used

### Core Libraries
- **Python 3.8+**
- **pandas** - Data manipulation
- **numpy** - Numerical computations
- **scikit-learn** - Machine learning algorithms
- **matplotlib** - Data visualization
- **seaborn** - Statistical visualizations

### ML Algorithms
- Decision Tree (Regressor & Classifier)
- Random Forest (Regressor & Classifier)
- Gradient Boosting (Regressor & Classifier)
- K-Nearest Neighbors (Regressor & Classifier)

### Tools
- Jupyter Notebook
- pickle - Model serialization
- StandardScaler - Feature scaling

---

## 💻 Installation

### Prerequisites
```bash
Python 3.8 or higher
pip package manager
```
### Steps
1. Clone Repository
2. Install Dependencies
```bash
pip install -r requirements.txt
```
3. Launch Jupyter Notebook

---
## 🚀 Usuage
1. Use Full Pipeline
2. Use Saved Models (Fast!)
3. Interactive Predictions
---
## 📊 Results
1. Attendance is Most Important
2. Study Hours Matter
3. Participation Helps

## 📜 License
This project is licensed under the MIT License.