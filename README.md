# 🏥 Hospital Emergency Room Analytics Dashboard

An interactive **Microsoft Excel dashboard** developed to analyze hospital emergency-room operations, patient flow, waiting times, admission patterns, satisfaction, demographics, and department referrals.

## 📊 Project Overview

The project analyzes **9,216 emergency-room patient records** covering the period from **April 2023 to October 2024**.

The objective was to transform raw patient-level data into an interactive dashboard that helps understand emergency-room activity and operational patterns.

## 🎯 Business Questions

The dashboard was designed to answer questions such as:

* How many patients visited the emergency room?
* What is the average patient waiting time?
* How many patients were admitted?
* How many patients experienced delays?
* How does patient satisfaction change over time?
* Which departments receive the highest number of referrals?
* What is the distribution of patients across age groups?
* How is the patient population distributed by gender?
* Are there noticeable daily or monthly patterns in patient volume?

## 📈 Key Metrics

| Metric                      |         Value |
| --------------------------- | ------------: |
| Total Patients              |         9,216 |
| Male Patients               |         4,729 |
| Female Patients             |         4,487 |
| Admitted Patients           |         4,612 |
| Non-Admitted Patients       |         4,604 |
| Average Wait Time           | 35.26 minutes |
| On-Time Attendance          |         3,749 |
| Delayed Attendance          |         5,467 |
| Satisfaction Responses      |         2,517 |
| Average Satisfaction Score* |     4.99 / 10 |

*Average satisfaction is calculated only for records where a satisfaction score is available.

## 🔍 Analysis Areas

### Patient Flow

* Total patient volume
* Daily patient trends
* On-time vs. delayed attendance
* Admission status

### Waiting Time

* Average waiting time
* Daily waiting-time trends
* Identification of higher waiting-time periods

### Patient Satisfaction

* Satisfaction-score analysis
* Daily satisfaction trends
* Relationship between operational performance and satisfaction

### Demographics

* Gender distribution
* Age-group distribution
* Patient demographic analysis

### Department Analysis

* Referral department distribution
* Comparison of patient demand across departments

## 🛠️ Tools & Techniques

* Microsoft Excel
* Data Cleaning
* Data Transformation
* PivotTables
* PivotCharts
* Calculated Fields
* Dashboard Design
* KPI Analysis
* Trend Analysis
* Data Visualization

## 📁 Workbook Structure

The workbook contains several analytical layers:

* **Hospital Emergency Room Data** — source patient data
* **Transform Data** — transformed and analysis-ready dataset
* **Pivot Table** — supporting calculations and summaries
* **Dashboard** — final interactive dashboard
* **Satisfaction Score** — satisfaction trend analysis
* **Average Wait Time** — waiting-time analysis
* **Additional analysis sheets** — supporting calculations and visualizations

## 💡 Key Observations

Based on the full transformed dataset:

* The dataset contains **9,216 unique patient records**.
* The average recorded waiting time is approximately **35.26 minutes**.
* Admission and non-admission volumes are relatively close.
* Delayed attendance is higher than on-time attendance in the full dataset.
* General Practice represents the largest referral category among the named departments.
* Satisfaction scores are available for only a subset of patients, so satisfaction analysis should be interpreted separately from the full patient population.

## 🚀 Project Workflow

```text
Raw Hospital Data
       ↓
Data Cleaning & Transformation
       ↓
Derived Fields
       ↓
PivotTable Analysis
       ↓
KPI Calculation
       ↓
Charts & Visualizations
       ↓
Interactive Excel Dashboard
       ↓
Operational Insights
```

## 📷 Dashboard Preview

Add your final dashboard screenshot here:

<img width="1477" height="602" alt="Dashboard_Preview" src="https://github.com/user-attachments/assets/84509af0-16f8-4230-bd80-a099b18a7812" />


## ⚠️ Data Privacy

The workbook contains patient-level fields and identifiers. Before publishing this project publicly, remove or anonymize any patient IDs, names, or other potentially identifying information.

For the public GitHub repository, use a sanitized dataset or screenshots rather than uploading the original patient-level workbook.

## 👤 Author

**Abhinav Vaidhya**

Aspiring Data Analyst | Excel | SQL | Power BI | Python
