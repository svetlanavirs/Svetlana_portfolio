# Svetlana_portfolio
Analytics portfolio
# Project 1: AI Jobs & Skills Analytics Dashboard  
Power BI Project | Data Modeling | DAX | Data Visualization

## Project Overview
This project analyzes global AI job market trends, salaries, and skill demand across countries, job roles, and experience levels (2020–2026).  
The goal was to build a clean, professional Power BI dashboard using a STAR schema, optimized relationships, and clear analytical insights.

---

## Data Model (STAR Schema)

The final model consists of:

### **Fact tables**
- `ai_jobs` — job listings, salaries, experience, location  

### **Dimension tables**
- `job_title_mapping` — standardized job titles and role categories  
- `country_ai_trends` — aggregated country-level AI statistics (linked via `country_year`)
- `skills_demand` — skill occurrences linked by `job_id`
 
### **Key modeling decisions**
- Created composite key `country_year` to avoid many‑to‑many relationships
- Ensured single‑direction filtering for stable model behavior

**Data model:**  

<img width="867" height="723" alt="Star" src="https://github.com/user-attachments/assets/fb17ed9a-6915-4acd-8eea-b1802b53abd6" />

---

## Dataset Overview

The project is based on five structured datasets:

- `ai_jobs.xlsx`  
- `country_ai_trends.xlsx`  
- `skills_demand.xlsx`  
- `job_title_mapping.xlsx`  
- `data_dictionary.xlsx`

---

## Dashboard Pages

### **1. Overview**
- Total AI jobs  
- Salary KPIs  
- Country comparison  
- Trends over time  

<img width="1302" height="731" alt="1" src="https://github.com/user-attachments/assets/cb076094-ec9e-401f-8a47-71a5fe702ef4" />

---

### **2. Total AI Jobs**
- Jobs by country  
- Jobs by year  
- Interactive filters  

<img width="1302" height="732" alt="2" src="https://github.com/user-attachments/assets/e715ce76-cf85-48bd-9497-91ceffca5971" />

---

### **3. Average Salary**
- Average monthly salary  
- Salary by job title  
- Salary trends by year  

<img width="1301" height="736" alt="3" src="https://github.com/user-attachments/assets/9ee50e4f-2ddf-43ae-bb97-0bb15a6c8fa3" />

---

### **4. Salary Range**
- Min, max, and midpoint salary trends  
- Experience-level comparison  

<img width="1302" height="730" alt="4" src="https://github.com/user-attachments/assets/569a13ed-8ad3-492a-b125-dcfe6f816eff" />

---

### **5. Skills**
- Skill categories (ML, Cloud, Programming)  
- Top 5 skills  
- Skill demand by job role  
- Skill demand by experience level  

<img width="1302" height="734" alt="5" src="https://github.com/user-attachments/assets/c0caa8b1-c998-4a70-bffd-2b26b02a960e" />

---

### **6. Q&A — Key Insights**

**1. How many AI & Data Science job postings are in the market?**  
Job volume fluctuates between **200K and 343K per year**, depending on country and year.

**2. What are the salary ranges for entry‑level Data Analysts?**  
Entry-level monthly salaries range from **€3,477 to €6,255**.

**3. How have salaries changed from 2020 to 2026?**  
Salary levels remain **stable**, with only minor fluctuations across years.

**4. How does experience impact salary?**  
Experience has a **major impact** — the gap between entry-level and senior roles can reach **€9,000 per month**.

**5. Which skills are most in demand?**  
Machine Learning dominates. Top skills: **AWS, GCP, TensorFlow, Azure, Scikit‑learn**.


<img width="1305" height="735" alt="6" src="https://github.com/user-attachments/assets/2f3ab2cd-735a-4515-9858-3daf31bfb6bf" />


---

## Tools & Technologies
- Power BI Desktop  
- Power Query  
- DAX  
- Data Modeling (STAR schema)  
- GitHub  

---

## What I Learned
- Building a clean STAR schema  
- Resolving ambiguous relationships  
- Creating composite keys  
- Designing intuitive dashboards  
- Documenting analytics projects for portfolio use  

---

## Contact
**Svetlana — Data Analyst**  
🔗 LinkedIn: https://www.linkedin.com/in/svetlana-virsulo/  
🌐 Portfolio Website: https://svetlanavirs.github.io/Svetlana_portfolio/  
