# 🗄️ SQL Data Analyst Job Market Analysis

[![SQL](https://img.shields.io/badge/SQL-PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)](https://www.postgresql.org/)
[![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visualstudio-code&logoColor=white)](https://code.visualstudio.com/)

## 📌 Project Overview
This SQL repository explores global job posting data for Data Analysts to analyze key industry trends, including **top-paying roles**, **most in-demand technical skills**, and **optimal skill sets** for high compensation.

The goal of this analysis is to identify actionable insights for aspiring data professionals navigating the current job market.

---

## ❓ Business Questions Explored

The queries in this repository were structured to address 5 core questions:

1. **Top-Paying Jobs:** What are the highest-paying Data Analyst roles available?
2. **Skills for Top-Paying Jobs:** What specific technical skills do these top-paying roles demand?
3. **In-Demand Skills:** What are the most frequently requested skills for Data Analysts overall?
4. **High-Salary Skills:** Which individual skills are associated with the highest average compensation?
5. **Optimal Skills (High Demand + High Pay):** What are the most strategic skills to learn to maximize career ROI?

---

## 🛠️ Technical Concepts Applied

* **Relational Database Querying:** `SELECT`, `WHERE`, `ORDER BY`, `LIMIT`
* **Data Aggregation:** `GROUP BY`, `HAVING`, `COUNT()`, `AVG()`, `ROUND()`
* **Complex Table Joins:** `INNER JOIN`, `LEFT JOIN` across relational schemas (`job_postings_fact`, `skills_dim`, `skills_job_dim`)
* **Advanced Querying Techniques:** Common Table Expressions (CTEs), Subqueries, and Date Functions (`EXTRACT()`, `DATE_TRUNC()`)

---

## 💡 Key Market Insights

* **Core Competencies:** **SQL** and **Python** are the undisputed top two most demanded skills across job postings.
* **High-ROI Skills:** Specialized cloud tools (**AWS, Azure**) and big data frameworks (**Spark**) show a strong correlation with top-tier salary benchmarks.
* **Optimal Focus:** Combining foundational querying (SQL) with a programming language (Python) and a modern cloud/BI platform yields the strongest market demand and salary growth.

---

## 👥 Acknowledgments & Attribution

This project was developed as part of the **SQL for Data Analytics** course by **[Luke Barousse](https://www.youtube.com/@LukeBarousse)**.

* **Dataset Source:** Luke Barousse Data Job Postings Dataset.
* **Course Reference:** Luke Barousse's SQL for Data Analytics tutorial.

---

## 🚀 How to Run the Queries

1. Install **PostgreSQL** and a SQL client (e.g., **pgAdmin** or **VS Code with PostgreSQL extension**).
2. Load the database schema and job postings dataset.
3. Execute the `.sql` files in sequence inside the `project_sql/` directory.

## 📂 Repository Structure

```text
├── project_sql/
│   ├── 1_top_paying_jobs.sql       # Query identifying highest-paying data roles
│   ├── 2_top_paying_job_skills.sql # Query mapping skills to top-paying roles
│   ├── 3_top_demanded_skills.sql   # Query ranking skills by total job count
│   ├── 4_top_paying_skills.sql     # Query calculating average salary per skill
│   └── 5_optimal_skills.sql        # Query finding high-demand & high-pay overlap
└── README.md                       # Project documentation

