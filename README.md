--- 

# Hi, I’m Deva Kiran Geddam 👋

# Four years of production data work — Google Maps scale, last-mile logistics, disease surveillance.

I don't just write queries. I build the pipelines, dashboards, and models that operations teams actually use to make decisions.

---
## 📌 Featured Projects


### 🏥 Hantavirus Clinical Analysis — SQL Server + Tableau

> Clinical outcomes · Outbreak detection · Diagnosis lag · Geographic ICU access scoring

<!-- 
  📸 ADD YOUR IMAGE HERE
  Step 1: Take a screenshot of your best Tableau dashboard or SQL query output
  Step 2: Create a folder called 'assets' in this repo
  Step 3: Upload the screenshot as 'assets/hantavirus-dashboard.png'
  Step 4: Delete this comment block and the placeholder below
-->

![Hantavirus Dashboard Preview](assets/hantavirus-dashboard.png)

6 production-ready analytical insights built on a multi-table public health dataset in SQL Server Management Studio, visualized in Tableau.

**Key SQL techniques used:**

- `NTILE()` quartile ranking for severity tier classification, `PERCENTILE_CONT` for continuous distribution analysis, `LAG()` for temporal drift and diagnosis lag detection, Conditional aggregation for Case Fatality Rate (CFR) calculation, `NULLIF` zero-division protection across all rate calculations, CTE structuring for multi-step analytical pipelines, `CAST` for BIT-to-INT conversion in comorbidity scoring

**Insights delivered:**

| # | Insight | Technique |
|---|---------|-----------|
| 1 | Intervention Stack Score vs. Clinical Outcome | Conditional aggregation + CASE |
| 2 | Treatment Protocol Effectiveness by Severity | GROUP BY + CFR calculation |
| 3 | Diagnosis Lag vs. Mortality | NTILE quartile ranking |
| 4 | Comorbidity + Viral Load Compound Risk Matrix | Multi-join + risk scoring |
| 5 | Length of Stay Anomaly Detection | LAG + window functions |
| 6 | Geographic Setting Penalty on ICU Access | RANK + geographic grouping |

🔗 [View Repository →](https://github.com/devakiran046/Hantavirus-Clinical-Analysis)

---

### ❤️ Heart Disease Prediction — Python + Machine Learning

> Logistic Regression · scikit-learn · Clinical Feature Analysis · Healthcare ML

<!-- 
  📸 ADD YOUR IMAGE HERE
  Step 1: Take a screenshot of your model accuracy output, confusion matrix, or feature importance chart from Jupyter
  Step 2: Create a folder called 'assets' in this repo (same folder as above)
  Step 3: Upload the screenshot as 'assets/heart-disease-model.png'
  Step 4: Delete this comment block and the placeholder below
-->
End-to-end machine learning classification pipeline built in Python to predict cardiovascular disease risk from clinical patient data.

**Stack:** Python · pandas · NumPy · scikit-learn · Jupyter Notebook · Matplotlib · Seaborn

**What's in this project:**

- Exploratory Data Analysis (EDA) on clinical features: age, cholesterol, resting BP, chest pain type, max heart rate, Data preprocessing: null handling, feature encoding, train-test split, Logistic Regression classification model with accuracy evaluation, Confusion matrix and classification report for model performance, Feature importance analysis to identify top predictors of heart disease risk

**Why it matters:** The same analytical thinking that detects anomalies in a logistics pipeline also detects risk patterns in clinical data — this project demonstrates the crossover from operational analytics to healthcare predictive modeling.

🔗 [View Repository →](https://github.com/devakiran046/Heart-Disease-prediction)

---

### 🛍️ Christmas Retail Sales Analysis — SQL + Power BI / Tableau

> Seasonal Trend Analysis · Revenue KPIs · Customer Behavior · Retail Analytics

<!-- 
  📸 ADD YOUR IMAGE HERE
  Step 1: Take a screenshot of your Power BI or Tableau dashboard, or your key SQL output
  Step 2: Create a folder called 'assets' in this repo (same folder as above)
  Step 3: Upload the screenshot as 'assets/christmas-retail-dashboard.png'
  Step 4: Delete this comment block and the placeholder below
-->

![Christmas Retail Dashboard Preview](assets/christmas-retail-dashboard.png)

Retail sales analysis focused on Christmas season performance — revenue trends, product category breakdown, customer purchasing behavior, and seasonal KPI tracking.

**What this project covers:**

- Revenue and transaction volume analysis across the holiday season, Product category performance and top SKU identification, Customer segmentation by purchase frequency and spend, Seasonal trend comparison (pre-Christmas vs peak vs post-Christmas), KPI dashboard: Total Revenue · Avg Order Value · Units Sold · Customer Count

**Domain relevance:** Retail and eCommerce analytics is one of the highest-demand areas for Data Analyst and BI Developer roles. This project demonstrates the ability to translate raw sales data into the business metrics that drive stocking, pricing, and marketing decisions.

🔗 [View Repository →](https://github.com/devakiran046/Christmas-Retail-Sales-Analysis-)

---

## 🔧 What I Build

| Layer | Tools |
|---|---|
| **Analytics & SQL** | SQL Server (SSMS) · MySQL · Window Functions · CTEs · Statistical Analysis |
| **Machine Learning** | Python · pandas · NumPy · scikit-learn · Logistic Regression · Random Forest |
| **BI & Visualization** | Power BI (PL-300) · DAX · Tableau · KPI Dashboard Design |
| **Cloud & ETL** | Snowflake · Azure · ETL Pipelines · Star Schema Design |
| **Domains** | Healthcare Analytics · Retail & eCommerce · Logistics (WMS/TMS) · Operations |
## 🛠 Tech Stack

**Languages**

![SQL](https://img.shields.io/badge/SQL-SQL%20Server%20%7C%20MySQL-blue?style=flat-square)
![Python](https://img.shields.io/badge/Python-pandas%20%7C%20NumPy%20%7C%20scikit--learn-3776AB?style=flat-square&logo=python&logoColor=white)

**BI & Visualization**

![Power BI](https://img.shields.io/badge/Power%20BI-PL--300%20Certified-F2C811?style=flat-square&logo=powerbi&logoColor=black)
![Tableau](https://img.shields.io/badge/Tableau-Certified-E97627?style=flat-square&logo=tableau&logoColor=white)

**Cloud & Data Engineering**

![Snowflake](https://img.shields.io/badge/Snowflake-ETL%20%7C%20Data%20Modeling-29B5E8?style=flat-square&logo=snowflake&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-Cloud%20%7C%20Kubernetes-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)

**Tools**

![SSMS](https://img.shields.io/badge/SSMS-SQL%20Server%20Management%20Studio-CC2927?style=flat-square)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=flat-square&logo=jupyter&logoColor=white)
![Git](https://img.shields.io/badge/Git-GitHub-181717?style=flat-square&logo=github&logoColor=white)

---

## 📈 GitHub Stats

![Deva's GitHub Stats](https://github-readme-stats.vercel.app/api?username=devakiran046&show_icons=true&theme=default&hide_border=true&include_all_commits=true&count_private=false)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=devakiran046&layout=compact&theme=default&hide_border=true)

---

## 🎓 Background

**MS Business Analytics** — Lewis University (GPA 3.9 · Expected Dec 2026)
Concentration: Operations & Supply Chain Management · WMS · TMS · YMS systems

**3.5 years at Cognizant**
- Technical Lead, Google Maps back-end data operations — accuracy-critical, global scale
- Logistics analytics for Ekart (Flipkart subsidiary) — WMS/TMS, last-mile delivery performance

**Certifications:**
- Microsoft Power BI Data Analyst Associate (PL-300)
- IBM Data Analyst Professional Certificate
- Tableau Certified

---

## 📬 Currently Interviewing For

**Data Analyst · BI Developer · Healthcare Data Analyst** — Chicago, IL (open to remote)

If your team runs on SQL, Python, or Power BI and you need someone who owns the pipeline and the dashboard layer:

📧 devakirangeddam@gmail.com
🔗 [linkedin.com/in/devakirangeddam](https://linkedin.com/in/devakirangeddam)

---

<!-- PROJECTS-LIST -->

## My Projects
- [devakiran046](https://github.com/devakiran046/devakiran046)
- [Python-BI-dashboard-](https://github.com/devakiran046/Python-BI-dashboard-)
- [World-Seasons-Analysis-Dashboard-in-Power-BI](https://github.com/devakiran046/World-Seasons-Analysis-Dashboard-in-Power-BI)
