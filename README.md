<div align="center">

# 📊 Employee Attrition Analytics

### Uncovering why employees leave — and what the business can do about it

<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" />
<img src="https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" />
<img src="https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge" />
<img src="https://img.shields.io/badge/Seaborn-3776AB?style=for-the-badge" />

</div>

---

## 📌 Overview

This project analyzes the **IBM HR Employee Attrition dataset** (1,470 employees, 35 attributes)
to understand **why employees leave**, and to turn that understanding into an
**interactive Power BI dashboard** with clear, actionable business recommendations.

The project covers the full analytics workflow:

```
Raw Data → Cleaning → Exploratory Analysis (Python) → Visualizations → Power BI Dashboard → Business Insights
```

---

## 🎯 Objectives

- Clean and prepare the raw HR dataset for analysis
- Analyze employees by **department** and **job role**
- Study **salary, experience, and performance** patterns
- Measure **employee satisfaction** across multiple dimensions
- Identify the strongest **drivers of attrition** (Overtime, Job Satisfaction, Work-Life Balance)
- Build an **interactive Power BI dashboard** with KPIs for business stakeholders

---

## 🗂️ Dataset

| Property | Value |
|---|---|
| Rows | 1,470 employees |
| Original columns | 35 |
| Missing values | 0 |
| Duplicate rows | 0 |
| Target variable | `Attrition` (Yes / No) |

---

## 🧹 Data Cleaning

- Verified there are **no missing values** and **no duplicate rows**

---

## 🐍 Python Analysis

Built entirely with **pandas, numpy, matplotlib, and seaborn**. The analysis is organized into 5 stages:

<table>
<tr><td width="30%"><b>1. Departments & Job Roles</b></td>
<td>Employee distribution and attrition rate per Department and per Job Role</td></tr>
<tr><td><b>2. Salary, Experience & Performance</b></td>
<td>Average income by role, income-vs-experience correlation, performance by department</td></tr>
<tr><td><b>3. Satisfaction Analysis</b></td>
<td>Job / Environment / Relationship Satisfaction and Work-Life Balance distributions</td></tr>
<tr><td><b>4. Attrition Drivers</b></td>
<td>Attrition rate broken down by Overtime, Job Satisfaction, and Work-Life Balance</td></tr>
<tr><td><b>5. Correlation Heatmap</b></td>
<td>Relationships between age, income, tenure, satisfaction, and attrition</td></tr>
</table>

---

## 📈 Power BI Dashboard

<div align="center">

<img src="Home.jfif" width="700"/>

<br/><br/>

<img src="Overview.jfif" width="420"/> <img src="Departmenrs.jfif" width="420"/>

<br/><br/>

<img src="Performance.jfif" width="420"/> <img src="WhyAttrition.jfif" width="420"/>

</div>

**Pages included:**
- 🏠 **Home** — navigation landing page
- 📊 **Overview** — Total Employees, Attrition Rate, Attrition by Overtime, Avg Income by Marital Status, Avg Age by Gender
- 🏢 **Departments** — Attrition Rate by Job Role & Department, income/satisfaction breakdown table
- 📈 **Performance** — Income vs. Experience scatter, Avg Income by Education Field
- ❓ **Why Attrition?** — Attrition rate by all 4 satisfaction indicators

---

## 💡 Key Business Insights

| Metric | Value |
|---|---|
| Overall attrition rate | **16.12%** (237 of 1,470 employees) |
| Attrition rate — with Overtime | **30.5%** |
| Attrition rate — without Overtime | **10.4%** |
| Highest-attrition department | **Sales (20.6%)** |
| Highest-attrition job role | **Sales Representative (39.8%)** |
| Income ↔ Experience correlation | **0.77** |
| Avg. Performance Rating (company-wide) | **3.15 / 4** |

### 🔑 Top findings

- **Overtime is the strongest single driver of attrition** — employees working overtime leave at nearly **3x** the rate of those who don't.
- **Sales Representatives** are the single highest-risk group in the company (39.8% attrition), earning the **lowest average income** of any role (~$2,626/month) despite comparable performance ratings to other roles (~3.1/4 company-wide).
- **Satisfaction and attrition move in opposite directions** across every indicator — Job Satisfaction, Environment Satisfaction, Relationship Satisfaction, and Work-Life Balance.
- **Compensation grows strongly with tenure** (0.77 correlation), meaning junior / low-tenure employees — like most Sales Representatives — are structurally paid less, compounding their flight risk.

### ✅ Recommendation

> Prioritize **reducing mandatory overtime** and **improving compensation and work-life balance for the Sales Representative role** — this single group represents the company's largest, most fixable attrition risk.

---

## 📁 Repository Structure

```
├── employee_attrition.csv                  # Raw dataset           
├── analysis.py                              # Full Python EDA script
├── Employee_Attrition_Insights_Report.docx  # Written insights report
├── Task3_Voltix.pbix                        # Power BI dashboard file
├── images/                                  # Dashboard screenshots for this README
└── README.md
```

---

## 🚀 How to Run

```bash
pip install pandas numpy matplotlib seaborn
python analysis.py
```

This regenerates the  dataset 

For the dashboard, open **`Task3_Voltix.pbix`** in Power BI Desktop.

---

<div align="center">

Made with 🐍 Python + 📊 Power BI

</div>
<!-- Connect with me Section -->
<h3>📫 Connect with me</h3>
<p align="center">
  <a href="https://www.linkedin.com/in/alaa-ramadan-" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="https://www.kaggle.com/alaaaymanramadan" target="_blank">
    <img src="https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=Kaggle&logoColor=white" alt="Kaggle" />
  </a>
  <a href="https://github.com/Alaa-Ramadan-Elsaidy" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
  </a>
</p>

</div>
