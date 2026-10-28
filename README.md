# Taofeek Salami | Data Analyst

I analyse customer, product and credit-risk data to help teams make better-informed decisions. My work spans SQL, Python, Excel and Tableau—from data-quality checks and statistical analysis to clear findings and practical recommendations.

**Focus areas:** Credit Risk Analytics · Product Analytics · CRM & Customer Analytics  
**Location:** Ilorin, Nigeria (WAT, UTC+1) · **Availability:** Remote · Full-time or contract

[![Portfolio](https://img.shields.io/badge/Portfolio-taofeeksalami.com-1F2937?style=for-the-badge)](https://taofeeksalami.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/taofeek-salami-460a93245)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:salamitaofeek92@gmail.com)
[![DataCamp Certified](https://img.shields.io/badge/DataCamp-Certified%20Associate%20Data%20Analyst-05192D?style=for-the-badge)](https://www.datacamp.com/certificate/DAA0015344805241)

---

## How I Approach Analysis

- **Start with the decision.** Define the business question, success measures and decision criteria before interpreting results.
- **Validate before reporting.** Check row counts, joins, filters and calculated metrics against their underlying outputs.
- **Make limitations visible.** Distinguish what the data supports from what it cannot establish.
- **Document the process.** Use a phase-based workflow and a figure-checking script in my [Data Analysis Playbook](https://github.com/HarjiiBoss/analytics-playbook).

---

## Featured Projects

### 🎮 Cookie Cats A/B Test — Should the First Gate Stay at Level 30?
*BigQuery SQL · Python · SciPy · statsmodels · Tableau*

Analysed an A/B test involving 90,189 mobile-game players to assess whether moving the first progression gate from level 30 to level 40 affected seven-day retention. Decision criteria were defined before the outcome data was examined.

- Seven-day retention was **19.0%** for the level-30 group and **18.2%** for the level-40 group—a difference of **−0.8 percentage points** for level 40 (95% CI: −1.3 to −0.3 percentage points; *p* = 0.002).
- **Recommendation:** Keep the first gate at level 30 based on the retention evidence.
- Checked the result with a sample-ratio test, power analysis, a bootstrap confidence interval and three sensitivity checks.
- **Scope limitation:** The analysis evaluates retention, not revenue or in-app purchases.

[Repository](https://github.com/HarjiiBoss/cookie-cats-ab-test) · [Project page](https://taofeeksalami.com/cookie-cats-ab-test) · [Tableau dashboard](https://public.tableau.com/views/CookieCats-ShouldtheFirstGateStayatLevel30/CookieCatsShouldtheFirstGateStayatLevel30)

### 💳 Fintech Credit Risk Analysis
*SQL · MySQL · Python · pandas · scikit-learn · Tableau*

Built a bureau-independent behavioural risk segmentation and custom Exposure Index for 149,999 borrowers. This was the capstone project for the 3MTT Data Analysis & Visualization programme.

- The Critical behavioural-risk tier had a **47.11%** default rate, compared with **2.23%** in the Low tier. Borrowers classified as Critical on both risk and exposure had a **55.0%** default rate.
- Investigated placeholder delinquency codes rather than automatically discarding them. The 269 affected borrowers had a **54.65%** default rate.
- A logistic-regression model using the tiers achieved **0.83 AUC** on held-out data and identified **72% of defaulters** at the evaluated threshold.
- Missing income affected **19.82%** of borrowers; these records were retained in an explicit `Indeterminate` category rather than imputed.

[Repository](https://github.com/HarjiiBoss/fintech-credit-risk-analysis) · [Project page](https://taofeeksalami.com/fintech-credit-risk-analysis) · [Tableau dashboard](https://public.tableau.com/views/FintechCreditRiskAnalysisDashboard/DB01-ExecutiveOverview) · [Live risk check](https://f4872123.mydala.app)

### 📉 Telco Customer Churn Analysis
*SQL · MySQL · Excel · Power Query*

Created 22 SQL queries and 17 analysis-ready datasets to support a four-dashboard Excel reporting suite covering customers, revenue and churn risk.

- Overall churn rate was **26.54%**.
- **55.5%** of churned customers (1,037 of 1,869) left within their first 12 months.
- Month-to-month customers had a **42.71%** churn rate.
- Fibre-optic customers contributed **62.11%** of monthly revenue and had the highest service-level churn rate (**41.89%**).
- Churned customers represented approximately **£1.67M in annualised charges**, equivalent to 30.50% of monthly charges on an annualised basis.

[Repository](https://github.com/HarjiiBoss/Telco_Customer_Churn_Analysis) · [Project page](https://taofeeksalami.com/Telco_Customer_Churn_Analysis)

---

## More Projects

### 🚚 Logistics Operations Performance Analysis
*Python · pandas · SciPy · Tableau · TS Academy capstone*

Analysed more than 85,000 trip records across 14 tables, covering drivers, routes and fleet maintenance.

- On-time delivery rate was **44.6%**; a chi-square test found no statistically significant difference between drivers and the fleet overall (*p* = 0.41).
- Traced an apparent **−609% route margin** to a faulty fuel join. After estimating fuel cost from gallons used, route-level revenue remaining after fuel ranged from **59% to 78%** (median **72.0%**).
- Analysed **$5.7M** in maintenance spend across 120 trucks; the highest-cost 10% of trucks accounted for **15.2%** of spend.

[Repository](https://github.com/HarjiiBoss/logistics-analysis) · [Project page](https://taofeeksalami.com/logistics-analysis) · [Tableau dashboard](https://public.tableau.com/app/profile/taofeek.salami/viz/LogisticsOperation/LogisticsOperationsDashboard)

### 🛒 Superstore Sales Database Exploration
*Python · MySQL · SQLAlchemy · pandas · Matplotlib*

Designed a normalised MySQL schema and Python/SQLAlchemy ETL pipeline for 8,399 order lines from 2009–2012, then used pandas to answer 10 business questions.

- **50.8%** of order lines were loss-making despite **$14.9M** in revenue.
- Furniture generated a **2.3%** margin on **$5.18M** in sales; Tables recorded a **$99.1K loss**.
- December and January accounted for **9.84%** and **9.69%** of sales, respectively.

[Repository](https://github.com/HarjiiBoss/Superstore_Database) · [Project page](https://taofeeksalami.com/Superstore_Database)

### 📈 Quantium Chip Category & Trial Store Uplift
*Python · pandas · Forage job simulation*

- Cleaned 264,836 transactions to 245,302 chip purchases and joined them with 72,637 loyalty-customer records.
- Budget Older Families were the highest-selling segment, with **$156K** in sales.
- Matched trial stores to control stores using correlation; Store 77 showed the strongest observed result, with **33.5% sales uplift**.

[Repository](https://github.com/HarjiiBoss/forage-quantium-data-analytics) · [Project page](https://taofeeksalami.com/forage-quantium-data-analytics)

### 👥 Northwind — Employee Performance & Sales Analysis
*SQL · MySQL*

- The three busiest employees processed **100 of 196 orders (51%)**; the busiest active employee processed 6.7 times as many orders as the least busy.
- **52 of 74 customers (70%)** placed repeat orders.
- **82%** of same-country supplier pairs were in the USA and Europe.

[Repository](https://github.com/HarjiiBoss/Employee-Performance-Sales-Analysis) · [Project page](https://taofeeksalami.com/Employee-Performance-Sales-Analysis)

### 🧾 Northwind — Customer & Product Performance Analysis
*SQL · MySQL*

- **17 customers** had never placed an order: nine in Europe, six in North America and two in Argentina.
- Product prices ranged from **$2.50 to $263.50**; the average was **$28.87**.
- The top 10 customers placed **62 orders**.

[Repository](https://github.com/HarjiiBoss/northwind-customer-analysis) · [Project page](https://taofeeksalami.com/northwind-customer-analysis)

---

## Skills & Tools

| Area | Skills and tools |
|---|---|
| **SQL & databases** | SQL, MySQL, Google BigQuery, joins, CTEs, window functions, subqueries |
| **Python & analysis** | pandas, NumPy, SciPy, statsmodels, scikit-learn, Matplotlib, seaborn, SQLAlchemy, Jupyter |
| **Statistics** | A/B testing, hypothesis testing, confidence intervals, power analysis, bootstrap methods, chi-square tests, logistic regression |
| **Reporting & visualisation** | Tableau, Excel dashboards, Power Query, PivotTables, executive summaries |
| **Workflow** | Git, GitHub, VS Code, MySQL Workbench, TablePlus |

---

## Certifications & Training

| Certification or programme | Issuer | Date |
|---|---|---|
| [Associate Data Analyst in SQL](https://www.datacamp.com/certificate/DAA0015344805241) | DataCamp | Jul 2026 |
| Data Analysis & Visualization programme (capstone: Fintech Credit Risk Analysis) | 3MTT (NITDA) | Sep 2026 |
| Data Analytics Programme (capstone: Logistics Operations Performance Analysis) | TS Academy | Jul 2026 |
| Job simulations: Quantium Data Analytics, Deloitte Australia Data Analytics, BCG Data for Decision Makers | Forage | May–Jun 2026 |
| Data Analytics Pathway (seven courses) | IBM SkillsBuild | Jan–Mar 2026 |

---

![GitHub Stats](github-metrics.svg)

---

## Contact

I'm open to **Data Analyst opportunities in credit risk, product and CRM/customer analytics**, including remote full-time and contract roles.

- **Email:** [salamitaofeek92@gmail.com](mailto:salamitaofeek92@gmail.com)
- **LinkedIn:** [taofeek-salami](https://linkedin.com/in/taofeek-salami-460a93245)
- **Portfolio:** [taofeeksalami.com](https://taofeeksalami.com) — project pages, dashboards and certificates
