# 🏥 Apollo Healthcare Data Analysis Project

This project analyzes hospital-level data from Apollo Healthcare to uncover insights into patient care, operational efficiency, financial billing, and patient satisfaction. The analysis includes Python-based EDA and an interactive Power BI dashboard.

## 📊 Tools & Technologies Used

- **Python** – Pandas, Matplotlib, Seaborn
- **Power BI** – Interactive KPI dashboard
- **Jupyter Notebook**
- **Excel** – Data sourced in `.xlsx` format

### 📊 Apollo Healthcare Dataset – EDA Summary
This analysis explores patient, financial, and operational data from Apollo Healthcare to uncover patterns in hospital performance, resource usage, and patient satisfaction.

#### 📁 Dataset Overview
- Total Records: 7,035 patients

- Features: Admission/discharge dates, diagnosis, doctor, tests, billing, feedback

- Data Range: Single-month inpatient visits (assumed short time period)

#### 🧼 Data Preparation
- Converted date fields: Admit_Date, Discharge_Date, Followup Date

- Created new column: Length_of_Stay = Discharge - Admit

- Verified no missing values

#### 🔍 Key Insights
##### 🏥 Hospital Operations
- Average Length of Stay: 8.25 days

- Bed Type Usage:

- Private: 50%

- General: 33%

- ICU: 17%

##### Most Common Diagnoses:

- Viral Infection, Flu, Malaria, Typhoid, Pneumonia

#### 💰 Financial Overview
- Average Billing Amount: ₹26,597

- Average Insurance Coverage: ₹23,938

- Average Out-of-Pocket Expense: ₹2,660

#### 🧪 Test Utilization
- Top tests: Blood Test, MRI, CT Scan, Ultrasound, X-Ray

- MRI patients tend to have higher billing than others

#### 👨‍⚕️ Doctor Performance
- Top doctors (by patient volume): Mark Joy, Naresh Goyenka, Ravi D, Jay Sinha, Jaya Yaadav

- Feedback ratings mostly 4.5 to 5.0

#### 💬 Patient Feedback
- Average Feedback Score: 4.72 / 5

- High satisfaction across doctors and services

