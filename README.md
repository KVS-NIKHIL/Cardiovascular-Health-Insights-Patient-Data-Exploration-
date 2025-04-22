# Heart Disease Clinical Analysis: Exploratory Data Analysis

![Python](https://img.shields.io/badge/Python-3.8+-blue)
![Pandas](https://img.shields.io/badge/Pandas-1.3+-orange)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3.4+-blueviolet)
![Seaborn](https://img.shields.io/badge/Seaborn-0.11+-yellowgreen)

An exploratory data analysis (EDA) of clinical heart disease indicators, examining risk factors across age, gender, and diagnostic measurements.

##  Project Overview

This analysis investigates:
- Prevalence of heart disease in the dataset
- Demographic distributions (age/sex)
- Clinical indicators:
  - Chest pain types (cp)
  - Resting blood pressure (trestbps)
  - Cholesterol levels (chol)
  - Maximum heart rate (thalach)
  - Exercise-induced angina (exang)
   
  ## Key Findings
 
  ### Visual Analysis Highlights

- **Age Distribution**: Most patients with heart disease were aged between 40 and 60.
- **Sex-based Risk**: Males showed a higher prevalence of heart disease in the dataset.
- **Chest Pain Types (cp)**:
  - `cp=0` (typical angina) was more common in those **without** heart disease.
  - `cp=2` (non-anginal pain) and `cp=3` (asymptomatic) were higher among patients **with** heart disease.
- **Cholesterol & Blood Pressure**:
  - No strong correlation between `chol` and heart disease presence.
  - Elevated `trestbps` found in both classes, though slightly more in diseased cases.
- **Max Heart Rate (thalach)**:
  - Patients with heart disease tended to have **lower max heart rates**.
- **Exercise-Induced Angina (exang)**:
  - More common in patients **with** heart disease.

###  Heart Disease Distribution
  data.target.value_counts()
  - 1: 165 (Heart Disease)
  - 0: 138 (No Heart Disease)
