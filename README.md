# 👥 HR Employee Attrition Analysis
### A 3-Page Interactive Power BI Dashboard

> **What really drives employees to leave?** This project analyses 1,470 IBM employee records across 35 variables to uncover the true drivers behind a 16.1% company-wide attrition rate — proving that overtime, low pay, and poor work-life balance are far more powerful predictors than most organisations realise.

<br>

---


## 🎯 Business Problem

Employee attrition is one of the most costly and disruptive challenges any organisation faces. Replacing a single employee costs between **50% and 200% of their annual salary** — yet most HR teams rely on gut feel and exit interviews that come too late and capture too little.

**This dashboard shifts the conversation from reactive to data-driven by answering six core business questions:**

1. What is the overall attrition rate, and which department has the highest exits?
2. Do employees who work overtime leave at a significantly higher rate?
3. Is there a relationship between job satisfaction score and attrition?
4. Which salary band has the highest attrition — are underpaid employees more likely to quit?
5. Does years of experience reduce the chance of an employee leaving?
6. Which job roles show the highest attrition, and what do they have in common?

---

## 📊 Dashboard Preview

### Page 1 — What is Happening? (Overview)
> *Business question: What is the overall attrition rate, and which department has the highest exits?*

![Page 1 — Overview](screenshots/page1_overview.png)

---

### Page 2 — Why is it Happening? (Drivers)
> *Business question: Overtime vs attrition · Job satisfaction vs attrition · Salary band vs attrition*

![Page 2 — Drivers](screenshots/page2_drivers.png)

---

### Page 3 — Where Should HR Intervene First? (Risk/Action)
> *Business question: Does experience reduce attrition? · Which job roles have highest exits? · What do they have in common?*

![Page 3 — Risk & Action](screenshots/page3_risk_action.png)

---

## 🔍 Key Findings

| # | Finding | Data Point |
|---|---------|------------|
| 1 | **1 in every 6 employees left the company** | 237 exits out of 1,470 — **16.12%** attrition rate |
| 2 | **Sales bleeds talent fastest** | Sales: **20.63%** · HR: **19.05%** · R&D: **13.84%** |
| 3 | **Overtime is the single strongest attrition driver** | Overtime: **30.53%** vs No Overtime: **10.44%** — a **3× gap** |
| 4 | **Poor work-life balance drives the most exits** | Poor balance: **31.25%** vs Very Good: **14.22%** |
| 5 | **Underpaid employees quit at nearly 3× the rate** | Under $3K/mo: **28.61%** vs Over $9K: **10.21%** |
| 6 | **Low job satisfaction doubles attrition risk** | Score 1 (Low): **22.84%** vs Score 4 (Very High): **11.33%** |
| 7 | **Experience is the strongest retention factor** | 0–2 yrs: **43.90%** → 20+ yrs: **7.73%** — a 5.7× difference |
| 8 | **Sales Representatives are the highest-risk role** | **39.76%** — **16× higher** than Research Directors at 2.50% |
| 9 | **Sales Rep + Overtime = the most dangerous combination** | **66.67%** attrition — the highest single data point in the dataset |
| 10 | **Leavers earned $2,046 less per month than stayers** | Avg leaver income: **$4.79K** vs stayers across all roles |

---

## 📋 Dashboard Pages

### Page 1 — What is Happening? (Overview)

**Navigation label:** Overview  
**Slicers:** Gender · Marital Status

| Element | Detail | Insight |
|---------|--------|---------|
| KPI — Overall Attrition Rate | **16.12%** | 1 in 6 employees left — well above healthy 10% benchmark |
| KPI — Avg Employee Salary | **$6.50K** | Baseline salary context for the full workforce |
| KPI — Total Employees | **1.47K** | Full company headcount |
| KPI — Avg Job Satisfaction | **2.73/4.0** | Below midpoint — the workforce is not satisfied overall |
| Donut Chart | 237 Yes · 1,233 No | 1 in every 6 employees left — 237 out of 1,470 total |
| Bar Chart | Attrition by Department | Sales has the highest exit rate — over 20% of the department left |
| Column Chart | Attrition by Age Band | Employees aged 18–25 have the highest attrition rate at 35.77% |
| Matrix Table | Attrition by Gender & Department | Female attrition peaks in Human Resources at 30.00% |
| Column Chart | Attrition by Tenure Band | Employees in their first 2 years are 3× more likely to leave (29.82%) |

---

### Page 2 — Why is it Happening? (Drivers)

**Navigation label:** Drivers  
**Slicers:** Salary Band · Work Life Balance Level

| Element | Detail | Insight |
|---------|--------|---------|
| KPI — Under $3K Employees | **395** | Size of the single highest-risk salary group |
| KPI — Poor WLB Attrition | **31.25%** | Highest attrition of any work-life balance category |
| KPI — Overtime Attrition | **30.53%** | Nearly 3× the non-overtime rate of 10.44% |
| Scatter Plot | Avg Income vs Avg Job Satisfaction coloured by Attrition | Yes cluster sits bottom-left — low pay AND low satisfaction compound the risk |
| Bar Chart | Work-Life Balance vs Attrition | Poor: 31.25% · Excellent: 17.65% · Good: 16.86% · Very Good: 14.22% |
| Bar Chart | Salary Band vs Attrition | Under $3K: 28.61% · $3K–$6K: 12.72% · $6K–$9K: 10.76% · Over $9K: 10.21% |
| Donut Chart | Overtime vs No Overtime exits | Overtime employees contribute 74.52% of all exits despite being a minority |
| Bar Chart | Job Satisfaction vs Attrition | Low: 22.84% · High: 16.52% · Medium: 16.43% · Very High: 11.33% |

---

### Page 3 — Where Should HR Intervene First? (Risk/Action)

**Navigation label:** Risk Dive  
**Slicers:** Experience Band · Work Life Balance Level

| Element | Detail | Insight |
|---------|--------|---------|
| KPI — Sales Rep OT Attrition | **66.67%** | Highest-risk combination in the entire dataset |
| KPI — Early Tenure Risk (0–2 yrs) | **43.90%** | Nearly half of all new employees leave |
| KPI — Avg Income Leavers | **$4.79K** | Leavers earn significantly less than those who stayed |
| KPI — Avg Years Experience | **11.28** | Average career experience across the workforce |
| Bar Chart | Attrition by Job Role | Sales Rep: 39.76% — 16× higher than Research Directors at 2.50% |
| Line Chart | Attrition by Experience Band | 43.90% → 9.17% → 14.99% → 11.47% → 7.73% — steep drop after 2 years |
| Grouped Bar | Income: Leavers vs Stayers per Role | In every single role, leavers earned less than those who stayed |
| Matrix Heatmap | Job Role × Overtime attrition | Sales Rep + OT: **66.67%** · Lab Tech + OT: **50.00%** in red |

---

## 📁 Data Overview

| Property | Detail |
|----------|--------|
| **Dataset** | IBM HR Analytics Employee Attrition & Performance |
| **Total records** | 1,470 employees |
| **Total features** | 35 original columns |
| **Attrition — Yes** | 237 employees (16.12%) |
| **Attrition — No** | 1,233 employees (83.88%) |
| **Missing values** | None — clean dataset |
| **Data type** | Cross-sectional employee snapshot |

### Attrition by department

| Department | Headcount | Exits | Rate |
|------------|-----------|-------|------|
| Sales | 446 | 92 | **20.63%** |
| Human Resources | 63 | 12 | **19.05%** |
| Research & Development | 961 | 133 | **13.84%** |

### Attrition by job role

| Rank | Job Role | Rate |
|------|----------|------|
| 1 | Sales Representative | **39.76%** |
| 2 | Laboratory Technician | 23.94% |
| 3 | Human Resources | 23.08% |
| 4 | Sales Executive | 17.48% |
| 5 | Research Scientist | 16.10% |
| 6 | Manufacturing Director | 6.90% |
| 7 | Healthcare Representative | 6.87% |
| 8 | Manager | 4.90% |
| 9 | Research Director | **2.50%** |

### Overtime attrition breakdown by role

| Job Role | No Overtime | Overtime |
|----------|-------------|----------|
| Sales Representative | 28.81% | **66.67%** 🔴 |
| Laboratory Technician | 15.74% | **50.00%** 🔴 |
| Human Resources | 17.95% | 38.46% |
| Research Scientist | 7.18% | 34.02% |
| Sales Executive | 11.21% | 32.98% |
| Manager | 1.33% | 14.81% |
| Manufacturing Director | 5.66% | 10.26% |
| Research Director | 1.75% | 4.35% |
| Healthcare Representative | 7.45% | 5.41% |
| **Total** | **10.44%** | **30.53%** |

### Attrition by experience band

| Experience | Attrition Rate |
|------------|---------------|
| 0–2 years | **43.90%** |
| 3–5 years | 9.17% |
| 6–10 years | 14.99% |
| 11–20 years | 11.47% |
| 20+ years | **7.73%** |

---

## 🛠 Tools & Skills

| Tool / Skill | How I used it |
|---|---|
| **Power BI Desktop** | 3-page interactive dashboard · 22 visuals · sidebar navigation · conditional formatting · bookmarks · tooltip pages |
| **DAX** | 11 custom measures — filtered attrition rates, income comparisons, headcount calculations |
| **Power Query (M Language)** | 6 custom grouping columns — bands for age, tenure, salary, experience, satisfaction labels, attrition flag |
| **Data Cleaning** | Column type validation, sort order management via number prefixes, feature engineering |
| **HR Analytics** | Domain knowledge applied — satisfaction score interpretation, tenure risk, role-level attrition profiling |
| **Data Storytelling** | Every chart title states the business finding — insight-first design across all 3 pages |
| **Dashboard Design** | Consistent green branding · analyst photo · business question headers · 3-page narrative structure |
| **Advanced Power BI** | Bookmarks · tooltip pages · conditional colouring arrows on matrix · custom button navigation |

---

## 📐 DAX Measures

```dax
-- Core measure — powers all visuals
Attrition Rate =
  DIVIDE(
    COUNTROWS(FILTER('HR_Attrition', 'HR_Attrition'[Attrition] = "Yes")),
    COUNTROWS('HR_Attrition'), 0
  )

-- Page 1 KPI cards
Total Employees = COUNTROWS('HR_Attrition')

Total Exits =
  COUNTROWS(FILTER('HR_Attrition', 'HR_Attrition'[Attrition] = "Yes"))

Avg Employee Salary = AVERAGE('HR_Attrition'[MonthlyIncome])

Avg Job Satisfaction = AVERAGE('HR_Attrition'[JobSatisfaction])

-- Page 2 KPI cards
Overtime Attrition Rate =
  CALCULATE([Attrition Rate], 'HR_Attrition'[OverTime] = "Yes")

Poor WLB Attrition Rate =
  CALCULATE([Attrition Rate], 'HR_Attrition'[WorkLifeBalance] = 1)

Under 3K Employees =
  COUNTROWS(FILTER('HR_Attrition', 'HR_Attrition'[MonthlyIncome] < 3000))

-- Page 3 KPI cards
Sales Rep OT Attrition =
  CALCULATE(
    [Attrition Rate],
    'HR_Attrition'[JobRole] = "Sales Representative",
    'HR_Attrition'[OverTime] = "Yes"
  )

Early Tenure Attrition =
  CALCULATE([Attrition Rate], 'HR_Attrition'[TotalWorkingYears] <= 2)

Avg Income Leavers =
  CALCULATE(
    AVERAGE('HR_Attrition'[MonthlyIncome]),
    'HR_Attrition'[Attrition] = "Yes"
  )

Avg Years Experience = AVERAGE('HR_Attrition'[TotalWorkingYears])
```

---

## ⚙️ Power Query Columns

Six custom columns created in Power Query. Number prefixes force correct sort order — without them Power BI sorts bands alphabetically instead of logically.

```m
// AgeBand — from Age — Page 1
if [Age] <= 25 then "1. 18-25"
else if [Age] <= 35 then "2. 26-35"
else if [Age] <= 45 then "3. 36-45"
else if [Age] <= 55 then "4. 46-55"
else "5. 55+"

// TenureBand — from YearsAtCompany — Page 1
if [YearsAtCompany] <= 2 then "1. 0-2 yrs"
else if [YearsAtCompany] <= 5 then "2. 3-5 yrs"
else if [YearsAtCompany] <= 10 then "3. 6-10 yrs"
else if [YearsAtCompany] <= 20 then "4. 11-20 yrs"
else "5. 20+ yrs"

// SalaryBand — from MonthlyIncome — Page 2
if [MonthlyIncome] < 3000 then "1. Under $3K"
else if [MonthlyIncome] < 6000 then "2. $3K-$6K"
else if [MonthlyIncome] < 9000 then "3. $6K-$9K"
else "4. Over $9K"

// SatisfactionLabel — from JobSatisfaction — Page 2
if [JobSatisfaction] = 1 then "1. Low"
else if [JobSatisfaction] = 2 then "2. Medium"
else if [JobSatisfaction] = 3 then "3. High"
else "4. Very High"

// WorkLifeBalanceLabel — from WorkLifeBalance — Page 2
if [WorkLifeBalance] = 1 then "1. Poor"
else if [WorkLifeBalance] = 2 then "2. Good"
else if [WorkLifeBalance] = 3 then "3. Very Good"
else "4. Excellent"

// ExperienceBand — from TotalWorkingYears — Page 3
if [TotalWorkingYears] <= 2 then "1. 0-2 yrs"
else if [TotalWorkingYears] <= 5 then "2. 3-5 yrs"
else if [TotalWorkingYears] <= 10 then "3. 6-10 yrs"
else if [TotalWorkingYears] <= 20 then "4. 11-20 yrs"
else "5. 20+ yrs"
```

---


## 📄 Data Source

| Property | Detail |
|----------|--------|
| **Name** | IBM HR Analytics Employee Attrition & Performance |
| **Source** | [Kaggle](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset) |
| **Records** | 1,470 employees · 35 features |
| **Missing values** | None |
| **License** | Open Database License (ODbL) |
| **Note** | Fictional dataset created by IBM data scientists for analytical use |

---

## 🏆 Conclusion

This analysis confirms that **employee attrition is not random** — it follows clear, measurable patterns that HR teams can detect and act on before a resignation letter lands.

Three priority intervention areas emerge from the data:

**1. Overtime policy — the fastest win**
Employees on overtime leave at 30.53% vs 10.44% for those who don't. Sales Representatives on overtime hit 66.67%. Reducing mandatory overtime for these roles is the single highest-ROI retention action available.

**2. Compensation for under-$3K earners**
28.61% of employees earning under $3,000/month leave. The income gap between leavers and stayers is visible across every single job role. A targeted pay review for the lowest band costs far less than the 50–200% of annual salary needed to replace each person who walks out.

**3. Early tenure investment**
43.90% of employees with under 2 years of experience leave. A structured onboarding programme, 30/60/90-day manager check-ins, and clear career pathing for new hires would have the largest single impact on overall attrition numbers.

> *"Attrition is not a mystery. It is a measurement problem — and this dashboard solves it."*

---

## 🎨 Design Notes

| Element | Detail |
|---------|--------|
| **Colour palette** | Dark green headers · Light green KPI backgrounds · White card bodies |
| **Navigation** | Custom sidebar — Overview · Drivers · Risk Dive |
| **Chart titles** | All written as business conclusions — not chart descriptions |
| **Conditional formatting** | Red cells on overtime matrix · Up/down arrows on gender matrix |
| **Interactive elements** | Bookmarks · tooltip page · button-triggered risk profile card |
| **Branding** | Analyst photo + name (Fasanya Segun) on all 3 pages |

---

## 👤 About the Analyst

**Fasanya Segun** — Data Analyst, Lagos Nigeria

- 🔗 [LinkedIn](https://www.linkedin.com/in/segun-fasanya-879a943b1)
- 💻 [GitHub Portfolio](https://github.com/simplysmarty/data-analysis-portfolio)

*Open to remote roles — Junior Data Analyst · BI Analyst · People Analytics · Reporting Analyst*

---

*Built by Fasanya Segun · May 2026 · Power BI · DAX · Power Query · HR Analytics*
