# 📊 Employee Attrition Analysis & Prediction

![Python](https://img.shields.io/badge/python-3.8+-blue.svg)
![Data Analysis](https://img.shields.io/badge/analysis-EDA-orange.svg)
![Data Science](https://img.shields.io/badge/domain-Aviation-green.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)

## 📌 Project Overview
Employee turnover presents a significant challenge to modern organizations, introducing massive financial burdens, disrupting team dynamics, and stalling productivity. 📉 This project focuses on analyzing an organization's internal workforce data to understand the root causes behind a baseline attrition rate of **16.12%**. By leveraging exploratory data analysis (EDA) and data profiling, the goal is to pinpoint exactly why talent leaves 🔍 and provide data-backed strategies to optimize employee retention. 💡

---

## 🗂️ Dataset & Feature Engineering
The dataset utilized contains historical records of employee demographics, job roles, compensation data, and work-life balance indicators. Key features analyzed include:

*   **👤 Demographics & Background:** Age, Gender, Marital Status, and Distance from Home.
*   **👔 Job Metrics:** Job Level, Department, Job Role, and Years at Company.
*   **📈 Performance & Motivation:** Performance Rating, Job Satisfaction, Relationship Satisfaction, and Training Times.
*   **💼 Workload & Compensation:** Overtime status, Monthly Income, and Business Travel frequency.

---

## 🔬 Exploratory Data Analysis (EDA) & Key Insights
The analysis systematically breaks down variables to isolate the primary catalysts driving voluntary employee departures. The findings reveal that attrition is heavily concentrated around work strain and financial variables:

### 1. ⚖️ Work-Life Balance & Burnout Factors
*   **⏰ The Overtime Imbalance:** Employees who log regular overtime show a drastically higher rate of attrition compared to those with standard working hours. Overtime serves as a primary leading indicator of employee burnout.
*   **✈️ Travel Fatigue:** Business travel frequency shows a strong correlation with turnover. Employees required to travel "Frequently" exit the company at a much higher velocity than those who travel rarely or not at all.

### 2. 💰 Financial Metrics & Career Stagnation
*   **📉 The Compensation Gap:** Grouping employees by income tiers shows a stark concentration of attrition within lower monthly income brackets. When pay does not scale alongside demanding roles, retention drops significantly.
*   **🧗 Entry-Level Vulnerability:** Attrition rates are disproportionately high among lower Job Levels (Tiers 1 and 2). This signals a bottleneck where early-career talent departs due to a perceived lack of clear upward mobility or financial incentive.

---

## 📊 Key Visualizations & Data Insights
### 1. Attrition Rate by Overtime Status ⏰
This chart shows a clear connection between workload and employee turnover. Employees who work overtime are three times more likely to leave the company compared to those who work standard hours.

<img width="1131" height="623" alt="Screenshot 2026-07-04 143238" src="https://github.com/user-attachments/assets/05f3ea20-d5a8-4c0d-a3d1-90726e82d87a" />


### 2. Attrition Distribution by Monthly Income 💵
This visualization highlights the financial gap. The data shows a heavy cluster of employee departures right at the lowest salary tiers, making baseline compensation a critical retention risk.

<img width="1141" height="621" alt="Screenshot 2026-07-04 141943" src="https://github.com/user-attachments/assets/528d5181-1090-4d28-8554-32ac383fc3c5" />


---

## 🤔 Why I Chose These Graphs
*   **The Overtime Bar Chart:** I chose this because it gives an immediate visual contrast. Seeing a 31.5% spike versus a 10.4% baseline instantly tells a clear story about workplace burnout.
*   **The Income Distribution Chart:** Instead of just looking at average numbers, this chart actually maps out the exact target zone where the company is losing people. It clearly proves that the lowest-paid employees are the highest flight risks.
---

## ⚙️ Technical Workflow
The notebook follows a structured data science workflow to ensure clean, reliable insights:

1.  **📥 Data Ingestion & Profiling:** Inspecting structural data types, checking shapes, and identifying missing values or anomalies.
2.  **🧹 Data Cleaning:** Addressing data consistency, formatting column headers, and encoding categorical text features for downstream analysis.
3.  **📊 Univariate Analysis:** Mapping the distribution of individual variables (e.g., age distributions, income ranges) to establish baseline population metrics.
4.  **🔄 Bivariate & Multivariate Analysis:** Utilizing correlation matrices, box plots, and cross-tabulations to isolate the precise intersections where multiple negative factors (like high overtime combined with low pay) maximize attrition risk.

---

## 🎯 Strategic Recommendations
Based on the data-driven conclusions of this analysis, the following structural updates are recommended for organizational leadership:

*   **🛡️ Establish Overtime Guardrails:** Implement tracking mechanisms to flag departments with prolonged overtime cycles. Distribute workloads evenly or increase headcount where overtime is consistently high.
*   **🗺️ Optimize Travel Frameworks:** Transition administrative or secondary operations to hybrid/remote collaboration to minimize physical travel strain, reserving high-frequency travel strictly for critical growth initiatives.
*   **📈 Revamp Base Compensation Tiers:** Adjust monthly income baselines for entry-level and foundational roles to match market competitiveness, pairing updates with clear 12-to-18-month career progression pathways.

---

## 🛠️ Tech Stack
*   **Language:** Python 🐍
*   **Libraries:** Pandas 🐼, Matplotlib 🎨, Seaborn 🌊
*   **Environment:** Jupyter Notebook 📓

---

## 🏁 Conclusion
By analyzing the core metrics underlying this dataset, it becomes evident that a 16.12% attrition rate is not an unfixable structural problem, but rather an operational warning sign. ⚠️ Voluntary turnover is heavily fueled by systemic burnout, intense travel schedules, and a baseline compensation model that fails early-career talent. 📉 Resolving these retention pain points requires moving away from reactive solutions and leaning into proactive corporate structural health. 🤝 Investing in better compensation frameworks and protecting employee personal time will stabilize talent pipelines, preserve operational continuity, and drive institutional productivity forward. 🚀
