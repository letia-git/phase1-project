
# 📘 Gender Gap in School Enrollment in Kenya (2010–2023)

## 🔍 Overview

This project explores gender disparities in primary and secondary school enrollment across Kenya from 2010 to 2023. The goal is to help the Ministry of Education and other stakeholders identify regions with high gender gaps and recommend actions to improve gender equity in education.

---

## 💼 Business Understanding

Despite national progress, gender gaps in education persist in many Kenyan counties, especially at the secondary level. This project provides actionable insights by:
- Analyzing trends in male vs. female enrollment
- Identifying counties with the greatest disparities
- Highlighting regional enrollment strengths and weaknesses

### 👤 Stakeholder
**Ministry of Education, NGOs, county governments, and gender equity advocates**

### 🧩 Key Business Questions:
- How has the gender gap changed over time in Kenya?
- Which counties have the highest gender disparities?
- Are girls dropping out more in secondary education?

---

## 📊 Data Understanding and Cleaning

**Source**: Kenya National Bureau of Statistics (KNBS) – Enrollment data by County, Gender, Year, and Education Level

**Features Used**:
- `County`
- `Year`
- `Gender`
- `Level` (Primary / Secondary)
- `Enrollment` (number of students)

**Cleaning Steps (done in Python using pandas)**:
- Removed placeholder rows
- Standardized column names
- Converted year to integer type
- Handled missing and inconsistent entries
- Saved cleaned dataset: `Kenya_Enrollment_Clean.csv`

---

## 📈 Exploratory Data Analysis (EDA)

The notebook includes descriptive statistics, trend analysis, and grouped comparisons. Insights include:

- Girls’ enrollment in primary education is nearly on par with boys nationally
- A gender gap persists in **secondary school**, where female enrollment lags
- Counties like **Turkana**, **Mandera**, and **Garissa** show significantly lower female participation
- Overall gender ratio is improving over the years, but uneven across counties

---

## 📊 Visualizations (Tableau)

Explore the interactive dashboard 👉 [**Tableau Public Dashboard**](https://public.tableau.com/app/profile/YOUR_LINK)

### Key Charts:
1. **Line Chart** – Gender enrollment trends over time
2. **Bar Chart by County** – Gender disparity by region
3. **Pie Chart** – National gender ratio
4. **Top 5 Counties** – Highest total enrollment
5. *(Optional)* Scatter plot of Male vs Female Enrollment per county

🧩 Filters: `Year`, `Level`, and `Gender` are interactive.

---

## ✅ Business Recommendations

1. **Target High-Disparity Counties**: Prioritize gender-inclusive programs in Mandera, Garissa, and Turkana.
2. **Focus on Secondary School Retention**: Address dropout rates for girls through scholarships and awareness programs.
3. **Monitor Gender Gaps Annually**: Use dashboards like this to continuously monitor county-level gender equity in education.

---

## 🧪 Tools Used
- **Python (pandas, matplotlib, seaborn)** – For cleaning and analysis
- **Jupyter Notebook** – For exploratory analysis and documentation
- **Tableau Public** – For interactive dashboards
- **GitHub** – For version control and portfolio hosting

---
## 📊 Interactive Tableau Dashboard
Explore the dashboard 👉 [View Dashboard on Tableau Public](https://public.tableau.com/app/profile/letia.kareisi/viz/PHASE1PROJECT_17509436136160/GENDERGAPINEDUCATION?publish=yes)

