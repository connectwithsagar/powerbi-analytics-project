# 🏥 Healthcare Analytics Dashboard (Power BI)

## Overview
This project is an interactive **Healthcare Analytics Dashboard** built in **Power BI** to analyze patient records, billing trends, medical conditions, and insurance insights.

The dashboard transforms healthcare data into actionable insights through KPIs, interactive visuals, and trend analysis.

---

## Tools & Technologies
- Power BI
- SQL
- DAX
- Power Query
- Data Visualization

---

## Dataset Information
The dataset includes healthcare-related information such as:

- Patient demographics
- Age Groups
- Gender
- Admission Types
- Medical Conditions
- Test Results
- Billing Amount
- Insurance Providers
- Blood Groups
- Admission Dates
- Average Hospital Stay

---

## Dashboard Features

### KPI Cards
- Total Patients: **55.50K**
- Average Stay: **15.51 Days**
- Billing Amount: **1.42 Billion**

### Interactive Visualizations
- Patient Distribution by Age Group
- Admission Type by Medical Condition
- Insurance Provider Analysis
- Year-wise Admission Trends
- Gender Filter
- Blood Group Filter

---

## Dashboard Preview

![Healthcare Dashboard](screenshots/dashboard.png)

---

## Insights Generated
### Patient Analysis
- Highest patient count belongs to 66+ age group.
- Lower admissions in 0–18 age group.

### Medical Insights
- Conditions analyzed:
  - Arthritis
  - Diabetes
  - Hypertension
  - Obesity
  - Cancer
  - Asthma

### Financial Insights
- Billing amount analysis by patients.
- Insurance provider distribution comparison.

### Trend Analysis
- Yearly admissions trend from 2019–2024.
- Age-group based admission patterns.

---

## Project Structure

```bash
healthcare-powerbi-dashboard/
│
├── DashBoard.pbix
├── healthcare_dataset.csv
├── screenshots/
│   └── dashboard.png
└── README.md
```

---

## SQL Use Cases (Optional)
SQL was used for:
- Data extraction
- Aggregations
- Data cleaning
- Joins and preprocessing

Example:
```sql
SELECT medical_condition,
COUNT(*) as patients
FROM healthcare_data
GROUP BY medical_condition;
```

---

## How to Run
1. Clone repository

```bash
git clone https://github.com/yourusername/healthcare-powerbi-dashboard.git
```

2. Open:
```text
DashBoard.pbix
```

3. Explore dashboard using slicers and filters.

---

## Future Improvements
- Predictive healthcare analytics
- Disease forecasting
- Real-time dashboard integration
- Advanced DAX KPIs

---

## Skills Demonstrated
- Data Analysis
- Power BI Dashboarding
- SQL Querying
- DAX Calculations
- Business Intelligence
- Healthcare Analytics

---

## Author
**Sagar Singh**

If you found this project useful, give it a ⭐
