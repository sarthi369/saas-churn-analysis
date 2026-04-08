# 📊 SaaS Customer Churn Analysis

## 📌 Problem Statement
This project analyzes customer churn for a digital product to identify potential drivers of user drop-off and provide actionable business insights. The goal is to understand whether user behavior, satisfaction, or purchase patterns influence churn.

---

## 📊 Dataset
The dataset contains customer-level data including:

- Demographics (Age, Gender, Location)
- Engagement metrics (Number of Interactions, Time Spent on Site)
- Behavioral signals (Products Viewed, Products Purchased)
- Satisfaction scores
- Retention status (Retained / Churned)

---

## 🔍 Analysis Performed

The following analyses were conducted using SQL:

- Overall churn rate calculation
- Churn segmentation by gender
- Churn segmentation by age groups
- Satisfaction vs churn analysis
- Purchase behavior vs churn analysis
- Engagement-based analysis

---

## 💡 Key Insights

- Churn rate across satisfaction levels showed minimal variation (~28%–32%), indicating a weak relationship.
- Engagement could not be evaluated effectively due to lack of variation (all users had low interaction levels).
- Users with higher product purchases showed slightly higher churn (~31%) compared to low purchase users (~23%), but the difference was not strong enough to establish causation.
- No single variable strongly explained churn independently.

---

## ⚠️ Limitations

- Lack of detailed behavioral data (e.g., session frequency, feature usage)
- Limited variation in engagement metrics
- No pricing or revenue data available
- Dataset does not capture user journey or feature-level interactions

---

## 🚀 Recommendations

- Track deeper behavioral metrics such as feature usage and session frequency
- Analyze user journey to identify drop-off points
- Implement cohort-based retention tracking
- Improve onboarding to ensure users reach the “aha moment”
- Collect richer product usage data to identify engagement drivers

---

## 🛠 Tools Used

- MySQL (Data Analysis)
- SQL (Data Cleaning & Aggregation)
- GitHub (Project Documentation)

---

## 📁 Project Structure

aas-churn-analysis/
│
├── data/
├── sql/
├── outputs/
└── README.md

---

## 📢 Final Note

This project focuses on applying SQL and analytical thinking to a real-world business problem. It emphasizes not only metric calculation but also interpreting results, identifying limitations, and making business recommendations.
