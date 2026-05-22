
# Healthcare Patient Flow & Operational Analytics

## Project Overview

This project analyzes over 9,200 patient encounter records from a medium-sized hospital facility between September 2023 and December 2024. The objective of the analysis is to uncover operational inefficiencies, identify patient flow patterns, evaluate wait-time variability, and generate data-driven recommendations to improve healthcare service delivery.

The project focuses on real-world healthcare operational challenges including:

- Patient congestion
- Seasonal demand fluctuations
- Wait time instability
- Adult-centered healthcare utilization
- Emergency and overnight service pressure
- Operational resource planning

---

## Business Objectives

This analysis aims to support:

- Operational efficiency optimization
- Strategic staffing decisions
- Seasonal resource forecasting
- Patient throughput improvement
- Healthcare service planning
- Wait-time reduction strategies

---

## Tools & Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- Visual Studio Code

---

## Project Structure

```text
healthcare-patient-flow-analysis/
│
├── data/
│   └── healthcare_analytics_patient_flow_data.csv
│
├── notebooks/
│   └── patient_flow_analysis.ipynb
│
├── images/
│   └── charts/
│
├── README.md
├── requirements.txt
└── .gitignore
```

---

# Key Analyses Performed

## 1. Age Group Distribution Analysis

### Findings

- Patient ages ranged from 1 to 79 years.
- Adults aged 20–59 years represented the largest share of hospital utilization.
- Elderly patients accounted for approximately 25% of total visits.
- Findings suggest the hospital workload is predominantly adult-centered.

### Operational Insights

- High demand for adult medicine services
- Significant chronic disease management burden
- Increased outpatient and occupational healthcare utilization

### Recommendations

- Expand adult-focused triage capacity
- Increase outpatient and internal medicine staffing
- Develop hypertension and diabetes screening programs
- Improve geriatric accessibility and outreach services

---

## 2. Monthly Patient Visits Analysis

### Findings

- Elevated patient attendance occurred between April and October.
- Mid-year periods demonstrated sustained hospital congestion.
- Year-end decline may reflect seasonal behavioral changes and operational slowdowns.

### Operational Insights

- Strong seasonal demand patterns exist
- Peak periods require proactive planning

### Recommendations

- Increase staffing during peak months
- Improve inventory forecasting
- Avoid excessive leave approvals during high-demand periods
- Strengthen emergency preparedness capacity

---

## 3. Patient Congestion Analysis

### Findings

- Significant overnight congestion occurred between 00:00–05:59.
- Saturdays experienced the highest admission pressure.
- Overnight services appear heavily utilized.

### Operational Insights

- Emergency care demand is substantial
- Nighttime staffing shortages may exist
- Overnight workflow pressure affects operations

### Recommendations

- Strengthen overnight staffing
- Expand emergency support services
- Optimize overnight triage systems
- Redistribute workforce toward night coverage

---

## 4. Patient Wait Time Variability Analysis

### Findings

- Wait time variability remained consistently high across all time periods.
- Coefficient of variation ranged between approximately 40%–43%.
- Midday periods showed the greatest instability.

### Operational Insights

- Workflow inconsistency exists hospital-wide
- Delays may stem from process inefficiencies rather than patient volume alone

### Recommendations

- Improve patient routing workflows
- Optimize triage and registration systems
- Investigate extreme wait-time cases
- Implement continuous performance monitoring

---

# Executive Summary

Patient flow analysis reveals that hospital utilization is primarily driven by adults aged 20–59 years, while seasonal attendance trends demonstrate elevated patient volumes between April and October.

Operational analysis further identifies substantial overnight congestion, particularly on Saturdays, indicating heavy reliance on emergency and after-hours healthcare services. Additionally, patient wait-time analysis reveals moderate-to-high operational variability across all service periods, suggesting systemic workflow instability throughout the hospital system.

Collectively, these findings support the need for:

- Strategic staffing redistribution
- Strengthened nighttime operational capacity
- Proactive seasonal resource planning
- Workflow optimization
- Continuous performance monitoring

Implementing these recommendations may improve patient throughput, reduce service delays, strengthen operational efficiency, and enhance overall healthcare service delivery.

---

# Future Improvements

Potential future extensions of this project include:

- Machine learning admission prediction
- Patient volume forecasting
- Interactive dashboards
- Department-level congestion modeling
- Real-time operational monitoring systems

---

# DocMe! 05/2025

>>>>>>> f103acf0f0b00b3b588082f9112e2017018651aa
Healthcare Operations & Data Analytics Project developed using Python and healthcare operational data analysis techniques.
