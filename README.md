# Student Performance Prediction

## 📌 Overview

This project focuses on predicting students' performance based on their study habits, previous academic scores, and other related factors.

The project uses a machine learning regression approach to predict the **Performance Index** of students.

---
# Student Performance Prediction

## Overview

A machine learning regression project for predicting student performance based on study habits, previous scores, sleep hours, extracurricular activities, and practice questions.

## Dataset

The dataset contains **10,000 student records** with 5 input features:

* Hours Studied
* Previous Scores
* Extracurricular Activities
* Sleep Hours
* Sample Question Papers Practiced

**Target:** Performance Index

## Model

The final model is **Polynomial Regression (Degree 2)**.

The model was evaluated using MAE, MSE, RMSE, and R².

### Results

| Metric |  Score |
| ------ | -----: |
| MAE    | 1.6115 |
| MSE    | 4.0806 |
| RMSE   | 2.0201 |
| R²     | 0.9890 |

## Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* Jupyter Notebook / Google Colab

## Project Structure

```text
Student-Performance-Prediction/
├── student_performance.ipynb
├── README.md
└── requirements.txt
```

## Conclusion

Polynomial Regression with degree 2 achieved strong performance on the test set, with an **R² score of 0.9890**.

## Author

**Rasoul Dashti**
