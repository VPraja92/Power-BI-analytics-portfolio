# Power BI Analytics Portfolio

Welcome to my Power BI portfolio repository! This project features two fully interactive, end-to-end business intelligence dashboards built to solve complex analytical challenges in the **Insurance** and **Healthcare** sectors. 

---

## 📋 Table of Contents
1. [Insurance Analysis Dashboard](#-insurance-analysis-dashboard)
2. [Healthcare Analysis Dashboard](#-healthcare-analysis-dashboard)
3. [Repository Structure](#-repository-structure)
4. [Technologies Used](#-technologies-used)

---

## 🛡️ 1. Insurance Analysis Dashboard

An interactive dashboard designed to monitor and evaluate insurance policy portfolios, risk exposure, claim distributions, and financial metrics across diverse demographics[cite: 3].

![Insurance Analysis Dashboard](images/insurance-dashboard.png)

### 🔍 Key Features & Metrics
* **Demographic Breakdown**: Analyzes customer distributions spanning **5K Male** and **5K Female** active portfolios[cite: 3].
* **Core Financial KPIs**:
  * **Total Premium**: **5.97M**[cite: 3]
  * **Total Coverage**: **600.33M**[cite: 3]
  * **Total Claim Amount**: **16.90M**[cite: 3]
* **Claim Lifecycle Tracking**: Monitors claim volumes across **Rejected**, **Settled**, and **Pending** states[cite: 3].
* **Policy Status Health**: Evaluates active vs. inactive policies (**5.81K Active** vs. **4.19K Inactive**)[cite: 3].
* **Risk by Age & Product Type**: Breaks down claim amounts across age brackets (*Adults*, *Older*, *Young Adults*) and product categories (*Travel*, *Health*, *Auto*, *Life*, and *Home*)[cite: 3].

---

## 🏥 2. Healthcare Analysis Dashboard

An operational intelligence dashboard built to track hospital footfall, patient demographics, department efficiency, and patient satisfaction ratings[cite: 4].

![Healthcare Analysis Dashboard](images/healthcare-dashboard.png)

### 🔍 Key Features & Metrics
* **Patient Volume & Breakdown**: 
  * **Total Patients**: **2,506**[cite: 4]
  * **Inpatients**: **1,679**[cite: 4]
  * **Outpatients**: **827**[cite: 4]
* **Operational Performance**:
  * **Total Staff**: **262**[cite: 4]
  * **Average Treatment Cost / Time**: **161.41**[cite: 4]
  * **Average ER Response Time**: **65.63 mins**[cite: 4]
  * **Patient-to-Staff Ratio**: **0.10**[cite: 4]
* **Capacity Management**: Tracks **1,751** occupied beds against a maximum facility capacity of **3,502**[cite: 4].
* **Financial & Demographic Insights**: Highlights revenue streams mapped across patient age buckets (led by the **6–20Y** demographic contributing **0.14M**)[cite: 4].
* **Patient Feedback & Sentiment**: Evaluates sentiment metrics regarding doctor-patient communication and satisfaction scores across age groups[cite: 4].

---

## 📁 Repository Structure

```text
Power-BI-analytics-portfolio/
│
├── Power_BI_Dashbords/
│   ├── HealthcareAnalaysis Dashboard.pbix   # Healthcare Power BI report file
│   ├── Insurance Analysis Dashboard.pbix    # Insurance Power BI report file
│   └── Dashboard Data/
│       ├── Health_Care_Data.xlsx            # Healthcare operational dataset[cite: 1]
│       └── Insurance_Data.csv               # Insurance portfolio dataset[cite: 1]
│
├── images/
│   ├── healthcare-dashboard.png             # Healthcare dashboard preview
│   └── insurance-dashboard.png              # Insurance dashboard preview
│
└── README.md                                # Project documentation
