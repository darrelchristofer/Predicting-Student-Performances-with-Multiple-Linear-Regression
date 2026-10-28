# Predicting-Student-Performances-with-Multiple-Linear-Regression
EDA and Multiple Linear Regression on the Student Performance dataset (10,000 students) to predict a Performance Index from hours studied, previous scores, sleep, practice papers and extracurricular activities with Python, pandas, seaborn and scikit-learn. In this project, we will compare the use of different models, and pick the best model that can predict the best outcome.

---
## 📌 Case Overview

WE want to know which study habits and background factors go with better academic results, so we can tell students and teachers what to decide and where to put efforts. We are going to build a simple, explainable model that predicts a student’s Performance Index and shows how much each factor contributes through Data Cleaning, EDA, and Modeling.

---

## 🗂️ Dataset

Access through:
https://www.kaggle.com/datasets/nikhil7280/student-performance-multiple-linear-regression?select=Student_Performance.csv

---

## 🖼️ Preview

<img width="728" height="296" alt="image" src="https://github.com/user-attachments/assets/e242f114-8884-40fc-b792-edef47004475" />

Comparing the model

---

### Key Insights

- Past performance is by far the strongest predictor. Previous Scores has a 0.92 correlation with the Performance Index, and each extra previous-score point goes with about +1.02 points.
- Study time is the second driver and the most controllable one. Each extra hour studied per day goes with about +2.85 points, holding the other features fixed. The average index rises roughly in a straight line from about 44 at 1 hour to about 66 at 9 hours.
- Sleep, practice papers and extracurricular activities have small effects. Per unit they add only +0.48, +0.19 and +0.61 points.
- A simple linear model is enough. In cross-validation, Linear Regression (R² 0.9887) matches Ridge and Lasso and is slightly ahead of Gradient Boosting (0.9878) and Random Forest (0.9850). The more complex models add nothing, so the easier-to-explain model is the right choice.

---

## 🗂️ Project Structure

```
Predicting-Student-Performances-with-Multiple-Linear-Regression/
├── Student_Performance_Prediction_with_multiplt_linear_Regression.ipynb   # EDA + modeling + extra analysis
├── requirements.txt
├── Student_Performance.csv                       # download from Kaggle
└── README.md

```
---

## 👤 Author

**Darrel Christofer**
*(www.linkedin.com/in/darrel-christofer / christoferdarrel@gmail.com)*
