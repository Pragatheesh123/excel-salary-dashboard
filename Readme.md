# 📊 Jobs Salary Dashboard

An interactive Excel dashboard that analyzes **median salaries, job counts, and hiring trends** across data roles worldwide — filterable by job title, country, and employment type.

---

## 🎬 Live Demo

![Dashboard Demo](![Video Project](https://github.com/user-attachments/assets/617c38ec-240e-4c65-be0b-d9bb71f1fcf8)
)

---

## 🖥️ Dashboard Overview

![Jobs Salary Dashboard](<img width="1515" height="669" alt="Screenshot 2026-03-10 215722" src="https://github.com/user-attachments/assets/4c8c7052-920f-47c4-9de6-aeea8e5efd89" />)

> Filter by **Job Title**, **Country**, and **Schedule Type** to instantly update all charts and KPIs. The dashboard shows median salary, top job platform, and job count for any combination.

---

## ✨ Features

| Feature | Description |
|---|---|
| 🔍 **Role Filter** | Dropdown to select any data job title |
| 🌍 **Country Filter** | Filter salary data by country with a live map |
| 🗂️ **Schedule Type Filter** | Full-time, Part-time, Contractor, etc. |
| 💰 **Median Salary KPI** | Live card showing filtered median salary |
| 🏆 **Top Job Platform** | Shows which platform has the most listings |
| 🔢 **Job Count KPI** | Number of postings matching the current filters |

---

## 📁 Data Source

![Raw Data Table](<img width="1894" height="680" alt="Screenshot 2026-03-10 221125" src="https://github.com/user-attachments/assets/1fdfa46a-3512-4ef6-8b8e-68c2dee627fa" />

)

The dataset contains **275+ job postings** with the following columns:

`job_title` · `job_location` · `job_via` · `job_schedule_type` · `job_work_from_home` · `job_posted_date` · `salary_year_avg` · `salary_hour_avg` · `company_name` · `job_skills`

---

## 🌍 Salary by Country

![Country Salary Breakdown]( <img width="289" height="433" alt="Screenshot 2026-03-10 221150" src="https://github.com/user-attachments/assets/ad1dfcaf-e216-4d2f-881b-3253270f95ee" />

)

Median salaries vary significantly by country. The dashboard includes data from **100+ countries**, with the United Kingdom clocking in at **$78,922** median for Data Analyst roles.

---

## 🔗 Job Platforms Tracked

![Platform Data](<img width="785" height="651" alt="Screenshot 2026-03-10 221209" src="https://github.com/user-attachments/assets/8bbec9e4-5ff3-4982-88e8-8024f485428e" />

)

The dashboard tracks job postings across **20+ platforms** including LinkedIn, Indeed, ZipRecruiter, Ai-Jobs.net, Snagajob, Ladders, and more — surfacing which platform dominates for your selected role and country.

---

## 🛠️ Built With

![Microsoft Excel](https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)

- **Pivot Tables** — aggregating salary and count data by role, country, and type  
- **XLOOKUP / INDEX-MATCH** — dynamic KPI lookups based on filter state  
- **Data Validation** — dropdown lists for Job Title, Country, and Type  
- **Bing Maps Chart** — geographic salary visualization  
- **Conditional Formatting** — visual highlights on selected filters  
- **Named Ranges** — clean formula references across sheets  

---

## 📂 Project Structure

```
Project_1.xlsx
├── Salary_Dashboard   ← Main interactive dashboard
├── Data               ← Raw job postings (275+ rows)
├── Jobs               ← Median salary per role
├── Country            ← Median salary per country
├── Type               ← Salary by schedule type
├── Platform           ← Job count by platform
└── Data Validation    ← Dropdown source lists
```

---

## 🚀 How to Use

1. **Download** `Project_1.xlsx`
2. **Open** in Microsoft Excel (2016 or later recommended)
3. **Enable editing** if prompted
4. Use the **dropdowns** at the top to filter by Job Title, Country, and Type
5. All charts and KPIs update **instantly**

---

## 📬 Contact

Feel free to reach out or open an issue if you have feedback or questions!
