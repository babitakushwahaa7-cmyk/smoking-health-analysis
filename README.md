# smoking-health-analysis
Smoking Health Risk Analysis - Power BI Dashboard | Analysis of 2,500 patients by Smoking Status, Organ Damage, Age Group, Gender &amp; BP Risk.
# 🚬 Smoking Health Risk Analysis - Power BI Dashboard

An interactive Power BI dashboard that analyzes how smoking affects different organs, blood pressure, and overall health risk across 2,500 patients.

## 📊 Dashboard Overview

This dashboard answers one main question:
**How does smoking damage different organs in the body?**

It uses filters for Organ Condition (Damaged / Healthy) and Organ Type (Heart, Kidney, Liver, Lungs, etc.) to show real-time health impact.

## 🔑 Key KPIs

- **Count of Patient_ID:** 897 (Healthy) | 1,603 (Damaged)
- **Avg Age:** 53.9 - 54.1 years
- **Avg BMI:** 29.4 - 29.8 (Overweight range)
- **Total Patients Analyzed:** 2,500

## 📈 Visuals Included

### 1. Count of Patient_ID by Smoking_Status (Donut Chart)
- **Never:** 320 (24.53%) / 411 (25.64%)
- **Current:** 421 (46.83%) / 715 (44.58%)
- **Former:** 256 (28.54%) / 477 (29.78%)
- Insight: Almost 45% patients are current smokers.

### 2. Sum of Cigarettes_Per_Day by Age Group (Line Chart)
- Shows daily cigarette consumption across age groups
- Peak consumption in 39-48 and 49-58 age groups

### 3. Count of Patient_ID by Smoking_Status and Gender (Ribbon / Area Chart)
- Comparison of Male vs Female smokers
- Male patients are significantly higher in Current smoker category

### 4. Count of Patient_ID by Age Group and BP_Risk (Stacked Bar Chart)
- BP Risk: High / Low / Normal
- High BP Risk is highest in 69+ and 59-68 age groups
- Shows smoking + age = higher BP risk

### 5. Organ Visual (Center Image Slicer)
- Interactive human body / organ image
- Click on Heart, Kidney, Liver, Lungs to filter whole dashboard
- Shows Healthy vs Damaged organ condition

## 🎛️ Filters / Slicers Used
- Organ_Condition: Damaged / Healthy
- Organ: Heart, Kidney, Liver, Lungs, etc.

## 💡 Key Insights From Dashboard
1. Out of 2,500 patients, 1,603 (64%) have damaged organs.
2. Current smokers have the highest organ damage rate.
3. Average BMI of patients is ~29.8, which is in overweight category - smoking + high BMI = double risk.
4. BP Risk increases sharply after age 49.
5. Lungs and Liver are the most affected organs in smokers.
6. Former smokers still show damage, proving long-term effect of smoking.

## 🛠️ Tools Used
- Power BI Desktop
- Power Query for Data Cleaning
- DAX for Measures (Count, Average, Sum)
- Dataset: Smoking Health Risk Patient Data (CSV / Excel)

## 📂 Files in Repo
