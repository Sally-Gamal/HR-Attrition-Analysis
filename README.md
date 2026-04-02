# 👥 Employee Retention & Attrition Analysis (HR Analytics)

## 1. 📊 Interactive Dashboard Preview
![HR Attrition Dashboard](HR_Attrition_Dashboard.jpg)

---

## 2. 📝 Executive Summary
This project provides a deep dive into **Employee Attrition** using a dataset of 1,470 employees. The primary objective is to identify the critical drivers behind employee turnover and provide data-driven recommendations to HR management to enhance retention strategies and reduce associated hiring costs.

### 📈 Global Metrics (KPIs):
* **Total Workforce:** 1,470 Employees
* **Attrition Count:** 237 Left (16% Turnover Rate)
* **Active Employees:** 1,233
* **Average Monthly Income:** $6,503
* **Retention Health:** 84%

---

## 3. 🔍 Business Insights & Analytical Findings

### A. Turnover by Department & Role
* **Departmental Stress:** The **R&D Department** houses the majority of the workforce, yet shows significant turnover. **Sales Representatives** exhibit the highest vulnerability to attrition, likely due to performance pressure.
* **Job Role Impact:** Laboratory Technicians and Sales Executives represent a large portion of those leaving, suggesting a need for better career pathing in these roles.

### B. Compensation & Satisfaction Correlation
* **Income Threshold:** There is a clear correlation between low monthly income and high attrition. Employees earning near the **$2,600** mark (Sales Reps) are significantly more likely to leave compared to Managers earning over **$17,000**.
* **Job Satisfaction:** With an average satisfaction score of **2.7/4**, there is a clear room for improvement in workplace culture and employee engagement.

### C. Work-Life Balance & Travel
* **Travel Frequency:** Employees who **Travel Frequently** account for **52%** of the total attrition. This indicates that "Burnout" from constant travel is a primary driver for resignation.
* **Overtime:** **28%** of the attrition comes from employees working overtime, further confirming the impact of work-life imbalance on retention.

---

## 🛠️ 4. Data Engineering & Methodology
To ensure high data integrity, the following preprocessing steps were conducted:
* **Data Auditing:** Performed a thorough check for missing values and outliers in salary columns.
* **Metric Calculation:** Developed custom measures to calculate **Attrition Rate** and **Retention Percentages**.
* **Categorical Binning:** Grouped employees by Age, Education Field, and Income levels to identify specific "Risk Groups".
* **Visualization:** Built an interactive dashboard using **Advanced Excel/Pivot Tables** to allow for dynamic filtering by Department and Gender.

---

## 💡 5. Strategic Recommendations
1. **Targeted Retention:** Implement stay-interviews for employees in the **$2k - $5k income bracket** to address compensation concerns.
2. **Travel Policy:** Review travel requirements for roles with high "Travel Frequency" to mitigate burnout.
3. **Engagement Programs:** Launch engagement initiatives for employees with **5-10 years of tenure** to prevent mid-career exits.

---

## 📂 Project Structure
* `HR-Employee-Attrition.csv`: Raw HR dataset.
* `HR_Attrition_Dashboard.jpg`: Final dashboard visualization.
