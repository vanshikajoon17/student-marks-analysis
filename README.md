# student-marks-analysis
EDA on student performance dataset using Python
# 🎓 Student Marks Analysis & Grade Prediction

A data analysis project exploring factors that influence student academic performance using Python, Pandas, Matplotlib, and Seaborn.

---

## 📌 Project Overview

This project performs Exploratory Data Analysis (EDA) on a real-world student performance dataset (649 students, 33 features) sourced from Kaggle. The goal is to identify key factors — such as study time, past failures, and internet access — that impact final grades.

---

## 📊 Dataset

- **Source:** [Kaggle - Student Performance Data Set](https://www.kaggle.com/datasets/larsen0966/student-performance-data-set)
- **Records:** 649 students
- **Features:** 33 (demographics, social, academic)
- **Target Variable:** G3 (Final Grade, scale 0–20)

---

## 🔍 Key Insights

| Factor | Finding |
|--------|---------|
| 📚 Study Time | Higher study time leads to **13.8% better** final grades |
| ❌ Past Failures | Students with 0 failures score **45.6% higher** on average |
| 🌐 Internet Access | Students with internet score **10.4% higher** on average |
| 📈 Average Final Grade | 11.91 / 20 across all 649 students |

---

## 📁 Project Structure
student-marks-analysis/
│
├── Student_Marks_Analysis.ipynb   # Main analysis notebook
├── student-por.csv                # Dataset
└── README.md                      # Project documentation

---

## 🛠️ Tools & Libraries

- Python 3
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab

---

## 📈 Visualisations

- Grade distribution histograms (G1, G2, G3)
- Correlation heatmap of all numeric features
- Scatter plots — Study Time vs Final Grade, Absences vs Final Grade
- Bar charts — Grade by Past Failures and Internet Access

---

## 🚀 How to Run

1. Clone this repository
2. Upload `student-por.csv` to Google Colab
3. Open `Student_Marks_Analysis.ipynb` in Google Colab
4. Run all cells in order

---

## 👩‍💻 Author

**Vanshika**  
BTech CSE — GGSIPU
