# MENA Healthcare Efficiency & Outcomes  
### Executive Consulting Analytics Dashboard

## Overview
This project presents a **consulting-style analysis of healthcare efficiency across MENA countries**, focusing on how effectively **healthcare spending** translates into **health outcomes**.

Rather than measuring spending alone, the analysis emphasizes **efficiency, benchmarking, and decision support**, following a management consulting mindset suitable for **public sector and healthcare transformation initiatives**.

---

## Scope
- **Region:** MENA
- **Sector:** Public Healthcare
- **Perspective:** Efficiency & outcomes (not spending volume)
- **Audience:** Policy makers, consultants, and analytics leaders

---

## Data
- **Source:** World Bank – Health, Nutrition & Population
- **Methodology Note:**  
  Due to public-sector reporting lags, the analysis uses the **latest available value per indicator for each country**, reflecting real-world government analytics practices.

---

## Key Metrics
- Health Expenditure per Capita (PPP)
- Life Expectancy at Birth
- Infant Mortality Rate
- Physicians per 1,000 People
- Hospital Beds per 1,000 People

---

## Methodology
1. Cleaned and reshaped World Bank indicators using **Python (pandas, numpy)**.
2. Consolidated the **latest available value per indicator** per country.
3. Established **regional benchmarks (MENA averages)**.
4. Classified countries into **Efficiency Categories**:
   - High Efficiency  
   - Best Practice  
   - Efficiency Gap  
   - Under-resourced
5. Built an **Executive Power BI Dashboard**, optimized for **desktop and mobile** viewing.

---

## Key Insights
- **Efficiency varies significantly:** Higher healthcare spending does not consistently translate into better outcomes across MENA.
- **Best practices exist:** Some countries achieve strong health outcomes with moderate spending levels.
- **Clear priority areas:** High-spend, low-outcome countries represent the strongest opportunities for efficiency improvement.

---

## Recommendations
1. **Target efficiency gaps** by focusing on operational and governance improvements.
2. **Scale regional best practices** from high-efficiency countries.
3. **Strengthen performance monitoring** through unified healthcare KPI dashboards.

---

## Dashboard Preview
### Executive View (Desktop)
![Executive Dashboard](images/Dashboard.png)

### Mobile View
![Mobile Dashboard](images/Dashboard-mobile-version.png)

---

## Repository Structure

├── datasets/
│ └── World_Bank_Health_Data.csv
├── images/
│ ├── dashboard_desktop.png
│ └── dashboard_mobile.png
├── health_care_analysis.ipynb
├── MENA_Healthcare_Dashboard.pbix
└── README.md


---

## Tools & Technologies
- **Python:** pandas, numpy  
- **Power BI:** DAX, Executive dashboard design  
- **Data Source:** World Bank Open Data

---

## Why This Project Matters
This project demonstrates the ability to:
- Translate raw public-sector data into **decision-ready insights**
- Apply **consulting logic** rather than descriptive reporting
- Design **executive-level dashboards** suitable for leadership and policy discussions

---



## 👤 Author
### Asem Haij
#### Data Analyst | Financial Analysis | Power BI
#### GitHub: https://github.com/ProfASEM
#### LinkedIn: www.linkedin.com/in/asem-haij-9797562a8
