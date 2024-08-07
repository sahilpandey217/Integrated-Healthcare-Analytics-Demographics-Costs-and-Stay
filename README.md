# Comprehensive Healthcare Analytics

## Overview
This project integrates multiple healthcare analytics components to provide a holistic view of patient demographics, healthcare costs, length of stay, and medication outcomes. Using a synthetic healthcare dataset, the project performs in-depth analyses to extract meaningful insights and visualize key metrics relevant to healthcare management and decision-making.

## Objectives
1. **Patient Demographics Analysis**
   - **Objective:** Analyze the demographic distribution of patients.
   - **Key Metrics:** Age distribution, gender distribution, blood type distribution.
   - **Visualization:** Histograms, pie charts, and bar plots.

2. **Healthcare Costs Analysis**
   - **Objective:** Explore billing amounts and identify cost drivers.
   - **Key Metrics:** Average billing amount by medical condition, insurance provider, and admission type.
   - **Visualization:** Box plots, bar charts, and scatter plots.

3. **Length of Stay Analysis**
   - **Objective:** Investigate the length of stay in the hospital and its influencing factors.
   - **Key Metrics:** Length of stay (calculated as discharge date - admission date) by medical condition, age, and admission type.
   - **Visualization:** Histograms, box plots, and heatmaps.

4. **Medication and Treatment Outcomes**
   - **Objective:** Examine the relationship between medication prescribed and test results.
   - **Key Metrics:** Medication types, test results (normal, abnormal, inconclusive).
   - **Visualization:** Bar plots and stacked bar charts.

## Data
- **Dataset:** Synthetic healthcare dataset generated using the Faker library.
- **Columns:** Name, Age, Gender, Blood Type, Medical Condition, Date of Admission, Doctor, Hospital, Insurance Provider, Billing Amount, Room Number, Admission Type, Discharge Date, Medication, Test Results.

## Installation
To run this project, ensure you have the following Python libraries installed:
```bash
pip install pandas seaborn matplotlib numpy
