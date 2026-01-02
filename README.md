# Healthcare Patient Data Analysis

## 📌 Project Overview

This project focuses on analyzing healthcare patient data to understand **patient demographics, admission patterns, billing behavior, and hospital efficiency**.
The analysis transforms raw healthcare data into meaningful insights using **Python for data preprocessing** and **Excel dashboards for visualization**.

The objective is to support **data-driven decision-making** for healthcare providers by identifying trends in patient inflow, medical conditions, and resource utilization.

---

Dashboard Overview
<img width="970" height="699" alt="Screenshot 2025-12-28 154659" src="https://github.com/user-attachments/assets/1fe00105-0c59-4119-a23d-804159bb75e7" />

---


## 🎯 Business Objectives

* Analyze patient demographics and admission types
* Measure hospital efficiency using length of stay metrics
* Understand billing patterns across insurance providers
* Identify high-impact medical conditions
* Enable interactive analysis for healthcare stakeholders

---

## 📂 Dataset Description

The dataset contains detailed healthcare records where each row represents a single patient.

### Key Attributes:

* Patient age and gender
* Admission and discharge dates
* Admission type (Emergency, Urgent, Elective)
* Medical condition
* Insurance provider
* Billing amount
* Length of hospital stay

---

## 🛠 Tools & Technologies Used

* **Python (Pandas)** – Data cleaning & feature engineering
* **Excel** – Dashboard creation & visualization

---

## 🧹 Data Preprocessing (Python)

Python was used to clean and prepare the healthcare dataset before visualization:

### Key Steps:

* Loaded dataset using Pandas
* Standardized column names:

  * Converted to lowercase
  * Removed extra spaces
  * Replaced spaces with underscores
* Converted admission and discharge dates into datetime format
* Cleaned text-based categorical columns:

  * Gender
  * Blood type
  * Medical condition
  * Admission type
  * Insurance provider
* Removed invalid records:

  * Age ≤ 0
  * Billing amount ≤ 0
* Removed duplicate patient records
* Engineered new features:

  * **Length_of_Stay** (Discharge Date − Admission Date)
* Created **Age Groups** for simplified demographic analysis
* Exported the cleaned dataset for Excel visualization 

---

## 📊 Key Performance Indicators (KPIs)

* **Total Patients:** 54,860
* **Average Billing Amount:** ₹25,595
* **Average Length of Stay:** 15.49 days
* **Average Patient Age:** 51.53 years

These KPIs provide a high-level overview of healthcare operations and patient trends .

---

## 🔍 Key Analysis & Insights

### 🏥 Admission Type Analysis

* Emergency admissions form a significant portion of hospital visits
* Urgent admissions require prompt care but are less critical
* Elective admissions represent planned procedures
* Helps hospitals plan staff and resources efficiently 

---

### 👥 Gender Distribution

* Patient distribution between male and female is relatively balanced
* Supports gender-specific healthcare planning and service optimization 

---

### 🎂 Age Group Analysis

* Highest patient volume comes from the **60+ age group**
* Adult and middle-aged groups also contribute significantly
* Indicates higher healthcare demand among senior citizens 

---

### 🩺 Medical Condition Analysis

* Most common conditions:

  * Diabetes
  * Arthritis
  * Hypertension
* Chronic conditions dominate patient inflow
* Helps prioritize long-term treatment strategies 

---

### ⏱ Length of Stay by Condition

* Asthma and Arthritis patients have the longest hospital stays
* Diabetes and Hypertension patients show shorter stays
* Useful for bed utilization and resource planning 

---

### 📈 Admission Trend Over Time

* Sharp increase in admissions from 2019 to 2020
* Stable trend from 2020 to 2023
* Decline observed in 2024
* Supports forecasting and capacity planning 

---

### 💰 Billing Analysis by Insurance Provider

* Medicare shows the highest average billing amount
* UnitedHealthcare has the lowest average billing
* Helps in financial planning and insurer negotiations 

---

## 🎛 Interactive Dashboard Features

The Excel dashboard includes slicers for:

* Admission Type
* Medical Condition
* Gender
* Age Group

All charts and KPIs update dynamically, enabling scenario-based analysis for stakeholders .

---

## 📈 Business Value

* Identifies patient segments with high healthcare demand
* Improves hospital efficiency through length-of-stay analysis
* Supports financial planning using billing insights
* Enables faster, data-driven decisions via interactive dashboards

---

## ✅ Conclusion

This project demonstrates how **Python-based data preprocessing** combined with **Excel dashboards** can convert raw healthcare data into actionable insights.
It highlights patient demographics, operational efficiency, and financial trends that are critical for healthcare management.

---

## 📚 Learning Outcomes

* Healthcare data cleaning and preprocessing using Python
* Feature engineering and demographic segmentation
* KPI-driven dashboard design
* Translating data insights into business decisions

