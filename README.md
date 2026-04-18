# 🎓 Predicting Student Academic Performance Using Data Mining Techniques

---

## 📌 Overview

This project applies data mining and machine learning techniques to predict student academic performance as **Good**, **Average**, or **Poor** based on behavioral and academic features.

The workflow includes data generation, preprocessing, exploratory data analysis (EDA), classification, clustering, and interpretation of results.

---

## 🎯 Objective

To build a predictive system that can:

* Identify student performance levels early
* Detect **at-risk students**
* Provide actionable insights for academic intervention

---

## 📊 Dataset

* Synthetic dataset of **350 students**
* Generated within the notebook using realistic distributions

### Features:

* **Attendance** (%)
* **StudyHours** (hours/day)
* **PreviousGrade** (%)
* **ExtracurricularActivities** (hours/week)
* **SleepHours** (hours/night)

### Target:

* **Performance** → `Good`, `Average`, `Poor`

---

## ⚙️ Techniques Used

### 🔍 Exploratory Data Analysis (EDA)

* Distribution plots
* Correlation heatmap
* Box plots & scatter plots

### 🤖 Classification Models

* Decision Tree
* Random Forest ⭐ (Best performing)
* Naïve Bayes

### 🔵 Clustering

* K-Means (K=3)
* Elbow method
* PCA visualization

### 📈 Evaluation Metrics

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

---

## 🧠 Key Insights

* **Study Hours** and **Previous Grades** are the strongest predictors
* **Random Forest** achieved the highest performance (~87% F1-score)
* Students naturally cluster into 3 groups aligning with performance categories
* Low attendance + low study hours strongly indicate **at-risk students**

---

## 🚨 At-Risk Student Indicators

A student is likely at risk if:

* Attendance < 65%
* Study Hours < 3 hrs/day
* Previous Grade < 55
* Sleep Hours < 6 hrs

---

## 🛠 Tech Stack

* Python
* NumPy, Pandas
* Scikit-learn
* Matplotlib, Seaborn

---

## ▶️ How to Run

1. Open the notebook:

   ```
   student-performance-analysis.ipynb
   ```

2. Run all cells sequentially

3. The dataset is generated within the notebook automatically

---

## 📁 Project Files

* `student-performance-analysis.ipynb` → Full implementation
* `DM_Project_Report.pdf` → Detailed report

---

## 📌 Future Improvements

* Use real-world student datasets
* Add more features (socioeconomic, engagement metrics)
* Deploy as a web application (Flask/Dashboard)
* Incorporate time-series analysis for performance trends

---

## 🎉 Conclusion

This project demonstrates how data mining techniques can be used to extract meaningful insights from student data and support data-driven academic decision-making.
