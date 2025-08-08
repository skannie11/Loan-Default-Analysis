# 📊 Loan Default & Overview 

## 📌 Problem Statement

This dashboard analyzes **loan default patterns** based on various factors like **loan purpose**, **employment type**, **age group**, and **year**. It helps financial institutions understand default risks and optimize loan offerings.

---

## 📈 Dashboard Insights

### 1. Loan Amount by Purpose
- 🏠 **Home**: ₹6545M (Highest)
- 💼 **Business**: ₹6522M
- 🎓 **Education**: ₹6511M
- 🚗 **Auto**: ₹6501M
- 🔧 **Other**: ₹6498M

🔍 **Insight**: Home loans account for the largest share in loan distribution.

---

### 2. Average Income by Employment Type
- **Full-time**: ₹82,890 (Highest)
- **Self-employed**: ₹82,447
- **Part-time**: ₹82,389
- **Unemployed**: ₹82,272

🔍 **Insight**: Income varies slightly by employment type, affecting repayment ability.

---

### 3. Default Rate (%) by Employment Type
- ❌ **Unemployed**: 3.39% (Highest)
- ⏱️ **Part-time**: 3.01%
- 💼 **Self-employed**: 2.86%
- ✅ **Full-time**: 2.36% (Lowest)

🔍 **Insight**: Default risk is **highest for unemployed** individuals, lowest for full-time workers.

---

### 4. Average Loan Amount by Age Group
- 👨 Adults: ₹127,901
- 👴 Middle Age Adults: ₹127,459
- 👵 Senior Citizens: ₹127,355
- 🧑 Teen: ₹126,674

🔍 **Insight**: Adults tend to borrow the highest loan amounts.

---

### 5. Default Rate (%) by Year
| Year | Default Rate (%) |
|------|------------------|
| 2013 | 11.62            |
| 2014 | 11.50            |
| 2015 | 11.70            |
| 2016 | 11.75 (Highest)  |
| 2017 | 11.50 (Lowest)   |
| 2018 | 11.60            |

🔍 **Insight**: Default rate peaked in 2016 and remained relatively stable across years.

---

## 🛠️ Steps Followed in Building the Dashboard

1. **Data Load**: Imported data into Power BI Desktop from CSV.
2. **Data Cleaning**: Removed nulls from relevant fields (minimal missing values).
3. **Profiling**: Enabled column distribution, quality & profile for full dataset.
4. **Measures & Calculated Fields**:
   - Created metrics for average loan, income, and default rate.
   - Added age group column using DAX.
5. **Visualizations Used**:
   - Bar charts, line/area charts, card visuals.
   - Slicers for dynamic filtering.
6. **Styling**: Applied consistent theme, proper labels, tooltips.
7. **Publishing**: Dashboard was published to **Power BI Service** for online access.

---

## 🧠 Final Insights Summary

| Metric                           | Value/Insight               |
|----------------------------------|-----------------------------|
| Highest Loan Purpose             | Home (₹6545M)               |
| Lowest Default Rate (Employment) | Full-time (2.36%)           |
| Highest Default Rate (Employment)| Unemployed (3.39%)          |
| Highest Average Loan             | Adults (₹127,901)           |
| Lowest Average Loan              | Teens (₹126,674)            |
| Peak Default Year                | 2016 (11.75%)               |
| Lowest Default Year              | 2014 & 2017 (11.50%)        |

---

## 📤 Publish & Share

This dashboard can be shared via **Power BI Service**, embedded in internal portals, or exported for reports. It provides actionable insights for loan strategy optimization and default risk management.

---
![Loan Dashboard](<img width="2000" height="1140" alt="Image" src="https://github.com/user-attachments/assets/8772f0c1-916a-403a-add1-22271d7ced1f" />)
