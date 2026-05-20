# 🫁 Smoking Health Risk Analysis Dashboard

> An interactive, multi-organ health analytics dashboard built in Power BI — visualizing the impact of smoking on organ health across age groups, genders, and smoking status categories.

<img width="879" height="484" alt="Screenshot 2026-05-20 223722" src="https://github.com/user-attachments/assets/3ce3a5d0-6502-4deb-b225-39342f42f542" />

---

## 📌 Project Overview

This dashboard provides a comprehensive view of **how smoking affects major organs** — Heart, Lungs, Liver, Kidney, and the Human body system — by analyzing patient data segmented by smoking status, age group, gender, cholesterol levels, and BMI.

It enables clinicians, researchers, and health analysts to toggle between **Damaged** and **Healthy** cohorts and instantly see how key health indicators shift across populations.

---

## 🖥️ Dashboard Features

| Feature | Description |
|---|---|
| 🫀 **Organ Navigation** | Switch between Heart, Lungs, Liver, Kidney, and Human body views |
| ⚖️ **Damaged vs Healthy Toggle** | Instantly compare patient cohorts by organ health status |
| 🚬 **Smoking Status Breakdown** | Donut chart split across Never / Current / Former smokers |
| 📊 **Smoking Duration & Daily Intake** | Line chart (CPD & YOS) across age groups 18–69+ |
| 👥 **Smoking Status by Gender** | Stream/area chart comparing Female vs Male across smoking categories |
| 💉 **Cholesterol & Hypertension Risk** | Stacked bar chart (High / Low / Normal) across age groups |
| 🔢 **KPI Cards** | Total patients, Average Age, Average BMI per filtered cohort |

---

## 📸 Dashboard Previews

<img width="884" height="495" alt="human_damaged" src="https://github.com/user-attachments/assets/8510dab2-5055-4b93-a7a6-d81126d70a91" />

<img width="875" height="484" alt="lungs_damaged" src="https://github.com/user-attachments/assets/42cebbc4-b903-4065-9262-a104adcdca09" />

<img width="873" height="490" alt="heart_healthy" src="https://github.com/user-attachments/assets/278aa1a3-b265-4b38-944b-30c0025549c2" />

<img width="858" height="481" alt="heart_damaged" src="https://github.com/user-attachments/assets/0f0e6ab2-1e84-4e92-9779-a1de2246fe31" />

<img width="879" height="484" alt="Screenshot 2026-05-20 223722" src="https://github.com/user-attachments/assets/1622914f-f92b-4358-96dd-e58b995ba43b" />

---

## 📂 Project Structure

```
smoking-health-risk-dashboard/
│
├── SmokingHealthRisk.pbix        # Main Power BI dashboard file
├── data/
│   └── smoking_health_data.csv   # Raw dataset used for analysis
├── screenshots/
│   ├── heart_damaged.png
│   ├── heart_healthy.png
│   ├── lungs_damaged.png
│   ├── human_damaged.png
│   └── liver_healthy.png
└── README.md
```

---

## 📊 Dataset Overview

The dataset includes patient-level records with the following key attributes:

| Column | Description |
|---|---|
| `Age` | Patient age (grouped: 18–28, 29–38, ..., 69+) |
| `Gender` | Male / Female |
| `Smoking_Status` | Never / Current / Former |
| `CPD` | Cigarettes per day |
| `YOS` | Years of smoking |
| `BMI` | Body mass index |
| `Cholesterol_Level` | High / Low / Normal |
| `Hypertension` | Yes / No |
| `Organ_Condition` | Damaged / Healthy (per organ) |

---

## 🔍 Key Insights

- **Damaged Heart patients** had a higher average BMI (30.1) and were older (Avg Age 54.9) vs the healthy cohort
- **Former smokers** represent the largest segment (≈40–50%) across most organ conditions, suggesting long-term residual risk
- **Lung-damaged patients** showed the highest current-smoker proportion, reinforcing direct smoking-to-lung damage correlation
- **Cholesterol risk** (High category) peaks in the **39–58 age band** across all organ groups
- **Female patients** show a steeper drop in the "Never smoked" category in damaged cohorts compared to males

---

## 🛠️ Tools & Technologies

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-0078D4?style=for-the-badge&logo=microsoft&logoColor=white)
![Excel](https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)

- **Power BI Desktop** — Dashboard design, interactivity, and publishing
- **DAX** — Custom measures for KPI cards, cohort filtering, and dynamic titles
- **Power Query** — Data cleaning and transformation
- **Excel / CSV** — Source data preparation

---

## 💡 Use Cases

- **Healthcare Analytics** — Understand organ-specific smoking risks across demographics
- **Public Health Reporting** — Data-driven communication of smoking cessation priorities
- **Clinical Research** — Segment and filter patient cohorts by health status
- **Portfolio Project** — Demonstrates end-to-end BI skills: data modeling, DAX, visual design, and storytelling

---

## 🙋 About the Author

**[Your Name]**
Data Analyst | Power BI Developer | Health Analytics Enthusiast

- 🔗 [LinkedIn]( https://www.linkedin.com/in/prateek-yadav-408961277/)
- 💼 [Portfolio](https://your-portfolio.com)
- 📧 yadavprateek084@gmail.com

