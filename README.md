# 📊 Student Burnout Risk Analysis

![Python](https://img.shields.io/badge/Python-3.10-blue)
![Pandas](https://img.shields.io/badge/Pandas-2.0-lightgrey)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen)
![License](https://img.shields.io/badge/License-MIT-yellow)


## 📌 Overview

This project analyzes a dataset of 1 million student records to identify key psychological,
academic, and lifestyle factors contributing to burnout — and flags high-risk individuals
using a composite stress indicator.
The goal is to uncover patterns and build a simple system to detect high-risk students using data analysis techniques.
**Dataset:** [Student Mental Health & Burnout – 1M Records](https://www.kaggle.com/datasets/sharmajicoder/student-mental-health-and-burnout)

---

## 🎯 Objectives

* Identify major factors influencing student burnout
* Analyze relationships between psychological, academic, and lifestyle variables
* Detect high-risk students based on combined indicators
* Provide actionable insights for early intervention

---

## 📂 Project Structure

```
student-burnout-analysis/
│
├── data/
│   └── student_mental_health_burnout_1M.csv
│
├── notebooks/
│   └── student_burnout_analysis.ipynb
│
├── images/
│   └── heatmap.png
│
├── README.md
├── requirements.txt
└── .gitignore
```

---

## ⚙️ Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn

---

## 🔍 Key Questions Answered

1. What factors most strongly influence student burnout?
2. How does sleep impact burnout levels?
3. Can high-risk students be identified using psychological indicators?
4. Do lifestyle factors like physical activity and social support reduce burnout?
5. Are psychological factors more impactful than academic pressure?

---

## 📈 Key Insights

* **Stress level** is the strongest predictor of burnout
* **Anxiety and depression** significantly increase burnout risk
* * **Sleep hours** show a strong negative correlation with burnout (r = -0.37) —
  students sleeping under 6 hours were significantly more likely to be flagged high-risk
* **Social support** and **physical activity** reduce burnout levels
* Psychological factors have greater impact than purely academic variables
* **Interestingly, smartphone usage showed a negative correlation with burnout, suggesting it may act as a coping mechanism rather than a direct contributor to stress. However, this relationship should be interpreted cautiously, as correlation does not imply causation.**

---

## ⚠️ High-Risk Student Identification

A composite risk score was engineered using Z-score normalization across four factors — stress level, anxiety score, depression score, and sleep hours — weighted by their correlation strength with burnout score. Students in the top 25% of this composite score were flagged as high risk.

This helps identify students who may require immediate intervention.

---

## 📊 Sample Visualization

![Correlation Heatmap](images/heatmap.png)

---

## 💡 Practical Applications

* Early identification of at-risk students
* Improved mental health support systems in institutions
* Data-driven decision making for academic policies

---

## 🚀 How to Run the Project

1. Clone the repository
2. Install dependencies:

   ```
   pip install -r requirements.txt
   ```
3. Open the notebook:

   ```
   notebooks/student_burnout_analysis.ipynb
   ```

---

## 🔮 Future Improvements

* Apply clustering to segment students
* Build a predictive model for burnout scoring
* Create an interactive dashboard (Power BI / Tableau)

---

## 🤖 Note on AI Usage

AI tools were used to assist with code structuring and analysis.
All interpretations, logic, and understanding are independently developed.

---

## 👤 Author

Rahul Goyal
