# Glassdoor_review_data_analysis_project


# 📊 Glassdoor Job Reviews Analysis

## 📌 Overview
This project analyzes **Glassdoor job reviews** to uncover insights about **company ratings, employee sentiment, work-life balance, and job trends**. The dataset has been processed, stored in **MySQL**, and visualized using **Power BI** for better decision-making.

---

## 🚀 Project Workflow
1️⃣ **Data Collection**  
   - Extracted a large Glassdoor job reviews dataset (~3.8 GB, ~9.9M records).  
   - Uploaded the dataset to **GitHub** for open access.  

2️⃣ **Data Cleaning & Processing** (Python 🐍)  
   - Removed null & duplicate records.  
   - Standardized `job_title` (truncated long titles, cleaned special characters).  
   - Converted timestamps to MySQL-compatible `DATETIME` format.  
   - Transformed categorical data (e.g., `recommend`, `ceo_approval`) to Boolean values.

3️⃣ **Database Storage** (MySQL 🗄️)  
   - Designed an optimized schema for **efficient querying**.  
   - Uploaded clean data into **MySQL database**.  

4️⃣ **Data Analysis** (SQL & Python)  
   - Identified the **most reviewed companies & job titles**.  
   - Analyzed **employee sentiment on work-life balance, compensation, and senior management**.  
   - Evaluated **CEO approval ratings** and **job satisfaction trends**.

5️⃣ **Visualization & Insights** (Power BI 📊)  
   - Created **interactive dashboards** to visualize **trends, sentiment analysis, and job insights**.  
   - Used **DAX formulas** to process and present data in Power BI effectively.

---

## 🛠️ Technologies Used
- **Python** (for data cleaning & transformation)  
- **MySQL** (for structured data storage)  
- **SQL Queries** (for data analysis & aggregation)  
- **Power BI** (for interactive dashboards & reports)  
- **GitHub** (for version control & collaboration)  

---

## 📂 Folder Structure


---

## 🏛️ Database Schema (MySQL)
| Column Name | Data Type | Description |
|-------------|----------|-------------|
| `id` | INT (PK) | Auto-incremented ID |
| `review_date` | DATETIME | Date of review |
| `company` | VARCHAR(255) | Company name |
| `job_title` | VARCHAR(250) | Truncated & cleaned job title |
| `employment_status` | VARCHAR(50) | Current/former employee |
| `experience_years` | FLOAT | Years of experience |
| `overall_rating` | FLOAT | Employee rating (1-5) |
| `career_opportunities` | FLOAT | Career growth rating |
| `compensation_benefits` | FLOAT | Salary & benefits rating |
| `senior_management` | FLOAT | Leadership rating |
| `work_life_balance` | FLOAT | Work-life balance rating |
| `culture_values` | FLOAT | Culture & values rating |
| `diversity_inclusion` | FLOAT | Diversity rating |
| `recommend` | BOOLEAN | Would recommend to a friend (True/False) |
| `ceo_approval` | BOOLEAN | CEO approval rating (True/False) |
| `business_outlook` | BOOLEAN | Positive business outlook (True/False) |

---




