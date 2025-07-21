# HR_Attrition_Analysis
HR Attrition Analysis using R, SQL, Power BI, and MongoDB. This project explores employee turnover trends and helps identify key factors influencing attrition through data analysis and visualization.
---

## 📊 Project Overview

- **Objective:** Understand the key drivers of employee attrition to support data-driven HR decisions.
- **Dataset:** HR dataset with 1,470 records and 35 variables, covering demographics, job roles, satisfaction levels, compensation, and more.
- **Tools Used:**
  - 🐍 **R** – Data exploration and transformation
  - 🧮 **SQL** – Structured data preparation and normalization (1NF to 3NF)
  - 🍃 **MongoDB** – NoSQL structure for flexible document-based storage
  - 📊 **Power BI** – Interactive dashboards and KPI visualizations

---

## ⚙️ Project Structure

---

## 🔍 Key Analysis Highlights

- Global attrition rate: **16.1%**
- Strong patterns found in:
  - **OverTime** employees with higher attrition
  - Lower **Job Satisfaction** linked to higher turnover
  - Attrition more frequent in certain **departments** and **roles**
- Normalization of original dataset into 3NF:
  - Entities: Employees, Education, Job, WorkDetails, Satisfaction, Journey
  - Proper use of surrogate keys, PKs and FKs
- NoSQL structure built for flexible reporting needs (MongoDB collections)
- OLAP star schema created for performance-based analysis

---

## 📷 Dashboard Preview

_Add screenshots to `/images/` and include them here:_

![Dashboard Preview](images/dashboard_screenshot.png)

---

## 📁 How to Use

1. Clone this repository
2. Explore scripts in `r-scripts/` and `sql/` folders
3. Open `.pbix` file in Power BI Desktop to view interactive dashboard
4. Review MongoDB queries or structures in `mongodb/`

---

## ⚠️ Notes

- All data is simulated and anonymized for learning/demo purposes.
- Scripts may be adapted to any HR dataset with similar structure.
- This project is part of my Data Analyst learning journey.

---

## 📬 Contact

If you'd like to collaborate, request a dashboard, or discuss freelance work, feel free to reach out:

📧 julio91fonseca@gmail.com  
🌐 [LinkedIn](https://www.linkedin.com/in/teuperfil) _(replace with your actual LinkedIn profile if available)_

---
