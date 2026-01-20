# 📊 Student Satisfaction Survey Analysis

## 📌 Project Overview

This project analyzes student satisfaction survey data to evaluate course performance using weighted average ratings (1–5 scale). The goal is to identify satisfaction levels, understand feedback distribution, and derive actionable insights for academic improvement.

---

## 🧩 Dataset Description

* Source: Student Satisfaction Survey (CSV)
* Key Fields:

  * Course Name
  * Weightage 1–5 (number of responses for each rating)

---

## 🛠️ Tools & Technologies Used

* Python
* Pandas (data manipulation)
* Matplotlib & Seaborn (visualization)
* Jupyter Notebook

---

## 🔍 Methodology

1. **Data Loading & Cleaning**

   * Handled encoding issues
   * Checked missing values and duplicates
   * Standardized column names

2. **Feature Engineering**

   * Calculated total responses per course
   * Computed weighted average ratings
   * Classified satisfaction levels:

     * ≥ 4.0 → Highly Satisfied
     * ≥ 3.0 → Satisfied
     * < 3.0 → Not Satisfied

3. **Exploratory Data Analysis (EDA)**

   * Course-wise average satisfaction
   * Distribution of total feedback
   * Distribution of weighted average ratings

---

## 📈 Key Visualizations

* Bar chart: Average Satisfaction by Course
* Histogram: Distribution of Total Feedback
* Histogram: Distribution of Weighted Average Ratings

---

## 📊 Key Findings

* Most courses fall in the **Satisfied to Highly Satisfied** range.
* A small number of courses receive consistently lower ratings, indicating improvement areas.
* Feedback distribution is right-skewed, meaning fewer courses receive very high response counts.

---

## 💡 Insights & Recommendations

* Courses with ratings below 3.0 should be reviewed for curriculum or teaching methodology improvements.
* Highly rated courses can be used as benchmarks for best practices.
* Collecting more balanced feedback across courses may improve decision-making accuracy.

---

## ✅ Conclusion

This analysis provides a clear, data-driven view of student satisfaction across courses. By using weighted averages and visual exploration, institutions can identify strengths, weaknesses, and opportunities for academic enhancement.

---

⭐ *If you found this project insightful, feel free to connect on LinkedIn and explore the repository on GitHub.*
